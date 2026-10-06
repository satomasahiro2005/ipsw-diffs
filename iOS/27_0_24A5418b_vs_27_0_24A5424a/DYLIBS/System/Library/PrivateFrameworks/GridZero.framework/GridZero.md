## GridZero

> `/System/Library/PrivateFrameworks/GridZero.framework/GridZero`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x93a28` | `0x93adc` | **`+0xb4`** |
| `__AUTH_CONST.__const` | `0x31b0` | `0x31d0` | **`+0x20`** |
| `__DATA.__bss` | `0x23f8` | `0x2408` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x11a0` | `0x11a8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x7500` | `0x7508` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2a08` | `0x2a10` | **`+0x8`** |

### Other Changes

```diff

-912.0.232.0.0
+912.0.233.0.0

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 5350
-  Symbols:   7641
+  Functions: 5351
+  Symbols:   7645
Symbols:
+ GCC_except_table1496
+ GCC_except_table1516
+ GCC_except_table1609
+ GCC_except_table1650
+ GCC_except_table1735
+ GCC_except_table1768
+ GCC_except_table1943
+ GCC_except_table1947
+ GCC_except_table2239
+ GCC_except_table2436
+ GCC_except_table2454
+ GCC_except_table2459
+ GCC_except_table2500
+ GCC_except_table2502
+ GCC_except_table2506
+ GCC_except_table2508
+ GCC_except_table2517
+ GCC_except_table2632
+ GCC_except_table2651
+ GCC_except_table2663
+ GCC_except_table2669
+ GCC_except_table2671
+ GCC_except_table2775
+ GCC_except_table2979
+ GCC_except_table2993
+ GCC_except_table3063
+ GCC_except_table3140
+ GCC_except_table3186
+ _MGIsDeviceOneOfType
+ _PXPhotosContentHardwareRequiresDisableMetalViewDisplayCompositing.onceToken
+ _PXPhotosContentHardwareRequiresDisableMetalViewDisplayCompositing.requiresDisableMetalViewDisplayCompositing
+ ___PXPhotosContentHardwareRequiresDisableMetalViewDisplayCompositing_block_invoke
- GCC_except_table1495
- GCC_except_table1515
- GCC_except_table1608
- GCC_except_table1649
- GCC_except_table1734
- GCC_except_table1767
- GCC_except_table1942
- GCC_except_table1946
- GCC_except_table2238
- GCC_except_table2435
- GCC_except_table2453
- GCC_except_table2458
- GCC_except_table2499
- GCC_except_table2501
- GCC_except_table2505
- GCC_except_table2507
- GCC_except_table2516
- GCC_except_table2631
- GCC_except_table2650
- GCC_except_table2662
- GCC_except_table2668
- GCC_except_table2670
- GCC_except_table2774
- GCC_except_table2978
- GCC_except_table2992
- GCC_except_table3062
- GCC_except_table3139
- GCC_except_table3185
Functions:
~ -[PXPhotosContentController initWithConfiguration:traitCollection:gridViewFactory:] : 1780 -> 1848
+ ___PXPhotosContentHardwareRequiresDisableMetalViewDisplayCompositing_block_invoke
```
