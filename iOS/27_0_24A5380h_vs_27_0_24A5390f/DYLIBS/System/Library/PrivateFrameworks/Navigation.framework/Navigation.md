## Navigation

> `/System/Library/PrivateFrameworks/Navigation.framework/Navigation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x5830` | `0x3280` | **`-0x25b0`** |
| `__DATA_DIRTY.__objc_data` | `0x1b10` | `0x40c0` | **`+0x25b0`** |
| `__DATA_DIRTY.__data` | `0x2c8` | `0xb88` | **`+0x8c0`** |
| `__AUTH.__data` | `0x4ef8` | `0x46e0` | **`-0x818`** |
| `__DATA.__bss` | `0x12710` | `0x127e0` | **`+0xd0`** |
| `__DATA_DIRTY.__bss` | `0x240` | `0x178` | **`-0xc8`** |
| `__DATA.__common` | `0x318` | `0x2b0` | **`-0x68`** |
| `__DATA_DIRTY.__common` | `—` | `0x68` | **`+0x68`** |
| `__DATA.__data` | `0x7ae8` | `0x7aa8` | **`-0x40`** |
| `__TEXT.__text` | `0x21ec5c` | `0x21ec9c` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0xcde0` | `0xce00` | **`+0x20`** |
| `__TEXT.__cstring` | `0x20639` | `0x2064f` | **`+0x16`** |
| `__DATA_CONST.__const` | `0x4010` | `0x4018` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x8dc8` | `0x8dd0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x12284` | `0x1228c` | **`+0x8`** |

### Other Changes

