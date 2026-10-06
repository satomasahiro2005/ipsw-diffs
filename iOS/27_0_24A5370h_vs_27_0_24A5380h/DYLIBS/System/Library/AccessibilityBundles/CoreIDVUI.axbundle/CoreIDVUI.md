## CoreIDVUI

> `/System/Library/AccessibilityBundles/CoreIDVUI.axbundle/CoreIDVUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x678` | `0x2ac` | **`-0x3cc`** |
| `__AUTH_CONST.__objc_const` | `0x510` | `0x2d0` | **`-0x240`** |
| `__DATA_DIRTY.__objc_data` | `0x2d0` | `0x190` | **`-0x140`** |
| `__AUTH_CONST.__cfstring` | `0x220` | `0x140` | **`-0xe0`** |
| `__TEXT.__cstring` | `0x1f6` | `0x119` | **`-0xdd`** |
| `__TEXT.__objc_methlist` | `0x154` | `0xa4` | **`-0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0xe0` | `0x80` | **`-0x60`** |
| `__DATA_CONST.__got` | `0x68` | `0x28` | **`-0x40`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x28` | **`-0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x18` | `—` | **`-0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x8` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x90` | `0x80` | **`-0x10`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 24
-  Symbols:   113
-  CStrings:  21
+  Functions: 13
+  Symbols:   68
+  CStrings:  12
Symbols:
- +[IDScanConfirmationViewControllerAccessibility _accessibilityPerformValidations:]
- +[IDScanConfirmationViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[IDScanConfirmationViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[IdentityProofingViewControllerAccessibility _accessibilityPerformValidations:]
- +[IdentityProofingViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[IdentityProofingViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[IDScanConfirmationViewControllerAccessibility _accessibilityLoadAccessibilityInformation]
- -[IDScanConfirmationViewControllerAccessibility viewDidLoad]
- -[IdentityProofingViewControllerAccessibility _accessibilityLoadAccessibilityInformation]
- -[IdentityProofingViewControllerAccessibility viewDidAppear:]
- -[IdentityProofingViewControllerAccessibility viewDidLoad]
- _OBJC_CLASS_$_IDScanConfirmationViewControllerAccessibility
- _OBJC_CLASS_$_IdentityProofingViewControllerAccessibility
- _OBJC_CLASS_$_NSAttributedString
- _OBJC_CLASS_$_NSConstantIntegerNumber
- _OBJC_CLASS_$_NSDictionary
- _OBJC_CLASS_$___IDScanConfirmationViewControllerAccessibility_super
- _OBJC_CLASS_$___IdentityProofingViewControllerAccessibility_super
- _OBJC_METACLASS_$_IDScanConfirmationViewControllerAccessibility
- _OBJC_METACLASS_$_IdentityProofingViewControllerAccessibility
- _OBJC_METACLASS_$___IDScanConfirmationViewControllerAccessibility_super
- _OBJC_METACLASS_$___IdentityProofingViewControllerAccessibility_super
- _UIAccessibilityAnnouncementNotification
- _UIAccessibilityPriorityHigh
- _UIAccessibilitySpeechAttributeAnnouncementPriority
- _UIAccessibilityTraitHeader
- _UIAccessibilityTraitImage
- __OBJC_$_CLASS_METHODS_IDScanConfirmationViewControllerAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_IdentityProofingViewControllerAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_IDScanConfirmationViewControllerAccessibility
- __OBJC_$_INSTANCE_METHODS_IdentityProofingViewControllerAccessibility
- __OBJC_CLASS_RO_$_IDScanConfirmationViewControllerAccessibility
- __OBJC_CLASS_RO_$_IdentityProofingViewControllerAccessibility
- __OBJC_CLASS_RO_$___IDScanConfirmationViewControllerAccessibility_super
- __OBJC_CLASS_RO_$___IdentityProofingViewControllerAccessibility_super
- __OBJC_METACLASS_RO_$_IDScanConfirmationViewControllerAccessibility
- __OBJC_METACLASS_RO_$_IdentityProofingViewControllerAccessibility
- __OBJC_METACLASS_RO_$___IDScanConfirmationViewControllerAccessibility_super
- __OBJC_METACLASS_RO_$___IdentityProofingViewControllerAccessibility_super
- ___stack_chk_fail
- ___stack_chk_guard
- _objc_alloc
- _objc_release_x20
- _objc_release_x21
- _objc_retain_x2
CStrings:
- "@"
- "CoreIDVUI.IDScanConfirmationViewController"
- "CoreIDVUI.IdentityProofingViewController"
- "I"
- "IDScanConfirmationViewControllerAccessibility"
- "IdentityProofingViewControllerAccessibility"
- "id.card.scanned.photo"
- "imageView"
- "titleLabel"
```
