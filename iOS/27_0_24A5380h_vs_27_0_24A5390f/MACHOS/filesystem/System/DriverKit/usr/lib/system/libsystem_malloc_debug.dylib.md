## libsystem_malloc_debug.dylib

> `/System/DriverKit/usr/lib/system/libsystem_malloc_debug.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf0860` | `0xf0b64` | **`+0x304`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH.__v_zone`
- `__AUTH_CONST.__const`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__dof_magmalloc`
- `__TEXT.__eh_frame`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-886.0.4.0.0
+886.0.8.0.0

-  Symbols:   1471
+  Symbols:   1472
Symbols:
+ __msl_lock
+ _msl_registered
- __register_msl_dylib_pred
Functions:
~ __malloc_lock_all : 480 -> 700
~ __malloc_unlock_all : 440 -> 620
~ __malloc_reinit_lock_all : 412 -> 440
~ __malloc_register_stack_logger : 260 -> 604
```
