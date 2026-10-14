## PhotosPosterUI

> `/System/Library/PrivateFrameworks/PhotosPosterUI.framework/PhotosPosterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc52f4` | `0xc67c8` | **`+0x14d4`** |
| `__AUTH_CONST.__objc_const` | `0x11d10` | `0x11f50` | **`+0x240`** |
| `__TEXT.__objc_methlist` | `0xa7b4` | `0xa8e4` | **`+0x130`** |
| `__TEXT.__oslogstring` | `0x4de6` | `0x4ef0` | **`+0x10a`** |
| `__AUTH.__objc_data` | `0x3178` | `0x3280` | **`+0x108`** |
| `__TEXT.__unwind_info` | `0x3110` | `0x31a0` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x7438` | `0x74c0` | **`+0x88`** |
| `__DATA.__data` | `0x2a38` | `0x2ab8` | **`+0x80`** |
| `__TEXT.__const` | `0x2ce0` | `0x2d38` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x2cd0` | `0x2d10` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x11f0` | `0x1228` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x1700` | `0x172c` | **`+0x2c`** |
| `__AUTH.__data` | `0x940` | `0x968` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0xaac` | `0xac8` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0xb2c` | `0xb48` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x1b10` | `0x1b28` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x358` | `0x368` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1988` | `0x1998` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xf11` | `0xf21` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x4f6e` | `0x4f7a` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0xb4` | `0xb8` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-916.51.202.0.0
+916.57.151.0.0

