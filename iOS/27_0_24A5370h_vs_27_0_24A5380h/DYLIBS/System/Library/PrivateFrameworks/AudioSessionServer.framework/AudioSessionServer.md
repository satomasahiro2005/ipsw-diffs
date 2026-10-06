## AudioSessionServer

> `/System/Library/PrivateFrameworks/AudioSessionServer.framework/AudioSessionServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4df9` | `0x48ff` | **`-0x4fa`** |
| `__TEXT.__text` | `0x6f3d4` | `0x6ef38` | **`-0x49c`** |
| `__TEXT.__oslogstring` | `0x52ea` | `0x52a3` | **`-0x47`** |
| `__AUTH_CONST.__objc_const` | `0xe40` | `0xe00` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0xa63c` | `0xa600` | **`-0x3c`** |
| `__DATA.__bss` | `0x50` | `0x40` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2d40` | `0x2d30` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x6c` | `0x64` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x4d8` | `0x4e0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x898` | `0x8a0` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x388` | `0x390` | **`+0x8`** |

### Other Changes

```diff

-449.101.0.0.0
+449.102.0.0.0

-  Functions: 1671
-  Symbols:   2602
-  CStrings:  1025
+  Functions: 1673
+  Symbols:   2595
+  CStrings:  1005
Symbols:
+ GCC_except_table110
+ GCC_except_table138
+ GCC_except_table183
+ GCC_except_table186
+ _OBJC_CLASS_$_NSXPCConnection
+ __ZL28AudioSessionServerXPCTimeoutv
+ __ZZL28AudioSessionServerXPCTimeoutvE8onceFlag
+ ___block_descriptor_100_ea8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
+ ___block_descriptor_92_ea8_32s40r_e5_v8?0lr40l8s32l8
- GCC_except_table100
- GCC_except_table105
- GCC_except_table118
- GCC_except_table122
- GCC_except_table145
- GCC_except_table169
- GCC_except_table177
- GCC_except_table181
- GCC_except_table184
- _OBJC_IVAR_$_AVAudioSessionRemoteXPCClient._replyWatchdogFunctionName
- _OBJC_IVAR_$_AVAudioSessionRemoteXPCClient._replyWatchdogMinTimestamp
- __ZL28AudioSessionServerXPCTimeoutPKc
- __ZNSt3__16chrono12system_clock3nowEv
- __ZZL28AudioSessionServerXPCTimeoutPKcE8onceFlag
- ___block_descriptor_100_ea8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
- ___block_descriptor_92_ea8_32s40bs_e5_v8?0ls32l8s40l8
CStrings:
+ "XPC message timeout in AudioSessionServer, probably deadlocked. Writing a stackshot and terminating."
- "%25s:%-5d XPC watchdog timer fired too soon, skipping timeout handling"
- ", probably deadlocked. Writing a stackshot and terminating."
- "-[AVAudioSessionRemoteXPCClient addMXNotificationListener:notificationName:reply:]"
- "-[AVAudioSessionRemoteXPCClient createIONodeWithSourceSession:sessionOwnerPID:playerType:reply:]"
- "-[AVAudioSessionRemoteXPCClient createSession:reply:]"
- "-[AVAudioSessionRemoteXPCClient getDeferredMessagesForSessions:reply:]"
- "-[AVAudioSessionRemoteXPCClient getIOControllerPeriod:decoupledInput:reply:]"
- "-[AVAudioSessionRemoteXPCClient getMXPropertyGenericPipe:propertyName:reply:]"
- "-[AVAudioSessionRemoteXPCClient getProperties:properties:genericMXPipe:reply:]"
- "-[AVAudioSessionRemoteXPCClient getPropertiesForCache:reply:]"
- "-[AVAudioSessionRemoteXPCClient getPropertiesIONode:properties:reply:]"
- "-[AVAudioSessionRemoteXPCClient getProperty:propertyName:MXProperty:reply:]"
- "-[AVAudioSessionRemoteXPCClient invalidateIONode:reply:]"
- "-[AVAudioSessionRemoteXPCClient removeMXNotificationListener:notificationName:reply:]"
- "-[AVAudioSessionRemoteXPCClient setMXPropertyOnAllSessions:clientID:MXProperty:values:reply:]"
- "-[AVAudioSessionRemoteXPCClient setProperties:values:MXProperties:batchStrategy:genericMXPipe:reply:]"
- "-[AVAudioSessionRemoteXPCClient setPropertiesIONode:values:reply:]"
- "-[AVAudioSessionRemoteXPCClient toggleInputMuteForRecordingProcess:]"
- "-[AVAudioSessionRemoteXPCClient verifySessionExists:reply:]"
- "XPC message timeout in "
- "unknown"
```
