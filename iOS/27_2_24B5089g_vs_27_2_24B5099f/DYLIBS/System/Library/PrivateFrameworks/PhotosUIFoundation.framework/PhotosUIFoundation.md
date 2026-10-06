## PhotosUIFoundation

> `/System/Library/PrivateFrameworks/PhotosUIFoundation.framework/PhotosUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xb976` | `0xb922` | **`-0x54`** |
| `__AUTH_CONST.__objc_const` | `0x1f170` | `0x1f1b8` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x7d00` | `0x7cc0` | **`-0x40`** |
| `__TEXT.__const` | `0x71f0` | `0x7230` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x6160` | `0x6140` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1960` | `0x1978` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xfc84` | `0xfc9c` | **`+0x18`** |
| `__DATA.__bss` | `0x6bd0` | `0x6bc0` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x7860` | `0x7850` | **`-0x10`** |
| `__TEXT.__text` | `0xf64b4` | `0xf64a8` | **`-0xc`** |
| `__DATA_CONST.__const` | `0x3f30` | `0x3f28` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x5748` | `0x5740` | **`-0x8`** |

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0

-  Functions: 9599
+  Functions: 9597

-  CStrings:  1576
+  CStrings:  1575
Symbols:
+ -[PXBaseDisplayCollection px_allowsScopedSearch]
+ -[UIScrollView(PhotosUICore) px_setTopEdgePocketHidden:]
+ GCC_except_table1132
+ GCC_except_table1136
+ GCC_except_table1139
+ GCC_except_table1142
+ GCC_except_table1150
+ GCC_except_table1154
+ GCC_except_table1161
+ GCC_except_table1163
+ GCC_except_table1165
+ GCC_except_table1167
+ GCC_except_table1169
+ GCC_except_table1171
+ GCC_except_table1173
+ GCC_except_table1179
+ GCC_except_table1241
+ GCC_except_table1306
+ GCC_except_table1568
+ GCC_except_table1578
+ GCC_except_table1603
+ GCC_except_table1629
+ GCC_except_table1847
+ GCC_except_table1868
+ GCC_except_table1877
+ GCC_except_table1879
+ GCC_except_table1896
+ GCC_except_table1934
+ GCC_except_table1938
+ GCC_except_table2075
+ GCC_except_table2090
+ GCC_except_table2108
+ GCC_except_table2148
+ GCC_except_table2236
+ GCC_except_table2400
+ GCC_except_table2618
+ GCC_except_table2652
+ GCC_except_table2680
+ GCC_except_table2949
+ GCC_except_table3048
+ GCC_except_table3050
+ GCC_except_table3103
+ GCC_except_table3117
+ GCC_except_table3121
+ GCC_except_table3128
+ GCC_except_table3135
+ GCC_except_table3150
+ GCC_except_table3157
+ GCC_except_table3171
+ GCC_except_table3440
+ GCC_except_table3475
+ GCC_except_table3496
+ GCC_except_table3576
+ GCC_except_table3578
+ GCC_except_table3613
+ GCC_except_table3644
+ GCC_except_table3648
+ GCC_except_table3664
+ GCC_except_table3713
+ GCC_except_table3729
+ _MGCopyAnswer
+ _MGIsDeviceOfType
+ _PXDeviceIsV68
+ _PXDeviceIsV68.isV68
+ _PXDeviceIsV68.onceToken
+ ___PXDeviceIsV68_block_invoke
+ _atoi
+ _getenv
- -[PXFeatureSpec _fullscreenContentInsetsForWidth:]
- GCC_except_table1131
- GCC_except_table1135
- GCC_except_table1138
- GCC_except_table1141
- GCC_except_table1149
- GCC_except_table1153
- GCC_except_table1160
- GCC_except_table1162
- GCC_except_table1164
- GCC_except_table1166
- GCC_except_table1168
- GCC_except_table1170
- GCC_except_table1172
- GCC_except_table1178
- GCC_except_table1240
- GCC_except_table1305
- GCC_except_table1567
- GCC_except_table1577
- GCC_except_table1602
- GCC_except_table1628
- GCC_except_table1848
- GCC_except_table1869
- GCC_except_table1878
- GCC_except_table1880
- GCC_except_table1897
- GCC_except_table1936
- GCC_except_table1939
- GCC_except_table2076
- GCC_except_table2091
- GCC_except_table2109
- GCC_except_table2149
- GCC_except_table2237
- GCC_except_table2401
- GCC_except_table2619
- GCC_except_table2654
- GCC_except_table2681
- GCC_except_table2950
- GCC_except_table3049
- GCC_except_table3051
- GCC_except_table3104
- GCC_except_table3118
- GCC_except_table3122
- GCC_except_table3129
- GCC_except_table3136
- GCC_except_table3151
- GCC_except_table3158
- GCC_except_table3172
- GCC_except_table3441
- GCC_except_table3476
- GCC_except_table3497
- GCC_except_table3577
- GCC_except_table3579
- GCC_except_table3614
- GCC_except_table3645
- GCC_except_table3649
- GCC_except_table3665
- GCC_except_table3714
- GCC_except_table3730
- _NSSelectorFromString
- _PXAdditionalEnhancedLandscapeEnabled
- _PXAdditionalEnhancedLandscapeSupported.onceToken
- _PXAdditionalEnhancedLandscapeSupported.supported
- _PXAssetActionTypeShowAdjustKeywords
- _PXPhotosBundle.bundle
- _PXPhotosBundle.onceToken
- ___PXAdditionalEnhancedLandscapeSupported_block_invoke
- ___PXPhotosBundle_block_invoke
CStrings:
+ "TargetSubType"
+ "V68"
+ "V68_DEVICE_EMULATION_ENABLED"
- "/System/Library/Photos/Resources/PhotosBundle.bundle"
- "PXAdditionalEnhancedLandscape"
- "PXAssetActionTypeShowAdjustKeywords"
- "isSupported"
```
