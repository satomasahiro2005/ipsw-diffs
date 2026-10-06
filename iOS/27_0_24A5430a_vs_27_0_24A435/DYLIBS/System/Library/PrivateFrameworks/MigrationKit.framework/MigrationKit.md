## MigrationKit

> `/System/Library/PrivateFrameworks/MigrationKit.framework/MigrationKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78aa64` | `0x78abd0` | **`+0x16c`** |

### Other Changes

```text
Functions:
~ -[MKHomescreenMigrator import:] : 1276 -> 1280
~ sub_29049296c -> sub_2909d9970 : 1024 -> 1028
~ sub_29049fdcc -> sub_2909e6dd4 : 852 -> 848
~ sub_2904a0120 -> sub_2909e7124 : 408 -> 412
~ sub_29053bf58 -> sub_290a82f60 : 1952 -> 1960
~ sub_29056d32c -> sub_290ab433c : 1444 -> 1448
~ sub_29056d8d0 -> sub_290ab48e4 : 1636 -> 1640
~ sub_29056df34 -> sub_290ab4f4c : 1608 -> 1564
~ sub_290590b34 -> sub_290ad7b20 : 1552 -> 1544
~ sub_29059ceac -> sub_290ae3e90 : 3184 -> 3204
~ sub_29059db1c -> sub_290ae4b14 : 3004 -> 3028
~ sub_2905ab65c -> sub_290af266c : 968 -> 972
~ sub_2905e7170 -> sub_290b2e184 : 240 -> 236
~ sub_2905f353c -> sub_290b3a54c : 836 -> 844
~ sub_2905f4848 -> sub_290b3b860 : 908 -> 924
~ sub_2905f57b4 -> sub_290b3c7dc : 720 -> 724
~ sub_2905f5a84 -> sub_290b3cab0 : 708 -> 728
~ sub_2905f5d48 -> sub_290b3cd88 : 708 -> 728
~ sub_2905f6ad0 -> sub_290b3db24 : 824 -> 776
~ sub_2905f706c -> sub_290b3e090 : 776 -> 768
~ sub_2905f7b30 -> sub_290b3eb4c : 712 -> 716
~ sub_2905f7df8 -> sub_290b3ee18 : 764 -> 768
~ sub_2905f8660 -> sub_290b3f684 : 848 -> 856
~ sub_2905fa040 -> sub_290b4106c : 360 -> 364
~ sub_2905fa1e4 -> sub_290b41214 : 380 -> 384
~ sub_2905fa4c0 -> sub_290b414f4 : 616 -> 624
~ sub_2905fab30 -> sub_290b41b6c : 648 -> 652
~ sub_2905fb548 -> sub_290b42588 : 356 -> 360
~ sub_2905fb944 -> sub_290b42988 : 360 -> 364
~ sub_2905fc5cc -> sub_290b43614 : 456 -> 460
~ sub_2905fc794 -> sub_290b437e0 : 360 -> 364
~ sub_2905fc8fc -> sub_290b4394c : 360 -> 364
~ sub_2905fd058 -> sub_290b440ac : 372 -> 376
~ sub_2905fd1cc -> sub_290b44224 : 372 -> 376
~ sub_2905fd75c -> sub_290b447b8 : 456 -> 460
~ sub_2905fdd90 -> sub_290b44df0 : 344 -> 348
~ sub_2905fdee8 -> sub_290b44f4c : 356 -> 360
~ sub_2905fe1b4 -> sub_290b4521c : 392 -> 396
~ sub_2905fe73c -> sub_290b457a8 : 380 -> 384
~ sub_2905fe8b8 -> sub_290b45928 : 356 -> 360
~ sub_29060ac28 -> sub_290b51c9c : 3356 -> 3388
~ sub_29060ba04 -> sub_290b52a98 : 3808 -> 3840
~ sub_29061394c -> sub_290b5aa00 : 404 -> 408
~ sub_290642b7c -> sub_290b89c34 : 1592 -> 1596
~ sub_290652f64 -> sub_290b9a020 : 3688 -> 3708
~ sub_29067bfec -> sub_290bc30bc : 604 -> 608
~ sub_29067c248 -> sub_290bc331c : 732 -> 736
~ sub_29067c524 -> sub_290bc35fc : 680 -> 684
~ sub_29067e3b8 -> sub_290bc5494 : 5528 -> 5552
~ sub_2906840fc -> sub_290bcb1f0 : 3304 -> 3284
~ sub_2906860e8 -> sub_290bcd1c8 : 4632 -> 4604
~ sub_29068c184 -> sub_290bd3248 : 1176 -> 1180
~ sub_29068c644 -> sub_290bd370c : 1152 -> 1156
~ sub_29068cac4 -> sub_290bd3b90 : 4268 -> 4180
~ sub_29068eae0 -> sub_290bd5b54 : 448 -> 456
~ sub_2906a3584 -> sub_290bea600 : 1656 -> 1660
~ sub_2906b5a6c -> sub_290bfcaec : 10812 -> 10820
~ sub_2906f5bf4 -> sub_290c3cc7c : 1604 -> 1600
~ sub_2906f6650 -> sub_290c3d6d4 : 1052 -> 1056
~ sub_29073e558 -> sub_290c855e0 : 1152 -> 1156
~ sub_29073e9d8 -> sub_290c85a64 : 1348 -> 1352
~ sub_29073ef34 -> sub_290c85fc4 : 1212 -> 1216
~ sub_29073f3f0 -> sub_290c86484 : 1164 -> 1168
~ sub_29073f87c -> sub_290c86914 : 1300 -> 1304
~ sub_29073fda8 -> sub_290c86e44 : 1124 -> 1128
~ sub_29074020c -> sub_290c872ac : 1204 -> 1208
~ sub_2907406c0 -> sub_290c87764 : 1204 -> 1208
~ sub_290740b74 -> sub_290c87c1c : 1312 -> 1316
~ sub_2907410b0 -> sub_290c8815c : 1196 -> 1200
~ sub_2907415e8 -> sub_290c88698 : 116 -> 120
~ sub_29074fa90 -> sub_290c96b44 : 992 -> 988
~ sub_290757404 -> sub_290c9e4b4 : 2232 -> 2236
~ sub_290757cbc -> sub_290c9ed70 : 976 -> 980
~ sub_29075895c -> sub_290c9fa14 : 400 -> 404
~ sub_290758db8 -> sub_290c9fe74 : 3168 -> 3172
~ sub_290759a18 -> sub_290ca0ad8 : 412 -> 416
~ sub_290759c00 -> sub_290ca0cc4 : 752 -> 756
~ sub_29075ca34 -> sub_290ca3afc : 172 -> 176
~ sub_29075cb90 -> sub_290ca3c5c : 752 -> 756
~ sub_29075d2dc -> sub_290ca43ac : 428 -> 436
~ sub_29075d520 -> sub_290ca45f8 : 1184 -> 1192
~ sub_29075d9c0 -> sub_290ca4aa0 : 404 -> 408
~ sub_2907a0970 -> sub_290ce7a54 : 3232 -> 3264
~ sub_2907a27a0 -> sub_290ce98a4 : 632 -> 636
~ sub_2907a80dc -> sub_290cef1e4 : 812 -> 816
~ sub_2907f4d0c -> sub_290d3be18 : 13400 -> 13468
~ sub_290806d14 -> sub_290d4de64 : 372 -> 376
~ sub_2908074b0 -> sub_290d4e604 : 668 -> 692
~ sub_290807da0 -> sub_290d4ef0c : 372 -> 376
~ sub_29083509c -> sub_290d7c20c : 2668 -> 2672
~ sub_2908391e8 -> sub_290d8035c : 3292 -> 3288
~ sub_290856fc0 -> sub_290d9e130 : 1244 -> 1248
~ sub_2908586f8 -> sub_290d9f86c : 4128 -> 4108
~ sub_2908bc9f8 -> sub_290e03b58 : 7388 -> 7348
~ sub_2909df7b4 -> sub_290f268ec : 208 -> 212
~ sub_2909df89c -> sub_290f269d8 : 184 -> 192
~ sub_2909dfab4 -> sub_290f26bf8 : 256 -> 264
~ sub_290a2eaa8 -> sub_290f75bf4 : 4052 -> 4060
~ sub_290a37084 -> sub_290f7e1d8 : 1292 -> 1284
~ sub_290a5db64 -> sub_290fa4cb0 : 6376 -> 6388
~ sub_290ab0a44 -> sub_290ff7b9c : 704 -> 696
~ sub_290ab7724 -> sub_290ffe874 : 1096 -> 1100
~ sub_290ac2984 -> sub_291009ad8 : 284 -> 288
~ sub_290ae8e54 -> sub_29102ffac : 684 -> 688
~ sub_290aed4d0 -> sub_29103462c : 852 -> 856
~ sub_290af46ec -> sub_29103b84c : 5480 -> 5488
~ sub_290b28abc -> sub_29106fc24 : 384 -> 388
```
