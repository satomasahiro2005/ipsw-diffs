## libBKDM2.dylib

> `/usr/lib/libBKDM2.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7bae0` | `0x7c434` | **`+0x954`** |
| `__AUTH.__objc_data` | `0x4b0` | `0x1e0` | **`-0x2d0`** |
| `__DATA_DIRTY.__objc_data` | `0x410` | `0x6e0` | **`+0x2d0`** |
| `__AUTH_CONST.__cfstring` | `0x64e0` | `0x65a0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x6f88` | `0x703d` | **`+0xb5`** |
| `__TEXT.__oslogstring` | `0x45af` | `0x465c` | **`+0xad`** |
| `__AUTH_CONST.__objc_const` | `0x98c8` | `0x9948` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1580` | `0x15e8` | **`+0x68`** |
| `__DATA_DIRTY.__bss` | `0x60` | `0xa0` | **`+0x40`** |
| `__DATA.__bss` | `0x80` | `0x49` | **`-0x37`** |
| `__TEXT.__gcc_except_tab` | `0x1758` | `0x177c` | **`+0x24`** |
| `__AUTH_CONST.__const` | `0xbe8` | `0xc08` | **`+0x20`** |
| `__DATA.__data` | `0x898` | `0x880` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0xdf8` | `0xe10` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `—` | `0x14` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0xaa0` | `0xab0` | **`+0x10`** |
| `__TEXT.__const` | `0xd7a8` | `0xd7b8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d20` | `0x3d28` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x5d24` | `0x5d2c` | **`+0x8`** |

### Other Changes

```diff

-979.0.0.0.2
+980.0.0.0.10

-  Functions: 2884
-  Symbols:   4315
-  CStrings:  1595
+  Functions: 2895
+  Symbols:   4330
+  CStrings:  1607
Symbols:
+ +[BLHelper deviceModelString]
+ GCC_except_table218
+ GCC_except_table228
+ GCC_except_table237
+ GCC_except_table241
+ GCC_except_table244
+ GCC_except_table247
+ GCC_except_table253
+ GCC_except_table254
+ GCC_except_table260
+ GCC_except_table262
+ GCC_except_table263
+ _OBJC_IVAR_$_BiometricKitXPCServerPearl._secureFaceDetectMatchRetryType
+ _OBJC_IVAR_$_BiometricKitXPCServerPearl._secureFaceDetectMessagingQueue
+ _OBJC_IVAR_$_BiometricKitXPCServerPearl._secureFaceDetectPeriocularMatchState
+ _OBJC_IVAR_$_BiometricKitXPCServerPearl._secureFaceDetectRestartAfterStop
+ _OUTLINED_FUNCTION_59
+ ___29+[BLHelper deviceModelString]_block_invoke
+ ___52-[BiometricKitXPCServerPearl processCoachingStatus:]_block_invoke
+ ___66-[BiometricKitXPCServerPearl processMetadataObjects:fromCameraID:]_block_invoke
+ ___66-[BiometricKitXPCServerPearl processMetadataObjects:fromCameraID:]_block_invoke_2
+ ___block_descriptor_41_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_84_e8_32s_e5_v8?0ls32l8
+ _deviceModelString.modelString
+ _deviceModelString.onceToken
- GCC_except_table213
- GCC_except_table232
- GCC_except_table236
- GCC_except_table239
- GCC_except_table242
- GCC_except_table248
- GCC_except_table249
- GCC_except_table255
- GCC_except_table257
- GCC_except_table258
CStrings:
+ "Enroll"
+ "FaceDetect"
+ "HWModelStr"
+ "Match"
+ "Unknown"
+ "_avcStartStopQueue"
+ "_secureFaceDetectInterruptionDispatchSource"
+ "_secureFaceDetectMessagingQueue"
+ "com.apple.pearld.sfdMessaging"
+ "device_model"
+ "processSecureFaceDetectRequestMessage: start:<%{public}@> sequenceNumber:%u matchRetryType:%u periocularMatchState:0x%x\n"
+ "stopSecureFaceDetect: trying to restart after stop\n"
```
