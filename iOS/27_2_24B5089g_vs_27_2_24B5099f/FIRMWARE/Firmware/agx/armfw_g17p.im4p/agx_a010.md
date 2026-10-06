## agx_a010

> `Firmware/agx/armfw_g17p.im4p/agx_a010`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3bb4c` | `0x3bbe0` | **`+0x94`** |
| `__TEXT.__gxf_code` | `0x4f40` | `0x4f50` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__TEXT.__const`
- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ sub_fffffc0000037954 : 432 -> 468
~ sub_fffffc0000037b04 -> sub_fffffc0000037b28 : 428 -> 540
~ sub_fffffc000003ba08 -> sub_fffffc000003ba9c : 332 -> 324
CStrings:
+ "Sep 27 2026 20:54:40"
- "Sep 13 2026 22:04:02"
```
