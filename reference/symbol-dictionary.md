# Symbol Dictionary

_This page is generated from the Sagittal data set; corrections belong in the data, not here._

One row per glyph in the **Sagittal-2 character map** (`sheet/01-characters.csv`, 219 accidental symbols + 8 diacritics). This is the dictionary **v1**: it covers every distinct character in the font. The exhaustive enumeration of *valid symbol combinations* lives in `sheet/02-symbols-valid.csv` (981 rows), of which only ~404 were captured — those additional pure/mixed combinations beyond the character map are **deferred** to a later pass.

Columns: the glyph image (to be added), long (pure) and short sagitypes, [Sagispeak](../concept-explanations/sagispeak.md), [primary comma](primary-commas-table.md) as a directed name (single-shaft only), cents, the frozen [SMuFL](../concept-explanations/comma-names.md) codepoint and class name, and the [apotome complement](../concept-explanations/apotome-complements.md) (the symbol that completes an apotome with this one). Primary-comma names come from `sheet/03`; apotome complements are the symbol at `apotome − cents`. Blank cells mean the datum does not apply (e.g. multi-shaft symbols have no single primary comma).

## Single-shaft symbols

The core comma symbols, each with a primary comma. Sorted by size; negative cents are the downward twins.

| Glyph | Long | Short | Sagispeak | Primary comma | ¢ | SMuFL | Apotome complement |
|---|---|---|---|---|---|---|---|
| <img src="../.gitbook/assets/glyphs/accSagittal5v13LargeDiesisDown.svg" alt=")!//" data-size="line"> | `)!//` |  | rachao | 13/5L | -67.291 | U+E3AD<br>accSagittal5v13LargeDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal35LargeDiesisDown.svg" alt="(!/" data-size="line"> | `(!/` | `d` | dao | 1/35L | -64.915 | U+E30F<br>accSagittal35LargeDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal11v19LargeDiesisDown.svg" alt="!//" data-size="line"> | `!//` |  | chao | 11/19L | -63.790 | U+E3AB<br>accSagittal11v19LargeDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal11LargeDiesisDown.svg" alt="(!)" data-size="line"> | `(!)` | `w` | wao | 11L | -60.412 | U+E30D<br>accSagittal11LargeDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal49LargeDiesisDown.svg" alt="!/)" data-size="line"> | `!/)` |  | ktao | 1/49L | -59.157 | U+E3A9<br>accSagittal49LargeDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal5v49MediumDiesisDown.svg" alt=")\!/" data-size="line"> | `)\!/` |  | vrao | 49/5M | -56.482 | U+E3A7<br>accSagittal5v49MediumDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal49MediumDiesisDown.svg" alt="(\!" data-size="line"> | `(\!` |  | jpao | 49M | -54.528 | U+E3A5<br>accSagittal49MediumDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal11MediumDiesisDown.svg" alt="\!/" data-size="line"> | `\!/` | `v` | vao | 1/11M | -53.273 | U+E30B<br>accSagittal11MediumDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal11v19MediumDiesisDown.svg" alt="(!~" data-size="line"> | `(!~` |  | jazao | 19/11M | -49.895 | U+E3A3<br>accSagittal11v19MediumDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal35MediumDiesisDown.svg" alt="\!)" data-size="line"> | `\!)` | `&` | gao | 35M | -48.770 | U+E309<br>accSagittal35MediumDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal5v13MediumDiesisDown.svg" alt=")\\!" data-size="line"> | `)\\!` |  | frao | 5/13M | -46.394 | U+E3A1<br>accSagittal5v13MediumDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal25SmallDiesisDown.svg" alt="\\!" data-size="line"> | `\\!` | `_` | fao | 25S | -43.013 | U+E307<br>accSagittal25SmallDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal23SmallDiesisDown.svg" alt="~!/" data-size="line"> | `~!/` |  | sakao | 1/23S | -40.004 | U+E39F<br>accSagittal23SmallDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal5v11SmallDiesisDown.svg" alt="(!(" data-size="line"> | `(!(` | `a` | janao | 11/5S | -38.906 | U+E349<br>accSagittal5v11SmallDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal5v23SmallDiesisDown.svg" alt="\!~" data-size="line"> | `\!~` |  | pazao | 5/23S | -38.051 | U+E375<br>accSagittal5v23SmallDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal49SmallDiesisDown.svg" alt="~!)" data-size="line"> | `~!)` |  | satao | 1/49S | -35.697 | U+E39D<br>accSagittal49SmallDiesisDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal7v11CommaDown.svg" alt="(!" data-size="line"> | `(!` | `j` | jao | 11/7C | -33.148 | U+E347<br>accSagittal7v11CommaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal55CommaDown.svg" alt="!/" data-size="line"> | `!/` | `k` | kao | 1/55C | -31.767 | U+E345<br>accSagittal55CommaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal7v19CommaDown.svg" alt=")!)" data-size="line"> | `)!)` |  | ratao | 7/19C | -30.642 | U+E39B<br>accSagittal7v19CommaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal7CommaDown.svg" alt="!)" data-size="line"> | `!)` | `t` | tao | 7C | -27.264 | U+E305<br>accSagittal7CommaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal5v19CommaDown.svg" alt=")\!" data-size="line"> | `)\!` |  | prao | 5/19C | -24.884 | U+E373<br>accSagittal5v19CommaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal5CommaDown.svg" alt="\!" data-size="line"> | `\!` | `\` | pao | 5C | -21.506 | U+E303<br>accSagittal5CommaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal19CommaDown.svg" alt=")!~" data-size="line"> | `)!~` |  | razao | 19C | -20.082 | U+E399<br>accSagittal19CommaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal11v49CommaDown.svg" alt="~~!" data-size="line"> | `~~!` |  | shao | 49/11C | -17.576 | U+E397<br>accSagittal11v49CommaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal23CommaDown.svg" alt="!~" data-size="line"> | `!~` | `z` | zao | 1/23C | -16.544 | U+E371<br>accSagittal23CommaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal17CommaDown.svg" alt="~!(" data-size="line"> | `~!(` | `o` | sanao | 1/17C | -14.730 | U+E343<br>accSagittal17CommaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal143CommaDown.svg" alt=")~!" data-size="line"> | `)~!` |  | slao | 143C | -12.064 | U+E395<br>accSagittal143CommaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal7v11KleismaDown.svg" alt=")!(" data-size="line"> | `)!(` | `i` | ranao | 11/7k | -9.688 | U+E341<br>accSagittal7v11KleismaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal17KleismaDown.svg" alt="~!" data-size="line"> | `~!` | `s` | sao | 17k | -8.730 | U+E393<br>accSagittal17KleismaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal5v7KleismaDown.svg" alt="!(" data-size="line"> | `!(` | `n` | nao | 7/5k | -5.758 | U+E301<br>accSagittal5v7KleismaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal19SchismaDown.svg" alt=")!" data-size="line"> | `)!` | `;` | rao | 1/19s | -3.378 | U+E391<br>accSagittal19SchismaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal19SchismaUp.svg" alt=")&#124;" data-size="line"> | `)|` | `r` | rai | 19s | 3.378 | U+E390<br>accSagittal19SchismaUp | `(||~` |
| <img src="../.gitbook/assets/glyphs/accSagittal5v7KleismaUp.svg" alt="&#124;(" data-size="line"> | `|(` | `u` | nai | 5/7k | 5.758 | U+E300<br>accSagittal5v7KleismaUp | `/||)` |
| <img src="../.gitbook/assets/glyphs/accSagittal17KleismaUp.svg" alt="~&#124;" data-size="line"> | `~|` | `$` | sai | 1/17k | 8.730 | U+E392<br>accSagittal17KleismaUp | `)//||` |
| <img src="../.gitbook/assets/glyphs/accSagittal7v11KleismaUp.svg" alt=")&#124;(" data-size="line"> | `)|(` | `*` | ranai | 7/11k | 9.688 | U+E340<br>accSagittal7v11KleismaUp | `//||` |
| <img src="../.gitbook/assets/glyphs/accSagittal143CommaUp.svg" alt=")~&#124;" data-size="line"> | `)~|` |  | slai | 1/143C | 12.064 | U+E394<br>accSagittal143CommaUp | `~||\` |
| <img src="../.gitbook/assets/glyphs/accSagittal17CommaUp.svg" alt="~&#124;(" data-size="line"> | `~|(` | `e` | sanai | 17C | 14.730 | U+E342<br>accSagittal17CommaUp | `(||(` |
| <img src="../.gitbook/assets/glyphs/accSagittal23CommaUp.svg" alt="&#124;~" data-size="line"> | `|~` | `~` | zai | 23C | 16.544 | U+E370<br>accSagittal23CommaUp | `/||~` |
| <img src="../.gitbook/assets/glyphs/accSagittal11v49CommaUp.svg" alt="~~&#124;" data-size="line"> | `~~|` |  | shai | 11/49C | 17.576 | U+E396<br>accSagittal11v49CommaUp | `~||)` |
| <img src="../.gitbook/assets/glyphs/accSagittal19CommaUp.svg" alt=")&#124;~" data-size="line"> | `)|~` |  | razai | 1/19C | 20.082 | U+E398<br>accSagittal19CommaUp | `(||` |
| <img src="../.gitbook/assets/glyphs/accSagittal5CommaUp.svg" alt="/&#124;" data-size="line"> | `/|` | `/` | pai | 1/5C | 21.506 | U+E302<br>accSagittal5CommaUp | `||\` |
| <img src="../.gitbook/assets/glyphs/accSagittal5v19CommaUp.svg" alt=")/&#124;" data-size="line"> | `)/|` |  | prai | 19/5C | 24.884 | U+E372<br>accSagittal5v19CommaUp | `)||)` |
| <img src="../.gitbook/assets/glyphs/accSagittal7CommaUp.svg" alt="&#124;)" data-size="line"> | `|)` | `f` | tai | 1/7C | 27.264 | U+E304<br>accSagittal7CommaUp | `||)` |
| <img src="../.gitbook/assets/glyphs/accSagittal7v19CommaUp.svg" alt=")&#124;)" data-size="line"> | `)|)` |  | ratai | 19/7C | 30.642 | U+E39A<br>accSagittal7v19CommaUp | `)/||` |
| <img src="../.gitbook/assets/glyphs/accSagittal55CommaUp.svg" alt="&#124;\" data-size="line"> | `|\` | `y` | kai | 55C | 31.767 | U+E344<br>accSagittal55CommaUp | `/||` |
| <img src="../.gitbook/assets/glyphs/accSagittal7v11CommaUp.svg" alt="(&#124;" data-size="line"> | `(|` | `?` | jai | 7/11C | 33.148 | U+E346<br>accSagittal7v11CommaUp | `)||~` |
| <img src="../.gitbook/assets/glyphs/accSagittal49SmallDiesisUp.svg" alt="~&#124;)" data-size="line"> | `~|)` |  | satai | 49S | 35.697 | U+E39C<br>accSagittal49SmallDiesisUp | `~~||` |
| <img src="../.gitbook/assets/glyphs/accSagittal5v23SmallDiesisUp.svg" alt="/&#124;~" data-size="line"> | `/|~` |  | pazai | 23/5S | 38.051 | U+E374<br>accSagittal5v23SmallDiesisUp | `||~` |
| <img src="../.gitbook/assets/glyphs/accSagittal5v11SmallDiesisUp.svg" alt="(&#124;(" data-size="line"> | `(|(` | `g` | janai | 5/11S | 38.906 | U+E348<br>accSagittal5v11SmallDiesisUp | `~||(` |
| <img src="../.gitbook/assets/glyphs/accSagittal23SmallDiesisUp.svg" alt="~&#124;\" data-size="line"> | `~|\` |  | sakai | 23S | 40.004 | U+E39E<br>accSagittal23SmallDiesisUp | `)~||` |
| <img src="../.gitbook/assets/glyphs/accSagittal25SmallDiesisUp.svg" alt="//&#124;" data-size="line"> | `//|` | `=` | fai | 1/25S | 43.013 | U+E306<br>accSagittal25SmallDiesisUp | `)||(` |
| <img src="../.gitbook/assets/glyphs/accSagittal5v13MediumDiesisUp.svg" alt=")//&#124;" data-size="line"> | `)//|` |  | frai | 13/5M | 46.394 | U+E3A0<br>accSagittal5v13MediumDiesisUp | `)|\\` |
| <img src="../.gitbook/assets/glyphs/accSagittal35MediumDiesisUp.svg" alt="/&#124;)" data-size="line"> | `/|)` | `%` | gai | 1/35M | 48.770 | U+E308<br>accSagittal35MediumDiesisUp | `(|\` |
| <img src="../.gitbook/assets/glyphs/accSagittal11v19MediumDiesisUp.svg" alt="(&#124;~" data-size="line"> | `(|~` |  | jazai | 11/19M | 49.895 | U+E3A2<br>accSagittal11v19MediumDiesisUp | `|\\` |
| <img src="../.gitbook/assets/glyphs/accSagittal11MediumDiesisUp.svg" alt="/&#124;\" data-size="line"> | `/|\` | `^` | vai | 11M | 53.273 | U+E30A<br>accSagittal11MediumDiesisUp | `(|)` |
| <img src="../.gitbook/assets/glyphs/accSagittal49MediumDiesisUp.svg" alt="(/&#124;" data-size="line"> | `(/|` |  | jpai | 1/49M | 54.528 | U+E3A4<br>accSagittal49MediumDiesisUp | `|\)` |
| <img src="../.gitbook/assets/glyphs/accSagittal5v49MediumDiesisUp.svg" alt=")/&#124;\" data-size="line"> | `)/|\` |  | vrai | 5/49M | 56.482 | U+E3A6<br>accSagittal5v49MediumDiesisUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittal49LargeDiesisUp.svg" alt="&#124;\)" data-size="line"> | `|\)` |  | ktai | 49L | 59.157 | U+E3A8<br>accSagittal49LargeDiesisUp | `(/|` |
| <img src="../.gitbook/assets/glyphs/accSagittal11LargeDiesisUp.svg" alt="(&#124;)" data-size="line"> | `(|)` | `m` | wai | 1/11L | 60.412 | U+E30C<br>accSagittal11LargeDiesisUp | `/|\` |
| <img src="../.gitbook/assets/glyphs/accSagittal11v19LargeDiesisUp.svg" alt="&#124;\\" data-size="line"> | `|\\` |  | chai | 19/11L | 63.790 | U+E3AA<br>accSagittal11v19LargeDiesisUp | `(|~` |
| <img src="../.gitbook/assets/glyphs/accSagittal35LargeDiesisUp.svg" alt="(&#124;\" data-size="line"> | `(|\` | `q` | dai | 35L | 64.915 | U+E30E<br>accSagittal35LargeDiesisUp | `/|)` |
| <img src="../.gitbook/assets/glyphs/accSagittal5v13LargeDiesisUp.svg" alt=")&#124;\\" data-size="line"> | `)|\\` |  | rachai | 5/13L | 67.291 | U+E3AC<br>accSagittal5v13LargeDiesisUp | `)//|` |

## Multi-shaft symbols

Two-, three- and four-shaft symbols (Revo) and the Evo compounds, Spartan and Athenian sets first. These carry a sharp/flat’s worth of apotomes plus a comma, so they have no single primary comma; Sagispeak is the composed form (e.g. `kaisharp`).

| Glyph | Long | Short | Sagispeak | Primary comma | ¢ | SMuFL | Apotome complement |
|---|---|---|---|---|---|---|---|
| <img src="../.gitbook/assets/glyphs/accSagittalFlat.svg" alt="\!!/" data-size="line"> | `\!!/` | `b` | flat |  | -113.685 | U+E319<br>accSagittalFlat |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat5v7kUp.svg" alt="\!!)" data-size="line"> | `\!!)` | `ub` | naiflat |  | -107.927 | U+E317<br>accSagittalFlat5v7kUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat5CUp.svg" alt="!!/" data-size="line"> | `!!/` | `/b` | paiflat |  | -92.179 | U+E315<br>accSagittalFlat5CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat7CUp.svg" alt="!!)" data-size="line"> | `!!)` | `fb` | taiflat |  | -86.421 | U+E313<br>accSagittalFlat7CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat25SUp.svg" alt=")!!(" data-size="line"> | `)!!(` | `=b` | faiflat |  | -70.672 | U+E311<br>accSagittalFlat25SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp25SDown.svg" alt=")&#124;&#124;(" data-size="line"> | `)||(` | `_#` | faosharp |  | 70.672 | U+E310<br>accSagittalSharp25SDown | `//|` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp7CDown.svg" alt="&#124;&#124;)" data-size="line"> | `||)` | `t#` | taosharp |  | 86.421 | U+E312<br>accSagittalSharp7CDown | `|)` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp5CDown.svg" alt="&#124;&#124;\" data-size="line"> | `||\` | `\#` | paosharp |  | 92.179 | U+E314<br>accSagittalSharp5CDown | `/|` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp5v7kDown.svg" alt="/&#124;&#124;)" data-size="line"> | `/||)` | `n#` | naosharp |  | 107.927 | U+E316<br>accSagittalSharp5v7kDown | `|(` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp.svg" alt="/&#124;&#124;\" data-size="line"> | `/||\` | `#` | sharp |  | 113.685 | U+E318<br>accSagittalSharp | `|//|` |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat35LDown.svg" alt="(!!!/" data-size="line"> | `(!!!/` | `db` | daoflat |  | -178.600 | U+E32B<br>accSagittalFlat35LDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat11LDown.svg" alt="(!!!)" data-size="line"> | `(!!!)` | `wb` | waoflat |  | -174.097 | U+E329<br>accSagittalFlat11LDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat11MDown.svg" alt="\!!!/" data-size="line"> | `\!!!/` | `vb` | vaoflat |  | -166.958 | U+E327<br>accSagittalFlat11MDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat35MDown.svg" alt="\!!!)" data-size="line"> | `\!!!)` | `&b` | gaoflat |  | -162.455 | U+E325<br>accSagittalFlat35MDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat25SDown.svg" alt="\\!!!" data-size="line"> | `\\!!!` | `_b` | faoflat |  | -156.698 | U+E323<br>accSagittalFlat25SDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat7CDown.svg" alt="!!!)" data-size="line"> | `!!!)` | `tb` | taoflat |  | -140.949 | U+E321<br>accSagittalFlat7CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat5CDown.svg" alt="\!!!" data-size="line"> | `\!!!` | `\b` | paoflat |  | -135.191 | U+E31F<br>accSagittalFlat5CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat5v7kDown.svg" alt="!!!(" data-size="line"> | `!!!(` | `nb` | naoflat |  | -119.443 | U+E31D<br>accSagittalFlat5v7kDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp5v7kUp.svg" alt="&#124;&#124;&#124;(" data-size="line"> | `|||(` | `u#` | naisharp |  | 119.443 | U+E31C<br>accSagittalSharp5v7kUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp5CUp.svg" alt="/&#124;&#124;&#124;" data-size="line"> | `/|||` | `/#` | paisharp |  | 135.191 | U+E31E<br>accSagittalSharp5CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp7CUp.svg" alt="&#124;&#124;&#124;)" data-size="line"> | `|||)` | `f#` | taisharp |  | 140.949 | U+E320<br>accSagittalSharp7CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp25SUp.svg" alt="//&#124;&#124;&#124;" data-size="line"> | `//|||` | `=#` | faisharp |  | 156.698 | U+E322<br>accSagittalSharp25SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp35MUp.svg" alt="/&#124;&#124;&#124;)" data-size="line"> | `/|||)` | `%#` | gaisharp |  | 162.455 | U+E324<br>accSagittalSharp35MUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp11MUp.svg" alt="/&#124;&#124;&#124;\" data-size="line"> | `/|||\` | `^#` | vaisharp |  | 166.958 | U+E326<br>accSagittalSharp11MUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp11LUp.svg" alt="(&#124;&#124;&#124;)" data-size="line"> | `(|||)` | `m#` | waisharp |  | 174.097 | U+E328<br>accSagittalSharp11LUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp35LUp.svg" alt="(&#124;&#124;&#124;\" data-size="line"> | `(|||\` | `q#` | daisharp |  | 178.600 | U+E32A<br>accSagittalSharp35LUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat.svg" alt="\Y/" data-size="line"> | `\Y/` | `bb` | doubleflat |  | -227.370 | U+E335<br>accSagittalDoubleFlat |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat5v7kUp.svg" alt="\Y)" data-size="line"> | `\Y)` | `ubb` | naidoubleflat |  | -221.612 | U+E333<br>accSagittalDoubleFlat5v7kUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat5CUp.svg" alt="Y/" data-size="line"> | `Y/` | `/bb` | paidoubleflat |  | -205.864 | U+E331<br>accSagittalDoubleFlat5CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat7CUp.svg" alt="Y)" data-size="line"> | `Y)` | `fbb` | taidoubleflat |  | -200.106 | U+E32F<br>accSagittalDoubleFlat7CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat25SUp.svg" alt=")Y(" data-size="line"> | `)Y(` | `=bb` | faidoubleflat |  | -184.357 | U+E32D<br>accSagittalDoubleFlat25SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp25SDown.svg" alt=")X(" data-size="line"> | `)X(` | `_x` | faodoublesharp |  | 184.357 | U+E32C<br>accSagittalDoubleSharp25SDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp7CDown.svg" alt="X)" data-size="line"> | `X)` | `tx` | taodoublesharp |  | 200.106 | U+E32E<br>accSagittalDoubleSharp7CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp5CDown.svg" alt="X\" data-size="line"> | `X\` | `\x` | paodoublesharp |  | 205.864 | U+E330<br>accSagittalDoubleSharp5CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp5v7kDown.svg" alt="/X)" data-size="line"> | `/X)` | `nx` | naodoublesharp |  | 221.612 | U+E332<br>accSagittalDoubleSharp5v7kDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp.svg" alt="/X\" data-size="line"> | `/X\` | `x` | doublesharp |  | 227.370 | U+E334<br>accSagittalDoubleSharp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat7v11kUp.svg" alt="\\!!" data-size="line"> | `\\!!` | `*b` | ranaiflat |  | -103.997 | U+E353<br>accSagittalFlat7v11kUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat17CUp.svg" alt="(!!(" data-size="line"> | `(!!(` | `eb` | sanaiflat |  | -98.955 | U+E351<br>accSagittalFlat17CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat55CUp.svg" alt="\!!" data-size="line"> | `\!!` | `yb` | kaiflat |  | -81.918 | U+E34F<br>accSagittalFlat55CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat7v11CUp.svg" alt=")!!~" data-size="line"> | `)!!~` | `?b` | jaiflat |  | -80.537 | U+E34D<br>accSagittalFlat7v11CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat5v11SUp.svg" alt="~!!(" data-size="line"> | `~!!(` | `gb` | janaiflat |  | -74.779 | U+E34B<br>accSagittalFlat5v11SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp5v11SDown.svg" alt="~&#124;&#124;(" data-size="line"> | `~||(` | `a#` | janaosharp |  | 74.779 | U+E34A<br>accSagittalSharp5v11SDown | `(|(` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp7v11CDown.svg" alt=")&#124;&#124;~" data-size="line"> | `)||~` | `j#` | jaosharp |  | 80.537 | U+E34C<br>accSagittalSharp7v11CDown | `(|` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp55CDown.svg" alt="/&#124;&#124;" data-size="line"> | `/||` | `k#` | kaosharp |  | 81.918 | U+E34E<br>accSagittalSharp55CDown | `|\` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp17CDown.svg" alt="(&#124;&#124;(" data-size="line"> | `(||(` | `o#` | sanaosharp |  | 98.955 | U+E350<br>accSagittalSharp17CDown | `~|(` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp7v11kDown.svg" alt="//&#124;&#124;" data-size="line"> | `//||` | `i#` | ranaosharp |  | 103.997 | U+E352<br>accSagittalSharp7v11kDown | `)|(` |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat5v11SDown.svg" alt="(!!!(" data-size="line"> | `(!!!(` | `ab` | janaoflat |  | -152.591 | U+E35D<br>accSagittalFlat5v11SDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat7v11CDown.svg" alt="(!!!" data-size="line"> | `(!!!` | `jb` | jaoflat |  | -146.833 | U+E35B<br>accSagittalFlat7v11CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat55CDown.svg" alt="!!!/" data-size="line"> | `!!!/` | `kb` | kaoflat |  | -145.452 | U+E359<br>accSagittalFlat55CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat17CDown.svg" alt="~!!!(" data-size="line"> | `~!!!(` | `ob` | sanaoflat |  | -128.415 | U+E357<br>accSagittalFlat17CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat7v11kDown.svg" alt=")!!!(" data-size="line"> | `)!!!(` | `ib` | ranaoflat |  | -123.373 | U+E355<br>accSagittalFlat7v11kDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp7v11kUp.svg" alt=")&#124;&#124;&#124;(" data-size="line"> | `)|||(` | `*#` | ranaisharp |  | 123.373 | U+E354<br>accSagittalSharp7v11kUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp17CUp.svg" alt="~&#124;&#124;&#124;(" data-size="line"> | `~|||(` | `e#` | sanaisharp |  | 128.415 | U+E356<br>accSagittalSharp17CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp55CUp.svg" alt="&#124;&#124;&#124;\" data-size="line"> | `|||\` | `y#` | kaisharp |  | 145.452 | U+E358<br>accSagittalSharp55CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp7v11CUp.svg" alt="(&#124;&#124;&#124;" data-size="line"> | `(|||` | `?#` | jaisharp |  | 146.833 | U+E35A<br>accSagittalSharp7v11CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp5v11SUp.svg" alt="(&#124;&#124;&#124;(" data-size="line"> | `(|||(` | `g#` | janaisharp |  | 152.591 | U+E35C<br>accSagittalSharp5v11SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat7v11kUp.svg" alt="\\Y" data-size="line"> | `\\Y` | `*bb` | ranaidoubleflat |  | -217.682 | U+E367<br>accSagittalDoubleFlat7v11kUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat17CUp.svg" alt="(Y(" data-size="line"> | `(Y(` | `ebb` | sanaidoubleflat |  | -212.640 | U+E365<br>accSagittalDoubleFlat17CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat55CUp.svg" alt="\Y" data-size="line"> | `\Y` | `ybb` | kaidoubleflat |  | -195.603 | U+E363<br>accSagittalDoubleFlat55CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat7v11CUp.svg" alt=")Y~" data-size="line"> | `)Y~` | `?bb` | jaidoubleflat |  | -194.222 | U+E361<br>accSagittalDoubleFlat7v11CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat5v11SUp.svg" alt="~Y(" data-size="line"> | `~Y(` | `gbb` | janaidoubleflat |  | -188.464 | U+E35F<br>accSagittalDoubleFlat5v11SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp5v11SDown.svg" alt="~X(" data-size="line"> | `~X(` | `ax` | janaodoublesharp |  | 188.464 | U+E35E<br>accSagittalDoubleSharp5v11SDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp7v11CDown.svg" alt=")X~" data-size="line"> | `)X~` | `jx` | jaodoublesharp |  | 194.222 | U+E360<br>accSagittalDoubleSharp7v11CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp55CDown.svg" alt="/X" data-size="line"> | `/X` | `kx` | kaodoublesharp |  | 195.603 | U+E362<br>accSagittalDoubleSharp55CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp17CDown.svg" alt="(X(" data-size="line"> | `(X(` | `ox` | sanaodoublesharp |  | 212.640 | U+E364<br>accSagittalDoubleSharp17CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp7v11kDown.svg" alt="//X" data-size="line"> | `//X` | `ix` | ranaodoublesharp |  | 217.682 | U+E366<br>accSagittalDoubleSharp7v11kDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat19sUp.svg" alt="(!!~" data-size="line"> | `(!!~` | `rb` | raiflat |  | -110.307 | U+E3BF<br>accSagittalFlat19sUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat17kUp.svg" alt=")\\!!" data-size="line"> | `)\\!!` | `$b` | saiflat |  | -104.955 | U+E3BD<br>accSagittalFlat17kUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat143CUp.svg" alt="~!!/" data-size="line"> | `~!!/` |  | slaiflat |  | -101.621 | U+E3BB<br>accSagittalFlat143CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat11v49CUp.svg" alt="~!!)" data-size="line"> | `~!!)` |  | shaiflat |  | -96.109 | U+E3B9<br>accSagittalFlat11v49CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat19CUp.svg" alt="(!!" data-size="line"> | `(!!` |  | razaiflat |  | -93.603 | U+E3B7<br>accSagittalFlat19CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat7v19CUp.svg" alt=")\!!" data-size="line"> | `)\!!` |  | rataiflat |  | -83.043 | U+E3B5<br>accSagittalFlat7v19CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat49SUp.svg" alt="~~!!" data-size="line"> | `~~!!` |  | sataiflat |  | -77.988 | U+E3B3<br>accSagittalFlat49SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat23SUp.svg" alt=")~!!" data-size="line"> | `)~!!` |  | sakaiflat |  | -73.681 | U+E3B1<br>accSagittalFlat23SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp23SDown.svg" alt=")~&#124;&#124;" data-size="line"> | `)~||` |  | sakaosharp |  | 73.681 | U+E3B0<br>accSagittalSharp23SDown | `~|\` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp49SDown.svg" alt="~~&#124;&#124;" data-size="line"> | `~~||` |  | sataosharp |  | 77.988 | U+E3B2<br>accSagittalSharp49SDown | `~|)` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp7v19CDown.svg" alt=")/&#124;&#124;" data-size="line"> | `)/||` |  | rataosharp |  | 83.043 | U+E3B4<br>accSagittalSharp7v19CDown | `)|)` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp19CDown.svg" alt="(&#124;&#124;" data-size="line"> | `(||` |  | razaosharp |  | 93.603 | U+E3B6<br>accSagittalSharp19CDown | `)|~` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp11v49CDown.svg" alt="~&#124;&#124;)" data-size="line"> | `~||)` |  | shaosharp |  | 96.109 | U+E3B8<br>accSagittalSharp11v49CDown | `~~|` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp143CDown.svg" alt="~&#124;&#124;\" data-size="line"> | `~||\` |  | slaosharp |  | 101.621 | U+E3BA<br>accSagittalSharp143CDown | `)~|` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp17kDown.svg" alt=")//&#124;&#124;" data-size="line"> | `)//||` | `s#` | saosharp |  | 104.955 | U+E3BC<br>accSagittalSharp17kDown | `~|` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp19sDown.svg" alt="(&#124;&#124;~" data-size="line"> | `(||~` | `;#` | raosharp |  | 110.307 | U+E3BE<br>accSagittalSharp19sDown | `)|` |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat5v13LDown.svg" alt=")!!!//" data-size="line"> | `)!!!//` |  | rachaoflat |  | -180.976 | U+E3DD<br>accSagittalFlat5v13LDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat11v19LDown.svg" alt="!!!//" data-size="line"> | `!!!//` |  | chaoflat |  | -177.475 | U+E3DB<br>accSagittalFlat11v19LDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat49LDown.svg" alt="!!!/)" data-size="line"> | `!!!/)` |  | ktaoflat |  | -172.842 | U+E3D9<br>accSagittalFlat49LDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat5v49MDown.svg" alt=")\!!!/" data-size="line"> | `)\!!!/` |  | vraoflat |  | -170.167 | U+E3D7<br>accSagittalFlat5v49MDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat49MDown.svg" alt="(\!!!" data-size="line"> | `(\!!!` |  | jpaoflat |  | -168.213 | U+E3D5<br>accSagittalFlat49MDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat11v19MDown.svg" alt="(!!!~" data-size="line"> | `(!!!~` |  | jazaoflat |  | -163.580 | U+E3D3<br>accSagittalFlat11v19MDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat5v13MDown.svg" alt=")\\!!!" data-size="line"> | `)\\!!!` |  | fraoflat |  | -160.079 | U+E3D1<br>accSagittalFlat5v13MDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat23SDown.svg" alt="~!!!/" data-size="line"> | `~!!!/` |  | sakaoflat |  | -153.689 | U+E3CF<br>accSagittalFlat23SDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat49SDown.svg" alt="~!!!)" data-size="line"> | `~!!!)` |  | sataoflat |  | -149.382 | U+E3CD<br>accSagittalFlat49SDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat7v19CDown.svg" alt=")!!!)" data-size="line"> | `)!!!)` |  | rataoflat |  | -144.327 | U+E3CB<br>accSagittalFlat7v19CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat19CDown.svg" alt=")!!!~" data-size="line"> | `)!!!~` |  | razaoflat |  | -133.767 | U+E3C9<br>accSagittalFlat19CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat11v49CDown.svg" alt="~~!!!" data-size="line"> | `~~!!!` |  | shaoflat |  | -131.261 | U+E3C7<br>accSagittalFlat11v49CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat143CDown.svg" alt=")~!!!" data-size="line"> | `)~!!!` |  | slaoflat |  | -125.749 | U+E3C5<br>accSagittalFlat143CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat17kDown.svg" alt="~!!!" data-size="line"> | `~!!!` | `sb` | saoflat |  | -122.415 | U+E3C3<br>accSagittalFlat17kDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat19sDown.svg" alt=")!!!" data-size="line"> | `)!!!` | `;b` | raoflat |  | -117.063 | U+E3C1<br>accSagittalFlat19sDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp19sUp.svg" alt=")&#124;&#124;&#124;" data-size="line"> | `)|||` | `r#` | raisharp |  | 117.063 | U+E3C0<br>accSagittalSharp19sUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp17kUp.svg" alt="~&#124;&#124;&#124;" data-size="line"> | `~|||` | `$#` | saisharp |  | 122.415 | U+E3C2<br>accSagittalSharp17kUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp143CUp.svg" alt=")~&#124;&#124;&#124;" data-size="line"> | `)~|||` |  | slaisharp |  | 125.749 | U+E3C4<br>accSagittalSharp143CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp11v49CUp.svg" alt="~~&#124;&#124;&#124;" data-size="line"> | `~~|||` |  | shaisharp |  | 131.261 | U+E3C6<br>accSagittalSharp11v49CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp19CUp.svg" alt=")&#124;&#124;&#124;~" data-size="line"> | `)|||~` |  | razaisharp |  | 133.767 | U+E3C8<br>accSagittalSharp19CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp7v19CUp.svg" alt=")&#124;&#124;&#124;)" data-size="line"> | `)|||)` |  | rataisharp |  | 144.327 | U+E3CA<br>accSagittalSharp7v19CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp49SUp.svg" alt="~&#124;&#124;&#124;)" data-size="line"> | `~|||)` |  | sataisharp |  | 149.382 | U+E3CC<br>accSagittalSharp49SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp23SUp.svg" alt="~&#124;&#124;&#124;\" data-size="line"> | `~|||\` |  | sakaisharp |  | 153.689 | U+E3CE<br>accSagittalSharp23SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp5v13MUp.svg" alt=")//&#124;&#124;&#124;" data-size="line"> | `)//|||` |  | fraisharp |  | 160.079 | U+E3D0<br>accSagittalSharp5v13MUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp11v19MUp.svg" alt="(&#124;&#124;&#124;~" data-size="line"> | `(|||~` |  | jazaisharp |  | 163.580 | U+E3D2<br>accSagittalSharp11v19MUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp49MUp.svg" alt="(/&#124;&#124;&#124;" data-size="line"> | `(/|||` |  | jpaisharp |  | 168.213 | U+E3D4<br>accSagittalSharp49MUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp5v49MUp.svg" alt=")/&#124;&#124;&#124;\" data-size="line"> | `)/|||\` |  | vraisharp |  | 170.167 | U+E3D6<br>accSagittalSharp5v49MUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp49LUp.svg" alt="&#124;&#124;&#124;\)" data-size="line"> | `|||\)` |  | ktaisharp |  | 172.842 | U+E3D8<br>accSagittalSharp49LUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp11v19LUp.svg" alt="&#124;&#124;&#124;\\" data-size="line"> | `|||\\` |  | chaisharp |  | 177.475 | U+E3DA<br>accSagittalSharp11v19LUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp5v13LUp.svg" alt=")&#124;&#124;&#124;\\" data-size="line"> | `)|||\\` |  | rachaisharp |  | 180.976 | U+E3DC<br>accSagittalSharp5v13LUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat19sUp.svg" alt="(Y~" data-size="line"> | `(Y~` | `rbb` | raidoubleflat |  | -223.992 | U+E3EF<br>accSagittalDoubleFlat19sUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat17kUp.svg" alt=")\\Y" data-size="line"> | `)\\Y` | `$bb` | saidoubleflat |  | -218.640 | U+E3ED<br>accSagittalDoubleFlat17kUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat143CUp.svg" alt="~Y/" data-size="line"> | `~Y/` |  | slaidoubleflat |  | -215.306 | U+E3EB<br>accSagittalDoubleFlat143CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat11v49CUp.svg" alt="~Y)" data-size="line"> | `~Y)` |  | shaidoubleflat |  | -209.794 | U+E3E9<br>accSagittalDoubleFlat11v49CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat19CUp.svg" alt="(Y" data-size="line"> | `(Y` |  | razaidoubleflat |  | -207.288 | U+E3E7<br>accSagittalDoubleFlat19CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat7v19CUp.svg" alt=")\Y" data-size="line"> | `)\Y` |  | rataidoubleflat |  | -196.728 | U+E3E5<br>accSagittalDoubleFlat7v19CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat49SUp.svg" alt="~~Y" data-size="line"> | `~~Y` |  | sataidoubleflat |  | -191.673 | U+E3E3<br>accSagittalDoubleFlat49SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat23SUp.svg" alt=")~Y" data-size="line"> | `)~Y` |  | sakaidoubleflat |  | -187.366 | U+E3E1<br>accSagittalDoubleFlat23SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp23SDown.svg" alt=")~X" data-size="line"> | `)~X` |  | sakaodoublesharp |  | 187.366 | U+E3E0<br>accSagittalDoubleSharp23SDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp49SDown.svg" alt="~~X" data-size="line"> | `~~X` |  | sataodoublesharp |  | 191.673 | U+E3E2<br>accSagittalDoubleSharp49SDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp7v19CDown.svg" alt=")/X" data-size="line"> | `)/X` |  | rataodoublesharp |  | 196.728 | U+E3E4<br>accSagittalDoubleSharp7v19CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp19CDown.svg" alt="(X" data-size="line"> | `(X` |  | razaodoublesharp |  | 207.288 | U+E3E6<br>accSagittalDoubleSharp19CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp11v49CDown.svg" alt="~X)" data-size="line"> | `~X)` |  | shaodoublesharp |  | 209.794 | U+E3E8<br>accSagittalDoubleSharp11v49CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp143CDown.svg" alt="~X\" data-size="line"> | `~X\` |  | slaodoublesharp |  | 215.306 | U+E3EA<br>accSagittalDoubleSharp143CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp17kDown.svg" alt=")//X" data-size="line"> | `)//X` | `sx` | saodoublesharp |  | 218.640 | U+E3EC<br>accSagittalDoubleSharp17kDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp19sDown.svg" alt="(X~" data-size="line"> | `(X~` | `;x` | raodoublesharp |  | 223.992 | U+E3EE<br>accSagittalDoubleSharp19sDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat23CUp.svg" alt="\!!~" data-size="line"> | `\!!~` | `~b` | zaiflat |  | -97.141 | U+E37B<br>accSagittalFlat23CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat5v19CUp.svg" alt=")!!)" data-size="line"> | `)!!)` |  | praiflat |  | -88.801 | U+E379<br>accSagittalFlat5v19CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat5v23SUp.svg" alt="!!~" data-size="line"> | `!!~` |  | pazaiflat |  | -75.634 | U+E377<br>accSagittalFlat5v23SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp5v23SDown.svg" alt="&#124;&#124;~" data-size="line"> | `||~` |  | pazaosharp |  | 75.634 | U+E376<br>accSagittalSharp5v23SDown | `/|~` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp5v19CDown.svg" alt=")&#124;&#124;)" data-size="line"> | `)||)` |  | praosharp |  | 88.801 | U+E378<br>accSagittalSharp5v19CDown | `)/|` |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp23CDown.svg" alt="/&#124;&#124;~" data-size="line"> | `/||~` | `z#` | zaosharp |  | 97.141 | U+E37A<br>accSagittalSharp23CDown | `|~` |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat5v23SDown.svg" alt="\!!!~" data-size="line"> | `\!!!~` |  | pazaoflat |  | -151.736 | U+E381<br>accSagittalFlat5v23SDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat5v19CDown.svg" alt=")\!!!" data-size="line"> | `)\!!!` |  | praoflat |  | -138.569 | U+E37F<br>accSagittalFlat5v19CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalFlat23CDown.svg" alt="!!!~" data-size="line"> | `!!!~` | `zb` | zaoflat |  | -130.229 | U+E37D<br>accSagittalFlat23CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp23CUp.svg" alt="&#124;&#124;&#124;~" data-size="line"> | `|||~` | `~#` | zaisharp |  | 130.229 | U+E37C<br>accSagittalSharp23CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp5v19CUp.svg" alt=")/&#124;&#124;&#124;" data-size="line"> | `)/|||` |  | praisharp |  | 138.569 | U+E37E<br>accSagittalSharp5v19CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalSharp5v23SUp.svg" alt="/&#124;&#124;&#124;~" data-size="line"> | `/|||~` |  | pazaisharp |  | 151.736 | U+E380<br>accSagittalSharp5v23SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat23CUp.svg" alt="\Y~" data-size="line"> | `\Y~` | `~bb` | zaidoubleflat |  | -210.826 | U+E387<br>accSagittalDoubleFlat23CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat5v19CUp.svg" alt=")Y)" data-size="line"> | `)Y)` |  | praidoubleflat |  | -202.486 | U+E385<br>accSagittalDoubleFlat5v19CUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleFlat5v23SUp.svg" alt="Y~" data-size="line"> | `Y~` |  | pazaidoubleflat |  | -189.319 | U+E383<br>accSagittalDoubleFlat5v23SUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp5v23SDown.svg" alt="X~" data-size="line"> | `X~` |  | pazaodoublesharp |  | 189.319 | U+E382<br>accSagittalDoubleSharp5v23SDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp5v19CDown.svg" alt=")X)" data-size="line"> | `)X)` |  | praodoublesharp |  | 202.486 | U+E384<br>accSagittalDoubleSharp5v19CDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalDoubleSharp23CDown.svg" alt="/X~" data-size="line"> | `/X~` | `zx` | zaodoublesharp |  | 210.826 | U+E386<br>accSagittalDoubleSharp23CDown |  |

