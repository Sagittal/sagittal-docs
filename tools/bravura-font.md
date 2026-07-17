# Fonts: Bravura, Bravura Text & BravuraMSS

Sagittal symbols are part of **SMuFL** (the Standard Music Font Layout), so they ship inside the SMuFL reference fonts. That is what lets notation software and web pages render sagittals at all.

## Bravura and Bravura Text

**Bravura** is the reference SMuFL font, created by Daniel Spreadbury at Steinberg. Sagittal enjoys a long cooperation with Steinberg, and the full Sagittal range — including the [Olympian and Magrathean](../concept-explanations/symbol-sets.md) accent glyphs added in SMuFL 1.4 — lives in Bravura and its sibling **Bravura Text**.

The difference is what each is *for*:

* **Bravura** is the engraving font — the one music-notation applications draw scores with.
* **Bravura Text** is built to place SMuFL glyphs in ordinary runs of text, which makes it the right choice for spreadsheets, documents, and the web. The [JI Notation Calculator](the-sagittal-calculator.md) needs it to show real glyphs, so installing it is worth doing.

{% hint style="info" %}
Installation is the usual font install for your operating system; the Sagittal site hosts installers for the current Bravura.
{% endhint %}

## BravuraMSS

**BravuraMSS** — "Mixed Spartan Sagittal" — is a specialized derivative. It starts from Bravura and replaces the multi-shaft [Revo](../concept-explanations/evo-v.-revo.md) Spartans with the **Evo** compound accidentals, each mapped to a single alphabet character (with the natural at zero). It exists to make Evo notation easy to produce a symbol at a time where a full engraving workflow would be overkill.

A further relative, **BravuraTextSC** (a small-caps variant of Bravura Text), is the font behind [StaffCode](staffcode.md).

## Licensing

The Sagittal typeface itself is **free software** under the **GNU General Public License** (© 2003–2006 David C. Keenan & George D. Secor). Dave's guiding principle was "the free-er the better": commercial use and modification are welcome under share-alike, the one condition being that a modified result not be passed off as the originals'.

{% hint style="info" %}
Only the **large** form of the conventional double-sharp (SMuFL U+E47D) is visually compatible with Sagittal — a detail that matters when mixing the double-sharp into [Evo](../concept-explanations/evo-v.-revo.md) notation.
{% endhint %}

{% page-ref page="staffcode.md" %}
