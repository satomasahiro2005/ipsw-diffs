## EventKitUIFramework

> `/System/Library/AccessibilityBundles/EventKitUIFramework.axbundle/EventKitUIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xee88` | `0xee58` | **`-0x30`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0
Functions:
~ -[UIView(AccessibilityDragAndDrop) _accessibilityDragAndDropTargetViewForDrop:eventGestureController:] : 736 -> 728
~ _accessibilityCalendarTitleForEventIfNecessary : 556 -> 552
~ -[MobileCalOccurrencyContainerAccessibilityElement dealloc] : 288 -> 284
~ -[MobileCalDayContainerAccessibilityElement dealloc] : 288 -> 284
~ -[MobileCalDayContainerAccessibilityElement _accessibilityHitTest:withEvent:] : 620 -> 616
~ -[EKDayGridViewAccessibility _axResetChildren] : 592 -> 588
~ -[EKDayGridViewAccessibility accessibilityElements] : 3364 -> 3360
~ -[EKDayViewContentAccessibility _accessibilityLoadAccessibilityInformation] : 452 -> 448
~ -[EKEventDetailAttendeesCellAccessibility _axStringForParticipants:] : 640 -> 636
~ -[EKEventDetailTitleCellAccessibility _axAnnotateLocationViewsIfNeeded] : 592 -> 584
~ -[EKEventDetailTitleCellAccessibility accessibilityCustomContent] : 1688 -> 1684
~ -[EKTextViewWithLabelTextMetricsAccessibility accessibilityIsLocationLink] : 432 -> 436
```
