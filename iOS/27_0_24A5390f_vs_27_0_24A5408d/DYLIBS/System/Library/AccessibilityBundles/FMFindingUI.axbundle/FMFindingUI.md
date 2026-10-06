## FMFindingUI

> `/System/Library/AccessibilityBundles/FMFindingUI.axbundle/FMFindingUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfa8` | `0x15e0` | **`+0x638`** |
| `__AUTH_CONST.__objc_const` | `0x3f0` | `0x630` | **`+0x240`** |
| `__AUTH.__objc_data` | `—` | `0x140` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x190` | `0x290` | **`+0x100`** |
| `__TEXT.__cstring` | `0x315` | `0x405` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x3c0` | `0x480` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f8` | `0x220` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x58` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xd8` | `0xf8` | **`+0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA.__data` | `0x8` | `—` | **`-0x8`** |
| `__DATA.__bss` | `0xa` | `0xe` | **`+0x4`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 34
-  Symbols:   141
-  CStrings:  38
+  Functions: 52
+  Symbols:   181
+  CStrings:  44
Symbols:
+ +[FMFindingSystemComponentsViewControllerAccessibility _accessibilityPerformValidations:]
+ +[FMFindingSystemComponentsViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[FMFindingSystemComponentsViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[PrecisionVFXViewControllerAccessibility _accessibilityPerformValidations:]
+ +[PrecisionVFXViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PrecisionVFXViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[FMFindingSystemComponentsViewControllerAccessibility _axPreviousDistance]
+ -[FMFindingSystemComponentsViewControllerAccessibility _axSetPreviousDistance:]
+ -[FMFindingSystemComponentsViewControllerAccessibility accessibilityDidUpdateWithTopLabelMessage:instruction:]
+ -[FMFindingSystemComponentsViewControllerAccessibility accessibilityDistanceAndDirectionUpdated]
+ -[FMFindingViewControllerAccessibility _axPreviousDistance]
+ -[FMFindingViewControllerAccessibility _axSetPreviousDistance:]
+ -[PrecisionVFXViewControllerAccessibility _axPreviousDistance]
+ -[PrecisionVFXViewControllerAccessibility _axPreviousInstruction]
+ -[PrecisionVFXViewControllerAccessibility _axSetPreviousDistance:]
+ -[PrecisionVFXViewControllerAccessibility _axSetPreviousInstruction:]
+ -[PrecisionVFXViewControllerAccessibility accessibilityDidUpdateWithTopLabelMessage:instruction:]
+ -[PrecisionVFXViewControllerAccessibility accessibilityDistanceAndDirectionUpdated]
+ _OBJC_CLASS_$_FMFindingSystemComponentsViewControllerAccessibility
+ _OBJC_CLASS_$_PrecisionVFXViewControllerAccessibility
+ _OBJC_CLASS_$___FMFindingSystemComponentsViewControllerAccessibility_super
+ _OBJC_CLASS_$___PrecisionVFXViewControllerAccessibility_super
+ _OBJC_METACLASS_$_FMFindingSystemComponentsViewControllerAccessibility
+ _OBJC_METACLASS_$_PrecisionVFXViewControllerAccessibility
+ _OBJC_METACLASS_$___FMFindingSystemComponentsViewControllerAccessibility_super
+ _OBJC_METACLASS_$___PrecisionVFXViewControllerAccessibility_super
+ __OBJC_$_CLASS_METHODS_FMFindingSystemComponentsViewControllerAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS_PrecisionVFXViewControllerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_FMFindingSystemComponentsViewControllerAccessibility
+ __OBJC_$_INSTANCE_METHODS_PrecisionVFXViewControllerAccessibility
+ __OBJC_CLASS_RO_$_FMFindingSystemComponentsViewControllerAccessibility
+ __OBJC_CLASS_RO_$_PrecisionVFXViewControllerAccessibility
+ __OBJC_CLASS_RO_$___FMFindingSystemComponentsViewControllerAccessibility_super
+ __OBJC_CLASS_RO_$___PrecisionVFXViewControllerAccessibility_super
+ __OBJC_METACLASS_RO_$_FMFindingSystemComponentsViewControllerAccessibility
+ __OBJC_METACLASS_RO_$_PrecisionVFXViewControllerAccessibility
+ __OBJC_METACLASS_RO_$___FMFindingSystemComponentsViewControllerAccessibility_super
+ __OBJC_METACLASS_RO_$___PrecisionVFXViewControllerAccessibility_super
+ ___FMFindingSystemComponentsViewControllerAccessibility___axPreviousDistance
+ ___FMFindingViewControllerAccessibility___axPreviousDistance
+ ___PrecisionVFXViewControllerAccessibility___axPreviousDistance
+ ___PrecisionVFXViewControllerAccessibility___axPreviousInstruction
+ _objc_retain_x20
- _accessibilityDistanceAndDirectionUpdated.previousDistance
- _objc_retain_x3
- _objc_storeStrong
CStrings:
+ "FMFindingSystemComponentsViewControllerAccessibility"
+ "FMFindingUI.FMFindingSystemComponentsViewController"
+ "FMFindingUI.PrecisionVFXViewController"
+ "PrecisionVFXViewControllerAccessibility"
+ "accessibilityFormattedDistance"
+ "accessibilityInstruction"
```
