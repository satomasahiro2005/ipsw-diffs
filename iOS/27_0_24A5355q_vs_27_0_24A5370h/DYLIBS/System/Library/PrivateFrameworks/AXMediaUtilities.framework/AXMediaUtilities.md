## AXMediaUtilities

> `/System/Library/PrivateFrameworks/AXMediaUtilities.framework/AXMediaUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd4314` | `0xd4428` | **`+0x114`** |
| `__TEXT.__oslogstring` | `0x5395` | `0x5420` | **`+0x8b`** |
| `__TEXT.__gcc_except_tab` | `0x5860` | `0x58b8` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x61d0` | `0x6220` | **`+0x50`** |
| `__TEXT.__cstring` | `0xa666` | `0xa686` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x14368` | `0x14378` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xe20` | `0xe30` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3568` | `0x3578` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xb514` | `0xb51c` | **`+0x8`** |

### Other Changes

```diff

-181.0.0.0.0
+182.0.0.0.0

-  Functions: 4741
-  Symbols:   8738
-  CStrings:  2497
+  Functions: 4743
+  Symbols:   8743
+  CStrings:  2499
Symbols:
+ -[AXMDisplay currentPhysicalOrientation]
+ GCC_except_table1134
+ GCC_except_table2702
+ GCC_except_table2705
+ GCC_except_table2714
+ GCC_except_table2715
+ GCC_except_table2730
+ GCC_except_table2740
+ GCC_except_table2867
+ GCC_except_table2870
+ GCC_except_table2876
+ GCC_except_table2885
+ GCC_except_table2886
+ GCC_except_table2892
+ GCC_except_table2969
+ GCC_except_table2970
+ GCC_except_table2977
+ GCC_except_table3002
+ GCC_except_table3003
+ GCC_except_table3013
+ GCC_except_table3018
+ GCC_except_table3053
+ GCC_except_table3054
+ GCC_except_table3058
+ GCC_except_table3059
+ GCC_except_table3225
+ GCC_except_table3283
+ GCC_except_table3288
+ GCC_except_table3289
+ GCC_except_table3304
+ GCC_except_table3305
+ GCC_except_table3318
+ GCC_except_table3331
+ GCC_except_table3355
+ GCC_except_table3370
+ GCC_except_table3374
+ GCC_except_table3378
+ GCC_except_table3381
+ GCC_except_table3400
+ GCC_except_table3590
+ GCC_except_table3593
+ GCC_except_table3604
+ GCC_except_table3608
+ GCC_except_table3644
+ GCC_except_table3858
+ GCC_except_table3862
+ GCC_except_table3874
+ GCC_except_table3931
+ GCC_except_table3935
+ GCC_except_table3941
+ GCC_except_table3955
+ GCC_except_table3959
+ GCC_except_table3963
+ GCC_except_table3967
+ GCC_except_table3971
+ GCC_except_table3974
+ GCC_except_table3996
+ GCC_except_table4112
+ GCC_except_table4117
+ GCC_except_table4121
+ GCC_except_table4125
+ GCC_except_table4134
+ GCC_except_table4135
+ _AVMediaTypeVideo
+ _OBJC_CLASS_$_AVCaptureDeviceInput
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__110shared_ptrI17espresso_buffer_tED1B9fqe220106Ev
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorINS_10shared_ptrI17espresso_buffer_tEENS_9allocatorIS3_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIU8__strongP8NSStringNS_9allocatorIS3_EEE18__assign_with_sizeB9fqe220106INS_17_ClassicAlgPolicyEPU8__strongKS2_SA_EEvT0_T1_l
+ __ZNSt3__16vectorIU8__strongP8NSStringNS_9allocatorIS3_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIU8__strongP8NSStringNS_9allocatorIS3_EEED2B9fqe220106Ev
+ __ZNSt3__16vectorIbNS_9allocatorIbEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE18__assign_with_sizeB9fqe220106INS_17_ClassicAlgPolicyEPKfS7_EEvT0_T1_l
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIiNS_9allocatorIiEEE18__assign_with_sizeB9fqe220106INS_17_ClassicAlgPolicyEPKiS7_EEvT0_T1_l
+ __ZNSt3__16vectorIiNS_9allocatorIiEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ __axmPhysicalOrientationForCCWRadians
+ __cwRadiansForCADisplayOrientationString
- -[AXMDisplayManager _discreteOrientationForOrientation:]
- GCC_except_table2696
- GCC_except_table2699
- GCC_except_table2708
- GCC_except_table2709
- GCC_except_table2728
- GCC_except_table2738
- GCC_except_table2865
- GCC_except_table2868
- GCC_except_table2874
- GCC_except_table2881
- GCC_except_table2882
- GCC_except_table2890
- GCC_except_table2967
- GCC_except_table2968
- GCC_except_table2975
- GCC_except_table3000
- GCC_except_table3001
- GCC_except_table3011
- GCC_except_table3016
- GCC_except_table3044
- GCC_except_table3045
- GCC_except_table3055
- GCC_except_table3056
- GCC_except_table3223
- GCC_except_table3280
- GCC_except_table3281
- GCC_except_table3285
- GCC_except_table3302
- GCC_except_table3303
- GCC_except_table3316
- GCC_except_table3329
- GCC_except_table3353
- GCC_except_table3368
- GCC_except_table3372
- GCC_except_table3376
- GCC_except_table3379
- GCC_except_table3398
- GCC_except_table3588
- GCC_except_table3591
- GCC_except_table3602
- GCC_except_table3606
- GCC_except_table3642
- GCC_except_table3856
- GCC_except_table3860
- GCC_except_table3872
- GCC_except_table3929
- GCC_except_table3933
- GCC_except_table3939
- GCC_except_table3953
- GCC_except_table3957
- GCC_except_table3961
- GCC_except_table3965
- GCC_except_table3969
- GCC_except_table3972
- GCC_except_table3994
- GCC_except_table4110
- GCC_except_table4115
- GCC_except_table4119
- GCC_except_table4123
- GCC_except_table4130
- GCC_except_table4131
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__110shared_ptrI17espresso_buffer_tED1B9fqe220100Ev
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorINS_10shared_ptrI17espresso_buffer_tEENS_9allocatorIS3_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIU8__strongP8NSStringNS_9allocatorIS3_EEE18__assign_with_sizeB9fqe220100INS_17_ClassicAlgPolicyEPU8__strongKS2_SA_EEvT0_T1_l
- __ZNSt3__16vectorIU8__strongP8NSStringNS_9allocatorIS3_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIU8__strongP8NSStringNS_9allocatorIS3_EEED2B9fqe220100Ev
- __ZNSt3__16vectorIbNS_9allocatorIbEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEE18__assign_with_sizeB9fqe220100INS_17_ClassicAlgPolicyEPKfS7_EEvT0_T1_l
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIiNS_9allocatorIiEEE18__assign_with_sizeB9fqe220100INS_17_ClassicAlgPolicyEPKiS7_EEvT0_T1_l
- __ZNSt3__16vectorIiNS_9allocatorIiEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
CStrings:
+ "AXMDisplay<%p>: Backing:%@ Name:%@ displayID:%@ uniqueID: %@ scale:%@ size:[%.2f %.2f] physicalSize:[%.2f %.2f] orientation:%@ (%s) currentPhysicalOrientation:(%s) refBounds:[%.2f %.2f %.2f %.2f] deepColor:%d"
+ "Failed to re-lock white balance after addOutput: %@"
+ "setWhiteBalanceModeLockedWithDeviceWhiteBalanceGains threw — skipping WB restore: %@"
- "AXMDisplay<%p>: Backing:%@ Name:%@ displayID:%@ uniqueID: %@ scale:%@ size:[%.2f %.2f] physicalSize:[%.2f %.2f] orientation:%@ (%s) refBounds:[%.2f %.2f %.2f %.2f] deepColor:%d"
```
