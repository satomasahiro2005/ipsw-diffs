## Arcade

> `/System/Library/AccessibilityBundles/Arcade.axbundle/Arcade`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa748` | `0xa7e4` | **`+0x9c`** |
| `__AUTH_CONST.__cfstring` | `0x3960` | `0x39a0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x36c8` | `0x36e2` | **`+0x1a`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  CStrings:  494
+  CStrings:  496
Functions:
~ +[AppUpdatesDetailCollectionViewCellAccessibility _accessibilityPerformValidations:] : 128 -> 184
~ -[AppUpdatesDetailCollectionViewCellAccessibility accessibilityValue] : 84 -> 168
~ -[OfferButtonAccessibility accessibilityLabel] : 336 -> 356
~ -[ProductLockupCollectionViewCellAccessibility _accessibilityLoadAccessibilityInformation] : 304 -> 300
CStrings:
+ "UIView"
+ "[state=installing]"
```
