# Symbol Dictionary

_This page is generated from the Sagittal data set; corrections belong in the data, not here._

One row per glyph in the **Sagittal-2 character map** (`sheet/01-characters.csv`, 219 accidental symbols + 8 diacritics). This is the dictionary **v1**: it covers every distinct character in the font. The exhaustive enumeration of *valid symbol combinations* lives in `sheet/02-symbols-valid.csv` (981 rows), of which only ~404 were captured — those additional pure/mixed combinations beyond the character map are **deferred** to a later pass.

Columns: the glyph image (to be added), long (pure) and short sagitypes, [Sagispeak](../concept-explanations/sagispeak.md), [primary comma](primary-commas-table.md) as a directed name (single-shaft only), cents, the frozen [SMuFL](../concept-explanations/comma-names.md) codepoint and class name, and the [apotome complement](../concept-explanations/apotome-complements.md) (the symbol that completes an apotome with this one). Primary-comma names come from `sheet/03`; apotome complements are the symbol at `apotome − cents`. Blank cells mean the datum does not apply (e.g. multi-shaft symbols have no single primary comma).

## Single-shaft symbols

The core comma symbols, each with a primary comma. Sorted by size; negative cents are the downward twins.

| Glyph | Long | Short | Sagispeak | Primary comma | ¢ | SMuFL | Apotome complement |
|---|---|---|---|---|---|---|---|
| <!-- TODO: symbol image --> | `)!//` |  | rachao | 13/5L | -67.291 | U+E3AD<br>accSagittal5v13LargeDiesisDown |  |
| <!-- TODO: symbol image --> | `(!/` | `d` | dao | 1/35L | -64.915 | U+E30F<br>accSagittal35LargeDiesisDown |  |
| <!-- TODO: symbol image --> | `!//` |  | chao | 11/19L | -63.790 | U+E3AB<br>accSagittal11v19LargeDiesisDown |  |
| <!-- TODO: symbol image --> | `(!)` | `w` | wao | 11L | -60.412 | U+E30D<br>accSagittal11LargeDiesisDown |  |
| <!-- TODO: symbol image --> | `!/)` |  | ktao | 1/49L | -59.157 | U+E3A9<br>accSagittal49LargeDiesisDown |  |
| <!-- TODO: symbol image --> | `)\!/` |  | vrao | 49/5M | -56.482 | U+E3A7<br>accSagittal5v49MediumDiesisDown |  |
| <!-- TODO: symbol image --> | `(\!` |  | jpao | 49M | -54.528 | U+E3A5<br>accSagittal49MediumDiesisDown |  |
| <!-- TODO: symbol image --> | `\!/` | `v` | vao | 1/11M | -53.273 | U+E30B<br>accSagittal11MediumDiesisDown |  |
| <!-- TODO: symbol image --> | `(!~` |  | jazao | 19/11M | -49.895 | U+E3A3<br>accSagittal11v19MediumDiesisDown |  |
| <!-- TODO: symbol image --> | `\!)` | `&` | gao | 35M | -48.770 | U+E309<br>accSagittal35MediumDiesisDown |  |
| <!-- TODO: symbol image --> | `)\\!` |  | frao | 5/13M | -46.394 | U+E3A1<br>accSagittal5v13MediumDiesisDown |  |
| <!-- TODO: symbol image --> | `\\!` | `_` | fao | 25S | -43.013 | U+E307<br>accSagittal25SmallDiesisDown |  |
| <!-- TODO: symbol image --> | `~!/` |  | sakao | 1/23S | -40.004 | U+E39F<br>accSagittal23SmallDiesisDown |  |
| <!-- TODO: symbol image --> | `(!(` | `a` | janao | 11/5S | -38.906 | U+E349<br>accSagittal5v11SmallDiesisDown |  |
| <!-- TODO: symbol image --> | `\!~` |  | pazao | 5/23S | -38.051 | U+E375<br>accSagittal5v23SmallDiesisDown |  |
| <!-- TODO: symbol image --> | `~!)` |  | satao | 1/49S | -35.697 | U+E39D<br>accSagittal49SmallDiesisDown |  |
| <!-- TODO: symbol image --> | `(!` | `j` | jao | 11/7C | -33.148 | U+E347<br>accSagittal7v11CommaDown |  |
| <!-- TODO: symbol image --> | `!/` | `k` | kao | 1/55C | -31.767 | U+E345<br>accSagittal55CommaDown |  |
| <!-- TODO: symbol image --> | `)!)` |  | ratao | 7/19C | -30.642 | U+E39B<br>accSagittal7v19CommaDown |  |
| <!-- TODO: symbol image --> | `!)` | `t` | tao | 7C | -27.264 | U+E305<br>accSagittal7CommaDown |  |
| <!-- TODO: symbol image --> | `)\!` |  | prao | 5/19C | -24.884 | U+E373<br>accSagittal5v19CommaDown |  |
| <!-- TODO: symbol image --> | `\!` | `\` | pao | 5C | -21.506 | U+E303<br>accSagittal5CommaDown |  |
| <!-- TODO: symbol image --> | `)!~` |  | razao | 19C | -20.082 | U+E399<br>accSagittal19CommaDown |  |
| <!-- TODO: symbol image --> | `~~!` |  | shao | 49/11C | -17.576 | U+E397<br>accSagittal11v49CommaDown |  |
| <!-- TODO: symbol image --> | `!~` | `z` | zao | 1/23C | -16.544 | U+E371<br>accSagittal23CommaDown |  |
| <!-- TODO: symbol image --> | `~!(` | `o` | sanao | 1/17C | -14.730 | U+E343<br>accSagittal17CommaDown |  |
| <!-- TODO: symbol image --> | `)~!` |  | slao | 143C | -12.064 | U+E395<br>accSagittal143CommaDown |  |
| <!-- TODO: symbol image --> | `)!(` | `i` | ranao | 11/7k | -9.688 | U+E341<br>accSagittal7v11KleismaDown |  |
| <!-- TODO: symbol image --> | `~!` | `s` | sao | 17k | -8.730 | U+E393<br>accSagittal17KleismaDown |  |
| <!-- TODO: symbol image --> | `!(` | `n` | nao | 7/5k | -5.758 | U+E301<br>accSagittal5v7KleismaDown |  |
| <!-- TODO: symbol image --> | `)!` | `;` | rao | 1/19s | -3.378 | U+E391<br>accSagittal19SchismaDown |  |
| <!-- TODO: symbol image --> | `)|` | `r` | rai | 19s | 3.378 | U+E390<br>accSagittal19SchismaUp | `(||~` |
| <!-- TODO: symbol image --> | `|(` | `u` | nai | 5/7k | 5.758 | U+E300<br>accSagittal5v7KleismaUp | `/||)` |
| <!-- TODO: symbol image --> | `~|` | `$` | sai | 1/17k | 8.730 | U+E392<br>accSagittal17KleismaUp | `)//||` |
| <!-- TODO: symbol image --> | `)|(` | `*` | ranai | 7/11k | 9.688 | U+E340<br>accSagittal7v11KleismaUp | `//||` |
| <!-- TODO: symbol image --> | `)~|` |  | slai | 1/143C | 12.064 | U+E394<br>accSagittal143CommaUp | `~||\` |
| <!-- TODO: symbol image --> | `~|(` | `e` | sanai | 17C | 14.730 | U+E342<br>accSagittal17CommaUp | `(||(` |
| <!-- TODO: symbol image --> | `|~` | `~` | zai | 23C | 16.544 | U+E370<br>accSagittal23CommaUp | `/||~` |
| <!-- TODO: symbol image --> | `~~|` |  | shai | 11/49C | 17.576 | U+E396<br>accSagittal11v49CommaUp | `~||)` |
| <!-- TODO: symbol image --> | `)|~` |  | razai | 1/19C | 20.082 | U+E398<br>accSagittal19CommaUp | `(||` |
| <!-- TODO: symbol image --> | `/|` | `/` | pai | 1/5C | 21.506 | U+E302<br>accSagittal5CommaUp | `||\` |
| <!-- TODO: symbol image --> | `)/|` |  | prai | 19/5C | 24.884 | U+E372<br>accSagittal5v19CommaUp | `)||)` |
| <!-- TODO: symbol image --> | `|)` | `f` | tai | 1/7C | 27.264 | U+E304<br>accSagittal7CommaUp | `||)` |
| <!-- TODO: symbol image --> | `)|)` |  | ratai | 19/7C | 30.642 | U+E39A<br>accSagittal7v19CommaUp | `)/||` |
| <!-- TODO: symbol image --> | `|\` | `y` | kai | 55C | 31.767 | U+E344<br>accSagittal55CommaUp | `/||` |
| <!-- TODO: symbol image --> | `(|` | `?` | jai | 7/11C | 33.148 | U+E346<br>accSagittal7v11CommaUp | `)||~` |
| <!-- TODO: symbol image --> | `~|)` |  | satai | 49S | 35.697 | U+E39C<br>accSagittal49SmallDiesisUp | `~~||` |
| <!-- TODO: symbol image --> | `/|~` |  | pazai | 23/5S | 38.051 | U+E374<br>accSagittal5v23SmallDiesisUp | `||~` |
| <!-- TODO: symbol image --> | `(|(` | `g` | janai | 5/11S | 38.906 | U+E348<br>accSagittal5v11SmallDiesisUp | `~||(` |
| <!-- TODO: symbol image --> | `~|\` |  | sakai | 23S | 40.004 | U+E39E<br>accSagittal23SmallDiesisUp | `)~||` |
| <!-- TODO: symbol image --> | `//|` | `=` | fai | 1/25S | 43.013 | U+E306<br>accSagittal25SmallDiesisUp | `)||(` |
| <!-- TODO: symbol image --> | `)//|` |  | frai | 13/5M | 46.394 | U+E3A0<br>accSagittal5v13MediumDiesisUp | `)|\\` |
| <!-- TODO: symbol image --> | `/|)` | `%` | gai | 1/35M | 48.770 | U+E308<br>accSagittal35MediumDiesisUp | `(|\` |
| <!-- TODO: symbol image --> | `(|~` |  | jazai | 11/19M | 49.895 | U+E3A2<br>accSagittal11v19MediumDiesisUp | `|\\` |
| <!-- TODO: symbol image --> | `/|\` | `^` | vai | 11M | 53.273 | U+E30A<br>accSagittal11MediumDiesisUp | `(|)` |
| <!-- TODO: symbol image --> | `(/|` |  | jpai | 1/49M | 54.528 | U+E3A4<br>accSagittal49MediumDiesisUp | `|\)` |
| <!-- TODO: symbol image --> | `)/|\` |  | vrai | 5/49M | 56.482 | U+E3A6<br>accSagittal5v49MediumDiesisUp |  |
| <!-- TODO: symbol image --> | `|\)` |  | ktai | 49L | 59.157 | U+E3A8<br>accSagittal49LargeDiesisUp | `(/|` |
| <!-- TODO: symbol image --> | `(|)` | `m` | wai | 1/11L | 60.412 | U+E30C<br>accSagittal11LargeDiesisUp | `/|\` |
| <!-- TODO: symbol image --> | `|\\` |  | chai | 19/11L | 63.790 | U+E3AA<br>accSagittal11v19LargeDiesisUp | `(|~` |
| <!-- TODO: symbol image --> | `(|\` | `q` | dai | 35L | 64.915 | U+E30E<br>accSagittal35LargeDiesisUp | `/|)` |
| <!-- TODO: symbol image --> | `)|\\` |  | rachai | 5/13L | 67.291 | U+E3AC<br>accSagittal5v13LargeDiesisUp | `)//|` |

## Multi-shaft symbols

Two-, three- and four-shaft symbols (Revo) and the Evo compounds, Spartan and Athenian sets first. These carry a sharp/flat’s worth of apotomes plus a comma, so they have no single primary comma; Sagispeak is the composed form (e.g. `kaisharp`).

| Glyph | Long | Short | Sagispeak | Primary comma | ¢ | SMuFL | Apotome complement |
|---|---|---|---|---|---|---|---|
| <!-- TODO: symbol image --> | `\!!/` | `b` | flat |  | -113.685 | U+E319<br>accSagittalFlat |  |
| <!-- TODO: symbol image --> | `\!!)` | `ub` | naiflat |  | -107.927 | U+E317<br>accSagittalFlat5v7kUp |  |
| <!-- TODO: symbol image --> | `!!/` | `/b` | paiflat |  | -92.179 | U+E315<br>accSagittalFlat5CUp |  |
| <!-- TODO: symbol image --> | `!!)` | `fb` | taiflat |  | -86.421 | U+E313<br>accSagittalFlat7CUp |  |
| <!-- TODO: symbol image --> | `)!!(` | `=b` | faiflat |  | -70.672 | U+E311<br>accSagittalFlat25SUp |  |
| <!-- TODO: symbol image --> | `)||(` | `_#` | faosharp |  | 70.672 | U+E310<br>accSagittalSharp25SDown | `//|` |
| <!-- TODO: symbol image --> | `||)` | `t#` | taosharp |  | 86.421 | U+E312<br>accSagittalSharp7CDown | `|)` |
| <!-- TODO: symbol image --> | `||\` | `\#` | paosharp |  | 92.179 | U+E314<br>accSagittalSharp5CDown | `/|` |
| <!-- TODO: symbol image --> | `/||)` | `n#` | naosharp |  | 107.927 | U+E316<br>accSagittalSharp5v7kDown | `|(` |
| <!-- TODO: symbol image --> | `/||\` | `#` | sharp |  | 113.685 | U+E318<br>accSagittalSharp | `|//|` |
| <!-- TODO: symbol image --> | `(!!!/` | `db` | daoflat |  | -178.600 | U+E32B<br>accSagittalFlat35LDown |  |
| <!-- TODO: symbol image --> | `(!!!)` | `wb` | waoflat |  | -174.097 | U+E329<br>accSagittalFlat11LDown |  |
| <!-- TODO: symbol image --> | `\!!!/` | `vb` | vaoflat |  | -166.958 | U+E327<br>accSagittalFlat11MDown |  |
| <!-- TODO: symbol image --> | `\!!!)` | `&b` | gaoflat |  | -162.455 | U+E325<br>accSagittalFlat35MDown |  |
| <!-- TODO: symbol image --> | `\\!!!` | `_b` | faoflat |  | -156.698 | U+E323<br>accSagittalFlat25SDown |  |
| <!-- TODO: symbol image --> | `!!!)` | `tb` | taoflat |  | -140.949 | U+E321<br>accSagittalFlat7CDown |  |
| <!-- TODO: symbol image --> | `\!!!` | `\b` | paoflat |  | -135.191 | U+E31F<br>accSagittalFlat5CDown |  |
| <!-- TODO: symbol image --> | `!!!(` | `nb` | naoflat |  | -119.443 | U+E31D<br>accSagittalFlat5v7kDown |  |
| <!-- TODO: symbol image --> | `|||(` | `u#` | naisharp |  | 119.443 | U+E31C<br>accSagittalSharp5v7kUp |  |
| <!-- TODO: symbol image --> | `/|||` | `/#` | paisharp |  | 135.191 | U+E31E<br>accSagittalSharp5CUp |  |
| <!-- TODO: symbol image --> | `|||)` | `f#` | taisharp |  | 140.949 | U+E320<br>accSagittalSharp7CUp |  |
| <!-- TODO: symbol image --> | `//|||` | `=#` | faisharp |  | 156.698 | U+E322<br>accSagittalSharp25SUp |  |
| <!-- TODO: symbol image --> | `/|||)` | `%#` | gaisharp |  | 162.455 | U+E324<br>accSagittalSharp35MUp |  |
| <!-- TODO: symbol image --> | `/|||\` | `^#` | vaisharp |  | 166.958 | U+E326<br>accSagittalSharp11MUp |  |
| <!-- TODO: symbol image --> | `(|||)` | `m#` | waisharp |  | 174.097 | U+E328<br>accSagittalSharp11LUp |  |
| <!-- TODO: symbol image --> | `(|||\` | `q#` | daisharp |  | 178.600 | U+E32A<br>accSagittalSharp35LUp |  |
| <!-- TODO: symbol image --> | `\Y/` | `bb` | doubleflat |  | -227.370 | U+E335<br>accSagittalDoubleFlat |  |
| <!-- TODO: symbol image --> | `\Y)` | `ubb` | naidoubleflat |  | -221.612 | U+E333<br>accSagittalDoubleFlat5v7kUp |  |
| <!-- TODO: symbol image --> | `Y/` | `/bb` | paidoubleflat |  | -205.864 | U+E331<br>accSagittalDoubleFlat5CUp |  |
| <!-- TODO: symbol image --> | `Y)` | `fbb` | taidoubleflat |  | -200.106 | U+E32F<br>accSagittalDoubleFlat7CUp |  |
| <!-- TODO: symbol image --> | `)Y(` | `=bb` | faidoubleflat |  | -184.357 | U+E32D<br>accSagittalDoubleFlat25SUp |  |
| <!-- TODO: symbol image --> | `)X(` | `_x` | faodoublesharp |  | 184.357 | U+E32C<br>accSagittalDoubleSharp25SDown |  |
| <!-- TODO: symbol image --> | `X)` | `tx` | taodoublesharp |  | 200.106 | U+E32E<br>accSagittalDoubleSharp7CDown |  |
| <!-- TODO: symbol image --> | `X\` | `\x` | paodoublesharp |  | 205.864 | U+E330<br>accSagittalDoubleSharp5CDown |  |
| <!-- TODO: symbol image --> | `/X)` | `nx` | naodoublesharp |  | 221.612 | U+E332<br>accSagittalDoubleSharp5v7kDown |  |
| <!-- TODO: symbol image --> | `/X\` | `x` | doublesharp |  | 227.370 | U+E334<br>accSagittalDoubleSharp |  |
| <!-- TODO: symbol image --> | `\\!!` | `*b` | ranaiflat |  | -103.997 | U+E353<br>accSagittalFlat7v11kUp |  |
| <!-- TODO: symbol image --> | `(!!(` | `eb` | sanaiflat |  | -98.955 | U+E351<br>accSagittalFlat17CUp |  |
| <!-- TODO: symbol image --> | `\!!` | `yb` | kaiflat |  | -81.918 | U+E34F<br>accSagittalFlat55CUp |  |
| <!-- TODO: symbol image --> | `)!!~` | `?b` | jaiflat |  | -80.537 | U+E34D<br>accSagittalFlat7v11CUp |  |
| <!-- TODO: symbol image --> | `~!!(` | `gb` | janaiflat |  | -74.779 | U+E34B<br>accSagittalFlat5v11SUp |  |
| <!-- TODO: symbol image --> | `~||(` | `a#` | janaosharp |  | 74.779 | U+E34A<br>accSagittalSharp5v11SDown | `(|(` |
| <!-- TODO: symbol image --> | `)||~` | `j#` | jaosharp |  | 80.537 | U+E34C<br>accSagittalSharp7v11CDown | `(|` |
| <!-- TODO: symbol image --> | `/||` | `k#` | kaosharp |  | 81.918 | U+E34E<br>accSagittalSharp55CDown | `|\` |
| <!-- TODO: symbol image --> | `(||(` | `o#` | sanaosharp |  | 98.955 | U+E350<br>accSagittalSharp17CDown | `~|(` |
| <!-- TODO: symbol image --> | `//||` | `i#` | ranaosharp |  | 103.997 | U+E352<br>accSagittalSharp7v11kDown | `)|(` |
| <!-- TODO: symbol image --> | `(!!!(` | `ab` | janaoflat |  | -152.591 | U+E35D<br>accSagittalFlat5v11SDown |  |
| <!-- TODO: symbol image --> | `(!!!` | `jb` | jaoflat |  | -146.833 | U+E35B<br>accSagittalFlat7v11CDown |  |
| <!-- TODO: symbol image --> | `!!!/` | `kb` | kaoflat |  | -145.452 | U+E359<br>accSagittalFlat55CDown |  |
| <!-- TODO: symbol image --> | `~!!!(` | `ob` | sanaoflat |  | -128.415 | U+E357<br>accSagittalFlat17CDown |  |
| <!-- TODO: symbol image --> | `)!!!(` | `ib` | ranaoflat |  | -123.373 | U+E355<br>accSagittalFlat7v11kDown |  |
| <!-- TODO: symbol image --> | `)|||(` | `*#` | ranaisharp |  | 123.373 | U+E354<br>accSagittalSharp7v11kUp |  |
| <!-- TODO: symbol image --> | `~|||(` | `e#` | sanaisharp |  | 128.415 | U+E356<br>accSagittalSharp17CUp |  |
| <!-- TODO: symbol image --> | `|||\` | `y#` | kaisharp |  | 145.452 | U+E358<br>accSagittalSharp55CUp |  |
| <!-- TODO: symbol image --> | `(|||` | `?#` | jaisharp |  | 146.833 | U+E35A<br>accSagittalSharp7v11CUp |  |
| <!-- TODO: symbol image --> | `(|||(` | `g#` | janaisharp |  | 152.591 | U+E35C<br>accSagittalSharp5v11SUp |  |
| <!-- TODO: symbol image --> | `\\Y` | `*bb` | ranaidoubleflat |  | -217.682 | U+E367<br>accSagittalDoubleFlat7v11kUp |  |
| <!-- TODO: symbol image --> | `(Y(` | `ebb` | sanaidoubleflat |  | -212.640 | U+E365<br>accSagittalDoubleFlat17CUp |  |
| <!-- TODO: symbol image --> | `\Y` | `ybb` | kaidoubleflat |  | -195.603 | U+E363<br>accSagittalDoubleFlat55CUp |  |
| <!-- TODO: symbol image --> | `)Y~` | `?bb` | jaidoubleflat |  | -194.222 | U+E361<br>accSagittalDoubleFlat7v11CUp |  |
| <!-- TODO: symbol image --> | `~Y(` | `gbb` | janaidoubleflat |  | -188.464 | U+E35F<br>accSagittalDoubleFlat5v11SUp |  |
| <!-- TODO: symbol image --> | `~X(` | `ax` | janaodoublesharp |  | 188.464 | U+E35E<br>accSagittalDoubleSharp5v11SDown |  |
| <!-- TODO: symbol image --> | `)X~` | `jx` | jaodoublesharp |  | 194.222 | U+E360<br>accSagittalDoubleSharp7v11CDown |  |
| <!-- TODO: symbol image --> | `/X` | `kx` | kaodoublesharp |  | 195.603 | U+E362<br>accSagittalDoubleSharp55CDown |  |
| <!-- TODO: symbol image --> | `(X(` | `ox` | sanaodoublesharp |  | 212.640 | U+E364<br>accSagittalDoubleSharp17CDown |  |
| <!-- TODO: symbol image --> | `//X` | `ix` | ranaodoublesharp |  | 217.682 | U+E366<br>accSagittalDoubleSharp7v11kDown |  |
| <!-- TODO: symbol image --> | `(!!~` | `rb` | raiflat |  | -110.307 | U+E3BF<br>accSagittalFlat19sUp |  |
| <!-- TODO: symbol image --> | `)\\!!` | `$b` | saiflat |  | -104.955 | U+E3BD<br>accSagittalFlat17kUp |  |
| <!-- TODO: symbol image --> | `~!!/` |  | slaiflat |  | -101.621 | U+E3BB<br>accSagittalFlat143CUp |  |
| <!-- TODO: symbol image --> | `~!!)` |  | shaiflat |  | -96.109 | U+E3B9<br>accSagittalFlat11v49CUp |  |
| <!-- TODO: symbol image --> | `(!!` |  | razaiflat |  | -93.603 | U+E3B7<br>accSagittalFlat19CUp |  |
| <!-- TODO: symbol image --> | `)\!!` |  | rataiflat |  | -83.043 | U+E3B5<br>accSagittalFlat7v19CUp |  |
| <!-- TODO: symbol image --> | `~~!!` |  | sataiflat |  | -77.988 | U+E3B3<br>accSagittalFlat49SUp |  |
| <!-- TODO: symbol image --> | `)~!!` |  | sakaiflat |  | -73.681 | U+E3B1<br>accSagittalFlat23SUp |  |
| <!-- TODO: symbol image --> | `)~||` |  | sakaosharp |  | 73.681 | U+E3B0<br>accSagittalSharp23SDown | `~|\` |
| <!-- TODO: symbol image --> | `~~||` |  | sataosharp |  | 77.988 | U+E3B2<br>accSagittalSharp49SDown | `~|)` |
| <!-- TODO: symbol image --> | `)/||` |  | rataosharp |  | 83.043 | U+E3B4<br>accSagittalSharp7v19CDown | `)|)` |
| <!-- TODO: symbol image --> | `(||` |  | razaosharp |  | 93.603 | U+E3B6<br>accSagittalSharp19CDown | `)|~` |
| <!-- TODO: symbol image --> | `~||)` |  | shaosharp |  | 96.109 | U+E3B8<br>accSagittalSharp11v49CDown | `~~|` |
| <!-- TODO: symbol image --> | `~||\` |  | slaosharp |  | 101.621 | U+E3BA<br>accSagittalSharp143CDown | `)~|` |
| <!-- TODO: symbol image --> | `)//||` | `s#` | saosharp |  | 104.955 | U+E3BC<br>accSagittalSharp17kDown | `~|` |
| <!-- TODO: symbol image --> | `(||~` | `;#` | raosharp |  | 110.307 | U+E3BE<br>accSagittalSharp19sDown | `)|` |
| <!-- TODO: symbol image --> | `)!!!//` |  | rachaoflat |  | -180.976 | U+E3DD<br>accSagittalFlat5v13LDown |  |
| <!-- TODO: symbol image --> | `!!!//` |  | chaoflat |  | -177.475 | U+E3DB<br>accSagittalFlat11v19LDown |  |
| <!-- TODO: symbol image --> | `!!!/)` |  | ktaoflat |  | -172.842 | U+E3D9<br>accSagittalFlat49LDown |  |
| <!-- TODO: symbol image --> | `)\!!!/` |  | vraoflat |  | -170.167 | U+E3D7<br>accSagittalFlat5v49MDown |  |
| <!-- TODO: symbol image --> | `(\!!!` |  | jpaoflat |  | -168.213 | U+E3D5<br>accSagittalFlat49MDown |  |
| <!-- TODO: symbol image --> | `(!!!~` |  | jazaoflat |  | -163.580 | U+E3D3<br>accSagittalFlat11v19MDown |  |
| <!-- TODO: symbol image --> | `)\\!!!` |  | fraoflat |  | -160.079 | U+E3D1<br>accSagittalFlat5v13MDown |  |
| <!-- TODO: symbol image --> | `~!!!/` |  | sakaoflat |  | -153.689 | U+E3CF<br>accSagittalFlat23SDown |  |
| <!-- TODO: symbol image --> | `~!!!)` |  | sataoflat |  | -149.382 | U+E3CD<br>accSagittalFlat49SDown |  |
| <!-- TODO: symbol image --> | `)!!!)` |  | rataoflat |  | -144.327 | U+E3CB<br>accSagittalFlat7v19CDown |  |
| <!-- TODO: symbol image --> | `)!!!~` |  | razaoflat |  | -133.767 | U+E3C9<br>accSagittalFlat19CDown |  |
| <!-- TODO: symbol image --> | `~~!!!` |  | shaoflat |  | -131.261 | U+E3C7<br>accSagittalFlat11v49CDown |  |
| <!-- TODO: symbol image --> | `)~!!!` |  | slaoflat |  | -125.749 | U+E3C5<br>accSagittalFlat143CDown |  |
| <!-- TODO: symbol image --> | `~!!!` | `sb` | saoflat |  | -122.415 | U+E3C3<br>accSagittalFlat17kDown |  |
| <!-- TODO: symbol image --> | `)!!!` | `;b` | raoflat |  | -117.063 | U+E3C1<br>accSagittalFlat19sDown |  |
| <!-- TODO: symbol image --> | `)|||` | `r#` | raisharp |  | 117.063 | U+E3C0<br>accSagittalSharp19sUp |  |
| <!-- TODO: symbol image --> | `~|||` | `$#` | saisharp |  | 122.415 | U+E3C2<br>accSagittalSharp17kUp |  |
| <!-- TODO: symbol image --> | `)~|||` |  | slaisharp |  | 125.749 | U+E3C4<br>accSagittalSharp143CUp |  |
| <!-- TODO: symbol image --> | `~~|||` |  | shaisharp |  | 131.261 | U+E3C6<br>accSagittalSharp11v49CUp |  |
| <!-- TODO: symbol image --> | `)|||~` |  | razaisharp |  | 133.767 | U+E3C8<br>accSagittalSharp19CUp |  |
| <!-- TODO: symbol image --> | `)|||)` |  | rataisharp |  | 144.327 | U+E3CA<br>accSagittalSharp7v19CUp |  |
| <!-- TODO: symbol image --> | `~|||)` |  | sataisharp |  | 149.382 | U+E3CC<br>accSagittalSharp49SUp |  |
| <!-- TODO: symbol image --> | `~|||\` |  | sakaisharp |  | 153.689 | U+E3CE<br>accSagittalSharp23SUp |  |
| <!-- TODO: symbol image --> | `)//|||` |  | fraisharp |  | 160.079 | U+E3D0<br>accSagittalSharp5v13MUp |  |
| <!-- TODO: symbol image --> | `(|||~` |  | jazaisharp |  | 163.580 | U+E3D2<br>accSagittalSharp11v19MUp |  |
| <!-- TODO: symbol image --> | `(/|||` |  | jpaisharp |  | 168.213 | U+E3D4<br>accSagittalSharp49MUp |  |
| <!-- TODO: symbol image --> | `)/|||\` |  | vraisharp |  | 170.167 | U+E3D6<br>accSagittalSharp5v49MUp |  |
| <!-- TODO: symbol image --> | `|||\)` |  | ktaisharp |  | 172.842 | U+E3D8<br>accSagittalSharp49LUp |  |
| <!-- TODO: symbol image --> | `|||\\` |  | chaisharp |  | 177.475 | U+E3DA<br>accSagittalSharp11v19LUp |  |
| <!-- TODO: symbol image --> | `)|||\\` |  | rachaisharp |  | 180.976 | U+E3DC<br>accSagittalSharp5v13LUp |  |
| <!-- TODO: symbol image --> | `(Y~` | `rbb` | raidoubleflat |  | -223.992 | U+E3EF<br>accSagittalDoubleFlat19sUp |  |
| <!-- TODO: symbol image --> | `)\\Y` | `$bb` | saidoubleflat |  | -218.640 | U+E3ED<br>accSagittalDoubleFlat17kUp |  |
| <!-- TODO: symbol image --> | `~Y/` |  | slaidoubleflat |  | -215.306 | U+E3EB<br>accSagittalDoubleFlat143CUp |  |
| <!-- TODO: symbol image --> | `~Y)` |  | shaidoubleflat |  | -209.794 | U+E3E9<br>accSagittalDoubleFlat11v49CUp |  |
| <!-- TODO: symbol image --> | `(Y` |  | razaidoubleflat |  | -207.288 | U+E3E7<br>accSagittalDoubleFlat19CUp |  |
| <!-- TODO: symbol image --> | `)\Y` |  | rataidoubleflat |  | -196.728 | U+E3E5<br>accSagittalDoubleFlat7v19CUp |  |
| <!-- TODO: symbol image --> | `~~Y` |  | sataidoubleflat |  | -191.673 | U+E3E3<br>accSagittalDoubleFlat49SUp |  |
| <!-- TODO: symbol image --> | `)~Y` |  | sakaidoubleflat |  | -187.366 | U+E3E1<br>accSagittalDoubleFlat23SUp |  |
| <!-- TODO: symbol image --> | `)~X` |  | sakaodoublesharp |  | 187.366 | U+E3E0<br>accSagittalDoubleSharp23SDown |  |
| <!-- TODO: symbol image --> | `~~X` |  | sataodoublesharp |  | 191.673 | U+E3E2<br>accSagittalDoubleSharp49SDown |  |
| <!-- TODO: symbol image --> | `)/X` |  | rataodoublesharp |  | 196.728 | U+E3E4<br>accSagittalDoubleSharp7v19CDown |  |
| <!-- TODO: symbol image --> | `(X` |  | razaodoublesharp |  | 207.288 | U+E3E6<br>accSagittalDoubleSharp19CDown |  |
| <!-- TODO: symbol image --> | `~X)` |  | shaodoublesharp |  | 209.794 | U+E3E8<br>accSagittalDoubleSharp11v49CDown |  |
| <!-- TODO: symbol image --> | `~X\` |  | slaodoublesharp |  | 215.306 | U+E3EA<br>accSagittalDoubleSharp143CDown |  |
| <!-- TODO: symbol image --> | `)//X` | `sx` | saodoublesharp |  | 218.640 | U+E3EC<br>accSagittalDoubleSharp17kDown |  |
| <!-- TODO: symbol image --> | `(X~` | `;x` | raodoublesharp |  | 223.992 | U+E3EE<br>accSagittalDoubleSharp19sDown |  |
| <!-- TODO: symbol image --> | `\!!~` | `~b` | zaiflat |  | -97.141 | U+E37B<br>accSagittalFlat23CUp |  |
| <!-- TODO: symbol image --> | `)!!)` |  | praiflat |  | -88.801 | U+E379<br>accSagittalFlat5v19CUp |  |
| <!-- TODO: symbol image --> | `!!~` |  | pazaiflat |  | -75.634 | U+E377<br>accSagittalFlat5v23SUp |  |
| <!-- TODO: symbol image --> | `||~` |  | pazaosharp |  | 75.634 | U+E376<br>accSagittalSharp5v23SDown | `/|~` |
| <!-- TODO: symbol image --> | `)||)` |  | praosharp |  | 88.801 | U+E378<br>accSagittalSharp5v19CDown | `)/|` |
| <!-- TODO: symbol image --> | `/||~` | `z#` | zaosharp |  | 97.141 | U+E37A<br>accSagittalSharp23CDown | `|~` |
| <!-- TODO: symbol image --> | `\!!!~` |  | pazaoflat |  | -151.736 | U+E381<br>accSagittalFlat5v23SDown |  |
| <!-- TODO: symbol image --> | `)\!!!` |  | praoflat |  | -138.569 | U+E37F<br>accSagittalFlat5v19CDown |  |
| <!-- TODO: symbol image --> | `!!!~` | `zb` | zaoflat |  | -130.229 | U+E37D<br>accSagittalFlat23CDown |  |
| <!-- TODO: symbol image --> | `|||~` | `~#` | zaisharp |  | 130.229 | U+E37C<br>accSagittalSharp23CUp |  |
| <!-- TODO: symbol image --> | `)/|||` |  | praisharp |  | 138.569 | U+E37E<br>accSagittalSharp5v19CUp |  |
| <!-- TODO: symbol image --> | `/|||~` |  | pazaisharp |  | 151.736 | U+E380<br>accSagittalSharp5v23SUp |  |
| <!-- TODO: symbol image --> | `\Y~` | `~bb` | zaidoubleflat |  | -210.826 | U+E387<br>accSagittalDoubleFlat23CUp |  |
| <!-- TODO: symbol image --> | `)Y)` |  | praidoubleflat |  | -202.486 | U+E385<br>accSagittalDoubleFlat5v19CUp |  |
| <!-- TODO: symbol image --> | `Y~` |  | pazaidoubleflat |  | -189.319 | U+E383<br>accSagittalDoubleFlat5v23SUp |  |
| <!-- TODO: symbol image --> | `X~` |  | pazaodoublesharp |  | 189.319 | U+E382<br>accSagittalDoubleSharp5v23SDown |  |
| <!-- TODO: symbol image --> | `)X)` |  | praodoublesharp |  | 202.486 | U+E384<br>accSagittalDoubleSharp5v19CDown |  |
| <!-- TODO: symbol image --> | `/X~` | `zx` | zaodoublesharp |  | 210.826 | U+E386<br>accSagittalDoubleSharp23CDown |  |

