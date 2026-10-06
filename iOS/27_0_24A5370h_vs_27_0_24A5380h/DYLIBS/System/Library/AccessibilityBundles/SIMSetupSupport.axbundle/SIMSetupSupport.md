## SIMSetupSupport

> `/System/Library/AccessibilityBundles/SIMSetupSupport.axbundle/SIMSetupSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xa0` | `—` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0xf0` | `0x190` | **`+0xa0`** |
| `__TEXT.__text` | `0x67c` | `0x64c` | **`-0x30`** |
| `__TEXT.__cstring` | `0x15e` | `0x15c` | **`-0x2`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  CStrings:  24
+  CStrings:  22
Functions:
~ +[TSTransferQRCodeViewControllerAccessibility _accessibilityPerformValidations:] : 72 -> 24
CStrings:
+ "UIViewController"
- "B"
- "v"
- "viewDidAppear:"
```
