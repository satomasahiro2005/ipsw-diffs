## AppStore

> `/System/Library/AccessibilityBundles/AppStore.axbundle/AppStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbfc8` | `0xbda4` | **`-0x224`** |
| `__TEXT.__cstring` | `0x3a29` | `0x399c` | **`-0x8d`** |
| `__AUTH_CONST.__cfstring` | `0x3b40` | `0x3ae0` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0x6d8` | `0x6c8` | **`-0x10`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  CStrings:  521
+  CStrings:  518
Functions:
~ ___48+[AXAppStore3Glue accessibilityInitializeBundle]_block_invoke_3 : 2072 -> 2012
~ +[AppUpdatesDetailCollectionViewCellAccessibility _accessibilityPerformValidations:] : 128 -> 184
~ -[AppUpdatesDetailCollectionViewCellAccessibility accessibilityValue] : 84 -> 168
~ +[AccountDetailCollectionViewCellAccessibility _accessibilityPerformValidations:] : 292 -> 16
~ +[AccountActionSectionFooterViewAccessibility _accessibilityPerformValidations:] : 108 -> 24
~ +[AnnotationCollectionViewCellAccessibility _accessibilityPerformValidations:] : 288 -> 4
~ -[OfferButtonAccessibility accessibilityLabel] : 336 -> 356
~ -[ProductLockupCollectionViewCellAccessibility _accessibilityLoadAccessibilityInformation] : 304 -> 300
CStrings:
+ "[state=installing]"
- "AccountActionSectionFooterViewAccessibility"
- "AccountDetailCollectionViewCellAccessibility"
- "AnnotationCollectionViewCellAccessibility"
- "accessibilityLinkLabelTapped"
```
