## _AppIntentsServices_ToolKit

> `/System/Library/PrivateFrameworks/_AppIntentsServices_ToolKit.framework/_AppIntentsServices_ToolKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x102b0` | `0x10f34` | **`+0xc84`** |
| `__TEXT.__eh_frame` | `0x440` | `0x518` | **`+0xd8`** |
| `__TEXT.__oslogstring` | `0x3be` | `0x45e` | **`+0xa0`** |
| `__AUTH_CONST.__auth_got` | `0x728` | `0x780` | **`+0x58`** |
| `__TEXT.__cstring` | `0x22a` | `0x24a` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x340` | `0x360` | **`+0x20`** |
| `__DATA.__common` | `0x30` | `0x48` | **`+0x18`** |
| `__DATA.__data` | `0x238` | `0x248` | **`+0x10`** |
| `__TEXT.__const` | `0x5f0` | `0x5e8` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x274` | `0x27c` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `—` | `0x4` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-41.0.50.0.0
+41.1.9.0.0

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 328
-  Symbols:   295
-  CStrings:  33
+  Functions: 342
+  Symbols:   303
+  CStrings:  36
Symbols:
+ ___swift_async_cont_functlets
+ ___swift_async_entry_functlets
+ ___swift_async_ret_functlets
+ ___swift_destroy_boxed_opaque_existential_0
+ _swift_task_alloc
+ _swift_task_dealloc
+ _swift_task_switch
+ _symbolic _____Sg 18AppIntentsServices13SchemaVersionV
CStrings:
+ "Skipping remote prewarm: App Intent tool %s has no backing App Intent action identifier"
+ "Skipping remote prewarm: tool %s is not an App Intent"
+ "remoteDispatcher"
```
