## agx_a010

> `Firmware/agx/armfw_g18p.im4p/agx_a010`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__gxf_code` | `0x4f50` | `0x5120` | **`+0x1d0`** |
| `__DATA.__gxf_data` | `0x80b8` | `0x8160` | **`+0xa8`** |
| `__TEXT.__text` | `0x3ccbc` | `0x3cc68` | **`-0x54`** |
| `__TEXT.__const` | `0x107d` | `0x10ad` | **`+0x30`** |
| `__TEXT.__chain_starts` | `0x20` | `0x24` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`
- `__TEXT.__cstring`
- `__TEXT._rtk_patchbay`

### Other Changes

```diff

-  Symbols:   168
+  Symbols:   172
Symbols:
+ _agfUPPLRegisterPageCount
+ _agfUPPLRegisterPages
+ _gClientFunctions
+ _premap_ranges
Functions:
~ sub_fffffc000000be38 : 11152 -> 11068
CStrings:
+ "Oct 10 2026 01:18:33"
- "Sep 27 2026 20:49:56"
```
