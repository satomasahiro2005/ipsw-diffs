## libsat

> `/System/Library/PrivateFrameworks/libsat.framework/libsat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81f8` | `0x8618` | **`+0x420`** |
| `__TEXT.__cstring` | `0x3e7` | `0x427` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x6c8` | `0x700` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x3e0` | `0x400` | **`+0x20`** |

### Other Changes

```diff

-113.0.0.0.0
+120.0.0.502.1

-  Functions: 305
-  Symbols:   416
-  CStrings:  45
+  Functions: 314
+  Symbols:   433
+  CStrings:  48
Symbols:
+ _SAT_TimeSyncClose
+ _SAT_TimeSyncEntrySize
+ _SAT_TimeSyncGetInfo
+ _SAT_TimeSyncOpen
+ _SAT_TimeSyncSetCallback
+ __ZL14_ts_drain_syncPv
+ __ZL17_ts_timer_handlerPv
+ __ZL8_ts_noopPv
+ __ZL9_ts_drainP20sat_timesync_session
+ __dispatch_source_type_timer
+ _dispatch_release
+ _dispatch_source_cancel
+ _dispatch_source_set_timer
+ _dispatch_sync_f
+ _dispatch_time
+ _free
+ _malloc_type_calloc
CStrings:
+ "120.0.0.502.1"
+ "AppleThunderboltSATTimeSyncPort"
+ "com.apple.sat.timesync"
```
