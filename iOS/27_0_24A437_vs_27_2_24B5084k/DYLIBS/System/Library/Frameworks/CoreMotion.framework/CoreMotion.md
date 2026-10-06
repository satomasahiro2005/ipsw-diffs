## CoreMotion

> `/System/Library/Frameworks/CoreMotion.framework/CoreMotion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ce334` | `0x3cf9f8` | **`+0x16c4`** |
| `__TEXT.__cstring` | `0x47503` | `0x477f3` | **`+0x2f0`** |
| `__AUTH_CONST.__objc_const` | `0x1db18` | `0x1dd88` | **`+0x270`** |
| `__AUTH_CONST.__cfstring` | `0x13c00` | `0x13d20` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0xd854` | `0xd964` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x2f686` | `0x2f779` | **`+0xf3`** |
| `__TEXT.__const` | `0xcc90` | `0xcd60` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x15810` | `0x158b8` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0xbc50` | `0xbce0` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0xd458` | `0xd4d0` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x56a0` | `0x56f8` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x4290` | `0x42e0` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x1798` | `0x17bc` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x818` | `0x828` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x3d60` | `0x3d68` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x8d8` | `0x8e0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x7c0` | `0x7c8` | **`+0x8`** |

### Other Changes

```diff

-3185.0.6.0.3
+3186.0.12.0.0

-  Functions: 12679
-  Symbols:   1811
-  CStrings:  11394
+  Functions: 12715
+  Symbols:   1815
+  CStrings:  11414
Symbols:
+ _CLCopyAuthorization
+ _OBJC_CLASS_$_CMVO2MaxClassificationThreshold
+ _OBJC_METACLASS_$_CMVO2MaxClassificationThreshold
+ _kTCCServiceMotionSensors
CStrings:
+ "#Spi, CLCopyAuthorization failed"
+ "%@,<biologicalSex %ld, ageLowerBound %ld, ageUpperBound %ld, thresholdType %ld, slope %f, intercept %f>"
+ "+[CMWakeGestureManager toPropertyC:]"
+ "-[CLLocationInternalClient_CoreMotion copyAuthorizationFromBundleID:toBundleID:]_block_invoke"
+ "22:28:36"
+ "Assertion failed: lambda2 != 0, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMOQuaternion.cpp, line 172,invalid weights."
+ "Assertion failed: t >= 0 && t <= 1, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMOQuaternion.cpp, line 320,Invalid time t for slerp."
+ "CL: CLCopyAuthorization"
+ "Invalid PropertyA input."
+ "ParameterK"
+ "PropertyA Ambiguous for PropertyB Ambiguous, ParameterD & ParameterE."
+ "Sep 10 2026"
+ "TempestDefaultLidAngleDeg"
+ "TempestForceDefaultLidAngle"
+ "[Gesture %{public}ld] Gesture%{public}s notification: %{public}d(%{public}@), Mode:%{public}@, Start:%{public}@, End:%{public}@, HostAwake, %{public}d, Inferred:%{public}u, IsSuppressionActive:%{public}d"
+ "[RelDMService][parseLidAngleDeg] checkedLidAngleDeg: %{public}.1f deg"
+ "distanceCalibratedPedometer"
+ "float CMRelDMService::parseLidAngleDeg(const float) const"
+ "inHandDoubleTapBaseDetectorReset"
+ "isSuppressionActive"
+ "kCMVO2MaxClassificationThresholdCodingKeyAgeLowerBound"
+ "kCMVO2MaxClassificationThresholdCodingKeyAgeUpperBound"
+ "kCMVO2MaxClassificationThresholdCodingKeyBiologicalSex"
+ "kCMVO2MaxClassificationThresholdCodingKeyIntercept"
+ "kCMVO2MaxClassificationThresholdCodingKeySlope"
+ "kCMVO2MaxClassificationThresholdCodingKeyThresholdType"
+ "pencilState"
+ "{\"msg%{public}.0s\":\"CLCopyAuthorization\", \"event\":%{public, location:escape_only}s}"
- "21:09:51"
- "Assertion failed: lambda2 != 0, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMOQuaternion.cpp, line 152,invalid weights."
- "Assertion failed: t >= 0 && t <= 1, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMOQuaternion.cpp, line 300,Invalid time t for slerp."
- "Aug 20 2026"
- "Invalid propertyA input."
- "PropertyA ambiguous for PropertyB Ambiguous, ParameterD & ParameterE."
- "[Gesture %{public}ld] Gesture%{public}s notification: %{public}d(%{public}@), Mode:%{public}@, Start:%{public}@, End:%{public}@, HostAwake, %{public}d, Inferred:%{public}u"
- "sharedManager_%@"
```
