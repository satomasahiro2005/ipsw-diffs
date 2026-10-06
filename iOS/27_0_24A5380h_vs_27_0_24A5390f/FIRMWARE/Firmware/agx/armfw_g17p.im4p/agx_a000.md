## agx_a000

> `Firmware/agx/armfw_g17p.im4p/agx_a000`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b7ec` | `0x3b7a0` | **`-0x4c`** |
| `__TEXT.__cstring` | `0x22e1` | `0x22df` | **`-0x2`** |
| `__TEXT.__const` | `0x1cf7` | `0x1cf8` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`
- `__TEXT._rtk_patchbay`

### Other Changes

```diff
Functions:
~ sub_fffffc000002301c : 368 -> 384
~ sub_fffffc0000029e0c -> sub_fffffc0000029e1c : 112 -> 116
~ sub_fffffc000002bcd0 -> sub_fffffc000002bce4 : 832 -> 836
~ sub_fffffc000002cb0c -> sub_fffffc000002cb24 : 724 -> 720
~ sub_fffffc000002d8d4 -> sub_fffffc000002d8e8 : 368 -> 364
~ sub_fffffc000002dad0 -> sub_fffffc000002dae0 : 468 -> 456
~ sub_fffffc000002dd0c -> sub_fffffc000002dd10 : 664 -> 652
~ sub_fffffc000002dfa4 -> sub_fffffc000002df9c : 1008 -> 992
~ sub_fffffc000002e394 -> sub_fffffc000002e37c : 268 -> 256
~ sub_fffffc000002e854 -> sub_fffffc000002e830 : 956 -> 988
~ sub_fffffc000002f798 -> sub_fffffc000002f794 : 328 -> 324
~ sub_fffffc000002fe30 -> sub_fffffc000002fe28 : 468 -> 480
~ sub_fffffc0000030110 -> sub_fffffc0000030114 : 2832 -> 2840
~ sub_fffffc0000033370 -> sub_fffffc000003337c : 196 -> 192
~ sub_fffffc00000348a0 -> sub_fffffc00000348a8 : 528 -> 524
~ sub_fffffc0000036628 -> sub_fffffc000003662c : 656 -> 652
~ sub_fffffc00000368b8 : 796 -> 792
~ sub_fffffc0000036c7c -> sub_fffffc0000036c78 : 672 -> 668
~ sub_fffffc00000370dc -> sub_fffffc00000370d4 : 228 -> 224
~ sub_fffffc0000037da8 -> sub_fffffc0000037d9c : 544 -> 532
~ sub_fffffc00000390e0 -> sub_fffffc00000390c8 : 800 -> 816
~ sub_fffffc000003980c -> sub_fffffc0000039804 : 508 -> 504
~ sub_fffffc0000039ce8 -> sub_fffffc0000039cdc : 552 -> 540
~ sub_fffffc0000039fa0 -> sub_fffffc0000039f88 : 212 -> 200
~ sub_fffffc000003a5d8 -> sub_fffffc000003a5b4 : 208 -> 204
~ sub_fffffc000003abe4 -> sub_fffffc000003abbc : 2332 -> 2300
~ sub_fffffc000003b6a4 -> sub_fffffc000003b65c : 336 -> 324
CStrings:
+ "!MIDR: 0x%x"
+ "Jul 14 2026 21:09:04"
- "!MIDR: 0x%llx"
- "Jun 30 2026 21:02:17"
```
