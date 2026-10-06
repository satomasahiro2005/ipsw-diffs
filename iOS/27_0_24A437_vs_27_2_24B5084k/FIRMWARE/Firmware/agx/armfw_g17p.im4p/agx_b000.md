## agx_b000

> `Firmware/agx/armfw_g17p.im4p/agx_b000`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x1cf8` | `0x1d0d` | **`+0x15`** |
| `__TEXT.__text` | `0x3bb38` | `0x3bb4c` | **`+0x14`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`
- `__TEXT.__cstring`
- `__TEXT._rtk_patchbay`

### Other Changes

```diff
Functions:
~ sub_fffffc000000a81c : 316 -> 332
~ sub_fffffc0000032e98 -> sub_fffffc0000032ea8 : 384 -> 388
CStrings:
+ "Sep  4 2026 23:12:48"
- "Aug 13 2026 21:36:12"
```
