## Diagnostic-9006

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9006.appex/Diagnostic-9006`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3eec` | `0x4514` | **`+0x628`** |
| `__TEXT.__objc_stubs` | `0x11c0` | `0x1300` | **`+0x140`** |
| `__DATA_CONST.__cfstring` | `0x500` | `0x5a0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x3eb` | `0x46a` | **`+0x7f`** |
| `__TEXT.__auth_stubs` | `0x2c0` | `0x330` | **`+0x70`** |
| `__DATA_CONST.__const` | `0xb0` | `0x100` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x1fbb` | `0x2007` | **`+0x4c`** |
| `__TEXT.__oslogstring` | `0x10f` | `0x14f` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x170` | `0x1a8` | **`+0x38`** |
| `__DATA_CONST.__got` | `0xc8` | `0xf8` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x828` | `0x840` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xd8` | `0xe8` | **`+0x10`** |
| `__TEXT.__const` | `0x78` | `0x80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 88
-  Symbols:   89
-  CStrings:  486
+  Functions: 91
+  Symbols:   102
+  CStrings:  498
Symbols:
+ _CRErrorDomain
+ _MGGetBoolAnswer
+ _NSLocalizedDescriptionKey
+ _OBJC_CLASS_$_CRPreflightController
+ _OBJC_CLASS_$_CRRepairStatus
+ _OBJC_CLASS_$_NSError
+ __dispatch_main_q
+ _dispatch_async
+ _dispatch_get_global_queue
+ _dispatch_semaphore_signal
+ _dispatch_time
+ _objc_retain_x19
+ _objc_retain_x21
CStrings:
+ "1"
+ "InDiagnosticsMode"
+ "InternalBuild"
+ "Preflight error: %@"
+ "Preflight results: %@"
+ "Preflight success: %d"
+ "Preflight time out"
+ "Service part mTub/MLB not supported"
+ "errorWithDomain:code:userInfo:"
+ "isServicePartWithError:"
+ "preflight:withReply:"
+ "v28@?0B8@\"NSDictionary\"12@\"NSError\"20"
```
