## batteryintelligenced

> `/usr/libexec/batteryintelligenced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41c70` | `0x42004` | **`+0x394`** |
| `__TEXT.__objc_methname` | `0x62e3` | `0x643c` | **`+0x159`** |
| `__TEXT.__oslogstring` | `0x7924` | `0x7a54` | **`+0x130`** |
| `__DATA_CONST.__got` | `0x2a8` | `0x338` | **`+0x90`** |
| `__DATA.__objc_const` | `0x79f0` | `0x7a50` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x1778` | `0x17a8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x314c` | `0x317c` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x4920` | `0x4940` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x330` | `0x338` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-215.0.0.0.0
+218.0.0.0.0

+  - /System/Library/PrivateFrameworks/MobileStoreDemoKit.framework/MobileStoreDemoKit

-  Functions: 1492
-  Symbols:   271
-  CStrings:  2426
+  Functions: 1499
+  Symbols:   272
+  CStrings:  2440
Symbols:
+ _OBJC_CLASS_$_MSDKDemoState
CStrings:
+ "Not a supported device for BatteryAnalysis (isDemoDevice=%d, isVirtualDevice=%d). Skipping manager setup."
+ "Rejected new connection from pid %d. Not a supported device for BatteryAnalysis."
+ "TB,N,V_isBatteryAnalysisSupportedDevice"
+ "TB,N,V_shouldRunBatteryAnalysisEstimator"
+ "_isBatteryAnalysisSupportedDevice"
+ "_shouldRunBatteryAnalysisEstimator"
+ "isBatteryAnalysisSupportedDevice"
+ "isDemoDevice: isDeviceEnrolledWithDeKOTA returned error: %@"
+ "isDemoDevice: isSecureDemoModeEnabled returned error: %@"
+ "isDeviceEnrolledWithDeKOTA:"
+ "isSecureDemoModeEnabled:"
+ "setIsBatteryAnalysisSupportedDevice:"
+ "setShouldRunBatteryAnalysisEstimator:"
+ "shouldRunBatteryAnalysisEstimator"
```
