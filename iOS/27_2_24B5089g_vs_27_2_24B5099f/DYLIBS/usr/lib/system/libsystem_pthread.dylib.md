## libsystem_pthread.dylib

> `/usr/lib/system/libsystem_pthread.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa6f8` | `0xa67c` | **`-0x7c`** |
| `__DATA.__data` | `0x10` | `0x8` | **`-0x8`** |

### Other Changes

```diff

-  Functions: 312
-  Symbols:   397
+  Functions: 311
+  Symbols:   396
Symbols:
- _get_xprr_version.cached_xprr_version
Functions:
~ ___pthread_init : 1216 -> 1188
~ _pthread_jit_write_protect_supported_np : 48 -> 24
~ _pthread_jit_write_with_callback_np : 304 -> 292
~ _pthread_jit_write_freeze_callbacks_np : 156 -> 132
- _OUTLINED_FUNCTION_1
~ _pthread_jit_write_with_callback_np.cold.2 : 612 -> 596
```
