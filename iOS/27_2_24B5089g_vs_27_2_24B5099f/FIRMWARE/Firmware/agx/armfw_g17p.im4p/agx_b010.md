## agx_b010

> `Firmware/agx/armfw_g17p.im4p/agx_b010`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ba74` | `0x3bb08` | **`+0x94`** |
| `__TEXT.__gxf_code` | `0x4f40` | `0x4f50` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__TEXT.__const`
- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ sub_fffffc000003787c : 432 -> 468
~ sub_fffffc0000037a2c -> sub_fffffc0000037a50 : 428 -> 540
~ sub_fffffc000003b930 -> sub_fffffc000003b9c4 : 324 -> 332
CStrings:
+ "Sep 27 2026 20:58:03"
- "Sep 13 2026 22:06:31"
```
