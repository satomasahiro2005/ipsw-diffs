## CameraColorProcessing

> `/System/Library/PrivateFrameworks/CameraColorProcessing.framework/CameraColorProcessing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b240` | `0x8a658` | **`-0xbe8`** |
| `__TEXT.__oslogstring` | `0xbe83` | `0xb949` | **`-0x53a`** |
| `__TEXT.__cstring` | `0x8fbc` | `0x9434` | **`+0x478`** |
| `__TEXT.__gcc_except_tab` | `0x519c` | `0x5064` | **`-0x138`** |
| `__AUTH_CONST.__const` | `0x598` | `0x4b8` | **`-0xe0`** |
| `__DATA_CONST.__const` | `0x1b8` | `0x118` | **`-0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x4cf0` | `0x4c60` | **`-0x90`** |
| `__DATA_DIRTY.__objc_data` | `0x820` | `0x7d0` | **`-0x50`** |
| `__TEXT.__const` | `0x6a64` | `0x6ab4` | **`+0x50`** |
| `__DATA_DIRTY.__bss` | `0x7d0` | `0x7a8` | **`-0x28`** |
| `__DATA_DIRTY.__common` | `0x1668` | `0x1648` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x1f5c` | `0x1f44` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x490` | `0x488` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xd8` | `0xd0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xf28` | `0xf20` | **`-0x8`** |

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3

-  Functions: 1338
-  Symbols:   1936
-  CStrings:  1870
+  Functions: 1361
+  Symbols:   1914
+  CStrings:  1886
Symbols:
+ -[AWBStatistics process:awbStatsBuffer:awbTileStatsConfig:anstSkinMaskData:skyMaskData:downsizeFactor:]
+ GCC_except_table47
+ _CMIUtilitiesGetFinalCropRect
+ _CMIUtilitiesGetTransformFromSensorCoordsToValidBufferCoords
+ _CMIUtilitiesISPFaces
+ _CMIUtilitiesISPFacesRectsArray
+ __ZN7CAWBAFE17ComputeProjectionEtPfS0_S0_S0_PA2_KsP18eAWBProjectionTypeS0_
+ __ZN7CAWBAFE36SetBrightDisplaySkinMitigationEnableEb
+ ___103-[AWBStatistics process:awbStatsBuffer:awbTileStatsConfig:anstSkinMaskData:skyMaskData:downsizeFactor:]_block_invoke
+ ___103-[AWBStatistics process:awbStatsBuffer:awbTileStatsConfig:anstSkinMaskData:skyMaskData:downsizeFactor:]_block_invoke_2
+ _e5rt_execution_stream_reset
- +[GeometryUtilities getTransformCropRectFromSensorCoordsToValidBufferCoordsWithMetadata:validBufferRect:]
- +[GeometryUtilities initialize]
- -[AWBStatistics process:clipped:lscGainsTex:validRectInBufferCoords:validRectInSensorReadoutCoords:awbStatsBuffer:awbTileStatsConfig:anstSkinMask:anstSkinMaskData:skyMaskTex:skyMaskData:regionOfInterestRectInBufferCoords:downsizeFactor:]
- GCC_except_table48
- _CGAffineTransformScale
- _CGAffineTransformTranslate
- _GeometryUtilitiesGetFinalCropRect
- _OBJC_CLASS_$_GeometryUtilities
- _OBJC_METACLASS_$_GeometryUtilities
- _UNAGI_NOTE_VARIABLE
- __OBJC_$_CLASS_METHODS_GeometryUtilities
- __OBJC_CLASS_RO_$_GeometryUtilities
- __OBJC_METACLASS_RO_$_GeometryUtilities
- __ZN7CAWBAFE17ComputeProjectionEtPfS0_S0_S0_PA2_KsP18eAWBProjectionType
- __ZZN11LTMDriverV19LTMDriver24computeFaceWeightForToneEPK24sRefDriverInputs_SOFTISPP16sLtmComputeInputE9onceToken
- __ZZN11LTMDriverV29LTMDriver17computeFaceWeightEPK7sBTRectP16sLtmComputeInputPK11sCIspFDRectiPfPKifE9onceToken
- __ZZN11LTMDriverV29LTMDriver27computeFaceWeightForToneHFFEPK24sRefDriverInputs_SOFTISPP16sLtmComputeInputE9onceToken
- __ZZN12LTMComputeV110LTMCompute18generateSpatialLTCEPK16sLtmComputeInputPK23sLtmComputeMeta_SOFTISPP17sLtmComputeOutputE9onceToken
- __ZZN12LTMComputeV210LTMCompute18generateSpatialLTCEPK24sLtmComputeInput_SOFTISPPK23sLtmComputeMeta_SOFTISPP17sLtmComputeOutputE9onceToken
- ___237-[AWBStatistics process:clipped:lscGainsTex:validRectInBufferCoords:validRectInSensorReadoutCoords:awbStatsBuffer:awbTileStatsConfig:anstSkinMask:anstSkinMaskData:skyMaskTex:skyMaskData:regionOfInterestRectInBufferCoords:downsizeFactor:]_block_invoke
- ___237-[AWBStatistics process:clipped:lscGainsTex:validRectInBufferCoords:validRectInSensorReadoutCoords:awbStatsBuffer:awbTileStatsConfig:anstSkinMask:anstSkinMaskData:skyMaskTex:skyMaskData:regionOfInterestRectInBufferCoords:downsizeFactor:]_block_invoke_2
- ___45-[AWBAlgorithm configFaceMetadata:awbParams:]_block_invoke
- ___85-[AWBStatistics configWindowsV2:metadata:tilesConfig:validRect:regionOfInterestRect:]_block_invoke
- ____ZN11LTMDriverV19LTMDriver24computeFaceWeightForToneEPK24sRefDriverInputs_SOFTISPP16sLtmComputeInput_block_invoke
- ____ZN11LTMDriverV29LTMDriver17computeFaceWeightEPK7sBTRectP16sLtmComputeInputPK11sCIspFDRectiPfPKif_block_invoke
- ____ZN11LTMDriverV29LTMDriver27computeFaceWeightForToneHFFEPK24sRefDriverInputs_SOFTISPP16sLtmComputeInput_block_invoke
- ____ZN12LTMComputeV110LTMCompute18generateSpatialLTCEPK16sLtmComputeInputPK23sLtmComputeMeta_SOFTISPP17sLtmComputeOutput_block_invoke
- ____ZN12LTMComputeV210LTMCompute18generateSpatialLTCEPK24sLtmComputeInput_SOFTISPPK23sLtmComputeMeta_SOFTISPP17sLtmComputeOutput_block_invoke
- ___block_descriptor_tmp
- _kFigCaptureSampleBufferMetadata_FinalCropRect
- _objc_release_x9
- _objc_retain_x25
- _objc_retain_x26
CStrings:
+ "-[AWBStatistics process:awbStatsBuffer:awbTileStatsConfig:anstSkinMaskData:skyMaskData:downsizeFactor:]"
+ "<<<< AWBAlgorithm >>>> %s: Face angleInfoRoll missing"
+ "<<<< AWBAlgorithm::CAWBAFEFDAssist >>>> %s: CAWBAFEFDAssist: numSemanticTiles %d"
+ "<<<< AWBStats >>>> %s: -[ANSTInferenceWrapper processANST] failed! SoftISP AWB will fall back to using face boxes"
+ "<<<< AWBStats >>>> %s: Face rect missing"
+ "<<<< LTMAlgorithm >>>> %s: globalHist is nil."
+ "<<<< LTMAlgorithm >>>> %s: localHist is nil."
+ "<<<< LTMAlgorithm >>>> %s: thumbnail is nil."
+ "AWB statistics calculation failed"
+ "CalculateSkinTileSemanticProbMap"
+ "Fail to extract metadata for LTM calculation"
+ "Fail to process LTM compute"
+ "Fail to process LTM compute for HLG"
+ "Fail to process LTM driver"
+ "Failed to prepareThumbnail"
+ "Failed to run estimateHaze"
+ "Failed to setup AWBAlgorithm"
+ "Failed to setup AWBStatistics"
+ "HITH statistics calculation failed"
+ "IOSurfaceRef invalid or NULL"
+ "LTMStatsCompute computeInputParameters failed"
+ "Locking anstBuf32Float failed"
+ "Locking anstBuf8 failed"
+ "Source and destination pixel buffer sizes do not match"
+ "Unable to translate combo skin gains from Wide to SuperWide"
+ "_bindANSTEspressoV5IOPort failed"
+ "anstBuf32Float is NULL"
+ "anstBuf8 is NULL"
+ "awbStatsBuffer is NULL"
+ "dstBufAddr is NULL"
+ "e5rt_execution_stream_reset failed: %s"
+ "failed to convert ANST mask buffer to required data type"
+ "foundEyeCoveringConfidence"
+ "foundFaceMaskConfidence"
+ "imageTex"
+ "imageTex is NULL"
+ "kCameraColorProcessingError_ANSTConfigUnsupported"
+ "kCameraColorProcessingError_ANSTPipelineSetupFailed"
+ "kCameraColorProcessingError_ANSTProcessingFailed"
+ "kCameraColorProcessingError_AWBAlgorithmProcessingFailed"
+ "kCameraColorProcessingError_AWBAlgorithmSetupFailed"
+ "kCameraColorProcessingError_AWBStatsCalculationFailed"
+ "kCameraColorProcessingError_AWBStatsSetupFailed"
+ "kCameraColorProcessingError_AllocationFailed"
+ "kCameraColorProcessingError_HazeEstimationProcessingFailed"
+ "kCameraColorProcessingError_HazeEstimationSetupFailed"
+ "kCameraColorProcessingError_Invalidated"
+ "kCameraColorProcessingError_LTMAlgorithmProcessingFailed"
+ "kCameraColorProcessingError_LTMAlgorithmSetupFailed"
+ "kCameraColorProcessingError_LTMStatsCalculationFailed"
+ "kCameraColorProcessingError_LTMStatsSetupFailed"
+ "kCameraColorProcessingError_ParamErr"
+ "kCameraColorProcessingError_UnsupportedOperation"
+ "kCameraColorProcessingError_UnsupportedVersion"
+ "kCameraColorProcessingError_ValueNotAvailable"
+ "srcBufAddr is NULL"
+ "tileStatsConfig"
+ "tileStatsConfig is NULL"
+ "translateAWBGainsToSecondaryChannelID failed"
+ "validBufferRect"
+ "validBufferRect is NULL"
- "! CGRectIsEmpty( normalizedSensorRawValidBufferRect )"
- "! CGRectIsEmpty( normalizedValidBufferRect )"
- "+[GeometryUtilities getTransformCropRectFromSensorCoordsToValidBufferCoordsWithMetadata:validBufferRect:]"
- "-1"
- "-[AWBStatistics process:clipped:lscGainsTex:validRectInBufferCoords:validRectInSensorReadoutCoords:awbStatsBuffer:awbTileStatsConfig:anstSkinMask:anstSkinMaskData:skyMaskTex:skyMaskData:regionOfInterestRectInBufferCoords:downsizeFactor:]"
- "<<<< ANSTInferenceWrapper >>>> %s: IOSurfaceRef invalid or NULL"
- "<<<< ANSTInferenceWrapper >>>> %s: Locking anstBuf32Float failed"
- "<<<< ANSTInferenceWrapper >>>> %s: Locking anstBuf8 failed"
- "<<<< ANSTInferenceWrapper >>>> %s: Source and destination pixel buffer sizes do not match"
- "<<<< ANSTInferenceWrapper >>>> %s: _bindANSTEspressoV5IOPort failed"
- "<<<< ANSTInferenceWrapper >>>> %s: anstBuf32Float is NULL"
- "<<<< ANSTInferenceWrapper >>>> %s: anstBuf8 is NULL"
- "<<<< ANSTInferenceWrapper >>>> %s: dstBufAddr is NULL"
- "<<<< ANSTInferenceWrapper >>>> %s: srcBufAddr is NULL"
- "<<<< AWBAlgorithm >>>> %s: Unable to translate combo skin gains from Wide to SuperWide"
- "<<<< CameraColorProcessing >>>> %s: Normalization of TotalSensorCropRect failed"
- "<<<< CameraColorProcessing >>>> %s: Normalization of valid buffer rect failed"
- "<<<< CameraColorProcessing >>>> %s: RawSensorHeight not found"
- "<<<< CameraColorProcessing >>>> %s: RawSensorWidth not found"
- "<<<< CameraColorProcessing >>>> %s: TotalSensorCropRect not found"
- "<<<< CameraColorProcessing >>>> %s: normalizedSensorRawValidBufferRect: {{%g, %g}, {%g, %g}}"
- "<<<< CameraColorProcessing >>>> %s: normalizedValidBufferRect: {{%g, %g}, {%g, %g}}"
- "<<<< CameraColorProcessing >>>> %s: totalSensorCropRectRawCoords: {{%g, %g}, {%g, %g}}"
- "<<<< CameraColorProcessing >>>> %s: validBufferRect: {{%g, %g}, {%g, %g}}"
- "<<<< CameraColorProcessing >>>> Fig"
- "<<<< LTMAlgorithm >>>> %s: Fail to extract metadata for LTM calculation"
- "<<<< LTMAlgorithmV1 >>>> %s: Fail to process LTM compute"
- "<<<< LTMAlgorithmV1 >>>> %s: Fail to process LTM compute for HLG"
- "<<<< LTMAlgorithmV1 >>>> %s: Fail to process LTM driver"
- "<<<< LTMAlgorithmV2 >>>> %s: Fail to process LTM compute"
- "<<<< LTMAlgorithmV2 >>>> %s: Fail to process LTM compute for HLG"
- "<<<< LTMAlgorithmV2 >>>> %s: Fail to process LTM driver"
- "AWB statistics process failed"
- "FigCFDictionaryGetCGRectIfPresent( (__bridge CFDictionaryRef)metadata, kFigCaptureStreamMetadata_TotalSensorCropRect, &totalSensorCropRectRawCoords )"
- "GeometryUtilities.mm"
- "angleInfoRoll"
- "angleInfoRoll is NULL"
- "hasEyeCovering"
- "hasFaceMask"
- "kCMBaseObjectError_AllocationFailed"
- "kCMBaseObjectError_ParamErr"
- "kCMBaseObjectError_UnsupportedOperation"
- "kCMBaseObjectError_UnsupportedVersion"
- "kCMBaseObjectError_ValueNotAvailable"
- "unagi_trace"
```
