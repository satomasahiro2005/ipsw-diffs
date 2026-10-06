## PreferencesFramework

> `/System/Library/AccessibilityBundles/PreferencesFramework.axbundle/PreferencesFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7b4c` | `0x7be4` | **`+0x98`** |
| `__AUTH_CONST.__cfstring` | `0x2020` | `0x2040` | **`+0x20`** |
| `__TEXT.__cstring` | `0x191b` | `0x1934` | **`+0x19`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x1f8` | **`+0x18`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Symbols:   877
-  CStrings:  289
+  Symbols:   880
+  CStrings:  290
Symbols:
+ _UIAccessibilitySpeechAttributePunctuation
+ _UIAccessibilityTokenLiteralText
+ ___kCFBooleanTrue
Functions:
~ -[PSSpecifierContentConfigurationCellAccessibility accessibilityLabel] : 348 -> 500
CStrings:
+ "axIsDateNumberFormatCell"
```
