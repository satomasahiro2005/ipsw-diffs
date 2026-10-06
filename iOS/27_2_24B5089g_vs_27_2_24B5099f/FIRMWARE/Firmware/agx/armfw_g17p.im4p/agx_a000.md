## agx_a000

> `Firmware/agx/armfw_g17p.im4p/agx_a000`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3bd24` | `0x3bdb8` | **`+0x94`** |
| `__TEXT.__gxf_code` | `0x4f40` | `0x4f50` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__TEXT.__const`
- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ sub_fffffc0000037b2c : 432 -> 468
~ sub_fffffc0000037cdc -> sub_fffffc0000037d00 : 428 -> 540
~ sub_fffffc000003bbe0 -> sub_fffffc000003bc74 : 324 -> 332
CStrings:
+ "Sep 27 2026 20:36:05"
- "Sep 13 2026 21:50:35"
```
