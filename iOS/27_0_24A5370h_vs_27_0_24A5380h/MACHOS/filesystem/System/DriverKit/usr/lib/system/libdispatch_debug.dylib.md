## libdispatch_debug.dylib

> `/System/DriverKit/usr/lib/system/libdispatch_debug.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbba7c` | `0xbbb38` | **`+0xbc`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH_CONST.__auth_got`
- `__AUTH_CONST.__const`
- `__DATA_CONST.__const`
- `__TEXT.__dof_dispatch`
- `__TEXT.__dof_voucher`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ _firehose_buffer_stream_chunk_install : 4464 -> 4496
~ ____dispatch_transform_to_base32_with_table_block_invoke : 1668 -> 1760
~ ____dispatch_transform_to_base64_block_invoke : 1032 -> 1080
~ ____dispatch_transform_to_utf16_block_invoke : 1440 -> 1456
```
