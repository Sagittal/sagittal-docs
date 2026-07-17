# Prime Mapping & EDO Consistency

Here is a puzzle. The same three sagittals notate the first three steps of **72-EDO** *and* of **65-EDO** — even though 65's steps are a different size. Stranger still, one sagittal can notate a step of 17-EDO and a step of 31-EDO, which is nearly twice as big. How can one symbol serve steps of such different sizes?

The answer is that a sagittal's appropriateness has less to do with its **absolute size in cents** than with its **harmonic function** — the way the EDO in question maps the prime harmonics.

## An EDO distorts harmonic space

In JI you move by exact frequency ratios. In an EDO you cannot: you approximate each ratio by snapping it to the nearest step. Only factors of 2 stay exact (a factor of 2 is an octave, and an EDO divides the octave). Every other prime gets rounded to some whole number of steps — and that rounding **distorts harmonic space**.

We can capture an EDO's rounding in a compact **prime mapping**. For 72-EDO:

$$
\langle 72\ 114\ 167 ]
$$

This says: a factor of 2 maps to 72 steps, a factor of 3 to 114 steps, a factor of 5 to 167 steps. (The true values are more like 114.1 and 167.2 — the EDO snaps them to whole numbers.)

## Computing a symbol's step

Now take a sagittal and write its primary comma as a **prime exponent vector**. The 5-comma symbol `/|` has primary comma 80/81, which factors as:

$$
[\,4\ {-}4\ 1\,\rangle
$$

— four 2's, minus four 3's, one 5. To find how many steps of 72-EDO this comma spans, pair the vector against the mapping term by term:

$$
4(72) - 4(114) + 1(167) = 288 - 456 + 167 = -1
$$

One step *down* — which is exactly right: `/|` points down, so it notates the first (downward) step of 72-EDO. Run the same comma against **63-EDO**'s mapping `⟨63 100 146]` and you get −2 steps instead, because 63 distorts harmonic space differently. Same comma, different EDO, different step count. That is why one symbol can serve EDOs of very different sizes.

## Symbol swaps are revealing

Watch what happens in 63-EDO: its first two steps take the same two sagittals as 65-EDO, but **flipped** — the assignment of the 5-comma and 7-comma symbols is swapped, even though 63 and 65 have nearly identical step sizes. That is not a defect; it is *information*. The swap shows that 63-EDO distorts the primes 5 and 7 in a dramatically different way from 65 (or from undistorted JI). A notation that used one generic symbol per step would hide this; Sagittal's does not.

{% hint style="info" %}
This is the deep reason Sagittal's EDO notations are worth more than a bare step count: a symbol carries the *harmonic meaning* the EDO assigns to a step, not merely its size.
{% endhint %}

## Consistency

The property that lets this rounding cohere is **consistency** — that pairing-against-the-mapping always lands on the step you would expect.

{% hint style="info" %}
Consistency is older than regular temperament theory (RTT) — it traces to **Paul Hahn**, and it originally applied only to the simple maps of pure-octave EDOs, to a given odd limit. It is a property of an EDO's **naive round-to-nearest map**, not of a chosen temperament. If you are asking whether an EDO is "consistent," you are thinking with rounding-to-nearest brain, not RTT brain; for a rank-2-or-higher temperament the question does not even have a meaning, since with enough generators you can reach every pitch.
{% endhint %}

## The fringes of the table

This tidy prime-mapping story holds in the **middle** of the [Periodic Table](the-periodic-table-of-edos.md), where an EDO's primes all temper sensibly. On the **fringes** — the bad-fifth EDOs — it breaks down, and Sagittal switches strategy:

* **Limma-fraction notations** (the flat side, the "no-sharp" EDOs). The symbols no longer represent tempered primary commas; they are treated as their untempered JI values and chosen by how close they sit to fractions of the **limma** (the JI diatonic semitone). When basing a notation on the chromatic semitone fails, this is plan B: base it on the diatonic semitone instead.
* **Apotome-fraction notations** (the sharp side), the analogous fallback where the apotome is still positive.

The mechanical process — chain fifths, then fill gaps with sagittals — does not change on the fringes; only the *meaning* of the symbols does.

{% page-ref page="the-periodic-table-of-edos.md" %}
