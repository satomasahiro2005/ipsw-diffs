## Logging

> `/System/Library/Trace/Providers/Logging.bundle/Logging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xc85` | `0x19ea` | **`+0xd65`** |
| `__TEXT.__text` | `0xa1b0` | `0xa928` | **`+0x778`** |
| `__TEXT.__objc_methlist` | `0x444` | `0x5c8` | **`+0x184`** |
| `__DATA.__objc_const` | `0x828` | `0x920` | **`+0xf8`** |
| `__DATA.__objc_data` | `0x7d0` | `0x890` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x330` | `0x3e0` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x5e0` | `0x590` | **`-0x50`** |
| `__TEXT.__objc_methname` | `0x5dc` | `0x61c` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x31c` | `0x358` | **`+0x3c`** |
| `__TEXT.__objc_classname` | `0x1fb` | `0x236` | **`+0x3b`** |
| `__TEXT.__const` | `0x8de` | `0x912` | **`+0x34`** |
| `__DATA.__data` | `0x488` | `0x4b8` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x45b` | `0x42b` | **`-0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x2c4` | `0x2e0` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x178` | `0x188` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x32c` | `0x332` | **`+0x6`** |
| `__TEXT.__swift5_proto` | `0x5c` | `0x60` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x38` | `0x3c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-188.0.0.0.0
+196.0.0.0.0

-  Functions: 320
+  Functions: 371

-  CStrings:  174
+  CStrings:  199
Symbols:
+ _os_variant_has_internal_content
- _ktrace_events_range
CStrings:
+ "Apple Logging System data source"
+ "Application launch instrumentation"
+ "Instruments 'Points of Interest' instrumentation"
+ "Internal-only, always-on 'PeriodicSystemMetrics' instrumentation."
+ "Logging.PeriodicSystemMetricsDataCategory"
+ "Metal performance instrumentation"
+ "MetricKit client-provided instrumentation"
+ "PowerProfiler instrumentation"
+ "Runloop hang instrumentation"
+ "Scrolling animation instrumentation"
+ "StateReporting instrumentation"
+ "The 'AppLaunch' data category contains `os_signpost` interval instrumentation that records\nthe various phases of UI application launches."
+ "The 'Hangs' data category contains `os_signpost` instrumentation describing non-macOS application\nrunloop hangs. These intervals correspond to UI unresponsiveness and indicate that the main runloop\nof the application did not turn quickly. This may be due to too much CPU work, synchronous waits\nfor activity such as disk I/O, networking, or XPC messaging, CPU contention, or a combination\nof the above."
+ "The 'InteractionTracking' data category contains `os_signpost` instrumentation that records\nUI interaction tracking information describing when view controllers appear, disappear, drag, or animate."
+ "The 'LoggingSystem' passive data source collects serialized os_signpost, os_log, and other Apple Logging System tracepoint types.\nThis passive data source defines a number of different passive data categories that can be used to collect instrumentation describing\nspecific aspects of system behavior (i.e. hangs, app launch, Metal frame pacing, etc). See individual passive data categories for more details."
+ "The 'MetalFramePacing' data category contains `os_signpost` instrumentation that describes `Metal` performance.\nThis instrumentation provides bucketed, always-on, second-by-second aggregated data and optional\nper-drawable information. The per-drawable information must be explicitly enabled via environment \nvariable, default, or tool UI."
+ "The 'MetricKit' data category contains `os_signpost` instrumentation emitted by client\napplications using `MetricKit`-provided log handles."
+ "The 'PSM' (i.e. 'PeriodicSystemMetrics') data category contains `os_signpost` instrumentation emitted by \nthe `PeriodicSystemMetricsCore` framework. This Internal-only, always-on data describes different\naspects of system power and performance at relatively high (i.e. ~1Hz) cadence and can be programmatically\naccessed using the `SignpostSupport SSPeriodicSystemMetricsReader` Internal framework class."
+ "The 'PerfPowerMetrics' data category contains iOS-only `os_signpost` instrumentation emitted\nwhen users trigger 'Power Profiler' trace recording via the `Control Center` `Performance Trace` control."
+ "The 'PointsOfInterest' data category contains instrumentation emitted to the\n`PointsOfInterest` logging category for visualization in `Instruments`."
+ "The 'Scrolling' data category contains `os_signpost` interval instrumentation that records\nuser scrolling activity."
+ "The `StateReporting` data category contains `os_signpost` instrumentation that describes \nper-domain state transitions and volatile updates reported by `StateReporting.framework` clients."
+ "User application interaction animation instrumentation"
+ "_TtC7Logging33PeriodicSystemMetricsDataCategory"
+ "com.apple.AppleTracingSupport.LoggingProvider"
+ "conciseDocumentation"
+ "detailedDocumentation"
+ "subsystem == \"com.apple.PeriodicSystemMetrics\""
- "com.apple.SwiftUI"
- "swift-ui"
- "v16@?0^{trace_point=QQQQQQII{timeval=qi}**i}8"
```
