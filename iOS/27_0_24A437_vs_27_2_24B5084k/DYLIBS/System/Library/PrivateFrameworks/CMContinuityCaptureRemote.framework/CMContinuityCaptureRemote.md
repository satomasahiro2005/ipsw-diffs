## CMContinuityCaptureRemote

> `/System/Library/PrivateFrameworks/CMContinuityCaptureRemote.framework/CMContinuityCaptureRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xae1ec` | `0xafb40` | **`+0x1954`** |
| `__TEXT.__oslogstring` | `0xb27d` | `0xb8cd` | **`+0x650`** |
| `__TEXT.__cstring` | `0xa7d5` | `0xa9c5` | **`+0x1f0`** |
| `__TEXT.__gcc_except_tab` | `0x33bc` | `0x3400` | **`+0x44`** |
| `__AUTH_CONST.__cfstring` | `0x3ce0` | `0x3d20` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1038` | `0x1058` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x15d8` | `0x15b8` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x2ab0` | `0x2ad0` | **`+0x20`** |
| `__DATA.__common` | `0xe0` | `0xf0` | **`+0x10`** |
| `__TEXT.__const` | `0x13d0` | `0x13e0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xb98` | `0xba0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2ed0` | `0x2ed8` | **`+0x8`** |

### Other Changes

```diff

-764.22.13.0.0
+764.40.4.122.1

-  Functions: 3176
-  Symbols:   4612
-  CStrings:  1849
+  Functions: 3185
+  Symbols:   4614
+  CStrings:  1877
Symbols:
+ _CFPreferencesGetAppIntegerValue
+ _CVPixelBufferGetIOSurface
+ _IOSurfaceGetID
+ ___67-[CMContinuityCaptureTimeSyncClock startEmittingHeartBeatSignposts]_block_invoke
+ _gCMContinuityCaptureTimeSyncClockTrace
+ _gGMFigKTraceEnabled
+ _kdebug_trace
- ___70-[CMContinuityCaptureXPCServerCCD listener:shouldAcceptNewConnection:]_block_invoke_3
- ___70-[CMContinuityCaptureXPCServerCCD listener:shouldAcceptNewConnection:]_block_invoke_4
- ___80-[CMContinuityCaptureXPCClientCCD connectToContinuityCaptureServerWithDelegate:]_block_invoke_3
- ___80-[CMContinuityCaptureXPCClientCCD connectToContinuityCaptureServerWithDelegate:]_block_invoke_4
- ___80-[CMContinuityCaptureXPCClientCCD connectToContinuityCaptureServerWithDelegate:]_block_invoke_5
CStrings:
+ "-[CMContinuityCaptureTimeSyncClock initWithClock:]"
+ "-[CMContinuityCaptureTimeSyncClock startEmittingHeartBeatSignposts]"
+ "-[CMContinuityCaptureTimeSyncClock startEmittingHeartBeatSignposts]_block_invoke"
+ "-[CMContinuityCaptureXPCClientCCD connectToContinuityCaptureServerWithDelegate:]_block_invoke_2"
+ "-[CMContinuityCaptureXPCServerCCD listener:shouldAcceptNewConnection:]_block_invoke_2"
+ "-[CVPixelBufferCoder _createPixelBufferForImage:fillWidth:fillHeight:]"
+ "-[CVPixelBufferCoder encodeWithCoder:]"
+ "-[CVPixelBufferCoder initWithCoder:]"
+ "-[NSCoder(CVPixelBuffer) decodeCVPixelBufferForKey:expectSourceMedia:]"
+ "<<<< CMContinuityCaptureTimeSyncClock >>>> %s: %@ %lld: (%lld) %lld -> %lld"
+ "<<<< CMContinuityCaptureTimeSyncClock >>>> %s: %@ starting heart beat signposts with interval %lu seconds"
+ "<<<< CMContinuityCaptureTimeSyncClock >>>> %s: Failed to create PTP clock with identifier %llu, available identifiers %@"
+ "<<<< CMContinuityCaptureXPCClientCCD >>>> %s: connection interrupted %@. Scheduling reconnect in 3 seconds."
+ "<<<< CMContinuityCaptureXPCClientCCD >>>> %s: connection invalidated %@"
+ "<<<< CMContinuityCaptureXPCServer >>>> %s: connection interrupted %@"
+ "<<<< CMContinuityCaptureXPCServer >>>> %s: connection invalidated %@"
+ "<<<< NSCoding+CVPixelBufferRef >>>> %s: Could not create pixel buffer: %d"
+ "<<<< NSCoding+CVPixelBufferRef >>>> %s: Could not read source media %@, falling back to pixel buffer copy"
+ "<<<< NSCoding+CVPixelBufferRef >>>> %s: Could not serialize pixel buffer, error %d"
+ "<<<< NSCoding+CVPixelBufferRef >>>> %s: Error creating pixel buffer %zu x %zu: %d"
+ "<<<< NSCoding+CVPixelBufferRef >>>> %s: Expected source media but pixel buffer data was found instead (not fatal)"
+ "<<<< NSCoding+CVPixelBufferRef >>>> %s: Failed to create pixel buffer %zu x %zu"
+ "<<<< NSCoding+CVPixelBufferRef >>>> %s: Fallback not using atom data, outdated peer connection for pixel buffer"
+ "<<<< NSCoding+CVPixelBufferRef >>>> %s: No pixel data"
+ "<<<< NSCoding+CVPixelBufferRef >>>> %s: bad source image offset"
+ "<<<< NSCoding+CVPixelBufferRef >>>> %s: image planes don't match, encoded %d allocated %d"
+ "<<<< NSCoding+CVPixelBufferRef >>>> %s: source image offset overrun"
+ "<<<< NSCoding+CVPixelBufferRef >>>> %s: source image stride overrun"
+ "cmcontinuitycapturetimesyncclock_trace"
+ "continuitycapture_timesync_heartbeat_interval"
- "-[CMContinuityCaptureXPCClientCCD connectToContinuityCaptureServerWithDelegate:]_block_invoke_5"
- "-[CMContinuityCaptureXPCServerCCD listener:shouldAcceptNewConnection:]_block_invoke_4"
```
