## AudioAnalyticsExternal

> `/System/Library/PrivateFrameworks/AudioAnalyticsExternal.framework/AudioAnalyticsExternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68c14` | `0x68b2c` | **`-0xe8`** |
| `__AUTH.__data` | `0x7f0` | `0x750` | **`-0xa0`** |
| `__DATA.__data` | `0x5f0` | `0x550` | **`-0xa0`** |
| `__TEXT.__oslogstring` | `0x2a5e` | `0x2afe` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x2120` | `0x2088` | **`-0x98`** |
| `__TEXT.__swift5_reflstr` | `0x1baa` | `0x1b2a` | **`-0x80`** |
| `__TEXT.__constg_swiftt` | `0x1408` | `0x1398` | **`-0x70`** |
| `__AUTH_CONST.__const` | `0x21d0` | `0x2178` | **`-0x58`** |
| `__TEXT.__swift5_typeref` | `0xe30` | `0xe88` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x1860` | `0x180c` | **`-0x54`** |
| `__AUTH.__objc_data` | `0x230` | `0x1e0` | **`-0x50`** |
| `__TEXT.__const` | `0x3258` | `0x3208` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0xfd8` | `0xfa8` | **`-0x30`** |
| `__TEXT.__swift5_builtin` | `0xb4` | `0xa0` | **`-0x14`** |
| `__AUTH_CONST.__auth_got` | `0x1280` | `0x1270` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x1dc` | `0x1e0` | **`+0x4`** |

### Other Changes

```diff

-291.1.0.0.0
+294.0.0.0.0

-  Functions: 1426
+  Functions: 1422
Symbols:
+ _get_type_metadata 15Synchronization6AtomicVySdG noncopyable
+ _symbolic Say_____10reporterID_SS7appNametG s5Int64V
+ _symbolic _____ 22AudioAnalyticsExternal15SessionRegistry33_3B265FC8C218B82212F5652CB909967DLLV
+ _symbolic _____10reporterID_SS7appNamet s5Int64V
+ _symbolic _____ySdG 15Synchronization6AtomicV
+ _symbolic _____y_____10reporterID_SS7appNametG s23_ContiguousArrayStorageC s5Int64V
+ _type_layout_string 22AudioAnalyticsExternal15SessionRegistry33_3B265FC8C218B82212F5652CB909967DLLV
- ___swift_memcpy4_4
- _get_type_metadata 15Synchronization5MutexVySdG noncopyable
- _swift_release_x9
- _symbolic _____ So16os_unfair_lock_sV
- _symbolic _____ySbG 15Synchronization5_CellVAARi_zrlE
- _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE So16os_unfair_lock_sV
- _type_layout_string So16os_unfair_lock_sV
CStrings:
+ "Dropping HID report. { reason=\"no active sessions\" }"
+ "Dropping HID report. { reason=\"unknown serial number\" }"
+ "Duplicate session registration. { reporterID=%{private}lld }"
+ "Firing packet. { reportID=%{private}hhu, interval=%{private}u }"
+ "Found AV device, starting AV session. { reporterID=%lld }"
+ "Registered session. { reporterID=%{private}lld, appName=%{private}s, numActiveSessions=%ld }"
+ "Stopping AV session. { reporterID=%lld }"
+ "Unknown session at unregister. { reporterID=%{private}lld }"
+ "Unregistered session. { reporterID=%{private}lld, appName=%{private}s, numActiveSessions=%ld }"
- "Couldn't find appName in sessionInfo. { appName=%{private}s }"
- "Firing packet { reportID=%{private}hhu, interval=%{private}u}"
- "Found AV device, starting AV session"
- "No active AdaptiveVolumeSession"
- "Starting AV manager"
- "Starting session. { appName=%{private}s }"
- "Stopping AV manager"
- "Stopping session. { appName=%{private}s, numActiveSessions=%ld }"
- "Updated activeAppName. { activeAppName=%{private}s }"
```
