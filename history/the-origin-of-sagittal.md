# The Origin of Sagittal

**George Secor** — a microtonal composer, theorist, and keyboard virtuoso — began developing Sagittal in **August 2001**, and in **January 2002** presented what he had built to the Yahoo tuning list in two messages he called **"Buried Treasure."** At that stage it could already notate the 17, 19, 22, 29, 31, 41, and 72 divisions of the octave. Those posts, still preserved on the [Sagittal Forum](http://forum.sagittal.org), are the founding documents of the system.

The name comes from the Latin *sagitta*, "arrow." George had come across the phrase "sagittarian notation" in a 1978 *Xenharmonikôn* comment by Ivor Darreg (describing a sharp with an arrow affixed) and decided that, once his own symbols had grown their arrowheads and shafts, "sagittal" fit them even better.

## The motive: simplicity

George's guiding conviction was that **the best notation is the simplest one**. He was dissatisfied with the existing notations for 72-EDO, which cluttered the staff by stacking arrows on top of sharps and flats. He wanted a **single symbol per note**.

That goal ran into an immediate problem. A single-symbol notation for 72-EDO, covering a whole tone of alteration up and down, would need 24 symbols. George halved that to 12 with one elegant requirement: **every symbol must invert to its own mirror**, giving an equal-but-opposite alteration for free. This requirement forced him to discard most conventional accidentals — the sharp looks the same upside down, the flat points the wrong way when inverted, and the fractional sharps and the double-sharp all failed the test. Only the natural survived. What remained had to be built fresh.

## Four ideas, integrated

The canonical *Xenharmonikôn* article calls this section "A Quadruple Feature": Sagittal's arrows combine **four** excellent features of earlier notations.

* **Arrows** pointing up or down — the most intuitive possible indicator of pitch direction (long used, most often for quartertones).
* **Multiple vertical strokes** to count multiples of a semisharp. These are frequently — and, the authors note, *mistakenly* — attributed to Giuseppe Tartini; they were in fact first used by **Richard Stein** (1909). Sagittal keeps the essential idea (strokes counting the alteration) while making it invertible, so it works for flats as well as sharps.
* **Bosanquet's slanted lines** — around 1875, Bosanquet used sloping marks for commatic alterations, the seed of Sagittal's **flags**, whose slant points toward the pitch alteration.
* **Mildred Couper's merging** — Couper merged two mirror-image stemmed symbols into a single symbol standing for their combined alteration. Sagittal adopts exactly this, up to a threshold (for Couper it fell between three and four quartertones; for Sagittal, between three and four twelfthtones).

The design evolved quickly. An August 2001 "expanded saggital" used arrows with multiple arrowheads; by December 2001 George had simplified to single arrowheads with one to three vertical strokes — the compact symbols recognizably ancestral to today's sagittals.

{% hint style="info" %}
One notation George pointedly did **not** draw on was Ezra Sims's 72-EDO notation. "Any similarity is purely coincidental," he wrote — he was "appalled" when he later saw it. Sagittal's resemblances to other systems come from shared principles, not borrowing.
{% endhint %}

## Symbols mean commas, not degrees

The deeper innovation is in what the symbols *mean*. Where other systems' symbols count degrees of an equal temperament or fractions of a sharp, **Sagittal's symbols represent alterations by approximations of certain superparticular ratios** — small, harmonically meaningful commas.

The two flags of the basic arrow each carry a comma:

* the **left flag** = the comma of Didymus (81:80, the syntonic comma, prime 5), and
* the **right flag** = the comma of Archytas (64:63, the septimal comma, prime 7).

Both flags together make the undecimal diesis, 33:32 (prime 11). And here is a lovely piece of arithmetic George noticed: 33/32 divided by (64/63 × 81/80) comes out to **385:384**, about 4.5¢ — a comma that vanishes in **Miracle temperament**. As he put it, it "would not be inappropriate to call this a Miracle notation." The degree-value of a symbol in any given EDO is simply the sum of its flags' comma-degrees in that EDO — the same alphabet, pronounced a little differently in each tuning.

George also argued that commas should honor their discoverers — **Didymus' comma** and **Archytas' comma** rather than the "syntonic" and "ditonic" labels that, in his words, "only a scholar could love."

## From the tuning list to Xenharmonikôn

The Yahoo tuning, tuning-math, and MakeMicroMusic groups were where Sagittal grew up. **Dave Keenan**, in Australia, was drawn in by the Buried Treasure posts and became George's collaborator; **Gene Ward Smith** contributed early as well. A February 2002 draft paper — "A Common Notation System for Extended Just Intonation and Equal Temperaments," by Gene Ward Smith, George Secor, and David C Keenan — already proposed the mature core: one comma symbol per prime, no comma fractions, primes through 19 sufficing for most equal temperaments "well into the hundreds," with the nominals arranged along a Pythagorean chain F C G D A E B centered on D.

Sagittal was formally introduced to the world in **2006**, in an article in Volume 18 of the historic alternative-tuning journal *Xenharmonikôn*. That article — *Sagittal: A Microtonal Notation System* — remains the canonical published reference, laying out and defending the design choices, the historical precedents and anti-inspirations, and the comparisons with other systems; it has been kept lightly updated ever since (most recently in 2025). Its closing vision is the one the whole system serves: a future in which every microtonal musician, "whatever their instrument or musical style, will share a single harmonically-based lingua franca of pitch."

## The people behind Sagittal

**George Secor** (1943–2020) was an American microtonal composer, theorist, and keyboard virtuoso — a player of both conventional and generalized microtonal keyboards, including the Motorola Generalized Keyboard Scalatron. He derived the generator of **Miracle temperament** in a 1975 *Xenharmonikôn* article (the interval was later named the **secor** in his honor), devised a 17-tone well temperament, and co-created Sagittal. His surname is pronounced **"SEE-kor."**

**Dave Keenan** is an Australian engineer and tuning theorist based in Brisbane, and the co-creator of Sagittal. In 2001 he and Paul Erlich derived Miracle temperament — the rediscovery that eventually drew George onto the tuning lists — and Dave went on to propose the name *secor* for its generator. Across an eighteen-year email collaboration with George he systematized the notation: refining the symbol sets, running the arithmetic, and building the comma-naming scheme that underlies Sagittal today. He remains the authority on the system's design rationale and history, and maintains [sagittal.org](https://sagittal.org) and the [Sagittal Forum](http://forum.sagittal.org).

**Douglas Blumeyer** has been a co-developer of Sagittal since 2020, when a self-described "full-blown obsession" with the system led him to write to Dave about building an online notation calculator; he became Dave's collaborator and the project's software and community lead. His Sagittal work includes the [Standard JI Notation Calculator](../tools/the-sagittal-calculator.md), [StaffCode](../tools/staffcode.md), the Sagittal-SMuFL character map, and the JavaScript codebase that generates Sagittal's data (`@sagittal/general` and `@sagittal/system`), along with much of the [Periodic Table of EDOs](../concept-explanations/the-periodic-table-of-edos.md) and EDO-notation work. With Dave he also co-authored a guide to regular temperament theory and a paper at MCM 2024, and he edits Sagittal's presence across the Xenharmonic wiki, this documentation site, and the tutorial video series, sometimes under the handle **cmloegcmluin**.
