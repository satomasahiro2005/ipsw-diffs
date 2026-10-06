## fsck_msdos

> `/System/Library/Filesystems/msdos.fs/fsck_msdos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ed8` | `0x6f14` | **`+0x3c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-844.0.0.0.0
+845.0.0.0.0
Functions:
~ sub_1000010a8 : 3060 -> 3064
~ sub_100001cf4 -> sub_100001cf8 : 708 -> 716
~ sub_100002420 -> sub_10000242c : 8824 -> 8848
~ sub_100004d38 -> sub_100004d5c : 1268 -> 1280
~ sub_100005fcc -> sub_100005ffc : 708 -> 716
~ sub_1000073f8 -> sub_100007430 : 88 -> 92
```
