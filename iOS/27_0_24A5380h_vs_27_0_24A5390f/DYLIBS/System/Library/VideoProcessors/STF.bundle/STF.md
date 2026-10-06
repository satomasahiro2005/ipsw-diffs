## STF

> `/System/Library/VideoProcessors/STF.bundle/STF`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf9128` | `0xf93d8` | **`+0x2b0`** |
| `__AUTH_CONST.__objc_const` | `0x3dd0` | `0x3e60` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x1c4b` | `0x1cc9` | **`+0x7e`** |
| `__TEXT.__objc_methlist` | `0x171c` | `0x1734` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x468` | `0x478` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xcf0` | `0xd00` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x190` | `0x198` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-758.0.0.122.2
+761.0.0.0.3

-  Functions: 2136
-  Symbols:   2177
-  CStrings:  1211
+  Functions: 2138
+  Symbols:   2184
+  CStrings:  1212
Symbols:
+ -[STFRingData quadraBinningFactor]
+ -[STFRingData setQuadraBinningFactor:]
+ _OBJC_IVAR_$_STFRingData._quadraBinningFactor
+ _OBJC_IVAR_$_STFVideoProcessorV1._framesSinceQuadraTransition
+ _OBJC_IVAR_$_STFVideoProcessorV1._previousQuadraBinningFactor
+ _OBJC_IVAR_$_STFVideoProcessorV1._quadraTransitionPending
+ _kFigCaptureStreamMetadata_QuadraBinningFactor
CStrings:
+ "<<<< STF >>>> %s: Sensor/Binning Switch Detected Backwards at:%d and currentIndex:%d size:%d"
+ "<<<< STF >>>> %s: Sensor/Binning Switch Detected Forwards at:%d and currentIndex:%d"
+ "<<<< STF >>>> %s: quadra transition: clamping LTM application homography (delay=%u, framesSinceTransition=%d)"
- "<<<< STF >>>> %s: Sensor Switch Detected Backwards at:%d and currentIndex:%d size:%d"
- "<<<< STF >>>> %s: Sensor Switch Detected Forwards at:%d and currentIndex:%d"
```
