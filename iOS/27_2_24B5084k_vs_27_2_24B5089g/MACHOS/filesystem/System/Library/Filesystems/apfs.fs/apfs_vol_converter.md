## apfs_vol_converter

> `/System/Library/Filesystems/apfs.fs/apfs_vol_converter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5ab8c` | `0x5acdc` | **`+0x150`** |

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
~ sub_100034930 : 584 -> 608
~ sub_10004ce44 -> sub_10004ce5c : 1028 -> 1044
~ sub_10004d248 -> sub_10004d270 : 3796 -> 3868
~ sub_100050098 -> sub_100050108 : 3520 -> 3592
~ sub_100050e58 -> sub_100050f10 : 3612 -> 3744
~ sub_10005415c -> sub_100054298 : 68 -> 88
CStrings:
+ "3288.40.14"
- "3288.40.13"
```
