# Finale

Finale can notate Sagittal, but with a significant constraint for microtonal work: it is **capped by the 128-note MIDI ceiling**. Because Finale's pitch handling runs through standard MIDI, EDOs with many steps per octave quickly exhaust the available note numbers — where a SMuFL-native editor like [Dorico](dorico.md) treats large EDOs (and JI, and rank-2 temperaments notated as large-EDO subsets) with far more headroom.

## Where Finale still fits

Finale's MIDI import is useful precisely *because* it exists in a chain with other tools. A common workflow for getting non-12 material into Dorico is to **import MIDI into Finale, export MusicXML, and open that in Dorico** — using Finale as a format bridge.

{% hint style="info" %}
The 128-note ceiling is a limit of MIDI-based pitch handling, not of Sagittal. For large EDOs and high-precision JI, a SMuFL-native editor will serve you better.
{% endhint %}

{% page-ref page="dorico.md" %}

<!-- GAP: the specifics of entering sagittals in Finale (font setup, palettes) were not ingested; this page carries only the 128-note-MIDI limitation and the format-bridge workflow from the forum digest. -->
