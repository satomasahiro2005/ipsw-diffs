## newfs_apfs

> `/System/Library/Filesystems/apfs.fs/newfs_apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x510bc` | `0x51390` | **`+0x2d4`** |
| `__TEXT.__cstring` | `0xf7e1` | `0xf7d9` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3277.0.0.0.1
+3283.0.0.0.0

-  Functions: 714
+  Functions: 715
CStrings:
+ "3283"
- "3277.0.0.0.1"
```
