## CoreLocation

> `/System/Library/Frameworks/CoreLocation.framework/CoreLocation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x205ef0` | `0x206ef8` | **`+0x1008`** |
| `__TEXT.__cstring` | `0x24f39` | `0x2514e` | **`+0x215`** |
| `__AUTH_CONST.__objc_const` | `0x10298` | `0x10468` | **`+0x1d0`** |
| `__AUTH_CONST.__cfstring` | `0xb920` | `0xba40` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x3ab5c` | `0x3abea` | **`+0x8e`** |
| `__TEXT.__gcc_except_tab` | `0xf1fc` | `0xf264` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x9b74` | `0x9bd4` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x2158` | `0x21b0` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x2800` | `0x2850` | **`+0x50`** |
| `__TEXT.__const` | `0x4cd0` | `0x4d10` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x5688` | `0x56c0` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x52a0` | `0x52d0` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0xb00` | `0xb24` | **`+0x24`** |
| `__AUTH_CONST.__const` | `0x3d10` | `0x3d30` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x498` | `0x4a0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x420` | `0x428` | **`+0x8`** |

### Other Changes

```diff

-3183.0.0.0.0
+3185.0.6.0.1

-  Functions: 5203
-  Symbols:   1083
-  CStrings:  5541
+  Functions: 5216
+  Symbols:   1084
+  CStrings:  5556
Symbols:
+ _CLFlushErrorDomain
CStrings:
+ "-[CLLocationManager notifyWhenFlushedBufferedLocationsThroughDate:timeout:completion:]"
+ "-[CLLocationManager notifyWhenFlushedBufferedLocationsThroughDate:timeout:completion:]_block_invoke"
+ "00:18:13"
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMFactoredMatrix.h, line 255,invalid col %zu > %zu."
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 71,invalid col %zu > %zu."
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 78,invalid col %zu > %zu."
+ "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMFactoredMatrix.h, line 256,invalid element %zu <= %zu."
+ "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMVector.h, line 321,invalid index %zu >= %zu."
+ "Assertion failed: ldx < M*N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 84,invalid element %zu >= %zu."
+ "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 70,invalid row %zu > %zu."
+ "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 77,invalid row %zu > %zu."
+ "Aug  5 2026"
+ "CLFlushErrorDomain"
+ "CLMM,%{public}.1lf,Propagating,lat,%{sensitive}.8lf,lon,%{sensitive}.8lf,course,%{public}.3lf,speed,%{public}.1lf,speedLimit,%{public}.1lf,rampSpeed,%{public}.1lf,speedAtPropagationStart,%{public}.1lf"
+ "SimulateBufferedGnssPlatform"
+ "com.apple.corelocation.bufferedlocationflushmonitor"
+ "flush aborted: location updates stopped"
+ "flush aborted: manager invalidated"
+ "flush called with a nil completion; nothing to signal"
+ "flush completion will run on the shared queue; this manager is not backed by a dispatch delegate queue"
+ "flush not supported on this device"
+ "flush rejected: %{public}@"
+ "flush requires a non-nil date"
+ "flush requires an active rhythmic-waking session"
+ "flush superseded by a newer flush"
+ "flush timeout must be a positive, finite number"
+ "isContinuationOfPriorBatch"
+ "v24@?0q8@\"NSString\"16"
- "19:39:25"
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMFactoredMatrix.h, line 242,invalid col %zu > %zu."
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 73,invalid col %zu > %zu."
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 80,invalid col %zu > %zu."
- "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMFactoredMatrix.h, line 243,invalid element %zu <= %zu."
- "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMVector.h, line 299,invalid index %zu >= %zu."
- "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMVector.h, line 305,invalid index %zu >= %zu."
- "Assertion failed: ldx < M*N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 86,invalid element %zu >= %zu."
- "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 72,invalid row %zu > %zu."
- "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 79,invalid row %zu > %zu."
- "Jul 11 2026"
- "T CMVector<double, 2>::operator[](const size_t) const [T = double, N = 2]"
- "[Umeyama]:problem is infeasible"
```
