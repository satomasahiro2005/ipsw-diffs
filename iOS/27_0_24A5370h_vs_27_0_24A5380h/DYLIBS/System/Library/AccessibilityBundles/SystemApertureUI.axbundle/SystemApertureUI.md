## SystemApertureUI

> `/System/Library/AccessibilityBundles/SystemApertureUI.axbundle/SystemApertureUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xa0` | `—` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x190` | `0x230` | **`+0xa0`** |
| `__TEXT.__text` | `0x26d4` | `0x270c` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x720` | `0x740` | **`+0x20`** |
| `__TEXT.__cstring` | `0x5c2` | `0x5de` | **`+0x1c`** |
| `__DATA.__bss` | `0x10` | `0x8` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x8` | `0x10` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  CStrings:  70
+  CStrings:  71
Functions:
~ -[SAUIElementViewAccessibility accessibilityCustomActions] : 1248 -> 1276
~ ___82-[SAUIElementViewControllerAccessibility _axShiftFocusToElementViewForPowerAlerts]_block_invoke : 220 -> 248
CStrings:
+ "SBChargingAlertElement"
+ "SBLowBatteryAlertElement"
- "SBPowerAlertElement"
```
