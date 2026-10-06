## AppleProResHWEncoder.videoencoder

> `/System/Library/VideoEncoders/AppleProResHWEncoder.videoencoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20820` | `0x209c8` | **`+0x1a8`** |
| `__AUTH_CONST.__cfstring` | `0x360` | `0x4a0` | **`+0x140`** |
| `__TEXT.__cstring` | `0x1403` | `0x1491` | **`+0x8e`** |
| `__TEXT.__oslogstring` | `0x40f4` | `0x4151` | **`+0x5d`** |
| `__TEXT.__unwind_info` | `0x448` | `0x440` | **`-0x8`** |

### Other Changes

```diff

-600.38.0.0.0
+600.45.0.0.0

-  - /System/Library/PrivateFrameworks/CMCaptureCore.framework/CMCaptureCore

-  Symbols:   603
-  CStrings:  403
+  Symbols:   593
+  CStrings:  414
Symbols:
- _kFigCaptureStreamMetadata_AGC
- _kFigCaptureStreamMetadata_AWBComboBGain
- _kFigCaptureStreamMetadata_AWBComboRGain
- _kFigCaptureStreamMetadata_ConversionGain
- _kFigCaptureStreamMetadata_DistortionOpticalCenterV2
- _kFigCaptureStreamMetadata_LensShadingModulationWeight
- _kFigCaptureStreamMetadata_PostDemosaicGain
- _kFigCaptureStreamMetadata_ReadNoise_1x
- _kFigCaptureStreamMetadata_ReadNoise_8x
- _kFigCaptureStreamMetadata_SensorCropRect
Functions:
~ __Z18findMetadataSetTagPhjRKjS1_ : 340 -> 364
~ __Z23addVDDMetadataToMetaExtPK14__CFDictionaryPNSt3__16vectorIhNS2_9allocatorIhEEEERhj : 976 -> 1272
~ __Z23addLSCMetadataToMetaExtPK14__CFDictionaryPNSt3__16vectorIhNS2_9allocatorIhEEEERhj : 560 -> 668
~ __Z22getLog2DownscaleFactorjjPj : 64 -> 60
CStrings:
+ "AD"
+ "AGC"
+ "AWBComboBGain"
+ "AWBComboRGain"
+ "ConversionGain"
+ "DistortionOpticalCenterV2"
+ "LensShadingModulationWeight"
+ "PostDemosaicGain"
+ "ReadNoise_1x"
+ "ReadNoise_8x"
+ "SensorCropRect"
+ "WARNING AppleProResHW (0x%x): %d: %s(): VDD metadata keys not present in metadataDictionary\n"
- "ProResRawNRMetadata"
```
