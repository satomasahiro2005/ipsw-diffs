## SafariUsageBundle

> `/System/Library/UsageBundles/SafariUsageBundle.bundle/SafariUsageBundle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x9e0` | `0x9c0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x9aa` | `0x997` | **`-0x13`** |
| `__TEXT.__text` | `0x2d34` | `0x2d28` | **`-0xc`** |
| `__DATA_CONST.__const` | `0x3e8` | `0x3e0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.1.18.10.4
+7625.1.20.10.3

-  Symbols:   154
-  CStrings:  271
+  Symbols:   153
+  CStrings:  270
Symbols:
- _showRecentSearchesDefaultsKey
Functions:
~ sub_1e0c : 1028 -> 1024
~ sub_2cfc -> sub_2cf8 : 600 -> 596
~ sub_3820 -> sub_3818 : 340 -> 336
CStrings:
- "ShowRecentSearches"
```
