## VideosUICore

> `/System/Library/PrivateFrameworks/VideosUICore.framework/VideosUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f840` | `0x35218` | **`+0x59d8`** |
| `__TEXT.__oslogstring` | `0xe71` | `0x165b` | **`+0x7ea`** |
| `__AUTH_CONST.__cfstring` | `0x5b40` | `0x6240` | **`+0x700`** |
| `__DATA_CONST.__objc_selrefs` | `0x35b8` | `0x3c60` | **`+0x6a8`** |
| `__TEXT.__objc_methlist` | `0x501c` | `0x5604` | **`+0x5e8`** |
| `__AUTH_CONST.__objc_const` | `0x8178` | `0x8658` | **`+0x4e0`** |
| `__TEXT.__cstring` | `0x2f81` | `0x3421` | **`+0x4a0`** |
| `__TEXT.__const` | `0x206` | `0x546` | **`+0x340`** |
| `__DATA_CONST.__const` | `0x1c50` | `0x1ed0` | **`+0x280`** |
| `__TEXT.__unwind_info` | `0xfc8` | `0x1150` | **`+0x188`** |
| `__AUTH_CONST.__const` | `0x580` | `0x6e0` | **`+0x160`** |
| `__TEXT.__gcc_except_tab` | `0x78c` | `0x854` | **`+0xc8`** |
| `__DATA.__bss` | `0x78` | `0x121` | **`+0xa9`** |
| `__DATA.__data` | `0x858` | `0x8f8` | **`+0xa0`** |
| `__DATA_CONST.__objc_catlist` | `0xb0` | `0x128` | **`+0x78`** |
| `__DATA_CONST.__got` | `0x5e8` | `0x640` | **`+0x58`** |
| `__TEXT.__ustring` | `0x6a` | `0x7c` | **`+0x12`** |
| `__DATA_CONST.__objc_superrefs` | `0x1a0` | `0x1a8` | **`+0x8`** |

### Other Changes

