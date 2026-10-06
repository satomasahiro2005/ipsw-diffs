## VideoStabilizationV2

> `/System/Library/VideoProcessors/VideoStabilizationV2.bundle/VideoStabilizationV2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35ea8` | `0x38778` | **`+0x28d0`** |
| `__TEXT.__objc_stubs` | `0x3260` | `0x39c0` | **`+0x760`** |
| `__TEXT.__objc_methname` | `0x5c79` | `0x639e` | **`+0x725`** |
| `__TEXT.__cstring` | `0x4d9d` | `0x50e3` | **`+0x346`** |
| `__DATA.__objc_const` | `0x4598` | `0x47a8` | **`+0x210`** |
| `__DATA.__objc_selrefs` | `0x1000` | `0x11d8` | **`+0x1d8`** |
| `__DATA_CONST.__got` | `0x8c0` | `0x9e0` | **`+0x120`** |
| `__TEXT.__const` | `0x6d0` | `0x720` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x960` | `0x9a0` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x4bc` | `0x4f8` | **`+0x3c`** |
| `__TEXT.__objc_methtype` | `0x191a` | `0x194b` | **`+0x31`** |
| `__TEXT.__objc_methlist` | `0x1c44` | `0x1c74` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x324` | `0x34c` | **`+0x28`** |
| `__DATA_CONST.__objc_intobj` | `0xa08` | `0xa20` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xce0` | `0xcf0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x808` | `0x818` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x680` | `0x688` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-  Functions: 1298
-  Symbols:   2106
-  CStrings:  1705
+  Functions: 1339
+  Symbols:   2221
+  CStrings:  1807
Symbols:
+ -[VISConfigurationV2 setTextureStyleRenderingEnabled:]
+ -[VISConfigurationV2 textureStyleRenderingEnabled]
+ OBJC_IVAR_$_VISConfigurationV2._textureStyleRenderingEnabled
+ OBJC_IVAR_$_affineGPUMetal._skinSmoothingBlurEstimate
+ OBJC_IVAR_$_affineGPUMetal._skinSmoothingDegrunge
+ OBJC_IVAR_$_affineGPUMetal._skinSmoothingFaceStats
+ OBJC_IVAR_$_affineGPUMetal._skinSmoothingHighlightRetention
+ OBJC_IVAR_$_affineGPUMetal._skinSmoothingIntermediateROI
+ OBJC_IVAR_$_affineGPUMetal._skinSmoothingLargeBlurGuidedFilterA
+ OBJC_IVAR_$_affineGPUMetal._skinSmoothingLargeBlurGuidedFilterB
+ OBJC_IVAR_$_affineGPUMetal._skinSmoothingPlusGreenGuide
+ OBJC_IVAR_$_affineGPUMetal._skinSmoothingPores
+ OBJC_IVAR_$_affineGPUMetal._skinSmoothingProcessedSkinMask
+ OBJC_IVAR_$_affineGPUMetal._skinSmoothingSkinMask
+ OBJC_IVAR_$_affineGPUMetal._skinSmoothingSmallBlur
+ OBJC_IVAR_$_affineGPUMetal._skinSmoothingTextureAddback
+ OBJC_IVAR_$_affineGPUMetal._skinSmoothingTextureRestore
+ _FigCaptureUnityRect
+ _GVSComputeSampledInputRect
+ _OBJC_CLASS_$_CMIImageTile
+ _OBJC_CLASS_$_CMITextureStylesEffectDescriptor
+ _OBJC_CLASS_$_CMITextureStylesPersonInputDataUtilities
+ _OBJC_CLASS_$_CMITextureStylesProcessor
+ _OBJC_CLASS_$_CMITextureStylesSkinSmoothParameters
+ _OUTLINED_FUNCTION_62
+ ___NSArray0__struct
+ _kCMITextureStylesMinFaceDiagonalRatio
+ _kCMITextureStylesPersonInputDataKey_faceAnglePitch
+ _kCMITextureStylesPersonInputDataKey_faceAngleRoll
+ _kCMITextureStylesPersonInputDataKey_faceAngleYaw
+ _kCMITextureStylesPersonInputDataKey_faceID
+ _kCMITextureStylesSoftGatingLowerBoundStreaming
+ _kCMITextureStylesSoftGatingUpperBoundStreaming
+ _kCMITextureStylesStreamingMaxFaceCount
+ _kFigCapturePortType_RenoFrontFacingSuperWideCamera
+ _kFigCaptureSampleBufferAttachedMediaKey_TextureStyleFaceAttitudeMetadata
+ _kFigCaptureSampleBufferAttachedMediaKey_TextureStyleImageStatistics
+ _kFigCaptureSampleBufferAttachedMediaKey_TextureStyleSkinSmoothingFaceStats
+ _kFigCaptureSampleBufferAttachedMediaKey_TextureStyleSkinSmoothingLargeBlurGuidedFilterA
+ _kFigCaptureSampleBufferAttachedMediaKey_TextureStyleSkinSmoothingLargeBlurGuidedFilterB
+ _kFigCaptureSampleBufferAttachedMediaKey_TextureStyleSkinSmoothingProcessedMask
+ _kFigCaptureSampleBufferAttachedMediaKey_TextureStyleSkinSmoothingSmallBlur
+ _kFigCaptureSampleBufferAttachedMediaKey_TextureStyleSkinSmoothingTextureAddback
+ _kFigCaptureSampleBufferMetadata_SmartStyleLearnedCoefficientsOnThisFrame
+ _kFigCaptureSampleBufferMetadata_TextureStyleSkinSmoothingRenderingParameters
+ _kFigCaptureStreamMetadata_BrightnessValue
+ _kFigCaptureTextureStyleSkinSmoothingRenderingParametersKey_BlurEstimate
+ _kFigCaptureTextureStyleSkinSmoothingRenderingParametersKey_Degrunge
+ _kFigCaptureTextureStyleSkinSmoothingRenderingParametersKey_HighlightRetention
+ _kFigCaptureTextureStyleSkinSmoothingRenderingParametersKey_IntermediateROI
+ _kFigCaptureTextureStyleSkinSmoothingRenderingParametersKey_PlusGreenGuide
+ _kFigCaptureTextureStyleSkinSmoothingRenderingParametersKey_Pores
+ _kFigCaptureTextureStyleSkinSmoothingRenderingParametersKey_TextureRestore
+ _kFigVideoStabilizationSampleBufferAttachmentKey_TextureStyleTuningParameters
+ _kFigVideoStabilizationSampleBufferProcessorOption_TextureStyleRenderingEnabled
+ _kFigVideoStabilizationTextureStyleTuningKey_Intensity
+ _objc_msgSend$degrunge
+ _objc_msgSend$detailSize
+ _objc_msgSend$dictionaryRepresentationForKeys:
+ _objc_msgSend$effectTypeToEffectName:
+ _objc_msgSend$enableTextureAddback
+ _objc_msgSend$externalMemoryResource
+ _objc_msgSend$faceDiagonalRatioForFaceSize:imageSize:
+ _objc_msgSend$faceROI
+ _objc_msgSend$fastMode
+ _objc_msgSend$gFContrast
+ _objc_msgSend$gFRadius
+ _objc_msgSend$highlightRetention
+ _objc_msgSend$initWithPixelBuffer:regionInFullImageCoords:
+ _objc_msgSend$initWithTuningDictionary:
+ _objc_msgSend$initWithtype:parameters:
+ _objc_msgSend$maxDarknessTrigger
+ _objc_msgSend$minDarknessTrigger
+ _objc_msgSend$nightMode
+ _objc_msgSend$nightModeSharpness
+ _objc_msgSend$normalizePersonInputDataArray:toCropRect:
+ _objc_msgSend$objectAtIndex:
+ _objc_msgSend$personInputDataArrayFromDetectedFaces:
+ _objc_msgSend$plusGreenGuide
+ _objc_msgSend$pores
+ _objc_msgSend$roughSamples
+ _objc_msgSend$setBrightnessValue:
+ _objc_msgSend$setDegrunge:
+ _objc_msgSend$setDetailSize:
+ _objc_msgSend$setEffectsToRender:
+ _objc_msgSend$setEnableDeltaMapDetailEnhancement:
+ _objc_msgSend$setEnableTextureAddback:
+ _objc_msgSend$setFastMode:
+ _objc_msgSend$setFragmentBuffer:offset:atIndex:
+ _objc_msgSend$setFullImageSize:
+ _objc_msgSend$setGFContrast:
+ _objc_msgSend$setGFRadius:
+ _objc_msgSend$setHighlightRetention:
+ _objc_msgSend$setInputImage:
+ _objc_msgSend$setInputMasks:
+ _objc_msgSend$setInputPersonData:
+ _objc_msgSend$setInputSkinMaskPixelBuffer:
+ _objc_msgSend$setOutputImage:
+ _objc_msgSend$setOutputPersonImageStats:
+ _objc_msgSend$setOutputSkinSmoothingLargeBlurGuidedFilterA:
+ _objc_msgSend$setOutputSkinSmoothingLargeBlurGuidedFilterB:
+ _objc_msgSend$setOutputSkinSmoothingProcessedMask:
+ _objc_msgSend$setOutputSkinSmoothingSmallBlur:
+ _objc_msgSend$setOutputSkinSmoothingStats:
+ _objc_msgSend$setOutputSkinSmoothingTextureAddback:
+ _objc_msgSend$setPlusGreenGuide:
+ _objc_msgSend$setPores:
+ _objc_msgSend$setRegionToRender:
+ _objc_msgSend$setRoughSamples:
+ _objc_msgSend$setStreamingMode:
+ _objc_msgSend$setTextureRestore:
+ _objc_msgSend$softFadeGatingForFaceSize:imageSize:lowerBound:upperBound:
+ _objc_msgSend$sortPersonInputDataArrayByFaceSize:maxCount:
+ _objc_msgSend$textureRestore
+ _objc_msgSend$textureStyleRenderingEnabled
CStrings:
+ "EffectOrder"
+ "SkinSmoothingStandalone"
+ "TB,N,V_textureStyleRenderingEnabled"
+ "_skinSmoothingBlurEstimate"
+ "_skinSmoothingDegrunge"
+ "_skinSmoothingFaceStats"
+ "_skinSmoothingHighlightRetention"
+ "_skinSmoothingIntermediateROI"
+ "_skinSmoothingLargeBlurGuidedFilterA"
+ "_skinSmoothingLargeBlurGuidedFilterB"
+ "_skinSmoothingPlusGreenGuide"
+ "_skinSmoothingPores"
+ "_skinSmoothingProcessedSkinMask"
+ "_skinSmoothingSkinMask"
+ "_skinSmoothingSkinMask == ((void*)0) || skinMaskMetalTextureRef"
+ "_skinSmoothingSmallBlur"
+ "_skinSmoothingTextureAddback"
+ "_skinSmoothingTextureRestore"
+ "_textureStyleRenderingEnabled"
+ "cameraMetadata->currentPort < ( kFigPortIndex_RenoFrontFacingSuperWideCamera + 1 )"
+ "degrunge"
+ "degrungeNum"
+ "detailSize"
+ "dictionaryRepresentationForKeys:"
+ "digitalZoomFactor > 0.0f && storage->outputWidth > 0 && storage->outputHeight > 0"
+ "effectDescriptor"
+ "effectTypeToEffectName:"
+ "enableTextureAddback"
+ "faceDiagonalRatioForFaceSize:imageSize:"
+ "faceROI"
+ "fastMode"
+ "gFContrast"
+ "gFRadius"
+ "highlightRetention"
+ "highlightRetentionNum"
+ "initWithPixelBuffer:regionInFullImageCoords:"
+ "initWithTuningDictionary:"
+ "initWithtype:parameters:"
+ "inputImageTile"
+ "localBlockError == 0 "
+ "maxDarknessTrigger"
+ "minDarknessTrigger"
+ "nightMode"
+ "nightModeSharpness"
+ "normalizePersonInputDataArray:toCropRect:"
+ "objectAtIndex:"
+ "outputImageTile"
+ "outputMetadataDict"
+ "outputStats"
+ "peopleData"
+ "peopleDataSerialized"
+ "personInputDataArrayFromDetectedFaces:"
+ "plusGreenGuide"
+ "plusGreenGuideNum"
+ "pores"
+ "poresNum"
+ "processor"
+ "roughSamples"
+ "setBrightnessValue:"
+ "setDegrunge:"
+ "setDetailSize:"
+ "setEffectsToRender:"
+ "setEnableDeltaMapDetailEnhancement:"
+ "setEnableTextureAddback:"
+ "setFastMode:"
+ "setFragmentBuffer:offset:atIndex:"
+ "setFullImageSize:"
+ "setGFContrast:"
+ "setGFRadius:"
+ "setHighlightRetention:"
+ "setInputImage:"
+ "setInputMasks:"
+ "setInputPersonData:"
+ "setInputSkinMaskPixelBuffer:"
+ "setOutputImage:"
+ "setOutputPersonImageStats:"
+ "setOutputSkinSmoothingLargeBlurGuidedFilterA:"
+ "setOutputSkinSmoothingLargeBlurGuidedFilterB:"
+ "setOutputSkinSmoothingProcessedMask:"
+ "setOutputSkinSmoothingSmallBlur:"
+ "setOutputSkinSmoothingStats:"
+ "setOutputSkinSmoothingTextureAddback:"
+ "setPlusGreenGuide:"
+ "setPores:"
+ "setRegionToRender:"
+ "setRoughSamples:"
+ "setStreamingMode:"
+ "setTextureRestore:"
+ "setTextureStyleRenderingEnabled:"
+ "skin smoothing degrunge parameter is missing"
+ "skin smoothing highlightRetention parameter is missing"
+ "skin smoothing plusGreenGuide parameter is missing"
+ "skin smoothing pores parameter is missing"
+ "skin smoothing textureRestore parameter is missing"
+ "skinSmoothingParameters"
+ "smallBlurTexture && largeBlurGuidedFilterATexture && largeBlurGuidedFilterBTexture && faceStatsBuffer"
+ "softFadeGatingForFaceSize:imageSize:lowerBound:upperBound:"
+ "sortPersonInputDataArrayByFaceSize:maxCount:"
+ "textureRestore"
+ "textureRestoreNum"
+ "textureStyleContext->textureStyleProcessor"
+ "textureStyleRenderingEnabled"
+ "textureStyleStats"
+ "{?=\"clampingEnabled\"B\"replicationRect\"\"srlFixOn\"B\"srlCurveParameter\"f\"applyAppleLogEncoding\"B\"outputIsYCC\"B\"fovScaling\"f\"fovScalingOffset\"\"rcpOutputDims\"\"inputRGBFromYCCMatrix\"{?=\"columns\"[4]}\"outputYCCFromRGBMatrix\"{?=\"columns\"[4]}\"outputRGBFromYCCMatrix\"{?=\"columns\"[4]}\"deltaMapYCCFromRGBMatrix\"{?=\"columns\"[4]}\"ditherSeed\"I\"ditherStrengthLuma\"f\"ditherStrengthChroma\"f\"fbsParamsLuma\"{?=\"inputBias\"f\"deltaThreshold\"f\"edgeThreshold\"f}\"fbsParamsChroma\"{?=\"inputBias\"f\"deltaThreshold\"f\"edgeThreshold\"f}\"outputUnstyledImage\"B\"skinSmoothPores\"f\"skinSmoothDegrunge\"f\"skinSmoothTextureRestore\"f\"skinSmoothHighlightRetention\"f\"skinSmoothPlusGreenGuide\"f\"skinSmoothBlurEstimate\"f\"skinSmoothIntermediateROI\"}"
- "cameraMetadata->currentPort < ( kFigPortIndex_BackFacingTimeOfFlightCamera + 1 )"
- "{?=\"clampingEnabled\"B\"replicationRect\"\"srlFixOn\"B\"srlCurveParameter\"f\"applyAppleLogEncoding\"B\"outputIsYCC\"B\"fovScaling\"f\"fovScalingOffset\"\"rcpOutputDims\"\"inputRGBFromYCCMatrix\"{?=\"columns\"[4]}\"outputYCCFromRGBMatrix\"{?=\"columns\"[4]}\"outputRGBFromYCCMatrix\"{?=\"columns\"[4]}\"deltaMapYCCFromRGBMatrix\"{?=\"columns\"[4]}\"ditherSeed\"I\"ditherStrengthLuma\"f\"ditherStrengthChroma\"f\"fbsParamsLuma\"{?=\"inputBias\"f\"deltaThreshold\"f\"edgeThreshold\"f}\"fbsParamsChroma\"{?=\"inputBias\"f\"deltaThreshold\"f\"edgeThreshold\"f}\"outputUnstyledImage\"B\"toneCurveStrength\"f\"smoothingAmount\"f\"textureGain\"f\"highlightGain\"f\"channelMixAmount\"f\"adaptiveGainFactor\"f\"regionScaleFactor\"}"
```
