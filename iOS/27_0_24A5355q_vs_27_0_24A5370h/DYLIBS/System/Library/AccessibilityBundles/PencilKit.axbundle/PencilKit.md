## PencilKit

> `/System/Library/AccessibilityBundles/PencilKit.axbundle/PencilKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4100` | `0x42cc` | **`+0x1cc`** |
| `__AUTH_CONST.__objc_const` | `0x1ef0` | `0x2010` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x320` | `0x3c0` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x18e0` | `0x1980` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1372` | `0x13e1` | **`+0x6f`** |
| `__TEXT.__objc_methlist` | `0xa18` | `0xa60` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c8` | `0x2e0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x1b8` | `0x1c8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x230` | `0x240` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x98` | `0xa0` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 176
-  Symbols:   547
-  CStrings:  215
+  Functions: 180
+  Symbols:   562
+  CStrings:  220
Symbols:
+ +[PKPaletteContainerViewAccessibility _accessibilityPerformValidations:]
+ +[PKPaletteContainerViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PKPaletteContainerViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[PKPaletteContainerViewAccessibility _accessibilityHitTest:withEvent:]
+ GCC_except_table124
+ _CGRectContainsPoint
+ _OBJC_CLASS_$_PKPaletteContainerViewAccessibility
+ _OBJC_CLASS_$___PKPaletteContainerViewAccessibility_super
+ _OBJC_METACLASS_$_PKPaletteContainerViewAccessibility
+ _OBJC_METACLASS_$___PKPaletteContainerViewAccessibility_super
+ __OBJC_$_CLASS_METHODS_PKPaletteContainerViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_PKPaletteContainerViewAccessibility
+ __OBJC_CLASS_RO_$_PKPaletteContainerViewAccessibility
+ __OBJC_CLASS_RO_$___PKPaletteContainerViewAccessibility_super
+ __OBJC_METACLASS_RO_$_PKPaletteContainerViewAccessibility
+ __OBJC_METACLASS_RO_$___PKPaletteContainerViewAccessibility_super
- GCC_except_table120
CStrings:
+ "PKPaletteAccessoryView"
+ "PKPaletteContainerView"
+ "PKPaletteContainerViewAccessibility"
+ "accessoryView"
+ "dragHandleView"
```
