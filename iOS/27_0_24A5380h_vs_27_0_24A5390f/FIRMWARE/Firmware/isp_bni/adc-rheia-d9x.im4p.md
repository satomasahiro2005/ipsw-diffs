## adc-rheia-d9x.im4p

> `Firmware/isp_bni/adc-rheia-d9x.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaa1bc4` | `0xaa1b38` | **`-0x8c`** |
| `__TEXT.__cstring` | `0xa7f15` | `0xa7f1f` | **`+0xa`** |
| `__TEXT.__const` | `0x9cba40` | `0x9cba48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__DATA._rtk_smp_main`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-  CStrings:  18343
+  CStrings:  18344
Functions:
~ sub_39500 : 22036 -> 22032
~ sub_a8843c -> sub_a88438 : 104 -> 108
~ sub_a884a4 : 168 -> 164
~ sub_a8ac7c -> sub_a8ac78 : 980 -> 984
~ sub_a8ba28 : 812 -> 808
~ sub_a8cb38 -> sub_a8cb34 : 368 -> 364
~ sub_a8cd34 -> sub_a8cd2c : 464 -> 452
~ sub_a8cf6c -> sub_a8cf58 : 668 -> 656
~ sub_a8d208 -> sub_a8d1e8 : 1008 -> 992
~ sub_a8d5f8 -> sub_a8d5c8 : 260 -> 248
~ sub_a8dab0 -> sub_a8da74 : 944 -> 976
~ sub_a8eeac -> sub_a8ee90 : 288 -> 284
~ sub_a8f350 -> sub_a8f330 : 248 -> 268
~ sub_a8fcb4 -> sub_a8fca8 : 208 -> 204
~ sub_a90e8c -> sub_a90e7c : 392 -> 380
~ sub_a91d10 -> sub_a91cf4 : 144 -> 140
~ sub_a91da0 -> sub_a91d80 : 256 -> 248
~ sub_a91ea0 -> sub_a91e78 : 588 -> 584
~ sub_a922d8 -> sub_a922ac : 244 -> 240
~ sub_a93888 -> sub_a93858 : 328 -> 320
~ sub_a93b70 -> sub_a93b38 : 208 -> 196
~ sub_a93ea4 -> sub_a93e60 : 2268 -> 2276
~ sub_a97060 -> sub_a97024 : 640 -> 656
~ sub_a98038 -> sub_a9800c : 648 -> 644
~ sub_a982c0 -> sub_a98290 : 756 -> 752
~ sub_a98658 -> sub_a98624 : 684 -> 680
~ sub_a98ab4 -> sub_a98a7c : 920 -> 916
~ sub_a98e70 -> sub_a98e34 : 132 -> 128
~ sub_a98f14 -> sub_a98ed4 : 840 -> 820
~ sub_a99aa4 -> sub_a99a50 : 488 -> 476
~ sub_a99f34 -> sub_a99ed4 : 276 -> 272
~ sub_a9ceec -> sub_a9ce88 : 324 -> 332
~ sub_a9d408 -> sub_a9d3ac : 236 -> 232
~ sub_a9d54c -> sub_a9d4ec : 516 -> 512
~ sub_a9dd58 -> sub_a9dcf4 : 180 -> 176
~ sub_aa0700 -> sub_aa0698 : 252 -> 264
~ sub_aa07fc -> sub_aa07a0 : 300 -> 288
~ sub_aa12f0 -> sub_aa1288 : 1452 -> 1420
~ sub_aa1a88 -> sub_aa1a00 : 316 -> 320
CStrings:
+ "!MIDR: 0x%x"
+ "23:57:20"
+ "Jul 15 2026"
- "!MIDR: 0x%llx"
- "23:41:57"
```
