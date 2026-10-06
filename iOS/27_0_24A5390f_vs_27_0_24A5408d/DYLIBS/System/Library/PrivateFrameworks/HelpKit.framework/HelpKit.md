## HelpKit

> `/System/Library/PrivateFrameworks/HelpKit.framework/HelpKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c2c4` | `0x2c244` | **`-0x80`** |
| `__AUTH_CONST.__cfstring` | `0x2e20` | `0x2e40` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x329` | `0x336` | **`+0xd`** |
| `__DATA_CONST.__got` | `0x578` | `0x570` | **`-0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x88` | `0x90` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-206.0.0.0.0
+208.0.0.0.0

-  Symbols:   2356
-  CStrings:  466
+  Symbols:   2355
+  CStrings:  468
Symbols:
- _OBJC_CLASS_$_NSMutableOrderedSet
Functions:
~ -[HLPHelpViewController loadHelpBook] : 2816 -> 2688
CStrings:
+ "Languages %@"
+ "tvapp"
```
