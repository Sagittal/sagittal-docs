# The Periodic Table of EDOs

The **Periodic Table of EDOs** is the central artifact of Sagittal's EDO notations. It gives a recommended standard notation for every EDO from 5 up to 72, and it packs a remarkable amount of information into a small space. That density makes it look daunting at first — but it is completely decodable, and by the end of this page you should be reading it with no trouble.

![The Periodic Table of EDOs](../.gitbook/assets/periodic-table-of-edos.png)
<!-- TODO: confirm/insert the Periodic Table image asset -->

{% hint style="info" %}
This page teaches you to **read** the table. To see the table used to actually derive a notation step by step, see the worked examples in the EDO Notations guide.
{% endhint %}

{% page-ref page="../notation-how-to-guides/equal-divisions-of-the-octave.md" %}

## What's in a box

Each EDO from 5 to 72 appears once, in a box labeled with its number. The boxes are in reading order — left to right, top to bottom — except that lines **alternate** between odd-numbered and even-numbered EDOs.

Inside each box is a **minimal representation of the sagittals** you need to notate that EDO. Only the upward symbols are shown; each implies its downward mirror. For example, 72-EDO's box holds the Sagittal starter set — the same `/|` <img src="../.gitbook/assets/glyphs/accSagittal5CommaUp.svg" alt="/|" data-size="line">, `|)` <img src="../.gitbook/assets/glyphs/accSagittal7CommaUp.svg" alt="|)" data-size="line">, `/|\` <img src="../.gitbook/assets/glyphs/accSagittal11MediumDiesisUp.svg" alt="/|\" data-size="line"> you met in the introduction — because those notate its first three steps.

Some boxes are empty (like 12-EDO), meaning no sagittals are needed at all.

## The tornado: reading step counts

The striking tornado shape is not decoration. The two sets of crossed diagonal lines connect EDOs whose **semitones take the same number of steps**.

* The **blue lines** (running mostly top-left to bottom-right) connect EDOs with the same **chromatic** semitone count — the distance from C to C♯, written ♯. Along any blue line, the EDO numbers go **up by 7**. For instance, 17, 24, and 31 all sit on the blue line marked ♯ = 2: one step is a different size in cents in each, but it takes 2 steps to get from C to C♯ in all three.
* The **black lines** (running mostly top-right to bottom-left) connect EDOs with the same **diatonic** semitone count — the distance from E to F, written EF. Along any black line, the EDO numbers go **up by 5**. For instance, 12, 17, and 22 all sit on the black line marked EF = 1.

Once you know both semitone counts, you know the **whole tone** too, since it is their sum (C to C♯, then C♯ to D). And conveniently, each **horizontal row** groups EDOs whose whole tone has the same step count. For example, 17 and 19 are both in the CD = 3 row — they differ only in *which* semitone is the larger of the two.

From there, the fifth follows from the formula:

$$
\text{fifth} = \frac{\text{edo} + CD}{2}
$$

## Columns and color: fifth size

Where rows share a whole-tone *step count*, **vertical columns** share a fifth *size in cents*. Vertically aligned EDOs are multiples of one another, so their fifths are literally the same size. 12, 24, and 36 all have a 700¢ fifth (of 7, 14, and 21 steps respectively). EDOs with similarly sized fifths are grouped by giving their boxes the same **color**.

Color also carries a subtler meaning:

{% hint style="info" %}
**Notations of the same color use the same sagittal to represent the same fraction of a chromatic semitone (a sharp)** — or nearly so. The one exception is the **rose** notations, where the same sagittal instead represents the same fraction of a **diatonic semitone**, such as EF.
{% endhint %}

The **12n EDOs** — 12, 24, 36, 48, 60, 72 — are mutually consistent and form the **orange** band down the middle. The true center of the table is where the fifth is tuned perfectly just; those EDOs are left **grey** (uncolored) to indicate untempered, or nearly so.

## The fringes: bad-fifth EDOs

Toward the edges the fifth grows badly out of tune — more than about 10¢ from just — and conventional notation needs adjusting.

* The **gold** EDOs on the left tune the fifth extremely **wide** (sharp).
* The **rose** EDOs on the right tune it extremely **flat** (narrow).

No judgment is intended by "bad fifth" — the *fifth* may be bad if you frame the just fifth as good, but the EDO itself can be wonderful and strange. Conventional notation simply wasn't built for tunings out there, so Sagittal adapts:

* In the **5n** region (gold): the diatonic semitone is 0 steps, so F equals E and B equals C. These EDOs use only **five nominals**, and the table says **do not use F or B**. Further left, the diatonic semitone goes negative, and the EDO is better notated as a **subset** of a multiple of itself.
* In the **7n** region (rose): the chromatic semitone is 0 steps, so C♯ equals C, and **sharps and flats become worthless**. The table says **do not use ♯ or ♭**. Further right, the chromatic semitone goes negative — these are the **Mavila** EDOs (9, 16, 23), where the apotome itself is negative.

This all follows one rule:

> **Sagittal never uses a symbol to notate a tuning if that symbol's comma has a negative tempered size in that tuning.**

That is why the Mavila EDOs get no sharps or flats at all — they use limma-fraction sagittals instead — which keeps every Sagittal notation both melodically and harmonically consistent. (Every gold notation with the same ♯ count shares one notation; every rose notation with the same EF count shares one too.)

## Conventional-notation cardinalities

How many notes you can place before you need a sagittal depends on which vertical section you are in:

| Region | Notes before a sagittal |
|---|---|
| 5n EDOs | 5 |
| 7n EDOs | 7 |
| equal-tempered / Pythagorean / super-Pythagorean | 12 (D out to G♯) |
| meantone | 19 (D out to C♭) |
| sub-meantone (only 26, 52) | 26 (D out to G𝄪, using double sharps/flats) |

(45 and 64 only reach 19 before crossing, so they are not grouped with the sub-meantone band — these sections don't line up exactly with box colors.)

## Beyond 72

The table cuts off at 72 because it is such a powerful EDO for its size that cramming in anything larger has diminishing returns. But unlike the periodic table of the elements, the Periodic Table of EDOs goes on forever. Plenty of EDOs above 72 have agreed notations, and new ones are worked out regularly on the [Sagittal Forum](http://forum.sagittal.org).

## A note on the name

The table is a deliberate homage to Dmitri Mendeleev's Periodic Table of the Elements. It was first unveiled to the world in November 2019 — the International Year of the Periodic Table, marking the 150th anniversary of Mendeleev's — through a small prank in which "Dmitri Mendeleev himself" presented it on Facebook. In Dave Keenan's words, it "was the last thing that George and I did together," four months before George Secor's passing.

{% page-ref page="../history/sagittal-mythology-and-fun.md" %}
