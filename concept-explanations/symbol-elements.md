# Symbol Elements: Shafts, Flags & Accents

A sagittal is not an indivisible glyph. It is built from a small kit of **elements**, and once you can see the elements, the "over a hundred symbols" stop looking like a hundred things to memorize and start looking like a few shapes combined by simple rules.

## The shaft

Every sagittal has at least one **shaft** — the vertical line, like the shaft of an arrow. Shafts are all alike; what varies is how many there are. A single shaft is the ordinary case. Two, three, or four shafts appear in the [Revo flavor](evo-v.-revo.md), where extra shafts stand in for sharps and flats (four shafts are drawn as an "X," called an *ex-shaft*, for readability).

## The flags

The parts that hang off the sides of the shaft are **flags**. There are four flag shapes:

* **barb** — a straight flag. <!-- TODO: symbol image -->
* **arc** — a flag curved *outward*, away from the shaft (convex). <!-- TODO: symbol image -->
* **scroll** — a smaller flag curved *inward*, toward the shaft (concave). <!-- TODO: symbol image -->
* **boathook** — a flag that is concave *and* convex; it turns up in the later symbol sets. <!-- TODO: symbol image -->

## Left versus right

It matters which side of the shaft a flag sits on. **A left barb is not the same as a right barb** — they carry different commas, and (by the size-to-pitch-alteration proportionality that governs all sagittals) they are even drawn slightly different sizes. The left barb is the 5-comma; the right barb is the 55-comma.

There is a single-flag sagittal for every flag, on each of its two sides. So you can name any sagittal just by describing its flags: "left barb," "right arc," "left barb right arc," and so on. When the same flag appears on both sides, say "double" — the 11-comma symbol `/|\` is the "double barb." When two of the same flag stack on one side, say "double left barb."

{% hint style="info" %}
These flag descriptions are precise but a mouthful. There is a shorter way to name sagittals — one syllable each for the simplest ones — called [Sagispeak](sagispeak.md).
{% endhint %}

## The accents

Beyond shafts and flags, a sagittal may carry **accents** (also called diacritics) — small marks for alterations finer than about 2¢. Accents always represent smaller alterations than flags, so, by the **smallest-to-the-left** principle, they always sit to the *left* of the shafts-and-flags **core**, and they are drawn smaller. Unlike flags, accents may point in a different direction from the core and from each other.

{% page-ref page="accents.md" %}

## Flag arithmetic

Here is the payoff of seeing the elements. When you combine two single-flag sagittals into a two-flag one, you can often just **combine their primary commas** to get the new symbol's comma. This is **flag arithmetic**.

The cleanest example: the left barb `/|` <img src="../.gitbook/assets/glyphs/accSagittal5CommaUp.svg" alt="/|" data-size="line"> is the 5-comma (81/80) and the right arc `|)` <img src="../.gitbook/assets/glyphs/accSagittal7CommaUp.svg" alt="|)" data-size="line"> is the 7-comma (64/63). Put them together into the left-barb-right-arc `/|)` <img src="../.gitbook/assets/glyphs/accSagittal35MediumDiesisUp.svg" alt="/|)" data-size="line"> and you get the **35-comma** (36/35) — and sure enough, 5 × 7 = 35. The full ratios multiply out exactly: 81/80 × 64/63 = 36/35.

Work with the **2,3-free ratios** (the [comma-name](comma-names.md) numbers, "the ratios for humans") and the arithmetic is small enough to do in your head: left barb (5) times right arc (7) is 35.

### Barb cancellation

The most striking move is **cancellation**. Because every sagittal has a mirrored downward twin of equal and opposite value, a left barb up and a left barb down annihilate each other. So:

> The 5-comma symbol `\!` <img src="../.gitbook/assets/glyphs/accSagittal5CommaDown.svg" alt="\!" data-size="line"> (pao) plus the 11-diesis symbol `/|\` <img src="../.gitbook/assets/glyphs/accSagittal11MediumDiesisUp.svg" alt="/|\" data-size="line"> (pakai) equals the 55-comma symbol `|\` <img src="../.gitbook/assets/glyphs/accSagittal55CommaUp.svg" alt="|\" data-size="line"> (kai) — the downward and upward **left barbs cancel**, leaving the right barb. And indeed 5 × 11 = 55.

Once you notice the barbs canceling, you cannot un-see it. This is exactly why Sagittal's [comma names are directed](comma-names.md) (keeping the 1s, so `1/5C` + `55C` reads as `11M`): the arithmetic of the *ratios* is made to mirror the arithmetic of the *symbols*.

{% hint style="info" %}
For the Spartan set, flag arithmetic is **exact**. For more complex symbols it can come out slightly off — but always within about 2¢. So think of a multi-flag sagittal as *at least approximately* the sum of its flags, with a little life of its own: not "A"-"B" but "Ab."
{% endhint %}

## Don't invent symbols

Flag arithmetic is for *understanding* symbols, not for manufacturing them. All the valid sagittals already exist — the result of a carefully optimized network of commas — so do not go combining flags to mint new ones (combine a left barb and a right scroll for a "1/7-comma" and you will have drawn something that is simply not valid). The healthy habit is the reverse: **split** a multi-flag symbol you encounter, if splitting helps you see what it means.

The general form of this arithmetic, extended to accents and to tempered values, is:

{% page-ref page="element-arithmetic.md" %}
