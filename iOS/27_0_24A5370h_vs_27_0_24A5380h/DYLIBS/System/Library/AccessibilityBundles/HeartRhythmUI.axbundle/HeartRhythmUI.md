## HeartRhythmUI

> `/System/Library/AccessibilityBundles/HeartRhythmUI.axbundle/HeartRhythmUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1664` | `0xfb0` | **`-0x6b4`** |
| `__AUTH_CONST.__objc_const` | `0x1050` | `0xab0` | **`-0x5a0`** |
| `__DATA_DIRTY.__objc_data` | `0x910` | `0x5f0` | **`-0x320`** |
| `__TEXT.__cstring` | `0x74e` | `0x555` | **`-0x1f9`** |
| `__TEXT.__objc_methlist` | `0x46c` | `0x2fc` | **`-0x170`** |
| `__AUTH_CONST.__cfstring` | `0x640` | `0x4e0` | **`-0x160`** |
| `__DATA_CONST.__objc_classlist` | `0xe8` | `0x98` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x128` | `0xe8` | **`-0x40`** |
| `__DATA_CONST.__objc_superrefs` | `0x60` | `0x38` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x138` | `0x128` | **`-0x10`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 76
-  Symbols:   277
-  CStrings:  59
+  Functions: 55
+  Symbols:   206
+  CStrings:  48
Symbols:
+ GCC_except_table38
- +[HRAtrialFibrillationIntroViewControllerAccessibility _accessibilityPerformValidations:]
- +[HRAtrialFibrillationIntroViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[HRAtrialFibrillationIntroViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[HROnboardingAtrialFibrillationEnableViewControllerAccessibility _accessibilityPerformValidations:]
- +[HROnboardingAtrialFibrillationEnableViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[HROnboardingAtrialFibrillationEnableViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility _accessibilityPerformValidations:]
- +[HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[HROnboardingHeroExplanationViewControllerAccessibility _accessibilityPerformValidations:]
- +[HROnboardingHeroExplanationViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[HROnboardingHeroExplanationViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[HRSpeedBumpViewControllerAccessibility _accessibilityPerformValidations:]
- +[HRSpeedBumpViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[HRSpeedBumpViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[HRAtrialFibrillationIntroViewControllerAccessibility _accessibilityLoadAccessibilityInformation]
- -[HRAtrialFibrillationIntroViewControllerAccessibility setUpUI]
- -[HROnboardingAtrialFibrillationEnableViewControllerAccessibility _accessibilityLoadAccessibilityInformation]
- -[HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility _accessibilityLoadAccessibilityInformation]
- -[HROnboardingHeroExplanationViewControllerAccessibility _accessibilityLoadAccessibilityInformation]
- -[HRSpeedBumpViewControllerAccessibility _accessibilityLoadAccessibilityInformation]
- GCC_except_table55
- _OBJC_CLASS_$_HRAtrialFibrillationIntroViewControllerAccessibility
- _OBJC_CLASS_$_HROnboardingAtrialFibrillationEnableViewControllerAccessibility
- _OBJC_CLASS_$_HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility
- _OBJC_CLASS_$_HROnboardingHeroExplanationViewControllerAccessibility
- _OBJC_CLASS_$_HRSpeedBumpViewControllerAccessibility
- _OBJC_CLASS_$___HRAtrialFibrillationIntroViewControllerAccessibility_super
- _OBJC_CLASS_$___HROnboardingAtrialFibrillationEnableViewControllerAccessibility_super
- _OBJC_CLASS_$___HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility_super
- _OBJC_CLASS_$___HROnboardingHeroExplanationViewControllerAccessibility_super
- _OBJC_CLASS_$___HRSpeedBumpViewControllerAccessibility_super
- _OBJC_METACLASS_$_HRAtrialFibrillationIntroViewControllerAccessibility
- _OBJC_METACLASS_$_HROnboardingAtrialFibrillationEnableViewControllerAccessibility
- _OBJC_METACLASS_$_HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility
- _OBJC_METACLASS_$_HROnboardingHeroExplanationViewControllerAccessibility
- _OBJC_METACLASS_$_HRSpeedBumpViewControllerAccessibility
- _OBJC_METACLASS_$___HRAtrialFibrillationIntroViewControllerAccessibility_super
- _OBJC_METACLASS_$___HROnboardingAtrialFibrillationEnableViewControllerAccessibility_super
- _OBJC_METACLASS_$___HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility_super
- _OBJC_METACLASS_$___HROnboardingHeroExplanationViewControllerAccessibility_super
- _OBJC_METACLASS_$___HRSpeedBumpViewControllerAccessibility_super
- __OBJC_$_CLASS_METHODS_HRAtrialFibrillationIntroViewControllerAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_HROnboardingAtrialFibrillationEnableViewControllerAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_HROnboardingHeroExplanationViewControllerAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_HRSpeedBumpViewControllerAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_HRAtrialFibrillationIntroViewControllerAccessibility
- __OBJC_$_INSTANCE_METHODS_HROnboardingAtrialFibrillationEnableViewControllerAccessibility
- __OBJC_$_INSTANCE_METHODS_HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility
- __OBJC_$_INSTANCE_METHODS_HROnboardingHeroExplanationViewControllerAccessibility
- __OBJC_$_INSTANCE_METHODS_HRSpeedBumpViewControllerAccessibility
- __OBJC_CLASS_RO_$_HRAtrialFibrillationIntroViewControllerAccessibility
- __OBJC_CLASS_RO_$_HROnboardingAtrialFibrillationEnableViewControllerAccessibility
- __OBJC_CLASS_RO_$_HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility
- __OBJC_CLASS_RO_$_HROnboardingHeroExplanationViewControllerAccessibility
- __OBJC_CLASS_RO_$_HRSpeedBumpViewControllerAccessibility
- __OBJC_CLASS_RO_$___HRAtrialFibrillationIntroViewControllerAccessibility_super
- __OBJC_CLASS_RO_$___HROnboardingAtrialFibrillationEnableViewControllerAccessibility_super
- __OBJC_CLASS_RO_$___HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility_super
- __OBJC_CLASS_RO_$___HROnboardingHeroExplanationViewControllerAccessibility_super
- __OBJC_CLASS_RO_$___HRSpeedBumpViewControllerAccessibility_super
- __OBJC_METACLASS_RO_$_HRAtrialFibrillationIntroViewControllerAccessibility
- __OBJC_METACLASS_RO_$_HROnboardingAtrialFibrillationEnableViewControllerAccessibility
- __OBJC_METACLASS_RO_$_HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility
- __OBJC_METACLASS_RO_$_HROnboardingHeroExplanationViewControllerAccessibility
- __OBJC_METACLASS_RO_$_HRSpeedBumpViewControllerAccessibility
- __OBJC_METACLASS_RO_$___HRAtrialFibrillationIntroViewControllerAccessibility_super
- __OBJC_METACLASS_RO_$___HROnboardingAtrialFibrillationEnableViewControllerAccessibility_super
- __OBJC_METACLASS_RO_$___HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility_super
- __OBJC_METACLASS_RO_$___HROnboardingHeroExplanationViewControllerAccessibility_super
- __OBJC_METACLASS_RO_$___HRSpeedBumpViewControllerAccessibility_super
CStrings:
- "HRAtrialFibrillationIntroViewController"
- "HRAtrialFibrillationIntroViewControllerAccessibility"
- "HROnboardingAtrialFibrillationEnableViewController"
- "HROnboardingAtrialFibrillationEnableViewControllerAccessibility"
- "HROnboardingElectrocardiogramTakeRecordingViewController"
- "HROnboardingElectrocardiogramTakeRecordingViewControllerAccessibility"
- "HROnboardingHeroExplanationViewController"
- "HROnboardingHeroExplanationViewControllerAccessibility"
- "HRSpeedBumpViewController"
- "HRSpeedBumpViewControllerAccessibility"
- "setUpUI"
```
