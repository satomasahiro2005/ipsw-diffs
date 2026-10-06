## MetricKit

> `/System/Library/Frameworks/MetricKit.framework/MetricKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c7e0` | `0x7cf4c` | **`+0x76c`** |
| `__AUTH_CONST.__objc_const` | `0x66b8` | `0x6718` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x1b20` | `0x1b60` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1e92` | `0x1ec2` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x286c` | `0x2894` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x428` | `0x430` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1220` | `0x1228` | **`+0x8`** |

### Other Changes

```diff

-353.0.0.0.0
+356.0.0.0.0

-  Functions: 3322
-  Symbols:   2426
-  CStrings:  350
+  Functions: 3325
+  Symbols:   2431
+  CStrings:  352
Symbols:
+ -[MXSignpostIntervalData initWithHistogramDurationData:withCumulativeCPUTime:withAverageMemory:withCumulativeLogicalWrites:withCumulativeHitchTimeRatio:withTotalHitchTime:withTotalAnimationTime:]
+ -[MXSignpostIntervalData totalAnimationTime]
+ -[MXSignpostIntervalData totalHitchTime]
+ _OBJC_IVAR_$_MXSignpostIntervalData._totalAnimationTime
+ _OBJC_IVAR_$_MXSignpostIntervalData._totalHitchTime
CStrings:
+ "signpostTotalAnimationTime"
+ "signpostTotalHitchTime"
```
