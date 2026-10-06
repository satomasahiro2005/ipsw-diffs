## HealthUI

> `/System/Library/AccessibilityBundles/HealthUI.axbundle/HealthUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6134` | `0x610c` | **`-0x28`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0
Functions:
~ -[HKSingleAudiogramChartViewControllerAccessibility _axUpdateAXElementsForGraphView] : 2424 -> 2416
~ -[HKSingleAudiogramChartViewControllerAccessibility _axCollectSeriesDataForGraphView:] : 912 -> 908
~ -[HKSingleAudiogramChartViewControllerAccessibility _axUpdateSelectionAXElementsForGraphView] : 636 -> 628
~ -[HKSingleAudiogramChartViewControllerAccessibility _axSelectedXCoordinateForGraphView:] : 624 -> 620
~ -[HKInteractiveChartAnnotationViewAccessibility accessibilityTraits] : 400 -> 396
~ +[HKInteractiveChartViewControllerAccessibility _axConfigureGraphViewInfoFromData:forGraphView:] : 616 -> 612
~ +[HKInteractiveChartViewControllerAccessibility _axConfigureGraphAccessibilityFromData:forGraphView:] : 1248 -> 1244
~ -[HKMonthWeekViewAccessibility accessibilityElements] : 488 -> 484
```
