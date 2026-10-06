## Cinematic

> `/System/Library/Frameworks/Cinematic.framework/Cinematic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21064` | `0x2103c` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xfd0` | `0xfc0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x470` | `0x468` | **`-0x8`** |

### Other Changes

```diff

-560.40.3.0.0
+560.40.5.0.0

-  Symbols:   1244
+  Symbols:   1243
Symbols:
- _OBJC_CLASS_$_PTCinematographyScriptOptions
Functions:
~ +[CNScript loadFromAsset:changes:progress:completionHandler:] : 468 -> 428
```
