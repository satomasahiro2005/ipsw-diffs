## EventKit

> `/System/Library/Frameworks/EventKit.framework/EventKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x2f30` | `0x34d0` | **`+0x5a0`** |
| `__DATA_DIRTY.__objc_data` | `0x2170` | `0x1bd0` | **`-0x5a0`** |
| `__TEXT.__text` | `0x1a1160` | `0x1a1510` | **`+0x3b0`** |
| `__DATA_CONST.__got` | `0x1978` | `0x1a08` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0xef48` | `0xef78` | **`+0x30`** |
| `__DATA.__data` | `0x2850` | `0x2830` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x15a4c` | `0x15a6c` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xae40` | `0xae58` | **`+0x18`** |
| `__TEXT.__const` | `0x4820` | `0x4810` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x3918` | `0x3928` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x6720` | `0x6730` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x194c` | `0x1942` | **`-0xa`** |
| `__AUTH_CONST.__objc_const` | `0x18540` | `0x18548` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x580` | `0x588` | **`+0x8`** |

### Other Changes

```diff

-1968.0.0.0.0
+1970.0.0.0.0

-  Functions: 10661
-  Symbols:   13226
-  CStrings:  2665
+  Functions: 10665
+  Symbols:   13229
+  CStrings:  2666
Symbols:
+ -[EKEventStore isMagicComposeRestrictedByMDM]
+ -[EKLocationSearchModel removeRecentSearchResult:]
+ GCC_except_table119
+ GCC_except_table127
+ GCC_except_table133
+ GCC_except_table139
+ GCC_except_table142
+ GCC_except_table161
+ GCC_except_table165
+ GCC_except_table176
+ GCC_except_table183
+ GCC_except_table189
+ GCC_except_table192
+ GCC_except_table230
+ GCC_except_table236
+ GCC_except_table239
+ GCC_except_table242
+ GCC_except_table249
+ GCC_except_table253
+ GCC_except_table268
+ GCC_except_table276
+ GCC_except_table279
+ GCC_except_table285
+ GCC_except_table288
+ GCC_except_table323
+ GCC_except_table326
+ GCC_except_table364
+ GCC_except_table369
+ GCC_except_table377
+ GCC_except_table383
+ GCC_except_table390
+ GCC_except_table393
+ GCC_except_table401
+ GCC_except_table413
+ GCC_except_table417
+ GCC_except_table421
+ GCC_except_table422
+ GCC_except_table443
+ GCC_except_table448
+ GCC_except_table454
+ GCC_except_table464
+ GCC_except_table468
+ GCC_except_table471
+ GCC_except_table474
+ GCC_except_table478
+ GCC_except_table481
+ GCC_except_table509
+ GCC_except_table555
+ GCC_except_table562
+ GCC_except_table571
+ GCC_except_table585
+ GCC_except_table588
+ GCC_except_table592
+ GCC_except_table607
+ GCC_except_table643
+ GCC_except_table66
+ GCC_except_table685
+ GCC_except_table691
+ GCC_except_table709
+ GCC_except_table714
+ GCC_except_table717
+ GCC_except_table72
+ GCC_except_table724
+ GCC_except_table731
+ GCC_except_table739
+ GCC_except_table747
+ GCC_except_table757
+ GCC_except_table766
+ GCC_except_table770
+ GCC_except_table87
+ GCC_except_table90
+ GCC_except_table99
+ ___45-[EKEventStore isMagicComposeRestrictedByMDM]_block_invoke
- GCC_except_table109
- GCC_except_table117
- GCC_except_table125
- GCC_except_table131
- GCC_except_table135
- GCC_except_table140
- GCC_except_table159
- GCC_except_table163
- GCC_except_table172
- GCC_except_table181
- GCC_except_table187
- GCC_except_table190
- GCC_except_table193
- GCC_except_table228
- GCC_except_table232
- GCC_except_table237
- GCC_except_table240
- GCC_except_table243
- GCC_except_table251
- GCC_except_table262
- GCC_except_table274
- GCC_except_table277
- GCC_except_table283
- GCC_except_table286
- GCC_except_table319
- GCC_except_table324
- GCC_except_table352
- GCC_except_table367
- GCC_except_table375
- GCC_except_table379
- GCC_except_table388
- GCC_except_table391
- GCC_except_table394
- GCC_except_table411
- GCC_except_table415
- GCC_except_table419
- GCC_except_table420
- GCC_except_table441
- GCC_except_table446
- GCC_except_table450
- GCC_except_table462
- GCC_except_table466
- GCC_except_table469
- GCC_except_table472
- GCC_except_table476
- GCC_except_table479
- GCC_except_table505
- GCC_except_table539
- GCC_except_table553
- GCC_except_table560
- GCC_except_table569
- GCC_except_table583
- GCC_except_table586
- GCC_except_table590
- GCC_except_table605
- GCC_except_table637
- GCC_except_table683
- GCC_except_table687
- GCC_except_table705
- GCC_except_table712
- GCC_except_table715
- GCC_except_table722
- GCC_except_table729
- GCC_except_table737
- GCC_except_table741
- GCC_except_table751
- GCC_except_table764
- GCC_except_table768
- GCC_except_table88
- _symbolic ______pSg 8EventKit20IntelligentSchedulerC20ScheduleInfoProviderP
CStrings:
+ "Error fetching Magic Compose MDM restriction: %d"
```
