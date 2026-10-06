## PerfPowerServicesReader

> `/System/Library/PrivateFrameworks/PerfPowerServicesReader.framework/PerfPowerServicesReader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15871c` | `0x15895c` | **`+0x240`** |
| `__TEXT.__cstring` | `0xe092` | `0xe156` | **`+0xc4`** |
| `__AUTH_CONST.__cfstring` | `0x10b80` | `0x10be0` | **`+0x60`** |
| `__TEXT.__const` | `0x5fd2` | `0x5fe2` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x60a8` | `0x60b0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x13994` | `0x1399c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4b68` | `0x4b70` | **`+0x8`** |

### Other Changes

```diff

-3486.2.4.0.0
+3486.40.92.0.0

-  Functions: 8164
-  Symbols:   12065
-  CStrings:  2358
+  Functions: 8165
+  Symbols:   12066
+  CStrings:  2361
Symbols:
+ -[PPSTimeSeriesRequest initWithDistinctMetrics:predicate:timeFilter:]
Functions:
~ -[PPSSQLiteTimeSeriesIngester parseDataForRequest:outError:] : 2840 -> 2852
~ -[PPSRequestValidator validateDataRequest:filepath:withError:] : 1992 -> 2504
+ -[PPSTimeSeriesRequest initWithDistinctMetrics:predicate:timeFilter:]
CStrings:
+ "Distinct requests cannot select the timestampEnd metric."
+ "Distinct requests cannot select variable-length array metric '%@'."
+ "Distinct requests cannot use limitCount, offsetCount, or readDirection."
```
