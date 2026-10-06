## TipsApp

> `/System/Library/AccessibilityBundles/TipsApp.axbundle/TipsApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfe0` | `0x1238` | **`+0x258`** |
| `__AUTH_CONST.__objc_const` | `0x630` | `0x750` | **`+0x120`** |
| `__AUTH_CONST.__cfstring` | `0x6c0` | `0x7c0` | **`+0x100`** |
| `__TEXT.__cstring` | `0x39d` | `0x47e` | **`+0xe1`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x1cc` | `0x214` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a0` | `0x1d8` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x88` | `0x98` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x58` | `0x68` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xc0` | `0xd0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x20` | `0x28` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 32
-  Symbols:   144
-  CStrings:  60
+  Functions: 36
+  Symbols:   160
+  CStrings:  69
Symbols:
+ +[_UIButtonBarButtonAccessibility__Tips__UIKit _accessibilityPerformValidations:]
+ +[_UIButtonBarButtonAccessibility__Tips__UIKit(SafeCategory) safeCategoryBaseClass]
+ +[_UIButtonBarButtonAccessibility__Tips__UIKit(SafeCategory) safeCategoryTargetClassName]
+ -[_UIButtonBarButtonAccessibility__Tips__UIKit accessibilityActivate]
+ _OBJC_CLASS_$_UIApplication
+ _OBJC_CLASS_$_UIBarButtonItem
+ _OBJC_CLASS_$__UIButtonBarButtonAccessibility__Tips__UIKit
+ _OBJC_CLASS_$____UIButtonBarButtonAccessibility__Tips__UIKit_super
+ _OBJC_METACLASS_$__UIButtonBarButtonAccessibility__Tips__UIKit
+ _OBJC_METACLASS_$____UIButtonBarButtonAccessibility__Tips__UIKit_super
+ __OBJC_$_CLASS_METHODS__UIButtonBarButtonAccessibility__Tips__UIKit(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS__UIButtonBarButtonAccessibility__Tips__UIKit
+ __OBJC_CLASS_RO_$__UIButtonBarButtonAccessibility__Tips__UIKit
+ __OBJC_CLASS_RO_$____UIButtonBarButtonAccessibility__Tips__UIKit_super
+ __OBJC_METACLASS_RO_$__UIButtonBarButtonAccessibility__Tips__UIKit
+ __OBJC_METACLASS_RO_$____UIButtonBarButtonAccessibility__Tips__UIKit_super
Functions:
~ ___43+[AXTipsGlue accessibilityInitializeBundle]_block_invoke_3 : 152 -> 172
CStrings:
+ "UIControl"
+ "_UIButtonBarButton"
+ "_UIButtonBarButtonAccessibility__Tips__UIKit"
+ "_UIButtonBarButtonVisualProvider"
+ "_UIButtonBarButtonVisualProviderIOS"
+ "_barButtonItem"
+ "_visualProvider"
+ "_visualProvider._barButtonItem"
+ "tips.tip.saveButton"
```
