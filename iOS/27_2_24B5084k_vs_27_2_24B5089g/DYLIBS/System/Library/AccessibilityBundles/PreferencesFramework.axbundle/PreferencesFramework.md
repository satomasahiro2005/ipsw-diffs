## PreferencesFramework

> `/System/Library/AccessibilityBundles/PreferencesFramework.axbundle/PreferencesFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c14` | `0x847c` | **`+0x868`** |
| `__AUTH_CONST.__objc_const` | `0x2fd0` | `0x30f0` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x1e0` | `0x280` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x2060` | `0x20e0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1941` | `0x19b3` | **`+0x72`** |
| `__TEXT.__objc_methlist` | `0x1024` | `0x1074` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x1f8` | `0x238` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x6d0` | `0x710` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x378` | `0x3a0` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x140` | `0x160` | **`+0x20`** |
| `__DATA.__bss` | `0x8` | `0x18` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x2a8` | `0x2b8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xd0` | `0xd8` | **`+0x8`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  Functions: 298
-  Symbols:   880
-  CStrings:  291
+  Functions: 306
+  Symbols:   915
+  CStrings:  295
Symbols:
+ +[PSSwitchTableCellAccessibility _accessibilityPerformValidations:]
+ +[PSSwitchTableCellAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PSSwitchTableCellAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[PSSwitchTableCellAccessibility _axSwitchCellContentFrame]
+ -[PSSwitchTableCellAccessibility accessibilityPath]
+ -[PSSwitchTableCellAccessibility tableTextAccessibleFrame:]
+ GCC_except_table117
+ GCC_except_table122
+ GCC_except_table178
+ GCC_except_table205
+ GCC_except_table97
+ _CGRectEqualToRect
+ _CGRectIsEmpty
+ _CGRectIsNull
+ _CGRectNull
+ _CGRectUnion
+ _OBJC_CLASS_$_NSSet
+ _OBJC_CLASS_$_PSSwitchTableCellAccessibility
+ _OBJC_CLASS_$_UIActivityIndicatorView
+ _OBJC_CLASS_$_UIBezierPath
+ _OBJC_CLASS_$_UIControl
+ _OBJC_CLASS_$_UIImageView
+ _OBJC_CLASS_$_UILabel
+ _OBJC_CLASS_$_UITableViewCell
+ _OBJC_CLASS_$___PSSwitchTableCellAccessibility_super
+ _OBJC_METACLASS_$_PSSwitchTableCellAccessibility
+ _OBJC_METACLASS_$___PSSwitchTableCellAccessibility_super
+ _UIAccessibilityConvertFrameToScreenCoordinates
+ __OBJC_$_CLASS_METHODS_PSSwitchTableCellAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_PSSwitchTableCellAccessibility
+ __OBJC_CLASS_RO_$_PSSwitchTableCellAccessibility
+ __OBJC_CLASS_RO_$___PSSwitchTableCellAccessibility_super
+ __OBJC_METACLASS_RO_$_PSSwitchTableCellAccessibility
+ __OBJC_METACLASS_RO_$___PSSwitchTableCellAccessibility_super
+ ____axCollectContentFrames_block_invoke
+ __axCollectContentFrames
+ __axCollectContentFrames.ExcludedClasses
+ __axCollectContentFrames.onceToken
+ _dispatch_once
+ _objc_release_x9
- GCC_except_table109
- GCC_except_table114
- GCC_except_table170
- GCC_except_table197
- GCC_except_table89
CStrings:
+ "PSSwitchTableCell"
+ "PSSwitchTableCellAccessibility"
+ "UITableViewCellDeleteConfirmationView"
+ "UITableViewCellEditControl"
```
