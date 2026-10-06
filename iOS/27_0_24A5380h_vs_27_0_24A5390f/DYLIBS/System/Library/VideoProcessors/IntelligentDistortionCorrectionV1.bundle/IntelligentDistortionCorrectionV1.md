## IntelligentDistortionCorrectionV1

> `/System/Library/VideoProcessors/IntelligentDistortionCorrectionV1.bundle/IntelligentDistortionCorrectionV1`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16fd8` | `0x172f0` | **`+0x318`** |
| `__AUTH_CONST.__cfstring` | `0xda0` | `0xe20` | **`+0x80`** |
| `__TEXT.__cstring` | `0x5575` | `0x55f1` | **`+0x7c`** |
| `__TEXT.__oslogstring` | `0x20fb` | `0x215a` | **`+0x5f`** |
| `__TEXT.__const` | `0x1a0` | `0x1b0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x218` | `0x220` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x788` | `0x790` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xd8c` | `0xd94` | **`+0x8`** |

### Other Changes

```diff

-758.0.0.122.2
+761.0.0.0.3

-  Functions: 497
-  Symbols:   125
-  CStrings:  588
+  Functions: 501
+  Symbols:   127
+  CStrings:  594
Symbols:
+ _FigCaptureComputeImageGainFromMetadata
+ _idcInverseValidRadiusSqr
CStrings:
+ "'adaptiveJittering' parsing aborted."
+ "[Intelligent Distortion Correction Processor] %s: Could not extract adaptive jittering options"
+ "adaptiveJittering"
+ "jitterEnabledTotalGainThreshold"
+ "jitterMaxDistance"
+ "jitterRatioScaling"
```
