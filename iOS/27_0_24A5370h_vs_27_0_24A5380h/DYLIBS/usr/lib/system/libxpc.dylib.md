## libxpc.dylib

> `/usr/lib/system/libxpc.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53010` | `0x52fe0` | **`-0x30`** |
| `__DATA.__bss` | `0x70` | `0x58` | **`-0x18`** |
| `__DATA_DIRTY.__bss` | `0x120` | `0x138` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x1d8` | **`-0x8`** |

### Other Changes

```diff

-3298.0.4.502.1
+3298.0.10.0.0
Functions:
~ __xpc_date_hash : 48 -> 40
~ __xpc_double_hash : 48 -> 40
~ __xpc_int64_hash : 248 -> 240
~ __xpc_uint64_hash : 248 -> 240
~ __xpc_uuid_hash : 48 -> 40
~ __xpc_pointer_hash : 48 -> 40
```