## Sagittal-compatible and other

Conventional and Wilson-extension accidentals usable alongside sagittals.

| Glyph | Long | Short | Sagispeak | Primary comma | ¢ | SMuFL | Apotome complement |
|---|---|---|---|---|---|---|---|
| <img src="../.gitbook/assets/glyphs/accidentalDoubleFlat.svg" alt="doubleflat" data-size="line"> |  |  | doubleflat |  | -227.370 | U+E264<br>accidentalDoubleFlat |  |
| <img src="../.gitbook/assets/glyphs/accidentalNarrowReversedFlatAndFlat.svg" alt="accidentalNarrowReversedFlatAndFlat" data-size="line"> |  |  |  |  | -166.958 | U+E285<br>accidentalNarrowReversedFlatAndFlat |  |
| <img src="../.gitbook/assets/glyphs/accidentalFlat.svg" alt="flat" data-size="line"> |  |  | flat |  | -113.685 | U+E260<br>accidentalFlat |  |
| <img src="../.gitbook/assets/glyphs/accidentalNarrowReversedFlat.svg" alt="accidentalNarrowReversedFlat" data-size="line"> |  |  |  |  | -53.273 | U+E284<br>accidentalNarrowReversedFlat |  |
| <img src="../.gitbook/assets/glyphs/accidentalWilsonMinus.svg" alt="accidentalWilsonMinus" data-size="line"> |  |  |  |  | -21.506 | U+E47C<br>accidentalWilsonMinus |  |
| <!-- TODO: symbol image --> | `|//|` | `h` | natural |  | 0.000 | U+F090<br>- | `/||\` |
| <img src="../.gitbook/assets/glyphs/accidentalWilsonPlus.svg" alt="accidentalWilsonPlus" data-size="line"> |  |  |  |  | 21.506 | U+E47B<br>accidentalWilsonPlus |  |
| <img src="../.gitbook/assets/glyphs/accidentalQuarterToneSharpStein.svg" alt="accidentalQuarterToneSharpStein" data-size="line"> |  |  |  |  | 53.273 | U+E282<br>accidentalQuarterToneSharpStein |  |
| <img src="../.gitbook/assets/glyphs/accidentalSharp.svg" alt="sharp" data-size="line"> |  |  | sharp |  | 113.685 | U+E262<br>accidentalSharp |  |
| <img src="../.gitbook/assets/glyphs/accidentalThreeQuarterTonesSharpStein.svg" alt="accidentalThreeQuarterTonesSharpStein" data-size="line"> |  |  |  |  | 166.958 | U+E283<br>accidentalThreeQuarterTonesSharpStein |  |
| <img src="../.gitbook/assets/glyphs/accidentalLargeDoubleSharp.svg" alt="doublesharp" data-size="line"> |  |  | doublesharp |  | 227.370 | U+E47D<br>accidentalLargeDoubleSharp |  |

## Diacritics (accents)

The schisma, mina and tina accents. Each nudges the symbol it attaches to by a tiny amount.

| Glyph | Long | Short | Sagispeak | Primary comma | ¢ | SMuFL | Apotome complement |
|---|---|---|---|---|---|---|---|
| <img src="../.gitbook/assets/glyphs/accSagittalGrave.svg" alt="." data-size="line"> | `.` | `.` | bo |  | -1.954 | U+E3F3<br>accSagittalGrave |  |
| <img src="../.gitbook/assets/glyphs/accSagittal2MinasDown.svg" alt=",," data-size="line"> | `,,` | `,,` | momo |  | -0.833 | U+E3F7<br>accSagittal2MinasDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal1MinaDown.svg" alt="," data-size="line"> | `,` | `,` | mo |  | -0.423 | U+E3F5<br>accSagittal1MinaDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittalShaftUp.svg" alt="&#124;" data-size="line"> | `|` |  | ai | 1u | 0.000 | U+E3F0<br>accSagittalShaftUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalShaftDown.svg" alt="!" data-size="line"> | `!` |  | ao | 1u | 0.000 | U+E3F1<br>accSagittalShaftDown |  |
| <img src="../.gitbook/assets/glyphs/accSagittal1MinaUp.svg" alt="&#96;" data-size="line"> | `` ` `` | `` ` `` | mi |  | 0.423 | U+E3F4<br>accSagittal1MinaUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittal2MinasUp.svg" alt="&#96;&#96;" data-size="line"> | `` `` `` | `` `` `` | mimi |  | 0.833 | U+E3F6<br>accSagittal2MinasUp |  |
| <img src="../.gitbook/assets/glyphs/accSagittalAcute.svg" alt="'" data-size="line"> | `'` | `'` | bi |  | 1.954 | U+E3F2<br>accSagittalAcute |  |

## What is deferred

- The ~577 further valid symbol combinations in `sheet/02-symbols-valid.csv` beyond this character map (and the rows past its ~404-row capture point).
- Glyph images for every row (`<!-- TODO: symbol image -->`).
- Trojan common-tone and prime-factor/12R membership columns held in `sheet/01`.
