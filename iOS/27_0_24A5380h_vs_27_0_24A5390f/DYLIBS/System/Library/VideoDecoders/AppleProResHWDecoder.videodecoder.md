## AppleProResHWDecoder.videodecoder

> `/System/Library/VideoDecoders/AppleProResHWDecoder.videodecoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x160` | `0x2a0` | **`+0x140`** |
| `__TEXT.__text` | `0x220a8` | `0x221d0` | **`+0x128`** |
| `__TEXT.__cstring` | `0x1258` | `0x12e6` | **`+0x8e`** |
| `__TEXT.__const` | `0x74460` | `0x743e0` | **`-0x80`** |
| `__TEXT.__oslogstring` | `0x46d6` | `0x46ce` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x458` | `0x450` | **`-0x8`** |

### Other Changes

```diff

-600.38.0.0.0
+600.45.0.0.0

-  - /System/Library/PrivateFrameworks/CMCaptureCore.framework/CMCaptureCore

-  Functions: 539
-  Symbols:   591
-  CStrings:  414
+  Functions: 538
+  Symbols:   581
+  CStrings:  424
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
~ __ZL25ProResDecoder_SetPropertyP18OpaqueCMBaseObjectPK10__CFStringPKv : 1352 -> 1328
+ _OUTLINED_FUNCTION_7
- _OUTLINED_FUNCTION_14
~ __ZL25ProResDecoder_SetPropertyP18OpaqueCMBaseObjectPK10__CFStringPKv.cold.2 : 104 -> 80
~ __ZL25ProResDecoder_SetPropertyP18OpaqueCMBaseObjectPK10__CFStringPKv.cold.3 : 80 -> 84
~ __ZL25ProResDecoder_SetPropertyP18OpaqueCMBaseObjectPK10__CFStringPKv.cold.5 : 84 -> 80
- __ZL39ProResDecoder_WaitForAsynchronousFramesP20OpaqueVTVideoDecoderj.cold.2
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
- "ERROR AppleProResHW (0x%x): %d: %s(): log2DownScaleFactorW %d not equal to log2DownScaleFactorH %d!\n"
- "ProResRawNRMetadata"
```
