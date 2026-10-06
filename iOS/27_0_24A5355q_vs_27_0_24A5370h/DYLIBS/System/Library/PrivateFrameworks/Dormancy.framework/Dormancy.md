## Dormancy

> `/System/Library/PrivateFrameworks/Dormancy.framework/Dormancy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6810` | `0x6c44` | **`+0x434`** |
| `__DATA_CONST.__objc_selrefs` | `0x30` | `—` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x460` | `0x448` | **`-0x18`** |
| `__TEXT.__eh_frame` | `0x1f0` | `0x1e8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x280` | `0x288` | **`+0x8`** |
| `__TEXT.__objc_stubs` | `0x0` | `—` | **`-0x0`** |

### Other Changes

```diff

-27.0.43.0.0
+27.0.50.0.0

-  - /System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary

-  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 224
-  Symbols:   201
+  Functions: 226
+  Symbols:   191
Symbols:
- _BiomeLibrary
- _OBJC_CLASS_$_BMDormancyRemoteUserInteraction
- _objc_allocWithZone
- _objc_msgSend
- _objc_release
- _objc_release_x20
- _objc_release_x21
- _objc_retainAutoreleasedReturnValue
- _swift_task_alloc
- _swift_task_dealloc
```
