# Sagitype Key

_This page is generated from the Sagittal data set; corrections belong in the data, not here._

[Sagitype](../concept-explanations/sagitype.md) is the ASCII scheme for typing sagittals. **Long** Sagitype spells out every [symbol element](../concept-explanations/symbol-elements.md) as one character; **short** Sagitype gives the handful of most common symbols a single character. Both keys are below, from `sheet/05-ascii-key.csv`.

## Long Sagitype: one character per element

Each row is one keyboard character and the element it stands for. Several characters do double duty — the `(` and `)` keys spell both an **arc** and a **scroll**, and `~` spells a **boathook** — so the **side** (which flag is meant) is read from **context**: what sits to the character's left or right. A left flag has the shaft character (`|` or `!`) to its right; a right flag has it to the left.

| Left context | Char | Right context | Side | Element | Direction | Flag type | Also called |
|---|---|---|---|---|---|---|---|
|  | `|` |  | — | shaft | up | — | pipe, vertical bar |
|  | `!` |  | — | shaft | down | — | pipe, vertical bar |
|  | `X` |  | — | ex (four shafts) | up | — |  |
|  | `Y` |  | — | ex (four shafts) | down | — |  |
| `|` | `\` |  | right | barb | up | straight |  |
|  | `\` | `!` | left | barb | down | straight |  |
|  | `/` | `|` | left | barb | up | straight |  |
| `!` | `/` |  | right | barb | down | straight |  |
| `|` | `(` |  | right | scroll | up | concave |  |
|  | `)` | `!` | left | scroll | down | concave |  |
|  | `)` | `|` | left | scroll | up | concave |  |
| `!` | `(` |  | right | scroll | down | concave |  |
| `|` | `)` |  | right | arc | up | convex |  |
|  | `(` | `!` | left | arc | down | convex |  |
|  | `(` | `|` | left | arc | up | convex |  |
| `!` | `)` |  | right | arc | down | convex |  |
| `|` | `~` |  | right | boathook | up | concavoconvex | wavy flag |
|  | `~` | `!` | left | boathook | down | concavoconvex | wavy flag |
|  | `~` | `|` | left | boathook | up | concavoconvex | wavy flag |
| `!` | `~` |  | right | boathook | down | concavoconvex | wavy flag |
|  | `'` | _symbol_ | — | accent mark | acute | — |  |
|  | `.` | _symbol_ | — | accent mark | grave | — |  |
|  | `` ` `` | _symbol_ | — | slanted breve | acute | — |  |
|  | `,` | _symbol_ | — | slanted breve | grave | — |  |

For the multi-shaft [Revo](../concept-explanations/evo-v.-revo.md) symbols, repeat the shaft: `||`, `|||` (and `X` for four) going up; `!!`, `!!!` (and `Y`) going down.

## Short Sagitype

A single character for the six most common symbols — handy for quick chord and lattice sketches.

| Short | Long | [Sagispeak](sagispeak-key.md) |
|---|---|---|
| `/` | `/|` | pai |
| `\` | `\!` | pao |
| `f` | `|)` | tai |
| `t` | `!)` | tao |
| `u` | `|(` | nai |
| `n` | `!(` | nao |
