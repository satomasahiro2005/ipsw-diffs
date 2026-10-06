## PhotoImaging

> `/System/Library/PrivateFrameworks/PhotoImaging.framework/PhotoImaging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27cc3c` | `0x29bdd0` | **`+0x1f194`** |
| `__TEXT.__cstring` | `0x46f77` | `0x4a6de` | **`+0x3767`** |
| `__AUTH_CONST.__cfstring` | `0x26e40` | `0x29bc0` | **`+0x2d80`** |
| `__AUTH_CONST.__objc_const` | `0x286f0` | `0x29ad0` | **`+0x13e0`** |
| `__TEXT.__oslogstring` | `0x6cef` | `0x7d58` | **`+0x1069`** |
| `__TEXT.__objc_methlist` | `0x165e0` | `0x173c8` | **`+0xde8`** |
| `__DATA_CONST.__objc_selrefs` | `0xb5d0` | `0xbca0` | **`+0x6d0`** |
| `__AUTH.__objc_data` | `0x378` | `0x968` | **`+0x5f0`** |
| `__DATA.__bss` | `0x1600` | `0x1a80` | **`+0x480`** |
| `__DATA_CONST.__objc_arraydata` | `0x9350` | `0x9718` | **`+0x3c8`** |
| `__TEXT.__unwind_info` | `0x5898` | `0x5c58` | **`+0x3c0`** |
| `__DATA_CONST.__const` | `0x4128` | `0x44d0` | **`+0x3a8`** |
| `__TEXT.__gcc_except_tab` | `0x4b6c` | `0x4ee0` | **`+0x374`** |
| `__AUTH_CONST.__const` | `0x5320` | `0x5648` | **`+0x328`** |
| `__TEXT.__const` | `0x8a7c` | `0x8d04` | **`+0x288`** |
| `__DATA_CONST.__got` | `0x25c0` | `0x2830` | **`+0x270`** |
| `__AUTH_CONST.__objc_intobj` | `0x1488` | `0x1668` | **`+0x1e0`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x558` | `0x6c0` | **`+0x168`** |
| `__AUTH_CONST.__objc_dictobj` | `0x5b18` | `0x5c58` | **`+0x140`** |
| `__DATA.__data` | `0x16f0` | `0x17f8` | **`+0x108`** |
| `__DATA_DIRTY.__objc_data` | `0xa7a0` | `0xa890` | **`+0xf0`** |
| `__DATA_CONST.__objc_classlist` | `0x10f0` | `0x11a0` | **`+0xb0`** |
| `__DATA.__objc_ivar` | `0x1594` | `0x1600` | **`+0x6c`** |
| `__TEXT.__eh_frame` | `0x9f0` | `0xa50` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `0x48` | `0x90` | **`+0x48`** |
| `__DATA_CONST.__objc_superrefs` | `0x710` | `0x750` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x299` | `0x2d8` | **`+0x3f`** |
| `__TEXT.__swift5_proto` | `0x7c` | `0xa0` | **`+0x24`** |
| `__TEXT.__constg_swiftt` | `0x210` | `0x230` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x3b8` | `0x3d4` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0x64` | `0x78` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x14f8` | `0x1508` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x190` | `0x1a0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x34` | `0x38` | **`+0x4`** |

### Other Changes

