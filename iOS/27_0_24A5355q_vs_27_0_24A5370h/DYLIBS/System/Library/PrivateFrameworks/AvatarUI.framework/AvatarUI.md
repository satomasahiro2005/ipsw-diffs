## AvatarUI

> `/System/Library/PrivateFrameworks/AvatarUI.framework/AvatarUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc1764` | `0xc1530` | **`-0x234`** |

### Other Changes

```diff

-402.100.1.0.0
+403.100.1.0.0
Functions:
~ -[AVTAvatarAttributeEditorCategory initWithSectionProviders:localizedName:previewMode:modelGroup:symbolNames:] : 540 -> 536
~ ___86-[AVTAvatarRecordImageGenerator updateThumbnailsForChangesWithTracker:recordProvider:]_block_invoke : 444 -> 440
~ ___86-[AVTAvatarRecordImageGenerator updateThumbnailsForChangesWithTracker:recordProvider:]_block_invoke_3 : 504 -> 500
~ -[AVTAvatarAttributeEditorPreloader cancelAllPreloading] : 360 -> 356
~ -[AVTInMemoryResourceCache nts_evictObjectsToFreeUpCost:] : 540 -> 536
~ -[AVTAvatarAttributeEditorCategory(AVTPresetResourcesProviding) representedAVTPresetResources] : 556 -> 552
~ +[AVTGroupDial estimatedContentWidthForTitleSizes:] : 328 -> 324
~ -[AVTGroupDial cacheTitleSizes] : 528 -> 524
~ -[AVTBodyCarouselController updateStickersforVisibleCells] : 268 -> 264
~ -[AVTCoalescingInvertingTaskScheduler startTasksFrom:] : 520 -> 516
~ -[AVTEdgeDisappearingCollectionViewLayout layoutAttributesForElementsInRect:] : 472 -> 468
~ -[AVTAvatarInlineActionsController setButtonsDisabled:] : 264 -> 260
~ -[AVTStickerSheetController sheetDidDisappear] : 460 -> 456
~ -[AVTStickerSheetController discardStickerItems] : 260 -> 256
~ -[AVTStickerSheetController areAllStickersRendered] : 304 -> 300
~ +[AVTPoseSelectionViewController poseConfigurationsForTypes:avatarRecord:] : 728 -> 720
~ -[AVTAvatarAttributeEditorDataSource updateCoordinatorsFromCategory:currentCoordinators:] : 896 -> 888
~ -[AVTAvatarAttributeEditorDataSource discardControllersForNonCurrentCategory] : 444 -> 440
~ -[AVTAvatarAttributeEditorDataSource groupPickerItemsForCategories] : 420 -> 416
~ -[AVTAvatarAttributeEditorDataSource sectionProviderForSectionAtIndex:inCategoryAtIndex:] : 380 -> 376
~ -[AVTAvatarConfiguration(AVTCacheableResource) volatileIdentifierForScope:] : 920 -> 912
~ -[AVTStickerPagingController didEndDisplaying] : 296 -> 292
~ -[AVTStickerPagingController collectionView:prefetchItemsAtIndexPaths:] : 308 -> 304
~ -[AVTStickerPagingController collectionView:cancelPrefetchingForItemsAtIndexPaths:] : 308 -> 304
~ +[AVTAvatarAttributeEditorSectionController maxLabelHeightInSection:fittingWidth:] : 512 -> 508
~ +[AVTAvatarAttributeEditorSectionController shouldHideLabelBackgroundInSection:fittingWidth:] : 660 -> 656
~ +[AVTMultiAvatarController listItemsForAvatarRecords:] : 348 -> 344
~ -[AVTStickerRecentsMigrator performMigrationIfNeeded] : 1208 -> 1196
~ -[AVTAttributeEditorSectionHeaderView updateMenu] : 560 -> 556
~ -[AVTAvatarLibraryModel numberOfRecords] : 292 -> 288
~ -[AVTAvatarLibraryModel libraryItemsFromAvatarRecords:] : 444 -> 440
~ -[AVTAvatarLibraryModel presetShareSheetWithRecords:fromItem:] : 520 -> 516
~ +[AVTStickerRecentsPresetsProvider filteredAndPaddedStickerRecordsWithRecents:excludingRecords:paddingMemojiIdentifier:avatarStore:numberOfStickers:resultBlock:] : 900 -> 892
~ +[AVTStickerRecentsPresetsProvider filteredRecentStickers:withAvailableRecordIdentifiersMap:] : 392 -> 388
~ +[AVTStickerRecentsPresetsProvider paddedStickerRecordsWithRecents:excludingRecords:paddingMemojiIdentifier:numberOfStickers:] : 856 -> 852
~ -[AVTCoreModelFramingModeOverrides initWithCameraOverrides:] : 852 -> 848
~ +[AVTArrayPairClassification clustersForObjectsInArray:withClassifier:likenessThreshold:likenessComparator:] : 656 -> 652
~ -[AVTAvatarAttributeEditorModelManager buildIntitialColorsState] : 832 -> 828
~ -[AVTAvatarAttributeEditorModelManager updateAvatarByDeletingSectionItems:animated:] : 492 -> 488
~ -[AVTAvatarAttributeEditorModelManager updateAvatarByApplyingPresetOverrides:animated:] : 420 -> 416
~ -[AVTEditingModelDefinitionsParser parseCoreModelFromGroupsDefinitions:colorDefaultsDefinitions:] : 748 -> 744
~ -[AVTEditingModelDefinitionsParser coreModelGroupFromGroupDictionary:] : 1032 -> 1028
~ -[AVTEditingModelDefinitionsParser coreModelMulticolorPickerForDictionary:groupPickerCategory:defaultOptions:parsedPickerKeys:error:] : 1876 -> 1852
~ -[AVTEditingModelDefinitionsParser multicolorAuxiliaryPickerForDictionary:error:] : 828 -> 824
~ -[AVTEditingModelDefinitionsParser coreModelPresetsForCategory:] : 440 -> 436
~ -[AVTEditingModelDefinitionsParser gatherAllTagsFromPresets:] : 436 -> 432
~ +[AVTFunCamAvatarPickerController itemsFromRecords:] : 332 -> 328
~ -[AVTFunCamAvatarPickerController selectAvatarRecordWithIdentifier:animated:] : 564 -> 560
~ -[AVTPresetResourceLoader performPresetResourcesPreloadingTask:] : 412 -> 408
~ -[AVTAvatarAttributeEditorFlowLayout layoutAttributesForElementsInRect:] : 304 -> 300
~ -[AVTAvatarLibraryViewController updateVisibleHeaders] : 368 -> 364
~ -[AVTAttributeValueView relayoutSublayers] : 672 -> 668
~ -[NSData(AvatarUI) avt_SHA256] : 224 -> 232
~ +[AVTAvatarConfiguration configurationFromAvatar:coreModel:] : 1436 -> 1428
~ -[AVTAvatarConfiguration removePresetsForSettingKind:storage:] : 396 -> 392
~ -[AVTAvatarConfiguration presetsForStorage:] : 360 -> 356
~ -[AVTSelectableStickerSheetController sheetDidDisappear] : 444 -> 440
~ -[AVTSelectableStickerSheetController discardStickerItems] : 272 -> 268
~ -[AVTSelectableStickerSheetController areAllStickersRendered] : 312 -> 308
~ -[AVTColorSlider relayoutSublayers] : 300 -> 296
~ -[AVTStickerRecentsSwiftProvider fetchRecents:excludingStickersMatchingRules:] : 1756 -> 1752
~ -[AVTUsageTrackingSession nts_reportAvatarLikenessClustersWithClient:] : 1124 -> 1120
~ +[AVTImageValidator _calculateStatistics:withSize:] : 792 -> 760
~ +[AVTStickerSheetModel sheetModelForAvatarRecord:withConfigurations:cache:taskScheduler:renderingQueue:encodingQueue:stickerGeneratorPool:imageProvider:environment:] : 856 -> 852
~ ___98+[AVTAvatarConfigurationMetric enumerateDifferencesFromConfiguration:toConfiguration:withHandler:]_block_invoke : 484 -> 472
~ ___61-[AVTUIStickerPlaceholderProviderFactory placeholderProvider]_block_invoke_2 : 352 -> 348
~ ___120+[AVTAvatarUpdaterFactory updaterForColor:variationOverride:colorsState:pairedColors:additionalColor:saveToColorsState:]_block_invoke : 912 -> 908
~ ___57+[AVTAvatarUpdaterFactory updaterForAggregatingUpdaters:]_block_invoke : 268 -> 264
~ -[AVTAvatarAttributeEditorMulticolorSectionProvider sections] : 572 -> 568
~ ___76-[AVTStickerTaskScheduler cancelStickerSheetTasksForAvatarRecordIdentifier:]_block_invoke : 376 -> 372
~ -[AVTStickerTaskScheduler nextPickerThumbnailFromTasksStorage:allAvatarRecordIdentifiers:] : 408 -> 404
~ -[AVTStickerTaskScheduler nextPickerThumbnailFromTasksBacklogStorage:allAvatarRecordIdentifiers:] : 408 -> 404
~ -[AVTStickerTaskScheduler nextVisibleSelectedSheetStickerFromTasksStorage:selectedAvatarRecordIdentifier:visibleIndexPaths:] : 676 -> 672
~ -[AVTStickerTaskScheduler nextSheetPlaceHolderFromTasksStorage:allAvatarRecordIdentifiers:] : 408 -> 404
~ -[AVTStickerTaskScheduler nextSheetStickerFromTasksStorage:allAvatarRecordIdentifiers:] : 440 -> 436
~ +[AVTAvatarAttributeEditorMulticolorSectionPickerController estimatedContentWidthForTitleSizes:items:] : 492 -> 488
~ -[AVTAvatarAttributeEditorMulticolorSectionPickerController cacheTitleSizes] : 556 -> 552
~ -[AVTAvatarAttributeEditorModel differenceFromModel:] : 952 -> 948
~ +[AVTMultiAvatarController(Snapshotting) snapshotProviderFocusedOnRecordWithIdentifier:size:avtViewAspectRatio:dataSource:environment:] : 972 -> 968
~ -[AVTTransitionCoordinator cancelAllTransitions] : 352 -> 348
~ -[AVTTouchDownGestureRecognizer gestureRecognizer:shouldReceiveTouch:] : 416 -> 412
~ +[AVTAvatarAttributeEditorModelBuilder buildDataSourceCategoriesFromCoreModel:selectingFromAvatarConfiguration:imageProvider:colorLayerProvider:stickerRenderer:modelManager:withSelectedCategory:atIndex:] : 1260 -> 1252
~ +[AVTAvatarAttributeEditorModelBuilder sectionProvidersForCoreModelCategory:platform:modelManager:pairingPickers:editingColors:colorDefaultsProvider:previousSectionMap:imageProvider:colorLayerProvider:stickerRenderer:configuration:displayConditionEvaluator:] : 2168 -> 2152
~ +[AVTAvatarAttributeEditorModelBuilder selectedModelPresetForSelectedPreset:inPresetsList:] : 364 -> 360
~ +[AVTAvatarAttributeEditorModelBuilder multicolorSectionProviderForCoreMulticolorPicker:platform:configuration:imageProvider:colorLayerProvider:editingColors:colorDefaultsProvider:modelManager:previousSectionMap:pairingPickers:] : 3864 -> 3884
~ +[AVTAvatarAttributeEditorModelBuilder sectionColorItemsForColors:selectedPreset:configuration:modelManager:additionalUpdateKind:imageProvider:colorLayerProvider:pairedCategory:editingColors:] : 872 -> 864
~ +[AVTAvatarAttributeEditorModelBuilder sectionForModelRow:fromModelPresets:selectedModelPreset:tagSelection:fixedTags:availableTags:category:imageProvider:stickerRenderer:configuration:previousSection:pairedCategory:] : 1956 -> 1940
~ +[AVTAvatarAttributeEditorModelBuilder framingModeForRow:selectedPreset:] : 536 -> 528
~ +[AVTAvatarAttributeEditorModelBuilder filterPresets:forRowRepresentingTags:currentTagSelection:fixedTags:availableTags:sortingOption:] : 920 -> 916
~ +[AVTAvatarAttributeEditorModelBuilder tagCombinationsForTagNames:availableTags:] : 840 -> 836
~ +[AVTAvatarAttributeEditorModelBuilder tagSetByRemovingTagNames:fromTagSet:] : 304 -> 300
~ +[AVTAvatarAttributeEditorModelBuilder filterPresets:matchingTagValues:sortedUsing:] : 672 -> 668
~ +[AVTAvatarAttributeEditorModelBuilder scoreForTags:forCombination:currentSelection:] : 576 -> 568
~ +[AVTAvatarAttributeEditorModelBuilder tagSetForTagNames:inTagSet:] : 384 -> 380
~ +[AVTAvatarAttributeEditorState buildStateFromCoreModel:avatarConfiguration:] : 1576 -> 1572
~ ___74-[AVTFaceTrackingManager layoutMonitorDidUpdateDisplayLayout:withContext:]_block_invoke : 596 -> 592
~ -[AVTAvatarAttributeEditorViewController notifyingContainerViewDidChangeSize:] : 480 -> 476
~ -[AVTAvatarAttributeEditorViewController maxGroupLabelWidth] : 408 -> 404
~ ___93-[AVTAvatarAttributeEditorViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke : 528 -> 524
~ -[AVTAvatarAttributeEditorViewController selectedItemInSection:] : 340 -> 336
~ -[AVTAvatarAttributeEditorViewController collectionView:prefetchItemsAtIndexPaths:] : 328 -> 324
~ -[AVTAvatarAttributeEditorViewController collectionView:cancelPrefetchingForItemsAtIndexPaths:] : 296 -> 292
~ +[AVTAvatarAttributeEditorSectionColorDataSource selectedItemFromItems:] : 284 -> 280
~ -[AVTStickerConfigurationProvider stickerConfigurationsForAvatarRecord:] : 572 -> 568
~ -[AVTStickerConfigurationProvider stickerConfigurationForAvatarRecord:stickerName:] : 372 -> 368
~ -[AVTStickerConfigurationProvider availableStickerNamesForAvatarRecord:] : 428 -> 424
~ -[AVTStickerConfigurationProvider filteredStickerConfigurations:] : 508 -> 504
~ -[UICollectionViewLayout(AVTCollectionViewLayout) indexesForElementsInRect:visibleBounds:numberOfItems:] : 432 -> 428
~ -[AVTImageStore deleteImagesForItemsWithPersistentIdentifierPrefix:error:] : 580 -> 576
~ -[AVTImageStore copyImagesForPersistentIdentifierPrefix:toPersistentIdentifierPrefix:error:] : 788 -> 784
~ -[AVTZIndexEngagementListCollectionViewLayout layoutAttributesForElementsInRect:] : 332 -> 328
~ +[AVTEditingModelColors buildAllColors] : 332 -> 328
~ ___93+[AVTEditingModelColors createColorsForPaletteCategory:inCache:withDerivedPaletteCategories:]_block_invoke : 932 -> 920
~ -[AVTEditingModelColors colorHasDerivedColorDependency:] : 844 -> 840
~ -[AVTAvatarAttributeEditorSectionCoordinator attributeEditorSectionController:didUpdateSectionItem:] : 384 -> 380
~ -[AVTAggregateCacheableResource requiresEncryption] : 256 -> 252
~ -[AVTAggregateCacheableResource identifierForScope:persistent:] : 504 -> 500
```
