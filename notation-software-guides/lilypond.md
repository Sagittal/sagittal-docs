# LilyPond

[LilyPond](https://lilypond.org) — the text-based, engraving-quality music typesetter — can produce Sagittal notation through **Graham Breed's Sagittal support**, hosted at [x31eq.com/lilypond](http://x31eq.com/lilypond/). Breed is one of the few people who has understood Sagittal deeply, which makes his implementation a trustworthy starting point.

## The font question

LilyPond's own music font is **Emmentaler**, not a SMuFL font, so bringing Sagittal to LilyPond runs into the same font-mapping issues every non-SMuFL toolchain faces. There has been an effort — led by Owen Lamb — to make a **SMuFL-compliant Emmentaler**, mapping its glyphs onto the standard layout so that Sagittal (and other SMuFL accidentals) drop in cleanly.

{% hint style="info" %}
SMuFL has no formal glyph-naming guide, so mapping a font's accidentals onto the standard is done by "discern[ing] patterns in the existing names and follow[ing] them." Dave is a go-to reviewer for getting microtonal accidental mappings right.
{% endhint %}

{% page-ref page="../tools/bravura-font.md" %}

<!-- GAP: the specifics of Graham Breed's LilyPond syntax for entering sagittals were not ingested; see x31eq.com/lilypond for current usage. -->
