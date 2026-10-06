## SearchUI

> `/System/Library/PrivateFrameworks/SearchUI.framework/SearchUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf587c` | `0xf71e8` | **`+0x196c`** |
| `__TEXT.__cstring` | `0x3a79` | `0x3b79` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x1dff8` | `0x1e0e8` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x3360` | `0x3420` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x4750` | `0x4800` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x12430` | `0x124d8` | **`+0xa8`** |
| `__DATA_CONST.__objc_selrefs` | `0xa260` | `0xa2e8` | **`+0x88`** |
| `__AUTH_CONST.__const` | `0x2ab0` | `0x2b28` | **`+0x78`** |
| `__TEXT.__swift5_typeref` | `0x3992` | `0x39f8` | **`+0x66`** |
| `__DATA_CONST.__const` | `0x28a0` | `0x28f0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x48b8` | `0x4908` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x145c` | `0x14a0` | **`+0x44`** |
| `__TEXT.__const` | `0x3a84` | `0x3ac4` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0xa18` | `0xa58` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x7ec` | `0x824` | **`+0x38`** |
| `__AUTH.__data` | `0x7c8` | `0x7f0` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1900` | `0x1920` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x6fa` | `0x71a` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x8f4` | `0x910` | **`+0x1c`** |
| `__DATA.__data` | `0x3374` | `0x3384` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2568` | `0x2578` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xad8` | `0xae0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xcfc` | `0xd00` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xe0` | `0xe4` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-673.0.12.104.0
+685.1.2.0.0

-  Functions: 7004
-  Symbols:   11496
-  CStrings:  824
+  Functions: 7027
+  Symbols:   11523
+  CStrings:  833
Symbols:
+ -[SearchUICollectionViewDataSource applySnapshot:animated:completion:]
+ -[SearchUICollectionViewDataSource indexForSectionIdentifier:]
+ -[SearchUICollectionViewDataSource liveCellReuseIdentifierForRowModel:]
+ -[SearchUICollectionViewDataSource liveReuseIdentifiersInSnapshot:]
+ -[SearchUICollectionViewDataSource logSnapshotDiffFromCurrentSnapshot:toNewSnapshot:]
+ -[SearchUICollectionViewDataSource reloadRowModelsWithChangedCellClassInSnapshot:]
+ -[SearchUICollectionViewDataSource shouldReloadRowModel:appliedReuseIdentifiers:]
+ -[SearchUIContactCache contactFetchCompletionQueue]
+ -[SearchUIContactCache contactFetchQueue]
+ -[SearchUIContactCache fetchAvailableContactsForIdentifiers:completionHandler:]
+ -[SearchUIDataSourceSnapshotBuilder generateUniqueIdentifierForBaseIdentifier:withUnavailableIdentifiers:]
+ -[SearchUILeadingTrailingSectionModel initWithCardSection:rowModels:result:queryId:section:builder:]
+ -[SearchUILeadingTrailingSectionModel rowModelsForCardSections:result:queryId:builder:]
+ -[SearchUIMultiResultCollectionView numberOfVisibleAppsForCurrentWidth]
+ -[SearchUIPhotosOneUpController oneUpPresentationPreferredModalPresentationStyle:]
+ GCC_except_table104
+ GCC_except_table12
+ GCC_except_table23
+ GCC_except_table29
+ _OBJC_CLASS_$_NSUUID
+ _OBJC_CLASS_$__TtC8SearchUI24SearchUISnippetUIMetrics
+ _OBJC_IVAR_$_SearchUIContactCache._contactFetchCompletionQueue
+ _OBJC_IVAR_$_SearchUIContactCache._contactFetchQueue
+ _OBJC_METACLASS_$__TtC8SearchUI24SearchUISnippetUIMetrics
+ _SearchUIContactCacheResultIsUnavailable
+ _SearchUIInsetFromPlatterToHighlightForStandardRow
+ __CLASS_METHODS__TtC8SearchUI24SearchUISnippetUIMetrics
+ __CLASS_PROPERTIES__TtC8SearchUI24SearchUISnippetUIMetrics
+ __DATA__TtC8SearchUI24SearchUISnippetUIMetrics
+ __INSTANCE_METHODS__TtC8SearchUI24SearchUISnippetUIMetrics
+ __METACLASS_DATA__TtC8SearchUI24SearchUISnippetUIMetrics
+ ___58-[SearchUIPersonHeaderCardSectionView updateWithRowModel:]_block_invoke_3
+ ___64-[SearchUIContactCache computeObjectsForKeys:completionHandler:]_block_invoke
+ ___64-[SearchUIContactCache computeObjectsForKeys:completionHandler:]_block_invoke_2
+ ___64-[SearchUIContactCache computeObjectsForKeys:completionHandler:]_block_invoke_3
+ ___64-[SearchUIContactCache computeObjectsForKeys:completionHandler:]_block_invoke_4
+ ___70-[SearchUICollectionViewDataSource applySnapshot:animated:completion:]_block_invoke
+ ___70-[SearchUIContactCache fetchContactsForIdentifiers:completionHandler:]_block_invoke
+ ___block_descriptor_40_e8_32w_e42_v16?0"SearchUICollectionViewDataSource"8lw32l8
+ ___block_descriptor_48_e8_32s40bs_e17_v16?0"NSArray"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40bs_e19_v16?0"CNContact"8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40bs48r_e17_v16?0"NSArray"8ls32l8r48l8s40l8
+ ___block_descriptor_56_e8_32s40bs48r_e5_v8?0lr48l8s40l8s32l8
+ ___block_descriptor_57_e8_32s40s48w_e5_v8?0lw48l8s32l8s40l8
+ _symbolic SSSgycSg
+ _symbolic So32SearchUICollectionViewControllerCSgXwz_Xx
+ _symbolic _____ 8SearchUI0A18UISnippetUIMetricsC
+ _symbolic _____y_____GSgXw 8SearchUI24SupplementaryHostingViewC AA6HeaderV
+ _symbolic _____y_____GSgXwz_Xx 8SearchUI24SupplementaryHostingViewC AA6HeaderV
- -[SearchUICollectionViewCell _applyIntrinsicContentHeightToAttributes:]
- -[SearchUICollectionViewController searchui_contentColumnWidthForContainerWidth:]
- -[SearchUICollectionViewDataSource applySnapshot:animated:skipsDiffing:completion:]
- -[SearchUICollectionViewDataSource numberOfUpdatesInProgress]
- -[SearchUICollectionViewDataSource setNumberOfUpdatesInProgress:]
- -[SearchUIDataSourceSnapshotBuilder generateIterativeIdentifierForBaseIdentifier:withUnavailableIdentifiers:]
- -[SearchUILeadingTrailingSectionModel initWithCardSection:rowModels:result:queryId:section:]
- -[SearchUILeadingTrailingSectionModel rowModelsForCardSections:result:queryId:]
- -[SearchUIResultsViewController frameForChildViewControllers]
- GCC_except_table105
- GCC_except_table22
- GCC_except_table24
- GCC_except_table25
- _OBJC_IVAR_$_SearchUICollectionViewDataSource._numberOfUpdatesInProgress
- _SearchUISpotlightColumnTopMargin
- _SearchUISpotlightContentColumnWidth
- ___83-[SearchUICollectionViewDataSource applySnapshot:animated:skipsDiffing:completion:]_block_invoke
- ___83-[SearchUICollectionViewDataSource applySnapshot:animated:skipsDiffing:completion:]_block_invoke_2
- ___block_descriptor_40_e8_32s_e19_v16?0"CNContact"8ls32l8
- ___block_descriptor_57_e8_32s40bs48w_e5_v8?0lw48l8s40l8s32l8
- ___block_descriptor_58_e8_32s40bs48w_e5_v8?0lw48l8s32l8s40l8
- ___block_descriptor_58_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
CStrings:
+ "\n  %@{%ld, %lu}"
+ "\n  [NEW]  {%ld, %lu}"
+ "\n  [SKIP] {%ld, %lu}"
+ "(non-recycling)"
+ "Applied snapshot"
+ "Applying snapshot asynchronously"
+ "Reloading item %{sensitive}@ instead of reconfiguring: reuse identifier changed %@ -> %@."
+ "Snapshot update summary:"
+ "[reconfigure] "
+ "[reload]  "
+ "com.apple.searchui.contactcache.completion"
+ "com.apple.searchui.contactcache.fetch"
+ "v16@?0@\"SearchUICollectionViewDataSource\"8"
- "%@-%ld"
- "Applied snapshot, skisDiffing %d"
- "Applying snapshot asynchronously, skipsDiffing:%d, updatesInProgress:%d"
- "Applying snapshot synchronously"
```
