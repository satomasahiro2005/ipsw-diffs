## libSavageUpdater_iOS.dylib

> `/usr/lib/updaters/libSavageUpdater_iOS.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ddec` | `0x1f3c4` | **`+0x15d8`** |
| `__TEXT.__cstring` | `0x4842` | `0x4a10` | **`+0x1ce`** |
| `__TEXT.__oslogstring` | `0xa60` | `0xb2a` | **`+0xca`** |
| `__AUTH_CONST.__auth_got` | `0x300` | `0x368` | **`+0x68`** |
| `__AUTH_CONST.__cfstring` | `0x1ea0` | `0x1ee0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x114` | `0x154` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0xa0` | `0xd0` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x88` | `0xa8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x4d8` | `0x4f8` | **`+0x20`** |
| `__TEXT.__const` | `0x638` | `0x648` | **`+0x10`** |

### Other Changes

```diff

-  Functions: 485
-  Symbols:   548
-  CStrings:  632
+  Functions: 490
+  Symbols:   571
+  CStrings:  648
Symbols:
+ GCC_except_table12
+ _OBJC_CLASS_$_NSMutableData
+ _OUTLINED_FUNCTION_55
+ _OUTLINED_FUNCTION_56
+ _OUTLINED_FUNCTION_57
+ __Block_object_assign
+ __Block_object_dispose
+ __NSConcreteStackBlock
+ ___block_descriptor_48_e8_32s40r_e8_v12?0i8l
+ ___copy_helper_block_e8_32s40r
+ ___destroy_helper_block_e8_32s40r
+ ___objc_personality_v0
+ ___waitForPearldReadiness_block_invoke
+ _dispatch_get_global_queue
+ _dispatch_semaphore_create
+ _dispatch_semaphore_signal
+ _dispatch_semaphore_wait
+ _dispatch_time
+ _notify_cancel
+ _notify_get_state
+ _notify_post
+ _notify_register_check
+ _notify_register_dispatch
CStrings:
+ "ApplePearlExclaveSEPDriver"
+ "Generating reference frames info record...\n"
+ "Reference frames info record written to %s\n"
+ "ReferenceFramesSetInfo, index: %zu, type: %d, count: %d, size: %d\n"
+ "Verifying new reference frames info record...\n"
+ "com.apple.pearld.check_secure_streaming"
+ "com.apple.pearld.ready"
+ "hamal"
+ "notifyResult == 0"
+ "outDataSize <= signedRefFramesInfoRecordData.length"
+ "pearldReady"
+ "reference-info-record.DAT"
+ "requestData"
+ "sema"
+ "signedRefFramesInfoRecordData"
+ "v12@?0i8"
```
