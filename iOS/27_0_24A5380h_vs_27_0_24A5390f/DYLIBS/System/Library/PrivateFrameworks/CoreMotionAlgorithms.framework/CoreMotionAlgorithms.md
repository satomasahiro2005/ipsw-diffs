## CoreMotionAlgorithms

> `/System/Library/PrivateFrameworks/CoreMotionAlgorithms.framework/CoreMotionAlgorithms`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b114c` | `0x1b15a0` | **`+0x454`** |
| `__TEXT.__cstring` | `0x13176` | `0x131ac` | **`+0x36`** |
| `__TEXT.__unwind_info` | `0x5650` | `0x5658` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x4348` | `0x4344` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-3176.0.0.0.0
+3183.0.0.0.0

-  CStrings:  4095
+  CStrings:  4099
Functions:
~ sub_25ad3f8c8 -> sub_25bf588c8 : 184 -> 140
~ sub_25ad77d74 -> sub_25bf90d48 : 36 -> 40
~ sub_25ad77e64 -> sub_25bf90e3c : 116 -> 160
~ sub_25ad77f80 -> sub_25bf90f84 : 144 -> 172
~ sub_25ad78010 -> sub_25bf91030 : 444 -> 684
~ sub_25ad78284 -> sub_25bf91394 : 76 -> 128
~ sub_25ad782d0 -> sub_25bf91414 : 36 -> 40
~ sub_25ad783c0 -> sub_25bf91508 : 116 -> 160
~ sub_25ad784dc -> sub_25bf91650 : 144 -> 172
~ sub_25ad7856c -> sub_25bf916fc : 444 -> 684
~ sub_25ad787e0 -> sub_25bf91a60 : 76 -> 128
~ sub_25ad93600 -> sub_25bfac8b4 : 152 -> 208
~ sub_25ad9369c -> sub_25bfac988 : 196 -> 260
~ sub_25ad93760 -> sub_25bfaca8c : 1364 -> 1876
~ sub_25ad93cb4 -> sub_25bfad1e0 : 168 -> 224
~ sub_25aeac7fc -> sub_25c0c5d60 : 432 -> 460
~ sub_25aeac9b0 -> sub_25c0c5f30 : 516 -> 548
~ sub_25aeacbb4 -> sub_25c0c6154 : 1964 -> 2020
~ sub_25aead360 -> sub_25c0c6938 : 56 -> 60
~ sub_25aead398 -> sub_25c0c6974 : 448 -> 476
~ sub_25aed4114 -> sub_25c0ed70c : 1292 -> 936
~ sub_25aed70d8 -> sub_25c0f056c : 488 -> 524
~ sub_25aed7908 -> sub_25c0f0dc0 : 840 -> 872
~ sub_25aed8014 -> sub_25c0f14ec : 528 -> 540
~ sub_25aed9284 -> sub_25c0f2768 : 96 -> 108
~ sub_25aedcf48 -> sub_25c0f6438 : 188 -> 156
~ sub_25aede608 -> sub_25c0f7ad8 : 176 -> 164
~ sub_25aedf6b8 -> sub_25c0f8b7c : 304 -> 280
~ sub_25aee07c4 -> sub_25c0f9c70 : 768 -> 680
CStrings:
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMMatrix.h, line 73,invalid col %zu > %zu."
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMMatrix.h, line 80,invalid col %zu > %zu."
+ "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMVector.h, line 299,invalid index %zu >= %zu."
+ "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMVector.h, line 305,invalid index %zu >= %zu."
+ "Assertion failed: ldx < M*N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMMatrix.h, line 86,invalid element %zu >= %zu."
+ "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMMatrix.h, line 72,invalid row %zu > %zu."
+ "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMMatrix.h, line 79,invalid row %zu > %zu."
+ "gpsAltitudeUncertainty"
+ "imuIndex"
+ "propertyA0"
+ "propertyA1"
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMMatrix.h, line 81,invalid col %zu > %zu."
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMMatrix.h, line 88,invalid col %zu > %zu."
- "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMVector.h, line 292,invalid index %zu >= %zu."
- "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMVector.h, line 298,invalid index %zu >= %zu."
- "Assertion failed: ldx < M*N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMMatrix.h, line 94,invalid element %zu >= %zu."
- "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMMatrix.h, line 80,invalid row %zu > %zu."
- "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionAlgorithmsFramework/Oscar/Math/CMMatrix.h, line 87,invalid row %zu > %zu."
```
