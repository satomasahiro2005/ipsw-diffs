## PhotosPosterUI

> `/System/Library/PrivateFrameworks/PhotosPosterUI.framework/PhotosPosterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc4190` | `0xc4834` | **`+0x6a4`** |
| `__TEXT.__oslogstring` | `0x48cc` | `0x4934` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x11840` | `0x11898` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x30f0` | `0x3138` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0xa4ec` | `0xa52c` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x18f0` | `0x1928` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x2c78` | `0x2ca0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x7280` | `0x72a8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x3368` | `0x3388` | **`+0x20`** |
| `__TEXT.__const` | `0x2ef0` | `0x2ee0` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0xa78` | `0xa7c` | **`+0x4`** |
| `__TEXT.__cstring` | `0x6e76` | `0x6e73` | **`-0x3`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Functions: 5290
-  Symbols:   7062
-  CStrings:  1239
+  Functions: 5301
+  Symbols:   7075
+  CStrings:  1240
Symbols:
+ -[PUParallaxLayerStackViewModelUpdater savedLayoutUsesHeadroom]
+ -[PUParallaxLayerStackViewModelUpdater setSavedLayoutUsesHeadroom:]
+ -[PUWallpaperPosterEditorController _animateVisibleFrameToLayout:]
+ -[PUWallpaperPosterEditorController _restoreHeadroomAndAwaitMainRenderForOutfillCancelWithCompletion:]
+ GCC_except_table1848
+ GCC_except_table1857
+ GCC_except_table1865
+ GCC_except_table1890
+ GCC_except_table1893
+ GCC_except_table1904
+ GCC_except_table1908
+ GCC_except_table1910
+ GCC_except_table1913
+ GCC_except_table1916
+ GCC_except_table1919
+ GCC_except_table1928
+ GCC_except_table1967
+ GCC_except_table2029
+ GCC_except_table2054
+ GCC_except_table2057
+ GCC_except_table2068
+ GCC_except_table2074
+ GCC_except_table2077
+ GCC_except_table2093
+ GCC_except_table2096
+ GCC_except_table2132
+ GCC_except_table2145
+ GCC_except_table2148
+ GCC_except_table2151
+ GCC_except_table2161
+ GCC_except_table2163
+ GCC_except_table2166
+ GCC_except_table2174
+ GCC_except_table2178
+ GCC_except_table2184
+ GCC_except_table2186
+ GCC_except_table2189
+ GCC_except_table2192
+ GCC_except_table2201
+ GCC_except_table2206
+ GCC_except_table2237
+ GCC_except_table2254
+ GCC_except_table2363
+ GCC_except_table2383
+ GCC_except_table2385
+ GCC_except_table2622
+ GCC_except_table2640
+ GCC_except_table3088
+ GCC_except_table3091
+ GCC_except_table3126
+ GCC_except_table3128
+ GCC_except_table3148
+ GCC_except_table3149
+ GCC_except_table3179
+ GCC_except_table3190
+ GCC_except_table3193
+ GCC_except_table3254
+ GCC_except_table3276
+ GCC_except_table3279
+ GCC_except_table3321
+ GCC_except_table3324
+ GCC_except_table3328
+ GCC_except_table3331
+ GCC_except_table3345
+ _OBJC_IVAR_$_PUParallaxLayerStackViewModelUpdater._savedLayoutUsesHeadroom
+ _OUTLINED_FUNCTION_75
+ ___102-[PUWallpaperPosterEditorController _restoreHeadroomAndAwaitMainRenderForOutfillCancelWithCompletion:]_block_invoke
+ ___102-[PUWallpaperPosterEditorController _restoreHeadroomAndAwaitMainRenderForOutfillCancelWithCompletion:]_block_invoke_2
+ ___66-[PUWallpaperPosterEditorController _animateVisibleFrameToLayout:]_block_invoke
+ ___66-[PUWallpaperPosterEditorController _enterOutfillMode:completion:]_block_invoke_3
+ ___block_descriptor_41_e8_32bs_e5_v8?0ls32l8
- GCC_except_table1847
- GCC_except_table1855
- GCC_except_table1862
- GCC_except_table1889
- GCC_except_table1892
- GCC_except_table1903
- GCC_except_table1907
- GCC_except_table1909
- GCC_except_table1912
- GCC_except_table1915
- GCC_except_table1918
- GCC_except_table1927
- GCC_except_table1966
- GCC_except_table2027
- GCC_except_table2052
- GCC_except_table2055
- GCC_except_table2066
- GCC_except_table2072
- GCC_except_table2075
- GCC_except_table2091
- GCC_except_table2094
- GCC_except_table2130
- GCC_except_table2141
- GCC_except_table2146
- GCC_except_table2154
- GCC_except_table2156
- GCC_except_table2159
- GCC_except_table2165
- GCC_except_table2167
- GCC_except_table2171
- GCC_except_table2177
- GCC_except_table2182
- GCC_except_table2185
- GCC_except_table2187
- GCC_except_table2199
- GCC_except_table2230
- GCC_except_table2247
- GCC_except_table2356
- GCC_except_table2376
- GCC_except_table2378
- GCC_except_table2615
- GCC_except_table2633
- GCC_except_table3081
- GCC_except_table3084
- GCC_except_table3119
- GCC_except_table3121
- GCC_except_table3141
- GCC_except_table3142
- GCC_except_table3172
- GCC_except_table3183
- GCC_except_table3186
- GCC_except_table3246
- GCC_except_table3268
- GCC_except_table3271
- GCC_except_table3315
- GCC_except_table3319
- GCC_except_table3322
- GCC_except_table3336
CStrings:
+ "Display configuration resolved with %lu display(s)"
+ "Shuffle asset %{public}@ already exists at target, treating export-from-directory as success"
+ "Triggering poster upgrade: forced (one-shot)"
- "External display support enabled with %lu displays"
- "Triggering poster upgrade: forced"
```
