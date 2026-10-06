## PosterKit

> `/System/Library/AccessibilityBundles/PosterKit.axbundle/PosterKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7cc4` | `0x7d54` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x2400` | `0x2440` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1d9f` | `0x1dc6` | **`+0x27`** |
| `__DATA_CONST.__objc_selrefs` | `0x558` | `0x560` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  CStrings:  311
+  CStrings:  313
Functions:
~ +[PREditingContentStyleItemViewAccessibility _accessibilityPerformValidations:] : 208 -> 272
~ -[PREditingContentStyleItemViewAccessibility accessibilityTraits] : 72 -> 152
CStrings:
+ "PRSelectableEditingItemView"
+ "isSelected"
```
