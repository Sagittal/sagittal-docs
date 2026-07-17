# Dorico

[Dorico](https://www.steinberg.net/dorico/) — Steinberg's professional score editor — has **native SMuFL** support, which makes it a strong home for Sagittal. Since Dorico ships with Bravura, the full Sagittal range is available, and Dave and George were consulted on the product before its release.

## Strengths

* **Large EDOs.** Dorico handles high-numbered EDOs comfortably, and because rank-2 temperaments and JI can be notated as **subsets of a large EDO**, it copes with those too.
* **Correct default placement.** Dorico's default positioning of sagittals turns out to be *correct as designed* — you should not need to drag symbols around to center them properly. (Early users who manually nudged every symbol were fixing a problem that was not there.)

{% page-ref page="../tools/bravura-font.md" %}

## Limits to know about

Dorico inherits some structural assumptions from conventional notation that constrain microtonal work:

* **Seven nominals per octave.** The staff is seven letter-names, and that cannot be extended.
* **Octaves cannot be retuned.**
* **Changing an accidental's size does not retune existing notes** already using it.
* **Accidental respelling is unreliable** away from 12-EDO.
* **No non-12 MIDI import.** A common workaround is to import MIDI into Finale, export MusicXML, and bring *that* into Dorico.

{% hint style="info" %}
These are limits of the software's model, not of Sagittal. The [engraving rules](../resources/engraving-and-score-setup.md) Sagittal asks for — centering the arrowhead, one accidental replacing rather than stacking — are ones Dorico's defaults already respect.
{% endhint %}

For the EDO-notation background these guides assume, see:

{% page-ref page="../notation-how-to-guides/equal-divisions-of-the-octave.md" %}
