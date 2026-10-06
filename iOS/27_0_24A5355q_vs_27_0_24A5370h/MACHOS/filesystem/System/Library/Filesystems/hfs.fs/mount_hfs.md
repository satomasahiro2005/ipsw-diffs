## mount_hfs

> `/System/Library/Filesystems/hfs.fs/mount_hfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x148c` | `0x1488` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-747.0.0.0.0
+748.0.0.0.0
Functions:
~ sub_100000984 : 120 -> 116
~ sub_100001844 -> sub_100001840 : 240 -> 248
~ sub_100001934 -> sub_100001938 : 184 -> 180
~ sub_100001aa4 : 240 -> 236
```
