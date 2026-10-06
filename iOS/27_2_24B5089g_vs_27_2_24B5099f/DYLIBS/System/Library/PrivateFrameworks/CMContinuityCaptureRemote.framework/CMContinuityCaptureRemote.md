## CMContinuityCaptureRemote

> `/System/Library/PrivateFrameworks/CMContinuityCaptureRemote.framework/CMContinuityCaptureRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xafb40` | `0xae084` | **`-0x1abc`** |
| `__TEXT.__oslogstring` | `0xb8cd` | `0xb27d` | **`-0x650`** |
| `__TEXT.__cstring` | `0xa9c5` | `0xa7d5` | **`-0x1f0`** |
| `__TEXT.__gcc_except_tab` | `0x3400` | `0x33bc` | **`-0x44`** |
| `__AUTH_CONST.__cfstring` | `0x3d20` | `0x3ce0` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1058` | `0x1038` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0x15b8` | `0x15d8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2ad0` | `0x2ab0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xba0` | `0xb88` | **`-0x18`** |
| `__DATA.__common` | `0xf0` | `0xe0` | **`-0x10`** |
| `__TEXT.__const` | `0x13e0` | `0x13d0` | **`-0x10`** |
| `__AUTH_CONST.__objc_const` | `0xac90` | `0xac98` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x5fb4` | `0x5fbc` | **`+0x8`** |

### Other Changes

```diff

-764.40.5.0.0
+764.40.7.0.0

-  Functions: 3185
-  Symbols:   4614
-  CStrings:  1877
+  Functions: 3176
+  Symbols:   4612
+  CStrings:  1849
Symbols:
+ ___70-[CMContinuityCaptureXPCServerCCD listener:shouldAcceptNewConnection:]_block_invoke_3
+ ___70-[CMContinuityCaptureXPCServerCCD listener:shouldAcceptNewConnection:]_block_invoke_4
+ ___80-[CMContinuityCaptureXPCClientCCD connectToContinuityCaptureServerWithDelegate:]_block_invoke_3
+ ___80-[CMContinuityCaptureXPCClientCCD connectToContinuityCaptureServerWithDelegate:]_block_invoke_4
+ ___80-[CMContinuityCaptureXPCClientCCD connectToContinuityCaptureServerWithDelegate:]_block_invoke_5
- _CFPreferencesGetAppIntegerValue
- _CVPixelBufferGetIOSurface
- _IOSurfaceGetID
- ___67-[CMContinuityCaptureTimeSyncClock startEmittingHeartBeatSignposts]_block_invoke
- _gCMContinuityCaptureTimeSyncClockTrace
- _gGMFigKTraceEnabled
- _kdebug_trace
CStrings:
+ "-[CMContinuityCaptureXPCClientCCD connectToContinuityCaptureServerWithDelegate:]_block_invoke_5"
+ "-[CMContinuityCaptureXPCServerCCD listener:shouldAcceptNewConnection:]_block_invoke_4"
- "-[CMContinuityCaptureTimeSyncClock initWithClock:]"
- "-[CMContinuityCaptureTimeSyncClock startEmittingHeartBeatSignposts]"
- "-[CMContinuityCaptureTimeSyncClock startEmittingHeartBeatSignposts]_block_invoke"
- "-[CMContinuityCaptureXPCClientCCD connectToContinuityCaptureServerWithDelegate:]_block_invoke_2"
- "-[CMContinuityCaptureXPCServerCCD listener:shouldAcceptNewConnection:]_block_invoke_2"
- "-[CVPixelBufferCoder _createPixelBufferForImage:fillWidth:fillHeight:]"
- "-[CVPixelBufferCoder encodeWithCoder:]"
- "-[CVPixelBufferCoder initWithCoder:]"
- "-[NSCoder(CVPixelBuffer) decodeCVPixelBufferForKey:expectSourceMedia:]"
- "<<<< CMContinuityCaptureTimeSyncClock >>>> %s: %@ %lld: (%lld) %lld -> %lld"
- "<<<< CMContinuityCaptureTimeSyncClock >>>> %s: %@ starting heart beat signposts with interval %lu seconds"
- "<<<< CMContinuityCaptureTimeSyncClock >>>> %s: Failed to create PTP clock with identifier %llu, available identifiers %@"
- "<<<< CMContinuityCaptureXPCClientCCD >>>> %s: connection interrupted %@. Scheduling reconnect in 3 seconds."
- "<<<< CMContinuityCaptureXPCClientCCD >>>> %s: connection invalidated %@"
- "<<<< CMContinuityCaptureXPCServer >>>> %s: connection interrupted %@"
- "<<<< CMContinuityCaptureXPCServer >>>> %s: connection invalidated %@"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: Could not create pixel buffer: %d"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: Could not read source media %@, falling back to pixel buffer copy"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: Could not serialize pixel buffer, error %d"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: Error creating pixel buffer %zu x %zu: %d"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: Expected source media but pixel buffer data was found instead (not fatal)"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: Failed to create pixel buffer %zu x %zu"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: Fallback not using atom data, outdated peer connection for pixel buffer"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: No pixel data"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: bad source image offset"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: image planes don't match, encoded %d allocated %d"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: source image offset overrun"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: source image stride overrun"
- "cmcontinuitycapturetimesyncclock_trace"
- "continuitycapture_timesync_heartbeat_interval"
```
