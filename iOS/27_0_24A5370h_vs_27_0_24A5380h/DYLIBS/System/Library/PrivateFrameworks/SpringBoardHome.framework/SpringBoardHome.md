## SpringBoardHome

> `/System/Library/PrivateFrameworks/SpringBoardHome.framework/SpringBoardHome`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0xeb20` | `0xf150` | **`+0x630`** |
| `__TEXT.__text` | `0x38987c` | `0x389278` | **`-0x604`** |
| `__AUTH_CONST.__objc_const` | `0x59108` | `0x58cd0` | **`-0x438`** |
| `__TEXT.__objc_methlist` | `0x3edac` | `0x3eab4` | **`-0x2f8`** |
| `__DATA.__bss` | `0x3a98` | `0x3838` | **`-0x260`** |
| `__TEXT.__ustring` | `0x620` | `0x476` | **`-0x1aa`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cc88` | `0x1cae8` | **`-0x1a0`** |
| `__TEXT.__cstring` | `0x188e3` | `0x18a83` | **`+0x1a0`** |
| `__DATA_CONST.__const` | `0x9d40` | `0x9ea8` | **`+0x168`** |
| `__AUTH_CONST.__cfstring` | `0x16c80` | `0x16da0` | **`+0x120`** |
| `__TEXT.__const` | `0x7fd4` | `0x7ec4` | **`-0x110`** |
| `__AUTH.__objc_data` | `0xb930` | `0xb830` | **`-0x100`** |
| `__TEXT.__unwind_info` | `0xf8d8` | `0xf7e0` | **`-0xf8`** |
| `__DATA_DIRTY.__objc_data` | `0x14f0` | `0x1590` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x7538` | `0x74a8` | **`-0x90`** |
| `__DATA.__data` | `0x96d8` | `0x9648` | **`-0x90`** |
| `__TEXT.__gcc_except_tab` | `0x42c4` | `0x4328` | **`+0x64`** |
| `__AUTH_CONST.__auth_got` | `0x1d10` | `0x1d68` | **`+0x58`** |
| `__DATA_CONST.__got` | `0x24d0` | `0x2478` | **`-0x58`** |
| `__TEXT.__swift5_capture` | `0x15b8` | `0x1564` | **`-0x54`** |
| `__TEXT.__eh_frame` | `0xc88` | `0xc48` | **`-0x40`** |
| `__TEXT.__swift5_assocty` | `0x540` | `0x510` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0xafa` | `0xb2a` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0xbe0` | `0xc08` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x65a0` | `0x657e` | **`-0x22`** |
| `__DATA.__objc_ivar` | `0x3de0` | `0x3dc0` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x38` | `0x18` | **`-0x20`** |
| `__AUTH.__data` | `0xc78` | `0xc60` | **`-0x18`** |
| `__DATA_CONST.__objc_protolist` | `0xbc0` | `0xba8` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x1e0` | `0x1cc` | **`-0x14`** |
| `__TEXT.__swift5_proto` | `0x174` | `0x160` | **`-0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x1328` | `0x1318` | **`-0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x1a8` | `0x198` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xea0` | `0xe98` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x1270` | `0x126c` | **`-0x4`** |

### Other Changes

