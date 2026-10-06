## NRFV4

> `/System/Library/VideoProcessors/NRFV4.bundle/NRFV4`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d16c8` | `0x2d6e08` | **`+0x5740`** |
| `__TEXT.__oslogstring` | `0x430d6` | `0x4424f` | **`+0x1179`** |
| `__AUTH_CONST.__objc_const` | `0x394f0` | `0x3a068` | **`+0xb78`** |
| `__TEXT.__cstring` | `0x5c956` | `0x5d201` | **`+0x8ab`** |
| `__AUTH_CONST.__cfstring` | `0x137e0` | `0x13a40` | **`+0x260`** |
| `__TEXT.__objc_methlist` | `0x126c8` | `0x128e8` | **`+0x220`** |
| `__DATA.__objc_ivar` | `0x3c84` | `0x3db4` | **`+0x130`** |
| `__DATA_CONST.__objc_selrefs` | `0x6b10` | `0x6c20` | **`+0x110`** |
| `__AUTH.__objc_data` | `0x9b0` | `0xa50` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x1498` | `0x14e8` | **`+0x50`** |
| `__TEXT.__const` | `0x103168` | `0x1031a8` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x960` | `0x980` | **`+0x20`** |
| `__DATA.__common` | `0x30` | `0x50` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x55f8` | `0x55e0` | **`-0x18`** |
| `__DATA.__bss` | `0x14` | `0x28` | **`+0x14`** |
| `__AUTH_CONST.__objc_floatobj` | `0x80` | `0x90` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xdf0` | `0xe00` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1ccc` | `0x1cd8` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x860` | `0x868` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xac8` | `0xad0` | **`+0x8`** |

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3

