## SafariServices

> `/System/Library/Frameworks/SafariServices.framework/SafariServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1856c8` | `0x1857f0` | **`+0x128`** |
| `__AUTH.__data` | `0x2e0` | `0x2b0` | **`-0x30`** |
| `__DATA_DIRTY.__data` | `—` | `0x30` | **`+0x30`** |
| `__AUTH.__objc_data` | `0x5e98` | `0x5ec0` | **`+0x28`** |
| `__DATA_DIRTY.__objc_data` | `0xb40` | `0xb18` | **`-0x28`** |
| `__TEXT.__objc_methlist` | `0x1bdbc` | `0x1bde4` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x2c700` | `0x2c718` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x12390` | `0x123a8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x9268` | `0x9280` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xfe5c` | `0xfe60` | **`+0x4`** |

### Other Changes

```diff

-625.2.4.1.0
+625.2.5.10.1

-  Functions: 9308
-  Symbols:   17546
+  Functions: 9311
+  Symbols:   17547
Symbols:
+ -[_SFBrowserContentViewController bannerLayoutMargins]
+ -[_SFNavigationBar _tabBarHeightContribution]
+ -[_SFNavigationBar defaultHeightExcludingTabBar]
+ GCC_except_table169
+ GCC_except_table220
+ GCC_except_table239
+ GCC_except_table264
+ GCC_except_table267
+ GCC_except_table269
+ GCC_except_table271
+ GCC_except_table275
+ GCC_except_table279
+ GCC_except_table285
+ GCC_except_table294
+ GCC_except_table299
+ GCC_except_table310
+ GCC_except_table314
+ GCC_except_table322
+ GCC_except_table326
+ GCC_except_table331
+ GCC_except_table333
+ GCC_except_table338
+ GCC_except_table340
+ GCC_except_table344
+ GCC_except_table348
+ GCC_except_table353
+ GCC_except_table359
+ GCC_except_table371
+ GCC_except_table375
+ GCC_except_table377
+ GCC_except_table381
+ GCC_except_table384
+ GCC_except_table393
+ GCC_except_table399
+ GCC_except_table402
+ GCC_except_table404
+ GCC_except_table416
+ GCC_except_table419
+ GCC_except_table426
+ GCC_except_table443
+ GCC_except_table449
+ GCC_except_table451
+ GCC_except_table453
+ GCC_except_table456
+ GCC_except_table461
+ GCC_except_table464
+ GCC_except_table466
+ GCC_except_table474
+ GCC_except_table484
+ GCC_except_table491
+ GCC_except_table493
+ GCC_except_table507
+ GCC_except_table519
+ GCC_except_table525
+ GCC_except_table529
+ GCC_except_table537
+ GCC_except_table544
+ GCC_except_table547
+ GCC_except_table550
+ GCC_except_table554
+ GCC_except_table559
+ GCC_except_table569
+ GCC_except_table571
+ GCC_except_table573
+ GCC_except_table576
+ GCC_except_table578
+ GCC_except_table580
+ GCC_except_table584
+ GCC_except_table588
+ GCC_except_table591
+ GCC_except_table597
+ GCC_except_table599
+ GCC_except_table602
+ GCC_except_table607
+ GCC_except_table614
+ GCC_except_table620
+ GCC_except_table623
+ GCC_except_table625
+ GCC_except_table630
+ GCC_except_table632
+ GCC_except_table634
+ GCC_except_table639
+ GCC_except_table642
+ GCC_except_table646
+ GCC_except_table648
+ GCC_except_table651
+ GCC_except_table658
+ GCC_except_table665
+ GCC_except_table667
+ GCC_except_table674
- GCC_except_table133
- GCC_except_table179
- GCC_except_table233
- GCC_except_table235
- GCC_except_table243
- GCC_except_table266
- GCC_except_table270
- GCC_except_table272
- GCC_except_table276
- GCC_except_table286
- GCC_except_table298
- GCC_except_table300
- GCC_except_table302
- GCC_except_table307
- GCC_except_table311
- GCC_except_table316
- GCC_except_table318
- GCC_except_table323
- GCC_except_table330
- GCC_except_table332
- GCC_except_table336
- GCC_except_table339
- GCC_except_table343
- GCC_except_table347
- GCC_except_table349
- GCC_except_table354
- GCC_except_table368
- GCC_except_table374
- GCC_except_table376
- GCC_except_table378
- GCC_except_table382
- GCC_except_table385
- GCC_except_table395
- GCC_except_table400
- GCC_except_table403
- GCC_except_table415
- GCC_except_table418
- GCC_except_table421
- GCC_except_table427
- GCC_except_table448
- GCC_except_table450
- GCC_except_table452
- GCC_except_table454
- GCC_except_table460
- GCC_except_table462
- GCC_except_table465
- GCC_except_table473
- GCC_except_table483
- GCC_except_table490
- GCC_except_table492
- GCC_except_table506
- GCC_except_table517
- GCC_except_table523
- GCC_except_table527
- GCC_except_table532
- GCC_except_table542
- GCC_except_table545
- GCC_except_table549
- GCC_except_table551
- GCC_except_table557
- GCC_except_table568
- GCC_except_table570
- GCC_except_table572
- GCC_except_table575
- GCC_except_table577
- GCC_except_table579
- GCC_except_table582
- GCC_except_table585
- GCC_except_table589
- GCC_except_table596
- GCC_except_table598
- GCC_except_table601
- GCC_except_table603
- GCC_except_table613
- GCC_except_table619
- GCC_except_table622
- GCC_except_table624
- GCC_except_table628
- GCC_except_table631
- GCC_except_table633
- GCC_except_table636
- GCC_except_table640
- GCC_except_table643
- GCC_except_table647
- GCC_except_table649
- GCC_except_table655
- GCC_except_table659
- GCC_except_table666
- GCC_except_table668
```
