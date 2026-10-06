## HomeUI

> `/System/Library/AccessibilityBundles/HomeUI.axbundle/HomeUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x134e0` | `0x13838` | **`+0x358`** |
| `__AUTH_CONST.__objc_const` | `0x76f0` | `0x7810` | **`+0x120`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x56a0` | `0x5700` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x2828` | `0x2878` | **`+0x50`** |
| `__TEXT.__cstring` | `0x44b6` | `0x44fe` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0xaf0` | `0xb08` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x2d8` | `0x2e8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x698` | `0x6a8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x858` | `0x868` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x220` | `0x228` | **`+0x8`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  Functions: 752
-  Symbols:   2040
-  CStrings:  733
+  Functions: 757
+  Symbols:   2057
+  CStrings:  736
Symbols:
+ +[HULiveMosaicCameraCellAccessibility _accessibilityPerformValidations:]
+ +[HULiveMosaicCameraCellAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[HULiveMosaicCameraCellAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[HULiveMosaicCameraCellAccessibility _axCameraName]
+ -[HULiveMosaicCameraCellAccessibility accessibilityLabel]
+ _OBJC_CLASS_$_HFCameraItem
+ _OBJC_CLASS_$_HMCameraProfile
+ _OBJC_CLASS_$_HULiveMosaicCameraCellAccessibility
+ _OBJC_CLASS_$___HULiveMosaicCameraCellAccessibility_super
+ _OBJC_METACLASS_$_HULiveMosaicCameraCellAccessibility
+ _OBJC_METACLASS_$___HULiveMosaicCameraCellAccessibility_super
+ __OBJC_$_CLASS_METHODS_HULiveMosaicCameraCellAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_HULiveMosaicCameraCellAccessibility
+ __OBJC_CLASS_RO_$_HULiveMosaicCameraCellAccessibility
+ __OBJC_CLASS_RO_$___HULiveMosaicCameraCellAccessibility_super
+ __OBJC_METACLASS_RO_$_HULiveMosaicCameraCellAccessibility
+ __OBJC_METACLASS_RO_$___HULiveMosaicCameraCellAccessibility_super
CStrings:
+ "HFCameraItem"
+ "HULiveMosaicCameraCell"
+ "HULiveMosaicCameraCellAccessibility"
```
