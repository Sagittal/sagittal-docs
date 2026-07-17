# StaffCode

[StaffCode](https://staffcode.org) renders **inline staff notation** — Sagittal or conventional — from a compact text code. Write something like `Ab\!` and StaffCode draws it on a little staff, using the [BravuraTextSC](bravura-font.md) font. Douglas built it.

## What it is for

StaffCode's niche is **transparent, copy-pasteable notation** in places that are otherwise text-only — the [Sagittal forum](http://forum.sagittal.org), this wiki, chat. Instead of generating an image and attaching it, you paste a short code that renders as notation *and* that anyone can peek inside to see exactly how it was written. That transparency is the whole point: it is a teaching and discussion aid.

{% hint style="warning" %}
StaffCode is **not** a replacement for notation software. In Douglas's and Dave's own words, it "does not have anywhere near the capabilities of music notation software like Dorico, Sibelius or Finale. It cannot do beams, ties or slurs that are not horizontal. It does not have aesthetic engraving rules. It cannot align parts." For a real score, reach for one of the [notation software](notation-software.md) options.
{% endhint %}

## Spacing

StaffCode measures space in **octals** — eighths of a staff space — and controls it with `sp` codes. The default is `sp2`; `sp0` joins symbols together, which is what you use when notes need to touch, as with a beamed group.

## Relationship to the font stack

StaffCode leans directly on the SMuFL font work: its glyphs come from BravuraTextSC, the small-caps variant of Bravura Text, so the same corrected Sagittal glyphs that appear everywhere else appear here.

{% page-ref page="bravura-font.md" %}
