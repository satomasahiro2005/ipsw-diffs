## com.apple.driver.AppleSPU

> `com.apple.driver.AppleSPU`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0xc00` | **`+0xc00`** |
| `__TEXT_EXEC.__text` | `0x48240` | `0x48d70` | **`+0xb30`** |
| `__TEXT.__os_log` | `0xb29` | `0xbee` | **`+0xc5`** |
| `__TEXT.__cstring` | `0x5d68` | `0x5dab` | **`+0x43`** |
| `__TEXT.__const` | `0x358` | `0x388` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x17488` | `0x174a8` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x5f8` | `0x600` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1d0` | **`+0x8`** |

### Other Changes

```diff

-1084.0.0.0.0
-  Functions: 2321
+1087.0.0.0.0
+  Functions: 2330

-  CStrings:  962
+  CStrings:  968
CStrings:
+ "1211111212221212111111111222222"
+ "12111112122212121111111211111122111111222222"
+ "AppleSPUGNSSDriver::_setDataNotificationPortGated kIOReturnNotReady"
+ "AppleSPUGNSSDriver::_setDataQueueGated kIOReturnExclusiveAccess"
+ "AppleSPUGNSSDriver::_setEventQueueGated kIOReturnExclusiveAccess"
+ "IMMERSION_TEMP"
+ "aop_flip"
+ "com.apple.aop.hid-driver.hid-service.cma"
- "121111121222121211111111122222"
- "1211111212221212111111121111112211111122222"
```
