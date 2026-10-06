## PhotoLibraryServicesCore

> `/System/Library/PrivateFrameworks/PhotoLibraryServicesCore.framework/PhotoLibraryServicesCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc9238` | `0xca10c` | **`+0xed4`** |
| `__TEXT.__cstring` | `0x15a59` | `0x15b77` | **`+0x11e`** |
| `__TEXT.__oslogstring` | `0xb055` | `0xb142` | **`+0xed`** |
| `__AUTH_CONST.__objc_const` | `0xa818` | `0xa900` | **`+0xe8`** |
| `__TEXT.__unwind_info` | `0x3388` | `0x3430` | **`+0xa8`** |
| `__AUTH_CONST.__cfstring` | `0x11d20` | `0x11d80` | **`+0x60`** |
| `__DATA.__data` | `0x1080` | `0x10e0` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x2d0` | `0x320` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x8214` | `0x8264` | **`+0x50`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x240` | `0x288` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x56cc` | `0x570c` | **`+0x40`** |
| `__DATA_CONST.__objc_arraydata` | `0x3e8` | `0x420` | **`+0x38`** |
| `__AUTH_CONST.__objc_intobj` | `0x8d0` | `0x900` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x4bf0` | `0x4c18` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x35d0` | `0x35e8` | **`+0x18`** |
| `__DATA.__bss` | `0xdb0` | `0xdc0` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x3c18` | `0x3c20` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xa48` | `0xa50` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x400` | `0x408` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x158` | `0x160` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0xc0` | `0xc8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x65c` | `0x660` | **`+0x4`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Functions: 3934
-  Symbols:   7833
-  CStrings:  3638
+  Functions: 3945
+  Symbols:   7859
+  CStrings:  3648
Symbols:
+ +[PLFileUtilities replaceItemAtURL:withItemAtURL:backupItemName:options:resultingItemURL:error:]
+ +[PLFileUtilities statFileAtPath:error:]
+ +[PLFileUtilities statFileAtURL:error:]
+ -[PLAssetsdCloudClient setDisableSyncMode:reply:]
+ -[PLAssetsdNonBindingResourceInternalClient cancelAllPrewarming:]
+ -[PLAssetsdNonBindingResourceInternalClient cancelAllPrewarmingWithCompletionHandler:]
+ -[PLAssetsdNonBindingResourceInternalClient prewarmWithCapturePhotoSettings:completionHandler:]
+ -[PLAssetsdNonBindingResourceInternalClient prewarmWithCapturePhotoSettings:error:]
+ -[PLNonBindingAssetsdClient nonBindingResourceInternalClient]
+ GCC_except_table1449
+ GCC_except_table1464
+ GCC_except_table1473
+ GCC_except_table1590
+ GCC_except_table1613
+ GCC_except_table1618
+ GCC_except_table1655
+ GCC_except_table1671
+ GCC_except_table1697
+ GCC_except_table1714
+ GCC_except_table1717
+ GCC_except_table1720
+ GCC_except_table1723
+ GCC_except_table1726
+ GCC_except_table1731
+ GCC_except_table1733
+ GCC_except_table1736
+ GCC_except_table1739
+ GCC_except_table1742
+ GCC_except_table1745
+ GCC_except_table1762
+ GCC_except_table1765
+ GCC_except_table1768
+ GCC_except_table1771
+ GCC_except_table1774
+ GCC_except_table1777
+ GCC_except_table1781
+ GCC_except_table1785
+ GCC_except_table1788
+ GCC_except_table1791
+ GCC_except_table1794
+ GCC_except_table1797
+ GCC_except_table1800
+ GCC_except_table1802
+ GCC_except_table1805
+ GCC_except_table1808
+ GCC_except_table1821
+ GCC_except_table1829
+ GCC_except_table1837
+ GCC_except_table1934
+ GCC_except_table1953
+ GCC_except_table1957
+ GCC_except_table2115
+ GCC_except_table2165
+ GCC_except_table2170
+ GCC_except_table2171
+ GCC_except_table2173
+ GCC_except_table2176
+ GCC_except_table2315
+ GCC_except_table2403
+ GCC_except_table2442
+ GCC_except_table2476
+ GCC_except_table2481
+ GCC_except_table2484
+ GCC_except_table2487
+ GCC_except_table2490
+ GCC_except_table2493
+ GCC_except_table2496
+ GCC_except_table2499
+ GCC_except_table2502
+ GCC_except_table2505
+ GCC_except_table2508
+ GCC_except_table2511
+ GCC_except_table2525
+ GCC_except_table2532
+ GCC_except_table2577
+ GCC_except_table2582
+ GCC_except_table2585
+ GCC_except_table2588
+ GCC_except_table2592
+ GCC_except_table2596
+ GCC_except_table2600
+ GCC_except_table2605
+ GCC_except_table2609
+ GCC_except_table2613
+ GCC_except_table2617
+ GCC_except_table2621
+ GCC_except_table2625
+ GCC_except_table2629
+ GCC_except_table2633
+ GCC_except_table2637
+ GCC_except_table2641
+ GCC_except_table2645
+ GCC_except_table2649
+ GCC_except_table2653
+ GCC_except_table2657
+ GCC_except_table2661
+ GCC_except_table2664
+ GCC_except_table2668
+ GCC_except_table2676
+ GCC_except_table2680
+ GCC_except_table2684
+ GCC_except_table2688
+ GCC_except_table2691
+ GCC_except_table2697
+ GCC_except_table2700
+ GCC_except_table2704
+ GCC_except_table2708
+ GCC_except_table2712
+ GCC_except_table2716
+ GCC_except_table2720
+ GCC_except_table2728
+ GCC_except_table2732
+ GCC_except_table2741
+ GCC_except_table2744
+ GCC_except_table2746
+ GCC_except_table2747
+ GCC_except_table2749
+ GCC_except_table2752
+ GCC_except_table2756
+ GCC_except_table2758
+ GCC_except_table2761
+ GCC_except_table2764
+ GCC_except_table2767
+ GCC_except_table2770
+ GCC_except_table2773
+ GCC_except_table2776
+ GCC_except_table2779
+ GCC_except_table2782
+ GCC_except_table2785
+ GCC_except_table2788
+ GCC_except_table2791
+ GCC_except_table2794
+ GCC_except_table2797
+ GCC_except_table2799
+ GCC_except_table2855
+ GCC_except_table2921
+ GCC_except_table2924
+ GCC_except_table2981
+ GCC_except_table3035
+ GCC_except_table3046
+ GCC_except_table3048
+ GCC_except_table3052
+ GCC_except_table3054
+ GCC_except_table3074
+ GCC_except_table3080
+ GCC_except_table3228
+ GCC_except_table3230
+ GCC_except_table3232
+ GCC_except_table3236
+ GCC_except_table3241
+ GCC_except_table3244
+ GCC_except_table3247
+ GCC_except_table3250
+ GCC_except_table3253
+ GCC_except_table3338
+ GCC_except_table3462
+ GCC_except_table3530
+ GCC_except_table3541
+ GCC_except_table3594
+ GCC_except_table3597
+ GCC_except_table3603
+ GCC_except_table3606
+ GCC_except_table3609
+ GCC_except_table3612
+ GCC_except_table3624
+ GCC_except_table3628
+ GCC_except_table3632
+ GCC_except_table3636
+ GCC_except_table3640
+ GCC_except_table3661
+ GCC_except_table3664
+ GCC_except_table3673
+ GCC_except_table3686
+ GCC_except_table3712
+ GCC_except_table3714
+ GCC_except_table3723
+ GCC_except_table3729
+ GCC_except_table3740
+ GCC_except_table3754
+ GCC_except_table3767
+ GCC_except_table3770
+ GCC_except_table3776
+ GCC_except_table3779
+ GCC_except_table3783
+ GCC_except_table3787
+ GCC_except_table3801
+ GCC_except_table3804
+ GCC_except_table3848
+ GCC_except_table3865
+ GCC_except_table3867
+ GCC_except_table3869
+ GCC_except_table3871
+ GCC_except_table3873
+ GCC_except_table3874
+ GCC_except_table3876
+ GCC_except_table3885
+ GCC_except_table3898
+ GCC_except_table3903
+ GCC_except_table3910
+ GCC_except_table3915
+ _OBJC_CLASS_$_PLAssetsdNonBindingResourceInternalClient
+ _OBJC_IVAR_$_PLNonBindingAssetsdClient._nonBindingResourceInternalClient
+ _OBJC_METACLASS_$_PLAssetsdNonBindingResourceInternalClient
+ _PLCoreAnalyticsBackgroundResourceUploadEventDeveloperModeEnabledCountKey
+ _PLCoreAnalyticsBackgroundResourceUploadEventServerSupportsResumableUploadsCountKey
+ _PLCoreAnalyticsBackgroundResourceUploadTotalJobCancelledCountKey
+ _PLCoreAnalyticsBackgroundResourceUploadTotalJobCountKey
+ _PLCoreAnalyticsBackgroundResourceUploadTotalJobFailedCountKey
+ _PLFileProviderGetLog
+ _PLFileProviderGetLog.log
+ _PLFileProviderGetLog.predicate
+ _PLFileStatResultFileExists
+ _PLIsErrorOrUnderlyingErrorCancelled
+ _PLPhotoingestdBundleId
+ __OBJC_$_INSTANCE_METHODS_PLAssetsdNonBindingResourceInternalClient
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_PLAssetsdNonBindingResourceInternalServiceProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_PLAssetsdNonBindingResourceInternalServiceProtocol
+ __OBJC_$_PROTOCOL_REFS_PLAssetsdNonBindingResourceInternalServiceProtocol
+ __OBJC_CLASS_RO_$_PLAssetsdNonBindingResourceInternalClient
+ __OBJC_LABEL_PROTOCOL_$_PLAssetsdNonBindingResourceInternalServiceProtocol
+ __OBJC_METACLASS_RO_$_PLAssetsdNonBindingResourceInternalClient
+ __OBJC_PROTOCOL_$_PLAssetsdNonBindingResourceInternalServiceProtocol
+ __OBJC_PROTOCOL_REFERENCE_$_PLAssetsdNonBindingResourceInternalServiceProtocol
+ ___49-[PLAssetsdCloudClient setDisableSyncMode:reply:]_block_invoke
+ ___61-[PLNonBindingAssetsdClient nonBindingResourceInternalClient]_block_invoke
+ ___65-[PLAssetsdNonBindingResourceInternalClient cancelAllPrewarming:]_block_invoke
+ ___83-[PLAssetsdNonBindingResourceInternalClient prewarmWithCapturePhotoSettings:error:]_block_invoke
+ ___86-[PLAssetsdNonBindingResourceInternalClient cancelAllPrewarmingWithCompletionHandler:]_block_invoke
+ ___86-[PLAssetsdNonBindingResourceInternalClient cancelAllPrewarmingWithCompletionHandler:]_block_invoke_2
+ ___95-[PLAssetsdNonBindingResourceInternalClient prewarmWithCapturePhotoSettings:completionHandler:]_block_invoke
+ ___PLFileProviderGetLog_block_invoke
+ ___block_descriptor_104_e8_32bs40n18_8_8_t0w1_s8_t16w32_e41_v16?0"<PLAssetsdCloudServiceProtocol>"8l
+ ___block_descriptor_40_e8_32bs_e62_v16?0"<PLAssetsdNonBindingResourceInternalServiceProtocol>"8ls32l8
+ ___block_descriptor_48_e8_32s40bs_e62_v16?0"<PLAssetsdNonBindingResourceInternalServiceProtocol>"8ls32l8s40l8
- -[PLAssetsdResourceInternalClient cancelAllPrewarming:]
- -[PLAssetsdResourceInternalClient cancelAllPrewarmingWithCompletionHandler:]
- -[PLAssetsdResourceInternalClient cancelAllPrewarming]
- -[PLAssetsdResourceInternalClient prewarmWithCapturePhotoSettings:]
- -[PLAssetsdResourceInternalClient prewarmWithCapturePhotoSettings:completionHandler:]
- -[PLAssetsdResourceInternalClient prewarmWithCapturePhotoSettings:error:]
- GCC_except_table1447
- GCC_except_table1572
- GCC_except_table1595
- GCC_except_table1600
- GCC_except_table1637
- GCC_except_table1653
- GCC_except_table1679
- GCC_except_table1684
- GCC_except_table1687
- GCC_except_table1690
- GCC_except_table1693
- GCC_except_table1696
- GCC_except_table1699
- GCC_except_table1713
- GCC_except_table1715
- GCC_except_table1718
- GCC_except_table1721
- GCC_except_table1724
- GCC_except_table1727
- GCC_except_table1732
- GCC_except_table1735
- GCC_except_table1738
- GCC_except_table1741
- GCC_except_table1744
- GCC_except_table1763
- GCC_except_table1767
- GCC_except_table1770
- GCC_except_table1773
- GCC_except_table1776
- GCC_except_table1779
- GCC_except_table1782
- GCC_except_table1784
- GCC_except_table1787
- GCC_except_table1790
- GCC_except_table1793
- GCC_except_table1803
- GCC_except_table1819
- GCC_except_table1916
- GCC_except_table1935
- GCC_except_table1939
- GCC_except_table2097
- GCC_except_table2147
- GCC_except_table2152
- GCC_except_table2153
- GCC_except_table2155
- GCC_except_table2158
- GCC_except_table2297
- GCC_except_table2381
- GCC_except_table2420
- GCC_except_table2454
- GCC_except_table2459
- GCC_except_table2462
- GCC_except_table2465
- GCC_except_table2468
- GCC_except_table2471
- GCC_except_table2474
- GCC_except_table2477
- GCC_except_table2480
- GCC_except_table2483
- GCC_except_table2486
- GCC_except_table2489
- GCC_except_table2503
- GCC_except_table2510
- GCC_except_table2544
- GCC_except_table2548
- GCC_except_table2552
- GCC_except_table2555
- GCC_except_table2560
- GCC_except_table2563
- GCC_except_table2578
- GCC_except_table2581
- GCC_except_table2583
- GCC_except_table2587
- GCC_except_table2591
- GCC_except_table2595
- GCC_except_table2599
- GCC_except_table2607
- GCC_except_table2611
- GCC_except_table2615
- GCC_except_table2619
- GCC_except_table2623
- GCC_except_table2627
- GCC_except_table2631
- GCC_except_table2635
- GCC_except_table2639
- GCC_except_table2642
- GCC_except_table2646
- GCC_except_table2650
- GCC_except_table2654
- GCC_except_table2658
- GCC_except_table2662
- GCC_except_table2666
- GCC_except_table2669
- GCC_except_table2675
- GCC_except_table2678
- GCC_except_table2682
- GCC_except_table2686
- GCC_except_table2690
- GCC_except_table2698
- GCC_except_table2702
- GCC_except_table2706
- GCC_except_table2710
- GCC_except_table2714
- GCC_except_table2717
- GCC_except_table2719
- GCC_except_table2722
- GCC_except_table2725
- GCC_except_table2727
- GCC_except_table2730
- GCC_except_table2734
- GCC_except_table2742
- GCC_except_table2745
- GCC_except_table2748
- GCC_except_table2751
- GCC_except_table2754
- GCC_except_table2757
- GCC_except_table2760
- GCC_except_table2763
- GCC_except_table2766
- GCC_except_table2769
- GCC_except_table2772
- GCC_except_table2775
- GCC_except_table2777
- GCC_except_table2833
- GCC_except_table2897
- GCC_except_table2900
- GCC_except_table2957
- GCC_except_table3011
- GCC_except_table3022
- GCC_except_table3024
- GCC_except_table3028
- GCC_except_table3030
- GCC_except_table3050
- GCC_except_table3056
- GCC_except_table3204
- GCC_except_table3206
- GCC_except_table3208
- GCC_except_table3212
- GCC_except_table3217
- GCC_except_table3220
- GCC_except_table3223
- GCC_except_table3226
- GCC_except_table3229
- GCC_except_table3314
- GCC_except_table3437
- GCC_except_table3508
- GCC_except_table3518
- GCC_except_table3523
- GCC_except_table3527
- GCC_except_table3587
- GCC_except_table3590
- GCC_except_table3596
- GCC_except_table3599
- GCC_except_table3602
- GCC_except_table3608
- GCC_except_table3614
- GCC_except_table3622
- GCC_except_table3626
- GCC_except_table3630
- GCC_except_table3651
- GCC_except_table3654
- GCC_except_table3663
- GCC_except_table3676
- GCC_except_table3694
- GCC_except_table3702
- GCC_except_table3709
- GCC_except_table3713
- GCC_except_table3724
- GCC_except_table3727
- GCC_except_table3730
- GCC_except_table3750
- GCC_except_table3753
- GCC_except_table3766
- GCC_except_table3769
- GCC_except_table3777
- GCC_except_table3791
- GCC_except_table3794
- GCC_except_table3838
- GCC_except_table3855
- GCC_except_table3856
- GCC_except_table3857
- GCC_except_table3859
- GCC_except_table3861
- GCC_except_table3863
- GCC_except_table3864
- GCC_except_table3875
- GCC_except_table3888
- GCC_except_table3893
- GCC_except_table3900
- GCC_except_table3905
- _PLCoreAnalyticsBackgroundResourceUploadTotalJobCancelledCountCountKey
- _PLCoreAnalyticsBackgroundResourceUploadTotalJobCountCountKey
- _PLCoreAnalyticsBackgroundResourceUploadTotalJobFailedCountCountKey
- ___55-[PLAssetsdResourceInternalClient cancelAllPrewarming:]_block_invoke
- ___73-[PLAssetsdResourceInternalClient prewarmWithCapturePhotoSettings:error:]_block_invoke
- ___76-[PLAssetsdResourceInternalClient cancelAllPrewarmingWithCompletionHandler:]_block_invoke
- ___76-[PLAssetsdResourceInternalClient cancelAllPrewarmingWithCompletionHandler:]_block_invoke_2
- ___85-[PLAssetsdResourceInternalClient prewarmWithCapturePhotoSettings:completionHandler:]_block_invoke
- ___block_descriptor_40_e8_32bs_e52_v16?0"<PLAssetsdResourceInternalServiceProtocol>"8ls32l8
- ___block_descriptor_48_e8_32s40bs_e52_v16?0"<PLAssetsdResourceInternalServiceProtocol>"8ls32l8s40l8
- _kPLImageWriterJobTypeSyncedVideoSave
- _kPLImageWriterJobTypeVideoThumbnails
CStrings:
+ "-[PLAssetsdCloudClient setDisableSyncMode:reply:]_block_invoke"
+ "-[PLAssetsdNonBindingResourceInternalClient cancelAllPrewarming:]_block_invoke"
+ "-[PLAssetsdNonBindingResourceInternalClient cancelAllPrewarmingWithCompletionHandler:]_block_invoke"
+ "-[PLAssetsdNonBindingResourceInternalClient cancelAllPrewarmingWithCompletionHandler:]_block_invoke_2"
+ "-[PLAssetsdNonBindingResourceInternalClient prewarmWithCapturePhotoSettings:completionHandler:]_block_invoke"
+ "-[PLAssetsdNonBindingResourceInternalClient prewarmWithCapturePhotoSettings:error:]_block_invoke"
+ "Failed to remove replacement directory after cross-device replace %@: %@"
+ "Failed to remove source file after cross-device replace %@: %@"
+ "FileProvider"
+ "PLPhotosErrorBeforeFirstUnlock"
+ "PLXPC Client: setDisableSyncMode:reply:"
+ "com.apple.photoingestd"
+ "developerModeEnabledCount"
+ "findPhotoLibraryIdentifiersMatchingSearchCriteria failed: %@"
+ "kPLQueryKey_rating"
+ "serverSupportsResumableUploadsCount"
+ "v16@?0@\"<PLAssetsdNonBindingResourceInternalServiceProtocol>\"8"
- "-[PLAssetsdResourceInternalClient cancelAllPrewarming:]_block_invoke"
- "-[PLAssetsdResourceInternalClient cancelAllPrewarmingWithCompletionHandler:]_block_invoke"
- "-[PLAssetsdResourceInternalClient cancelAllPrewarmingWithCompletionHandler:]_block_invoke_2"
- "-[PLAssetsdResourceInternalClient prewarmWithCapturePhotoSettings:completionHandler:]_block_invoke"
- "-[PLAssetsdResourceInternalClient prewarmWithCapturePhotoSettings:error:]_block_invoke"
- "SyncedVideoSaveJob"
- "VideoThumbnailsJob"
```
