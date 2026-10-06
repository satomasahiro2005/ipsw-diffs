## libcmark-gfm.dylib

> `/usr/lib/libcmark-gfm.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24514` | `0x24bbc` | **`+0x6a8`** |
| `__DATA.__bss` | `0x110` | `0x210` | **`+0x100`** |
| `__DATA.__data` | `0x100` | `0x150` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x410` | `0x458` | **`+0x48`** |
| `__AUTH.__data` | `0x30` | `0x50` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xd8` | `0xf8` | **`+0x20`** |

### Other Changes

```diff

-1.29.0.18.0
+1.29.0.19.0

-  Functions: 446
-  Symbols:   447
+  Functions: 467
+  Symbols:   478
Symbols:
+ _arena_calloc_typed
+ _arena_lock
+ _arena_once
+ _arena_realloc_typed
+ _cmark_mem_calloc
+ _cmark_mem_calloc_typed
+ _cmark_mem_free
+ _cmark_mem_realloc
+ _cmark_mem_realloc_typed
+ _extensions_lock
+ _extensions_once
+ _free_table_row
+ _init_arena
+ _initialize_arena
+ _initialize_extensions
+ _initialize_nextflag
+ _initialize_safety
+ _make_simple
+ _nextflag_lock
+ _nextflag_once
+ _pthread_mutex_init
+ _pthread_mutex_lock
+ _pthread_mutex_unlock
+ _pthread_once
+ _push_bracket
+ _push_delimiter
+ _register_plugins
+ _registered_once
+ _safety_lock
+ _safety_once
+ _xcalloc_typed
+ _xrealloc_typed
- _registered
```