## Sagittal-compatible and other

Conventional and Wilson-extension accidentals usable alongside sagittals.

| Glyph | Long | Short | Sagispeak | Primary comma | ¢ | SMuFL | Apotome complement |
|---|---|---|---|---|---|---|---|
| <!-- TODO: symbol image --> |  |  | doubleflat |  | -227.370 | U+E264<br>accidentalDoubleFlat |  |
| <!-- TODO: symbol image --> |  |  |  |  | -166.958 | U+E285<br>accidentalNarrowReversedFlatAndFlat |  |
| <!-- TODO: symbol image --> |  |  | flat |  | -113.685 | U+E260<br>accidentalFlat |  |
| <!-- TODO: symbol image --> |  |  |  |  | -53.273 | U+E284<br>accidentalNarrowReversedFlat |  |
| <!-- TODO: symbol image --> |  |  |  |  | -21.506 | U+E47C<br>accidentalWilsonMinus |  |
| <!-- TODO: symbol image --> | `|//|` | `h` | natural |  | 0.000 | U+F090<br>- | `/||\` |
| <!-- TODO: symbol image --> |  |  |  |  | 21.506 | U+E47B<br>accidentalWilsonPlus |  |
| <!-- TODO: symbol image --> |  |  |  |  | 53.273 | U+E282<br>accidentalQuarterToneSharpStein |  |
| <!-- TODO: symbol image --> |  |  | sharp |  | 113.685 | U+E262<br>accidentalSharp |  |
| <!-- TODO: symbol image --> |  |  |  |  | 166.958 | U+E283<br>accidentalThreeQuarterTonesSharpStein |  |
| <!-- TODO: symbol image --> |  |  | doublesharp |  | 227.370 | U+E47D<br>accidentalLargeDoubleSharp |  |

## Diacritics (accents)

The schisma, mina and tina accents. Each nudges the symbol it attaches to by a tiny amount.

| Glyph | Long | Short | Sagispeak | Primary comma | ¢ | SMuFL | Apotome complement |
|---|---|---|---|---|---|---|---|
| <!-- TODO: symbol image --> | `.` | `.` | bo |  | -1.954 | U+E3F3<br>accSagittalGrave |  |
| <!-- TODO: symbol image --> | `,,` | `,,` | momo |  | -0.833 | U+E3F7<br>accSagittal2MinasDown |  |
| <!-- TODO: symbol image --> | `,` | `,` | mo |  | -0.423 | U+E3F5<br>accSagittal1MinaDown |  |
| <!-- TODO: symbol image --> | `|` |  | ai | 1u | 0.000 | U+E3F0<br>accSagittalShaftUp |  |
| <!-- TODO: symbol image --> | `!` |  | ao | 1u | 0.000 | U+E3F1<br>accSagittalShaftDown |  |
| <!-- TODO: symbol image --> | `` ` `` | `` ` `` | mi |  | 0.423 | U+E3F4<br>accSagittal1MinaUp |  |
| <!-- TODO: symbol image --> | `` `` `` | `` `` `` | mimi |  | 0.833 | U+E3F6<br>accSagittal2MinasUp |  |
| <!-- TODO: symbol image --> | `'` | `'` | bi |  | 1.954 | U+E3F2<br>accSagittalAcute |  |

## What is deferred

- The ~577 further valid symbol combinations in `sheet/02-symbols-valid.csv` beyond this character map (and the rows past its ~404-row capture point).
- Glyph images for every row (`<!-- TODO: symbol image -->`).
- Trojan common-tone and prime-factor/12R membership columns held in `sheet/01`.
