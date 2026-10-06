## AuthenticationServices

> `/System/Library/AccessibilityBundles/AuthenticationServices.axbundle/AuthenticationServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c0` | `0x54c` | **`+0x18c`** |
| `__AUTH_CONST.__objc_const` | `0x2d0` | `0x3f0` | **`+0x120`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x13b` | `0x1a9` | **`+0x6e`** |
| `__AUTH_CONST.__cfstring` | `0x160` | `0x1c0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xa4` | `0x104` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xb0` | `0xc8` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x38` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x88` | `0x90` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 13
-  Symbols:   72
-  CStrings:  14
+  Functions: 19
+  Symbols:   89
+  CStrings:  17
Symbols:
+ +[ASCredentialRequestPaneViewControllerAccessibility _accessibilityPerformValidations:]
+ +[ASCredentialRequestPaneViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[ASCredentialRequestPaneViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[ASCredentialRequestPaneViewControllerAccessibility _accessibilityConfigureModalSheet]
+ -[ASCredentialRequestPaneViewControllerAccessibility _accessibilityLoadAccessibilityInformation]
+ -[ASCredentialRequestPaneViewControllerAccessibility viewDidAppear:]
+ _OBJC_CLASS_$_ASCredentialRequestPaneViewControllerAccessibility
+ _OBJC_CLASS_$___ASCredentialRequestPaneViewControllerAccessibility_super
+ _OBJC_METACLASS_$_ASCredentialRequestPaneViewControllerAccessibility
+ _OBJC_METACLASS_$___ASCredentialRequestPaneViewControllerAccessibility_super
+ __OBJC_$_CLASS_METHODS_ASCredentialRequestPaneViewControllerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_ASCredentialRequestPaneViewControllerAccessibility
+ __OBJC_CLASS_RO_$_ASCredentialRequestPaneViewControllerAccessibility
+ __OBJC_CLASS_RO_$___ASCredentialRequestPaneViewControllerAccessibility_super
+ __OBJC_METACLASS_RO_$_ASCredentialRequestPaneViewControllerAccessibility
+ __OBJC_METACLASS_RO_$___ASCredentialRequestPaneViewControllerAccessibility_super
+ _objc_retain_x20
CStrings:
+ "ASCredentialRequestPaneViewController"
+ "ASCredentialRequestPaneViewControllerAccessibility"
+ "navigationController"
```
