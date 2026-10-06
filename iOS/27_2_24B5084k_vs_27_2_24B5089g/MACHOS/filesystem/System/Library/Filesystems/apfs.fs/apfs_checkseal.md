## apfs_checkseal

> `/System/Library/Filesystems/apfs.fs/apfs_checkseal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x500dc` | `0x5022c` | **`+0x150`** |

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
~ sub_100020880 : 584 -> 608
~ sub_100042058 -> sub_100042070 : 1028 -> 1044
~ sub_10004245c -> sub_100042484 : 3796 -> 3868
~ sub_1000452ac -> sub_10004531c : 3520 -> 3592
~ sub_10004606c -> sub_100046124 : 3612 -> 3744
~ sub_100049370 -> sub_1000494ac : 68 -> 88
```
