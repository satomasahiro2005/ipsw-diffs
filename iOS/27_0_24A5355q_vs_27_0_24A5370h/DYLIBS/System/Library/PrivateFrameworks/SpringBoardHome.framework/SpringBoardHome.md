## SpringBoardHome

> `/System/Library/PrivateFrameworks/SpringBoardHome.framework/SpringBoardHome`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3890c0` | `0x38987c` | **`+0x7bc`** |
| `__TEXT.__unwind_info` | `0xf670` | `0xf8d8` | **`+0x268`** |
| `__AUTH_CONST.__const` | `0x7728` | `0x7538` | **`-0x1f0`** |
| `__TEXT.__oslogstring` | `0xea80` | `0xeb20` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x59188` | `0x59108` | **`-0x80`** |
| `__DATA.__data` | `0x9758` | `0x96d8` | **`-0x80`** |
| `__TEXT.__cstring` | `0x18943` | `0x188e3` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x9d90` | `0x9d40` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0x4308` | `0x42c4` | **`-0x44`** |
| `__TEXT.__swift5_reflstr` | `0xaca` | `0xafa` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x65c8` | `0x65a0` | **`-0x28`** |
| `__TEXT.__swift5_capture` | `0x15dc` | `0x15b8` | **`-0x24`** |
| `__AUTH_CONST.__cfstring` | `0x16ca0` | `0x16c80` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cca8` | `0x1cc88` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1cf8` | `0x1d10` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0xbc8` | `0xbe0` | **`+0x18`** |
| `__AUTH.__data` | `0xc68` | `0xc78` | **`+0x10`** |
| `__DATA.__bss` | `0x3a88` | `0x3a98` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x24c0` | `0x24d0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xe90` | `0xea0` | **`+0x10`** |
| `__TEXT.__const` | `0x7fc4` | `0x7fd4` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3edbc` | `0x3edac` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x3dec` | `0x3de0` | **`-0xc`** |

### Other Changes

```diff

-214.0.4.0.0
+217.0.101.0.0

