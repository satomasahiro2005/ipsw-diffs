## EventKitUIFramework

> `/System/Library/AccessibilityBundles/EventKitUIFramework.axbundle/EventKitUIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xee58` | `0xefc4` | **`+0x16c`** |
| `__AUTH_CONST.__objc_const` | `0x41e8` | `0x4308` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x190` | `0x230` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x17b4` | `0x1814` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2da1` | `0x2de4` | **`+0x43`** |
| `__AUTH_CONST.__cfstring` | `0x3580` | `0x35c0` | **`+0x40`** |
| `__DATA_CONST.__objc_classlist` | `0x380` | `0x390` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x550` | `0x560` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x138` | `0x140` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 444
-  Symbols:   1256
-  CStrings:  481
+  Functions: 450
+  Symbols:   1272
+  CStrings:  483
Symbols:
+ +[EKReminderDeleteDetailCellAccessibility _accessibilityPerformValidations:]
+ +[EKReminderDeleteDetailCellAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[EKReminderDeleteDetailCellAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[EKReminderDeleteDetailCellAccessibility accessibilityLabel]
+ -[EKReminderDeleteDetailCellAccessibility accessibilityTraits]
+ -[EKReminderDeleteDetailCellAccessibility isAccessibilityElement]
+ GCC_except_table198
+ GCC_except_table237
+ GCC_except_table280
+ GCC_except_table287
+ GCC_except_table303
+ GCC_except_table318
+ GCC_except_table335
+ _OBJC_CLASS_$_EKReminderDeleteDetailCellAccessibility
+ _OBJC_CLASS_$___EKReminderDeleteDetailCellAccessibility_super
+ _OBJC_METACLASS_$_EKReminderDeleteDetailCellAccessibility
+ _OBJC_METACLASS_$___EKReminderDeleteDetailCellAccessibility_super
+ __OBJC_$_CLASS_METHODS_EKReminderDeleteDetailCellAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_EKReminderDeleteDetailCellAccessibility
+ __OBJC_CLASS_RO_$_EKReminderDeleteDetailCellAccessibility
+ __OBJC_CLASS_RO_$___EKReminderDeleteDetailCellAccessibility_super
+ __OBJC_METACLASS_RO_$_EKReminderDeleteDetailCellAccessibility
+ __OBJC_METACLASS_RO_$___EKReminderDeleteDetailCellAccessibility_super
- GCC_except_table192
- GCC_except_table231
- GCC_except_table274
- GCC_except_table281
- GCC_except_table297
- GCC_except_table306
- GCC_except_table329
CStrings:
+ "EKReminderDeleteDetailCell"
+ "EKReminderDeleteDetailCellAccessibility"
```
