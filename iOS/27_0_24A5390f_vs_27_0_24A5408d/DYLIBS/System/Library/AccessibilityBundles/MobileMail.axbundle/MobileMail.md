## MobileMail

> `/System/Library/AccessibilityBundles/MobileMail.axbundle/MobileMail`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x135f8` | `0x13544` | **`-0xb4`** |
| `__AUTH.__objc_data` | `0x140` | `0x1e0` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x23a0` | `0x2300` | **`-0xa0`** |
| `__DATA_CONST.__const` | `0x798` | `0x7c0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x48a0` | `0x4880` | **`-0x20`** |
| `__TEXT.__cstring` | `0x3735` | `0x3727` | **`-0xe`** |
| `__DATA_CONST.__objc_selrefs` | `0xd80` | `0xd88` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x160` | `0x158` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x720` | `0x718` | **`-0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 539
-  Symbols:   1391
-  CStrings:  623
+  Functions: 540
+  Symbols:   1394
+  CStrings:  622
Symbols:
+ +[FilterCriteriaContainerViewAccessibility _accessibilityPerformValidations:]
+ +[FilterCriteriaContainerViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[FilterCriteriaContainerViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[FilterCriteriaContainerViewAccessibility isAccessibilityElement]
+ GCC_except_table106
+ GCC_except_table108
+ GCC_except_table138
+ GCC_except_table151
+ GCC_except_table183
+ GCC_except_table197
+ GCC_except_table230
+ GCC_except_table272
+ GCC_except_table282
+ GCC_except_table330
+ GCC_except_table351
+ GCC_except_table358
+ GCC_except_table378
+ GCC_except_table382
+ GCC_except_table388
+ GCC_except_table407
+ GCC_except_table418
+ GCC_except_table421
+ GCC_except_table441
+ GCC_except_table454
+ GCC_except_table471
+ GCC_except_table494
+ GCC_except_table504
+ GCC_except_table74
+ GCC_except_table83
+ GCC_except_table95
+ _OBJC_CLASS_$_FilterCriteriaContainerViewAccessibility
+ _OBJC_CLASS_$___FilterCriteriaContainerViewAccessibility_super
+ _OBJC_METACLASS_$_FilterCriteriaContainerViewAccessibility
+ _OBJC_METACLASS_$___FilterCriteriaContainerViewAccessibility_super
+ __OBJC_$_CLASS_METHODS_FilterCriteriaContainerViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_FilterCriteriaContainerViewAccessibility
+ __OBJC_CLASS_RO_$_FilterCriteriaContainerViewAccessibility
+ __OBJC_CLASS_RO_$___FilterCriteriaContainerViewAccessibility_super
+ __OBJC_METACLASS_RO_$_FilterCriteriaContainerViewAccessibility
+ __OBJC_METACLASS_RO_$___FilterCriteriaContainerViewAccessibility_super
+ ___86-[DockContainerViewControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_2
+ ___block_descriptor_48_e8_32s40w_e5_v8?0lw40l8s32l8
+ _dispatch_async
- +[CategorizationOptionViewAccessibility _accessibilityPerformValidations:]
- +[CategorizationOptionViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[CategorizationOptionViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[CategorizationOptionViewAccessibility _accessibilityLoadAccessibilityInformation]
- GCC_except_table102
- GCC_except_table104
- GCC_except_table134
- GCC_except_table147
- GCC_except_table178
- GCC_except_table192
- GCC_except_table225
- GCC_except_table271
- GCC_except_table281
- GCC_except_table329
- GCC_except_table350
- GCC_except_table357
- GCC_except_table377
- GCC_except_table381
- GCC_except_table387
- GCC_except_table406
- GCC_except_table417
- GCC_except_table420
- GCC_except_table440
- GCC_except_table453
- GCC_except_table470
- GCC_except_table493
- GCC_except_table503
- GCC_except_table66
- GCC_except_table79
- GCC_except_table91
- _OBJC_CLASS_$_CategorizationOptionViewAccessibility
- _OBJC_CLASS_$___CategorizationOptionViewAccessibility_super
- _OBJC_METACLASS_$_CategorizationOptionViewAccessibility
- _OBJC_METACLASS_$___CategorizationOptionViewAccessibility_super
- __OBJC_$_CLASS_METHODS_CategorizationOptionViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_CategorizationOptionViewAccessibility
- __OBJC_CLASS_RO_$_CategorizationOptionViewAccessibility
- __OBJC_CLASS_RO_$___CategorizationOptionViewAccessibility_super
- __OBJC_METACLASS_RO_$_CategorizationOptionViewAccessibility
- __OBJC_METACLASS_RO_$___CategorizationOptionViewAccessibility_super
CStrings:
+ "FilterCriteriaContainerViewAccessibility"
+ "MFFilterCriteriaContainerView"
- "CategorizationOptionView"
- "CategorizationOptionViewAccessibility"
- "checkmark.circle.fill"
```
