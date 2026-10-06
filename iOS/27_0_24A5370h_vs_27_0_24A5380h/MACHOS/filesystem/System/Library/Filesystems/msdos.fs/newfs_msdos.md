## newfs_msdos

> `/System/Library/Filesystems/msdos.fs/newfs_msdos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3068` | `0x3048` | **`-0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-845.0.0.0.0
+845.0.2.0.0
Functions:
~ sub_100000718 : 5696 -> 5684
~ sub_100001d58 -> sub_100001d4c : 200 -> 192
~ sub_1000022f0 -> sub_1000022dc : 108 -> 100
~ sub_100002688 -> sub_10000266c : 188 -> 172
~ sub_100002744 -> sub_100002718 : 2816 -> 2828
```
