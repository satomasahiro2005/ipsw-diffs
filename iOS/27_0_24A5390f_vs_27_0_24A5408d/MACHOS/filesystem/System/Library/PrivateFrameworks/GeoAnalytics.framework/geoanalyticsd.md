## geoanalyticsd

> `/System/Library/PrivateFrameworks/GeoAnalytics.framework/geoanalyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2019c` | `0x21f50` | **`+0x1db4`** |
| `__DATA_CONST.__cfstring` | `0x12620` | `0x12760` | **`+0x140`** |
| `__TEXT.__cstring` | `0xd992` | `0xdac8` | **`+0x136`** |
| `__TEXT.__objc_stubs` | `0x3580` | `0x3660` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x2f8c` | `0x304d` | **`+0xc1`** |
| `__TEXT.__oslogstring` | `0x118c` | `0x1241` | **`+0xb5`** |
| `__DATA_CONST.__const` | `0x1090` | `0x1108` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0xe44` | `0xe9c` | **`+0x58`** |
| `__TEXT.__objc_methtype` | `0xbc7` | `0xc16` | **`+0x4f`** |
| `__DATA.__objc_selrefs` | `0xee8` | `0xf20` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x680` | `0x6b0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x2b8` | `0x2d0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x4e0` | `0x4f4` | **`+0x14`** |
| `__DATA.__objc_const` | `0x1c28` | `0x1c38` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x2b8` | `0x2c3` | **`+0xb`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-2075.30.6.12.8
+2075.30.6.12.12

-  Functions: 392
-  Symbols:   241
-  CStrings:  3319
+  Functions: 402
+  Symbols:   244
+  CStrings:  3343
Symbols:
+ _GEOAPAnalyticsInspectionMaxRows
+ _NSLocalizedDescriptionKey
+ ___NSArray0__struct
CStrings:
+ "%s table=%@"
+ "-[GEOAPDaemonManagerBridge listAnalyticsDatabaseTable:reply:]"
+ "-[GEOAPServiceLocal listAnalyticsDatabaseTable:reply:]"
+ "DailyCounts"
+ "GEOAnalyticsDatabaseInspection"
+ "Inspection"
+ "array"
+ "caseInsensitiveCompare:"
+ "countTypeName"
+ "enumerateDailyCounts SelectDailyCounts: %@"
+ "enumerateDailyCountsWithLimit:block:"
+ "errorWithDomain:code:userInfo:"
+ "listAnalyticsDatabaseTable: '%@' result truncated to %lu rows"
+ "listAnalyticsDatabaseTable:reply:"
+ "networkEventFileDescriptorForRepresentativeDate:inEvalMode:"
+ "no time sync; will not aggregate"
+ "numberWithLongLong:"
+ "rowid"
+ "runAggregationForDate:inEvalMode:"
+ "runEvalAggregation"
+ "starting eval-mode aggregation"
+ "unknown table '%@'"
+ "v28@0:8@16B24"
+ "v32@0:8@\"NSString\"16@?<v@?@\"NSArray\"@\"NSError\">24"
+ "v32@0:8Q16@?24"
+ "v52@?0q8i16@\"NSString\"20@\"NSString\"28@\"NSNumber\"36@\"NSDate\"44"
- "networkEventFileDescriptorForRepresentativeDate:"
- "runAggregationForDate:"
```
