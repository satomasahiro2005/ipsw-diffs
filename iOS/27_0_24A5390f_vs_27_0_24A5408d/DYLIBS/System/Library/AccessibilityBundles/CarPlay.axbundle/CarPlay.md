## CarPlay

> `/System/Library/AccessibilityBundles/CarPlay.axbundle/CarPlay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x550` | `0x310` | **`-0x240`** |
| `__TEXT.__text` | `0x934` | `0x734` | **`-0x200`** |
| `__DATA_DIRTY.__objc_data` | `0x2d0` | `0x190` | **`-0x140`** |
| `__AUTH_CONST.__cfstring` | `0x2e0` | `0x1e0` | **`-0x100`** |
| `__TEXT.__cstring` | `0x213` | `0x146` | **`-0xcd`** |
| `__TEXT.__objc_methlist` | `0x180` | `0xe4` | **`-0x9c`** |
| `__DATA_CONST.__objc_selrefs` | `0x120` | `0xf0` | **`-0x30`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x28` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0xb0` | `0xa0` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x10` | **`-0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 28
-  Symbols:   125
-  CStrings:  29
+  Functions: 19
+  Symbols:   95
+  CStrings:  19
Symbols:
- +[CARApplicationAccessibility _accessibilityPerformValidations:]
- +[CARApplicationAccessibility(SafeCategory) safeCategoryBaseClass]
- +[CARApplicationAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[CarZoomButtonViewAccessibility _accessibilityPerformValidations:]
- +[CarZoomButtonViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[CarZoomButtonViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[CARApplicationAccessibility _accessibilityIsStarkElement]
- -[CarZoomButtonViewAccessibility _accessibilityLoadAccessibilityInformation]
- -[CarZoomButtonViewAccessibility initWithFrame:]
- _OBJC_CLASS_$_CARApplicationAccessibility
- _OBJC_CLASS_$_CarZoomButtonViewAccessibility
- _OBJC_CLASS_$___CARApplicationAccessibility_super
- _OBJC_CLASS_$___CarZoomButtonViewAccessibility_super
- _OBJC_METACLASS_$_CARApplicationAccessibility
- _OBJC_METACLASS_$_CarZoomButtonViewAccessibility
- _OBJC_METACLASS_$___CARApplicationAccessibility_super
- _OBJC_METACLASS_$___CarZoomButtonViewAccessibility_super
- __OBJC_$_CLASS_METHODS_CARApplicationAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_CarZoomButtonViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_CARApplicationAccessibility
- __OBJC_$_INSTANCE_METHODS_CarZoomButtonViewAccessibility
- __OBJC_CLASS_RO_$_CARApplicationAccessibility
- __OBJC_CLASS_RO_$_CarZoomButtonViewAccessibility
- __OBJC_CLASS_RO_$___CARApplicationAccessibility_super
- __OBJC_CLASS_RO_$___CarZoomButtonViewAccessibility_super
- __OBJC_METACLASS_RO_$_CARApplicationAccessibility
- __OBJC_METACLASS_RO_$_CarZoomButtonViewAccessibility
- __OBJC_METACLASS_RO_$___CARApplicationAccessibility_super
- __OBJC_METACLASS_RO_$___CarZoomButtonViewAccessibility_super
- _objc_retainAutoreleasedReturnValue
CStrings:
+ "DBFolderView"
+ "DBIconScrollView"
+ "DBTodayViewController"
+ "DashBoard.DBDashboardHomeViewController"
- "CARApplication"
- "CARApplicationAccessibility"
- "CARFolderView"
- "CARIconScrollView"
- "CARTodayViewController"
- "CarFocusableImageButton"
- "CarZoomButton-In"
- "CarZoomButtonView"
- "CarZoomButtonViewAccessibility"
- "_CARDashboardHomeViewController"
- "_zoomInButton"
- "_zoomOutButton"
- "initWithFrame:"
- "{CGRect={CGPoint=dd}{CGSize=dd}}"
```
