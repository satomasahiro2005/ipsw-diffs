## PhotosPosterUI

> `/System/Library/PrivateFrameworks/PhotosPosterUI.framework/PhotosPosterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc6b58` | `0xc52f4` | **`-0x1864`** |
| `__DATA.__bss` | `0x1df0` | `0x1ae0` | **`-0x310`** |
| `__TEXT.__const` | `0x2ed8` | `0x2ce0` | **`-0x1f8`** |
| `__DATA.__data` | `0x2c28` | `0x2a38` | **`-0x1f0`** |
| `__TEXT.__eh_frame` | `0x4dc` | `0x364` | **`-0x178`** |
| `__AUTH_CONST.__const` | `0x32e0` | `0x31d0` | **`-0x110`** |
| `__TEXT.__oslogstring` | `0x4d18` | `0x4de6` | **`+0xce`** |
| `__TEXT.__unwind_info` | `0x31a8` | `0x3110` | **`-0x98`** |
| `__TEXT.__swift5_typeref` | `0x4ffc` | `0x4f6e` | **`-0x8e`** |
| `__TEXT.__swift5_capture` | `0x8dc` | `0x87c` | **`-0x60`** |
| `__AUTH.__objc_data` | `0x3128` | `0x3178` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x2d18` | `0x2cd0` | **`-0x48`** |
| `__AUTH_CONST.__cfstring` | `0x50c0` | `0x5100` | **`+0x40`** |
| `__DATA_CONST.__objc_protolist` | `0x268` | `0x228` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0xa7f4` | `0xa7b4` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1b48` | `0x1b10` | **`-0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x7468` | `0x7438` | **`-0x30`** |
| `__TEXT.__swift5_assocty` | `0x2d8` | `0x2a8` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x172c` | `0x1700` | **`-0x2c`** |
| `__DATA_CONST.__objc_protorefs` | `0x88` | `0x68` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xb48` | `0xb2c` | **`-0x1c`** |
| `__DATA_CONST.__got` | `0x1208` | `0x11f0` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0xd0` | `0xb8` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0xdc` | `0xc8` | **`-0x14`** |
| `__TEXT.__gcc_except_tab` | `0x1998` | `0x1988` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0xf21` | `0xf11` | **`-0x10`** |
| `__AUTH.__data` | `0x948` | `0x940` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xaa4` | `0xaac` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x350` | `0x358` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x270` | `0x278` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x10` | `0x8` | **`-0x8`** |
| `__TEXT.__cstring` | `0x6e7f` | `0x6e83` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xb8` | `0xb4` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x10` | `0xc` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0xc` | `0x8` | **`-0x4`** |

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0

-  - /usr/lib/libMobileGestalt.dylib

-  Functions: 5322
-  Symbols:   7190
-  CStrings:  1257
+  Functions: 5267
+  Symbols:   7163
+  CStrings:  1260
Symbols:
+ -[PUParallaxImageLayerContentView _shouldAnimatePropertyWithKey:]
+ -[PUParallaxImageLayerView blurLayer]
+ -[PUParallaxLayerLayoutInfo viewBoundsSize]
+ -[PUParallaxLayerView blurLayer]
+ -[PUPosterGlobalEditProperties initWithEditViewModel:]
+ -[PUPosterGlobalEditProperties initWithStyle:spatialPhotoEnabled:settlingEffectEnabled:depthEnabled:userAdjustedVisibleFrame:]
+ -[PUPosterGlobalEditProperties isDepthEnabled]
+ -[PUPosterGlobalEditProperties userAdjustedVisibleFrame]
+ -[PUWallpaperPosterEditorController _canAdoptBakedLayoutAtWallpaperURL:]
+ GCC_except_table1029
+ GCC_except_table1066
+ GCC_except_table1074
+ GCC_except_table1079
+ GCC_except_table1102
+ GCC_except_table1104
+ GCC_except_table1106
+ GCC_except_table1567
+ GCC_except_table1568
+ GCC_except_table1592
+ GCC_except_table1793
+ GCC_except_table1798
+ GCC_except_table1820
+ GCC_except_table1864
+ GCC_except_table1872
+ GCC_except_table1899
+ GCC_except_table1907
+ GCC_except_table1908
+ GCC_except_table1914
+ GCC_except_table1915
+ GCC_except_table1916
+ GCC_except_table1945
+ GCC_except_table1960
+ GCC_except_table1962
+ GCC_except_table1965
+ GCC_except_table1968
+ GCC_except_table1971
+ GCC_except_table1980
+ GCC_except_table2019
+ GCC_except_table2081
+ GCC_except_table2106
+ GCC_except_table2109
+ GCC_except_table2120
+ GCC_except_table2126
+ GCC_except_table2129
+ GCC_except_table2145
+ GCC_except_table2148
+ GCC_except_table2184
+ GCC_except_table2195
+ GCC_except_table2201
+ GCC_except_table2204
+ GCC_except_table2215
+ GCC_except_table2217
+ GCC_except_table2220
+ GCC_except_table2226
+ GCC_except_table2228
+ GCC_except_table2232
+ GCC_except_table2233
+ GCC_except_table2238
+ GCC_except_table2240
+ GCC_except_table2248
+ GCC_except_table2250
+ GCC_except_table2257
+ GCC_except_table2262
+ GCC_except_table2294
+ GCC_except_table2313
+ GCC_except_table2423
+ GCC_except_table2443
+ GCC_except_table2445
+ GCC_except_table2686
+ GCC_except_table2704
+ GCC_except_table3162
+ GCC_except_table3165
+ GCC_except_table3200
+ GCC_except_table3202
+ GCC_except_table3222
+ GCC_except_table3223
+ GCC_except_table3253
+ GCC_except_table3264
+ GCC_except_table3267
+ GCC_except_table3328
+ GCC_except_table3350
+ GCC_except_table3353
+ GCC_except_table3406
+ GCC_except_table3410
+ GCC_except_table3414
+ GCC_except_table890
+ GCC_except_table901
+ _CGRectIntegral
+ _OBJC_CLASS_$_PUParallaxImageLayerContentView
+ _OBJC_IVAR_$_PUPosterGlobalEditProperties._depthEnabled
+ _OBJC_IVAR_$_PUPosterGlobalEditProperties._userAdjustedVisibleFrame
+ _OBJC_METACLASS_$_PUParallaxImageLayerContentView
+ _OUTLINED_FUNCTION_74
+ _PUWallpaperCacheURLForWallpaperURL
+ __OBJC_$_INSTANCE_METHODS_PUParallaxImageLayerContentView
+ __OBJC_CLASS_RO_$_PUParallaxImageLayerContentView
+ __OBJC_METACLASS_RO_$_PUParallaxImageLayerContentView
+ ___block_descriptor_137_e8_32s40s_e29_v16?0"PUParallaxLayerView"8ls32l8s40l8
+ ___block_descriptor_72_e8_32s40bs48w_e52_v24?0"PUWallpaperPosterEditViewModel"8"NSError"16lw48l8s40l8s32l8
+ ___block_descriptor_72_e8_32s40s48s56bs64w_e42_v24?0"PISegmentationLoader"8"NSError"16ls56l8w64l8s32l8s40l8s48l8
+ ___block_descriptor_88_e8_32s40s48s56bs64w_e42_v24?0"<PISegmentationItem>"8"NSError"16lw64l8s56l8s32l8s40l8s48l8
- -[PUPosterGlobalEditProperties initWithStyle:spatialPhotoEnabled:settlingEffectEnabled:]
- -[PUWallpaperPosterEditorController(OutfillStatus) _clampOutfillRect:toSafeEdgesWithOriginalRect:]
- -[PUWallpaperPosterEditorController(OutfillStatus) _precomputeOutfillSafeEdges]
- GCC_except_table1028
- GCC_except_table1065
- GCC_except_table1073
- GCC_except_table1078
- GCC_except_table1101
- GCC_except_table1103
- GCC_except_table1105
- GCC_except_table1563
- GCC_except_table1564
- GCC_except_table1588
- GCC_except_table1789
- GCC_except_table1794
- GCC_except_table1816
- GCC_except_table1860
- GCC_except_table1868
- GCC_except_table1895
- GCC_except_table1903
- GCC_except_table1904
- GCC_except_table1910
- GCC_except_table1911
- GCC_except_table1912
- GCC_except_table1937
- GCC_except_table1952
- GCC_except_table1958
- GCC_except_table1961
- GCC_except_table1964
- GCC_except_table1967
- GCC_except_table1976
- GCC_except_table2015
- GCC_except_table2077
- GCC_except_table2102
- GCC_except_table2105
- GCC_except_table2116
- GCC_except_table2122
- GCC_except_table2125
- GCC_except_table2141
- GCC_except_table2144
- GCC_except_table2180
- GCC_except_table2191
- GCC_except_table2193
- GCC_except_table2200
- GCC_except_table2211
- GCC_except_table2213
- GCC_except_table2216
- GCC_except_table2223
- GCC_except_table2225
- GCC_except_table2229
- GCC_except_table2230
- GCC_except_table2235
- GCC_except_table2237
- GCC_except_table2241
- GCC_except_table2246
- GCC_except_table2253
- GCC_except_table2258
- GCC_except_table2290
- GCC_except_table2309
- GCC_except_table2418
- GCC_except_table2438
- GCC_except_table2440
- GCC_except_table2681
- GCC_except_table2699
- GCC_except_table3155
- GCC_except_table3158
- GCC_except_table3193
- GCC_except_table3195
- GCC_except_table3215
- GCC_except_table3216
- GCC_except_table3246
- GCC_except_table3257
- GCC_except_table3260
- GCC_except_table3321
- GCC_except_table3343
- GCC_except_table3346
- GCC_except_table3396
- GCC_except_table3399
- GCC_except_table3407
- GCC_except_table3421
- GCC_except_table889
- GCC_except_table900
- _MGIsDeviceOfType
- _OBJC_CLASS_$_NUAssetLoader
- _OBJC_CLASS_$_PIParallaxSegmentationItem
- _PUPosterShouldNormalizeBlurEdges.onceToken
- _PUPosterShouldNormalizeBlurEdges.shouldNormalizeBlurEdges
- __OBJC_$_PROP_LIST_NUAsset
- __OBJC_$_PROP_LIST_NUAssetPrivate
- __OBJC_$_PROP_LIST_NUImageAssetPrivate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_NUAsset
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_NUAssetPrivate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_NUImageAssetPrivate
- __OBJC_$_PROTOCOL_METHOD_TYPES_NUAsset
- __OBJC_$_PROTOCOL_METHOD_TYPES_NUAssetPrivate
- __OBJC_$_PROTOCOL_METHOD_TYPES_NUImageAssetPrivate
- __OBJC_$_PROTOCOL_REFS_NUAssetPrivate
- __OBJC_$_PROTOCOL_REFS_NUImageAsset
- __OBJC_$_PROTOCOL_REFS_NUImageAssetPrivate
- __OBJC_LABEL_PROTOCOL_$_NUAsset
- __OBJC_LABEL_PROTOCOL_$_NUAssetPrivate
- __OBJC_LABEL_PROTOCOL_$_NUImageAsset
- __OBJC_LABEL_PROTOCOL_$_NUImageAssetPrivate
- __OBJC_PROTOCOL_$_NUAsset
- __OBJC_PROTOCOL_$_NUAssetPrivate
- __OBJC_PROTOCOL_$_NUImageAsset
- __OBJC_PROTOCOL_$_NUImageAssetPrivate
- ___79-[PUWallpaperPosterEditorController(OutfillStatus) _precomputeOutfillSafeEdges]_block_invoke
- ___79-[PUWallpaperPosterEditorController(OutfillStatus) _precomputeOutfillSafeEdges]_block_invoke_2
- ___PUPosterShouldNormalizeBlurEdges_block_invoke
- ___block_descriptor_137_e8_32s40s_e16_v16?0"UIView"8ls32l8s40l8
- ___block_descriptor_40_e55_v16?0"<PUParallaxLayerStackMutableViewModelPrivate>"8l
- ___block_descriptor_40_e8_32w_e15_v16?0"NSSet"8lw32l8
- ___block_descriptor_80_e8_32s40bs48w_e52_v24?0"PUWallpaperPosterEditViewModel"8"NSError"16lw48l8s40l8s32l8
- ___block_descriptor_80_e8_32s40s48s56bs64w_e42_v24?0"PISegmentationLoader"8"NSError"16ls56l8w64l8s32l8s40l8s48l8
- ___block_descriptor_96_e8_32s40s48s56bs64w_e42_v24?0"<PISegmentationItem>"8"NSError"16lw64l8s56l8s32l8s40l8s48l8
- _associated conformance So13NUAssetOptionaSHSCSQ
- _associated conformance So13NUAssetOptionas20_SwiftNewtypeWrapperSCSY
- _associated conformance So13NUAssetOptionas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
- _flat unique So19NUImageAssetPrivate_p
- _swift_dynamicCastObjCProtocolConditional
- _symbolic $ss21_ObjectiveCBridgeableP
- _symbolic So5NSSetCSgIegg_
- _symbolic So5NSSetCSgIeyBy_
- _symbolic So8NSStringC
- _symbolic _____ So13NUAssetOptiona
- _symbolic ______p So19NUImageAssetPrivateP
- _type_layout_string So13NUAssetOptiona
CStrings:
+ "-%@"
+ "Contact poster resources were laid out for the lock screen, re-segmenting"
+ "Failed to load baked layer stack for contact poster, re-segmenting: %{public}@"
+ "Reloading %{public}@ to establish outfill safe edges"
+ "filters.gaussianBlur.inputBounds"
- "v16@?0@\"NSSet\"8"
- "v16@?0@\"UIView\"8"
```
