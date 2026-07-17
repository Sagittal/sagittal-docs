# 12-Relative (Binary & Trinary) Notation

The [Trojan](12-relative-trojan.md) notation is the everyday 12-Relative notation, its capture zones sized for the pitches you actually meet. The **Binary** and **Trinary** notations are higher-resolution variants of the same idea: they subdivide the 12-EDO semitone systematically, so you can pin a pitch down as finely as you like relative to 12-EDO.

They share everything the Trojan notation established — the 700¢ fifth, the exactly-100¢ apotome, cent offsets read straight off the symbol. They differ only in *how* the semitone gets divided.

## Binary: repeated halving

The Binary notation divides the 12-EDO semitone by successive **halves**. Each symbol is worth exactly half the cent value of the one before, which lines it up with a power-of-two multiple of 12-EDO:

| Sagittal | Offset (¢) | EDO step of… |
|---|---|---|
| `/|\` | 50 | 24-EDO |
| `|~` | 25 | 48-EDO |
| `/|` | 12.5 | 96-EDO |
| `|(` | 6.25 | 192-EDO |
| `)|` | 3.125 | 384-EDO |

<!-- TODO: symbol images -->
<!-- above these in the ladder sit the whole and half semitone: /||\ = 100¢ (12-EDO) and /|\ = 50¢ -->


…and it keeps halving from there, down past a fortieth of a cent.

{% hint style="info" %}
Binary's defining virtue: **its components never point in opposite directions.** To reach a value you only ever *add* successive halvings, never add one and subtract another. That is a real advantage over a balanced-ternary ladder, where representing a value can force two components to oppose each other — the same kind of opposing-alteration clutter the [JI notation](just-intonation.md) was built to avoid.
{% endhint %}

## Trinary: dividing by threes

The Trinary notation instead subdivides by **thirds** — a balanced-ternary resolution ladder. It reaches some fine divisions more directly than repeated halving can, at the cost of the never-opposing guarantee that makes Binary so clean.

<!-- GAP: STV.08's Binary/Trinary slide is a stub, and no ingested source gives the full Trinary symbol table or its worked mechanics. The exact resolution ladders belong to the generated reference layer (sheet/11 and sheet/12); this page describes the concepts only. -->

## Which to reach for

For nearly all purposes the plain [Trojan](12-relative-trojan.md) notation is enough — you rarely need to resolve a 12-EDO-relative pitch more finely than its capture zones already allow. Reach for Binary when you want arbitrary precision with no opposing components, and for Trinary when a threefold division fits your pitches better than a twofold one.

{% page-ref page="12-relative-trojan.md" %}
