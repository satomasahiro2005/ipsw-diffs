## ToneKit

> `/System/Library/PrivateFrameworks/ToneKit.framework/ToneKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x268c0` | `0x26858` | **`-0x68`** |

### Other Changes

```diff

-670.1.0.0.0
+671.0.0.0.0
Functions:
~ -[TKTonePickerController _invalidatePickerItemCaches] : 672 -> 664
~ -[TKTonePickerController _reloadTonesForExternalChange:shouldSkipDelegateFullReload:] : 3240 -> 3232
~ ___53-[TKTonePickerController toneStoreDownloadsDidStart:]_block_invoke_2 : 708 -> 704
~ ___56-[TKTonePickerController toneStoreDownloadsDidProgress:]_block_invoke : 644 -> 640
~ ___54-[TKTonePickerController toneStoreDownloadsDidFinish:]_block_invoke : 1172 -> 1156
~ -[TKTonePickerViewController dealloc] : 704 -> 700
~ ___87-[TKTonePickerViewController _handlePreferredContentSizeCategoryDidChangeNotification:]_block_invoke : 428 -> 424
~ -[TKTonePickerViewController setShowsMedia:] : 740 -> 736
~ -[TKTonePickerViewController addMediaItems:] : 392 -> 388
~ -[TKTonePickerViewController updateDividerContentColorToMatchSeparatorColorInTableView:] : 380 -> 376
~ ___74-[TKTonePickerViewController layoutMarginsDidChangeInTonePickerTableView:]_block_invoke : 340 -> 336
~ -[TKTonePickerViewController tonePickerController:didDeletePickerRowItems:] : 800 -> 796
~ -[TKTonePickerViewController tonePickerController:didDeleteTonePickerSectionItems:] : 324 -> 320
~ -[TKTonePickerViewController tonePickerController:didInsertPickerRowItems:] : 800 -> 796
~ -[TKTonePickerViewController tonePickerController:didInsertTonePickerSectionItems:] : 324 -> 320
~ -[TKTonePickerViewController tonePickerController:didUpdateHeaderTextOfTonePickerSectionItems:] : 324 -> 320
~ -[TKTonePickerViewController tonePickerControllerRequestsMediaItemsRefresh:] : 544 -> 540
~ -[TKToneClassicsTableViewController layoutMarginsDidChangeInTonePickerTableView:] : 388 -> 384
~ -[TKVibrationPickerViewController _sortedArrayWithVibrationIdentifiers:allowsDuplicateVibrationNames:] : 836 -> 828
~ -[TKVibrationPickerViewController _adjustedNameForVibrationWithDesiredName:vibrationIdentifier:] : 952 -> 956
~ -[TKVibrationPickerViewController _updateCheckedStateOfAllVisibleCells] : 336 -> 332
~ -[TKVibrationPickerViewController tableView:didSelectRowAtIndexPath:] : 832 -> 828
~ ___55-[TKVibrationPickerViewController setEditing:animated:]_block_invoke : 1260 -> 1252
~ -[TKVibrationRecorderProgressView clearAllVibrationComponents] : 300 -> 296
~ -[TKVibrationRecorderRippleView _currentSpeed] : 540 -> 548
~ -[TKVibrationRecorderRippleView layoutSubviews] : 444 -> 440
~ -[TKVibrationRecorderTouchSurfaceRecordedDataWrapper _updateMaximumFramesPerSecondRate:] : 448 -> 464
~ -[TKDownloadIndicatorView _stopProgressAnimation] : 420 -> 416
~ -[UIView(TKConstraintBasedLayout) _tk_recursiveAutolayoutTraceAtLevel:anyDescendantHasAmbiguousLayout:] : 492 -> 488
```
