## APFS

> `/System/Library/PrivateFrameworks/APFS.framework/APFS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x543a8` | `0x545e4` | **`+0x23c`** |
| `__AUTH_CONST.__cfstring` | `0x1360` | `0x13a0` | **`+0x40`** |
| `__TEXT.__cstring` | `0xe85d` | `0xe88d` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x9d8` | `0x9e0` | **`+0x8`** |

### Other Changes

```diff

-3288.2.1.0.0
+3288.40.13.0.0

-  Functions: 901
-  Symbols:   1127
-  CStrings:  1404
+  Functions: 903
+  Symbols:   1129
+  CStrings:  1407
Symbols:
+ _btree_node_val_space_total
+ _is_fake_mount_node
CStrings:
+ "3288.40.13"
+ "IOMatchCategory"
+ "btree_node_compact"
+ "mount_apfs"
- "3288.2.1"
```
