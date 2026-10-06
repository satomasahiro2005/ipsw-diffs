## CoreParsec

> `/System/Library/PrivateFrameworks/CoreParsec.framework/CoreParsec`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x5afe` | `0x5b21` | **`+0x23`** |
| `__AUTH_CONST.__cfstring` | `0x8120` | `0x8100` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x743` | `0x756` | **`+0x13`** |
| `__TEXT.__text` | `0xc2afc` | `0xc2b0c` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xa08` | `0xa14` | **`+0xc`** |

### Other Changes

```diff

-3600.56.26.11.2
+3605.21.1.1.1

-  CStrings:  1259
+  CStrings:  1260
Symbols:
+ _os_variant_has_internal_diagnostics
- _MGGetBoolAnswer
Functions:
~ sub_1b38a9e04 -> sub_1b4a3ce04 : 48 -> 52
~ sub_1b3942538 -> sub_1b4ad553c : 220 -> 232
CStrings:
+ "DictionarySearch"
+ "com.apple.siri.parsec.CoreParsec"
- "InternalBuild"
```
