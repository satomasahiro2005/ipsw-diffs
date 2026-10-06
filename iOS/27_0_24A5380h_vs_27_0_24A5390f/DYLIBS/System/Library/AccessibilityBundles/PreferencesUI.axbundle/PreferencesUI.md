## PreferencesUI

> `/System/Library/AccessibilityBundles/PreferencesUI.axbundle/PreferencesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x500` | `0xa1c` | **`+0x51c`** |
| `__AUTH_CONST.__objc_const` | `0x3f0` | `0x510` | **`+0x120`** |
| `__AUTH.__objc_data` | `0xa0` | `0x140` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x200` | `0x280` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1ad` | `0x1fd` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xb8` | `0x100` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0xf4` | `0x13c` | **`+0x48`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x38` | **`+0x38`** |
| `__AUTH_CONST.__objc_arrayobj` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x98` | `0xb0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x48` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x10` | `0x18` | **`+0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 20
-  Symbols:   92
-  CStrings:  21
+  Functions: 24
+  Symbols:   115
+  CStrings:  25
Symbols:
+ +[PSUICellularPlanTableCellAccessibility _accessibilityPerformValidations:]
+ +[PSUICellularPlanTableCellAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PSUICellularPlanTableCellAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[PSUICellularPlanTableCellAccessibility accessibilityLabel]
+ _OBJC_CLASS_$_NSConstantArray
+ _OBJC_CLASS_$_NSMutableArray
+ _OBJC_CLASS_$_PSUICellularPlanTableCellAccessibility
+ _OBJC_CLASS_$_UILabel
+ _OBJC_CLASS_$___PSUICellularPlanTableCellAccessibility_super
+ _OBJC_METACLASS_$_PSUICellularPlanTableCellAccessibility
+ _OBJC_METACLASS_$___PSUICellularPlanTableCellAccessibility_super
+ __OBJC_$_CLASS_METHODS_PSUICellularPlanTableCellAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_PSUICellularPlanTableCellAccessibility
+ __OBJC_CLASS_RO_$_PSUICellularPlanTableCellAccessibility
+ __OBJC_CLASS_RO_$___PSUICellularPlanTableCellAccessibility_super
+ __OBJC_METACLASS_RO_$_PSUICellularPlanTableCellAccessibility
+ __OBJC_METACLASS_RO_$___PSUICellularPlanTableCellAccessibility_super
+ ___UIAccessibilityCastAsClass
+ ___stack_chk_fail
+ ___stack_chk_guard
+ _abort
+ _objc_enumerationMutation
+ _objc_release_x25
CStrings:
+ ", "
+ "PSUICellularPlanTableCell"
+ "PSUICellularPlanTableCellAccessibility"
+ "statusLabel"
```
