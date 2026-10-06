## FRC

> `/System/Library/PrivateFrameworks/FRC.framework/FRC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f0cc` | `0x400dc` | **`+0x1010`** |
| `__AUTH_CONST.__objc_const` | `0xa488` | `0xa710` | **`+0x288`** |
| `__TEXT.__cstring` | `0x63f5` | `0x65fb` | **`+0x206`** |
| `__AUTH_CONST.__cfstring` | `0x3d40` | `0x3ec0` | **`+0x180`** |
| `__TEXT.__objc_methlist` | `0x3a24` | `0x3a9c` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x2268` | `0x22d8` | **`+0x70`** |
| `__DATA.__objc_ivar` | `0xd64` | `0xdb0` | **`+0x4c`** |
| `__TEXT.__oslogstring` | `0xe93` | `0xec3` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xc48` | `0xc78` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x6e0` | `0x708` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x458` | `0x460` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x268` | `0x26c` | **`+0x4`** |

### Other Changes

```diff

-255.0.0.0.0
+258.0.0.0.0

-  Functions: 1435
-  Symbols:   2950
-  CStrings:  828
+  Functions: 1445
+  Symbols:   2981
+  CStrings:  842
Symbols:
+ -[DualOpticalFlowE5 allocateSubsampledInputBuffers]
+ -[DualOpticalFlowE5 expectOriginalInput]
+ -[FRCFrameInterpolator allocateNormalizedOutputBufferPool]
+ -[FRCFrameInterpolator setUseOriginalForOpticalFlow:]
+ -[FRCFrameInterpolator setUseOriginalForSynthesis:]
+ -[FRCFrameInterpolator synthesizeInterpolatedFrames:second:timeScales:outputSize:outputPixelFormat:scalerEnabled:]
+ -[FRCFrameInterpolator useOriginalForOpticalFlow]
+ -[FRCFrameInterpolator useOriginalForSynthesis]
+ -[Forwarp encodeWarpAndBlendFeaturesWithErrorMaskComputeToCommandBuffer:first:second:forwardFlow:backwardFlow:forwardErrorMap:backwardErrorMap:forwarpConsistency:backwardConsistency:timeScale:destination:]
+ -[Forwarp encodeWarpAndBlendFeaturesWithErrorMaskRenderToCommandBuffer:first:second:forwardFlow:backwardFlow:forwardErrorMap:backwardErrorMap:forwarpConsistency:backwardConsistency:timeScale:destination:]
+ -[OpticalFlow expectOriginalInput]
+ -[Pyramid encodeLayerBlendRenderToCommandBuffer:baseLayer:acLayer:toDestination:]
+ -[Pyramid encodeLayerBlendToCommandBuffer:baseLayer:acLayer:toDestination:]
+ -[Synthesis allocateBlendedAcTexture]
+ -[Synthesis allocateSubsampledInputPixelBuffersForUsage:]
+ -[Synthesis featureLevelFor:Level:]
+ -[Synthesis synthesizeFrameForTimeScale:frameIndex:outputFrame:lastFrame:]
+ -[Synthesis synthesizeFrameFromFirstImage:secondImage:flowForward:flowBackward:timeScale:frameIndex:output:lastFrame:]
+ -[Synthesis synthesizeImageWithFlowSplattingFromFirstImage:secondImage:flowForward:flowBackward:timeScale:destination:lastFrame:]
+ _OBJC_CLASS_$_MTLCommandQueueDescriptor
+ _OBJC_IVAR_$_DualOpticalFlowE5._inputPixelFormat
+ _OBJC_IVAR_$_FRCBlit._yuvTextureToLinearBuffer
+ _OBJC_IVAR_$_FRCFrameInterpolator._inputFrameHeight
+ _OBJC_IVAR_$_FRCFrameInterpolator._inputFrameWidth
+ _OBJC_IVAR_$_FRCFrameInterpolator._inputPixelFormat
+ _OBJC_IVAR_$_FRCFrameInterpolator._normalizedOutputBufferPool
+ _OBJC_IVAR_$_FRCFrameInterpolator._paddingOnly
+ _OBJC_IVAR_$_FRCFrameInterpolator._useOriginalForOpticalFlow
+ _OBJC_IVAR_$_FRCFrameInterpolator._useOriginalForSynthesis
+ _OBJC_IVAR_$_FRCOpticalFlowEstimator._scaler
+ _OBJC_IVAR_$_Forwarp._vertsBuffer
+ _OBJC_IVAR_$_Forwarp._warpAndBlendTexturesWithConsistencyYCbCr
+ _OBJC_IVAR_$_Forwarp._warpAndBlendTexturesYCbCr
+ _OBJC_IVAR_$_NeuFlow._useDistilledModel
+ _OBJC_IVAR_$_Normalization._paddingOnly
+ _OBJC_IVAR_$_Pyramid._gaussian3x3FilterYCbCrKernel
+ _OBJC_IVAR_$_Pyramid._residueYCbCrKernel
+ _OBJC_IVAR_$_Pyramid._twoLayerBlendYCbCrRenderKernel
+ _OBJC_IVAR_$_Pyramid._vertsBuffer
+ _OBJC_IVAR_$_Synthesis._blendedACBuffer
+ _OBJC_IVAR_$_Synthesis._blendedACTexture
+ ___block_descriptor_58_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_93_e8_32s40s48s56s64r_e5_v8?0lr64l8s32l8s40l8s48l8s56l8
+ _isYUV420Format
+ _objc_retain_x10
- -[DualOpticalFlowE5 expectRGBAInput]
- -[FRCFrameInterpolator setUseRGBAForOpticalFlow:]
- -[FRCFrameInterpolator setUseRGBAForSynthesis:]
- -[FRCFrameInterpolator synthesizeInterpolatedFrames:second:preprocessedFirst:preprocessedSecond:timeScales:outputSize:outputPixelFormat:scalerEnabled:]
- -[FRCFrameInterpolator useRGBAForOpticalFlow]
- -[FRCFrameInterpolator useRGBAForSynthesis]
- -[OpticalFlow expectRGBAInput]
- -[Pyramid encodeLayerBlendToCommandBuffer:baseLayer:toDestination:]
- -[Synthesis synthesizeFrameFromFirstImage:secondImage:flowForward:flowBackward:timeScale:frameIndex:]
- -[Synthesis synthesizeImageWithFlowSplattingFromFirstImage:secondImage:flowForward:flowBackward:timeScale:destination:]
- _OBJC_IVAR_$_FRCFrameInterpolator._useRGBAForOpticalFlow
- _OBJC_IVAR_$_FRCFrameInterpolator._useRGBAForSynthesis
- ___block_descriptor_93_e8_32s40s48s56s64r_e5_v8?0ls32l8r64l8s40l8s48l8s56l8
- _objc_retain_x9
CStrings:
+ "\v"
+ "FRC::yuvTextureToLineraBuffer"
+ "FrameInterpolator Command Queue"
+ "NeuFlowUseDistilledModel"
+ "Neuflow2_s8_ctx_flowAttn_lite_432x768_landscape_1x_s8Refine_ML_lv1flow_part1_ANE"
+ "Neuflow2_s8_ctx_flowAttn_lite_432x768_landscape_1x_s8Refine_ML_lv1flow_part2_ANE"
+ "Neuflow2_s8_ctx_flowAttn_lite_432x768_landscape_1x_s8Refine_ML_lv1flow_part3_ANE"
+ "OpticalFlow Command Queue"
+ "Using Distilled Model"
+ "Using Non Distilled Model"
+ "blend_two_layer_pyramid_YCbCr"
+ "create_residue_YCbCr"
+ "gaussian3x3_filter_YCbCr_SIMD"
+ "warpAndBlendImageWithErrorAndFlowConsistencyYCbCr"
+ "warpAndBlendWithErrorMapYCbCr"
- "\n"
```
