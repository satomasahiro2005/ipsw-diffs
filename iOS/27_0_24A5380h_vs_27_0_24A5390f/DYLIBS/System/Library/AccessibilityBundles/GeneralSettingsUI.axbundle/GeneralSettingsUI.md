## GeneralSettingsUI

> `/System/Library/AccessibilityBundles/GeneralSettingsUI.axbundle/GeneralSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x3f0` | `0x1b0` | **`-0x240`** |
| `__DATA_DIRTY.__objc_data` | `0x230` | `0xf0` | **`-0x140`** |
| `__TEXT.__text` | `0x424` | `0x2f8` | **`-0x12c`** |
| `__TEXT.__objc_methlist` | `0x100` | `0x5c` | **`-0xa4`** |
| `__AUTH_CONST.__cfstring` | `0x1e0` | `0x140` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x186` | `0x103` | **`-0x83`** |
| `__DATA_CONST.__objc_selrefs` | `0xd0` | `0xa8` | **`-0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x18` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x88` | `0x78` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x30` | `0x28` | **`-0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 20
-  Symbols:   89
-  CStrings:  19
+  Functions: 10
+  Symbols:   57
+  CStrings:  13
Symbols:
- +[PSGCarrierRejectCodePaneAccessibility _accessibilityPerformValidations:]
- +[PSGCarrierRejectCodePaneAccessibility(SafeCategory) safeCategoryBaseClass]
- +[PSGCarrierRejectCodePaneAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[PSGPreBuddyCellAccessibility _accessibilityPerformValidations:]
- +[PSGPreBuddyCellAccessibility(SafeCategory) safeCategoryBaseClass]
- +[PSGPreBuddyCellAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[PSGCarrierRejectCodePaneAccessibility accessibilityLabel]
- -[PSGCarrierRejectCodePaneAccessibility isAccessibilityElement]
- -[PSGPreBuddyCellAccessibility accessibilityLabel]
- -[PSGPreBuddyCellAccessibility accessibilityTraits]
- _OBJC_CLASS_$_PSGCarrierRejectCodePaneAccessibility
- _OBJC_CLASS_$_PSGPreBuddyCellAccessibility
- _OBJC_CLASS_$___PSGCarrierRejectCodePaneAccessibility_super
- _OBJC_CLASS_$___PSGPreBuddyCellAccessibility_super
- _OBJC_METACLASS_$_PSGCarrierRejectCodePaneAccessibility
- _OBJC_METACLASS_$_PSGPreBuddyCellAccessibility
- _OBJC_METACLASS_$___PSGCarrierRejectCodePaneAccessibility_super
- _OBJC_METACLASS_$___PSGPreBuddyCellAccessibility_super
- _UIAccessibilityTraitNone
- __OBJC_$_CLASS_METHODS_PSGCarrierRejectCodePaneAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_PSGPreBuddyCellAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_PSGCarrierRejectCodePaneAccessibility
- __OBJC_$_INSTANCE_METHODS_PSGPreBuddyCellAccessibility
- __OBJC_CLASS_RO_$_PSGCarrierRejectCodePaneAccessibility
- __OBJC_CLASS_RO_$_PSGPreBuddyCellAccessibility
- __OBJC_CLASS_RO_$___PSGCarrierRejectCodePaneAccessibility_super
- __OBJC_CLASS_RO_$___PSGPreBuddyCellAccessibility_super
- __OBJC_METACLASS_RO_$_PSGCarrierRejectCodePaneAccessibility
- __OBJC_METACLASS_RO_$_PSGPreBuddyCellAccessibility
- __OBJC_METACLASS_RO_$___PSGCarrierRejectCodePaneAccessibility_super
- __OBJC_METACLASS_RO_$___PSGPreBuddyCellAccessibility_super
- _objc_release
Functions:
~ ___56+[AXGeneralSettingsUIGlue accessibilityInitializeBundle]_block_invoke_3 : 112 -> 20
CStrings:
- "PSGCarrierRejectCodePane"
- "PSGCarrierRejectCodePaneAccessibility"
- "PSGPreBuddyCell"
- "PSGPreBuddyCellAccessibility"
- "UILabel"
- "_rejectMessage"
```
