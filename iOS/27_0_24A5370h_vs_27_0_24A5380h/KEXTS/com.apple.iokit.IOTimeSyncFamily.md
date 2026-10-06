## com.apple.iokit.IOTimeSyncFamily

> `com.apple.iokit.IOTimeSyncFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__os_log` | `0x8af5` | `0x8cdf` | **`+0x1ea`** |
| `__TEXT_EXEC.__text` | `0x312f8` | `0x314d8` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x3eaa` | `0x3ee0` | **`+0x36`** |

### Other Changes

```diff

-1501.1.0.0.0
-  Functions: 1486
+1501.4.0.0.0
+  Functions: 1488

-  CStrings:  721
+  CStrings:  730
CStrings:
+ "12111112122212121111111111111111111111211"
+ "1211111212221212111111111111111122111111"
+ "IOTimeSyncClockManagerUserClient: missing entitlement %s\n"
+ "IOTimeSyncClockTestUserClient: missing entitlement %s\n"
+ "IOTimeSyncEdgeTimeCaptureUserClient: missing entitlement %s\n"
+ "IOTimeSyncSyncUserClient: missing entitlement %s\n"
+ "IOTimeSyncTimedEdgeGeneratorUserClient: missing entitlement %s\n"
+ "IOTimeSyncUserClient: missing entitlement %s\n"
+ "NULL == fIOTimeSyncClockManagerLock"
+ "com.apple.private.timesync.direct-userclient"
+ "failed to allocate clock manager lock\n"
+ "failed to allocate service lock\n"
+ "super::start failed\n"
+ "superStarted"
- "1211111212221212111111111111111111111211"
- "121111121222121211111111111111122111111"
- "Not entitled\n"
- "entitlement"
- "entitlement == kOSBooleanTrue"
```