```diff

-1138.0.0.0.2
+1143.0.0.0.2

-  Functions: 1716
-  Symbols:   3394
-  CStrings:  856
+  Functions: 1872
+  Symbols:   3676
+  CStrings:  951
Symbols:
+ +[AMSBag(VUIAdditions) vui_defaultBag]
+ +[CAMeshTransform(VideosUI) vuiMeshTransformWithEdges:mirrorPercentage:]
+ +[NSDate(VideosUI) shouldShowLabelForDownloadExpirationDate:]
+ +[NSDate(VideosUI) vui_startOfDateInGMT:]
+ +[NSDistributedNotificationCenter(VideosUI) vui_wasSentByDifferentProcess:]
+ +[NSOperationQueue(VUIAdditions) vuiDefaultQueue]
+ +[NSURL(VideosUICoreAdditions) vui_sortedQueryItemsFromDictionary:]
+ +[UICollectionView(VideosUI) _vui_indexPathsWithIndexSet:andSection:]
+ +[UICollectionView(VideosUICore) collectionViewWithFrame:parentView:collectionViewLayout:]
+ +[UIColor(VideosUI) vui_dynamicColorWithLightColor:darkColor:]
+ +[UIColor(VideosUI) vui_imageBorderColor]
+ +[UIColor(VideosUI) vui_imageHighlightColor]
+ +[UIColor(VideosUI) vui_keyBlueHighlightedColor]
+ +[UIColor(VideosUI) vui_keyColor]
+ +[UIColor(VideosUI) vui_lockupBorderColor]
+ +[UIColor(VideosUI) vui_opacityColorWithType:]
+ +[UIColor(VideosUI) vui_opacityColorWithType:userInterfaceStyle:]
+ +[UIColor(VideosUI) vui_opaqueSeparatorColor]
+ +[UIColor(VideosUI) vui_primaryDynamicBackgroundColor]
+ +[UIColor(VideosUI) vui_primaryTextColor]
+ +[UIColor(VideosUI) vui_progressBarFillColor]
+ +[UIColor(VideosUI) vui_secondaryDynamicBackgroundColor]
+ +[UIColor(VideosUI) vui_secondaryFillColor]
+ +[UIColor(VideosUI) vui_secondaryTextColor]
+ +[UIColor(VideosUI) vui_separatorColor]
+ +[UIColor(VideosUI) vui_systemLightGrayColor]
+ +[UIColor(VideosUI) vui_tertiaryDynamicBackgroundColor]
+ +[UIColor(VideosUI) vui_tertiaryFillColor]
+ +[UIColor(VideosUI) vui_windowBackgroundColor]
+ +[UITableView(VideosUI) _vui_indexPathsWithIndexSet:andSection:]
+ +[UIViewController(VideosUI) _vui_TVLoadingViewControllerClass]
+ -[NSDate(VideosUI) vui_isInTheFuture]
+ -[NSDate(VideosUI) vui_isInThePast]
+ -[NSDistributedNotificationCenter(VideosUI) vui_postNotificationName:object:userInfo:]
+ -[NSNumber(VideosUI) vui_languageAwareDescription]
+ -[NSObject(VideosUI) vui_debounce:object:delay:]
+ -[NSString(VideosUICore) vui_stringWithFirstStrongDirectionalIsolates]
+ -[NSURL(VideosUICoreAdditions) vui_URLByAddingQueryParamWithName:value:]
+ -[NSURL(VideosUICoreAdditions) vui_URLByAddingQueryParamsDictionary:]
+ -[NSURL(VideosUICoreAdditions) vui_URLByRemovingQueryParamWithName:]
+ -[NSURL(VideosUICoreAdditions) vui_containsQueryParamWithName:]
+ -[NSURL(VideosUICoreAdditions) vui_parsedQueryParametersDictionary]
+ -[UICollectionView(VideosUI) _vui_applyChangeSet:inSection:updateDataSourceBlock:applyChangeBlock:shouldWrapInUpdate:completionHandler:]
+ -[UICollectionView(VideosUI) _vui_applyDeleteChange:inSection:applyChangeBlock:]
+ -[UICollectionView(VideosUI) _vui_applyInsertChange:inSection:applyChangeBlock:]
+ -[UICollectionView(VideosUI) _vui_applyItemUpdateChanges:inSection:applyChangeBlock:]
+ -[UICollectionView(VideosUI) _vui_applyMoveChanges:inSection:applyChangeBlock:]
+ -[UICollectionView(VideosUI) _vui_applySectionUpdateChanges:applyChangeBlock:updateDataSourceBlock:]
+ -[UICollectionView(VideosUI) _vui_applyUpdateChanges:inSection:applyChangeBlock:updateDataSourceBlock:]
+ -[UICollectionView(VideosUI) vui_applyChangeSet:completionHandler:]
+ -[UICollectionView(VideosUI) vui_applyChangeSet:inSection:completionHandler:]
+ -[UICollectionView(VideosUI) vui_applyChangeSet:inSection:updateDataSourceBlock:applyChangeBlock:completionHandler:]
+ -[UICollectionView(VideosUI) vui_applyChangeSet:inSection:updateDataSourceBlock:completionHandler:]
+ -[UICollectionView(VideosUICore) _preciseIndexPathsForVisibleItems:]
+ -[UICollectionView(VideosUICore) setVuiContentInsets:]
+ -[UICollectionView(VideosUICore) setVuiContentOffset:]
+ -[UICollectionView(VideosUICore) setVuiContentOffset:animated:]
+ -[UICollectionView(VideosUICore) vuiAdjustedContentInset]
+ -[UICollectionView(VideosUICore) vuiBounds]
+ -[UICollectionView(VideosUICore) vuiContentInsets]
+ -[UICollectionView(VideosUICore) vuiContentOffset]
+ -[UICollectionView(VideosUICore) vuiContentSize]
+ -[UICollectionView(VideosUICore) vuiIndexPathsForVisibleItems]
+ -[UICollectionView(VideosUICore) vuiPreciseIndexPathsForFullyVisibleItems]
+ -[UICollectionView(VideosUICore) vuiPreciseIndexPathsForVisibleItems]
+ -[UICollectionView(VideosUICore) vuiSafeAreaInsets]
+ -[UICollectionView(VideosUICore) vuiSize]
+ -[UICollectionView(VideosUICore) vuiVisibleCells]
+ -[UICollectionView(VideosUICore) vui_cellForItemAtIndexPath:]
+ -[UICollectionView(VideosUICore) vui_dequeueReusableCellWithIdentifier:indexPath:]
+ -[UICollectionView(VideosUICore) vui_dequeueReusableSupplementaryViewOfKind:withReuseIdentifier:forIndexPath:]
+ -[UICollectionView(VideosUICore) vui_indexPathForCell:]
+ -[UICollectionView(VideosUICore) vui_isIndexPathValid:]
+ -[UICollectionView(VideosUICore) vui_registerClass:forCellWithReuseIdentifier:]
+ -[UICollectionView(VideosUICore) vui_registerClass:forSupplementaryViewOfKind:withReuseIdentifier:]
+ -[UICollectionView(VideosUICore) vui_scrollToItemAtIndexPath:atScrollPosition:animated:]
+ -[UICollectionView(VideosUICore) vui_scrollToItemAtIndexPath:atScrollPosition:animated:completionHandler:]
+ -[UICollectionView(VideosUICore) vui_setLayout:]
+ -[UICollectionViewLayout(VideosUICore) vui_layoutFrameForSection:]
+ -[UICollectionViewLayout(VideosUICore) vui_registerClass:forDecorationViewOfKind:]
+ -[UIColor(VideosUI) vui_blendWithColor:percentage:]
+ -[UIImage(VideosUICore) vuiImageByApplyingSymbolConfiguration:]
+ -[UILabel(VideosUI) vui_alignmentInsetsForExpectedWidth:]
+ -[UILabel(VideosUI) vui_heightToBaseline]
+ -[UILabel(VideosUI) vui_textSizeForSize:]
+ -[UINavigationItem(Additions) setStackedSearchBarPlacement]
+ -[UIScene(VideosUI) vui_isNonLightningSecondScreenScene]
+ -[UISpringTimingParameters(VideosUI) vui_initWithDampingRatio:frequencyResponse:]
+ -[UITableView(VideosUI) _vui_applyDeleteChange:inSection:rowAnimation:]
+ -[UITableView(VideosUI) _vui_applyInsertChange:inSection:rowAnimation:]
+ -[UITableView(VideosUI) _vui_applyMoveChanges:inSection:rowAnimation:]
+ -[UITableView(VideosUI) _vui_applyUpdateChanges:inSection:rowAnimation:]
+ -[UITableView(VideosUI) vui_applyChangeSet:completionHandler:]
+ -[UITableView(VideosUI) vui_applyChangeSet:inSection:completionHandler:]
+ -[UITableView(VideosUI) vui_applyChangeSet:inSection:rowAnimation:updateDataSourceBlock:completionHandler:]
+ -[UIView(VideosUI) bottomMarginWithBaselineMargin:]
+ -[UIView(VideosUI) bottomMarginWithBaselineMargin:maximumContentSizeCategory:]
+ -[UIView(VideosUI) setHighlighted:]
+ -[UIView(VideosUI) setHighlighted:animated:withAnimationCoordinator:]
+ -[UIView(VideosUI) setSelected:animated:]
+ -[UIView(VideosUI) setSelected:animated:withAnimationCoordinator:]
+ -[UIView(VideosUI) topMarginWithBaselineMargin:]
+ -[UIView(VideosUI) topMarginWithBaselineMargin:maximumContentSizeCategory:]
+ -[UIView(VideosUI) vui_shouldRecomputeCachedSizeThatFits:previousTargetSize:previousTraitCollection:newTargetSize:]
+ -[UIView(VideosUI) vui_sizeThatFits:layout:]
+ -[UIView(VideosUI) vui_sizeThatFits:layout:withSizeCalculation:]
+ -[UIViewController(VideosUI) vui_ppt_isLoading]
+ -[UIViewController(VideosUI) vui_presentViewController:animated:completion:]
+ -[VUIImage isDecoded]
+ _CGRectContainsRect
+ _CGRectIntersectsRect
+ _NSCalendarIdentifierGregorian
+ _NSClassFromString
+ _NSStringFromPlatformEdgeInsets
+ _NSStringFromUIEdgeInsets
+ _OBJC_CLASS_$_AMSPurchase
+ _OBJC_CLASS_$_CAMeshTransform
+ _OBJC_CLASS_$_CAMutableMeshTransform
+ _OBJC_CLASS_$_NSCalendar
+ _OBJC_CLASS_$_NSDistributedNotificationCenter
+ _OBJC_CLASS_$_NSIndexPath
+ _OBJC_CLASS_$_NSLocale
+ _OBJC_CLASS_$_NSTimeZone
+ _OBJC_CLASS_$_NSURLQueryItem
+ _OBJC_CLASS_$_UIActivityIndicatorView
+ _OBJC_CLASS_$_UICollectionView
+ _OBJC_CLASS_$_UICollectionViewLayout
+ _OBJC_CLASS_$_UILabel
+ _OBJC_CLASS_$_UINavigationItem
+ _OBJC_CLASS_$_UIScene
+ _OBJC_CLASS_$_UISpringTimingParameters
+ _OBJC_CLASS_$_UITableView
+ _OBJC_EHTYPE_$_NSException
+ _OBJC_METACLASS_$_UICollectionView
+ _TVAppProfileName
+ _TVAppProfileVersion
+ _VUICollectionViewApplyChangeSetSectionIndexSections
+ _VUIDefaultLogObject
+ _VUIDefaultLogObject.logger
+ _VUIDefaultLogObject.onceToken
+ _VUIPrewarmNetworkSignpostObject
+ _VUIPrewarmNetworkSignpostObject.logger
+ _VUIPrewarmNetworkSignpostObject.onceToken
+ _VUISignpostLogObject
+ _VUISignpostLogObject.logger
+ _VUISignpostLogObject.onceToken
+ _VUISystemCompactRoundedFontFamily
+ _VUISystemDefaultFontFamily
+ _VUISystemRoundedFontFamily
+ _VUIURLQueryParamNameBingeWatching
+ _VUIURLQueryParamNameGroupActivityDay
+ _VUIURLQueryParamNamePostPlayType
+ _VUIURLQueryParamNameStartOver
+ _VUIURLQueryParamValueId
+ _VUIURLQueryParamValueNextEpisodeDifferentSeason
+ _VUIURLQueryParamValueNextEpisodeSameSeason
+ _VUIURLQueryParamValueOther
+ _VUIURLQueryParamValueTrue
+ _VUIURLRequestHeaderXForwardedFor
+ _VUIVPAFLogObject
+ _VUIVPAFLogObject.logger
+ _VUIVPAFLogObject.onceToken
+ __OBJC_$_CATEGORY_AMSBag_$_VUIAdditions
+ __OBJC_$_CATEGORY_AMSPurchase_$_VideosUI
+ __OBJC_$_CATEGORY_CAMeshTransform_$_VideosUI
+ __OBJC_$_CATEGORY_CLASS_METHODS_AMSBag_$_VUIAdditions
+ __OBJC_$_CATEGORY_CLASS_METHODS_CAMeshTransform_$_VideosUI
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSDate_$_VideosUI
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSDistributedNotificationCenter_$_VideosUI
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSOperationQueue_$_VUIAdditions
+ __OBJC_$_CATEGORY_CLASS_METHODS_UITableView_$_VideosUI
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSDate_$_VideosUI
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSDistributedNotificationCenter_$_VideosUI
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSNumber_$_VideosUI
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSObject_$_VideosUI
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_UICollectionViewLayout_$_VideosUICore
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_UILabel_$_VideosUI
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_UINavigationItem_$_Additions
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_UIScene_$_VideosUI
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_UISpringTimingParameters_$_VideosUI
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_UITableView_$_VideosUI
+ __OBJC_$_CATEGORY_NSDate_$_VideosUI
+ __OBJC_$_CATEGORY_NSDistributedNotificationCenter_$_VideosUI
+ __OBJC_$_CATEGORY_NSNumber_$_VideosUI
+ __OBJC_$_CATEGORY_NSObject_$_VideosUI
+ __OBJC_$_CATEGORY_NSOperationQueue_$_VUIAdditions
+ __OBJC_$_CATEGORY_UICollectionViewLayout_$_VideosUICore
+ __OBJC_$_CATEGORY_UICollectionView_$_VideosUICore
+ __OBJC_$_CATEGORY_UILabel_$_VideosUI
+ __OBJC_$_CATEGORY_UINavigationItem_$_Additions
+ __OBJC_$_CATEGORY_UIScene_$_VideosUI
+ __OBJC_$_CATEGORY_UISpringTimingParameters_$_VideosUI
+ __OBJC_$_CATEGORY_UITableView_$_VideosUI
+ __OBJC_$_CLASS_METHODS_UICollectionView(VideosUICore|VideosUI)
+ __OBJC_$_CLASS_METHODS_UIColor(VideosUICore|VideosUI)
+ __OBJC_$_CLASS_METHODS_UIViewController(VideosUICore|VUIControllerPresenter|VideosUI)
+ __OBJC_$_INSTANCE_METHODS_UICollectionView(VideosUICore|VideosUI)
+ __OBJC_$_INSTANCE_METHODS_UIColor(VideosUICore|VideosUI)
+ __OBJC_$_INSTANCE_METHODS_UIView(VideosUICore|VideosUI)
+ __OBJC_$_INSTANCE_METHODS_UIViewController(VideosUICore|VUIControllerPresenter|VideosUI)
+ __OBJC_$_PROP_LIST_AMSPurchase_$_VideosUI
+ __OBJC_$_PROP_LIST_NSDate_$_VideosUI
+ __OBJC_$_PROP_LIST_UICollectionView_$_VideosUICore
+ __OBJC_$_PROP_LIST_UIScene_$_VideosUI
+ __OBJC_CLASS_PROTOCOLS_$_UIViewController(VideosUICore|VUIControllerPresenter|VideosUI)
+ ___107-[UITableView(VideosUI) vui_applyChangeSet:inSection:rowAnimation:updateDataSourceBlock:completionHandler:]_block_invoke
+ ___107-[UITableView(VideosUI) vui_applyChangeSet:inSection:rowAnimation:updateDataSourceBlock:completionHandler:]_block_invoke_2
+ ___136-[UICollectionView(VideosUI) _vui_applyChangeSet:inSection:updateDataSourceBlock:applyChangeBlock:shouldWrapInUpdate:completionHandler:]_block_invoke
+ ___136-[UICollectionView(VideosUI) _vui_applyChangeSet:inSection:updateDataSourceBlock:applyChangeBlock:shouldWrapInUpdate:completionHandler:]_block_invoke_2
+ ___41+[UIColor(VideosUI) vui_imageBorderColor]_block_invoke
+ ___41-[UILabel(VideosUI) vui_textSizeForSize:]_block_invoke
+ ___42+[UIColor(VideosUI) vui_lockupBorderColor]_block_invoke
+ ___44+[UIColor(VideosUI) vui_imageHighlightColor]_block_invoke
+ ___44-[UIView(VideosUI) vui_sizeThatFits:layout:]_block_invoke
+ ___45+[UIColor(VideosUI) vui_progressBarFillColor]_block_invoke
+ ___46+[UIColor(VideosUI) vui_opacityColorWithType:]_block_invoke
+ ___47-[UIViewController(VideosUI) vui_ppt_isLoading]_block_invoke
+ ___47-[UIViewController(VideosUI) vui_ppt_isLoading]_block_invoke_2
+ ___49+[NSOperationQueue(VUIAdditions) vuiDefaultQueue]_block_invoke
+ ___57-[UILabel(VideosUI) vui_alignmentInsetsForExpectedWidth:]_block_invoke
+ ___57-[UILabel(VideosUI) vui_alignmentInsetsForExpectedWidth:]_block_invoke_2
+ ___62+[UIColor(VideosUI) vui_dynamicColorWithLightColor:darkColor:]_block_invoke
+ ___63+[UIViewController(VideosUI) _vui_TVLoadingViewControllerClass]_block_invoke
+ ___64+[UITableView(VideosUI) _vui_indexPathsWithIndexSet:andSection:]_block_invoke
+ ___68-[UICollectionView(VideosUICore) _preciseIndexPathsForVisibleItems:]_block_invoke
+ ___69+[UICollectionView(VideosUI) _vui_indexPathsWithIndexSet:andSection:]_block_invoke
+ ___76-[UIViewController(VideosUI) vui_presentViewController:animated:completion:]_block_invoke
+ ___VUIDefaultLogObject_block_invoke
+ ___VUIPrewarmNetworkSignpostObject_block_invoke
+ ___VUISignpostLogObject_block_invoke
+ ___VUIVPAFLogObject_block_invoke
+ ___block_descriptor_32_e37_q24?0"NSIndexPath"8"NSIndexPath"16l
+ ___block_descriptor_40_e8_32bs_e35_v40?0"UIFont"8{_NSRange=QQ}16^B32ls32l8
+ ___block_descriptor_40_e8_32r_e23_v32?0"UIView"8Q16^B24lr32l8
+ ___block_descriptor_40_e8_32s_e28_{CGSize=dd}24?0{CGSize=dd}8ls32l8
+ ___block_descriptor_48_e36_"UIColor"16?0"UITraitCollection"8l
+ ___block_descriptor_48_e8_32r40r_e16_v16?0"UIFont"8lr32l8r40l8
+ ___block_descriptor_48_e8_32r_e23_v32?0"UIView"8Q16^B24lr32l8
+ ___block_descriptor_48_e8_32s40s_e36_"UIColor"16?0"UITraitCollection"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s_e12_v24?0Q8^B16ls32l8
+ ___block_descriptor_72_e8_32s40s48bs_e5_v8?0ls48l8s32l8s40l8
+ ___block_descriptor_72_e8_32s40s48bs_e8_v12?0B8ls32l8s40l8s48l8
+ ___block_descriptor_73_e8_32s40s48bs56bs_e5_v8?0ls48l8s32l8s40l8s56l8
+ ___block_descriptor_81_e8_32s40s48bs56bs64bs_e8_v12?0B8ls32l8s40l8s48l8s56l8s64l8
+ ___isPerfLoggingEnabled_block_invoke
+ __vui_TVLoadingViewControllerClass.__loadingViewClass
+ __vui_TVLoadingViewControllerClass.__onceToken
+ _getpid
+ _isPerfLoggingEnabled
+ _isPerfLoggingEnabled.isPerfLoggingEnabled
+ _isPerfLoggingEnabled.onceToken
+ _kCADepthNormalizationNone
+ _kVUIBagAcknowledgePrivacyLink
+ _kVUIBagKeyAddFundsURL
+ _kVUIBagKeyGetWatchListSettings
+ _kVUIBagKeyManageSubscriptionsURL
+ _kVUIBagKeyMetrics
+ _kVUIBagKeyModifyAccountURL
+ _kVUIBagKeyPushNotificationsEnvironment
+ _kVUIBagKeyRedeemCodeURL
+ _kVUIBagKeySignUpURL
+ _kVUIBagKeyUVSearchEnabledNotificationTypes
+ _kVUIBagKeyUVSearchInitConfigGetURLLengthLimit
+ _kVUIBagKeyUVSearchLocationEnabled
+ _kVUIBagKeyUVSearchMaxLocalSettingsAgeSeconds
+ _kVUIBagKeyUVSearchNowPlayingEnabled
+ _kVUIBagKeyUVSearchNowSportsEnabled
+ _kVUIBagKeyUVSearchRoutesInitConfigPath
+ _kVUIBagKeyUVSearchUtsApiBaseURL
+ _kVUIBagKeyUpdateWatchListSettings
+ _kVUIBagPlaybackErrorMessageURL
+ _kVUIBagTVAppJetpackURL
+ _memcpy
+ _notify_post
+ _objc_begin_catch
+ _objc_end_catch
+ _vuiDefaultQueue._once
+ _vuiDefaultQueue._vuiDefaultQueue
+ _vui_imageBorderColor.__imageBorderColor
+ _vui_imageBorderColor.onceToken
+ _vui_imageHighlightColor.__imageHighlightColor
+ _vui_imageHighlightColor.onceToken
+ _vui_lockupBorderColor.__imageBorderColor
+ _vui_lockupBorderColor.onceToken
+ _vui_progressBarFillColor.__fillColor
+ _vui_progressBarFillColor.onceToken
- __OBJC_$_CATEGORY_INSTANCE_METHODS_UIColor_$_VideosUICore
- __OBJC_$_CATEGORY_INSTANCE_METHODS_UIView_$_VideosUICore
- __OBJC_$_INSTANCE_METHODS_UIViewController(VideosUICore|VUIControllerPresenter)
- __OBJC_CLASS_PROTOCOLS_$_UIViewController(VideosUICore|VUIControllerPresenter)
CStrings:
+ "&"
+ "<none>"
+ "="
+ "@\"UIColor\"16@?0@\"UITraitCollection\"8"
+ "AddFundsUrl"
+ "Applying Delete Change To Section: %lu. Delete Items At: %@"
+ "Applying Delete Change. Deleting Rows At: %@"
+ "Applying Delete Change: Deleting Section At: %lu"
+ "Applying Delete Change: Deleting Sections At: %@"
+ "Applying Insert Change To Section: %lu. Insert Items At: %@"
+ "Applying Insert Change. Inserting Rows At: %@"
+ "Applying Insert Change: Inserting Section At: %lu"
+ "Applying Insert Change: Inserting Sections At: %@"
+ "Applying Move Change To Item %@ to %@"
+ "Applying Move Change To Row %@ to %@"
+ "Applying Move Change To Section %lu to %lu"
+ "Applying Update Change To Section: %@. Reloading Items At: %@"
+ "Applying Update Change To Section: %@. Reloading Rows At: %@"
+ "Applying Update Change: Updating Sections At: %@"
+ "Found window scene with display name %@"
+ "GMT"
+ "LogLevel"
+ "LoggingPerf"
+ "Prewarm"
+ "SFCompactRounded"
+ "SFPro"
+ "SFRounded"
+ "Signpost"
+ "TVOut"
+ "URLImageLoader:: Adding request %@ URL %@"
+ "URLImageLoader:: Canceling request %@ URL %@"
+ "URLImageLoader:: Canceling task %@ URL %@"
+ "URLImageLoader:: Finished loading task %@ url %@ statusCode=%ld bytes=%lu image=%@"
+ "URLImageLoader:: Finished loading task %@ url %@ with NO DATA — statusCode=%ld receivedData=%@"
+ "URLImageLoader:: Finished task %@ url %@ with error [%@]"
+ "URLImageLoader:: Loading task %@ URL %@"
+ "URLImageLoader:: cannot create key for object of type [%@]"
+ "URLImageLoader:: cannot load image for object of type [%@]"
+ "URLImageLoader:: didComplete url=%@ statusCode=%ld receivedDataLen=%lu finalError=%@ resultImage=%@ loadIDsCount=%lu"
+ "URLImageLoader:: didCompleteWithError DROPPED url=%@ task superseded (taskOptions[Key]=%@ vs task=%@). error=%@ — registered completions (if any) NOT fired"
+ "URLImageLoader:: didCompleteWithError DROPPED url=%@ taskOptions is nil (task already cancelled/cleaned up). error=%@ — registered completions (if any) NOT fired"
+ "URLImageLoader:: didReceiveResponse url=%@ status=%ld"
+ "URLImageLoader:: invalid NSURLSessionTask source type"
+ "URLImageLoader:: returned a non-NSHTTPURLResponse with url [%@]"
+ "Unable to add query param %@ to URL %@"
+ "VPAF"
+ "VUIImageProxy::(%p) Failed to create image from file path %@"
+ "VUIImageProxy::(%p) _callCompletionHandler: object=%@ image=%@ error=%@ finished=%d completionHandler=%@"
+ "VUIImageProxy::(%p) _completeImageLoad: object=%@ image=%@ imagePath=%@ error=%@"
+ "VUIImageProxy::(%p) cancel: cancelling. object=%@ requestToken=%@"
+ "VUIImageProxy::(%p) cancel: not loading, no-op. object=%@"
+ "VUIImageProxy::(%p) load completion: SILENT NO-OP requestToken=%@ completionRequestToken=%@"
+ "VUIImageProxy::(%p) load: already loading, returning early. object=%@"
+ "VUIImageProxy::(%p) load: starting. object=%@ requestToken=%@"
+ "VUIImageView::(%p) setImageProxy: cancelling old in-flight proxy. oldProxy=%p newProxy=%p oldURL=%@ newURL=%@"
+ "X-Forwarded-For"
+ "_TVLoadingViewController"
+ "bingeWatching"
+ "com.apple.videosui.defaultqueue"
+ "disablePreActionSharesData"
+ "disablePreviewItemSharesData"
+ "disableSharesActionDataSource"
+ "get-watchlist-settings"
+ "groupActivityDay"
+ "id"
+ "manageSubscriptionsUrl"
+ "metrics"
+ "modifyAccount"
+ "nextEpisodeDifferentSeason"
+ "nextEpisodeSameSeason"
+ "nil"
+ "non-nil"
+ "other"
+ "perfLoggingEnabled"
+ "postPlayType"
+ "preActionSharesData"
+ "previewItemSharesData"
+ "privacyAcknowledgementUrl"
+ "push-notifications/environment"
+ "q24@?0@\"NSIndexPath\"8@\"NSIndexPath\"16"
+ "redeemCodeLanding"
+ "sendingPID"
+ "sharesActionDataSource"
+ "signup"
+ "startOver"
+ "tr-tv"
+ "true"
+ "tv-app-jetpack-url"
+ "tv-app-playback-error-message-url"
+ "update-watchlist-settings"
+ "uvSearch/enabled-notification-types"
+ "uvSearch/init-config-get-url-length-limit"
+ "uvSearch/locationEnabled"
+ "uvSearch/max-local-settings-age-seconds"
+ "uvSearch/nowplaying-enabled"
+ "uvSearch/routes/init-config-path"
+ "uvSearch/sports-enabled"
+ "uvSearch/uts-api-base-url"
+ "v12@?0B8"
+ "v16@?0@\"UIFont\"8"
+ "v24@?0Q8^B16"
+ "v32@?0@\"UIView\"8Q16^B24"
+ "v40@?0@\"UIFont\"8{_NSRange=QQ}16^B32"
+ "{CGSize=dd}24@?0{CGSize=dd}8"
+ "\u200e"
+ "\u200f"
+ "\u2068%@\u2069"
- "Failed to create image from file path %@"
- "URLImageLoader Adding request %@ URL %@"
- "URLImageLoader Canceling request %@ URL %@"
- "URLImageLoader Canceling task %@ URL %@"
- "URLImageLoader Finished loading task %@ url %@"
- "URLImageLoader Finished loading task %@ url %@ with no data"
- "URLImageLoader Finished task %@ url %@ with error [%@]"
- "URLImageLoader Loading task %@ URL %@"
- "URLImageLoader cannot create key for object of type [%@]"
- "URLImageLoader cannot load image for object of type [%@]"
- "URLImageLoader invalid NSURLSessionTask source type"
- "URLImageLoader returned a non-NSHTTPURLResponse with url [%@]"
```
