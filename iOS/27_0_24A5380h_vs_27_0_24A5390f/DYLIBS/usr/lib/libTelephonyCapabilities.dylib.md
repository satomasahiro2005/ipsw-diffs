## libTelephonyCapabilities.dylib

> `/usr/lib/libTelephonyCapabilities.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53694` | `0x53f64` | **`+0x8d0`** |
| `__TEXT.__gcc_except_tab` | `0x89b0` | `0x8ac0` | **`+0x110`** |
| `__TEXT.__cstring` | `0x49e6` | `0x4a54` | **`+0x6e`** |
| `__TEXT.__unwind_info` | `0x3d28` | `0x3d78` | **`+0x50`** |
| `__DATA_DIRTY.__bss` | `0x1868` | `0x18b0` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x11b8` | `0x11d0` | **`+0x18`** |
| `__TEXT.__const` | `0x3ec4` | `0x3ed4` | **`+0x10`** |

### Other Changes

```diff

-6562.0.0.0.0
+6565.0.0.0.0

-  Functions: 1870
-  Symbols:   3043
-  CStrings:  711
+  Functions: 1879
+  Symbols:   3059
+  CStrings:  714
Symbols:
+ GCC_except_table314
+ GCC_except_table317
+ GCC_except_table356
+ GCC_except_table359
+ GCC_except_table368
+ GCC_except_table380
+ GCC_except_table392
+ GCC_except_table401
+ GCC_except_table410
+ GCC_except_table666
+ GCC_except_table667
+ __ZN12capabilities2ct25supportsBacklightServicesEv
+ __ZN12capabilities2ct29kKeySupportsBacklightServicesE
+ __ZN12capabilities2ct35supportsBacklightServicesForProductE16TelephonyProduct
+ __ZN12capabilities2ctL26sSupportsBacklightServicesE16TelephonyProduct
+ __ZN12capabilities3abs34thresholdFaceDetectionDistanceCam1Ev
+ __ZN12capabilities3abs34thresholdFaceDetectionDistanceCam2Ev
+ __ZN12capabilities3abs38kKeyThresholdFaceDetectionDistanceCam1E
+ __ZN12capabilities3abs38kKeyThresholdFaceDetectionDistanceCam2E
+ __ZN12capabilities3abs44thresholdFaceDetectionDistanceCam1ForProductE16TelephonyProduct
+ __ZN12capabilities3abs44thresholdFaceDetectionDistanceCam2ForProductE16TelephonyProduct
+ __ZN12capabilities3absL35sThresholdFaceDetectionDistanceCam1E16TelephonyProduct
+ __ZN12capabilities3absL35sThresholdFaceDetectionDistanceCam2E16TelephonyProduct
- GCC_except_table350
- GCC_except_table353
- GCC_except_table362
- GCC_except_table374
- GCC_except_table386
- GCC_except_table395
- GCC_except_table404
CStrings:
+ "abs::thresholdFaceDetectionDistanceCam1"
+ "abs::thresholdFaceDetectionDistanceCam2"
+ "ct::supportsBacklightServices"
```
