## ScreenTimeSettingsUI

> `/System/Library/AccessibilityBundles/ScreenTimeSettingsUI.axbundle/ScreenTimeSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x71ac` | `0x728c` | **`+0xe0`** |
| `__AUTH_CONST.__cfstring` | `0x15a0` | `0x1640` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1119` | `0x11b2` | **`+0x99`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  CStrings:  195
+  CStrings:  200
Functions:
~ +[STUsageSummaryTitleViewAccessibility _accessibilityPerformValidations:] : 328 -> 412
~ -[STUsageSummaryTitleViewAccessibility accessibilityLabel] : 476 -> 616
CStrings:
+ "notificationDeltaFromHistoricalAverage"
+ "pickupDeltaFromHistoricalAverage"
+ "screenTimeDeltaFromHistoricalAverage"
+ "usage.delta.decreased"
+ "usage.delta.increased"
```
