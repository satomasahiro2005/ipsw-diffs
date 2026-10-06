## fsck_exfat

> `/System/Library/Filesystems/exfat.fs/fsck_exfat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcc30` | `0xcc08` | **`-0x28`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_100001760 : 1736 -> 1732
~ sub_100002a70 -> sub_100002a6c : 384 -> 380
~ sub_100003dd0 -> sub_100003dc8 : 484 -> 480
~ sub_1000070a4 -> sub_100007098 : 296 -> 272
~ sub_10000c82c -> sub_10000c808 : 648 -> 644
```
