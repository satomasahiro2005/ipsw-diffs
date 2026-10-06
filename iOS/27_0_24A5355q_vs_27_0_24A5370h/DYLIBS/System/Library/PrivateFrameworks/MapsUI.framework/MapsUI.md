## MapsUI

> `/System/Library/PrivateFrameworks/MapsUI.framework/MapsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a4f6c` | `0x1a5cc0` | **`+0xd54`** |
| `__TEXT.__delay_stubs` | `—` | `0x1c0` | **`+0x1c0`** |
| `__AUTH_CONST.__objc_const` | `0x2b9d8` | `0x2bb58` | **`+0x180`** |
| `__TEXT.__cstring` | `0x1219d` | `0x12297` | **`+0xfa`** |
| `__TEXT.__delay_helper` | `—` | `0xdc` | **`+0xdc`** |
| `__TEXT.__objc_methlist` | `0x156f4` | `0x157a4` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x15520` | `0x15580` | **`+0x60`** |
| `__AUTH.__objc_data` | `0xbd08` | `0xbd58` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x65e0` | `0x6628` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0xa448` | `0xa478` | **`+0x30`** |
| `__TEXT.__const` | `0x80d8` | `0x8108` | **`+0x30`** |
| `__DATA.__data` | `0x58d0` | `0x58f4` | **`+0x24`** |
| `__AUTH_CONST.__const` | `0x6a28` | `0x6a48` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1460` | `0x1478` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x167c` | `0x1694` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x2f10` | `0x2f28` | **`+0x18`** |
| `__DATA.__bss` | `0x5e98` | `0x5ea8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x14d8` | `0x14e8` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x10f4` | `0x10e4` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2fe7` | `0x2ff7` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x361c` | `0x3628` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0xd90` | `0xd98` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x4c4` | `0x4c0` | **`-0x4`** |

### Other Changes

```diff

-281.30.5.15.1
+284.30.6.5.2

