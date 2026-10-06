## AudioFlowDelegatePlugin

> `/System/Library/Assistant/FlowDelegatePlugins/AudioFlowDelegatePlugin.bundle/AudioFlowDelegatePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c9e8c` | `0x2cac64` | **`+0xdd8`** |
| `__DATA.__objc_const` | `0x9db0` | `0x9dd0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x6f00` | `0x6f20` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x3788` | `0x3798` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1ea8` | `0x1eb8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x421b` | `0x422b` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3654` | `0x3660` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.27.4.0.0
+3600.33.2.0.0

+  - /System/Library/Frameworks/StoreKit.framework/StoreKit

-  Symbols:   398
+  Symbols:   399
Symbols:
+ _OBJC_CLASS_$_SKCloudServiceController
Functions:
~ sub_4028 -> sub_4080 : 280 -> 276
~ sub_41b4 -> sub_4208 : 96 -> 104
~ sub_f8a0 -> sub_f8fc : 784 -> 960
~ sub_fc48 -> sub_fd54 : 276 -> 292
~ sub_11264 -> sub_11380 : 256 -> 276
~ sub_19ff4 -> sub_1a124 : 152 -> 160
~ sub_1aad4 -> sub_1ac0c : 25184 -> 25180
~ sub_20d34 -> sub_20e68 : 24680 -> 24740
~ sub_2db10 -> sub_2dc80 : 504 -> 508
~ sub_2dd08 -> sub_2de7c : 268 -> 280
~ sub_2dfe0 -> sub_2e160 : 2568 -> 2572
~ sub_2fae0 -> sub_2fc64 : 2144 -> 2180
~ sub_31598 -> sub_31740 : 13288 -> 13112
~ sub_34980 -> sub_34a78 : 488 -> 496
~ sub_35adc -> sub_35bdc : 524 -> 520
~ sub_36504 -> sub_36600 : 3576 -> 3520
~ sub_38028 -> sub_380ec : 1680 -> 1672
~ sub_45484 -> sub_45540 : 308 -> 320
~ sub_45d30 -> sub_45df8 : 1848 -> 1828
~ sub_4bbbc -> sub_4bc70 : 2668 -> 2696
~ sub_4f834 -> sub_4f904 : 308 -> 320
~ sub_56e64 -> sub_56f40 : 2568 -> 2572
~ sub_58c40 -> sub_58d20 : 2292 -> 2316
~ sub_5aad0 -> sub_5abc8 : 11312 -> 11360
~ sub_5f288 -> sub_5f3b0 : 524 -> 520
~ sub_5f690 -> sub_5f7b4 : 212 -> 228
~ sub_5f764 -> sub_5f898 : 404 -> 428
~ sub_5fa6c -> sub_5fbb8 : 536 -> 544
~ sub_5fc84 -> sub_5fdd8 : 320 -> 332
~ sub_5fdd8 -> sub_5ff38 : 488 -> 496
~ sub_63e3c -> sub_63fa4 : 476 -> 480
~ sub_64018 -> sub_64184 : 1704 -> 1712
~ sub_647dc -> sub_64950 : 2536 -> 2544
~ sub_6965c -> sub_697d8 : 168 -> 176
~ sub_6bb38 -> sub_6bcbc : 1632 -> 1644
~ sub_6c22c -> sub_6c3bc : 1708 -> 1716
~ sub_73f18 -> sub_740b0 : 308 -> 320
~ sub_78908 -> sub_78aac : 2908 -> 2936
~ sub_7b65c -> sub_7b81c : 524 -> 520
~ sub_7d360 -> sub_7d51c : 312 -> 316
~ sub_7e61c -> sub_7e7dc : 308 -> 324
~ sub_7e868 -> sub_7ea38 : 2272 -> 2276
~ sub_7f238 -> sub_7f40c : 1216 -> 1196
~ sub_8b544 -> sub_8b704 : 244 -> 268
~ sub_8b638 -> sub_8b810 : 244 -> 268
~ sub_8b72c -> sub_8b91c : 252 -> 276
~ sub_8b828 -> sub_8ba30 : 256 -> 264
~ sub_8b928 -> sub_8bb38 : 260 -> 276
~ sub_8ba2c -> sub_8bc4c : 272 -> 276
~ sub_8bb3c -> sub_8bd60 : 428 -> 424
~ sub_8c96c -> sub_8cb8c : 532 -> 548
~ sub_8cdfc -> sub_8d02c : 152 -> 160
~ sub_94284 -> sub_944bc : 544 -> 556
~ sub_9f0e0 -> sub_9f324 : 152 -> 160
~ sub_a1100 -> sub_a134c : 4912 -> 4936
~ sub_a699c -> sub_a6c00 : 772 -> 796
~ sub_a8000 -> sub_a827c : 1788 -> 1772
~ sub_a97f8 -> sub_a9a64 : 1420 -> 1444
~ sub_a9f58 -> sub_aa1dc : 524 -> 508
~ sub_aba44 -> sub_abcb8 : 124 -> 132
~ sub_abac0 -> sub_abd3c : 176 -> 180
~ sub_ad114 -> sub_ad394 : 2628 -> 2644
~ sub_adb58 -> sub_adde8 : 2468 -> 2516
~ sub_b16ac -> sub_b196c : 2828 -> 2840
~ sub_b36e8 -> sub_b39b4 : 480 -> 484
~ sub_b53dc -> sub_b56ac : 2528 -> 2552
~ sub_be4d4 -> sub_be7bc : 956 -> 972
~ sub_be890 -> sub_beb88 : 988 -> 1004
~ sub_bf16c -> sub_bf474 : 980 -> 996
~ sub_c0168 -> sub_c0480 : 136 -> 144
~ sub_c01f0 -> sub_c0510 : 280 -> 292
~ sub_cc0d4 -> sub_cc400 : 364 -> 368
~ sub_daae8 -> sub_dae18 : 1260 -> 1276
~ sub_dafd4 -> sub_db314 : 1268 -> 1284
~ sub_dbb3c -> sub_dbe8c : 1248 -> 1264
~ sub_dc01c -> sub_dc37c : 1244 -> 1260
~ sub_dcd80 -> sub_dd0f0 : 1260 -> 1276
~ sub_dd64c -> sub_dd9cc : 1236 -> 1252
~ sub_ddce8 -> sub_de078 : 1080 -> 1096
~ sub_de120 -> sub_de4c0 : 1108 -> 1124
~ sub_dead0 -> sub_dee80 : 1100 -> 1116
~ sub_e2c3c -> sub_e2ffc : 1220 -> 1236
~ sub_e3100 -> sub_e34d0 : 1228 -> 1244
~ sub_e3c40 -> sub_e4020 : 1228 -> 1244
~ sub_e410c -> sub_e44fc : 1204 -> 1220
~ sub_e4d28 -> sub_e5128 : 1220 -> 1236
~ sub_e538c -> sub_e579c : 1196 -> 1212
~ sub_e5a00 -> sub_e5e20 : 1060 -> 1076
~ sub_e5e24 -> sub_e6254 : 1068 -> 1084
~ sub_e6ae0 -> sub_e6f20 : 1060 -> 1076
~ sub_e9d68 -> sub_ea1b8 : 180 -> 188
~ sub_e9e68 -> sub_ea2c0 : 756 -> 752
~ sub_f0f44 -> sub_f1398 : 2872 -> 2880
~ sub_f27a4 -> sub_f2c00 : 3336 -> 3312
~ sub_f5604 -> sub_f5a48 : 4940 -> 5028
~ sub_f6f34 -> sub_f73d0 : 152 -> 160
~ sub_107e58 -> sub_1082fc : 7376 -> 7544
~ sub_112f14 -> sub_113460 : 304 -> 316
~ sub_118f88 -> sub_1194e0 : 316 -> 328
~ sub_119fcc -> sub_11a530 : 5248 -> 5244
~ sub_124568 -> sub_124ac8 : 3172 -> 3188
~ sub_1269a0 -> sub_126f10 : 152 -> 160
~ sub_126e4c -> sub_1273c4 : 5940 -> 5948
~ sub_128930 -> sub_128eb0 : 216 -> 220
~ sub_12a8dc -> sub_12ae60 : 128 -> 136
~ sub_12a95c -> sub_12aee8 : 220 -> 224
~ sub_13213c -> sub_1326cc : 2068 -> 2136
~ sub_133074 -> sub_133648 : 152 -> 160
~ sub_1331e0 -> sub_1337bc : 1492 -> 1664
~ sub_13a880 -> sub_13af08 : 2680 -> 2836
~ sub_1448ec -> sub_145010 : 332 -> 336
~ sub_144a38 -> sub_145160 : 524 -> 520
~ sub_154b18 -> sub_15523c : 292 -> 304
~ sub_155630 -> sub_155d60 : 1224 -> 1228
~ sub_159d8c -> sub_15a4c0 : 4320 -> 4336
~ sub_15f048 -> sub_15f78c : 4336 -> 4352
~ sub_162540 -> sub_162c94 : 4544 -> 4560
~ sub_16c8cc -> sub_16d030 : 408 -> 428
~ sub_16ca9c -> sub_16d214 : 300 -> 312
~ sub_16d340 -> sub_16dac4 : 560 -> 572
~ sub_16d968 -> sub_16e0f8 : 552 -> 568
~ sub_16dd64 -> sub_16e504 : 464 -> 476
~ sub_177680 -> sub_177e2c : 2932 -> 2940
~ sub_1781f4 -> sub_1789a8 : 1988 -> 2024
~ sub_179304 -> sub_179adc : 2636 -> 2696
~ sub_17a0b8 -> sub_17a8cc : 2440 -> 2516
~ sub_17abc4 -> sub_17b424 : 7064 -> 7060
~ sub_17c75c -> sub_17cfb8 : 488 -> 496
~ sub_17c944 -> sub_17d1a8 : 5316 -> 5292
~ sub_180d64 -> sub_1815b0 : 664 -> 684
~ sub_180ffc -> sub_18185c : 1288 -> 1304
~ sub_181e5c -> sub_1826cc : 444 -> 456
~ sub_182018 -> sub_182894 : 372 -> 376
~ sub_183fb0 -> sub_184830 : 268 -> 292
~ sub_1848a8 -> sub_185140 : 276 -> 284
~ sub_185358 -> sub_185bf8 : 25252 -> 25448
~ sub_19a100 -> sub_19aa64 : 140 -> 148
~ sub_19a228 -> sub_19ab94 : 152 -> 160
~ sub_19abf0 -> sub_19b564 : 128 -> 148
~ sub_1a0550 -> sub_1a0ed8 : 8516 -> 8496
~ sub_1a26b8 -> sub_1a302c : 60 -> 68
~ sub_1a6b78 -> sub_1a74f4 : 1492 -> 1488
~ sub_1bb19c -> sub_1bbb14 : 152 -> 160
~ sub_1bb6c4 -> sub_1bc044 : 1056 -> 1064
~ sub_1bd488 -> sub_1bde10 : 288 -> 296
~ sub_1bd5a8 -> sub_1bdf38 : 328 -> 336
~ sub_1be20c -> sub_1beba4 : 316 -> 324
~ sub_1c2d9c -> sub_1c373c : 140 -> 148
~ sub_1c5240 -> sub_1c5be8 : 472 -> 484
~ sub_1c795c -> sub_1c8310 : 308 -> 320
~ sub_1cdbb0 -> sub_1ce570 : 372 -> 376
~ sub_1cdd30 -> sub_1ce6f4 : 444 -> 456
~ sub_1cdeec -> sub_1ce8bc : 372 -> 376
~ sub_1ce208 -> sub_1cebdc : 240 -> 244
~ sub_1ce400 -> sub_1cedd8 : 460 -> 472
~ sub_1d3e5c -> sub_1d4840 : 9096 -> 9040
~ sub_1d61e4 -> sub_1d6b90 : 308 -> 320
~ sub_1db254 -> sub_1dbc0c : 1984 -> 1960
~ sub_1dba14 -> sub_1dc3b4 : 716 -> 712
~ sub_1dbce0 -> sub_1dc67c : 856 -> 868
~ sub_1dc044 -> sub_1dc9ec : 7272 -> 7432
~ sub_1ddd88 -> sub_1de7d0 : 4404 -> 4420
~ sub_1df6a4 -> sub_1e00fc : 2636 -> 2640
~ sub_1e0dd4 -> sub_1e1830 : 1528 -> 1524
~ sub_1e13cc -> sub_1e1e24 : 1032 -> 1028
~ sub_1e1bcc -> sub_1e2620 : 300 -> 316
~ sub_1e6b90 -> sub_1e75f4 : 620 -> 636
~ sub_1e6dfc -> sub_1e7870 : 1196 -> 1220
~ sub_1e94f4 -> sub_1e9f80 : 344 -> 340
~ sub_1e96f8 -> sub_1ea180 : 8568 -> 8600
~ sub_1eb8a8 -> sub_1ec350 : 2132 -> 2128
~ sub_1ec0fc -> sub_1ecba0 : 408 -> 428
~ sub_1ec294 -> sub_1ecd4c : 152 -> 164
~ sub_1ec3d8 -> sub_1ece9c : 764 -> 808
~ sub_1f2f7c -> sub_1f3a6c : 436 -> 432
~ sub_1f3154 -> sub_1f3c40 : 1412 -> 1588
~ sub_1f36d8 -> sub_1f4274 : 868 -> 1040
~ sub_1f3a3c -> sub_1f4684 : 9636 -> 10416
~ sub_1ff1e4 -> sub_200138 : 5068 -> 5064
~ sub_20b044 -> sub_20bf94 : 152 -> 160
~ sub_20fa40 -> sub_210998 : 1224 -> 1248
~ sub_213fb8 -> sub_214f28 : 15992 -> 15924
~ sub_21e59c -> sub_21f4c8 : 116 -> 132
~ sub_21e610 -> sub_21f54c : 268 -> 280
~ sub_21e71c -> sub_21f664 : 900 -> 896
~ sub_223778 -> sub_2246bc : 7496 -> 7548
~ sub_228d1c -> sub_229c94 : 3232 -> 3200
~ sub_2299bc -> sub_22a914 : 1656 -> 1668
~ sub_22a034 -> sub_22af98 : 4860 -> 4884
~ sub_22ddd4 -> sub_22ed50 : 348 -> 344
~ sub_23057c -> sub_2314f4 : 152 -> 160
~ sub_230790 -> sub_231710 : 560 -> 580
~ sub_2309c0 -> sub_231954 : 604 -> 592
~ sub_232090 -> sub_233018 : 852 -> 856
~ sub_236344 -> sub_2372d0 : 568 -> 552
~ sub_2368b0 -> sub_23782c : 480 -> 488
~ sub_2391ac -> sub_23a130 : 5488 -> 5476
~ sub_23e918 -> sub_23f890 : 692 -> 684
~ sub_23f628 -> sub_240598 : 412 -> 388
~ sub_23f7c4 -> sub_24071c : 360 -> 352
~ sub_24b014 -> sub_24bf64 : 4300 -> 4264
~ sub_265f7c -> sub_266ea8 : 2240 -> 2216
~ sub_266a50 -> sub_267964 : 308 -> 320
~ sub_266f8c -> sub_267eac : 128 -> 136
~ sub_26700c -> sub_267f34 : 220 -> 224
~ sub_2671ac -> sub_2680d8 : 228 -> 232
~ sub_2673ec -> sub_26831c : 348 -> 352
~ sub_267548 -> sub_26847c : 316 -> 328
~ sub_2783c8 -> sub_279308 : 332 -> 336
~ sub_27a528 -> sub_27b46c : 3136 -> 3060
~ sub_27c564 -> sub_27d45c : 320 -> 312
~ sub_27c834 -> sub_27d724 : 164 -> 172
~ sub_27ccf0 -> sub_27dbe8 : 280 -> 292
~ sub_27ce78 -> sub_27dd7c : 272 -> 284
~ sub_27d0b0 -> sub_27dfc0 : 208 -> 216
~ sub_27d244 -> sub_27e15c : 128 -> 136
~ sub_27f378 -> sub_280298 : 3268 -> 3276
~ sub_284828 -> sub_285750 : 400 -> 404
~ sub_28d4e4 -> sub_28e410 : 1796 -> 1792
~ sub_28dbe8 -> sub_28eb10 : 1796 -> 1792
~ sub_2981e8 -> sub_29910c : 5464 -> 5484
~ sub_29a384 -> sub_29b2bc : 5616 -> 5560
~ sub_29c970 -> sub_29d870 : 4820 -> 4780
~ sub_2a5628 -> sub_2a6500 : 140 -> 148
~ sub_2aefb8 -> sub_2afe98 : 164 -> 172
~ sub_2b0134 -> sub_2b101c : 1140 -> 1112
~ sub_2b05a8 -> sub_2b1474 : 1012 -> 1000
~ sub_2b099c -> sub_2b185c : 1184 -> 1168
~ sub_2b0e3c -> sub_2b1cec : 892 -> 880
~ sub_2b1294 -> sub_2b2138 : 320 -> 308
~ sub_2b13d4 -> sub_2b226c : 6320 -> 6200
~ sub_2b42e4 -> sub_2b5104 : 2168 -> 2172
~ sub_2b52a8 -> sub_2b60cc : 4608 -> 4624
~ sub_2b959c -> sub_2ba3d0 : 152 -> 160
~ sub_2bda48 -> sub_2be884 : 1216 -> 1212
~ sub_2bdf08 -> sub_2bed40 : 1216 -> 1212
~ sub_2c05bc -> sub_2c13f0 : 2392 -> 2388
```
