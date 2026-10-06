## h17_ane_fw_theia_d9x.im4p

> `Firmware/ane/h17_ane_fw_theia_d9x.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbd714` | `0xbd6bc` | **`-0x58`** |
| `__TEXT.__cstring` | `0x1d144` | `0x1d142` | **`-0x2`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__TEXT.__const`

### Other Changes

```diff
Functions:
~ sub_aa164 : 88 -> 92
~ sub_aa1bc -> sub_aa1c0 : 316 -> 312
~ sub_acb9c : 572 -> 588
~ sub_ad688 -> sub_ad698 : 816 -> 820
~ sub_ae3e8 -> sub_ae3fc : 740 -> 736
~ sub_af1bc -> sub_af1cc : 368 -> 364
~ sub_af3b8 -> sub_af3c4 : 468 -> 456
~ sub_af5f4 : 668 -> 656
~ sub_af890 -> sub_af884 : 1008 -> 992
~ sub_afc80 -> sub_afc64 : 260 -> 248
~ sub_b0138 -> sub_b0110 : 960 -> 992
~ sub_b1554 -> sub_b154c : 288 -> 284
~ sub_b18ac -> sub_b18a0 : 504 -> 516
~ sub_b2198 : 88 -> 84
~ sub_b22b8 -> sub_b22b4 : 88 -> 84
~ sub_b2310 -> sub_b2308 : 208 -> 204
~ sub_b3fa4 -> sub_b3f98 : 140 -> 136
~ sub_b4304 -> sub_b42f4 : 244 -> 240
~ sub_b5b50 -> sub_b5b3c : 352 -> 344
~ sub_b5df0 -> sub_b5dd4 : 240 -> 224
~ sub_b6018 -> sub_b5fec : 2716 -> 2724
~ sub_b8b38 -> sub_b8b14 : 656 -> 652
~ sub_b8dc8 -> sub_b8da0 : 784 -> 780
~ sub_b921c -> sub_b91f0 : 704 -> 700
~ sub_b9ef4 -> sub_b9ec4 : 712 -> 700
~ sub_ba48c -> sub_ba450 : 284 -> 280
~ sub_bc4d4 -> sub_bc494 : 2224 -> 2204
~ sub_bd5cc -> sub_bd578 : 328 -> 332
CStrings:
+ "!MIDR: 0x%x"
+ "21:47:59"
+ "Jul 10 2026"
- "!MIDR: 0x%llx"
- "00:42:26"
- "Jun 27 2026"
```
