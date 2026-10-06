## MobileStoreUI

> `/System/Library/AccessibilityBundles/MobileStoreUI.axbundle/MobileStoreUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x186f0` | `0x18608` | **`-0xe8`** |
| `__TEXT.__cstring` | `0x477b` | `0x4760` | **`-0x1b`** |
| `__TEXT.__unwind_info` | `0x908` | `0x910` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  CStrings:  774
+  CStrings:  773
Functions:
~ -[SUUICollectionViewAccessibility _accessibilityScrollToFrame:forView:] : 1268 -> 1264
~ -[SUUIProductPageFeaturesViewAccessibility accessibilityElements] : 572 -> 568
~ -[SUUIHorizontalListViewAccessibility _accessibilityLoadAccessibilityInformation] : 560 -> 556
~ -[SUUIAttributedStringViewAccessibility accessibilityLabel] : 664 -> 660
~ -[SUUIOverlayContainerViewAccessibility _accessibilityObscuredScreenAllowedViews] : 548 -> 544
~ -[SUUIToggleButtonAccessibility _accessibilityFindAttributedStringView] : 320 -> 316
~ -[SUUIStyledButtonAccessibility _axIsCloseButton] : 568 -> 564
~ -[SUUISectionHeaderViewAccessibility layoutSubviews] : 372 -> 368
~ -[SUUISectionHeaderViewAccessibility _axHasOnlyStringViews] : 292 -> 288
~ -[SUUISectionHeaderViewAccessibility accessibilityLabel] : 416 -> 412
~ -[SUUISectionHeaderViewAccessibility accessibilityTraits] : 372 -> 368
~ -[SUUITabularLockupViewAccessibility accessibilityLabel] : 1136 -> 1128
~ -[SUUIReviewCollectionViewCellAccessibility accessibilityLabel] : 504 -> 500
~ -[SUUIHorizontalLockupViewAccessibility accessibilityLabel] : 1708 -> 1704
~ -[SUUIHorizontalLockupViewAccessibility _accessibilityHitTest:withEvent:] : 472 -> 468
~ -[SUUIHorizontalLockupViewAccessibility _accessibilitySupplementaryHeaderViews] : 1072 -> 1060
~ -[SUUIHorizontalLockupViewAccessibility accessibilityFrame] : 324 -> 320
~ -[SUUIHorizontalLockupViewAccessibility _accessibilitySupplementaryFooterViewsIncludePlayButton:includeStyledImageButton:] : 1452 -> 1448
~ -[SUUIHorizontalLockupViewAccessibility _accessibilityFindPlayButton] : 400 -> 396
~ -[SUUIHorizontalLockupViewAccessibility _accessibilityFindStyledImageButton] : 348 -> 344
~ -[SUUIHorizontalLockupViewAccessibility _accessibilityFindToggleButton] : 328 -> 324
~ -[SUUIReviewsHistogramViewAccessibility setHistogramValues:] : 472 -> 468
~ -[SUUIImageDeckViewAccessibility accessibilityLabel] : 520 -> 516
~ -[SUUIVerticalLockupCollectionViewCellAccessibility hasOnlyStringViews] : 444 -> 440
~ -[SUUIVerticalLockupCollectionViewCellAccessibility _accessibilityFindPlayButton] : 348 -> 344
~ -[SUUIVerticalLockupCollectionViewCellAccessibility accessibilityLabel] : 700 -> 696
~ -[SUUIVerticalLockupCollectionViewCellAccessibility _accessibilitySupplementaryFooterViewsForThisCell:includeText:] : 928 -> 920
~ -[SUUIVerticalLockupCollectionViewCellAccessibility _accessibilityHitTest:withEvent:] : 528 -> 524
~ +[SUUISearchFieldTableViewAccessibility _accessibilityPerformValidations:] : 124 -> 64
~ -[SUUISettingsTableViewCellAcccessibility _axLockupView] : 456 -> 452
~ -[SUUISettingsTableViewCellAcccessibility _axViewContainsSwitch] : 384 -> 380
~ -[SUUIImageCollectionViewCellAccessibility accessibilityLabel] : 904 -> 896
~ -[SUUITracklistLockupCollectionViewCellAccessibility accessibilityLabel] : 928 -> 936
~ -[SUUITracklistLockupCollectionViewCellAccessibility _accessibilitySupplementaryFooterViews] : 392 -> 388
~ -[SUUITextBoxViewAccessibility _accessibilitySwitchOrderedChildrenFrom:] : 344 -> 340
~ -[SUUICardViewElementCollectionViewCellAccessibility _axLockupElements] : 536 -> 532
~ -[SUUICardViewElementCollectionViewCellAccessibility _axAdornedImageElement] : 388 -> 384
~ -[SUUICardViewElementCollectionViewCellAccessibility accessibilityLabel] : 524 -> 520
~ -[SUUICardViewElementCollectionViewCellAccessibility _accessibilityHitTest:withEvent:] : 440 -> 436
~ -[SUUICardViewElementCollectionViewCellAccessibility _accessibilitySupplementaryFooterViews] : 668 -> 664
~ -[SUUICardViewElementCollectionViewCellAccessibility accessibilityCustomActions] : 368 -> 364
~ -[SUUIChartColumnHeaderViewAccessibility _accessibilityLoadAccessibilityInformation] : 332 -> 328
CStrings:
- "SUUITrendingSearchPageView"
```
