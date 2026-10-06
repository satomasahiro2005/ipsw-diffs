## SetupAssistantUI

> `/System/Library/AccessibilityBundles/SetupAssistantUI.axbundle/SetupAssistantUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x390` | `0x2e0` | **`-0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x140` | `0x100` | **`-0x40`** |
| `__DATA_CONST.__got` | `0x28` | `0x0` | **`-0x28`** |
| `__TEXT.__cstring` | `0x142` | `0x124` | **`-0x1e`** |
| `__DATA_CONST.__objc_selrefs` | `0x98` | `0x88` | **`-0x10`** |
| `__DATA.__bss` | `0x8` | `—` | **`-0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 15
-  Symbols:   70
-  CStrings:  16
+  Functions: 14
+  Symbols:   64
+  CStrings:  14
Symbols:
- _OBJC_CLASS_$_NSBundle
- _accessibilityLocalizedString
- _accessibilityLocalizedString.axBundle
- _objc_autoreleaseReturnValue
- _objc_release_x8
- _objc_retain
Functions:
- _accessibilityLocalizedString
CStrings:
- ""
- "Accessibility-SetupAssistant"
```
