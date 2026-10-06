## AuthKitUI

> `/System/Library/AccessibilityBundles/AuthKitUI.axbundle/AuthKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__objc_data` | `0x4b0` | `0x5f0` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0xab0` | `0xbd0` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x140` | `0xa0` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0x370` | `0x3c0` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x6e0` | `0x720` | **`+0x40`** |
| `__TEXT.__text` | `0x1530` | `0x156c` | **`+0x3c`** |
| `__TEXT.__cstring` | `0x5f1` | `0x624` | **`+0x33`** |
| `__DATA_CONST.__objc_classlist` | `0x98` | `0xa8` | **`+0x10`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 64
-  Symbols:   229
-  CStrings:  66
+  Functions: 69
+  Symbols:   245
+  CStrings:  68
Symbols:
+ +[AKUIUserAvatarViewAccessibility _accessibilityPerformValidations:]
+ +[AKUIUserAvatarViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[AKUIUserAvatarViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[AKUIUserAvatarViewAccessibility accessibilityLabel]
+ -[AKUIUserAvatarViewAccessibility isAccessibilityElement]
+ _OBJC_CLASS_$_AKUIUserAvatarViewAccessibility
+ _OBJC_CLASS_$___AKUIUserAvatarViewAccessibility_super
+ _OBJC_METACLASS_$_AKUIUserAvatarViewAccessibility
+ _OBJC_METACLASS_$___AKUIUserAvatarViewAccessibility_super
+ _UIAXStringForAllLeafNodeChildren
+ __OBJC_$_CLASS_METHODS_AKUIUserAvatarViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_AKUIUserAvatarViewAccessibility
+ __OBJC_CLASS_RO_$_AKUIUserAvatarViewAccessibility
+ __OBJC_CLASS_RO_$___AKUIUserAvatarViewAccessibility_super
+ __OBJC_METACLASS_RO_$_AKUIUserAvatarViewAccessibility
+ __OBJC_METACLASS_RO_$___AKUIUserAvatarViewAccessibility_super
Functions:
~ ___46+[AXAuthKitGlue accessibilityInitializeBundle]_block_invoke_3 : 232 -> 252
CStrings:
+ "AKUIUserAvatarView"
+ "AKUIUserAvatarViewAccessibility"
```
