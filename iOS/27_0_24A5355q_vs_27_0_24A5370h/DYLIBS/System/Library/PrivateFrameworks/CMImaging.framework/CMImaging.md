## CMImaging

> `/System/Library/PrivateFrameworks/CMImaging.framework/CMImaging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e1c0c` | `0x1dd8a4` | **`-0x4368`** |
| `__TEXT.__oslogstring` | `0x14b01` | `0x1526c` | **`+0x76b`** |
| `__AUTH_CONST.__objc_const` | `0x1e930` | `0x1f050` | **`+0x720`** |
| `__TEXT.__eh_frame` | `0xb90` | `0x6a0` | **`-0x4f0`** |
| `__TEXT.__cstring` | `0x2866a` | `0x28ae8` | **`+0x47e`** |
| `__TEXT.__objc_methlist` | `0xd0cc` | `0xd31c` | **`+0x250`** |
| `__AUTH.__objc_data` | `0x50` | `0x1e0` | **`+0x190`** |
| `__TEXT.__unwind_info` | `0x3120` | `0x31d0` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x61d0` | `0x6218` | **`+0x48`** |
| `__DATA.__objc_ivar` | `0x1784` | `0x17c4` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xbd0` | `0xc00` | **`+0x30`** |
| `__DATA_CONST.__objc_classlist` | `0x5d0` | `0x5f8` | **`+0x28`** |
| `__DATA_CONST.__objc_superrefs` | `0x4b0` | `0x4c8` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1550` | `0x154c` | **`-0x4`** |

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3

-  Functions: 7514
-  Symbols:   8643
-  CStrings:  5248
+  Functions: 7581
+  Symbols:   8750
+  CStrings:  5286
Symbols:
+ +[CMIInferenceBypassResourceDescriptor bypassTextureDescriptorWithName:direction:layout:pixelFormat:width:height:depth:arrayLength:]
+ -[CMIInferenceBypassResourceDescriptor arrayLength]
+ -[CMIInferenceBypassResourceDescriptor depth]
+ -[CMIInferenceBypassResourceDescriptor height]
+ -[CMIInferenceBypassResourceDescriptor setArrayLength:]
+ -[CMIInferenceBypassResourceDescriptor setDepth:]
+ -[CMIInferenceBypassResourceDescriptor setHeight:]
+ -[CMIInferenceBypassResourceDescriptor setWidth:]
+ -[CMIInferenceBypassResourceDescriptor width]
+ -[CMIInferenceDeviceBypass createExecutionStream]
+ -[CMIInferenceDeviceBypass init]
+ -[CMIInferenceDeviceBypass loadNetworkWithPath:shareIntermediates:]
+ -[CMIInferenceExecutionStreamBypass enqueueNetworkInstance:]
+ -[CMIInferenceExecutionStreamBypass init]
+ -[CMIInferenceExecutionStreamBypass submitAsyncWithCompletionHandler:]
+ -[CMIInferenceNetworkBypass .cxx_destruct]
+ -[CMIInferenceNetworkBypass allocateInstancesWithDevice:instanceCount:useTextureArrays:]
+ -[CMIInferenceNetworkBypass bindBufferPortsWithDescriptors:]
+ -[CMIInferenceNetworkBypass bindIOPortsWithInputDescriptors:withOutputDescriptors:]
+ -[CMIInferenceNetworkBypass getInputs]
+ -[CMIInferenceNetworkBypass getInstanceWithIndex:]
+ -[CMIInferenceNetworkBypass getOutputs]
+ -[CMIInferenceNetworkBypass init]
+ -[CMIInferenceNetworkBypass verifyBindings]
+ -[CMIInferenceNetworkInstanceBypass .cxx_destruct]
+ -[CMIInferenceNetworkInstanceBypass _allocateTexturesWithDevice:descriptors:useTextureArrays:outputTextureArray:]
+ -[CMIInferenceNetworkInstanceBypass buffers]
+ -[CMIInferenceNetworkInstanceBypass inputTextures]
+ -[CMIInferenceNetworkInstanceBypass outputTextures]
+ -[CMIInferenceNetworkInstanceBypass parentNetwork]
+ -[CMIInferenceNetworkInstanceBypass setBuffers:]
+ -[CMIInferenceNetworkInstanceBypass setInputTextures:]
+ -[CMIInferenceNetworkInstanceBypass setOutputTextures:]
+ -[CMIInferenceNetworkInstanceBypass setParentNetwork:]
+ -[CMIInferenceNetworkInstanceBypass synchronizeMetalWaitOnNetworkSignal:]
+ -[CMIInferenceNetworkInstanceBypass synchronizeNetworkWaitOnMetalSignal:]
+ -[CMIStyleEngineApplyStyle inputSkinMaskImage]
+ -[CMIStyleEngineApplyStyle setInputSkinMaskImage:]
+ -[CMIStyleEngineProcessor inputSkinMaskPixelBuffer]
+ -[CMIStyleEngineProcessor setInputSkinMaskPixelBuffer:]
+ -[CMITiledInferenceProcessorNetworkConfig setSkipInference:]
+ -[CMITiledInferenceProcessorNetworkConfig skipInference]
+ -[FigM2MController _initWithTransformPriority:]
+ -[FigM2MController initWithTransformPriority:]
+ GCC_except_table91
+ GCC_except_table92
+ _CMILSCOISAdaptation_extrapolateV3LSCTable
+ _CMIUtilitiesGetFinalCropRect
+ _OBJC_CLASS_$_CMIInferenceBypassResourceDescriptor
+ _OBJC_CLASS_$_CMIInferenceDeviceBypass
+ _OBJC_CLASS_$_CMIInferenceExecutionStreamBypass
+ _OBJC_CLASS_$_CMIInferenceNetworkBypass
+ _OBJC_CLASS_$_CMIInferenceNetworkInstanceBypass
+ _OBJC_IVAR_$_CMIInferenceBypassResourceDescriptor._arrayLength
+ _OBJC_IVAR_$_CMIInferenceBypassResourceDescriptor._depth
+ _OBJC_IVAR_$_CMIInferenceBypassResourceDescriptor._height
+ _OBJC_IVAR_$_CMIInferenceBypassResourceDescriptor._width
+ _OBJC_IVAR_$_CMIInferenceNetworkBypass._bufferDescriptors
+ _OBJC_IVAR_$_CMIInferenceNetworkBypass._inputDescriptors
+ _OBJC_IVAR_$_CMIInferenceNetworkBypass._instances
+ _OBJC_IVAR_$_CMIInferenceNetworkBypass._outputDescriptors
+ _OBJC_IVAR_$_CMIInferenceNetworkInstanceBypass._buffers
+ _OBJC_IVAR_$_CMIInferenceNetworkInstanceBypass._inputTextures
+ _OBJC_IVAR_$_CMIInferenceNetworkInstanceBypass._outputTextures
+ _OBJC_IVAR_$_CMIInferenceNetworkInstanceBypass._parentNetwork
+ _OBJC_IVAR_$_CMISmartStyleUtilitiesV1._inputSkinMaskPixelBuffer
+ _OBJC_IVAR_$_CMIStyleEngineApplyStyle._inputSkinMaskImage
+ _OBJC_IVAR_$_CMIStyleEngineProcessor._inputSkinMaskPixelBuffer
+ _OBJC_IVAR_$_CMITiledInferenceProcessorNetworkConfig._skipInference
+ _OBJC_METACLASS_$_CMIInferenceBypassResourceDescriptor
+ _OBJC_METACLASS_$_CMIInferenceDeviceBypass
+ _OBJC_METACLASS_$_CMIInferenceExecutionStreamBypass
+ _OBJC_METACLASS_$_CMIInferenceNetworkBypass
+ _OBJC_METACLASS_$_CMIInferenceNetworkInstanceBypass
+ __OBJC_$_CLASS_METHODS_CMIInferenceBypassResourceDescriptor
+ __OBJC_$_INSTANCE_METHODS_CMIInferenceBypassResourceDescriptor
+ __OBJC_$_INSTANCE_METHODS_CMIInferenceDeviceBypass
+ __OBJC_$_INSTANCE_METHODS_CMIInferenceExecutionStreamBypass
+ __OBJC_$_INSTANCE_METHODS_CMIInferenceNetworkBypass
+ __OBJC_$_INSTANCE_METHODS_CMIInferenceNetworkInstanceBypass
+ __OBJC_$_INSTANCE_VARIABLES_CMIInferenceBypassResourceDescriptor
+ __OBJC_$_INSTANCE_VARIABLES_CMIInferenceNetworkBypass
+ __OBJC_$_INSTANCE_VARIABLES_CMIInferenceNetworkInstanceBypass
+ __OBJC_$_PROP_LIST_CMIInferenceBypassResourceDescriptor
+ __OBJC_$_PROP_LIST_CMIInferenceDeviceBypass
+ __OBJC_$_PROP_LIST_CMIInferenceExecutionStreamBypass
+ __OBJC_$_PROP_LIST_CMIInferenceNetworkBypass
+ __OBJC_$_PROP_LIST_CMIInferenceNetworkInstanceBypass
+ __OBJC_CLASS_PROTOCOLS_$_CMIInferenceDeviceBypass
+ __OBJC_CLASS_PROTOCOLS_$_CMIInferenceExecutionStreamBypass
+ __OBJC_CLASS_PROTOCOLS_$_CMIInferenceNetworkBypass
+ __OBJC_CLASS_PROTOCOLS_$_CMIInferenceNetworkInstanceBypass
+ __OBJC_CLASS_RO_$_CMIInferenceBypassResourceDescriptor
+ __OBJC_CLASS_RO_$_CMIInferenceDeviceBypass
+ __OBJC_CLASS_RO_$_CMIInferenceExecutionStreamBypass
+ __OBJC_CLASS_RO_$_CMIInferenceNetworkBypass
+ __OBJC_CLASS_RO_$_CMIInferenceNetworkInstanceBypass
+ __OBJC_METACLASS_RO_$_CMIInferenceBypassResourceDescriptor
+ __OBJC_METACLASS_RO_$_CMIInferenceDeviceBypass
+ __OBJC_METACLASS_RO_$_CMIInferenceExecutionStreamBypass
+ __OBJC_METACLASS_RO_$_CMIInferenceNetworkBypass
+ __OBJC_METACLASS_RO_$_CMIInferenceNetworkInstanceBypass
+ ___destructor_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88_s96_s104_s112_s120_s128_s136_s144_s152_s160_s168_s176_s184_s192_s200_s208
+ ___move_assignment_8_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88_s96_s104_s112_s120_s128_s136_s144_s152_s160_s168_s176_s184_s192_s200_s208
+ _createCMIInferenceDeviceBypass
+ _extrapolateSingleChannelGrid
+ _kFigCaptureSampleBufferMetadata_FinalCropRect
+ _kFigCaptureStreamMetadata_AngleInfoRoll
+ _kFigCaptureStreamMetadata_EyeCoveringConfidenceLevel
+ _kFigCaptureStreamMetadata_FaceMaskConfidenceLevel
+ _kIOSurfaceAcceleratorPriorityBand
- GCC_except_table87
- GCC_except_table90
- ___destructor_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88_s96_s104_s112_s120_s128_s136_s144_s152_s160_s168_s176_s184_s192_s200
- ___move_assignment_8_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88_s96_s104_s112_s120_s128_s136_s144_s152_s160_s168_s176_s184_s192_s200
CStrings:
+ "( inputLSCGridHeader->properties == FigCaptureStreamLSCGainGridPropertyFlag_None || inputLSCGridHeader->properties == FigCaptureStreamLSCGainGridPropertyFlag_OISAdaptive_LSCExtrapCropLumaOnly_CICExtrapCrop )"
+ "(nil)"
+ "-[CMIInferenceDeviceBypass loadNetworkWithPath:shareIntermediates:]"
+ "-[CMIInferenceExecutionStreamBypass enqueueNetworkInstance:]"
+ "-[CMIInferenceNetworkBypass allocateInstancesWithDevice:instanceCount:useTextureArrays:]"
+ "-[CMIInferenceNetworkBypass getInstanceWithIndex:]"
+ "-[CMIInferenceNetworkInstanceBypass _allocateTexturesWithDevice:descriptors:useTextureArrays:outputTextureArray:]"
+ "-[CMIInferenceNetworkInstanceBypass synchronizeMetalWaitOnNetworkSignal:]"
+ "-[CMIInferenceNetworkInstanceBypass synchronizeNetworkWaitOnMetalSignal:]"
+ "-[FigM2MController _initWithTransformPriority:]"
+ "<<<< CMITIP >>>> %s: CMITIP bypass: loadNetworkWithPath: %s (ignored — no Espresso/ANE)."
+ "<<<< CMITIP >>>> %s: CMITIP: skipInference enabled, no Espresso/ANE will be engaged."
+ "<<<< CMITIP >>>> %s: _allocateTexturesWithDevice (inputs) failed (%d)."
+ "<<<< CMITIP >>>> %s: _allocateTexturesWithDevice (outputs) failed (%d)."
+ "<<<< CMITIP >>>> %s: commandBuffer must not be enqueued."
+ "<<<< CMITIP >>>> %s: device nil."
+ "<<<< CMITIP >>>> %s: failed to create _inferenceDevice with createCMIInferenceDeviceBypass."
+ "<<<< CMITIP >>>> %s: instance must be CMIInferenceNetworkInstanceBypass."
+ "<<<< CMITIP >>>> %s: instanceCount must be > 0."
+ "<<<< CMITIP >>>> %s: instanceIndex %lu out of range (count=%lu)."
+ "<<<< CMITIP >>>> %s: newTextureWithDescriptor failed for bypass descriptor '%s'."
+ "<<<< CMITIP >>>> %s: skipInference descriptor '%s' depth (%lu) must be a positive multiple of pixelFormat components (%lu)."
+ "<<<< CMITIP >>>> %s: skipInference descriptor '%s' has unsupported pixel format."
+ "<<<< CMITIP >>>> %s: skipInference descriptor '%s' is not a texture descriptor (buffers not supported in bypass)."
+ "<<<< CMITIP >>>> %s: skipInference descriptor '%s' missing shape (width=%lu height=%lu depth=%lu). Set them via the shape-bearing factory."
+ "<<<< CMITIP >>>> %s: skipInference descriptor '%s' must be a CMIInferenceBypassResourceDescriptor — use +bypassTextureDescriptorWithName:... to construct it."
+ "<<<< CMITIP >>>> %s: skipInference input descriptor '%s' must be a CMIInferenceBypassResourceDescriptor when descriptors are non-empty (carries width/height/depth that the bypass device needs)."
+ "<<<< CMITIP >>>> %s: skipInference must be uniform across pipeline stages: stage '%s' skip=%d disagrees with first stage skip=%d."
+ "<<<< CMITIP >>>> %s: skipInference output descriptor '%s' must be a CMIInferenceBypassResourceDescriptor when descriptors are non-empty."
+ "<<<< FigMetalContext >>>> %s: [id<MTLDevice> newBinaryArchiveWithDescriptor:error:] failed - %@ [binaryArchivePath = %@]"
+ "<<<< FigMetalContext >>>> %s: [id<MTLDeviceSPI> newPipelineLibraryWithFilePath:error:] failed - %@ [pipelineLibraryPath = %@]"
+ "CMILSCOISAdaptation_extrapolateV3LSCTable"
+ "IOSurfaceAcceleratorCreate with priority band create options failed"
+ "err = FigSignalErrorAt3(\"%s%s%s signalled err=%d (%s) (%s) at %s:%d\", gStyleEngineProcessorTrace.note.emitter, (CMIStyleEngineStatusResourcesNotReleased), \"CMIStyleEngineStatusResourcesNotReleased\", (\"FigMetalAllocator resources not correctly released\"), \"<<<< StyleEngineProcessor >>>>\", __FUNCTION__, \"CMIStyleEngineProcessor.m\", 3586, __builtin_return_address(0), 0) == 0 "
+ "input skin mask"
+ "inputLSCGainGrid is not version 3"
+ "inputLSCGainGrid->version == FigCaptureStreamLSCGainGridVersion_3"
+ "inputLSCGridHeader->lscApertureInfoCount > 0 && inputLSCGridHeader->lscApertureInfoCount <= 4"
+ "inputV3LSCdata"
+ "inputV3LSCdata is nil"
+ "lscApertureInfoCount is out of range [1, 4]"
+ "memorySizeOfInput == [inputV3LSCdata length]"
+ "outputV3LSCData"
+ "outputV3LSCData pointer is nil"
- "( inputLSCGridHeader->properties == 0 || inputLSCGridHeader->properties == 2 )"
- "-[FigM2MController init]"
- "<<<< FigMetalContext >>>> %s: [id<MTLDevice> newBinaryArchiveWithDescriptor:error:] failed - %@"
- "<<<< FigMetalContext >>>> %s: [id<MTLDeviceSPI> newPipelineLibraryWithFilePath:error:] failed - %@"
- "IOSurfaceAcceleratorCreate failed"
- "err = FigSignalErrorAt3(\"%s%s%s signalled err=%d (%s) (%s) at %s:%d\", gStyleEngineProcessorTrace.note.emitter, (CMIStyleEngineStatusResourcesNotReleased), \"CMIStyleEngineStatusResourcesNotReleased\", (\"FigMetalAllocator resources not correctly released\"), \"<<<< StyleEngineProcessor >>>>\", __FUNCTION__, \"CMIStyleEngineProcessor.m\", 3574, __builtin_return_address(0), 0) == 0 "
```
