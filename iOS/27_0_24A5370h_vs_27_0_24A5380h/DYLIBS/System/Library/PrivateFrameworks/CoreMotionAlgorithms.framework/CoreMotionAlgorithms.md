## CoreMotionAlgorithms

> `/System/Library/PrivateFrameworks/CoreMotionAlgorithms.framework/CoreMotionAlgorithms`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b0388` | `0x1b114c` | **`+0xdc4`** |
| `__TEXT.__cstring` | `0x1311f` | `0x13176` | **`+0x57`** |
| `__AUTH_CONST.__const` | `0xb760` | `0xb7b0` | **`+0x50`** |
| `__TEXT.__const` | `0x57e0` | `0x5800` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x5638` | `0x5650` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x4340` | `0x4348` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-3169.4.0.0.0
+3176.0.0.0.0

-  Functions: 5805
+  Functions: 5813

-  CStrings:  4087
+  CStrings:  4095
CStrings:
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMFactoredMatrix.h, line 236,invalid col %zu > %zu."
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMFactoredMatrix.h, line 242,invalid col %zu > %zu."
+ "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMFactoredMatrix.h, line 237,invalid element %zu <= %zu."
+ "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMFactoredMatrix.h, line 243,invalid element %zu <= %zu."
+ "Assertion failed: i0 < N-Ni+1 && j0 < N-Nj+1, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMFactoredMatrix.h, line 307,indices exceed factored matrix size."
+ "Assertion failed: row < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMFactoredMatrix.h, line 191,invalid row %zu > %zu."
+ "Assertion failed: row < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMFactoredMatrix.h, line 196,invalid row %zu > %zu."
+ "accelBias0"
+ "accelBias1"
+ "buttonPress"
+ "deltaPositionAltimeterZ"
+ "down"
+ "usage"
+ "usagePage"
+ "yOffset"
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMFactoredMatrix.h, line 234,invalid col %zu > %zu."
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMFactoredMatrix.h, line 240,invalid col %zu > %zu."
- "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMFactoredMatrix.h, line 235,invalid element %zu <= %zu."
- "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMFactoredMatrix.h, line 241,invalid element %zu <= %zu."
- "Assertion failed: i0 < N-Ni+1 && j0 < N-Nj+1, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMFactoredMatrix.h, line 305,indices exceed factored matrix size."
- "Assertion failed: row < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMFactoredMatrix.h, line 189,invalid row %zu > %zu."
- "Assertion failed: row < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMFactoredMatrix.h, line 194,invalid row %zu > %zu."
```
