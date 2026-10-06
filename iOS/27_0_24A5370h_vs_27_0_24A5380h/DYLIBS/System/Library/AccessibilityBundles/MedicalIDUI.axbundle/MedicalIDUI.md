## MedicalIDUI

> `/System/Library/AccessibilityBundles/MedicalIDUI.axbundle/MedicalIDUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x1b0` | `0x90` | **`-0x120`** |
| `__AUTH.__objc_data` | `0xf0` | `—` | **`-0xf0`** |
| `__TEXT.__text` | `0x288` | `0x1b0` | **`-0xd8`** |
| `__TEXT.__objc_methlist` | `0x80` | `0x14` | **`-0x6c`** |
| `__AUTH_CONST.__cfstring` | `0xe0` | `0x80` | **`-0x60`** |
| `__TEXT.__cstring` | `0xbc` | `0x66` | **`-0x56`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x90` | `0x48` | **`-0x48`** |
| `__DATA_CONST.__got` | `0x30` | `0x18` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x18` | `0x8` | **`-0x10`** |
| `__DATA.__bss` | `0x10` | `0x8` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x8` | `—` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x78` | `0x70` | **`-0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 12
-  Symbols:   58
-  CStrings:  9
+  Functions: 5
+  Symbols:   34
+  CStrings:  6
Symbols:
- +[MIUIMedicalIDNavigationBarViewAccessibility _accessibilityPerformValidations:]
- +[MIUIMedicalIDNavigationBarViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[MIUIMedicalIDNavigationBarViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[MIUIMedicalIDNavigationBarViewAccessibility _accessibilityLoadAccessibilityInformation]
- -[MIUIMedicalIDNavigationBarViewAccessibility accessibilityLabel]
- -[MIUIMedicalIDNavigationBarViewAccessibility accessibilityTraits]
- -[MIUIMedicalIDNavigationBarViewAccessibility isAccessibilityElement]
- _OBJC_CLASS_$_MIUIMedicalIDNavigationBarViewAccessibility
- _OBJC_CLASS_$_UIAccessibilitySafeCategory
- _OBJC_CLASS_$_UIView
- _OBJC_CLASS_$___MIUIMedicalIDNavigationBarViewAccessibility_super
- _OBJC_METACLASS_$_MIUIMedicalIDNavigationBarViewAccessibility
- _OBJC_METACLASS_$_UIAccessibilitySafeCategory
- _OBJC_METACLASS_$___MIUIMedicalIDNavigationBarViewAccessibility_super
- _UIAccessibilityTraitHeader
- __OBJC_$_CLASS_METHODS_MIUIMedicalIDNavigationBarViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_MIUIMedicalIDNavigationBarViewAccessibility
- __OBJC_CLASS_RO_$_MIUIMedicalIDNavigationBarViewAccessibility
- __OBJC_CLASS_RO_$___MIUIMedicalIDNavigationBarViewAccessibility_super
- __OBJC_METACLASS_RO_$_MIUIMedicalIDNavigationBarViewAccessibility
- __OBJC_METACLASS_RO_$___MIUIMedicalIDNavigationBarViewAccessibility_super
- ___UIAccessibilityCastAsClass
- _abort
- _objc_msgSendSuper2
Functions:
~ ___50+[AXMedicalIDUIGlue accessibilityInitializeBundle]_block_invoke_3 : 20 -> 4
CStrings:
- "MIUIMedicalIDNavigationBarView"
- "MIUIMedicalIDNavigationBarViewAccessibility"
- "medical.id"
```
