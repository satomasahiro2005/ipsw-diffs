## MetricMeasurementHelper

> `/System/Library/PrivateFrameworks/MetricMeasurement.framework/XPCServices/MetricMeasurementHelper.xpc/MetricMeasurementHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0xe60` | `0xe80` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x111d` | `0x112e` | **`+0x11`** |
| `__TEXT.__text` | `0x58e8` | `0x58f4` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x568` | `0x570` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x5da` | `0x5de` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-361.0.0.0.0
+367.0.0.0.0

-  CStrings:  416
+  CStrings:  417
Functions:
~ sub_10000201c : 188 -> 200
CStrings:
+ "collectLiteMetricsOnSnapshot:"
+ "setLiteMode:"
+ "v40@0:8@\"MXMProxyMetric\"16d24@?<v@?@\"PPSLiteMetricCollection\"Q@\"NSError\">32"
- "collectMetricsOnSnapshot:"
- "v40@0:8@\"MXMProxyMetric\"16d24@?<v@?@\"PPSMetricCollection\"Q@\"NSError\">32"
```
