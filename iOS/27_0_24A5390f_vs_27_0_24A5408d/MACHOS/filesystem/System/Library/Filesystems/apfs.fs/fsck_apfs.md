## fsck_apfs

> `/System/Library/Filesystems/apfs.fs/fsck_apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5687c` | `0x56a7c` | **`+0x200`** |
| `__TEXT.__unwind_info` | `0xba0` | `0xba8` | **`+0x8`** |
| `__TEXT.__cstring` | `0x1a6d9` | `0x1a6d8` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`

### Other Changes

```diff

-3283.0.13.0.0
+3288.2.1.0.0

-  Functions: 988
+  Functions: 989
CStrings:
+ "3288.2.1"
- "3283.0.13"
```
