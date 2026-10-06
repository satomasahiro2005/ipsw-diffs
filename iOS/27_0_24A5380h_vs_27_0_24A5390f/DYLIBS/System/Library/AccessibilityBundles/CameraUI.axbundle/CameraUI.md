## CameraUI

> `/System/Library/AccessibilityBundles/CameraUI.axbundle/CameraUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18344` | `0x18528` | **`+0x1e4`** |
| `__AUTH_CONST.__cfstring` | `0x4560` | `0x45a0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3443` | `0x3474` | **`+0x31`** |
| `__TEXT.__objc_methlist` | `0x267c` | `0x26a4` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1518` | `0x1530` | **`+0x18`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 818
-  Symbols:   1830
-  CStrings:  614
+  Functions: 822
+  Symbols:   1837
+  CStrings:  616
Symbols:
+ -[CAMCaptureEngineAccessibility _accessibilityHasActiveRecording]
+ -[CAMFullscreenViewfinderAccessibility axLastSuggestionButton]
+ -[CAMFullscreenViewfinderAccessibility setAxLastSuggestionButton:]
+ GCC_except_table476
+ GCC_except_table490
+ GCC_except_table493
+ GCC_except_table499
+ GCC_except_table505
+ GCC_except_table518
+ GCC_except_table548
+ GCC_except_table560
+ GCC_except_table573
+ GCC_except_table606
+ GCC_except_table652
+ GCC_except_table666
+ GCC_except_table749
+ ___54-[CAMMotionControllerAccessibility _axDoMotionUpdate:]_block_invoke
+ ___CAMFullscreenViewfinderAccessibility__axLastSuggestionButton
+ ___UIAccessibilityGetAssociatedLong
+ ___UIAccessibilitySetAssociatedLong
- GCC_except_table472
- GCC_except_table489
- GCC_except_table492
- GCC_except_table498
- GCC_except_table504
- GCC_except_table517
- GCC_except_table547
- GCC_except_table559
- GCC_except_table572
- GCC_except_table605
- GCC_except_table649
- GCC_except_table662
- GCC_except_table745
CStrings:
+ "__captureController"
+ "isCapturingPanorama"
+ "isCapturingTimelapse"
- "viewDidLoad"
```
