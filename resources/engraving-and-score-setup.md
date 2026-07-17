# Engraving & Score Setup

This page collects the practical rules for putting Sagittal on the page: how the symbols are placed, how they combine, and how to set up a score so a reader knows exactly what your symbols mean.

## Placement: center the arrowhead

A sagittal is placed on the staff the same way a flat is:

{% hint style="info" %}
**Ignore the shaft; center the arrowhead on the staff position** — exactly as you ignore a flat's vertical stem and center its loop. The arrowhead is where the symbol's strokes are thick, and it marks the note being altered.
{% endhint %}

A secondary cue, like a natural: when a sagittal sits on a space, its shaft stops just short of the neighboring staff line. Good notation software gets this right by default — Dorico's placement, for instance, turned out to be correct as designed, so you shouldn't need to drag symbols around by hand.

## Accidentals replace, they don't stack

Sagittal accidentals **replace** one another rather than stacking up.

This is exactly what already happens with conventional accidentals when you move between a single and a double flat: to go back to a single flat you write a single flat, not a flat plus a natural. A flat alone is sufficient. Sagittals follow the same logic — a later accidental on the same note supersedes the earlier one.

## Diacritics attach only to sagittals or bare shafts

The small accent marks (diacritics) that add precision attach **only** to a sagittal or to a bare shaft — never on their own, and never on a conventional sharp or flat.

{% page-ref page="../concept-explanations/accents.md" %}

## Accidentals combine as a whole — and naturals stand alone

This is the single rule that governs cancelling and replacing Sagittal accidentals, and it extends the convention you already know from the conventional double flat:

{% hint style="info" %}
**Any combination of symbols against one note is treated as a single accidental.** It can only be cancelled or replaced *as a whole* — you never add or remove one part of it. A **natural cancels the lot**, and a new combination **replaces the lot**.
{% endhint %}

So a natural never needs to be combined with anything else — **naturals always stand alone**. And the rule reads the same in Evo and Revo: to walk a doubly-altered note back to a plain nominal you write a single natural, not a natural plus a leftover symbol.

## Sagittals in key signatures

Sagittals **may** be used in key signatures, and are treated exactly like conventional sharps and flats: they are **sticky** for the rest of the measure, and the whole-accidental-group rule above applies to them there too.

The guiding principle is that a key signature should establish a **7-note MOS** (a moment-of-symmetry scale), following the historical precedent of the Pythagorean\[7] and meantone\[7] key signatures — not a MODMOS. Deviations from that scale within the piece are written as accidentals on the notes. For any tuning richer than meantone this genuinely requires sagittals in the signature: a **Porcupine\[7]** key signature in 22-EDO, for instance, is a chain of "quills" that can only be spelled with comma accidentals.

Because one MOS can be spelled several enharmonically equivalent ways, state the MOS and the tuning in words at the top of the score — for example, *"Porcupine\[7] in 22-EDO"* — and prefer the key signature nearest the middle of the generator chain.

An example of how the whole-group rule plays out in a signature: if a comma-raised D sits in the key signature and you want a plain D, you write the plain D **in full**; conversely, since the raised D is now the default, you write nothing extra to get it.

## The score legend

Because a Sagittal symbol has flexible values, a score must tell the reader which tuning it is in and where its pitch reference lies. The standard place for this is a **legend** at the top of the score.

{% hint style="info" %}
Call it a **legend**, not a "key" — "key" is already overloaded in music (keyboard, key signature, key of C).
{% endhint %}

A legend typically states the sizes of the defining intervals, using a **D-to-F span** (D is the symmetry point of the chain F C G D A E B, and this span gives the apotome first, then the limma):

* the **fifth** (CG) — give both sizes if the notation uses a non-native fifth;
* the **apotome** (the chromatic semitone, C–C♯);
* the **limma** (EF — preferred over BC, since EF is visually distinct and avoids the German convention where B means our B♭);
* the **whole tone** (CD).

For an EDO, the legend also lists the **per-step accidentals**, exactly as on the Periodic Table — for example, in 72-EDO, `/|` = 1 step, `|)` = 2 steps, `/|\` = 3 steps. <!-- TODO: symbol images -->

Two typographic conventions:

* An **"="** sign in a legend is reserved for **redefinition** — for instance, a note that an accented symbol should be read as its plain form for this piece (dropping unneeded diacritics) effectively redefines that symbol's value for the work.
* A **tilde (~)** is reserved to mean **"tempered."** (In running text elsewhere, use "≈" for "approximately," so the tilde keeps its special meaning.)

## Standard staff layout for EDO examples

When presenting an EDO's notation as a reference (as on the Xenharmonic wiki), the agreed format uses two flavors, one above the other, so that vertically aligned notes are the same pitch:

* **Evo first** (single-shaft sagittals with conventional sharps and flats), because it is the educational stepping-stone to Revo;
* **Revo** below it (multi-shaft sagittals, no sharps or flats).

Each flavor shows an ascending chromatic scale from C to C using the **minimum** number of distinct symbols — using upward symbols on the lower nominal up to the halfway point, then downward symbols on the upper nominal, which minimizes naturals. Beneath that, all available symbols for the EDO from double-flat to double-sharp are applied to a single nominal — **F**, chosen because it shares the tonic C's "environment" (a whole tone up to the next nominal, a diatonic semitone down). Degree numbers 0 through *n* are included, above the staff.

{% page-ref page="../concept-explanations/evo-v.-revo.md" %}