-  Functions: 24697
-  Symbols:   33665
-  CStrings:  4541
+  Functions: 24673
+  Symbols:   33671
+  CStrings:  4540
Symbols:
+ +[SBHClockApplicationIconImageView precacheDataWithIconImageInfo:appearance:priority:]
+ +[SBHIconImageCache memoryPoolBitDepth]
+ +[SBHIconImageCache memoryPoolSlotLengthForIconImageInfo:]
+ +[SBHIconImageCache waitForCachingActivityToComplete]
+ +[SBHomeScreenButton hasCustomDisabledAppearance]
+ +[SBTitledHomeScreenButton hasCustomDisabledAppearance]
+ -[SBFolderView _updateIconListFramesAnimated:previousScrollViewContentSize:]
+ -[SBFolderView layoutPagesWithAnimationType:options:previousScrollViewContentSize:]
+ -[SBHIconImageCache cacheImageForIcon:compatibleWithTraitCollection:priority:reason:options:completionHandler:]
+ -[SBHIconImageCache dealloc]
+ -[SBHIconImageCache downscaledImageForMemoryPooling:]
+ -[SBHIconImageVariantCache removeFromActiveRequestsIfPresent:]
+ -[SBHIconStateArchiver archivableObjectForFixedIconLocations:inList:]
+ -[SBHIconStateUnarchiver fixedIconLocationsForUnarchivedObject:inList:]
+ -[SBHIconStylePreviewManager configurationMiniIconImageInfo]
+ -[SBHIconStylePreviewManager setTintableMiniIcons:]
+ -[SBHIconStylePreviewManager tintableMiniIcons]
+ -[SBHLibrarySearchController _shouldPinFeatherBlurToScreenPosition]
+ -[SBHLibrarySearchController noteFeatherBlurPinningDidChange]
+ -[SBHLibrarySearchController searchBarShouldPinFeatherBlurToScreenPosition:]
+ -[SBHLibraryViewController librarySearchControllerShouldPinFeatherBlurToScreenPosition:]
+ -[SBHLibraryViewController noteFeatherBlurPinningDidChange]
+ -[SBHRedoButton configureMetrics:forScreenType:]
+ -[SBHUndoButton configureMetrics:forScreenType:]
+ -[SBIcon loadIconLayerInBackgroundWithLocalImageCacheIfPossibleWithInfo:traitCollection:reason:context:options:priority:placeholderHandler:completionHandler:]
+ -[SBIconListModel _rotatedIconListModelFromList:potentialFixedIconLocations:sourceGridCellInfoOptions:mutationOptions:alwaysUseRotatedListModelClass:]
+ -[SBIconListModel _rotatedLayoutFromList:potentialFixedIconLocations:sourceGridCellInfoOptions:mutationOptions:iconOrder:]
+ -[SBIconListModel combinedLayoutDescription]
+ -[SBIconListModel fixedIcons]
+ -[SBIconListModel setFixedLocation:forIcon:gridCellInfoOptions:mutationOptions:]
+ -[SBIconListView isGridCellIndexVisible:]
+ -[SBIconProgressView didMoveToWindow]
+ -[SBRootFolderView editUndoRedoButtonsAlpha]
+ -[SBRootFolderView effectiveEditButtonAlpha]
+ -[SBRootFolderView effectiveUndoRedoButtonsAlpha]
+ -[SBRootFolderView setEditUndoRedoButtonsAlpha:]
+ -[SBRootFolderView shouldShowUndoRedoButtons]
+ -[SBRootFolderView updateTitledButtonsAlphaAnimated:]
+ -[SBRootFolderView validateUndoRedoButtonsAnimated:]
+ -[SBRotatedIconListModel needsRebuild]
+ -[SBRotatedIconListModel setNeedsRebuild:]
+ -[SBTitledHomeScreenButton setEnabled:]
+ GCC_except_table113
+ GCC_except_table147
+ GCC_except_table186
+ GCC_except_table198
+ GCC_except_table200
+ GCC_except_table224
+ GCC_except_table249
+ GCC_except_table271
+ GCC_except_table274
+ GCC_except_table283
+ GCC_except_table294
+ GCC_except_table296
+ GCC_except_table363
+ GCC_except_table405
+ GCC_except_table424
+ GCC_except_table437
+ GCC_except_table439
+ GCC_except_table444
+ GCC_except_table454
+ GCC_except_table459
+ GCC_except_table46
+ GCC_except_table463
+ GCC_except_table477
+ GCC_except_table500
+ GCC_except_table511
+ GCC_except_table534
+ GCC_except_table536
+ GCC_except_table54
+ GCC_except_table572
+ GCC_except_table577
+ GCC_except_table601
+ GCC_except_table625
+ GCC_except_table82
+ GCC_except_table84
+ GCC_except_table93
+ _CGBitmapGetAlignedBytesPerRow
+ _CGContextDrawImage
+ _CGImageCreateCopyWithContentHeadroom
+ _CGImageGetContentHeadroom
+ _NSDefaultRunLoopMode
+ _OBJC_IVAR_$_SBHIconStylePreviewManager._tintableMiniIcons
+ _OBJC_IVAR_$_SBRootFolderView._editUndoRedoButtonsAlpha
+ _OBJC_IVAR_$_SBRotatedIconListModel._needsRebuild
+ _OUTLINED_FUNCTION_24
+ _OUTLINED_FUNCTION_25
+ _SBHIconImageCacheOptionsForIconImageOptions
+ _SBHIconImageCachePriorityForIconImageLoadPriority
+ _SBIconImageLoadPriorityForIconImageCachePriority
+ _SBIconLocationEqualToIconLocation
+ _SBIconLocationEqualToIconLocationFuzzy
+ __OBJC_$_CLASS_METHODS_SBHomeScreenButton
+ __OBJC_$_CLASS_METHODS_SBTitledHomeScreenButton
+ __SBHPLKLegibilityDescriptorForStyleWithForegroundColors
+ ___158-[SBIcon loadIconLayerInBackgroundWithLocalImageCacheIfPossibleWithInfo:traitCollection:reason:context:options:priority:placeholderHandler:completionHandler:]_block_invoke
+ ___39-[SBTitledHomeScreenButton setEnabled:]_block_invoke
+ ___43-[SBHIconManager _precacheDataForRootIcons]_block_invoke_2
+ ___44-[SBHIconManager undoChangeWithPreparation:]_block_invoke_3
+ ___53+[SBHIconImageCache waitForCachingActivityToComplete]_block_invoke
+ ___53-[SBRootFolderView updateTitledButtonsAlphaAnimated:]_block_invoke
+ ___56-[SBIconListModel hasFixedIconInGridRange:gridCellInfo:]_block_invoke
+ ___59-[SBIcon loadingIconLayerWithInfo:traitCollection:options:]_block_invoke
+ ___59-[SBIcon loadingIconLayerWithInfo:traitCollection:options:]_block_invoke_2
+ ___71-[SBHIconStateUnarchiver fixedIconLocationsForUnarchivedObject:inList:]_block_invoke
+ ___76-[SBFolderView _updateIconListFramesAnimated:previousScrollViewContentSize:]_block_invoke
+ ___76-[SBFolderView _updateIconListFramesAnimated:previousScrollViewContentSize:]_block_invoke_2
+ ___76-[SBFolderView _updateIconListFramesAnimated:previousScrollViewContentSize:]_block_invoke_3
+ ___76-[SBFolderView _updateIconListFramesAnimated:previousScrollViewContentSize:]_block_invoke_4
+ ___76-[SBFolderView _updateIconListFramesAnimated:previousScrollViewContentSize:]_block_invoke_5
+ ___76-[SBFolderView _updateIconListFramesAnimated:previousScrollViewContentSize:]_block_invoke_6
+ ___76-[SBIconListModel swapFixedIconLocationForReplacedIcon:withReplacementIcon:]_block_invoke
+ ___block_descriptor_144_e8_32s40s48s56s64s72s80bs88bs_e45_v16?0"<SBHIconImageCacheResultDescribing>"8ls32l8s40l8s48l8s56l8s80l8s64l8s72l8s88l8
+ ___block_descriptor_57_e8_32bs40r48r_e28_v24?0"SBIconListView"8^B16lr40l8s32l8r48l8
+ ___block_descriptor_65_e8_32s40bs48r_e27_v32?0"SBIconView"8Q16^B24ls32l8s40l8r48l8
+ ___swift_memcpy96_8
+ _dispatch_semaphore_create
+ _dispatch_semaphore_signal
+ _dispatch_semaphore_wait
+ _getPLKLegibilityForegroundContentDescriptorClass
+ _kCGColorSpaceExtendedLinearSRGB
+ _loadingIconLayerWithInfo:traitCollection:options:.cache
+ _objc_retain_x13
- +[SBHClockApplicationIconImageView precacheDataWithIconImageInfo:]
- +[SBHClockApplicationIconImageView precacheDataWithIconImageInfo:appearance:]
- +[SBHClockApplicationIconImageView precacheDataWithIconImageInfo:appearance:options:]
- +[SBHIconImageCache canFallBackToLightImageForImageAppearance:]
- +[SBHIconImageCache overlayImageWithInfo:]
- +[SBHIconImageCache tintingBackgroundImageWithInfo:]
- +[SBHIconImageCache unmaskedOverlayImageWithInfo:]
- -[SBFloatyFolderView _didAddIconListView:]
- -[SBFolderController scrollingLightUpdatesAssertion]
- -[SBFolderController setScrollingLightUpdatesAssertion:]
- -[SBFolderIconImageView updateOngoingAnimationState]
- -[SBFolderView _updateIconListFramesAnimated:]
- -[SBHIconImageCache _cacheKeyForIcon:]
- -[SBHIconImageCache _iconImageOfSize:scale:failGracefully:drawing:]
- -[SBHIconImageCache memoryMappedIconImageForIconImage:icon:]
- -[SBHIconImageCache memoryMappedIconImageOfSize:scale:withDrawing:]
- -[SBHIconImageCache notifyObserversOfUnmaskedUpdateForIcon:]
- -[SBHIconImageCache overlayImage]
- -[SBHIconImageCache tintingBackgroundImage]
- -[SBHIconImageCache unmaskedOverlayImage]
- -[SBHIconImageCacheRequest copyWithZone:]
- -[SBHIconImageCacheRequest init]
- -[SBHIconImageVariantCache _canPoolImageForIcon:]
- -[SBHIconImageVariantCache _iconImageOfSize:scale:failGracefully:drawing:]
- -[SBHIconImageVariantCache addCachedIcon:]
- -[SBHIconImageVariantCache iconImagesMemoryPool]
- -[SBHIconImageVariantCache memoryMappedIconImageForIconImage:icon:]
- -[SBHIconImageVariantCache memoryMappedIconImageOfSize:scale:withDrawing:]
- -[SBHIconImageVariantCache removeCachedIcon:]
- -[SBHIconManager contentHiddenPauseLightAngleUpdatesAssertion]
- -[SBHIconManager performanceFlagDisableLightAngleUpdatesAssertion]
- -[SBHIconManager setContentHiddenPauseLightAngleUpdatesAssertion:]
- -[SBHIconManager setPerformanceFlagDisableLightAngleUpdatesAssertion:]
- -[SBHIconStateUnarchiver _sanitizedFixedIconLocationsFromDictionary:iconIdentifiers:]
- -[SBIcon locallyCacheIconImage:imageInfo:traitCollection:context:options:]
- -[SBIconImageView areLightAngleUpdatesAllowed]
- -[SBIconImageView beginLightAngleUpdatesIfAllowed]
- -[SBIconImageView beginLightAngleUpdates]
- -[SBIconImageView lightSourceManager]
- -[SBIconImageView pauseLightAngleUpdatesForIconLayer:]
- -[SBIconImageView pauseLightAngleUpdates]
- -[SBIconListModel _rotatedIconListModelFromList:sourceGridCellInfoOptions:mutationOptions:alwaysUseRotatedListModelClass:]
- -[SBIconListModel _rotatedLayoutFromList:sourceGridCellInfoOptions:mutationOptions:iconOrder:]
- -[SBIconListModel hasFixedIconsInGridRange:gridCellInfo:]
- GCC_except_table111
- GCC_except_table142
- GCC_except_table194
- GCC_except_table199
- GCC_except_table206
- GCC_except_table217
- GCC_except_table252
- GCC_except_table270
- GCC_except_table273
- GCC_except_table281
- GCC_except_table289
- GCC_except_table362
- GCC_except_table387
- GCC_except_table406
- GCC_except_table423
- GCC_except_table435
- GCC_except_table438
- GCC_except_table44
- GCC_except_table443
- GCC_except_table460
- GCC_except_table462
- GCC_except_table468
- GCC_except_table472
- GCC_except_table476
- GCC_except_table503
- GCC_except_table514
- GCC_except_table537
- GCC_except_table539
- GCC_except_table571
- GCC_except_table576
- GCC_except_table624
- GCC_except_table628
- GCC_except_table656
- GCC_except_table77
- _CGColorSpaceCreateDeviceRGB
- _CGContextClear
- _OBJC_IVAR_$_SBFolderController._scrollingLightUpdatesAssertion
- _OBJC_IVAR_$_SBHIconImageCache._overlayImage
- _OBJC_IVAR_$_SBHIconImageCache._tintingBackgroundImage
- _OBJC_IVAR_$_SBHIconImageCache._unmaskedOverlayImage
- _OBJC_IVAR_$_SBHIconManager._contentHiddenPauseLightAngleUpdatesAssertion
- _OBJC_IVAR_$_SBHIconManager._performanceFlagDisableLightAngleUpdatesAssertion
- ___189+[SBIconListLayoutEngine layOutIconsPrioritizedByGridArea:inGridCellInfo:gridSize:gridSizeClassSizes:iconLayoutBehavior:referenceIconOrder:referenceGridCellInfo:fixedIconLocations:options:]_block_invoke_5
- ___189+[SBIconListLayoutEngine layOutIconsPrioritizedByGridArea:inGridCellInfo:gridSize:gridSizeClassSizes:iconLayoutBehavior:referenceIconOrder:referenceGridCellInfo:fixedIconLocations:options:]_block_invoke_6
- ___25-[SBHIconManager dealloc]_block_invoke
- ___33-[SBHIconImageCache overlayImage]_block_invoke
- ___35-[SBIconListModel areAllIconsFixed]_block_invoke
- ___35-[SBIconListModel areAllIconsFixed]_block_invoke_2
- ___41-[SBHIconImageCache unmaskedOverlayImage]_block_invoke
- ___46-[SBFolderView _updateIconListFramesAnimated:]_block_invoke
- ___46-[SBFolderView _updateIconListFramesAnimated:]_block_invoke_2
- ___46-[SBFolderView _updateIconListFramesAnimated:]_block_invoke_3
- ___46-[SBFolderView _updateIconListFramesAnimated:]_block_invoke_4
- ___46-[SBFolderView _updateIconListFramesAnimated:]_block_invoke_5
- ___46-[SBFolderView _updateIconListFramesAnimated:]_block_invoke_6
- ___48-[SBIconListModel setFixedIconLocationBehavior:]_block_invoke
- ___49-[SBIconListModel enumerateFixedIconsUsingBlock:]_block_invoke
- ___49-[SBIconListModel setFixedIconLocations:options:]_block_invoke
- ___50+[SBHIconImageCache unmaskedOverlayImageWithInfo:]_block_invoke
- ___54-[SBHIconManager supportedGridSizeClassesForIconView:]_block_invoke
- ___55-[SBFolderIconImageView fulfillGridViewForPageElement:]_block_invoke
- ___57-[SBIconListModel hasFixedIconsInGridRange:gridCellInfo:]_block_invoke
- ___74-[SBIcon locallyCacheIconImage:imageInfo:traitCollection:context:options:]_block_invoke
- ___85-[SBHIconStateUnarchiver _sanitizedFixedIconLocationsFromDictionary:iconIdentifiers:]_block_invoke
- ___block_descriptor_40_e8_32s_e30_v24?0"SBHIconLayerView"8^B16ls32l8
- ___block_descriptor_48_e8_32s40bs_e35_v32?0"NSString"8"NSNumber"16^B24ls32l8s40l8
- ___block_descriptor_56_e8_32s40s_e35_v32?0"NSString"8"NSNumber"16^B24ls32l8s40l8
- ___block_descriptor_81_e8_32s40bs48r_e27_v32?0"SBIconView"8Q16^B24ls32l8s40l8r48l8
- ___block_descriptor_89_e8_32bs40r48r_e28_v24?0"SBIconListView"8^B16lr40l8r48l8s32l8
- _soft_PLKLegibilityStyleForUILegibilityStyle
- _symbolic Iegh_
- _symbolic Say_____G 8Dispatch0A13WorkItemFlagsV
- _symbolic So17OS_dispatch_groupC
CStrings:
+ "%@\t%@\n"
+ "CacheIconServicesIcon"
+ "Local image cache load completed but without any CGImage"
+ "Pre-caching clock background at %.0fx%.0f@%.0f for %{public}@ (priority: %li)"
+ "SBIconLocal"
+ "SBRootFolderView setEditUndoRedoButtonsAlpha: %{public}f"
+ "clock background data precache"
+ "imageForDescriptor %@:%@ %lx"
+ "prepareImageForDescriptor %@:%@ %lx"
+ "style preview (mini)"
- "BigAndTall"
- "Calistoga"
- "IconServices"
- "IsSolariumLowPerformanceDevice"
- "ReduceBlankIcons"
- "SBIcon.local"
- "SwiftUI"
- "color context with dimensions %{public}@ @%fx does not fit in 'iconImages' memory pool - returning nil"
- "com.apple.lightsourcesupport.listener"
- "content hidden"
- "performanceFlagDisableSpecularEverywhere"
```
