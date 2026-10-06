## SIMSetupUIService

> `/System/Library/AccessibilityBundles/SIMSetupUIService.axbundle/SIMSetupUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5e4` | `0x8b0` | **`+0x2cc`** |
| `__AUTH_CONST.__objc_const` | `0x2d0` | `0x3f0` | **`+0x120`** |
| `__AUTH_CONST.__cfstring` | `0x1c0` | `0x280` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x190` | `0x230` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x16b` | `0x1f4` | **`+0x89`** |
| `__TEXT.__objc_methlist` | `0xdc` | `0x12c` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x30` | `0x60` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xc0` | `0xf0` | **`+0x30`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x38` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x90` | `0xa0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x10` | `0x18` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 18
-  Symbols:   78
-  CStrings:  21
+  Functions: 23
+  Symbols:   105
+  CStrings:  27
Symbols:
+ +[TSDeviceInfoViewControllerAccessibility _accessibilityPerformValidations:]
+ +[TSDeviceInfoViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[TSDeviceInfoViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[TSDeviceInfoViewControllerAccessibility _accessibilityLoadAccessibilityInformation]
+ -[TSDeviceInfoViewControllerAccessibility tableView:viewForHeaderInSection:]
+ _OBJC_CLASS_$_NSAttributedString
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_TSDeviceInfoViewControllerAccessibility
+ _OBJC_CLASS_$_UITableView
+ _OBJC_CLASS_$___TSDeviceInfoViewControllerAccessibility_super
+ _OBJC_METACLASS_$_TSDeviceInfoViewControllerAccessibility
+ _OBJC_METACLASS_$___TSDeviceInfoViewControllerAccessibility_super
+ _UIAccessibilitySpeechAttributeSpellOut
+ __OBJC_$_CLASS_METHODS_TSDeviceInfoViewControllerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_TSDeviceInfoViewControllerAccessibility
+ __OBJC_CLASS_RO_$_TSDeviceInfoViewControllerAccessibility
+ __OBJC_CLASS_RO_$___TSDeviceInfoViewControllerAccessibility_super
+ __OBJC_METACLASS_RO_$_TSDeviceInfoViewControllerAccessibility
+ __OBJC_METACLASS_RO_$___TSDeviceInfoViewControllerAccessibility_super
+ ___UIAccessibilityCastAsClass
+ ___kCFBooleanTrue
+ ___stack_chk_fail
+ ___stack_chk_guard
+ _abort
+ _objc_alloc
+ _objc_release_x22
+ _objc_release_x23
CStrings:
+ "TSDeviceInfoViewController"
+ "TSDeviceInfoViewControllerAccessibility"
+ "UITableViewCell"
+ "tableView"
+ "tableView:viewForHeaderInSection:"
+ "textLabel"
```
