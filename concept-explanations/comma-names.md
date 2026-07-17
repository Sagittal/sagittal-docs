# Comma Names

Every Sagittal symbol has a **primary comma** — the small just intonation interval it represents by default. Those commas need names, and Sagittal uses a systematic naming scheme developed by George Secor and Dave Keenan. This page explains how a comma name is built and how to read it.

A comma name has two parts:

> **name = a 2,3-free directed ratio + a size category**

For example, **5C** is the syntonic comma, a *comma* in size (the C) built on the prime *5*. Let's unpack both halves.

## Why we strip the 2's and 3's

Conventional notation already handles primes 2 and 3 completely. The octave (prime 2) is the staff repeating itself, and the chain of fifths (prime 3) gives you the nominals plus sharps and flats. So a Sagittal comma only ever needs to express what's *left over* — the primes 5 and up.

Accordingly, we describe a comma by its **2,3-free** ratio: the ratio with all factors of 2 and 3 removed. The syntonic comma 80:81 reduces to just **5** (its only surviving prime), so it is a "5-something." The septimal comma 63:64 reduces to **7**. This is why a comma name leads with a small number: it is telling you the harmonic content that conventional notation *couldn't* already express.

{% hint style="info" %}
This is also why commas with many factors of 3 are still perfectly usable — they just sit farther along the chain of fifths. Stripping the 3's doesn't lose information; it relocates it to the part of the notation (the nominals and sharps) that was built to carry it.
{% endhint %}

## Directed names and the harmonic series

The ratio in a comma name is **directed** — it keeps its numerator and denominator oriented a particular way, which encodes *how the symbol is used*.

The cleanest way to learn this is straight from the **harmonic series**, with no mention of commas at all. Harmonics are real and otonal chords are common, while subharmonics are rare, so you learn a **symbol direction for each prime harmonic**:

* C to E, with the E altered by `\!` (pao, a *downward* symbol), gives the just major third **4:5**. <!-- TODO: symbol image -->
* C to B, with the B altered downward, gives **4:7**.
* C to F, with the F altered by `/|\` (pakai, an *upward* symbol), gives **8:11**. <!-- TODO: symbol image -->

So you simply learn that **primes 5 and 7 use a downward symbol, while prime 11 uses an upward symbol** — because the 5th and 7th harmonics sit *below* their nearest Pythagorean note, and the 11th sits *above*. No commas required.

Once you know that, the naming falls out:

> **The _n_-comma is the comma that notates harmonic _n_.** So the 5-comma (`5C`) is the downward comma that lowers a Pythagorean major third to 5/4, and the **1/5-comma** (`1/5C`) is its upward mirror that notates the subharmonic.

Written as ratios oriented for a chord whose root is the lowest and Pythagorean, the 5-comma is 80:81 (downward) and the 1/5-comma is 81:80 (upward).

## Why keep the "1"? Flag arithmetic

Keeping the "1" in `1/5C` — rather than dropping it to write "5C" for the upward comma — may look fussy, but it makes **flag arithmetic** read naturally right in the names. When you combine symbols, their left and right flags add or cancel, and the directed names track it:

> The 5-comma symbol `\!` (pao) plus the 11-diesis symbol `/|\` (pakai) equals the 55-comma symbol `|\` (kai) — because the downward and upward **left barbs cancel**, leaving the right barb — and indeed 5 × 11 = 55. <!-- TODO: symbol images -->

You "can't unsee the canceling of the barbs" once you notice it. Directed names are what let the arithmetic of the *ratios* mirror the arithmetic of the *symbols*.

{% page-ref page="flag-arithmetic.md" %}

## The unison: 1u

What about the ratio 1/1? It is not really a comma at all — it is **no move**. Rather than shoehorn it into the smallest size category, Sagittal gives it its own name: **1u**, for **unison**.

(The choice of "u" is a small visual joke: it's an upside-down "n," so it fits nicely underneath all the comma names that end in "n." And "3u" quietly underlines that moving by a factor of 3 is, notationally, also a non-move.) All comma **size-category boundaries are exclusive**, so nothing lands exactly on the unison; 1u stands alone.

## Factorization thresholds

For a comma whose 2,3-free number is composite, the name either uses that number directly or factorizes it. The rule, settled for Sagittal's SMuFL submission, is:

> **Factorize when the number has more than two prime factors (counting repeats), _except_ 125; or when it has any prime factor above 11, _except_ 65 and 143.**

In practice:

* **91** = 7·13 and **169** = 13² **are** factorized (they have a prime factor above 11).
* **121**, **125**, **143**, and **65** are **not** factorized (they're the listed exceptions).

Factorized denominators with more than one distinct prime get parentheses — 7/(5·37) — while a single-prime denominator does not: 1/13²C. Multiplication uses the dot operator (⋅), and repeated primes become powers (7⁴/25n, not 7·7·7·7).

## Complexity prefixes

Sometimes two different commas share the same 2,3-free ratio *and* the same size category. They are distinguished by **complexity prefixes** — **complex**, **supercomplex**, **hypercomplex**, **ultracomplex**, then **5-complex**, **6-complex**, and so on. What the prefixes rank is essentially **product complexity** (how big the powers of 2 and 3 are), and a negative power of 3 counts as slightly more complex than the equal positive one.

For example, the syntonic comma is simply `5C`; a much more complex comma with the same 5-and-comma profile becomes `c5C` (the complex-5-comma). Because the size categories are narrow, ordinary notation never actually needs the complex-named commas — they only come up when you're cataloguing commas systematically.

## 3-limit commas: the e-form

Commas made only of 2's and 3's (like the Pythagorean comma) are never directed. Instead they're named by the **EDO** that tempers them out, since a 3-limit comma's number of 3's *is* that EDO. This is the **e-form** (e for EDO): the Pythagorean comma is `3C` (output form), its more complex sibling is `41e3C`, the Pythagorean schisma is `3s` = `53e3s`, and so on. The e-part is dropped for the simplest comma in each category.

## Default comma per size category

If you name only a size category with no ratio, it resolves to a conventional default (from historical usage):

| Category | Default comma |
|---|---|
| schismina (n) | 4095:4096 |
| schisma (s) | 32768:32805 |
| kleisma (k) | 15552:15625 |
| comma (C) | 80:81 |
| small diesis (S) | 125:128 |
| medium diesis (M) | 32:33 |
| large diesis (L) | 625:648 |
| medium semitone / limma (MS) | 243:256 |
| apotome (A) | 2048:2187 |

## Directed vs. undirected (and why SMuFL differs)

Sagittal's own materials use **directed** names everywhere. The **SMuFL** font standard, by contrast, uses **undirected** names (dropping the 1s) to match the older conventions it inherited — and, crucially, **SMuFL identifiers are frozen**: renaming them would break downstream software like MuseScore. So the identifier `accSagittal143CommaUp` keeps its undirected form permanently, even though Sagittal prose calls that comma something directed. A symbol dictionary therefore shows both.

This is not a contradiction to fix — it's a boundary to respect. Directed names live in Sagittal's explanatory materials; undirected, frozen names live in the font standard.

For the size half of a comma name, continue to:

{% page-ref page="comma-sizes.md" %}
