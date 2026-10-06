## filecoordinationd

> `/usr/sbin/filecoordinationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x88` | `0x80` | **`-0x8`** |
| `__TEXT.__text` | `0x16f0` | `0x16e8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5027.0.51.2.101
+5027.0.55.1.0
Functions:
~ _vfs_nspace_server_routine : 64 -> 60
~ _vfs_nspace_server : 156 -> 152
```
