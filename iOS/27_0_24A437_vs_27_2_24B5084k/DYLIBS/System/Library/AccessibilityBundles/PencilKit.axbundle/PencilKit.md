## PencilKit

> `/System/Library/AccessibilityBundles/PencilKit.axbundle/PencilKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x2010` | `0x2130` | **`+0x120`** |
| `__TEXT.__text` | `0x435c` | `0x443c` | **`+0xe0`** |
| `__AUTH.__objc_data` | `0x140` | `0x1e0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x145f` | `0x14ae` | **`+0x4f`** |
| `__TEXT.__objc_methlist` | `0xa30` | `0xa78` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x19c0` | `0x1a00` | **`+0x40`** |
| `__DATA_CONST.__objc_classlist` | `0x1c8` | `0x1d8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x108` | `0x110` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e8` | `0x2f0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xa8` | `0xb0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x248` | `0x250` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 177
-  Symbols:   558
-  CStrings:  222
+  Functions: 181
+  Symbols:   573
+  CStrings:  224
Symbols:
+ +[PKPaletteAttributeViewControllerAccessibility _accessibilityPerformValidations:]
+ +[PKPaletteAttributeViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PKPaletteAttributeViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[PKPaletteAttributeViewControllerAccessibility viewDidAppear:]
+ GCC_except_table125
+ _OBJC_CLASS_$_PKPaletteAttributeViewControllerAccessibility
+ _OBJC_CLASS_$___PKPaletteAttributeViewControllerAccessibility_super
+ _OBJC_METACLASS_$_PKPaletteAttributeViewControllerAccessibility
+ _OBJC_METACLASS_$___PKPaletteAttributeViewControllerAccessibility_super
+ _UIAccessibilityScreenChangedNotification
+ __OBJC_$_CLASS_METHODS_PKPaletteAttributeViewControllerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_PKPaletteAttributeViewControllerAccessibility
+ __OBJC_CLASS_RO_$_PKPaletteAttributeViewControllerAccessibility
+ __OBJC_CLASS_RO_$___PKPaletteAttributeViewControllerAccessibility_super
+ __OBJC_METACLASS_RO_$_PKPaletteAttributeViewControllerAccessibility
+ __OBJC_METACLASS_RO_$___PKPaletteAttributeViewControllerAccessibility_super
- GCC_except_table121
CStrings:
+ "PKPaletteAttributeViewController"
+ "PKPaletteAttributeViewControllerAccessibility"
```
