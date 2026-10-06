## fsck_hfs

> `/System/Library/Filesystems/hfs.fs/fsck_hfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34c44` | `0x34ddc` | **`+0x198`** |
| `__TEXT.__cstring` | `0x6e74` | `0x6f24` | **`+0xb0`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-753.40.3.0.0
+753.40.4.0.0

-  CStrings:  785
+  CStrings:  790
Functions:
~ sub_100007e94 : 308 -> 412
~ sub_100007fc8 -> sub_100008030 : 160 -> 276
~ sub_1000093b4 -> sub_100009490 : 1908 -> 1916
~ sub_100009b28 -> sub_100009c0c : 1088 -> 1120
~ sub_100011a44 -> sub_100011b48 : 6912 -> 7060
CStrings:
+ "%s(%d):  index %u >= numRecords %u\n"
+ "DeleteOffset"
+ "DeleteRecord"
+ "hfs_UNswap_BTNode: initial record at bad offset (0x%04X)\n"
+ "hfs_swap_BTNode: initial record at bad offset (0x%04X)\n"
```
