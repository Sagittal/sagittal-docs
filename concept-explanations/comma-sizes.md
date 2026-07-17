# Comma Size Categories

The second half of a [comma name](comma-names.md) is its **size category** — a label like *kleisma* or *medium diesis* that tells you roughly how big the comma is. This page defines the categories and the precise boundaries between them. (For the general concept of a comma, see the Xenharmonic wiki's [Comma article](https://en.xen.wiki/w/Comma).)

{% hint style="info" %}
You do **not** need this page to use Sagittal notation. It is here for following Sagittal's JI discussions (how commas get assigned to symbols) and as a systematic comma-naming scheme that is useful even outside Sagittal.
{% endhint %}

## Size is the only criterion

There are **seven** core size categories. From smallest to largest:

| Category | Abbrev. | Meaning |
|---|---|---|
| schismina | n | the tiniest useful commas |
| schisma | s | |
| kleisma | k | |
| comma | C | the category right in the middle, three on either side |
| small diesis | S | |
| medium diesis | M | |
| large diesis | L | |

The only thing that determines a comma's category is its **size in cents** — not its prime content, not its complexity, nothing else. (Note the double duty of the word "comma": it is both the general term for any interval a Sagittal symbol represents, and the specific name of the middle category.)

## The boundaries: square roots of 3-limit commas

Each boundary between categories sits at the **square root of a meaningful 3-limit comma** — that is, halfway between two commas (in log-frequency / cents / monzo space) that share the same 2,3-free ratio. When you take the geometric mean of such a close pair, everything but the powers of 2 and 3 cancels, leaving the square root of a purely 3-limit interval. This is why the bounds look like monzos with half-integer entries (a monzo divided by 2).

Here are the seven categories with their upper bounds (each bound is **exclusive**):

| Category | Upper bound (¢) | Bound as monzo/2 |
|---|---|---|
| schismina | 1.808 | [-84 53⟩ / 2 |
| schisma | 4.500 | [317 -200⟩ / 2 |
| kleisma | 11.730 | [-19 12⟩ / 2 |
| comma | 33.382 | [27 -17⟩ / 2 |
| small diesis | 45.112 | [8 -5⟩ / 2 |
| medium diesis | 56.843 | [-11 7⟩ / 2 |
| large diesis | 68.573 | [-30 19⟩ / 2 |

So, for example, the category **comma** runs from 11.730¢ up to 33.382¢.

## Mirrored about the half-apotome

The categories don't stop at the large diesis. They continue upward, **mirrored about the half-apotome** (about 56.84¢), extending through the semitone categories all the way to the apotome:

| Category | Upper bound (¢) | Bound as monzo/2 |
|---|---|---|
| small semitone | 80.303 | [-49 31⟩ / 2 |
| medium semitone (limma) | 101.955 | [-3 2⟩ / 2 |
| large semitone | 111.877 | [62 -39⟩ / 2 |
| apotome | 115.493 | [-106 67⟩ / 2 |

The whole pattern can even be reflected again to reach the **double apotome**. The apotome itself is 113.685¢, and the half-apotome — the mirror axis — is exactly the boundary between the medium and large diesis regions.

{% hint style="info" %}
In output, "limma" and "apotome" are strongly Pythagorean-flavored words, so Sagittal prefers **medium semitone** and keeps "limma" as an input alias. Likewise the bare word "diesis" resolves to **medium diesis**.
{% endhint %}

## The unison

The very bottom of the scale is the **unison**, 1/1, written **1u**. Because all category boundaries are exclusive, nothing lands exactly on it — the unison is a single point, not really a size category at all.

## Complexity within a category

When two commas fall in the same category with the same 2,3-free ratio, they are told apart by **complexity prefixes** (complex, supercomplex, and so on). That is a matter of naming rather than size, so it is covered on the Comma Names page.

{% page-ref page="comma-names.md" %}

<!-- TODO: insert the "size category bounds mirrored about the half apotome" diagram (forum t=505) once available. -->
