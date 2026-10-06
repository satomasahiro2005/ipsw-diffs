## HearingUtilities

> `/System/Library/PrivateFrameworks/HearingUtilities.framework/HearingUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbadb0` | `0xbb80c` | **`+0xa5c`** |
| `__TEXT.__oslogstring` | `0x10145` | `0x102b9` | **`+0x174`** |
| `__DATA.__bss` | `0x7e0` | `0x828` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x37e8` | `0x3830` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x2934` | `0x297c` | **`+0x48`** |
| `__DATA_DIRTY.__bss` | `0x110` | `0xd0` | **`-0x40`** |
| `__TEXT.__cstring` | `0x60da` | `0x6104` | **`+0x2a`** |
| `__AUTH_CONST.__const` | `0x1638` | `0x1658` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2cf0` | `0x2d10` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x56f8` | `0x5708` | **`+0x10`** |
| `__TEXT.__const` | `0x7e4` | `0x7f4` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x9474` | `0x9484` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x778` | `0x780` | **`+0x8`** |

### Other Changes

```diff

-543.2.1.0.0
+543.2.3.0.0

-  Functions: 4145
-  Symbols:   6459
-  CStrings:  2125
+  Functions: 4149
+  Symbols:   6466
+  CStrings:  2131
Symbols:
+ -[HUNoiseController exposureDatumsFromSamples:]
+ GCC_except_table3136
+ GCC_except_table3166
+ GCC_except_table3188
+ GCC_except_table3196
+ GCC_except_table3205
+ GCC_except_table3214
+ GCC_except_table3217
+ GCC_except_table3219
+ GCC_except_table3275
+ GCC_except_table3302
+ GCC_except_table3380
+ GCC_except_table3384
+ GCC_except_table3385
+ GCC_except_table3409
+ GCC_except_table3415
+ GCC_except_table3421
+ GCC_except_table3424
+ GCC_except_table3436
+ GCC_except_table3444
+ GCC_except_table3451
+ GCC_except_table3456
+ GCC_except_table3465
+ GCC_except_table3467
+ GCC_except_table3477
+ GCC_except_table3480
+ GCC_except_table3489
+ GCC_except_table3492
+ GCC_except_table3494
+ GCC_except_table3519
+ GCC_except_table3582
+ GCC_except_table3592
+ GCC_except_table3663
+ GCC_except_table3665
+ GCC_except_table3708
+ GCC_except_table3745
+ GCC_except_table3820
+ GCC_except_table3838
+ GCC_except_table3841
+ GCC_except_table3851
+ _AVSystemController_RouteDescriptionKey_RouteUID
+ ___47-[HUNoiseController exposureDatumsFromSamples:]_block_invoke
+ ___69-[HUComfortSoundsController calculateVolumeForSessionWithCompletion:]_block_invoke
+ ___block_descriptor_32_e41_q24?0"HUNoiseSample"8"HUNoiseSample"16l
+ ___block_descriptor_48_e8_32s40w_e20_v20?0B8"NSError"12ls32l8w40l8
+ ___block_descriptor_72_e8_32s40s48r56r64r_e39_v32?0"NSString"8"NSDictionary"16^B24ls32l8s40l8r48l8r56l8r64l8
- GCC_except_table3135
- GCC_except_table3165
- GCC_except_table3186
- GCC_except_table3195
- GCC_except_table3204
- GCC_except_table3213
- GCC_except_table3216
- GCC_except_table3218
- GCC_except_table3274
- GCC_except_table3301
- GCC_except_table3382
- GCC_except_table3383
- GCC_except_table3405
- GCC_except_table3411
- GCC_except_table3417
- GCC_except_table3420
- GCC_except_table3432
- GCC_except_table3440
- GCC_except_table3447
- GCC_except_table3452
- GCC_except_table3461
- GCC_except_table3463
- GCC_except_table3473
- GCC_except_table3476
- GCC_except_table3485
- GCC_except_table3488
- GCC_except_table3490
- GCC_except_table3515
- GCC_except_table3578
- GCC_except_table3584
- GCC_except_table3659
- GCC_except_table3661
- GCC_except_table3704
- GCC_except_table3741
- GCC_except_table3816
- GCC_except_table3834
- GCC_except_table3837
- GCC_except_table3847
- ___block_descriptor_56_e8_32s40s48r_e39_v32?0"NSString"8"NSDictionary"16^B24ls32l8s40l8r48l8
CStrings:
+ "Batch exposure write of %lu datums failed, retrying individually: %@"
+ "Dropped %lu exposure samples fully overlapped by their predecessor"
+ "HAServer: Available devices update changed connection status, isConnected: %d"
+ "LiveListenController: Sizing rewind ring for %.1fs at IOBufferDuration %.6fs = %lu buffers"
+ "Skipping exposure sample with non-positive duration: %@ - %@"
+ "Updating volume, media playing %d"
+ "q24@?0@\"HUNoiseSample\"8@\"HUNoiseSample\"16"
- "Updating volume %d, %d, %lf"
```
