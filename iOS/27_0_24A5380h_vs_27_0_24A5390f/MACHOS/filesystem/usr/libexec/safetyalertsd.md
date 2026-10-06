## safetyalertsd

> `/usr/libexec/safetyalertsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfdb50` | `0xfe188` | **`+0x638`** |
| `__TEXT.__oslogstring` | `0x432c5` | `0x4359a` | **`+0x2d5`** |
| `__TEXT.__gcc_except_tab` | `0xeed4` | `0xef60` | **`+0x8c`** |
| `__TEXT.__unwind_info` | `0x43d0` | `0x4408` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x89d8` | `0x89b8` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x5b8` | `0x5c8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x10c0` | `0x10b0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x870` | `0x868` | **`-0x8`** |
| `__TEXT.__cstring` | `0x7a52` | `0x7a5a` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-70.0.17.0.0
+70.0.19.0.0

-  Functions: 3602
-  Symbols:   470
-  CStrings:  5100
+  Functions: 3605
+  Symbols:   469
+  CStrings:  5108
Symbols:
- _dispatch_after
CStrings:
+ "cleanupStaleAlertsAndNotifications"
+ "{\"msg%{public}.0s\":\"#chNg,#getRBDChannelsListForAlertType,invalid locationd\"}"
+ "{\"msg%{public}.0s\":\"#daemon,cleanupGeoAlertCache,completed\", \"removedCount\":%{public}lu, \"remainingCount\":%{public}lu, \"writeSucceeded\":%{public}hhd}"
+ "{\"msg%{public}.0s\":\"#daemon,writeGeoAlertCacheFile,emptyPath\"}"
+ "{\"msg%{public}.0s\":\"#daemon,writeGeoAlertCacheFile,emptySerialization\"}"
+ "{\"msg%{public}.0s\":\"#daemon,writeGeoAlertCacheFile,nilCache\"}"
+ "{\"msg%{public}.0s\":\"#main,Daemon not supported, idling and letting launchd manage lifecycle\", \"isSupportedDevice\":%{private}hhd, \"isSupportedOSType\":%{private}hhd}"
+ "{\"msg%{public}.0s\":\"#notif,removeExpiredDeliveredNotifications,saMatch\", \"notifId\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#notif,removeExpiredDeliveredNotifications,totalDelivered\", \"totalDelivered\":%{public}lu}"
+ "{\"msg%{public}.0s\":\"#notif,removeExpiredDeliveredNotifications,zeroDelivered\", \"bundleId\":%{private, location:escape_only}s}"
- "removeExpiredNotifications"
- "{\"msg%{public}.0s\":\"#main,Daemon not supported, shutdown sequence will be initiated after idle timeout\", \"shutdownIdleTimeoutSeconds\":%{private}d, \"isSupportedDevice\":%{private}hhd, \"isSupportedOSType\":%{private}hhd}"
```
