## ISPKit

> `/System/Library/PrivateFrameworks/ISPKit.framework/ISPKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e10c` | `0x1ff04` | **`+0x1df8`** |
| `__AUTH_CONST.__objc_const` | `0x6c20` | `0x6f98` | **`+0x378`** |
| `__AUTH_CONST.__cfstring` | `0x1340` | `0x16a0` | **`+0x360`** |
| `__TEXT.__cstring` | `0x143d` | `0x1764` | **`+0x327`** |
| `__TEXT.__gcc_except_tab` | `0x358` | `0x620` | **`+0x2c8`** |
| `__TEXT.__oslogstring` | `0x2caa` | `0x2ece` | **`+0x224`** |
| `__TEXT.__objc_methlist` | `0x1da4` | `0x1f9c` | **`+0x1f8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1138` | `0x12a0` | **`+0x168`** |
| `__AUTH.__objc_data` | `0x190` | `0x280` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x588` | `0x660` | **`+0xd8`** |
| `__DATA_CONST.__const` | `0x1c8` | `0x290` | **`+0xc8`** |
| `__DATA_DIRTY.__objc_data` | `0xe10` | `0xdc0` | **`-0x50`** |
| `__DATA.__objc_ivar` | `0x588` | `0x5b8` | **`+0x30`** |
| `__TEXT.__const` | `0x260` | `0x280` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x30` | `0x48` | **`+0x18`** |
| `__AUTH_CONST.__weak_auth_got` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x60` | `0x70` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x190` | `0x1a0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x130` | `0x140` | **`+0x10`** |

### Other Changes

