## BacklightServicesHost

> `/System/Library/PrivateFrameworks/BacklightServicesHost.framework/BacklightServicesHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9a87c` | `0x9a7b0` | **`-0xcc`** |
| `__AUTH_CONST.__objc_const` | `0x18fd0` | `0x19048` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x9c44` | `0x9c74` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x7c60` | `0x7c80` | **`+0x20`** |
| `__TEXT.__cstring` | `0x7cde` | `0x7cfb` | **`+0x1d`** |
| `__DATA_CONST.__objc_selrefs` | `0x3bd8` | `0x3bf0` | **`+0x18`** |

### Other Changes

```diff

-6.0.33.0.0
+6.0.35.0.0

-  Functions: 4203
-  Symbols:   7406
-  CStrings:  1981
+  Functions: 4204
+  Symbols:   7407
+  CStrings:  1982
Symbols:
+ -[BLSHDisplayWakeTelemetry _handleBacklightDidCompleteUpdateToState:updateTime:originatingTime:forEvents:abortedEvents:]
+ -[BLSHDisplayWakeTelemetry _logBacklightTelemetryEventForPendingEvent:duration:endTimestamp:]
+ -[BLSHLocalHostSceneEnvironment clientSupportsLowPowerRendering]
+ ___93-[BLSHDisplayWakeTelemetry _logBacklightTelemetryEventForPendingEvent:duration:endTimestamp:]_block_invoke
+ ___93-[BLSHDisplayWakeTelemetry _logBacklightTelemetryEventForPendingEvent:duration:endTimestamp:]_block_invoke_2
- -[BLSHDisplayWakeTelemetry _handleBacklightDidCompleteUpdateToState:updateTime:forEvents:abortedEvents:]
- -[BLSHDisplayWakeTelemetry _logBacklightTelemetryEventForPendingEvent:duration:]
- ___80-[BLSHDisplayWakeTelemetry _logBacklightTelemetryEventForPendingEvent:duration:]_block_invoke
- ___80-[BLSHDisplayWakeTelemetry _logBacklightTelemetryEventForPendingEvent:duration:]_block_invoke_2
CStrings:
+ "__pps_timeSensitiveEntryDate"
```
