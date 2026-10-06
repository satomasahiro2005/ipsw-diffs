## PhotoFoundation

> `/System/Library/PrivateFrameworks/PhotoFoundation.framework/PhotoFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x125f` | `0x118f` | **`-0xd0`** |
| `__TEXT.__swift5_reflstr` | `0x9f9` | `0x929` | **`-0xd0`** |
| `__TEXT.__text` | `0x23fec` | `0x23f74` | **`-0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x854` | `0x800` | **`-0x54`** |
| `__AUTH_CONST.__objc_const` | `0x2800` | `0x2828` | **`+0x28`** |
| `__TEXT.__const` | `0x22f8` | `0x22d8` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0xd04` | `0xd1c` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xc8` | `0xdc` | **`+0x14`** |
| `__DATA.__bss` | `0x1fc0` | `0x1fd0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x8c8` | `0x8d0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xdc0` | `0xdc8` | **`+0x8`** |

### Other Changes

```diff

-912.0.235.0.0
+916.40.110.0.0

-  Functions: 1494
-  Symbols:   1342
-  CStrings:  259
+  Functions: 1496
+  Symbols:   1349
+  CStrings:  252
Symbols:
+ +[PFStateCaptureHandler stateCaptureDictionariesForAllHandlers]
+ -[PFStateCaptureHandler name]
+ -[PFStateCaptureHandler stateCaptureDictionary]
+ GCC_except_table134
+ GCC_except_table197
+ GCC_except_table308
+ GCC_except_table312
+ _PFHeapBytesAllocated
+ _PFHeapBytesInUse
+ _PFHeapFragmentationRatio
+ __OBJC_$_PROP_LIST_PFStateCaptureHandler
+ _sAllStateCaptureHandlers
+ _sAllStateCaptureHandlersLock
- +[PFCoalescer arrayCoalescerWithLabel:queue:action:]
- GCC_except_table135
- GCC_except_table196
- GCC_except_table306
- GCC_except_table310
- _PFReduceF
CStrings:
+ "VISyncWatch"
- "AlbumPickerSearchSortFilter"
- "GyroReframing"
- "Lemonade"
- "SearchUIImprovements"
- "SharedCollections"
- "SolariumVisionOSSearch"
- "SpatialPanoramas"
- "UtilityIntelligence"
```
