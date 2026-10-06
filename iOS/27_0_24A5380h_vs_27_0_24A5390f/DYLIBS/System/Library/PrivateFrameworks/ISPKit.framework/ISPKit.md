## ISPKit

> `/System/Library/PrivateFrameworks/ISPKit.framework/ISPKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x200f8` | `0x2068c` | **`+0x594`** |
| `__AUTH_CONST.__objc_const` | `0x6fb8` | `0x7438` | **`+0x480`** |
| `__TEXT.__objc_methlist` | `0x1fac` | `0x21ec` | **`+0x240`** |
| `__AUTH_CONST.__cfstring` | `0x16a0` | `0x1740` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x12a8` | `0x1328` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x2f60` | `0x2fc3` | **`+0x63`** |
| `__DATA.__objc_ivar` | `0x5bc` | `0x61c` | **`+0x60`** |
| `__TEXT.__cstring` | `0x1764` | `0x17b1` | **`+0x4d`** |
| `__DATA_CONST.__const` | `0x290` | `0x2b8` | **`+0x28`** |
| `__TEXT.__const` | `0x280` | `0x298` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x660` | `0x668` | **`+0x8`** |

### Other Changes

```diff

-20.55.3.0.0
+20.57.3.0.0

-  Functions: 942
-  Symbols:   1688
-  CStrings:  546
+  Functions: 993
+  Symbols:   1767
+  CStrings:  553
Symbols:
+ -[FrameOutCombinedEncoder encodeToCommandBuffer:inputDenoisedYUV:degammaLUT:gammaLUT:lscGainGrid:outputBand0Y:outputBand1R:outputBand1GB:outputBand1GBBytesPerRow:shaderModelInfo:lscCropParams:inputCropParams:ditherSeed:ditherStrength:artifactThreshold:uvMaskParams:]
+ -[LLVPostProcessorFrameParameters inputAWBCombBGain]
+ -[LLVPostProcessorFrameParameters inputAWBCombGGain]
+ -[LLVPostProcessorFrameParameters inputAWBCombRGain]
+ -[LLVPostProcessorFrameParameters inputAWBGrayWorldBGain]
+ -[LLVPostProcessorFrameParameters inputAWBGrayWorldGGain]
+ -[LLVPostProcessorFrameParameters inputAWBGrayWorldRGain]
+ -[LLVPostProcessorFrameParameters inputAWBLocked]
+ -[LLVPostProcessorFrameParameters inputAWBStable]
+ -[LLVPostProcessorFrameParameters setInputAWBCombBGain:]
+ -[LLVPostProcessorFrameParameters setInputAWBCombGGain:]
+ -[LLVPostProcessorFrameParameters setInputAWBCombRGain:]
+ -[LLVPostProcessorFrameParameters setInputAWBGrayWorldBGain:]
+ -[LLVPostProcessorFrameParameters setInputAWBGrayWorldGGain:]
+ -[LLVPostProcessorFrameParameters setInputAWBGrayWorldRGain:]
+ -[LLVPostProcessorFrameParameters setInputAWBLocked:]
+ -[LLVPostProcessorFrameParameters setInputAWBStable:]
+ -[LLVPreProcessorFrameParameters inputAWBCombBGain]
+ -[LLVPreProcessorFrameParameters inputAWBCombGGain]
+ -[LLVPreProcessorFrameParameters inputAWBCombRGain]
+ -[LLVPreProcessorFrameParameters inputAWBGrayWorldBGain]
+ -[LLVPreProcessorFrameParameters inputAWBGrayWorldGGain]
+ -[LLVPreProcessorFrameParameters inputAWBGrayWorldRGain]
+ -[LLVPreProcessorFrameParameters inputAWBLocked]
+ -[LLVPreProcessorFrameParameters inputAWBStable]
+ -[LLVPreProcessorFrameParameters setInputAWBCombBGain:]
+ -[LLVPreProcessorFrameParameters setInputAWBCombGGain:]
+ -[LLVPreProcessorFrameParameters setInputAWBCombRGain:]
+ -[LLVPreProcessorFrameParameters setInputAWBGrayWorldBGain:]
+ -[LLVPreProcessorFrameParameters setInputAWBGrayWorldGGain:]
+ -[LLVPreProcessorFrameParameters setInputAWBGrayWorldRGain:]
+ -[LLVPreProcessorFrameParameters setInputAWBLocked:]
+ -[LLVPreProcessorFrameParameters setInputAWBStable:]
+ -[LLVProcessorFrameParameters inputAWBCombBGain]
+ -[LLVProcessorFrameParameters inputAWBCombGGain]
+ -[LLVProcessorFrameParameters inputAWBCombRGain]
+ -[LLVProcessorFrameParameters inputAWBGrayWorldBGain]
+ -[LLVProcessorFrameParameters inputAWBGrayWorldGGain]
+ -[LLVProcessorFrameParameters inputAWBGrayWorldRGain]
+ -[LLVProcessorFrameParameters inputAWBLocked]
+ -[LLVProcessorFrameParameters inputAWBStable]
+ -[LLVProcessorFrameParameters setInputAWBCombBGain:]
+ -[LLVProcessorFrameParameters setInputAWBCombGGain:]
+ -[LLVProcessorFrameParameters setInputAWBCombRGain:]
+ -[LLVProcessorFrameParameters setInputAWBGrayWorldBGain:]
+ -[LLVProcessorFrameParameters setInputAWBGrayWorldGGain:]
+ -[LLVProcessorFrameParameters setInputAWBGrayWorldRGain:]
+ -[LLVProcessorFrameParameters setInputAWBLocked:]
+ -[LLVProcessorFrameParameters setInputAWBStable:]
+ _LLVTuningGroupName_FrameOutFilter
+ _LLVTuningKey_FrameOutFilter_BilateralThresholdLUT
+ _LLVTuningKey_FrameOutFilter_UVApplyRects
+ _LLVTuningKey_FrameOutFilter_UVBypassRects
+ _LLVTuningKey_FrameOutFilter_UVTransition
+ _OBJC_IVAR_$_LLVPostProcessorFrameParameters._inputAWBCombBGain
+ _OBJC_IVAR_$_LLVPostProcessorFrameParameters._inputAWBCombGGain
+ _OBJC_IVAR_$_LLVPostProcessorFrameParameters._inputAWBCombRGain
+ _OBJC_IVAR_$_LLVPostProcessorFrameParameters._inputAWBGrayWorldBGain
+ _OBJC_IVAR_$_LLVPostProcessorFrameParameters._inputAWBGrayWorldGGain
+ _OBJC_IVAR_$_LLVPostProcessorFrameParameters._inputAWBGrayWorldRGain
+ _OBJC_IVAR_$_LLVPostProcessorFrameParameters._inputAWBLocked
+ _OBJC_IVAR_$_LLVPostProcessorFrameParameters._inputAWBStable
+ _OBJC_IVAR_$_LLVPreProcessorFrameParameters._inputAWBCombBGain
+ _OBJC_IVAR_$_LLVPreProcessorFrameParameters._inputAWBCombGGain
+ _OBJC_IVAR_$_LLVPreProcessorFrameParameters._inputAWBCombRGain
+ _OBJC_IVAR_$_LLVPreProcessorFrameParameters._inputAWBGrayWorldBGain
+ _OBJC_IVAR_$_LLVPreProcessorFrameParameters._inputAWBGrayWorldGGain
+ _OBJC_IVAR_$_LLVPreProcessorFrameParameters._inputAWBGrayWorldRGain
+ _OBJC_IVAR_$_LLVPreProcessorFrameParameters._inputAWBLocked
+ _OBJC_IVAR_$_LLVPreProcessorFrameParameters._inputAWBStable
+ _OBJC_IVAR_$_LLVProcessorFrameParameters._inputAWBCombBGain
+ _OBJC_IVAR_$_LLVProcessorFrameParameters._inputAWBCombGGain
+ _OBJC_IVAR_$_LLVProcessorFrameParameters._inputAWBCombRGain
+ _OBJC_IVAR_$_LLVProcessorFrameParameters._inputAWBGrayWorldBGain
+ _OBJC_IVAR_$_LLVProcessorFrameParameters._inputAWBGrayWorldGGain
+ _OBJC_IVAR_$_LLVProcessorFrameParameters._inputAWBGrayWorldRGain
+ _OBJC_IVAR_$_LLVProcessorFrameParameters._inputAWBLocked
+ _OBJC_IVAR_$_LLVProcessorFrameParameters._inputAWBStable
+ __parseUVRects
+ _e5rt_precompiled_compute_op_create_options_set_anef_intermediate_buffer_size_hint
- -[FrameOutCombinedEncoder encodeToCommandBuffer:inputDenoisedYUV:degammaLUT:gammaLUT:lscGainGrid:outputBand0Y:outputBand1R:outputBand1GB:outputBand1GBBytesPerRow:shaderModelInfo:lscCropParams:inputCropParams:ditherSeed:ditherStrength:]
CStrings:
+ "ArtifactThreshold = %f (totalGain = %f)"
+ "BilateralThresholdLUT"
+ "FrameOutFilter"
+ "Options set anef intermediate buffer size hint hint failed"
+ "UVApplyRects"
+ "UVBypassRects"
+ "UVTransition"
+ "\x92"
+ "\xa1"
- "R"
- "\x81"
```
