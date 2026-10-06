## MobileCal

> `/System/Library/AccessibilityBundles/MobileCal.axbundle/MobileCal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__objc_selrefs` | `0xb08` | `0xb18` | **`+0x10`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0
Functions:
~ -[CalendarMonthControlAccessibility _accessibilityUpdateOcurrenceTileCount:] : 824 -> 820
~ -[CompactMonthWeekDayNumberAccessibility accessibilityCustomContent] : 1068 -> 1064
~ -[CompactMonthWeekDayNumberAccessibility(UIFocusConformance) focusItemsInRect:] : 444 -> 500
~ -[CompactMonthWeekViewAccessibility _axAnnotateDayNumbers] : 268 -> 264
~ -[CompactMonthWeekViewAccessibility accessibilityElements] : 668 -> 664
~ -[CompactMonthWeekViewAccessibility dealloc] : 296 -> 292
~ -[LargeMonthViewControllerAccessibility _axTopWeekViewWithTopPoint:] : 368 -> 364
~ -[LargeMonthWeekViewAccessibility _axUpdateDayNumberLabels] : 1296 -> 1292
~ -[MonthViewControllerAccessibility _axTopWeekViewWithTopPoint:] : 460 -> 456
~ -[RootNavigationControllerAccessibility todayPressed] : 444 -> 440
~ ___53-[RootNavigationControllerAccessibility todayPressed]_block_invoke : 288 -> 284
~ -[MobileCalUITransitionViewAccessibility _accessibilityObscuredScreenAllowedViews] : 580 -> 576
~ -[WeekAllDayDayContainerAccessibilityElement dealloc] : 288 -> 284
~ -[WeekAllDayViewAccessibility accessibilityElements] : 1448 -> 1444
~ -[WeekViewControllerAccessibility accessibilityScrollStatusForScrollView:] : 1168 -> 1164
```
