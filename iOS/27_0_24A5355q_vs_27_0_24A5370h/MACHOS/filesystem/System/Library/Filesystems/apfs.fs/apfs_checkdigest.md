## apfs_checkdigest

> `/System/Library/Filesystems/apfs.fs/apfs_checkdigest`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf00` | `0xf20` | **`+0x20`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3277.0.0.0.1
+3283.0.0.0.0
Functions:
~ sub_100000750 : 1992 -> 2004
~ sub_100001048 -> sub_100001054 : 584 -> 588
~ sub_10000137c -> sub_10000138c : 148 -> 164
```
