## GenerativeSearchAdapter

> `/System/Library/PrivateFrameworks/GenerativeSearchAdapter.framework/GenerativeSearchAdapter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1432f8` | `0x16ea0c` | **`+0x2b714`** |
| `__AUTH_CONST.__const` | `0x73c8` | `0xfba0` | **`+0x87d8`** |
| `__DATA.__bss` | `0x6350` | `0x78d0` | **`+0x1580`** |
| `__TEXT.__cstring` | `0x1ca1` | `0x30f1` | **`+0x1450`** |
| `__TEXT.__const` | `0x113f4` | `0x126a4` | **`+0x12b0`** |
| `__AUTH.__data` | `0x1aa0` | `0x2870` | **`+0xdd0`** |
| `__TEXT.__swift5_fieldmd` | `0x2208` | `0x2d54` | **`+0xb4c`** |
| `__TEXT.__swift5_reflstr` | `0x1987` | `0x20e7` | **`+0x760`** |
| `__TEXT.__unwind_info` | `0x4590` | `0x4c30` | **`+0x6a0`** |
| `__TEXT.__eh_frame` | `0xca4c` | `0xd0c8` | **`+0x67c`** |
| `__TEXT.__constg_swiftt` | `0x1cfc` | `0x2310` | **`+0x614`** |
| `__DATA.__common` | `0x30` | `0x601` | **`+0x5d1`** |
| `__DATA.__data` | `0x2428` | `0x28c0` | **`+0x498`** |
| `__TEXT.__swift5_typeref` | `0x372e` | `0x3b84` | **`+0x456`** |
| `__AUTH_CONST.__auth_got` | `0x20e0` | `0x22d8` | **`+0x1f8`** |
| `__AUTH_CONST.__objc_const` | `0x500` | `0x688` | **`+0x188`** |
| `__TEXT.__swift5_proto` | `0x3a0` | `0x484` | **`+0xe4`** |
| `__DATA_CONST.__got` | `0xfd8` | `0x10a8` | **`+0xd0`** |
| `__TEXT.__swift5_assocty` | `0x1a0` | `0x248` | **`+0xa8`** |
| `__TEXT.__swift5_types` | `0x298` | `0x33c` | **`+0xa4`** |
| `__AUTH.__objc_data` | `0x190` | `0x1e0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x352a0` | `0x352d8` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x560` | `0x580` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0xb10` | `0xb28` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x78` | `0x64` | **`-0x14`** |
| `__TEXT.__swift_as_entry` | `0x4c8` | `0x4dc` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x40` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x560` | `0x570` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x38` | `0x30` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x44` | `0x48` | **`+0x4`** |

### Other Changes

```diff

-53.0.0.0.0
+57.0.1.0.0

