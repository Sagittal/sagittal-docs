# EDO Notations

This guide shows you how to notate any **equal division of the octave** in Sagittal. EDOs are, in a way, the easiest tunings to notate: an *n*-EDO has exactly *n* pitches per octave — no more, no less — so the job is always finite.

{% hint style="info" %}
**In a hurry for one specific EDO?** Many EDOs already have a full chromatic scale spelled out in Sagittal on the Xenharmonic wiki. Look up your EDO's own page there — for example [31edo](https://en.xen.wiki/w/31edo), whose **Notation** section gives its Sagittal spelling — and you can be off and running. (See also the wiki's general [EDO article](https://en.xen.wiki/w/EDO).) It is still worth understanding the process below, though — it shows how each notation fits the bigger picture. For most EDOs a single standard exists; for some you have two options, a native-fifth notation or a subset notation.
{% endhint %}

## The idea in one sentence

To notate an EDO, first lay down as much **conventional notation** as you can — the nominals plus sharps and flats — then fill the remaining gaps with **sagittals**.

We always want the notation to be as simple as possible, so we do as much as possible with conventional notation before reaching for a sagittal. Two pieces of information get us there:

1. **The minimal set of sagittals** for the EDO, read from its box on the Periodic Table of EDOs.
2. **The step counts** of the EDO's fifth (and/or its semitones and whole tone), also read from the table.

{% page-ref page="../concept-explanations/the-periodic-table-of-edos.md" %}

## Getting the step counts

The single most useful number is the **fifth**, measured in steps of the EDO. If you know the fifth's step count, you don't strictly need any other. You can read it off the Periodic Table, or compute it from the whole-tone count with this formula:

$$
\text{fifth} = \frac{\text{edo} + CD}{2}
$$

where *CD* is the whole-tone step count (the interval from C to D). For example, in 12-EDO the whole tone is 2 steps, so the fifth is (12 + 2) / 2 = **7 steps**.

You will also sometimes work from the two semitone counts directly:

* the **chromatic** semitone, C to C♯ (written ♯ = _n_), and
* the **diatonic** semitone, E to F (written EF = _n_).

Their sum is the whole tone.

## Worked example: 12-EDO

12-EDO is the warm-up. Its box on the Periodic Table is empty — its minimal representation of sagittals is *no sagittals* — which shouldn't surprise you, since you have been notating 12-EDO your whole life without them.

Its fifth is 7 steps. Start on the central note **D** and chain fifths in both directions:

* +1 fifth lands on step 7 (A); −1 fifth on step 5 (G).
* +2 fifths on step 2 (E); −2 on step 10 (C).
* Continue to B/F, then F♯/B♭, then C♯/E♭, then G♯/A♭…

…and at G♯/A♭ the nominals collide. As usual we prefer the sharp, keeping **G♯**. The collision happens exactly as we place the last of the 12 pitches, so we are done — and every pitch was notated with conventional symbols alone.

## Worked example: 31-EDO

31-EDO has at least one sagittal in its box, so it shows the full process.

First the fifth: 31 is in the whole-tone-5 row, so CD = 5, and the fifth is (31 + 5) / 2 = **18 steps**. Chain fifths from D:

You get all the way out to G♯ and A♭ **without** a nominal crossing, so you keep going — adding D♭/D♯, G♭/A♯, C♭… — until F♭ and B♯ finally create two simultaneous nominal crossings. Reject those two pitches. Conventional notation has taken you as far as it can: **19 of the 31 pitches** are placed, leaving 12 gaps.

Now fill the gaps with sagittals. Look at each gap and, if it borders a natural note, notate relative to that natural:

* Step 1 sits between D and D♯ — so notate it as **D plus one sagittal** (the EDO's first sagittal). You *could* write it as D♯ with a downward sagittal, but that's two symbols where one will do.
* Step 4 sits just below E — so notate it as **E with the first sagittal pointing down**. Remember, every sagittal has a mirrored pair for the opposite direction; the box only shows the upward versions to save space.

The rest of the gaps are the same kind of decision, and that gives you the standard Sagittal notation for 31-EDO.

## Worked example: 41-EDO (by semitones)

41-EDO has **two** sagittals in its box. This time, instead of chaining fifths, let's lay down conventional notation in pitch order using the **semitone** step counts — which works because we already know the shape of the scale a fifth-chain produces.

41 has a chromatic semitone of **4 steps** (♯ = 4) and a diatonic semitone of **3 steps** (EF = 3). Starting on D and stepping up:

| Note | From previous | Step |
|---|---|---|
| D | — | 0 |
| E♭ | diatonic (3) | 3 |
| E | chromatic (4) | 7 |
| F | diatonic (3) | 10 |
| F♯ | chromatic (4) | 14 |
| G | diatonic (3) | 17 |

Then fill the gaps between these with sagittals, always preferring the simpler (natural) side:

* Between D and E♭, work up from **D**: one step up uses the **first** sagittal, two steps up uses the **second**.
* Between E♭ and E, work down from **E**: the first sagittal, then the second — but you run out of sagittals before reaching all the way down, so the remaining step is notated relative to **E♭** instead, with the first sagittal opposing the flat.
* Between two naturals like E and F, just **split** the gap: the first sagittal up from E, and the first sagittal down from F.

The same handful of decisions, repeated, notates the whole EDO.

## Native-fifth vs. subset (non-native-fifth) notations

The examples above are all **native-fifth** notations: they use the fifth that is native to the EDO. This works well as long as the EDO's fifth is reasonably close to just.

For EDOs with a badly tuned fifth, conventional notation does such a poor job that Sagittal instead treats the tuning as a **subset** of a larger EDO and samples that EDO's notation. For instance, the table notates **8-EDO** as a subset of 24-EDO (take every 3rd step, since 24 ÷ 8 = 3), and **11-EDO** as a subset of 22-EDO (every other step). Because these notations borrow another EDO's fifth, they are also called **non-native-fifth** notations.

## The bad-fifth regions: 5n and 7n

Two special regions sit at the fringes of the Periodic Table, where the fifth is more than about 10¢ from just.

* **5n EDOs** (5, 10, 15, 20, 25, 30) have such a **wide** fifth that going down five of them lands you back where you started — the diatonic semitone is **0 steps**. That makes F the same pitch as E, and B the same as C. So these EDOs use only **five nominals**, and the table tells you **not to use F or B**. (The chain of fifths F C G D A means the worst that happens is one fifth, A to F, is spelled as a sixth — there is no Sagittal notation that spells a perfect fifth as a major third.)
* **7n EDOs** have such a **narrow** fifth that the chromatic semitone is **0 steps** — C♯ is the same pitch as C — so sharps and flats are worthless. The table tells you **not to use ♯ or ♭** here; these EDOs use limma-fraction sagittals instead.

This is a specific instance of a general Sagittal rule:

{% hint style="info" %}
**Sagittal never uses a symbol to notate a tuning if that symbol's comma has a *negative* tempered size in that tuning.** In the Mavila EDOs (9, 16, 23) at the far right of the table, the apotome itself is negative, so those EDOs get **no sharps or flats at all** — keeping every notation both melodically and harmonically consistent.
{% endhint %}

## Multiple valid spellings

The standard notations are a **community standard**, not a rulebook of right and wrong. Where a gap has a sharped or flatted note on both sides, prefer the spelling closer to D on the chain of fifths (E♭ is only −5 fifths from D, while D♯ is +7, so prefer E♭). And in an actual piece of music you may have good reason to prefer one spelling over another — for instance, if your scale only ever needs the first sagittal, you might avoid the second entirely. Feel free to do that. Standards gain their strength from being shared, so use them where you can; but if the people you are sharing with understand you, that is what matters.

## Beyond 72

The Periodic Table stops at 72 only because it is such a powerful EDO for its size that there are diminishing returns past it. But the principles go on forever, and many EDOs above 72 have agreed standard notations. New ones are discussed regularly on the [Sagittal Forum](http://forum.sagittal.org).

Next, learn to read the table itself:

{% page-ref page="../concept-explanations/the-periodic-table-of-edos.md" %}
