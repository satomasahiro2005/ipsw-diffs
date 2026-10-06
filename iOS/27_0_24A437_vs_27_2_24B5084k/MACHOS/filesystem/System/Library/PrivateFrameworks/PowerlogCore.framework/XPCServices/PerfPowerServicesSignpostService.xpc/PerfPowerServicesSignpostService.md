## PerfPowerServicesSignpostService

> `/System/Library/PrivateFrameworks/PowerlogCore.framework/XPCServices/PerfPowerServicesSignpostService.xpc/PerfPowerServicesSignpostService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6c68` | `0x77b8` | **`+0xb50`** |
| `__TEXT.__objc_stubs` | `0x1660` | `0x1800` | **`+0x1a0`** |
| `__DATA_CONST.__cfstring` | `0xf40` | `0x1080` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0x166e` | `0x179c` | **`+0x12e`** |
| `__TEXT.__gcc_except_tab` | `0x7c` | `0x198` | **`+0x11c`** |
| `__TEXT.__oslogstring` | `0x5aa` | `0x6aa` | **`+0x100`** |
| `__TEXT.__cstring` | `0xa4c` | `0xb2d` | **`+0xe1`** |
| `__DATA.__objc_selrefs` | `0x890` | `0x900` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x7e8` | `0x828` | **`+0x40`** |
| `__DATA.__objc_const` | `0xa58` | `0xa88` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x898` | `0x8c0` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x530` | `0x550` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x2db` | `0x2f9` | **`+0x1e`** |
| `__DATA_CONST.__auth_got` | `0x2a8` | `0x2b8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xf0` | `0x100` | **`+0x10`** |
| `__TEXT.__const` | `0xb0` | `0xc0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1a0` | `0x1b0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x58` | `0x5c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-3486.2.4.0.0
+3486.40.92.0.0

+  - /System/Library/PrivateFrameworks/PowerLog.framework/PowerLog

-  Functions: 266
-  Symbols:   141
-  CStrings:  539
+  Functions: 273
+  Symbols:   145
+  CStrings:  573
Symbols:
+ _OBJC_CLASS_$_NSCountedSet
+ _OBJC_CLASS_$_NSMutableSet
+ _PPSCreateTelemetryIdentifier
+ _PPSSendTelemetry
+ _os_transaction_create
- _objc_retain_x25
CStrings:
+ "\n"
+ "%@%@%@"
+ "'%@::%@' is not registered for PowerLog telemetry; skipping collection summary"
+ "@\"NSCountedSet\""
+ "Collected signposts across %lu categories for time-series task: '%@'"
+ "CollectionSummary"
+ "Count"
+ "DistinctCategoryCount"
+ "ProcessName"
+ "RunDuration"
+ "Sending collection summary to PowerLog: %{public}@"
+ "SignpostServiceMetrics"
+ "T@\"NSCountedSet\",&,V_categoryCounts"
+ "Top #%lu by collected signpost count: '%@' in '%@' (%lu)"
+ "TotalSignpostCount"
+ "__PPSKVPairs__"
+ "_categoryCounts"
+ "_categoryFromTallyKey:"
+ "_processFromTallyKey:"
+ "_tallyCategory:process:"
+ "allObjects"
+ "categoryCounts"
+ "com.apple.perfpowerservices.signpost.collection-summary"
+ "compare:"
+ "countForObject:"
+ "objectAtIndexedSubscript:"
+ "q24@?0@\"NSString\"8@\"NSString\"16"
+ "rangeOfString:"
+ "set"
+ "setCategoryCounts:"
+ "sortedArrayUsingComparator:"
+ "substringFromIndex:"
+ "substringToIndex:"
+ "v32@0:8@16@24"
```
