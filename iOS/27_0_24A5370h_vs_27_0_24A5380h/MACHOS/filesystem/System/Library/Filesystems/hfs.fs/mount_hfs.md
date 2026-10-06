## mount_hfs

> `/System/Library/Filesystems/hfs.fs/mount_hfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1488` | `0x1470` | **`-0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-748.0.0.0.0
+749.0.0.0.0
Functions:
~ sub_100001678 : 160 -> 152
~ sub_100001718 -> sub_100001710 : 160 -> 152
~ sub_100001840 -> sub_100001830 : 248 -> 240
```
