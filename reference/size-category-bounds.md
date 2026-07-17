# Size-Category Bounds

_This page is generated from the Sagittal data set; corrections belong in the data, not here._

A comma [size category](../concept-explanations/comma-sizes.md) is decided by size alone. Each category runs from the previous boundary up to its own, and **every boundary is exclusive** — nothing lands exactly on a bound, or exactly on the unison. The boundaries are the square roots (the monzo halved, hence "monzo/2") of the 3-limit commas that sit near them, so the categories are mirrored about the half-apotome.

## The categories

Boundaries and their monzo/2 are from `sheet/15-pythagorean-commatic-intervals.csv`; default commas and the alternate names are from the t=484 comma-naming canon.

| Size category | Abbr. | Range (¢) | Upper bound (monzo/2) | Default comma | Other names |
|---|---|---|---|---|---|
| unison | u | 0 (exact point) | [0⟩ | 1/1 | "no move" |
| schismina | n | 0 – 1.808 | [-84 53⟩/2 | 4095:4096 | |
| schisma | s | 1.808 – 4.500 | [317 -200⟩/2 | 32768:32805 | |
| kleisma | k | 4.500 – 11.730 | [-19 12⟩/2 | 15552:15625 | |
| comma | C | 11.730 – 33.382 | [27 -17⟩/2 | 80:81 | |
| small diesis | S | 33.382 – 45.112 | [8 -5⟩/2 | 125:128 | fifth-tone |
| medium diesis | M | 45.112 – 56.843 | [-11 7⟩/2 | 32:33 | quarter-tone |
| large diesis | L | 56.843 – 68.573 | [-30 19⟩/2 | 625:648 | third-tone |
| small semitone | SS | 68.573 – 80.303 | [-49 31⟩/2 | 24:25 | |
| medium semitone | MS | 80.303 – 101.955 | [-3 2⟩/2 | 243:256 | limma |
| large semitone | LS | 101.955 – 111.877 | [62 -39⟩/2 | 15:16 | |
| apotome | A | 111.877 – 115.493 | [-106 67⟩/2 | 2048:2187 | |

The lower bound of each category is the upper bound of the one above it in the table; the schismina's lower bound is the unison itself.

## The unison

The ratio 1/1 is not really a comma — it is no move at all. Rather than force it into the schismina category, it gets its own name, **1u** (for unison), and stands alone as a single point. Because the boundaries are exclusive, `3u` — a bare move by a factor of 3 — is likewise a non-move notationally.

## Continuing past the apotome

The same categories repeat one apotome higher, written with a `+A` suffix — schisma-plus-apotome (`s+A`), and so on — running up to the **double apotome, `A+A` < 229.180¢** ([-128 81⟩/2). The category **limma+apotome** in this range may be called a **whole-tone**. Per-category continuation monzos are not enumerated in `sheet/15`; only the double-apotome bound above is given in the t=484 canon.

## Landmark 3-limit intervals

For reference, the actual Pythagorean intervals near these boundaries (also from `sheet/15`):

| Interval | Alternate name | Monzo | Ratio | ¢ |
|---|---|---|---|---|
| Pythagorean comma | ditonic comma | [-19 12⟩ | 531441:524288 | 23.460 |
| limma | Pythagorean semitone | [8 -5⟩ | 256:243 | 90.225 |
| apotome | chromatic semitone | [-11 7⟩ | 2187:2048 | 113.685 |
| whole tone | apotome + limma | [-3 2⟩ | 9:8 | 203.910 |
