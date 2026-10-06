## libsystem_platform_debug.dylib

> `/System/DriverKit/usr/lib/system/libsystem_platform_debug.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__script_config` | `0x8000` | `0x4000` | **`-0x4000`** |
| `__TEXT.__text` | `0xa7fc` | `0xa72c` | **`-0xd0`** |
| `__TEXT.__cstring` | `0x7f2` | `0x795` | **`-0x5d`** |
| `__TEXT.__auth_stubs` | `0x1c0` | `0x1b0` | **`-0x10`** |
| `__TEXT.__const` | `0xb0` | `0xc0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xe0` | `0xd8` | **`-0x8`** |

### Same-size Content Changes

- `__AUTH_CONST.__const`
- `__DATA_DIRTY.__la_resolver`
- `__TEXT.__eh_frame`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-402.0.0.0.0
+402.0.1.0.0

-  Functions: 265
-  Symbols:   312
-  CStrings:  56
+  Functions: 263
+  Symbols:   310
+  CStrings:  54
Symbols:
- ___restrictions_config
- _mach_vm_protect
CStrings:
- "BUG IN LIBPLATFORM: Failed to freeze config."
- "BUG IN LIBPLATFORM: Failed to reprotect config."
```
