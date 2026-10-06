## apfs_iosd

> `/System/Library/Filesystems/apfs.fs/apfs_iosd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33eac` | `0x340e0` | **`+0x234`** |
| `__DATA_CONST.__cfstring` | `0xc80` | `0xcc0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x67af` | `0x67dd` | **`+0x2e`** |
| `__TEXT.__auth_stubs` | `0xa90` | `0xaa0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x548` | `0x550` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x650` | `0x658` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`

### Other Changes

```diff

-3288.2.1.0.0
+3288.40.13.0.0

-  Functions: 562
-  Symbols:   197
-  CStrings:  752
+  Functions: 564
+  Symbols:   198
+  CStrings:  755
Symbols:
+ _CFEqual
CStrings:
+ "IOMatchCategory"
+ "btree_node_compact"
+ "mount_apfs"
```
