## SeymourMetrics

> `/System/Library/PrivateFrameworks/SeymourMetrics.framework/SeymourMetrics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c99c` | `0x3ec7c` | **`+0x22e0`** |
| `__TEXT.__eh_frame` | `0x32b4` | `0x348c` | **`+0x1d8`** |
| `__TEXT.__oslogstring` | `0xc7e` | `0xd5e` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x1150` | `0x11c0` | **`+0x70`** |
| `__TEXT.__const` | `0xec0` | `0xf10` | **`+0x50`** |
| `__TEXT.__cstring` | `0x89b` | `0x85b` | **`-0x40`** |
| `__TEXT.__swift_as_cont` | `0x3e8` | `0x420` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x8da` | `0x900` | **`+0x26`** |
| `__AUTH_CONST.__auth_got` | `0xf48` | `0xf68` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0xdc0` | `0xde0` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x7e0` | `0x800` | **`+0x20`** |
| `__DATA.__data` | `0x198` | `0x1b8` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x4f2` | `0x512` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x2ac` | `0x2c4` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x518` | `0x524` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x16c` | `0x178` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x124` | `0x12c` | **`+0x8`** |

### Other Changes

```diff

-2027.1.54.0.0
+2027.1.63.0.0

-  Functions: 758
-  Symbols:   436
-  CStrings:  95
+  Functions: 783
+  Symbols:   440
+  CStrings:  97
Symbols:
+ ___swift_closure_destructor.26Tm
+ ___swift_closure_destructor.45Tm
+ _symbolic Say_____G 18SeymourMetricsCore22MetricTopicIdentifiersV
+ _symbolic Sbyc
+ _symbolic _____Sg 18SeymourMetricsCore0B13XPIdentifiersV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 18SeymourMetricsCore22MetricTopicIdentifiersV
- ___swift_closure_destructor.25Tm
- ___swift_closure_destructor.44Tm
CStrings:
+ "Deidentified identity fields unavailable; returning no topic identifiers: %{public}s"
+ "MetricListener ready - 14 handlers registered, components activate on first use"
+ "MetricListener.queryMetricTopicIdentifiers"
+ "Registered 14 message handlers"
+ "Skipping XP identifiers for topic %{public}s: %{public}s"
+ "Skipping identifiers for topic %{public}s: %{public}s"
- "MetricListener ready - 15 handlers registered, components activate on first use"
- "MetricListener.queryMetricDeidentifiedIdentityFields"
- "MetricListener.queryMetricXPIdentifiers"
- "Registered 15 message handlers"
```
