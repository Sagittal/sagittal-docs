# Element Arithmetic

[Flag arithmetic](symbol-elements.md) combines the primary commas of a sagittal's *flags*. **Element arithmetic** is the same idea taken to its full generality: it combines the primary commas of **all** of a symbol's [elements](symbol-elements.md) — flags *and* accents — to give the value of the whole symbol.

So flag arithmetic is really just element arithmetic restricted to symbols with no accents. Once a symbol carries an [accent](accents.md), you need the general form.

## Summing the elements

Every element — each flag, each accent — has a primary comma, and every comma is a small interval you can write as a **prime exponent vector**. To combine elements you simply **add their vectors** (equivalently, multiply their ratios). Add the vectors of all of a symbol's elements and you get the comma of the whole symbol.

Because the vectors add, the arithmetic reads naturally in the [directed comma names](comma-names.md): the whole symbol's name falls out of its parts, opposite flags cancel, and a left-side element plus a right-side element land on their product.

{% hint style="info" %}
Worked in the abstract: give the boathook `~|` its primary comma (the 17-kleisma) and combine it with another element's comma by adding the two prime exponent vectors; the sum is the compound symbol's comma. The full grid of these sums lives in the "Element Arithmetic" data of the reference layer.
{% endhint %}

## Tempered values

There is one wrinkle the flag-arithmetic examples could ignore. When a symbol is being used in a **tempered** context — a step of some EDO, say — its elements should be combined in their **tempered** forms, not their pure JI values. Prime mapping distorts each element's comma, so the sum has to be taken after that distortion, in the tuning at hand.

{% page-ref page="prime-mapping-and-edo-consistency.md" %}

## When it is not exact

As with flag arithmetic, element arithmetic is **exact for the simpler symbols** and only *approximately* right for more complex ones — but the approximation is always close, within about 2¢. In the middle zone near the half-apotome, a simpler symbol can *override* the value a strict element sum would predict, which is exactly why a multi-element symbol is more than the bare sum of its parts.

And the same caution applies: this arithmetic is for **understanding** symbols by splitting them, not for inventing new ones by adding elements together. Every valid Sagittal symbol already exists.

{% page-ref page="symbol-elements.md" %}
