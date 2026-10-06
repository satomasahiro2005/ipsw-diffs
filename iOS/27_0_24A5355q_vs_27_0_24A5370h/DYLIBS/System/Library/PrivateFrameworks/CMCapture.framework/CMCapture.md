## CMCapture

> `/System/Library/PrivateFrameworks/CMCapture.framework/CMCapture`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b6464` | `0x8c0df8` | **`+0xa994`** |
| `__TEXT.__cstring` | `0xfb822` | `0xfe485` | **`+0x2c63`** |
| `__TEXT.__oslogstring` | `0x162d06` | `0x1651cd` | **`+0x24c7`** |
| `__AUTH_CONST.__cfstring` | `0x57060` | `0x58da0` | **`+0x1d40`** |
| `__TEXT.__unwind_info` | `0x11380` | `0x11e60` | **`+0xae0`** |
| `__AUTH_CONST.__objc_const` | `0xa5c88` | `0xa6388` | **`+0x700`** |
| `__TEXT.__objc_methlist` | `0x3a0b8` | `0x3a488` | **`+0x3d0`** |
| `__DATA_CONST.__objc_selrefs` | `0x17338` | `0x17478` | **`+0x140`** |
| `__AUTH.__objc_data` | `0x40b0` | `0x4150` | **`+0xa0`** |
| `__DATA.__objc_ivar` | `0xbcc0` | `0xbd4c` | **`+0x8c`** |
| `__DATA_CONST.__const` | `0x111e8` | `0x11270` | **`+0x88`** |
| `__AUTH_CONST.__objc_intobj` | `0x65b8` | `0x6558` | **`-0x60`** |
| `__DATA.__data` | `0x5920` | `0x5980` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x2d60` | `0x2da8` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x6d78` | `0x6db8` | **`+0x40`** |
| `__DATA.__common` | `0x2c40` | `0x2c70` | **`+0x30`** |
| `__TEXT.__const` | `0x151750` | `0x151780` | **`+0x30`** |
| `__DATA_CONST.__objc_superrefs` | `0x1ce0` | `0x1d08` | **`+0x28`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x2c40` | `0x2c58` | **`+0x18`** |
| `__AUTH_CONST.__weak_auth_got` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1ee0` | `0x1ef0` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x1548` | `0x1558` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x4978` | `0x4988` | **`+0x10`** |
| `__DATA.__bss` | `0x2e10` | `0x2e08` | **`-0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x3bb0` | `0x3bb8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x620` | `0x628` | **`+0x8`** |

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3

-  Functions: 41389
-  Symbols:   56184
-  CStrings:  38400
+  Functions: 41492
+  Symbols:   56375
+  CStrings:  38731
Symbols:
+ +[FigCaptureExposureLimits exposureLimitsForStream:]
+ +[FigCaptureMSGScheduling initialize]
+ +[FigCaptureRecordingSettings initialize]
+ -[BWBackgroundBlurNode _configurePTEffect]
+ -[BWBroadcastVideoSinkNode _retuneDisplayForFrameRate:]
+ -[BWBroadcastVideoSinkNode didChangeMaximumFrameRate:]
+ -[BWBroadcastVideoSinkNode setCaptureDevice:]
+ -[BWCamGazeInferenceConfiguration description]
+ -[BWDisparityAPSScaling adjustedDisparityScaleFactorForDisparityBuffer:focusRect:focusDistance:initialScale:]
+ -[BWE5InferenceProvider _anePriorityForSchedulerPriority:]
+ -[BWE5InferenceProvider anefIntermediateBufferSizeMultiplierHint]
+ -[BWE5InferenceProvider initWithType:networkURL:networkConfiguration:context:executionTarget:schedulerPriority:preventionReasons:resourceProvider:allowedCompressionDirection:updateMetadataWithCropRect:anefProcedureVariantHintOverride:]
+ -[BWE5InferenceProvider setAnefIntermediateBufferSizeMultiplierHint:]
+ -[BWEspressoInferenceAdapter _newInferenceProviderWithType:networkURL:networkConfiguration:networkConfigurationByLayout:defaultLayout:portraitOrientationSupportEnabled:context:executionTarget:configuration:preventionReasons:resourceProvider:allowedCompressionDirection:concurrentSubmissionLimit:e5Allowed:updateMetadataWithCropRect:anefProcedureVariantHint:additionalCacheKeyAttributes:]
+ -[BWFaceAndInstanceSegmentationConfiguration description]
+ -[BWFaceQualityInferenceConfiguration description]
+ -[BWFaceprintInferenceConfiguration description]
+ -[BWFastStereoDisparityConfiguration description]
+ -[BWFigVideoCaptureDevice _speedOverQualitySupportedIfEnabled:settings:captureType:ultraHighResCapture:speedOverQualityCaptureTypeOut:]
+ -[BWFigVideoCaptureDevice _ubAdaptiveStillImageCaptureSettingsWithSettings:captureType:captureFlags:sceneFlags:frameStatisticsByPortType:metadata:flushing:]
+ -[BWFigVideoCaptureDevice _ubEVZeroCountForCaptureType:sceneFlags:captureFlags:frameStatistics:hdrErrorRecoveryEVZeroEnabledOut:]
+ -[BWFigVideoCaptureDevice _ubResolveStillImageCaptureFlagsForCaptureType:sceneFlags:settings:frameStatisticsByPortType:hdrMode:speedOverQuality:speedOverQualityDowngrade:qualityPrioritization:highResolutionFlavor:ultraHighResolutionDowngrade:canDefer:assetBundle:flushing:timeMachineFrameSelectionOut:zeroShutterLagFailureReasonOut:metadata:]
+ -[BWFigVideoCaptureDevice _ubStillImageCaptureSettingsWithSettings:assetBundle:flushing:]
+ -[BWFigVideoCaptureDevice exposureLimitsByPortType]
+ -[BWFigVideoCaptureDevice isSpeedOverQualityDowngradeSupportedForStillImageSettings:]
+ -[BWFigVideoCaptureDevice ringLightSupportedPortTypes]
+ -[BWFigVideoCaptureDevice secureMetadataCategoriesEnabled]
+ -[BWFigVideoCaptureDevice setMaximumFrameRateChangedDelegate:]
+ -[BWFigVideoCaptureDevice setNondisruptiveSwitchingFormatIndicesByZoomFactorSIFRBinned:nondisruptiveSwitchingFormatIndicesByZoomFactorMainAndSIFRBinned:nondisruptiveSwitchingFormatIndicesByZoomFactorSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:forPortType:quadraSubPixelSwitchingParameters:]
+ -[BWFigVideoCaptureDevice setSecureMetadataCategoriesEnabled:]
+ -[BWFigVideoCaptureDevice setStructuredLightAFEnabled:]
+ -[BWFigVideoCaptureDevice stillImageCaptureSettingsWithSettings:assetBundle:flushing:]
+ -[BWFigVideoCaptureDevice structuredLightAFEnabled]
+ -[BWFigVideoCaptureStream setZoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexMainAndSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:quadraSubPixelSwitchingParameters:]
+ -[BWFileCoordinatorNode _addBufferToVideoRecordingPrimingQueue:forInputIndex:]
+ -[BWFileCoordinatorNode _flushVideoRecordingPrimingQueues]
+ -[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:]
+ -[BWInferenceScalerConfiguration scalerPriority]
+ -[BWInferenceScalerConfiguration setScalerPriority:]
+ -[BWInferenceScheduler prepareForInferenceRequirements:dependencyProviderSource:formatProvider:pixelBufferPoolProvider:connection:backPressureDrivenPipelining:engineReconfigured:processingConfiguration:postProcessors:schedulerPriority:engineDescription:]
+ -[BWInferenceSchedulerFramebufferBuilder initWithInferenceRequirements:dependencyProvider:formatProvider:processingConfiguration:postProcessors:framebufferPriority:engineDescription:]
+ -[BWInferenceVideoScalingProvider initWithInputRequirement:derivedFromRequirement:outputRequirements:enableFencing:filterType:scalerPriority:]
+ -[BWIrisMovieGenerator setSmartStyleEditInfosBitmask:]
+ -[BWIrisMovieGenerator smartStyleEditInfosBitmask]
+ -[BWMultiStreamCameraSourceNode _calculateZoomFactorsToNondisruptiveSwitchingFormatIndexMapping:nondisruptiveSwitchingFormatIndicesByZoomfactorMainAndSIFRBinnedOut:nondisruptiveSwitchingFormatIndicesByZoomfactorSIFRNonBinnedOut:ultraHighResolutionNondisruptiveStreamingFormatIndex:]
+ -[BWNondisruptiveSwitchingFormatSelector initWithPortType:quadraSubPixelSwitchingParameters:baseZoomFactor:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexMainAndSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:]
+ -[BWNondisruptiveSwitchingFormatSelector zoomFactorToNondisruptiveSwitchingFormatIndexMainAndSIFRBinned]
+ -[BWPhotoEncoderControllerInput processingCanceled]
+ -[BWPhotoEncoderControllerInput setProcessingCanceled:]
+ -[BWPhotonicEngineNodeConfiguration portTypesWithDeepFusionEnabled]
+ -[BWPhotonicEngineNodeConfiguration setPortTypesWithDeepFusionEnabled:]
+ -[BWPhotonicEngineNodeConfiguration(Utilities) _updatedInferencePrepareInputDimensionsForAspectRatio:]
+ -[BWPhotonicEngineNodeConfiguration(Utilities) mattingOutputDimensionsForReferenceDimensions:aspectRatio:]
+ -[BWPixelBufferTransferRenderer _prescaleIfNeededForSourceBuffer:sourceRect:destinationRect:rotationDegrees:]
+ -[BWRealtimeCinematographyNode didReachEndOfDataForConfigurationID:input:]
+ -[BWRealtimeCinematographyNode hasNonLiveConfigurationChanges]
+ -[BWRenderListProcessorPixelBufferJuggler setBufferToDrop:]
+ -[BWRingLightController _currentScreenNits]
+ -[BWRingLightController _disableRingLight]
+ -[BWRingLightController _getUserBrightnessChangeInitial:final:]
+ -[BWRingLightController _initializeStateFromProprietaryDefaultsAndSetUpChangeListener]
+ -[BWRingLightController _setScreenNitsFloor:]
+ -[BWRingLightController configureEffectDescriptor:]
+ -[BWRingLightController initWithDisplayID:captureDevice:]
+ -[BWRingLightController populateRenderRequest:metadataDictionary:]
+ -[BWRingLightController prepareRenderRequest:]
+ -[BWRingLightController processRenderRequestOutput:]
+ -[BWRingLightController ringLightEnabled]
+ -[BWRingLightController screenNitsEstimationEnabled]
+ -[BWRingLightController setRingLightEnabled:]
+ -[BWRingLightController tearDown]
+ -[BWSmartStyleLearningNode _propagateMostRecentMasksAndLearnedFlagToSampleBuffer:metadataDict:]
+ -[BWSoftISPProcessorController _draftDemosaicApplyGDCEnabledForFrame:tuningType:gdcEnabled:]
+ -[BWSoftISPProcessorController _processingRectForDenormalizedRect:targetOutputDimensions:validBufferRect:bounds:]
+ -[BWStillImageCaptureSettings updateForFusionMissingEVMinus:missingHDRErrorRecoveryEVZero:]
+ -[BWStillImageCaptureStreamSettings updateForFusionMissingEVMinus:missingHDRErrorRecoveryEVZero:]
+ -[BWStillImageProcessingSettings isPhotoFormat]
+ -[BWStillImageProcessingSettings setPhotoFormat:]
+ -[BWStreamingPersonSegmentationConfiguration description]
+ -[BWStreamingSessionAnalyticsPayload secureMetadataUseCase]
+ -[BWStreamingSessionAnalyticsPayload setSecureMetadataUseCase:]
+ -[BWTemporalFilterNode initWithMaxLossyCompression:temporalFilterSessionConfigurationsByPortType:lowLightBandingMitigationEnabled:]
+ -[BWTiledEspressoInferenceConfiguration anefIntermediateBufferSizeMultiplierHint]
+ -[BWTiledEspressoInferenceConfiguration setAnefIntermediateBufferSizeMultiplierHint:]
+ -[BWVISNode _updateSmartStyleEditInfosBitmaskForSampleBuffer:]
+ -[BWVMRefinerInferenceConfiguration description]
+ -[FigAudioCaptureConnectionConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCameraCalibrationDataCaptureConnectionConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCaptureBroadcastVideoSinkConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCaptureBroadcastVideoSinkPipeline _buildBroadcastVideoSinkPipelineWithConfiguration:sourceOutput:graph:clientAuditToken:delegate:captureDevice:]
+ -[FigCaptureBroadcastVideoSinkPipeline initWithConfiguration:sourceOutput:graph:name:clientAuditToken:delegate:captureDevice:]
+ -[FigCaptureCameraCalibrationDataSinkConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCaptureCameraSourcePipeline _insertDockKitNodeWithPipelineConfiguration:graph:]
+ -[FigCaptureCameraSourcePipelineConfiguration setPreviewStabilizationEnabled:]
+ -[FigCaptureClientApplicationStateMonitor clientAuditToken]
+ -[FigCaptureConnectionConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCaptureCustomExposureConfiguration _processConfigurationForPortType:limits:]
+ -[FigCaptureCustomExposureConfiguration applyFrameStatistics:forPortTypes:primaryPortType:limitsByPortType:]
+ -[FigCaptureCustomExposureConfiguration requiresUnlockedAE]
+ -[FigCaptureCustomExposureConfiguration sensorSpaceRectOfInterest]
+ -[FigCaptureCustomExposureConfiguration useSpotMetering]
+ -[FigCaptureDepthDataSinkConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCaptureIrisSinkConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCaptureMSGScheduling dealloc]
+ -[FigCaptureMSGScheduling init]
+ -[FigCaptureMSGScheduling scheduledApplyForSyncID:offsetTicks:assertDurTicks:frameSkip:atLeaderFrameIndex:]
+ -[FigCaptureMovieFileSinkConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCapturePhotonicEngineSinkPipelineConfiguration portTypesWithDeepFusionEnabled]
+ -[FigCapturePhotonicEngineSinkPipelineConfiguration setPortTypesWithDeepFusionEnabled:]
+ -[FigCapturePointCloudDataSinkConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCapturePulseGenerator _armRampDownCompletionTimerIfNeeded]
+ -[FigCapturePulseGenerator _scheduledApplyToAllFollowersWithOffsetTicks:frameSkip:atLeaderFrameIndex:]
+ -[FigCapturePulseGenerator setMSGDebugInterrupts:]
+ -[FigCaptureSessionConfiguration _reasonForConnectionConfigurationsArrayNotEqualingArray:]
+ -[FigCaptureSessionConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCaptureSessionStateManager didSuppressAutoResume]
+ -[FigCaptureSinkConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCaptureSourceAttributes cmioSpecialDeviceType]
+ -[FigCaptureSourceAttributes stillImageNoiseReductionAndFusionScheme]
+ -[FigCaptureSourceConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCaptureSourceVideoFormat stillImageProcessingDimensionsByResolutionFlavor]
+ -[FigCaptureStillImageSinkConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCaptureVideoDataSinkConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCaptureVideoDataSinkPipelineConfiguration setTemporalFilterConfigurationsByPortType:]
+ -[FigCaptureVideoPreviewSinkConfiguration reasonForNotEqualingConfiguration:]
+ -[FigCaptureVisionDataSinkConfiguration reasonForNotEqualingConfiguration:]
+ -[FigMetadataItemCaptureConnectionConfiguration reasonForNotEqualingConfiguration:]
+ -[FigMetadataObjectCaptureConnectionConfiguration reasonForNotEqualingConfiguration:]
+ -[FigPointCloudDataCaptureConnectionConfiguration reasonForNotEqualingConfiguration:]
+ -[FigVideoCaptureConnectionConfiguration reasonForNotEqualingConfiguration:]
+ GCC_except_table134
+ GCC_except_table171
+ GCC_except_table235
+ GCC_except_table282
+ GCC_except_table319
+ GCC_except_table325
+ GCC_except_table330
+ GCC_except_table340
+ GCC_except_table341
+ GCC_except_table347
+ GCC_except_table349
+ GCC_except_table381
+ GCC_except_table401
+ GCC_except_table403
+ GCC_except_table406
+ GCC_except_table420
+ GCC_except_table521
+ GCC_except_table64
+ GCC_except_table684
+ GCC_except_table92
+ GCC_except_table97
+ _BWAttachedMediaKeysRequiredBySmartStyleRenderingPipelines.sLTMThumbnailEnabled
+ _BWAttachedMediaKeysRequiredBySmartStyleRenderingPipelines.sOnceToken
+ _BWAttachedMediaKeysRequiredBySmartStyleRenderingPipelines.sPreLTMThumbnailEnabled
+ _BWPhotonicEngineUtilitiesUpdatedInferenceDownscalingFactor
+ _CMILSCOISAdaptation_extrapolateV3LSCTable
+ _FigCaptureClientApplicationIdentifierOSDCameraTester
+ _FigCaptureIsDebuggerInAnyProcessOrSlowAllocationPathEnabled
+ _FigCaptureSourceFormatKey_StillImageProcessingDimensionsByResolutionFlavor
+ _FigCaptureSourceSetStructuredLightAFEnabled
+ _IOSurfaceGetBaseAddressOfCompressedTileDataRegionOfSliceAndPlane
+ _IOSurfaceGetBaseAddressOfCompressedTileHeaderRegionOfSliceAndPlane
+ _IOSurfaceGetBytesPerRowOfTileDataOfPlane
+ _MSGGetCurrentSyncTiming
+ _OBJC_CLASS_$_FigCaptureExposureLimits
+ _OBJC_CLASS_$_FigCaptureMSGScheduling
+ _OBJC_IVAR_$_BWBroadcastVideoSinkNode._captureDevice
+ _OBJC_IVAR_$_BWBroadcastVideoSinkNode._currentDisplayedFrameRate
+ _OBJC_IVAR_$_BWBroadcastVideoSinkNode._lastDriftReassertTime
+ _OBJC_IVAR_$_BWBroadcastVideoSinkNode._lastRequestedFrameRate
+ _OBJC_IVAR_$_BWE5InferenceProvider._anefIntermediateBufferSizeMultiplierHint
+ _OBJC_IVAR_$_BWE5InferenceProvider._anefProcedureVariantHintOverride
+ _OBJC_IVAR_$_BWFigVideoCaptureDevice._hasFlashByPortType
+ _OBJC_IVAR_$_BWFigVideoCaptureDevice._maximumFrameRateChangedDelegate
+ _OBJC_IVAR_$_BWFigVideoCaptureDevice._ringLightSupportedPortTypes
+ _OBJC_IVAR_$_BWFigVideoCaptureDevice._secureMetadataCategoriesEnabled
+ _OBJC_IVAR_$_BWFigVideoCaptureDevice._structuredLightAFEnabled
+ _OBJC_IVAR_$_BWFileCoordinatorNode._videoRecordingPrimingQueueLimit
+ _OBJC_IVAR_$_BWFileCoordinatorNode._videoRecordingPrimingQueues
+ _OBJC_IVAR_$_BWInferenceScalerConfiguration._scalerPriority
+ _OBJC_IVAR_$_BWInferenceSchedulerFramebufferBuilder._framebufferPriority
+ _OBJC_IVAR_$_BWInferenceVideoScalingProvider._scalerPriority
+ _OBJC_IVAR_$_BWIrisMovieGenerator._smartStyleEditInfosBitmask
+ _OBJC_IVAR_$_BWNondisruptiveSwitchingFormatSelector._mainAndSIFRBinnedNondisruptiveSwitchingEnabled
+ _OBJC_IVAR_$_BWNondisruptiveSwitchingFormatSelector._zoomFactorToNondisruptiveSwitchingFormatIndexMainAndSIFRBinned
+ _OBJC_IVAR_$_BWPhotoEncoderControllerInput._processingCanceled
+ _OBJC_IVAR_$_BWPhotonicEngineNodeConfiguration._portTypesWithDeepFusionEnabled
+ _OBJC_IVAR_$_BWPixelBufferTransferRenderer._scalingIntermediatePixelBuffer
+ _OBJC_IVAR_$_BWPixelBufferTransferRenderer._useCPUForAlignedBlackFill
+ _OBJC_IVAR_$_BWQuickTimeMovieFileSinkNode._smartStyleEditInfosBitmask
+ _OBJC_IVAR_$_BWRingLightController._captureDevice
+ _OBJC_IVAR_$_BWRingLightController._ringLightState
+ _OBJC_IVAR_$_BWRingLightController._ringLightStateLock
+ _OBJC_IVAR_$_BWRingLightController._weakReferenceToSelf
+ _OBJC_IVAR_$_BWSmartStyleLearningNode._mostRecentUpdatedMasks
+ _OBJC_IVAR_$_BWStillImageProcessingSettings._photoFormat
+ _OBJC_IVAR_$_BWStreamingCVAFilterRenderer._configuredColorBufferHeight
+ _OBJC_IVAR_$_BWStreamingCVAFilterRenderer._configuredColorBufferWidth
+ _OBJC_IVAR_$_BWStreamingSessionAnalyticsPayload._secureMetadataUseCase
+ _OBJC_IVAR_$_BWSubjectSelectionNode._subjectSelectionSessionCreationToken
+ _OBJC_IVAR_$_BWSubjectSelectionNode._subjectSelectionSessionCreatorQueue
+ _OBJC_IVAR_$_BWTemporalFilterNode._filterSessionConfigurationsByPortType
+ _OBJC_IVAR_$_BWTemporalFilterNode._forceBypassTemporalFilter
+ _OBJC_IVAR_$_BWTemporalFilterNode._forceEnableTemporalFilter
+ _OBJC_IVAR_$_BWTiledEspressoInferenceConfiguration._anefIntermediateBufferSizeMultiplierHint
+ _OBJC_IVAR_$_BWVISNode._smartStyleEditInfosBitmask
+ _OBJC_IVAR_$_FigCaptureCameraSourcePipelineConfiguration._previewStabilizationEnabled
+ _OBJC_IVAR_$_FigCaptureExposureLimits._maxExposureDuration
+ _OBJC_IVAR_$_FigCaptureExposureLimits._maxISO
+ _OBJC_IVAR_$_FigCaptureExposureLimits._minExposureDuration
+ _OBJC_IVAR_$_FigCaptureExposureLimits._minISO
+ _OBJC_IVAR_$_FigCaptureMSGScheduling._controller
+ _OBJC_IVAR_$_FigCapturePhotonicEngineSinkPipelineConfiguration._portTypesWithDeepFusionEnabled
+ _OBJC_IVAR_$_FigCapturePreviewSinkPipeline._filterNodeIsPostStitcher
+ _OBJC_IVAR_$_FigCapturePulseGenerator._hasInFlightRampDown
+ _OBJC_IVAR_$_FigCapturePulseGenerator._isNotifyingUpdating
+ _OBJC_IVAR_$_FigCapturePulseGenerator._msgDebugInterrupts
+ _OBJC_IVAR_$_FigCapturePulseGenerator._msgHandleAltCluster
+ _OBJC_IVAR_$_FigCapturePulseGenerator._msgScheduling
+ _OBJC_IVAR_$_FigCapturePulseGenerator._rampDownCompletionTimer
+ _OBJC_IVAR_$_FigCapturePulseGenerator._rampDownFrameDurationTicks
+ _OBJC_IVAR_$_FigCapturePulseGenerator._rampDownStartFrame
+ _OBJC_IVAR_$_FigCaptureSessionStateManager._didSuppressAutoResume
+ _OBJC_IVAR_$_FigCaptureSourceAttributes._cmioSpecialDeviceType
+ _OBJC_IVAR_$_FigCaptureSourceAttributes._stillImageNoiseReductionAndFusionScheme
+ _OBJC_IVAR_$_FigCaptureVideoDataSinkPipelineConfiguration._temporalFilterConfigurationsByPortType
+ _OBJC_IVAR_$_TrackedSubject._trajectoryTimeStamps
+ _OBJC_METACLASS_$_FigCaptureExposureLimits
+ _OBJC_METACLASS_$_FigCaptureMSGScheduling
+ _TimeSyncClockGetClockRate
+ __OBJC_$_CLASS_METHODS_FigCaptureMSGScheduling
+ __OBJC_$_INSTANCE_METHODS_FigCaptureMSGScheduling
+ __OBJC_$_INSTANCE_VARIABLES_FigCaptureExposureLimits
+ __OBJC_$_INSTANCE_VARIABLES_FigCaptureMSGScheduling
+ __OBJC_$_PROP_LIST_BWBroadcastVideoSinkNode
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BWFigVideoCaptureDeviceMaximumFrameRateChangedDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BWFigVideoCaptureDeviceMaximumFrameRateChangedDelegate
+ __OBJC_$_PROTOCOL_REFS_BWFigVideoCaptureDeviceMaximumFrameRateChangedDelegate
+ __OBJC_CLASS_PROTOCOLS_$_BWBroadcastVideoSinkNode
+ __OBJC_CLASS_RO_$_FigCaptureExposureLimits
+ __OBJC_CLASS_RO_$_FigCaptureMSGScheduling
+ __OBJC_LABEL_PROTOCOL_$_BWFigVideoCaptureDeviceMaximumFrameRateChangedDelegate
+ __OBJC_METACLASS_RO_$_FigCaptureExposureLimits
+ __OBJC_METACLASS_RO_$_FigCaptureMSGScheduling
+ __OBJC_PROTOCOL_$_BWFigVideoCaptureDeviceMaximumFrameRateChangedDelegate
+ __ZN13MSGController15SlaveSyncConfigEjN8AppleMSG19sync_slave_config_tEt
+ __ZN13MSGControllerC1Ebb
+ __ZN13MSGControllerD1Ev
+ __ZdlPvSt19__type_descriptor_t
+ __ZnwmSt19__type_descriptor_t
+ ___256-[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:]_block_invoke
+ ___45-[BWBroadcastVideoSinkNode setCaptureDevice:]_block_invoke
+ ___54-[BWBroadcastVideoSinkNode didChangeMaximumFrameRate:]_block_invoke
+ ___54-[BWSubjectSelectionNode _initSubjectSelectionSession]_block_invoke
+ ___55-[BWBroadcastVideoSinkNode _retuneDisplayForFrameRate:]_block_invoke
+ ___63-[FigCapturePulseGenerator _armRampDownCompletionTimerIfNeeded]_block_invoke
+ ___67-[BWStreamingFilterNode prepareForCurrentConfigurationToBecomeLive]_block_invoke_2
+ ___86-[BWRingLightController _initializeStateFromProprietaryDefaultsAndSetUpChangeListener]_block_invoke
+ ___BWAttachedMediaKeysRequiredBySmartStyleRenderingPipelines_block_invoke
+ ___FigCaptureSourceSetStructuredLightAFEnabled_block_invoke
+ ___block_descriptor_48_e8_32o_e5_i8?0ls32l8
+ ___block_descriptor_48_e8_32r40w_e5_v8?0lw40l8r32l8
+ ___block_descriptor_64_e8_32b_e8_v12?0B8ls32l8
+ ___block_descriptor_72_e8_32o40o48o56r_e5_v8?0ls32l8s40l8r56l8s48l8
+ ___captureSession_liveReconfigureAfterWaitingOnStillImageCoordinatorsIfNeeded_block_invoke_2
+ ___gxx_personality_v0
+ ___vcn_encoderCallback_block_invoke_3
+ _captureSession_updateVideoZoomFactorReset.__counta__
+ _captureSession_updateVideoZoomFactorReset.__totala__
+ _cs_stillImagePhotonicEngineSinkPipelineConfiguration
+ _gFigCaptureMSGSchedulingTrace
+ _gFigCaptureRecordingSettingsTrace
+ _initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:.onceToken
+ _kBWNodeSampleBufferAttachmentKey_IsPrimingFrame
+ _kCVPixelFormatCompressionType
+ _kFigCaptureSampleBufferMetadata_SmartStyleEditInfos
+ _kFigCaptureSessionNotificationPayloadKey_SessionRequiresRestart
+ _kFigCaptureSourceAttributeKey_CMIOSpecialDeviceType
+ _kFigCaptureStreamMetadata_AD
+ _kFigCaptureStreamMetadata_ApertureValue
+ _kFigCaptureStreamMetadata_Signals
+ _kFigCaptureStreamProperty_CMIOSpecialDeviceType
+ _kFigQuicktimeMetadataKey_SmartStyleEditInfos
+ _multiply3x3Matrices
+ _psr_imageByExtendingForBlackFill
+ _ssln_getMasksFromDictionary
- -[BWDisparityAPSScaling adjustedDisparityScaleFactorForDisparityBuffer:focusRect:focusDisatance:initialScale:]
- -[BWE5InferenceProvider initWithType:networkURL:networkConfiguration:context:executionTarget:schedulerPriority:preventionReasons:resourceProvider:allowedCompressionDirection:updateMetadataWithCropRect:]
- -[BWEspressoInferenceAdapter _newInferenceProviderWithType:networkURL:networkConfiguration:networkConfigurationByLayout:defaultLayout:portraitOrientationSupportEnabled:context:executionTarget:configuration:preventionReasons:resourceProvider:allowedCompressionDirection:concurrentSubmissionLimit:e5Allowed:updateMetadataWithCropRect:additionalCacheKeyAttributes:]
- -[BWFigVideoCaptureDevice _ubAdaptiveStillImageCaptureSettingsWithSettings:captureType:captureFlags:sceneFlags:frameStatisticsByPortType:metadata:]
- -[BWFigVideoCaptureDevice _ubEVZeroCountForCaptureType:sceneFlags:captureFlags:frameStatistics:]
- -[BWFigVideoCaptureDevice _ubResolveStillImageCaptureFlagsForCaptureType:sceneFlags:settings:frameStatisticsByPortType:hdrMode:speedOverQuality:speedOverQualityDowngrade:qualityPrioritization:highResolutionFlavor:ultraHighResolutionDowngrade:canDefer:assetBundle:timeMachineFrameSelectionOut:zeroShutterLagFailureReasonOut:metadata:]
- -[BWFigVideoCaptureDevice _ubStillImageCaptureSettingsWithSettings:assetBundle:]
- -[BWFigVideoCaptureDevice setNondisruptiveSwitchingFormatIndicesByZoomFactorSIFRBinned:nondisruptiveSwitchingFormatIndicesByZoomFactorSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:forPortType:quadraSubPixelSwitchingParameters:]
- -[BWFigVideoCaptureStream setZoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:quadraSubPixelSwitchingParameters:]
- -[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:]
- -[BWInferenceScheduler prepareForInferenceRequirements:dependencyProviderSource:formatProvider:pixelBufferPoolProvider:connection:backPressureDrivenPipelining:engineReconfigured:processingConfiguration:postProcessors:engineDescription:]
- -[BWInferenceSchedulerFramebufferBuilder initWithInferenceRequirements:dependencyProvider:formatProvider:processingConfiguration:postProcessors:engineDescription:]
- -[BWInferenceVideoScalingProvider initWithInputRequirement:derivedFromRequirement:outputRequirements:enableFencing:filterType:]
- -[BWMultiStreamCameraSourceNode _calculateZoomFactorsToNondisruptiveSwitchingFormatIndexMapping:nondisruptiveSwitchingFormatIndicesByZoomfactorSIFRNonBinnedOut:ultraHighResolutionNondisruptiveStreamingFormatIndex:]
- -[BWNondisruptiveSwitchingFormatSelector initWithPortType:quadraSubPixelSwitchingParameters:baseZoomFactor:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:]
- -[BWPhotonicEngineNodeConfiguration deepFusionSupportEnabled]
- -[BWPhotonicEngineNodeConfiguration setDeepFusionSupportEnabled:]
- -[BWRealtimeCinematographyNode didReachEndOfDataForInput:]
- -[BWRingLightController currentScreenNits]
- -[BWRingLightController disableRingLight]
- -[BWRingLightController getUserBrightnessChangeInitial:final:]
- -[BWRingLightController initWithDisplayID:]
- -[BWRingLightController setScreenNitsFloor:]
- -[BWStillImageCaptureSettings updateForLearnedFusionMissingEVMinus:missingHDRErrorRecoveryEVZero:]
- -[BWStillImageCaptureStreamSettings updateForLearnedFusionMissingEVMinus:missingHDRErrorRecoveryEVZero:]
- -[BWTemporalFilterNode initWithMaxLossyCompression:filterSessionConfiguration:lowLightBandingMitigationEnabled:]
- -[FigCaptureBroadcastVideoSinkPipeline _buildBroadcastVideoSinkPipelineWithConfiguration:sourceOutput:graph:clientAuditToken:delegate:]
- -[FigCaptureBroadcastVideoSinkPipeline initWithConfiguration:sourceOutput:graph:name:clientAuditToken:delegate:]
- -[FigCaptureCustomExposureConfiguration _processConfigurationWithBaseISO:forPortType:]
- -[FigCaptureCustomExposureConfiguration applyFrameStatistics:forPortTypes:primaryPortType:]
- -[FigCapturePhotonicEngineSinkPipelineConfiguration deepFusionSupported]
- -[FigCapturePhotonicEngineSinkPipelineConfiguration setDeepFusionSupported:]
- -[FigCaptureSessionConfiguration _isConnectionConfigurationsArrayEqual:toOtherConnectionConfigurationsArray:]
- -[FigCaptureSourceExtendedAttributes stillImageNoiseReductionAndFusionScheme]
- GCC_except_table100
- GCC_except_table169
- GCC_except_table232
- GCC_except_table279
- GCC_except_table318
- GCC_except_table322
- GCC_except_table327
- GCC_except_table338
- GCC_except_table339
- GCC_except_table346
- GCC_except_table348
- GCC_except_table378
- GCC_except_table398
- GCC_except_table400
- GCC_except_table404
- GCC_except_table417
- GCC_except_table517
- GCC_except_table675
- GCC_except_table86
- _FigCaptureSourcePositionToShortString
- _OBJC_IVAR_$_BWAttachedMediaTimeMachineSinkNode._formatDescription
- _OBJC_IVAR_$_BWBackgroundBlurNode._captureDevice
- _OBJC_IVAR_$_BWBackgroundBlurNode._ringLightAdaptiveSettings
- _OBJC_IVAR_$_BWBackgroundBlurNode._ringLightAdjustWidth
- _OBJC_IVAR_$_BWBackgroundBlurNode._ringLightAutoColorEnabled
- _OBJC_IVAR_$_BWBackgroundBlurNode._ringLightBias
- _OBJC_IVAR_$_BWBackgroundBlurNode._ringLightColor
- _OBJC_IVAR_$_BWBackgroundBlurNode._ringLightEnabled
- _OBJC_IVAR_$_BWBackgroundBlurNode._ringLightMetadataFile
- _OBJC_IVAR_$_BWBackgroundBlurNode._ringLightMode
- _OBJC_IVAR_$_BWBackgroundBlurNode._ringLightOnboardingState
- _OBJC_IVAR_$_BWBackgroundBlurNode._ringLightRecommendedColorTemperatureNormalized
- _OBJC_IVAR_$_BWBackgroundBlurNode._ringLightRecommendedScreenNitsFloor
- _OBJC_IVAR_$_BWBackgroundBlurNode._ringLightScreenBrightnessUserOverridden
- _OBJC_IVAR_$_BWBackgroundBlurNode._ringLightWidth
- _OBJC_IVAR_$_BWBackgroundBlurNode._weakReferenceToSelf
- _OBJC_IVAR_$_BWFigVideoCaptureDevice._hasFlash
- _OBJC_IVAR_$_BWPhotonicEngineNodeConfiguration._deepFusionSupportEnabled
- _OBJC_IVAR_$_BWSmartStyleLearningNode._mostRecentMasksUpdated
- _OBJC_IVAR_$_BWTemporalFilterNode._bypassTemporalFilter
- _OBJC_IVAR_$_BWTemporalFilterNode._enforceTemporalFilter
- _OBJC_IVAR_$_BWTemporalFilterNode._filterSessionConfiguration
- _OBJC_IVAR_$_FigCaptureCustomExposureConfiguration._enableExposureConfiguration
- _OBJC_IVAR_$_FigCapturePhotonicEngineSinkPipelineConfiguration._deepFusionSupported
- _OBJC_IVAR_$_FigCapturePulseGenerator._msgHandleV6xP1P2FrontCamCluster
- _OBJC_IVAR_$_FigCaptureSourceExtendedAttributes._stillImageNoiseReductionAndFusionScheme
- _OUTLINED_FUNCTION_742
- _OUTLINED_FUNCTION_743
- _OUTLINED_FUNCTION_744
- _OUTLINED_FUNCTION_745
- _TimeSyncClockGetClockRateAndAnchors
- ___224-[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:]_block_invoke
- ___block_descriptor_64_e8_32o40o48r_e5_v8?0ls32l8r48l8s40l8
- ___vtoip_textOrientationVector_block_invoke
- _captureSession_createStillImageSinkPipeline
- _initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:.onceToken
- _sPTEffectSuspensionLock
- _sSuspendedPTEffect
- _sSuspendedPTEffectID
- _vtoip_textOrientationVector.onceToken
- _vtoip_textOrientationVector.sQuantizationLimit
CStrings:
+ " assetBundle:%@"
+ "%@ %p: captureID:%lld '%.4s'('%.4s')%@ %dx%d R:%d%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@"
+ "%@ fsdNetStereoImagesAlignment:%d, disparityType:%d, disparityPrioritization:%ld"
+ "%@ inputAspectRatioIsLandscape:%d portraitOrientationSupportEnabled:%d"
+ "%@ inputRotationAngle:%d, propagateColorInput:%d, cropColorInputToPrimaryCaptureRect:%d, useLowFrameRateOptimizedNetwork:%d, alternativeStreamingPersonSegmentationMaskKey:%@, alternativeStreamingSkinSegmentationMaskKey:%@"
+ "%@ masksDimensions:%@"
+ "%@ maximumNumberOfFaces:%lu"
+ "%@ sensorOrientationAngle:%d"
+ "'StillImageProcessingDimensionsByResolutionFlavor' plist entry for '%@' on port '%@' conflicts with computed dimensions; ignoring plist entry"
+ "( ( dataBase >= surfaceBase ) && ( ( dataBase + dataBufferSize ) <= surfaceEnd ) )"
+ "( ( intermediateRectDimensions.width <= (int32_t)CVPixelBufferGetWidth( _scalingIntermediatePixelBuffer ) ) && ( intermediateRectDimensions.height <= (int32_t)CVPixelBufferGetHeight( _scalingIntermediatePixelBuffer ) ) )"
+ "( ( metadataBase + metadataSurfaceSize ) <= surfaceEnd )"
+ "( _scalingIntermediatePixelBuffer != ((void*)0) )"
+ "( exceedsUpscale != exceedsDownscale )"
+ "( lscGridHeader && ( lscGridHeader->version == FigCaptureStreamLSCGainGridVersion_2 || lscGridHeader->version == FigCaptureStreamLSCGainGridVersion_3 ) )"
+ "( mbDataOffset + mbDataSize <= dataBufferSize )"
+ "( metaMBOffset + metadataElementSize <= metadataSurfaceSize )"
+ "( pixelFormatDescription != ((void *)0) )"
+ "( surface != ((void *)0) )"
+ "+00:00"
+ "-[BWBackgroundBlurNode _configurePTEffect]"
+ "-[BWBroadcastVideoSinkNode _retuneDisplayForFrameRate:]"
+ "-[BWBroadcastVideoSinkNode didChangeMaximumFrameRate:]_block_invoke"
+ "-[BWDisparityAPSScaling adjustedDisparityScaleFactorForDisparityBuffer:focusRect:focusDistance:initialScale:]"
+ "-[BWEspressoInferenceAdapter _newInferenceProviderWithType:networkURL:networkConfiguration:networkConfigurationByLayout:defaultLayout:portraitOrientationSupportEnabled:context:executionTarget:configuration:preventionReasons:resourceProvider:allowedCompressionDirection:concurrentSubmissionLimit:e5Allowed:updateMetadataWithCropRect:anefProcedureVariantHint:additionalCacheKeyAttributes:]"
+ "-[BWFigVideoCaptureDevice _ubAdaptiveStillImageCaptureSettingsWithSettings:captureType:captureFlags:sceneFlags:frameStatisticsByPortType:metadata:flushing:]"
+ "-[BWFigVideoCaptureDevice _ubEVZeroCountForCaptureType:sceneFlags:captureFlags:frameStatistics:hdrErrorRecoveryEVZeroEnabledOut:]"
+ "-[BWFigVideoCaptureDevice _ubResolveStillImageCaptureFlagsForCaptureType:sceneFlags:settings:frameStatisticsByPortType:hdrMode:speedOverQuality:speedOverQualityDowngrade:qualityPrioritization:highResolutionFlavor:ultraHighResolutionDowngrade:canDefer:assetBundle:flushing:timeMachineFrameSelectionOut:zeroShutterLagFailureReasonOut:metadata:]"
+ "-[BWFigVideoCaptureDevice _ubStillImageCaptureSettingsWithSettings:assetBundle:flushing:]"
+ "-[BWFigVideoCaptureDevice setNondisruptiveSwitchingFormatIndicesByZoomFactorSIFRBinned:nondisruptiveSwitchingFormatIndicesByZoomFactorMainAndSIFRBinned:nondisruptiveSwitchingFormatIndicesByZoomFactorSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:forPortType:quadraSubPixelSwitchingParameters:]"
+ "-[BWFigVideoCaptureDevice stillImageCaptureSettingsWithSettings:assetBundle:flushing:]"
+ "-[BWFigVideoCaptureStream setZoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexMainAndSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:quadraSubPixelSwitchingParameters:]"
+ "-[BWFileCoordinatorNode _flushVideoRecordingPrimingQueues]"
+ "-[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:]"
+ "-[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:videoRecordingPrimingQueueLimit:]_block_invoke"
+ "-[BWInferenceScheduler prepareForInferenceRequirements:dependencyProviderSource:formatProvider:pixelBufferPoolProvider:connection:backPressureDrivenPipelining:engineReconfigured:processingConfiguration:postProcessors:schedulerPriority:engineDescription:]"
+ "-[BWInferenceSchedulerFramebufferBuilder initWithInferenceRequirements:dependencyProvider:formatProvider:processingConfiguration:postProcessors:framebufferPriority:engineDescription:]"
+ "-[BWMultiStreamCameraSourceNode _calculateZoomFactorsToNondisruptiveSwitchingFormatIndexMapping:nondisruptiveSwitchingFormatIndicesByZoomfactorMainAndSIFRBinnedOut:nondisruptiveSwitchingFormatIndicesByZoomfactorSIFRNonBinnedOut:ultraHighResolutionNondisruptiveStreamingFormatIndex:]"
+ "-[BWMultiStreamCameraSourceNode configure:]"
+ "-[BWNondisruptiveSwitchingFormatSelector initWithPortType:quadraSubPixelSwitchingParameters:baseZoomFactor:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexMainAndSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:]"
+ "-[BWOpticalFlowInferenceProvider prepareForSubmissionWithWorkQueue:]"
+ "-[BWOpticalFlowInferenceProvider reconcileWithPlaceholderProvider:]"
+ "-[BWPixelBufferTransferRenderer _prescaleIfNeededForSourceBuffer:sourceRect:destinationRect:rotationDegrees:]"
+ "-[BWRealtimeCinematographyNode didReachEndOfDataForConfigurationID:input:]"
+ "-[BWRingLightController _currentScreenNits]"
+ "-[BWRingLightController _disableRingLight]"
+ "-[BWRingLightController _initializeStateFromProprietaryDefaultsAndSetUpChangeListener]"
+ "-[BWRingLightController _setScreenNitsFloor:]"
+ "-[BWRingLightController processRenderRequestOutput:]"
+ "-[BWSmartStyleLearningNode _initVMRefinerInference]"
+ "-[BWStillImageCaptureStreamSettings updateForFusionMissingEVMinus:missingHDRErrorRecoveryEVZero:]"
+ "-[BWSubjectSelectionNode _initSubjectSelectionSession]_block_invoke"
+ "-[BWTemporalFilterNode initWithMaxLossyCompression:temporalFilterSessionConfigurationsByPortType:lowLightBandingMitigationEnabled:]"
+ "-[BWVISNode _updateSmartStyleEditInfosBitmaskForSampleBuffer:]"
+ "-[FigCaptureCameraSourcePipeline setStreamsSuspendedBySourceDeviceType:]"
+ "-[FigCaptureCustomExposureConfiguration _processConfigurationForPortType:limits:]"
+ "-[FigCaptureDeferredProcessingEngine graph:didFinishStartingWithError:]_block_invoke"
+ "-[FigCaptureMSGScheduling scheduledApplyForSyncID:offsetTicks:assertDurTicks:frameSkip:atLeaderFrameIndex:]"
+ "-[FigCapturePulseGenerator _armRampDownCompletionTimerIfNeeded]"
+ "-[FigCapturePulseGenerator _scheduledApplyToAllFollowersWithOffsetTicks:frameSkip:atLeaderFrameIndex:]"
+ "-[FigCaptureRecordingSettings initWithCoder:]"
+ "22:36:09"
+ "3a57f7b63d39d44b01f8076a01393de403326e42"
+ "40fddd6d92eab3d590b4a36dec7d4a84942e1b93"
+ "<%@ %p; executionTarget = %lu; networkURL = %@; type = %@>"
+ "<<< FigCaptureCustomExposureConfiguration >>> %s: Unexpected use of invalid min ISO: %@ applied to %@"
+ "<<<< BWBackgroundBlurNode >>>> %s: PTEffect instance is nil!"
+ "<<<< BWBroadcastVideoSinkNode >>>> %s: Display changed but its the same %d; mode drifted (%.3f Hz, expected %.3f Hz). Re-asserting."
+ "<<<< BWBroadcastVideoSinkNode >>>> %s: No display mode for rate %.3f; leaving current mode"
+ "<<<< BWBroadcastVideoSinkNode >>>> %s: Retuning display from %.3f Hz to %.3f Hz (requested %.3f)"
+ "<<<< BWBroadcastVideoSinkNode >>>> %s: didChangeMaximumFrameRate: new rate %.3f Hz (currently displayed %.3f Hz)"
+ "<<<< BWDeepZoomInferenceProvider >>>> %s: Skipping Deep Transfer: lowRes FCR %@ projected into high-res buffer space %@ exceeds unit rect (lowRes and highRes input sbufs have geometrically inconsistent FCRs, likely due to zoom ramp during capture)."
+ "<<<< BWE5InferenceProvider >>>> %s: Cached provider %@ with placeholder provider %@ input requirement prepared for %@ does not match the incoming input format for reconcilation %@. Refusing to cache the provider and will reload the network. E5 input SurfaceDescriptor dimensions are immutable post E5 operation prepare."
+ "<<<< BWE5InferenceProvider >>>> %s: Cached provider %@ with placeholder provider %@ output requirement prepared for %@ does not match the incoming output format for reconcilation %@. Refusing to cache the provider. E5 output SurfaceDescriptor dimensions are immutable post E5 operation prepare."
+ "<<<< BWEspressoInferenceAdapter >>>> %s: Loading FSINC version v%d.%d via VisionCore for the appropriate aspect ratio so not leveraging portraitOrientationSupportEnabled"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: [%@] sifrBinned %@, mainAndSIFRBinned %@, sifrNonBinned %@"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: called with flushing:%d%@"
+ "<<<< BWFigVideoCaptureStream >>>> %s: %@: Setting zoomFactorToNondisruptiveSwitchingFormatIndex sifrBinned %@, mainAndSIFRBinned %@, sifrNonBinned %@, mainFormatSIFRBinningFactor %d, ultraHighResolutionNondisruptiveStreamingFormatIndex %d"
+ "<<<< BWFigVideoCaptureStream >>>> %s: [%@] Nondisruptive switching format set to %@ with ID:%d, previous %d, minFrameRate %d, maxFrameRate %d, maximumAllowedFrameRate %d, isSecondary %d, format %@"
+ "<<<< BWFileCoordinatorNode >>>> %s: %p: emitting priming frame PTS %.4lf on video output %zu"
+ "<<<< BWGraph >>>> %s: <%p[%{public}d][%{public}@]> Node <%p, %@, %@, %{public}@> Input %{public}@ is %{public}@, but the upstream output %{public}@ is %{public}@."
+ "<<<< BWGraph >>>> %s: <%p[%{public}d][%{public}@]> Node <%p, %@, %@, %{public}@> has all inputs in the desired state but still has %{public}@ outputs. Offending outputs: %{public}@"
+ "<<<< BWGraph >>>> %s: <%p[%{public}d][%{public}@]> Sink node <%p, %@, %{public}@> is %{public}@ despite all inputs being %{public}@, preventing graph stop completion"
+ "<<<< BWGraph >>>> %s: <%p[%{public}d][%{public}@]> Source node <%p, %@, %@, %{public}@> has outputs that aren't yet %{public}@. Possible bug in %@. Offending outputs: %{public}@"
+ "<<<< BWGraph >>>> %s: <%p[%{public}d][%{public}@]> node <%p, %@, %@, %{public}@> is a deferred source in unexpected state %d despite deferred start never being triggered. Possible BWGraph or FigCaptureSession bug."
+ "<<<< BWGraph >>>> %s: <%p[%{public}d][%{public}@]> node <%p, %@, %@, %{public}@> was never started by the graph (%@). This should block starting but isn't caused by this node."
+ "<<<< BWLearnSmartStyleRenderer >>>> %s: Failed to get inputStyledROIRect"
+ "<<<< BWMultiStreamCameraSourceNode >>>> %s: %@, full/full=%@, full/bin=%@, bin/bin=%@"
+ "<<<< BWMultiStreamCameraSourceNode >>>> %s: %@: Base zoom factor updated to %f for aspect ratio %@"
+ "<<<< BWOpticalFlowInferenceProvider >>>> %s: %@ took %.2fms"
+ "<<<< BWOpticalFlowInferenceProvider >>>> %s: Cannot reconcile provider %@ with custom identifier %@ as its identifier does not match the placeholder provider %@ with custom identifier :%@ we are trying to move requirements from"
+ "<<<< BWOpticalFlowInferenceProvider >>>> %s: Cannot reconcile provider %@ with type %@ as its type does not match the placeholder provider %@ with type :%@ we are trying to move requirements from"
+ "<<<< BWOpticalFlowInferenceProvider >>>> %s: Preparing for inference of type:%@"
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: CVPixelBufferCreate returned noErr but null buffer (%dx%d)"
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: Required intermediate pre-scale dimensions (%@) exceed allocated buffer (%dx%d) - sourceRect=%@, destRect=%@"
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: Unable to allocate intermediate buffer (%dx%d) for over-limit scaling: %d"
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: Unsupported anamorphic scaling: src=%@, dst=%@, scale=%@"
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: cpuBlackFillCompressedRect: ERROR data write OOB at MB(%d,%d): offset=%zu + size=%d > dataBufferSize=%zu"
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: cpuBlackFillCompressedRect: ERROR metadata write OOB at MB(%d,%d): twiddleIdx=%u offset=%zu + elemSize=%d > metaSurfaceSize=%zu"
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: cpuBlackFillCompressedRect: ERROR plane %d - data region [%p, %p) outside surface [%p, %p). Aborting."
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: cpuBlackFillCompressedRect: ERROR plane %d - metadata region [%p, %p) outside surface [%p, %p). Aborting."
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: cpuBlackFillCompressedRect: plane %d complete"
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: cpuBlackFillCompressedRect: plane %d diagnostics:\n  planeWidth=%d planeHeight=%d stride=%d\n  mbWidth=%d mbHeight=%d mbDataSize=%d numSubBlocksPerMB=%d\n  widthInMBs=%d heightInMBs=%d\n  surfaceBase=%p surfaceAllocSize=%zu surfaceEnd=%p\n  dataBase=%p dataBufferSize=%zu (dataEnd=%p)\n  metadataBase=%p metadataSurfaceSize=%zu (metaEnd=%p)\n  metadataElementSize=%d ceil_pow2_w=%d ceil_pow2_h=%d"
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: cpuBlackFillCompressedRect: plane %d fill range: MBs [%d,%d) -> [%d,%d)"
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: dest(%d)Dimensions = %dx%d, destFormat = %@, validRect = %@"
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: pixelBuffer %@ is not IOSurface-backed"
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: pixelFormatDescription of pixelBuffer %@ is nil"
+ "<<<< BWPixelBufferTransferRenderer >>>> %s: pre-scaling source->intermediate once for over-limit scale (%.3fx%.3f): sourceRect=%@, intermediateRect=%@"
+ "<<<< BWPreviewStitcherRenderer >>>> %s: aligning destination rectangle from (%@) -> (%@) for faster black-fill"
+ "<<<< BWProResRawMetadataUtilities >>>> %s: Expected LSC grid with header version 2 or 3."
+ "<<<< BWProResRawMetadataUtilities >>>> %s: Expected NULL value for LSC grid header."
+ "<<<< BWProResRawMetadataUtilities >>>> %s: LSC grid verion %d. Expected LSC grid with header version 2 or 3."
+ "<<<< BWRingLightController >>>> %s: Setting ring light adaptive settings from %@ to %@"
+ "<<<< BWRingLightController >>>> %s: Setting ring light recommended nits floor from %f to %f"
+ "<<<< BWRingLightController >>>> %s: Setting ring light width from %f to %f"
+ "<<<< BWRingLightController >>>> %s: ringlight init: s:%d, e:%d, a:%d, b:%f, snf:%f, w:%f, c:%f, ace:%d, rc:%f, as:%d, m:%lu, os:%lu, osc:%i, optt:%@"
+ "<<<< BWSmartStyleLearningNode >>>> %s: Failed to add BWInferenceTypeVMRefiner inference to BWInferenceEngine (preparationStatus=%d)"
+ "<<<< BWSmartStyleLearningNode >>>> %s: Failed to read refined masks"
+ "<<<< BWSmartStyleLearningNode >>>> %s: Failed to read unrefined masks"
+ "<<<< BWSmartStyleLearningNode >>>> %s: person mask pixel buffer is NULL"
+ "<<<< BWSmartStyleLearningNode >>>> %s: person mask sample buffer is NULL"
+ "<<<< BWSmartStyleLearningNode >>>> %s: skin mask pixel buffer is NULL"
+ "<<<< BWSmartStyleLearningNode >>>> %s: skin mask sample buffer is NULL"
+ "<<<< BWSmartStyleLearningNode >>>> %s: sky mask pixel buffer is NULL"
+ "<<<< BWSmartStyleLearningNode >>>> %s: sky mask sample buffer is NULL"
+ "<<<< BWStillImageFilterNode >>>> %s: Skipping portrait effects, adjustedImageError (%d) already set for %@"
+ "<<<< BWStillImageProcessing >>>> %s: Request was cancelled - Skipping piecemeal encoding for attachedMediaKey:%{public}@ captureID:%lld"
+ "<<<< BWStillImageProcessing >>>> %s: Request was cancelled - Skipping prewarm for captureID:%lld"
+ "<<<< BWStillImageProcessing >>>> %s: [%@] Expanding output rect for an aspect ratio capture to preserve padding for GDC: %@ %@ --> %@ (contains minimumValidBufferRectForGDC:%d)"
+ "<<<< BWSubjectSelectionNode >>>> %s: %u. SubjectSelectionSession %@ created."
+ "<<<< BWSubjectSelectionNode >>>> %s: %u. SubjectSelectionSession set."
+ "<<<< BWSubjectSelectionNode >>>> %s: Creation of SubjectSelectionSession %@ went so long as its now obsolete (creation token %u, current token %u"
+ "<<<< BWSubjectSelectionNode >>>> %s: Still waiting for SubjectSelectionSession creation to complete, so input buffer %.4lf is not processed by a session"
+ "<<<< BWSubjectSelectionNode >>>> %s: creating SubjectSelectionSession..."
+ "<<<< BWTemporalFilterNode >>>> %s: %@ bypassing MCTF because frame port type (%@) doesn't match any of the current config's supported frame types, frame no %lld"
+ "<<<< BWTemporalFilterNode >>>> %s: %@ bypassing MCTF because the current config's \"Supported\" is set to no, frame no %lld"
+ "<<<< BWTemporalFilterNode >>>> %s: %@ force enabling MCTF because the current config's \"ForceEnabled\" is set to true, frame no %lld"
+ "<<<< BWVISNode >>>> %s: metadataDict is nil"
+ "<<<< BWVideoDepthInferenceAdapter >>>> %s: Optical flow provider was not already cached, hence creating a brand new one: %@"
+ "<<<< BWVisionInferenceProvider >>>> %s: Dropping face observation due to invalid bounding box: %@"
+ "<<<< BWVisionInferenceProvider >>>> %s: [%@] Dropped %lu face observation(s) with an invalid bounding box from request %{public}@ before forwarding (kept %lu) captureID:%lld"
+ "<<<< BWVisionTextOrientationInferenceProvider >>>> %s: document has %lu lines, below minimum %d, not enough text to determine orientation"
+ "<<<< CMCaptureLocalSessionController >>>> %s: %@ Fatal! Failed to copy capture sources"
+ "<<<< CMCaptureLocalSessionController >>>> %s: %{public}@ Created metadata capture session %@ with capture source %@."
+ "<<<< CMCaptureLocalSessionController >>>> %s: %{public}@ Created video capture session %@ with capture source %@. Default activeMinFrameRate:%@ activeMaxFrameRate:%@"
+ "<<<< CMCaptureLocalSessionController >>>> %s: %{public}@ Empty video capture source deviceFormats array, err=%d"
+ "<<<< CMCaptureLocalSessionController >>>> %s: %{public}@ Sources %@"
+ "<<<< CMCaptureLocalSessionController >>>> %s: %{public}@ Unable to lock capture source. Error %d"
+ "<<<< CMCaptureLocalSessionController >>>> %s: Multiple metadata sources found, only one is supported"
+ "<<<< CMCaptureLocalSessionController >>>> %s: Multiple video sources found, only one is supported"
+ "<<<< CMCaptureLocalSessionController >>>> %s: Skipping FigCaptureSource with unsupported device type %d"
+ "<<<< FigCaptureCameraSourcePipeline >>>> %s: Failed to %@ stream for %@ (err=%d). Continuing to update remaining streams."
+ "<<<< FigCaptureCameraSourcePipeline >>>> %s: GDC configuration is not same for capture %d and preview %d, configuring them both to %d since they are using the same ISP output"
+ "<<<< FigCaptureDeferredProcessingEngine >>>> %s: Ignoring stale didFinishStartingWithError for graph %p; current _graph is %p"
+ "<<<< FigCaptureDeferredProcessingEngine >>>> %s: [client pid:%d] Releasing resources at background QoS. This will be slow since runtime is not guaranteed at this QoS"
+ "<<<< FigCaptureMSGScheduling >>>> %s: FollowerSyncConfig(sync=%u, offset=%llu, skip=%u, schedFrame=%u) NoSpace; caller should retry"
+ "<<<< FigCaptureMSGScheduling >>>> %s: FollowerSyncConfig(sync=%u, offset=%llu, skip=%u, schedFrame=%u) failed: %d"
+ "<<<< FigCaptureMSGScheduling >>>> %s: No MSGController available"
+ "<<<< FigCaptureMetadataUtilities >>>> %s: exifExtraRotationDegrees: %d must be a multiple of 90"
+ "<<<< FigCapturePhotonicEngineSinkPipeline >>>> %s: Still Image PhotonicEngine Pipeline Configuration (continued):%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@"
+ "<<<< FigCapturePhotonicEngineSinkPipeline >>>> %s: Still Image PhotonicEngine Pipeline Configuration (continued):%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ Applying sync offset (immediate, ramp-up): %llu ticks"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ MSG queue full on apply 1; deferring ramp-down to next debounce tick"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ MSG queue full on apply 2; deferring offset change to next debounce tick"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ MSGConfigureDerivedSync failed for alt cluster: %d"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ MSGGetCurrentSyncTiming failed (%d) while computing ramp-down deadline; emitting NO immediately"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ MSGGetCurrentSyncTiming failed: %d"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ Ramp-down NO deferred %u frame(s) (~%llu ns) until K+%u settles (K=%u, currentK=%u)"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ Ramping offset down: K=%u; apply 1 {%llu, skip=1} at K+2=%u, apply 2 {%llu, skip=0} at K+4=%u"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ Ramping offset up: target=%llu step=%llu -> %llu"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ Received error while doing reset in stop, error: %d"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ cancelling ramp-down completion timer"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ enabling debug interrupts on derived syncs"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ failed configuring alt cluster follow frameRate: %@ error (%d)"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ failed follow init on alt cluster frameRate: %@ error (%d)"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ failed for alt cluster handler, error (%d)"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ failed starting sync alt cluster frameRate: %@ error (%d)"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ scheduled apply 1 (skip enable) failed: %d"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ scheduled apply 2 (offset change) failed: %d"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ scheduled apply alt cluster failed: %d"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ scheduled apply front failed: %d"
+ "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ scheduled apply rear failed: %d"
+ "<<<< FigCaptureRadarUtils >>>> %s: Skipping Tap-to-Radar prompt because a debugger is attached or a slow allocation path is enabled."
+ "<<<< FigCaptureRecordingSettings >>>> %s: provided URL cannot generate a file path: %{public}@"
+ "<<<< FigCaptureSession >>>> %s: %@ took %.2fms average %.2fms"
+ "<<<< FigCaptureSession >>>> %s: %@: client is not allowed to write to URL: %{public}@"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Client requested startRunning without a valid inflightConfiguration - sending DidStopRunning with an error"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Client requested startRunning without a valid inflightConfiguration - stopping prewarmed session with error"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Skipping live reconfiguration for stale graphID %lld"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Stopping session to recover from live reconfiguration failure with err (%d)"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Tearing down graph to recover from err (%d) during graph build"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Unable to commit invalid new configuration while BWGraph is running"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ err (%d) updating graph connection enabled state for preview sink. Continuing anyway"
+ "<<<< FigCaptureSession >>>> %s: 'StillImageProcessingDimensionsByResolutionFlavor' plist entry for '%@' on port '%@' conflicts with computed dimensions; ignoring plist entry"
+ "<<<< FigCaptureSession >>>> %s: Failed to retrieve camera sensor orientation degrees of underlying port type for capture source: %@ and sink configuration: %@"
+ "<<<< FigCaptureSession >>>> %s: Trying to live reconfig for output aspect ratio change, but couldn't find a video connection configuration. Skipping reconfiguration."
+ "<<<< FigCaptureSession >>>> %s: called, shouldResetZoomFactorDueToBackgrounding = %d, disableResetAfterHandling = %d"
+ "<<<< FigCaptureSession >>>> %s: fcs config(%lld -> %lld) differs from old due to: %{public}@"
+ "<<<< FigCaptureSession >>>> %s: matchesExceptForZoomFactor = %d"
+ "<<<< FigCaptureSourceBackingsProvider >>>> %s: %@, 'StillImageProcessingDimensionsByResolutionFlavor' contains unrecognized flavor key '%@'"
+ "<<<< FigCaptureSourceBackingsProvider >>>> %s: %@, 'StillImageProcessingDimensionsByResolutionFlavor[%@]' contains invalid video dimensions %@: %@"
+ "<<<< FigCaptureSourceBackingsProvider >>>> %s: %@: search criteria are ambiguous, '%@%@' also resolves to:\n\n\t%i: %@\n\n\t Sticking with first match: \n\n\t%i: %@\n\n\tParams: %@\n\n\t "
+ "<<<< FigCaptureSourceServer >>>> %s: \t%@"
+ "<<<< FigCaptureSourceServer >>>> %s: Failed to copy sourceToken for capture source %@"
+ "<<<< FigCaptureSourceServer >>>> %s: Failed to find source for sourceToken %d, available sources:"
+ "<<<< FigCaptureSourceServer >>>> %s: Failed to lock sSourceListLock"
+ "<<<< FigCaptureSystemStatus >>>> %s: System awake and clamshell is open"
+ "<<<< FigCaptureSystemStatus >>>> %s: System awake but clamshell is closed"
+ "<FigCaptureSource %p%s type:%@ active:%d token:%lld prewarmEnabled:%d, client:%@>"
+ "AVGQ47VE37PL2WQ2B6PNAKBKYS55GY"
+ "ApplyGDC"
+ "Bilinear"
+ "CMIOSpecialDeviceType"
+ "CVPixelBufferCreate returned noErr but null buffer"
+ "CompareZoomFactorBeforeReset"
+ "DraftDemosaicApplyGDC"
+ "Failed to build SmartStyle learning node"
+ "HDRErrorRecoveryEVZero"
+ "Intermediate scaling buffer too small"
+ "IsPrimingFrame"
+ "J700"
+ "Jun 17 2026"
+ "LastShownBuild:BWAudioSourceNode.m:3304"
+ "LastShownBuild:BWCameraInfoMetadataNode.m:533"
+ "LastShownBuild:BWCameraInfoMetadataNode.m:707"
+ "LastShownBuild:BWDeepZoomInferenceProvider.m:484"
+ "LastShownBuild:BWDeepZoomInferenceProvider.m:564"
+ "LastShownBuild:BWE5InferenceProvider.m:861"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:10178"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:10688"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11139"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11174"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11363"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11372"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11384"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11391"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11422"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11488"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:11657"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:12568"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:15539"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:18357"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:18745"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:1887"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:19477"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:19972"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:19974"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:19976"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:21857"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:23240"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:23272"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:23412"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:24170"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:24416"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:24771"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:5881"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:7502"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:7511"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:8588"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:8589"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:8608"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:8897"
+ "LastShownBuild:BWFigVideoCaptureDevice.m:9711"
+ "LastShownBuild:BWFigVideoCaptureStream.m:3193"
+ "LastShownBuild:BWFigVideoCaptureStream.m:3854"
+ "LastShownBuild:BWFigVideoCaptureStream.m:4274"
+ "LastShownBuild:BWFileCoordinatorNode.m:1319"
+ "LastShownBuild:BWGraph.m:3577"
+ "LastShownBuild:BWGraph.m:3580"
+ "LastShownBuild:BWGraph.m:3593"
+ "LastShownBuild:BWGraph.m:3596"
+ "LastShownBuild:BWGraph.m:3599"
+ "LastShownBuild:BWInferenceSchedulerFramebufferBuilder.m:499"
+ "LastShownBuild:BWInferenceSchedulerFramebufferBuilder.m:509"
+ "LastShownBuild:BWInferenceSchedulerFramebufferBuilder.m:522"
+ "LastShownBuild:BWIntelligentDistortionCorrectionProcessorController.m:1174"
+ "LastShownBuild:BWIntelligentDistortionCorrectionProcessorController.m:1737"
+ "LastShownBuild:BWIntelligentDistortionCorrectionProcessorController.m:741"
+ "LastShownBuild:BWLearnSmartStyleRenderer.m:338"
+ "LastShownBuild:BWMultiStreamCameraSourceNode.m:13591"
+ "LastShownBuild:BWMultiStreamCameraSourceNode.m:2710"
+ "LastShownBuild:BWMultiStreamCameraSourceNode.m:4387"
+ "LastShownBuild:BWMultiStreamCameraSourceNode.m:4394"
+ "LastShownBuild:BWMultiStreamCameraSourceNode.m:4401"
+ "LastShownBuild:BWMultiStreamCameraSourceNode.m:9367"
+ "LastShownBuild:BWNRFProcessorController.m:1667"
+ "LastShownBuild:BWNRFProcessorController.m:1668"
+ "LastShownBuild:BWNRFProcessorController.m:2066"
+ "LastShownBuild:BWPhotoEncoderController.m:1256"
+ "LastShownBuild:BWPhotoEncoderController.m:1259"
+ "LastShownBuild:BWPhotoEncoderController.m:1645"
+ "LastShownBuild:BWPhotoEncoderController.m:1650"
+ "LastShownBuild:BWPhotoEncoderController.m:1903"
+ "LastShownBuild:BWPhotoEncoderController.m:2042"
+ "LastShownBuild:BWPhotoEncoderController.m:2058"
+ "LastShownBuild:BWPhotoEncoderController.m:2068"
+ "LastShownBuild:BWPhotoEncoderController.m:3227"
+ "LastShownBuild:BWPhotoEncoderController.m:4615"
+ "LastShownBuild:BWPhotoEncoderController.m:6344"
+ "LastShownBuild:BWPhotonicEngineNode.m:1385"
+ "LastShownBuild:BWPhotonicEngineNode.m:1445"
+ "LastShownBuild:BWPhotonicEngineNode.m:1548"
+ "LastShownBuild:BWPhotonicEngineNode.m:1551"
+ "LastShownBuild:BWPhotonicEngineNode.m:1575"
+ "LastShownBuild:BWPhotonicEngineNode.m:2018"
+ "LastShownBuild:BWPhotonicEngineNode.m:2069"
+ "LastShownBuild:BWPhotonicEngineNode.m:2370"
+ "LastShownBuild:BWPhotonicEngineNode.m:2380"
+ "LastShownBuild:BWPhotonicEngineNode.m:2924"
+ "LastShownBuild:BWPhotonicEngineNode.m:2961"
+ "LastShownBuild:BWPhotonicEngineNode.m:2964"
+ "LastShownBuild:BWPhotonicEngineNode.m:3691"
+ "LastShownBuild:BWPhotonicEngineNode.m:3706"
+ "LastShownBuild:BWPhotonicEngineNode.m:3808"
+ "LastShownBuild:BWPhotonicEngineNode.m:3833"
+ "LastShownBuild:BWPhotonicEngineNode.m:4896"
+ "LastShownBuild:BWPhotonicEngineNode.m:5615"
+ "LastShownBuild:BWPhotonicEngineNode.m:5640"
+ "LastShownBuild:BWPhotonicEngineNode.m:741"
+ "LastShownBuild:BWPhotonicEngineNode.m:755"
+ "LastShownBuild:BWPhotonicEngineNode.m:762"
+ "LastShownBuild:BWPhotonicEngineNode.m:7724"
+ "LastShownBuild:BWPhotonicEngineNode.m:7726"
+ "LastShownBuild:BWPhotonicEngineNode.m:9225"
+ "LastShownBuild:BWPhotonicEngineNodeResourceCoordinator.m:2445"
+ "LastShownBuild:BWPhotonicEngineNodeResourceCoordinator.m:3947"
+ "LastShownBuild:BWPhotonicEngineNodeResourceCoordinator.m:4219"
+ "LastShownBuild:BWPhotonicEngineNodeResourceCoordinator.m:4422"
+ "LastShownBuild:BWPhotonicEngineNodeResourceCoordinator.m:4431"
+ "LastShownBuild:BWPhotonicEngineNodeResourceCoordinator.m:4439"
+ "LastShownBuild:BWPhotonicEngineNodeUtilities.m:1347"
+ "LastShownBuild:BWPixelBufferTransferRenderer.m:639"
+ "LastShownBuild:BWSoftISPProcessorController.m:2869"
+ "LastShownBuild:BWStillImageCoordinatorNode.m:1414"
+ "LastShownBuild:BWStillImageCoordinatorNode.m:1484"
+ "LastShownBuild:BWStillImageCoordinatorNode.m:1567"
+ "LastShownBuild:BWStillImageCoordinatorNode.m:2171"
+ "LastShownBuild:BWStillImageCoordinatorNode.m:3630"
+ "LastShownBuild:BWStillImageFilterNode.m:1261"
+ "LastShownBuild:BWStillImageMetadataUtilities.m:1039"
+ "LastShownBuild:BWStillImageMetadataUtilities.m:119"
+ "LastShownBuild:BWStillImageMetadataUtilities.m:1816"
+ "LastShownBuild:BWStillImageMetadataUtilities.m:1823"
+ "LastShownBuild:BWStillImageMetadataUtilities.m:1829"
+ "LastShownBuild:BWStillImageMetadataUtilities.m:1852"
+ "LastShownBuild:BWStillImageMetadataUtilities.m:2601"
+ "LastShownBuild:BWStillImageMetadataUtilities.m:2631"
+ "LastShownBuild:BWStillImageMetadataUtilities.m:651"
+ "LastShownBuild:BWStillImageMetadataUtilities.m:785"
+ "LastShownBuild:BWStillImageMetadataUtilities.m:964"
+ "LastShownBuild:BWStillImageMetadataUtilities.m:970"
+ "LastShownBuild:BWStillImageMetadataUtilities.m:982"
+ "LastShownBuild:BWTiledE5InferenceProvider.m:870"
+ "LastShownBuild:BWTiledE5InferenceProvider.m:903"
+ "LastShownBuild:BWUBNRFProcessorController.m:1360"
+ "LastShownBuild:BWUBNRFProcessorController.m:1361"
+ "LastShownBuild:BWUBNode.m:1024"
+ "LastShownBuild:BWUBNode.m:1027"
+ "LastShownBuild:BWUBNode.m:1044"
+ "LastShownBuild:BWUBNode.m:1186"
+ "LastShownBuild:BWUBNode.m:1195"
+ "LastShownBuild:BWUBNode.m:1464"
+ "LastShownBuild:BWUBNode.m:1894"
+ "LastShownBuild:BWUBNode.m:2112"
+ "LastShownBuild:BWUBNode.m:2115"
+ "LastShownBuild:BWUBNode.m:2202"
+ "LastShownBuild:BWUBNode.m:2515"
+ "LastShownBuild:BWUBNode.m:3583"
+ "LastShownBuild:BWUBNode.m:5560"
+ "LastShownBuild:BWUBNode.m:5959"
+ "LastShownBuild:BWUBNode.m:6276"
+ "LastShownBuild:BWUBNode.m:902"
+ "LastShownBuild:BWUBNode.m:929"
+ "LastShownBuild:BWUtilities.m:1071"
+ "LastShownBuild:BWVISNode.m:2382"
+ "LastShownBuild:BWVISNode.m:2400"
+ "LastShownBuild:BWVISNode.m:455"
+ "LastShownBuild:BWVisionTextOrientationInferenceProvider.m:283"
+ "LastShownBuild:CMCaptureLocalSessionController.m:878"
+ "LastShownBuild:FigCaptureDeferredProcessingEngine.m:1757"
+ "LastShownBuild:FigCaptureMetadataUtilities.m:1498"
+ "LastShownBuild:FigCaptureMetadataUtilities.m:6185"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1617"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1623"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1624"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1628"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1775"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1781"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1784"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1948"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3015"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3135"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3136"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3297"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3300"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3479"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3483"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3528"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:4506"
+ "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:4512"
+ "LastShownBuild:FigCaptureSession.m:10156"
+ "LastShownBuild:FigCaptureSession.m:10881"
+ "LastShownBuild:FigCaptureSession.m:11073"
+ "LastShownBuild:FigCaptureSession.m:11975"
+ "LastShownBuild:FigCaptureSession.m:18463"
+ "LastShownBuild:FigCaptureSession.m:19965"
+ "LastShownBuild:FigCaptureSession.m:19968"
+ "LastShownBuild:FigCaptureSession.m:27219"
+ "LastShownBuild:FigCaptureSession.m:4396"
+ "LastShownBuild:FigCaptureSession.m:5041"
+ "LastShownBuild:FigCaptureSession.m:8963"
+ "LastShownBuild:FigCaptureSession.m:8969"
+ "LastShownBuild:FigCaptureSession.m:8972"
+ "LastShownBuild:FigCaptureSession.m:8975"
+ "LastShownBuild:FigCaptureSession.m:8978"
+ "LastShownBuild:FigCaptureSession.m:8989"
+ "LastShownBuild:FigCaptureSession.m:8992"
+ "LastShownBuild:FigCaptureSession.m:9000"
+ "LastShownBuild:FigCaptureSession.m:9018"
+ "LastShownBuild:FigCaptureSession.m:9063"
+ "LastShownBuild:FigCaptureSession.m:9067"
+ "LastShownBuild:FigCaptureSession.m:9091"
+ "LastShownBuild:FigCaptureSession.m:9106"
+ "LastShownBuild:FigCaptureSession.m:9110"
+ "LastShownBuild:FigCaptureSession.m:9113"
+ "LastShownBuild:FigCaptureSession.m:9236"
+ "LastShownBuild:FigCaptureSession.m:9242"
+ "LastShownBuild:FigCaptureSession.m:9268"
+ "LastShownBuild:FigCaptureSession.m:9280"
+ "LastShownBuild:FigCaptureSession.m:9678"
+ "LastShownBuild:FigCaptureSession.m:990"
+ "LastShownBuild:FigCaptureSession.m:9961"
+ "LastShownBuild:FigCaptureSessionStateManager.m:352"
+ "LastShownBuild:FigCaptureSessionStateManager.m:384"
+ "LastShownBuild:FigCaptureSessionStateManager.m:517"
+ "LastShownBuild:FigCaptureSource.m:872"
+ "LastShownBuild:FigCaptureSource.m:876"
+ "LastShownBuild:FigCaptureSourceBackingsProvider.m:2730"
+ "LastShownBuild:FigCaptureUtilities.m:1120"
+ "LastShownBuild:FigCaptureUtilities.m:1246"
+ "LastShownBuild:FigSampleBufferProcessor_Autofocus.m:929"
+ "LastShownDate:BWAudioSourceNode.m:3304"
+ "LastShownDate:BWCameraInfoMetadataNode.m:533"
+ "LastShownDate:BWCameraInfoMetadataNode.m:707"
+ "LastShownDate:BWDeepZoomInferenceProvider.m:484"
+ "LastShownDate:BWDeepZoomInferenceProvider.m:564"
+ "LastShownDate:BWE5InferenceProvider.m:861"
+ "LastShownDate:BWFigVideoCaptureDevice.m:10178"
+ "LastShownDate:BWFigVideoCaptureDevice.m:10688"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11139"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11174"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11363"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11372"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11384"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11391"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11422"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11488"
+ "LastShownDate:BWFigVideoCaptureDevice.m:11657"
+ "LastShownDate:BWFigVideoCaptureDevice.m:12568"
+ "LastShownDate:BWFigVideoCaptureDevice.m:15539"
+ "LastShownDate:BWFigVideoCaptureDevice.m:18357"
+ "LastShownDate:BWFigVideoCaptureDevice.m:18745"
+ "LastShownDate:BWFigVideoCaptureDevice.m:1887"
+ "LastShownDate:BWFigVideoCaptureDevice.m:19477"
+ "LastShownDate:BWFigVideoCaptureDevice.m:19972"
+ "LastShownDate:BWFigVideoCaptureDevice.m:19974"
+ "LastShownDate:BWFigVideoCaptureDevice.m:19976"
+ "LastShownDate:BWFigVideoCaptureDevice.m:21857"
+ "LastShownDate:BWFigVideoCaptureDevice.m:23240"
+ "LastShownDate:BWFigVideoCaptureDevice.m:23272"
+ "LastShownDate:BWFigVideoCaptureDevice.m:23412"
+ "LastShownDate:BWFigVideoCaptureDevice.m:24170"
+ "LastShownDate:BWFigVideoCaptureDevice.m:24416"
+ "LastShownDate:BWFigVideoCaptureDevice.m:24771"
+ "LastShownDate:BWFigVideoCaptureDevice.m:5881"
+ "LastShownDate:BWFigVideoCaptureDevice.m:7502"
+ "LastShownDate:BWFigVideoCaptureDevice.m:7511"
+ "LastShownDate:BWFigVideoCaptureDevice.m:8588"
+ "LastShownDate:BWFigVideoCaptureDevice.m:8589"
+ "LastShownDate:BWFigVideoCaptureDevice.m:8608"
+ "LastShownDate:BWFigVideoCaptureDevice.m:8897"
+ "LastShownDate:BWFigVideoCaptureDevice.m:9711"
+ "LastShownDate:BWFigVideoCaptureStream.m:3193"
+ "LastShownDate:BWFigVideoCaptureStream.m:3854"
+ "LastShownDate:BWFigVideoCaptureStream.m:4274"
+ "LastShownDate:BWFileCoordinatorNode.m:1319"
+ "LastShownDate:BWGraph.m:3577"
+ "LastShownDate:BWGraph.m:3580"
+ "LastShownDate:BWGraph.m:3593"
+ "LastShownDate:BWGraph.m:3596"
+ "LastShownDate:BWGraph.m:3599"
+ "LastShownDate:BWInferenceSchedulerFramebufferBuilder.m:499"
+ "LastShownDate:BWInferenceSchedulerFramebufferBuilder.m:509"
+ "LastShownDate:BWInferenceSchedulerFramebufferBuilder.m:522"
+ "LastShownDate:BWIntelligentDistortionCorrectionProcessorController.m:1174"
+ "LastShownDate:BWIntelligentDistortionCorrectionProcessorController.m:1737"
+ "LastShownDate:BWIntelligentDistortionCorrectionProcessorController.m:741"
+ "LastShownDate:BWLearnSmartStyleRenderer.m:338"
+ "LastShownDate:BWMultiStreamCameraSourceNode.m:13591"
+ "LastShownDate:BWMultiStreamCameraSourceNode.m:2710"
+ "LastShownDate:BWMultiStreamCameraSourceNode.m:4387"
+ "LastShownDate:BWMultiStreamCameraSourceNode.m:4394"
+ "LastShownDate:BWMultiStreamCameraSourceNode.m:4401"
+ "LastShownDate:BWMultiStreamCameraSourceNode.m:9367"
+ "LastShownDate:BWNRFProcessorController.m:1667"
+ "LastShownDate:BWNRFProcessorController.m:1668"
+ "LastShownDate:BWNRFProcessorController.m:2066"
+ "LastShownDate:BWPhotoEncoderController.m:1256"
+ "LastShownDate:BWPhotoEncoderController.m:1259"
+ "LastShownDate:BWPhotoEncoderController.m:1645"
+ "LastShownDate:BWPhotoEncoderController.m:1650"
+ "LastShownDate:BWPhotoEncoderController.m:1903"
+ "LastShownDate:BWPhotoEncoderController.m:2042"
+ "LastShownDate:BWPhotoEncoderController.m:2058"
+ "LastShownDate:BWPhotoEncoderController.m:2068"
+ "LastShownDate:BWPhotoEncoderController.m:3227"
+ "LastShownDate:BWPhotoEncoderController.m:4615"
+ "LastShownDate:BWPhotoEncoderController.m:6344"
+ "LastShownDate:BWPhotonicEngineNode.m:1385"
+ "LastShownDate:BWPhotonicEngineNode.m:1445"
+ "LastShownDate:BWPhotonicEngineNode.m:1548"
+ "LastShownDate:BWPhotonicEngineNode.m:1551"
+ "LastShownDate:BWPhotonicEngineNode.m:1575"
+ "LastShownDate:BWPhotonicEngineNode.m:2018"
+ "LastShownDate:BWPhotonicEngineNode.m:2069"
+ "LastShownDate:BWPhotonicEngineNode.m:2370"
+ "LastShownDate:BWPhotonicEngineNode.m:2380"
+ "LastShownDate:BWPhotonicEngineNode.m:2924"
+ "LastShownDate:BWPhotonicEngineNode.m:2961"
+ "LastShownDate:BWPhotonicEngineNode.m:2964"
+ "LastShownDate:BWPhotonicEngineNode.m:3691"
+ "LastShownDate:BWPhotonicEngineNode.m:3706"
+ "LastShownDate:BWPhotonicEngineNode.m:3808"
+ "LastShownDate:BWPhotonicEngineNode.m:3833"
+ "LastShownDate:BWPhotonicEngineNode.m:4896"
+ "LastShownDate:BWPhotonicEngineNode.m:5615"
+ "LastShownDate:BWPhotonicEngineNode.m:5640"
+ "LastShownDate:BWPhotonicEngineNode.m:741"
+ "LastShownDate:BWPhotonicEngineNode.m:755"
+ "LastShownDate:BWPhotonicEngineNode.m:762"
+ "LastShownDate:BWPhotonicEngineNode.m:7724"
+ "LastShownDate:BWPhotonicEngineNode.m:7726"
+ "LastShownDate:BWPhotonicEngineNode.m:9225"
+ "LastShownDate:BWPhotonicEngineNodeResourceCoordinator.m:2445"
+ "LastShownDate:BWPhotonicEngineNodeResourceCoordinator.m:3947"
+ "LastShownDate:BWPhotonicEngineNodeResourceCoordinator.m:4219"
+ "LastShownDate:BWPhotonicEngineNodeResourceCoordinator.m:4422"
+ "LastShownDate:BWPhotonicEngineNodeResourceCoordinator.m:4431"
+ "LastShownDate:BWPhotonicEngineNodeResourceCoordinator.m:4439"
+ "LastShownDate:BWPhotonicEngineNodeUtilities.m:1347"
+ "LastShownDate:BWPixelBufferTransferRenderer.m:639"
+ "LastShownDate:BWSoftISPProcessorController.m:2869"
+ "LastShownDate:BWStillImageCoordinatorNode.m:1414"
+ "LastShownDate:BWStillImageCoordinatorNode.m:1484"
+ "LastShownDate:BWStillImageCoordinatorNode.m:1567"
+ "LastShownDate:BWStillImageCoordinatorNode.m:2171"
+ "LastShownDate:BWStillImageCoordinatorNode.m:3630"
+ "LastShownDate:BWStillImageFilterNode.m:1261"
+ "LastShownDate:BWStillImageMetadataUtilities.m:1039"
+ "LastShownDate:BWStillImageMetadataUtilities.m:119"
+ "LastShownDate:BWStillImageMetadataUtilities.m:1816"
+ "LastShownDate:BWStillImageMetadataUtilities.m:1823"
+ "LastShownDate:BWStillImageMetadataUtilities.m:1829"
+ "LastShownDate:BWStillImageMetadataUtilities.m:1852"
+ "LastShownDate:BWStillImageMetadataUtilities.m:2601"
+ "LastShownDate:BWStillImageMetadataUtilities.m:2631"
+ "LastShownDate:BWStillImageMetadataUtilities.m:651"
+ "LastShownDate:BWStillImageMetadataUtilities.m:785"
+ "LastShownDate:BWStillImageMetadataUtilities.m:964"
+ "LastShownDate:BWStillImageMetadataUtilities.m:970"
+ "LastShownDate:BWStillImageMetadataUtilities.m:982"
+ "LastShownDate:BWTiledE5InferenceProvider.m:870"
+ "LastShownDate:BWTiledE5InferenceProvider.m:903"
+ "LastShownDate:BWUBNRFProcessorController.m:1360"
+ "LastShownDate:BWUBNRFProcessorController.m:1361"
+ "LastShownDate:BWUBNode.m:1024"
+ "LastShownDate:BWUBNode.m:1027"
+ "LastShownDate:BWUBNode.m:1044"
+ "LastShownDate:BWUBNode.m:1186"
+ "LastShownDate:BWUBNode.m:1195"
+ "LastShownDate:BWUBNode.m:1464"
+ "LastShownDate:BWUBNode.m:1894"
+ "LastShownDate:BWUBNode.m:2112"
+ "LastShownDate:BWUBNode.m:2115"
+ "LastShownDate:BWUBNode.m:2202"
+ "LastShownDate:BWUBNode.m:2515"
+ "LastShownDate:BWUBNode.m:3583"
+ "LastShownDate:BWUBNode.m:5560"
+ "LastShownDate:BWUBNode.m:5959"
+ "LastShownDate:BWUBNode.m:6276"
+ "LastShownDate:BWUBNode.m:902"
+ "LastShownDate:BWUBNode.m:929"
+ "LastShownDate:BWUtilities.m:1071"
+ "LastShownDate:BWVISNode.m:2382"
+ "LastShownDate:BWVISNode.m:2400"
+ "LastShownDate:BWVISNode.m:455"
+ "LastShownDate:BWVisionTextOrientationInferenceProvider.m:283"
+ "LastShownDate:CMCaptureLocalSessionController.m:878"
+ "LastShownDate:FigCaptureDeferredProcessingEngine.m:1757"
+ "LastShownDate:FigCaptureMetadataUtilities.m:1498"
+ "LastShownDate:FigCaptureMetadataUtilities.m:6185"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1617"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1623"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1624"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1628"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1775"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1781"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1784"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1948"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3015"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3135"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3136"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3297"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3300"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3479"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3483"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3528"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:4506"
+ "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:4512"
+ "LastShownDate:FigCaptureSession.m:10156"
+ "LastShownDate:FigCaptureSession.m:10881"
+ "LastShownDate:FigCaptureSession.m:11073"
+ "LastShownDate:FigCaptureSession.m:11975"
+ "LastShownDate:FigCaptureSession.m:18463"
+ "LastShownDate:FigCaptureSession.m:19965"
+ "LastShownDate:FigCaptureSession.m:19968"
+ "LastShownDate:FigCaptureSession.m:27219"
+ "LastShownDate:FigCaptureSession.m:4396"
+ "LastShownDate:FigCaptureSession.m:5041"
+ "LastShownDate:FigCaptureSession.m:8963"
+ "LastShownDate:FigCaptureSession.m:8969"
+ "LastShownDate:FigCaptureSession.m:8972"
+ "LastShownDate:FigCaptureSession.m:8975"
+ "LastShownDate:FigCaptureSession.m:8978"
+ "LastShownDate:FigCaptureSession.m:8989"
+ "LastShownDate:FigCaptureSession.m:8992"
+ "LastShownDate:FigCaptureSession.m:9000"
+ "LastShownDate:FigCaptureSession.m:9018"
+ "LastShownDate:FigCaptureSession.m:9063"
+ "LastShownDate:FigCaptureSession.m:9067"
+ "LastShownDate:FigCaptureSession.m:9091"
+ "LastShownDate:FigCaptureSession.m:9106"
+ "LastShownDate:FigCaptureSession.m:9110"
+ "LastShownDate:FigCaptureSession.m:9113"
+ "LastShownDate:FigCaptureSession.m:9236"
+ "LastShownDate:FigCaptureSession.m:9242"
+ "LastShownDate:FigCaptureSession.m:9268"
+ "LastShownDate:FigCaptureSession.m:9280"
+ "LastShownDate:FigCaptureSession.m:9678"
+ "LastShownDate:FigCaptureSession.m:990"
+ "LastShownDate:FigCaptureSession.m:9961"
+ "LastShownDate:FigCaptureSessionStateManager.m:352"
+ "LastShownDate:FigCaptureSessionStateManager.m:384"
+ "LastShownDate:FigCaptureSessionStateManager.m:517"
+ "LastShownDate:FigCaptureSource.m:872"
+ "LastShownDate:FigCaptureSource.m:876"
+ "LastShownDate:FigCaptureSourceBackingsProvider.m:2730"
+ "LastShownDate:FigCaptureUtilities.m:1120"
+ "LastShownDate:FigCaptureUtilities.m:1246"
+ "LastShownDate:FigSampleBufferProcessor_Autofocus.m:929"
+ "Live reconfiguring BWRealtimeCinematographyNode with changing formats is not supported"
+ "SessionRequiresRestart"
+ "StillImageProcessingDimensionsByResolutionFlavor"
+ "Unsupported anamorphic scaling"
+ "Z"
+ "[ %d : %d ]\n"
+ "[graph connectOutput:videoOutput toInput:dockkitNode.input pipelineStage:((void *)0)]"
+ "_sourceToken (%d -> %d)"
+ "_sourceUID (%@ -> %@)"
+ "allowedToRunInMultitaskingMode (%d -> %d)"
+ "applyMaxExposureDurationFrameworkOverrideWhenAvailable (%d -> %d)"
+ "applyStandardSmartStyleForStillsWhenNoStyleRequested (%d -> %d)"
+ "attachMetadataToVideoBuffers (%d -> %d)"
+ "attentionDetectionEnabled (%d -> %d)"
+ "attentionForFaceIDReadinessRequired (%d -> %d)"
+ "audioCaptureMode (%d -> %d)"
+ "audioZoomEnabled (%d -> %d)"
+ "automaticallyRunsDeferredStart (%d -> %d)"
+ "backgroundBlurEnabled (%d -> %d)"
+ "backgroundBlurSupported (%d -> %d)"
+ "backgroundReplacementEnabled (%d -> %d)"
+ "backgroundReplacementSupported (%d -> %d)"
+ "bravoConstituentPhotoDeliveryEnabled (%d -> %d)"
+ "builtInMicrophonePosition (%d -> %d)"
+ "builtInMicrophoneRequiredSampleRate (%g -> %g)"
+ "bwvip_faceObservationsWithValidBoundingBoxes"
+ "cameraIntrinsicMatrixDeliveryEnabled (%d -> %d)"
+ "cameraSensorOrientationCompensationEnabled (%d -> %d)"
+ "captureSession_checkClientIsAllowedToWriteToOutputURLsInRecordingSettings"
+ "captureSession_liveReconfigureAfterWaitingOnStillImageCoordinatorsIfNeeded_block_invoke"
+ "captureSession_liveReconfigureAfterWaitingOnStillImageCoordinatorsIfNeeded_block_invoke_2"
+ "cb85e4188c22fad08accc69478bf1b456af8b5ea"
+ "checkIfFileAlreadyExistForMFO (%d -> %d)"
+ "cinematicFramingControlMode (%d -> %d)"
+ "cinematicFramingEnabled (%d -> %d)"
+ "cinematicFramingSupported (%d -> %d)"
+ "cinematicVideoCaptureEnabled (%d -> %d)"
+ "clientAudioClockDeviceUID (%@ -> %@)"
+ "clientExpectsCameraMountedInLandscapeOrientation (%d -> %d)"
+ "clientIsVOIP (%d -> %d)"
+ "clientOSVersionSupportsDecoupledIO (%d -> %d)"
+ "clientSDKVersionToken (%llu -> %llu)"
+ "clock (%@ -> %@)"
+ "colorSpace (%d -> %d)"
+ "com.apple.osdiags.OSDCameraTester"
+ "com.apple.subjectselectionsession.creation"
+ "configurationID (%lld -> %lld)"
+ "configuresAppAudioSession (%d -> %d)"
+ "configuresAppAudioSessionForBluetoothHighQualityRecording (%d -> %d)"
+ "configuresAppAudioSessionToMixWithOthers (%d -> %d)"
+ "connectionConfigurations.count (%d -> %d)"
+ "connectionConfigurations[%@]: %@"
+ "connectionID (%@ -> %@)"
+ "constantColorClippingRecoveryEnabled (%d -> %d)"
+ "constantColorEnabled (%d -> %d)"
+ "constantColorSaturationBoostEnabled (%d -> %d)"
+ "continuityCameraClientDeviceClass (%d -> %d)"
+ "continuityCameraIsWired (%d -> %d)"
+ "deferred start was never triggered"
+ "deferredProcessingEnabled (%d -> %d)"
+ "deferredStartEnabled (%d -> %d)"
+ "demosaicedRawEnabled (%d -> %d)"
+ "depthDataDeliveryEnabled (%d -> %d)"
+ "depthDataFormat (%@ -> %@)"
+ "depthDataMaxFrameRate (%g -> %g)"
+ "description=CameraCapture-753.0.0.122.3"
+ "deskCamEnabled (%d -> %d)"
+ "deviceOrientationCorrectionEnabled (%d -> %d)"
+ "digitalFlashCaptureEnabled (%d -> %d)"
+ "discardsLateCameraCalibrationData (%d -> %d)"
+ "discardsLateDepthData (%d -> %d)"
+ "discardsLatePointCloudData (%d -> %d)"
+ "discardsLateVideoFrames (%d -> %d)"
+ "dockedTrackingEnabled (%d -> %d)"
+ "droppedFrameReplacementPolicy (%llu -> %llu)"
+ "embeddedCaptureDeviceConfiguration (%@ -> %@)"
+ "emitsEmptyObjectDetectionMetadata (%d -> %d)"
+ "enabled (%d -> %d)"
+ "enabledSemanticSegmentationMatteURNs (%@ -> %@)"
+ "exifFocalLengthsByZoomFactor (%@ -> %@)"
+ "externalSyncFrameRate (%g -> %g)"
+ "faceDetectionConfiguration.BlinkDetectionEnabled (%d -> %d)"
+ "faceDetectionConfiguration.EyeDetectionEnabled (%d -> %d)"
+ "faceDetectionConfiguration.SmileDetectionEnabled (%d -> %d)"
+ "faceDrivenAEAFEnabledByDefault (%d -> %d)"
+ "faceDrivenAEAFMode (%d -> %d)"
+ "faceOcclusionDetectionEnabled (%d -> %d)"
+ "faceTrackingFailureFieldOfViewModifier (%g -> %g)"
+ "faceTrackingMaxFaces (%d -> %d)"
+ "faceTrackingNetworkFailureThresholdMultiplier (%g -> %g)"
+ "faceTrackingPlusEnabled (%d -> %d)"
+ "faceTrackingSuspended (%d -> %d)"
+ "faceTrackingUsesFaceRecognition (%d -> %d)"
+ "fallbackPrimaryConstituentDeviceTypes (%@ -> %@)"
+ "fastCapturePrioritizationEnabled (%d -> %d)"
+ "figcapturerecordingsettings_trace"
+ "filterRenderingEnabled (%d -> %d)"
+ "filteringEnabled (%d -> %d)"
+ "filters (%@ -> %@)"
+ "focusPixelBlurScoreEnabled (%d -> %d)"
+ "formatDescription (%@ -> %@)"
+ "gazeSelectionEnabled (%d -> %d)"
+ "geometricDistortionCorrectionEnabled (%d -> %d)"
+ "highlightRecoveryEnabled (%d -> %d)"
+ "i8@?0"
+ "imageControlMode (%d -> %d)"
+ "intValue"
+ "intelligentDistortionCorrectionEnabled (%d -> %d)"
+ "irisMovieAutoTrimMethod (%d -> %d)"
+ "irisMovieCaptureEnabled (%d -> %d)"
+ "irisMovieCaptureSuspended (%d -> %d)"
+ "irisMovieDuration (%g -> %g)"
+ "irisMovieVideoFrameDuration (%g -> %g)"
+ "irisPreparedSettings (%@ -> %@)"
+ "isMultiCamSession (%d -> %d)"
+ "lensSmudgeDetectionEnabled (%d -> %d)"
+ "lensSmudgeDetectionInterval (%g -> %g)"
+ "live for inflight configurationID %lld"
+ "livePhotoMetadataWritingEnabled (%d -> %d)"
+ "lockedFrameRate (%g -> %g)"
+ "lowLightVideoCaptureEnabled (%d -> %d)"
+ "manualCinematicFramingEnabled (%d -> %d)"
+ "manualFramingPanningAngleX (%g -> %g)"
+ "manualFramingPanningAngleY (%g -> %g)"
+ "maxBufferedFrameCount (%ld -> %ld)"
+ "maxExposureDurationClientOverride (%g -> %g)"
+ "maxFrameRateClientOverride (%g -> %g)"
+ "maxGainClientOverride (%g -> %g)"
+ "maxPhotoDimensions (%@ -> %@)"
+ "maxQualityPrioritization (%d -> %d)"
+ "mediaType (%u -> %u)"
+ "metadataIdentifiers (%@ -> %@)"
+ "metadataRectOfInterest (%@ -> %@)"
+ "mirroringEnabled (%d -> %d)"
+ "momentCaptureMovieRecordingEnabled (%d -> %d)"
+ "motionToWakeTargetFrameRate (%g -> %g)"
+ "msgscheduling_trace"
+ "multiCamClientCompositingEnabled (%d -> %d)"
+ "multiCamClientCompositingPrimaryConnectionID (%@ -> %@)"
+ "nonDestructiveCropEnabled (%d -> %d)"
+ "normalizedNonDestructiveCropSize (%@ -> %@)"
+ "not yet live for inflight configurationID %lld"
+ "objectDetectionTargetFrameRate (%g -> %g)"
+ "optimizedForPreview (%d -> %d)"
+ "optimizesImagesForOfflineVideoStabilization (%d -> %d)"
+ "outputAspectRatio (%d -> %d)"
+ "outputAspectRatioRequestID (%lld -> %lld)"
+ "outputFormat (%d -> %d)"
+ "outputHeight (%d -> %d)"
+ "outputWidth (%d -> %d)"
+ "panoRecordingInProgress (%d -> %d)"
+ "pbtr_cpuBlackFillCompressedRect"
+ "periocularForFaceIDReadinessEnabled (%d -> %d)"
+ "personMaskPixelBuffer"
+ "physicalMirroringForMovieRecordingEnabled (%d -> %d)"
+ "pointCloudOutputDisabled (%d -> %d)"
+ "portTypesWithDeepFusionEnabled"
+ "portraitAutoSuggestEnabled (%d -> %d)"
+ "portraitEffectsMatteDeliveryEnabled (%d -> %d)"
+ "portraitLightingEffectStrength (%g -> %g)"
+ "preferredIOBufferDuration (%@ -> %@)"
+ "preparesCellularRadioForNetworkConnection (%d -> %d)"
+ "preservesDynamicHDRMetadata (%d -> %d)"
+ "preservesIrisMovieCaptureSuspendedOnSessionStop (%d -> %d)"
+ "previewQualityAdjustedPhotoFilterRenderingEnabled (%d -> %d)"
+ "primaryCaptureRectAspectRatio (%g -> %g)"
+ "primaryCaptureRectCenter (%@ -> %@)"
+ "primaryCaptureRectModificationEnabled (%d -> %d)"
+ "primaryCaptureRectUniqueID (%lld -> %lld)"
+ "projectorMode (%d -> %d)"
+ "psr_imageByExtendingForBlackFill"
+ "reactionEffectsEnabled (%d -> %d)"
+ "reactionEffectsSupported (%d -> %d)"
+ "remoteIOOutputFormat (%@ -> %@)"
+ "requestedBufferAttachments (%@ -> %@)"
+ "requiredFormat (%@ -> %@)"
+ "requiredMaxFrameRate (%g -> %g)"
+ "requiredMinFrameRate (%g -> %g)"
+ "responsiveCaptureEnabled (%d -> %d)"
+ "retainedBufferCount (%d -> %d)"
+ "ringLightEnabled (%d -> %d)"
+ "ringLightSupported (%d -> %d)"
+ "rotationDegrees (%d -> %d)"
+ "sceneStabilityMetadataEnabled (%d -> %d)"
+ "secureMetadataUseCase"
+ "semanticStyle (%@ -> %@)"
+ "semanticStyleRenderingEnabled (%d -> %d)"
+ "sensitiveContentAnalyzerEnabled (%d -> %d)"
+ "sensitiveContentAnalyzerXPCObject (%@ -> %@)"
+ "sensorHDREnabled (%d -> %d)"
+ "sessionPreset (%@ -> %@)"
+ "simulatedAperture (%g -> %g)"
+ "sinkConfiguration: %@"
+ "sinkID (%@ -> %@)"
+ "sinkType (%d -> %d)"
+ "skinMaskPixelBuffer"
+ "smartFramingEnabled (%d -> %d)"
+ "smartStyle (%@ -> %@)"
+ "smartStyleControlMode (%d -> %d)"
+ "smartStyleRenderingEnabled (%d -> %d)"
+ "sourceConfiguration: %@"
+ "sourceID (%@ -> %@)"
+ "sourceSubType (%d -> %d)"
+ "spatialAudioChannelLayoutTag (%u -> %u)"
+ "spatialOverCaptureEnabled (%d -> %d)"
+ "ssln_getMasksFromDictionary"
+ "stereoPhotoCaptureEnabled (%d -> %d)"
+ "stereoVideoCaptureEnabled (%d -> %d)"
+ "still in idle state"
+ "studioLightingEnabled (%d -> %d)"
+ "studioLightingSupported (%d -> %d)"
+ "supplementalPointCloudData (%d -> %d)"
+ "suppressVideoEffects (%d -> %d)"
+ "tccIdentity (%@ -> %@)"
+ "tccIdentity (%@/%d -> %@/%d)"
+ "temporalFilterLowLightBandingMitigationEnabled (%d -> %d)"
+ "tenBitFromISPEnabled (%d -> %d)"
+ "testPatternToInject (%llu -> %llu)"
+ "trackErr == 0 "
+ "trueVideoCaptureEnabled (%d -> %d)"
+ "ultraHighResolutionZeroShutterLagSupportEnabled (%d -> %d)"
+ "underlyingDeviceType (%d -> %d)"
+ "usesAppAudioSession (%d -> %d)"
+ "variableFrameRateVideoCaptureEnabled (%d -> %d)"
+ "vcn_encoderCallback_block_invoke_3"
+ "videoGreenGhostMitigationEnabled (%d -> %d)"
+ "videoStabilizationMethod (%d -> %d)"
+ "videoStabilizationStrength (%d -> %d)"
+ "videoStabilizationType (%d -> %d)"
+ "videoZoomFactor (%g -> %g)"
+ "videoZoomRampAcceleration (%g -> %g)"
+ "visualIntelligenceCameraEnabled (%d -> %d)"
+ "windNoiseRemovalEnabled (%d -> %d)"
+ "xctestAuthorizedToStealDevice (%d -> %d)"
+ "zeroShutterLagEnabled (%d -> %d)"
+ "zoomPIPOverlayEnabled (%d -> %d)"
+ "zoomSmoothingEnabled (%d -> %d)"
+ "\xf0\xf0\""
+ "\xf0\xf0\xf0q"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xa1\xf0\xf0!"
- "! CGRectIsNull( trackedRect )"
- "%@ %p: captureID:%lld '%.4s'('%.4s')%@ %dx%d R:%d%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@%@"
- "( lscGridHeader->version == FigCaptureStreamLSCGainGridVersion_2 )"
- "-[BWDisparityAPSScaling adjustedDisparityScaleFactorForDisparityBuffer:focusRect:focusDisatance:initialScale:]"
- "-[BWEspressoInferenceAdapter _newInferenceProviderWithType:networkURL:networkConfiguration:networkConfigurationByLayout:defaultLayout:portraitOrientationSupportEnabled:context:executionTarget:configuration:preventionReasons:resourceProvider:allowedCompressionDirection:concurrentSubmissionLimit:e5Allowed:updateMetadataWithCropRect:additionalCacheKeyAttributes:]"
- "-[BWFigVideoCaptureDevice _ubAdaptiveStillImageCaptureSettingsWithSettings:captureType:captureFlags:sceneFlags:frameStatisticsByPortType:metadata:]"
- "-[BWFigVideoCaptureDevice _ubEVZeroCountForCaptureType:sceneFlags:captureFlags:frameStatistics:]"
- "-[BWFigVideoCaptureDevice _ubResolveStillImageCaptureFlagsForCaptureType:sceneFlags:settings:frameStatisticsByPortType:hdrMode:speedOverQuality:speedOverQualityDowngrade:qualityPrioritization:highResolutionFlavor:ultraHighResolutionDowngrade:canDefer:assetBundle:timeMachineFrameSelectionOut:zeroShutterLagFailureReasonOut:metadata:]"
- "-[BWFigVideoCaptureDevice _ubStillImageCaptureSettingsWithSettings:assetBundle:]"
- "-[BWFigVideoCaptureDevice setNondisruptiveSwitchingFormatIndicesByZoomFactorSIFRBinned:nondisruptiveSwitchingFormatIndicesByZoomFactorSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:forPortType:quadraSubPixelSwitchingParameters:]"
- "-[BWFigVideoCaptureStream setZoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:quadraSubPixelSwitchingParameters:]"
- "-[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:]"
- "-[BWFileCoordinatorNode initWithNumberOfVideoInputs:numberOfAudioInputs:numberOfMetadataInputs:numberOfActionOnlyOutputs:overCaptureEnabled:allowLowLatencyWhenPossible:useTrueVideoFileRecordingStaging:motionDataTimeMachine:]_block_invoke"
- "-[BWInferenceScheduler prepareForInferenceRequirements:dependencyProviderSource:formatProvider:pixelBufferPoolProvider:connection:backPressureDrivenPipelining:engineReconfigured:processingConfiguration:postProcessors:engineDescription:]"
- "-[BWInferenceSchedulerFramebufferBuilder initWithInferenceRequirements:dependencyProvider:formatProvider:processingConfiguration:postProcessors:engineDescription:]"
- "-[BWMultiStreamCameraSourceNode _calculateZoomFactorsToNondisruptiveSwitchingFormatIndexMapping:nondisruptiveSwitchingFormatIndicesByZoomfactorSIFRNonBinnedOut:ultraHighResolutionNondisruptiveStreamingFormatIndex:]"
- "-[BWNondisruptiveSwitchingFormatSelector initWithPortType:quadraSubPixelSwitchingParameters:baseZoomFactor:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRBinned:zoomFactorToNondisruptiveSwitchingFormatIndexSIFRNonBinned:ultraHighResolutionNondisruptiveStreamingFormatIndex:mainFormatSIFRBinningFactor:]"
- "-[BWRealtimeCinematographyNode didReachEndOfDataForInput:]"
- "-[BWRingLightController currentScreenNits]"
- "-[BWRingLightController disableRingLight]"
- "-[BWRingLightController setScreenNitsFloor:]"
- "-[BWStillImageCaptureStreamSettings updateForLearnedFusionMissingEVMinus:missingHDRErrorRecoveryEVZero:]"
- "-[BWTemporalFilterNode initWithMaxLossyCompression:filterSessionConfiguration:lowLightBandingMitigationEnabled:]"
- "-[FigCaptureCustomExposureConfiguration _processConfigurationWithBaseISO:forPortType:]"
- "-[FigCaptureSessionConfiguration _isConnectionConfigurationsArrayEqual:toOtherConnectionConfigurationsArray:]"
- "-[FigCaptureSessionConfiguration isEqual:]"
- "02:28:52"
- "210860e788f3beada193590877ac8d692852fdf5"
- "9c8e3c1920776cf8eeec6ae399defc5475c07d61"
- "<<<< BWBackgroundBlurNode >>>> %s: Setting ring light adaptive settings from %@ to %@"
- "<<<< BWBackgroundBlurNode >>>> %s: Setting ring light recommended nits floor from %f to %f"
- "<<<< BWBackgroundBlurNode >>>> %s: Setting ring light width from %f to %f"
- "<<<< BWBackgroundBlurNode >>>> %s: error (%d) initializing portrait effect, aka _ptEffect"
- "<<<< BWBackgroundBlurNode >>>> %s: ringlight init: s:%d, e:%d, a:%d, b:%f, snf:%f, w:%f, c:%f, ace:%d, rc:%f, as:%d, m:%lu, os:%lu, osc:%i, optt:%@"
- "<<<< BWFigVideoCaptureDevice >>>> %s: [%@] sifrBinned %@, sifrNonBinned %@"
- "<<<< BWFigVideoCaptureStream >>>> %s: %@: Setting zoomFactorToNondisruptiveSwitchingFormatIndex sifrBinned %@, sifrNonBinned %@, mainFormatSIFRBinningFactor %d, ultraHighResolutionNondisruptiveStreamingFormatIndex %d"
- "<<<< BWFigVideoCaptureStream >>>> %s: [%@] Nondisruptive switching format set to %@ with ID:%d, previous %d, minFrameRate %d, maxFrameRate %d, maximumAllowedFrameRate %d, isSecondary %d"
- "<<<< BWGraph >>>> %s: <%p[%{public}d][%{public}@]> Node <%p, %@, %@, %{public}@> Input %{public}@ is %@, but the upstream output %{public}@ is %@."
- "<<<< BWGraph >>>> %s: <%p[%{public}d][%{public}@]> Node <%p, %@, %@, %{public}@> has all inputs in the desired state but still has %@ outputs. Offending outputs: %{public}@"
- "<<<< BWGraph >>>> %s: <%p[%{public}d][%{public}@]> Sink node <%p, %@, %{public}@> is %{public}@ despite all inputs being %@, preventing graph stop completion"
- "<<<< BWGraph >>>> %s: <%p[%{public}d][%{public}@]> Source node <%p, %@, %@, %{public}@> has outputs that aren't yet %@. Possible bug in %@. Offending outputs: %{public}@"
- "<<<< BWGraph >>>> %s: <%p[%{public}d][%{public}@]> node <%p, %@, %@, %{public}@> was never called to start and %@ marked for deferred start. Possible bug in the graph or session framework."
- "<<<< BWLearnSmartStyleRenderer >>>> %s: Styled Sample buffer doesn't have metadata"
- "<<<< BWProResRawMetadataUtilities >>>> %s: Expected LSC grid with header version 2."
- "<<<< BWSmartStyleLearningNode >>>> %s: personMaskSampleBuffer is NULL"
- "<<<< BWSmartStyleLearningNode >>>> %s: refinedPersonMaskPixelBuffer is NULL"
- "<<<< BWSmartStyleLearningNode >>>> %s: refinedPersonMaskSampleBuffer is NULL"
- "<<<< BWSmartStyleLearningNode >>>> %s: refinedSkinMaskPixelBuffer is NULL"
- "<<<< BWSmartStyleLearningNode >>>> %s: refinedSkinMaskSampleBuffer is NULL"
- "<<<< BWSmartStyleLearningNode >>>> %s: refinedSkyMaskPixelBuffer is NULL"
- "<<<< BWSmartStyleLearningNode >>>> %s: refinedSkyMaskSampleBuffer is NULL"
- "<<<< BWSmartStyleLearningNode >>>> %s: skinMaskSampleBuffer is NULL"
- "<<<< BWSmartStyleLearningNode >>>> %s: unrefinedPersonMaskPixelBuffer is NULL"
- "<<<< BWSmartStyleLearningNode >>>> %s: unrefinedPersonMaskSampleBuffer is NULL"
- "<<<< BWSmartStyleLearningNode >>>> %s: unrefinedSkinMaskPixelBuffer is NULL"
- "<<<< BWSmartStyleLearningNode >>>> %s: unrefinedSkinMaskSampleBuffer is NULL"
- "<<<< BWSmartStyleLearningNode >>>> %s: unrefinedSkyMaskPixelBuffer is NULL"
- "<<<< BWSmartStyleLearningNode >>>> %s: unrefinedSkyMaskSampleBuffer is NULL"
- "<<<< BWStillImageCoordinatorNode >>>> %s: Active port type has changed from '%{public}@' to '%{public}@' for captureID:%{public}lld with capture device %{public}@ primary capture stream %{public}@"
- "<<<< CMCaptureLocalSessionController >>>> %s: %@ Failed to create a valid video capture session"
- "<<<< CMCaptureLocalSessionController >>>> %s: %@ Fatal! A valid video capture session was created but failed to copy capture source"
- "<<<< CMCaptureLocalSessionController >>>> %s: %{public}@ Error copying video capture source formats %d"
- "<<<< CMCaptureLocalSessionController >>>> %s: %{public}@ FigCaptureSession %@ Sources %@"
- "<<<< CMCaptureLocalSessionController >>>> %s: %{public}@ FigCaptureSession %@ error:%d"
- "<<<< CMCaptureLocalSessionController >>>> %s: %{public}@ FigCaptureSession for metadata %@ (source %@) error:%d"
- "<<<< CMCaptureLocalSessionController >>>> %s: %{public}@ Invalid metadata capture source deviceFormats array"
- "<<<< CMCaptureLocalSessionController >>>> %s: %{public}@ Invalid video capture source deviceFormats array"
- "<<<< CMCaptureLocalSessionController >>>> %s: %{public}@ create capture session"
- "<<<< CMCaptureLocalSessionController >>>> %s: %{public}@ unable to lock capture source. Error %d"
- "<<<< CMCaptureLocalSessionController >>>> %s: %{public}@ video capture source formats array is NULL"
- "<<<< CMCaptureLocalSessionController >>>> %s: Default activeMinFrameRate:%@ activeMaxFrameRate:%@"
- "<<<< CMCaptureLocalSessionController >>>> %s: Unknown device type %d"
- "<<<< FigCaptureCMClockFromTimeSyncMSGClock >>>> %s: TimeSyncClockGetClockRateAndAnchors failed"
- "<<<< FigCaptureCameraSourcePipeline >>>> %s: smartStyleLearningNode is nil"
- "<<<< FigCaptureDeferredProcessingEngine >>>> %s: [client pid:%d] Releasing resources at background QoS %{public}@. This will be slow since runtime is not guaranteed at this QoS"
- "<<<< FigCaptureMetadataUtilities >>>> %s: rotationDegrees: %d must be a multiple of 90"
- "<<<< FigCapturePhotonicEngineSinkPipeline >>>> %s: Still Image PhotonicEngine Pipeline Configuration (continued):%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@"
- "<<<< FigCapturePhotonicEngineSinkPipeline >>>> %s: Still Image PhotonicEngine Pipeline Configuration (continued):%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@%{public}@"
- "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ Applying sync offset: %llu ticks directly to active MSG sync configuration"
- "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ Clamping offset %llu to lastApplied %llu"
- "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ MSGConfigureDerivedSync failed for V6xP1P2FrontCamCluster: %d"
- "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ Offset would go backward — advanced by %llu frame(s): %llu -> %llu ticks"
- "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ Ramping offset: target=%llu step=%llu -> %llu"
- "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ Received error while doing reset in stop"
- "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ failed configuring V6xP1P2FrontCamCluster follow frameRate: %@ error (%d)"
- "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ failed follow init on kV6xP1P2FrontCamCluster frameRate: %@ error (%d)"
- "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ failed for V6xP1P2FrontCamCluster handler, error (%d)"
- "<<<< FigCapturePulseGenerator >>>> %s: %{public}@ failed starting sync V6xP1P2FrontCamCluster frameRate: %@ error (%d)"
- "<<<< FigCaptureSession >>>> %s: %{public}@ Client requested startRunning without a valid inflightConfiguration - sending DidStopRunning with InvalidConfiguration error"
- "<<<< FigCaptureSession >>>> %s: %{public}@ Client requested startRunning without a valid inflightConfiguration - stopping prewarmed session with InvalidConfiguration error"
- "<<<< FigCaptureSession >>>> %s: Failed to retrieve camera sensor orientation degrees of underlying port type for capture source: (%@) and sink configuration: (%@)"
- "<<<< FigCaptureSession >>>> %s: Trying to live reconfig for output aspect ratio change, but couldn't find a video connection configuration."
- "<<<< FigCaptureSession >>>> %s: called, shouldResetZoomFactorDueToBackgrounding = %d"
- "<<<< FigCaptureSessionConfiguration >>>> %s: Connection configurations are not equal (%d):"
- "<<<< FigCaptureSessionConfiguration >>>> %s: connection array not identical: (%d vs %d)"
- "<<<< FigCaptureSessionConfiguration >>>> %s: connectionConfiguration: %@"
- "<<<< FigCaptureSessionConfiguration >>>> %s: connectionConfigurations connection count doesn't match - (%d vs %d)"
- "<<<< FigCaptureSessionConfiguration >>>> %s: connectionConfigurations doesn't match - connection %@ not found in other"
- "<<<< FigCaptureSessionConfiguration >>>> %s: connections match"
- "<<<< FigCaptureSessionConfiguration >>>> %s: found match for connection %@"
- "<<<< FigCaptureSessionConfiguration >>>> %s: otherConnectionConfiguration: %@"
- "<<<< FigCaptureSourceBackingsProvider >>>> %s: %@: search criteria are ambiguous, '%@%@' also resolves to:\n\n\t%i: %@\n\n\tParams: %@\n\n\t Sticking with first match: \n\n\t%i: %@\n\n\t "
- "<<<< FigCaptureSystemStatus >>>> %s: System Wake"
- "<FigCaptureSource %p> retainCount: %ld%s, allocator: %p, type: %@, position: %@, active = %d, token = %lld, prewarmEnabled = %d"
- "BackCamera"
- "Failed to add BWInferenceTypeVMRefiner inference to BWInferenceEngine"
- "FrontCamera"
- "Full 1:1"
- "FullSquare"
- "LastShownBuild:BWAudioSourceNode.m:3300"
- "LastShownBuild:BWCameraInfoMetadataNode.m:529"
- "LastShownBuild:BWCameraInfoMetadataNode.m:686"
- "LastShownBuild:BWDeepZoomInferenceProvider.m:474"
- "LastShownBuild:BWDeepZoomInferenceProvider.m:554"
- "LastShownBuild:BWE5InferenceProvider.m:812"
- "LastShownBuild:BWFigVideoCaptureDevice.m:10082"
- "LastShownBuild:BWFigVideoCaptureDevice.m:10592"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11043"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11078"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11267"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11276"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11288"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11295"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11323"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11389"
- "LastShownBuild:BWFigVideoCaptureDevice.m:11558"
- "LastShownBuild:BWFigVideoCaptureDevice.m:12466"
- "LastShownBuild:BWFigVideoCaptureDevice.m:15408"
- "LastShownBuild:BWFigVideoCaptureDevice.m:18119"
- "LastShownBuild:BWFigVideoCaptureDevice.m:18510"
- "LastShownBuild:BWFigVideoCaptureDevice.m:1869"
- "LastShownBuild:BWFigVideoCaptureDevice.m:19260"
- "LastShownBuild:BWFigVideoCaptureDevice.m:19727"
- "LastShownBuild:BWFigVideoCaptureDevice.m:19729"
- "LastShownBuild:BWFigVideoCaptureDevice.m:19731"
- "LastShownBuild:BWFigVideoCaptureDevice.m:21581"
- "LastShownBuild:BWFigVideoCaptureDevice.m:22964"
- "LastShownBuild:BWFigVideoCaptureDevice.m:22996"
- "LastShownBuild:BWFigVideoCaptureDevice.m:23136"
- "LastShownBuild:BWFigVideoCaptureDevice.m:23894"
- "LastShownBuild:BWFigVideoCaptureDevice.m:24140"
- "LastShownBuild:BWFigVideoCaptureDevice.m:24492"
- "LastShownBuild:BWFigVideoCaptureDevice.m:5814"
- "LastShownBuild:BWFigVideoCaptureDevice.m:7413"
- "LastShownBuild:BWFigVideoCaptureDevice.m:7422"
- "LastShownBuild:BWFigVideoCaptureDevice.m:8499"
- "LastShownBuild:BWFigVideoCaptureDevice.m:8500"
- "LastShownBuild:BWFigVideoCaptureDevice.m:8519"
- "LastShownBuild:BWFigVideoCaptureDevice.m:8801"
- "LastShownBuild:BWFigVideoCaptureDevice.m:9615"
- "LastShownBuild:BWFigVideoCaptureStream.m:3158"
- "LastShownBuild:BWFigVideoCaptureStream.m:3819"
- "LastShownBuild:BWFigVideoCaptureStream.m:4234"
- "LastShownBuild:BWFileCoordinatorNode.m:1298"
- "LastShownBuild:BWGraph.m:3552"
- "LastShownBuild:BWGraph.m:3555"
- "LastShownBuild:BWGraph.m:3568"
- "LastShownBuild:BWGraph.m:3571"
- "LastShownBuild:BWGraph.m:3574"
- "LastShownBuild:BWInferenceSchedulerFramebufferBuilder.m:491"
- "LastShownBuild:BWInferenceSchedulerFramebufferBuilder.m:501"
- "LastShownBuild:BWInferenceSchedulerFramebufferBuilder.m:514"
- "LastShownBuild:BWIntelligentDistortionCorrectionProcessorController.m:1170"
- "LastShownBuild:BWIntelligentDistortionCorrectionProcessorController.m:1734"
- "LastShownBuild:BWIntelligentDistortionCorrectionProcessorController.m:737"
- "LastShownBuild:BWLearnSmartStyleRenderer.m:340"
- "LastShownBuild:BWMultiStreamCameraSourceNode.m:13524"
- "LastShownBuild:BWMultiStreamCameraSourceNode.m:2689"
- "LastShownBuild:BWMultiStreamCameraSourceNode.m:4366"
- "LastShownBuild:BWMultiStreamCameraSourceNode.m:4373"
- "LastShownBuild:BWMultiStreamCameraSourceNode.m:4380"
- "LastShownBuild:BWMultiStreamCameraSourceNode.m:9303"
- "LastShownBuild:BWNRFProcessorController.m:1658"
- "LastShownBuild:BWNRFProcessorController.m:1659"
- "LastShownBuild:BWNRFProcessorController.m:2057"
- "LastShownBuild:BWPhotoEncoderController.m:1248"
- "LastShownBuild:BWPhotoEncoderController.m:1251"
- "LastShownBuild:BWPhotoEncoderController.m:1637"
- "LastShownBuild:BWPhotoEncoderController.m:1642"
- "LastShownBuild:BWPhotoEncoderController.m:1895"
- "LastShownBuild:BWPhotoEncoderController.m:2034"
- "LastShownBuild:BWPhotoEncoderController.m:2050"
- "LastShownBuild:BWPhotoEncoderController.m:2060"
- "LastShownBuild:BWPhotoEncoderController.m:3219"
- "LastShownBuild:BWPhotoEncoderController.m:4607"
- "LastShownBuild:BWPhotoEncoderController.m:6336"
- "LastShownBuild:BWPhotonicEngineNode.m:1378"
- "LastShownBuild:BWPhotonicEngineNode.m:1438"
- "LastShownBuild:BWPhotonicEngineNode.m:1541"
- "LastShownBuild:BWPhotonicEngineNode.m:1544"
- "LastShownBuild:BWPhotonicEngineNode.m:1568"
- "LastShownBuild:BWPhotonicEngineNode.m:2011"
- "LastShownBuild:BWPhotonicEngineNode.m:2062"
- "LastShownBuild:BWPhotonicEngineNode.m:2353"
- "LastShownBuild:BWPhotonicEngineNode.m:2363"
- "LastShownBuild:BWPhotonicEngineNode.m:2907"
- "LastShownBuild:BWPhotonicEngineNode.m:2944"
- "LastShownBuild:BWPhotonicEngineNode.m:2947"
- "LastShownBuild:BWPhotonicEngineNode.m:3674"
- "LastShownBuild:BWPhotonicEngineNode.m:3689"
- "LastShownBuild:BWPhotonicEngineNode.m:3791"
- "LastShownBuild:BWPhotonicEngineNode.m:3816"
- "LastShownBuild:BWPhotonicEngineNode.m:4876"
- "LastShownBuild:BWPhotonicEngineNode.m:5588"
- "LastShownBuild:BWPhotonicEngineNode.m:5613"
- "LastShownBuild:BWPhotonicEngineNode.m:728"
- "LastShownBuild:BWPhotonicEngineNode.m:742"
- "LastShownBuild:BWPhotonicEngineNode.m:749"
- "LastShownBuild:BWPhotonicEngineNode.m:7697"
- "LastShownBuild:BWPhotonicEngineNode.m:7699"
- "LastShownBuild:BWPhotonicEngineNode.m:9194"
- "LastShownBuild:BWPhotonicEngineNodeResourceCoordinator.m:2514"
- "LastShownBuild:BWPhotonicEngineNodeResourceCoordinator.m:4041"
- "LastShownBuild:BWPhotonicEngineNodeResourceCoordinator.m:4317"
- "LastShownBuild:BWPhotonicEngineNodeResourceCoordinator.m:4520"
- "LastShownBuild:BWPhotonicEngineNodeResourceCoordinator.m:4529"
- "LastShownBuild:BWPhotonicEngineNodeResourceCoordinator.m:4537"
- "LastShownBuild:BWPhotonicEngineNodeUtilities.m:1338"
- "LastShownBuild:BWPixelBufferTransferRenderer.m:621"
- "LastShownBuild:BWSoftISPProcessorController.m:2794"
- "LastShownBuild:BWStillImageCoordinatorNode.m:1400"
- "LastShownBuild:BWStillImageCoordinatorNode.m:1477"
- "LastShownBuild:BWStillImageCoordinatorNode.m:1560"
- "LastShownBuild:BWStillImageCoordinatorNode.m:2164"
- "LastShownBuild:BWStillImageCoordinatorNode.m:3606"
- "LastShownBuild:BWStillImageFilterNode.m:1246"
- "LastShownBuild:BWStillImageMetadataUtilities.m:1048"
- "LastShownBuild:BWStillImageMetadataUtilities.m:128"
- "LastShownBuild:BWStillImageMetadataUtilities.m:1881"
- "LastShownBuild:BWStillImageMetadataUtilities.m:1888"
- "LastShownBuild:BWStillImageMetadataUtilities.m:1894"
- "LastShownBuild:BWStillImageMetadataUtilities.m:1917"
- "LastShownBuild:BWStillImageMetadataUtilities.m:2666"
- "LastShownBuild:BWStillImageMetadataUtilities.m:2696"
- "LastShownBuild:BWStillImageMetadataUtilities.m:660"
- "LastShownBuild:BWStillImageMetadataUtilities.m:794"
- "LastShownBuild:BWStillImageMetadataUtilities.m:973"
- "LastShownBuild:BWStillImageMetadataUtilities.m:979"
- "LastShownBuild:BWStillImageMetadataUtilities.m:991"
- "LastShownBuild:BWTiledE5InferenceProvider.m:856"
- "LastShownBuild:BWTiledE5InferenceProvider.m:889"
- "LastShownBuild:BWUBNRFProcessorController.m:1351"
- "LastShownBuild:BWUBNRFProcessorController.m:1352"
- "LastShownBuild:BWUBNode.m:1018"
- "LastShownBuild:BWUBNode.m:1021"
- "LastShownBuild:BWUBNode.m:1038"
- "LastShownBuild:BWUBNode.m:1180"
- "LastShownBuild:BWUBNode.m:1189"
- "LastShownBuild:BWUBNode.m:1458"
- "LastShownBuild:BWUBNode.m:1888"
- "LastShownBuild:BWUBNode.m:2106"
- "LastShownBuild:BWUBNode.m:2109"
- "LastShownBuild:BWUBNode.m:2196"
- "LastShownBuild:BWUBNode.m:2509"
- "LastShownBuild:BWUBNode.m:3574"
- "LastShownBuild:BWUBNode.m:5548"
- "LastShownBuild:BWUBNode.m:5947"
- "LastShownBuild:BWUBNode.m:6264"
- "LastShownBuild:BWUBNode.m:896"
- "LastShownBuild:BWUBNode.m:923"
- "LastShownBuild:BWUtilities.m:1032"
- "LastShownBuild:BWVISNode.m:2370"
- "LastShownBuild:BWVISNode.m:2388"
- "LastShownBuild:BWVISNode.m:453"
- "LastShownBuild:BWVisionTextOrientationInferenceProvider.m:288"
- "LastShownBuild:CMCaptureLocalSessionController.m:906"
- "LastShownBuild:FigCaptureDeferredProcessingEngine.m:1744"
- "LastShownBuild:FigCaptureMetadataUtilities.m:1489"
- "LastShownBuild:FigCaptureMetadataUtilities.m:6147"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1576"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1582"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1583"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1587"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1731"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1737"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1740"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:1902"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:2961"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3081"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3082"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3245"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3248"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3427"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3431"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:3476"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:4453"
- "LastShownBuild:FigCapturePhotonicEngineSinkPipeline.m:4459"
- "LastShownBuild:FigCaptureSession.m:10812"
- "LastShownBuild:FigCaptureSession.m:10997"
- "LastShownBuild:FigCaptureSession.m:11861"
- "LastShownBuild:FigCaptureSession.m:18258"
- "LastShownBuild:FigCaptureSession.m:19756"
- "LastShownBuild:FigCaptureSession.m:19759"
- "LastShownBuild:FigCaptureSession.m:26937"
- "LastShownBuild:FigCaptureSession.m:4352"
- "LastShownBuild:FigCaptureSession.m:4997"
- "LastShownBuild:FigCaptureSession.m:8876"
- "LastShownBuild:FigCaptureSession.m:8882"
- "LastShownBuild:FigCaptureSession.m:8885"
- "LastShownBuild:FigCaptureSession.m:8888"
- "LastShownBuild:FigCaptureSession.m:8891"
- "LastShownBuild:FigCaptureSession.m:8902"
- "LastShownBuild:FigCaptureSession.m:8905"
- "LastShownBuild:FigCaptureSession.m:8913"
- "LastShownBuild:FigCaptureSession.m:8931"
- "LastShownBuild:FigCaptureSession.m:8976"
- "LastShownBuild:FigCaptureSession.m:8980"
- "LastShownBuild:FigCaptureSession.m:9004"
- "LastShownBuild:FigCaptureSession.m:9019"
- "LastShownBuild:FigCaptureSession.m:9023"
- "LastShownBuild:FigCaptureSession.m:9026"
- "LastShownBuild:FigCaptureSession.m:9149"
- "LastShownBuild:FigCaptureSession.m:9155"
- "LastShownBuild:FigCaptureSession.m:9181"
- "LastShownBuild:FigCaptureSession.m:9193"
- "LastShownBuild:FigCaptureSession.m:9591"
- "LastShownBuild:FigCaptureSession.m:986"
- "LastShownBuild:FigCaptureSession.m:9874"
- "LastShownBuild:FigCaptureSessionStateManager.m:345"
- "LastShownBuild:FigCaptureSessionStateManager.m:377"
- "LastShownBuild:FigCaptureSessionStateManager.m:506"
- "LastShownBuild:FigCaptureSource.m:862"
- "LastShownBuild:FigCaptureSource.m:866"
- "LastShownBuild:FigCaptureSourceBackingsProvider.m:2715"
- "LastShownBuild:FigCaptureUtilities.m:1044"
- "LastShownBuild:FigCaptureUtilities.m:1170"
- "LastShownBuild:FigSampleBufferProcessor_Autofocus.m:926"
- "LastShownDate:BWAudioSourceNode.m:3300"
- "LastShownDate:BWCameraInfoMetadataNode.m:529"
- "LastShownDate:BWCameraInfoMetadataNode.m:686"
- "LastShownDate:BWDeepZoomInferenceProvider.m:474"
- "LastShownDate:BWDeepZoomInferenceProvider.m:554"
- "LastShownDate:BWE5InferenceProvider.m:812"
- "LastShownDate:BWFigVideoCaptureDevice.m:10082"
- "LastShownDate:BWFigVideoCaptureDevice.m:10592"
- "LastShownDate:BWFigVideoCaptureDevice.m:11043"
- "LastShownDate:BWFigVideoCaptureDevice.m:11078"
- "LastShownDate:BWFigVideoCaptureDevice.m:11267"
- "LastShownDate:BWFigVideoCaptureDevice.m:11276"
- "LastShownDate:BWFigVideoCaptureDevice.m:11288"
- "LastShownDate:BWFigVideoCaptureDevice.m:11295"
- "LastShownDate:BWFigVideoCaptureDevice.m:11323"
- "LastShownDate:BWFigVideoCaptureDevice.m:11389"
- "LastShownDate:BWFigVideoCaptureDevice.m:11558"
- "LastShownDate:BWFigVideoCaptureDevice.m:12466"
- "LastShownDate:BWFigVideoCaptureDevice.m:15408"
- "LastShownDate:BWFigVideoCaptureDevice.m:18119"
- "LastShownDate:BWFigVideoCaptureDevice.m:18510"
- "LastShownDate:BWFigVideoCaptureDevice.m:1869"
- "LastShownDate:BWFigVideoCaptureDevice.m:19260"
- "LastShownDate:BWFigVideoCaptureDevice.m:19727"
- "LastShownDate:BWFigVideoCaptureDevice.m:19729"
- "LastShownDate:BWFigVideoCaptureDevice.m:19731"
- "LastShownDate:BWFigVideoCaptureDevice.m:21581"
- "LastShownDate:BWFigVideoCaptureDevice.m:22964"
- "LastShownDate:BWFigVideoCaptureDevice.m:22996"
- "LastShownDate:BWFigVideoCaptureDevice.m:23136"
- "LastShownDate:BWFigVideoCaptureDevice.m:23894"
- "LastShownDate:BWFigVideoCaptureDevice.m:24140"
- "LastShownDate:BWFigVideoCaptureDevice.m:24492"
- "LastShownDate:BWFigVideoCaptureDevice.m:5814"
- "LastShownDate:BWFigVideoCaptureDevice.m:7413"
- "LastShownDate:BWFigVideoCaptureDevice.m:7422"
- "LastShownDate:BWFigVideoCaptureDevice.m:8499"
- "LastShownDate:BWFigVideoCaptureDevice.m:8500"
- "LastShownDate:BWFigVideoCaptureDevice.m:8519"
- "LastShownDate:BWFigVideoCaptureDevice.m:8801"
- "LastShownDate:BWFigVideoCaptureDevice.m:9615"
- "LastShownDate:BWFigVideoCaptureStream.m:3158"
- "LastShownDate:BWFigVideoCaptureStream.m:3819"
- "LastShownDate:BWFigVideoCaptureStream.m:4234"
- "LastShownDate:BWFileCoordinatorNode.m:1298"
- "LastShownDate:BWGraph.m:3552"
- "LastShownDate:BWGraph.m:3555"
- "LastShownDate:BWGraph.m:3568"
- "LastShownDate:BWGraph.m:3571"
- "LastShownDate:BWGraph.m:3574"
- "LastShownDate:BWInferenceSchedulerFramebufferBuilder.m:491"
- "LastShownDate:BWInferenceSchedulerFramebufferBuilder.m:501"
- "LastShownDate:BWInferenceSchedulerFramebufferBuilder.m:514"
- "LastShownDate:BWIntelligentDistortionCorrectionProcessorController.m:1170"
- "LastShownDate:BWIntelligentDistortionCorrectionProcessorController.m:1734"
- "LastShownDate:BWIntelligentDistortionCorrectionProcessorController.m:737"
- "LastShownDate:BWLearnSmartStyleRenderer.m:340"
- "LastShownDate:BWMultiStreamCameraSourceNode.m:13524"
- "LastShownDate:BWMultiStreamCameraSourceNode.m:2689"
- "LastShownDate:BWMultiStreamCameraSourceNode.m:4366"
- "LastShownDate:BWMultiStreamCameraSourceNode.m:4373"
- "LastShownDate:BWMultiStreamCameraSourceNode.m:4380"
- "LastShownDate:BWMultiStreamCameraSourceNode.m:9303"
- "LastShownDate:BWNRFProcessorController.m:1658"
- "LastShownDate:BWNRFProcessorController.m:1659"
- "LastShownDate:BWNRFProcessorController.m:2057"
- "LastShownDate:BWPhotoEncoderController.m:1248"
- "LastShownDate:BWPhotoEncoderController.m:1251"
- "LastShownDate:BWPhotoEncoderController.m:1637"
- "LastShownDate:BWPhotoEncoderController.m:1642"
- "LastShownDate:BWPhotoEncoderController.m:1895"
- "LastShownDate:BWPhotoEncoderController.m:2034"
- "LastShownDate:BWPhotoEncoderController.m:2050"
- "LastShownDate:BWPhotoEncoderController.m:2060"
- "LastShownDate:BWPhotoEncoderController.m:3219"
- "LastShownDate:BWPhotoEncoderController.m:4607"
- "LastShownDate:BWPhotoEncoderController.m:6336"
- "LastShownDate:BWPhotonicEngineNode.m:1378"
- "LastShownDate:BWPhotonicEngineNode.m:1438"
- "LastShownDate:BWPhotonicEngineNode.m:1541"
- "LastShownDate:BWPhotonicEngineNode.m:1544"
- "LastShownDate:BWPhotonicEngineNode.m:1568"
- "LastShownDate:BWPhotonicEngineNode.m:2011"
- "LastShownDate:BWPhotonicEngineNode.m:2062"
- "LastShownDate:BWPhotonicEngineNode.m:2353"
- "LastShownDate:BWPhotonicEngineNode.m:2363"
- "LastShownDate:BWPhotonicEngineNode.m:2907"
- "LastShownDate:BWPhotonicEngineNode.m:2944"
- "LastShownDate:BWPhotonicEngineNode.m:2947"
- "LastShownDate:BWPhotonicEngineNode.m:3674"
- "LastShownDate:BWPhotonicEngineNode.m:3689"
- "LastShownDate:BWPhotonicEngineNode.m:3791"
- "LastShownDate:BWPhotonicEngineNode.m:3816"
- "LastShownDate:BWPhotonicEngineNode.m:4876"
- "LastShownDate:BWPhotonicEngineNode.m:5588"
- "LastShownDate:BWPhotonicEngineNode.m:5613"
- "LastShownDate:BWPhotonicEngineNode.m:728"
- "LastShownDate:BWPhotonicEngineNode.m:742"
- "LastShownDate:BWPhotonicEngineNode.m:749"
- "LastShownDate:BWPhotonicEngineNode.m:7697"
- "LastShownDate:BWPhotonicEngineNode.m:7699"
- "LastShownDate:BWPhotonicEngineNode.m:9194"
- "LastShownDate:BWPhotonicEngineNodeResourceCoordinator.m:2514"
- "LastShownDate:BWPhotonicEngineNodeResourceCoordinator.m:4041"
- "LastShownDate:BWPhotonicEngineNodeResourceCoordinator.m:4317"
- "LastShownDate:BWPhotonicEngineNodeResourceCoordinator.m:4520"
- "LastShownDate:BWPhotonicEngineNodeResourceCoordinator.m:4529"
- "LastShownDate:BWPhotonicEngineNodeResourceCoordinator.m:4537"
- "LastShownDate:BWPhotonicEngineNodeUtilities.m:1338"
- "LastShownDate:BWPixelBufferTransferRenderer.m:621"
- "LastShownDate:BWSoftISPProcessorController.m:2794"
- "LastShownDate:BWStillImageCoordinatorNode.m:1400"
- "LastShownDate:BWStillImageCoordinatorNode.m:1477"
- "LastShownDate:BWStillImageCoordinatorNode.m:1560"
- "LastShownDate:BWStillImageCoordinatorNode.m:2164"
- "LastShownDate:BWStillImageCoordinatorNode.m:3606"
- "LastShownDate:BWStillImageFilterNode.m:1246"
- "LastShownDate:BWStillImageMetadataUtilities.m:1048"
- "LastShownDate:BWStillImageMetadataUtilities.m:128"
- "LastShownDate:BWStillImageMetadataUtilities.m:1881"
- "LastShownDate:BWStillImageMetadataUtilities.m:1888"
- "LastShownDate:BWStillImageMetadataUtilities.m:1894"
- "LastShownDate:BWStillImageMetadataUtilities.m:1917"
- "LastShownDate:BWStillImageMetadataUtilities.m:2666"
- "LastShownDate:BWStillImageMetadataUtilities.m:2696"
- "LastShownDate:BWStillImageMetadataUtilities.m:660"
- "LastShownDate:BWStillImageMetadataUtilities.m:794"
- "LastShownDate:BWStillImageMetadataUtilities.m:973"
- "LastShownDate:BWStillImageMetadataUtilities.m:979"
- "LastShownDate:BWStillImageMetadataUtilities.m:991"
- "LastShownDate:BWTiledE5InferenceProvider.m:856"
- "LastShownDate:BWTiledE5InferenceProvider.m:889"
- "LastShownDate:BWUBNRFProcessorController.m:1351"
- "LastShownDate:BWUBNRFProcessorController.m:1352"
- "LastShownDate:BWUBNode.m:1018"
- "LastShownDate:BWUBNode.m:1021"
- "LastShownDate:BWUBNode.m:1038"
- "LastShownDate:BWUBNode.m:1180"
- "LastShownDate:BWUBNode.m:1189"
- "LastShownDate:BWUBNode.m:1458"
- "LastShownDate:BWUBNode.m:1888"
- "LastShownDate:BWUBNode.m:2106"
- "LastShownDate:BWUBNode.m:2109"
- "LastShownDate:BWUBNode.m:2196"
- "LastShownDate:BWUBNode.m:2509"
- "LastShownDate:BWUBNode.m:3574"
- "LastShownDate:BWUBNode.m:5548"
- "LastShownDate:BWUBNode.m:5947"
- "LastShownDate:BWUBNode.m:6264"
- "LastShownDate:BWUBNode.m:896"
- "LastShownDate:BWUBNode.m:923"
- "LastShownDate:BWUtilities.m:1032"
- "LastShownDate:BWVISNode.m:2370"
- "LastShownDate:BWVISNode.m:2388"
- "LastShownDate:BWVISNode.m:453"
- "LastShownDate:BWVisionTextOrientationInferenceProvider.m:288"
- "LastShownDate:CMCaptureLocalSessionController.m:906"
- "LastShownDate:FigCaptureDeferredProcessingEngine.m:1744"
- "LastShownDate:FigCaptureMetadataUtilities.m:1489"
- "LastShownDate:FigCaptureMetadataUtilities.m:6147"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1576"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1582"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1583"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1587"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1731"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1737"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1740"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:1902"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:2961"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3081"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3082"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3245"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3248"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3427"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3431"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:3476"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:4453"
- "LastShownDate:FigCapturePhotonicEngineSinkPipeline.m:4459"
- "LastShownDate:FigCaptureSession.m:10812"
- "LastShownDate:FigCaptureSession.m:10997"
- "LastShownDate:FigCaptureSession.m:11861"
- "LastShownDate:FigCaptureSession.m:18258"
- "LastShownDate:FigCaptureSession.m:19756"
- "LastShownDate:FigCaptureSession.m:19759"
- "LastShownDate:FigCaptureSession.m:26937"
- "LastShownDate:FigCaptureSession.m:4352"
- "LastShownDate:FigCaptureSession.m:4997"
- "LastShownDate:FigCaptureSession.m:8876"
- "LastShownDate:FigCaptureSession.m:8882"
- "LastShownDate:FigCaptureSession.m:8885"
- "LastShownDate:FigCaptureSession.m:8888"
- "LastShownDate:FigCaptureSession.m:8891"
- "LastShownDate:FigCaptureSession.m:8902"
- "LastShownDate:FigCaptureSession.m:8905"
- "LastShownDate:FigCaptureSession.m:8913"
- "LastShownDate:FigCaptureSession.m:8931"
- "LastShownDate:FigCaptureSession.m:8976"
- "LastShownDate:FigCaptureSession.m:8980"
- "LastShownDate:FigCaptureSession.m:9004"
- "LastShownDate:FigCaptureSession.m:9019"
- "LastShownDate:FigCaptureSession.m:9023"
- "LastShownDate:FigCaptureSession.m:9026"
- "LastShownDate:FigCaptureSession.m:9149"
- "LastShownDate:FigCaptureSession.m:9155"
- "LastShownDate:FigCaptureSession.m:9181"
- "LastShownDate:FigCaptureSession.m:9193"
- "LastShownDate:FigCaptureSession.m:9591"
- "LastShownDate:FigCaptureSession.m:986"
- "LastShownDate:FigCaptureSession.m:9874"
- "LastShownDate:FigCaptureSessionStateManager.m:345"
- "LastShownDate:FigCaptureSessionStateManager.m:377"
- "LastShownDate:FigCaptureSessionStateManager.m:506"
- "LastShownDate:FigCaptureSource.m:862"
- "LastShownDate:FigCaptureSource.m:866"
- "LastShownDate:FigCaptureSourceBackingsProvider.m:2715"
- "LastShownDate:FigCaptureUtilities.m:1044"
- "LastShownDate:FigCaptureUtilities.m:1170"
- "LastShownDate:FigSampleBufferProcessor_Autofocus.m:926"
- "LearnedFusionHDRErrorRecoveryEVZero"
- "May 28 2026"
- "[graph connectOutput:videoCaptureOutput toInput:dockkitNode.input pipelineStage:((void *)0)]"
- "da786fa9df45462ab85e4f458dd648a94b7dcb9f"
- "description=CameraCapture-748.0.0.122.2"
- "fcft_GetRate"
- "fsqr"
- "refinedPersonMaskPixelBuffer"
- "refinedPersonMaskSampleBuffer"
- "refinedSkinMaskPixelBuffer"
- "refinedSkinMaskSampleBuffer"
- "refinedSkyMaskPixelBuffer"
- "refinedSkyMaskSampleBuffer"
- "requiredFormat.isDynamicAspectRatioSupported"
- "unrefinedPersonMaskPixelBuffer"
- "unrefinedPersonMaskSampleBuffer"
- "unrefinedSkinMaskPixelBuffer"
- "unrefinedSkinMaskSampleBuffer"
- "unrefinedSkyMaskPixelBuffer"
- "unrefinedSkyMaskSampleBuffer"
- "vcn_encoderCallback_block_invoke_2"
- "\xf0\xc2"
- "\xf0\xf0\xf0\xf01"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\x81\xf0\xf0!"
```
