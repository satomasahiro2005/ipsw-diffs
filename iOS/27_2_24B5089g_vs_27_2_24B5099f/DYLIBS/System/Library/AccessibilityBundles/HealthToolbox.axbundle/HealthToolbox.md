## HealthToolbox

> `/System/Library/AccessibilityBundles/HealthToolbox.axbundle/HealthToolbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdf0` | `0xfb0` | **`+0x1c0`** |
| `__AUTH_CONST.__cfstring` | `0x440` | `0x480` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x118` | `0x150` | **`+0x38`** |
| `__TEXT.__cstring` | `0x2d9` | `0x300` | **`+0x27`** |
| `__TEXT.__objc_methlist` | `0x1b4` | `0x1cc` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x38` | `0x48` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xc8` | `0xd0` | **`+0x8`** |

### Other Changes

```diff

-3050.3.1.0.0
+3050.3.5.0.0

-  Functions: 34
-  Symbols:   144
-  CStrings:  41
+  Functions: 36
+  Symbols:   148
+  CStrings:  44
Symbols:
+ -[WDProfileTableViewCellAccessibility accessibilityTraits]
+ -[WDProfileTableViewCellAccessibility layoutSubviews]
+ GCC_except_table24
+ _OBJC_CLASS_$_UITextField
+ _UIAccessibilityTraitButton
- GCC_except_table22
Functions:
~ +[WDProfileTableViewCellAccessibility _accessibilityPerformValidations:] : 128 -> 188
+ -[WDProfileTableViewCellAccessibility layoutSubviews]
+ -[WDProfileTableViewCellAccessibility accessibilityTraits]
CStrings:
+ "displayValueTextField"
+ "layoutSubviews"
+ "v"
```
