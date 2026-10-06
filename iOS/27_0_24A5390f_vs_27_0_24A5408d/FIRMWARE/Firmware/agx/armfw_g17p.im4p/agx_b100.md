## agx_b100

> `Firmware/agx/armfw_g17p.im4p/agx_b100`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x17478` | `0x17c98` | **`+0x820`** |
| `__TEXT.__text` | `0x3b5c8` | `0x3bb38` | **`+0x570`** |
| `__DATA.__zerofill` | `0x5b198` | `0x5b1d8` | **`+0x40`** |
| `__TEXT.__cstring` | `0x2271` | `0x2295` | **`+0x24`** |
| `__DATA.__const` | `0x820` | `0x830` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`
- `__DATA._rtk_power`
- `__TEXT.__chain_starts`
- `__TEXT.__const`
- `__TEXT._rtk_patchbay`

### Other Changes

```diff

-  CStrings:  232
+  CStrings:  233
Functions:
~ sub_fffffc0000003ab4 : 7884 -> 7880
~ sub_fffffc000000b26c -> sub_fffffc000000b268 : 10592 -> 10924
~ sub_fffffc000000f1cc -> sub_fffffc000000f314 : 10304 -> 10324
~ sub_fffffc0000011be4 -> sub_fffffc0000011d40 : 4880 -> 4952
~ sub_fffffc00000147d8 -> sub_fffffc000001497c : 2044 -> 2092
~ sub_fffffc000001bd60 -> sub_fffffc000001bf34 : 360 -> 352
~ sub_fffffc000001c4c8 -> sub_fffffc000001c694 : 1676 -> 1692
~ sub_fffffc000001d2a0 -> sub_fffffc000001d47c : 756 -> 768
~ sub_fffffc000001d928 -> sub_fffffc000001db10 : 848 -> 832
~ sub_fffffc000001e368 -> sub_fffffc000001e540 : 2332 -> 2340
~ sub_fffffc00000203f8 -> sub_fffffc00000205d8 : 2108 -> 2120
~ sub_fffffc0000022e44 -> sub_fffffc0000023030 : 384 -> 368
~ sub_fffffc00000236dc -> sub_fffffc00000238b8 : 1368 -> 1380
~ sub_fffffc00000247b8 -> sub_fffffc00000249a0 : 768 -> 772
~ sub_fffffc00000269a8 -> sub_fffffc0000026b94 : 6324 -> 7096
~ sub_fffffc000002825c -> sub_fffffc000002874c : 2084 -> 2212
CStrings:
+ "Aug  5 2026 22:00:21"
+ "kAGFIPIORegionTypeAFRD2DNIRegisters"
- "Jul 14 2026 21:20:13"
```
