## NeutrinoCore

> `/System/Library/PrivateFrameworks/NeutrinoCore.framework/NeutrinoCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f7688` | `0x30b6a4` | **`+0x1401c`** |
| `__TEXT.__cstring` | `0x3bf3e` | `0x3d642` | **`+0x1704`** |
| `__AUTH_CONST.__objc_const` | `0x34ae8` | `0x35f28` | **`+0x1440`** |
| `__TEXT.__objc_methlist` | `0x1f1a4` | `0x201dc` | **`+0x1038`** |
| `__AUTH_CONST.__cfstring` | `0x1b900` | `0x1c840` | **`+0xf40`** |
| `__TEXT.__oslogstring` | `0x4e1c` | `0x537e` | **`+0x562`** |
| `__DATA_CONST.__objc_selrefs` | `0xad20` | `0xb280` | **`+0x560`** |
| `__AUTH.__objc_data` | `0x4b0` | `0x9b0` | **`+0x500`** |
| `__TEXT.__unwind_info` | `0x8010` | `0x83f8` | **`+0x3e8`** |
| `__AUTH_CONST.__const` | `0x4b18` | `0x4e58` | **`+0x340`** |
| `__DATA_CONST.__const` | `0x3c90` | `0x3ed0` | **`+0x240`** |
| `__TEXT.__gcc_except_tab` | `0x7cd4` | `0x7e84` | **`+0x1b0`** |
| `__TEXT.__const` | `0x2620` | `0x2708` | **`+0xe8`** |
| `__DATA.__objc_ivar` | `0x188c` | `0x1964` | **`+0xd8`** |
| `__AUTH_CONST.__objc_intobj` | `0x840` | `0x8d0` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x2160` | `0x21f0` | **`+0x90`** |
| `__DATA_CONST.__objc_classlist` | `0x1538` | `0x15b0` | **`+0x78`** |
| `__DATA.__data` | `0x37d8` | `0x3838` | **`+0x60`** |
| `__DATA_CONST.__objc_superrefs` | `0xf88` | `0xfe0` | **`+0x58`** |
| `__DATA_DIRTY.__objc_data` | `0xcf80` | `0xcf30` | **`-0x50`** |
| `__DATA.__bss` | `0xe50` | `0xe90` | **`+0x40`** |
| `__AUTH_CONST.__objc_dictobj` | `0x370` | `0x348` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1098` | `0x10b8` | **`+0x20`** |
| `__AUTH_CONST.__objc_floatobj` | `0x60` | `0x70` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0xae8` | `0xae0` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x4e8` | `0x4f0` | **`+0x8`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Functions: 11247
-  Symbols:   19777
-  CStrings:  6930
+  Functions: 11635
+  Symbols:   20365
+  CStrings:  7145
Symbols:
+ +[NUChannelExpression abs:]
+ +[NUChannelExpression clamp:min:max:]
+ +[NUChannelExpression number:]
+ +[NUChannelExpression smoothStep:]
+ +[NUChannelExpression smoothStep:edge0:edge1:]
+ +[NUChannelExpression step:]
+ +[NUChannelExpression step:edge:]
+ +[NUGlobalSettings enableConcurrentAudioExport]
+ +[NUGlobalSettings setEnableConcurrentAudioExport:]
+ +[NUHDRColorVolumeFilter volumeClipKernel]
+ +[NUHDRColorVolumeFilter volumeWarnKernel]
+ +[NUHDRLumaCorrectionFilter lumaCorrectionKernel]
+ +[NUHDRLumaRatioFilter convertFromLinearYPbPr:]
+ +[NUHDRLumaRatioFilter convertToLinearYPbPr:]
+ +[NUObjectPointerArray strongObjectsPointerArray]
+ +[NUObjectPointerArray unretainedObjectsPointerArray]
+ +[NUObjectPointerArray weakObjectsPointerArray]
+ +[NUPipelineFactory _buildCacheNodePipelineForClass:baseSettings:error:]
+ +[NUPipelineFactory colorVolumePipeline]
+ +[NUPipelineFactory gainMapComputePipelineWithOptions:]
+ +[NUPipelineFactory gainMapComputePipeline]
+ +[NUPipelineFactory memoryCachePipelineWithOptions:]
+ +[NUPipelineFactory playbackRateDescriptor]
+ +[NURunQueueConfiguration defaultConcurrentConfiguration]
+ +[NURunQueueConfiguration defaultSerialConfiguration]
+ +[NURunQueueLaneID background]
+ +[NURunQueueLaneID userInitiated]
+ +[NURunQueueLaneID userInteractive]
+ +[NURunQueueLaneID utility]
+ +[NUStyleTransferApplyNode applyStyle:toImage:thumbnail:target:deltaMap:displacement:colorSpace:configuration:tuningParameters:noiseModel:error:]
+ +[NUStyleTransferLearnNode learnStyleFromInputThumbnail:targetThumbnail:colorSpace:configuration:tuningParameters:error:]
+ +[NUStyleTransferPipeline colorSpaceFromControlData:]
+ +[NUStyleTransferPipeline configurationDescriptor]
+ +[NUStyleTransferPipeline configurationFromControlData:]
+ +[NUStyleTransferThumbnailNode generateThumbnailForImage:targetSize:colorSpace:configuration:tuningParameters:error:]
+ +[_NUHDRColorVolumePipeline clippingChannel]
+ +[_NUHDRColorVolumePipeline headroomChannel]
+ +[_NUHDRGainMapComputePipeline hdrImageChannel]
+ +[_NUHDRGainMapComputePipeline metadataChannel]
+ +[_NUHDRGainMapComputePipeline sdrImageChannel]
+ +[_NUHDRToneMapApplyPipeline intensityChannel]
+ +[_NUPlaybackRatePipeline transformDescriptor]
+ +[_NURenderNodePipeline pipelineWithRenderNodeClassName:baseSettings:error:]
+ +[_NUStyleTransferApplyProcessor applyStyle:toImage:thumbnail:target:deltaMap:displacement:colorSpace:configuration:tuningParameters:noiseModel:error:]
+ -[CIImage(Debug) nu_readFirstPixel]
+ -[NUAuxiliaryImageRenderJob wantsRenderScaleRelativeToNativeScale]
+ -[NUAuxiliaryImageRenderRequest .cxx_destruct]
+ -[NUAuxiliaryImageRenderRequest scalePolicy]
+ -[NUAuxiliaryImageRenderRequest setScalePolicy:]
+ -[NUChannelExpression detachFromPort:]
+ -[NUChannelExpression isDetached]
+ -[NUChannelMathFunctionExpression hash]
+ -[NUChannelMathFunctionExpression isEqualToExpression:]
+ -[NUChannelMathFunctionExpression isEqualToMathFunctionExpression:]
+ -[NUChannelMathFunctionExpression(StandardFunctions) abs_argc]
+ -[NUChannelMathFunctionExpression(StandardFunctions) abs_func]
+ -[NUChannelMathFunctionExpression(StandardFunctions) clamp_argc]
+ -[NUChannelMathFunctionExpression(StandardFunctions) clamp_func]
+ -[NUChannelMathFunctionExpression(StandardFunctions) smoothstep01_argc]
+ -[NUChannelMathFunctionExpression(StandardFunctions) smoothstep01_func]
+ -[NUChannelMathFunctionExpression(StandardFunctions) smoothstep_argc]
+ -[NUChannelMathFunctionExpression(StandardFunctions) smoothstep_func]
+ -[NUChannelMathFunctionExpression(StandardFunctions) step0_argc]
+ -[NUChannelMathFunctionExpression(StandardFunctions) step0_func]
+ -[NUChannelMathFunctionExpression(StandardFunctions) step_argc]
+ -[NUChannelMathFunctionExpression(StandardFunctions) step_func]
+ -[NUChannelStaticExpression _detach]
+ -[NUChannelStaticExpression detachFromPort:]
+ -[NUChannelStaticExpression isDetached]
+ -[NUCompoundDescriptor defaultValueType]
+ -[NUDevice identifier]
+ -[NUExportJob executionTarget]
+ -[NUGlobalSettings rawDecodeDisableV9]
+ -[NUGlobalSettings rawDecodeEnableDefaultV9]
+ -[NUGlobalSettings schedulerEnableRunQueues]
+ -[NUGlobalSettings setRawDecodeDisableV9:]
+ -[NUGlobalSettings setRawDecodeEnableDefaultV9:]
+ -[NUGlobalSettings setSchedulerEnableRunQueues:]
+ -[NUHDRColorVolumeFilter .cxx_destruct]
+ -[NUHDRColorVolumeFilter colorSpace]
+ -[NUHDRColorVolumeFilter headroom]
+ -[NUHDRColorVolumeFilter inputImage]
+ -[NUHDRColorVolumeFilter outputImage]
+ -[NUHDRColorVolumeFilter setColorSpace:]
+ -[NUHDRColorVolumeFilter setHeadroom:]
+ -[NUHDRColorVolumeFilter setInputImage:]
+ -[NUHDRColorVolumeFilter setShowClippedColors:]
+ -[NUHDRColorVolumeFilter showClippedColors]
+ -[NUHDRConvertToLumaFilter colorSpace]
+ -[NUHDRConvertToLumaFilter setColorSpace:]
+ -[NUHDRLumaCorrectionFilter .cxx_destruct]
+ -[NUHDRLumaCorrectionFilter inputImage]
+ -[NUHDRLumaCorrectionFilter inputTargetImage]
+ -[NUHDRLumaCorrectionFilter outputImage]
+ -[NUHDRLumaCorrectionFilter setInputImage:]
+ -[NUHDRLumaCorrectionFilter setInputTargetImage:]
+ -[NUHDRLumaScaleByRatioFilter intensity]
+ -[NUHDRLumaScaleByRatioFilter setIntensity:]
+ -[NUHDROpticalScaleNode contentHeadroom]
+ -[NUHDROpticalScaleNode initWithInput:opticalScale:contentHeadroom:]
+ -[NUHDRTargetHeadroomNode initWithBase:alternate:sourceHeadroom:targetHeadroom:]
+ -[NUMemoryProcessorCacheNode _evaluateImage:]
+ -[NUMemoryProcessorCacheNode alphaMode]
+ -[NUMemoryProcessorCacheNode colorSpace]
+ -[NUMemoryProcessorCacheNode disableSubsampling]
+ -[NUMemoryProcessorCacheNode isTiled]
+ -[NUMemoryProcessorCacheNode pixelFormat]
+ -[NUMemoryProcessorCacheNode subsampleFactorForScale:]
+ -[NUMemoryProcessorCacheNode wantsDependentJob]
+ -[NUObjectPointerArray .cxx_destruct]
+ -[NUObjectPointerArray addObject:]
+ -[NUObjectPointerArray allObjects]
+ -[NUObjectPointerArray compact]
+ -[NUObjectPointerArray containsObject:]
+ -[NUObjectPointerArray countByEnumeratingWithState:objects:count:]
+ -[NUObjectPointerArray count]
+ -[NUObjectPointerArray debugDescription]
+ -[NUObjectPointerArray description]
+ -[NUObjectPointerArray indexOfObject:]
+ -[NUObjectPointerArray initWithPointerArray:]
+ -[NUObjectPointerArray objectAtIndex:]
+ -[NUObjectPointerArray removeAllObjects]
+ -[NUObjectPointerArray removeObject:]
+ -[NUObjectPointerArray removeObjectAtIndex:]
+ -[NUPipelineIntermediateNode _setupRenderContext]
+ -[NUPipelineIntermediateNode _setupResultQueue]
+ -[NUPipelineIntermediateNode _setupSharedRenderContext:]
+ -[NUPipelineIntermediateNode setupStandaloneRenderNode]
+ -[NUPriority initWithQoSClass:order:]
+ -[NUPriority qosClass]
+ -[NUProcessorCache alphaMode]
+ -[NUProcessorCache setAlphaMode:]
+ -[NUProviderCacheNode disableSubsampling]
+ -[NUProviderCacheNode subsampleFactorForScale:]
+ -[NURAWImageSourceNode _addCacheNode:sourceSettings:]
+ -[NURAWImageSourceNode _filterAvailableRawDecodeVersions:]
+ -[NURAWImageSourceNode _validateRawDecodeVersion:availableVersions:]
+ -[NURenderContext _setTemporalScope:]
+ -[NURenderContext setTemporalScope:]
+ -[NURenderContext temporalScope]
+ -[NURenderContextTemporalScope .cxx_destruct]
+ -[NURenderContextTemporalScope identifier]
+ -[NURenderContextTemporalScope initWithIdentifier:]
+ -[NURenderContextTemporalScope init]
+ -[NURenderContextTemporalScope processorCache]
+ -[NURenderJob abortExecute]
+ -[NURenderJob execute:]
+ -[NURenderJob executionTarget]
+ -[NURenderJob groupNumber]
+ -[NURenderJob setTemporalScope:]
+ -[NURenderJob setVideoFrameContext:]
+ -[NURenderJob temporalScope]
+ -[NURenderJob useRunQueues]
+ -[NURenderJob videoFrameContext]
+ -[NURenderJob wantsRenderScaleRelativeToNativeScale]
+ -[NURenderNodeDependencyEvaluationContext renderSession]
+ -[NURenderNodeDependencyEvaluationContext temporalScope]
+ -[NURenderPipelineState setTemporalScope:]
+ -[NURenderPipelineState temporalScope]
+ -[NURunQueue .cxx_destruct]
+ -[NURunQueue _addJob:]
+ -[NURunQueue _addJobs:]
+ -[NURunQueue _indexOfLane:]
+ -[NURunQueue _laneForPriority:]
+ -[NURunQueue _pauseAllLanes]
+ -[NURunQueue _pause]
+ -[NURunQueue _reprioritizeJob:fromLane:toLane:]
+ -[NURunQueue _reprioritizeJob:withinLane:]
+ -[NURunQueue _resumeAllLanes]
+ -[NURunQueue _resumeOneLane]
+ -[NURunQueue _resume]
+ -[NURunQueue addJob:]
+ -[NURunQueue addJobs:]
+ -[NURunQueue beginBatch]
+ -[NURunQueue delegate]
+ -[NURunQueue description]
+ -[NURunQueue endBatch]
+ -[NURunQueue initWithConfiguration:name:]
+ -[NURunQueue lane:shouldForwardJob:afterStage:]
+ -[NURunQueue laneDidBecomeIdle:]
+ -[NURunQueue name]
+ -[NURunQueue removeJob:]
+ -[NURunQueue removeJob:atStage:]
+ -[NURunQueue reprioritizeJob:fromPriority:]
+ -[NURunQueue setDelegate:]
+ -[NURunQueueConfiguration .cxx_destruct]
+ -[NURunQueueConfiguration canRunLanesConcurrently]
+ -[NURunQueueConfiguration description]
+ -[NURunQueueConfiguration init]
+ -[NURunQueueConfiguration lanes]
+ -[NURunQueueConfiguration maxConcurrentJobs]
+ -[NURunQueueConfiguration setCanRunLanesConcurrently:]
+ -[NURunQueueConfiguration setLanes:]
+ -[NURunQueueConfiguration setMaxConcurrentJobs:]
+ -[NURunQueueLane .cxx_destruct]
+ -[NURunQueueLane _addJob:]
+ -[NURunQueueLane _addJobs:]
+ -[NURunQueueLane _description]
+ -[NURunQueueLane _handleJobCompletion:inStage:]
+ -[NURunQueueLane _hasActiveJobs]
+ -[NURunQueueLane _isIdle]
+ -[NURunQueueLane _pause]
+ -[NURunQueueLane _pendingCount]
+ -[NURunQueueLane _removeJob:]
+ -[NURunQueueLane _reprioritizeJob:]
+ -[NURunQueueLane _resume]
+ -[NURunQueueLane _stageForJobStage:]
+ -[NURunQueueLane addJob:]
+ -[NURunQueueLane addJobs:]
+ -[NURunQueueLane capacity]
+ -[NURunQueueLane completeStage]
+ -[NURunQueueLane dealloc]
+ -[NURunQueueLane description]
+ -[NURunQueueLane executeStage]
+ -[NURunQueueLane hasActiveJobs]
+ -[NURunQueueLane initWithRunQueue:laneID:configuration:]
+ -[NURunQueueLane isPaused]
+ -[NURunQueueLane laneID]
+ -[NURunQueueLane name]
+ -[NURunQueueLane pause]
+ -[NURunQueueLane pendingCount]
+ -[NURunQueueLane prepareStage]
+ -[NURunQueueLane removeJob:]
+ -[NURunQueueLane removeJob:atStage:]
+ -[NURunQueueLane reprioritizeJob:]
+ -[NURunQueueLane resume]
+ -[NURunQueueLane signpostID]
+ -[NURunQueueLane stage:didRunJob:]
+ -[NURunQueueLaneID compare:]
+ -[NURunQueueLaneID description]
+ -[NURunQueueLaneID hash]
+ -[NURunQueueLaneID initWithQoSClass:]
+ -[NURunQueueLaneID init]
+ -[NURunQueueLaneID isEqual:]
+ -[NURunQueueLaneID isEqualToLaneID:]
+ -[NURunQueueLaneID name]
+ -[NURunQueueLaneID qosClass]
+ -[NURunQueueStage .cxx_destruct]
+ -[NURunQueueStage _dequeueNextAdmissibleJob]
+ -[NURunQueueStage _dispatchJob:]
+ -[NURunQueueStage _finishJob:]
+ -[NURunQueueStage _hasRunningJobWithGroup:]
+ -[NURunQueueStage _signpostBeginRun:]
+ -[NURunQueueStage _signpostBeginWait:]
+ -[NURunQueueStage _signpostEndRun:]
+ -[NURunQueueStage _signpostEndWait:]
+ -[NURunQueueStage _sortIfNeeded]
+ -[NURunQueueStage addJob:]
+ -[NURunQueueStage description]
+ -[NURunQueueStage initWithLane:jobStage:]
+ -[NURunQueueStage isBackPressured]
+ -[NURunQueueStage isEmpty]
+ -[NURunQueueStage jobStage]
+ -[NURunQueueStage name]
+ -[NURunQueueStage nextStage]
+ -[NURunQueueStage previousStage]
+ -[NURunQueueStage removeJob:]
+ -[NURunQueueStage reprioritizeJob:]
+ -[NURunQueueStage run]
+ -[NURunQueueStage runningCount]
+ -[NURunQueueStage setNextStage:]
+ -[NURunQueueStage setPreviousStage:]
+ -[NURunQueueStage waitingCount]
+ -[NUScheduler _batchEnqueueJobs:]
+ -[NUScheduler _beginBatch]
+ -[NUScheduler _defaultConfigurationForExecutionTarget:]
+ -[NUScheduler _endBatch]
+ -[NUScheduler _enqueueNewJobs:]
+ -[NUScheduler _ensureRunQueueForJob:]
+ -[NUScheduler _runQueueForJob:]
+ -[NUScheduler _runQueueIdentifierForExecutionTarget:device:]
+ -[NUScheduler enqueueReleasedJobs:]
+ -[NUScheduler runQueue:shouldForwardJob:afterStage:]
+ -[NUStyleTransferPipeline initWithIdentifier:]
+ -[NUStyleTransferPipeline init]
+ -[NUVideoAccumulationFrameJob accumulate:]
+ -[NUVideoAccumulationFrameJob execute:]
+ -[NUVideoExportJob abortExecute]
+ -[NUVideoExportJob execute:]
+ -[NUVideoExporter _export:]
+ -[NUVideoExporter _exportAudioTrack:toURL:error:]
+ -[NUVideoExporter exportAudioTrack:completionQueue:completion:]
+ -[_NUAccumulationComputeJob _extractAccumulatedData:]
+ -[_NUAccumulationComputeJob abortExecute]
+ -[_NUAccumulationComputeJob complete:]
+ -[_NUAccumulationComputeJob execute:]
+ -[_NUAccumulationComputeJob executionTarget]
+ -[_NUCachePipeline cacheNodeBaseSettings]
+ -[_NUChannelPort _addReferencingPort:]
+ -[_NUChannelPort _clearExpression]
+ -[_NUChannelPort _detachExpressionFromPort:]
+ -[_NUChannelPort _detachFromPipeline]
+ -[_NUChannelPort _registerExpressionReferences]
+ -[_NUChannelPort _removeReferencingPort:]
+ -[_NUChannelPort _unregisterExpressionReferences]
+ -[_NUChannelPort attachToPipeline:]
+ -[_NUChannelPort detachFromPipeline:]
+ -[_NUComputeJob abortExecute]
+ -[_NUComputeJob compute:]
+ -[_NUComputeJob execute:]
+ -[_NUComputeJob executionTarget]
+ -[_NUCoreImageComputeJob abortExecute]
+ -[_NUCoreImageComputeJob compute:]
+ -[_NUCoreImageComputeJob execute:]
+ -[_NUCoreImageComputeJob executionTarget]
+ -[_NUHDRColorVolumePipeline _evaluateOutputPort:context:error:]
+ -[_NUHDRColorVolumePipeline alias]
+ -[_NUHDRColorVolumePipeline initWithIdentifier:]
+ -[_NUHDRColorVolumePipeline init]
+ -[_NUHDRGainMapComputePipeline _evaluateOutputPort:context:error:]
+ -[_NUHDRGainMapComputePipeline alias]
+ -[_NUHDRGainMapComputePipeline initWithIdentifier:]
+ -[_NUHDRGainMapComputePipeline initWithOptions:]
+ -[_NUMemoryCachePipeline .cxx_destruct]
+ -[_NUMemoryCachePipeline cacheNodeBaseSettings]
+ -[_NUMemoryCachePipeline initWithOptions:]
+ -[_NUMemoryCachePipeline options]
+ -[_NUMemoryCachePipeline setOptions:]
+ -[_NUMemoryCachePipeline usesProcessor]
+ -[_NUPipeline dealloc]
+ -[_NURawDecodePipeline rawCacheModeWithOptions:version:]
+ -[_NURenderNodePipeline baseSettings]
+ -[_NURenderNodePipeline initWithRenderNodeClass:baseSettings:identifier:]
+ -[_NUStyleTransferApplyPipelineProcessor inputChannels]
+ -[_NUStyleTransferApplyPipelineProcessor isInputChannelRequired:]
+ -[_NUStyleTransferApplyPipelineProcessor mainInput]
+ -[_NUStyleTransferApplyPipelineProcessor outputChannel]
+ -[_NUStyleTransferApplyPipelineProcessor outputImageWithInputs:controlData:error:]
+ -[_NUStyleTransferApplyPipelineProcessor renderScaleForInput:geometry:outputScale:]
+ -[_NUStyleTransferConfigurationFunction evaluateWithArguments:error:]
+ -[_NUStyleTransferConfigurationFunction format]
+ -[_NUStyleTransferLearnPipelineProcessor inputChannels]
+ -[_NUStyleTransferLearnPipelineProcessor isInputChannelRequired:]
+ -[_NUStyleTransferLearnPipelineProcessor mainInput]
+ -[_NUStyleTransferLearnPipelineProcessor outputChannel]
+ -[_NUStyleTransferLearnPipelineProcessor outputGeometryWithInputGeometry:controlData:error:]
+ -[_NUStyleTransferLearnPipelineProcessor outputImageWithInputs:controlData:error:]
+ -[_NUStyleTransferLearnPipelineProcessor renderScaleForInput:geometry:outputScale:]
+ -[_NUStyleTransferThumbnailPipelineProcessor inputChannels]
+ -[_NUStyleTransferThumbnailPipelineProcessor isInputChannelRequired:]
+ -[_NUStyleTransferThumbnailPipelineProcessor outputChannel]
+ -[_NUStyleTransferThumbnailPipelineProcessor outputGeometryWithInputGeometry:controlData:error:]
+ -[_NUStyleTransferThumbnailPipelineProcessor outputImageWithInputs:controlData:error:]
+ -[_NUStyleTransferThumbnailPipelineProcessor renderScaleForInput:geometry:outputScale:]
+ GCC_except_table10119
+ GCC_except_table10120
+ GCC_except_table10126
+ GCC_except_table10127
+ GCC_except_table10129
+ GCC_except_table10130
+ GCC_except_table10227
+ GCC_except_table10228
+ GCC_except_table10231
+ GCC_except_table10232
+ GCC_except_table10233
+ GCC_except_table10234
+ GCC_except_table10235
+ GCC_except_table10236
+ GCC_except_table10238
+ GCC_except_table10241
+ GCC_except_table10242
+ GCC_except_table10244
+ GCC_except_table10245
+ GCC_except_table10246
+ GCC_except_table10248
+ GCC_except_table10249
+ GCC_except_table10259
+ GCC_except_table10260
+ GCC_except_table10265
+ GCC_except_table10266
+ GCC_except_table10267
+ GCC_except_table10268
+ GCC_except_table10270
+ GCC_except_table10271
+ GCC_except_table10272
+ GCC_except_table10273
+ GCC_except_table10275
+ GCC_except_table10276
+ GCC_except_table10277
+ GCC_except_table10278
+ GCC_except_table10279
+ GCC_except_table10280
+ GCC_except_table10281
+ GCC_except_table10284
+ GCC_except_table10285
+ GCC_except_table10288
+ GCC_except_table10289
+ GCC_except_table10290
+ GCC_except_table10296
+ GCC_except_table10297
+ GCC_except_table10298
+ GCC_except_table10299
+ GCC_except_table10300
+ GCC_except_table10301
+ GCC_except_table10303
+ GCC_except_table10305
+ GCC_except_table10306
+ GCC_except_table10307
+ GCC_except_table10312
+ GCC_except_table10313
+ GCC_except_table10314
+ GCC_except_table10315
+ GCC_except_table10316
+ GCC_except_table10318
+ GCC_except_table10319
+ GCC_except_table10320
+ GCC_except_table10321
+ GCC_except_table10322
+ GCC_except_table10323
+ GCC_except_table10324
+ GCC_except_table10325
+ GCC_except_table10330
+ GCC_except_table10331
+ GCC_except_table10332
+ GCC_except_table10333
+ GCC_except_table10334
+ GCC_except_table10335
+ GCC_except_table10381
+ GCC_except_table10432
+ GCC_except_table105
+ GCC_except_table10509
+ GCC_except_table10513
+ GCC_except_table106
+ GCC_except_table1068
+ GCC_except_table108
+ GCC_except_table109
+ GCC_except_table10954
+ GCC_except_table11115
+ GCC_except_table11117
+ GCC_except_table11163
+ GCC_except_table11215
+ GCC_except_table11223
+ GCC_except_table11228
+ GCC_except_table11229
+ GCC_except_table11233
+ GCC_except_table1248
+ GCC_except_table1252
+ GCC_except_table1260
+ GCC_except_table1261
+ GCC_except_table1262
+ GCC_except_table1265
+ GCC_except_table1266
+ GCC_except_table1267
+ GCC_except_table1288
+ GCC_except_table1297
+ GCC_except_table1320
+ GCC_except_table1324
+ GCC_except_table1326
+ GCC_except_table1327
+ GCC_except_table1328
+ GCC_except_table1338
+ GCC_except_table1386
+ GCC_except_table1388
+ GCC_except_table1593
+ GCC_except_table1606
+ GCC_except_table1618
+ GCC_except_table1641
+ GCC_except_table1653
+ GCC_except_table1658
+ GCC_except_table170
+ GCC_except_table1747
+ GCC_except_table1750
+ GCC_except_table1759
+ GCC_except_table1781
+ GCC_except_table1806
+ GCC_except_table1807
+ GCC_except_table1868
+ GCC_except_table1990
+ GCC_except_table1991
+ GCC_except_table1992
+ GCC_except_table1993
+ GCC_except_table1994
+ GCC_except_table1996
+ GCC_except_table2021
+ GCC_except_table2074
+ GCC_except_table2179
+ GCC_except_table2180
+ GCC_except_table2671
+ GCC_except_table2736
+ GCC_except_table2784
+ GCC_except_table2796
+ GCC_except_table2955
+ GCC_except_table3102
+ GCC_except_table3182
+ GCC_except_table3189
+ GCC_except_table3190
+ GCC_except_table3191
+ GCC_except_table3192
+ GCC_except_table3196
+ GCC_except_table3197
+ GCC_except_table3200
+ GCC_except_table3203
+ GCC_except_table3204
+ GCC_except_table3206
+ GCC_except_table3211
+ GCC_except_table3212
+ GCC_except_table3213
+ GCC_except_table3214
+ GCC_except_table3224
+ GCC_except_table3227
+ GCC_except_table3228
+ GCC_except_table324
+ GCC_except_table3256
+ GCC_except_table3257
+ GCC_except_table3262
+ GCC_except_table3263
+ GCC_except_table3265
+ GCC_except_table3268
+ GCC_except_table3269
+ GCC_except_table3273
+ GCC_except_table3276
+ GCC_except_table3277
+ GCC_except_table3279
+ GCC_except_table3280
+ GCC_except_table3283
+ GCC_except_table3285
+ GCC_except_table3287
+ GCC_except_table3288
+ GCC_except_table3289
+ GCC_except_table3290
+ GCC_except_table3291
+ GCC_except_table3295
+ GCC_except_table3301
+ GCC_except_table332
+ GCC_except_table347
+ GCC_except_table3653
+ GCC_except_table3833
+ GCC_except_table387
+ GCC_except_table3902
+ GCC_except_table3906
+ GCC_except_table3908
+ GCC_except_table4045
+ GCC_except_table4053
+ GCC_except_table4054
+ GCC_except_table4059
+ GCC_except_table4065
+ GCC_except_table4070
+ GCC_except_table4093
+ GCC_except_table4100
+ GCC_except_table4105
+ GCC_except_table4107
+ GCC_except_table420
+ GCC_except_table4234
+ GCC_except_table4235
+ GCC_except_table4236
+ GCC_except_table4241
+ GCC_except_table4246
+ GCC_except_table4248
+ GCC_except_table4274
+ GCC_except_table4301
+ GCC_except_table4337
+ GCC_except_table4338
+ GCC_except_table4341
+ GCC_except_table4342
+ GCC_except_table4347
+ GCC_except_table4348
+ GCC_except_table4351
+ GCC_except_table4352
+ GCC_except_table4353
+ GCC_except_table4354
+ GCC_except_table4355
+ GCC_except_table4356
+ GCC_except_table4357
+ GCC_except_table4359
+ GCC_except_table4365
+ GCC_except_table4369
+ GCC_except_table4373
+ GCC_except_table4374
+ GCC_except_table4375
+ GCC_except_table4377
+ GCC_except_table4384
+ GCC_except_table4386
+ GCC_except_table4387
+ GCC_except_table4462
+ GCC_except_table467
+ GCC_except_table4761
+ GCC_except_table4872
+ GCC_except_table4878
+ GCC_except_table4881
+ GCC_except_table4891
+ GCC_except_table4895
+ GCC_except_table4896
+ GCC_except_table4910
+ GCC_except_table5019
+ GCC_except_table5149
+ GCC_except_table5231
+ GCC_except_table5523
+ GCC_except_table553
+ GCC_except_table5624
+ GCC_except_table5701
+ GCC_except_table5703
+ GCC_except_table5705
+ GCC_except_table5710
+ GCC_except_table5719
+ GCC_except_table5720
+ GCC_except_table5724
+ GCC_except_table577
+ GCC_except_table5770
+ GCC_except_table5810
+ GCC_except_table5815
+ GCC_except_table5834
+ GCC_except_table5836
+ GCC_except_table5837
+ GCC_except_table5842
+ GCC_except_table5843
+ GCC_except_table5845
+ GCC_except_table5846
+ GCC_except_table5855
+ GCC_except_table5858
+ GCC_except_table5859
+ GCC_except_table5860
+ GCC_except_table5861
+ GCC_except_table5862
+ GCC_except_table5863
+ GCC_except_table5864
+ GCC_except_table5865
+ GCC_except_table5866
+ GCC_except_table5868
+ GCC_except_table5869
+ GCC_except_table5870
+ GCC_except_table5871
+ GCC_except_table5872
+ GCC_except_table5873
+ GCC_except_table5874
+ GCC_except_table5875
+ GCC_except_table5876
+ GCC_except_table5877
+ GCC_except_table5878
+ GCC_except_table5879
+ GCC_except_table5880
+ GCC_except_table5885
+ GCC_except_table5886
+ GCC_except_table5892
+ GCC_except_table5893
+ GCC_except_table5898
+ GCC_except_table5899
+ GCC_except_table5900
+ GCC_except_table5902
+ GCC_except_table5903
+ GCC_except_table5904
+ GCC_except_table5905
+ GCC_except_table5906
+ GCC_except_table5911
+ GCC_except_table5912
+ GCC_except_table5913
+ GCC_except_table5914
+ GCC_except_table5916
+ GCC_except_table5917
+ GCC_except_table5921
+ GCC_except_table5922
+ GCC_except_table5923
+ GCC_except_table5924
+ GCC_except_table5925
+ GCC_except_table5927
+ GCC_except_table5928
+ GCC_except_table5930
+ GCC_except_table5932
+ GCC_except_table5935
+ GCC_except_table5936
+ GCC_except_table5937
+ GCC_except_table5938
+ GCC_except_table5939
+ GCC_except_table5941
+ GCC_except_table5943
+ GCC_except_table5944
+ GCC_except_table5946
+ GCC_except_table601
+ GCC_except_table6059
+ GCC_except_table609
+ GCC_except_table6119
+ GCC_except_table6151
+ GCC_except_table6152
+ GCC_except_table6189
+ GCC_except_table6196
+ GCC_except_table6217
+ GCC_except_table6293
+ GCC_except_table6302
+ GCC_except_table6305
+ GCC_except_table6310
+ GCC_except_table6325
+ GCC_except_table6343
+ GCC_except_table6346
+ GCC_except_table6347
+ GCC_except_table6351
+ GCC_except_table6352
+ GCC_except_table6455
+ GCC_except_table6464
+ GCC_except_table6484
+ GCC_except_table6501
+ GCC_except_table6575
+ GCC_except_table6640
+ GCC_except_table6645
+ GCC_except_table6648
+ GCC_except_table6671
+ GCC_except_table6715
+ GCC_except_table6858
+ GCC_except_table6933
+ GCC_except_table6948
+ GCC_except_table6949
+ GCC_except_table6950
+ GCC_except_table6963
+ GCC_except_table6964
+ GCC_except_table6965
+ GCC_except_table6966
+ GCC_except_table6981
+ GCC_except_table6982
+ GCC_except_table6996
+ GCC_except_table6997
+ GCC_except_table7001
+ GCC_except_table7041
+ GCC_except_table7114
+ GCC_except_table7115
+ GCC_except_table7119
+ GCC_except_table7121
+ GCC_except_table7125
+ GCC_except_table7127
+ GCC_except_table7129
+ GCC_except_table7130
+ GCC_except_table7134
+ GCC_except_table7138
+ GCC_except_table7139
+ GCC_except_table7140
+ GCC_except_table7141
+ GCC_except_table7142
+ GCC_except_table7144
+ GCC_except_table7145
+ GCC_except_table7147
+ GCC_except_table7148
+ GCC_except_table7218
+ GCC_except_table7253
+ GCC_except_table7341
+ GCC_except_table8032
+ GCC_except_table8035
+ GCC_except_table8100
+ GCC_except_table8239
+ GCC_except_table8242
+ GCC_except_table8247
+ GCC_except_table8250
+ GCC_except_table8252
+ GCC_except_table8257
+ GCC_except_table8271
+ GCC_except_table8273
+ GCC_except_table8274
+ GCC_except_table8279
+ GCC_except_table8280
+ GCC_except_table8300
+ GCC_except_table8307
+ GCC_except_table8308
+ GCC_except_table8309
+ GCC_except_table8310
+ GCC_except_table8323
+ GCC_except_table8502
+ GCC_except_table8549
+ GCC_except_table8889
+ GCC_except_table8983
+ GCC_except_table9161
+ GCC_except_table9354
+ GCC_except_table9369
+ GCC_except_table9406
+ GCC_except_table9413
+ GCC_except_table9452
+ GCC_except_table9453
+ GCC_except_table9459
+ GCC_except_table9465
+ GCC_except_table9466
+ GCC_except_table9473
+ GCC_except_table9476
+ GCC_except_table9483
+ GCC_except_table9485
+ GCC_except_table9486
+ GCC_except_table9488
+ GCC_except_table9489
+ GCC_except_table9490
+ GCC_except_table9491
+ GCC_except_table9496
+ GCC_except_table9498
+ GCC_except_table9499
+ GCC_except_table95
+ GCC_except_table9500
+ GCC_except_table9501
+ GCC_except_table9505
+ GCC_except_table9506
+ GCC_except_table9508
+ GCC_except_table9510
+ GCC_except_table9512
+ GCC_except_table9514
+ GCC_except_table9520
+ GCC_except_table9523
+ GCC_except_table9527
+ GCC_except_table9528
+ GCC_except_table9531
+ GCC_except_table9532
+ GCC_except_table9533
+ GCC_except_table9534
+ GCC_except_table9536
+ GCC_except_table9537
+ GCC_except_table9538
+ GCC_except_table9539
+ GCC_except_table9541
+ GCC_except_table9542
+ GCC_except_table9543
+ GCC_except_table9544
+ GCC_except_table9545
+ GCC_except_table9546
+ GCC_except_table9547
+ GCC_except_table9548
+ GCC_except_table9549
+ GCC_except_table9550
+ GCC_except_table9551
+ GCC_except_table9552
+ GCC_except_table9553
+ GCC_except_table9610
+ GCC_except_table9617
+ GCC_except_table9695
+ GCC_except_table9743
+ GCC_except_table9767
+ GCC_except_table9768
+ GCC_except_table9772
+ GCC_except_table9773
+ GCC_except_table9774
+ GCC_except_table9775
+ GCC_except_table9783
+ GCC_except_table9792
+ GCC_except_table9802
+ GCC_except_table9808
+ GCC_except_table9809
+ GCC_except_table9810
+ GCC_except_table9813
+ GCC_except_table9815
+ GCC_except_table9818
+ GCC_except_table9819
+ GCC_except_table9820
+ GCC_except_table9894
+ _MLAllComputeDevices
+ _NUAssetPipelineOptionRawDecodeCacheMode
+ _NUCMPhotoAuxiliaryImageTypeURN_HumanSemanticEyebrows
+ _NUChannelNameEyebrowsMatte
+ _NUGainMapComputePipelineOptionRGBGainMap
+ _NUMemoryCachePipelineOptionDisableSubsampling
+ _NUMemoryCachePipelineOptionEnableTiling
+ _NUMemoryCachePipelineOptionUseProcessor
+ _NUMemoryCachePipelineOptionUseProvider
+ _NUPixelRectFlipYOriginRelative
+ _NURawDecodeCachingStrategyAuto
+ _NURawDecodeCachingStrategyContiguousStorage
+ _NURawDecodeCachingStrategyNone
+ _NURawDecodeCachingStrategyTiledStorage
+ _NUScheduleLogger
+ _NUStyleTransferCoefficientTextureSizeForConfiguration
+ _NUVisionVMApplyComputeDeviceOverride
+ _NUVisionVMGPUComputeDevice.onceToken
+ _NUVisionVMGPUComputeDevice.sGPUDevice
+ _NUVisionVMRenderSegmentationMatte
+ _OBJC_CLASS_$_AVAssetWritingPlanner
+ _OBJC_CLASS_$_MLGPUComputeDevice
+ _OBJC_CLASS_$_NSPointerFunctions
+ _OBJC_CLASS_$_NUHDRColorVolumeFilter
+ _OBJC_CLASS_$_NUHDRLumaCorrectionFilter
+ _OBJC_CLASS_$_NUMemoryProcessorCacheNode
+ _OBJC_CLASS_$_NUObjectPointerArray
+ _OBJC_CLASS_$_NURenderContextTemporalScope
+ _OBJC_CLASS_$_NURunQueue
+ _OBJC_CLASS_$_NURunQueueConfiguration
+ _OBJC_CLASS_$_NURunQueueLane
+ _OBJC_CLASS_$_NURunQueueLaneID
+ _OBJC_CLASS_$_NURunQueueStage
+ _OBJC_CLASS_$_NUStyleTransferPipeline
+ _OBJC_CLASS_$__NUHDRColorVolumePipeline
+ _OBJC_CLASS_$__NUHDRGainMapComputePipeline
+ _OBJC_CLASS_$__NUStyleTransferApplyPipelineProcessor
+ _OBJC_CLASS_$__NUStyleTransferConfigurationFunction
+ _OBJC_CLASS_$__NUStyleTransferLearnPipelineProcessor
+ _OBJC_CLASS_$__NUStyleTransferThumbnailPipelineProcessor
+ _OBJC_IVAR_$_NUAuxiliaryImageRenderRequest._scalePolicy
+ _OBJC_IVAR_$_NUChannelStaticExpression._isDetached
+ _OBJC_IVAR_$_NUDevice._identifier
+ _OBJC_IVAR_$_NUHDRColorVolumeFilter._colorSpace
+ _OBJC_IVAR_$_NUHDRColorVolumeFilter._headroom
+ _OBJC_IVAR_$_NUHDRColorVolumeFilter._inputImage
+ _OBJC_IVAR_$_NUHDRColorVolumeFilter._showClippedColors
+ _OBJC_IVAR_$_NUHDRConvertToLumaFilter._colorSpace
+ _OBJC_IVAR_$_NUHDRLumaCorrectionFilter._inputImage
+ _OBJC_IVAR_$_NUHDRLumaCorrectionFilter._inputTargetImage
+ _OBJC_IVAR_$_NUHDRLumaScaleByRatioFilter._intensity
+ _OBJC_IVAR_$_NUObjectPointerArray._pointerArray
+ _OBJC_IVAR_$_NUPipelineIntermediateNode._renderContext
+ _OBJC_IVAR_$_NUPriority._qosClass
+ _OBJC_IVAR_$_NUProcessorCache._alphaMode
+ _OBJC_IVAR_$_NURenderContext._temporalScope
+ _OBJC_IVAR_$_NURenderContextTemporalScope._identifier
+ _OBJC_IVAR_$_NURenderContextTemporalScope._processorCache
+ _OBJC_IVAR_$_NURenderJob._temporalScope
+ _OBJC_IVAR_$_NURenderJob._useRunQueues
+ _OBJC_IVAR_$_NURenderJob._videoFrameContext
+ _OBJC_IVAR_$_NURenderPipelineState._temporalScope
+ _OBJC_IVAR_$_NURunQueue._batch
+ _OBJC_IVAR_$_NURunQueue._canRunLanesConcurrently
+ _OBJC_IVAR_$_NURunQueue._delegate
+ _OBJC_IVAR_$_NURunQueue._laneCount
+ _OBJC_IVAR_$_NURunQueue._lanes
+ _OBJC_IVAR_$_NURunQueue._name
+ _OBJC_IVAR_$_NURunQueueConfiguration._canRunLanesConcurrently
+ _OBJC_IVAR_$_NURunQueueConfiguration._lanes
+ _OBJC_IVAR_$_NURunQueueConfiguration._maxConcurrentJobs
+ _OBJC_IVAR_$_NURunQueueLane._capacity
+ _OBJC_IVAR_$_NURunQueueLane._completeStage
+ _OBJC_IVAR_$_NURunQueueLane._executeStage
+ _OBJC_IVAR_$_NURunQueueLane._laneID
+ _OBJC_IVAR_$_NURunQueueLane._name
+ _OBJC_IVAR_$_NURunQueueLane._owningRunQueue
+ _OBJC_IVAR_$_NURunQueueLane._paused
+ _OBJC_IVAR_$_NURunQueueLane._prepareStage
+ _OBJC_IVAR_$_NURunQueueLane._signpostID
+ _OBJC_IVAR_$_NURunQueueLane._stateQueue
+ _OBJC_IVAR_$_NURunQueueLaneID._qosClass
+ _OBJC_IVAR_$_NURunQueueStage._jobStage
+ _OBJC_IVAR_$_NURunQueueStage._lane
+ _OBJC_IVAR_$_NURunQueueStage._name
+ _OBJC_IVAR_$_NURunQueueStage._needSort
+ _OBJC_IVAR_$_NURunQueueStage._nextStage
+ _OBJC_IVAR_$_NURunQueueStage._previousStage
+ _OBJC_IVAR_$_NURunQueueStage._runQueue
+ _OBJC_IVAR_$_NURunQueueStage._runningJobs
+ _OBJC_IVAR_$_NURunQueueStage._waitingJobs
+ _OBJC_IVAR_$_NUScheduler._runQueues
+ _OBJC_IVAR_$_NUScheduler._useRunQueues
+ _OBJC_IVAR_$__NUChannelPort._referencingPorts
+ _OBJC_IVAR_$__NUHDRGainMapComputePipeline._generateRGBGainMap
+ _OBJC_IVAR_$__NUMemoryCachePipeline._options
+ _OBJC_IVAR_$__NURenderNodePipeline._baseSettings
+ _OBJC_METACLASS_$_NUHDRColorVolumeFilter
+ _OBJC_METACLASS_$_NUHDRLumaCorrectionFilter
+ _OBJC_METACLASS_$_NUMemoryProcessorCacheNode
+ _OBJC_METACLASS_$_NUObjectPointerArray
+ _OBJC_METACLASS_$_NURenderContextTemporalScope
+ _OBJC_METACLASS_$_NURunQueue
+ _OBJC_METACLASS_$_NURunQueueConfiguration
+ _OBJC_METACLASS_$_NURunQueueLane
+ _OBJC_METACLASS_$_NURunQueueLaneID
+ _OBJC_METACLASS_$_NURunQueueStage
+ _OBJC_METACLASS_$_NUStyleTransferPipeline
+ _OBJC_METACLASS_$__NUHDRColorVolumePipeline
+ _OBJC_METACLASS_$__NUHDRGainMapComputePipeline
+ _OBJC_METACLASS_$__NUStyleTransferApplyPipelineProcessor
+ _OBJC_METACLASS_$__NUStyleTransferConfigurationFunction
+ _OBJC_METACLASS_$__NUStyleTransferLearnPipelineProcessor
+ _OBJC_METACLASS_$__NUStyleTransferThumbnailPipelineProcessor
+ _VNComputeStageMain
+ __OBJC_$_CLASS_METHODS_NUHDRColorVolumeFilter
+ __OBJC_$_CLASS_METHODS_NUHDRLumaCorrectionFilter
+ __OBJC_$_CLASS_METHODS_NUObjectPointerArray
+ __OBJC_$_CLASS_METHODS_NURunQueueConfiguration
+ __OBJC_$_CLASS_METHODS_NURunQueueLaneID
+ __OBJC_$_CLASS_METHODS_NUStyleTransferApplyNode
+ __OBJC_$_CLASS_METHODS_NUStyleTransferLearnNode
+ __OBJC_$_CLASS_METHODS_NUStyleTransferPipeline
+ __OBJC_$_CLASS_METHODS_NUStyleTransferThumbnailNode
+ __OBJC_$_CLASS_METHODS__NUHDRColorVolumePipeline
+ __OBJC_$_CLASS_METHODS__NUHDRGainMapComputePipeline
+ __OBJC_$_CLASS_PROP_LIST_NURunQueueLaneID
+ __OBJC_$_CLASS_PROP_LIST__NUHDRGainMapComputePipeline
+ __OBJC_$_INSTANCE_METHODS_NUHDRColorVolumeFilter
+ __OBJC_$_INSTANCE_METHODS_NUHDRLumaCorrectionFilter
+ __OBJC_$_INSTANCE_METHODS_NUMemoryProcessorCacheNode
+ __OBJC_$_INSTANCE_METHODS_NUObjectPointerArray
+ __OBJC_$_INSTANCE_METHODS_NURenderContextTemporalScope
+ __OBJC_$_INSTANCE_METHODS_NURunQueue
+ __OBJC_$_INSTANCE_METHODS_NURunQueueConfiguration
+ __OBJC_$_INSTANCE_METHODS_NURunQueueLane
+ __OBJC_$_INSTANCE_METHODS_NURunQueueLaneID
+ __OBJC_$_INSTANCE_METHODS_NURunQueueStage
+ __OBJC_$_INSTANCE_METHODS_NUStyleTransferPipeline
+ __OBJC_$_INSTANCE_METHODS__NUHDRColorVolumePipeline
+ __OBJC_$_INSTANCE_METHODS__NUHDRGainMapComputePipeline
+ __OBJC_$_INSTANCE_METHODS__NUStyleTransferApplyPipelineProcessor
+ __OBJC_$_INSTANCE_METHODS__NUStyleTransferConfigurationFunction
+ __OBJC_$_INSTANCE_METHODS__NUStyleTransferLearnPipelineProcessor
+ __OBJC_$_INSTANCE_METHODS__NUStyleTransferThumbnailPipelineProcessor
+ __OBJC_$_INSTANCE_VARIABLES_NUHDRColorVolumeFilter
+ __OBJC_$_INSTANCE_VARIABLES_NUHDRLumaCorrectionFilter
+ __OBJC_$_INSTANCE_VARIABLES_NUObjectPointerArray
+ __OBJC_$_INSTANCE_VARIABLES_NURenderContextTemporalScope
+ __OBJC_$_INSTANCE_VARIABLES_NURunQueue
+ __OBJC_$_INSTANCE_VARIABLES_NURunQueueConfiguration
+ __OBJC_$_INSTANCE_VARIABLES_NURunQueueLane
+ __OBJC_$_INSTANCE_VARIABLES_NURunQueueLaneID
+ __OBJC_$_INSTANCE_VARIABLES_NURunQueueStage
+ __OBJC_$_INSTANCE_VARIABLES__NUHDRGainMapComputePipeline
+ __OBJC_$_INSTANCE_VARIABLES__NUMemoryCachePipeline
+ __OBJC_$_PROP_LIST_NUHDRColorVolumeFilter
+ __OBJC_$_PROP_LIST_NUHDRLumaCorrectionFilter
+ __OBJC_$_PROP_LIST_NUObjectPointerArray
+ __OBJC_$_PROP_LIST_NURenderContextTemporalScope
+ __OBJC_$_PROP_LIST_NURunQueue
+ __OBJC_$_PROP_LIST_NURunQueueConfiguration
+ __OBJC_$_PROP_LIST_NURunQueueLane
+ __OBJC_$_PROP_LIST_NURunQueueLaneID
+ __OBJC_$_PROP_LIST_NURunQueueStage
+ __OBJC_$_PROP_LIST_NUScheduler
+ __OBJC_$_PROP_LIST__NUMemoryCachePipeline
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NURunQueueDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NURunQueueDelegate
+ __OBJC_$_PROTOCOL_REFS_NURunQueueDelegate
+ __OBJC_CLASS_PROTOCOLS_$_NUObjectPointerArray
+ __OBJC_CLASS_PROTOCOLS_$_NUScheduler
+ __OBJC_CLASS_RO_$_NUHDRColorVolumeFilter
+ __OBJC_CLASS_RO_$_NUHDRLumaCorrectionFilter
+ __OBJC_CLASS_RO_$_NUMemoryProcessorCacheNode
+ __OBJC_CLASS_RO_$_NUObjectPointerArray
+ __OBJC_CLASS_RO_$_NURenderContextTemporalScope
+ __OBJC_CLASS_RO_$_NURunQueue
+ __OBJC_CLASS_RO_$_NURunQueueConfiguration
+ __OBJC_CLASS_RO_$_NURunQueueLane
+ __OBJC_CLASS_RO_$_NURunQueueLaneID
+ __OBJC_CLASS_RO_$_NURunQueueStage
+ __OBJC_CLASS_RO_$_NUStyleTransferPipeline
+ __OBJC_CLASS_RO_$__NUHDRColorVolumePipeline
+ __OBJC_CLASS_RO_$__NUHDRGainMapComputePipeline
+ __OBJC_CLASS_RO_$__NUStyleTransferApplyPipelineProcessor
+ __OBJC_CLASS_RO_$__NUStyleTransferConfigurationFunction
+ __OBJC_CLASS_RO_$__NUStyleTransferLearnPipelineProcessor
+ __OBJC_CLASS_RO_$__NUStyleTransferThumbnailPipelineProcessor
+ __OBJC_LABEL_PROTOCOL_$_NURunQueueDelegate
+ __OBJC_METACLASS_RO_$_NUHDRColorVolumeFilter
+ __OBJC_METACLASS_RO_$_NUHDRLumaCorrectionFilter
+ __OBJC_METACLASS_RO_$_NUMemoryProcessorCacheNode
+ __OBJC_METACLASS_RO_$_NUObjectPointerArray
+ __OBJC_METACLASS_RO_$_NURenderContextTemporalScope
+ __OBJC_METACLASS_RO_$_NURunQueue
+ __OBJC_METACLASS_RO_$_NURunQueueConfiguration
+ __OBJC_METACLASS_RO_$_NURunQueueLane
+ __OBJC_METACLASS_RO_$_NURunQueueLaneID
+ __OBJC_METACLASS_RO_$_NURunQueueStage
+ __OBJC_METACLASS_RO_$_NUStyleTransferPipeline
+ __OBJC_METACLASS_RO_$__NUHDRColorVolumePipeline
+ __OBJC_METACLASS_RO_$__NUHDRGainMapComputePipeline
+ __OBJC_METACLASS_RO_$__NUStyleTransferApplyPipelineProcessor
+ __OBJC_METACLASS_RO_$__NUStyleTransferConfigurationFunction
+ __OBJC_METACLASS_RO_$__NUStyleTransferLearnPipelineProcessor
+ __OBJC_METACLASS_RO_$__NUStyleTransferThumbnailPipelineProcessor
+ __OBJC_PROTOCOL_$_NURunQueueDelegate
+ __Z19NUPixelRectAbsolute11NUPixelRectS_
+ __Z19NUPixelRectRelative11NUPixelRectS_
+ __ZNKSt3__114default_deleteIN2NU9HistogramIldEEEclB9fqe220106EPS3_
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__112__hash_tableIN2NU10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__copy_constructB9fqe220106EPNS_16__hash_node_baseIPNS_11__hash_nodeIS2_PvEEEE
+ __ZNSt3__112__hash_tableIN2NU10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__copy_constructB9fqe220106EPNS_16__hash_node_baseIPNS_11__hash_nodeIS2_PvEEEESE_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIN2NU9HistogramIldE6SampleEEENS_16allocator_traitsIS6_EEEENS_19__allocation_resultINT0_7pointerENSA_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIdEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorI11CMTimeRangeNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIN2NU9HistogramIldE6SampleENS_9allocatorIS4_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIdNS_9allocatorIdEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIdNS_9allocatorIdEEE16__init_with_sizeB9fqe220106IPdS5_EEvT_T0_m
+ __ZNSt3__16vectorIdNS_9allocatorIdEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIhNS_9allocatorIhEEEC2B9fqe220106EmRKh
+ __ZNSt3__16vectorIlNS_9allocatorIlEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIlNS_9allocatorIlEEE16__init_with_sizeB9fqe220106IPlS5_EEvT_T0_m
+ __ZNSt3__16vectorIlNS_9allocatorIlEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIlNS_9allocatorIlEEEC2B9fqe220106EmRKl
+ __ZNSt3__1eqB9fqe220106IN2NU10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEEEbRKNS_13unordered_setIT_T0_T1_T2_EESE_
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ __ZZNSt3__112__hash_tableIN2NU10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__emplace_uniqueB9fqe220106IJRKS2_EEENS_4pairINS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlSA_SA_E_clESA_SA_
+ __ZZNSt3__112__hash_tableIN2NU10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__emplace_uniqueB9fqe220106IJS2_EEENS_4pairINS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlRKS2_OS2_E_clESL_SM_
+ ___22-[_NUPipeline dealloc]_block_invoke
+ ___22-[_NUPipeline dealloc]_block_invoke_2
+ ___23-[NURunQueueLane pause]_block_invoke
+ ___24-[NURunQueueLane resume]_block_invoke
+ ___24-[NUScheduler _endBatch]_block_invoke
+ ___25-[NURunQueueLane addJob:]_block_invoke
+ ___26-[NURunQueueLane addJobs:]_block_invoke
+ ___26-[NUScheduler _beginBatch]_block_invoke
+ ___27-[NUVideoExporter _export:]_block_invoke
+ ___28-[NURunQueueLane removeJob:]_block_invoke
+ ___29-[NURunQueueLane description]_block_invoke
+ ___30-[NURunQueueLane pendingCount]_block_invoke
+ ___31-[NURunQueue _laneForPriority:]_block_invoke
+ ___31-[NURunQueueLane hasActiveJobs]_block_invoke
+ ___32-[NURenderContext temporalScope]_block_invoke
+ ___32-[NURunQueueStage _dispatchJob:]_block_invoke
+ ___32-[NURunQueueStage _sortIfNeeded]_block_invoke
+ ___33-[NUChannelExpression isDetached]_block_invoke
+ ___34-[NURunQueueLane reprioritizeJob:]_block_invoke
+ ___34-[NURunQueueLane stage:didRunJob:]_block_invoke
+ ___34-[_NUChannelPort debugDescription]_block_invoke
+ ___35-[NUObjectPointerArray description]_block_invoke
+ ___35-[NUScheduler enqueueReleasedJobs:]_block_invoke
+ ___36-[NURenderContext setTemporalScope:]_block_invoke
+ ___36-[NURunQueueLane removeJob:atStage:]_block_invoke
+ ___38-[NUGlobalSettings rawDecodeDisableV9]_block_invoke
+ ___40-[NUObjectPointerArray debugDescription]_block_invoke
+ ___41-[NURunQueue initWithConfiguration:name:]_block_invoke
+ ___42+[NUHDRColorVolumeFilter volumeClipKernel]_block_invoke
+ ___42+[NUHDRColorVolumeFilter volumeWarnKernel]_block_invoke
+ ___43-[NURunQueueStage _hasRunningJobWithGroup:]_block_invoke
+ ___44-[NUGlobalSettings rawDecodeEnableDefaultV9]_block_invoke
+ ___44-[NUGlobalSettings schedulerEnableRunQueues]_block_invoke
+ ___47+[NUGlobalSettings enableConcurrentAudioExport]_block_invoke
+ ___49+[NUHDRLumaCorrectionFilter lumaCorrectionKernel]_block_invoke
+ ___58-[NURAWImageSourceNode _filterAvailableRawDecodeVersions:]_block_invoke
+ ___58-[NURAWImageSourceNode _filterAvailableRawDecodeVersions:]_block_invoke_2
+ ___58-[NURAWImageSourceNode _filterAvailableRawDecodeVersions:]_block_invoke_3
+ ___58-[NURAWImageSourceNode _filterAvailableRawDecodeVersions:]_block_invoke_4
+ ___58-[NURAWImageSourceNode _filterAvailableRawDecodeVersions:]_block_invoke_5
+ ___63-[NUVideoExporter exportAudioTrack:completionQueue:completion:]_block_invoke
+ ___63-[NUVideoExporter exportAudioTrack:completionQueue:completion:]_block_invoke_2
+ ___63-[NUVideoExporter exportAudioTrack:completionQueue:completion:]_block_invoke_3
+ ___63-[NUVideoExporter exportAudioTrack:completionQueue:completion:]_block_invoke_4
+ ___63-[NUVideoExporter exportAudioTrack:completionQueue:completion:]_block_invoke_5
+ ___68-[NURAWImageSourceNode _validateRawDecodeVersion:availableVersions:]_block_invoke
+ ___NUPipelineLogger_block_invoke
+ ___NUVisionVMGPUComputeDevice_block_invoke
+ ___block_descriptor_200_e8_32s40s48s56s64s72s80s88s_e33_B16?0"CMIStyleEngineProcessor"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8
+ ___block_descriptor_32_e24_16?0"_NUChannelPort"8l
+ ___block_descriptor_32_e25_B32?0"NSString"8Q16^B24l
+ ___block_descriptor_32_e37_v32?0"NSString"8"NURunQueue"16^B24l
+ ___block_descriptor_36_e24_B16?0"NURunQueueLane"8l
+ ___block_descriptor_40_e21_B16?0"NURenderJob"8l
+ ___block_descriptor_40_e8_32s_e24_B16?0"NURunQueueLane"8ls32l8
+ ___block_descriptor_40_e8_32s_e37_v16?0"<CIImageProcessorOutputSPI>"8ls32l8
+ ___block_descriptor_48_e8_32s40bs_e15_v16?0"NSURL"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_56_e49_B32?0"NURenderPipelineVideoSampleSlice"8Q16^B24l
+ ___block_descriptor_56_e8_32s40r48r_e5_v8?0ls32l8r40l8r48l8
+ ___block_descriptor_64_e8_32s40r48r56r_e5_v8?0lr40l8s32l8r48l8r56l8
+ ___block_descriptor_64_e8_32s40s48s56s_e40_v16?0"AVPlannedSegmentWritingRequest"8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_64_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56s_e20_v16?0"NUResponse"8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_88_e8_32s40s48s56s64bs72bs80r_e5_v8?0ls32l8s40l8s48l8r80l8s64l8s56l8s72l8
+ _clamp
+ _expf
+ _fabs
+ _fmodf
+ _kCIImageProcessorOnlyUsesMetal
+ _lumaCorrectionKernel.once
+ _lumaCorrectionKernel.s_lumaCorrectionKernel
+ _os_signpost_id_generate
+ _smoothstep
+ _smoothstep01
+ _step
+ _step0
+ _volumeClipKernel.once
+ _volumeClipKernel.s_kernel
+ _volumeWarnKernel.once
+ _volumeWarnKernel.s_kernel
- +[NUGlobalSettings rawDecodeDisableV9]
- +[NUGlobalSettings rawDecodeEnableDefaultV9]
- +[NUGlobalSettings setRawDecodeDisableV9:]
- +[NUGlobalSettings setRawDecodeEnableDefaultV9:]
- +[NUPipelineFactory playbackRateSettings]
- +[_NUHDRGainMapLearnPipeline hdrImageChannel]
- +[_NUHDRGainMapLearnPipeline metadataChannel]
- +[_NUHDRGainMapLearnPipeline sdrImageChannel]
- +[_NUPlaybackRatePipeline transformSettings]
- +[_NUStyleTransferApplyProcessor applyStyle:toImage:thumbnail:target:deltaMap:colorSpace:configuration:tuningParameters:noiseModel:error:]
- -[NUMediaAVBuilder timeWindowsForTracks:timescale:]
- -[NURenderContext pipelineProcessorCache]
- -[NURenderContext setPipelineProcessorCache:]
- -[NURenderPipelineState pipelineProcessorCache]
- -[NURenderPipelineState setPipelineProcessorCache:]
- -[_NUChannelPort setPipeline:]
- -[_NUHDRGainMapLearnPipeline _evaluateOutputPort:context:error:]
- -[_NUHDRGainMapLearnPipeline alias]
- -[_NUHDRGainMapLearnPipeline initWithIdentifier:]
- -[_NUHDRGainMapLearnPipeline init]
- -[_NURenderNodePipeline initWithRenderNodeClass:identifier:]
- -[_NUStyleTransferPipeline _evaluateOutputPort:context:error:]
- -[_NUStyleTransferPipeline init]
- GCC_except_table100
- GCC_except_table10017
- GCC_except_table10068
- GCC_except_table10132
- GCC_except_table10136
- GCC_except_table1024
- GCC_except_table10572
- GCC_except_table10731
- GCC_except_table10733
- GCC_except_table10779
- GCC_except_table10831
- GCC_except_table10839
- GCC_except_table10845
- GCC_except_table1204
- GCC_except_table1208
- GCC_except_table1216
- GCC_except_table1217
- GCC_except_table1218
- GCC_except_table1221
- GCC_except_table1222
- GCC_except_table1223
- GCC_except_table1244
- GCC_except_table1253
- GCC_except_table1276
- GCC_except_table1280
- GCC_except_table1282
- GCC_except_table1283
- GCC_except_table1284
- GCC_except_table1294
- GCC_except_table1342
- GCC_except_table1344
- GCC_except_table1549
- GCC_except_table1562
- GCC_except_table1574
- GCC_except_table1597
- GCC_except_table1609
- GCC_except_table161
- GCC_except_table1614
- GCC_except_table1703
- GCC_except_table1706
- GCC_except_table1715
- GCC_except_table1737
- GCC_except_table1762
- GCC_except_table1763
- GCC_except_table1824
- GCC_except_table1946
- GCC_except_table1947
- GCC_except_table1948
- GCC_except_table1949
- GCC_except_table1950
- GCC_except_table1952
- GCC_except_table1977
- GCC_except_table2030
- GCC_except_table2135
- GCC_except_table2136
- GCC_except_table2624
- GCC_except_table2689
- GCC_except_table2737
- GCC_except_table2749
- GCC_except_table2908
- GCC_except_table3055
- GCC_except_table3135
- GCC_except_table314
- GCC_except_table3142
- GCC_except_table3143
- GCC_except_table3144
- GCC_except_table3145
- GCC_except_table3146
- GCC_except_table3149
- GCC_except_table3150
- GCC_except_table3153
- GCC_except_table3156
- GCC_except_table3157
- GCC_except_table3159
- GCC_except_table3162
- GCC_except_table3163
- GCC_except_table3164
- GCC_except_table3165
- GCC_except_table3166
- GCC_except_table3167
- GCC_except_table3168
- GCC_except_table3169
- GCC_except_table3177
- GCC_except_table3180
- GCC_except_table3181
- GCC_except_table3186
- GCC_except_table3218
- GCC_except_table322
- GCC_except_table3221
- GCC_except_table3222
- GCC_except_table3226
- GCC_except_table3229
- GCC_except_table3230
- GCC_except_table3232
- GCC_except_table3236
- GCC_except_table3238
- GCC_except_table3241
- GCC_except_table3242
- GCC_except_table3243
- GCC_except_table3244
- GCC_except_table3248
- GCC_except_table3254
- GCC_except_table338
- GCC_except_table3569
- GCC_except_table3746
- GCC_except_table377
- GCC_except_table3815
- GCC_except_table3819
- GCC_except_table3821
- GCC_except_table3957
- GCC_except_table3960
- GCC_except_table3963
- GCC_except_table3968
- GCC_except_table3972
- GCC_except_table3995
- GCC_except_table4002
- GCC_except_table4007
- GCC_except_table4009
- GCC_except_table409
- GCC_except_table4136
- GCC_except_table4137
- GCC_except_table4138
- GCC_except_table4141
- GCC_except_table4142
- GCC_except_table4143
- GCC_except_table4148
- GCC_except_table4150
- GCC_except_table4155
- GCC_except_table4156
- GCC_except_table4157
- GCC_except_table4159
- GCC_except_table4161
- GCC_except_table4176
- GCC_except_table4178
- GCC_except_table4203
- GCC_except_table4243
- GCC_except_table4244
- GCC_except_table4249
- GCC_except_table4250
- GCC_except_table4256
- GCC_except_table4258
- GCC_except_table4261
- GCC_except_table4267
- GCC_except_table4271
- GCC_except_table4275
- GCC_except_table4277
- GCC_except_table4279
- GCC_except_table4286
- GCC_except_table4288
- GCC_except_table4289
- GCC_except_table4532
- GCC_except_table455
- GCC_except_table4643
- GCC_except_table4649
- GCC_except_table4652
- GCC_except_table4662
- GCC_except_table4666
- GCC_except_table4667
- GCC_except_table4681
- GCC_except_table4787
- GCC_except_table4912
- GCC_except_table4993
- GCC_except_table5253
- GCC_except_table5354
- GCC_except_table5395
- GCC_except_table541
- GCC_except_table5431
- GCC_except_table5433
- GCC_except_table5435
- GCC_except_table5440
- GCC_except_table5449
- GCC_except_table5450
- GCC_except_table5454
- GCC_except_table5500
- GCC_except_table5519
- GCC_except_table5540
- GCC_except_table5545
- GCC_except_table5564
- GCC_except_table5566
- GCC_except_table5567
- GCC_except_table5572
- GCC_except_table5573
- GCC_except_table5575
- GCC_except_table5576
- GCC_except_table5585
- GCC_except_table5588
- GCC_except_table5589
- GCC_except_table5590
- GCC_except_table5591
- GCC_except_table5592
- GCC_except_table5593
- GCC_except_table5594
- GCC_except_table5595
- GCC_except_table5596
- GCC_except_table5598
- GCC_except_table5599
- GCC_except_table5600
- GCC_except_table5601
- GCC_except_table5602
- GCC_except_table5603
- GCC_except_table5604
- GCC_except_table5605
- GCC_except_table5606
- GCC_except_table5607
- GCC_except_table5608
- GCC_except_table5609
- GCC_except_table5610
- GCC_except_table5615
- GCC_except_table5616
- GCC_except_table5622
- GCC_except_table5623
- GCC_except_table5628
- GCC_except_table5629
- GCC_except_table5630
- GCC_except_table5632
- GCC_except_table5633
- GCC_except_table5634
- GCC_except_table5635
- GCC_except_table5636
- GCC_except_table5641
- GCC_except_table5642
- GCC_except_table5643
- GCC_except_table5644
- GCC_except_table5646
- GCC_except_table5647
- GCC_except_table565
- GCC_except_table5651
- GCC_except_table5652
- GCC_except_table5653
- GCC_except_table5654
- GCC_except_table5655
- GCC_except_table5656
- GCC_except_table5657
- GCC_except_table5658
- GCC_except_table5660
- GCC_except_table5662
- GCC_except_table5666
- GCC_except_table5667
- GCC_except_table5668
- GCC_except_table5669
- GCC_except_table5671
- GCC_except_table5673
- GCC_except_table5674
- GCC_except_table5676
- GCC_except_table5677
- GCC_except_table5785
- GCC_except_table5849
- GCC_except_table5881
- GCC_except_table5882
- GCC_except_table589
- GCC_except_table5919
- GCC_except_table597
- GCC_except_table6023
- GCC_except_table6032
- GCC_except_table6035
- GCC_except_table6040
- GCC_except_table6073
- GCC_except_table6076
- GCC_except_table6077
- GCC_except_table6081
- GCC_except_table6082
- GCC_except_table6185
- GCC_except_table6194
- GCC_except_table6214
- GCC_except_table6231
- GCC_except_table6295
- GCC_except_table6360
- GCC_except_table6365
- GCC_except_table6368
- GCC_except_table6391
- GCC_except_table6433
- GCC_except_table6576
- GCC_except_table6651
- GCC_except_table6666
- GCC_except_table6667
- GCC_except_table6668
- GCC_except_table6681
- GCC_except_table6682
- GCC_except_table6683
- GCC_except_table6684
- GCC_except_table6696
- GCC_except_table6697
- GCC_except_table6711
- GCC_except_table6712
- GCC_except_table6716
- GCC_except_table6756
- GCC_except_table6829
- GCC_except_table6830
- GCC_except_table6834
- GCC_except_table6836
- GCC_except_table6840
- GCC_except_table6842
- GCC_except_table6844
- GCC_except_table6845
- GCC_except_table6849
- GCC_except_table6853
- GCC_except_table6854
- GCC_except_table6855
- GCC_except_table6856
- GCC_except_table6857
- GCC_except_table6859
- GCC_except_table6860
- GCC_except_table6862
- GCC_except_table6863
- GCC_except_table6924
- GCC_except_table6954
- GCC_except_table7042
- GCC_except_table7700
- GCC_except_table7703
- GCC_except_table7768
- GCC_except_table7907
- GCC_except_table7910
- GCC_except_table7915
- GCC_except_table7918
- GCC_except_table7920
- GCC_except_table7925
- GCC_except_table7939
- GCC_except_table7941
- GCC_except_table7942
- GCC_except_table7947
- GCC_except_table7948
- GCC_except_table7968
- GCC_except_table7975
- GCC_except_table7976
- GCC_except_table7977
- GCC_except_table7978
- GCC_except_table7991
- GCC_except_table8170
- GCC_except_table8217
- GCC_except_table8536
- GCC_except_table86
- GCC_except_table8630
- GCC_except_table8803
- GCC_except_table8995
- GCC_except_table9010
- GCC_except_table9043
- GCC_except_table9050
- GCC_except_table9088
- GCC_except_table9089
- GCC_except_table9090
- GCC_except_table9091
- GCC_except_table9096
- GCC_except_table9102
- GCC_except_table9103
- GCC_except_table9110
- GCC_except_table9113
- GCC_except_table9120
- GCC_except_table9122
- GCC_except_table9123
- GCC_except_table9125
- GCC_except_table9126
- GCC_except_table9127
- GCC_except_table9128
- GCC_except_table9133
- GCC_except_table9135
- GCC_except_table9136
- GCC_except_table9137
- GCC_except_table9138
- GCC_except_table9142
- GCC_except_table9143
- GCC_except_table9145
- GCC_except_table9147
- GCC_except_table9149
- GCC_except_table9151
- GCC_except_table9157
- GCC_except_table9160
- GCC_except_table9164
- GCC_except_table9165
- GCC_except_table9167
- GCC_except_table9168
- GCC_except_table9169
- GCC_except_table9170
- GCC_except_table9171
- GCC_except_table9173
- GCC_except_table9174
- GCC_except_table9175
- GCC_except_table9176
- GCC_except_table9177
- GCC_except_table9178
- GCC_except_table9179
- GCC_except_table9180
- GCC_except_table9181
- GCC_except_table9182
- GCC_except_table9183
- GCC_except_table9184
- GCC_except_table9185
- GCC_except_table9186
- GCC_except_table9187
- GCC_except_table9188
- GCC_except_table9189
- GCC_except_table9190
- GCC_except_table9247
- GCC_except_table9254
- GCC_except_table9332
- GCC_except_table9380
- GCC_except_table9403
- GCC_except_table9404
- GCC_except_table9408
- GCC_except_table9409
- GCC_except_table9410
- GCC_except_table9411
- GCC_except_table9419
- GCC_except_table9428
- GCC_except_table9438
- GCC_except_table9444
- GCC_except_table9445
- GCC_except_table9446
- GCC_except_table9449
- GCC_except_table9455
- GCC_except_table9456
- GCC_except_table96
- GCC_except_table97
- GCC_except_table9755
- GCC_except_table9756
- GCC_except_table9762
- GCC_except_table9763
- GCC_except_table9765
- GCC_except_table9766
- GCC_except_table9863
- GCC_except_table9864
- GCC_except_table9867
- GCC_except_table9868
- GCC_except_table9869
- GCC_except_table9870
- GCC_except_table9871
- GCC_except_table9872
- GCC_except_table9874
- GCC_except_table9877
- GCC_except_table9878
- GCC_except_table9880
- GCC_except_table9881
- GCC_except_table9882
- GCC_except_table9884
- GCC_except_table9885
- GCC_except_table9895
- GCC_except_table9896
- GCC_except_table99
- GCC_except_table9901
- GCC_except_table9902
- GCC_except_table9903
- GCC_except_table9906
- GCC_except_table9907
- GCC_except_table9908
- GCC_except_table9909
- GCC_except_table9911
- GCC_except_table9912
- GCC_except_table9913
- GCC_except_table9914
- GCC_except_table9915
- GCC_except_table9916
- GCC_except_table9917
- GCC_except_table9920
- GCC_except_table9921
- GCC_except_table9924
- GCC_except_table9925
- GCC_except_table9926
- GCC_except_table9932
- GCC_except_table9933
- GCC_except_table9934
- GCC_except_table9935
- GCC_except_table9936
- GCC_except_table9937
- GCC_except_table9939
- GCC_except_table9941
- GCC_except_table9942
- GCC_except_table9943
- GCC_except_table9948
- GCC_except_table9949
- GCC_except_table9950
- GCC_except_table9951
- GCC_except_table9952
- GCC_except_table9954
- GCC_except_table9955
- GCC_except_table9956
- GCC_except_table9957
- GCC_except_table9958
- GCC_except_table9959
- GCC_except_table9960
- GCC_except_table9961
- GCC_except_table9966
- GCC_except_table9967
- GCC_except_table9968
- GCC_except_table9969
- GCC_except_table9970
- GCC_except_table9971
- _NUPriorityLevelToDispatchQOS
- _OBJC_CLASS_$_AVAssetExportPlanner
- _OBJC_CLASS_$__NUHDRGainMapLearnPipeline
- _OBJC_CLASS_$__NUStyleTransferPipeline
- _OBJC_IVAR_$_NUPipelineIntermediateNode._sharedRenderContext
- _OBJC_IVAR_$_NURenderContext._pipelineProcessorCache
- _OBJC_IVAR_$_NURenderPipelineState._pipelineProcessorCache
- _OBJC_METACLASS_$__NUHDRGainMapLearnPipeline
- _OBJC_METACLASS_$__NUStyleTransferPipeline
- __OBJC_$_CLASS_METHODS__NUHDRGainMapLearnPipeline
- __OBJC_$_CLASS_PROP_LIST__NUHDRGainMapLearnPipeline
- __OBJC_$_INSTANCE_METHODS__NUHDRGainMapLearnPipeline
- __OBJC_$_INSTANCE_METHODS__NUStyleTransferPipeline
- __OBJC_CLASS_RO_$__NUHDRGainMapLearnPipeline
- __OBJC_CLASS_RO_$__NUStyleTransferPipeline
- __OBJC_METACLASS_RO_$__NUHDRGainMapLearnPipeline
- __OBJC_METACLASS_RO_$__NUStyleTransferPipeline
- __ZNKSt3__114default_deleteIN2NU9HistogramIldEEEclB9fqe220100EPS3_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__112__hash_tableIN2NU10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__copy_constructB9fqe220100EPNS_16__hash_node_baseIPNS_11__hash_nodeIS2_PvEEEE
- __ZNSt3__112__hash_tableIN2NU10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__copy_constructB9fqe220100EPNS_16__hash_node_baseIPNS_11__hash_nodeIS2_PvEEEESE_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIN2NU9HistogramIldE6SampleEEENS_16allocator_traitsIS6_EEEENS_19__allocation_resultINT0_7pointerENSA_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIdEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorI11CMTimeRangeNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIN2NU9HistogramIldE6SampleENS_9allocatorIS4_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIdNS_9allocatorIdEEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIdNS_9allocatorIdEEE16__init_with_sizeB9fqe220100IPdS5_EEvT_T0_m
- __ZNSt3__16vectorIdNS_9allocatorIdEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIhNS_9allocatorIhEEEC2B9fqe220100EmRKh
- __ZNSt3__16vectorIlNS_9allocatorIlEEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIlNS_9allocatorIlEEE16__init_with_sizeB9fqe220100IPlS5_EEvT_T0_m
- __ZNSt3__16vectorIlNS_9allocatorIlEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIlNS_9allocatorIlEEEC2B9fqe220100EmRKl
- __ZNSt3__1eqB9fqe220100IN2NU10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEEEbRKNS_13unordered_setIT_T0_T1_T2_EESE_
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- __ZZNSt3__112__hash_tableIN2NU10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__emplace_uniqueB9fqe220100IJRKS2_EEENS_4pairINS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlSA_SA_E_clESA_SA_
- __ZZNSt3__112__hash_tableIN2NU10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__emplace_uniqueB9fqe220100IJS2_EEENS_4pairINS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlRKS2_OS2_E_clESL_SM_
- ___26-[NUVideoExporter export:]_block_invoke
- ___31-[NUProcessorCache outputImage]_block_invoke_2
- ___38+[NUGlobalSettings rawDecodeDisableV9]_block_invoke
- ___44+[NUGlobalSettings rawDecodeEnableDefaultV9]_block_invoke
- ___56-[NUVideoExporter exportSegment:ofTrack:progress:error:]_block_invoke_2
- ___block_descriptor_192_e8_32s40s48s56s64s72s80s_e33_B16?0"CMIStyleEngineProcessor"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8
- ___block_descriptor_32_e70_{CGRect={CGPoint=dd}{CGSize=dd}}40?0{CGRect={CGPoint=dd}{CGSize=dd}}8l
- ___block_descriptor_40_e8_32s_e65_v24?0"<CIImageProcessorInput>"8"<CIImageProcessorOutputSPI>"16ls32l8
- ___block_descriptor_56_e8_32s40r48r_e5_v8?0lr40l8s32l8r48l8
- ___block_descriptor_56_e8_32s40s48s_e40_v16?0"AVPlannedSegmentWritingRequest"8ls32l8s40l8s48l8
- ___block_descriptor_64_e8_32s_e49_v32?0"NURenderPipelineVideoSampleSlice"8Q16^B24ls32l8
CStrings:
+ "\n  %@"
+ "%@(%@)+%.3f"
+ "%@.%@"
+ "%{public}@"
+ "%{public}@ Job=#%llu '%{public}@'"
+ "(\n\t%@\n)"
+ "(null)"
+ "*** Invalid displacement input extent: %{public}@"
+ "+[NUChannelExpression abs:]"
+ "+[NUChannelExpression clamp:min:max:]"
+ "+[NUChannelExpression smoothStep:]"
+ "+[NUChannelExpression smoothStep:edge0:edge1:]"
+ "+[NUChannelExpression step:]"
+ "+[NUChannelExpression step:edge:]"
+ "+[NUPipelineFactory _buildCacheNodePipelineForClass:baseSettings:error:]"
+ "+[NUPipelineFactory memoryCachePipelineWithOptions:]"
+ "+[_NURenderNodePipeline pipelineWithRenderNodeClassName:baseSettings:error:]"
+ "+[_NUStyleTransferApplyProcessor applyStyle:toImage:thumbnail:target:deltaMap:displacement:colorSpace:configuration:tuningParameters:noiseModel:error:]"
+ ",\n\t"
+ "-[NUChannelStaticExpression detachFromPort:]"
+ "-[NUHDROpticalScaleNode initWithInput:opticalScale:contentHeadroom:]"
+ "-[NUHDRTargetHeadroomNode initWithBase:alternate:sourceHeadroom:targetHeadroom:]"
+ "-[NUObjectPointerArray addObject:]"
+ "-[NUObjectPointerArray containsObject:]"
+ "-[NUObjectPointerArray indexOfObject:]"
+ "-[NUObjectPointerArray removeObject:]"
+ "-[NUPriority initWithQoSClass:order:]"
+ "-[NURAWImageSourceNode _filterAvailableRawDecodeVersions:]"
+ "-[NURenderContext _setTemporalScope:]"
+ "-[NURenderContextTemporalScope init]"
+ "-[NURenderJob _nextStageForStage:]"
+ "-[NURunQueue _indexOfLane:]"
+ "-[NURunQueue addJob:]"
+ "-[NURunQueue initWithConfiguration:name:]"
+ "-[NURunQueue removeJob:atStage:]"
+ "-[NURunQueue reprioritizeJob:fromPriority:]"
+ "-[NURunQueueLane _stageForJobStage:]"
+ "-[NURunQueueLane addJob:]"
+ "-[NURunQueueLane initWithRunQueue:laneID:configuration:]"
+ "-[NURunQueueLane removeJob:]"
+ "-[NURunQueueLane removeJob:atStage:]"
+ "-[NURunQueueLane reprioritizeJob:]"
+ "-[NURunQueueLaneID init]"
+ "-[NUScheduler _defaultConfigurationForExecutionTarget:]"
+ "-[NUScheduler _runQueueForJob:]"
+ "-[NUScheduler _runQueueIdentifierForExecutionTarget:device:]"
+ "-[NUStyleTransferPipeline initWithIdentifier:]"
+ "-[NUVideoExporter _export:]"
+ "-[NUVideoExporter exportAudioTrack:completionQueue:completion:]"
+ "-[NUVideoExporter exportSegmentsWithPlanner:error:]"
+ "-[_NUChannelPort _addReferencingPort:]"
+ "-[_NUChannelPort _detachExpressionFromPort:]"
+ "-[_NUChannelPort _removeReferencingPort:]"
+ "-[_NUComputeJob compute:]"
+ "-[_NUCoreImageComputeJob compute:]"
+ "-[_NUHDRColorVolumePipeline _evaluateOutputPort:context:error:]"
+ "-[_NUHDRColorVolumePipeline initWithIdentifier:]"
+ "-[_NUHDRGainMapComputePipeline _evaluateOutputPort:context:error:]"
+ "-[_NUHDRGainMapComputePipeline initWithIdentifier:]"
+ "-[_NURenderNodePipeline initWithRenderNodeClass:baseSettings:identifier:]"
+ "-[_NUStyleTransferApplyPipelineProcessor outputImageWithInputs:controlData:error:]"
+ "-[_NUStyleTransferLearnPipelineProcessor outputImageWithInputs:controlData:error:]"
+ "-[_NUStyleTransferThumbnailPipelineProcessor outputImageWithInputs:controlData:error:]"
+ ".dng"
+ ".state"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Photos/workspaces/neutrino/Core/Pipeline/API/NUStyleTransferPipeline.m"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Photos/workspaces/neutrino/Core/Render/NURunQueue.m"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Photos/workspaces/neutrino/Core/Util/NUObjectPointerArray.m"
+ ":<applyGlobalRecovery"
+ ":<colorSpace"
+ ":<displacementMap"
+ ":<source"
+ ":<target"
+ ":>primary"
+ "<%@: %@ (%@)>"
+ "<%@: %@ P:[%@] E:[%@] C:[%@]>"
+ "<%@: %lu lanes, %@, N=%lu>"
+ "<%@:%p pipeline:'%@' %@:'%@' format:'%@' data:%@ expression:%@ connectedTo:%@ outputPorts:%@ referencingPorts:%@ subports:%@>"
+ "<%@:%p ref=%@ port=%@ detached=%@>"
+ "@16@?0@\"_NUChannelPort\"8"
+ "AVAssetWritingPlanner global progress: %.3f%%"
+ "AVAssetWritingPlanner intermediate directory: %@"
+ "AVAssetWritingPlanner returned no segment recommendations (regression of rdar://170564263?)"
+ "B16@?0@\"NURenderJob\"8"
+ "B16@?0@\"NURunQueueLane\"8"
+ "B32@?0@\"NSString\"8Q16^B24"
+ "Background"
+ "CGSize NUStyleTransferCoefficientTextureSizeForConfiguration(NSDictionary *__strong _Nonnull)"
+ "CPU"
+ "Cannot add AVAssetReaderOutput for audio"
+ "Cannot add AVAssetWriterInput for audio"
+ "ConcurrentAudioExport"
+ "Duplicate laneID detected: %@"
+ "Execute"
+ "Expression was invalidated"
+ "EyebrowsMatte"
+ "Failed to convert transformsValue to expected type"
+ "Failed to create color volume filter"
+ "Failed to delete temp audio file"
+ "Failed to find audio track in pre-rendered file"
+ "Failed to get image geometry"
+ "Failed to initialize AVAssetReader for audio"
+ "Failed to initialize AVAssetWriter for audio"
+ "Failed to move audio export file"
+ "Failed to reassemble concurrent audio track"
+ "Failed to reassemble pre-rendered audio track"
+ "FileSystem"
+ "GMC"
+ "Invalid accumulation node"
+ "Invalid intensity data"
+ "Invalid lane configuration"
+ "Invalid showClipping data"
+ "Invalid source headroom"
+ "Invalid stage transition"
+ "Lane not found: %@"
+ "Missing displacement extent!"
+ "Missing headroom value"
+ "Missing primary geometry"
+ "Missing primary image"
+ "Missing required apply input"
+ "Missing source or target thumbnail"
+ "NUAssetLoader.loadAsset"
+ "NUHDRColorVolumeFilter"
+ "NUMemoryProcessorCacheNode(%@)"
+ "NU_ENABLE_CONCURRENT_AUDIO_EXPORT"
+ "NU_SCHEDULER_ENABLE_RUN_QUEUES"
+ "No raw decoder version available"
+ "RGB"
+ "Raw decode v9 is disabled by default, but there was no alternative RAW Method Version found %{public}@"
+ "RunQueue not found for identifier '%@'"
+ "RunQueue.Complete.Run"
+ "RunQueue.Complete.Wait"
+ "RunQueue.Execute.Run"
+ "RunQueue.Execute.Wait"
+ "RunQueue.Lane.Active"
+ "RunQueue.Prepare.Run"
+ "RunQueue.Prepare.Wait"
+ "RunQueueStage '%@' [%lu|%lu]/%lu"
+ "Temporal scope already set"
+ "Unhandled execution target %d"
+ "Unsupported stage: %@"
+ "UserInitiated"
+ "UserInteractive"
+ "Utility"
+ "VM-fallback failed to create output pixel buffer"
+ "VM-fallback failed to extract instance mask"
+ "VM-fallback failed to transfer pixel buffer"
+ "VM-fallback foreground instance mask failed"
+ "VM-fallback sky heuristic: failed to allocate output buffer"
+ "VM-fallback sky heuristic: failed to allocate working buffer"
+ "VM-fallback sky heuristic: failed to lock working buffer"
+ "VM-fallback sky heuristic: invalid input extent"
+ "VideoExport"
+ "VideoExportFinalPass"
+ "VideoExportSegment"
+ "VideoExportSegmentFinishWriting"
+ "VideoFrameContext<%@>"
+ "_GPU"
+ "_NUStyleTransferConfigurationFunction"
+ "abs"
+ "alphaMode"
+ "apply:<colorSpace"
+ "apply:<configuration"
+ "apply:<displacementMap"
+ "apply:<primary"
+ "apply:<primaryThumbnail"
+ "apply:<style"
+ "apply:<targetThumbnail"
+ "apply:>primary"
+ "applyGlobalRecovery argument must be control data"
+ "assetId: '%@', assetType: %{public}@"
+ "audio_export_track_%d"
+ "auto"
+ "cacheMode"
+ "clamp"
+ "colorVolume"
+ "concurrent"
+ "concurrentAudioResponseQueue"
+ "contiguous"
+ "descriptor:%@[%@..%@]"
+ "descriptor:%@[%@..]"
+ "descriptor:%@[..%@]"
+ "disableSubsampling"
+ "displacementIndex"
+ "edge != nil"
+ "edge0 != nil"
+ "edge1 != nil"
+ "eyebrowsMatte"
+ "failed"
+ "gainMapCompute"
+ "hdcv"
+ "job #%llu CIRenderInfo: exec=%0.3fms pass=%d pixels=%0.3fMpix"
+ "kernel vec4 hdr_luma_correction(__sample img, __sample ysdr, __sample yhdr) \n{ \n  float3 sdr = (ysdr.rgb + 0.01) * (img.rgb + 0.01) / (yhdr.rgb + 0.01) - 0.01; \n  float maxRGB = max(max(sdr.r, sdr.g), sdr.b); \n  float rmax = 1.0 / max(maxRGB, 1.0); \n  sdr *= rmax; \n  return vec4(sdr, 1.0); \n}\n"
+ "kernel vec4 hdr_luma_hue_chroma_ratio(__sample lhc0, __sample lhc1, float k) \n{ \n  float3 ratio; \n  ratio.x = (lhc0.x*lhc1.x + k*k) / (lhc1.x * lhc1.x + k*k); \n  ratio.y = lhc0.x - ratio.x * lhc1.x; \n  ratio.z = (max(0.0, lhc0.z) + k) / (max(0.0, lhc1.z) + k); \n  return vec4(ratio, 1.0); \n}\n"
+ "kernel vec4 hdr_luma_hue_chroma_scale_by_ratio(__sample lhc, __sample ratio, float k) \n{ \n  lhc.x = ratio.x * lhc.x + ratio.y; \n  lhc.z = ratio.z * (max(0.0, lhc.z) + k) - k; \n  return vec4(lhc.xyz, 1.0); \n}\n"
+ "kernel vec4 hdr_volume_clip(__sample img, float maxVal) \n{ \n  float3 clip = clamp(img.rgb, 0.0, maxVal); \n  return vec4(clip, 1.0); \n}\n"
+ "kernel vec4 hdr_volume_warn(__sample img, float maxVal) \n{ \n  float3 clip1 = step(maxVal, img.rgb); \n  float3 clip0 = step(0.0, img.rgb); \n  float3 warn = (1.0 - clip1) * img.rgb + (1.0 - clip0); \n  return vec4(warn, 1.0); \n}\n"
+ "kernel vec4 ipt_from_srgb(__sample im)\n{\n    vec3 lms = im.r * vec3(0.3139902162, 0.15537240628, 0.01775238698) +\n    im.g * vec3(0.63951293834, 0.75789446163, 0.1094420944) +\n    im.b * vec3(0.04649754622, 0.08670141862, 0.87256922462);\n    lms = sign(lms)*pow(abs(lms), vec3(0.43));\n    vec3 ipt = lms.r * vec3(0.4,  4.455,  0.8056) +\n    lms.g * vec3(0.4, -4.851,  0.3572) +\n    lms.b * vec3(0.2,  0.396,-1.1628);\n    return vec4(ipt, im.a);\n}\n"
+ "laneID != nil"
+ "learn:<colorSpace"
+ "learn:<configuration"
+ "learn:<source"
+ "learn:<target"
+ "learn:>style"
+ "maxVal != nil"
+ "minVal != nil"
+ "nu_audio_track_%d.mov"
+ "nu_audio_track_temp_%d.mov"
+ "oldPriority != nil"
+ "outputURL"
+ "primaryThumbnail"
+ "primaryThumbnail:<colorSpace"
+ "primaryThumbnail:<configuration"
+ "primaryThumbnail:<primary"
+ "primaryThumbnail:>primary"
+ "qosClass != QOS_CLASS_UNSPECIFIED"
+ "rawDecodeCacheMode"
+ "result=%{public}s"
+ "result=cancelled"
+ "runQueue '%{public}@' addJob: #%llu → lane '%{public}@' (priority=%{public}@)"
+ "runQueue '%{public}@' reprioritize: #%llu %{public}@ → %{public}@ (lane '%{public}@' → '%{public}@')"
+ "runQueue '%{public}@' shouldForwardJob: #%llu after: %{public}@ -> %@"
+ "runQueue lane '%{public}@' addJob: #%llu at stage '%{public}@'"
+ "runQueue lane '%{public}@' pause"
+ "runQueue lane '%{public}@' resume"
+ "runQueue stage '%{public}@' dispatch: #%llu [%lu|%lu]"
+ "runQueue stage '%{public}@' enqueueJob: #%llu [%lu|%lu]"
+ "runQueue stage '%{public}@' enqueueJob: #%llu [%lu|%lu] (exceeding capacity: %lu)"
+ "runQueue stage '%{public}@' finished: #%llu [%lu|%lu]"
+ "runQueue stage '%{public}@' removeJob: #%llu [%lu|%lu]"
+ "serial"
+ "showClippedColors"
+ "showClipping"
+ "smoothstep"
+ "smoothstep01"
+ "sourceThumbnail"
+ "sourceThumbnail:<colorSpace"
+ "sourceThumbnail:<configuration"
+ "sourceThumbnail:<primary"
+ "sourceThumbnail:>primary"
+ "step"
+ "step0"
+ "success"
+ "tag:apple.com,2026:photo:aux:semanticeyebrowsmatte"
+ "targetThumbnail"
+ "targetThumbnail:<colorSpace"
+ "targetThumbnail:<configuration"
+ "targetThumbnail:<primary"
+ "targetThumbnail:>primary"
+ "tempURL"
+ "temporalScope"
+ "tiled"
+ "track.audioMix != nil"
+ "track.mediaType == AVMediaTypeAudio"
+ "trackID=%d"
+ "trackID=%d, start=%.3fs, duration=%.3fs"
+ "tracks=%lu"
+ "useProcessor"
+ "useProvider"
+ "v16@?0@\"<CIImageProcessorOutputSPI>\"8"
+ "v16@?0@\"NSError\"8"
+ "v16@?0@\"NSURL\"8"
+ "v32@?0@\"NSString\"8@\"NURunQueue\"16^B24"
- "\nrequestDebugInfo = \n%@\n"
- "+[NUPipelineFactory _buildCacheNodePipelineForClass:error:]"
- "+[NUPipelineFactory memoryCachePipeline]"
- "+[_NURenderNodePipeline pipelineWithRenderNodeClassName:error:]"
- "+[_NUStyleTransferApplyProcessor applyStyle:toImage:thumbnail:target:deltaMap:colorSpace:configuration:tuningParameters:noiseModel:error:]"
- "----\n"
- "-[NUAuxiliaryImageRenderJob scalePolicy]"
- "-[NUHDROpticalScaleNode initWithInput:opticalScale:]"
- "-[NUHDRTargetHeadroomNode initWithBase:alternate:targetHeadroom:]"
- "-[NURenderJob complete:]"
- "-[NURenderJob export:]"
- "-[NURenderJob render:]"
- "-[NUVideoAccumulationFrameJob complete:]"
- "-[NUVideoExporter export:]"
- "-[_NUComputeJob complete:]"
- "-[_NUCoreImageComputeJob complete:]"
- "-[_NUHDRGainMapLearnPipeline _evaluateOutputPort:context:error:]"
- "-[_NUHDRGainMapLearnPipeline initWithIdentifier:]"
- "-[_NURenderNodePipeline initWithRenderNodeClass:identifier:]"
- "-[_NUStyleTransferPipeline _evaluateOutputPort:context:error:]"
- "<%@:%p - level:%@ order:%.4f>"
- "<%@:%p pipeline:'%@' %@:'%@' format:'%@' data:%@>"
- "<%@:%p ref=%@ port=%@>"
- "AVAssetExportPlanner intermediate directory: %@"
- "AVAssetPlanner global progress: %.3f%%"
- "Duration = %.3f\n"
- "GML"
- "Invalid alternate headroom"
- "Invalid applyGlobalRecovery data, expecting a control"
- "Invalid displacement map data, expecting a media"
- "Invalid primary data, expecting a media"
- "Invalid source data, expecting a media"
- "Invalid target data, expecting a media"
- "Missing image properties"
- "Missing source input"
- "Missing target input"
- "Name=%@, Job=%llu\n\n"
- "Not a connected port: %@"
- "Port is already connected: %@"
- "Stage = %@\n"
- "descriptor:%@[%@:%@]"
- "jobDebugInfo = \n%@\n"
- "kernel vec4 hdr_luma_hue_chroma_ratio(__sample lhc0, __sample lhc1, float k) \n{ \n  float3 ratio; \n  ratio.xz = (max(vec2(0), lhc0.xz) + k) / (max(vec2(0), lhc1.xz) + k); \n  ratio.y = 0.0; \n  return vec4(ratio, 1.0); \n}\n"
- "kernel vec4 hdr_luma_hue_chroma_scale_by_ratio(__sample lhc, __sample ratio, float k) \n{ \n  lhc.xz = ratio.xz * (max(vec2(0), lhc.xz) + k) - k; \n  lhc.y += ratio.y; \n  return vec4(lhc.xyz, 1.0); \n}\n"
- "kernel vec4 ipt_from_srgb(__sample im)\n{\n    // First convert into perceptual cone space\n    vec3 lms = im.r * vec3(0.3139902162, 0.15537240628, 0.01775238698) +\n    im.g * vec3(0.63951293834, 0.75789446163, 0.1094420944) +\n    im.b * vec3(0.04649754622, 0.08670141862, 0.87256922462);\n    // nonlinearity for perceptual uniformity\n    lms = sign(lms)*pow(abs(lms), vec3(0.43));\n    // finally convert into a lightness, red-green, blue-yellow space\n    vec3 ipt = lms.r * vec3(0.4,  4.455,  0.8056) +\n    lms.g * vec3(0.4, -4.851,  0.3572) +\n    lms.b * vec3(0.2,  0.396,-1.1628);\n    return vec4(ipt, im.a);\n}\n"
- "v24@?0@\"<CIImageProcessorInput>\"8@\"<CIImageProcessorOutputSPI>\"16"
- "v32@?0@\"NURenderPipelineVideoSampleSlice\"8Q16^B24"
- "{CGRect={CGPoint=dd}{CGSize=dd}}40@?0{CGRect={CGPoint=dd}{CGSize=dd}}8"
```
