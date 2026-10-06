## MetricKit

> `/System/Library/Frameworks/MetricKit.framework/MetricKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7cf4c` | `0x7c148` | **`-0xe04`** |
| `__DATA.__bss` | `0x12a50` | `0x12720` | **`-0x330`** |
| `__TEXT.__const` | `0x8f06` | `0x8d76` | **`-0x190`** |
| `__AUTH_CONST.__const` | `0x4779` | `0x4681` | **`-0xf8`** |
| `__AUTH_CONST.__objc_const` | `0x6718` | `0x67f0` | **`+0xd8`** |
| `__AUTH.__objc_data` | `0xd8` | `0x188` | **`+0xb0`** |
| `__DATA_DIRTY.__data` | `0x1328` | `0x1298` | **`-0x90`** |
| `__TEXT.__eh_frame` | `0x2838` | `0x27b8` | **`-0x80`** |
| `__TEXT.__objc_methlist` | `0x2894` | `0x290c` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x1c88` | `0x1c30` | **`-0x58`** |
| `__AUTH_CONST.__cfstring` | `0x1b60` | `0x1ba0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x108` | `0x148` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x18b4` | `0x1884` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x23c0` | `0x2390` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x11b1` | `0x1183` | **`-0x2e`** |
| `__AUTH.__data` | `0x198` | `0x1c0` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x145c` | `0x143c` | **`-0x20`** |
| `__TEXT.__swift5_assocty` | `0x4c8` | `0x4b0` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x8dc` | `0x8c4` | **`-0x18`** |
| `__DATA.__data` | `0x11d0` | `0x11c0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x490` | `0x480` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x3a0` | `0x390` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x430` | `0x43c` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x9e8` | `0x9f0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1228` | `0x1220` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x21c` | `0x218` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-361.0.0.0.0
+367.0.0.0.0

