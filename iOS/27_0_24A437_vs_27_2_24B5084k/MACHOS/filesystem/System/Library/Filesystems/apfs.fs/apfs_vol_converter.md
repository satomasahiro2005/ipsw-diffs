## apfs_vol_converter

> `/System/Library/Filesystems/apfs.fs/apfs_vol_converter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a91c` | `0x5ab8c` | **`+0x270`** |
| `__DATA_CONST.__cfstring` | `0xb40` | `0xb80` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1203c` | `0x1206c` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xcb0` | `0xcb8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`

### Other Changes

```diff

-3288.2.1.0.0
+3288.40.13.0.0

-  Functions: 906
+  Functions: 908

-  CStrings:  1614
+  CStrings:  1617
CStrings:
+ "3288.40.13"
+ "IOMatchCategory"
+ "btree_node_compact"
+ "mount_apfs"
- "3288.2.1"
```
