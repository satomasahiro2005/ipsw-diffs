## SearchUI

> `/System/Library/PrivateFrameworks/SearchUI.framework/SearchUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x33c0` | `0x3360` | **`-0x60`** |
| `__TEXT.__objc_methlist` | `0x123d8` | `0x12430` | **`+0x58`** |
| `__DATA_DIRTY.__objc_data` | `0x3258` | `0x3208` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x4870` | `0x48b8` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x1e028` | `0x1dff8` | **`-0x30`** |
| `__TEXT.__cstring` | `0x3aa9` | `0x3a79` | **`-0x30`** |
| `__TEXT.__text` | `0xf58a0` | `0xf587c` | **`-0x24`** |
| `__TEXT.__gcc_except_tab` | `0xa00` | `0xa18` | **`+0x18`** |
| `__DATA.__data` | `0x3384` | `0x3374` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x2578` | `0x2568` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0xce8` | `0xcd8` | **`-0x10`** |
| `__TEXT.__const` | `0x3a74` | `0x3a84` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xcf4` | `0xcfc` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xae0` | `0xad8` | **`-0x8`** |

### Other Changes

```diff

-673.0.6.0.0
+673.0.12.102.0

-  Functions: 6996
+  Functions: 7004

-  CStrings:  826
+  CStrings:  824
Symbols:
+ +[SearchUIAppIconUtilities idealHorizontalSpacingBetweenAppIconsForWidth:]
+ +[SearchUIAppIconUtilities numberOfAppIconsPerRowForWidth:]
+ +[SearchUIHomeScreenAppIconView iconImageInfoForVariant:requiresCircleShape:]
+ +[SearchUIUtilities isCampoProcess]
+ +[SearchUIUtilities openApplicationOptionsSpotlightSource:]
+ +[SearchUIUtilities openPunchout:presentationSource:]
+ +[SearchUIUtilities openPunchout:presentationSource:completion:]
+ +[SearchUIUtilities openURL:presentationSource:withCompletion:]
+ +[SearchUIUtilities requestClipInstallWithURL:presentationSource:completion:]
+ -[SFAppIconCardSection(SearchUILeadingTrailingSectionModel) searchUILeadingTrailingSectionModel_leadingFractionalWidthForContainerWidth:]
+ -[SFCardSection(SearchUILeadingTrailingSectionModel) searchUILeadingTrailingSectionModel_leadingFractionalWidthForContainerWidth:]
+ -[SearchUIBackgroundColorView currentColorRequestId]
+ -[SearchUIBackgroundColorView setCurrentColorRequestId:]
+ -[SearchUICollectionViewController searchui_contentColumnWidthForContainerWidth:]
+ -[SearchUIColorRequest requestId]
+ -[SearchUIColorRequest setRequestId:]
+ -[SearchUICommandEnvironment presentationSource]
+ -[SearchUICommandEnvironment setPresentationSource:]
+ -[SearchUIMultiResultCollectionView updateVisibleCountForWidthIfNeeded]
+ -[SearchUIResultsViewController frameForChildViewControllers]
+ GCC_except_table105
+ GCC_except_table22
+ _OBJC_IVAR_$_SearchUIBackgroundColorView._currentColorRequestId
+ _OBJC_IVAR_$_SearchUIColorRequest._requestId
+ _OBJC_IVAR_$_SearchUICommandEnvironment._presentationSource
+ _SearchUIAppIconsPerRowForWidth
+ _SearchUISpotlightColumnTopMargin
+ _SearchUISpotlightContentColumnWidth
+ _SearchUISpotlightMaxContentWidth
+ ___35+[SearchUIUtilities isCampoProcess]_block_invoke
+ ___63+[SearchUIUtilities openURL:presentationSource:withCompletion:]_block_invoke
+ ___67-[SearchUIPhotoAssetCache computeObjectsForKeys:completionHandler:]_block_invoke
+ ___67-[SearchUIPhotoAssetCache computeObjectsForKeys:completionHandler:]_block_invoke_2
+ ___77+[SearchUIUtilities requestClipInstallWithURL:presentationSource:completion:]_block_invoke
+ ___block_descriptor_64_e8_32s40bs_e20_v20?0B8"NSError"12ls32l8s40l8
+ ___block_descriptor_65_e8_32s40s48s56r_e44_v16?0"SearchUIResolvedBackgroundColoring"8ls32l8s40l8s48l8r56l8
+ ___block_descriptor_73_e8_32s40s48s56s64r_e5_v8?0ls32l8s40l8s48l8s56l8r64l8
+ _computeObjectsForKeys:completionHandler:.onceToken
+ _computeObjectsForKeys:completionHandler:.queue
+ _isCampoProcess.isCampoProcess
+ _isCampoProcess.onceToken
- +[SearchUIAppIconUtilities idealHorizontalSpacingBetweenAppIconsForContainerWidth:insets:]
- +[SearchUIHomeScreenAppIconView cacheForVariant:requiresCircleShape:]
- +[SearchUIHomeScreenAppIconView cacheKeyForVariant:requiresCircleShape:]
- +[SearchUIUtilities openApplicationOptions]
- -[SearchUIBackgroundColorView currentColorRequest]
- -[SearchUIHomeScreenAppIconView currentIconIsPlaceholder]
- -[SearchUIHomeScreenAppIconView hidePlaceholder:]
- -[SearchUIHomeScreenAppIconView iconImageViewDidChangeContents:forIcon:]
- -[SearchUIHomeScreenAppIconView imageLoadingBehavior]
- -[SearchUIHomeScreenAppIconView placeholderView]
- -[SearchUIHomeScreenAppIconView removePlaceholderAndSetShadowAnimated:]
- -[SearchUIHomeScreenAppIconView setPlaceholderView:]
- -[SearchUIIconImageCache genericImage]
- GCC_except_table103
- GCC_except_table21
- _OBJC_CLASS_$_SBHClockApplicationIcon
- _OBJC_CLASS_$_SBHIconImageCache
- _OBJC_CLASS_$_SearchUIIconImageCache
- _OBJC_IVAR_$_SearchUIHomeScreenAppIconView._placeholderView
- _OBJC_METACLASS_$_SBHIconImageCache
- _OBJC_METACLASS_$_SearchUIIconImageCache
- _SearchUIPlaceholderIconIdentifier
- __OBJC_$_INSTANCE_METHODS_SearchUIIconImageCache
- __OBJC_CLASS_RO_$_SearchUIIconImageCache
- __OBJC_METACLASS_RO_$_SearchUIIconImageCache
- ___43+[SearchUIUtilities openApplicationOptions]_block_invoke
- ___44+[SearchUIUtilities openURL:withCompletion:]_block_invoke
- ___58+[SearchUIUtilities requestClipInstallWithURL:completion:]_block_invoke
- ___69+[SearchUIHomeScreenAppIconView cacheForVariant:requiresCircleShape:]_block_invoke
- ___71-[SearchUIHomeScreenAppIconView removePlaceholderAndSetShadowAnimated:]_block_invoke
- ___76+[SearchUILaunchAppHandler openApplicationWithBundleIdentifier:environment:]_block_invoke_2
- ___block_descriptor_56_e8_32s40bs_e20_v20?0B8"NSError"12ls32l8s40l8
- ___block_descriptor_65_e8_32s40s48s56s_e44_v16?0"SearchUIResolvedBackgroundColoring"8ls32l8s40l8s48l8s56l8
- ___block_descriptor_66_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
- _cacheForVariant:requiresCircleShape:.iconCache
- _cacheForVariant:requiresCircleShape:.onceToken
- _idealHorizontalSpacingBetweenAppIcons.spacing
- _openApplicationOptions.onceToken
- _openApplicationOptions.options
- _openApplicationWithBundleIdentifier:environment:.onceToken
- _openApplicationWithBundleIdentifier:environment:.openApplicationService
CStrings:
+ "Campo"
+ "com.apple.searchui.SearchUIPhotoAssetCache"
- "-%@"
- "Identifier:AppIconButton,AppName:%@"
- "SearchUIIconImageCache"
- "searchUIPlaceholderIcon"
```
