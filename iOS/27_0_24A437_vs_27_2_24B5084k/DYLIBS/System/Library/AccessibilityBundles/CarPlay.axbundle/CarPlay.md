## CarPlay

> `/System/Library/AccessibilityBundles/CarPlay.axbundle/CarPlay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x734` | `0x238` | **`-0x4fc`** |
| `__AUTH_CONST.__objc_const` | `0x310` | `0xd0` | **`-0x240`** |
| `__AUTH_CONST.__cfstring` | `0x1e0` | `0x80` | **`-0x160`** |
| `__DATA_DIRTY.__objc_data` | `0x190` | `0x50` | **`-0x140`** |
| `__TEXT.__cstring` | `0x146` | `0x60` | **`-0xe6`** |
| `__TEXT.__objc_methlist` | `0xe4` | `0x50` | **`-0x94`** |
| `__DATA_CONST.__objc_selrefs` | `0xf0` | `0x60` | **`-0x90`** |
| `__DATA_CONST.__got` | `0x48` | `0x20` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0xa0` | `0x78` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x80` | `0x60` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x60` | `0x40` | **`-0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x8` | **`-0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0x10` | `0x8` | **`-0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 19
-  Symbols:   95
-  CStrings:  19
+  Functions: 9
+  Symbols:   47
+  CStrings:  6
Symbols:
- +[CARFolderViewAccessibility _accessibilityPerformValidations:]
- +[CARFolderViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[CARFolderViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[CARIconScrollViewAccessibility _accessibilityPerformValidations:]
- +[CARIconScrollViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[CARIconScrollViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[CARFolderViewAccessibility _accessibilityUserTestingChildrenFromSBRootFolderView]
- -[CARFolderViewAccessibility automationElements]
- -[CARIconScrollViewAccessibility automationElements]
- _AXGuaranteedMutableArray
- _AXSafeClassFromString
- _OBJC_CLASS_$_CARFolderViewAccessibility
- _OBJC_CLASS_$_CARIconScrollViewAccessibility
- _OBJC_CLASS_$_NSArray
- _OBJC_CLASS_$_UIAccessibilitySafeCategory
- _OBJC_CLASS_$_UIView
- _OBJC_CLASS_$_UIViewController
- _OBJC_CLASS_$___CARFolderViewAccessibility_super
- _OBJC_CLASS_$___CARIconScrollViewAccessibility_super
- _OBJC_METACLASS_$_CARFolderViewAccessibility
- _OBJC_METACLASS_$_CARIconScrollViewAccessibility
- _OBJC_METACLASS_$_UIAccessibilitySafeCategory
- _OBJC_METACLASS_$___CARFolderViewAccessibility_super
- _OBJC_METACLASS_$___CARIconScrollViewAccessibility_super
- __OBJC_$_CLASS_METHODS_CARFolderViewAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_CARIconScrollViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_CARFolderViewAccessibility
- __OBJC_$_INSTANCE_METHODS_CARIconScrollViewAccessibility
- __OBJC_CLASS_RO_$_CARFolderViewAccessibility
- __OBJC_CLASS_RO_$_CARIconScrollViewAccessibility
- __OBJC_CLASS_RO_$___CARFolderViewAccessibility_super
- __OBJC_CLASS_RO_$___CARIconScrollViewAccessibility_super
- __OBJC_METACLASS_RO_$_CARFolderViewAccessibility
- __OBJC_METACLASS_RO_$_CARIconScrollViewAccessibility
- __OBJC_METACLASS_RO_$___CARFolderViewAccessibility_super
- __OBJC_METACLASS_RO_$___CARIconScrollViewAccessibility_super
- ___52-[CARIconScrollViewAccessibility automationElements]_block_invoke
- ___UIAccessibilityCastAsClass
- ___UIAccessibilityCastAsSafeCategory
- ___block_descriptor_32_e8_B16?08l
- _abort
- _objc_opt_isKindOfClass
- _objc_release
- _objc_release_x21
- _objc_release_x22
- _objc_release_x23
- _objc_release_x24
- _objc_retain_x2
Functions:
~ ___46+[AXCarPlayGlue accessibilityInitializeBundle]_block_invoke_3 : 92 -> 4
CStrings:
- "@"
- "B16@?0@8"
- "CARFolderViewAccessibility"
- "CARIconScrollViewAccessibility"
- "DBFolderView"
- "DBIconScrollView"
- "DBTodayViewController"
- "DashBoard.DBDashboardHomeViewController"
- "SBFolderView"
- "UIView"
- "UIViewController"
- "pageControl"
- "todayViewController"
```
