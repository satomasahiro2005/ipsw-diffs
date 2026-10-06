## GridZero

> `/System/Library/PrivateFrameworks/GridZero.framework/GridZero`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x934a0` | `0x93a28` | **`+0x588`** |
| `__AUTH_CONST.__objc_const` | `0x189c8` | `0x18b20` | **`+0x158`** |
| `__TEXT.__objc_methlist` | `0xced8` | `0xcfc8` | **`+0xf0`** |
| `__DATA_CONST.__objc_selrefs` | `0x7488` | `0x7500` | **`+0x78`** |
| `__AUTH.__objc_data` | `0x2160` | `0x21d0` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0x3160` | `0x31b0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x29d8` | `0x2a08` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x188a` | `0x18ae` | **`+0x24`** |
| `__AUTH.__data` | `0xc50` | `0xc70` | **`+0x20`** |
| `__DATA.__data` | `0x3198` | `0x31b8` | **`+0x20`** |
| `__TEXT.__const` | `0x3058` | `0x3078` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x1864` | `0x1884` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x10d0` | `0x10ec` | **`+0x1c`** |
| `__DATA.__objc_ivar` | `0x14a4` | `0x14b8` | **`+0x14`** |
| `__TEXT.__swift5_builtin` | `0x230` | `0x244` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x494` | `0x4a8` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x1190` | `0x11a0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xb70` | `0xb78` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x2e8` | `0x2f0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x148` | `0x14c` | **`+0x4`** |
| `__TEXT.__cstring` | `0x549e` | `0x549f` | **`+0x1`** |

### Other Changes

```diff

-910.33.102.0.0
+912.0.111.0.0

-  Functions: 5324
-  Symbols:   7616
+  Functions: 5350
+  Symbols:   7641
Symbols:
+ -[PXPhotosViewConfiguration canBlockMainThreadIfNeeded]
+ -[PXPhotosViewConfiguration initialContentExpectation]
+ -[PXPhotosViewConfiguration setCanBlockMainThreadIfNeeded:]
+ -[PXPhotosViewConfiguration setInitialContentExpectation:]
+ -[PXPhotosViewModel actions]
+ -[PXPhotosViewModel hasOpaqueBars]
+ -[PXPhotosViewModel initialContentExpectation]
+ -[PXPhotosViewModel setHasOpaqueBars:]
+ -[PXZoomablePhotosLayout _invalidateEffectiveOverlayInsetsForAnchoringChange]
+ -[PXZoomablePhotosLayout sublayout:didAddAnchor:]
+ -[PXZoomablePhotosLayout sublayout:didRemoveAnchor:]
+ GCC_except_table1089
+ GCC_except_table1122
+ GCC_except_table1143
+ GCC_except_table1239
+ GCC_except_table1293
+ GCC_except_table1334
+ GCC_except_table1383
+ GCC_except_table1495
+ GCC_except_table1515
+ GCC_except_table1608
+ GCC_except_table1649
+ GCC_except_table1734
+ GCC_except_table1767
+ GCC_except_table1946
+ GCC_except_table2238
+ GCC_except_table2435
+ GCC_except_table2453
+ GCC_except_table2458
+ GCC_except_table2499
+ GCC_except_table2505
+ GCC_except_table2507
+ GCC_except_table2516
+ GCC_except_table2631
+ GCC_except_table2650
+ GCC_except_table2662
+ GCC_except_table2668
+ GCC_except_table2670
+ GCC_except_table2774
+ GCC_except_table2978
+ GCC_except_table2992
+ GCC_except_table3062
+ GCC_except_table3139
+ GCC_except_table3185
+ _OBJC_CLASS_$_PXPhotosViewActionModel
+ _OBJC_IVAR_$_PXPhotosViewConfiguration._canBlockMainThreadIfNeeded
+ _OBJC_IVAR_$_PXPhotosViewConfiguration._initialContentExpectation
+ _OBJC_IVAR_$_PXPhotosViewModel._actions
+ _OBJC_IVAR_$_PXPhotosViewModel._hasOpaqueBars
+ _OBJC_IVAR_$_PXPhotosViewModel._initialContentExpectation
+ _OBJC_METACLASS_$_PXPhotosViewActionModel
+ _PFIsPhotosAppAnyPlatform
+ __DATA_PXPhotosViewActionModel
+ __INSTANCE_METHODS_PXPhotosViewActionModel
+ __METACLASS_DATA_PXPhotosViewActionModel
+ ___77-[PXZoomablePhotosLayout _invalidateEffectiveOverlayInsetsForAnchoringChange]_block_invoke
+ _symbolic So23PXPhotosViewActionModelC
+ _symbolic _____ So30PXPhotosViewActionModelChangedV
- GCC_except_table1086
- GCC_except_table1118
- GCC_except_table1139
- GCC_except_table1235
- GCC_except_table1289
- GCC_except_table1330
- GCC_except_table1379
- GCC_except_table1491
- GCC_except_table1511
- GCC_except_table1604
- GCC_except_table1645
- GCC_except_table1730
- GCC_except_table1763
- GCC_except_table1938
- GCC_except_table2234
- GCC_except_table2431
- GCC_except_table2449
- GCC_except_table2454
- GCC_except_table2495
- GCC_except_table2497
- GCC_except_table2503
- GCC_except_table2512
- GCC_except_table2627
- GCC_except_table2646
- GCC_except_table2658
- GCC_except_table2664
- GCC_except_table2666
- GCC_except_table2770
- GCC_except_table2974
- GCC_except_table2988
- GCC_except_table3058
- GCC_except_table3135
- GCC_except_table3181
CStrings:
+ "\xe1\xf0r"
+ "\xf0\xf0\xf0\xd2\xf0\xf0\xf0\xf1Q"
- "\xd1\xf0r"
- "\xf0\xf0\xf0\xb2\xf0\xf0\xf0\xf1Q"
```
