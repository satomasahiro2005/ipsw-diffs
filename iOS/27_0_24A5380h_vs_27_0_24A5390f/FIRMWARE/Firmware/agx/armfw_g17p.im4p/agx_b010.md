## agx_b010

> `Firmware/agx/armfw_g17p.im4p/agx_b010`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b524` | `0x3b4d8` | **`-0x4c`** |
| `__TEXT.__cstring` | `0x2273` | `0x2271` | **`-0x2`** |
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
~ sub_fffffc0000022e44 : 368 -> 384
~ sub_fffffc0000029b44 -> sub_fffffc0000029b54 : 112 -> 116
~ sub_fffffc000002ba08 -> sub_fffffc000002ba1c : 832 -> 836
~ sub_fffffc000002c844 -> sub_fffffc000002c85c : 724 -> 720
~ sub_fffffc000002d60c -> sub_fffffc000002d620 : 368 -> 364
~ sub_fffffc000002d808 -> sub_fffffc000002d818 : 468 -> 456
~ sub_fffffc000002da44 -> sub_fffffc000002da48 : 664 -> 652
~ sub_fffffc000002dcdc -> sub_fffffc000002dcd4 : 1008 -> 992
~ sub_fffffc000002e0cc -> sub_fffffc000002e0b4 : 268 -> 256
~ sub_fffffc000002e58c -> sub_fffffc000002e568 : 956 -> 988
~ sub_fffffc000002f4d0 -> sub_fffffc000002f4cc : 328 -> 324
~ sub_fffffc000002fb68 -> sub_fffffc000002fb60 : 468 -> 480
~ sub_fffffc000002fe48 -> sub_fffffc000002fe4c : 2832 -> 2840
~ sub_fffffc00000330a8 -> sub_fffffc00000330b4 : 196 -> 192
~ sub_fffffc00000345d8 -> sub_fffffc00000345e0 : 528 -> 524
~ sub_fffffc0000036360 -> sub_fffffc0000036364 : 656 -> 652
~ sub_fffffc00000365f0 : 796 -> 792
~ sub_fffffc00000369b4 -> sub_fffffc00000369b0 : 672 -> 668
~ sub_fffffc0000036e14 -> sub_fffffc0000036e0c : 228 -> 224
~ sub_fffffc0000037ae0 -> sub_fffffc0000037ad4 : 544 -> 532
~ sub_fffffc0000038e18 -> sub_fffffc0000038e00 : 800 -> 816
~ sub_fffffc0000039544 -> sub_fffffc000003953c : 508 -> 504
~ sub_fffffc0000039a20 -> sub_fffffc0000039a14 : 552 -> 540
~ sub_fffffc0000039cd8 -> sub_fffffc0000039cc0 : 212 -> 200
~ sub_fffffc000003a310 -> sub_fffffc000003a2ec : 208 -> 204
~ sub_fffffc000003a91c -> sub_fffffc000003a8f4 : 2332 -> 2300
~ sub_fffffc000003b3dc -> sub_fffffc000003b394 : 328 -> 332
CStrings:
+ "!MIDR: 0x%x"
+ "Jul 14 2026 21:24:49"
- "!MIDR: 0x%llx"
- "Jun 30 2026 21:14:48"
```
