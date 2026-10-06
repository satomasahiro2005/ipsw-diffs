## HearingUtilities

> `/System/Library/PrivateFrameworks/HearingUtilities.framework/HearingUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb9a80` | `0xba044` | **`+0x5c4`** |
| `__TEXT.__oslogstring` | `0xfd57` | `0xfdda` | **`+0x83`** |
| `__TEXT.__objc_methlist` | `0x93e4` | `0x9434` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0xc078` | `0xc0a8` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x5688` | `0x56b8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x60b7` | `0x60da` | **`+0x23`** |
| `__AUTH_CONST.__cfstring` | `0x5d60` | `0x5d80` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2cd8` | `0x2ce8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2900` | `0x290c` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0xa24` | `0xa28` | **`+0x4`** |

### Other Changes

```diff

-  Functions: 4130
-  Symbols:   6442
-  CStrings:  2109
+  Functions: 4138
+  Symbols:   6451
+  CStrings:  2113
Symbols:
+ -[HUNoiseController filterPendingNoiseSamplesForAOP2IfNeeded]
+ -[HUNoiseController lastClassificationSampleDate]
+ -[HUNoiseController processSoundClassificationMeasurementsAOP2:withMetadata:]
+ -[HUNoiseController setLastClassificationSampleDate:]
+ -[HUNoiseController updateLastClassificationSampleWithDetectionState:sampleDate:]
+ -[HUNoiseSettings internalOverrideSoundDetectionType]
+ GCC_except_table2630
+ GCC_except_table2656
+ GCC_except_table2663
+ GCC_except_table2717
+ GCC_except_table2720
+ GCC_except_table2729
+ GCC_except_table2733
+ GCC_except_table2772
+ GCC_except_table2777
+ GCC_except_table2784
+ GCC_except_table2792
+ GCC_except_table2797
+ GCC_except_table2799
+ GCC_except_table2808
+ GCC_except_table2812
+ GCC_except_table2914
+ GCC_except_table2936
+ GCC_except_table2968
+ GCC_except_table2996
+ GCC_except_table3133
+ GCC_except_table3163
+ GCC_except_table3185
+ GCC_except_table3193
+ GCC_except_table3202
+ GCC_except_table3211
+ GCC_except_table3214
+ GCC_except_table3216
+ GCC_except_table3272
+ GCC_except_table3299
+ GCC_except_table3378
+ GCC_except_table3379
+ GCC_except_table3398
+ GCC_except_table3404
+ GCC_except_table3410
+ GCC_except_table3413
+ GCC_except_table3425
+ GCC_except_table3440
+ GCC_except_table3445
+ GCC_except_table3454
+ GCC_except_table3456
+ GCC_except_table3466
+ GCC_except_table3469
+ GCC_except_table3478
+ GCC_except_table3481
+ GCC_except_table3483
+ GCC_except_table3508
+ GCC_except_table3571
+ GCC_except_table3577
+ GCC_except_table3581
+ GCC_except_table3652
+ GCC_except_table3654
+ GCC_except_table3697
+ GCC_except_table3734
+ GCC_except_table3809
+ GCC_except_table3827
+ GCC_except_table3830
+ GCC_except_table3840
+ _OBJC_IVAR_$_HUNoiseController._lastClassificationSampleDate
+ ___54-[HUNoiseController _startADAMClassificationReceiving]_block_invoke_2
+ ___77-[HUNoiseController processSoundClassificationMeasurementsAOP2:withMetadata:]_block_invoke
- GCC_except_table2629
- GCC_except_table2655
- GCC_except_table2662
- GCC_except_table2716
- GCC_except_table2718
- GCC_except_table2724
- GCC_except_table2732
- GCC_except_table2771
- GCC_except_table2776
- GCC_except_table2783
- GCC_except_table2791
- GCC_except_table2796
- GCC_except_table2798
- GCC_except_table2807
- GCC_except_table2811
- GCC_except_table2913
- GCC_except_table2935
- GCC_except_table2967
- GCC_except_table2995
- GCC_except_table3132
- GCC_except_table3162
- GCC_except_table3183
- GCC_except_table3192
- GCC_except_table3201
- GCC_except_table3210
- GCC_except_table3213
- GCC_except_table3215
- GCC_except_table3271
- GCC_except_table3298
- GCC_except_table3375
- GCC_except_table3376
- GCC_except_table3391
- GCC_except_table3397
- GCC_except_table3403
- GCC_except_table3406
- GCC_except_table3418
- GCC_except_table3426
- GCC_except_table3437
- GCC_except_table3446
- GCC_except_table3448
- GCC_except_table3458
- GCC_except_table3461
- GCC_except_table3470
- GCC_except_table3473
- GCC_except_table3475
- GCC_except_table3500
- GCC_except_table3563
- GCC_except_table3569
- GCC_except_table3573
- GCC_except_table3644
- GCC_except_table3646
- GCC_except_table3689
- GCC_except_table3726
- GCC_except_table3801
- GCC_except_table3819
- GCC_except_table3822
- GCC_except_table3832
CStrings:
+ "InternalOverrideSoundDetectionType"
+ "Invalid classification date: %@"
+ "Last sample date is later than start date"
+ "Update last classification state from %d (%@) to %d (%@)"
```
