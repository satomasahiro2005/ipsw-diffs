## libsystem_trace.dylib

> `/usr/lib/system/libsystem_trace.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b7e4` | `0x1bb64` | **`+0x380`** |
| `__TEXT.__cstring` | `0x1c6b` | `0x1d32` | **`+0xc7`** |
| `__TEXT.__const` | `0x2b0` | `0x2c0` | **`+0x10`** |

### Other Changes

```diff

-1966.2.1.0.0
+1966.40.15.502.2

-  CStrings:  420
+  CStrings:  424
Functions:
~ __os_log_impl_flatten_and_send : 8572 -> 8580
~ _os_metric_dimensions_create : 124 -> 128
~ __os_metric_create_impl : 312 -> 596
~ __os_metric_uint64_op_impl : 696 -> 844
~ __os_metric_int64_op_impl : 708 -> 864
~ __os_metric_double_op_impl : 716 -> 896
~ __os_metric_reset_data : 228 -> 284
~ __os_metric_emit_value_impl : 1140 -> 1200
CStrings:
+ "BUG IN CLIENT OF LIBTRACE: custom histogram cannot have greater than (128 / 2) bins."
+ "_os_metric_get_bin_count"
+ "md->type == _OS_METRIC_TYPE_HISTOGRAM"
+ "metric->metadata.type == _OS_METRIC_TYPE_HISTOGRAM"
```
