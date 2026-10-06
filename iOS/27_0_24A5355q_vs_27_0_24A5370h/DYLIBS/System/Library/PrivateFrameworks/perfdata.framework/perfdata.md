## perfdata

> `/System/Library/PrivateFrameworks/perfdata.framework/perfdata`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x779c` | `0x7778` | **`-0x24`** |

### Other Changes

```text
Functions:
~ _pdwriter_close : 248 -> 268
~ _pdwriter_flush : 240 -> 256
~ _pdwriter_defer : 136 -> 140
~ _json_printf_s : 360 -> 364
~ -[PDAggregateMeasurement updateWithMeasurement:] : 1784 -> 1776
~ -[PDMeasurement(PDContainerAdditions) initWithContainer:dictionary:group:error:] : 2332 -> 2296
~ -[PDContainer measurementCount] : 384 -> 380
~ -[PDContainer enumerateMeasurementsMatchingNullableFilter:error:usingBlock:] : 1092 -> 1088
~ -[PDContainer enumerateAggregatedMeasurementsMatchingNullableFilter:ignoringVariables:error:usingBlock:] : 600 -> 596
~ _get_metric_filter_variables : 732 -> 728
~ -[PDMeasurement matchesVariables:ignoringMissing:] : 380 -> 376
~ -[PDMeasurement metricFilterIgnoringNullableVariables:] : 500 -> 496
~ -[PDMeasurement enumerateHistogramBucketsWithError:usingBlock:] : 860 -> 852
~ -[PDMeasurement enumeratePercentilesWithError:usingBlock:] : 732 -> 728
```
