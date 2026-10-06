## fsck_hfs

> `/System/Library/Filesystems/hfs.fs/fsck_hfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34ba8` | `0x34bbc` | **`+0x14`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_100005314 : 852 -> 816
~ sub_100008fec -> sub_100008fc8 : 1000 -> 1004
~ sub_10000c618 -> sub_10000c5f8 : 2208 -> 2240
~ sub_100011a44 : 6892 -> 6912
~ sub_10002f28c -> sub_10002f2a0 : 736 -> 740
~ sub_100033fbc -> sub_100033fd4 : 2220 -> 2216
```
