## AppleHIDTransportSupport

> `/System/Library/PrivateFrameworks/AppleHIDTransportSupport.framework/AppleHIDTransportSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x623c` | `0x6420` | **`+0x1e4`** |
| `__TEXT.__oslogstring` | `0x178` | `0x1bc` | **`+0x44`** |
| `__AUTH_CONST.__objc_const` | `0x8f0` | `0x8c0` | **`-0x30`** |
| `__TEXT.__const` | `0x88` | `0x98` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x210` | `0x218` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x7c` | `0x78` | **`-0x4`** |

### Other Changes

```diff

-10100.34.0.0.0
+10100.38.1.0.0

-  Functions: 171
-  Symbols:   392
-  CStrings:  74
+  Functions: 172
+  Symbols:   391
+  CStrings:  75
Symbols:
+ -[AHTDevice drainInputReportLoggingBuffer:]
+ -[AHTDevice enableInputReportLogging:enable:]
- -[AHTDevice pollingScheduled]
- -[AHTDevice setPollingScheduled:]
- _OBJC_IVAR_$_AHTDevice._pollingScheduled
CStrings:
+ "AHTDevice: beginDrainPollingFifo failed: 0x%x"
+ "AHTDevice: drainInputReportLoggingBuffer failed: 0x%x"
+ "AHTDevice: endDrainPollingFifo failed: 0x%x"
- "AHTDevice: beginDrainFifo failed: 0x%x"
- "AHTDevice: endDrainFifo failed: 0x%x"
```
