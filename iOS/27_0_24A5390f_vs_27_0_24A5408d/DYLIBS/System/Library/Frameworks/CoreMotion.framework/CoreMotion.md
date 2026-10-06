## CoreMotion

> `/System/Library/Frameworks/CoreMotion.framework/CoreMotion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ae150` | `0x3b5ea4` | **`+0x7d54`** |
| `__TEXT.__cstring` | `0x457a3` | `0x459ba` | **`+0x217`** |
| `__TEXT.__const` | `0xc530` | `0xc690` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x2d130` | `0x2d273` | **`+0x143`** |
| `__AUTH_CONST.__cfstring` | `0x135c0` | `0x136e0` | **`+0x120`** |
| `__AUTH_CONST.__objc_const` | `0x1c9f8` | `0x1caa8` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0xb6e0` | `0xb648` | **`-0x98`** |
| `__DATA_DIRTY.__bss` | `0x1038` | `0x10a0` | **`+0x68`** |
| `__AUTH_CONST.__const` | `0x14fc0` | `0x14f60` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x3a48` | `0x3a08` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0xca1c` | `0xc9e4` | **`-0x38`** |
| `__TEXT.__objc_methlist` | `0xd0b4` | `0xd0e4` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x16d8` | `0x16e8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x5488` | `0x5480` | **`-0x8`** |

### Other Changes

```diff

-3183.0.0.0.0
+3185.0.6.0.1

