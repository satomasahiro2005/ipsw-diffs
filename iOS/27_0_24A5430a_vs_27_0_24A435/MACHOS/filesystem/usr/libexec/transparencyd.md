## transparencyd

> `/usr/libexec/transparencyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3520e8` | `0x3521e4` | **`+0xfc`** |
| `__TEXT.__objc_stubs` | `0x1e000` | `0x1e020` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x4c70` | `0x4c60` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x2648` | `0x2640` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xd788` | `0xd780` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__thread_vars`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Symbols:   2370
+  Symbols:   2369
Symbols:
- _objc_retain_x12
Functions:
~ sub_10004b79c : 36 -> 84
~ sub_100097b40 -> sub_100097b70 : 3264 -> 3252
~ sub_10009a350 -> sub_10009a374 : 356 -> 360
~ sub_10009c180 -> sub_10009c1a8 : 2084 -> 2088
~ sub_1000b5418 -> sub_1000b5444 : 360 -> 364
~ sub_1000e8674 -> sub_1000e86a4 : 352 -> 356
~ sub_1000ec264 -> sub_1000ec298 : 648 -> 652
~ sub_1000f5f48 -> sub_1000f5f80 : 772 -> 776
~ sub_1000f6a24 -> sub_1000f6a60 : 424 -> 428
~ sub_1000ff0b4 -> sub_1000ff0f4 : 536 -> 532
~ sub_100103eac -> sub_100103ee8 : 188 -> 192
~ sub_1001280cc -> sub_10012810c : 984 -> 992
~ sub_1001284a4 -> sub_1001284ec : 628 -> 640
~ sub_1001322ec -> sub_100132340 : 6296 -> 6300
~ sub_100134a78 -> sub_100134ad0 : 4588 -> 4600
~ sub_10013d788 -> sub_10013d7ec : 2428 -> 2424
~ sub_10013e518 -> sub_10013e578 : 360 -> 364
~ sub_100140e88 -> sub_100140eec : 696 -> 708
~ sub_100143eb4 -> sub_100143f24 : 356 -> 360
~ sub_10014b360 -> sub_10014b3d4 : 424 -> 428
~ sub_10014baa4 -> sub_10014bb1c : 384 -> 388
~ sub_10014c804 -> sub_10014c880 : 412 -> 416
~ sub_10014ca08 -> sub_10014ca88 : 412 -> 416
~ sub_10014d0f0 -> sub_10014d174 : 2604 -> 2608
~ sub_100160dd0 -> sub_100160e58 : 832 -> 836
~ sub_100162394 -> sub_100162420 : 392 -> 396
~ sub_100183688 -> sub_100183718 : 6456 -> 6464
~ sub_100185564 -> sub_1001855fc : 1804 -> 1796
~ sub_100187f20 -> sub_100187fb0 : 360 -> 364
~ sub_100188088 -> sub_10018811c : 340 -> 344
~ sub_1001be890 -> sub_1001be928 : 2012 -> 2032
~ sub_1001bf1d8 -> sub_1001bf284 : 1668 -> 1684
~ sub_1001bf9c8 -> sub_1001bfa84 : 1296 -> 1308
~ sub_1001c0044 -> sub_1001c010c : 960 -> 968
~ sub_1001c0570 -> sub_1001c0640 : 588 -> 592
~ sub_1001c11a0 -> sub_1001c1274 : 1548 -> 1556
~ sub_1001cc2e4 -> sub_1001cc3c0 : 356 -> 360
~ sub_1001d8930 -> sub_1001d8a10 : 680 -> 684
~ sub_1001db1cc -> sub_1001db2b0 : 4168 -> 4192
~ sub_1001dceec -> sub_1001dcfe8 : 1336 -> 1344
~ sub_1001f2cd8 -> sub_1001f2ddc : 680 -> 684
~ sub_1001f62fc -> sub_1001f6404 : 356 -> 360
~ sub_1002082b8 -> sub_1002083c4 : 2380 -> 2376
~ sub_100212594 -> sub_10021269c : 5812 -> 5804
~ sub_10021bee4 -> sub_10021bfe4 : 992 -> 984
~ sub_10021cb88 -> sub_10021cc80 : 748 -> 752
~ sub_100234af0 -> sub_100234bec : 4976 -> 4980
~ sub_100237e80 -> sub_100237f80 : 2428 -> 2424
~ sub_100238b84 -> sub_100238c80 : 648 -> 652
~ sub_100247438 -> sub_100247538 : 20 -> 12
~ sub_10024744c -> sub_100247544 : 12 -> 20
~ sub_100247458 -> sub_100247558 : 20 -> 12
~ sub_100247478 -> sub_100247570 : 12 -> 20
~ sub_10024b2d0 -> sub_10024b3d0 : 48 -> 52
~ sub_10025bcd0 -> sub_10025bdd4 : 264 -> 260
~ sub_1003498e8 -> sub_1003499e8 : 452 -> 448
```
