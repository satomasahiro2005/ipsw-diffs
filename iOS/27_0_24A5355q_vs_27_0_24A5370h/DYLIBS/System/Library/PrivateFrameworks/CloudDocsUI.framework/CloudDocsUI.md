## CloudDocsUI

> `/System/Library/PrivateFrameworks/CloudDocsUI.framework/CloudDocsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2cb68` | `0x2cac8` | **`-0xa0`** |

### Other Changes

```text
Functions:
~ -[BRUITestDiagnostic writeToDiskWithError:] : 872 -> 868
~ -[_UIDocumentListController selectedItems] : 400 -> 396
~ -[_UIDocumentListController setSelectedItems:] : 396 -> 392
~ +[_UIDocumentListController _listControllerHierarchyForURL:withConstructorBlock:] : 728 -> 724
~ -[BRGeometry gatherSubviews:] : 408 -> 404
~ -[BRGeometry initWithView:rootView:] : 628 -> 624
~ _appendDescription : 388 -> 384
~ -[BRGeometry isValidForGeometryValidation:offendingGeometry:] : 360 -> 356
~ +[UIView(BRGeometry) br_setGatherBehaviour:forClassesNamed:] : 388 -> 384
~ -[UIView(BRGeometry) br_viewIsClipped] : 664 -> 656
~ -[_UIDocumentPickerCloudDirectoryObserver initWithScopes:delegate:] : 728 -> 724
~ -[_UIDocumentPickerCloudDirectoryObserver _updateQuery] : 1068 -> 1064
~ -[_UIDocumentPickerCloudDirectoryObserver _initialGatherFinished:] : 764 -> 760
~ ___58-[_UIDocumentPickerCloudDirectoryObserver setStaticItems:]_block_invoke : 468 -> 464
~ ___61-[_UIDocumentPickerCloudDirectoryObserver isVisiblePredicate]_block_invoke : 368 -> 364
~ +[_UIDocumentPickerURLContainerModel _tagColorsDidChange] : 868 -> 864
~ -[_UIDocumentPickerURLContainerModel shouldEnableContainer:] : 364 -> 360
~ -[_UIDocumentPickerURLContainerModel shouldAllowPickingType:] : 348 -> 344
~ -[_UIDocumentPickerURLContainerModel shouldShowContainerForType:] : 340 -> 336
~ -[_UIDocumentPickerURLContainerModel arrayController:modelChanged:differences:] : 600 -> 596
~ -[_UIDocumentPickerRootContainerModel _containerListDidChange] : 504 -> 500
~ +[_UIDocumentPickerContainerItem(Icons) _blockingBadgeForContainer:size:scale:] : 848 -> 844
~ +[_UIDocumentPickerContainerItem(Icons) _blockingFolderIconForURL:container:size:scale:] : 1048 -> 1060
~ ___49+[BRObservableFile _applicationWillResignActive:]_block_invoke : 608 -> 604
~ +[BRObservableFile _applicationDidBecomeActive:] : 576 -> 572
~ -[_UIDocumentTargetSelectionController _commonInitItems:crossContainer:sourceContainer:] : 1064 -> 1052
~ -[_UIDocumentTargetSelectionController initForCrossContainerMoveWithItemsToMove:] : 488 -> 484
~ +[_UIDocumentPickerDescriptor allPickers] : 1172 -> 1168
~ -[_UIDocumentPickerDescriptor pickerEnabledForMode:documentTypes:reason:] : 792 -> 788
~ -[_UIDocumentPickerDescriptor nonUIBundle] : 432 -> 428
~ __CDAdaptLocalizedStringForItemType : 492 -> 488
~ -[_UIDocumentPickerLocalDirectoryObserver initWithScopes:delegate:] : 784 -> 780
~ ___58-[_UIDocumentPickerLocalDirectoryObserver setStaticItems:]_block_invoke : 464 -> 460
~ -[_UIDocumentPickerLocalDirectoryObserver gatherResultsForSource:] : 440 -> 436
~ -[_UIDocumentPickerLocalDirectoryObserver gatherResults] : 404 -> 400
~ ___56-[_UIDocumentPickerLocalDirectoryObserver initialUpdate]_block_invoke : 368 -> 364
~ -[_UIDocumentPickerOverviewViewController updateContents] : 620 -> 616
~ ___95-[_UIDocumentPickerDocumentCollectionViewController containersChangedWithSnapshot:differences:]_block_invoke : 624 -> 616
~ -[_UIDocumentPickerDocumentCollectionViewController setIndexPathsForSelectedItems:] : 280 -> 276
~ -[_UIDocumentPickerAllContainersModel startMonitoringChanges] : 664 -> 660
```
