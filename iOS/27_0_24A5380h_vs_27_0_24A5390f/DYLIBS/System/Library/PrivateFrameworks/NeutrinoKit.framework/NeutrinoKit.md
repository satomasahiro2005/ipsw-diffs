## NeutrinoKit

> `/System/Library/PrivateFrameworks/NeutrinoKit.framework/NeutrinoKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1898c` | `0x18fa4` | **`+0x618`** |
| `__TEXT.__cstring` | `0x1224` | `0x1271` | **`+0x4d`** |
| `__AUTH_CONST.__cfstring` | `0xb20` | `0xb40` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1708` | `0x1718` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1a6c` | `0x1a74` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6d8` | `0x6e0` | **`+0x8`** |

### Other Changes

```diff

-910.27.103.0.0
+910.33.102.0.0

-  Functions: 567
-  Symbols:   1190
-  CStrings:  207
+  Functions: 568
+  Symbols:   1192
+  CStrings:  209
Symbols:
+ -[NUMediaView convertTime:toSpace:]
+ GCC_except_table252
+ GCC_except_table256
+ GCC_except_table354
+ GCC_except_table384
+ GCC_except_table386
+ GCC_except_table399
+ GCC_except_table410
+ GCC_except_table414
+ GCC_except_table417
+ GCC_except_table420
+ GCC_except_table499
+ _objc_retain_x28
- GCC_except_table251
- GCC_except_table255
- GCC_except_table353
- GCC_except_table383
- GCC_except_table385
- GCC_except_table398
- GCC_except_table409
- GCC_except_table413
- GCC_except_table416
- GCC_except_table419
- GCC_except_table498
Functions:
+ -[NUMediaView convertTime:toSpace:]
CStrings:
+ "-[NUMediaView convertTime:toSpace:]"
+ "Converting time before geometry is valid"
```
