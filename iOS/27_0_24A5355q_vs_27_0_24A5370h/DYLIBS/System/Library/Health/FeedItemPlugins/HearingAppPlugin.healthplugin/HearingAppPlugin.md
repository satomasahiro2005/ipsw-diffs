## HearingAppPlugin

> `/System/Library/Health/FeedItemPlugins/HearingAppPlugin.healthplugin/HearingAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81c7c` | `0x81dcc` | **`+0x150`** |
| `__TEXT.__cstring` | `0x2d65` | `0x2d25` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x1980` | `0x1988` | **`+0x8`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  CStrings:  358
+  CStrings:  357
Functions:
~ sub_228c0f2a8 -> sub_229bda2a8 : 4080 -> 4060
~ sub_228c10b80 -> sub_229bdbb6c : 2888 -> 2892
~ sub_228c12204 -> sub_229bdd1f4 : 4396 -> 4384
~ sub_228c13a0c -> sub_229bde9f0 : 1632 -> 1612
~ sub_228c1406c -> sub_229bdf03c : 1632 -> 1612
~ sub_228c15240 -> sub_229be01fc : 2396 -> 2368
~ sub_228c15b9c -> sub_229be0b3c : 2368 -> 2340
~ sub_228c192b8 -> sub_229be423c : 1644 -> 1692
~ sub_228c199d8 -> sub_229be498c : 764 -> 780
~ sub_228c1bb80 -> sub_229be6b44 : 1272 -> 1288
~ sub_228c1c170 -> sub_229be7144 : 2212 -> 2216
~ sub_228c1cc18 -> sub_229be7bf0 : 356 -> 352
~ sub_228c22d44 -> sub_229bedd18 : 3032 -> 3036
~ sub_228c244ec -> sub_229bef4c4 : 128 -> 136
~ sub_228c24e10 -> sub_229befdf0 : 232 -> 256
~ sub_228c25848 -> sub_229bf0840 : 1564 -> 1568
~ sub_228c29e6c -> sub_229bf4e68 : 776 -> 780
~ sub_228c367c4 -> sub_229c017c4 : 776 -> 780
~ sub_228c39320 -> sub_229c04324 : 156 -> 164
~ sub_228c397dc -> sub_229c047e8 : 140 -> 148
~ sub_228c39ab0 -> sub_229c04ac4 : 156 -> 164
~ sub_228c39c68 -> sub_229c04c84 : 408 -> 420
~ sub_228c3a7c8 -> sub_229c057f0 : 860 -> 864
~ sub_228c3b734 -> sub_229c06760 : 776 -> 780
~ sub_228c3d8cc -> sub_229c088fc : 156 -> 164
~ sub_228c3dabc -> sub_229c08af4 : 140 -> 148
~ sub_228c3dc4c -> sub_229c08c8c : 140 -> 148
~ sub_228c3ddc8 -> sub_229c08e10 : 392 -> 404
~ sub_228c3e5c0 -> sub_229c09614 : 88 -> 84
~ sub_228c3ee60 -> sub_229c09eb0 : 1056 -> 1060
~ sub_228c3f7dc -> sub_229c0a830 : 76 -> 72
~ sub_228c3fd88 -> sub_229c0add8 : 1788 -> 1824
~ sub_228c41c90 -> sub_229c0cd04 : 1308 -> 1312
~ sub_228c43940 -> sub_229c0e9b8 : 276 -> 264
~ sub_228c43db4 -> sub_229c0ee20 : 1272 -> 1260
~ sub_228c453a4 -> sub_229c10404 : 632 -> 628
~ sub_228c456d4 -> sub_229c10730 : 416 -> 424
~ sub_228c45874 -> sub_229c108d8 : 176 -> 188
~ sub_228c45abc -> sub_229c10b2c : 400 -> 424
~ sub_228c4925c -> sub_229c142e4 : 1136 -> 1132
~ sub_228c4e9d8 -> sub_229c19a5c : 504 -> 508
~ sub_228c4f9cc -> sub_229c1aa54 : 368 -> 364
~ sub_228c4fb3c -> sub_229c1abc0 : 348 -> 340
~ sub_228c4fc98 -> sub_229c1ad14 : 472 -> 464
~ sub_228c4fe70 -> sub_229c1aee4 : 832 -> 844
~ sub_228c5193c -> sub_229c1c9bc : 244 -> 248
~ sub_228c51b98 -> sub_229c1cc1c : 732 -> 708
~ sub_228c560fc -> sub_229c21168 : 4676 -> 4684
~ sub_228c5cf80 -> sub_229c27ff4 : 140 -> 160
~ sub_228c5d00c -> sub_229c28094 : 540 -> 564
~ sub_228c5d6a0 -> sub_229c28740 : 284 -> 292
~ sub_228c5d7bc -> sub_229c28864 : 400 -> 416
~ sub_228c5e070 -> sub_229c29128 : 480 -> 484
~ sub_228c5e8f8 -> sub_229c299b4 : 536 -> 548
~ sub_228c60394 -> sub_229c2b45c : 280 -> 276
~ sub_228c60e20 -> sub_229c2bee4 : 320 -> 328
~ sub_228c60f88 -> sub_229c2c054 : 352 -> 372
~ sub_228c61910 -> sub_229c2c9f0 : 804 -> 808
~ sub_228c628fc -> sub_229c2d9e0 : 2076 -> 2072
~ sub_228c63250 -> sub_229c2e330 : 880 -> 876
~ sub_228c635c0 -> sub_229c2e69c : 880 -> 876
~ sub_228c64274 -> sub_229c2f34c : 312 -> 292
~ sub_228c662ec -> sub_229c313b0 : 504 -> 500
~ sub_228c6b748 -> sub_229c36808 : 168 -> 172
~ sub_228c6b7f0 -> sub_229c368b4 : 168 -> 172
~ sub_228c6d248 -> sub_229c38310 : 248 -> 252
~ sub_228c6e8f0 -> sub_229c399bc : 1664 -> 1660
~ sub_228c7024c -> sub_229c3b314 : 332 -> 328
~ sub_228c70398 -> sub_229c3b45c : 112 -> 124
~ sub_228c70668 -> sub_229c3b738 : 3004 -> 3024
~ sub_228c72524 -> sub_229c3d608 : 248 -> 272
~ sub_228c7261c -> sub_229c3d718 : 232 -> 240
~ sub_228c72704 -> sub_229c3d808 : 220 -> 228
~ sub_228c727e0 -> sub_229c3d8ec : 264 -> 284
~ sub_228c728e8 -> sub_229c3da08 : 248 -> 272
~ sub_228c73998 -> sub_229c3ead0 : 2292 -> 2296
~ sub_228c74c38 -> sub_229c3fd74 : 136 -> 144
~ sub_228c793b8 -> sub_229c444fc : 636 -> 652
~ sub_228c7b270 -> sub_229c463c4 : 316 -> 324
~ sub_228c80124 -> sub_229c4b280 : 360 -> 368
~ sub_228c8123c -> sub_229c4c3a0 : 812 -> 828
~ sub_228c81660 -> sub_229c4c7d4 : 324 -> 328
~ sub_228c82548 -> sub_229c4d6c0 : 500 -> 504
~ sub_228c84860 -> sub_229c4f9dc : 4024 -> 3996
~ sub_228c85bf0 -> sub_229c50d50 : 312 -> 316
~ sub_228c8896c -> sub_229c53ad0 : 580 -> 576
~ sub_228c8b2ac -> sub_229c5640c : 1452 -> 1436
CStrings:
+ "AudiogramEducation-Localizable"
+ "HeadphoneListeningEducation-Localizable"
+ "HearingAidsEducation-Localizable"
+ "HearingHealthEducation-Localizable"
- "AudiogramEducation-Localizable-Yodel"
- "HeadphoneListeningEducation-Localizable-Yodel"
- "HearingAidsEducation-Localizable-Yodel"
- "HearingAppPlugin-Localizable-Yodel"
- "HearingHealthEducation-Localizable-Yodel"
```