-  Functions: 5267
-  Symbols:   7163
-  CStrings:  1260
+  Functions: 5310
+  Symbols:   7211
+  CStrings:  1264
Symbols:
+ -[PUParallaxLayerStackViewModel normalizedVisibleFrameFittingContainer:]
+ -[PUWallpaperCachedLayerStack .cxx_destruct]
+ -[PUWallpaperCachedLayerStack layerStack]
+ -[PUWallpaperCachedLayerStack options]
+ -[PUWallpaperCachedLayerStack setLayerStack:]
+ -[PUWallpaperCachedLayerStack setOptions:]
+ -[PUWallpaperCachedLayerStack setSpatialScenes:]
+ -[PUWallpaperCachedLayerStack setWallpaperURL:]
+ -[PUWallpaperCachedLayerStack spatialScenes]
+ -[PUWallpaperCachedLayerStack wallpaperURL]
+ -[PUWallpaperPosterController _cacheLayerStack:forWallpaperURL:displayContext:options:]
+ -[PUWallpaperPosterController _cachedLayerStackForWallpaperURL:displayContext:options:]
+ -[PUWallpaperPosterController _containerBoundsInEnvironmentOrientation]
+ -[PUWallpaperPosterController _deviceConfigurationForDisplayContext:]
+ -[PUWallpaperPosterController _invalidateLayerStackCache]
+ -[PUWallpaperPosterController _regularLayerStackLoadingOptions]
+ -[PUWallpaperPosterController _retainSpatialSceneForCurrentDisplay]
+ -[PUWallpaperPosterController _updatePosterImageWithLayerStack:]
+ -[PUWallpaperPosterController _wantsLayerStackCache]
+ -[PUWallpaperPosterEditViewModel _normalizedVisibleFrameFittingContainer:]
+ -[PUWallpaperShuffleResourceExportOperation dynamicLayoutConfiguration]
+ -[PUWallpaperShuffleResourceExportOperation setDynamicLayoutConfiguration:]
+ GCC_except_table1038
+ GCC_except_table1076
+ GCC_except_table1084
+ GCC_except_table1096
+ GCC_except_table1119
+ GCC_except_table1121
+ GCC_except_table1123
+ GCC_except_table1167
+ GCC_except_table1450
+ GCC_except_table1451
+ GCC_except_table1587
+ GCC_except_table1588
+ GCC_except_table1612
+ GCC_except_table1812
+ GCC_except_table1817
+ GCC_except_table1839
+ GCC_except_table1883
+ GCC_except_table1891
+ GCC_except_table1918
+ GCC_except_table1926
+ GCC_except_table1927
+ GCC_except_table1933
+ GCC_except_table1934
+ GCC_except_table1935
+ GCC_except_table1964
+ GCC_except_table1975
+ GCC_except_table1979
+ GCC_except_table1981
+ GCC_except_table1984
+ GCC_except_table1987
+ GCC_except_table1990
+ GCC_except_table1999
+ GCC_except_table2038
+ GCC_except_table2100
+ GCC_except_table2125
+ GCC_except_table2128
+ GCC_except_table2139
+ GCC_except_table2164
+ GCC_except_table2167
+ GCC_except_table2203
+ GCC_except_table2214
+ GCC_except_table2216
+ GCC_except_table2223
+ GCC_except_table2234
+ GCC_except_table2236
+ GCC_except_table2239
+ GCC_except_table2245
+ GCC_except_table2247
+ GCC_except_table2251
+ GCC_except_table2252
+ GCC_except_table2256
+ GCC_except_table2258
+ GCC_except_table2266
+ GCC_except_table2268
+ GCC_except_table2275
+ GCC_except_table2280
+ GCC_except_table2312
+ GCC_except_table2331
+ GCC_except_table2442
+ GCC_except_table2462
+ GCC_except_table2464
+ GCC_except_table2705
+ GCC_except_table2723
+ GCC_except_table3182
+ GCC_except_table3185
+ GCC_except_table3224
+ GCC_except_table3244
+ GCC_except_table3245
+ GCC_except_table3275
+ GCC_except_table3286
+ GCC_except_table3289
+ GCC_except_table3372
+ GCC_except_table3375
+ GCC_except_table3425
+ GCC_except_table3428
+ GCC_except_table3432
+ GCC_except_table3436
+ _CGImageRetain
+ _OBJC_CLASS_$_PUSpatialPhotoRendererReuseAssertion
+ _OBJC_CLASS_$_PUWallpaperCachedLayerStack
+ _OBJC_IVAR_$_PUWallpaperCachedLayerStack._layerStack
+ _OBJC_IVAR_$_PUWallpaperCachedLayerStack._options
+ _OBJC_IVAR_$_PUWallpaperCachedLayerStack._spatialScenes
+ _OBJC_IVAR_$_PUWallpaperCachedLayerStack._wallpaperURL
+ _OBJC_IVAR_$_PUWallpaperPosterController._layerStacksByDisplayContext
+ _OBJC_IVAR_$_PUWallpaperPosterController._spatialRendererReuseAssertion
+ _OBJC_IVAR_$_PUWallpaperShuffleResourceExportOperation._dynamicLayoutConfiguration
+ _OBJC_METACLASS_$_PUSpatialPhotoRendererReuseAssertion
+ _OBJC_METACLASS_$_PUWallpaperCachedLayerStack
+ _PFParallaxLayerID_InactiveBackground
+ __DATA_PUSpatialPhotoRendererReuseAssertion
+ __INSTANCE_METHODS_PUSpatialPhotoRendererReuseAssertion
+ __IVARS_PUSpatialPhotoRendererReuseAssertion
+ __METACLASS_DATA_PUSpatialPhotoRendererReuseAssertion
+ __OBJC_$_INSTANCE_METHODS_PUWallpaperCachedLayerStack
+ __OBJC_$_INSTANCE_VARIABLES_PUWallpaperCachedLayerStack
+ __OBJC_$_PROP_LIST_PUWallpaperCachedLayerStack
+ __OBJC_CLASS_RO_$_PUWallpaperCachedLayerStack
+ __OBJC_METACLASS_RO_$_PUWallpaperCachedLayerStack
+ ___block_descriptor_64_e63_v24?0"<PXPosterMutablePreferences>"8"<PXPosterTransition>"16l
+ ___block_descriptor_64_e8_32s40s48s56s_e51_v24?0"PFWallpaperCompoundLayerStack"8"NSError"16ls32l8s40l8s48l8s56l8
+ ___block_descriptor_80_e63_v24?0"<PXPosterMutablePreferences>"8"<PXPosterTransition>"16l
+ ___block_descriptor_80_e8_32s40s48s56w_e51_v24?0"PFWallpaperCompoundLayerStack"8"NSError"16lw56l8s32l8s40l8s48l8
+ _symbolic _____ 14PhotosPosterUI36PUSpatialPhotoRendererReuseAssertionC
+ _symbolic _____ 22PhotosSpatialMediaCore0B5PhotoO18RealityKitRendererC14ReuseAssertionC
- GCC_except_table1029
- GCC_except_table1066
- GCC_except_table1074
- GCC_except_table1079
- GCC_except_table1102
- GCC_except_table1104
- GCC_except_table1106
- GCC_except_table1150
- GCC_except_table1430
- GCC_except_table1431
- GCC_except_table1567
- GCC_except_table1568
- GCC_except_table1592
- GCC_except_table1793
- GCC_except_table1798
- GCC_except_table1820
- GCC_except_table1864
- GCC_except_table1872
- GCC_except_table1899
- GCC_except_table1907
- GCC_except_table1908
- GCC_except_table1914
- GCC_except_table1915
- GCC_except_table1916
- GCC_except_table1941
- GCC_except_table1945
- GCC_except_table1956
- GCC_except_table1962
- GCC_except_table1965
- GCC_except_table1968
- GCC_except_table1971
- GCC_except_table1980
- GCC_except_table2019
- GCC_except_table2081
- GCC_except_table2106
- GCC_except_table2109
- GCC_except_table2120
- GCC_except_table2126
- GCC_except_table2129
- GCC_except_table2184
- GCC_except_table2195
- GCC_except_table2197
- GCC_except_table2201
- GCC_except_table2204
- GCC_except_table2215
- GCC_except_table2217
- GCC_except_table2226
- GCC_except_table2228
- GCC_except_table2232
- GCC_except_table2233
- GCC_except_table2238
- GCC_except_table2240
- GCC_except_table2244
- GCC_except_table2248
- GCC_except_table2250
- GCC_except_table2257
- GCC_except_table2294
- GCC_except_table2313
- GCC_except_table2423
- GCC_except_table2443
- GCC_except_table2445
- GCC_except_table2686
- GCC_except_table2704
- GCC_except_table3162
- GCC_except_table3165
- GCC_except_table3200
- GCC_except_table3202
- GCC_except_table3223
- GCC_except_table3253
- GCC_except_table3264
- GCC_except_table3267
- GCC_except_table3328
- GCC_except_table3353
- GCC_except_table3403
- GCC_except_table3406
- GCC_except_table3410
- GCC_except_table3414
- ___block_descriptor_56_e8_32s_e63_v24?0"<PXPosterMutablePreferences>"8"<PXPosterTransition>"16ls32l8
- ___block_descriptor_72_e8_32s40s48s56w_e51_v24?0"PFWallpaperCompoundLayerStack"8"NSError"16lw56l8s32l8s40l8s48l8
CStrings:
+ "Failed to create poster image from background layer, code: %d"
+ "Failed to fetch cold-start asset: %{public}@, reloading from wallpaper only"
+ "Failed to load regular layers, error: %{public}@"
+ "Loaded layer stack is not spatial, falling back to loading regular layers"
+ "Reusing cached layer stack for context %{public}@"
- "Failed to fetch cold-start asset: %{public}@"
```
