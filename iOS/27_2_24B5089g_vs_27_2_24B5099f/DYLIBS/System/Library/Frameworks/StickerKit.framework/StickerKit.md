## StickerKit

> `/System/Library/Frameworks/StickerKit.framework/StickerKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x257dac` | `0x258c3c` | **`+0xe90`** |
| `__DATA.__data` | `0x7260` | `0x72f0` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x5fff` | `0x603f` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0xdfd8` | `0xe010` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x2da50` | `0x2da70` | **`+0x20`** |
| `__AUTH.__data` | `0x72d0` | `0x72e0` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x1cc0` | `0x1cb0` | **`-0x10`** |
| `__TEXT.__const` | `0x13b04` | `0x13b14` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xe2ea` | `0xe2f8` | **`+0xe`** |
| `__TEXT.__swift5_fieldmd` | `0x6728` | `0x6734` | **`+0xc`** |
| `__DATA_DIRTY.__objc_data` | `0x2130` | `0x2138` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xb64c` | `0xb654` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x7d38` | `0x7d40` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x83c0` | `0x83c8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-150.0.0.0.0
+152.1.2.0.0

-  Functions: 11222
-  Symbols:   5021
-  CStrings:  975
+  Functions: 11224
+  Symbols:   5022
+  CStrings:  976
Symbols:
+ ___swift_closure_destructor.282Tm
+ ___swift_closure_destructor.301Tm
+ ___swift_closure_destructor.399Tm
+ ___swift_closure_destructor.403Tm
+ ___swift_closure_destructor.411Tm
+ ___swift_closure_destructor.489Tm
+ _symbolic _____y_____G s11_SetStorageC 8Stickers7StickerC
- ___swift_closure_destructor.281Tm
- ___swift_closure_destructor.300Tm
- ___swift_closure_destructor.398Tm
- ___swift_closure_destructor.402Tm
- ___swift_closure_destructor.410Tm
- ___swift_closure_destructor.488Tm
CStrings:
+ "Dropped %ld duplicate %{public}s sticker(s) from the library"
```
