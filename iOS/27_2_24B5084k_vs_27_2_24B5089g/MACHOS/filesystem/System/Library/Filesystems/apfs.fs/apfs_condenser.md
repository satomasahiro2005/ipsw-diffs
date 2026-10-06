## apfs_condenser

> `/System/Library/Filesystems/apfs.fs/apfs_condenser`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4d294` | `0x4d3e8` | **`+0x154`** |

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
~ sub_1000052c0 : 68 -> 88
~ sub_100014a30 -> sub_100014a44 : 584 -> 608
~ sub_100030a48 -> sub_100030a74 : 280 -> 284
~ sub_100042e74 -> sub_100042ea4 : 1028 -> 1044
~ sub_100043278 -> sub_1000432b8 : 3796 -> 3868
~ sub_1000460c8 -> sub_100046150 : 3520 -> 3592
~ sub_100046e88 -> sub_100046f58 : 3612 -> 3744
CStrings:
+ "3288.40.14"
- "3288.40.13"
```
