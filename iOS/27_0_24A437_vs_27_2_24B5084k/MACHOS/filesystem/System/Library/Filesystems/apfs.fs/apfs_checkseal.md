## apfs_checkseal

> `/System/Library/Filesystems/apfs.fs/apfs_checkseal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4fef8` | `0x500dc` | **`+0x1e4`** |
| `__TEXT.__cstring` | `0x10104` | `0x10117` | **`+0x13`** |
| `__TEXT.__unwind_info` | `0x900` | `0x908` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`

### Other Changes

```diff

-3288.2.1.0.0
+3288.40.13.0.0

-  Functions: 747
+  Functions: 748

-  CStrings:  1294
+  CStrings:  1295
CStrings:
+ "btree_node_compact"
```
