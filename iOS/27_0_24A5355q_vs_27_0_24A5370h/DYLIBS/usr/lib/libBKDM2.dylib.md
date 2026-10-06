## libBKDM2.dylib

> `/usr/lib/libBKDM2.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7b780` | `0x7bae0` | **`+0x360`** |
| `__AUTH_CONST.__objc_const` | `0x9868` | `0x98c8` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x45dd` | `0x45af` | **`-0x2e`** |
| `__AUTH_CONST.__auth_got` | `0x700` | `0x728` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x64c0` | `0x64e0` | **`+0x20`** |
| `__DATA.__bss` | `0x68` | `0x80` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x78` | `0x60` | **`-0x18`** |
| `__DATA_CONST.__const` | `0x1570` | `0x1580` | **`+0x10`** |
| `__TEXT.__cstring` | `0x6f96` | `0x6f88` | **`-0xe`** |
| `__DATA.__objc_ivar` | `0xa94` | `0xaa0` | **`+0xc`** |
| `__DATA.__data` | `0x890` | `0x898` | **`+0x8`** |
| `__TEXT.__const` | `0xd7a0` | `0xd7a8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xe00` | `0xdf8` | **`-0x8`** |

### Other Changes

```diff

-968.0.0.0.0
+979.0.0.0.2

-  Functions: 2880
-  Symbols:   4305
-  CStrings:  1594
+  Functions: 2884
+  Symbols:   4315
+  CStrings:  1595
Symbols:
+ -[BiometricKitXPCServerPearl processLastSecureFaceDetectRequestMessage]
+ _OBJC_IVAR_$_BiometricKitXPCServerPearl._lastSecureFaceDetectRequestMessage
+ _OBJC_IVAR_$_BiometricKitXPCServerPearl._lastSecureFaceDetectRequestMessageValid
+ _OBJC_IVAR_$_BiometricKitXPCServerPearl._secureFaceDetectPaused
+ _OUTLINED_FUNCTION_58
+ __MergedGlobals
+ __oidSmtpUTF8Mailbox
+ __pearldReadinessToken
+ _notify_cancel
+ _notify_get_state
+ _notify_post
+ _notify_register_check
+ _notify_set_state
+ _oidSmtpUTF8Mailbox
- -[BiometricKitXPCServerPearl processMergedSecureFaceDetectRequestMessage]
- ___listener
- ___xpcListenerQueue
- ___xpcServer
CStrings:
+ "ComponentIndex"
+ "_pearldReadinessToken == -1"
+ "com.apple.pearld.ready"
+ "notifyResult == 0"
- "_secureFaceDetectRequest == kSecureFDRequestMatch"
- "message->sessionID == _secureFaceDetectSessionID"
- "processSecureFaceDetectRequestMessage: pause\n"
```
