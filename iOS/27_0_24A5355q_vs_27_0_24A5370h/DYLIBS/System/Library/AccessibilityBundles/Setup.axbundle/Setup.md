## Setup

> `/System/Library/AccessibilityBundles/Setup.axbundle/Setup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55bc` | `0x55b0` | **`-0xc`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0
Functions:
~ -[LabeledSliderAccessibility _accessibilityReportModeChanged] : 380 -> 376
~ -[UIBuddyApplicationAccessibility _accessibilityCanRequestSetupControllerSafely] : 372 -> 368
~ -[BuddyUIViewAccessibility _accessibilityHitTest:withEvent:] : 504 -> 500
```
