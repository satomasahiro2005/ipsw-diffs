## newfs_exfat

> `/System/Library/Filesystems/exfat.fs/newfs_exfat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x353c` | `0x3574` | **`+0x38`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-560.0.0.0.0
+561.0.0.0.0
Functions:
~ sub_100000718 : 1360 -> 1368
~ sub_100000c68 -> sub_100000c70 : 88 -> 96
~ sub_100000d4c -> sub_100000d5c : 876 -> 912
~ sub_100002038 -> sub_10000206c : 1276 -> 1272
~ sub_100002534 -> sub_100002564 : 496 -> 492
~ sub_100002750 -> sub_10000277c : 116 -> 112
~ sub_100002aa4 -> sub_100002acc : 296 -> 304
~ sub_1000039d8 -> sub_100003a08 : 164 -> 172
```
