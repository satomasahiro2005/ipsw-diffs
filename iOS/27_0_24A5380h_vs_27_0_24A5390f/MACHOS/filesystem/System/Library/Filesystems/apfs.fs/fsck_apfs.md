## fsck_apfs

> `/System/Library/Filesystems/apfs.fs/fsck_apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1a6cc` | `0x1a6d9` | **`+0xd`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3283.0.9.502.1
+3283.0.13.0.0
CStrings:
+ "3283.0.13"
+ "reap list object 0x%llx first index %u larger than max index %u\n"
+ "reap list object 0x%llx free index %u larger than max index %u\n"
+ "reap list object 0x%llx last index %u larger than max index %u\n"
- "3283.0.9.502.1"
- "reap list object 0x%llx first index %u larger than max %u\n"
- "reap list object 0x%llx free index %u larger than max %u\n"
- "reap list object 0x%llx last index %u larger than max %u\n"
```