-  Functions: 3325
-  Symbols:   2431
-  CStrings:  352
+  Functions: 3311
+  Symbols:   2438
+  CStrings:  354
Symbols:
+ +[MXCrashDiagnostic _terminationCategoryForNamespace:code:signal:]
+ -[MXCrashDiagnostic initWithMetaData:applicationVersion:signpostData:reportedStateData:pid:terminationReason:applicationSpecificInfo:virtualMemoryRegionInfo:exceptionType:exceptionCode:exceptionReason:signal:terminationNamespace:terminationCode:stackTrace:]
+ -[MXCrashDiagnostic terminationCode]
+ -[MXCrashDiagnostic terminationNamespace]
+ -[MXLocationActivityMetric cumulativeReducedAccuracyTime]
+ -[MXLocationActivityMetric initWithCumulativeBestAccuracyTimeMeasurement:cumulativeBestAccuracyForNavigationTimeMeasurement:nearestTenMetersAccuracyTimeMeasurement:hundredMetersAccuracyTimeMeasurement:kilometerAccuracyTimeMeasurement:threeKilometerAccuracyTimeMeasurement:reducedAccuracyTimeMeasurement:]
+ _OBJC_CLASS_$__TtC9MetricKit14HitchTimeRatio
+ _OBJC_IVAR_$_MXCrashDiagnostic._terminationCode
+ _OBJC_IVAR_$_MXCrashDiagnostic._terminationNamespace
+ _OBJC_IVAR_$_MXLocationActivityMetric._cumulativeReducedAccuracyTime
+ _OBJC_METACLASS_$__TtC9MetricKit14HitchTimeRatio
+ __CLASS_METHODS__TtC9MetricKit14HitchTimeRatio
+ __DATA__TtC9MetricKit14HitchTimeRatio
+ __INSTANCE_METHODS__TtC9MetricKit14HitchTimeRatio
+ __METACLASS_DATA__TtC9MetricKit14HitchTimeRatio
+ _associated conformance 9MetricKit09HitchTimeA0V10CodingKeys33_FD315CFDC4824D66A6FC5270D3174733LLOSHAASQ
+ _associated conformance 9MetricKit09HitchTimeA0V10CodingKeys33_FD315CFDC4824D66A6FC5270D3174733LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 9MetricKit09HitchTimeA0V10CodingKeys33_FD315CFDC4824D66A6FC5270D3174733LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _objc_retain_x4
+ _symbolic _____ 9MetricKit09HitchTimeA0V10CodingKeys33_FD315CFDC4824D66A6FC5270D3174733LLO
+ _symbolic _____ 9MetricKit14HitchTimeRatioC
+ _symbolic _____y_____G 10Foundation11MeasurementV 9MetricKit14HitchTimeRatioC
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9MetricKit09HitchTimeD0V10CodingKeys33_FD315CFDC4824D66A6FC5270D3174733LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9MetricKit09HitchTimeD0V10CodingKeys33_FD315CFDC4824D66A6FC5270D3174733LLO
+ _symbolic _____y_____GSg 10Foundation11MeasurementV 9MetricKit14HitchTimeRatioC
+ _symbolic _____y_____GSg_ADt 10Foundation11MeasurementV 9MetricKit14HitchTimeRatioC
- +[MXCrashDiagnostic _resolveTerminationCategoryWithSignal:terminationReason:]
- _OBJC_CLASS_$_NSRegularExpression
- _OBJC_CLASS_$_NSScanner
- _associated conformance 9MetricKit015ScrollHitchTimeA0V10CodingKeys33_03245610228668DEF28556E7C33FDCA3LLOSHAASQ
- _associated conformance 9MetricKit015ScrollHitchTimeA0V10CodingKeys33_03245610228668DEF28556E7C33FDCA3LLOs0F3KeyAAs23CustomStringConvertible
- _associated conformance 9MetricKit015ScrollHitchTimeA0V10CodingKeys33_03245610228668DEF28556E7C33FDCA3LLOs0F3KeyAAs28CustomDebugStringConvertible
- _associated conformance 9MetricKit015ScrollHitchTimeA0VSHAASQ
- _associated conformance 9MetricKit09HitchTimeA0V10CodingKeys011_2B5C7FD179G20A6A18C2E25E0EB7EAAA5LLOSHAASQ
- _associated conformance 9MetricKit09HitchTimeA0V10CodingKeys011_2B5C7FD179G20A6A18C2E25E0EB7EAAA5LLOs0E3KeyAAs23CustomStringConvertible
- _associated conformance 9MetricKit09HitchTimeA0V10CodingKeys011_2B5C7FD179G20A6A18C2E25E0EB7EAAA5LLOs0E3KeyAAs28CustomDebugStringConvertible
- _symbolic _____ 9MetricKit015ScrollHitchTimeA0V
- _symbolic _____ 9MetricKit015ScrollHitchTimeA0V10CodingKeys33_03245610228668DEF28556E7C33FDCA3LLO
- _symbolic _____ 9MetricKit09HitchTimeA0V10CodingKeys011_2B5C7FD179G20A6A18C2E25E0EB7EAAA5LLO
- _symbolic _____Sg 9MetricKit015ScrollHitchTimeA0V
- _symbolic _____ySo6NSUnitCGSg_AEt 10Foundation11MeasurementV
- _symbolic _____y_____G s22KeyedDecodingContainerV 9MetricKit015ScrollHitchTimeD0V10CodingKeys33_03245610228668DEF28556E7C33FDCA3LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 9MetricKit09HitchTimeD0V10CodingKeys011_2B5C7FD179J20A6A18C2E25E0EB7EAAA5LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 9MetricKit015ScrollHitchTimeD0V10CodingKeys33_03245610228668DEF28556E7C33FDCA3LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 9MetricKit09HitchTimeD0V10CodingKeys011_2B5C7FD179J20A6A18C2E25E0EB7EAAA5LLO
CStrings:
+ "cumulativeReducedAccuracyTime"
+ "reducedAccuracy"
+ "terminationCode"
+ "terminationNamespace"
- "domain:(\\d+)\\s+code:0x([0-9A-Fa-f]+)"
- "scrollHitchTimeMetric"
```
