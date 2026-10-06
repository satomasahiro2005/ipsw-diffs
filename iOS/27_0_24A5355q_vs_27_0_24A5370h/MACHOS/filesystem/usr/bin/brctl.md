## brctl

> `/usr/bin/brctl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x140e8` | `0x140bc` | **`-0x2c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5044.0.0.0.0
+5140.0.0.0.0
Functions:
~ sub_100001cdc : 220 -> 216
~ sub_100002358 -> sub_100002354 : 1344 -> 1340
~ sub_100003134 -> sub_10000312c : 524 -> 516
~ sub_100003340 -> sub_100003330 : 1844 -> 1840
~ sub_10000411c -> sub_100004108 : 332 -> 328
~ sub_100007294 -> sub_10000727c : 3756 -> 3752
~ sub_100008458 -> sub_10000843c : 1296 -> 1288
~ sub_100008a48 -> sub_100008a24 : 216 -> 208
~ sub_100008c24 -> sub_100008bf8 : 244 -> 248
~ sub_100008fa8 -> sub_100008f80 : 1488 -> 1484
~ sub_10000b60c -> sub_10000b5e0 : 404 -> 400
~ sub_10000be30 -> sub_10000be00 : 364 -> 376
~ sub_10000bf9c -> sub_10000bf78 : 456 -> 468
~ sub_10000c410 -> sub_10000c3f8 : 2384 -> 2380
~ sub_10000cffc -> sub_10000cfe0 : 1304 -> 1300
~ sub_10000d514 -> sub_10000d4f4 : 400 -> 396
~ sub_10000d6a4 -> sub_10000d680 : 728 -> 716
~ sub_10000d97c -> sub_10000d94c : 1068 -> 1072
~ sub_10000dda8 -> sub_10000dd7c : 2396 -> 2388
~ sub_10000e9fc -> sub_10000e9c8 : 348 -> 344
~ sub_10000f094 -> sub_10000f05c : 540 -> 536
~ sub_10000f454 -> sub_10000f418 : 776 -> 772
~ sub_10000f7cc -> sub_10000f78c : 52 -> 48
~ sub_10000fde4 -> sub_10000fda0 : 52 -> 48
~ sub_10000fe9c -> sub_10000fe54 : 596 -> 592
~ sub_1000100f0 -> sub_1000100a4 : 540 -> 536
~ sub_100011140 -> sub_1000110f0 : 1336 -> 1400
~ sub_100011b0c -> sub_100011afc : 672 -> 668
~ sub_100011f8c -> sub_100011f78 : 592 -> 588
~ sub_10001274c -> sub_100012734 : 948 -> 932
~ sub_10001323c -> sub_100013214 : 696 -> 692
~ sub_10001364c -> sub_100013620 : 5668 -> 5660
~ sub_100014e54 -> sub_100014e20 : 436 -> 432
~ sub_100015380 -> sub_100015348 : 496 -> 508
```