```diff

-20.47.7.0.0
+20.50.6.1.0

-  Functions: 900
-  Symbols:   1580
-  CStrings:  509
+  Functions: 938
+  Symbols:   1686
+  CStrings:  543
Symbols:
+ +[ABDNoiseAddbackState createLookupTableFrom:]
+ +[ABDNoiseAddbackState getFloatValueFrom:at:]
+ -[ABDLookupTable dealloc]
+ -[ABDLookupTable getValueFor:]
+ -[ABDLookupTable initFromArray:]
+ -[ABDLookupTable initFromKeys:andValues:]
+ -[ABDLookupTable initFromLookupTable:]
+ -[ABDLookupTable keys]
+ -[ABDLookupTable setKeys:]
+ -[ABDLookupTable setSize:]
+ -[ABDLookupTable setValues:]
+ -[ABDLookupTable size]
+ -[ABDLookupTable values]
+ -[ABDNetworkNoiseAddback .cxx_destruct]
+ -[ABDNetworkNoiseAddback dealloc]
+ -[ABDNetworkNoiseAddback getFactorFromLux:andGain:]
+ -[ABDNetworkNoiseAddback init]
+ -[ABDNetworkNoiseAddback load:]
+ -[ABDNetworkNoiseAddback observeValueForKeyPath:ofObject:change:context:]
+ -[ABDNetworkNoiseAddback reset]
+ -[ABDNoiseAddbackState .cxx_destruct]
+ -[ABDNoiseAddbackState bias]
+ -[ABDNoiseAddbackState gainFactor]
+ -[ABDNoiseAddbackState gainTable]
+ -[ABDNoiseAddbackState getValueForLux:andGain:]
+ -[ABDNoiseAddbackState initFromDictionary:]
+ -[ABDNoiseAddbackState initFromOther:]
+ -[ABDNoiseAddbackState luxFactor]
+ -[ABDNoiseAddbackState luxTable]
+ -[ABDNoiseAddbackState setBias:]
+ -[ABDNoiseAddbackState setGainFactor:]
+ -[ABDNoiseAddbackState setGainTable:]
+ -[ABDNoiseAddbackState setLuxFactor:]
+ -[ABDNoiseAddbackState setLuxTable:]
+ -[HybridWarper encodeToCommandBuffer:tuningGroup:homography:currentY_mipmap:historyY_mipmap:history_YUV:anstRawMask:opticalFlow:warped_YUV:totalGain:flowThresholdScaler:inputValidRect:isHomographyReliable:isTripodDetected:]
+ -[LLVProcessorBufferManager fusionWeightMap]
+ -[LLVProcessorFrameParameters inputImageRegistrationGyroHomographyConfidence]
+ -[LLVProcessorFrameParameters inputImageRegistrationInliersConfidence]
+ -[LLVProcessorFrameParameters inputImageRegistrationStatus]
+ -[LLVProcessorFrameParameters setInputImageRegistrationGyroHomographyConfidence:]
+ -[LLVProcessorFrameParameters setInputImageRegistrationInliersConfidence:]
+ -[LLVProcessorFrameParameters setInputImageRegistrationStatus:]
+ -[LLVTuningParameters enumerateGroupsWithName:enumerator:]
+ -[MVD bindInputCurrent:historyWarped:dnrZoomMap:fusionZoomMap:denoisedYUV:stateYUV:fusionWeight:]
+ -[MVD fusion_weight]
+ -[MVD hasFusionWeightOutput]
+ -[MVD setFusion_weight:]
+ -[YUV6ChBlenderEncoder encodeToCommandBuffer:denoised_YUV:historyYUV6CH:historyBlendFactor:denoisedBlendFactor:fusionWeightMap:dnrAddbackScale:dnrAddbackOffset:]
+ GCC_except_table10
+ GCC_except_table13
+ GCC_except_table14
+ GCC_except_table15
+ GCC_except_table16
+ GCC_except_table28
+ GCC_except_table29
+ GCC_except_table3
+ GCC_except_table31
+ GCC_except_table32
+ GCC_except_table33
+ _LLVTuningKey_GuidedFilter_EpsilonLUT
+ _LLVTuningKey_HybridWarper_ImageRegistrationGyroHomographyConfidenceThresholdLUT
+ _LLVTuningKey_HybridWarper_ImageRegistrationInliersConfidenceThresholdLUT
+ _LLVTuningKey_HybridWarper_NCCRangeSigma
+ _LLVTuningKey_HybridWarper_NCCSpaceSigma
+ _LLVTuningKey_NetworkInputsModulation_DNRZoomFactorOffsetFirstFrameLUT
+ _LLVTuningKey_NetworkInputsModulation_DNRZoomFactorOffsetLUT
+ _LLVTuningKey_NetworkInputsModulation_DNRZoomFactorOffsetOnTripodLUT
+ _LLVTuningKey_NetworkInputsModulation_DNRZoomFactorScaleFirstFrameLUT
+ _LLVTuningKey_NetworkInputsModulation_DNRZoomFactorScaleLUT
+ _LLVTuningKey_NetworkInputsModulation_DNRZoomFactorScaleOnTripodLUT
+ _LLVTuningKey_NetworkInputsModulation_FusionZoomFactorOffsetLUT
+ _LLVTuningKey_NetworkInputsModulation_FusionZoomFactorOffsetOnTripodLUT
+ _LLVTuningKey_NetworkInputsModulation_FusionZoomFactorScaleLUT
+ _LLVTuningKey_NetworkInputsModulation_FusionZoomFactorScaleOnTripodLUT
+ _LLVTuningKey_NetworkOutputsModulation_DNRAddbackOffsetLUT
+ _LLVTuningKey_NetworkOutputsModulation_DNRAddbackOffsetOnTripodLUT
+ _LLVTuningKey_NetworkOutputsModulation_DNRAddbackScaleLUT
+ _LLVTuningKey_NetworkOutputsModulation_DNRAddbackScaleOnTripodLUT
+ _LLVTuningKey_OpticalFlow_LKTInputLumaGamma
+ _NSKeyValueChangeNewKey
+ _OBJC_CLASS_$_ABDLookupTable
+ _OBJC_CLASS_$_ABDNetworkNoiseAddback
+ _OBJC_CLASS_$_ABDNoiseAddbackState
+ _OBJC_CLASS_$_NSJSONSerialization
+ _OBJC_CLASS_$_NSMapTable
+ _OBJC_CLASS_$_NSNull
+ _OBJC_IVAR_$_ABDLookupTable._keys
+ _OBJC_IVAR_$_ABDLookupTable._size
+ _OBJC_IVAR_$_ABDLookupTable._values
+ _OBJC_IVAR_$_ABDNetworkNoiseAddback._original
+ _OBJC_IVAR_$_ABDNetworkNoiseAddback._userDefaults
+ _OBJC_IVAR_$_ABDNetworkNoiseAddback._working
+ _OBJC_IVAR_$_ABDNoiseAddbackState._bias
+ _OBJC_IVAR_$_ABDNoiseAddbackState._gainFactor
+ _OBJC_IVAR_$_ABDNoiseAddbackState._gainTable
+ _OBJC_IVAR_$_ABDNoiseAddbackState._luxFactor
+ _OBJC_IVAR_$_ABDNoiseAddbackState._luxTable
+ _OBJC_IVAR_$_HybridWarper._bilateralGrids
+ _OBJC_IVAR_$_LLVProcessorBufferManager._fusionWeightMap
+ _OBJC_IVAR_$_LLVProcessorFrameParameters._inputImageRegistrationGyroHomographyConfidence
+ _OBJC_IVAR_$_LLVProcessorFrameParameters._inputImageRegistrationInliersConfidence
+ _OBJC_IVAR_$_LLVProcessorFrameParameters._inputImageRegistrationStatus
+ _OBJC_IVAR_$_MVD._fusion_weight
+ _OBJC_METACLASS_$_ABDLookupTable
+ _OBJC_METACLASS_$_ABDNetworkNoiseAddback
+ _OBJC_METACLASS_$_ABDNoiseAddbackState
+ __OBJC_$_CLASS_METHODS_ABDNoiseAddbackState
+ __OBJC_$_INSTANCE_METHODS_ABDLookupTable
+ __OBJC_$_INSTANCE_METHODS_ABDNetworkNoiseAddback
+ __OBJC_$_INSTANCE_METHODS_ABDNoiseAddbackState
+ __OBJC_$_INSTANCE_VARIABLES_ABDLookupTable
+ __OBJC_$_INSTANCE_VARIABLES_ABDNetworkNoiseAddback
+ __OBJC_$_INSTANCE_VARIABLES_ABDNoiseAddbackState
+ __OBJC_$_PROP_LIST_ABDLookupTable
+ __OBJC_$_PROP_LIST_ABDNoiseAddbackState
+ __OBJC_CLASS_RO_$_ABDLookupTable
+ __OBJC_CLASS_RO_$_ABDNetworkNoiseAddback
+ __OBJC_CLASS_RO_$_ABDNoiseAddbackState
+ __OBJC_METACLASS_RO_$_ABDLookupTable
+ __OBJC_METACLASS_RO_$_ABDNetworkNoiseAddback
+ __OBJC_METACLASS_RO_$_ABDNoiseAddbackState
+ __ZdaPvSt19__type_descriptor_t
+ __ZnamSt19__type_descriptor_t
+ ___102-[HybridWarper initWithCommandQueue:textureCache:band0Size:band1Size:opticalFlowSize:blendingMapSize:]_block_invoke
+ ___223-[HybridWarper encodeToCommandBuffer:tuningGroup:homography:currentY_mipmap:historyY_mipmap:history_YUV:anstRawMask:opticalFlow:warped_YUV:totalGain:flowThresholdScaler:inputValidRect:isHomographyReliable:isTripodDetected:]_block_invoke
+ ___block_descriptor_88_e8_32s40s48s56s_e40_v32?0"LLVTuningGroup"8"NSString"16Q24ls32l8s40l8s48l8s56l8
+ _objc_getProperty
+ _objc_setProperty_atomic
- -[HybridWarper bilateralGrid]
- -[HybridWarper encodeToCommandBuffer:tuningGroup:homography:currentY_mipmap:historyY_mipmap:history_YUV:anstRawMask:opticalFlow:warped_YUV:totalGain:flowThresholdScaler:inputValidRect:]
- -[HybridWarper setBilateralGrid:]
- -[MVD bindInputCurrent:historyWarped:dnrZoomMap:fusionZoomMap:denoisedYUV:stateYUV:]
- -[YUV6ChBlenderEncoder encodeToCommandBuffer:denoised_YUV:historyYUV6CH:historyBlendFactor:denoisedBlendFactor:]
- -[YUV6ChDownscaleMipmapEncoder .cxx_destruct]
- -[YUV6ChDownscaleMipmapEncoder computePipelineState]
- -[YUV6ChDownscaleMipmapEncoder encodeToCommandBuffer:inputYUV6CH:outputDownscaled:]
- -[YUV6ChDownscaleMipmapEncoder initWithDevice:]
- _OBJC_CLASS_$_YUV6ChDownscaleMipmapEncoder
- _OBJC_IVAR_$_HybridWarper._bilateralGrid
- _OBJC_IVAR_$_LLVProcessorIBP._downscaleMipmapEncoder
- _OBJC_IVAR_$_YUV6ChDownscaleMipmapEncoder._computePipelineState
- _OBJC_IVAR_$_YUV6ChDownscaleMipmapEncoder._device
- _OBJC_IVAR_$_YUV6ChDownscaleMipmapEncoder._logger
- _OBJC_METACLASS_$_YUV6ChDownscaleMipmapEncoder
- __OBJC_$_INSTANCE_METHODS_YUV6ChDownscaleMipmapEncoder
- __OBJC_$_INSTANCE_VARIABLES_YUV6ChDownscaleMipmapEncoder
- __OBJC_$_PROP_LIST_YUV6ChDownscaleMipmapEncoder
- __OBJC_CLASS_RO_$_YUV6ChDownscaleMipmapEncoder
- __OBJC_METACLASS_RO_$_YUV6ChDownscaleMipmapEncoder
- ___185-[HybridWarper encodeToCommandBuffer:tuningGroup:homography:currentY_mipmap:historyY_mipmap:history_YUV:anstRawMask:opticalFlow:warped_YUV:totalGain:flowThresholdScaler:inputValidRect:]_block_invoke
CStrings:
+ "%@fusion_weight_map.%@"
+ "%d_%f"
+ "ABDNet: Expected ABDNet.noiseAddbackFormula to be an array of size 3"
+ "ABDNet: Expected keys to increase, but %5.2f < %5.2f"
+ "ABDNet: Expected single-array lookup table to be of an even size (k0,v0,k1,v1,...)"
+ "ABDNet: Key %.2f (above maximum %.2f) -> Value %.2f (using maximum)"
+ "ABDNet: Key %.2f (below minimum %.2f) -> Value %.2f (using minimum)"
+ "ABDNet: Key %.2f (between %.2f and %.2f) -> Value %.2f (between %.2f and %.2f)"
+ "ABDNet_noiseAddbackFormula"
+ "ABDNet_noiseAddback_LUT_gain"
+ "ABDNet_noiseAddback_LUT_lux"
+ "Bilateral grid setup completed for %@/%@/quadra=%d with config: space_sigma=%d, range_sigma=%f"
+ "DNRAddbackOffsetLUT"
+ "DNRAddbackOffsetOnTripodLUT"
+ "DNRAddbackScaleLUT"
+ "DNRAddbackScaleOnTripodLUT"
+ "DNRZoomFactorOffsetOnTripodLUT"
+ "DNRZoomFactorScaleOnTripodLUT"
+ "Dumped fusion weight map to: %@"
+ "Failed to create fusion weight map buffer"
+ "Failed to dump fusion weight map buffer"
+ "Frame %u: isHomographyReliable=%{BOOL}d isTripodDetected=%{BOOL}d (inputImageRegistrationStatus=%d, inputImageRegistrationInliersConfidence=%.4f vs %.4f, inputImageRegistrationGyroHomographyConfidence=%.4f vs %.4f)"
+ "FusionZoomFactorOffsetOnTripodLUT"
+ "FusionZoomFactorScaleOnTripodLUT"
+ "ImageRegistrationGyroHomographyConfidenceThresholdLUT"
+ "ImageRegistrationInliersConfidenceThresholdLUT"
+ "LLVProcessor-CopyRawOpticalFlowToGuidedFilterOutput"
+ "NCCRangeSigma"
+ "NCCSpaceSigma"
+ "Reusing existing bilateral grid for %@/%@/quadra=%d with config: space_sigma=%d, range_sigma=%f"
+ "bias"
+ "lux_LUT"
+ "lux_coeff"
+ "state_weight_band0"
+ "tgain_LUT"
+ "tgain_coeff"
+ "v32@?0@\"LLVTuningGroup\"8@\"NSString\"16Q24"
+ "y"
+ "\x81"
- "DEBUG: Bilateral grid setup completed with config: space_sigma=%d, range_sigma=%f"
- "Failed to create Metal function 'YUV6CH_to_Y_Remosaic'"
- "Failed to initialize YUV6ChDownscaleMipmapEncoder"
- "YUV6CH_to_Y_Remosaic"
- "a"
```
