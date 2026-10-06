## MetricMeasurement

> `/System/Library/PrivateFrameworks/MetricMeasurement.framework/MetricMeasurement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f878` | `0x1f770` | **`-0x108`** |
| `__TEXT.__cstring` | `0x27da` | `0x26d9` | **`-0x101`** |
| `__AUTH_CONST.__cfstring` | `0x2980` | `0x2880` | **`-0x100`** |
| `__DATA_CONST.__const` | `0x6f0` | `0x6c8` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1618` | `0x1640` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xa58` | `0xa50` | **`-0x8`** |

### Other Changes

```diff

-361.0.0.0.0
+367.0.0.0.0

-  Functions: 894
-  Symbols:   1716
-  CStrings:  426
+  Functions: 893
+  Symbols:   1715
+  CStrings:  417
Symbols:
+ GCC_except_table14
+ ___block_descriptor_56_e8_32r40r48r_e48_v32?0"PPSLiteMetricCollection"8Q16"NSError"24lr32l8r40l8r48l8
- ___47-[MXMEnergyMetric _convertMetricsToSampleData:]_block_invoke
- ___block_descriptor_40_e8_32s_e141_v88?0"PPSMetricSample"8"NSString"16"NSString"24"MXMSampleTag"32"NSDimension"40d48"NSString"56"NSNumber"64"MXMMutableSampleData"72Q80ls32l8
- ___block_descriptor_56_e8_32r40r48r_e44_v32?0"PPSMetricCollection"8Q16"NSError"24lr32l8r40l8r48l8
Functions:
~ -[MXMEnergyMetric _convertMetricsToSampleData:] : 1508 -> 1256
- ___47-[MXMEnergyMetric _convertMetricsToSampleData:]_block_invoke
CStrings:
+ "v32@?0@\"PPSLiteMetricCollection\"8Q16@\"NSError\"24"
- "aneEnergy"
- "bytesRead"
- "bytesWritten"
- "cpuEnergy"
- "cpuEnergyWithoutVouchers"
- "cpuInstructions"
- "gpuEnergy"
- "gpuEnergyWithoutVouchers"
- "v32@?0@\"PPSMetricCollection\"8Q16@\"NSError\"24"
- "v88@?0@\"PPSMetricSample\"8@\"NSString\"16@\"NSString\"24@\"MXMSampleTag\"32@\"NSDimension\"40d48@\"NSString\"56@\"NSNumber\"64@\"MXMMutableSampleData\"72Q80"
```
