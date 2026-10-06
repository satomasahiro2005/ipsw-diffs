## Diagnostic-8201

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8201.appex/Diagnostic-8201`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24494` | `0x25a54` | **`+0x15c0`** |
| `__TEXT.__cstring` | `0x65a3` | `0x676b` | **`+0x1c8`** |
| `__TEXT.__auth_stubs` | `0x830` | `0x900` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x9c4` | `0xa8e` | **`+0xca`** |
| `__TEXT.__objc_stubs` | `0xae0` | `0xb60` | **`+0x80`** |
| `__DATA_CONST.__auth_got` | `0x428` | `0x498` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x2bcc` | `0x2c0c` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0xc12` | `0xc46` | **`+0x34`** |
| `__DATA_CONST.__const` | `0x578` | `0x5a8` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x3c8` | `0x3e8` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x4aa0` | `0x4ac0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x7c0` | `0x7e0` | **`+0x20`** |
| `__TEXT.__const` | `0x248` | `0x258` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x358` | `0x360` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 490
-  Symbols:   423
-  CStrings:  1070
+  Functions: 495
+  Symbols:   438
+  CStrings:  1089
Symbols:
+ _IOServiceNameMatching
+ _OBJC_CLASS_$_NSMutableData
+ __Block_object_assign
+ __Block_object_dispose
+ ___objc_personality_v0
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
+ "appendData:"
+ "com.apple.pearld.check_secure_streaming"
+ "com.apple.pearld.ready"
+ "dataWithLength:"
+ "mutableBytes"
+ "notifyResult == 0"
+ "outDataSize <= signedRefFramesInfoRecordData.length"
+ "pearldReady"
+ "reference-info-record.DAT"
+ "requestData"
+ "sema"
+ "setLength:"
+ "signedRefFramesInfoRecordData"
+ "v12@?0i8"
```
