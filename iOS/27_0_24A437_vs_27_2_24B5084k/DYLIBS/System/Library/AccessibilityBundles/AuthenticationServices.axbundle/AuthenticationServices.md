## AuthenticationServices

> `/System/Library/AccessibilityBundles/AuthenticationServices.axbundle/AuthenticationServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x54c` | `0x59c` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x104` | `0x110` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0xc8` | `0xd0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x90` | `0x98` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 19
-  Symbols:   89
+  Functions: 20
+  Symbols:   90
Symbols:
+ -[ASCredentialRequestPaneViewControllerAccessibility _accessibilitySheetView]
Functions:
~ -[ASCredentialRequestPaneViewControllerAccessibility viewDidAppear:] : 76 -> 120
~ -[ASCredentialRequestPaneViewControllerAccessibility _accessibilityConfigureModalSheet] : 176 -> 68
+ -[ASCredentialRequestPaneViewControllerAccessibility _accessibilitySheetView]
```
