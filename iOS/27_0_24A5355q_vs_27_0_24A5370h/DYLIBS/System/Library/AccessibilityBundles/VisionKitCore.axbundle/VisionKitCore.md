## VisionKitCore

> `/System/Library/AccessibilityBundles/VisionKitCore.axbundle/VisionKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2658` | `0x29d4` | **`+0x37c`** |
| `__AUTH_CONST.__objc_const` | `0xdf0` | `0xf10` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x50` | `0xf0` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0xe80` | `0xf20` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x9d2` | `0xa57` | **`+0x85`** |
| `__TEXT.__objc_methlist` | `0x5c4` | `0x624` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x80` | `0xc0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2d0` | `0x308` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1a0` | `0x1b8` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xc0` | `0xd0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xa8` | `0xb0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x48` | `0x50` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 112
-  Symbols:   313
-  CStrings:  128
+  Functions: 120
+  Symbols:   336
+  CStrings:  133
Symbols:
+ +[_UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit _accessibilityPerformValidations:]
+ +[_UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit(SafeCategory) safeCategoryBaseClass]
+ +[_UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit(SafeCategory) safeCategoryTargetClassName]
+ -[_UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit _accessibilityObscuredScreenAllowedViews]
+ -[_UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit _ax_visionKitSourceViewIfApplicable]
+ -[_UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit accessibilityViewIsModal]
+ _AXSafeClassFromString
+ _OBJC_CLASS_$_UIView
+ _OBJC_CLASS_$__UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit
+ _OBJC_CLASS_$____UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit_super
+ _OBJC_METACLASS_$__UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit
+ _OBJC_METACLASS_$____UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit_super
+ __OBJC_$_CLASS_METHODS__UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS__UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit
+ __OBJC_CLASS_RO_$__UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit
+ __OBJC_CLASS_RO_$____UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit_super
+ __OBJC_METACLASS_RO_$__UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit
+ __OBJC_METACLASS_RO_$____UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit_super
+ ___103-[_UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit _accessibilityObscuredScreenAllowedViews]_block_invoke
+ ___98-[_UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit _ax_visionKitSourceViewIfApplicable]_block_invoke
+ ___UIAccessibilityCastAsClass
+ _objc_opt_isKindOfClass
+ _objc_retainAutoreleaseReturnValue
Functions:
~ ___52+[AXVisionKitCoreGlue accessibilityInitializeBundle]_block_invoke_3 : 272 -> 292
CStrings:
+ "_UIEditMenuContainerView"
+ "_UIEditMenuContainerViewAccessibility__VisionKitCore__UIKit"
+ "_UIEditMenuPresentation"
+ "presentation"
+ "sourceView"
```
