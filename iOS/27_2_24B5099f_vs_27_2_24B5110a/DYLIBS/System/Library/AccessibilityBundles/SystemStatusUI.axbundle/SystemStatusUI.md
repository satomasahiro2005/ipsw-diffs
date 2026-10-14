## SystemStatusUI

> `/System/Library/AccessibilityBundles/SystemStatusUI.axbundle/SystemStatusUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x28e0` | `0x2920` | **`+0x40`** |
| `__TEXT.__text` | `0x776c` | `0x779c` | **`+0x30`** |
| `__TEXT.__cstring` | `0x23e2` | `0x2404` | **`+0x22`** |

### Other Changes

```diff

-3050.3.5.0.0
+3050.3.8.0.0

-  CStrings:  345
+  CStrings:  347
Functions:
~ -[STUIStatusBarAccessibility accessibilityElements] : 280 -> 328
CStrings:
+ "controlCenterController"
+ "isVisible"
```
