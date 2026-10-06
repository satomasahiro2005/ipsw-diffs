## newfs_msdos

> `/System/Library/Filesystems/msdos.fs/newfs_msdos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x302c` | `0x3068` | **`+0x3c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-844.0.0.0.0
+845.0.0.0.0
Functions:
~ sub_100001d58 : 160 -> 200
~ sub_100002660 -> sub_100002688 : 172 -> 188
~ sub_10000270c -> sub_100002744 : 2812 -> 2816
```
