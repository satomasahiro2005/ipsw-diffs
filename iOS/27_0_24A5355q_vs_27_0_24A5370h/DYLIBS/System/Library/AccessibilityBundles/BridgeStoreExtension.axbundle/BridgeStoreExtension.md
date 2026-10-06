## BridgeStoreExtension

> `/System/Library/AccessibilityBundles/BridgeStoreExtension.axbundle/BridgeStoreExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb388` | `0xb424` | **`+0x9c`** |
| `__AUTH_CONST.__cfstring` | `0x39e0` | `0x3a20` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3e09` | `0x3e23` | **`+0x1a`** |
| `__TEXT.__unwind_info` | `0x670` | `0x678` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  CStrings:  506
+  CStrings:  508
Functions:
~ +[AppUpdatesDetailCollectionViewCellAccessibility _accessibilityPerformValidations:] : 128 -> 184
~ -[AppUpdatesDetailCollectionViewCellAccessibility accessibilityValue] : 84 -> 168
~ -[OfferButtonAccessibility accessibilityLabel] : 336 -> 356
~ -[ProductLockupCollectionViewCellAccessibility _accessibilityLoadAccessibilityInformation] : 304 -> 300
CStrings:
+ "UIView"
+ "[state=installing]"
```
