## libsystem_malloc.dylib

> `/usr/lib/system/libsystem_malloc.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4329c` | `0x43304` | **`+0x68`** |
| `__DATA.__bss` | `0x210c` | `0x2114` | **`+0x8`** |

### Other Changes

```diff

-886.0.4.0.0
+886.0.8.0.0

-  Functions: 1102
+  Functions: 1101
Symbols:
+ __msl_lock
+ _msl_registered
- __register_msl_dylib_pred
- _register_msl_dylib
Functions:
~ __malloc_fork_prepare : 240 -> 284
~ __malloc_fork_parent : 216 -> 256
~ __malloc_register_stack_logger : 236 -> 644
- _register_msl_dylib
~ __malloc_fork_child : 228 -> 236
```