-  Functions: 6370
-  Symbols:   223
-  CStrings:  347
+  Functions: 7275
+  Symbols:   225
+  CStrings:  485
Symbols:
+ _objc_retain_x21
+ _swift_unexpectedError
CStrings:
+ "  Conversations: "
+ "(?:(?<qtyDigit>\\d+)|"
+ "(?:(?<y>\\d{2,4})年)?(?<m>\\d{1,2})月(?<d>\\d{1,2})(?:日|号)?"
+ "(?:[,\\s]+\\d{2,4})?"
+ "(?:[,\\s]+\\d{2,4})?)\\b"
+ "(?:^|\\s)(\\d{1,2})(?:st|nd|rd|th|º|ª|°)?\\s*$"
+ "(?<![0-9:])(?<h>\\d{1,2})(?::(?<m>\\d{1,2}))?(?::(?<s>\\d{1,2}))?\\s*(?<mer>"
+ "(?<![0-9])(?<a>\\d{1,4})"
+ "(?<![0-9])(?<y>\\d{4})(?![0-9])"
+ "(?<![0-9])(?<y>\\d{4})[-/](?<m>\\d{1,2})[-/](?<d>\\d{1,2})(?![0-9])"
+ "(?<![0-9])(?<yy>\\d{4})[-/](?<mm>\\d{1,2})(?![0-9/-])"
+ "(?<![A-Za-z0-9:])(?<l>\\d{1,2})\\s*"
+ "(?<![A-Za-z])(?<h>\\d{1,2}):(?<m>\\d{1,2})(?::(?<s>\\d{1,2}))?(?![A-Za-z])"
+ "(?<![A-Za-z])(?<l>\\d{1,2}(?::\\d{1,2})?(?::\\d{1,2})?\\s*(?:"
+ "(?<![A-Za-z])(?<l>\\d{1,2}:\\d{1,2}(?::\\d{1,2})?)\\s*"
+ "(?<![A-Za-z])(?<l>\\d{1,2}:\\d{1,2})\\s*"
+ "(?<![A-Za-z])(?<qty>\\d+)(?<unit>"
+ "(?<b>\\d{1,2})(?:"
+ "(?<c>\\d{1,4}))?(?![0-9])"
+ "(?<dir>前|后|之前|之后|以前|以后)?"
+ "(?<h>[0-9零〇一二两三四五六七八九十]+)(?:点|时)(?:(?<m>[0-9零〇一二两三四五六七八九十]+)分?|(?<half>半))?(?:(?<s>[0-9零〇一二两三四五六七八九十]+)秒)?"
+ "(?<qty>[0-9]+|[零〇一二两三四五六七八九十百千万亿]{1,12})(?<unit>"
+ "(?<year2>\\d{2,4}))?\\b"
+ "(?<year>\\d{2,4}))?\\b"
+ ")(?:个)?(?<unit>"
+ ")?(?:个)?(?<wd>"
+ ")\\b(?:\\s+(?<modTrail>"
+ ")\\s+(?<dir>after|before)\\s+(?<anchor>"
+ ")\\s+(?<yearY>\\d{4})\\b"
+ ",\\s*(?<y>\\d{2,4})\\s*$"
+ "GenerativeSearchAdapter/RegexCache.swift"
+ "GenerativeSearchAdapter/Suggester.swift"
+ "NineteenSeventy: invalid regex "
+ "\\s(?<y>\\d{4})\\s*$"
+ "\\s*(?<r>\\d{1,2}(?::\\d{1,2})?(?::\\d{1,2})?\\s*(?:"
+ "\\s*(?<r>\\d{1,2}(?::\\d{1,2})?\\s*(?:"
+ "\\s*(?<r>\\d{1,2}:\\d{1,2}(?::\\d{1,2})?)(?![A-Za-z])"
+ "^[0-9零〇一二两三四五六七八九十]+\\s*(?:点|时|:)"
+ "achtundzwanzigste"
+ "achtundzwanzigsten"
+ "achtundzwanzigster"
+ "achtundzwanzigstes"
+ "am|dem|der|im|in|den|zum"
+ "am|pm|a\\.m\\.|p\\.m\\."
+ "de_DE"
+ "dreiundzwanzigste"
+ "dreiundzwanzigsten"
+ "dreiundzwanzigster"
+ "dreiundzwanzigstes"
+ "décembre|decembre"
+ "einunddreissigste"
+ "einunddreissigsten"
+ "einunddreissigster"
+ "einunddreissigstes"
+ "einunddreißigste"
+ "einunddreißigsten"
+ "einunddreißigster"
+ "einunddreißigstes"
+ "einundzwanzigste"
+ "einundzwanzigsten"
+ "einundzwanzigster"
+ "einundzwanzigstes"
+ "el|la|los|las|de|del|en|al"
+ "en este instante"
+ "en_US"
+ "fr_FR"
+ "fuenfundzwanzigste"
+ "fuenfundzwanzigsten"
+ "fuenfundzwanzigster"
+ "fuenfundzwanzigstes"
+ "février|fevrier"
+ "fünfundzwanzigste"
+ "fünfundzwanzigsten"
+ "fünfundzwanzigster"
+ "fünfundzwanzigstes"
+ "ième|ieme|ème|eme|ère|ere|nde|er"
+ "miércoles|miercoles"
+ "neunundzwanzigste"
+ "neunundzwanzigsten"
+ "neunundzwanzigster"
+ "neunundzwanzigstes"
+ "query too short for date suggestions"
+ "samstag|sonnabend"
+ "sechsundzwanzigste"
+ "sechsundzwanzigsten"
+ "sechsundzwanzigster"
+ "sechsundzwanzigstes"
+ "siebenundzwanzigste"
+ "siebenundzwanzigsten"
+ "siebenundzwanzigster"
+ "siebenundzwanzigstes"
+ "trente et unieme"
+ "trente et unième"
+ "trente-et-unieme"
+ "trente-et-unième"
+ "trigesimo primer"
+ "trigesimo primero"
+ "trigésimo primer"
+ "trigésimo primero"
+ "vierundzwanzigste"
+ "vierundzwanzigsten"
+ "vierundzwanzigster"
+ "vierundzwanzigstes"
+ "vigesimo primero"
+ "vigesimo segundo"
+ "vigesimo septimo"
+ "vigesimo tercero"
+ "vigésimo cuarto"
+ "vigésimo noveno"
+ "vigésimo octavo"
+ "vigésimo primer"
+ "vigésimo primero"
+ "vigésimo quinto"
+ "vigésimo segundo"
+ "vigésimo séptimo"
+ "vigésimo tercer"
+ "vigésimo tercero"
+ "vingt cinquième"
+ "vingt et unième"
+ "vingt quatrième"
+ "vingt troisième"
+ "vingt-cinquième"
+ "vingt-et-unième"
+ "vingt-quatrième"
+ "vingt-troisième"
+ "zh_Hans"
+ "zweiundzwanzigste"
+ "zweiundzwanzigsten"
+ "zweiundzwanzigster"
+ "zweiundzwanzigstes"
+ "à|a|le|la|du|de"
+ "星期一|周一|礼拜一|星期1|周1|礼拜1"
+ "星期三|周三|礼拜三|星期3|周3|礼拜3"
+ "星期二|周二|礼拜二|星期2|周2|礼拜2"
+ "星期五|周五|礼拜五|星期5|周5|礼拜5"
+ "星期六|周六|礼拜六|星期6|周6|礼拜6"
+ "星期四|周四|礼拜四|星期4|周4|礼拜4"
+ "星期日|星期天|周日|周天|礼拜日|礼拜天"
```
