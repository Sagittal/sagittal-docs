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

## Never put sagittals in a key signature

Key signatures never contain sagittals.

The reason is structural: a key signature should only ever create a **7-note MOS** scale — in the case of just intonation, a chain of just fifths. Sagittals alter individual notes by commas, which would break that requirement. So if a piece needs a sagittal, it goes on the note, not in the key signature. (A piece whose key signature would otherwise carry an unused sharp is simply given a blank key signature instead.)

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
