## FocusUI

> `/System/Library/PrivateFrameworks/FocusUI.framework/FocusUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23eb0` | `0x23e00` | **`-0xb0`** |

### Other Changes

```diff

-498.0.1.0.0
+502.0.100.0.0
Functions:
~ -[FCUIActivityPickerViewController _updateSelectedStateOfActivityControl:activeActivity:lifetimeOfActiveActivity:] : 580 -> 576
~ -[FCUIActivityPickerViewController _updateSelectedStateOfActivityViews] : 436 -> 432
~ -[FCUIActivityPickerViewController _configureActivityView:withLifetimesDescriptionsForActivity:] : 912 -> 908
~ -[FCUIActivityPickerViewController _configureActivityListViewWithAvailableActivities:] : 1572 -> 1596
~ -[FCUIFocusEnablementIndicatorBannerPresentable _enumerateObserversRespondingToSelector:usingBlock:] : 324 -> 320
~ -[FCUIFocusSelectionViewController _configureActivityListView] : 616 -> 612
~ -[FCUIFocusEnablementIndicatorBannerManager _postActivity:enabled:forPreviewing:withOptions:] : 616 -> 612
~ -[FCUIActivityControl _configureMenuViewIfNecessary] : 412 -> 408
~ -[FCUICAPackageView initWithURL:] : 720 -> 716
~ ___44+[FCUICAPackageView packageViewForActivity:]_block_invoke : 524 -> 520
~ -[FCUIActivityListView _setExpandedFrame:initialFrame:representedActivity:anchorActivityView:collapsedSizeBlock:preludeBlock:activityViewAnimationBlock:transitionCoordinator:] : 1832 -> 1824
~ ___110-[FCUIActivityListView _setExpandedFrame:initialFrame:viaResizeWithRepresentedActivity:transitionCoordinator:]_block_invoke_5 : 492 -> 484
~ -[FCUIActivityListView setExpandedActivityView:withTransitionCoordinator:] : 592 -> 580
~ -[FCUIActivityListView isolateActivityView:withInset:] : 444 -> 440
~ -[FCUIActivityListView endIsolation] : 328 -> 324
~ -[FCUIActivityListView _setContractedFrame:viaScaleWithRepresentedActivity:transitionCoordinator:] : 972 -> 968
~ -[FCUIActivityListView _setContractedFrame:viaResizeWithRepresentedActivity:transitionCoordinator:] : 580 -> 576
~ -[FCUIActivityListContentView subviewFramesInBounds:] : 1844 -> 1808
~ -[FCUIActivityListContentView layoutSubviews] : 1456 -> 1444
~ -[FCUIActivityListContentView setAdjustsFontForContentSizeCategory:] : 320 -> 316
~ -[FCUIActivityListContentView adjustForContentSizeCategoryChange] : 328 -> 324
~ -[FCUIActivityListContentView _sizeThatFits:collapsedToPill:includingFooter:forceMeasurement:] : 592 -> 588
~ -[FCUIActivityControlMenuView menuItemActions] : 324 -> 320
~ -[FCUIActivityControlMenuView _newMenuItemView] : 384 -> 380
~ -[FCUIActivityControlMenuView setMenuItemActions:] : 868 -> 860
~ -[FCUIActivityControlMenuView sizeThatFits:] : 356 -> 352
~ -[FCUIActivityControlMenuView layoutSubviews] : 1020 -> 1012
~ -[FCUIActivityControlMenuView requiredVisualStyleCategories] : 468 -> 464
~ -[FCUIActivityControlMenuView setAdjustsFontForContentSizeCategory:] : 328 -> 324
~ -[FCUIActivityControlMenuView adjustForContentSizeCategoryChange] : 336 -> 332
~ -[FCUIActivityControlMenuView _configureFooterViewIfNecessary] : 424 -> 420
~ -[FCUIActivityControlMenuView _visualStylingProvider:didChangeForCategory:outgoingProvider:] : 468 -> 464
~ -[FCUIActivityControlMenuView _toggleHighlightForMenuElement:] : 376 -> 372
~ -[FCUIActivityBaubleGroupView setAdjustsFontForContentSizeCategory:] : 296 -> 292
~ -[FCUIActivityBaubleGroupView adjustForContentSizeCategoryChange] : 376 -> 372
```
