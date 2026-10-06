## PreferencesFramework

> `/System/Library/AccessibilityBundles/PreferencesFramework.axbundle/PreferencesFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7be4` | `0x7c14` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x2040` | `0x2060` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1934` | `0x1941` | **`+0xd`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  CStrings:  290
+  CStrings:  291
Functions:
~ +[PSTableCellAccessibility _accessibilityPerformValidations:] : 316 -> 344
~ -[PSTableCellAccessibility accessibilityTraits] : 396 -> 416
CStrings:
+ "canBeChecked"
```
