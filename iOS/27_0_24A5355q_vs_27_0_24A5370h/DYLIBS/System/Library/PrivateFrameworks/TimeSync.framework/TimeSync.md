## TimeSync

> `/System/Library/PrivateFrameworks/TimeSync.framework/TimeSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5932c` | `0x59ad4` | **`+0x7a8`** |
| `__TEXT.__oslogstring` | `0x492c` | `0x4bd7` | **`+0x2ab`** |
| `__DATA_CONST.__const` | `0x10b8` | `0x1170` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x1aa0` | `0x1ae8` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0xf80` | `0xfc0` | **`+0x40`** |
| `__TEXT.__const` | `0x298` | `0x2b0` | **`+0x18`** |
| `__TEXT.__cstring` | `0x83c7` | `0x83d8` | **`+0x11`** |
| `__DATA_CONST.__objc_selrefs` | `0x2820` | `0x2830` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x6e54` | `0x6e64` | **`+0x10`** |

### Other Changes

```diff

-1500.96.0.0.0
+1501.1.0.0.0

-  Functions: 2913
-  Symbols:   4459
-  CStrings:  1257
+  Functions: 2924
+  Symbols:   4473
+  CStrings:  1264
Symbols:
+ -[_TSF_TSDKernelClock _dispatchLockState:onlyIfChanged:]
+ GCC_except_table26
+ _OUTLINED_FUNCTION_18
+ ___56-[_TSF_TSDKernelClock _dispatchLockState:onlyIfChanged:]_block_invoke
+ ___TimeSyncClockAddAWDLPortAndGetIdentity_block_invoke
+ ___TimeSyncClockAddAWDLPortAndGetIdentity_block_invoke_2
+ ___TimeSyncClockAddUDPv4EndToEndPortAndGetIdentity_block_invoke
+ ___TimeSyncClockAddUDPv4EndToEndPortAndGetIdentity_block_invoke_2
+ ___TimeSyncClockAddUDPv6EndToEndPortAndGetIdentity_block_invoke
+ ___TimeSyncClockAddUDPv6EndToEndPortAndGetIdentity_block_invoke_2
+ ___block_descriptor_46_e20_v20?0B8"NSError"12l
+ ___block_descriptor_50_e20_v20?0B8"NSError"12l
+ ___block_descriptor_52_e8_32s40r_e5_v8?0ls32l8r40l8
+ ___block_descriptor_52_e8_32s_e9_B16?0^8ls32l8
+ ___block_descriptor_56_e8_32s_e9_B16?0^8ls32l8
+ __tsVerifyOrRollbackAddedPort
- ___59-[_TSF_TSDKernelClock _refreshLockStateOnNotificationQueue]_block_invoke
- ___64-[_TSF_TSDKernelClock _handleInterestNotification:withArgument:]_block_invoke
CStrings:
+ "(none)"
+ "B16@?0^@8"
+ "TSDCKernelClock(0x%016llx) didChangeLockStateTo: %u"
+ "add succeeded but port number is 0xffff; rolling back to balance kernel refcount"
+ "rollback for %@ -> %02hhx%02hhx:%02hhx%02hhx:%02hhx%02hhx:%02hhx%02hhx:%02hhx%02hhx:%02hhx%02hhx:%02hhx%02hhx:%02hhx%02hhx (port %hu) failed: rolledBack=%d, error=%s; kernel refcount may be leaked"
+ "rollback for %@ -> %hhu.%hhu.%hhu.%hhu (port %hu) failed: rolledBack=%d, error=%s; kernel refcount may be leaked"
+ "rollback for AWDL %@ -> %02hhx:%02hhx:%02hhx:%02hhx:%02hhx:%02hhx (port %hu) failed: rolledBack=%d, error=%s; kernel refcount may be leaked"
+ "rollback got kIOReturnNotFound: slot already purged by interfaceTerminated (benign race), or rarely a wrong-type entry left the refcount unbalanced"
- "TSDCKernelClock(0x%016llx) didChangeLockStateTo"
```
