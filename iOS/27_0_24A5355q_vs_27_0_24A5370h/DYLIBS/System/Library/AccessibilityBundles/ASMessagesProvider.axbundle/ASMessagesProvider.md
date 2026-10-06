## ASMessagesProvider

> `/System/Library/AccessibilityBundles/ASMessagesProvider.axbundle/ASMessagesProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb38c` | `0xb428` | **`+0x9c`** |
| `__AUTH_CONST.__cfstring` | `0x3960` | `0x39a0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3cbb` | `0x3cd5` | **`+0x1a`** |
| `__TEXT.__unwind_info` | `0x668` | `0x670` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  CStrings:  504
+  CStrings:  506
Functions:
~ +[AppUpdatesDetailCollectionViewCellAccessibility _accessibilityPerformValidations:] : 128 -> 184
~ -[AppUpdatesDetailCollectionViewCellAccessibility accessibilityValue] : 84 -> 168
~ -[OfferButtonAccessibility accessibilityLabel] : 336 -> 356
~ -[ProductLockupCollectionViewCellAccessibility _accessibilityLoadAccessibilityInformation] : 304 -> 300
CStrings:
+ "UIView"
+ "[state=installing]"
```
