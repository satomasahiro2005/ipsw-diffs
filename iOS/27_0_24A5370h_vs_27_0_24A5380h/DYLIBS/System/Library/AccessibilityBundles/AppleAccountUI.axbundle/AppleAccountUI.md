## AppleAccountUI

> `/System/Library/AccessibilityBundles/AppleAccountUI.axbundle/AppleAccountUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77c` | `0x4c8` | **`-0x2b4`** |
| `__AUTH_CONST.__objc_const` | `0x3f0` | `0x2d0` | **`-0x120`** |
| `__DATA_DIRTY.__objc_data` | `0x230` | `0x190` | **`-0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x260` | `0x1e0` | **`-0x80`** |
| `__TEXT.__cstring` | `0x1c3` | `0x166` | **`-0x5d`** |
| `__TEXT.__objc_methlist` | `0x158` | `0x104` | **`-0x54`** |
| `__DATA_CONST.__objc_selrefs` | `0x100` | `0xd0` | **`-0x30`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x28` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xb0` | `0xa0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x38` | `0x30` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x8` | `—` | **`-0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 28
-  Symbols:   102
-  CStrings:  27
+  Functions: 23
+  Symbols:   80
+  CStrings:  22
Symbols:
- +[AAUISignInViewControllerAccessibility _accessibilityPerformValidations:]
- +[AAUISignInViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[AAUISignInViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[AAUISignInViewControllerAccessibility _passwordCell]
- -[AAUISignInViewControllerAccessibility _usernameCell]
- _OBJC_CLASS_$_AAUISignInViewControllerAccessibility
- _OBJC_CLASS_$_UITableViewCell
- _OBJC_CLASS_$___AAUISignInViewControllerAccessibility_super
- _OBJC_METACLASS_$_AAUISignInViewControllerAccessibility
- _OBJC_METACLASS_$___AAUISignInViewControllerAccessibility_super
- __OBJC_$_CLASS_METHODS_AAUISignInViewControllerAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_AAUISignInViewControllerAccessibility
- __OBJC_CLASS_RO_$_AAUISignInViewControllerAccessibility
- __OBJC_CLASS_RO_$___AAUISignInViewControllerAccessibility_super
- __OBJC_METACLASS_RO_$_AAUISignInViewControllerAccessibility
- __OBJC_METACLASS_RO_$___AAUISignInViewControllerAccessibility_super
- ___UIAccessibilityCastAsClass
- _abort
- _objc_msgSendSuper2
- _objc_release_x20
- _objc_release_x21
- _objc_release_x22
CStrings:
- "@"
- "AAUISignInViewController"
- "AAUISignInViewControllerAccessibility"
- "_passwordCell"
- "_usernameCell"
```
