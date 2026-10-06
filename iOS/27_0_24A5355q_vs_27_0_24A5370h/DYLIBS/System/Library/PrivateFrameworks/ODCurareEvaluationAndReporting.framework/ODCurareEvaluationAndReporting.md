## ODCurareEvaluationAndReporting

> `/System/Library/PrivateFrameworks/ODCurareEvaluationAndReporting.framework/ODCurareEvaluationAndReporting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5cf78` | `0x5cd44` | **`-0x234`** |

### Other Changes

```text
Functions:
~ -[ODCurareCandidateModel getDatesOfEventsForStream] : 1056 -> 1052
~ -[ODCurareCoreDuetStorage queryDataWithPredicate:] : 532 -> 528
~ -[ODCurareCoreDuetStorage deleteData:] : 668 -> 664
~ -[ODCurareCoreDuetStorage deleteMultipleData:] : 696 -> 692
~ -[ODCurareCoreDuetStorage deleteDataWithPredicate:] : 556 -> 552
~ -[ODCurareCoreDuetStorage deleteMultipleDataWithPredicate:] : 612 -> 608
~ -[ODCurareCoreDuetStorage deleteAllData] : 560 -> 556
~ -[ODCurareReportFillerReport dictionaryRepresentation] : 1264 -> 1248
~ -[ODCurareReportFillerReport writeTo:] : 840 -> 824
~ -[ODCurareReportFillerReport copyWithZone:] : 928 -> 912
~ -[ODCurareReportFillerReport mergeFrom:] : 812 -> 796
~ -[ODCurareReportFillerDataSet dictionaryRepresentation] : 540 -> 536
~ -[ODCurareReportFillerDataSet writeTo:] : 380 -> 376
~ -[ODCurareReportFillerDataSet copyWithZone:] : 444 -> 440
~ -[ODCurareReportFillerDataSet mergeFrom:] : 388 -> 384
~ -[ODCurareReportFillerModelEvaluationSummary dictionaryRepresentation] : 540 -> 536
~ -[ODCurareReportFillerModelEvaluationSummary writeTo:] : 384 -> 380
~ -[ODCurareReportFillerModelEvaluationSummary copyWithZone:] : 444 -> 440
~ -[ODCurareReportFillerModelEvaluationSummary mergeFrom:] : 388 -> 384
~ -[ODCurareReportFillerModelHyperparameters writeTo:] : 228 -> 220
~ sub_28c382358 -> sub_28d9182d4 : 7772 -> 7748
~ sub_28c3842ac -> sub_28d91a210 : 10004 -> 10100
~ sub_28c3883f4 -> sub_28d91e3b8 : 4180 -> 4172
~ sub_28c3899dc -> sub_28d91f998 : 476 -> 480
~ sub_28c38a0dc -> sub_28d92009c : 492 -> 496
~ sub_28c38a418 -> sub_28d9203dc : 280 -> 276
~ sub_28c38b348 -> sub_28d921308 : 640 -> 624
~ sub_28c38b5c8 -> sub_28d921578 : 676 -> 696
~ sub_28c38b86c -> sub_28d921830 : 1332 -> 1336
~ sub_28c38fa7c -> sub_28d925a44 : 7396 -> 7352
~ sub_28c3918f8 -> sub_28d927894 : 388 -> 400
~ sub_28c392618 -> sub_28d9285c0 : 4072 -> 3972
~ sub_28c393600 -> sub_28d929544 : 11788 -> 11756
~ sub_28c398134 -> sub_28d92e058 : 740 -> 748
~ sub_28c398418 -> sub_28d92e344 : 8496 -> 8556
~ sub_28c39a6a8 -> sub_28d930610 : 2836 -> 2824
~ sub_28c39d1f0 -> sub_28d93314c : 692 -> 684
~ sub_28c39efe8 -> sub_28d934f3c : 388 -> 384
~ sub_28c3a05b0 -> sub_28d936500 : 2996 -> 2964
~ sub_28c3a1164 -> sub_28d937094 : 640 -> 624
~ sub_28c3a1854 -> sub_28d937774 : 676 -> 696
~ sub_28c3a1af8 -> sub_28d937a2c : 628 -> 648
~ sub_28c3a1d6c -> sub_28d937cb4 : 1332 -> 1336
~ sub_28c3a22a0 -> sub_28d9381ec : 2492 -> 2512
~ sub_28c3a2d70 -> sub_28d938cd0 : 256 -> 264
~ sub_28c3a3214 -> sub_28d93917c : 1084 -> 1068
~ sub_28c3a3698 -> sub_28d9395f0 : 1948 -> 1984
~ sub_28c3a3f84 -> sub_28d939f00 : 256 -> 276
~ sub_28c3a5a60 -> sub_28d93b9f0 : 680 -> 660
~ sub_28c3a694c -> sub_28d93c8c8 : 376 -> 372
~ sub_28c3a6de4 -> sub_28d93cd5c : 412 -> 388
~ sub_28c3a6f94 -> sub_28d93cef4 : 352 -> 344
~ sub_28c3a7108 -> sub_28d93d060 : 348 -> 340
~ sub_28c3a752c -> sub_28d93d47c : 1156 -> 1120
~ sub_28c3a79b0 -> sub_28d93d8dc : 232 -> 236
~ sub_28c3a7a98 -> sub_28d93d9c8 : 628 -> 648
~ sub_28c3a7d0c -> sub_28d93dc50 : 728 -> 720
~ sub_28c3a86f4 -> sub_28d93e630 : 1824 -> 1828
~ sub_28c3a9c40 -> sub_28d93fb80 : 4096 -> 3984
~ sub_28c3aac40 -> sub_28d940b10 : 1532 -> 1524
~ sub_28c3ab23c -> sub_28d941104 : 688 -> 708
~ sub_28c3ab4ec -> sub_28d9413c8 : 3136 -> 3188
~ sub_28c3ac1fc -> sub_28d94210c : 1920 -> 1912
~ sub_28c3accbc -> sub_28d942bc4 : 2996 -> 2964
~ sub_28c3adce0 -> sub_28d943bc8 : 628 -> 648
~ sub_28c3adf54 -> sub_28d943e50 : 2492 -> 2512
~ sub_28c3aef58 -> sub_28d944e68 : 1056 -> 1052
~ sub_28c3b0038 -> sub_28d945f44 : 2732 -> 2692
~ sub_28c3b0c08 -> sub_28d946aec : 1548 -> 1540
~ sub_28c3b1214 -> sub_28d9470f0 : 2684 -> 2692
~ sub_28c3b2f4c -> sub_28d948e30 : 344 -> 340
~ sub_28c3b3128 -> sub_28d949008 : 300 -> 304
~ sub_28c3b3394 -> sub_28d949278 : 1196 -> 1200
~ sub_28c3b3ab4 -> sub_28d94999c : 1440 -> 1420
~ sub_28c3b4840 -> sub_28d94a714 : 472 -> 476
~ sub_28c3b4a60 -> sub_28d94a938 : 488 -> 492
~ sub_28c3b4e6c -> sub_28d94ad48 : 2568 -> 2556
~ sub_28c3b5874 -> sub_28d94b744 : 1928 -> 1920
~ sub_28c3b5ffc -> sub_28d94bec4 : 7556 -> 7472
~ sub_28c3ba1a0 -> sub_28d950014 : 588 -> 596
~ sub_28c3bcb7c -> sub_28d9529f8 : 640 -> 624
~ sub_28c3bcdfc -> sub_28d952c68 : 676 -> 696
~ sub_28c3bd0a0 -> sub_28d952f20 : 1332 -> 1336
~ sub_28c3bf204 -> sub_28d955088 : 7176 -> 7136
~ sub_28c3c95d4 -> sub_28d95f430 : 1872 -> 1896
~ sub_28c3c9d24 -> sub_28d95fb98 : 592 -> 588
~ sub_28c3c9f74 -> sub_28d95fde4 : 688 -> 708
~ sub_28c3ca224 -> sub_28d9600a8 : 1344 -> 1280
~ sub_28c3cc260 -> sub_28d9620a4 : 248 -> 260
~ sub_28c3cc544 -> sub_28d962394 : 2476 -> 2380
~ sub_28c3ccef0 -> sub_28d962ce0 : 700 -> 668
~ sub_28c3cd1ac -> sub_28d962f7c : 684 -> 704
~ sub_28c3cd458 -> sub_28d96323c : 1704 -> 1676
~ sub_28c3cdf18 -> sub_28d963ce0 : 420 -> 416
~ sub_28c3d15c0 -> sub_28d967384 : 640 -> 624
~ sub_28c3d1840 -> sub_28d9675f4 : 676 -> 696
~ sub_28c3d1ae4 -> sub_28d9678ac : 1332 -> 1336
```
