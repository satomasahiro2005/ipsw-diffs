## SpringBoardHome

> `/System/Library/PrivateFrameworks/SpringBoardHome.framework/SpringBoardHome`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38a1c4` | `0x38ad98` | **`+0xbd4`** |
| `__AUTH_CONST.__objc_const` | `0x58cb8` | `0x58d60` | **`+0xa8`** |
| `__TEXT.__objc_methlist` | `0x3eb3c` | `0x3eba4` | **`+0x68`** |
| `__AUTH.__objc_data` | `0xb830` | `0xb7e0` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0xf820` | `0xf860` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x7500` | `0x7528` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cb18` | `0x1cb40` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x16e20` | `0x16e00` | **`-0x20`** |
| `__TEXT.__oslogstring` | `0xf150` | `0xf170` | **`+0x20`** |
| `__DATA.__data` | `0x9628` | `0x9618` | **`-0x10`** |
| `__TEXT.__cstring` | `0x18af3` | `0x18ae3` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x1588` | `0x1598` | **`+0x10`** |
| `__AUTH.__data` | `0xc60` | `0xc58` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x3dbc` | `0x3db4` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x9ed0` | `0x9ec8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1318` | `0x1310` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xe98` | `0xe90` | **`-0x8`** |

### Other Changes

```diff

-223.100.0.0.0
+226.0.2.0.0