```diff

-2435.30.6.12.2
+2435.30.6.12.5

-  Functions: 11095
-  Symbols:   12950
-  CStrings:  4003
+  Functions: 11096
+  Symbols:   12951
+  CStrings:  4004
Symbols:
+ -[MNGuidanceManager _announce:parentEvent:sourceID:sourceGuidanceObject:options:completionHandler:]
+ -[MNGuidanceManager _handleCompositeAnnouncementComponent:parentEvent:options:completionHandler:]
+ -[MNGuidanceManager _handleCompositeAnnouncementEvent:options:]
+ -[MNGuidanceManager _notifySpeechEvent:waypointCategory:startingVariantIndex:options:]
+ GCC_except_table2374
+ GCC_except_table2396
+ GCC_except_table2461
+ GCC_except_table2465
+ GCC_except_table2493
+ GCC_except_table2499
+ GCC_except_table2531
+ GCC_except_table2535
+ GCC_except_table2538
+ GCC_except_table2549
+ GCC_except_table2553
+ GCC_except_table2556
+ GCC_except_table2558
+ GCC_except_table2580
+ GCC_except_table2582
+ GCC_except_table2587
+ GCC_except_table2602
+ GCC_except_table2613
+ GCC_except_table2621
+ GCC_except_table2625
+ GCC_except_table2635
+ GCC_except_table2687
+ GCC_except_table2807
+ GCC_except_table2835
+ GCC_except_table2837
+ GCC_except_table2840
+ GCC_except_table2849
+ GCC_except_table2877
+ GCC_except_table2887
+ GCC_except_table2889
+ GCC_except_table2906
+ GCC_except_table2908
+ GCC_except_table2910
+ GCC_except_table2913
+ GCC_except_table2916
+ GCC_except_table2922
+ GCC_except_table2924
+ GCC_except_table2927
+ GCC_except_table2935
+ GCC_except_table2987
+ GCC_except_table3039
+ GCC_except_table3058
+ GCC_except_table3065
+ GCC_except_table3076
+ GCC_except_table3085
+ GCC_except_table3091
+ GCC_except_table3095
+ GCC_except_table3097
+ GCC_except_table3102
+ GCC_except_table3105
+ GCC_except_table3116
+ GCC_except_table3129
+ GCC_except_table3131
+ GCC_except_table3140
+ GCC_except_table3145
+ GCC_except_table3166
+ GCC_except_table3169
+ GCC_except_table3172
+ GCC_except_table3182
+ GCC_except_table3245
+ GCC_except_table3293
+ GCC_except_table3385
+ GCC_except_table3458
+ GCC_except_table3535
+ GCC_except_table3634
+ GCC_except_table3651
+ GCC_except_table3657
+ GCC_except_table3659
+ GCC_except_table3661
+ GCC_except_table3663
+ GCC_except_table3678
+ GCC_except_table3693
+ GCC_except_table3766
+ GCC_except_table3802
+ GCC_except_table3811
+ GCC_except_table3819
+ GCC_except_table3877
+ GCC_except_table3939
+ GCC_except_table3943
+ GCC_except_table4215
+ GCC_except_table4222
+ GCC_except_table4225
+ GCC_except_table4229
+ GCC_except_table4271
+ GCC_except_table4280
+ GCC_except_table4283
+ GCC_except_table4285
+ GCC_except_table4406
+ GCC_except_table4536
+ GCC_except_table4538
+ GCC_except_table4540
+ GCC_except_table4732
+ GCC_except_table4818
+ GCC_except_table4820
+ GCC_except_table4822
+ GCC_except_table4852
+ GCC_except_table4856
+ GCC_except_table5099
+ GCC_except_table5177
+ GCC_except_table5364
+ GCC_except_table5368
+ GCC_except_table5399
+ GCC_except_table5413
+ GCC_except_table5452
+ GCC_except_table5695
+ GCC_except_table5697
+ GCC_except_table5700
+ GCC_except_table5706
+ GCC_except_table5749
+ GCC_except_table5761
+ GCC_except_table5764
+ ___63-[MNGuidanceManager _handleCompositeAnnouncementEvent:options:]_block_invoke
+ ___86-[MNGuidanceManager _notifySpeechEvent:waypointCategory:startingVariantIndex:options:]_block_invoke
+ ___99-[MNGuidanceManager _announce:parentEvent:sourceID:sourceGuidanceObject:options:completionHandler:]_block_invoke
- -[MNGuidanceManager _announce:parentEvent:sourceID:sourceGuidanceObject:completionHandler:]
- -[MNGuidanceManager _handleCompositeAnnouncementComponent:parentEvent:completionHandler:]
- -[MNGuidanceManager _handleCompositeAnnouncementEvent:]
- GCC_except_table2373
- GCC_except_table2395
- GCC_except_table2460
- GCC_except_table2464
- GCC_except_table2492
- GCC_except_table2498
- GCC_except_table2523
- GCC_except_table2532
- GCC_except_table2536
- GCC_except_table2544
- GCC_except_table2552
- GCC_except_table2554
- GCC_except_table2557
- GCC_except_table2559
- GCC_except_table2581
- GCC_except_table2586
- GCC_except_table2589
- GCC_except_table2603
- GCC_except_table2615
- GCC_except_table2622
- GCC_except_table2634
- GCC_except_table2686
- GCC_except_table2806
- GCC_except_table2826
- GCC_except_table2836
- GCC_except_table2839
- GCC_except_table2843
- GCC_except_table2875
- GCC_except_table2885
- GCC_except_table2888
- GCC_except_table2905
- GCC_except_table2907
- GCC_except_table2909
- GCC_except_table2911
- GCC_except_table2914
- GCC_except_table2917
- GCC_except_table2923
- GCC_except_table2926
- GCC_except_table2934
- GCC_except_table2985
- GCC_except_table3038
- GCC_except_table3057
- GCC_except_table3064
- GCC_except_table3075
- GCC_except_table3084
- GCC_except_table3089
- GCC_except_table3093
- GCC_except_table3096
- GCC_except_table3100
- GCC_except_table3104
- GCC_except_table3112
- GCC_except_table3128
- GCC_except_table3130
- GCC_except_table3139
- GCC_except_table3142
- GCC_except_table3162
- GCC_except_table3167
- GCC_except_table3171
- GCC_except_table3173
- GCC_except_table3243
- GCC_except_table3292
- GCC_except_table3384
- GCC_except_table3457
- GCC_except_table3534
- GCC_except_table3633
- GCC_except_table3650
- GCC_except_table3656
- GCC_except_table3658
- GCC_except_table3660
- GCC_except_table3662
- GCC_except_table3677
- GCC_except_table3692
- GCC_except_table3765
- GCC_except_table3801
- GCC_except_table3810
- GCC_except_table3818
- GCC_except_table3876
- GCC_except_table3938
- GCC_except_table3942
- GCC_except_table4214
- GCC_except_table4221
- GCC_except_table4224
- GCC_except_table4228
- GCC_except_table4269
- GCC_except_table4278
- GCC_except_table4282
- GCC_except_table4284
- GCC_except_table4404
- GCC_except_table4535
- GCC_except_table4537
- GCC_except_table4539
- GCC_except_table4731
- GCC_except_table4817
- GCC_except_table4819
- GCC_except_table4821
- GCC_except_table4851
- GCC_except_table4855
- GCC_except_table5098
- GCC_except_table5176
- GCC_except_table5363
- GCC_except_table5367
- GCC_except_table5398
- GCC_except_table5412
- GCC_except_table5451
- GCC_except_table5694
- GCC_except_table5696
- GCC_except_table5699
- GCC_except_table5704
- GCC_except_table5748
- GCC_except_table5760
- GCC_except_table5763
- ___55-[MNGuidanceManager _handleCompositeAnnouncementEvent:]_block_invoke
- ___78-[MNGuidanceManager _notifySpeechEvent:waypointCategory:startingVariantIndex:]_block_invoke
- ___91-[MNGuidanceManager _announce:parentEvent:sourceID:sourceGuidanceObject:completionHandler:]_block_invoke
CStrings:
+ "-[MNGuidanceManager _handleCompositeAnnouncementComponent:parentEvent:options:completionHandler:]"
+ "BASEMAP_PATCH"
- "-[MNGuidanceManager _handleCompositeAnnouncementComponent:parentEvent:completionHandler:]"
```
