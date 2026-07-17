# What the Symbols Really Represent

This page is for anyone implementing software that has to *play* Sagittal — a sequencer, a playback engine, a converter. If you only want to read and write the notation, you can skip it; nothing here changes how the symbols look on the page. But if your program has to turn a nominal-plus-sagittal into an actual frequency, this is the model you need.

## A system, not a notation

Sagittal is not one notation; it is a system that generates a notation for each tuning, arranged so those notations stay **harmonically consistent with one another** (and as melodically consistent as that allows). Concretely: a 4:5:6 major triad on C — or the best approximation your tuning offers — is always written C:E`\!`:G, in every tuning, *unless* the tuning tempers out the syntonic comma, in which case it simplifies to C:E:G.

## What defines one notation

A single notation within the system is fixed by a handful of things:

* a **notational octave size** and a **notational fifth size** — these fix what the seven nominals mean;
* a limited **set of accidental symbols**; and
* two lookup tables that make the conversion unambiguous in both directions.

**Pitch → symbol** needs a **capture zone** for each symbol: a range of pitch alterations it is responsible for, with no gaps and no overlaps. It is enough to list the symbols in pitch order and give each one's lower bound in cents.

**Symbol → pitch** needs a single **default** alteration for each symbol, lying inside that symbol's capture zone.

You can see exactly this data in Scala's `SAxxx.PAR` files. For an equal-division notation it is abbreviated — the defaults are simply successive degrees of the EDO and the zone boundaries fall halfway between them. For the 12-EDO-relative [Trojan](../notation-how-to-guides/12-relative-trojan.md) notation, bounds are in cents and defaults are fractions of a 12-EDO semitone. For a [just intonation](../notation-how-to-guides/just-intonation.md) notation, bounds are in cents and defaults are exact ratios.

## Primary commas: the glue

Those default JI ratios are what hold the whole system together. In the absence of any other information, they are what a symbol "really represents" — we call each one the symbol's **primary comma**.

The primary commas were chosen by **popularity**: which commas are most often needed to notate the most popular ratios, where popularity was measured by how often ratios occur in the Scala scale archive. In most cases the choice is not close — one candidate notates ratios that occur many times more often, and it usually agrees with intuition from consonance, ratio complexity, and prime limit.

Context narrows the default further. If you know an EDO is in force, the default is the EDO degree closest to the tempered primary comma (with rare exceptions that fall back to a secondary comma). And even within JI, the nominal itself is information:

## Smart defaults

A symbol can be made to represent slightly different commas depending on the nominal (and sharps or flats) it sits on. Re-mining the Scala archive for the most popular ratio behind each *nominal + sagittal* combination yields **smart defaults**: the symbol now returns the ratio you actually wanted maybe 99% of the time — more precision, with no extra symbols. The index into that table is the note's distance in fifths from the (possibly local) 1/1; a chord's root can serve as a local 1/1. Absent any key information, defaulting 1/1 to C still beats using the bare primary comma unless the key is far from C on the chain of fifths. All of this is typically a fine adjustment of **less than 2 cents**.

Where even smart defaults are not enough, higher-resolution JI notations add [accent marks](../concept-explanations/accents.md) — "like the semantic radicals of Chinese text" — to pin down which comma is intended, at the cost of a steeper learning curve. A good implementation can also simply show the user the pitch it inferred (as a ratio, cents, or EDO degree) and let them override it explicitly.

{% page-ref page="../concept-explanations/comma-names.md" %}
