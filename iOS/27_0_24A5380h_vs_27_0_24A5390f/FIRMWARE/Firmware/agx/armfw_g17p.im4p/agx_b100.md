## agx_b100

> `Firmware/agx/armfw_g17p.im4p/agx_b100`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b614` | `0x3b5c8` | **`-0x4c`** |
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
~ sub_fffffc0000029c34 -> sub_fffffc0000029c44 : 112 -> 116
~ sub_fffffc000002baf8 -> sub_fffffc000002bb0c : 832 -> 836
~ sub_fffffc000002c934 -> sub_fffffc000002c94c : 724 -> 720
~ sub_fffffc000002d6fc -> sub_fffffc000002d710 : 368 -> 364
~ sub_fffffc000002d8f8 -> sub_fffffc000002d908 : 468 -> 456
~ sub_fffffc000002db34 -> sub_fffffc000002db38 : 664 -> 652
~ sub_fffffc000002ddcc -> sub_fffffc000002ddc4 : 1008 -> 992
~ sub_fffffc000002e1bc -> sub_fffffc000002e1a4 : 268 -> 256
~ sub_fffffc000002e67c -> sub_fffffc000002e658 : 956 -> 988
~ sub_fffffc000002f5c0 -> sub_fffffc000002f5bc : 328 -> 324
~ sub_fffffc000002fc58 -> sub_fffffc000002fc50 : 468 -> 480
~ sub_fffffc000002ff38 -> sub_fffffc000002ff3c : 2832 -> 2840
~ sub_fffffc0000033198 -> sub_fffffc00000331a4 : 196 -> 192
~ sub_fffffc00000346c8 -> sub_fffffc00000346d0 : 528 -> 524
~ sub_fffffc0000036450 -> sub_fffffc0000036454 : 656 -> 652
~ sub_fffffc00000366e0 : 796 -> 792
~ sub_fffffc0000036aa4 -> sub_fffffc0000036aa0 : 672 -> 668
~ sub_fffffc0000036f04 -> sub_fffffc0000036efc : 228 -> 224
~ sub_fffffc0000037bd0 -> sub_fffffc0000037bc4 : 544 -> 532
~ sub_fffffc0000038f08 -> sub_fffffc0000038ef0 : 800 -> 816
~ sub_fffffc0000039634 -> sub_fffffc000003962c : 508 -> 504
~ sub_fffffc0000039b10 -> sub_fffffc0000039b04 : 552 -> 540
~ sub_fffffc0000039dc8 -> sub_fffffc0000039db0 : 212 -> 200
~ sub_fffffc000003a400 -> sub_fffffc000003a3dc : 208 -> 204
~ sub_fffffc000003aa0c -> sub_fffffc000003a9e4 : 2332 -> 2300
~ sub_fffffc000003b4cc -> sub_fffffc000003b484 : 328 -> 332
CStrings:
+ "!MIDR: 0x%x"
+ "Jul 14 2026 21:20:13"
- "!MIDR: 0x%llx"
- "Jun 30 2026 21:10:50"
```
