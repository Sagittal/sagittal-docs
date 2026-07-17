# MuseScore

[MuseScore](https://musescore.org) — the popular free, open-source score editor — has **first-class Spartan Sagittal accidentals**. They were coded by Jojo Schmitz (MuseScore PR #6182), prompted by Lajos Brons, which is why sagittals are available in MuseScore at all.

## Adding sagittals

The [Spartan](../concept-explanations/symbol-sets.md) sagittals are reachable through the **Master Palette → Symbols**, which exposes the Sagittal glyphs from the Bravura font. Apply them to notes as you would any accidental.

{% page-ref page="../tools/bravura-font.md" %}

## The one warning that matters

{% hint style="danger" %}
**MuseScore's sagittals carry 72-EDO (Trojan) cent values, not JI values.**

If you move from Sagittal's [JI notation](../notation-how-to-guides/just-intonation.md) pages to MuseScore, be aware that symbols like `/|)` and `(|\` will sound at their **12-relative / 72-EDO** cent values, not the JI cents you read about elsewhere. A symbol that is one thing in JI can be a slightly different number of cents in MuseScore.
{% endhint %}

This came about because MuseScore cannot handle JI as such. Flora Canou told the MuseScore developers that the accidentals "should be based on 72edo instead of ji, cuz musescore can't handle ji as of now," and opened the change (PR #21147). Dave and Douglas chose **not to contest it** — Dave preferring to trust that the author understood both Sagittal and MuseScore well enough to have improved on what was there. So the 72-EDO basis is the standing state of Sagittal in MuseScore.

{% hint style="info" %}
For the [12-Relative / Trojan notation](../notation-how-to-guides/12-relative-trojan.md), this is exactly what you want — the symbols already *mean* their 12-relative offsets. The mismatch only bites when you expected JI cent values.
{% endhint %}

## Rendering and export

MuseScore draws sagittals with Bravura and exports PNG images (handy for the forum or social media). It also has a plugin API — a stripped-down JavaScript with MuseScore-specific additions — so notation can be generated programmatically, though for small jobs manual entry is faster.
