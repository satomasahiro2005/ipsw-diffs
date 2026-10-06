## MetricKit

> `/System/Library/Frameworks/MetricKit.framework/MetricKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c140` | `0x86524` | **`+0xa3e4`** |
| `__DATA.__bss` | `0x12720` | `0x13820` | **`+0x1100`** |
| `__TEXT.__const` | `0x8d76` | `0x94b6` | **`+0x740`** |
| `__DATA.__data` | `0x11c0` | `0x13c0` | **`+0x200`** |
| `__TEXT.__unwind_info` | `0x2390` | `0x2570` | **`+0x1e0`** |
| `__TEXT.__swift5_typeref` | `0x1884` | `0x1938` | **`+0xb4`** |
| `__TEXT.__swift5_proto` | `0x8c4` | `0x94c` | **`+0x88`** |
| `__AUTH_CONST.__auth_got` | `0x9f0` | `0xa20` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x27b8` | `0x27e0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x480` | `0x498` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1ec2` | `0x1ed2` | **`+0x10`** |

### Other Changes

```diff

-369.0.0.0.0
+369.40.1.0.0

-  Functions: 3311
-  Symbols:   2438
-  CStrings:  354
+  Functions: 3495
+  Symbols:   2461
+  CStrings:  355
Symbols:
+ _associated conformance 9MetricKit0A6ReportV10StateEntryVSHAASQ
+ _associated conformance 9MetricKit0A6ReportV11EnvironmentVSHAASQ
+ _associated conformance 9MetricKit0A6ReportV13IntervalEntryVSHAASQ
+ _associated conformance 9MetricKit0A6ReportVSHAASQ
+ _associated conformance 9MetricKit0A6ResultOSHAASQ
+ _associated conformance 9MetricKit14HangDiagnosticVSHAASQ
+ _associated conformance 9MetricKit14SignpostRecordVSHAASQ
+ _associated conformance 9MetricKit15CrashDiagnosticV25ObjectiveCExceptionReasonVSHAASQ
+ _associated conformance 9MetricKit15CrashDiagnosticVSHAASQ
+ _associated conformance 9MetricKit16DiagnosticReportV11EnvironmentVSHAASQ
+ _associated conformance 9MetricKit16DiagnosticReportVSHAASQ
+ _associated conformance 9MetricKit16DiagnosticResultOSHAASQ
+ _associated conformance 9MetricKit19AppLaunchDiagnosticVSHAASQ
+ _associated conformance 9MetricKit22CPUExceptionDiagnosticVSHAASQ
+ _associated conformance 9MetricKit25MemoryExceptionDiagnosticVSHAASQ
+ _associated conformance 9MetricKit28DiskWriteExceptionDiagnosticVSHAASQ
+ _associated conformance 9MetricKit9OSVersionVSHAASQ
+ _swift_getTupleTypeMetadata2
+ _swift_retain_x25
+ _symbolic _____Sg_ABt 9MetricKit0A6ReportV11EnvironmentV
+ _symbolic _____Sg_ABt 9MetricKit15CrashDiagnosticV25ObjectiveCExceptionReasonV
+ _symbolic ______AAt 9MetricKit0A6ResultO
+ _symbolic ______AAt 9MetricKit16DiagnosticResultO
CStrings:
+ "key value "
```
