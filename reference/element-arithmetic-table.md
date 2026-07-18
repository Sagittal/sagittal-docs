# Element Arithmetic Table

_This page is generated from the Sagittal data set; corrections belong in the data, not here._

[Element arithmetic](../concept-explanations/element-arithmetic.md) builds a compound symbol's comma by **adding the prime-exponent vectors** of its [elements](../concept-explanations/symbol-elements.md) — its flags (and accents). This page is the worked table from `sheet/04-element-arithmetic.csv`: the single-flag building blocks, and the sums that combine them.

Comma names are the [directed forms](../concept-explanations/comma-names.md) from `sheet/03`; cents are from the source. As the concept page warns, these sums are **exact for the simpler symbols and only approximate for the rest** — always within about 2¢. The table is for *understanding* symbols by splitting them, not for inventing new ones.

## The flag elements

The single-flag symbols that act as the "addends". Each is one flag on one shaft, with its primary comma.

| Flag | Primary comma | ¢ |
|---|---|---|
| `//|` | 1/25S | 43.013 |
| `)/|` | 19/5C | 24.884 |
| `~|` | 1/17k | 8.730 |
| `)|` | 19s | 3.378 |
| `(|` | 7/11C | 33.148 |
| `/|` | 1/5C | 21.506 |
| `|)` | 1/7C | 27.264 |
| `|(` | 5/7k | 5.758 |
| `|\` | 55C | 31.767 |
| `|~` | 23C | 16.544 |
| `|\\` | 19/11L | 63.790 |

## Sum identities

Each row adds a left element to a right element; the prime-exponent vectors sum to the compound symbol shown. The **Sum ¢** is what element arithmetic predicts — compare it to the result symbol's own size to see the small approximation.

| Left element | Right element | ≈ Symbol | Comma | Sum ¢ |
|---|---|---|---|---|
| `//|` (1/25S) | `)|` (19s) | `)//|` | 13/5M | 46.391 |
| `~|` (1/17k) | `~|` (1/17k) | `~~|` | 11/49C | 17.460 |
| `~|` (1/17k) | `)|` (19s) | `)~|` | 1/143C | 12.108 |
| `~|` (1/17k) | `|)` (1/7C) | `~|)` | 49S | 35.994 |
| `~|` (1/17k) | `|(` (5/7k) | `~|(` | 17C | 14.488 |
| `~|` (1/17k) | `|\` (55C) | `~|\` | 23S | 40.497 |
| `)|` (19s) | `|(` (5/7k) | `)|(` | 7/11k | 9.136 |
| `)|` (19s) | `|~` (23C) | `)|~` | 1/19C | 19.922 |
| `)|` (19s) | `|\\` (19/11L) | `)|\\` | 5/13L | 67.168 |
| `(|` (7/11C) | `/|` (1/5C) | `(/|` | 1/49M | 54.654 |
| `(|` (7/11C) | `|~` (23C) | `(|~` | 11/19M | 49.692 |
| `|)` (1/7C) | `|\` (55C) | `|\)` | 49L | 59.031 |

The full per-symbol comma values, directed names and Sagispeak live in the [Symbol Dictionary](symbol-dictionary.md).
