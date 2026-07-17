# Chord & Interval Names

Sagittal notates **pitches** on a staff. Naming **intervals** and **chords** in words — the way common practice says "minor third" or "dominant seventh" — is a related but separate problem, and it is **not officially part of the Sagittal standard**.

The nearest thing to a standard is a system worked out by **Cam Taylor** on the [Sagittal Forum](http://forum.sagittal.org). Dave Keenan has endorsed it as "the most Sagittal" of the options and adopted it when translating songbooks, so it is what this page describes.

{% hint style="info" %}
This is a community convention, not a locked specification. Expect some details (especially punctuation) to still be settling.
{% endhint %}

## Intervals: accidental + fifths-interval

Cam's system builds directly on Sagittal. An interval name has two parts:

> **[accidental][fifths-interval]**

The **fifths-interval** is a familiar abbreviation — d5, m2, m6, m3, m7, P4, P1, P5, M2, M6, M3, M7, A4 — chosen so that their upper notes form a **chain of notational fifths**, irrespective of tuning. Intervals reachable with only sharps and flats keep their **common-practice names in every tuning**: D–F is a minor third (m3) no matter what, and G–F♯ is a major seventh (M7).

When a sagittal is involved, its Sagispeak name prefixes the interval:

* D up to F, with the F lowered by `!)` (tao... the 7-comma down), is a **tao minor third**, abbreviated **tm3**.
* G up to F, with the F lowered by pao, is a **pao major seventh** (\M7) — the just 15:8.

A nice consequence: **every Sagittal interval is also a just interval.** The name tells you both the notational spelling and the exact ratio.

## Chords: name from the first third

To name a chord, you **name it from its first third**, and a perfect fifth is assumed. This has a striking result: purely Pythagorean chords get **plain** common-practice names, so a chord's quality word ("major," "minor") describes its *notation*, not necessarily its sound.

Because different just major thirds are notated differently, they get different prefixes:

| Chord | Name |
|---|---|
| 4:5:6 | pao major |
| 14:18:21 | tai major |
| 22:28:33 | ranai major |
| 10:13:15 | phai major |

None of these is "the" major triad unless its comma happens to vanish in the tuning at hand (pao major in meantone, tai major in archy, and so on). Short forms may drop "major"/"minor" when the comma points the obvious way: /m3 = 6:5, \M3 = 5:4.

For sevenths, **name the third, then the seventh**:

* "pao tao 7" = 4:5:6:7
* "tao vai 7" = 6:7:9:11

Altered fifths work as in a fake book: 5:6:7:9 = "pai7 nao-flat-5" (/7 ♭5). **Subharmonic** chords take an "s": C\s9.

## The root and the binding rule

A chord's root is written as a **letter name plus its accidentals**. This raises a subtlety: an accidental right after the root letter alters the **root** itself. To alter the **chord quality** instead, the accidental must be **set off** from the root.

Two conventions have been trialed for setting it off:

* **Parentheses**: `E(!)m7` — a tao-minor-7 built on a plain E.
* **A dot after the root, commas between** later accidentals: `E.tm7`, `Gt./m7`, `Bbt.f,/7`. The dot does the job the parentheses would, and reads a little cleaner.

This punctuation policy is still provisional, and may switch to parentheses if the dot-and-comma style doesn't catch on.

## Notational vs. acoustic

There is a genuine tension worth flagging. In a tempered tuning like 22-EDO, a "pao major" third *sounds like* an ordinary major third, while the "major" (Pythagorean) third sounds super-major. Dave raised this as an objection: don't the names mislead the ear?

Cam's resolution — which is the rule to remember — is that **the name always describes the notation, never the sound.** The notational major is always the plain name; the acoustic 4:5:6 is always "pao (major)." The names never lie about *notation*, and any sound-alikes are simply tuning-specific facts. As Dave came around to it: "It's growing on me. I think I'm just gonna get out of the way, and see where this goes."

## Caveats

* The system leans on the fifth (prime 3) being decently approximated. **Bad-fifth or non-3 tunings** need subset treatment or different naming — the same caveat as the Mavila EDO notations.
* Names get heavy when a chord uses two or more double-sided flags.

<!-- GAP: forum f=8 "Interval and Chord names" is only partly ingested (thread t=8, the load-bearing one, plus Dave's confirming emails). Threads t=164, t=7, t=83, t=85 remain to be folded in. -->

For how these accidentals sit on the staff (and when they do and don't belong in a key signature), see:

{% page-ref page="engraving-and-score-setup.md" %}
