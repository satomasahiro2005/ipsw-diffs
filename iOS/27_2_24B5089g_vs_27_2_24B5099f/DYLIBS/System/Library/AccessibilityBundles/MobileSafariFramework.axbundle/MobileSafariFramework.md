## MobileSafariFramework

> `/System/Library/AccessibilityBundles/MobileSafariFramework.axbundle/MobileSafariFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcc28` | `0xdb18` | **`+0xef0`** |
| `__AUTH_CONST.__objc_const` | `0x3f90` | `0x41b0` | **`+0x220`** |
| `__AUTH_CONST.__cfstring` | `0x3920` | `0x3b00` | **`+0x1e0`** |
| `__DATA_CONST.__got` | `0x0` | `0x188` | **`+0x188`** |
| `__TEXT.__cstring` | `0x2cff` | `0x2e4a` | **`+0x14b`** |
| `__TEXT.__objc_methlist` | `0x1634` | `0x175c` | **`+0x128`** |
| `__AUTH.__objc_data` | `0xa0` | `0x190` | **`+0xf0`** |
| `__DATA_CONST.__objc_selrefs` | `0x770` | `0x828` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x560` | `0x5c8` | **`+0x68`** |
| `__TEXT.__gcc_except_tab` | `0x348` | `0x374` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x360` | `0x388` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x388` | `0x3a0` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x110` | `0x120` | **`+0x10`** |
| `__DATA.__objc_ivar` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-3050.3.1.0.0
+3050.3.5.0.0

-  Functions: 433
-  Symbols:   1165
-  CStrings:  532
+  Functions: 458
+  Symbols:   1223
+  CStrings:  547
Symbols:
+ +[SFMagicExtensionBannerAccessibility _accessibilityPerformValidations:]
+ +[SFMagicExtensionBannerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[SFMagicExtensionBannerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[SFMagicExtensionBannerAccessibility _accessibilityContentElement]
+ -[SFMagicExtensionBannerAccessibility _accessibilityDismissButtonLabel]
+ -[SFMagicExtensionBannerAccessibility _accessibilityHasBannerTapGesture]
+ -[SFMagicExtensionBannerAccessibility _accessibilitySynthesizedElements]
+ -[SFMagicExtensionBannerAccessibility accessibilityElements]
+ -[SFMagicExtensionBannerAccessibility accessibilityFrame:]
+ -[SFMagicExtensionBannerAccessibility accessibilityLabel:]
+ -[SFMagicExtensionBannerAccessibility accessibilityTraits:]
+ -[SFMagicExtensionBannerAccessibility accessibilityValue:]
+ -[SFMagicExtensionBannerAccessibility didMoveToWindow]
+ -[SFMagicExtensionBannerAccessibility isAccessibilityElement]
+ -[SFMagicExtensionBannerAccessibility shouldGroupAccessibilityChildren]
+ -[UIAccessibilityElementMagicExtensionBanner .cxx_destruct]
+ -[UIAccessibilityElementMagicExtensionBanner accessibilityActivate]
+ -[UIAccessibilityElementMagicExtensionBanner accessibilityFrame]
+ -[UIAccessibilityElementMagicExtensionBanner activateHandler]
+ -[UIAccessibilityElementMagicExtensionBanner frameSourceView]
+ -[UIAccessibilityElementMagicExtensionBanner setActivateHandler:]
+ -[UIAccessibilityElementMagicExtensionBanner setFrameSourceView:]
+ GCC_except_table316
+ GCC_except_table339
+ GCC_except_table344
+ GCC_except_table348
+ GCC_except_table370
+ GCC_except_table441
+ GCC_except_table442
+ _CGRectUnion
+ _OBJC_CLASS_$_SFMagicExtensionBannerAccessibility
+ _OBJC_CLASS_$_UIAccessibilityElement
+ _OBJC_CLASS_$_UIAccessibilityElementMagicExtensionBanner
+ _OBJC_CLASS_$_UITapGestureRecognizer
+ _OBJC_CLASS_$___SFMagicExtensionBannerAccessibility_super
+ _OBJC_IVAR_$_UIAccessibilityElementMagicExtensionBanner._activateHandler
+ _OBJC_IVAR_$_UIAccessibilityElementMagicExtensionBanner._frameSourceView
+ _OBJC_METACLASS_$_SFMagicExtensionBannerAccessibility
+ _OBJC_METACLASS_$_UIAccessibilityElement
+ _OBJC_METACLASS_$_UIAccessibilityElementMagicExtensionBanner
+ _OBJC_METACLASS_$___SFMagicExtensionBannerAccessibility_super
+ _UIAXFormatFloatWithPercentage
+ _UIAccessibilityTraitUpdatesFrequently
+ __OBJC_$_CLASS_METHODS_SFMagicExtensionBannerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_SFMagicExtensionBannerAccessibility
+ __OBJC_$_INSTANCE_METHODS_UIAccessibilityElementMagicExtensionBanner
+ __OBJC_$_INSTANCE_VARIABLES_UIAccessibilityElementMagicExtensionBanner
+ __OBJC_$_PROP_LIST_UIAccessibilityElementMagicExtensionBanner
+ __OBJC_CLASS_RO_$_SFMagicExtensionBannerAccessibility
+ __OBJC_CLASS_RO_$_UIAccessibilityElementMagicExtensionBanner
+ __OBJC_CLASS_RO_$___SFMagicExtensionBannerAccessibility_super
+ __OBJC_METACLASS_RO_$_SFMagicExtensionBannerAccessibility
+ __OBJC_METACLASS_RO_$_UIAccessibilityElementMagicExtensionBanner
+ __OBJC_METACLASS_RO_$___SFMagicExtensionBannerAccessibility_super
+ ___54-[SFMagicExtensionBannerAccessibility didMoveToWindow]_block_invoke
+ ___67-[UIAccessibilityElementMagicExtensionBanner accessibilityActivate]_block_invoke
+ ___72-[SFMagicExtensionBannerAccessibility _accessibilitySynthesizedElements]_block_invoke
+ ___block_descriptor_40_e8_32bs_e5_v8?0ls32l8
+ _kUIAccessibilityStorageKeyChildren
+ _objc_retain_x21
+ _objc_setProperty_nonatomic_copy
+ _objc_storeStrong
+ _objc_storeWeak
- GCC_except_table314
- GCC_except_table323
- GCC_except_table345
- GCC_except_table391
- GCC_except_table417
CStrings:
+ "AXMagicExtensionBannerDidMoveFocus"
+ "SFMagicExtensionBanner"
+ "SFMagicExtensionBannerAccessibility"
+ "WBSAnimatableSymbol"
+ "_bannerTapped"
+ "_dismissButton"
+ "action"
+ "didMoveToWindow"
+ "magic.extension.banner.cancel"
+ "magic.extension.banner.save"
+ "magic.extension.banner.stop"
+ "messageLabel"
+ "preferredCloseButtonStyle"
+ "progressIndicatorView"
+ "variableValue"
```
