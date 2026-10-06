## PerfPowerServicesReader

> `/System/Library/PrivateFrameworks/PerfPowerServicesReader.framework/PerfPowerServicesReader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15895c` | `0x158c60` | **`+0x304`** |
| `__TEXT.__oslogstring` | `0xda1` | `0xe59` | **`+0xb8`** |
| `__TEXT.__gcc_except_tab` | `0x4adc` | `0x4b10` | **`+0x34`** |
| `__TEXT.__unwind_info` | `0x4b70` | `0x4b88` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x60b0` | `0x60c0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1399c` | `0x139ac` | **`+0x10`** |

### Other Changes

```diff

-3486.40.98.0.0
+3486.40.112.0.0

-  Functions: 8165
-  Symbols:   12066
-  CStrings:  2361
+  Functions: 8166
+  Symbols:   12067
+  CStrings:  2363
Symbols:
+ -[PPSTimestampConverter monotonicRangeForStartEpoch:endEpoch:startMonotonic:endMonotonic:]
Functions:
~ -[PPSSQLiteTimeSeriesIngester parseDataForRequest:outError:] : 2852 -> 2956
~ +[PPSTimestampConverterRegistry converterForFilepath:] : 192 -> 236
~ +[PPSPredicateUtilities predicateForStartTimestamp:endTimestamp:withKeyPath:] : 280 -> 396
+ -[PPSTimestampConverter monotonicRangeForStartEpoch:endEpoch:startMonotonic:endMonotonic:]
CStrings:
+ "Epoch range [%.6f, %.6f] has no monotonic preimage in %{public}@ (%zu system-offset entries)."
+ "Inverted timestamp range for key-path %{public}@: [%.6f, %.6f]. Query will match no rows."
```
