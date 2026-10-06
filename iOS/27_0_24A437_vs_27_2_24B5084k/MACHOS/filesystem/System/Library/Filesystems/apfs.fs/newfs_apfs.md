## newfs_apfs

> `/System/Library/Filesystems/apfs.fs/newfs_apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x51b00` | `0x51d68` | **`+0x268`** |
| `__DATA_CONST.__cfstring` | `0x140` | `0x180` | **`+0x40`** |
| `__TEXT.__cstring` | `0xfa1e` | `0xfa4e` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x8d0` | `0x8e0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x468` | `0x470` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x848` | `0x850` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`

### Other Changes

```diff

-3288.2.1.0.0
+3288.40.13.0.0

-  Functions: 715
-  Symbols:   156
-  CStrings:  1318
+  Functions: 717
+  Symbols:   157
+  CStrings:  1321
Symbols:
+ _IORegistryEntryCreateCFProperty
CStrings:
+ "3288.40.13"
+ "IOMatchCategory"
+ "btree_node_compact"
+ "mount_apfs"
- "3288.2.1"
```
