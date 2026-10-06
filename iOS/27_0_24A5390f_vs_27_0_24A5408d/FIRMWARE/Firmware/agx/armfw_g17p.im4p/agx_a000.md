## agx_a000

> `Firmware/agx/armfw_g17p.im4p/agx_a000`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x17478` | `0x17c98` | **`+0x820`** |
| `__TEXT.__text` | `0x3b7a0` | `0x3bd10` | **`+0x570`** |
| `__DATA.__zerofill` | `0x5b198` | `0x5b1d8` | **`+0x40`** |
| `__TEXT.__cstring` | `0x22df` | `0x2303` | **`+0x24`** |
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

-  CStrings:  234
+  CStrings:  235
Functions:
~ sub_fffffc0000003ab4 : 7884 -> 7880
~ sub_fffffc000000b27c -> sub_fffffc000000b278 : 10592 -> 10924
~ sub_fffffc000000f250 -> sub_fffffc000000f398 : 10304 -> 10324
~ sub_fffffc0000011c68 -> sub_fffffc0000011dc4 : 4880 -> 4952
~ sub_fffffc000001485c -> sub_fffffc0000014a00 : 2044 -> 2092
~ sub_fffffc000001bde4 -> sub_fffffc000001bfb8 : 360 -> 352
~ sub_fffffc000001c54c -> sub_fffffc000001c718 : 1676 -> 1692
~ sub_fffffc000001d324 -> sub_fffffc000001d500 : 756 -> 768
~ sub_fffffc000001d9ac -> sub_fffffc000001db94 : 848 -> 832
~ sub_fffffc000001e3ec -> sub_fffffc000001e5c4 : 2332 -> 2340
~ sub_fffffc000002047c -> sub_fffffc000002065c : 2108 -> 2120
~ sub_fffffc000002301c -> sub_fffffc0000023208 : 384 -> 368
~ sub_fffffc00000238b4 -> sub_fffffc0000023a90 : 1368 -> 1380
~ sub_fffffc0000024990 -> sub_fffffc0000024b78 : 768 -> 772
~ sub_fffffc0000026b80 -> sub_fffffc0000026d6c : 6324 -> 7096
~ sub_fffffc0000028434 -> sub_fffffc0000028924 : 2084 -> 2212
CStrings:
+ "Aug  5 2026 21:49:19"
+ "kAGFIPIORegionTypeAFRD2DNIRegisters"
- "Jul 14 2026 21:09:04"
```
