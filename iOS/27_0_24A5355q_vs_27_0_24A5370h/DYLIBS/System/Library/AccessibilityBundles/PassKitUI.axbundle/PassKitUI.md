## PassKitUI

> `/System/Library/AccessibilityBundles/PassKitUI.axbundle/PassKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13a14` | `0x13c10` | **`+0x1fc`** |
| `__AUTH_CONST.__objc_const` | `0x7ff8` | `0x8118` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x870` | `0x910` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x40e4` | `0x4177` | **`+0x93`** |
| `__AUTH_CONST.__cfstring` | `0x5500` | `0x5580` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x2afc` | `0x2b4c` | **`+0x50`** |
| `__DATA_CONST.__objc_classlist` | `0x700` | `0x710` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x220` | `0x228` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xb10` | `0xb18` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x228` | `0x230` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x860` | `0x868` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 761
-  Symbols:   2119
-  CStrings:  729
+  Functions: 766
+  Symbols:   2137
+  CStrings:  733
Symbols:
+ +[PKTransactionAuthenticationPasscodeViewControllerAccessibility _accessibilityPerformValidations:]
+ +[PKTransactionAuthenticationPasscodeViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PKTransactionAuthenticationPasscodeViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[PKTransactionAuthenticationPasscodeViewControllerAccessibility viewWillAppear:]
+ -[PKTransactionAuthenticationPasscodeViewControllerAccessibility viewWillDisappear:]
+ GCC_except_table262
+ GCC_except_table294
+ GCC_except_table315
+ GCC_except_table341
+ GCC_except_table361
+ GCC_except_table445
+ GCC_except_table448
+ GCC_except_table452
+ GCC_except_table518
+ GCC_except_table520
+ GCC_except_table549
+ GCC_except_table583
+ GCC_except_table610
+ GCC_except_table621
+ GCC_except_table650
+ GCC_except_table706
+ _OBJC_CLASS_$_PKTransactionAuthenticationPasscodeViewControllerAccessibility
+ _OBJC_CLASS_$___PKTransactionAuthenticationPasscodeViewControllerAccessibility_super
+ _OBJC_METACLASS_$_PKTransactionAuthenticationPasscodeViewControllerAccessibility
+ _OBJC_METACLASS_$___PKTransactionAuthenticationPasscodeViewControllerAccessibility_super
+ _UIAccessibilityFocusedElement
+ _UIAccessibilityIsVoiceOverRunning
+ _UIAccessibilityNotificationVoiceOverIdentifier
+ __OBJC_$_CLASS_METHODS_PKTransactionAuthenticationPasscodeViewControllerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_PKTransactionAuthenticationPasscodeViewControllerAccessibility
+ __OBJC_CLASS_RO_$_PKTransactionAuthenticationPasscodeViewControllerAccessibility
+ __OBJC_CLASS_RO_$___PKTransactionAuthenticationPasscodeViewControllerAccessibility_super
+ __OBJC_METACLASS_RO_$_PKTransactionAuthenticationPasscodeViewControllerAccessibility
+ __OBJC_METACLASS_RO_$___PKTransactionAuthenticationPasscodeViewControllerAccessibility_super
- GCC_except_table257
- GCC_except_table289
- GCC_except_table310
- GCC_except_table336
- GCC_except_table356
- GCC_except_table440
- GCC_except_table443
- GCC_except_table447
- GCC_except_table513
- GCC_except_table515
- GCC_except_table544
- GCC_except_table578
- GCC_except_table600
- GCC_except_table616
- GCC_except_table645
- GCC_except_table701
CStrings:
+ "PKTransactionAuthenticationPasscodeViewController"
+ "PKTransactionAuthenticationPasscodeViewControllerAccessibility"
+ "_AXPayStackTriggerElementKey"
+ "view"
```
