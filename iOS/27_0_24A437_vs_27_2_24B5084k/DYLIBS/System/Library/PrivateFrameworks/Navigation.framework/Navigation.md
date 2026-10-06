## Navigation

> `/System/Library/PrivateFrameworks/Navigation.framework/Navigation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x220340` | `0x221e44` | **`+0x1b04`** |
| `__TEXT.__cstring` | `0x206d7` | `0x2086f` | **`+0x198`** |
| `__AUTH_CONST.__cfstring` | `0xce40` | `0xcf60` | **`+0x120`** |
| `__DATA.__data` | `0x7b48` | `0x7c48` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0xb738` | `0xb7c0` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x8e18` | `0x8e68` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x221a8` | `0x221f0` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x7848` | `0x7888` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x12394` | `0x123cc` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x4060` | `0x4090` | **`+0x30`** |
| `__TEXT.__const` | `0xdc9c` | `0xdcac` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1cc8` | `0x1cd0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x13f8` | `0x1400` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x4e44` | `0x4e4c` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x38a8` | `0x38b0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1578` | `0x157c` | **`+0x4`** |

### Other Changes

```diff

-2435.30.6.12.9
+2435.31.6.17.8

-  Functions: 11125
-  Symbols:   12981
-  CStrings:  4011
+  Functions: 11146
+  Symbols:   12995
+  CStrings:  4024
Symbols:
+ -[MNNavigationServiceLocalProxy resetWithReason:]
+ -[MNNavigationSessionManager deallocEndNavigationReason]
+ -[MNNavigationSessionManager setDeallocEndNavigationReason:]
+ -[MNNavigationStateGuidance deallocEndNavigationReason]
+ -[MNNavigationStateGuidance setDeallocEndNavigationReason:]
+ -[MNNavigationStateManager resetWithReason:]
+ GCC_except_table1109
+ GCC_except_table1135
+ GCC_except_table1141
+ GCC_except_table1667
+ GCC_except_table1695
+ GCC_except_table1702
+ GCC_except_table1707
+ GCC_except_table1710
+ GCC_except_table1725
+ GCC_except_table1761
+ GCC_except_table1842
+ GCC_except_table1851
+ GCC_except_table1912
+ GCC_except_table1916
+ GCC_except_table1927
+ GCC_except_table2192
+ GCC_except_table2271
+ GCC_except_table2287
+ GCC_except_table2305
+ GCC_except_table2315
+ GCC_except_table2383
+ GCC_except_table2405
+ GCC_except_table2470
+ GCC_except_table2474
+ GCC_except_table2502
+ GCC_except_table2508
+ GCC_except_table2540
+ GCC_except_table2544
+ GCC_except_table2547
+ GCC_except_table2558
+ GCC_except_table2562
+ GCC_except_table2565
+ GCC_except_table2567
+ GCC_except_table2589
+ GCC_except_table2591
+ GCC_except_table2596
+ GCC_except_table2611
+ GCC_except_table2622
+ GCC_except_table2630
+ GCC_except_table2634
+ GCC_except_table2644
+ GCC_except_table2696
+ GCC_except_table2816
+ GCC_except_table2844
+ GCC_except_table2846
+ GCC_except_table2849
+ GCC_except_table2858
+ GCC_except_table2888
+ GCC_except_table2898
+ GCC_except_table2900
+ GCC_except_table2917
+ GCC_except_table2919
+ GCC_except_table2921
+ GCC_except_table2924
+ GCC_except_table2927
+ GCC_except_table2933
+ GCC_except_table2935
+ GCC_except_table2938
+ GCC_except_table2946
+ GCC_except_table2998
+ GCC_except_table3050
+ GCC_except_table3069
+ GCC_except_table3076
+ GCC_except_table3087
+ GCC_except_table3096
+ GCC_except_table3102
+ GCC_except_table3106
+ GCC_except_table3108
+ GCC_except_table3113
+ GCC_except_table3116
+ GCC_except_table3127
+ GCC_except_table3140
+ GCC_except_table3142
+ GCC_except_table3151
+ GCC_except_table3156
+ GCC_except_table3177
+ GCC_except_table3180
+ GCC_except_table3183
+ GCC_except_table3193
+ GCC_except_table3256
+ GCC_except_table3304
+ GCC_except_table3396
+ GCC_except_table3471
+ GCC_except_table3548
+ GCC_except_table3649
+ GCC_except_table3666
+ GCC_except_table3672
+ GCC_except_table3674
+ GCC_except_table3676
+ GCC_except_table3678
+ GCC_except_table3693
+ GCC_except_table3708
+ GCC_except_table3781
+ GCC_except_table3817
+ GCC_except_table3827
+ GCC_except_table3835
+ GCC_except_table3893
+ GCC_except_table3955
+ GCC_except_table3959
+ GCC_except_table4236
+ GCC_except_table4246
+ GCC_except_table4250
+ GCC_except_table4291
+ GCC_except_table4292
+ GCC_except_table4300
+ GCC_except_table4304
+ GCC_except_table4306
+ GCC_except_table4426
+ GCC_except_table4427
+ GCC_except_table4557
+ GCC_except_table4559
+ GCC_except_table4561
+ GCC_except_table4754
+ GCC_except_table4840
+ GCC_except_table4842
+ GCC_except_table4844
+ GCC_except_table4874
+ GCC_except_table4878
+ GCC_except_table5121
+ GCC_except_table5199
+ GCC_except_table5387
+ GCC_except_table5391
+ GCC_except_table5422
+ GCC_except_table5436
+ GCC_except_table5475
+ GCC_except_table5722
+ GCC_except_table5730
+ GCC_except_table5731
+ GCC_except_table5774
+ GCC_except_table5786
+ GCC_except_table5789
+ _NavigationConfig_Dodgeball_EnableFasterSettings
+ _NavigationConfig_Dodgeball_MinimumTimeSavings
+ _NavigationConfig_Dodgeball_MinimumTimeSavingsOptions
+ _NavigationConfig_Dodgeball_ShouldDefaultAccept
+ _OBJC_CLASS_$_GEODodgeballOptions
+ _OBJC_IVAR_$_MNNavigationSessionManager._deallocEndNavigationReason
+ __CFPreferencesGetAppBooleanValueWithContainer
+ __OBJC_$_PROP_LIST_MNNavigationStateGuidance
+ ___49-[MNNavigationServiceLocalProxy resetWithReason:]_block_invoke
+ _symbolic SaySiG
- -[MNNavigationStateManager reset]
- GCC_except_table1108
- GCC_except_table1134
- GCC_except_table1139
- GCC_except_table1666
- GCC_except_table1694
- GCC_except_table1701
- GCC_except_table1706
- GCC_except_table1709
- GCC_except_table1724
- GCC_except_table1760
- GCC_except_table1841
- GCC_except_table1850
- GCC_except_table1911
- GCC_except_table1915
- GCC_except_table1926
- GCC_except_table2191
- GCC_except_table2270
- GCC_except_table2286
- GCC_except_table2304
- GCC_except_table2314
- GCC_except_table2382
- GCC_except_table2404
- GCC_except_table2469
- GCC_except_table2473
- GCC_except_table2501
- GCC_except_table2507
- GCC_except_table2532
- GCC_except_table2541
- GCC_except_table2545
- GCC_except_table2553
- GCC_except_table2561
- GCC_except_table2563
- GCC_except_table2566
- GCC_except_table2568
- GCC_except_table2590
- GCC_except_table2595
- GCC_except_table2598
- GCC_except_table2612
- GCC_except_table2624
- GCC_except_table2631
- GCC_except_table2643
- GCC_except_table2695
- GCC_except_table2815
- GCC_except_table2835
- GCC_except_table2845
- GCC_except_table2848
- GCC_except_table2852
- GCC_except_table2886
- GCC_except_table2896
- GCC_except_table2899
- GCC_except_table2916
- GCC_except_table2918
- GCC_except_table2920
- GCC_except_table2922
- GCC_except_table2925
- GCC_except_table2928
- GCC_except_table2934
- GCC_except_table2937
- GCC_except_table2945
- GCC_except_table2996
- GCC_except_table3049
- GCC_except_table3068
- GCC_except_table3075
- GCC_except_table3086
- GCC_except_table3095
- GCC_except_table3100
- GCC_except_table3104
- GCC_except_table3107
- GCC_except_table3111
- GCC_except_table3115
- GCC_except_table3123
- GCC_except_table3139
- GCC_except_table3141
- GCC_except_table3150
- GCC_except_table3153
- GCC_except_table3173
- GCC_except_table3178
- GCC_except_table3182
- GCC_except_table3184
- GCC_except_table3254
- GCC_except_table3303
- GCC_except_table3395
- GCC_except_table3468
- GCC_except_table3545
- GCC_except_table3646
- GCC_except_table3663
- GCC_except_table3669
- GCC_except_table3671
- GCC_except_table3673
- GCC_except_table3675
- GCC_except_table3690
- GCC_except_table3705
- GCC_except_table3778
- GCC_except_table3814
- GCC_except_table3824
- GCC_except_table3832
- GCC_except_table3890
- GCC_except_table3952
- GCC_except_table3956
- GCC_except_table4233
- GCC_except_table4240
- GCC_except_table4247
- GCC_except_table4288
- GCC_except_table4289
- GCC_except_table4297
- GCC_except_table4298
- GCC_except_table4303
- GCC_except_table4423
- GCC_except_table4424
- GCC_except_table4554
- GCC_except_table4556
- GCC_except_table4558
- GCC_except_table4751
- GCC_except_table4837
- GCC_except_table4839
- GCC_except_table4841
- GCC_except_table4871
- GCC_except_table4875
- GCC_except_table5118
- GCC_except_table5196
- GCC_except_table5384
- GCC_except_table5388
- GCC_except_table5419
- GCC_except_table5433
- GCC_except_table5472
- GCC_except_table5715
- GCC_except_table5717
- GCC_except_table5726
- GCC_except_table5769
- GCC_except_table5781
- GCC_except_table5784
- ___38-[MNNavigationServiceLocalProxy reset]_block_invoke
CStrings:
+ "AppTermination_MapsDisconnected"
+ "Dodgeball_EnableFasterSettings"
+ "Dodgeball_MinimumTimeSavings"
+ "Dodgeball_MinimumTimeSavingsOptions"
+ "Dodgeball_ShouldDefaultAccept"
+ "MapsDefaultAvoidBusyRoadsKey"
+ "MapsDefaultAvoidHighwaysKey"
+ "MapsDefaultAvoidHillsKey"
+ "MapsDefaultAvoidTollsKey"
+ "MapsDefaultWalkingAvoidBusyRoadsKey"
+ "MapsDefaultWalkingAvoidHillsKey"
+ "MapsDefaultWalkingAvoidStairsKey"
+ "group.com.apple.Maps"
```
