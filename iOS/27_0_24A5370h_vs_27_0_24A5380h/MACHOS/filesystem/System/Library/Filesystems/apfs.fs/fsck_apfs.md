## fsck_apfs

> `/System/Library/Filesystems/apfs.fs/fsck_apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1a637` | `0x1a6cc` | **`+0x95`** |
| `__TEXT.__text` | `0x56834` | `0x5687c` | **`+0x48`** |
| `__DATA.__data` | `0xf30` | `0xf38` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xb98` | `0xba0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`

### Other Changes

```diff

-3283.0.0.0.0
+3283.0.9.502.1

-  Functions: 987
+  Functions: 988

-  CStrings:  2000
+  CStrings:  2002
CStrings:
+ "%s (id %llu): class %u file references per-file crypto_id (%llu) but is missing INODE_PROT_CLASS_EXPLICIT\n"
+ "3283.0.9.502.1"
+ "Set INODE_PROT_CLASS_EXPLICIT? "
- "3283"
```
