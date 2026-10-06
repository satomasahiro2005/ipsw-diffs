## StorageKit

> `/System/Library/PrivateFrameworks/StorageKit.framework/StorageKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bc64` | `0x2bd00` | **`+0x9c`** |
| `__DATA_CONST.__objc_selrefs` | `0x1dc0` | `0x1dc8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x1390` | `0x1398` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x357c` | `0x3584` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc50` | `0xc58` | **`+0x8`** |

### Other Changes

```diff

-1075.0.0.0.0
+1076.0.0.0.0

-  Functions: 1202
-  Symbols:   2475
+  Functions: 1203
+  Symbols:   2477
Symbols:
+ +[SKError errorWithCode:underlyingError:error:]
+ -[SKDiskImage mount:params:wasAttached:outError:]
+ _swift_release_x24
- -[SKDiskImage mount:params:outError:]
```
