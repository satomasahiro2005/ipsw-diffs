## ProductPageExtension

> `/System/Library/AccessibilityBundles/ProductPageExtension.axbundle/ProductPageExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb4a4` | `0xb540` | **`+0x9c`** |
| `__AUTH_CONST.__cfstring` | `0x3a00` | `0x3a40` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3e79` | `0x3e93` | **`+0x1a`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  CStrings:  509
+  CStrings:  511
Functions:
~ +[AppUpdatesDetailCollectionViewCellAccessibility _accessibilityPerformValidations:] : 128 -> 184
~ -[AppUpdatesDetailCollectionViewCellAccessibility accessibilityValue] : 84 -> 168
~ -[OfferButtonAccessibility accessibilityLabel] : 336 -> 356
~ -[ProductLockupCollectionViewCellAccessibility _accessibilityLoadAccessibilityInformation] : 304 -> 300
CStrings:
+ "UIView"
+ "[state=installing]"
```
