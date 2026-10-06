## com.apple.plugin.IOgPTPPlugin

> `com.apple.plugin.IOgPTPPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x6fcec` | `0x70030` | **`+0x344`** |
| `__TEXT.__os_log` | `0x1c46f` | `0x1c585` | **`+0x116`** |
| `__TEXT.__cstring` | `0x6cc3` | `0x6d31` | **`+0x6e`** |
| `__DATA_CONST.__got` | `0x1b0` | `0x1b8` | **`+0x8`** |

### Other Changes

```diff

-1501.1.0.0.0
-  Functions: 1637
+1501.4.0.0.0
+  Functions: 1641

-  CStrings:  1569
+  CStrings:  1577
CStrings:
+ "121111121222121211111111111111111111211111111111111111111111"
+ "12111112122212121111111111111111222212121"
+ "Could not allocate number\n"
+ "IOTimeSyncNetworkPortUserClient: missing entitlement %s\n"
+ "IOTimeSyncgPTPManagerUserClient: missing entitlement %s\n"
+ "NULL == fIOTimeSyncgPTPManagerLock"
+ "com.apple.private.timesync.direct-userclient"
+ "fTimeSyncDomainLock != NULL"
+ "failed to allocate gPTP manager lock\n"
+ "super::start failed\n"
- "12111112122212121111111111111111111121111111111111111111111"
- "1211111212221212111111111111111222212121"
```
