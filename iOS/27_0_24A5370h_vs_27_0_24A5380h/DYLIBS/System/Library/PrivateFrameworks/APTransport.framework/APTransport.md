## APTransport

> `/System/Library/PrivateFrameworks/APTransport.framework/APTransport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb3f88` | `0xb5504` | **`+0x157c`** |
| `__TEXT.__cstring` | `0x2f86d` | `0x3004f` | **`+0x7e2`** |
| `__DATA.__data` | `0x1580` | `0x14a0` | **`-0xe0`** |
| `__DATA_DIRTY.__data` | `0xbd0` | `0xcb0` | **`+0xe0`** |
| `__AUTH.__objc_data` | `0x1e0` | `0x140` | **`-0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x6520` | `0x65c0` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x230` | `0x2d0` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b38` | `0x1b90` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x3d10` | `0x3d60` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2cc8` | `0x2d10` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x2db8` | `0x2dd8` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x60` | `0x78` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x3e8` | `0x400` | **`+0x18`** |
| `__DATA.__bss` | `0x148` | `0x138` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x2b8` | `0x2c8` | **`+0x10`** |

### Other Changes

```diff

-980.63.2.0.0
+980.67.2.0.0

-  Functions: 5314
-  Symbols:   4363
-  CStrings:  4502
+  Functions: 5342
+  Symbols:   4384
+  CStrings:  4543
Symbols:
+ GCC_except_table40
+ _APCarPlayHelperGetTypeID
+ _APSGetNANPerformanceForecastThresholds
+ _APTNANDataSessionGetPerformanceForecast
+ _APTransportDeviceIsTransportRecommended
+ _APTransportTrafficCaptureFlushForSysdiagnose
+ _NSFileSize
+ ___APTransportTrafficCaptureFlushForSysdiagnose_block_invoke
+ ___block_descriptor_32_e39_q24?0"NSDictionary"8"NSDictionary"16l
+ ___block_descriptor_72_e8_32r40r48r_e5_v8?0lr32l8r40l8r48l8
+ ___trafficCapture_enforceStorageLimits_block_invoke
+ _fflush
+ _fileno
+ _fsync
+ _kAPTransportTrafficCaptureCreationOption_CaptureDirectory
+ _localtime_r
+ _rename
+ _strerror
+ _strftime
+ _time
+ _trafficCapture_formatNow
+ _unlink
- GCC_except_table38
CStrings:
+ "%H-%M-%S"
+ "%Y.%m.%d"
+ "%s/airplaysnoop_%s__%s__%s.atslite"
+ "%s/airplaysnoop_%s__%s__live.atslite"
+ ".atslite"
+ "980.67.2"
+ "APTNANDataSessionGetPerformanceForecast"
+ "APTransportDeviceIsTransportRecommended"
+ "APTransportTrafficCaptureCreate: missing %@ option\n"
+ "Boolean transportDevice_isNANRecommended(APTransportDeviceRef, OSStatus *)"
+ "NANDS [%{ptr}] Failed to obtain NANEndpoint with error: %#m"
+ "NANDS [%{ptr}] perfForecast=%@"
+ "OSStatus APTNANDataSessionGetPerformanceForecast(APTNANDataSessionRef, APSTransportPerformanceInfo *)"
+ "OSStatus APTransportTrafficCaptureFlushForSysdiagnose(APTransportTrafficCaptureRef)_block_invoke"
+ "OSStatus APTransportTrafficCaptureStartSession(APTransportTrafficCaptureRef)_block_invoke"
+ "OSStatus trafficCapture_closeAndRenameToFinal(APTransportTrafficCaptureRef)"
+ "OSStatus trafficCapture_createCaptureDirectory(APTransportTrafficCaptureRef)"
+ "OSStatus trafficCapture_openSessionFile(APTransportTrafficCaptureRef)"
+ "Terminus_ExplicitNANControl"
+ "[%{ptr}] Created (directory: %@)\n"
+ "[%{ptr}] Created capture directory: %s\n"
+ "[%{ptr}] Deleted old capture file: %s\n"
+ "[%{ptr}] Failed to create capture directory %s: %s\n"
+ "[%{ptr}] Failed to delete old capture file (skipping cleanup): %s\n"
+ "[%{ptr}] Failed to list capture directory: %s\n"
+ "[%{ptr}] Failed to rename capture file %s → %s (errno: %d)\n"
+ "[%{ptr}] FlushForSysdiagnose completed: %s\n"
+ "[%{ptr}] FlushForSysdiagnose fflush failed: %s (errno: %d, %s)\n"
+ "[%{ptr}] FlushForSysdiagnose fsync failed: %s (errno: %d, %s)\n"
+ "[%{ptr}] FlushForSysdiagnose: no active capture file, nothing to flush\n"
+ "[%{ptr}] NAN [%{ptr}] not recommended due to NAN throughput of %f with threshold of %f"
+ "[%{ptr}] NAN [%{ptr}] not recommended due to infra throughput ratio of %f with threshold of %f"
+ "[%{ptr}] NAN [%{ptr}] not recommended due to latency of %f with threshold of %f"
+ "[%{ptr}] NAN [%{ptr}] not recommended due to signal strength of %f with threshold of %f"
+ "[%{ptr}] Opened capture file: %s\n"
+ "[%{ptr}] Renamed capture file to: %s\n"
+ "[%{ptr}] Session stop: no active capture session, nothing to do\n"
+ "[%{ptr}] Start session %s (err: %#m)\n"
+ "captureDirectory"
+ "path"
+ "q24@?0@\"NSDictionary\"8@\"NSDictionary\"16"
+ "size"
+ "trafficCapture_closeAndRenameToFinal"
+ "trafficCapture_openSessionFile"
+ "transportDevice_isNANRecommended"
+ "void trafficCapture_enforceStorageLimits(APTransportTrafficCaptureRef)"
- "980.63.2"
- "APTransportTrafficCaptureStartSession_block_invoke"
- "APTransportTrafficCaptureStopSession_block_invoke"
- "OSStatus APTransportTrafficCaptureStartSession(APTransportTrafficCaptureRef, const char *, CFDictionaryRef)_block_invoke"
- "[%{ptr}] Start session for %s %s (err: %#m)\n"
```
