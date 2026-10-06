## libBacktraceRecording.dylib

> `/usr/lib/libBacktraceRecording.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5948` | `0x59a8` | **`+0x60`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-64578.47.1.0.0
+64578.53.1.0.0
Functions:
~ _get_entry_from_free_list : 372 -> 400
~ _gcd_queue_item_enqueue_hook : 1252 -> 1248
~ _resetDyldInsertLibraries : 436 -> 424
~ _print_logical_backtrace : 1488 -> 1540
~ _backtrace_contains_function : 416 -> 428
~ _print_queue_item : 1604 -> 1608
~ _print_gcd_queue_item_enqueue_dequeue : 844 -> 848
~ _print_gcd_queue_item_complete : 768 -> 764
~ _print_backtrace : 572 -> 564
~ _print_dispatch_info : 556 -> 584
~ _print_logical_backtrace : 756 -> 752
```
