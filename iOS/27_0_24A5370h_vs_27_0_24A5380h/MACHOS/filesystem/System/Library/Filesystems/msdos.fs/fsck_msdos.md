## fsck_msdos

> `/System/Library/Filesystems/msdos.fs/fsck_msdos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f14` | `0x6f28` | **`+0x14`** |

### Same-size Content Changes

- `__DATA.__data`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-845.0.0.0.0
+845.0.2.0.0
Functions:
~ sub_1000010a8 : 3064 -> 3060
~ sub_1000046bc -> sub_1000046b8 : 532 -> 540
~ sub_100006abc -> sub_100006ac0 : 268 -> 284
```
