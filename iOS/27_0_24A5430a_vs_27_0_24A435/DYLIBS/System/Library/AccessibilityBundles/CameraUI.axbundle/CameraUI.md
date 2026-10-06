## CameraUI

> `/System/Library/AccessibilityBundles/CameraUI.axbundle/CameraUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18c40` | `0x19888` | **`+0xc48`** |
| `__AUTH_CONST.__cfstring` | `0x46a0` | `0x48e0` | **`+0x240`** |
| `__TEXT.__cstring` | `0x3542` | `0x370d` | **`+0x1cb`** |
| `__AUTH_CONST.__const` | `0x580` | `0x640` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x384` | `0x410` | **`+0x8c`** |
| `__DATA_CONST.__const` | `0xa98` | `0xb00` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x1598` | `0x15f0` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x2744` | `0x279c` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x928` | `0x980` | **`+0x58`** |
| `__TEXT.__const` | `0x160` | `0x170` | **`+0x10`** |
| `__DATA.__bss` | `0x41` | `0x49` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 836
-  Symbols:   1865
-  CStrings:  624
+  Functions: 858
+  Symbols:   1893
+  CStrings:  642
Symbols:
+ -[CAMDynamicShutterControlAccessibility _autoCaptureAccessibilityFrame]
+ -[CAMDynamicShutterControlAccessibility _autoCaptureAccessibilityPath]
+ -[CAMDynamicShutterControlAccessibility _axElementForAutoCaptureButton]
+ -[CAMDynamicShutterControlAccessibility _axElementForLeftCaptureButton]
+ -[CAMDynamicShutterControlAccessibility _leftCaptureAccessibilityFrame]
+ -[CAMDynamicShutterControlAccessibility _leftCaptureAccessibilityPath]
+ -[CAMZoomControlAccessibility _axIsSuppressedForPersonalPhotographerSession]
+ GCC_except_table154
+ GCC_except_table157
+ GCC_except_table159
+ GCC_except_table161
+ GCC_except_table168
+ GCC_except_table173
+ GCC_except_table340
+ GCC_except_table369
+ GCC_except_table395
+ GCC_except_table487
+ GCC_except_table501
+ GCC_except_table506
+ GCC_except_table516
+ GCC_except_table519
+ GCC_except_table524
+ GCC_except_table530
+ GCC_except_table536
+ GCC_except_table549
+ GCC_except_table579
+ GCC_except_table591
+ GCC_except_table604
+ GCC_except_table637
+ GCC_except_table683
+ GCC_except_table697
+ GCC_except_table781
+ ___71-[CAMDynamicShutterControlAccessibility _axElementForAutoCaptureButton]_block_invoke
+ ___71-[CAMDynamicShutterControlAccessibility _axElementForAutoCaptureButton]_block_invoke_2
+ ___71-[CAMDynamicShutterControlAccessibility _axElementForAutoCaptureButton]_block_invoke_3
+ ___71-[CAMDynamicShutterControlAccessibility _axElementForAutoCaptureButton]_block_invoke_4
+ ___71-[CAMDynamicShutterControlAccessibility _axElementForAutoCaptureButton]_block_invoke_5
+ ___71-[CAMDynamicShutterControlAccessibility _axElementForAutoCaptureButton]_block_invoke_6
+ ___71-[CAMDynamicShutterControlAccessibility _axElementForAutoCaptureButton]_block_invoke_7
+ ___71-[CAMDynamicShutterControlAccessibility _axElementForLeftCaptureButton]_block_invoke
+ ___71-[CAMDynamicShutterControlAccessibility _axElementForLeftCaptureButton]_block_invoke_2
+ ___71-[CAMDynamicShutterControlAccessibility _axElementForLeftCaptureButton]_block_invoke_3
+ ___71-[CAMDynamicShutterControlAccessibility _axElementForLeftCaptureButton]_block_invoke_4
+ ___71-[CAMDynamicShutterControlAccessibility _axElementForLeftCaptureButton]_block_invoke_5
+ ___71-[CAMDynamicShutterControlAccessibility _axElementForLeftCaptureButton]_block_invoke_6
+ ___71-[CAMDynamicShutterControlAccessibility _axElementForLeftCaptureButton]_block_invoke_7
+ ___block_descriptor_40_e8_32w_e5_B8?0lw32l8
+ _accessibilityCameraUIRavePopLocalizedString
+ _accessibilityCameraUIRavePopLocalizedString.axBundle
- GCC_except_table153
- GCC_except_table156
- GCC_except_table158
- GCC_except_table160
- GCC_except_table167
- GCC_except_table172
- GCC_except_table339
- GCC_except_table368
- GCC_except_table394
- GCC_except_table483
- GCC_except_table500
- GCC_except_table503
- GCC_except_table515
- GCC_except_table528
- GCC_except_table558
- GCC_except_table570
- GCC_except_table583
- GCC_except_table616
- GCC_except_table662
- GCC_except_table676
- GCC_except_table760
CStrings:
+ "AutoCaptureButton"
+ "CameraUIStrings-V68"
+ "ManualCaptureButton"
+ "ProvenanceCapture"
+ "TimeWarpCapture"
+ "TimelapseClassicCapture"
+ "_autoCaptureButtonCenter"
+ "_autoCaptureButtonOuterView"
+ "_leftCaptureButtonCenter"
+ "_leftCaptureButtonOuterView"
+ "_personalPhotographerSessionActive"
+ "auto.capture.button"
+ "auto.capture.stop.button"
+ "beginAutoCaptureSessionAnimated:"
+ "delegate"
+ "dynamicShutterControlDidPressAutoCaptureButton:"
+ "dynamicShutterControlDidPressLeftCaptureButton:"
+ "showingAutoCapture"
```
