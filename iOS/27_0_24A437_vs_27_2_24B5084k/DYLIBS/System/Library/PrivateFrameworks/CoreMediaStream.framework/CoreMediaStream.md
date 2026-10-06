## CoreMediaStream

> `/System/Library/PrivateFrameworks/CoreMediaStream.framework/CoreMediaStream`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcd3e0` | `0xcd52c` | **`+0x14c`** |
| `__TEXT.__oslogstring` | `0xef38` | `0xef85` | **`+0x4d`** |
| `__AUTH_CONST.__cfstring` | `0x87e0` | `0x8800` | **`+0x20`** |
| `__TEXT.__cstring` | `0xa4b5` | `0xa4ca` | **`+0x15`** |
| `__DATA_CONST.__objc_selrefs` | `0x4078` | `0x4080` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2d40` | `0x2d48` | **`+0x8`** |

### Other Changes

```diff

-912.0.235.0.0
+916.40.110.0.0

-  Functions: 3615
-  Symbols:   5786
-  CStrings:  2278
+  Functions: 3616
+  Symbols:   5787
+  CStrings:  2280
Symbols:
+ GCC_except_table2611
+ GCC_except_table2613
+ GCC_except_table2615
+ GCC_except_table2618
+ GCC_except_table2621
+ GCC_except_table2623
+ GCC_except_table2657
+ GCC_except_table2661
+ GCC_except_table2674
+ GCC_except_table2743
+ GCC_except_table2766
+ GCC_except_table2768
+ GCC_except_table2772
+ GCC_except_table2774
+ GCC_except_table2776
+ GCC_except_table2868
+ GCC_except_table2870
+ GCC_except_table2880
+ GCC_except_table2882
+ GCC_except_table2885
+ GCC_except_table2887
+ GCC_except_table3031
+ GCC_except_table3039
+ GCC_except_table3052
+ GCC_except_table3120
+ GCC_except_table3123
+ GCC_except_table3141
+ GCC_except_table3145
+ GCC_except_table3149
+ GCC_except_table3153
+ GCC_except_table3157
+ GCC_except_table3161
+ GCC_except_table3163
+ GCC_except_table3167
+ GCC_except_table3169
+ GCC_except_table3173
+ GCC_except_table3175
+ GCC_except_table3185
+ GCC_except_table3188
+ GCC_except_table3190
+ GCC_except_table3193
+ GCC_except_table3196
+ GCC_except_table3200
+ GCC_except_table3204
+ GCC_except_table3206
+ GCC_except_table3210
+ GCC_except_table3212
+ GCC_except_table3248
+ GCC_except_table3250
+ GCC_except_table3284
+ GCC_except_table3287
+ GCC_except_table3289
+ GCC_except_table3292
+ GCC_except_table3295
+ GCC_except_table3369
+ GCC_except_table3392
+ GCC_except_table3398
+ GCC_except_table3407
+ GCC_except_table3445
+ GCC_except_table3450
+ GCC_except_table3583
+ GCC_except_table3595
+ GCC_except_table3599
+ GCC_except_table3603
+ __logNonSuccessResponse
- GCC_except_table2608
- GCC_except_table2612
- GCC_except_table2614
- GCC_except_table2616
- GCC_except_table2620
- GCC_except_table2622
- GCC_except_table2652
- GCC_except_table2658
- GCC_except_table2673
- GCC_except_table2742
- GCC_except_table2765
- GCC_except_table2767
- GCC_except_table2771
- GCC_except_table2773
- GCC_except_table2775
- GCC_except_table2867
- GCC_except_table2869
- GCC_except_table2879
- GCC_except_table2881
- GCC_except_table2884
- GCC_except_table2886
- GCC_except_table3030
- GCC_except_table3038
- GCC_except_table3051
- GCC_except_table3119
- GCC_except_table3122
- GCC_except_table3140
- GCC_except_table3144
- GCC_except_table3148
- GCC_except_table3152
- GCC_except_table3156
- GCC_except_table3160
- GCC_except_table3162
- GCC_except_table3166
- GCC_except_table3168
- GCC_except_table3172
- GCC_except_table3174
- GCC_except_table3184
- GCC_except_table3187
- GCC_except_table3189
- GCC_except_table3192
- GCC_except_table3195
- GCC_except_table3199
- GCC_except_table3203
- GCC_except_table3205
- GCC_except_table3209
- GCC_except_table3211
- GCC_except_table3247
- GCC_except_table3249
- GCC_except_table3283
- GCC_except_table3286
- GCC_except_table3288
- GCC_except_table3291
- GCC_except_table3294
- GCC_except_table3368
- GCC_except_table3391
- GCC_except_table3397
- GCC_except_table3406
- GCC_except_table3444
- GCC_except_table3449
- GCC_except_table3582
- GCC_except_table3594
- GCC_except_table3598
- GCC_except_table3602
Functions:
~ ___153+[MSProtocolUtilities initiateMigrationToCPLForAlbumWithGUID:sharedAlbumTitle:personID:isSilentMigration:clientVersion:sourceAssetCount:completionBlock:]_block_invoke : 1324 -> 1328
+ __logNonSuccessResponse
~ ___153+[MSProtocolUtilities completeMigrationToCPLForAlbumWithGUID:clientOrgKey:personID:clientVersion:sourceAssetCount:destinationAssetCount:completionBlock:]_block_invoke : 1144 -> 1152
~ ___99+[MSProtocolUtilities cancelMigrationToCPLForAlbumWithGUID:personID:clientVersion:completionBlock:]_block_invoke : 1144 -> 1152
~ ___112+[MSProtocolUtilities failMigrationToCPLForAlbumWithGUID:migrationError:personID:clientVersion:completionBlock:]_block_invoke : 1144 -> 1152
~ ___102+[MSProtocolUtilities unarchiveMigrationToCPLForAlbumWithGUID:personID:clientVersion:completionBlock:]_block_invoke : 1144 -> 1152
CStrings:
+ "Request %@ to %{public}@ failed with status code %ld, %{public}@: %{public}@"
+ "X-Apple-Request-UUID"
```
