## apfs_iosd

> `/System/Library/Filesystems/apfs.fs/apfs_iosd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x340e0` | `0x34230` | **`+0x150`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3288.40.13.0.0
+3288.40.14.0.0
Functions:
~ sub_100018e08 : 584 -> 608
~ sub_1000290c8 -> sub_1000290e0 : 1028 -> 1044
~ sub_1000294cc -> sub_1000294f4 : 3796 -> 3868
~ sub_10002bfe0 -> sub_10002c050 : 3520 -> 3592
~ sub_10002cda0 -> sub_10002ce58 : 3612 -> 3744
~ sub_10002fbe0 -> sub_10002fd1c : 68 -> 88
```