```diff

-912.0.234.0.0
+912.0.235.0.0

-  Functions: 9139
-  Symbols:   15832
-  CStrings:  7103
+  Functions: 9495
+  Symbols:   16415
+  CStrings:  7578
Symbols:
+ +[PICinematicVideoComputeDisparityGenerator usingSharedDisparityProviderForQuality:size:globalRenderingMetadata:perform:error:]
+ +[PICinematicVideoRefinementProcessor requiredPreRollDuration]
+ +[PICinematicVideoTimedFocusDisparityProcessor usingSharedCinematographyScriptSnapshotForDictionaryRepresentation:perform:]
+ +[PIModularPhotosPipeline_v1 controlDataWithPortraitVideoV2Adjustment:]
+ +[PIPhotographicStyleLearnV2 addTextureStyleToPipeline:options:name:primaryInput:adjustmentInput:error:]
+ +[PIPhotographicStyleLearnV2 addTextureStyleToPipeline:options:name:primaryInput:adjustmentInput:linearThumbnailInput:error:]
+ +[PIPhotographicStyleLearnV2 addTextureStyleToPipeline:options:name:primaryInput:adjustmentInput:semanticStyleAdjustmentExpression:linearThumbnailInput:error:]
+ +[PIPhotographicStyleLearnV2 availableOptions]
+ +[PIPhotographicStyleLearnV2 identifier]
+ +[PIPhotographicStyleLearnV2 inputChannels:]
+ +[PIPhotosPipeline_v1 addPhotographicStyleApplyV2ToPipeline:options:primaryInput:styleInput:adjustmentInput:assetMedia:error:]
+ +[PIPhotosPipeline_v1 addPhotographicStyleLearnV2ToPipeline:options:primaryInput:adjustmentInput:assetMedia:error:]
+ +[PIPhotosPipeline_v1 connectPhotographicStyleV2ToPipeline:name:primaryInput:adjustmentInput:assetMedia:isVideo:]
+ +[PISchema textureStyleSchema]
+ +[PITextureStyle adjustmentDescriptor]
+ +[PITextureStyle adjustmentFormat]
+ +[PITextureStyle availableOptions]
+ +[PITextureStyle identifier]
+ +[PITextureStyleAdjustmentController allPresets]
+ +[PITextureStyleAdjustmentController grainIntensityKey]
+ +[PITextureStyleAdjustmentController intensityKey]
+ +[PITextureStyleAdjustmentController presetKey]
+ +[PITextureStyleAutoCalculator canRenderTextureStylesOnComposition:]
+ +[PITextureStylePipelineProcessor allowedEffectTypesForUsage:]
+ +[PITextureStylePipelineProcessor bloomConfiguration]
+ +[PITextureStylePipelineProcessor defaultTextureStyleDictionaryForCast:]
+ +[PITextureStylePipelineProcessor defaultTextureStyleDictionaryForPreset:]
+ +[PITextureStylePipelineProcessor diffusionConfiguration]
+ +[PITextureStylePipelineProcessor filmGrainConfiguration]
+ +[PITextureStylePipelineProcessor glowConfiguration]
+ +[PITextureStylePipelineProcessor halationConfiguration]
+ +[PITextureStylePipelineProcessor inputConfigurationForEffectType:isVideo:]
+ +[PITextureStylePipelineProcessor inputNames]
+ +[PITextureStylePipelineProcessor inputRequirementsForUsage:]
+ +[PITextureStylePipelineProcessor isAvailableForTesting]
+ +[PITextureStylePipelineProcessor isAvailable]
+ +[PITextureStylePipelineProcessor isUsageVideo:]
+ +[PITextureStylePipelineProcessor linearThumbnailChannel]
+ +[PITextureStylePipelineProcessor maskTypeFromIndex:]
+ +[PITextureStylePipelineProcessor mattifyConfiguration:]
+ +[PITextureStylePipelineProcessor personInstancesChannel]
+ +[PITextureStylePipelineProcessor semanticStyleCastChannel]
+ +[PITextureStylePipelineProcessor semanticStyleColorChannel]
+ +[PITextureStylePipelineProcessor skinSmoothingConfiguration:]
+ +[PITextureStylePipelineProcessor underEyeBrighteningConfiguration:]
+ +[PITextureStyleProcessorKernel allowPartialOutputRegion]
+ +[PITextureStyleProcessorKernel defaultEffectOrderForPreset:]
+ +[PITextureStyleProcessorKernel descriptorForBloomWithTuningDictionary:]
+ +[PITextureStyleProcessorKernel descriptorForDiffusionWithTuningDictionary:]
+ +[PITextureStyleProcessorKernel descriptorForEffectName:tuningDictionary:semanticStyleProperties:semanticStyleInfo:]
+ +[PITextureStyleProcessorKernel descriptorForFilmGrainWithTuningDictionary:semanticStyleInfo:]
+ +[PITextureStyleProcessorKernel descriptorForGlowWithTuningDictionary:semanticStyleProperties:semanticStyleInfo:]
+ +[PITextureStyleProcessorKernel descriptorForHalationWithTuningDictionary:semanticStyleInfo:]
+ +[PITextureStyleProcessorKernel descriptorForMattifyWithTuningDictionary:]
+ +[PITextureStyleProcessorKernel descriptorForSkinSmoothingWithTuningDictionary:]
+ +[PITextureStyleProcessorKernel descriptorForUnderEyeBrighteningWithTuningDictionary:]
+ +[PITextureStyleProcessorKernel effectDescriptorsForPreset:grainIntensity:tuningDictionary:usage:semanticStyleProperties:semanticStyleInfo:]
+ +[PITextureStyleProcessorKernel formatForInputAtIndex:arguments:]
+ +[PITextureStyleProcessorKernel outputFormat]
+ +[PITextureStyleProcessorKernel outputIsOpaque]
+ +[PITextureStyleProcessorKernel personInputDataFromStillProperties:]
+ +[PITextureStyleProcessorKernel personInputDataFromVideoProperties:effectDescriptors:]
+ +[PITextureStyleProcessorKernel processWithInputs:arguments:output:error:]
+ +[PITextureStyleProcessorKernel roiForInput:arguments:outputRect:]
+ +[PITextureStyleProcessorKernel roiTileArrayForInput:arguments:outputRect:]
+ +[PITextureStyleProcessorKernel synchronizeInputs]
+ +[PITextureStyleProcessorResource usingSharedProcessorWithUsage:isVideo:commandQueue:perform:]
+ +[_PISemanticStyleAdjustmentExpressionFunction adjustmentInfoDescriptor]
+ -[NUGlobalSettings(PIGlobalSettings) cinematicVideoUseRefinedCinematography]
+ -[NUGlobalSettings(PIGlobalSettings) debugEnableTextureStyleDump]
+ -[NUGlobalSettings(PIGlobalSettings) debugEnableTextureStyleTiledRendering]
+ -[NUGlobalSettings(PIGlobalSettings) debugTextureStyleDumpDirectory]
+ -[NUGlobalSettings(PIGlobalSettings) debugTextureStyleEnabledEffects]
+ -[NUGlobalSettings(PIGlobalSettings) enableCinematicEverywhere]
+ -[NUGlobalSettings(PIGlobalSettings) setCinematicVideoUseRefinedCinematography:]
+ -[NUGlobalSettings(PIGlobalSettings) setDebugEnableTextureStyleDump:]
+ -[NUGlobalSettings(PIGlobalSettings) setDebugEnableTextureStyleTiledRendering:]
+ -[NUGlobalSettings(PIGlobalSettings) setDebugTextureStyleDumpDirectory:]
+ -[NUGlobalSettings(PIGlobalSettings) setDebugTextureStyleEnabledEffects:]
+ -[NUGlobalSettings(PIGlobalSettings) setEnableCinematicEverywhere:]
+ -[PIAdjustmentConstants PITextureStyleAdjustmentKey]
+ -[PICinematicVideoAccumulatedStateProcessor .cxx_destruct]
+ -[PICinematicVideoAccumulatedStateProcessor accumulatedStateDescriptor]
+ -[PICinematicVideoAccumulatedStateProcessor computeDataWithInputs:settings:error:]
+ -[PICinematicVideoAccumulatedStateProcessor configurationWithInputGeometries:outputGeometry:settings:]
+ -[PICinematicVideoAccumulatedStateProcessor inputChannels]
+ -[PICinematicVideoAccumulatedStateProcessor needsTemporalState]
+ -[PICinematicVideoAccumulatedStateProcessor outputChannel]
+ -[PICinematicVideoAccumulatedStateProcessor pauseAndPersistentInternalStateWithConfiguration:error:]
+ -[PICinematicVideoAccumulatedStateProcessor prepareForConfiguration:controlData:error:]
+ -[PICinematicVideoAccumulatedStateProcessor resumeWithConfiguration:serializedState:controlData:error:]
+ -[PICinematicVideoAccumulatedStateProcessorConfiguration copyWithZone:]
+ -[PICinematicVideoAccumulatedStateProcessorConfiguration encodeWithCoder:]
+ -[PICinematicVideoAccumulatedStateProcessorConfiguration hash]
+ -[PICinematicVideoAccumulatedStateProcessorConfiguration initWithCoder:]
+ -[PICinematicVideoAccumulatedStateProcessorConfiguration isEqual:]
+ -[PICinematicVideoComputeDisparityGenerator .cxx_destruct]
+ -[PICinematicVideoComputeDisparityGenerator colorSpaceForInput:controlData:]
+ -[PICinematicVideoComputeDisparityGenerator computeDataWithInputs:settings:error:]
+ -[PICinematicVideoComputeDisparityGenerator configurationWithInputGeometries:outputGeometry:settings:]
+ -[PICinematicVideoComputeDisparityGenerator inputChannels]
+ -[PICinematicVideoComputeDisparityGenerator isInputChannelRequired:]
+ -[PICinematicVideoComputeDisparityGenerator needsTemporalState]
+ -[PICinematicVideoComputeDisparityGenerator outputChannel]
+ -[PICinematicVideoComputeDisparityGenerator pauseAndPersistentInternalStateWithConfiguration:error:]
+ -[PICinematicVideoComputeDisparityGenerator pixelFormatForInput:controlData:]
+ -[PICinematicVideoComputeDisparityGenerator prepareForConfiguration:controlData:error:]
+ -[PICinematicVideoComputeDisparityGenerator renderScaleForInput:geometry:outputScale:]
+ -[PICinematicVideoComputeDisparityGenerator resumeWithConfiguration:serializedState:controlData:error:]
+ -[PICinematicVideoDisparityCacheRetriever inputChannels]
+ -[PICinematicVideoDisparityCacheRetriever isInputChannelRequired:]
+ -[PICinematicVideoDisparityCacheRetriever outputChannel]
+ -[PICinematicVideoDisparityCacheRetriever outputGeometryWithInputGeometry:controlData:error:]
+ -[PICinematicVideoDisparityCacheRetriever outputImageWithSamples:controlData:error:]
+ -[PICinematicVideoDisparityCacheRetriever outputMetadataWithInputMetadata:settings:error:]
+ -[PICinematicVideoDisparityMaterializer inputChannels]
+ -[PICinematicVideoDisparityMaterializer isInputChannelRequired:]
+ -[PICinematicVideoDisparityMaterializer outputChannel]
+ -[PICinematicVideoDisparityMaterializer outputGeometryWithInputGeometry:controlData:error:]
+ -[PICinematicVideoDisparityMaterializer outputImageWithSamples:controlData:error:]
+ -[PICinematicVideoDisparityMaterializer outputMetadataWithInputMetadata:settings:error:]
+ -[PICinematicVideoFastFocusDisparityProcessor .cxx_destruct]
+ -[PICinematicVideoFastFocusDisparityProcessor _focusDisparityFromMetadataItems:disparityBuffer:renderTime:focusDisparity:error:]
+ -[PICinematicVideoFastFocusDisparityProcessor colorSpaceForInput:settings:]
+ -[PICinematicVideoFastFocusDisparityProcessor computeDataWithInputs:settings:error:]
+ -[PICinematicVideoFastFocusDisparityProcessor inputChannels]
+ -[PICinematicVideoFastFocusDisparityProcessor isInputChannelRequired:]
+ -[PICinematicVideoFastFocusDisparityProcessor outputChannel]
+ -[PICinematicVideoFastFocusDisparityProcessor pixelFormatForInput:settings:]
+ -[PICinematicVideoFastFocusDisparityProcessor renderScaleForInput:geometry:outputScale:]
+ -[PICinematicVideoRefinedFocusDisparityProcessor colorSpaceForInput:controlData:]
+ -[PICinematicVideoRefinedFocusDisparityProcessor computeDataWithInputs:settings:error:]
+ -[PICinematicVideoRefinedFocusDisparityProcessor inputChannels]
+ -[PICinematicVideoRefinedFocusDisparityProcessor isInputChannelRequired:]
+ -[PICinematicVideoRefinedFocusDisparityProcessor outputChannel]
+ -[PICinematicVideoRefinedFocusDisparityProcessor pixelFormatForInput:controlData:]
+ -[PICinematicVideoRefinedFocusDisparityProcessor renderScaleForInput:geometry:outputScale:]
+ -[PICinematicVideoRefinementProcessor .cxx_destruct]
+ -[PICinematicVideoRefinementProcessor accumulateAtTime:withInputs:settings:error:]
+ -[PICinematicVideoRefinementProcessor accumulatedDataWithSettings:error:]
+ -[PICinematicVideoRefinementProcessor accumulatedStateDescriptor]
+ -[PICinematicVideoRefinementProcessor accumulationTimeRangeForDuration:]
+ -[PICinematicVideoRefinementProcessor colorSpaceForInput:controlData:]
+ -[PICinematicVideoRefinementProcessor disparityBufferCache]
+ -[PICinematicVideoRefinementProcessor disparityProvider]
+ -[PICinematicVideoRefinementProcessor inputChannels]
+ -[PICinematicVideoRefinementProcessor inputSize]
+ -[PICinematicVideoRefinementProcessor isAccumulating]
+ -[PICinematicVideoRefinementProcessor isInitialized]
+ -[PICinematicVideoRefinementProcessor outputChannel]
+ -[PICinematicVideoRefinementProcessor pixelFormatForInput:controlData:]
+ -[PICinematicVideoRefinementProcessor refinement]
+ -[PICinematicVideoRefinementProcessor renderScaleForInput:geometry:outputScale:]
+ -[PICinematicVideoRefinementProcessor script]
+ -[PICinematicVideoRefinementProcessor setDisparityBufferCache:]
+ -[PICinematicVideoRefinementProcessor setDisparityProvider:]
+ -[PICinematicVideoRefinementProcessor setInputSize:]
+ -[PICinematicVideoRefinementProcessor setIsInitialized:]
+ -[PICinematicVideoRefinementProcessor setRefinement:]
+ -[PICinematicVideoRefinementProcessor setScript:]
+ -[PICinematicVideoTimedFocusDisparityProcessor .cxx_destruct]
+ -[PICinematicVideoTimedFocusDisparityProcessor colorSpaceForInput:settings:]
+ -[PICinematicVideoTimedFocusDisparityProcessor computeDataWithInputs:settings:error:]
+ -[PICinematicVideoTimedFocusDisparityProcessor configurationWithInputGeometries:outputGeometry:settings:]
+ -[PICinematicVideoTimedFocusDisparityProcessor inputChannels]
+ -[PICinematicVideoTimedFocusDisparityProcessor isInputChannelRequired:]
+ -[PICinematicVideoTimedFocusDisparityProcessor needsTemporalState]
+ -[PICinematicVideoTimedFocusDisparityProcessor outputChannel]
+ -[PICinematicVideoTimedFocusDisparityProcessor pauseAndPersistentInternalStateWithConfiguration:error:]
+ -[PICinematicVideoTimedFocusDisparityProcessor pixelFormatForInput:settings:]
+ -[PICinematicVideoTimedFocusDisparityProcessor prepareForConfiguration:controlData:error:]
+ -[PICinematicVideoTimedFocusDisparityProcessor renderScaleForInput:geometry:outputScale:]
+ -[PICinematicVideoTimedFocusDisparityProcessor resumeWithConfiguration:serializedState:controlData:error:]
+ -[PICinematicVideo_v2 _buildPreviewPipeline:primary:adjustment:cinematography:highQuality:error:]
+ -[PICinematicVideo_v2 _buildRefinedPipeline:primary:adjustment:cinematography:highQuality:error:]
+ -[PICompositionController(AdjustmentExtensions) modifyTextureStyleAdjustment:]
+ -[PICompositionController(AdjustmentExtensions) textureStyleAdjustmentController]
+ -[PICompositionExporterAuxiliaryOptions embedProvenanceData]
+ -[PICompositionExporterAuxiliaryOptions setEmbedProvenanceData:]
+ -[PICompositionExporterImageOptions embedProvenanceData]
+ -[PICompositionExporterImageOptions setEmbedProvenanceData:]
+ -[PICompositionExporterOptions cinematicVideoUseRefinedCinematography]
+ -[PICompositionExporterOptions enableCinematicEverywhere]
+ -[PIGlobalSettings cinematicVideoUseRefinedCinematography]
+ -[PIGlobalSettings enableCinematicEverywhere]
+ -[PIGlobalSettings setCinematicVideoUseRefinedCinematography:]
+ -[PIGlobalSettings setEnableCinematicEverywhere:]
+ -[PIPhotographicStyleApplyV2 _buildPipeline:error:]
+ -[PIPhotographicStyleApplyV2 buildPipeline:error:]
+ -[PIPhotographicStyleApplyV2 identifier]
+ -[PIPhotographicStyleApplyV2 inputChannels]
+ -[PIPhotographicStyleApplyV2 isVideo]
+ -[PIPhotographicStyleApplyV2 outputChannels]
+ -[PIPhotographicStyleLearnV2 buildPipeline:error:]
+ -[PIPhotographicStyleLearnV2 identifier]
+ -[PIPhotographicStyleLearnV2 inputChannels]
+ -[PIPhotographicStyleLearnV2 isVideo]
+ -[PIPhotographicStyleLearnV2 outputChannels]
+ -[PIPortraitVideoAdjustmentController cinematographySnapshot]
+ -[PIPortraitVideoAdjustmentController setCinematographySnapshot:]
+ -[PITextureStyle _buildTextureStylesPipeline:input:error:]
+ -[PITextureStyle buildPipeline:error:]
+ -[PITextureStyle identifier]
+ -[PITextureStyle inputChannels]
+ -[PITextureStyle isVideo]
+ -[PITextureStyle outputChannels]
+ -[PITextureStyle processorUsage]
+ -[PITextureStyleAdjustmentController _areValuesEquivalentBetween:and:nilEquivalentDefaultValue:]
+ -[PITextureStyleAdjustmentController grainIntensity]
+ -[PITextureStyleAdjustmentController intensity]
+ -[PITextureStyleAdjustmentController isSettingEqual:forKey:]
+ -[PITextureStyleAdjustmentController preset]
+ -[PITextureStyleAdjustmentController resetToUnstyledOriginal]
+ -[PITextureStyleAdjustmentController setGrainIntensity:]
+ -[PITextureStyleAdjustmentController setIntensity:]
+ -[PITextureStyleAdjustmentController setPreset:]
+ -[PITextureStyleAdjustmentController updateWithTextureStyleInfo:]
+ -[PITextureStyleAutoCalculator pipelineOutput]
+ -[PITextureStyleAutoCalculator processComputedData:error:]
+ -[PITextureStyleAutoCalculator submit:]
+ -[PITextureStylePipelineProcessor .cxx_destruct]
+ -[PITextureStylePipelineProcessor initWithUsage:]
+ -[PITextureStylePipelineProcessor init]
+ -[PITextureStylePipelineProcessor inputChannels]
+ -[PITextureStylePipelineProcessor isInputChannelRequired:]
+ -[PITextureStylePipelineProcessor isVideo]
+ -[PITextureStylePipelineProcessor outputImageWithSamples:controlData:error:]
+ -[PITextureStylePipelineProcessor renderScaleForInput:geometry:outputScale:]
+ -[PITextureStyleProcessorResource .cxx_destruct]
+ -[PITextureStyleProcessorResource createMemoryResource]
+ -[PITextureStyleProcessorResource dealloc]
+ -[PITextureStyleProcessorResource initWithUsage:metalCommandQueue:]
+ -[PITextureStyleProcessorResource matchesUsage:metalCommandQueue:]
+ -[PITextureStyleProcessorResource metalCommandQueue]
+ -[PITextureStyleProcessorResource processor]
+ -[PITextureStyleProcessorResource setupProcessor]
+ -[PITextureStyleProcessorResource usage]
+ -[PITextureStyleUsageInputConfiguration .cxx_destruct]
+ -[PITextureStyleUsageInputConfiguration debugDescription]
+ -[PITextureStyleUsageInputConfiguration initWithRequiredChannels:optionalChannels:personData:]
+ -[PITextureStyleUsageInputConfiguration isChannelRequired:]
+ -[PITextureStyleUsageInputConfiguration optionalChannelNames]
+ -[PITextureStyleUsageInputConfiguration optionalChannels]
+ -[PITextureStyleUsageInputConfiguration requiredChannelNames]
+ -[PITextureStyleUsageInputConfiguration requiredChannels]
+ -[PITextureStyleUsageInputConfiguration requiresPersonData]
+ -[_PICinematicVideoComputeDisparityGeneratorConfiguration copyWithZone:]
+ -[_PICinematicVideoComputeDisparityGeneratorConfiguration encodeWithCoder:]
+ -[_PICinematicVideoComputeDisparityGeneratorConfiguration hash]
+ -[_PICinematicVideoComputeDisparityGeneratorConfiguration initWithCoder:]
+ -[_PICinematicVideoComputeDisparityGeneratorConfiguration initWithSize:quality:]
+ -[_PICinematicVideoComputeDisparityGeneratorConfiguration isEqual:]
+ -[_PICinematicVideoComputeDisparityGeneratorConfiguration isEqualToConfiguration:]
+ -[_PICinematicVideoComputeDisparityGeneratorConfiguration quality]
+ -[_PICinematicVideoComputeDisparityGeneratorConfiguration size]
+ -[_PICinematicVideoTimedFocusDisparityProcessorConfiguration copyWithZone:]
+ -[_PICinematicVideoTimedFocusDisparityProcessorConfiguration encodeWithCoder:]
+ -[_PICinematicVideoTimedFocusDisparityProcessorConfiguration generation]
+ -[_PICinematicVideoTimedFocusDisparityProcessorConfiguration hash]
+ -[_PICinematicVideoTimedFocusDisparityProcessorConfiguration initWithCoder:]
+ -[_PICinematicVideoTimedFocusDisparityProcessorConfiguration initWithGeneration:]
+ -[_PICinematicVideoTimedFocusDisparityProcessorConfiguration isEqual:]
+ -[_PICinematicVideoTimedFocusDisparityProcessorConfiguration isEqualToConfiguration:]
+ -[_PISemanticStyleAdjustmentExpressionFunction evaluateWithArguments:error:]
+ -[_PISemanticStyleAdjustmentExpressionFunction format]
+ -[_PITextureStyleSettingsExpressionFunction evaluateWithArguments:error:]
+ -[_PITextureStyleSettingsExpressionFunction format]
+ GCC_except_table1108
+ GCC_except_table1710
+ GCC_except_table1724
+ GCC_except_table1893
+ GCC_except_table2069
+ GCC_except_table2223
+ GCC_except_table2239
+ GCC_except_table2247
+ GCC_except_table2254
+ GCC_except_table2262
+ GCC_except_table2340
+ GCC_except_table2380
+ GCC_except_table2409
+ GCC_except_table2414
+ GCC_except_table2429
+ GCC_except_table2445
+ GCC_except_table2456
+ GCC_except_table2543
+ GCC_except_table2778
+ GCC_except_table3131
+ GCC_except_table3136
+ GCC_except_table3170
+ GCC_except_table3172
+ GCC_except_table3173
+ GCC_except_table3175
+ GCC_except_table3177
+ GCC_except_table3179
+ GCC_except_table3185
+ GCC_except_table3190
+ GCC_except_table3199
+ GCC_except_table3294
+ GCC_except_table3363
+ GCC_except_table3364
+ GCC_except_table3473
+ GCC_except_table3515
+ GCC_except_table3523
+ GCC_except_table3575
+ GCC_except_table3790
+ GCC_except_table3909
+ GCC_except_table3919
+ GCC_except_table3922
+ GCC_except_table3923
+ GCC_except_table3935
+ GCC_except_table3982
+ GCC_except_table3991
+ GCC_except_table4019
+ GCC_except_table4042
+ GCC_except_table4272
+ GCC_except_table4445
+ GCC_except_table4531
+ GCC_except_table4634
+ GCC_except_table4658
+ GCC_except_table4662
+ GCC_except_table4781
+ GCC_except_table4819
+ GCC_except_table4825
+ GCC_except_table4827
+ GCC_except_table4851
+ GCC_except_table4873
+ GCC_except_table4977
+ GCC_except_table5034
+ GCC_except_table5074
+ GCC_except_table5226
+ GCC_except_table5249
+ GCC_except_table5256
+ GCC_except_table5259
+ GCC_except_table5270
+ GCC_except_table5277
+ GCC_except_table5424
+ GCC_except_table5516
+ GCC_except_table5577
+ GCC_except_table5580
+ GCC_except_table5592
+ GCC_except_table5593
+ GCC_except_table5597
+ GCC_except_table5598
+ GCC_except_table5599
+ GCC_except_table5604
+ GCC_except_table5612
+ GCC_except_table5705
+ GCC_except_table6093
+ GCC_except_table6112
+ GCC_except_table6113
+ GCC_except_table6119
+ GCC_except_table6124
+ GCC_except_table6176
+ GCC_except_table6181
+ GCC_except_table6182
+ GCC_except_table6192
+ GCC_except_table6194
+ GCC_except_table6218
+ GCC_except_table6220
+ GCC_except_table6221
+ GCC_except_table6222
+ GCC_except_table6224
+ GCC_except_table6226
+ GCC_except_table6228
+ GCC_except_table6231
+ GCC_except_table6234
+ GCC_except_table6236
+ GCC_except_table6237
+ GCC_except_table6238
+ GCC_except_table6239
+ GCC_except_table6241
+ GCC_except_table6246
+ GCC_except_table6279
+ GCC_except_table6382
+ GCC_except_table6385
+ GCC_except_table6451
+ GCC_except_table6525
+ GCC_except_table6847
+ GCC_except_table7095
+ GCC_except_table7096
+ GCC_except_table7186
+ GCC_except_table7189
+ GCC_except_table7193
+ GCC_except_table7194
+ GCC_except_table7198
+ GCC_except_table7199
+ GCC_except_table7201
+ GCC_except_table7207
+ GCC_except_table7216
+ GCC_except_table7232
+ GCC_except_table7283
+ GCC_except_table7335
+ GCC_except_table7336
+ GCC_except_table7337
+ GCC_except_table7338
+ GCC_except_table7370
+ GCC_except_table7373
+ GCC_except_table7441
+ GCC_except_table7451
+ GCC_except_table7556
+ GCC_except_table7609
+ GCC_except_table7611
+ GCC_except_table7705
+ GCC_except_table7711
+ GCC_except_table7716
+ GCC_except_table7717
+ GCC_except_table7718
+ GCC_except_table7719
+ GCC_except_table7721
+ GCC_except_table7725
+ GCC_except_table7726
+ GCC_except_table7727
+ GCC_except_table7729
+ GCC_except_table7730
+ GCC_except_table775
+ GCC_except_table7790
+ GCC_except_table7798
+ GCC_except_table7812
+ GCC_except_table7813
+ GCC_except_table7814
+ GCC_except_table7848
+ GCC_except_table7849
+ GCC_except_table7850
+ GCC_except_table7853
+ GCC_except_table7856
+ GCC_except_table786
+ GCC_except_table7901
+ GCC_except_table7903
+ GCC_except_table796
+ GCC_except_table8047
+ GCC_except_table8057
+ GCC_except_table8064
+ GCC_except_table8065
+ GCC_except_table8066
+ GCC_except_table8067
+ GCC_except_table8068
+ GCC_except_table8069
+ GCC_except_table8070
+ GCC_except_table8113
+ GCC_except_table816
+ GCC_except_table8299
+ GCC_except_table8527
+ GCC_except_table8529
+ GCC_except_table8530
+ GCC_except_table8592
+ GCC_except_table8594
+ GCC_except_table8596
+ GCC_except_table866
+ GCC_except_table8666
+ GCC_except_table867
+ GCC_except_table8689
+ GCC_except_table8691
+ GCC_except_table8694
+ GCC_except_table8698
+ GCC_except_table8700
+ GCC_except_table8716
+ GCC_except_table8733
+ GCC_except_table8741
+ GCC_except_table8745
+ GCC_except_table8746
+ GCC_except_table8754
+ GCC_except_table8764
+ GCC_except_table8765
+ GCC_except_table8768
+ GCC_except_table8770
+ GCC_except_table8774
+ GCC_except_table8776
+ GCC_except_table8777
+ GCC_except_table8789
+ _AVAppleMakerNote_TextureStyleKey_Grain
+ _AVAppleMakerNote_TextureStyleKey_Intensity
+ _AVAppleMakerNote_TextureStyleKey_Preset
+ _CMISetColorManagementMetadataOnTexture
+ _CMITextureStylePresetNameFilmic
+ _CMITextureStylePresetNameGlowy
+ _CMITextureStylePresetNameSoft
+ _CMITextureStylePresetNameStandard
+ _CMITextureStylePresetNameStudio
+ _NUAssetCapabilityPhotographicStyleV2
+ _NUChannelNameEarsMatte
+ _NUChannelNameEyebrowsMatte
+ _NUChannelNameFaceSkinMatte
+ _NUChannelNameGlassesMatteV2
+ _NUChannelNameHandsMatte
+ _NUChannelNameLipsMatte
+ _NUChannelNameNonFaceSkinMatte
+ _NUChannelNameNoseMatte
+ _NUChannelNamePersonInstances
+ _NUChannelNamePersonMatte
+ _NUChannelNameSkinMatteV2
+ _NUChannelNameTattooMatte
+ _NUChannelNameTeethMatteV2
+ _NUMediaAttachmentKeySemanticStyleProperties
+ _NUMediaAttachmentKeyTextureStyleProperties
+ _NUPipelineVariableIsSeeking
+ _NUTextureStyleMetadataKey_FaceAttitude
+ _OBJC_CLASS_$_CMIExternalMemoryResource
+ _OBJC_CLASS_$_CMIImageTile
+ _OBJC_CLASS_$_CMITextureColorManagementMetadata
+ _OBJC_CLASS_$_CMITextureStyleTuningLookup
+ _OBJC_CLASS_$_CMITextureStylesBloomParameters
+ _OBJC_CLASS_$_CMITextureStylesDiffusionParameters
+ _OBJC_CLASS_$_CMITextureStylesEffectDescriptor
+ _OBJC_CLASS_$_CMITextureStylesFilmGrainParameters
+ _OBJC_CLASS_$_CMITextureStylesGlowParameters
+ _OBJC_CLASS_$_CMITextureStylesHalationParameters
+ _OBJC_CLASS_$_CMITextureStylesMattifyParameters
+ _OBJC_CLASS_$_CMITextureStylesPersonInputData
+ _OBJC_CLASS_$_CMITextureStylesPersonInputDataUtilities
+ _OBJC_CLASS_$_CMITextureStylesProcessor
+ _OBJC_CLASS_$_CMITextureStylesSkinSmoothParameters
+ _OBJC_CLASS_$_CMITextureStylesUnderEyeBrightenParameters
+ _OBJC_CLASS_$_FigMetalAllocatorBackend
+ _OBJC_CLASS_$_FigMetalAllocatorBackendDescriptor
+ _OBJC_CLASS_$_NUAspectFitScalePolicy
+ _OBJC_CLASS_$_PICinematicVideoAccumulatedStateProcessor
+ _OBJC_CLASS_$_PICinematicVideoAccumulatedStateProcessorConfiguration
+ _OBJC_CLASS_$_PICinematicVideoComputeDisparityGenerator
+ _OBJC_CLASS_$_PICinematicVideoDisparityCacheRetriever
+ _OBJC_CLASS_$_PICinematicVideoDisparityMaterializer
+ _OBJC_CLASS_$_PICinematicVideoFastFocusDisparityProcessor
+ _OBJC_CLASS_$_PICinematicVideoRefinedFocusDisparityProcessor
+ _OBJC_CLASS_$_PICinematicVideoRefinementProcessor
+ _OBJC_CLASS_$_PICinematicVideoTimedFocusDisparityProcessor
+ _OBJC_CLASS_$_PIPhotographicStyleApplyV2
+ _OBJC_CLASS_$_PIPhotographicStyleLearnV2
+ _OBJC_CLASS_$_PITextureStyle
+ _OBJC_CLASS_$_PITextureStyleAdjustmentController
+ _OBJC_CLASS_$_PITextureStyleAutoCalculator
+ _OBJC_CLASS_$_PITextureStylePipelineProcessor
+ _OBJC_CLASS_$_PITextureStyleProcessorKernel
+ _OBJC_CLASS_$_PITextureStyleProcessorResource
+ _OBJC_CLASS_$_PITextureStyleUsageInputConfiguration
+ _OBJC_CLASS_$_PTCinematographyFocusDisparitySampler
+ _OBJC_CLASS_$_PTCinematographyPostcaptureRefinement
+ _OBJC_CLASS_$_PTCinematographyScriptSnapshot
+ _OBJC_CLASS_$_PTMonocularDisparityProvider
+ _OBJC_CLASS_$_PTMonocularDisparitySettings
+ _OBJC_CLASS_$_PTPixelBufferCache
+ _OBJC_CLASS_$__NUAuxiliaryMetadata
+ _OBJC_CLASS_$__NUSemanticStyleProperties
+ _OBJC_CLASS_$__NUTextureStyleProperties
+ _OBJC_CLASS_$__PICinematicVideoComputeDisparityGeneratorConfiguration
+ _OBJC_CLASS_$__PICinematicVideoTimedFocusDisparityProcessorConfiguration
+ _OBJC_CLASS_$__PISemanticStyleAdjustmentExpressionFunction
+ _OBJC_CLASS_$__PITextureStyleSettingsExpressionFunction
+ _OBJC_IVAR_$_PIAdjustmentConstants._PITextureStyleAdjustmentKey
+ _OBJC_IVAR_$_PICinematicVideoAccumulatedStateProcessor._accumulatedState
+ _OBJC_IVAR_$_PICinematicVideoComputeDisparityGenerator._disparityProvider
+ _OBJC_IVAR_$_PICinematicVideoComputeDisparityGenerator._lastSourceTime
+ _OBJC_IVAR_$_PICinematicVideoFastFocusDisparityProcessor._focusDisparitySampler
+ _OBJC_IVAR_$_PICinematicVideoRefinementProcessor._disparityBufferCache
+ _OBJC_IVAR_$_PICinematicVideoRefinementProcessor._disparityProvider
+ _OBJC_IVAR_$_PICinematicVideoRefinementProcessor._inputSize
+ _OBJC_IVAR_$_PICinematicVideoRefinementProcessor._isInitialized
+ _OBJC_IVAR_$_PICinematicVideoRefinementProcessor._refinement
+ _OBJC_IVAR_$_PICinematicVideoRefinementProcessor._script
+ _OBJC_IVAR_$_PICinematicVideoTimedFocusDisparityProcessor._cinematographySnapshot
+ _OBJC_IVAR_$_PICompositionExporterAuxiliaryOptions._embedProvenanceData
+ _OBJC_IVAR_$_PICompositionExporterImageOptions._embedProvenanceData
+ _OBJC_IVAR_$_PITextureStylePipelineProcessor._requirements
+ _OBJC_IVAR_$_PITextureStylePipelineProcessor._usage
+ _OBJC_IVAR_$_PITextureStyleProcessorResource._metalCommandQueue
+ _OBJC_IVAR_$_PITextureStyleProcessorResource._processor
+ _OBJC_IVAR_$_PITextureStyleProcessorResource._usage
+ _OBJC_IVAR_$_PITextureStyleUsageInputConfiguration._optionalChannelNames
+ _OBJC_IVAR_$_PITextureStyleUsageInputConfiguration._optionalChannels
+ _OBJC_IVAR_$_PITextureStyleUsageInputConfiguration._requiredChannelNames
+ _OBJC_IVAR_$_PITextureStyleUsageInputConfiguration._requiredChannels
+ _OBJC_IVAR_$_PITextureStyleUsageInputConfiguration._requiresPersonData
+ _OBJC_IVAR_$__PICinematicVideoComputeDisparityGeneratorConfiguration._quality
+ _OBJC_IVAR_$__PICinematicVideoComputeDisparityGeneratorConfiguration._size
+ _OBJC_IVAR_$__PICinematicVideoTimedFocusDisparityProcessorConfiguration._generation
+ _OBJC_METACLASS_$_PICinematicVideoAccumulatedStateProcessor
+ _OBJC_METACLASS_$_PICinematicVideoAccumulatedStateProcessorConfiguration
+ _OBJC_METACLASS_$_PICinematicVideoComputeDisparityGenerator
+ _OBJC_METACLASS_$_PICinematicVideoDisparityCacheRetriever
+ _OBJC_METACLASS_$_PICinematicVideoDisparityMaterializer
+ _OBJC_METACLASS_$_PICinematicVideoFastFocusDisparityProcessor
+ _OBJC_METACLASS_$_PICinematicVideoRefinedFocusDisparityProcessor
+ _OBJC_METACLASS_$_PICinematicVideoRefinementProcessor
+ _OBJC_METACLASS_$_PICinematicVideoTimedFocusDisparityProcessor
+ _OBJC_METACLASS_$_PIPhotographicStyleApplyV2
+ _OBJC_METACLASS_$_PIPhotographicStyleLearnV2
+ _OBJC_METACLASS_$_PITextureStyle
+ _OBJC_METACLASS_$_PITextureStyleAdjustmentController
+ _OBJC_METACLASS_$_PITextureStyleAutoCalculator
+ _OBJC_METACLASS_$_PITextureStylePipelineProcessor
+ _OBJC_METACLASS_$_PITextureStyleProcessorKernel
+ _OBJC_METACLASS_$_PITextureStyleProcessorResource
+ _OBJC_METACLASS_$_PITextureStyleUsageInputConfiguration
+ _OBJC_METACLASS_$__PICinematicVideoComputeDisparityGeneratorConfiguration
+ _OBJC_METACLASS_$__PICinematicVideoTimedFocusDisparityProcessorConfiguration
+ _OBJC_METACLASS_$__PISemanticStyleAdjustmentExpressionFunction
+ _OBJC_METACLASS_$__PITextureStyleSettingsExpressionFunction
+ _PIAdjustment_TextureStyle_Identifier
+ _PIComputeDisparityForFrame
+ _PIDisparitySizeFromGlobalRenderingData
+ _PIPhotographicStyleVideoMode
+ _PITextureStyleAdjustmentKey
+ _PITextureStyleCurrentMetadataVersion
+ _PITextureStyleDefaultTextureStyleDictionaryForCast
+ _PITextureStyleDefaultTextureStyleDictionaryForPreset
+ _PITextureStyleIsRenderSupported
+ _PITextureStyleIsRenderSupportedForProperties
+ _PITextureStyleIsTestingSupported
+ _PITextureStyleModuleGlobalEffectsOnly
+ _PITextureStyleModuleLocalEffectsOnly
+ _PITextureStyleModulePostTargetEffectsOnly
+ _PITextureStyleModulePreTargetEffectsOnly
+ _PITextureStyleModuleVideoMode
+ _PITextureStylePresetFilmic
+ _PITextureStylePresetFromMakerNoteValue
+ _PITextureStylePresetFromString
+ _PITextureStylePresetGlowy
+ _PITextureStylePresetSoft
+ _PITextureStylePresetStandard
+ _PITextureStylePresetStudio
+ _PITextureStyleRendererUsageROI
+ _PITextureStyleRendererUsageRender
+ _PITextureStyleSettingsFromMakerNoteProperties
+ _PTMonocularDisparityQualityToString
+ __OBJC_$_CLASS_METHODS_PICinematicVideoComputeDisparityGenerator
+ __OBJC_$_CLASS_METHODS_PICinematicVideoRefinementProcessor
+ __OBJC_$_CLASS_METHODS_PICinematicVideoTimedFocusDisparityProcessor
+ __OBJC_$_CLASS_METHODS_PIPhotographicStyleLearnV2
+ __OBJC_$_CLASS_METHODS_PITextureStyle
+ __OBJC_$_CLASS_METHODS_PITextureStyleAdjustmentController
+ __OBJC_$_CLASS_METHODS_PITextureStyleAutoCalculator
+ __OBJC_$_CLASS_METHODS_PITextureStylePipelineProcessor
+ __OBJC_$_CLASS_METHODS_PITextureStyleProcessorKernel
+ __OBJC_$_CLASS_METHODS_PITextureStyleProcessorResource
+ __OBJC_$_CLASS_METHODS__PISemanticStyleAdjustmentExpressionFunction
+ __OBJC_$_CLASS_PROP_LIST_PITextureStyle
+ __OBJC_$_INSTANCE_METHODS_PICinematicVideoAccumulatedStateProcessor
+ __OBJC_$_INSTANCE_METHODS_PICinematicVideoAccumulatedStateProcessorConfiguration
+ __OBJC_$_INSTANCE_METHODS_PICinematicVideoComputeDisparityGenerator
+ __OBJC_$_INSTANCE_METHODS_PICinematicVideoDisparityCacheRetriever
+ __OBJC_$_INSTANCE_METHODS_PICinematicVideoDisparityMaterializer
+ __OBJC_$_INSTANCE_METHODS_PICinematicVideoFastFocusDisparityProcessor
+ __OBJC_$_INSTANCE_METHODS_PICinematicVideoRefinedFocusDisparityProcessor
+ __OBJC_$_INSTANCE_METHODS_PICinematicVideoRefinementProcessor
+ __OBJC_$_INSTANCE_METHODS_PICinematicVideoTimedFocusDisparityProcessor
+ __OBJC_$_INSTANCE_METHODS_PIPhotographicStyleApplyV2
+ __OBJC_$_INSTANCE_METHODS_PIPhotographicStyleLearnV2
+ __OBJC_$_INSTANCE_METHODS_PITextureStyle
+ __OBJC_$_INSTANCE_METHODS_PITextureStyleAdjustmentController
+ __OBJC_$_INSTANCE_METHODS_PITextureStyleAutoCalculator
+ __OBJC_$_INSTANCE_METHODS_PITextureStylePipelineProcessor
+ __OBJC_$_INSTANCE_METHODS_PITextureStyleProcessorResource
+ __OBJC_$_INSTANCE_METHODS_PITextureStyleUsageInputConfiguration
+ __OBJC_$_INSTANCE_METHODS__PICinematicVideoComputeDisparityGeneratorConfiguration
+ __OBJC_$_INSTANCE_METHODS__PICinematicVideoTimedFocusDisparityProcessorConfiguration
+ __OBJC_$_INSTANCE_METHODS__PISemanticStyleAdjustmentExpressionFunction
+ __OBJC_$_INSTANCE_METHODS__PITextureStyleSettingsExpressionFunction
+ __OBJC_$_INSTANCE_VARIABLES_PICinematicVideoAccumulatedStateProcessor
+ __OBJC_$_INSTANCE_VARIABLES_PICinematicVideoComputeDisparityGenerator
+ __OBJC_$_INSTANCE_VARIABLES_PICinematicVideoFastFocusDisparityProcessor
+ __OBJC_$_INSTANCE_VARIABLES_PICinematicVideoRefinementProcessor
+ __OBJC_$_INSTANCE_VARIABLES_PICinematicVideoTimedFocusDisparityProcessor
+ __OBJC_$_INSTANCE_VARIABLES_PITextureStylePipelineProcessor
+ __OBJC_$_INSTANCE_VARIABLES_PITextureStyleProcessorResource
+ __OBJC_$_INSTANCE_VARIABLES_PITextureStyleUsageInputConfiguration
+ __OBJC_$_INSTANCE_VARIABLES__PICinematicVideoComputeDisparityGeneratorConfiguration
+ __OBJC_$_INSTANCE_VARIABLES__PICinematicVideoTimedFocusDisparityProcessorConfiguration
+ __OBJC_$_PROP_LIST_PICinematicVideoAccumulatedStateProcessorConfiguration
+ __OBJC_$_PROP_LIST_PICinematicVideoRefinementProcessor
+ __OBJC_$_PROP_LIST_PITextureStyleAdjustmentController
+ __OBJC_$_PROP_LIST_PITextureStyleProcessorResource
+ __OBJC_$_PROP_LIST_PITextureStyleUsageInputConfiguration
+ __OBJC_$_PROP_LIST__PICinematicVideoComputeDisparityGeneratorConfiguration
+ __OBJC_$_PROP_LIST__PICinematicVideoTimedFocusDisparityProcessorConfiguration
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCoding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSCoding
+ __OBJC_$_PROTOCOL_REFS_NUPipelineProcessorConfiguration
+ __OBJC_CLASS_PROTOCOLS_$_PICinematicVideoAccumulatedStateProcessorConfiguration
+ __OBJC_CLASS_PROTOCOLS_$__PICinematicVideoComputeDisparityGeneratorConfiguration
+ __OBJC_CLASS_PROTOCOLS_$__PICinematicVideoTimedFocusDisparityProcessorConfiguration
+ __OBJC_CLASS_RO_$_PICinematicVideoAccumulatedStateProcessor
+ __OBJC_CLASS_RO_$_PICinematicVideoAccumulatedStateProcessorConfiguration
+ __OBJC_CLASS_RO_$_PICinematicVideoComputeDisparityGenerator
+ __OBJC_CLASS_RO_$_PICinematicVideoDisparityCacheRetriever
+ __OBJC_CLASS_RO_$_PICinematicVideoDisparityMaterializer
+ __OBJC_CLASS_RO_$_PICinematicVideoFastFocusDisparityProcessor
+ __OBJC_CLASS_RO_$_PICinematicVideoRefinedFocusDisparityProcessor
+ __OBJC_CLASS_RO_$_PICinematicVideoRefinementProcessor
+ __OBJC_CLASS_RO_$_PICinematicVideoTimedFocusDisparityProcessor
+ __OBJC_CLASS_RO_$_PIPhotographicStyleApplyV2
+ __OBJC_CLASS_RO_$_PIPhotographicStyleLearnV2
+ __OBJC_CLASS_RO_$_PITextureStyle
+ __OBJC_CLASS_RO_$_PITextureStyleAdjustmentController
+ __OBJC_CLASS_RO_$_PITextureStyleAutoCalculator
+ __OBJC_CLASS_RO_$_PITextureStylePipelineProcessor
+ __OBJC_CLASS_RO_$_PITextureStyleProcessorKernel
+ __OBJC_CLASS_RO_$_PITextureStyleProcessorResource
+ __OBJC_CLASS_RO_$_PITextureStyleUsageInputConfiguration
+ __OBJC_CLASS_RO_$__PICinematicVideoComputeDisparityGeneratorConfiguration
+ __OBJC_CLASS_RO_$__PICinematicVideoTimedFocusDisparityProcessorConfiguration
+ __OBJC_CLASS_RO_$__PISemanticStyleAdjustmentExpressionFunction
+ __OBJC_CLASS_RO_$__PITextureStyleSettingsExpressionFunction
+ __OBJC_LABEL_PROTOCOL_$_NSCoding
+ __OBJC_LABEL_PROTOCOL_$_NUPipelineProcessorConfiguration
+ __OBJC_METACLASS_RO_$_PICinematicVideoAccumulatedStateProcessor
+ __OBJC_METACLASS_RO_$_PICinematicVideoAccumulatedStateProcessorConfiguration
+ __OBJC_METACLASS_RO_$_PICinematicVideoComputeDisparityGenerator
+ __OBJC_METACLASS_RO_$_PICinematicVideoDisparityCacheRetriever
+ __OBJC_METACLASS_RO_$_PICinematicVideoDisparityMaterializer
+ __OBJC_METACLASS_RO_$_PICinematicVideoFastFocusDisparityProcessor
+ __OBJC_METACLASS_RO_$_PICinematicVideoRefinedFocusDisparityProcessor
+ __OBJC_METACLASS_RO_$_PICinematicVideoRefinementProcessor
+ __OBJC_METACLASS_RO_$_PICinematicVideoTimedFocusDisparityProcessor
+ __OBJC_METACLASS_RO_$_PIPhotographicStyleApplyV2
+ __OBJC_METACLASS_RO_$_PIPhotographicStyleLearnV2
+ __OBJC_METACLASS_RO_$_PITextureStyle
+ __OBJC_METACLASS_RO_$_PITextureStyleAdjustmentController
+ __OBJC_METACLASS_RO_$_PITextureStyleAutoCalculator
+ __OBJC_METACLASS_RO_$_PITextureStylePipelineProcessor
+ __OBJC_METACLASS_RO_$_PITextureStyleProcessorKernel
+ __OBJC_METACLASS_RO_$_PITextureStyleProcessorResource
+ __OBJC_METACLASS_RO_$_PITextureStyleUsageInputConfiguration
+ __OBJC_METACLASS_RO_$__PICinematicVideoComputeDisparityGeneratorConfiguration
+ __OBJC_METACLASS_RO_$__PICinematicVideoTimedFocusDisparityProcessorConfiguration
+ __OBJC_METACLASS_RO_$__PISemanticStyleAdjustmentExpressionFunction
+ __OBJC_METACLASS_RO_$__PITextureStyleSettingsExpressionFunction
+ __OBJC_PROTOCOL_$_NSCoding
+ __OBJC_PROTOCOL_$_NUPipelineProcessorConfiguration
+ ___115-[PICinematicVideo_v2 _buildPipeline:primary:adjustment:cinematography:highQuality:useRefinedCinematography:error:]_block_invoke
+ ___115-[PICinematicVideo_v2 _buildPipeline:primary:adjustment:cinematography:highQuality:useRefinedCinematography:error:]_block_invoke_2
+ ___123+[PICinematicVideoTimedFocusDisparityProcessor usingSharedCinematographyScriptSnapshotForDictionaryRepresentation:perform:]_block_invoke
+ ___127+[PICinematicVideoComputeDisparityGenerator usingSharedDisparityProviderForQuality:size:globalRenderingMetadata:perform:error:]_block_invoke
+ ___140+[PITextureStyleProcessorKernel effectDescriptorsForPreset:grainIntensity:tuningDictionary:usage:semanticStyleProperties:semanticStyleInfo:]_block_invoke
+ ___38-[PITextureStyle buildPipeline:error:]_block_invoke
+ ___50-[PIPhotographicStyleApplyV2 buildPipeline:error:]_block_invoke
+ ___52-[PIPhotosPipeline_v1 buildLivePhotoPipeline:error:]_block_invoke_3
+ ___61+[PITextureStyleProcessorKernel defaultEffectOrderForPreset:]_block_invoke
+ ___63-[NUGlobalSettings(PIGlobalSettings) enableCinematicEverywhere]_block_invoke
+ ___65-[NUGlobalSettings(PIGlobalSettings) debugEnableTextureStyleDump]_block_invoke
+ ___66+[PITextureStyleProcessorKernel roiForInput:arguments:outputRect:]_block_invoke
+ ___68+[PITextureStyleProcessorKernel personInputDataFromStillProperties:]_block_invoke
+ ___68-[NUGlobalSettings(PIGlobalSettings) debugTextureStyleDumpDirectory]_block_invoke
+ ___69-[NUGlobalSettings(PIGlobalSettings) debugTextureStyleEnabledEffects]_block_invoke
+ ___71+[PIModularPhotosPipeline_v1 controlDataWithPortraitVideoV2Adjustment:]_block_invoke_2
+ ___74+[PITextureStyleProcessorKernel processWithInputs:arguments:output:error:]_block_invoke
+ ___75-[NUGlobalSettings(PIGlobalSettings) debugEnableTextureStyleTiledRendering]_block_invoke
+ ___76-[NUGlobalSettings(PIGlobalSettings) cinematicVideoUseRefinedCinematography]_block_invoke
+ ___76-[PITextureStylePipelineProcessor outputImageWithSamples:controlData:error:]_block_invoke
+ ___78-[PICompositionController(AdjustmentExtensions) modifyTextureStyleAdjustment:]_block_invoke
+ ___82-[PICinematicVideoComputeDisparityGenerator computeDataWithInputs:settings:error:]_block_invoke
+ ___82-[PICinematicVideoRefinementProcessor accumulateAtTime:withInputs:settings:error:]_block_invoke
+ ___85-[PICinematicVideoTimedFocusDisparityProcessor computeDataWithInputs:settings:error:]_block_invoke
+ ___94+[PITextureStyleProcessorResource usingSharedProcessorWithUsage:isVideo:commandQueue:perform:]_block_invoke
+ ___94-[PITextureStyleUsageInputConfiguration initWithRequiredChannels:optionalChannels:personData:]_block_invoke
+ ___94-[PITextureStyleUsageInputConfiguration initWithRequiredChannels:optionalChannels:personData:]_block_invoke_2
+ ___block_descriptor_133_e8_32s40s48r_e35_B16?0"CMITextureStylesProcessor"8ls32l8s40l8r48l8
+ ___block_descriptor_176_e8_32s40s48s56s64s72s80s88s96s104bs_e35_B16?0"CMITextureStylesProcessor"8ls32l8s40l8s48l8s56l8s64l8s104l8s72l8s80l8s88l8s96l8
+ ___block_descriptor_32_e18_B16?0"NSNumber"8l
+ ___block_descriptor_32_e28_"NSString"16?0"NSNumber"8l
+ ___block_descriptor_32_e29_"NSString"16?0"NUChannel"8l
+ ___block_descriptor_32_e82_"CMITextureStylesPersonInputData"16?0"_NUTextureStylePersonInstanceProperties"8l
+ ___block_descriptor_40_e40_B16?0"PTCinematographyScriptSnapshot"8l
+ ___block_descriptor_40_e8_32bs_e44_v16?0"PITextureStyleAdjustmentController"8ls32l8
+ ___block_descriptor_44_e38_B16?0"PTMonocularDisparityProvider"8l
+ ___block_descriptor_48_e8_32s40bs_e48_v32?0"CMITextureStylesPersonInputData"8Q16^B24ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e41_B16?0"PITextureStyleProcessorResource"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e57_v32?0"<NUTextureStylePersonInstanceProperties>"8Q16^B24ls32l8s40l8
+ ___block_descriptor_72_e8_32s40r_e40_v16?0"PTCinematographyScriptSnapshot"8lr40l8s32l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72r_e33_B24?0"<NUMutablePipeline>"8^16lr72l8s32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_98_e8_32s40s48r56r_e38_B16?0"PTMonocularDisparityProvider"8lr48l8s32l8s40l8r56l8
+ _associated conformance So20PITextureStylePresetaSHSCSQ
+ _associated conformance So20PITextureStylePresetas12CaseIterable12PhotoImaging8AllCasessACP_Sl
+ _associated conformance So20PITextureStylePresetas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So20PITextureStylePresetas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _kCIFormatR8
+ _kCMITextureStyleTuningBlendPreset_Key
+ _kCMITextureStyleTuningBlendThreshold_Key
+ _kCMITextureStyleTuningFilmGrainEffect_Key
+ _kCMITextureStyleTuningGrainSourcePreset_Key
+ _symbolic Say_____G So20PITextureStylePreseta
+ _symbolic _____ So20PITextureStylePreseta
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So20PITextureStylePreseta
+ _type_layout_string So20PITextureStylePreseta
- GCC_except_table1104
- GCC_except_table1706
- GCC_except_table1720
- GCC_except_table1887
- GCC_except_table2063
- GCC_except_table2217
- GCC_except_table2227
- GCC_except_table2241
- GCC_except_table2248
- GCC_except_table2256
- GCC_except_table2334
- GCC_except_table2374
- GCC_except_table2403
- GCC_except_table2408
- GCC_except_table2423
- GCC_except_table2439
- GCC_except_table2444
- GCC_except_table2537
- GCC_except_table2759
- GCC_except_table3112
- GCC_except_table3117
- GCC_except_table3147
- GCC_except_table3151
- GCC_except_table3153
- GCC_except_table3154
- GCC_except_table3156
- GCC_except_table3158
- GCC_except_table3160
- GCC_except_table3171
- GCC_except_table3180
- GCC_except_table3275
- GCC_except_table3344
- GCC_except_table3345
- GCC_except_table3454
- GCC_except_table3496
- GCC_except_table3504
- GCC_except_table3556
- GCC_except_table3782
- GCC_except_table3792
- GCC_except_table3795
- GCC_except_table3796
- GCC_except_table3808
- GCC_except_table3855
- GCC_except_table3864
- GCC_except_table3892
- GCC_except_table3915
- GCC_except_table4144
- GCC_except_table4396
- GCC_except_table4499
- GCC_except_table4523
- GCC_except_table4527
- GCC_except_table4646
- GCC_except_table4684
- GCC_except_table4690
- GCC_except_table4692
- GCC_except_table4716
- GCC_except_table4738
- GCC_except_table4961
- GCC_except_table4984
- GCC_except_table4991
- GCC_except_table4994
- GCC_except_table5005
- GCC_except_table5012
- GCC_except_table5159
- GCC_except_table5251
- GCC_except_table5312
- GCC_except_table5315
- GCC_except_table5327
- GCC_except_table5328
- GCC_except_table5332
- GCC_except_table5333
- GCC_except_table5334
- GCC_except_table5339
- GCC_except_table5347
- GCC_except_table5440
- GCC_except_table5790
- GCC_except_table5809
- GCC_except_table5810
- GCC_except_table5816
- GCC_except_table5821
- GCC_except_table5873
- GCC_except_table5878
- GCC_except_table5879
- GCC_except_table5889
- GCC_except_table5891
- GCC_except_table5915
- GCC_except_table5917
- GCC_except_table5918
- GCC_except_table5919
- GCC_except_table5921
- GCC_except_table5923
- GCC_except_table5925
- GCC_except_table5928
- GCC_except_table5931
- GCC_except_table5933
- GCC_except_table5934
- GCC_except_table5935
- GCC_except_table5936
- GCC_except_table5938
- GCC_except_table5943
- GCC_except_table5976
- GCC_except_table6079
- GCC_except_table6082
- GCC_except_table6122
- GCC_except_table6196
- GCC_except_table6515
- GCC_except_table6763
- GCC_except_table6764
- GCC_except_table6854
- GCC_except_table6857
- GCC_except_table6861
- GCC_except_table6862
- GCC_except_table6866
- GCC_except_table6867
- GCC_except_table6869
- GCC_except_table6875
- GCC_except_table6884
- GCC_except_table6900
- GCC_except_table6951
- GCC_except_table7003
- GCC_except_table7004
- GCC_except_table7005
- GCC_except_table7006
- GCC_except_table7038
- GCC_except_table7041
- GCC_except_table7109
- GCC_except_table7119
- GCC_except_table7223
- GCC_except_table7276
- GCC_except_table7278
- GCC_except_table7372
- GCC_except_table7378
- GCC_except_table7381
- GCC_except_table7383
- GCC_except_table7384
- GCC_except_table7385
- GCC_except_table7386
- GCC_except_table7388
- GCC_except_table7391
- GCC_except_table7392
- GCC_except_table7393
- GCC_except_table7394
- GCC_except_table7396
- GCC_except_table7397
- GCC_except_table7399
- GCC_except_table7400
- GCC_except_table7401
- GCC_except_table7402
- GCC_except_table7457
- GCC_except_table7465
- GCC_except_table7479
- GCC_except_table7480
- GCC_except_table7481
- GCC_except_table7515
- GCC_except_table7516
- GCC_except_table7517
- GCC_except_table7520
- GCC_except_table7523
- GCC_except_table7568
- GCC_except_table7570
- GCC_except_table771
- GCC_except_table7731
- GCC_except_table7736
- GCC_except_table7737
- GCC_except_table7780
- GCC_except_table782
- GCC_except_table792
- GCC_except_table7966
- GCC_except_table812
- GCC_except_table8194
- GCC_except_table8196
- GCC_except_table8197
- GCC_except_table8259
- GCC_except_table8261
- GCC_except_table8263
- GCC_except_table8333
- GCC_except_table8356
- GCC_except_table8358
- GCC_except_table8361
- GCC_except_table8365
- GCC_except_table8367
- GCC_except_table8383
- GCC_except_table8400
- GCC_except_table8408
- GCC_except_table8412
- GCC_except_table8413
- GCC_except_table8421
- GCC_except_table8431
- GCC_except_table8432
- GCC_except_table8435
- GCC_except_table8437
- GCC_except_table8441
- GCC_except_table8443
- GCC_except_table8444
- GCC_except_table8456
- GCC_except_table859
- GCC_except_table862
- _type_layout_string So19PISemanticStyleCasta
CStrings:
+ "#"
+ "+[PICinematicVideoComputeDisparityGenerator usingSharedDisparityProviderForQuality:size:globalRenderingMetadata:perform:error:]"
+ "+[PISchema textureStyleSchema]"
+ "+[PITextureStyleProcessorKernel processWithInputs:arguments:output:error:]"
+ "+[PITextureStyleProcessorKernel roiForInput:arguments:outputRect:]"
+ "-[PICinematicVideoComputeDisparityGenerator computeDataWithInputs:settings:error:]"
+ "-[PICinematicVideoComputeDisparityGenerator configurationWithInputGeometries:outputGeometry:settings:]"
+ "-[PICinematicVideoDisparityCacheRetriever outputImageWithSamples:controlData:error:]"
+ "-[PICinematicVideoDisparityMaterializer outputImageWithSamples:controlData:error:]"
+ "-[PICinematicVideoFastFocusDisparityProcessor _focusDisparityFromMetadataItems:disparityBuffer:renderTime:focusDisparity:error:]"
+ "-[PICinematicVideoFastFocusDisparityProcessor computeDataWithInputs:settings:error:]"
+ "-[PICinematicVideoRefinedFocusDisparityProcessor computeDataWithInputs:settings:error:]"
+ "-[PICinematicVideoRefinementProcessor accumulateAtTime:withInputs:settings:error:]"
+ "-[PICinematicVideoTimedFocusDisparityProcessor computeDataWithInputs:settings:error:]"
+ "-[PIPhotographicStyleApplyV2 buildPipeline:error:]"
+ "-[PIPhotographicStyleLearnV2 buildPipeline:error:]"
+ "-[PITextureStyle buildPipeline:error:]"
+ "-[PITextureStyleAutoCalculator submit:]"
+ "-[PITextureStylePipelineProcessor outputImageWithSamples:controlData:error:]"
+ "-[PITextureStyleProcessorResource setupProcessor]"
+ "-[_PISemanticStyleAdjustmentExpressionFunction evaluateWithArguments:error:]"
+ "-[_PITextureStyleSettingsExpressionFunction evaluateWithArguments:error:]"
+ "../video/photographicStyleV2KeyFrame:>image"
+ "/"
+ "/:"
+ "/:<cinematicVideoHighQuality"
+ "/:<cinematicVideoUseRefinedCinematography"
+ "/:<textureStyle.enabled"
+ "/:adjustment.grainIntensity"
+ "/:adjustment.intensity"
+ "/:adjustment.preset"
+ "/:default"
+ "/:defaultTextureStyle"
+ "/:earsMatte"
+ "/:eyebrowsMatte"
+ "/:faceInfoTimedMetadata"
+ "/:faceSkinMatte"
+ "/:glassesMatteV2"
+ "/:hairMatte"
+ "/:handsMatte"
+ "/:linearThumbnail"
+ "/:lipsMatte"
+ "/:nonFaceSkinMatte"
+ "/:noseMatte"
+ "/:personInstances"
+ "/:personMatte"
+ "/:portraitMatte"
+ "/:semanticStyleAdjustment"
+ "/:semanticStyleAdjustment.cast"
+ "/:semanticStyleAdjustment.color"
+ "/:semanticStyleCast"
+ "/:semanticStyleColor"
+ "/:semanticStyleTimedMetadata"
+ "/:skinMatte"
+ "/:skinMatteV2"
+ "/:style"
+ "/:tattooMatte"
+ "/:teethMatteV2"
+ "/:textureStyleAdjustment"
+ "/:textureStyleTimedMetadata"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Photos/workspaces/neutrino/PhotoImaging/Autocalculators/PITextureStyleAutoCalculator.m"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Photos/workspaces/neutrino/PhotoImaging/Pipeline/API/PIPhotographicStyleV2.m"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Photos/workspaces/neutrino/PhotoImaging/Pipeline/API/PITextureStyle.m"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Photos/workspaces/neutrino/PhotoImaging/Pipeline/API/PITextureStyleProcessor.m"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Photos/workspaces/neutrino/PhotoImaging/Pipeline/PICinematicVideoDisparityGenerator.m"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Photos/workspaces/neutrino/PhotoImaging/Pipeline/PICinematicVideoRefinementProcessor.m"
+ "/livePhotoKeyFrame:<adjustment.time"
+ "/video/photographicStyleLearn:>style"
+ ":<semanticStyleAdjustment.cast"
+ ":<semanticStyleAdjustment.color"
+ ":<semanticStyleAdjustment.intensity"
+ ":<semanticStyleAdjustment.tone"
+ ":<semanticStyleAdjustment.version"
+ ":>defaultSemanticStyle"
+ ":>defaultTextureStyle"
+ ":adjustment"
+ ":earsMatte"
+ ":eyebrowsMatte"
+ ":faceInfoTimedMetadata"
+ ":faceSkinMatte"
+ ":glassesMatteV2"
+ ":hairMatte"
+ ":handsMatte"
+ ":linearThumbnail"
+ ":lipsMatte"
+ ":nonFaceSkinMatte"
+ ":noseMatte"
+ ":personInstances"
+ ":personMatte"
+ ":portraitMatte"
+ ":semanticStyle"
+ ":semanticStyleAdjustment"
+ ":semanticStyleCast"
+ ":semanticStyleColor"
+ ":semanticStyleTimedMetadata"
+ ":skinMatte"
+ ":skinMatteV2"
+ ":skyMatte"
+ ":style"
+ ":tattooMatte"
+ ":teethMatteV2"
+ ":textureStyle"
+ ":textureStyleAdjustment"
+ ":textureStyleTimedMetadata"
+ "<PITextureStyleUsageInputConfiguration: required=%@, optional=%@, personData=%d>"
+ "@\"CMITextureStylesPersonInputData\"16@?0@\"_NUTextureStylePersonInstanceProperties\"8"
+ "@\"NSString\"16@?0@\"NSNumber\"8"
+ "@\"NSString\"16@?0@\"NUChannel\"8"
+ "Accumulated state does not have required data to serialize"
+ "Accumulated state not available"
+ "Already setup!"
+ "B16@?0@\"CMITextureStylesProcessor\"8"
+ "B16@?0@\"NSNumber\"8"
+ "B16@?0@\"PITextureStyleProcessorResource\"8"
+ "B16@?0@\"PTCinematographyScriptSnapshot\"8"
+ "B16@?0@\"PTMonocularDisparityProvider\"8"
+ "CinEverywhere (compute): Resetting provider state at sourceTime %.4f"
+ "CinEverywhere creating a shared disparity provider for quality %@ and size: %dx%d"
+ "CinEverywhere: AccumulatedStateProcessor passing through accumulated state"
+ "CinEverywhere: AccumulatedStateProcessor paused called!"
+ "CinEverywhere: AccumulatedStateProcessor paused with state (%lu bytes)"
+ "CinEverywhere: AccumulatedStateProcessor resume called!"
+ "CinEverywhere: AccumulatedStateProcessor resumed with deserialized state (%lu bytes)"
+ "CinEverywhere: Accumulation complete"
+ "CinEverywhere: Cannot compute disparity size, failed to allocate disparity settings"
+ "CinEverywhere: Cannot compute disparity size, failed to deserialize global rendering metadata: %@"
+ "CinEverywhere: Cannot compute disparity size, global rendering data is nil"
+ "CinEverywhere: Cannot read global rendering metadata to check disparity resources: %@"
+ "CinEverywhere: Created cinematography snapshot with generation %lu from the source asset"
+ "CinEverywhere: Disparity buffer retrieved from cache at renderTime %.4f"
+ "CinEverywhere: Export pipeline lookahead offset: %.2f seconds"
+ "CinEverywhere: Ignoring nil lookahead buffer at renderTime %.4f (refinement still expects input)"
+ "CinEverywhere: Initialized refinement and disparity provider for accumulation (size: %ldx%ld)"
+ "CinEverywhere: Primary media has no video metadata to check disparity resources"
+ "CinEverywhere: Refinement received all inputs, ending at renderTime %.4f"
+ "CinEverywhere: Unexpected PTDisparityResourceStatus %li"
+ "CinEverywhere: V2 asset is not supported due to PTDisparityResourceStatus %i"
+ "CinEverywhere: V2 asset is supported"
+ "Cinematic accumulation failed - one or more state objects missing"
+ "Cinematic global rendering metadata is missing from settings"
+ "Cinematography metadata is required"
+ "Cinematography metadata items required for fast path"
+ "Cinematography snapshot and videoURL are both missing from settings"
+ "Cinematography snapshot is missing from settings"
+ "Creating 1UP focus disparity smoother"
+ "Diffusion"
+ "Disparity buffer cache not available"
+ "Disparity buffer is required"
+ "EffectOrder"
+ "Expected exactly one input (disparity buffer)"
+ "Expected only 1 effect descriptor"
+ "Failed to add texture style apply pipeline"
+ "Failed to add texture style learn pipeline"
+ "Failed to allocate disparity buffer"
+ "Failed to build cinematic video processor"
+ "Failed to build cinematic video processor for preview"
+ "Failed to build photographicStyleApply pipeline"
+ "Failed to build photographicStyleLearn pipeline"
+ "Failed to build texture style pipeline"
+ "Failed to compute disparity"
+ "Failed to compute disparity size"
+ "Failed to connect compute disparity processor"
+ "Failed to connect pipeline components"
+ "Failed to connect preview pipeline components"
+ "Failed to create a shared disparity provider"
+ "Failed to create accumulated state pipeline"
+ "Failed to create cinematography refinement"
+ "Failed to create cinematography snapshot from script"
+ "Failed to create disparity cache retriever pipeline"
+ "Failed to create disparity materializer pipeline"
+ "Failed to create disparity processor pipeline"
+ "Failed to create fast focus disparity processor pipeline"
+ "Failed to create postcapture refinement pipeline"
+ "Failed to create refinement focus disparity processor pipeline"
+ "Failed to create texture style processor pipeline"
+ "Failed to create timed focus disparity processor pipeline"
+ "Failed to deserialize accumulated state"
+ "Failed to deserialize cinematography frame from timed metadata"
+ "Failed to deserialize cinematography snapshot state"
+ "Failed to deserialize disparity buffer cache data"
+ "Failed to deserialize disparity provider data"
+ "Failed to deserialize disparity provider state"
+ "Failed to deserialize global rendering metadata for resume"
+ "Failed to deserialize global rendering metadata: %@"
+ "Failed to deserialize refinement data"
+ "Failed to extract timed rendering data"
+ "Failed to generate disparity buffer"
+ "Failed to get blended tuning from tuning dictionary %@ - skipping"
+ "Failed to get texture style properties"
+ "Failed to get tuning dictionary for blend target %@ - skipping"
+ "Failed to process texture style"
+ "Failed to process texture style processor for roi"
+ "Failed to process texture styles"
+ "Failed to serialize accumulated state"
+ "Failed to serialize cinematography snapshot state"
+ "Failed to serialize disparity buffer cache state"
+ "Failed to serialize disparity provider state"
+ "Failed to serialize refinement state"
+ "Filmic"
+ "Gain"
+ "Global rendering metadata is required"
+ "Global rendering metadata must be present for cinematic assets"
+ "GlobalToneCurveLookUpTable"
+ "Glowy"
+ "Halation"
+ "Invalid URL in refinement processor"
+ "Invalid input index %lu for name %@ - skipping"
+ "Invalid input index for extents array"
+ "Invalid semantic style adjustment"
+ "Invalid texture style grain value: %{public}@, ignored."
+ "Invalid texture style intensity value: %{public}@, ignored."
+ "Invalid texture style preset value: %{public}@, ignored."
+ "Missing arguments"
+ "Missing cinematography metadata for postcapture refinement"
+ "Missing computed disparity buffer"
+ "Missing disparity buffer cache data in serialized state"
+ "Missing disparity provider data in serialized state"
+ "Missing global rendering metadata for postcapture refinement"
+ "Missing grain intensity"
+ "Missing input %lu, skipping"
+ "Missing intensity"
+ "Missing maker note"
+ "Missing preset"
+ "Missing primary input for postcapture refinement"
+ "Missing refinement data in serialized state"
+ "Missing required matte input: %@"
+ "Missing semantic style adjustment"
+ "Missing smart style info for glow effect descriptor - assuming standard 0,0"
+ "Missing smart style properties"
+ "Missing texture style properties"
+ "NSDictionary * _Nonnull PITextureStyleSettingsFromMakerNoteProperties(NSDictionary *__strong _Nonnull)"
+ "No accumulated state to serialize"
+ "No cached disparity buffer found for render time %.4f"
+ "No cinematography snapshot to serialize"
+ "No disparity provider to serialize"
+ "No person instances found but required for usage %@ - skipping"
+ "No texture style usage config for type %@ - continuing"
+ "OriginalRangeMax"
+ "OriginalRangeMin"
+ "PIPhotographicStyleApply"
+ "PITextureStyleProcessor-FigMetalAllocatorBackend"
+ "PI_CINEMATIC_VIDEO_USE_REFINED_CINEMATOGRAPHY"
+ "PI_ENABLE_CINEMATIC_EVERYWHERE"
+ "PI_TEXTURE_STYLE_DEBUG_DUMP_DIRECTORY"
+ "PI_TEXTURE_STYLE_ENABLED_EFFECTS"
+ "PI_TEXTURE_STYLE_ENABLE_DEBUG_DUMP"
+ "PI_TEXTURE_STYLE_ENABLE_TILED_RENDERING"
+ "PhotographicStyleV2"
+ "Primary geometry is required to configure the disparity provider"
+ "Quality is required to configure the disparity provider"
+ "Rect"
+ "Render time is required"
+ "Soft"
+ "Studio"
+ "Tap-to-track: starting asset reader (hasDisparityTrack=%d)"
+ "Texture Style not supported on current platform"
+ "Texture Style requires using the modular pipeline"
+ "TextureStyle"
+ "TextureStyleImageStatistics"
+ "TextureStyle~1.0"
+ "Unexpected extents count"
+ "Unexpected number of inputs"
+ "Unknown mask type for input %lu, skipping"
+ "Unknown preset %@, returning empty effect ordering"
+ "[TextureStyle ROI] Returning full inputExtent for LinearThumbnail: %@"
+ "[TextureStyle ROI] computeMinimumInputRegionInFullImageCoords status: %d"
+ "[TextureStyle ROI] input: %d outputRect %@"
+ "[TextureStyle ROI] inputExtent (from extents[%d]): %@"
+ "[TextureStyle ROI] inputImageRect: %@"
+ "[TextureStyle ROI] inputRegion: %@"
+ "[TextureStyle ROI] outputExtent: %@"
+ "[TextureStyle ROI] regionToRender: %@"
+ "[TextureStyle ROI] roi (scaled from fullImageRect): %@"
+ "[TextureStyle] -[FigMetalAllocatorBackend setupWithDescriptor:] failed with err:%d"
+ "[TextureStyle] Could not create CMIExternalMemoryResource"
+ "[TextureStyle] Could not create FigMetalAllocatorBackend"
+ "[TextureStyle] Could not create FigMetalAllocatorBackendDescriptor"
+ "[TextureStyle] Failed to create memory resource, using internal resource"
+ "[TextureStyle] Failed to prepare texture style processor with status %d"
+ "[TextureStyle] Failed to process person instance data, proceeding with no data"
+ "[TextureStyle] Failed to process texture style processor with status %d"
+ "[TextureStyle] Failed to setup processor: %d"
+ "[TextureStyle] Missing person data - some effects may be skipped"
+ "[TextureStyle] Missing person instance mask for key %@ - using empty image"
+ "[TextureStyle] Unexpected nil texture for person instance %@ - skipping"
+ "[TextureStyle] Unknown effect name in EffectOrder: %@"
+ "[TextureStyle] Using new PITextureStyleProcessor instance: %p"
+ "[TextureStyle] Using pooled PITextureStyleProcessor instance: %p"
+ "[TextureStyle] Workaround: swapped Diffusion/Halation order: %{public}@"
+ "[TextureStyle] inputImage.region: %@ (texture: %zux%zu)"
+ "[TextureStyle] inputLinearImage.region: %@"
+ "[TextureStyle] inputMask[%@].region: %@ (texture: %zux%zu)"
+ "[TextureStyle] regionToRender: %@, usage: %@"
+ "[TextureStyle] roiForInput:%d - computation failed (status=%d), falling back to outputRect"
+ "_PISemanticStyleAdjustmentExpressionFunction"
+ "_PITextureStyleSettingsExpressionFunction"
+ "_texture"
+ "accumulatedState"
+ "accumulatedStateProcessor"
+ "accumulatedStateProcessor:<accumulatedState"
+ "accumulatedStateProcessor:>accumulatedState"
+ "all"
+ "changesDictionary"
+ "cinematicVideoV2:<adjustment"
+ "cinematicVideoV2:<cinematography"
+ "cinematicVideoV2:<highQuality"
+ "cinematicVideoV2:<primary"
+ "cinematicVideoV2:<useRefinedCinematography"
+ "cinematicVideoV2:>primary"
+ "cinematographyScriptSnapshot"
+ "computedDisparity"
+ "defaultTextureStyle"
+ "disparityBuffer != nil"
+ "disparityBufferCache"
+ "disparityCacheRetriever"
+ "disparityCacheRetriever:<accumulatedState"
+ "disparityCacheRetriever:<cinematicGlobalRenderingMetadata"
+ "disparityCacheRetriever:<primaryGeometry"
+ "disparityCacheRetriever:<renderTime"
+ "disparityMaterializer"
+ "disparityMaterializer:<cinematicGlobalRenderingMetadata"
+ "disparityMaterializer:<computedDisparity"
+ "disparityMaterializer:<primaryGeometry"
+ "disparityMaterializer:<quality"
+ "disparityProcessor"
+ "disparityProcessor:<cinematicGlobalRenderingMetadata"
+ "disparityProcessor:<cinematography"
+ "disparityProcessor:<colorSpace"
+ "disparityProcessor:<isSeeking"
+ "disparityProcessor:<primary"
+ "disparityProcessor:<quality"
+ "disparityProcessor:<renderTime"
+ "disparityProcessor:>computedDisparity"
+ "disparityProvider"
+ "effectDescriptors"
+ "faceInfoTimedMetadata"
+ "fastFocusDisparityProcessor"
+ "fastFocusDisparityProcessor:<cinematography"
+ "fastFocusDisparityProcessor:<disparity"
+ "fastFocusDisparityProcessor:<renderTime"
+ "generation"
+ "global-still"
+ "globalEffectsOnly"
+ "globalRenderingData"
+ "grainIntensity"
+ "inputHeight"
+ "inputSize"
+ "inputWidth"
+ "isSeeking"
+ "isVideo"
+ "linearHighKey"
+ "linearThumbnail:output"
+ "livePhotoInfo"
+ "local-still"
+ "local-video"
+ "localEffectsOnly"
+ "lookAheadCinematographyTrimPipeline"
+ "lookAheadCinematographyTrimPipeline:<end"
+ "lookAheadCinematographyTrimPipeline:<media"
+ "lookAheadCinematographyTrimPipeline:<start"
+ "lookAheadCinematographyTrimPipeline:>media"
+ "lookAheadTrimPipeline"
+ "lookAheadTrimPipeline:<end"
+ "lookAheadTrimPipeline:<media"
+ "lookAheadTrimPipeline:<start"
+ "lookAheadTrimPipeline:>media"
+ "mattify"
+ "mattify:primary"
+ "outFocusDisparity != NULL"
+ "photograhicStyleVideoMode"
+ "photographicStyleApply"
+ "photographicStyleApply:<primary"
+ "photographicStyleApply:>primary"
+ "photographicStyleLearn"
+ "photographicStyleLearn:>style"
+ "photographicStyleLearn:defaultSemanticStyle"
+ "photographicStyleLearn:defaultTextureStyle"
+ "photographicStyleV2KeyFrame"
+ "photographicStyleV2KeyFrame:<applyCleanAperture"
+ "photographicStyleV2KeyFrame:<time"
+ "photographicStyleV2KeyFrame:video"
+ "photographicStyleV2KeyFrameBypass"
+ "post-target-video"
+ "postTargetEffectsOnly"
+ "postcaptureRefinementProcessor"
+ "postcaptureRefinementProcessor:<changesDictionary"
+ "postcaptureRefinementProcessor:<cinematicGlobalRenderingMetadata"
+ "postcaptureRefinementProcessor:<cinematography"
+ "postcaptureRefinementProcessor:<colorSpace"
+ "postcaptureRefinementProcessor:<primary"
+ "postcaptureRefinementProcessor:<quality"
+ "postcaptureRefinementProcessor:<videoURL"
+ "postcaptureRefinementProcessor:>accumulatedState"
+ "pre-target-video"
+ "preTargetEffectsOnly"
+ "preset"
+ "primaryGeometry"
+ "refined"
+ "refinement"
+ "refinementFocusDisparityProcessor"
+ "refinementFocusDisparityProcessor:<accumulatedState"
+ "refinementFocusDisparityProcessor:<cinematicGlobalRenderingMetadata"
+ "refinementFocusDisparityProcessor:<cinematography"
+ "refinementFocusDisparityProcessor:<colorSpace"
+ "refinementFocusDisparityProcessor:<primary"
+ "refinementFocusDisparityProcessor:<renderTime"
+ "render"
+ "roi"
+ "samples != nil"
+ "semanticStyleAdjustment"
+ "semanticStyleAdjustment.cast"
+ "semanticStyleAdjustment.color"
+ "semanticStyleAdjustment.enabled"
+ "semanticStyleAdjustment.intensity"
+ "semanticStyleAdjustment.tone"
+ "semanticStyleAdjustment.version"
+ "semanticStyleApply:adjustment"
+ "semanticStyleApply:primary"
+ "semanticStyleApply:style"
+ "semanticStyleCast"
+ "semanticStyleColor"
+ "semanticStyleMetadata"
+ "semanticStyleProperties"
+ "semanticStyleTarget"
+ "semanticStyleTarget:cast"
+ "semanticStyleTarget:color"
+ "semanticStyleTarget:inputImage"
+ "semanticStyleTarget:intensity"
+ "semanticStyleTarget:linearThumbnail"
+ "semanticStyleTarget:output"
+ "semanticStyleTarget:portraitMatte"
+ "semanticStyleTarget:skinMatte"
+ "semanticStyleTarget:skyMatte"
+ "semanticStyleTarget:tone"
+ "semanticStyleTarget:version"
+ "semanticStyleTimedMetadata"
+ "target-still"
+ "textureStyle"
+ "textureStyleAdjustment"
+ "textureStyleAdjustment.enabled"
+ "textureStyleGlobal"
+ "textureStyleGlobal:>primary"
+ "textureStyleLocal"
+ "textureStyleLocal:primary"
+ "textureStyleMetadata"
+ "textureStyleProcessor"
+ "textureStyleProcessor:"
+ "textureStyleProcessor:grainIntensity"
+ "textureStyleProcessor:intensity"
+ "textureStyleProcessor:preset"
+ "textureStyleProcessor:primary"
+ "textureStyleProcessor:semanticStyleCast"
+ "textureStyleProcessor:semanticStyleColor"
+ "textureStyleProcessor:semanticStyleMetadata"
+ "textureStyleProcessor:textureStyleMetadata"
+ "textureStyleProperties"
+ "textureStyleTarget"
+ "textureStyleTarget:>default"
+ "textureStyleTarget:>primary"
+ "textureStyleTimedMetadata"
+ "textureStyleVideoMode"
+ "thumbnail:cast"
+ "thumbnail:color"
+ "thumbnail:inputImage"
+ "thumbnail:intensity"
+ "thumbnail:output"
+ "thumbnail:tone"
+ "thumbnail:version"
+ "timedFocusDisparityProcessor"
+ "timedFocusDisparityProcessor:<cinematography"
+ "timedFocusDisparityProcessor:<cinematographySnapshot"
+ "timedFocusDisparityProcessor:<disparity"
+ "timedFocusDisparityProcessor:<renderTime"
+ "timedFocusDisparityProcessor:<videoURL"
+ "v16@?0@\"PITextureStyleAdjustmentController\"8"
+ "v16@?0@\"PTCinematographyScriptSnapshot\"8"
+ "v32@?0@\"<NUTextureStylePersonInstanceProperties>\"8Q16^B24"
+ "v32@?0@\"CMITextureStylesPersonInputData\"8Q16^B24"
- "Color-only tap-to-track requires a newer Portrait framework"
- "Disparity provider and cinematography snapshot unavailable"
- "Invalid input node"
```