-  Functions: 10133
-  Symbols:   13607
-  CStrings:  3417
+  Functions: 10154
+  Symbols:   13644
+  CStrings:  3422
Symbols:
+ +[MUETAHelper isFarAwayForETAProvider:]
+ +[MUFadingLabel _lineHeightCache]
+ -[MUCuratedGuidesSectionView collectionCount]
+ -[MUCuratedGuidesSectionView layoutSubviews]
+ -[MUCuratedGuidesSectionView setCollectionCount:]
+ -[MULinkMetadataActivityProvider activityViewControllerLinkMetadata:]
+ -[MUPlacePhotoSliderView _gridContentInset]
+ -[MUPlacePhotoSliderView _rowFittingSize:]
+ -[MUPlacePhotoSliderView _updatePhotoTileSizeForWidth:]
+ -[MUPlaceRibbonItemView updateAppearance]
+ -[MUPlaceRibbonItemViewCell updateAppearance]
+ -[MUPlaceRibbonView layoutSubviews]
+ -[_MUPlaceRibbonFlowLayout shouldInvalidateLayoutForBoundsChange:]
+ GCC_except_table1204
+ GCC_except_table1206
+ GCC_except_table1209
+ GCC_except_table1320
+ GCC_except_table1338
+ GCC_except_table1340
+ GCC_except_table1387
+ GCC_except_table1450
+ GCC_except_table1462
+ GCC_except_table1494
+ GCC_except_table1514
+ GCC_except_table1517
+ GCC_except_table1549
+ GCC_except_table1648
+ GCC_except_table1723
+ GCC_except_table1749
+ GCC_except_table1841
+ GCC_except_table1847
+ GCC_except_table1916
+ GCC_except_table2026
+ GCC_except_table2035
+ GCC_except_table2043
+ GCC_except_table2046
+ GCC_except_table2069
+ GCC_except_table2071
+ GCC_except_table2096
+ GCC_except_table2101
+ GCC_except_table2115
+ GCC_except_table2149
+ GCC_except_table2150
+ GCC_except_table2158
+ GCC_except_table2167
+ GCC_except_table2169
+ GCC_except_table2181
+ GCC_except_table2211
+ GCC_except_table2220
+ GCC_except_table2221
+ GCC_except_table2240
+ GCC_except_table2245
+ GCC_except_table2277
+ GCC_except_table2279
+ GCC_except_table2282
+ GCC_except_table2304
+ GCC_except_table2315
+ GCC_except_table2398
+ GCC_except_table2406
+ GCC_except_table2423
+ GCC_except_table2462
+ GCC_except_table2464
+ GCC_except_table2474
+ GCC_except_table2477
+ GCC_except_table2489
+ GCC_except_table2507
+ GCC_except_table2518
+ GCC_except_table2536
+ GCC_except_table2618
+ GCC_except_table2711
+ GCC_except_table2731
+ GCC_except_table2749
+ GCC_except_table2775
+ GCC_except_table2962
+ GCC_except_table2977
+ GCC_except_table2985
+ GCC_except_table2988
+ GCC_except_table3007
+ GCC_except_table3010
+ GCC_except_table3011
+ GCC_except_table3125
+ GCC_except_table3141
+ GCC_except_table3198
+ GCC_except_table3212
+ GCC_except_table3277
+ GCC_except_table3340
+ GCC_except_table3392
+ GCC_except_table3435
+ GCC_except_table3441
+ GCC_except_table3468
+ GCC_except_table3472
+ GCC_except_table3478
+ GCC_except_table3498
+ GCC_except_table3500
+ GCC_except_table3504
+ GCC_except_table3505
+ GCC_except_table3525
+ GCC_except_table3571
+ GCC_except_table3592
+ GCC_except_table3642
+ GCC_except_table3650
+ GCC_except_table3654
+ GCC_except_table3657
+ GCC_except_table3658
+ GCC_except_table3940
+ GCC_except_table3944
+ GCC_except_table4042
+ GCC_except_table4084
+ GCC_except_table4105
+ GCC_except_table4186
+ GCC_except_table4215
+ GCC_except_table4216
+ GCC_except_table4228
+ GCC_except_table4257
+ GCC_except_table4301
+ GCC_except_table4302
+ GCC_except_table4305
+ GCC_except_table4350
+ GCC_except_table4356
+ GCC_except_table4374
+ GCC_except_table4403
+ GCC_except_table4420
+ GCC_except_table4449
+ GCC_except_table4503
+ GCC_except_table4535
+ GCC_except_table4552
+ GCC_except_table4559
+ GCC_except_table4604
+ GCC_except_table4610
+ GCC_except_table4621
+ GCC_except_table4808
+ GCC_except_table4855
+ GCC_except_table4888
+ GCC_except_table4965
+ GCC_except_table5197
+ GCC_except_table5388
+ GCC_except_table5428
+ GCC_except_table5438
+ GCC_except_table5439
+ GCC_except_table5464
+ GCC_except_table5577
+ GCC_except_table5581
+ GCC_except_table870
+ _MUIsVisionIdiom
+ _MUPlaceGridGutter
+ _MUPlaceGridHorizontalPadding
+ _MUPlaceGridItemWidth
+ _MUPlaceGridPeek
+ _MUPlaceGridVisibleItems
+ _OBJC_CLASS_$__MUPlaceRibbonFlowLayout
+ _OBJC_IVAR_$_MUCuratedGuidesSectionView._collectionCount
+ _OBJC_IVAR_$_MUPlacePhotoSliderView._didApplyInitialContentOffset
+ _OBJC_IVAR_$_MUPlacePhotoSliderView._heightConstraint
+ _OBJC_IVAR_$_MUPlacePhotoSliderView._lastLaidOutWidth
+ _OBJC_IVAR_$_MUPlaceRibbonView._didApplyInitialContentOffset
+ _OBJC_IVAR_$_MUPlaceRibbonView._lastCollectionViewWidth
+ _OBJC_METACLASS_$__MUPlaceRibbonFlowLayout
+ __OBJC_$_CLASS_METHODS_MUFadingLabel
+ __OBJC_$_INSTANCE_METHODS__MUPlaceRibbonFlowLayout
+ __OBJC_CLASS_RO_$__MUPlaceRibbonFlowLayout
+ __OBJC_METACLASS_RO_$__MUPlaceRibbonFlowLayout
+ ___33+[MUFadingLabel _lineHeightCache]_block_invoke
+ ___block_descriptor_32_e44_"NSProgress"16?0?<v?"NSURL""NSError">8l
+ ___block_descriptor_48_e8_32s40w_e44_"NSProgress"16?0?<v?"NSURL""NSError">8lw40l8s32l8
+ __lineHeightCache.cache
+ __lineHeightCache.onceToken
+ _dlopen
+ _dlopenHelper$PromotedContentUI
+ _dlopenHelperFlag$PromotedContentUI
+ _swift_retain_x26
+ _swift_retain_x27
+ _symbolic Shy_____G 7Combine14AnyCancellableC
+ _symbolic _____y_____G s11_SetStorageC 7Combine14AnyCancellableC
- GCC_except_table1200
- GCC_except_table1202
- GCC_except_table1205
- GCC_except_table1316
- GCC_except_table1334
- GCC_except_table1336
- GCC_except_table1383
- GCC_except_table1443
- GCC_except_table1455
- GCC_except_table1487
- GCC_except_table1507
- GCC_except_table1510
- GCC_except_table1542
- GCC_except_table1634
- GCC_except_table1716
- GCC_except_table1742
- GCC_except_table1834
- GCC_except_table1840
- GCC_except_table1909
- GCC_except_table2019
- GCC_except_table2028
- GCC_except_table2036
- GCC_except_table2039
- GCC_except_table2062
- GCC_except_table2064
- GCC_except_table2082
- GCC_except_table2094
- GCC_except_table2108
- GCC_except_table2142
- GCC_except_table2143
- GCC_except_table2151
- GCC_except_table2153
- GCC_except_table2162
- GCC_except_table2174
- GCC_except_table2204
- GCC_except_table2213
- GCC_except_table2214
- GCC_except_table2233
- GCC_except_table2238
- GCC_except_table2270
- GCC_except_table2272
- GCC_except_table2275
- GCC_except_table2297
- GCC_except_table2301
- GCC_except_table2391
- GCC_except_table2399
- GCC_except_table2416
- GCC_except_table2455
- GCC_except_table2457
- GCC_except_table2467
- GCC_except_table2470
- GCC_except_table2482
- GCC_except_table2500
- GCC_except_table2511
- GCC_except_table2529
- GCC_except_table2608
- GCC_except_table2701
- GCC_except_table2721
- GCC_except_table2739
- GCC_except_table2765
- GCC_except_table2952
- GCC_except_table2967
- GCC_except_table2975
- GCC_except_table2978
- GCC_except_table2997
- GCC_except_table3000
- GCC_except_table3001
- GCC_except_table3115
- GCC_except_table3131
- GCC_except_table3188
- GCC_except_table3202
- GCC_except_table3264
- GCC_except_table3326
- GCC_except_table3378
- GCC_except_table3421
- GCC_except_table3427
- GCC_except_table3454
- GCC_except_table3458
- GCC_except_table3464
- GCC_except_table3476
- GCC_except_table3484
- GCC_except_table3486
- GCC_except_table3491
- GCC_except_table3511
- GCC_except_table3557
- GCC_except_table3578
- GCC_except_table3628
- GCC_except_table3636
- GCC_except_table3640
- GCC_except_table3643
- GCC_except_table3644
- GCC_except_table3926
- GCC_except_table3930
- GCC_except_table4028
- GCC_except_table4070
- GCC_except_table4091
- GCC_except_table4172
- GCC_except_table4201
- GCC_except_table4202
- GCC_except_table4214
- GCC_except_table4243
- GCC_except_table4287
- GCC_except_table4288
- GCC_except_table4291
- GCC_except_table4336
- GCC_except_table4342
- GCC_except_table4360
- GCC_except_table4388
- GCC_except_table4405
- GCC_except_table4434
- GCC_except_table4488
- GCC_except_table4520
- GCC_except_table4537
- GCC_except_table4544
- GCC_except_table4589
- GCC_except_table4595
- GCC_except_table4606
- GCC_except_table4793
- GCC_except_table4840
- GCC_except_table4871
- GCC_except_table4948
- GCC_except_table5180
- GCC_except_table5369
- GCC_except_table5409
- GCC_except_table5419
- GCC_except_table5420
- GCC_except_table5445
- GCC_except_table5558
- GCC_except_table5562
- GCC_except_table866
- _MUScaledVisionMetric
- _OBJC_CLASS_$_UICollectionViewFlowLayoutInvalidationContext
- _UTTypeURL
- ___block_descriptor_32_e63_v32?0?<v?"<NSSecureCoding>""NSError">8#16"NSDictionary"24l
- ___block_descriptor_48_e8_32s40w_e63_v32?0?<v?"<NSSecureCoding>""NSError">8#16"NSDictionary"24lw40l8s32l8
- _swift_retain_x25
CStrings:
+ "/System/Library/PrivateFrameworks/PromotedContentUI.framework/PromotedContentUI"
+ "@\"NSProgress\"16@?0@?<v@?@\"NSURL\"@\"NSError\">8"
+ "Plan"
+ "REORDER_ADD_STOP"
+ "TAP_ENRICHMENT_MARK"
+ "\xc2"
- "v32@?0@?<v@?@\"<NSSecureCoding>\"@\"NSError\">8#16@\"NSDictionary\"24"
```