-  Functions: 15204
-  Symbols:   14244
-  CStrings:  13880
+  Functions: 15301
+  Symbols:   14397
+  CStrings:  13983
Symbols:
+ -[CMITiledInferenceProcessorTilePipelineStage(RawNightModeDenoiseInference) initRawNightModeDenoiseInferenceWithMetalContext:networkPath:skipInference:error:]
+ -[FlareMitigation prepareForProcessingWithAsyncEnabled:queue:]
+ -[FlareMitigationNetworkParameters crossTalkFlareMapBin]
+ -[FlareMitigationNetworkParameters frameGain]
+ -[FlareMitigationNetworkParameters gateConfig]
+ -[FlareMitigationNetworkParameters overFracBuffer]
+ -[FlareMitigationNetworkParameters setCrossTalkFlareMapBin:]
+ -[FlareMitigationNetworkParameters setFrameGain:]
+ -[FlareMitigationNetworkParameters setGateConfig:]
+ -[FlareMitigationNetworkParameters setOverFracBuffer:]
+ -[FlareMitigationNetworkStage computeBinnedCrossTalkFlareMap:withConfig:]
+ -[FlareMitigationNetworkStage computeRatioAndDiffMaps:binnedFPDiff:withConfig:]
+ -[H13FastAWB configForInputFrame:bounds:updatedMetadata:processingOptions:staticParameters:]
+ -[H13FastLTMStage purgeStageResources]
+ -[H13FastRawScaleStage prepareToProcessWithDescriptor:]
+ -[LearnedDemosaicNetworkStage _loadNetwork]
+ -[LearnedDemosaicNetworkStage initWithContext:cameraInfo:isQuadra:shareIntermediates:networkLoadQueue:]
+ -[LearnedDemosaicNetworkStage isQuadra]
+ -[LearnedDemosaicNetworkStage prepareNetworkIfNeededWithAsyncEnabled:]
+ -[LearnedDemosaicNetworkStage setIsQuadra:]
+ -[LearnedFusionMainFrame releaseRgbTex]
+ -[LearnedFusionNetworkStage _loadNetwork]
+ -[LearnedFusionNetworkStage initWithMetal:networkLoadQueue:]
+ -[LearnedFusionNetworkStage prepareNetworkIfNeededWithAsyncEnabled:]
+ -[NRFAsyncLoader .cxx_destruct]
+ -[NRFAsyncLoader initWithLabel:queue:asyncEnabled:]
+ -[NRFAsyncLoader startLoad:]
+ -[NRFAsyncLoader wait]
+ -[QuadraBinStage purgeStageResources]
+ -[RawNMReferenceFrameSelector processingType]
+ -[RawNMReferenceFrameSelector referenceFrameHasEVMinus]
+ -[RawNMReferenceFrameSelector setProcessingType:]
+ -[RawNMReferenceFrameSelector setReferenceFrameHasEVMinus:]
+ -[RawNMReferenceFrameSelector signalReferenceFrameFound:]
+ -[RawNightModeDenoiseInferenceCMITIPNetworkStage initWithMetalContext:networkPath:skipInference:error:]
+ -[RawNightModeDenoiseInferenceCMITIPNetworkStage skipInferenceEnabled]
+ -[RawNightModeDenoiseInferenceCMITIPPreStage _dispatchBypassWriteOnTile:tileStart:firstPix:commandBuffer:]
+ -[RawNightModeDenoiseInferenceCMITIPPreStage _dispatchInputCreationOnTile:tileStart:params:commandBuffer:]
+ -[RawNightModeDenoiseInferenceCMITIPPreStage bypassEnabled]
+ -[RawNightModeDenoiseInferenceCMITIPPreStage cleanReferenceTexture]
+ -[RawNightModeDenoiseInferenceCMITIPPreStage setBypassEnabled:]
+ -[RawNightModeDenoiseInferenceCMITIPPreStage setCleanReferenceTexture:]
+ -[RawNightModeDenoiseInferenceInputs cleanReferenceRGBTexture]
+ -[RawNightModeDenoiseInferenceInputs setCleanReferenceRGBTexture:]
+ -[RawNightModeProcessor _autoEnableDNRBypassIfNeeded]
+ -[RawNightModeProcessor reportFusionReferenceFrame:]
+ -[SRLv4Plist .cxx_destruct]
+ -[SRLv4Plist readPlist:]
+ -[SRLv4Plist resolveForGain:]
+ -[SoftISPPipeline prepareToProcessWithDescriptor:]
+ -[SoftISPPipeline purgeStageResources]
+ -[SoftISPProcessor tuningFlagForProcessingOption:key:tuningType:metadata:]
+ -[SoftISPStaticParameters tuningFlagForProcessingOption:key:tuningType:metadata:]
+ _NRFAsyncLoaderTrace
+ _OBJC_CLASS_$_CMIInferenceBypassResourceDescriptor
+ _OBJC_CLASS_$_NRFAsyncLoader
+ _OBJC_CLASS_$_SRLv4Plist
+ _OBJC_IVAR_$_FlareMitigation._loadResult
+ _OBJC_IVAR_$_FlareMitigation._loadStarted
+ _OBJC_IVAR_$_FlareMitigation._networkLoader
+ _OBJC_IVAR_$_FlareMitigation._networkReady
+ _OBJC_IVAR_$_FlareMitigationNetworkParameters._crossTalkFlareMapBin
+ _OBJC_IVAR_$_FlareMitigationNetworkParameters._frameGain
+ _OBJC_IVAR_$_FlareMitigationNetworkParameters._gateConfig
+ _OBJC_IVAR_$_FlareMitigationNetworkParameters._overFracBuffer
+ _OBJC_IVAR_$_FlareMitigationNetworkStage._computeBinnedCrossTalkFlareMapKernel
+ _OBJC_IVAR_$_FlareMitigationNetworkStage._focusPixelRatioAndDiffExtractionKernel
+ _OBJC_IVAR_$_FlareMitigationNetworkStage._focusPixelRatioAndDiffExtractionQuadraKernel
+ _OBJC_IVAR_$_FlareMitigationNetworkStage._postNetworkStage
+ _OBJC_IVAR_$_FlareMitigationNetworkStage._preNetworkStage
+ _OBJC_IVAR_$_FlareMitigationPostNetworkStage._computeOverCorrectionMetricsKernel
+ _OBJC_IVAR_$_FlareMitigationTuning.overCorrectionFractionThreshold
+ _OBJC_IVAR_$_FlareMitigationTuning.overCorrectionGatingAlphaFallback
+ _OBJC_IVAR_$_FlareMitigationTuning.overCorrectionGatingEnabled
+ _OBJC_IVAR_$_FlareMitigationTuning.overCorrectionGatingModelCoefA
+ _OBJC_IVAR_$_FlareMitigationTuning.overCorrectionGatingModelCoefB
+ _OBJC_IVAR_$_FlareMitigationTuning.overCorrectionGatingModelScaling
+ _OBJC_IVAR_$_FlareMitigationTuning.overCorrectionNOverThreshold
+ _OBJC_IVAR_$_FlareMitigationTuning.overCorrectionPerBinThreshold
+ _OBJC_IVAR_$_FlareMitigationTuning.overCorrectionPredGMaxFloor
+ _OBJC_IVAR_$_FlareMitigationTuning.overCorrectionPredGMaxThreshold
+ _OBJC_IVAR_$_GainMapShaders._MPPFlexRangeExtract
+ _OBJC_IVAR_$_LearnedDemosaicNetworkStage._networkLoader
+ _OBJC_IVAR_$_LearnedFusionNetworkStage._networkLoader
+ _OBJC_IVAR_$_LearnedFusionProcessor._networkLoadQueue
+ _OBJC_IVAR_$_NRFAsyncLoader._error
+ _OBJC_IVAR_$_NRFAsyncLoader._group
+ _OBJC_IVAR_$_NRFAsyncLoader._loadInFlight
+ _OBJC_IVAR_$_NRFAsyncLoader._queue
+ _OBJC_IVAR_$_RawNMReferenceFrameSelector._processingType
+ _OBJC_IVAR_$_RawNMReferenceFrameSelector._referenceFrameHasEVMinus
+ _OBJC_IVAR_$_RawNightModeDenoiseInferenceCMITIPNetworkStage._skipInference
+ _OBJC_IVAR_$_RawNightModeDenoiseInferenceCMITIPPreStage._bypassEnabled
+ _OBJC_IVAR_$_RawNightModeDenoiseInferenceCMITIPPreStage._bypassWriteOutputPipelineState
+ _OBJC_IVAR_$_RawNightModeDenoiseInferenceCMITIPPreStage._cleanReferenceTexture
+ _OBJC_IVAR_$_RawNightModeDenoiseInferenceInputs._cleanReferenceRGBTexture
+ _OBJC_IVAR_$_RawNightModeProcessor._dnrNetworkPath
+ _OBJC_IVAR_$_SRLv4Plist._maskThresholdT
+ _OBJC_IVAR_$_SRLv4Plist._maxBoostAdjustmentProxyT
+ _OBJC_IVAR_$_SRLv4Plist._maxBoostT_I
+ _OBJC_IVAR_$_SRLv4Plist._maxBoostT_II
+ _OBJC_IVAR_$_SRLv4Plist._maxBoostT_III
+ _OBJC_IVAR_$_SRLv4Plist._maxBoostT_IV
+ _OBJC_IVAR_$_SRLv4Plist._maxBoostT_V
+ _OBJC_IVAR_$_SRLv4Plist._maxBoostT_VI
+ _OBJC_IVAR_$_SRLv4Plist._maxTargetRatioDarkeningT
+ _OBJC_IVAR_$_SRLv4Plist.biasFactorSRLv2
+ _OBJC_IVAR_$_SRLv4Plist.faceExpDifThreshold
+ _OBJC_IVAR_$_SRLv4Plist.maskThreshold
+ _OBJC_IVAR_$_SRLv4Plist.matchPreview
+ _OBJC_IVAR_$_SRLv4Plist.maxBoostAdjustmentProxy
+ _OBJC_IVAR_$_SRLv4Plist.maxBoost_I
+ _OBJC_IVAR_$_SRLv4Plist.maxBoost_II
+ _OBJC_IVAR_$_SRLv4Plist.maxBoost_III
+ _OBJC_IVAR_$_SRLv4Plist.maxBoost_IV
+ _OBJC_IVAR_$_SRLv4Plist.maxBoost_V
+ _OBJC_IVAR_$_SRLv4Plist.maxBoost_VI
+ _OBJC_IVAR_$_SRLv4Plist.maxCurveBoost
+ _OBJC_IVAR_$_SRLv4Plist.maxTargetRatioDarkening
+ _OBJC_IVAR_$_SRLv4Plist.maxTargetRatioLimit_unused
+ _OBJC_IVAR_$_SRLv4Plist.minCurveBoost
+ _OBJC_IVAR_$_SRLv4Plist.minDarken_I
+ _OBJC_IVAR_$_SRLv4Plist.minDarken_II
+ _OBJC_IVAR_$_SRLv4Plist.minDarken_III
+ _OBJC_IVAR_$_SRLv4Plist.minDarken_IV
+ _OBJC_IVAR_$_SRLv4Plist.minDarken_V
+ _OBJC_IVAR_$_SRLv4Plist.minDarken_VI
+ _OBJC_IVAR_$_SRLv4Plist.minFaceSize
+ _OBJC_IVAR_$_SRLv4Plist.relightOnlyPersonMask
+ _OBJC_IVAR_$_SRLv4Plist.targetMedian_I
+ _OBJC_IVAR_$_SRLv4Plist.targetMedian_II
+ _OBJC_IVAR_$_SRLv4Plist.targetMedian_III
+ _OBJC_IVAR_$_SRLv4Plist.targetMedian_IV
+ _OBJC_IVAR_$_SRLv4Plist.targetMedian_V
+ _OBJC_IVAR_$_SRLv4Plist.targetMedian_VI
+ _OBJC_IVAR_$_SRLv4Plist.toneSimilaritySigma
+ _OBJC_METACLASS_$_NRFAsyncLoader
+ _OBJC_METACLASS_$_SRLv4Plist
+ _OUTLINED_FUNCTION_135
+ _OUTLINED_FUNCTION_136
+ _OUTLINED_FUNCTION_137
+ _OUTLINED_FUNCTION_138
+ _OUTLINED_FUNCTION_139
+ _OUTLINED_FUNCTION_140
+ __OBJC_$_INSTANCE_METHODS_NRFAsyncLoader
+ __OBJC_$_INSTANCE_METHODS_SRLv4Plist
+ __OBJC_$_INSTANCE_VARIABLES_NRFAsyncLoader
+ __OBJC_$_INSTANCE_VARIABLES_SRLv4Plist
+ __OBJC_$_PROP_LIST_RawNightModeDenoiseInferenceCMITIPNetworkStage
+ __OBJC_CLASS_RO_$_NRFAsyncLoader
+ __OBJC_CLASS_RO_$_SRLv4Plist
+ __OBJC_METACLASS_RO_$_NRFAsyncLoader
+ __OBJC_METACLASS_RO_$_SRLv4Plist
+ ___28-[NRFAsyncLoader startLoad:]_block_invoke
+ ___55-[H13FastRawScaleStage prepareToProcessWithDescriptor:]_block_invoke
+ ___62-[FlareMitigation prepareForProcessingWithAsyncEnabled:queue:]_block_invoke
+ ___68-[LearnedFusionNetworkStage prepareNetworkIfNeededWithAsyncEnabled:]_block_invoke
+ ___70-[LearnedDemosaicNetworkStage prepareNetworkIfNeededWithAsyncEnabled:]_block_invoke
+ ___block_descriptor_40_e8_32s_e5_i8?0ls32l8
+ ___block_descriptor_48_e8_32s40bs_e5_v8?0ls32l8s40l8
+ __supportsDefectPixelCorrectionForFrame
+ _determineFPConfig
+ _dispatch_group_async
+ _kFigCaptureStreamMetadata_Fnumber
+ _prepareToProcessWithDescriptor:.fmLoadQueue
+ _prepareToProcessWithDescriptor:.onceToken
+ _srlv4GainArray
- +[FlareMitigation prewarmShaders:]
- +[FlareMitigationNetworkStage prewarmShaders:]
- -[CMITiledInferenceProcessorTilePipelineStage(RawNightModeDenoiseInference) initRawNightModeDenoiseInferenceWithMetalContext:networkPath:error:]
- -[FlareMitigationNetworkStage computeRatioMaps:withConfig:]
- -[H13FastAWB configForInputFrame:bounds:processingOptions:staticParameters:]
- -[LearnedDemosaicNetworkStage _prepareNetworkIfNeeded]
- -[LearnedDemosaicNetworkStage initWithContext:cameraInfo:isQuadra:shareIntermediates:]
- -[LearnedFusionNetworkStage initWithMetal:]
- -[LearnedFusionNetworkStage prepareNetworkIfNeeded]
- _OBJC_IVAR_$_FlareMitigationNetworkStage._focusPixelRatioExtractionKernel
- _OBJC_IVAR_$_FlareMitigationNetworkStage._focusPixelRatioExtractionQuadraKernel
- _OBJC_IVAR_$_H13FastRawScaleStage._flareMitigationPrepared
- __OBJC_$_CLASS_METHODS_FlareMitigation
- __OBJC_$_CLASS_METHODS_FlareMitigationNetworkStage
CStrings:
+ "! onR"
+ "! sensorHasFocusPixels || ( validLayout && ( focusShape == 1 || focusShape == 2 ) )"
+ "%@-%@"
+ "( ! applySemanticSpatialCCM ) || ( ( skinMask != ((void *)0) ) == applySemanticSpatialCCM )"
+ "( ! applySkinColorMitigationCCM ) || ( ( skinMask != ((void *)0) ) == applySkinColorMitigationCCM )"
+ ")"
+ "-[CMITiledInferenceProcessorTilePipelineStage(RawNightModeDenoiseInference) initRawNightModeDenoiseInferenceWithMetalContext:networkPath:skipInference:error:]"
+ "-[FlareMitigation prepareForProcessingWithAsyncEnabled:queue:]"
+ "-[FlareMitigationNetworkStage computeBinnedCrossTalkFlareMap:withConfig:]"
+ "-[FlareMitigationNetworkStage computeRatioAndDiffMaps:binnedFPDiff:withConfig:]"
+ "-[H13FastAWB configForInputFrame:bounds:updatedMetadata:processingOptions:staticParameters:]"
+ "-[LearnedDemosaicNetworkStage _loadNetwork]"
+ "-[LearnedDemosaicNetworkStage initWithContext:cameraInfo:isQuadra:shareIntermediates:networkLoadQueue:]"
+ "-[LearnedDemosaicNetworkStage prepareNetworkIfNeededWithAsyncEnabled:]"
+ "-[LearnedFusionNetworkStage _loadNetwork]"
+ "-[LearnedFusionNetworkStage initWithMetal:networkLoadQueue:]"
+ "-[LearnedFusionNetworkStage prepareNetworkIfNeededWithAsyncEnabled:]"
+ "-[NRFAsyncLoader startLoad:]"
+ "-[NRFAsyncLoader wait]"
+ "-[RawNightModeDenoiseInferenceCMITIPNetworkStage initWithMetalContext:networkPath:skipInference:error:]"
+ "-[RawNightModeDenoiseInferenceCMITIPPreStage _dispatchBypassWriteOnTile:tileStart:firstPix:commandBuffer:]"
+ "-[RawNightModeDenoiseInferenceCMITIPPreStage _dispatchInputCreationOnTile:tileStart:params:commandBuffer:]"
+ "-[SoftISPPipeline prepareToProcessWithDescriptor:]"
+ "-[SoftISPStaticParameters tuningFlagForProcessingOption:key:tuningType:metadata:]"
+ "<<<< LearnedDemosaicNetworkStage >>>> %s: Invalid networkModel format (expected v<major>[.<minor>]): %@"
+ "<<<< LearnedDemosaicNetworkStage >>>> %s: LearnedDemosaic network load kicked off (model: %@, async=%d)"
+ "<<<< LearnedDemosaicNetworkStage >>>> %s: Per-frame isQuadra (%d) disagrees with prepareToProcess value (%d); demosaic network will reload"
+ "<<<< LearnedDemosaicNetworkStage >>>> %s: Unable to resolve network path for model %@"
+ "<<<< LearnedDemosaicNetworkStage >>>> %s: _networkLoader nil"
+ "<<<< LearnedDemosaicNetworkStage >>>> %s: _networkModel nil; tuning plist must specify NetworkModel"
+ "<<<< LearnedDemosaicNetworkStage >>>> %s: prepareNetworkIfNeeded(sync) inside runDemosaic failed (%d)"
+ "<<<< LearnedDemosaicNetworkStage >>>> %s: startLoad failed (%d)"
+ "<<<< LearnedDemosaicNetworkStage >>>> %s: waitForAsyncLoadIfNeeded (post-load) failed (%d)"
+ "<<<< LearnedDemosaicNetworkStage >>>> %s: waitForAsyncLoadIfNeeded (pre-check) failed (%d)"
+ "<<<< LearnedFusionNetworkStage >>>> %s: Invalid networkModel format (expected v<major>[.<minor>]): %@"
+ "<<<< LearnedFusionNetworkStage >>>> %s: _networkLoader nil"
+ "<<<< LearnedFusionNetworkStage >>>> %s: _tuningParams nil"
+ "<<<< LearnedFusionNetworkStage >>>> %s: _tuningParams->networkModel nil; tuning plist must specify NetworkModel"
+ "<<<< LearnedFusionNetworkStage >>>> %s: prepareNetworkIfNeeded(sync) inside runLearnedFusion failed (%d)"
+ "<<<< LearnedFusionNetworkStage >>>> %s: startLoad failed (%d)"
+ "<<<< LearnedFusionNetworkStage >>>> %s: waitForAsyncLoadIfNeeded (post-load) failed (%d)"
+ "<<<< LearnedFusionNetworkStage >>>> %s: waitForAsyncLoadIfNeeded (pre-check) failed (%d)"
+ "<<<< LearnedFusionProcessor >>>> %s: %{private}@ Processor process: processingType (%{public}d), fusionMode (%{public}d, %{public}s): %{private}s(errCode=%{public}d)"
+ "<<<< LearnedFusionProcessor >>>> %s: LearnedDemosaic (background) prepareNetworkIfNeededWithAsyncEnabled:YES failed (%d)"
+ "<<<< LearnedFusionProcessor >>>> %s: LearnedDemosaic prepareNetworkIfNeededWithAsyncEnabled:YES failed (%d)"
+ "<<<< LearnedFusionProcessor >>>> %s: LearnedFusion prepareNetworkIfNeededWithAsyncEnabled:YES failed (%d)"
+ "<<<< LearnedFusionProcessor >>>> %s: Running async demosaic: addFrame#%d, uniqueFrameId=%d, tuning=%s, defectCorrection=%d"
+ "<<<< LearnedFusionProcessor >>>> %s: _networkLoadQueue nil"
+ "<<<< LearnedFusionProcessor >>>> %s: desc.sensorID nil; cannot resolve tuning for preload"
+ "<<<< LearnedFusionProcessor >>>> %s: no tuning for sensorID %@ (have keys: %@)"
+ "<<<< LearnedFusionProcessor >>>> %s: nrfPlist nil for sensorID=%@ tuningMode=%@ lfType=%@ (processingMode=%d)"
+ "<<<< LearnedFusionProcessor >>>> %s: prepareToProcess: kicking off async network loads (sensorID=%@, isQuadra=%d, demosaic=%@, fusion=%@)"
+ "<<<< LearnedFusionProcessor >>>> %s: processingMode not set before prepareToProcess"
+ "<<<< LearnedFusionProcessor >>>> %s: quadraLearnedDemosaicTuning->networkModel nil"
+ "<<<< LearnedFusionProcessor >>>> %s: quadraLearnedFusionTuning->ev0RefMode->networkModel nil"
+ "<<<< NRFAsyncLoader >>>> %s: NRFAsyncLoader: startLoad: called while a previous load is still in flight; new load skipped"
+ "<<<< NRFAsyncLoader >>>> %s: NRFAsyncLoader: timed out after 10s waiting for async load to finish"
+ "<<<< RawNightMode >>>> %s: Failed to parse defringing tuning"
+ "<<<< RawNightModeDenoiseNetworkStage >>>> %s: RawNightMode denoise: skipInference enabled — pre stage will dispatch a client-driven bypass kernel writing the faked inference output to nextNetwork.outputs[0]."
+ "<<<< RawNightModeDenoiseNetworkStage >>>> %s: skipInference input descriptor must be a CMIInferenceBypassResourceDescriptor (got %s)"
+ "<<<< RawNightModeDenoisePreStage >>>> %s: bypassEncoder is nil"
+ "<<<< RawNightModeDenoisePreStage >>>> %s: nil bypass output tile"
+ "<<<< RawNightModeDenoisePreStage >>>> %s: nil networkInputTile"
+ "<<<< RawNightModeDenoiseTilePipeline >>>> %s: RawNightMode denoise bypass: tile dims = %lux%lu (bundle native; CFPref overrides %ld/%ld)"
+ "<<<< RawNightModeDenoiseTilePipeline >>>> %s: introspected network has no input/output ports"
+ "<<<< RawNightModeDenoiseTilePipeline >>>> %s: shape introspection load failed (%d) for %@"
+ "<<<< SoftISP >>>> %s: Cross-talk flare map computation completed (patternCount=%u)"
+ "<<<< SoftISP >>>> %s: Failed to allocate post-network stage"
+ "<<<< SoftISP >>>> %s: Failed to allocate pre-network stage"
+ "<<<< SoftISP >>>> %s: Failed to load computeBinnedCrossTalkFlareMap kernel"
+ "<<<< SoftISP >>>> %s: Failed to load computeOverCorrectionMetrics kernel"
+ "<<<< SoftISP >>>> %s: Failed to load focusPixelRatioAndDiffExtraction kernel"
+ "<<<< SoftISP >>>> %s: Failed to load focusPixelRatioAndDiffExtractionQuadra kernel"
+ "<<<< SoftISP >>>> %s: FlareMitigation gating params: gating=%d, fNumber=%.2f, alpha=%.3f, predGMaxThd=%.2f, fractionThd=%.2f, nOverThd=%u, overPerBinThd=%.3f, predGMaxFloor=%.2f"
+ "<<<< SoftISP >>>> %s: FlareMitigation network load kicked off (async=%d)"
+ "<<<< SoftISP >>>> %s: FlareMitigation: isSIFR=%d, frameGain=%.2f"
+ "<<<< SoftISP >>>> %s: Post-stage: Dispatched kernel for %dx%d pixels, correctionStrength = %f, gating=%d"
+ "<<<< SoftISP >>>> %s: Ratio + diff map computation completed"
+ "<<<< SoftISP >>>> %s: _networkLoader initialized (async=%d)"
+ "<<<< ToneMappingStage >>>> %s: applySemanticSpatialCCM but no skin mask available - will fall back to legacy grid correction"
+ "<<<< ToneMappingStage >>>> %s: applySkinColorMitigationCCM but no skin mask available - unable to run the correction!"
+ "DraftDemosaicApplyGDC"
+ "Expecting hf20, 420f or 420v format for RawNightMode output pixelBuffer."
+ "Expecting hf20, 420f or 420v output."
+ "Failed to allocate binnedFPDiff"
+ "Failed to allocate crossTalkFlareMapBin"
+ "Failed to allocate diffMap"
+ "Failed to allocate overFracBuffer"
+ "Failed to find flare mitigation network; workaround: set 'defaults write com.apple.coremedia softisp.flareMitigation.enabled 0' to skip flare mitigation"
+ "FlareMitigation::computeBinnedCrossTalkFlareMap"
+ "FlareMitigation::computeOverCorrectionMetrics"
+ "FlareMitigation::focusPixelRatioAndDiffExtraction"
+ "FlareMitigation::focusPixelRatioAndDiffExtractionQuadra"
+ "H pair required for cross_talk flare map"
+ "LastShownBuild:RawNightModeProcessorV4.m:820"
+ "LastShownDate:RawNightModeProcessorV4.m:820"
+ "MPPFlexRangeExtract"
+ "MaxBoostAdjustmentProxy"
+ "NightModeDenoise:bypassWriteOutput"
+ "RawNightModeDenoiseCMITIP::bypassWriteOutputTileKernel"
+ "Sensor has no focus pixels"
+ "Unsupported FP CFA layout"
+ "Unsupported NRF Processing type"
+ "[rawInputDesc isKindOfClass:[CMIInferenceBypassResourceDescriptor class]]"
+ "_MPPFlexRangeExtract"
+ "_bypassWriteOutputPipelineState"
+ "_computeBinnedCrossTalkFlareMapKernel"
+ "_computeOverCorrectionMetricsKernel"
+ "_focusPixelRatioAndDiffExtractionKernel"
+ "_focusPixelRatioAndDiffExtractionQuadraKernel"
+ "_networkParameters.overFracBuffer"
+ "_postNetworkStage"
+ "_preNetworkStage"
+ "async=YES requires non-nil queue"
+ "binnedFPDiff"
+ "binnedFPDiff is NULL"
+ "binnedFPDiff[i]"
+ "binnedFPDiff_%@"
+ "bypassEncoder"
+ "bypassOutputTile"
+ "com.apple.coremedia.softisp.flareMitigation.load"
+ "com.apple.coremedia.softisp.flareMitigation.preload"
+ "com.apple.learned-demosaic-network-load"
+ "com.apple.learned-fusion-network-load"
+ "com.apple.lf.network-load"
+ "crossTalkBin"
+ "crossTalkFlareMapBin"
+ "diffMap"
+ "diffMap_%@"
+ "i8@?0"
+ "kSoftISPProcessorError_NetworkNotFound"
+ "layoutType != ((void *)0)"
+ "learnedfusion_demosaic_bayer"
+ "learnedfusion_demosaic_quadra"
+ "learnedfusion_fusion"
+ "long"
+ "networkInputThumbnail"
+ "networkInputThumbnail is NULL"
+ "otherEV0"
+ "overCorrectionFractionThreshold"
+ "overCorrectionGatingAlphaFallback"
+ "overCorrectionGatingEnabled"
+ "overCorrectionGatingModelCoefA"
+ "overCorrectionGatingModelCoefB"
+ "overCorrectionGatingModelScaling"
+ "overCorrectionNOverThreshold"
+ "overCorrectionPerBinThreshold"
+ "overCorrectionPredGMaxFloor"
+ "overCorrectionPredGMaxThreshold"
+ "rawnm.denoise_skip_inference"
+ "refEV0"
+ "sensorHasFocusPixels"
+ "softisp.flareMitigation.asyncPreload"
+ "v%@(?:\\.\\d+(?:\\.\\d+)?o?)?"
+ "v%@\\.%@(?:\\.\\d+)?o?"
+ "validLayout && ( onR ^ onG ^ onB )"
+ "\xf0\xf0\xf0q"
+ "\xf9"
- "! sensorHasFocusPixels || focusShape == 1 || focusShape == 2"
- "("
- "+[FlareMitigationNetworkStage prewarmShaders:]"
- "-[CMITiledInferenceProcessorTilePipelineStage(RawNightModeDenoiseInference) initRawNightModeDenoiseInferenceWithMetalContext:networkPath:error:]"
- "-[FlareMitigationNetworkStage computeRatioMaps:withConfig:]"
- "-[H13FastAWB configForInputFrame:bounds:processingOptions:staticParameters:]"
- "-[LearnedDemosaicNetworkStage _prepareNetworkIfNeeded]"
- "-[LearnedDemosaicNetworkStage initWithContext:cameraInfo:isQuadra:shareIntermediates:]"
- "-[LearnedFusionNetworkStage initWithMetal:]"
- "-[LearnedFusionNetworkStage prepareNetworkIfNeeded]"
- "-[RawNightModeDenoiseInferenceCMITIPNetworkStage initWithMetalContext:networkPath:error:]"
- "-[SoftISPStaticParameters tuningFlagForProcessingOption:tuningType:metadata:]"
- "<<<< LearnedDemosaicNetworkStage >>>> %s: LF Demosaic switched network to model %@"
- "<<<< LearnedDemosaicNetworkStage >>>> %s: setupNetwork failed, bailing (%d)"
- "<<<< LearnedFusionNetworkStage >>>> %s: setupNetwork failed, bailing (%d)"
- "<<<< LearnedFusionProcessor >>>> %s: %{private}@ Processor process: processingType (%{public}d): %{private}s(errCode=%{public}d)"
- "<<<< LearnedFusionProcessor >>>> %s: _nrfPlist is nil"
- "<<<< LearnedFusionProcessor >>>> %s: _nrfPlist->quadraLearnedFusionTuning->ev0RefMode is nil"
- "<<<< LearnedFusionProcessor >>>> %s: prepareNetworkIfNeeded failed (%d)"
- "<<<< RawNightModeDenoisePreStage >>>> %s: nil outputTileTex"
- "<<<< SoftISP >>>> %s: Failed to load focusPixelRatioExtraction kernel"
- "<<<< SoftISP >>>> %s: Failed to load focusPixelRatioExtractionQuadra kernel"
- "<<<< SoftISP >>>> %s: Post-stage: Dispatched kernel for %dx%d pixels, correctionStrength = %f"
- "<<<< SoftISP >>>> %s: Ratio map computation completed"
- "ApplyGDC"
- "DraftDemosaic"
- "Expecting HF20 format or 420p for RawNightMode output pixelBuffer."
- "Expecting HF20 or 420p output."
- "Failed to find flare mitigation network path"
- "Failed to find focusPixelCFAComp in tuning parameters"
- "Failed to prewarm network stage"
- "Failed to prewarm post-stage"
- "Failed to prewarm pre-stage"
- "FlareMitigation::focusPixelRatioExtraction"
- "FlareMitigation::focusPixelRatioExtractionQuadra"
- "LastShownBuild:RawNightModeProcessorV4.m:796"
- "LastShownDate:RawNightModeProcessorV4.m:796"
- "RegWarpParameters"
- "Warning: DraftDemosaic is missing; using default value"
- "Warning: DraftDemosaic::ApplyGDC is missing; using default value"
- "_focusPixelRatioExtractionKernel"
- "_focusPixelRatioExtractionQuadraKernel"
- "focusPixelCFAComponent"
- "isFullyShieldedFP"
- "kSoftISPProcessorError_SynthThumbnailFocusPixelConfigInvalid"
- "learnedfusion_demosaic_bayer-v%@(?:\\.%@)?"
- "learnedfusion_demosaic_quadra-v%@(?:\\.%@)?"
- "learnedfusion_fusion-v%@(?:\\.%@)?"
- "postStage"
- "preStage"
- "stage.postInferenceStage"
- "stage.postInferenceStage is NULL"
- "stage.preInferenceStage"
- "stage.preInferenceStage is NULL"
- "\xf0\xf0\xf0\xf0\xe1"
```
