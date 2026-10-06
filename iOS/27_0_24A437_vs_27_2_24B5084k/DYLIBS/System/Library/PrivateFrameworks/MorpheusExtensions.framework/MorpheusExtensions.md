## MorpheusExtensions

> `/System/Library/PrivateFrameworks/MorpheusExtensions.framework/MorpheusExtensions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xab420` | `0xaaa8c` | **`-0x994`** |
| `__AUTH_CONST.__const` | `0x95b8` | `0x9478` | **`-0x140`** |
| `__TEXT.__const` | `0x4c80` | `0x4d20` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x7374` | `0x73e4` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0xb6c` | `0xb2c` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1750` | `0x1788` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x15cf` | `0x15ff` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x2075` | `0x20a5` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xb20` | `0xb40` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2268` | `0x2250` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0x1422` | `0x1434` | **`+0x12`** |
| `__DATA.__bss` | `0x3800` | `0x3810` | **`+0x10`** |
| `__DATA.__data` | `0xd10` | `0xd20` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x710` | `0x700` | **`-0x10`** |
| `__TEXT.__cstring` | `0x40f6` | `0x40e6` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1450` | `0x145c` | **`+0xc`** |
| `__AUTH.__data` | `0x1d78` | `0x1d70` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x168` | `0x160` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x850` | `0x858` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x1418` | `0x1410` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x2e0` | `0x2d8` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x14c` | `0x148` | **`-0x4`** |

### Other Changes

```diff

-42.0.0.0.0
+44.0.0.0.0

+  - /System/Library/Frameworks/OSLog.framework/OSLog

+  - /System/Library/PrivateFrameworks/BiomeStorage.framework/BiomeStorage

-  - /usr/lib/swift/libswiftAppleArchive.dylib

-  Functions: 2393
-  Symbols:   939
-  CStrings:  576
+  Functions: 2375
+  Symbols:   936
+  CStrings:  577
Symbols:
+ _HKSampleSortIdentifierEndDate
+ _HKSampleSortIdentifierStartDate
+ _keypath_get_selector_endDate
+ _keypath_get_selector_startDate
+ _symbolic _____ySo8HKSampleCG 10Foundation14SortDescriptorV
+ _symbolic _____ySo8HKSampleCG 9HealthKit17HKSamplePredicateV
+ _symbolic _____ySo8HKSampleCG 9HealthKit23HKSampleQueryDescriptorV
+ _symbolic _____ySo8HKSampleCG 9HealthKit23HKSourceQueryDescriptorV
+ _symbolic _____y_____ySo8HKSampleCGG s23_ContiguousArrayStorageC 10Foundation14SortDescriptorV
+ _symbolic _____y_____ySo8HKSampleCGG s23_ContiguousArrayStorageC 9HealthKit17HKSamplePredicateV
- _OBJC_CLASS_$_HKActivitySummary
- _OBJC_CLASS_$_HKActivitySummaryQuery
- _OBJC_CLASS_$_HKSampleQuery
- _OBJC_CLASS_$_HKSourceQuery
- ___swift_closure_destructor.31Tm
- __objc_autoreleasePoolPop
- __objc_autoreleasePoolPush
- __swift_FORCE_LOAD_$_swiftAppleArchive
- __swift_FORCE_LOAD_$_swiftAppleArchive_$_MorpheusExtensions
- _symbolic ScCySaySo17HKActivitySummaryCG______pG s5ErrorP
- _symbolic ScCySaySo8HKSampleCG______pG s5ErrorP
- _symbolic ScCyShySo8HKSourceCG______pG s5ErrorP
- _symbolic ShySo8HKSourceCG
CStrings:
+ "COMPONENTNAME_TC"
+ "Text embedding result is missing an embedding"
- "querySourcesFunction"
```
