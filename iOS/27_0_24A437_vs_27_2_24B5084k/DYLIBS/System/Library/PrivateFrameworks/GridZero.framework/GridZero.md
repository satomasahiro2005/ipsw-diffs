## GridZero

> `/System/Library/PrivateFrameworks/GridZero.framework/GridZero`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x93aec` | `0x9456c` | **`+0xa80`** |
| `__AUTH_CONST.__objc_const` | `0x18b20` | `0x18d18` | **`+0x1f8`** |
| `__TEXT.__objc_methlist` | `0xcfc8` | `0xd0c8` | **`+0x100`** |
| `__DATA_CONST.__objc_selrefs` | `0x7508` | `0x75a0` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x1884` | `0x18e4` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x2a10` | `0x2a68` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x21d0` | `0x2220` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x23f0` | `0x2438` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x26e0` | `0x2720` | **`+0x40`** |
| `__TEXT.__cstring` | `0x549f` | `0x54dd` | **`+0x3e`** |
| `__TEXT.__swift5_reflstr` | `0x10c8` | `0x10f8` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x31d0` | `0x31f0` | **`+0x20`** |
| `__TEXT.__const` | `0x3078` | `0x3098` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x138` | `0x120` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x14b8` | `0x14cc` | **`+0x14`** |
| `__TEXT.__swift5_builtin` | `0x244` | `0x258` | **`+0x14`** |
| `__DATA.__data` | `0x31b8` | `0x31c8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x10ec` | `0x10f8` | **`+0xc`** |
| `__DATA_CONST.__objc_arraydata` | `0x210` | `0x208` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x2f0` | `0x2f8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x18ae` | `0x18b4` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x14c` | `0x150` | **`+0x4`** |

### Other Changes

```diff

-912.0.235.0.0
+916.40.110.0.0

