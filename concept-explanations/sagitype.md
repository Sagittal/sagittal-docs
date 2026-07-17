# Sagitype

Sagittal symbols live in the standard music font layout (SMuFL), so most notation software can render them. But sometimes you need to write a sagittal where that font is not available — in an email, a forum post, a code comment. It is the same problem you face writing "G sharp" in plain text: you either spell it out (`s-h-a-r-p`) or reach for a close pictorial stand-in (`#`).

Sagittal gives you both options. Spell it out with [Sagispeak](sagispeak.md), or type a pictorial approximation — and that pictorial ASCII form is what we call **Sagitype**.

{% hint style="warning" %}
Sagitype is for **typing** sagittals. Do not confuse it with [Sagiscript](sagiscript.md), which is for **handwriting** them. (The tutorial video that introduces Sagitype slips and calls it "Sagiscript" in its opening line — that is a misspeak; this is Sagitype.)
{% endhint %}

## One character per element

There are far too many sagittals, and far too few keyboard keys, to give each symbol its own character — and few sagittals look enough like any single key to make that work anyway. So Sagitype maps each **[symbol element](symbol-elements.md)** to a character instead. Each sagittal therefore takes **at least two characters** to type: a shaft, plus its flags.

| Element | Character | Notes |
|---|---|---|
| shaft (up) | `|` | the "pipe"; a vertical line |
| shaft (down) | `!` | the dot sits at the bottom — pointing down |
| barb | `/` `\` | straight flags |
| arc | `(` `)` | curved outward (convex) |
| scroll | `(` `)` | curved inward (concave) |
| boathook | `~` | the wavy flag |
| accents | `'` `.` `` ` `` `,` | acute, grave, and the slanted breves |

You read a flag's side from where it sits relative to the shaft: `/|` is a *left* barb (the `/` precedes the pipe), while `|\` is a *right* barb. The same key does duty for arc and scroll because context — which side, which direction — disambiguates.

## The shaft carries the direction

Notice there are two shaft characters, `|` (up) and `!` (down). Using the shaft to encode direction is a small stroke of cleverness: `/|` is pai (up) and `\!` is pao (down). You *could* get away with a pipe in the down case sometimes, but in many symbols that would leave the direction ambiguous, so Sagitype always uses `!` for down. The exclamation point is still basically a vertical line — a fine stand-in for a shaft — with its dot conveniently at the bottom.

For the multi-shaft [Revo](evo-v.-revo.md) symbols, just repeat the shaft: `||`, `|||`, and `X` for the ex-shaft going up; `!!`, `!!!`, and `Y` going down.

## Long versus short Sagitype

What we have described is **long** Sagitype — every element spelled out, so `\!` is pao and `|)` is tai. There is also a **short** Sagitype for the handful of most common symbols, giving each a single character:

| Short | Long | Sagispeak |
|---|---|---|
| `/` | `/|` | pai |
| `\` | `\!` | pao |
| `f` | `|)` | tai |
| `t` | `!)` | tao |
| `u` | `|(` | nai |
| `n` | `!(` | nao |

Short Sagitype is handy for quick chord and lattice sketches; long Sagitype is unambiguous for everything.

## Typing them directly

On a system with the font installed, you do not have to settle for an approximation — you can type the real glyph. **WinCompose** turns a Sagitype-like sequence into the actual Sagittal character: the compose key, then the element characters.

{% page-ref page="../tools/wincompose.md" %}
