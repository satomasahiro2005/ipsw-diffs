## CoreIDVRGBLiveness

> `/System/Library/AccessibilityBundles/CoreIDVRGBLiveness.axbundle/CoreIDVRGBLiveness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ec` | `0xb4` | **`-0x138`** |
| `__AUTH_CONST.__objc_const` | `0x1b0` | `0x90` | **`-0x120`** |
| `__TEXT.__cstring` | `0xde` | `0x14` | **`-0xca`** |
| `__AUTH_CONST.__cfstring` | `0xe0` | `0x40` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0xf0` | `0x50` | **`-0xa0`** |
| `__AUTH_CONST.__const` | `0x80` | `—` | **`-0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x80` | `0x18` | **`-0x68`** |
| `__DATA_CONST.__const` | `0x60` | `—` | **`-0x60`** |
| `__TEXT.__objc_methlist` | `0x74` | `0x14` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0x78` | `0x60` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x20` | `0x10` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x18` | `0x8` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x8` | `—` | **`-0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 12
-  Symbols:   54
-  CStrings:  10
+  Functions: 2
+  Symbols:   21
+  CStrings:  2
Symbols:
- +[RGBLivenessCoachingViewAccessibility _accessibilityPerformValidations:]
- +[RGBLivenessCoachingViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[RGBLivenessCoachingViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[RGBLivenessCoachingViewAccessibility _accessibilityMediaAnalysisOptions]
- -[RGBLivenessCoachingViewAccessibility accessibilityLabel]
- -[RGBLivenessCoachingViewAccessibility isAccessibilityElement]
- _AXPerformValidationChecks
- _OBJC_CLASS_$_AXValidationManager
- _OBJC_CLASS_$_RGBLivenessCoachingViewAccessibility
- _OBJC_CLASS_$_UIAccessibilitySafeCategory
- _OBJC_CLASS_$___RGBLivenessCoachingViewAccessibility_super
- _OBJC_METACLASS_$_RGBLivenessCoachingViewAccessibility
- _OBJC_METACLASS_$_UIAccessibilitySafeCategory
- _OBJC_METACLASS_$___RGBLivenessCoachingViewAccessibility_super
- __NSConcreteGlobalBlock
- __OBJC_$_CLASS_METHODS_RGBLivenessCoachingViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_RGBLivenessCoachingViewAccessibility
- __OBJC_CLASS_RO_$_RGBLivenessCoachingViewAccessibility
- __OBJC_CLASS_RO_$___RGBLivenessCoachingViewAccessibility_super
- __OBJC_METACLASS_RO_$_RGBLivenessCoachingViewAccessibility
- __OBJC_METACLASS_RO_$___RGBLivenessCoachingViewAccessibility_super
- ___57+[AXCoreIDVRGBLivenessGlue accessibilityInitializeBundle]_block_invoke
- ___57+[AXCoreIDVRGBLivenessGlue accessibilityInitializeBundle]_block_invoke_2
- ___57+[AXCoreIDVRGBLivenessGlue accessibilityInitializeBundle]_block_invoke_3
- ___57+[AXCoreIDVRGBLivenessGlue accessibilityInitializeBundle]_block_invoke_4
- ___block_descriptor_32_e29_B16?0"AXValidationManager"8l
- ___block_descriptor_32_e29_v16?0"AXValidationManager"8l
- ___block_descriptor_32_e5_v8?0l
- ___block_literal_global
- _accessibilityInitializeBundle.onceToken
- _dispatch_once
- _objc_release
- _objc_retain_x1
CStrings:
- "B16@?0@\"AXValidationManager\"8"
- "CoreIDVRGBLiveness AX"
- "CoreIDVRGBLiveness.RGBLivenessCoachingView"
- "CoreIDVUI"
- "RGBLivenessCoachingViewAccessibility"
- "stylized.animation.role"
- "v16@?0@\"AXValidationManager\"8"
- "v8@?0"
```
