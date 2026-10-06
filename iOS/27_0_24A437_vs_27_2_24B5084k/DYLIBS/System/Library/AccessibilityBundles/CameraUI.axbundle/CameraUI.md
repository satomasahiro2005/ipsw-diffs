## CameraUI

> `/System/Library/AccessibilityBundles/CameraUI.axbundle/CameraUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19888` | `0x19b84` | **`+0x2fc`** |
| `__AUTH_CONST.__objc_const` | `0x5430` | `0x5550` | **`+0x120`** |
| `__TEXT.__cstring` | `0x370d` | `0x37da` | **`+0xcd`** |
| `__AUTH_CONST.__cfstring` | `0x48e0` | `0x49a0` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x3c0` | `0x460` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x279c` | `0x2804` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x980` | `0x9a0` | **`+0x20`** |
| `__DATA.__bss` | `0x49` | `0x59` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x3d0` | `0x3e0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x15f0` | `0x15f8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x160` | `0x168` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x410` | `0x418` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 858
-  Symbols:   1893
-  CStrings:  642
+  Functions: 866
+  Symbols:   1915
+  CStrings:  648
Symbols:
+ +[CAMReplenishProVideoStorageInstructionLabelAccessibility _accessibilityPerformValidations:]
+ +[CAMReplenishProVideoStorageInstructionLabelAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[CAMReplenishProVideoStorageInstructionLabelAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[CAMDynamicShutterControlAccessibility _pepFeatureName]
+ -[CAMReplenishProVideoStorageInstructionLabelAccessibility accessibilityLabel]
+ -[CAMReplenishProVideoStorageInstructionLabelAccessibility accessibilityTraits]
+ -[CAMReplenishProVideoStorageInstructionLabelAccessibility isAccessibilityElement]
+ GCC_except_table160
+ GCC_except_table163
+ GCC_except_table165
+ GCC_except_table167
+ GCC_except_table174
+ GCC_except_table179
+ GCC_except_table346
+ GCC_except_table375
+ GCC_except_table401
+ GCC_except_table492
+ GCC_except_table493
+ GCC_except_table494
+ GCC_except_table495
+ GCC_except_table514
+ GCC_except_table517
+ GCC_except_table528
+ GCC_except_table532
+ GCC_except_table538
+ GCC_except_table544
+ GCC_except_table557
+ GCC_except_table587
+ GCC_except_table599
+ GCC_except_table612
+ GCC_except_table645
+ GCC_except_table691
+ GCC_except_table705
+ GCC_except_table789
+ _AXCFormattedString
+ _AXSystemRootDirectory
+ _OBJC_CLASS_$_CAMReplenishProVideoStorageInstructionLabelAccessibility
+ _OBJC_CLASS_$___CAMReplenishProVideoStorageInstructionLabelAccessibility_super
+ _OBJC_METACLASS_$_CAMReplenishProVideoStorageInstructionLabelAccessibility
+ _OBJC_METACLASS_$___CAMReplenishProVideoStorageInstructionLabelAccessibility_super
+ __OBJC_$_CLASS_METHODS_CAMReplenishProVideoStorageInstructionLabelAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_CAMReplenishProVideoStorageInstructionLabelAccessibility
+ __OBJC_CLASS_RO_$_CAMReplenishProVideoStorageInstructionLabelAccessibility
+ __OBJC_CLASS_RO_$___CAMReplenishProVideoStorageInstructionLabelAccessibility_super
+ __OBJC_METACLASS_RO_$_CAMReplenishProVideoStorageInstructionLabelAccessibility
+ __OBJC_METACLASS_RO_$___CAMReplenishProVideoStorageInstructionLabelAccessibility_super
+ ___56-[CAMDynamicShutterControlAccessibility _pepFeatureName]_block_invoke
+ __pepFeatureName.cameraUIBundle
+ __pepFeatureName.onceToken
- GCC_except_table154
- GCC_except_table157
- GCC_except_table159
- GCC_except_table161
- GCC_except_table168
- GCC_except_table173
- GCC_except_table340
- GCC_except_table369
- GCC_except_table395
- GCC_except_table484
- GCC_except_table485
- GCC_except_table486
- GCC_except_table487
- GCC_except_table501
- GCC_except_table506
- GCC_except_table516
- GCC_except_table519
- GCC_except_table530
- GCC_except_table536
- GCC_except_table549
- GCC_except_table579
- GCC_except_table591
- GCC_except_table604
- GCC_except_table637
- GCC_except_table683
- GCC_except_table697
- GCC_except_table781
CStrings:
+ "%@"
+ "CAMReplenishProVideoStorageInstructionLabel"
+ "CAMReplenishProVideoStorageInstructionLabelAccessibility"
+ "CameraUI-PEP"
+ "Chrome.PersonalPhotographer.axLabel"
+ "System/Library/PrivateFrameworks/CameraUI.framework"
```
