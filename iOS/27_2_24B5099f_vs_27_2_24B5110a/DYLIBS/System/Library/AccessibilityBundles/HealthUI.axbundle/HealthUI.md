## HealthUI

> `/System/Library/AccessibilityBundles/HealthUI.axbundle/HealthUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x610c` | `0x6568` | **`+0x45c`** |
| `__AUTH_CONST.__objc_const` | `0x1a70` | `0x1b90` | **`+0x120`** |
| `__AUTH_CONST.__cfstring` | `0x1be0` | `0x1ce0` | **`+0x100`** |
| `__TEXT.__cstring` | `0x14a4` | `0x156d` | **`+0xc9`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x8cc` | `0x92c` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x2e0` | `0x330` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x4c8` | `0x4f0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x268` | `0x288` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x160` | `0x174` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x128` | `0x138` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x178` | `0x188` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x70` | `0x78` | **`+0x8`** |

### Other Changes

```diff

-3050.3.5.0.0
+3050.3.8.0.0

-  Functions: 177
-  Symbols:   545
-  CStrings:  248
+  Functions: 185
+  Symbols:   568
+  CStrings:  257
Symbols:
+ +[HKSimpleDataEntryPlainTextCellAccessibility _accessibilityPerformValidations:]
+ +[HKSimpleDataEntryPlainTextCellAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[HKSimpleDataEntryPlainTextCellAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[HKSimpleDataEntryPlainTextCellAccessibility _accessibilityLoadAccessibilityInformation]
+ -[HKSimpleDataEntryPlainTextCellAccessibility _axSetInputTextFieldActivationSelectsRow]
+ -[HKSimpleDataEntryPlainTextCellAccessibility initWithIntention:reuseIdentifier:]
+ GCC_except_table59
+ GCC_except_table78
+ _OBJC_CLASS_$_HKSimpleDataEntryPlainTextCellAccessibility
+ _OBJC_CLASS_$_UITableView
+ _OBJC_CLASS_$_UITextField
+ _OBJC_CLASS_$___HKSimpleDataEntryPlainTextCellAccessibility_super
+ _OBJC_METACLASS_$_HKSimpleDataEntryPlainTextCellAccessibility
+ _OBJC_METACLASS_$___HKSimpleDataEntryPlainTextCellAccessibility_super
+ __OBJC_$_CLASS_METHODS_HKSimpleDataEntryPlainTextCellAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_HKSimpleDataEntryPlainTextCellAccessibility
+ __OBJC_CLASS_RO_$_HKSimpleDataEntryPlainTextCellAccessibility
+ __OBJC_CLASS_RO_$___HKSimpleDataEntryPlainTextCellAccessibility_super
+ __OBJC_METACLASS_RO_$_HKSimpleDataEntryPlainTextCellAccessibility
+ __OBJC_METACLASS_RO_$___HKSimpleDataEntryPlainTextCellAccessibility_super
+ ___87-[HKSimpleDataEntryPlainTextCellAccessibility _axSetInputTextFieldActivationSelectsRow]_block_invoke
+ ___87-[HKSimpleDataEntryPlainTextCellAccessibility _axSetInputTextFieldActivationSelectsRow]_block_invoke_2
+ ___block_descriptor_48_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_48_e8_32w40w_e5_B8?0lw32l8w40l8
- GCC_except_table70
CStrings:
+ "B8@?0"
+ "HKCaretOptionalTextField"
+ "HKSimpleDataEntryPlainTextCell"
+ "HKSimpleDataEntryPlainTextCellAccessibility"
+ "UITableView"
+ "_userSelectCell:"
+ "allowsSelection"
+ "initWithIntention:reuseIdentifier:"
+ "inputTextField"
```
