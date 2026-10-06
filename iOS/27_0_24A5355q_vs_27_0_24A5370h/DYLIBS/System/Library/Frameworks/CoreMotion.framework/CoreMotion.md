## CoreMotion

> `/System/Library/Frameworks/CoreMotion.framework/CoreMotion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ab4d8` | `0x3ac5fc` | **`+0x1124`** |
| `__AUTH_CONST.__objc_const` | `0x1c788` | `0x1c990` | **`+0x208`** |
| `__TEXT.__oslogstring` | `0x2cdc3` | `0x2cf87` | **`+0x1c4`** |
| `__TEXT.__cstring` | `0x45402` | `0x455b8` | **`+0x1b6`** |
| `__TEXT.__unwind_info` | `0xb590` | `0xb670` | **`+0xe0`** |
| `__AUTH_CONST.__cfstring` | `0x13460` | `0x13520` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0xcf84` | `0xd03c` | **`+0xb8`** |
| `__AUTH_CONST.__const` | `0x14ee0` | `0x14f50` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x1130` | `0x1180` | **`+0x50`** |
| `__TEXT.__const` | `0xc4c0` | `0xc500` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x5408` | `0x5438` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x16bc` | `0x16d8` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x3a38` | `0x3a48` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x1008` | `0x1018` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1480` | `0x1488` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x7d8` | `0x7e0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x878` | `0x880` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x768` | `0x770` | **`+0x8`** |

### Other Changes

```diff

-3164.0.0.0.0
+3169.4.0.0.0

-  Functions: 12314
-  Symbols:   1766
-  CStrings:  11027
+  Functions: 12337
+  Symbols:   1769
+  CStrings:  11046
Symbols:
+ _OBJC_CLASS_$_CMSedentaryRestingHeartRateData
+ _OBJC_METACLASS_$_CMSedentaryRestingHeartRateData
+ _PPSCreateTelemetryIdentifier
+ _PPSSendTelemetry
- _PLLogTimeSensitiveRegisteredEvent
CStrings:
+ "%@, <oneDayHR %.1f, sevenDayHR %.1f>"
+ "%@, <recordId %lu, startDate, %@, workoutSessionId %@, mets, %.3f, metSource, %lu, hr, %.3f, hrConf, %.3f, gradeType, %lu, grade, %.3f, cadence, %.3f, pace, %.3f, hasGPS, %d, hasStrideCal, %d, workoutType, %lu, isStroller, %d, heartRateTime, %f>"
+ "%@, <vo2maxInput, %@, vo2MaxResult, %@, vo2MaxSummary, %@, vo2MaxSessionAttribute, %@, vo2maxPrior, %@, recoveryHR, %@, recoveryWR, %@, recoverySessions, %@, sedentaryRestingHR, %@>"
+ "00:06:48"
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 240,invalid col %zu > %zu."
+ "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 235,invalid element %zu <= %zu."
+ "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 241,invalid element %zu <= %zu."
+ "Assertion failed: row < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 194,invalid row %zu > %zu."
+ "CMWakeGestureArrivalToNotified"
+ "CMWakeGestureDetectedToArrival"
+ "Incoming magic mount state, mountStatus,%{public}u, propertyC,%{public}u, isAPAwake,%{public}u, isSimulated,%{public}u, timestampSecs,%{public}f"
+ "Invalid data combination!"
+ "Jun 16 2026"
+ "LiftToWake"
+ "Not available for continuity camera configuration, propertyC,%{public}u"
+ "Notification=%{public}u Mode=%{public}u ConfigType=%{public}ld TimestampDeltaArrivalToNotified=%{public}f enableTelemetry=YES "
+ "Notification=%{public}u Mode=%{public}u ConfigType=%{public}u TimestampDeltaDetectedToArrival=%{public}f enableTelemetry=YES "
+ "Report,mountStatus,%{public}u,propertyC,%{public}u,APAwake,%{public}u,isSimulated,%{public}u,timestamp,%{public}lf,now,%{public}lf"
+ "[Gesture %{public}ld] Telemetry stream ID invalid"
+ "altitudeInMeters"
+ "companionAltitude"
+ "configType"
+ "kCMCardioHealthObjectCodingKeySedentaryRestingHR"
+ "kSedentaryRestingHRCodingKeyOneDayHR"
+ "kSedentaryRestingHRCodingKeySevenDayHR"
+ "kVO2MaxDataCodingKeyHeartRateTime"
+ "kVO2MaxDataCodingKeyIsStroller"
+ "l2NormGMMError"
+ "magneticInclinationError"
+ "magneticMagnitudeError"
+ "progress"
+ "uncertaintyInMeters"
+ "virtual IOHIDEventRef CLIoHidInterface::Device::copyEvent(NeedsEventUpdate)"
+ "void CLGestureService::onGestureService(const uint8_t *, size_t, uint64_t, CFTimeInterval)"
- "%@, <recordId %lu, startDate, %@, workoutSessionId %@, mets, %.3f, metSource, %lu, hr, %.3f, hrConf, %.3f, gradeType, %lu, grade, %.3f, cadence, %.3f, pace, %.3f, hasGPS, %d, hasStrideCal, %d, workoutType, %lu>"
- "%@, <vo2maxInput, %@, vo2MaxResult, %@, vo2MaxSummary, %@, vo2MaxSessionAttribute, %@, vo2maxPrior, %@, recoveryHR, %@, recoveryWR, %@, recoverySessions, %@>"
- "23:06:22"
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 237,invalid col %zu > %zu."
- "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 232,invalid element %zu <= %zu."
- "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 238,invalid element %zu <= %zu."
- "Assertion failed: row < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 191,invalid row %zu > %zu."
- "Incoming magic mount state, mountStatus,%{public}u, isAPAwake,%{public}u, isSimulated,%{public}u, timestampSecs,%{public}f"
- "MSLWriter - pruning rotated session file: %{private}s"
- "May 27 2026"
- "Report,mountStatus,%{public}u,APAwake,%{public}u,isSimulated,%{public}u,timestamp,%{public}lf,now,%{public}lf"
- "SurfBoard"
- "Wake-Gesture-Event"
- "virtual IOHIDEventRef CLIoHidInterface::Device::copyEvent()"
- "void CLGestureService::onGestureService(const uint8_t *, size_t, uint64_t)"
```
