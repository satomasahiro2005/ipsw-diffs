## Widgets

> `/System/Library/PrivateFrameworks/Widgets.framework/Widgets`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48708` | `0x485e4` | **`-0x124`** |

### Other Changes

```text
Functions:
~ -[WGWidgetVisibilityManager _widgetTagsForWidgetExtensionInfoDictionary:] : 412 -> 408
~ -[WGWidgetVisibilityManager _allWidgetTags] : 312 -> 308
~ -[WGWidgetVisibilityManager _updateWidgetTagsAndVisibilityForExtensions:] : 636 -> 628
~ -[WGWidgetVisibilityManager _updateWidgetVisibilityPreferences] : 276 -> 272
~ -[WGWidgetVisibilityManager _updateMobileGestaltQuestions] : 752 -> 748
~ -[WGWidgetViewController viewDidMoveToWindow:shouldAppearOrDisappear:] : 376 -> 372
~ -[_WGConcreteDataSource dataSource:replaceWithDatum:observerUpdateBlock:] : 344 -> 340
~ -[_WGConcreteDataSource dataSource:removeDatumWithIdentifier:observerUpdateBlock:] : 360 -> 356
~ -[WGWidgetDataSourceManager _updatePublishedWidgetExtensions:] : 912 -> 904
~ -[WGWidgetListEditViewController _loadItems] : 1188 -> 1180
~ -[WGWidgetListEditViewController _saveItemArrangement] : 504 -> 508
~ ___74-[WGWidgetListEditViewController _acknowledgeItemsAndResetNewWidgetsCount]_block_invoke : 244 -> 240
~ -[WGWidgetDiscoveryController _orderedEnabledIdentifiersForGroup:] : 92 -> 88
~ -[WGWidgetDiscoveryController _invalidateVisibleIdentifiersForGroup:] : 132 -> 128
~ -[WGWidgetDiscoveryController _applicationIconChanged:] : 440 -> 436
~ -[WGWidgetDiscoveryController handleWidgetLaunchRecommendation:completion:] : 884 -> 880
~ -[WGWidgetDiscoveryController _dataSourcesDidChange:] : 872 -> 860
~ ___63-[WGWidgetDiscoveryController _calculateAndPostNewWidgetsCount]_block_invoke : 552 -> 548
~ -[WGWidgetDiscoveryController _notifyObserversOfVisibilityChange:ofWidgetWithIdentifier:inGroup:] : 392 -> 388
~ -[WGWidgetDiscoveryController _notifyObserversOfSignificantWidgetsChange] : 300 -> 296
~ -[WGWidgetDiscoveryController _notifyObserversOfOrderChangeForWidgetIdentifiers:] : 316 -> 312
~ -[WGWidgetDiscoveryController widgetListEditViewController:didReorderItemsWithIdentifiersInGroups:] : 424 -> 420
~ -[WGWidgetDiscoveryController widgetListEditViewController:setEnabled:forItemsWithIdentifiers:] : 300 -> 296
~ -[WGWidgetDiscoveryController widgetListEditViewController:acknowledgeInterfaceItemsWithIdentifiers:] : 260 -> 256
~ ___63-[WGWidgetDiscoveryController deviceManagementPolicyDidChange:]_block_invoke : 508 -> 504
~ -[WGWidgetInfo updatePreferredContentSize:forWidgetHost:] : 376 -> 372
~ -[WGWidgetPlatterView _updateHeaderContentViewVisualStyling] : 356 -> 352
~ -[WGCarouselListViewController setVisuallyRevealed:withSlowAnimation:] : 952 -> 948
~ -[WGCarouselListViewController _createPropertiesForStackViewUpdate] : 376 -> 372
~ -[WGCarouselListViewController _stackViewArrangedSubviewsTransformPresentationValueChanged] : 712 -> 696
~ -[WGCarouselListViewController _updateCarouselEffect] : 2868 -> 2832
~ -[WGWidgetListViewController setShouldBlurContent:] : 320 -> 316
~ -[WGWidgetListViewController _repopulateStackViewWithWidgetIdentifiers:] : 504 -> 496
~ -[WGWidgetListViewController _createPropertiesForStackViewUpdate] : 388 -> 384
~ -[WGWidgetListViewController _stackViewArrangedSubviewsTransformPresentationValueChanged] : 280 -> 276
~ -[WGWidgetListViewController _pruneAlternateCaptureOnlyMaterialViews] : 604 -> 596
~ -[WGWidgetListViewController _invalidateAllAlternateCaptureOnlyMaterialViews] : 276 -> 272
~ -[WGWidgetListViewController _invalidateAllCancelTouchesAssertions] : 300 -> 296
~ -[WGWidgetListViewController _updateWidgetViewStateWithPreviouslyVisibleWidgetIdentifiers:] : 768 -> 764
~ -[WGWidgetListViewController widgetDiscoveryController:orderDidChangeForWidgetIdentifiers:] : 736 -> 732
~ -[WGDataSourceManager childDataSourceManagerDataSourcesDidChange:] : 288 -> 284
~ _WGTodayViewArchiveGetArchive : 2144 -> 2136
~ _WGTodayViewArchiveSetOrderedIdentifiersInGroup : 376 -> 372
~ __WGTodayViewArchiveMigrateOrderForNewDefaultWidgetsInGroup : 532 -> 528
~ -[WGWidgetListFooterView setVisibleWidgetsIDs:] : 644 -> 636
~ -[WGWidgetListFooterView setDelegate:] : 384 -> 380
~ -[WGWidgetListFooterView sizeThatFits:] : 616 -> 612
~ -[WGWidgetListFooterView layoutSubviews] : 1252 -> 1248
~ -[WGWidgetListFooterView invalidateSubviewGeometery] : 288 -> 284
~ -[WGWidgetListFooterView setLegibilitySettings:] : 388 -> 384
~ ___80-[WGMajorListViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke_2 : 360 -> 356
~ -[WGWidgetEventTracker widgetListDidAppearAtLocation:withEnabledWidgets:disabledWidgets:] : 596 -> 588
~ ___51-[WGWidgetDataSource addWidgetObserver:completion:]_block_invoke : 316 -> 312
~ ___85-[WGWidgetHostingViewController _removeAllSnapshotFilesMatchingPredicate:dueToIssue:]_block_invoke : 1064 -> 1060
```
