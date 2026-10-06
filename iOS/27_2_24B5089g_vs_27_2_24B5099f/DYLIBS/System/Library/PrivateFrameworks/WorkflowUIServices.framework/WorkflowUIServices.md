## WorkflowUIServices

> `/System/Library/PrivateFrameworks/WorkflowUIServices.framework/WorkflowUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10b1c8` | `0x10b424` | **`+0x25c`** |
| `__TEXT.__objc_methlist` | `0x5f3c` | `0x5f54` | **`+0x18`** |
| `__TEXT.__const` | `0xa630` | `0xa640` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x43c8` | `0x43d0` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x3f50` | `0x3f58` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4690` | `0x4698` | **`+0x8`** |

### Other Changes

```diff

-5111.0.2.0.0
+5113.0.1.1.1

-  Functions: 8212
-  Symbols:   5672
+  Functions: 8216
+  Symbols:   5674
Symbols:
+ -[WFPencilActionConfigurationMetricsCacheKey contentSize]
+ -[WFPencilActionConfigurationMetricsCacheKey initWithInterfaceOrientation:contentSize:]
+ -[WFPencilActionConfigurationMetricsCacheKey setContentSize:]
+ -[WFPencilActionConfigurationMetricsProvider metricsWithInterfaceOrientation:contentSize:]
+ -[WFPencilActionConfigurationMetricsProvider metricsWithInterfaceOrientation:contentView:]
+ -[WFPencilActionConfigurationMetricsProvider sheetPreferredContentSizeForContainerSize:interfaceOrientation:]
+ -[WFPencilActionConfigurationViewController containerSize]
+ GCC_except_table1545
+ GCC_except_table1549
+ _OBJC_IVAR_$_WFPencilActionConfigurationMetricsCacheKey._contentSize
- -[WFPencilActionConfigurationMetricsCacheKey initWithInterfaceOrientation:screenSize:]
- -[WFPencilActionConfigurationMetricsCacheKey screenSize]
- -[WFPencilActionConfigurationMetricsCacheKey setScreenSize:]
- -[WFPencilActionConfigurationMetricsProvider metricsWithInterfaceOrientation:]
- -[WFPencilActionConfigurationMetricsProvider sheetPreferredContentSizeWithMetrics:]
- GCC_except_table1544
- GCC_except_table1548
- _OBJC_IVAR_$_WFPencilActionConfigurationMetricsCacheKey._screenSize
```
