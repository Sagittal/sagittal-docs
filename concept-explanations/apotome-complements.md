# Apotome Complements

Here is a fact that surprises people: **every 2,3-free ratio has two commas, not one.**

Take 11. There is a smaller comma for it — the 11 *medium diesis*, the double barb `/|\`, at 32:33 ≈ 53.3¢ — and a larger one — the 11 *large diesis*, the double arc `(|)`, at 704:729 ≈ 60.4¢. Both are legitimately "11 commas." So which is *the* 11 comma?

## They differ by an apotome

The two commas differ by exactly one **apotome** — a chromatic semitone, the interval of the sharp (2187/2048 ≈ 113.7¢). And the apotome is a **2,3-only** ratio: it is built entirely from 2's and 3's. Moving by it can never change a ratio's 2,3-free part. That is why both commas share the same 2,3-free content (11) while sitting an apotome apart in pitch.

Turn that around and you get the defining relationship:

> **A sagittal plus its apotome complement equals a sharp.** <!-- TODO: symbol images -->

The double barb (32:33) plus the double arc (704:729) comes out to exactly the apotome (2048:2187) — a sharp. So the double barb and the double arc are **apotome complements** of each other. Every sagittal has one.

Writing the sharp in sagitype as the double-shaft double-barb `/||\`, the article gives two worked complement pairs:

> `/|\` + `(|)` = `/||\`  (11M diesis + 11L diesis = apotome)
>
> `/|)` + `(|\` = `/||\`  (35M diesis + 35L diesis = apotome)

Both pairs sum to a sharp, so in each the two single-shaft symbols are apotome complements. <!-- TODO: symbol images -->

{% hint style="info" %}
This is the engine behind the [Evo and Revo flavors](evo-v.-revo.md). In Evo you might write a sharp and then a downward sagittal to walk back; in Revo you write that pitch's single apotome complement instead. Complements are what let one Revo symbol replace a sharp-plus-sagittal pair.
{% endhint %}

## The half-apotome mirror

Because a symbol and its complement sum to a full apotome, they sit **mirrored about the half-apotome** (about 56.8¢). A symbol a little below the half-apotome has its complement a little above, and vice versa. The [size categories](comma-sizes.md) are mirrored about the same axis for exactly this reason — which is why the smaller of our two 1/11 commas lands in the *medium diesis* category and the larger in the *large diesis*.

This mirror is also how [comma size categories](comma-sizes.md) resolve the "two commas per ratio" ambiguity: naming the size (medium diesis vs. large diesis) says *which* of the two you mean.

## Memorizing them in Revo

In [Evo](evo-v.-revo.md), you rarely think about complements — the sharp is right there on the page. In **Revo**, though, you need to know each symbol's complement cold, because there is **no simple rule** relating a symbol's flags to its complement's flags. A double left barb becomes a double scroll; a right arc stays a right arc; a left barb becomes a right barb — no pattern you can read off the shapes. Revo users simply memorize the equivalences (it *is* possible to explain precisely why each complement is what it is, but that waits for the advanced material). Every symbol's apotome complement across one apotome is tabulated in [Evo ↔ Revo Correspondence](../reference/evo-revo-correspondence.md).

<!-- TODO: symbol image — the article's complement charts (Fig 4 Spartan set, p.7; Fig 13 full 31-symbol set, p.24) render from the font during the glyph pass. The generated symbol dictionary already lists each symbol's complement from sheet/07. -->

{% page-ref page="../reference/symbol-dictionary.md" %}
