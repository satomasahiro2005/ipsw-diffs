## libBacktraceRecording.dylib

> `/usr/lib/libBacktraceRecording.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59a8` | `0x5998` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-64578.53.1.0.0
+64578.53.2.0.0
Functions:
~ _get_entry_from_free_list : 400 -> 368
~ _resetDyldInsertLibraries : 424 -> 428
~ _backtrace_contains_function : 428 -> 440
```
