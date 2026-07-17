# WinCompose

**WinCompose** is a free Windows utility that lets you enter Unicode characters with a *compose key*: press the compose key, type a short mnemonic sequence, and the character appears. It ships with hundreds of built-in sequences, and Sagittal supplies its own — so you can type real sagittal glyphs into almost any application, no notation software required.

## How it works

The Sagittal sequences mirror the [Sagitype](../concept-explanations/sagitype.md) spelling of each symbol. You press the compose key (typically twice), then type the symbol's element characters:

| Symbol | Sagispeak | Sequence (after the compose key) |
|---|---|---|
| `/|` | pai | `/` `|` |
| `\!` | pao | `\` `!` |
| `|)` | tai | `|` `)` |
| `/|\` | pakai | `/` `|` `\` |

<!-- TODO: symbol images -->

Because the sequence *is* the Sagitype, you do not have to memorize anything new — if you can type a symbol's ASCII, you can compose its glyph.

{% hint style="info" %}
For this to produce visible sagittals rather than empty boxes, install a font that carries them, such as Bravura Text.
{% endhint %}

{% page-ref page="bravura-font.md" %}

The complete list of WinCompose sequences — one per sagittal and accent — is part of the character data behind the generated symbol dictionary.

{% page-ref page="../reference/symbol-dictionary.md" %}
