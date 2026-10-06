## PhotosPosterUI

> `/System/Library/PrivateFrameworks/PhotosPosterUI.framework/PhotosPosterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc5718` | `0xc5adc` | **`+0x3c4`** |
| `__AUTH_CONST.__objc_const` | `0x11978` | `0x119a8` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x7340` | `0x7370` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xa5f4` | `0xa624` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x32a0` | `0x32c0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x49d3` | `0x49ee` | **`+0x1b`** |
| `__TEXT.__unwind_info` | `0x3160` | `0x3178` | **`+0x18`** |
| `__DATA.__bss` | `0x1de0` | `0x1df0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xa84` | `0xa88` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x1994` | `0x1998` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-912.0.111.0.0
+912.0.232.0.0

-  Functions: 5298
-  Symbols:   7113
-  CStrings:  1242
+  Functions: 5304
+  Symbols:   7121
+  CStrings:  1243
Symbols:
+ -[PUWallpaperPosterController _deviceConfigurationForCurrentDisplay]
+ -[PUWallpaperPosterController forcedPosterUpgradeReason]
+ -[PUWallpaperPosterController setForcedPosterUpgradeReason:]
+ -[PUWallpaperPosterEditorController _effectiveDeviceOrientation]
+ GCC_except_table1021
+ GCC_except_table1058
+ GCC_except_table1063
+ GCC_except_table1068
+ GCC_except_table1091
+ GCC_except_table1093
+ GCC_except_table1095
+ GCC_except_table1140
+ GCC_except_table1420
+ GCC_except_table1421
+ GCC_except_table1541
+ GCC_except_table1542
+ GCC_except_table1566
+ GCC_except_table1764
+ GCC_except_table1786
+ GCC_except_table1830
+ GCC_except_table1839
+ GCC_except_table1866
+ GCC_except_table1874
+ GCC_except_table1875
+ GCC_except_table1881
+ GCC_except_table1882
+ GCC_except_table1883
+ GCC_except_table1908
+ GCC_except_table1912
+ GCC_except_table1923
+ GCC_except_table1929
+ GCC_except_table1932
+ GCC_except_table1935
+ GCC_except_table1938
+ GCC_except_table1947
+ GCC_except_table1986
+ GCC_except_table2048
+ GCC_except_table2073
+ GCC_except_table2076
+ GCC_except_table2087
+ GCC_except_table2093
+ GCC_except_table2096
+ GCC_except_table2112
+ GCC_except_table2115
+ GCC_except_table2151
+ GCC_except_table2164
+ GCC_except_table2167
+ GCC_except_table2170
+ GCC_except_table2182
+ GCC_except_table2185
+ GCC_except_table2192
+ GCC_except_table2198
+ GCC_except_table2204
+ GCC_except_table2214
+ GCC_except_table2216
+ GCC_except_table2228
+ GCC_except_table2260
+ GCC_except_table2277
+ GCC_except_table2386
+ GCC_except_table2406
+ GCC_except_table2408
+ GCC_except_table2647
+ GCC_except_table2665
+ GCC_except_table3116
+ GCC_except_table3119
+ GCC_except_table3154
+ GCC_except_table3156
+ GCC_except_table3176
+ GCC_except_table3177
+ GCC_except_table3207
+ GCC_except_table3218
+ GCC_except_table3221
+ GCC_except_table3282
+ GCC_except_table3304
+ GCC_except_table3307
+ GCC_except_table3357
+ GCC_except_table3360
+ GCC_except_table3364
+ GCC_except_table3367
+ GCC_except_table3381
+ _OBJC_IVAR_$_PUWallpaperPosterController._forcedPosterUpgradeReason
+ _PUFiltersForBacklightLuminanceUpdates
+ _PUPosterShouldNormalizeBlurEdges.onceToken
+ ___PUPosterShouldNormalizeBlurEdges_block_invoke
- GCC_except_table1018
- GCC_except_table1055
- GCC_except_table1060
- GCC_except_table1065
- GCC_except_table1088
- GCC_except_table1090
- GCC_except_table1092
- GCC_except_table1136
- GCC_except_table1415
- GCC_except_table1416
- GCC_except_table1536
- GCC_except_table1537
- GCC_except_table1561
- GCC_except_table1754
- GCC_except_table1781
- GCC_except_table1825
- GCC_except_table1834
- GCC_except_table1861
- GCC_except_table1869
- GCC_except_table1870
- GCC_except_table1876
- GCC_except_table1877
- GCC_except_table1878
- GCC_except_table1903
- GCC_except_table1907
- GCC_except_table1918
- GCC_except_table1922
- GCC_except_table1924
- GCC_except_table1930
- GCC_except_table1933
- GCC_except_table1942
- GCC_except_table1981
- GCC_except_table2043
- GCC_except_table2068
- GCC_except_table2071
- GCC_except_table2082
- GCC_except_table2088
- GCC_except_table2091
- GCC_except_table2107
- GCC_except_table2110
- GCC_except_table2146
- GCC_except_table2157
- GCC_except_table2159
- GCC_except_table2165
- GCC_except_table2175
- GCC_except_table2177
- GCC_except_table2187
- GCC_except_table2189
- GCC_except_table2193
- GCC_except_table2201
- GCC_except_table2209
- GCC_except_table2218
- GCC_except_table2254
- GCC_except_table2271
- GCC_except_table2380
- GCC_except_table2400
- GCC_except_table2402
- GCC_except_table2641
- GCC_except_table2659
- GCC_except_table3110
- GCC_except_table3113
- GCC_except_table3148
- GCC_except_table3150
- GCC_except_table3170
- GCC_except_table3171
- GCC_except_table3201
- GCC_except_table3212
- GCC_except_table3215
- GCC_except_table3276
- GCC_except_table3298
- GCC_except_table3301
- GCC_except_table3351
- GCC_except_table3354
- GCC_except_table3358
- GCC_except_table3361
- GCC_except_table3375
CStrings:
+ "Forcing depth off for stand-in layout on display %{public}@"
+ "Layout configuration mismatch detected, updating layout for display %{public}@"
+ "Triggering poster upgrade: %{public}@"
- "Forcing depth off for not-yet-migrated poster on landscape-capable display"
- "Layout configuration mismatch detected, updating layout for current device"
```
