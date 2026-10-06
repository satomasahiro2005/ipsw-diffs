## PerfPowerServicesReader

> `/System/Library/PrivateFrameworks/PerfPowerServicesReader.framework/PerfPowerServicesReader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14ac44` | `0x14ae04` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0xd078` | `0xd106` | **`+0x8e`** |
| `__AUTH_CONST.__cfstring` | `0xf020` | `0xf0a0` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0x16bf8` | `0x16c28` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x12d7c` | `0x12d94` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x5e98` | `0x5ea0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x49b0` | `0x49b8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1114` | `0x1118` | **`+0x4`** |

### Other Changes

```diff

-3486.0.46.502.1
+3486.0.81.502.4

-  Functions: 7902
-  Symbols:   11711
-  CStrings:  2138
+  Functions: 7904
+  Symbols:   11714
+  CStrings:  2142
Symbols:
+ +[PPSSQLiteTimeSeriesIngester _stringForSourceNames:metrics:predicate:distinct:]
+ -[PPSTimeSeriesRequest initWithMetrics:predicate:timeFilter:limitCount:offsetCount:readDirection:returnsDistinctEntities:]
+ -[PPSTimeSeriesRequest returnsDistinctEntities]
+ _OBJC_IVAR_$_PPSTimeSeriesRequest._returnsDistinctEntities
+ ___block_descriptor_99_e8_32s40s48s56s64r72r80r88r_e39_B32?0"NSArray"8^{PPSSQLiteRow=}16^24ls32l8r64l8s40l8s48l8s56l8r72l8r80l8r88l8
- +[PPSSQLiteTimeSeriesIngester _stringForSourceNames:metrics:predicate:]
- ___block_descriptor_98_e8_32s40s48s56s64r72r80r88r_e39_B32?0"NSArray"8^{PPSSQLiteRow=}16^24ls32l8r64l8s40l8s48l8s56l8r72l8r80l8r88l8
CStrings:
+ "%@::%lu::%d"
+ "<%@: %p { type: %ld, metrics: %@, predicate: %@, timeFilter: %@ limitCount:%ld offsetCount:%ld readDirection: %ld distinct: %d }>"
+ "Distinct requests cannot select the timestamp metric."
+ "Distinct requests require at least one metric."
+ "returnsDistinct"
- "<%@: %p { type: %ld, metrics: %@, predicate: %@, timeFilter: %@ limitCount:%ld offsetCount:%ld readDirection: %ld }>"
```
