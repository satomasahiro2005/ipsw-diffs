## InternationalSettings

> `/System/Library/AccessibilityBundles/InternationalSettings.axbundle/InternationalSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x96c` | `0xca4` | **`+0x338`** |
| `__AUTH_CONST.__objc_const` | `0x3f0` | `0x630` | **`+0x240`** |
| `__AUTH.__objc_data` | `0x230` | `0x370` | **`+0x140`** |
| `__TEXT.__cstring` | `0x1cd` | `0x2ae` | **`+0xe1`** |
| `__AUTH_CONST.__cfstring` | `0x220` | `0x2e0` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0xe4` | `0x17c` | **`+0x98`** |
| `__DATA_CONST.__got` | `0x0` | `0x78` | **`+0x78`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x58` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xb0` | `0xc8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x118` | `0x128` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x28` | **`+0x10`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 20
-  Symbols:   108
-  CStrings:  23
+  Functions: 29
+  Symbols:   139
+  CStrings:  29
Symbols:
+ +[AXInternationalSettingsGlue axTagDateNumberFormatCell:]
+ +[ISNumberFormatListItemControllersAccessibility _accessibilityPerformValidations:]
+ +[ISNumberFormatListItemControllersAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[ISNumberFormatListItemControllersAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[ISReloadOnLocaleChangeListItemsControllerAccessibility _accessibilityPerformValidations:]
+ +[ISReloadOnLocaleChangeListItemsControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[ISReloadOnLocaleChangeListItemsControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[ISNumberFormatListItemControllersAccessibility tableView:cellForRowAtIndexPath:]
+ -[ISReloadOnLocaleChangeListItemsControllerAccessibility tableView:cellForRowAtIndexPath:]
+ GCC_except_table6
+ _OBJC_CLASS_$_ISNumberFormatListItemControllersAccessibility
+ _OBJC_CLASS_$_ISReloadOnLocaleChangeListItemsControllerAccessibility
+ _OBJC_CLASS_$_UITableViewCell
+ _OBJC_CLASS_$___ISNumberFormatListItemControllersAccessibility_super
+ _OBJC_CLASS_$___ISReloadOnLocaleChangeListItemsControllerAccessibility_super
+ _OBJC_METACLASS_$_ISNumberFormatListItemControllersAccessibility
+ _OBJC_METACLASS_$_ISReloadOnLocaleChangeListItemsControllerAccessibility
+ _OBJC_METACLASS_$___ISNumberFormatListItemControllersAccessibility_super
+ _OBJC_METACLASS_$___ISReloadOnLocaleChangeListItemsControllerAccessibility_super
+ __OBJC_$_CLASS_METHODS_ISNumberFormatListItemControllersAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS_ISReloadOnLocaleChangeListItemsControllerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_ISNumberFormatListItemControllersAccessibility
+ __OBJC_$_INSTANCE_METHODS_ISReloadOnLocaleChangeListItemsControllerAccessibility
+ __OBJC_CLASS_RO_$_ISNumberFormatListItemControllersAccessibility
+ __OBJC_CLASS_RO_$_ISReloadOnLocaleChangeListItemsControllerAccessibility
+ __OBJC_CLASS_RO_$___ISNumberFormatListItemControllersAccessibility_super
+ __OBJC_CLASS_RO_$___ISReloadOnLocaleChangeListItemsControllerAccessibility_super
+ __OBJC_METACLASS_RO_$_ISNumberFormatListItemControllersAccessibility
+ __OBJC_METACLASS_RO_$_ISReloadOnLocaleChangeListItemsControllerAccessibility
+ __OBJC_METACLASS_RO_$___ISNumberFormatListItemControllersAccessibility_super
+ __OBJC_METACLASS_RO_$___ISReloadOnLocaleChangeListItemsControllerAccessibility_super
+ ___kCFBooleanTrue
- GCC_except_table5
CStrings:
+ "ISNumberFormatListItemControllers"
+ "ISNumberFormatListItemControllersAccessibility"
+ "ISReloadOnLocaleChangeListItemsController"
+ "ISReloadOnLocaleChangeListItemsControllerAccessibility"
+ "PSListItemsController"
+ "axIsDateNumberFormatCell"
```
