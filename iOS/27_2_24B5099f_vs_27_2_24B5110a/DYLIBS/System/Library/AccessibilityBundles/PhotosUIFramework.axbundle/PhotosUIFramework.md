## PhotosUIFramework

> `/System/Library/AccessibilityBundles/PhotosUIFramework.axbundle/PhotosUIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x141d4` | `0x14178` | **`-0x5c`** |
| `__AUTH_CONST.__cfstring` | `0x4d80` | `0x4d40` | **`-0x40`** |
| `__TEXT.__cstring` | `0x3a7e` | `0x3a66` | **`-0x18`** |

### Other Changes

```diff

-3050.3.5.0.0
+3050.3.8.0.0

-  CStrings:  663
+  CStrings:  661
Functions:
~ +[PUPhotoEditViewControllerAccessibility _accessibilityPerformValidations:] : 408 -> 380
~ -[PUPhotoEditViewControllerAccessibility _accessibilityLoadAccessibilityInformation] : 616 -> 552
CStrings:
- "_moreButton"
- "plugin.tool"
```
