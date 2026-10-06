## PaperKit

> `/System/Library/AccessibilityBundles/PaperKit.axbundle/PaperKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x750` | `0x870` | **`+0x120`** |
| `__TEXT.__text` | `0x11d4` | `0x12c8` | **`+0xf4`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x420` | `0x480` | **`+0x60`** |
| `__TEXT.__cstring` | `0x3b3` | `0x40c` | **`+0x59`** |
| `__TEXT.__objc_methlist` | `0x21c` | `0x264` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x170` | `0x188` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x58` | `0x68` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x68` | `0x78` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xf0` | `0xf8` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 49
-  Symbols:   183
-  CStrings:  45
+  Functions: 53
+  Symbols:   200
+  CStrings:  48
Symbols:
+ +[MarkupEditViewControllerAccessibility _accessibilityPerformValidations:]
+ +[MarkupEditViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[MarkupEditViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[MarkupEditViewControllerAccessibility viewDidAppear:]
+ GCC_except_table39
+ _OBJC_CLASS_$_MarkupEditViewControllerAccessibility
+ _OBJC_CLASS_$_UIViewController
+ _OBJC_CLASS_$___MarkupEditViewControllerAccessibility_super
+ _OBJC_METACLASS_$_MarkupEditViewControllerAccessibility
+ _OBJC_METACLASS_$___MarkupEditViewControllerAccessibility_super
+ _UIAccessibilityPostNotification
+ _UIAccessibilityScreenChangedNotification
+ __OBJC_$_CLASS_METHODS_MarkupEditViewControllerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_MarkupEditViewControllerAccessibility
+ __OBJC_CLASS_RO_$_MarkupEditViewControllerAccessibility
+ __OBJC_CLASS_RO_$___MarkupEditViewControllerAccessibility_super
+ __OBJC_METACLASS_RO_$_MarkupEditViewControllerAccessibility
+ __OBJC_METACLASS_RO_$___MarkupEditViewControllerAccessibility_super
- GCC_except_table35
CStrings:
+ "MarkupEditViewControllerAccessibility"
+ "PaperKit.MarkupEditViewController"
+ "UIViewController"
```
