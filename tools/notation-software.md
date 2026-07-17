# Notation Software

Sagittal support has landed, one way or another, in every major score editor. Most routes run through the SMuFL standard and the Bravura font, so that page is worth knowing whichever program you use.

{% page-ref page="bravura-font.md" %}

## MuseScore

[MuseScore](https://musescore.org) — the popular free, open-source score editor — has **first-class Spartan Sagittal accidentals**. They were coded by Jojo Schmitz (MuseScore PR #6182), prompted by Lajos Brons, which is why sagittals are available in MuseScore at all.

### Adding sagittals

The [Spartan](../concept-explanations/symbol-sets.md) sagittals are reachable through the **Master Palette → Symbols**, which exposes the Sagittal glyphs from the Bravura font. Apply them to notes as you would any accidental.

### The one warning that matters

{% hint style="danger" %}
**MuseScore's sagittals carry 72-EDO (Trojan) cent values, not JI values.**

If you move from Sagittal's [JI notation](../notation-how-to-guides/just-intonation.md) pages to MuseScore, be aware that symbols like `/|)` and `(|\` will sound at their **12-relative / 72-EDO** cent values, not the JI cents you read about elsewhere. A symbol that is one thing in JI can be a slightly different number of cents in MuseScore.
{% endhint %}

This came about because MuseScore cannot handle JI as such. Flora Canou told the MuseScore developers that the accidentals "should be based on 72edo instead of ji, cuz musescore can't handle ji as of now," and opened the change (PR #21147). Dave and Douglas chose **not to contest it** — Dave preferring to trust that the author understood both Sagittal and MuseScore well enough to have improved on what was there. So the 72-EDO basis is the standing state of Sagittal in MuseScore.

{% hint style="info" %}
For the [12-Relative / Trojan notation](../notation-how-to-guides/12-relative-trojan.md), this is exactly what you want — the symbols already *mean* their 12-relative offsets. The mismatch only bites when you expected JI cent values.
{% endhint %}

### Rendering and export

MuseScore draws sagittals with Bravura and exports PNG images (handy for the forum or social media). It also has a plugin API — a stripped-down JavaScript with MuseScore-specific additions — so notation can be generated programmatically, though for small jobs manual entry is faster.

## Dorico

[Dorico](https://www.steinberg.net/dorico/) — Steinberg's professional score editor — has **native SMuFL** support, which makes it a strong home for Sagittal. Since Dorico ships with Bravura, the full Sagittal range is available, and Dave and George were consulted on the product before its release.

### Strengths

* **Large EDOs.** Dorico handles high-numbered EDOs comfortably, and because rank-2 temperaments and JI can be notated as **subsets of a large EDO**, it copes with those too.
* **Correct default placement.** Dorico's default positioning of sagittals turns out to be *correct as designed* — you should not need to drag symbols around to center them properly. (Early users who manually nudged every symbol were fixing a problem that was not there.)

### Limits to know about

Dorico inherits some structural assumptions from conventional notation that constrain microtonal work:

* **Seven nominals per octave.** The staff is seven letter-names, and that cannot be extended.
* **Octaves cannot be retuned.**
* **Changing an accidental's size does not retune existing notes** already using it.
* **Accidental respelling is unreliable** away from 12-EDO.
* **No non-12 MIDI import.** A common workaround is to import MIDI into Finale, export MusicXML, and bring *that* into Dorico.

{% hint style="info" %}
These are limits of the software's model, not of Sagittal. The [engraving rules](../resources/engraving-and-score-setup.md) Sagittal asks for — centering the arrowhead, one accidental replacing rather than stacking — are ones Dorico's defaults already respect.
{% endhint %}

For the EDO-notation background this guide assumes, see:

{% page-ref page="../notation-how-to-guides/equal-divisions-of-the-octave.md" %}

## LilyPond

[LilyPond](https://lilypond.org) — the text-based, engraving-quality music typesetter — can produce Sagittal notation through **Graham Breed's Sagittal support**, hosted at [x31eq.com/lilypond](http://x31eq.com/lilypond/). Breed is one of the few people who has understood Sagittal deeply, which makes his implementation a trustworthy starting point.

### The font question

LilyPond's own music font is **Emmentaler**, not a SMuFL font, so bringing Sagittal to LilyPond runs into the same font-mapping issues every non-SMuFL toolchain faces. There has been an effort — led by Owen Lamb — to make a **SMuFL-compliant Emmentaler**, mapping its glyphs onto the standard layout so that Sagittal (and other SMuFL accidentals) drop in cleanly.

{% hint style="info" %}
SMuFL has no formal glyph-naming guide, so mapping a font's accidentals onto the standard is done by "discern[ing] patterns in the existing names and follow[ing] them." Dave is a go-to reviewer for getting microtonal accidental mappings right.
{% endhint %}

<!-- GAP: the specifics of Graham Breed's LilyPond syntax for entering sagittals were not ingested; see x31eq.com/lilypond for current usage. -->

## Sibelius

[Sibelius](https://www.avid.com/sibelius) gets Sagittal support through **Sagibelius**, a set of scripts (ManuScript plugins) by **Jacob Barton**, distributed as **donationware** together with a modified **Sagittal-2** font. The current release is Sagibelius 2.0, available from the Sagittal site as [`Sagibelius_2.0.zip`](https://sagittal.org/Sagibelius_2.0.zip).

Jacob Barton is a longtime member of the Sagittal community — he first taught Douglas the notation years ago — and also assembled the *Sagittal Songbook*, a collection of pieces demonstrating the notation in practice.

{% hint style="info" %}
Sagibelius predates Sibelius's broader SMuFL adoption, which is why it comes with its own font rather than relying on Bravura.
{% endhint %}

<!-- GAP: the Sagibelius workflow (which sagittals, how the plugins are invoked) was not ingested beyond the download and authorship; expand from the package's own documentation. -->

## Finale

Finale can notate Sagittal, but with a significant constraint for microtonal work: it is **capped by the 128-note MIDI ceiling**. Because Finale's pitch handling runs through standard MIDI, EDOs with many steps per octave quickly exhaust the available note numbers — where a SMuFL-native editor like [Dorico](#dorico) treats large EDOs (and JI, and rank-2 temperaments notated as large-EDO subsets) with far more headroom.

### Where Finale still fits

Finale's MIDI import is useful precisely *because* it exists in a chain with other tools. A common workflow for getting non-12 material into Dorico is to **import MIDI into Finale, export MusicXML, and open that in Dorico** — using Finale as a format bridge.

{% hint style="info" %}
The 128-note ceiling is a limit of MIDI-based pitch handling, not of Sagittal. For large EDOs and high-precision JI, a SMuFL-native editor will serve you better.
{% endhint %}

<!-- GAP: the specifics of entering sagittals in Finale (font setup, palettes) were not ingested; this page carries only the 128-note-MIDI limitation and the format-bridge workflow from the forum digest. -->
