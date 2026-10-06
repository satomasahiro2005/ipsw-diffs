## PerfPowerServicesMetadata

> `/System/Library/PrivateFrameworks/PerfPowerServicesMetadata.framework/PerfPowerServicesMetadata`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e888` | `0x3ea94` | **`+0x20c`** |
| `__AUTH_CONST.__objc_const` | `0x48c8` | `0x49e8` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x285c` | `0x290c` | **`+0xb0`** |
| `__AUTH.__objc_data` | `0x280` | `0x2d0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x938` | `0x970` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x8be0` | `0x8c00` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1308` | `0x1328` | **`+0x20`** |
| `__TEXT.__cstring` | `0x46da` | `0x46e3` | **`+0x9`** |
| `__DATA_CONST.__got` | `0x220` | `0x228` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1f8` | `0x200` | **`+0x8`** |
| `__TEXT.__const` | `0x108` | `0x110` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x17c` | `0x180` | **`+0x4`** |

### Other Changes

```diff

-3468.0.0.502.1
+3486.0.21.502.1

-  Functions: 1071
-  Symbols:   1706
-  CStrings:  1300
+  Functions: 1085
+  Symbols:   1730
+  CStrings:  1301
Symbols:
+ -[PPSMetric _lazyExtras]
+ -[PPSMetric extras]
+ -[PPSMetric setExtras:]
+ -[PPSMetricExtras .cxx_destruct]
+ -[PPSMetricExtras enumMapping]
+ -[PPSMetricExtras groupBy]
+ -[PPSMetricExtras indexKey]
+ -[PPSMetricExtras metricType]
+ -[PPSMetricExtras rounding]
+ -[PPSMetricExtras setEnumMapping:]
+ -[PPSMetricExtras setGroupBy:]
+ -[PPSMetricExtras setIndexKey:]
+ -[PPSMetricExtras setMetricType:]
+ -[PPSMetricExtras setRounding:]
+ GCC_except_table44
+ _OBJC_CLASS_$_PPSMetricExtras
+ _OBJC_IVAR_$_PPSMetric._extras
+ _OBJC_IVAR_$_PPSMetricExtras._enumMapping
+ _OBJC_IVAR_$_PPSMetricExtras._groupBy
+ _OBJC_IVAR_$_PPSMetricExtras._indexKey
+ _OBJC_IVAR_$_PPSMetricExtras._metricType
+ _OBJC_IVAR_$_PPSMetricExtras._rounding
+ _OBJC_METACLASS_$_PPSMetricExtras
+ __OBJC_$_INSTANCE_METHODS_PPSMetricExtras
+ __OBJC_$_INSTANCE_VARIABLES_PPSMetricExtras
+ __OBJC_$_PROP_LIST_PPSMetricExtras
+ __OBJC_CLASS_RO_$_PPSMetricExtras
+ __OBJC_METACLASS_RO_$_PPSMetricExtras
+ _objc_setProperty_atomic
+ _objc_setProperty_atomic_copy
- GCC_except_table38
- _OBJC_IVAR_$_PPSMetric._enumMapping
- _OBJC_IVAR_$_PPSMetric._groupBy
- _OBJC_IVAR_$_PPSMetric._indexKey
- _OBJC_IVAR_$_PPSMetric._metricType
- _OBJC_IVAR_$_PPSMetric._rounding
CStrings:
+ "assetLoadedFromCacheKB"
+ "extras"
- "assetloadedfromCacheKB"
```
