## newfs_apfs

> `/System/Library/Filesystems/apfs.fs/newfs_apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x51d68` | `0x51ec8` | **`+0x160`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3288.40.13.0.0
+3288.40.14.0.0
Functions:
~ sub_1000133f8 : 584 -> 608
~ sub_10002fa98 -> sub_10002fab0 : 68 -> 88
~ sub_1000361c0 -> sub_1000361ec : 304 -> 308
~ sub_1000434fc -> sub_10004352c : 2596 -> 2608
~ sub_100046318 -> sub_100046354 : 1028 -> 1044
~ sub_10004671c -> sub_100046768 : 3796 -> 3868
~ sub_10004956c -> sub_100049600 : 3520 -> 3592
~ sub_10004a32c -> sub_10004a408 : 3612 -> 3744
CStrings:
+ "3288.40.14"
- "3288.40.13"
```
