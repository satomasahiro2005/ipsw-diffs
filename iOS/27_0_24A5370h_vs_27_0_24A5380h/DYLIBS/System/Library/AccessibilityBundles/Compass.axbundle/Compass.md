## Compass

> `/System/Library/AccessibilityBundles/Compass.axbundle/Compass`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x141c` | `0x13a0` | **`-0x7c`** |
| `__AUTH_CONST.__cfstring` | `0x520` | `0x4e0` | **`-0x40`** |
| `__TEXT.__cstring` | `0x34f` | `0x320` | **`-0x2f`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  CStrings:  50
+  CStrings:  47
Functions:
~ +[CompassPageViewControllerAccessibility _accessibilityPerformValidations:] : 428 -> 424
~ +[UIViewCompassAccessibility _accessibilityPerformValidations:] : 148 -> 124
~ -[UIViewCompassAccessibility _accessibilitySupplementaryFooterViews] : 428 -> 332
CStrings:
+ "_locationInfoLabel"
- "CompassCopyableLabel"
- "_altitudeLabel"
- "_coordinatesLabel"
- "_placeLabel"
```
