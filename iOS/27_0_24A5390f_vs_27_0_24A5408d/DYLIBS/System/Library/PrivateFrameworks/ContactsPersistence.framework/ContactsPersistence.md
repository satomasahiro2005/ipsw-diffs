## ContactsPersistence

> `/System/Library/PrivateFrameworks/ContactsPersistence.framework/ContactsPersistence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a9e0` | `0x4ad04` | **`+0x324`** |
| `__TEXT.__objc_methlist` | `0x522c` | `0x52ec` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0xb4b8` | `0xb530` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x31f0` | `0x3260` | **`+0x70`** |
| `__DATA.__data` | `0xe58` | `0xeb8` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1c08` | `0x1c58` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x4020` | `0x4060` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x634` | `0x674` | **`+0x40`** |
| `__TEXT.__cstring` | `0x306f` | `0x308f` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x15e8` | `0x15f8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x828` | `0x830` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x100` | `0x108` | **`+0x8`** |

### Other Changes

```diff

-3839.100.3.2.1
+3844.100.1.0.0

-  Functions: 2265
-  Symbols:   4164
-  CStrings:  843
+  Functions: 2270
+  Symbols:   4177
+  CStrings:  845
Symbols:
+ -[CNCDRemotePersistentStoreEndpointFactory _fetchEndpoint]
+ -[CNCDRemotePersistentStoreEndpointFactory maximumNumberOfAttemptsForRetry:]
+ -[CNCDRemotePersistentStoreEndpointFactory retry:delayAfterError:onAttempt:]
+ -[CNCDRemotePersistentStoreEndpointFactory retry:shouldContinueAfterError:onAttempt:]
+ _OBJC_CLASS_$_CNRetry
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CNRetryDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CNRetryDelegate
+ __OBJC_$_PROTOCOL_REFS_CNRetryDelegate
+ __OBJC_LABEL_PROTOCOL_$_CNRetryDelegate
+ __OBJC_PROTOCOL_$_CNRetryDelegate
+ ___58-[CNCDRemotePersistentStoreEndpointFactory _fetchEndpoint]_block_invoke
+ ___block_descriptor_40_e8_32s_e15_"CNResult"8?0ls32l8
+ ___block_descriptor_48_e8_32s40r_e17_v16?0"NSError"8lr40l8s32l8
CStrings:
+ "CNErrorDomain"
+ "Unknown XPC connection failure"
```
