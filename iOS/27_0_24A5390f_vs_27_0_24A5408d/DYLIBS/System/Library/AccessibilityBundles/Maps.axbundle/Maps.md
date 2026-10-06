## Maps

> `/System/Library/AccessibilityBundles/Maps.axbundle/Maps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x157e8` | `0x159ac` | **`+0x1c4`** |
| `__AUTH_CONST.__objc_const` | `0x8270` | `0x8390` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x140` | `0x1e0` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x63c0` | `0x6460` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x48f7` | `0x496e` | **`+0x77`** |
| `__TEXT.__objc_methlist` | `0x27a0` | `0x27f0` | **`+0x50`** |
| `__DATA_CONST.__objc_classlist` | `0x738` | `0x748` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x890` | `0x8a0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x260` | `0x268` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 731
-  Symbols:   2129
-  CStrings:  857
+  Functions: 736
+  Symbols:   2144
+  CStrings:  863
Symbols:
+ +[CarZoomButtonViewAccessibility _accessibilityPerformValidations:]
+ +[CarZoomButtonViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[CarZoomButtonViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[CarZoomButtonViewAccessibility _accessibilityLoadAccessibilityInformation]
+ -[CarZoomButtonViewAccessibility initWithFrame:]
+ GCC_except_table571
+ GCC_except_table600
+ GCC_except_table609
+ GCC_except_table610
+ GCC_except_table727
+ _OBJC_CLASS_$_CarZoomButtonViewAccessibility
+ _OBJC_CLASS_$___CarZoomButtonViewAccessibility_super
+ _OBJC_METACLASS_$_CarZoomButtonViewAccessibility
+ _OBJC_METACLASS_$___CarZoomButtonViewAccessibility_super
+ __OBJC_$_CLASS_METHODS_CarZoomButtonViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_CarZoomButtonViewAccessibility
+ __OBJC_CLASS_RO_$_CarZoomButtonViewAccessibility
+ __OBJC_CLASS_RO_$___CarZoomButtonViewAccessibility_super
+ __OBJC_METACLASS_RO_$_CarZoomButtonViewAccessibility
+ __OBJC_METACLASS_RO_$___CarZoomButtonViewAccessibility_super
- GCC_except_table566
- GCC_except_table595
- GCC_except_table604
- GCC_except_table605
- GCC_except_table722
CStrings:
+ "CarFocusableImageButton"
+ "CarZoomButton-In"
+ "CarZoomButtonView"
+ "CarZoomButtonViewAccessibility"
+ "_zoomInButton"
+ "_zoomOutButton"
```
