## EventKitUIFramework

> `/System/Library/AccessibilityBundles/EventKitUIFramework.axbundle/EventKitUIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xefc4` | `0xf130` | **`+0x16c`** |
| `__AUTH_CONST.__objc_const` | `0x4308` | `0x4428` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x230` | `0x2d0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x1814` | `0x1874` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2de4` | `0x2e29` | **`+0x45`** |
| `__AUTH_CONST.__cfstring` | `0x35c0` | `0x3600` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x560` | `0x578` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x390` | `0x3a0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x140` | `0x148` | **`+0x8`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  Functions: 450
-  Symbols:   1272
-  CStrings:  483
+  Functions: 456
+  Symbols:   1288
+  CStrings:  485
Symbols:
+ +[EKShowInRemindersDetailCellAccessibility _accessibilityPerformValidations:]
+ +[EKShowInRemindersDetailCellAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[EKShowInRemindersDetailCellAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[EKShowInRemindersDetailCellAccessibility accessibilityLabel]
+ -[EKShowInRemindersDetailCellAccessibility accessibilityTraits]
+ -[EKShowInRemindersDetailCellAccessibility isAccessibilityElement]
+ GCC_except_table204
+ GCC_except_table243
+ GCC_except_table286
+ GCC_except_table293
+ GCC_except_table309
+ GCC_except_table324
+ GCC_except_table341
+ _OBJC_CLASS_$_EKShowInRemindersDetailCellAccessibility
+ _OBJC_CLASS_$___EKShowInRemindersDetailCellAccessibility_super
+ _OBJC_METACLASS_$_EKShowInRemindersDetailCellAccessibility
+ _OBJC_METACLASS_$___EKShowInRemindersDetailCellAccessibility_super
+ __OBJC_$_CLASS_METHODS_EKShowInRemindersDetailCellAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_EKShowInRemindersDetailCellAccessibility
+ __OBJC_CLASS_RO_$_EKShowInRemindersDetailCellAccessibility
+ __OBJC_CLASS_RO_$___EKShowInRemindersDetailCellAccessibility_super
+ __OBJC_METACLASS_RO_$_EKShowInRemindersDetailCellAccessibility
+ __OBJC_METACLASS_RO_$___EKShowInRemindersDetailCellAccessibility_super
- GCC_except_table198
- GCC_except_table237
- GCC_except_table280
- GCC_except_table287
- GCC_except_table303
- GCC_except_table312
- GCC_except_table335
CStrings:
+ "EKShowInRemindersDetailCell"
+ "EKShowInRemindersDetailCellAccessibility"
```
