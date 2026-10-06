## PreferencesFramework

> `/System/Library/AccessibilityBundles/PreferencesFramework.axbundle/PreferencesFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x19b3` | `0x198d` | **`-0x26`** |
| `__AUTH_CONST.__cfstring` | `0x20e0` | `0x20c0` | **`-0x20`** |
| `__TEXT.__text` | `0x847c` | `0x8484` | **`+0x8`** |

### Other Changes

```diff

-3050.3.1.0.0
+3050.3.5.0.0

-  CStrings:  295
+  CStrings:  294
Functions:
~ +[PSSwitchTableCellAccessibility _accessibilityPerformValidations:] : 156 -> 140
~ ____axCollectContentFrames_block_invoke : 184 -> 164
~ -[PSTableCellAccessibility automationElements] : 276 -> 320
CStrings:
- "UITableViewCellDeleteConfirmationView"
```
