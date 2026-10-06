## fsck_apfs

> `/System/Library/Filesystems/apfs.fs/fsck_apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x56b04` | `0x56dac` | **`+0x2a8`** |
| `__DATA_CONST.__cfstring` | `0x200` | `0x220` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xba8` | `0xbb8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1a6d8` | `0x1a6e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`

### Other Changes

```diff

-3288.2.1.0.0
+3288.40.13.0.0

-  Functions: 989
+  Functions: 992

-  CStrings:  2002
+  CStrings:  2003
CStrings:
+ "3288.40.13"
+ "The volume %s with UUID %s was found to have minor issues that can be repaired."
+ "mount_apfs"
- "3288.2.1"
- "The volume %s with UUID %s could not be verified completely and can not be repaired."
```
