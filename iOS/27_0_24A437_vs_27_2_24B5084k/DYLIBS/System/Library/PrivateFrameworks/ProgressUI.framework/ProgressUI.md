## ProgressUI

> `/System/Library/PrivateFrameworks/ProgressUI.framework/ProgressUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3470` | `0x348c` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x458` | `0x460` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x434` | `0x43c` | **`+0x8`** |

### Other Changes

```diff

-2858.0.0.0.0
+2858.1.3.0.0

-  Functions: 60
-  Symbols:   284
+  Functions: 61
+  Symbols:   285
Symbols:
+ -[PUIProgressWindow _isV68VMDevice]
+ GCC_except_table21
- GCC_except_table20
Functions:
+ -[PUIProgressWindow _isV68VMDevice]
~ -[PUIProgressWindow _layoutScreen] : 2228 -> 2232
```
