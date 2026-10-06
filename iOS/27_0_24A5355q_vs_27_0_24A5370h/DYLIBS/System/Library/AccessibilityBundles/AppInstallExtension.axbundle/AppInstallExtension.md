## AppInstallExtension

> `/System/Library/AccessibilityBundles/AppInstallExtension.axbundle/AppInstallExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb36c` | `0xb408` | **`+0x9c`** |
| `__AUTH_CONST.__cfstring` | `0x39c0` | `0x3a00` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3d88` | `0x3da2` | **`+0x1a`** |
| `__TEXT.__unwind_info` | `0x670` | `0x678` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  CStrings:  505
+  CStrings:  507
Functions:
~ +[AppUpdatesDetailCollectionViewCellAccessibility _accessibilityPerformValidations:] : 128 -> 184
~ -[AppUpdatesDetailCollectionViewCellAccessibility accessibilityValue] : 84 -> 168
~ -[OfferButtonAccessibility accessibilityLabel] : 336 -> 356
~ -[ProductLockupCollectionViewCellAccessibility _accessibilityLoadAccessibilityInformation] : 304 -> 300
CStrings:
+ "UIView"
+ "[state=installing]"
```
