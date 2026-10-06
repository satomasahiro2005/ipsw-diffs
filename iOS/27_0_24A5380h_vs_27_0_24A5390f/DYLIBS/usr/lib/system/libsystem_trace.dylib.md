## libsystem_trace.dylib

> `/usr/lib/system/libsystem_trace.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b724` | `0x1b7cc` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x1c4a` | `0x1c6b` | **`+0x21`** |
| `__DATA.__bss` | `0x200` | `0x208` | **`+0x8`** |

### Other Changes

```diff

-1965.0.0.0.0
+1966.0.6.0.0

-  Functions: 380
-  Symbols:   859
-  CStrings:  419
+  Functions: 382
+  Symbols:   862
+  CStrings:  420
Symbols:
+ __os_trace_preferences_cache_path
+ __os_trace_prefscachedir_path
+ __os_trace_set_prefscachedir_path
Functions:
~ ____os_trace_paths_init_block_invoke : 84 -> 100
+ __os_trace_prefscachedir_path
+ __os_trace_set_prefscachedir_path
CStrings:
+ "/private/var/db/diagnostics/logd"
```