-  Functions: 24663
-  Symbols:   33641
+  Functions: 24683
+  Symbols:   33633
Symbols:
+ +[SBHClockApplicationIconImageView precacheDataInCacheGroup:iconImageInfo:appearance:priority:options:]
+ -[SBHIconImageCache estimatedPoolDiskSpaceUsage]
+ -[SBHIconManager _precacheImagesForRequest:generation:allowLocalCache:completionHandler:]
+ -[SBHLibraryCategoryStackView displayedIcons]
+ -[SBHLibraryCategoryStackView setDisplayedIcons:]
+ -[SBHProxiedApplicationPlaceholder isPlaceholder]
+ -[SBIconImageCrossfadeView _shouldPreserveSourceMasking]
+ -[SBIconImageView usesGlassIconImage]
+ GCC_except_table1003
+ GCC_except_table1063
+ GCC_except_table1116
+ GCC_except_table1119
+ GCC_except_table1135
+ GCC_except_table1142
+ GCC_except_table173
+ GCC_except_table189
+ GCC_except_table194
+ GCC_except_table201
+ GCC_except_table305
+ GCC_except_table334
+ GCC_except_table340
+ GCC_except_table351
+ GCC_except_table494
+ GCC_except_table499
+ GCC_except_table512
+ GCC_except_table550
+ GCC_except_table579
+ GCC_except_table584
+ GCC_except_table632
+ GCC_except_table776
+ GCC_except_table786
+ GCC_except_table789
+ GCC_except_table798
+ GCC_except_table800
+ GCC_except_table802
+ GCC_except_table804
+ GCC_except_table806
+ GCC_except_table809
+ GCC_except_table811
+ GCC_except_table813
+ GCC_except_table815
+ GCC_except_table820
+ GCC_except_table823
+ GCC_except_table826
+ GCC_except_table829
+ GCC_except_table933
+ GCC_except_table987
+ GCC_except_table99
+ _OBJC_CLASS_$_NSByteCountFormatter
+ _OBJC_IVAR_$_SBHClockApplicationIconImageView._iconImageInfoChangeAnimationCount
+ _OBJC_IVAR_$_SBHLibraryCategoryStackView._displayedIcons
- -[SBHIconManager _extraIconImageCacheConfigurationsByLimitingUniqueTintedConfigurations:]
- -[SBHIconManager _precacheImagesForRequest:generation:completionHandler:]
- -[SBHPrecachedIconImageRecord .cxx_destruct]
- -[SBHPrecachedIconImageRecord appearance]
- -[SBHPrecachedIconImageRecord bundleIdentifier]
- -[SBHPrecachedIconImageRecord description]
- -[SBHPrecachedIconImageRecord imageInfo]
- -[SBHPrecachedIconImageRecord initWithBundleIdentifier:imageInfo:appearance:options:]
- -[SBHPrecachedIconImageRecord options]
- GCC_except_table1004
- GCC_except_table1064
- GCC_except_table1118
- GCC_except_table1120
- GCC_except_table1136
- GCC_except_table1143
- GCC_except_table174
- GCC_except_table188
- GCC_except_table195
- GCC_except_table306
- GCC_except_table335
- GCC_except_table352
- GCC_except_table495
- GCC_except_table513
- GCC_except_table551
- GCC_except_table580
- GCC_except_table585
- GCC_except_table633
- GCC_except_table777
- GCC_except_table787
- GCC_except_table790
- GCC_except_table799
- GCC_except_table801
- GCC_except_table803
- GCC_except_table805
- GCC_except_table807
- GCC_except_table810
- GCC_except_table812
- GCC_except_table814
- GCC_except_table816
- GCC_except_table821
- GCC_except_table824
- GCC_except_table827
- GCC_except_table830
- GCC_except_table934
- GCC_except_table988
- _OBJC_CLASS_$_SBHPrecachedIconImageRecord
- _OBJC_IVAR_$_SBHPrecachedIconImageRecord._appearance
- _OBJC_IVAR_$_SBHPrecachedIconImageRecord._bundleIdentifier
- _OBJC_IVAR_$_SBHPrecachedIconImageRecord._imageInfo
- _OBJC_IVAR_$_SBHPrecachedIconImageRecord._options
- _OBJC_METACLASS_$_SBHPrecachedIconImageRecord
- __OBJC_$_INSTANCE_METHODS_SBHPrecachedIconImageRecord
- __OBJC_$_INSTANCE_VARIABLES_SBHPrecachedIconImageRecord
- __OBJC_$_PROP_LIST_SBHPrecachedIconImageRecord
- __OBJC_CLASS_RO_$_SBHPrecachedIconImageRecord
- __OBJC_METACLASS_RO_$_SBHPrecachedIconImageRecord
- _globalPrecachedIconImageRecords
- _globalPrecachedIconImageRecordsLock
- _kSBIconStateCustomIconElementTypeDateTime
CStrings:
+ "Creating ISIcon on main thread for app %@"
+ "Relayouts: %lu\nDisplayed icon views: %lu\nRecycled icon views: %lu\nIcon view recyclings: %lu\nRecycled icon accessory views: %lu\nIcon accessory view recyclings: %lu\nRecycled icon label accessory views: %lu\nIcon label accessory view recyclings: %lu\nRecycled icon image views: %lu\nIcon image view recyclings: %lu\nLabel cache live/hits/misses: %lu/%lu/%lu\nLegibility cache live/hits/misses: %lu/%lu/%lu\nImage cache live/hits/misses/main: %lu/%lu/%lu/%lu (unmasked: %lu/%lu/%lu)\nFolder image cache live/hits/misses: %lu/%lu/%lu\nEstimated disk usage: %@"
+ "estimatedPoolDiskSpaceUsage"
- "<%@: %@ %.0fx%.0f@%.0fx appearance=%@ options=%lx>"
- "Relayouts: %lu\nDisplayed icon views: %lu\nRecycled icon views: %lu\nIcon view recyclings: %lu\nRecycled icon accessory views: %lu\nIcon accessory view recyclings: %lu\nRecycled icon label accessory views: %lu\nIcon label accessory view recyclings: %lu\nRecycled icon image views: %lu\nIcon image view recyclings: %lu\nLabel cache live/hits/misses: %lu/%lu/%lu\nLegibility cache live/hits/misses: %lu/%lu/%lu\nImage cache live/hits/misses/main: %lu/%lu/%lu/%lu (unmasked: %lu/%lu/%lu)\nFolder image cache live/hits/misses: %lu/%lu/%lu"
- "dateTime"
```
