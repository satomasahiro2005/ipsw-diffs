## apfs_condenser

> `/System/Library/Filesystems/apfs.fs/apfs_condenser`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4d0ac` | `0x4d294` | **`+0x1e8`** |
| `__TEXT.__cstring` | `0xf7b0` | `0xf7c5` | **`+0x15`** |
| `__TEXT.__unwind_info` | `0x828` | `0x830` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`

### Other Changes

```diff

-3288.2.1.0.0
+3288.40.13.0.0

-  Functions: 681
+  Functions: 682

-  CStrings:  1265
+  CStrings:  1266
CStrings:
+ "3288.40.13"
+ "btree_node_compact"
- "3288.2.1"
```