-  Functions: 12363
-  Symbols:   1772
-  CStrings:  11072
+  Functions: 12331
+  Symbols:   1776
+  CStrings:  11105
Symbols:
+ _CMSuppressionType2ClientEvent
+ _CMSuppressionType2ClientType
+ _CMSuppressionType2EventTime
+ _CMSuppressionType2VOEvent
CStrings:
+ "%@, <recordId, %lu, startDate, %@, activityEndTime, %@, workoutSessionId %@, workoutType, %lu, hrRecovery, %f, lambda, %f, hrMax, %f, hrMinAdjusted, %f, recoveryOnsetTime, %@, steadyStateHR, %f, status, %lu, sessionHrRecovery, %f, peakHR, %f, hrRecoveryReference, %f, testType, %ld>"
+ "%@, <recordId, %lu, startDate, %@, workoutType, %ld, sessionId, %@, durationInSeconds, %f, pointCount, %llu, hrMax, %f, hrMin, %f, meanHr, %f, meanVo2, %f, meanSpeed, %f, meanGrade, %f, meanHrConfidence, %f, meanHrCadenceAgreement, %f, meanCadence, %f, vo2MaxModelSource, %ld, sessionType, %ld, platformSource, %ld>"
+ ", platformSource, %ld, testType, %ld"
+ "-[CMBody _startUpdatingBodyToken:]"
+ "-[CMBody _stopUpdatingBodyToken:]"
+ "00:06:53"
+ "Assertion failed: !empty(), file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/CMVectorBuffer.h, line 141,front() on empty buffer."
+ "Assertion failed: !empty(), file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/CMVectorBuffer.h, line 147,back() on empty buffer."
+ "Assertion failed: !empty(), file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/CMVectorBuffer.h, line 163,maxElement() on empty buffer."
+ "Assertion failed: !empty(), file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/CMVectorBuffer.h, line 185,minElement() on empty buffer."
+ "Assertion failed: !empty(), file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/CMVectorBuffer.h, line 225,variance() on empty buffer."
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 255,invalid col %zu > %zu."
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMMatrix.h, line 71,invalid col %zu > %zu."
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMMatrix.h, line 78,invalid col %zu > %zu."
+ "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 250,invalid element %zu <= %zu."
+ "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 256,invalid element %zu <= %zu."
+ "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMVector.h, line 315,invalid index %zu >= %zu."
+ "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMVector.h, line 321,invalid index %zu >= %zu."
+ "Assertion failed: lambda2 != 0, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMOQuaternion.cpp, line 152,invalid weights."
+ "Assertion failed: ldx < M*N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMMatrix.h, line 84,invalid element %zu >= %zu."
+ "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMMatrix.h, line 70,invalid row %zu > %zu."
+ "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMMatrix.h, line 77,invalid row %zu > %zu."
+ "Assertion failed: row < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 209,invalid row %zu > %zu."
+ "Assertion failed: start <= end && end <= fCapacity, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/CMQueue.h, line 267,start=%zu end=%zu fCapacity=%u."
+ "Assertion failed: static_cast<uint32_t>(Cap) == fCapacity, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/CMQueue.h, line 252,fastIndex Cap=%zu mismatches fCapacity=%u."
+ "Assertion failed: t >= 0 && t <= 1, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMOQuaternion.cpp, line 300,Invalid time t for slerp."
+ "Aug  5 2026"
+ "CMVector<T, 3> CMFactoredMatrix<float, 3>::biermanObservationalUpdateSkew3(T, T, T, T, T, T, T) [T = float, N = 3, Dummy = void]"
+ "VOEvent"
+ "[CMBody] _startUpdatingBodyToken:%{public}@"
+ "[CMBody] _stopUpdatingBodyToken:%{public}@"
+ "adhrHeartRate"
+ "adhrHeartRateConfidence"
+ "alpha <= 0, matrix !positive definite"
+ "clientEvent"
+ "clientType"
+ "const T &CMQueue<CMVector<float, 3>>::fastIndex(const size_t) const [T = CMVector<float, 3>, Cap = 16UL]"
+ "epochsWithInsufficientHGForStiction"
+ "epochsWithStiction"
+ "epochsWithoutStiction"
+ "groupADeltaVThreshold1"
+ "groupADeltaVThreshold2"
+ "groupAMaxAccelNormThreshold"
+ "groupAPeakPressure"
+ "groupAShortAudioNumThreshold"
+ "groupAZgTimeThreshold"
+ "groupApplied"
+ "groupBDeltaVThreshold1"
+ "groupBDeltaVThreshold2"
+ "groupBMaxAccelNormThreshold"
+ "groupBPeakPressure"
+ "groupBShortAudioNumThreshold"
+ "groupBZgTimeThreshold"
+ "groupIsA"
+ "kCMCardioFitnessResultsCodingKeyPlatformSource"
+ "kCMCardioFitnessResultsCodingKeyTestType"
+ "kCMCardioFitnessSummaryCodingKeyPlatformSource"
+ "kCMRecoverySessionCodingKeyTestType"
+ "scaledADHRMets"
+ "stictionDuration"
+ "stictionStatus"
+ "stictionThreshold"
+ "void CMQueue<CMVector<float, 1>>::linearRanges(size_t, size_t, const T **, size_t *, const T **, size_t *) const [T = CMVector<float, 1>]"
+ "void CMQueue<CMVector<float, 3>>::linearRanges(size_t, size_t, const T **, size_t *, const T **, size_t *) const [T = CMVector<float, 3>]"
+ "zgIsAHStateStable"
+ "zgIsFreefallA"
+ "zgIsFreefallB"
+ "zgMetaTotalZgTimeA"
+ "zgMetaTotalZgTimeB"
+ "zgSelectedVariant"
+ "zgSettledAHState"
+ "zgUsedSettledState"
- "%@, <recordId, %lu, startDate, %@, activityEndTime, %@, workoutSessionId %@, workoutType, %lu, hrRecovery, %f, lambda, %f, hrMax, %f, hrMinAdjusted, %f, recoveryOnsetTime, %@, steadyStateHR, %f, status, %lu, sessionHrRecovery, %f, peakHR, %f, hrRecoveryReference, %f>"
- "%@, <recordId, %lu, startDate, %@, workoutType, %ld, sessionId, %@, durationInSeconds, %f, pointCount, %llu, hrMax, %f, hrMin, %f, meanHr, %f, meanVo2, %f, meanSpeed, %f, meanGrade, %f, meanHrConfidence, %f, meanHrCadenceAgreement, %f, meanCadence, %f, vo2MaxModelSource, %ld, sessionType, %ld>"
- "-[CMBody _startUpdatingMotionManager:]"
- "-[CMBody _stopUpdatingMotionManager:]"
- "19:30:32"
- "Assertion failed: !empty(), file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/CMVectorBuffer.h, line 139,front() on empty buffer."
- "Assertion failed: !empty(), file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/CMVectorBuffer.h, line 145,back() on empty buffer."
- "Assertion failed: !empty(), file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/CMVectorBuffer.h, line 161,maxElement() on empty buffer."
- "Assertion failed: !empty(), file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/CMVectorBuffer.h, line 183,minElement() on empty buffer."
- "Assertion failed: !empty(), file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/CMVectorBuffer.h, line 210,variance() on empty buffer."
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 242,invalid col %zu > %zu."
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMMatrix.h, line 73,invalid col %zu > %zu."
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMMatrix.h, line 80,invalid col %zu > %zu."
- "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 237,invalid element %zu <= %zu."
- "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 243,invalid element %zu <= %zu."
- "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMVector.h, line 299,invalid index %zu >= %zu."
- "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMVector.h, line 305,invalid index %zu >= %zu."
- "Assertion failed: i < size(), file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/CMVectorBuffer.h, line 39,out of buffer range %zu."
- "Assertion failed: lambda2 != 0, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMOQuaternion.cpp, line 208,invalid weights."
- "Assertion failed: ldx < M*N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMMatrix.h, line 86,invalid element %zu >= %zu."
- "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMMatrix.h, line 72,invalid row %zu > %zu."
- "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMMatrix.h, line 79,invalid row %zu > %zu."
- "Assertion failed: row < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 196,invalid row %zu > %zu."
- "Assertion failed: t >= 0 && t <= 1, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMOQuaternion.cpp, line 375,Invalid time t for slerp."
- "Element &CMVectorBufferBase<float, 1>::operator[](const size_t) [T = float, N = 1]"
- "Element &CMVectorBufferBase<float, 3>::operator[](const size_t) [T = float, N = 3]"
- "Jul 11 2026"
- "T &CMVector<float, 12>::operator[](const size_t) [T = float, N = 12]"
- "T &CMVector<float, 4>::operator[](const size_t) [T = float, N = 4]"
- "T &CMVector<float, 6>::operator[](const size_t) [T = float, N = 6]"
- "T &CMVector<float, 9>::operator[](const size_t) [T = float, N = 9]"
- "T CMVector<float, 12>::operator[](const size_t) const [T = float, N = 12]"
- "T CMVector<float, 2>::operator[](const size_t) const [T = float, N = 2]"
- "T CMVector<float, 3>::operator[](const size_t) const [T = float, N = 3]"
- "T CMVector<float, 4>::operator[](const size_t) const [T = float, N = 4]"
- "T CMVector<float, 6>::operator[](const size_t) const [T = float, N = 6]"
- "T CMVector<float, 9>::operator[](const size_t) const [T = float, N = 9]"
- "[CMBody] _startUpdatingMotionManager:%@"
- "[CMBody] _stopUpdatingMotionManager:%@"
```