```diff

-217.0.101.0.0
+220.105.0.0.0

-  - /System/Library/PrivateFrameworks/IconRendering.framework/IconRendering

-  - /System/Library/PrivateFrameworks/LightSourceSupport.framework/LightSourceSupport

-  Functions: 24673
-  Symbols:   33671
-  CStrings:  4540
+  Functions: 24643
+  Symbols:   33627
+  CStrings:  4565
Symbols:
+ +[NSArray(SBHArrayUtilities) sbh_arrayByCombiningArray:withArray:]
+ +[SBFolderView prefetchingContextForIconListViews:maxPrefetchedCells:scrolling:scrollingDirection:visibleRectProvider:]
+ +[SBFolderView updateVisibleCellsPrefetchingNextIconIfPossible:defaultContentVisibility:prefetchingContext:]
+ +[SBHClockApplicationIconImageView precacheDataWithIconImageInfo:appearance:priority:options:]
+ +[SBIcon canUseLocalCacheWithInfo:traitCollection:context:options:]
+ -[SBFolderView _prefetchNextIconIfPossible:]
+ -[SBFolderView isTemporaryFolderAllowed]
+ -[SBFolderView setTemporaryFolderAllowed:]
+ -[SBFolderView updateVisibleCellsPrefetchingNextIconIfPossible:visibleRect:effectiveVisibleRect:prefetchingContext:]
+ -[SBFolderViewIconListPrefetchingInfo .cxx_destruct]
+ -[SBFolderViewIconListPrefetchingInfo _cachePrefetchedIconsIfNecessary]
+ -[SBFolderViewIconListPrefetchingInfo areAllIconsLoaded]
+ -[SBFolderViewIconListPrefetchingInfo cachedPrefetchedIcons]
+ -[SBFolderViewIconListPrefetchingInfo iconListView]
+ -[SBFolderViewIconListPrefetchingInfo initWithIconListView:visibleRect:visibleGridCellIndexes:prefetchedGridCellIndexes:prefetchableGridCellIndexes:]
+ -[SBFolderViewIconListPrefetchingInfo prefetchableGridCellIndexes]
+ -[SBFolderViewIconListPrefetchingInfo prefetchedGridCellIndexes]
+ -[SBFolderViewIconListPrefetchingInfo prefetchedIcons]
+ -[SBFolderViewIconListPrefetchingInfo setCachedPrefetchedIcons:]
+ -[SBFolderViewIconListPrefetchingInfo setPrefetchedGridCellIndexes:]
+ -[SBFolderViewIconListPrefetchingInfo visibleGridCellIndexes]
+ -[SBFolderViewIconListPrefetchingInfo visibleRect]
+ -[SBFolderViewIconPrefetchingContext .cxx_destruct]
+ -[SBFolderViewIconPrefetchingContext _calculatePrimaryAndSecondaryDirectionsIfNecessary]
+ -[SBFolderViewIconPrefetchingContext hasCalculatedPrimaryAndSecondaryDirections]
+ -[SBFolderViewIconPrefetchingContext initWithMaxPrefetchedCells:scrolling:scrollingDirection:prefetchingInfosForFullyVisibleLists:leadingPrefetchingInfosForNotFullyVisibleLists:trailingPrefetchingInfosForNotFullyVisibleLists:]
+ -[SBFolderViewIconPrefetchingContext invalidatePrimaryandSecondaryDirections]
+ -[SBFolderViewIconPrefetchingContext isPrefetchingSettled]
+ -[SBFolderViewIconPrefetchingContext isScrolling]
+ -[SBFolderViewIconPrefetchingContext isVertical]
+ -[SBFolderViewIconPrefetchingContext leadingPrefetchingInfosForNotFullyVisibleLists]
+ -[SBFolderViewIconPrefetchingContext maxEdge]
+ -[SBFolderViewIconPrefetchingContext maxPrefetchedCells]
+ -[SBFolderViewIconPrefetchingContext minEdge]
+ -[SBFolderViewIconPrefetchingContext prefetchingInfosForFullyVisibleLists]
+ -[SBFolderViewIconPrefetchingContext prefetchingInfosForNotFullyVisibleListsInPrimaryDirection]
+ -[SBFolderViewIconPrefetchingContext prefetchingInfosForNotFullyVisibleListsInSecondaryDirection]
+ -[SBFolderViewIconPrefetchingContext primaryDirection]
+ -[SBFolderViewIconPrefetchingContext scrollingDirection]
+ -[SBFolderViewIconPrefetchingContext secondaryDirection]
+ -[SBFolderViewIconPrefetchingContext setHasCalculatedPrimaryAndSecondaryDirections:]
+ -[SBFolderViewIconPrefetchingContext setMaxEdge:]
+ -[SBFolderViewIconPrefetchingContext setMinEdge:]
+ -[SBFolderViewIconPrefetchingContext setPrimaryDirection:]
+ -[SBFolderViewIconPrefetchingContext setSecondaryDirection:]
+ -[SBFolderViewIconPrefetchingContext setVertical:]
+ -[SBFolderViewIconPrefetchingContext trailingPrefetchingInfosForNotFullyVisibleLists]
+ -[SBHAddWidgetSheetViewController _prefetchNextIconIfPossible:]
+ -[SBHAddWidgetSheetViewController _prefetchingContext]
+ -[SBHAddWidgetSheetViewController _updateVisibleIconsInCellsPrefetchingNextIconIfPossible:initialPrefetchingContext:]
+ -[SBHIconImageCache _canPoolImage:forIcon:]
+ -[SBHIconImageCache forcesMitigatedAppearance]
+ -[SBHIconImageCache setForcesMitigatedAppearance:]
+ -[SBHIconImageIdentity imageOptions]
+ -[SBHIconImageIdentity initWithIcon:iconImageInfo:imageGeneration:imageAppearance:imageOptions:]
+ -[SBHIconImageIdentity initWithIconIdentifier:iconImageInfo:imageGeneration:imageAppearance:imageOptions:]
+ -[SBHIconImagePrecacheInfo .cxx_destruct]
+ -[SBHIconImagePrecacheInfo bundleIdentifiers]
+ -[SBHIconImagePrecacheInfo copyWithZone:]
+ -[SBHIconImagePrecacheInfo description]
+ -[SBHIconImagePrecacheInfo hash]
+ -[SBHIconImagePrecacheInfo iconImageInfo]
+ -[SBHIconImagePrecacheInfo iconImageLoadPriority]
+ -[SBHIconImagePrecacheInfo initWithBundleIdentifiers:iconImageInfo:]
+ -[SBHIconImagePrecacheInfo initWithBundleIdentifiers:iconImageInfo:iconImageLoadPriority:]
+ -[SBHIconImagePrecacheInfo isEqual:]
+ -[SBHIconImagePrecacheRequest additionalPrecacheInfos]
+ -[SBHIconImagePrecacheRequest allImageAppearances]
+ -[SBHIconImagePrecacheRequest cachesMitigatedImages]
+ -[SBHIconImagePrecacheRequest setAdditionalPrecacheInfos:]
+ -[SBHIconImagePrecacheRequest setCachesMitigatedImages:]
+ -[SBHIconMiniGridView updateIconTintColorFromImageAppearance:]
+ -[SBHIconStylePreviewManager representitiveIconImageView]
+ -[SBHIconStylePreviewManager representitiveIconLayerView]
+ -[SBHIconStylePreviewManager setRepresentitiveIconImageView:]
+ -[SBHLibraryPodFolderView _createIconListViewForList:]
+ -[SBIcon reloadIconImageForReason:]
+ -[SBIconImageView isFastTintingEnabled]
+ -[SBIconImageView setFastTintingEnabled:]
+ -[SBIconImageView setSkipsImageCache:]
+ -[SBIconImageView skipsImageCache]
+ -[SBIconListModel _ensureIconsByIdentifierMapping]
+ -[SBIconListModel _invalidateIconsByIdentifierMapping]
+ -[SBIconListModel _mutateIcons:]
+ -[SBIconListModel setIconsFromIconListModel:mutationOptions:]
+ -[SBIconListView updateIconViewVisibility]
+ -[SBLeafIcon disableDataSourceChangeNotifications]
+ -[SBLeafIcon enableDataSourceChangeNotifications]
+ -[SBLeafIcon reloadIconImageForReason:]
+ -[SBLeafIcon shouldIgnoreDataSourceChangeNotifications]
+ GCC_except_table1004
+ GCC_except_table1064
+ GCC_except_table1112
+ GCC_except_table1113
+ GCC_except_table1115
+ GCC_except_table1131
+ GCC_except_table1138
+ GCC_except_table137
+ GCC_except_table156
+ GCC_except_table174
+ GCC_except_table188
+ GCC_except_table213
+ GCC_except_table246
+ GCC_except_table248
+ GCC_except_table252
+ GCC_except_table257
+ GCC_except_table268
+ GCC_except_table277
+ GCC_except_table295
+ GCC_except_table306
+ GCC_except_table328
+ GCC_except_table334
+ GCC_except_table335
+ GCC_except_table340
+ GCC_except_table352
+ GCC_except_table359
+ GCC_except_table368
+ GCC_except_table384
+ GCC_except_table390
+ GCC_except_table420
+ GCC_except_table435
+ GCC_except_table438
+ GCC_except_table440
+ GCC_except_table445
+ GCC_except_table470
+ GCC_except_table478
+ GCC_except_table484
+ GCC_except_table489
+ GCC_except_table493
+ GCC_except_table495
+ GCC_except_table496
+ GCC_except_table499
+ GCC_except_table513
+ GCC_except_table530
+ GCC_except_table541
+ GCC_except_table551
+ GCC_except_table564
+ GCC_except_table566
+ GCC_except_table580
+ GCC_except_table585
+ GCC_except_table61
+ GCC_except_table631
+ GCC_except_table633
+ GCC_except_table655
+ GCC_except_table777
+ GCC_except_table787
+ GCC_except_table790
+ GCC_except_table801
+ GCC_except_table803
+ GCC_except_table805
+ GCC_except_table807
+ GCC_except_table810
+ GCC_except_table812
+ GCC_except_table814
+ GCC_except_table821
+ GCC_except_table824
+ GCC_except_table827
+ GCC_except_table830
+ GCC_except_table934
+ GCC_except_table988
+ GCC_except_table99
+ _CFDataGetBytePtr
+ _CFEqual
+ _CGColorSpaceGetName
+ _CGDataProviderCopyData
+ _CGImageGetAlphaInfo
+ _CGImageGetBitmapInfo
+ _CGImageGetBitsPerComponent
+ _CGImageGetBitsPerPixel
+ _CGImageGetBytesPerRow
+ _CGImageGetColorSpace
+ _CGImageGetDataProvider
+ _CGImageGetHeight
+ _CGImageGetWidth
+ _OBJC_CLASS_$_SBFolderViewIconListPrefetchingInfo
+ _OBJC_CLASS_$_SBFolderViewIconPrefetchingContext
+ _OBJC_CLASS_$_SBHIconImageCacheGroup
+ _OBJC_CLASS_$_SBHIconImagePrecacheInfo
+ _OBJC_IVAR_$_SBFolderView._temporaryFolderAllowed
+ _OBJC_IVAR_$_SBFolderViewIconListPrefetchingInfo._cachedPrefetchedIcons
+ _OBJC_IVAR_$_SBFolderViewIconListPrefetchingInfo._iconListView
+ _OBJC_IVAR_$_SBFolderViewIconListPrefetchingInfo._prefetchableGridCellIndexes
+ _OBJC_IVAR_$_SBFolderViewIconListPrefetchingInfo._prefetchedGridCellIndexes
+ _OBJC_IVAR_$_SBFolderViewIconListPrefetchingInfo._visibleGridCellIndexes
+ _OBJC_IVAR_$_SBFolderViewIconListPrefetchingInfo._visibleRect
+ _OBJC_IVAR_$_SBFolderViewIconPrefetchingContext._hasCalculatedPrimaryAndSecondaryDirections
+ _OBJC_IVAR_$_SBFolderViewIconPrefetchingContext._leadingPrefetchingInfosForNotFullyVisibleLists
+ _OBJC_IVAR_$_SBFolderViewIconPrefetchingContext._maxEdge
+ _OBJC_IVAR_$_SBFolderViewIconPrefetchingContext._maxPrefetchedCells
+ _OBJC_IVAR_$_SBFolderViewIconPrefetchingContext._minEdge
+ _OBJC_IVAR_$_SBFolderViewIconPrefetchingContext._prefetchingInfosForFullyVisibleLists
+ _OBJC_IVAR_$_SBFolderViewIconPrefetchingContext._primaryDirection
+ _OBJC_IVAR_$_SBFolderViewIconPrefetchingContext._scrolling
+ _OBJC_IVAR_$_SBFolderViewIconPrefetchingContext._scrollingDirection
+ _OBJC_IVAR_$_SBFolderViewIconPrefetchingContext._secondaryDirection
+ _OBJC_IVAR_$_SBFolderViewIconPrefetchingContext._trailingPrefetchingInfosForNotFullyVisibleLists
+ _OBJC_IVAR_$_SBFolderViewIconPrefetchingContext._vertical
+ _OBJC_IVAR_$_SBHIconImageCache._forcesMitigatedAppearance
+ _OBJC_IVAR_$_SBHIconImageIdentity._imageOptions
+ _OBJC_IVAR_$_SBHIconImagePrecacheInfo._bundleIdentifiers
+ _OBJC_IVAR_$_SBHIconImagePrecacheInfo._iconImageInfo
+ _OBJC_IVAR_$_SBHIconImagePrecacheInfo._iconImageLoadPriority
+ _OBJC_IVAR_$_SBHIconImagePrecacheRequest._additionalPrecacheInfos
+ _OBJC_IVAR_$_SBHIconImagePrecacheRequest._cachesMitigatedImages
+ _OBJC_IVAR_$_SBHIconStylePreviewManager._representitiveIconImageView
+ _OBJC_IVAR_$_SBIconImageView._fastTintingEnabled
+ _OBJC_IVAR_$_SBIconImageView._skipsImageCache
+ _OBJC_IVAR_$_SBIconListModel._iconsByIdentifier
+ _OBJC_IVAR_$_SBLeafIcon._dataSourceChangeNotificationIgnoreCount
+ _OBJC_METACLASS_$_SBFolderViewIconListPrefetchingInfo
+ _OBJC_METACLASS_$_SBFolderViewIconPrefetchingContext
+ _OBJC_METACLASS_$_SBHIconImageCacheGroup
+ _OBJC_METACLASS_$_SBHIconImagePrecacheInfo
+ _SBHFeatureEnabled.__verboseCachingLoggingEnabled
+ _SBHFeatureEnabled.onceToken
+ _SBHIconCGImageIsBlank
+ _SBHIconImageLayerFromCGImage
+ _SBHStringForIconImageCacheOptions
+ _SBHStringForIconServicesOptions
+ _SBTreeNodeSetParentWithoutAncestryNotification
+ _UIRandomInRange
+ __DATA_SBHIconImageCacheGroup
+ __DATA_SBHIconImageLayer
+ __INSTANCE_METHODS_SBHIconImageCacheGroup
+ __INSTANCE_METHODS_SBHIconImageLayer
+ __IVARS_SBHIconImageCacheGroup
+ __IVARS_SBHIconImageLayer
+ __METACLASS_DATA_SBHIconImageCacheGroup
+ __METACLASS_DATA_SBHIconImageLayer
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSArray_$_SBHArrayUtilities
+ __OBJC_$_INSTANCE_METHODS_SBFolderViewIconListPrefetchingInfo
+ __OBJC_$_INSTANCE_METHODS_SBFolderViewIconPrefetchingContext
+ __OBJC_$_INSTANCE_METHODS_SBHIconImagePrecacheInfo
+ __OBJC_$_INSTANCE_VARIABLES_SBFolderViewIconListPrefetchingInfo
+ __OBJC_$_INSTANCE_VARIABLES_SBFolderViewIconPrefetchingContext
+ __OBJC_$_INSTANCE_VARIABLES_SBHIconImagePrecacheInfo
+ __OBJC_$_PROP_LIST_SBFolderViewIconListPrefetchingInfo
+ __OBJC_$_PROP_LIST_SBFolderViewIconPrefetchingContext
+ __OBJC_$_PROP_LIST_SBHIconImagePrecacheInfo
+ __OBJC_CLASS_PROTOCOLS_$_SBHIconImagePrecacheInfo
+ __OBJC_CLASS_RO_$_SBFolderViewIconListPrefetchingInfo
+ __OBJC_CLASS_RO_$_SBFolderViewIconPrefetchingContext
+ __OBJC_CLASS_RO_$_SBHIconImagePrecacheInfo
+ __OBJC_METACLASS_RO_$_SBFolderViewIconListPrefetchingInfo
+ __OBJC_METACLASS_RO_$_SBFolderViewIconPrefetchingContext
+ __OBJC_METACLASS_RO_$_SBHIconImagePrecacheInfo
+ __PROPERTIES_SBHIconImageCacheGroup
+ __PROPERTIES_SBHIconImageLayer
+ __UILerp
+ __UIUnlerp
+ ___100-[SBIconListModel removeIconWithoutChangingLayout:gridCellInfo:gridCellInfoOptions:mutationOptions:]_block_invoke
+ ___102-[SBIconListModel insertIconWhilePreservingQuads:toGridCellIndex:gridCellInfoOptions:mutationOptions:]_block_invoke_10
+ ___102-[SBIconListModel insertIconWhilePreservingQuads:toGridCellIndex:gridCellInfoOptions:mutationOptions:]_block_invoke_6
+ ___102-[SBIconListModel insertIconWhilePreservingQuads:toGridCellIndex:gridCellInfoOptions:mutationOptions:]_block_invoke_7
+ ___102-[SBIconListModel insertIconWhilePreservingQuads:toGridCellIndex:gridCellInfoOptions:mutationOptions:]_block_invoke_8
+ ___102-[SBIconListModel insertIconWhilePreservingQuads:toGridCellIndex:gridCellInfoOptions:mutationOptions:]_block_invoke_9
+ ___108+[SBFolderView updateVisibleCellsPrefetchingNextIconIfPossible:defaultContentVisibility:prefetchingContext:]_block_invoke
+ ___108+[SBFolderView updateVisibleCellsPrefetchingNextIconIfPossible:defaultContentVisibility:prefetchingContext:]_block_invoke_2
+ ___108+[SBFolderView updateVisibleCellsPrefetchingNextIconIfPossible:defaultContentVisibility:prefetchingContext:]_block_invoke_3
+ ___108+[SBFolderView updateVisibleCellsPrefetchingNextIconIfPossible:defaultContentVisibility:prefetchingContext:]_block_invoke_4
+ ___108+[SBFolderView updateVisibleCellsPrefetchingNextIconIfPossible:defaultContentVisibility:prefetchingContext:]_block_invoke_5
+ ___108+[SBFolderView updateVisibleCellsPrefetchingNextIconIfPossible:defaultContentVisibility:prefetchingContext:]_block_invoke_6
+ ___108+[SBFolderView updateVisibleCellsPrefetchingNextIconIfPossible:defaultContentVisibility:prefetchingContext:]_block_invoke_7
+ ___119+[SBFolderView prefetchingContextForIconListViews:maxPrefetchedCells:scrolling:scrollingDirection:visibleRectProvider:]_block_invoke
+ ___148-[SBIconListModel _checkAndRemoveBouncedIconsAfterChangeToIcons:ignoringTrailingIconCheck:gridCellInfoOptions:mutationOptions:computedGridCellInfo:]_block_invoke_5
+ ___38-[SBIconListModel removeIcon:options:]_block_invoke_3
+ ___42-[SBIconListView updateIconViewVisibility]_block_invoke
+ ___44-[SBFolderView _prefetchNextIconIfPossible:]_block_invoke
+ ___53-[SBIconListModel moveContainedIcon:toIndex:options:]_block_invoke
+ ___53-[SBIconListModel moveContainedIcon:toIndex:options:]_block_invoke_2
+ ___53-[SBIconListModel moveContainedIcon:toIndex:options:]_block_invoke_3
+ ___53-[SBIconListModel sortByLayoutOrderWithGridCellInfo:]_block_invoke
+ ___54-[SBHAddWidgetSheetViewController _prefetchingContext]_block_invoke
+ ___54-[SBHAddWidgetSheetViewController _prefetchingContext]_block_invoke_2
+ ___65-[SBIconListModel sortByIconGridSizeAreaWithGridCellInfoOptions:]_block_invoke_2
+ ___67-[SBIconListModel setIconOrderFromGridCellInfo:referenceIconOrder:]_block_invoke_2
+ ___70-[SBIconListModel performChangesByPreservingOrderOfDefaultSizedIcons:]_block_invoke_3
+ ___70-[SBIconListModel performChangesByPreservingOrderOfDefaultSizedIcons:]_block_invoke_4
+ ___70-[SBIconListModel performChangesByPreservingOrderOfDefaultSizedIcons:]_block_invoke_5
+ ___72-[SBIconListModel restorePositionsOfIconsLargerThanSizeClass:usingInfo:]_block_invoke
+ ___72-[SBIconListModel restorePositionsOfIconsLargerThanSizeClass:usingInfo:]_block_invoke_2
+ ___75-[SBIconListModel _clusterIconsForSizeClass:behavior:gridCellInfoProvider:]_block_invoke
+ ___77-[SBIconListModel replaceIcon:withIcons:gridCellInfoOptions:mutationOptions:]_block_invoke_2
+ ___77-[SBIconListModel replaceIcon:withIcons:gridCellInfoOptions:mutationOptions:]_block_invoke_3
+ ___77-[SBIconListModel setIcons:gridCellInfo:gridCellInfoOptions:mutationOptions:]_block_invoke_3
+ ___77-[SBIconListModel setIcons:gridCellInfo:gridCellInfoOptions:mutationOptions:]_block_invoke_4
+ ___79-[SBIconListModel removeIcon:gridCellInfo:gridCellInfoOptions:mutationOptions:]_block_invoke_7
+ ___83-[SBIconListModel insertIcons:atGridCellIndex:gridCellInfoOptions:mutationOptions:]_block_invoke
+ ___90-[SBIconListModel _rawInsertIcons:atIndex:callingWillAddIcon:gridCellInfoOptions:options:]_block_invoke_2
+ ___90-[SBIconListModel finishChangingFromGridSize:withOldIconCoordinates:bouncedIcons:options:]_block_invoke_2
+ ___90-[SBIconListModel finishChangingFromGridSize:withOldIconCoordinates:bouncedIcons:options:]_block_invoke_3
+ ___90-[SBIconListModel finishChangingFromGridSize:withOldIconCoordinates:bouncedIcons:options:]_block_invoke_4
+ ___92-[SBIconListModel _unclusterIcons:ofSizeClass:baseGridCellInfoOptions:gridCellInfoProvider:]_block_invoke
+ ___92-[SBIconListModel _unclusterIcons:ofSizeClass:baseGridCellInfoOptions:gridCellInfoProvider:]_block_invoke_2
+ ___SBHFeatureEnabled_block_invoke
+ ___SBHIconImageLayerFromCGImage_block_invoke
+ ___block_descriptor_106_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_112_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_120_e8_32s40s48s56s_e45_v16?0"<SBHIconImageCacheResultDescribing>"8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_120_e8_32s40s48s_e45_v16?0"<SBHIconImageCacheResultDescribing>"8ls32l8s40l8s48l8
+ ___block_descriptor_144_e8_32s40s48s56s64s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_32_e24_v16?0"NSMutableArray"8l
+ ___block_descriptor_32_e32_B16?0"SBHIconImageAppearance"8l
+ ___block_descriptor_40_e24_v16?0"NSMutableArray"8l
+ ___block_descriptor_40_e8_32r_e24_v16?0"NSMutableArray"8lr32l8
+ ___block_descriptor_40_e8_32s_e24_v16?0"NSMutableArray"8ls32l8
+ ___block_descriptor_48_e8_32s40r_e24_v16?0"NSMutableArray"8lr40l8s32l8
+ ___block_descriptor_48_e8_32s40s_e24_v16?0"NSMutableArray"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s_e24_v16?0"NSMutableArray"8ls32l8
+ ___block_descriptor_56_e8_32bs40r_e23_B24?0"NSArray"8I16B20lr40l8s32l8
+ ___block_descriptor_56_e8_32s40s_e24_v16?0"NSMutableArray"8ls32l8s40l8
+ ___block_descriptor_65_e8_32s40s_e49_v32?0"SBHWidgetContainerViewController"8Q16^B24ls32l8s40l8
+ __canPoolImage:forIcon:.__poolOptOutCount
+ _kCGColorSpaceExtendedSRGB
+ _symbolic So22SBHIconImageAppearanceCSg
+ _symbolic So7CALayerCSg
+ _symbolic _____ 15SpringBoardHome14IconImageLayerC
+ _symbolic _____ 15SpringBoardHome19IconImageCacheGroupC
- +[SBFolderView _allPrefetchableGridCellIndexesForListView:]
- +[SBFolderView _areAllIconsLoadedInListView:withPrefetchedGridCellIndexes:visibleGridCellIndexes:]
- +[SBFolderView _isPrefetchingSettledWithMaxPrefetchedCells:scrolling:notFullyVisibleIconListViewsInPrimaryDirection:visibleIconGridCellsInPrimaryDirection:notFullyVisibleIconListViewsInSecondaryDirection:visibleIconGridCellsInSecondaryDirection:]
- +[SBFolderView _numberOfPrefetchableCellsInIconListViews:]
- +[SBFolderView _numberOfPrefetchedCellsInIconListViews:]
- +[SBFolderView _sortAndCategorizeIconListViews:scrolling:scrollingDirection:visibleRectProvider:outFullyVisibleIconListViews:outPrimaryDirection:outNotFullyVisibleIconListViewsInPrimaryDirection:outVisibleIconGridCellsInPrimaryDirection:outSecondaryDirection:outNotFullyVisibleIconListViewsInSecondaryDirection:outVisibleIconGridCellsInSecondaryDirection:]
- +[SBFolderView _updateVisibleCellsPrefetchingNextIconIfPossible:maxPrefetchedCells:scrolling:defaultContentVisibility:fullyVisibleIconListViews:primaryDirection:notFullyVisibleIconListViewsInPrimaryDirection:visibleIconGridCellsInPrimaryDirection:secondaryDirection:notFullyVisibleIconListViewsInSecondaryDirection:visibleIconGridCellsInSecondaryDirection:]
- +[SBHClockApplicationIconImageView precacheDataWithIconImageInfo:appearance:priority:]
- +[SBHLightSourceManager managerForScreen:]
- +[SBHLightSourceManager sharedManager]
- +[SBHLightSourceManager tearDownManager:]
- +[SBHLightSourceOverlayManager isOverlayAllowed]
- -[SBFolderIconImageView enumerateCurrentPageIconLayersUsingBlock:]
- -[SBFolderView _prefetchNextIconIfPossible]
- -[SBFolderView _updateVisibleCellsPrefetchingNextIconIfPossible:visibleRect:effectiveVisibleRect:scrolling:fullyVisibleIconListViews:primaryDirection:notFullyVisibleIconListViewsInPrimaryDirection:visibleIconGridCellsInPrimaryDirection:secondaryDirection:notFullyVisibleIconListViewsInSecondaryDirection:visibleIconGridCellsInSecondaryDirection:]
- -[SBHAddWidgetSheetViewController _prefetchNextIconIfPossible]
- -[SBHAddWidgetSheetViewController _updateVisibleIconsInCellsPrefetchingNextIconIfPossible:]
- -[SBHIconImageCache _canPoolImageForIcon:]
- -[SBHIconImageContainerLayer .cxx_destruct]
- -[SBHIconImageContainerLayer imageLayer]
- -[SBHIconImageContainerLayer layoutSublayers]
- -[SBHIconImageContainerLayer setImageLayer:]
- -[SBHIconImageIdentity initWithIcon:iconImageInfo:imageGeneration:imageAppearance:masked:]
- -[SBHIconImageIdentity initWithIconIdentifier:iconImageInfo:imageGeneration:imageAppearance:masked:]
- -[SBHIconImageIdentity isMasked]
- -[SBHIconImageStyleConfiguration descriptionBuilderWithMultilinePrefix:]
- -[SBHIconImageStyleConfiguration descriptionWithMultilinePrefix:]
- -[SBHIconImageStyleConfiguration succinctDescriptionBuilder]
- -[SBHIconImageStyleConfiguration succinctDescription]
- -[SBHIconMiniGridView setIconTintColor:]
- -[SBHIconSettings setSheenEffectDebugUIEnabled:]
- -[SBHIconSettings setSheenEffectFadeInSettings:]
- -[SBHIconSettings setSheenEffectFadeOutSettings:]
- -[SBHIconSettings setSheenEffectMinimumMovementToBecomeVisible:]
- -[SBHIconSettings setSheenEffectStrength:]
- -[SBHIconSettings sheenEffectDebugUIEnabled]
- -[SBHIconSettings sheenEffectFadeInSettings]
- -[SBHIconSettings sheenEffectFadeOutSettings]
- -[SBHIconSettings sheenEffectMinimumMovementToBecomeVisible]
- -[SBHIconSettings sheenEffectStrength]
- -[SBHLightSourceManager .cxx_destruct]
- -[SBHLightSourceManager _didAddLightSourceObserverInView:]
- -[SBHLightSourceManager accumulatedDistance]
- -[SBHLightSourceManager activeRefreshRate]
- -[SBHLightSourceManager addLayer:inView:]
- -[SBHLightSourceManager addObserver:inView:]
- -[SBHLightSourceManager areUpdatesDisabled]
- -[SBHLightSourceManager canUpdateLight]
- -[SBHLightSourceManager currentActivityLevel]
- -[SBHLightSourceManager descriptionBuilderWithMultilinePrefix:]
- -[SBHLightSourceManager descriptionWithMultilinePrefix:]
- -[SBHLightSourceManager description]
- -[SBHLightSourceManager effectiveActivityLevel]
- -[SBHLightSourceManager effectiveLightSourceActivityLevel]
- -[SBHLightSourceManager evaluateLightAngleUpdates]
- -[SBHLightSourceManager iconSettings]
- -[SBHLightSourceManager initWithScreen:]
- -[SBHLightSourceManager initialDistanceThreshold]
- -[SBHLightSourceManager initialLightDirection]
- -[SBHLightSourceManager initialVelocityThreshold]
- -[SBHLightSourceManager invalidateAssertion:]
- -[SBHLightSourceManager invalidateDisableUpdatesAssertion:]
- -[SBHLightSourceManager invalidateReduceUpdateFrequencyAssertion:]
- -[SBHLightSourceManager lastLightAngle]
- -[SBHLightSourceManager lastLightDirection2]
- -[SBHLightSourceManager lastLightDirectionCoordinates]
- -[SBHLightSourceManager lastLightDirection]
- -[SBHLightSourceManager lastLightIntensity]
- -[SBHLightSourceManager lastLightTimestamp2]
- -[SBHLightSourceManager lastLightTimestamp]
- -[SBHLightSourceManager layerCount]
- -[SBHLightSourceManager layers]
- -[SBHLightSourceManager lightSourceDisplayLinkDidFire:]
- -[SBHLightSourceManager lightSourceDisplayLink]
- -[SBHLightSourceManager lightSourceSubscription]
- -[SBHLightSourceManager observerCount]
- -[SBHLightSourceManager overlayManager]
- -[SBHLightSourceManager pauseLightAngleUpdates]
- -[SBHLightSourceManager pauseUpdatesForReason:]
- -[SBHLightSourceManager preferredFrameRateRange]
- -[SBHLightSourceManager pushLightAngleUpdateWithDirection:intensity:]
- -[SBHLightSourceManager reduceMotionDidChange:]
- -[SBHLightSourceManager reduceUpdateFrequencyForReason:]
- -[SBHLightSourceManager removeLayer:]
- -[SBHLightSourceManager removeObserver:]
- -[SBHLightSourceManager resumeLightAngleUpdates]
- -[SBHLightSourceManager screenDisconnected:]
- -[SBHLightSourceManager screen]
- -[SBHLightSourceManager setAccumulatedDistance:]
- -[SBHLightSourceManager setActiveRefreshRate:]
- -[SBHLightSourceManager setCurrentActivityLevel:]
- -[SBHLightSourceManager setInitialDistanceThreshold:]
- -[SBHLightSourceManager setInitialLightDirection:]
- -[SBHLightSourceManager setInitialVelocityThreshold:]
- -[SBHLightSourceManager setLastLightAngle:]
- -[SBHLightSourceManager setLastLightDirection2:]
- -[SBHLightSourceManager setLastLightDirection:]
- -[SBHLightSourceManager setLastLightIntensity:]
- -[SBHLightSourceManager setLastLightTimestamp2:]
- -[SBHLightSourceManager setLastLightTimestamp:]
- -[SBHLightSourceManager setLightSourceDisplayLink:]
- -[SBHLightSourceManager setLightSourceSubscription:]
- -[SBHLightSourceManager setOverlayManager:]
- -[SBHLightSourceManager setUpDisplayLink]
- -[SBHLightSourceManager setUpLightSourceSubscription]
- -[SBHLightSourceManager setUpdatesDisabled:]
- -[SBHLightSourceManager settings:changedValueForKey:]
- -[SBHLightSourceManager shouldUpdateLight]
- -[SBHLightSourceManager startOrStopUpdatesAsNecessary]
- -[SBHLightSourceManager startUpdates]
- -[SBHLightSourceManager stopUpdates]
- -[SBHLightSourceManager succinctDescriptionBuilder]
- -[SBHLightSourceManager succinctDescription]
- -[SBHLightSourceManager tearDownDisplayLink]
- -[SBHLightSourceManager tearDownLightSourceSubscription]
- -[SBHLightSourceManager updateLightInLayerOutsideOfDisplayLink:]
- -[SBHLightSourceManager updateLightInObserverOutsideOfDisplayLink:]
- -[SBHLightSourceManager updateLightSourceForTargetTimestamp:]
- -[SBHLightSourceManager updateLightSourceRefreshRate]
- -[SBHLightSourceManager updateLightSourceUpdateActivityLevel:]
- -[SBHLightSourceManagerAssertion .cxx_destruct]
- -[SBHLightSourceManagerAssertion dealloc]
- -[SBHLightSourceManagerAssertion descriptionBuilderWithMultilinePrefix:]
- -[SBHLightSourceManagerAssertion descriptionWithMultilinePrefix:]
- -[SBHLightSourceManagerAssertion description]
- -[SBHLightSourceManagerAssertion initWithLightSourceManager:type:reason:]
- -[SBHLightSourceManagerAssertion invalidate]
- -[SBHLightSourceManagerAssertion isInvalidated]
- -[SBHLightSourceManagerAssertion lightSourceManager]
- -[SBHLightSourceManagerAssertion reason]
- -[SBHLightSourceManagerAssertion setInvalidated:]
- -[SBHLightSourceManagerAssertion succinctDescriptionBuilder]
- -[SBHLightSourceManagerAssertion succinctDescription]
- -[SBHLightSourceManagerAssertion type]
- -[SBHLightSourceOverlayManager .cxx_destruct]
- -[SBHLightSourceOverlayManager batchUpdateCount]
- -[SBHLightSourceOverlayManager initWithLightSourceManager:windowScene:]
- -[SBHLightSourceOverlayManager invalidate]
- -[SBHLightSourceOverlayManager label]
- -[SBHLightSourceOverlayManager lastBatchUpdateCount]
- -[SBHLightSourceOverlayManager lightSourceManager]
- -[SBHLightSourceOverlayManager noteLightAngleDidUpdate]
- -[SBHLightSourceOverlayManager overlayWindow]
- -[SBHLightSourceOverlayManager setBatchUpdateCount:]
- -[SBHLightSourceOverlayManager setLastBatchUpdateCount:]
- -[SBHLightSourceOverlayManager updateOverlay]
- -[SBHLightSourceOverlayManager updateTimerDidFire:]
- -[SBHLightSourceOverlayManager updateTimer]
- -[SBIconImageView ICRIconLayer]
- -[SBIconImageView clearDisplayedICRIconLayerAfterDelayIfContentHidden]
- GCC_except_table1056
- GCC_except_table1104
- GCC_except_table1105
- GCC_except_table1107
- GCC_except_table1123
- GCC_except_table113
- GCC_except_table1130
- GCC_except_table120
- GCC_except_table135
- GCC_except_table154
- GCC_except_table166
- GCC_except_table186
- GCC_except_table187
- GCC_except_table190
- GCC_except_table205
- GCC_except_table235
- GCC_except_table237
- GCC_except_table240
- GCC_except_table244
- GCC_except_table263
- GCC_except_table274
- GCC_except_table294
- GCC_except_table298
- GCC_except_table301
- GCC_except_table302
- GCC_except_table308
- GCC_except_table314
- GCC_except_table333
- GCC_except_table344
- GCC_except_table363
- GCC_except_table388
- GCC_except_table405
- GCC_except_table424
- GCC_except_table436
- GCC_except_table439
- GCC_except_table444
- GCC_except_table454
- GCC_except_table459
- GCC_except_table463
- GCC_except_table466
- GCC_except_table469
- GCC_except_table477
- GCC_except_table487
- GCC_except_table492
- GCC_except_table505
- GCC_except_table511
- GCC_except_table52
- GCC_except_table534
- GCC_except_table536
- GCC_except_table543
- GCC_except_table572
- GCC_except_table577
- GCC_except_table601
- GCC_except_table625
- GCC_except_table769
- GCC_except_table779
- GCC_except_table782
- GCC_except_table791
- GCC_except_table793
- GCC_except_table795
- GCC_except_table797
- GCC_except_table802
- GCC_except_table804
- GCC_except_table806
- GCC_except_table808
- GCC_except_table813
- GCC_except_table819
- GCC_except_table822
- GCC_except_table926
- GCC_except_table980
- GCC_except_table996
- _OBJC_CLASS_$_CHSColorSchemePolicy
- _OBJC_CLASS_$_ICRIconLayer
- _OBJC_CLASS_$_LSSSubscriber
- _OBJC_CLASS_$_SBHIconImageContainerLayer
- _OBJC_CLASS_$_SBHLightSourceManager
- _OBJC_CLASS_$_SBHLightSourceManagerAssertion
- _OBJC_CLASS_$_SBHLightSourceOverlayManager
- _OBJC_CLASS_$_SBHSheenEffectView
- _OBJC_CLASS_$__TtC15SpringBoardHome22SBHIconImageCacheGroup
- _OBJC_IVAR_$_SBHIconImageContainerLayer._imageLayer
- _OBJC_IVAR_$_SBHIconImageIdentity._masked
- _OBJC_IVAR_$_SBHIconSettings._sheenEffectDebugUIEnabled
- _OBJC_IVAR_$_SBHIconSettings._sheenEffectFadeInSettings
- _OBJC_IVAR_$_SBHIconSettings._sheenEffectFadeOutSettings
- _OBJC_IVAR_$_SBHIconSettings._sheenEffectMinimumMovementToBecomeVisible
- _OBJC_IVAR_$_SBHIconSettings._sheenEffectStrength
- _OBJC_IVAR_$_SBHLightSourceManager._accumulatedDistance
- _OBJC_IVAR_$_SBHLightSourceManager._activeRefreshRate
- _OBJC_IVAR_$_SBHLightSourceManager._currentActivityLevel
- _OBJC_IVAR_$_SBHLightSourceManager._disableUpdatesAssertions
- _OBJC_IVAR_$_SBHLightSourceManager._displayIdentity
- _OBJC_IVAR_$_SBHLightSourceManager._iconSettings
- _OBJC_IVAR_$_SBHLightSourceManager._initialDistanceThreshold
- _OBJC_IVAR_$_SBHLightSourceManager._initialLightDirection
- _OBJC_IVAR_$_SBHLightSourceManager._initialVelocityThreshold
- _OBJC_IVAR_$_SBHLightSourceManager._lastLightAngle
- _OBJC_IVAR_$_SBHLightSourceManager._lastLightDirection
- _OBJC_IVAR_$_SBHLightSourceManager._lastLightDirection2
- _OBJC_IVAR_$_SBHLightSourceManager._lastLightIntensity
- _OBJC_IVAR_$_SBHLightSourceManager._lastLightTimestamp
- _OBJC_IVAR_$_SBHLightSourceManager._lastLightTimestamp2
- _OBJC_IVAR_$_SBHLightSourceManager._layers
- _OBJC_IVAR_$_SBHLightSourceManager._lightSourceDisplayLink
- _OBJC_IVAR_$_SBHLightSourceManager._lightSourceSubscription
- _OBJC_IVAR_$_SBHLightSourceManager._observers
- _OBJC_IVAR_$_SBHLightSourceManager._overlayManager
- _OBJC_IVAR_$_SBHLightSourceManager._reduceUpdateFreqencyAssertions
- _OBJC_IVAR_$_SBHLightSourceManager._updatesDisabled
- _OBJC_IVAR_$_SBHLightSourceManagerAssertion._invalidated
- _OBJC_IVAR_$_SBHLightSourceManagerAssertion._lightSourceManager
- _OBJC_IVAR_$_SBHLightSourceManagerAssertion._reason
- _OBJC_IVAR_$_SBHLightSourceManagerAssertion._type
- _OBJC_IVAR_$_SBHLightSourceOverlayManager._batchUpdateCount
- _OBJC_IVAR_$_SBHLightSourceOverlayManager._label
- _OBJC_IVAR_$_SBHLightSourceOverlayManager._lastBatchUpdateCount
- _OBJC_IVAR_$_SBHLightSourceOverlayManager._lightSourceManager
- _OBJC_IVAR_$_SBHLightSourceOverlayManager._overlayWindow
- _OBJC_IVAR_$_SBHLightSourceOverlayManager._updateTimer
- _OBJC_METACLASS_$_SBHIconImageContainerLayer
- _OBJC_METACLASS_$_SBHLightSourceManager
- _OBJC_METACLASS_$_SBHLightSourceManagerAssertion
- _OBJC_METACLASS_$_SBHLightSourceOverlayManager
- _OBJC_METACLASS_$_SBHSheenEffectView
- _OBJC_METACLASS_$__TtC15SpringBoardHome22SBHIconImageCacheGroup
- _SBHStringForLightSourceActivityLevel
- _UIScreenDidDisconnectNotification
- __CLASS_METHODS_SBHIconLayerView
- __DATA_SBHSheenEffectView
- __DATA__TtC15SpringBoardHome22SBHIconImageCacheGroup
- __INSTANCE_METHODS__TtC15SpringBoardHome22SBHIconImageCacheGroup
- __IVARS_SBHSheenEffectView
- __IVARS__TtC15SpringBoardHome22SBHIconImageCacheGroup
- __METACLASS_DATA_SBHSheenEffectView
- __METACLASS_DATA__TtC15SpringBoardHome22SBHIconImageCacheGroup
- __OBJC_$_CLASS_METHODS_SBHLightSourceManager
- __OBJC_$_CLASS_METHODS_SBHLightSourceOverlayManager
- __OBJC_$_CLASS_PROP_LIST_SBHLightSourceManager
- __OBJC_$_INSTANCE_METHODS_SBHIconImageContainerLayer
- __OBJC_$_INSTANCE_METHODS_SBHLightSourceManager
- __OBJC_$_INSTANCE_METHODS_SBHLightSourceManagerAssertion
- __OBJC_$_INSTANCE_METHODS_SBHLightSourceOverlayManager
- __OBJC_$_INSTANCE_METHODS_SBHSheenEffectView(SpringBoardHome)
- __OBJC_$_INSTANCE_VARIABLES_SBHIconImageContainerLayer
- __OBJC_$_INSTANCE_VARIABLES_SBHLightSourceManager
- __OBJC_$_INSTANCE_VARIABLES_SBHLightSourceManagerAssertion
- __OBJC_$_INSTANCE_VARIABLES_SBHLightSourceOverlayManager
- __OBJC_$_PROP_LIST_SBHIconImageContainerLayer
- __OBJC_$_PROP_LIST_SBHLightSourceManager
- __OBJC_$_PROP_LIST_SBHLightSourceManagerAssertion
- __OBJC_$_PROP_LIST_SBHLightSourceOverlayManager
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SBHLightSourceObserver
- __OBJC_$_PROTOCOL_METHOD_TYPES_SBHLightSourceObserver
- __OBJC_$_PROTOCOL_REFS_SBHLightSourceObserver
- __OBJC_CLASS_PROTOCOLS_$_SBHLightSourceManager
- __OBJC_CLASS_PROTOCOLS_$_SBHLightSourceManagerAssertion
- __OBJC_CLASS_PROTOCOLS_$_SBHLightSourceOverlayManager
- __OBJC_CLASS_PROTOCOLS_$_SBHSheenEffectView(SpringBoardHome)
- __OBJC_CLASS_RO_$_SBHIconImageContainerLayer
- __OBJC_CLASS_RO_$_SBHIconImageLayer
- __OBJC_CLASS_RO_$_SBHLightSourceManager
- __OBJC_CLASS_RO_$_SBHLightSourceManagerAssertion
- __OBJC_CLASS_RO_$_SBHLightSourceOverlayManager
- __OBJC_LABEL_PROTOCOL_$_SBHLightSourceObserver
- __OBJC_METACLASS_RO_$_SBHIconImageContainerLayer
- __OBJC_METACLASS_RO_$_SBHIconImageLayer
- __OBJC_METACLASS_RO_$_SBHLightSourceManager
- __OBJC_METACLASS_RO_$_SBHLightSourceManagerAssertion
- __OBJC_METACLASS_RO_$_SBHLightSourceOverlayManager
- __OBJC_PROTOCOL_$_SBHLightSourceObserver
- __PROPERTIES_SBHSheenEffectView
- __PROPERTIES__TtC15SpringBoardHome22SBHIconImageCacheGroup
- ___356+[SBFolderView _sortAndCategorizeIconListViews:scrolling:scrollingDirection:visibleRectProvider:outFullyVisibleIconListViews:outPrimaryDirection:outNotFullyVisibleIconListViewsInPrimaryDirection:outVisibleIconGridCellsInPrimaryDirection:outSecondaryDirection:outNotFullyVisibleIconListViewsInSecondaryDirection:outVisibleIconGridCellsInSecondaryDirection:]_block_invoke
- ___357+[SBFolderView _updateVisibleCellsPrefetchingNextIconIfPossible:maxPrefetchedCells:scrolling:defaultContentVisibility:fullyVisibleIconListViews:primaryDirection:notFullyVisibleIconListViewsInPrimaryDirection:visibleIconGridCellsInPrimaryDirection:secondaryDirection:notFullyVisibleIconListViewsInSecondaryDirection:visibleIconGridCellsInSecondaryDirection:]_block_invoke
- ___357+[SBFolderView _updateVisibleCellsPrefetchingNextIconIfPossible:maxPrefetchedCells:scrolling:defaultContentVisibility:fullyVisibleIconListViews:primaryDirection:notFullyVisibleIconListViewsInPrimaryDirection:visibleIconGridCellsInPrimaryDirection:secondaryDirection:notFullyVisibleIconListViewsInSecondaryDirection:visibleIconGridCellsInSecondaryDirection:]_block_invoke_2
- ___357+[SBFolderView _updateVisibleCellsPrefetchingNextIconIfPossible:maxPrefetchedCells:scrolling:defaultContentVisibility:fullyVisibleIconListViews:primaryDirection:notFullyVisibleIconListViewsInPrimaryDirection:visibleIconGridCellsInPrimaryDirection:secondaryDirection:notFullyVisibleIconListViewsInSecondaryDirection:visibleIconGridCellsInSecondaryDirection:]_block_invoke_3
- ___357+[SBFolderView _updateVisibleCellsPrefetchingNextIconIfPossible:maxPrefetchedCells:scrolling:defaultContentVisibility:fullyVisibleIconListViews:primaryDirection:notFullyVisibleIconListViewsInPrimaryDirection:visibleIconGridCellsInPrimaryDirection:secondaryDirection:notFullyVisibleIconListViewsInSecondaryDirection:visibleIconGridCellsInSecondaryDirection:]_block_invoke_4
- ___357+[SBFolderView _updateVisibleCellsPrefetchingNextIconIfPossible:maxPrefetchedCells:scrolling:defaultContentVisibility:fullyVisibleIconListViews:primaryDirection:notFullyVisibleIconListViewsInPrimaryDirection:visibleIconGridCellsInPrimaryDirection:secondaryDirection:notFullyVisibleIconListViewsInSecondaryDirection:visibleIconGridCellsInSecondaryDirection:]_block_invoke_5
- ___357+[SBFolderView _updateVisibleCellsPrefetchingNextIconIfPossible:maxPrefetchedCells:scrolling:defaultContentVisibility:fullyVisibleIconListViews:primaryDirection:notFullyVisibleIconListViewsInPrimaryDirection:visibleIconGridCellsInPrimaryDirection:secondaryDirection:notFullyVisibleIconListViewsInSecondaryDirection:visibleIconGridCellsInSecondaryDirection:]_block_invoke_6
- ___357+[SBFolderView _updateVisibleCellsPrefetchingNextIconIfPossible:maxPrefetchedCells:scrolling:defaultContentVisibility:fullyVisibleIconListViews:primaryDirection:notFullyVisibleIconListViewsInPrimaryDirection:visibleIconGridCellsInPrimaryDirection:secondaryDirection:notFullyVisibleIconListViewsInSecondaryDirection:visibleIconGridCellsInSecondaryDirection:]_block_invoke_7
- ___36-[SBIconListView setVisiblySettled:]_block_invoke
- ___43-[SBFolderView _prefetchNextIconIfPossible]_block_invoke
- ___53-[SBHLightSourceManager setUpLightSourceSubscription]_block_invoke
- ___55-[SBIconListModel directlyContainedIconWithIdentifier:]_block_invoke
- ___58-[SBHLightSourceManager _didAddLightSourceObserverInView:]_block_invoke
- ___66-[SBFolderIconImageView enumerateCurrentPageIconLayersUsingBlock:]_block_invoke
- ___70-[SBIconImageView clearDisplayedICRIconLayerAfterDelayIfContentHidden]_block_invoke
- ___91-[SBHAddWidgetSheetViewController _updateVisibleIconsInCellsPrefetchingNextIconIfPossible:]_block_invoke
- ___91-[SBHAddWidgetSheetViewController _updateVisibleIconsInCellsPrefetchingNextIconIfPossible:]_block_invoke_2
- ___SBHGetIconLayerFromCGImage_block_invoke
- ___SBHGetIconLayerFromIconServicesImage_block_invoke
- ___SBHGetIconLayerWithImageAppearance_block_invoke
- ___block_descriptor_107_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
- ___block_descriptor_40_e8_32bs_e30_v24?0"SBHIconLayerView"8^B16ls32l8
- ___block_descriptor_40_e8_32w_e8_v12?0C8lw32l8
- ___block_descriptor_49_e8_32s40s_e49_v32?0"SBHWidgetContainerViewController"8Q16^B24ls32l8s40l8
- ___block_descriptor_64_e8_32bs40r_e35_B32?0"NSArray"8"NSArray"16I24B28lr40l8s32l8
- ___block_descriptor_99_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
- ___managers
- __canPoolImageForIcon:.__poolOptOutCount
- _kCAFilterSoftLightBlendMode
- _kCGColorSpaceExtendedLinearSRGB
- _objc_copyStruct
- _swift_unknownObjectUnownedDestroy
- _swift_unknownObjectUnownedInit
- _swift_unknownObjectUnownedLoadStrong
- _swift_willThrowTypedImpl
- _symbolic So18SBHSheenEffectViewC
- _symbolic So18SBHSheenEffectViewCSgXw
- _symbolic So18SBHSheenEffectViewCXo
- _symbolic _____ 15SpringBoardHome22SBHIconImageCacheGroupC
- _symbolic _____ So27SBHLightSourceActivityLevelV
CStrings:
+ "%@/%@"
+ "<%{public}@> Skipping snapshot resize; invalid iconImageInfo size %@"
+ "B16@?0@\"SBHIconImageAppearance\"8"
+ "B24@?0@\"NSArray\"8I16B20"
+ "Blank CGImage found in %@"
+ "Cache miss for %@ as %{public}@ at %.0fx%.0f (%{public}@)"
+ "Cached additional %{public}@ app images at %.0fx%.0f (%llu): %@"
+ "Cached mitigated app images (%llu): %@"
+ "Cached mitigated app images at %.0fx%.0f (%llu): %@"
+ "Cached mitigated app mini images (%llu): %@"
+ "Cached mitigated app mini images at %.0fx%.0f (%llu): %@"
+ "Changing content visibility of folder controller %p from %{public}@ to %{public}@"
+ "Changing content visibility of folder view %p from %{public}@ to %{public}@"
+ "Changing content visibility of icon manager %p from %{public}@ to %{public}@"
+ "Changing content visibility of list view %p from %{public}@ to %{public}@"
+ "Drag cancel preview target has a bad frame: %@"
+ "Drag cancel preview target has a non-finite center: %@"
+ "Drag preview target does not have a window, has a bad frame, or has a non-finite center: %@"
+ "Finished additional %{public}@ pre-caching of %lu bundle identifiers at %.0fx%.0f in %fs (%llu)"
+ "Finished additional %{public}@ pre-caching of %lu icons at %.0fx%.0f in %fs (%llu)"
+ "Finished mitigated full-size pre-caching at %.0fx%.0f in %fs (%llu)"
+ "Finished mitigated full-size pre-caching of %lu icons at %.0fx%.0f for %{public}@ in %fs (%llu)"
+ "Finished mitigated mini pre-caching of %lu icons at %.0fx%.0f for %{public}@ in %fs (%llu)"
+ "LaunchServices notification"
+ "No icon location given to stack view controller"
+ "No image found in %@"
+ "Non-sRGB image returned from ISImage: %@"
+ "Reload icon image of %@ for reason '%{public}@'"
+ "Returning Cancel for drop in sessionDidUpdate because current policy handler does not handle this message (%@)"
+ "Returning Forbidden for drop in sessionDidUpdate because list view is not visible (%{public}@)"
+ "SBHIconStylePreviewManager applying style configuration trait: %{public}@"
+ "SBHIconStylePreviewManager invalidate"
+ "SBHIconStylePreviewManager prepare"
+ "SBHIconStylePreviewManager starting prefetch of %lu images of %{public}@"
+ "Skipping setCenter for dragged iconView %@ because centerForDraggedIconView returned non-finite (%f, %f)"
+ "SpringBoardHome.IconImageCacheGroup"
+ "Starting pre-caching via local cache for high-priority appearances %{public}@ icon size %.0fx%.0f (%llu)"
+ "UIImage * _Nullable SBHGetIconImageFromIconServicesImage(IFImage *__strong _Nonnull, SBIconImageInfo, SBHIconImageAppearance *__strong _Nonnull, SBHIconServicesOptions)"
+ "active data source did change"
+ "active data source did generate image"
+ "added list"
+ "added/removed icons"
+ "allow placeholder"
+ "always uses image for layer"
+ "b"
+ "bold text changed"
+ "bundleIdentifiers"
+ "calendar icon image provider changed"
+ "can fall back to image for layer"
+ "contained icons added/removed"
+ "deprecated reloadIconImage"
+ "drop session did update finished with drop operation: %li, badge style: %li, identifier %{public}@"
+ "exclude masked image"
+ "fast tint"
+ "file stack icon image provider changed"
+ "filters.tintColor.inputColor"
+ "force cancelled"
+ "force reload image"
+ "foreground only"
+ "iconImageLoadPriority"
+ "include unmasked image"
+ "isTemporaryFolderAllowed"
+ "locale changed"
+ "precache root icons (additional)"
+ "precache root icons (mitigated)"
+ "precache root mini icons (mitigated)"
+ "removed lists"
+ "replaced icon"
+ "v16@?0@\"NSMutableArray\"8"
+ "\xa1!1Q"
- "%lu layers\n%lu observers\nActivity level: %li\nUpdate rate: %lu㎐\nAngle: %.1fº\nDirection: (%.2f,%.2f,%.2f)\nIntensity: %.2f\nInitial direction: (%.2f,%.2f,%.2f)\nDistance: %.2f (accum: %.2f, thres: %.2f)\nVelocity: %.2f"
- "<unknown: %lu>"
- "B32@?0@\"NSArray\"8@\"NSArray\"16I24B28"
- "CacheLoadingIcon"
- "Changing icon manager content visibility to %{public}@"
- "Drag preview target does not have a window or has a bad frame: %@"
- "Fade In"
- "Fade Out"
- "Light angle pause reason '%{public}@' did invalidate"
- "Light angle update frequency reason '%{public}@' did invalidate"
- "Light source update activity level changed: %li -> %li"
- "Minimum Movement (Degrees)"
- "Pausing light angle update display link"
- "Pausing light angle updates for reason '%{public}@'"
- "ReadGooder"
- "Reducing light angle update frequency for reason '%{public}@'"
- "Removing layer %p"
- "Removing observer %p"
- "SBHLightSourceManagerAssertion not invalidated in dealloc"
- "SBHUseIconServicesCache"
- "Sheen Effect"
- "SpringBoardHome.SBHIconImageCacheGroup"
- "SpringBoardHome/SheenEffectView.swift"
- "Starting light angle updates"
- "Starting pre-caching via local cache for high-priority appearances %{public}@ (%llu)"
- "Strength"
- "Updating icon light angle to %f (%fº)"
- "active (low power)"
- "areUpdatesDisabled"
- "currentActivityLevel"
- "idle"
- "isMasked"
- "lightSourceManager"
- "occasional"
- "read gooder is enabled: %@"
- "sheenEffectDebugUIEnabled"
- "sheenEffectFadeInSettings"
- "sheenEffectFadeOutSettings"
- "sheenEffectMinimumMovementToBecomeVisible"
- "sheenEffectStrength"
- "use init(frame:) instead"
- "v12@?0C8"
- "v24@?0@\"SBHIconLayerView\"8^B16"
- "\x84"
- "\x91!1Q"
```
