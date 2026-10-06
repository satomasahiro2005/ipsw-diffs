## slurpAPFSMeta

> `/System/Library/Filesystems/apfs.fs/slurpAPFSMeta`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37f98` | `0x381c8` | **`+0x230`** |
| `__DATA_CONST.__cfstring` | `0x140` | `0x180` | **`+0x40`** |
| `__TEXT.__cstring` | `0x911a` | `0x9148` | **`+0x2e`** |
| `__TEXT.__unwind_info` | `0x6a8` | `0x6b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`

### Other Changes

```diff

-3288.2.1.0.0
+3288.40.13.0.0

-  Functions: 534
+  Functions: 536

-  CStrings:  778
+  CStrings:  781
CStrings:
+ "IOMatchCategory"
+ "btree_node_compact"
+ "mount_apfs"
```
