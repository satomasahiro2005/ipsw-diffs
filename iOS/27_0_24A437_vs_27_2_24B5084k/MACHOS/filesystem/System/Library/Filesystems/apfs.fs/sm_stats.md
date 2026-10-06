## sm_stats

> `/System/Library/Filesystems/apfs.fs/sm_stats`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x441c0` | `0x443e4` | **`+0x224`** |
| `__DATA_CONST.__cfstring` | `0x120` | `0x160` | **`+0x40`** |
| `__TEXT.__cstring` | `0xce18` | `0xce46` | **`+0x2e`** |
| `__TEXT.__auth_stubs` | `0x720` | `0x730` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x390` | `0x398` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x720` | `0x728` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`

### Other Changes

```diff

-3288.2.1.0.0
+3288.40.13.0.0

-  Functions: 595
-  Symbols:   129
-  CStrings:  1051
+  Functions: 597
+  Symbols:   130
+  CStrings:  1054
Symbols:
+ _IORegistryEntryCreateCFProperty
CStrings:
+ "IOMatchCategory"
+ "btree_node_compact"
+ "mount_apfs"
```
