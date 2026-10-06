## WebUI

> `/System/Library/PrivateFrameworks/WebUI.framework/WebUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x318` | `0x90` | **`-0x288`** |
| `__DATA_DIRTY.__objc_data` | `0x460` | `0x6e8` | **`+0x288`** |
| `__DATA_DIRTY.__data` | `—` | `0xc8` | **`+0xc8`** |
| `__AUTH.__data` | `0x250` | `0x1d8` | **`-0x78`** |
| `__TEXT.__text` | `0x33048` | `0x33094` | **`+0x4c`** |
| `__DATA.__data` | `0x688` | `0x658` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x149c` | `0x14b4` | **`+0x18`** |
| `__DATA.__bss` | `0xbf0` | `0xbe0` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x40` | `0x50` | **`+0x10`** |
| `__TEXT.__const` | `0xd30` | `0xd40` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1698` | `0x16a0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xe28` | `0xe30` | **`+0x8`** |

### Other Changes

```diff

-625.1.20.10.3
+625.1.22.10.3

-  Functions: 993
-  Symbols:   1329
+  Functions: 994
+  Symbols:   1331
Symbols:
+ +[WBUHistory importHistoryAgeLimitCutoff]
+ __OBJC_$_CLASS_METHODS_WBUHistory
Functions:
+ +[WBUHistory importHistoryAgeLimitCutoff]
```
