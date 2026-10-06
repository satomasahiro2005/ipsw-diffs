## CPAnalytics

> `/System/Library/PrivateFrameworks/CPAnalytics.framework/CPAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x123c0` | `0x121f0` | **`-0x1d0`** |
| `__TEXT.__cstring` | `0x2411` | `0x24a3` | **`+0x92`** |
| `__TEXT.__oslogstring` | `0x1004` | `0xfba` | **`-0x4a`** |
| `__AUTH_CONST.__cfstring` | `0x2c00` | `0x2c40` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xd98` | `0xd88` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x8e0` | `0x8d8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x2a8` | `0x2a0` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x141c` | `0x1414` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x528` | `0x520` | **`-0x8`** |

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0

-  Functions: 391
-  Symbols:   1123
-  CStrings:  449
+  Functions: 390
+  Symbols:   1120
+  CStrings:  450
Symbols:
+ GCC_except_table142
+ GCC_except_table146
+ GCC_except_table152
+ GCC_except_table183
+ GCC_except_table185
+ GCC_except_table187
+ GCC_except_table189
+ GCC_except_table372
- -[CPAnalyticsBiomeDestination _donatePhotoDeleteEventWithBaseSample:andEvent:]
- GCC_except_table143
- GCC_except_table150
- GCC_except_table153
- GCC_except_table184
- GCC_except_table186
- GCC_except_table188
- GCC_except_table190
- GCC_except_table373
- _CPAnalyticsPhotosDeleteKey
- _OBJC_CLASS_$_BMPhotosDelete
Functions:
~ +[CPAnalyticsCoreAnalyticsHelper upgradePayload:sourceEvent:] : 620 -> 652
~ -[CPAnalyticsBiomeDestination _sendBiomeEvent:matcher:] : 832 -> 792
- -[CPAnalyticsBiomeDestination _donatePhotoDeleteEventWithBaseSample:andEvent:]
CStrings:
+ "com.apple.photos.CPAnalytics.gridHeaderControlTapped"
+ "com.apple.photos.CPAnalytics.slideshowCustomized"
+ "com.apple.photos.CPAnalytics.stagingArea.selectionCommitted"
- "/photos/deletes"
- "[Biome][Donation][Photos][Delete] Sent a photo delete event with uuid: %@"
```
