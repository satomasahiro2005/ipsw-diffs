## libdispatch.dylib

> `/usr/lib/system/introspection/libdispatch.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x433e0` | `0x433d8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xe80` | `0xe88` | **`+0x8`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH_CONST.__auth_got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```text
Functions:
~ __os_workgroup_lookup_type_from_workload_id : 164 -> 172
~ ___dispatch_io_create_with_path_block_invoke : 664 -> 668
~ _dispatch_data_copy_region : 356 -> 368
~ _dispatch_introspection_get_queues : 384 -> 364
~ _dispatch_introspection_get_queue_threads : 472 -> 460
```