-  Functions: 5352
-  Symbols:   7645
-  CStrings:  664
+  Functions: 5403
+  Symbols:   7677
+  CStrings:  666
Symbols:
+ -[PXAssetsSectionLayout customMediaProviderForDisplayAssetsInLayout:]
+ -[PXAssetsSectionLayout overrideMediaProvider]
+ -[PXAssetsSectionLayout setOverrideMediaProvider:]
+ -[PXPhotosGridAssetDecorationSource _updateTopLeadingCornerDecorations]
+ -[PXPhotosGridAssetDecorationSource additionalActiveDecorations]
+ -[PXPhotosGridAssetDecorationSource focusRingThicknessInLayout:]
+ -[PXPhotosGridAssetDecorationSource setAdditionalActiveDecorations:]
+ -[PXPhotosGridAssetDecorationSource setWantsLivePhotoBadges:]
+ -[PXPhotosGridAssetDecorationSource updateActiveDecorationsInDecoratingLayout:]
+ -[PXPhotosGridAssetDecorationSource wantsLivePhotoBadges]
+ -[PXPhotosGridAssetDecorationSource wantsTopLeadingCornerDecorations]
+ -[PXPhotosViewBannerControllerRegistration .cxx_destruct]
+ -[PXPhotosViewBannerControllerRegistration initWithPosition:provider:]
+ -[PXPhotosViewBannerControllerRegistration position]
+ -[PXPhotosViewBannerControllerRegistration provider]
+ -[PXPhotosViewConfiguration bannerControllerRegistrations]
+ -[PXPhotosViewConfiguration noThumbnailPlaceholderConfiguration]
+ -[PXPhotosViewConfiguration setBannerControllerRegistrations:]
+ -[PXPhotosViewConfiguration setNoThumbnailPlaceholderConfiguration:]
+ -[PXPhotosViewModel bannerControllerRegistrations]
+ -[PXZoomablePhotosLayout _updateAdditionalDecorationsInLayers]
+ GCC_except_table1092
+ GCC_except_table1125
+ GCC_except_table1146
+ GCC_except_table1242
+ GCC_except_table1296
+ GCC_except_table1337
+ GCC_except_table1386
+ GCC_except_table146
+ GCC_except_table1499
+ GCC_except_table1519
+ GCC_except_table1612
+ GCC_except_table1653
+ GCC_except_table1738
+ GCC_except_table1771
+ GCC_except_table1946
+ GCC_except_table1950
+ GCC_except_table2243
+ GCC_except_table2447
+ GCC_except_table2465
+ GCC_except_table2470
+ GCC_except_table2511
+ GCC_except_table2513
+ GCC_except_table2519
+ GCC_except_table2528
+ GCC_except_table2643
+ GCC_except_table2662
+ GCC_except_table2674
+ GCC_except_table2680
+ GCC_except_table2682
+ GCC_except_table2786
+ GCC_except_table2990
+ GCC_except_table3004
+ GCC_except_table3074
+ GCC_except_table3150
+ GCC_except_table3196
+ GCC_except_table595
+ GCC_except_table627
+ GCC_except_table83
+ _OBJC_CLASS_$_PXPhotosViewBannerControllerRegistration
+ _OBJC_IVAR_$_PXAssetsSectionLayout._overrideMediaProvider
+ _OBJC_IVAR_$_PXPhotosGridAssetDecorationSource._additionalActiveDecorations
+ _OBJC_IVAR_$_PXPhotosGridAssetDecorationSource._wantsLivePhotoBadges
+ _OBJC_IVAR_$_PXPhotosViewBannerControllerRegistration._position
+ _OBJC_IVAR_$_PXPhotosViewBannerControllerRegistration._provider
+ _OBJC_IVAR_$_PXPhotosViewConfiguration._bannerControllerRegistrations
+ _OBJC_IVAR_$_PXPhotosViewConfiguration._noThumbnailPlaceholderConfiguration
+ _OBJC_IVAR_$_PXPhotosViewModel._bannerControllerRegistrations
+ _OBJC_METACLASS_$_PXPhotosViewBannerControllerRegistration
+ _PXPhotosViewBannerPositionTitle
+ _PXPhotosViewBannerPositionTop
+ __OBJC_$_INSTANCE_METHODS_PXPhotosViewBannerControllerRegistration
+ __OBJC_$_INSTANCE_VARIABLES_PXPhotosViewBannerControllerRegistration
+ __OBJC_$_PROP_LIST_PXPhotosViewBannerControllerRegistration
+ __OBJC_CLASS_RO_$_PXPhotosViewBannerControllerRegistration
+ __OBJC_METACLASS_RO_$_PXPhotosViewBannerControllerRegistration
+ ___39-[PXZoomablePhotosLayout _updateLayers]_block_invoke_3
+ _symbolic _____ So27PXGSelectionDecorationStyleV
- -[PXPhotosViewConfiguration bannerControllerProvider]
- -[PXPhotosViewConfiguration setBannerControllerProvider:]
- -[PXPhotosViewModel bannerControllerProvider]
- -[PXZoomablePhotosLayout _wantsTopLeadingCornerDecoration]
- -[PXZoomablePhotosLayout addDecorationsToAllLayers:]
- GCC_except_table1089
- GCC_except_table1122
- GCC_except_table1143
- GCC_except_table1239
- GCC_except_table1293
- GCC_except_table1334
- GCC_except_table1383
- GCC_except_table143
- GCC_except_table1496
- GCC_except_table1516
- GCC_except_table1609
- GCC_except_table1650
- GCC_except_table1735
- GCC_except_table1768
- GCC_except_table1943
- GCC_except_table1947
- GCC_except_table2239
- GCC_except_table2436
- GCC_except_table2454
- GCC_except_table2459
- GCC_except_table2500
- GCC_except_table2502
- GCC_except_table2506
- GCC_except_table2508
- GCC_except_table2632
- GCC_except_table2651
- GCC_except_table2663
- GCC_except_table2669
- GCC_except_table2671
- GCC_except_table2775
- GCC_except_table2979
- GCC_except_table2993
- GCC_except_table3063
- GCC_except_table3140
- GCC_except_table3186
- GCC_except_table592
- GCC_except_table624
- GCC_except_table81
- _OBJC_IVAR_$_PXPhotosViewConfiguration._bannerControllerProvider
- _OBJC_IVAR_$_PXPhotosViewModel._bannerControllerProvider
- _OBJC_IVAR_$_PXZoomablePhotosLayout._layersHaveTopLeadingCornerDecoration
CStrings:
+ "PXPhotosViewBannerPositionTitle"
+ "PXPhotosViewBannerPositionTop"
```
