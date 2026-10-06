## VectorKit

> `/System/Library/AccessibilityBundles/VectorKit.axbundle/VectorKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27b20` | `0x27b88` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x3898` | `0x38c8` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x4da4` | `0x4db4` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2100` | `0x2108` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2b30` | `0x2b38` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x24c` | `0x250` | **`+0x4`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 873
-  Symbols:   2005
+  Functions: 874
+  Symbols:   2007
Symbols:
+ -[AXVKMultiSectionFeatureWrapper tileRect]
+ GCC_except_table209
+ GCC_except_table213
+ GCC_except_table225
+ GCC_except_table255
+ GCC_except_table257
+ GCC_except_table261
+ GCC_except_table267
+ GCC_except_table270
+ GCC_except_table281
+ GCC_except_table288
+ GCC_except_table304
+ GCC_except_table309
+ GCC_except_table313
+ GCC_except_table318
+ GCC_except_table325
+ GCC_except_table328
+ GCC_except_table337
+ GCC_except_table340
+ GCC_except_table342
+ GCC_except_table349
+ GCC_except_table353
+ GCC_except_table358
+ GCC_except_table362
+ GCC_except_table364
+ GCC_except_table367
+ GCC_except_table371
+ GCC_except_table440
+ GCC_except_table445
+ GCC_except_table450
+ GCC_except_table453
+ GCC_except_table456
+ GCC_except_table459
+ GCC_except_table473
+ GCC_except_table481
+ GCC_except_table483
+ GCC_except_table488
+ GCC_except_table494
+ GCC_except_table497
+ GCC_except_table501
+ GCC_except_table504
+ GCC_except_table507
+ GCC_except_table511
+ GCC_except_table519
+ GCC_except_table523
+ GCC_except_table530
+ GCC_except_table532
+ GCC_except_table536
+ GCC_except_table544
+ GCC_except_table546
+ GCC_except_table548
+ GCC_except_table552
+ GCC_except_table554
+ GCC_except_table565
+ GCC_except_table572
+ GCC_except_table575
+ GCC_except_table578
+ GCC_except_table581
+ GCC_except_table584
+ GCC_except_table586
+ GCC_except_table590
+ GCC_except_table605
+ GCC_except_table628
+ GCC_except_table633
+ GCC_except_table651
+ GCC_except_table657
+ GCC_except_table664
+ GCC_except_table668
+ GCC_except_table699
+ GCC_except_table703
+ GCC_except_table730
+ GCC_except_table733
+ GCC_except_table769
+ GCC_except_table791
+ GCC_except_table793
+ GCC_except_table809
+ GCC_except_table816
+ GCC_except_table818
+ GCC_except_table824
+ GCC_except_table836
+ GCC_except_table842
+ GCC_except_table846
+ GCC_except_table862
+ OBJC_IVAR_$_AXVKMultiSectionFeatureWrapper._tileRect
- GCC_except_table206
- GCC_except_table210
- GCC_except_table220
- GCC_except_table253
- GCC_except_table256
- GCC_except_table259
- GCC_except_table266
- GCC_except_table269
- GCC_except_table279
- GCC_except_table283
- GCC_except_table289
- GCC_except_table306
- GCC_except_table312
- GCC_except_table315
- GCC_except_table322
- GCC_except_table326
- GCC_except_table330
- GCC_except_table338
- GCC_except_table341
- GCC_except_table348
- GCC_except_table350
- GCC_except_table357
- GCC_except_table360
- GCC_except_table363
- GCC_except_table365
- GCC_except_table370
- GCC_except_table434
- GCC_except_table441
- GCC_except_table446
- GCC_except_table451
- GCC_except_table454
- GCC_except_table458
- GCC_except_table462
- GCC_except_table474
- GCC_except_table482
- GCC_except_table485
- GCC_except_table489
- GCC_except_table496
- GCC_except_table500
- GCC_except_table502
- GCC_except_table505
- GCC_except_table510
- GCC_except_table518
- GCC_except_table521
- GCC_except_table526
- GCC_except_table531
- GCC_except_table534
- GCC_except_table541
- GCC_except_table545
- GCC_except_table547
- GCC_except_table549
- GCC_except_table553
- GCC_except_table555
- GCC_except_table571
- GCC_except_table574
- GCC_except_table577
- GCC_except_table579
- GCC_except_table582
- GCC_except_table585
- GCC_except_table589
- GCC_except_table599
- GCC_except_table623
- GCC_except_table631
- GCC_except_table639
- GCC_except_table653
- GCC_except_table659
- GCC_except_table665
- GCC_except_table698
- GCC_except_table702
- GCC_except_table727
- GCC_except_table731
- GCC_except_table766
- GCC_except_table788
- GCC_except_table792
- GCC_except_table794
- GCC_except_table810
- GCC_except_table817
- GCC_except_table823
- GCC_except_table825
- GCC_except_table838
- GCC_except_table844
- GCC_except_table861
Functions:
~ -[AXVKMultiSectionFeatureWrapper initWithFeature:] : 160 -> 184
~ -[AXVKMultiSectionFeatureWrapper setFeature:] : 140 -> 184
+ -[AXVKMultiSectionFeatureWrapper .cxx_destruct]
~ -[VKFeatureAccessibilityElement _distanceAwayStringWithClockDirection:] : 408 -> 420
~ -[VKRoadFeatureAccessibilityElement _roadLength] : 872 -> 884
```
