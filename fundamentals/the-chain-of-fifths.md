# The Chain of Fifths

Before we get to the Sagittal notations for various tunings, we need to review one fundamental aspect of pitch notation: the **chain of fifths**. Sagittal builds directly on this foundation, so it pays to be comfortable with it. This may involve peeling away a few assumptions about conventional notation.

## Conventional notation was not designed for conventional tuning

If you have only ever read notation for conventional tuning — that is, **12-EDO**, twelve equal divisions of the octave — you may never have needed to understand what conventional notation is really based on.

Here is the key point: conventional tuning has only been around for about a hundred years, but conventional notation has been around for many centuries. (Those dates are extremely rough, and notation didn't arrive all at once — the five-line staff is more recent than the seven letters — but the *order* is what matters.) So **12-EDO is a layer of interpretation we apply on top of our notation**, not the thing the notation was built to express.

What conventional notation directly maps is an underlying just intonation landscape, carved out by the two simplest and most important harmonic intervals:

* the **octave**, ratio 1:2, and
* the **fifth**, ratio 2:3.

Pitches built only from pure octaves and fifths are called **Pythagorean**, or equivalently **3-limit JI**. These intervals have been known since at least the time of Pythagoras.

## Why the same notes look different in JI and 12-EDO

Consider the 21 pitches you get from the seven nominals A B C D E F G, each also with a sharp and with a flat.

If you interpret those as **12-EDO**, many of them are redundant — D♯ and E♭ are the same pitch, E♯ and F are the same pitch. We call such pairs **enharmonic**.

But in **JI** (Pythagorean tuning), every one of them is distinct. Some stay close — D♯ sits at about 114¢ while E♭ sits at about 90¢, a gap of roughly 24¢, or one **Pythagorean comma**. To explain this distribution of pitches, we build them up with a chain of Pythagorean fifths.

## Starting from D

We start the chain with a single pitch: **D**.

Why D, instead of A, the first letter of the alphabet? Because D is the middle letter of the seven — A B C **D** E F G — with three letters on either side. Starting there makes the chain **symmetrical**, which will matter shortly.

{% hint style="info" %}
D is what we call the **central note**, not the "tonic". The tonic depends on the key — the tonic of C major is C, and of A minor is A — but Sagittal's chain of fifths is centered on D in every case, purely for its symmetry. We describe the position of every other pitch relative to D.
{% endhint %}

We assign D the position 0¢ (equivalently 1200¢, an octave up), and then spiral outward by fifths in **both directions**.

<!-- TODO: chain-of-fifths diagram (double spiral centered on D) -->

* One fifth up lands on **A**, at about 702¢ — a pure fifth, just 2¢ from the 700¢ of 12-EDO.
* One fifth down lands on **G**, at about 498¢ (that's 1200 − 702), just 2¢ below 500.
* Chain once more each way to reach **E** (204¢) and **C** (996¢). Now we have a **pentatonic** scale.

Notice that this five-note scale has exactly **two step sizes** — two large steps and three small ones. Whenever chaining an interval yields exactly two step sizes, you have reached a natural stopping point, because such scales tend to sound good. But let's keep going.

## The diatonic scale and the nominals

Chain one more fifth in each direction and you reach a **diatonic** (seven-note) scale — the Pythagorean diatonic scale. Again it has just two step sizes: five large and two small.

This scale is central to the musical tradition that conventional notation grew up to serve. So it is exactly here that the founding notaters decided these seven pitches were important enough to get their own letters — their own **nominals**. All further pitches are treated as variations on these seven, marked with accidentals.

This seven-position basis is also why, when we talk about scales and chords, we speak of the second, third, fourth, fifth, and so on — and why the octave is called the octave (the eighth). The fifth is literally the fifth step.

## Sharps, flats, and nominal crossing

With only seven nominals, chaining further means recycling letters and distinguishing them with a **sharp** or **flat**:

* Continue the chain and the first accidentals appear: **F♯** (at +4 fifths) and **B♭** (at −4 fifths). Note that F is at −3 fifths and F♯ is at +4 — a difference of **7 fifths**. That octave-reduced chain of 7 fifths is the sharp's interval, the **chromatic semitone** (about 114¢).
* Chain again for **C♯** and **E♭** (±5 fifths).
* Chain again for **G♯** and **A♭** (±6 fifths). And here something goes wrong: we now have an A♭ sitting *between* two G's and a G♯ sitting *between* two A's. The letters have crossed into each other's territory.

We call this a **nominal crossing**, and it is a problem. A good notation lets the pitch letter always take precedence over the accidental, so that reading up the staff always means moving up in pitch. A nominal crossing breaks that — a **melodic violation** — and if we kept chaining until every sharped and flatted nominal existed, *every* close pair would be a crossing.

So we stop, and back up by the minimum amount to avoid crossing at all. We only need to keep *one* of G♯ or A♭. By a common design preference — favor the positive over the negative — we keep the upward one, **G♯**, the pitch we laid down first, and discard A♭.

## The Pythagorean chromatic scale

Now we have **12 pitches** with, once again, exactly two step sizes — five large and seven small:

* The **chromatic semitone** (large step here, e.g. G to G♯): about 114¢, equal to +7 fifths.
* The **diatonic semitone** (small step, e.g. G♯ to A, or E to F): about 90¢, equal to −5 fifths. It is called *diatonic* because it is the small step already present in the diatonic scale.

Their sum is the **whole tone** (e.g. D to E): about 204¢, equal to +2 fifths. So a whole tone is one diatonic semitone plus one chromatic semitone — neither kind of semitone is exactly half a whole tone; each is only approximately half.

This 12-note scale is the **Pythagorean chromatic scale**. Its chain runs from E♭ at −5 fifths to G♯ at +6 fifths. Unlike the diatonic scale it can't be notated symmetrically (seven nominals, twelve notes), but it is the largest chain-of-pure-fifths scale that can be notated without any nominal crossing — and it keeps the desirable two-step-sizes property.

## Why this matters for Sagittal

We now have everything we need for the moment: the seven nominals, the sharp and flat, the diatonic and chromatic semitones, and the whole tone — all derived from a chain of pure fifths, exactly as conventional notation was originally designed to model Pythagorean pitches.

This Pythagorean chain of fifths is one of the design choices that lets Sagittal adapt so easily between tunings — from JI, to EDOs, and anything in between or beyond. In the notation guides you will chain fifths the same way, then fill the remaining gaps with sagittals.

{% page-ref page="../notation-how-to-guides/choosing-a-notation.md" %}
