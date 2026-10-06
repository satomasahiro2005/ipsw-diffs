## PhotosGenerativeServices

> `/System/Library/PrivateFrameworks/PhotosGenerativeServices.framework/PhotosGenerativeServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9f528` | `0xad134` | **`+0xdc0c`** |
| `__TEXT.__cstring` | `0x65a4` | `0x72e4` | **`+0xd40`** |
| `__TEXT.__eh_frame` | `0x5688` | `0x6058` | **`+0x9d0`** |
| `__AUTH_CONST.__objc_const` | `0x3078` | `0x37f0` | **`+0x778`** |
| `__AUTH.__objc_data` | `0x658` | `0xd38` | **`+0x6e0`** |
| `__TEXT.__const` | `0x5ec8` | `0x63e0` | **`+0x518`** |
| `__TEXT.__unwind_info` | `0x2918` | `0x2d90` | **`+0x478`** |
| `__TEXT.__constg_swiftt` | `0x1adc` | `0x1e7c` | **`+0x3a0`** |
| `__AUTH.__data` | `0x6c0` | `0xa50` | **`+0x390`** |
| `__TEXT.__objc_methlist` | `0x1224` | `0x15ac` | **`+0x388`** |
| `__DATA.__bss` | `0x7c00` | `0x7900` | **`-0x300`** |
| `__TEXT.__swift5_fieldmd` | `0x1e48` | `0x211c` | **`+0x2d4`** |
| `__TEXT.__swift5_reflstr` | `0x13d7` | `0x1667` | **`+0x290`** |
| `__TEXT.__swift5_typeref` | `0x1bde` | `0x1dbc` | **`+0x1de`** |
| `__AUTH_CONST.__auth_got` | `0x1158` | `0x12f0` | **`+0x198`** |
| `__TEXT.__swift5_capture` | `0x6e0` | `0x550` | **`-0x190`** |
| `__DATA.__data` | `0x1a08` | `0x1b88` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0x506` | `0x406` | **`-0x100`** |
| `__DATA_CONST.__objc_classlist` | `0x100` | `0x168` | **`+0x68`** |
| `__TEXT.__swift_as_cont` | `0x2ec` | `0x354` | **`+0x68`** |
| `__TEXT.__swift5_assocty` | `0x390` | `0x330` | **`-0x60`** |
| `__TEXT.__swift5_types` | `0x248` | `0x298` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xff8` | `0x1040` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x51c0` | `0x5180` | **`-0x40`** |
| `__TEXT.__swift_as_entry` | `0x130` | `0x164` | **`+0x34`** |
| `__TEXT.__swift_as_ret` | `0x134` | `0x168` | **`+0x34`** |
| `__TEXT.__swift5_proto` | `0x3ec` | `0x3d4` | **`-0x18`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

+  - /System/Library/Frameworks/CoreText.framework/CoreText

-  Functions: 4437
-  Symbols:   1407
-  CStrings:  504
+  Functions: 4838
+  Symbols:   1574
+  CStrings:  568
Symbols:
+ _CGBitmapContextCreate
+ _CGBitmapContextCreateImage
+ _CGColorCreateGenericRGB
+ _CGContextBeginPath
+ _CGContextFillEllipseInRect
+ _CGContextFillRect
+ _CGContextRestoreGState
+ _CGContextSaveGState
+ _CGContextScaleCTM
+ _CGContextSetFillColorWithColor
+ _CGContextSetLineWidth
+ _CGContextSetStrokeColorWithColor
+ _CGContextSetTextMatrix
+ _CGContextStrokePath
+ _CGContextStrokeRect
+ _CGContextTranslateCTM
+ _CGImageGetHeight
+ _CGImageGetWidth
+ _CTFontCreateWithName
+ _CTFontGetAscent
+ _CTLineCreateWithAttributedString
+ _CTLineDraw
+ _CTLineGetBoundsWithOptions
+ _NUIsAppleInternal
+ _NUPixelSizeFromCGSize
+ _NUScaleMultiply
+ _NUScaleToDouble
+ _OBJC_CLASS_$_NSAttributedString
+ _OBJC_CLASS_$_NSLock
+ _OBJC_CLASS_$_NSObject
+ _OBJC_CLASS_$_NSUnitAngle
+ _OBJC_CLASS_$_NUCoreImageComputePipelineProcessor
+ _OBJC_CLASS_$_NUFitScalePolicy
+ _OBJC_CLASS_$_NUMediaGeometryDescriptor
+ _OBJC_CLASS_$_NUPixelFormat
+ _OBJC_CLASS_$_NUVectorDescriptor
+ _OBJC_CLASS_$_PGSDiagnostics
+ _OBJC_CLASS_$__TtC24PhotosGenerativeServices17TileCropProcessor
+ _OBJC_CLASS_$__TtC24PhotosGenerativeServices20InpaintMaskProcessor
+ _OBJC_CLASS_$__TtC24PhotosGenerativeServices20OutfillMaskProcessor
+ _OBJC_CLASS_$__TtC24PhotosGenerativeServices21OutfillUVMapProcessor
+ _OBJC_CLASS_$__TtC24PhotosGenerativeServices22DivideGainMapProcessor
+ _OBJC_CLASS_$__TtC24PhotosGenerativeServices22TileCompositeProcessor
+ _OBJC_CLASS_$__TtC24PhotosGenerativeServices24MultiplyGainMapProcessor
+ _OBJC_CLASS_$__TtC24PhotosGenerativeServices27ReframeUVMapRenderProcessor
+ _OBJC_CLASS_$__TtC24PhotosGenerativeServices29ReframeGainMapSwitchProcessor
+ _OBJC_CLASS_$__TtC24PhotosGenerativeServices33ReframeHomographyComputeProcessor
+ _OBJC_METACLASS_$_NUCoreImageComputePipelineProcessor
+ _OBJC_METACLASS_$_PGSDiagnostics
+ _OBJC_METACLASS_$__TtC24PhotosGenerativeServices17TileCropProcessor
+ _OBJC_METACLASS_$__TtC24PhotosGenerativeServices20InpaintMaskProcessor
+ _OBJC_METACLASS_$__TtC24PhotosGenerativeServices20OutfillMaskProcessor
+ _OBJC_METACLASS_$__TtC24PhotosGenerativeServices21OutfillUVMapProcessor
+ _OBJC_METACLASS_$__TtC24PhotosGenerativeServices22DivideGainMapProcessor
+ _OBJC_METACLASS_$__TtC24PhotosGenerativeServices22TileCompositeProcessor
+ _OBJC_METACLASS_$__TtC24PhotosGenerativeServices24MultiplyGainMapProcessor
+ _OBJC_METACLASS_$__TtC24PhotosGenerativeServices27ReframeUVMapRenderProcessor
+ _OBJC_METACLASS_$__TtC24PhotosGenerativeServices29ReframeGainMapSwitchProcessor
+ _OBJC_METACLASS_$__TtC24PhotosGenerativeServices33ReframeHomographyComputeProcessor
+ _OUTLINED_FUNCTION_123
+ _OUTLINED_FUNCTION_124
+ _OUTLINED_FUNCTION_125
+ _OUTLINED_FUNCTION_126
+ _OUTLINED_FUNCTION_127
+ _OUTLINED_FUNCTION_128
+ _OUTLINED_FUNCTION_129
+ _OUTLINED_FUNCTION_130
+ _OUTLINED_FUNCTION_131
+ _OUTLINED_FUNCTION_132
+ _OUTLINED_FUNCTION_133
+ _OUTLINED_FUNCTION_134
+ _OUTLINED_FUNCTION_135
+ _OUTLINED_FUNCTION_136
+ _OUTLINED_FUNCTION_137
+ _OUTLINED_FUNCTION_138
+ _OUTLINED_FUNCTION_139
+ _OUTLINED_FUNCTION_140
+ _OUTLINED_FUNCTION_141
+ _OUTLINED_FUNCTION_142
+ _OUTLINED_FUNCTION_143
+ _OUTLINED_FUNCTION_144
+ _OUTLINED_FUNCTION_145
+ _OUTLINED_FUNCTION_146
+ _OUTLINED_FUNCTION_147
+ _OUTLINED_FUNCTION_148
+ __CLASS_METHODS_PGSDiagnostics
+ __DATA_PGSDiagnostics
+ __DATA__TtC24PhotosGenerativeServices17TileCropProcessor
+ __DATA__TtC24PhotosGenerativeServices20InpaintMaskProcessor
+ __DATA__TtC24PhotosGenerativeServices20OutfillMaskProcessor
+ __DATA__TtC24PhotosGenerativeServices21OutfillUVMapProcessor
+ __DATA__TtC24PhotosGenerativeServices22DivideGainMapProcessor
+ __DATA__TtC24PhotosGenerativeServices22InpaintGainMapPipeline
+ __DATA__TtC24PhotosGenerativeServices22OutfillGainMapPipeline
+ __DATA__TtC24PhotosGenerativeServices22ReframeGainMapPipeline
+ __DATA__TtC24PhotosGenerativeServices22TileCompositeProcessor
+ __DATA__TtC24PhotosGenerativeServices24MultiplyGainMapProcessor
+ __DATA__TtC24PhotosGenerativeServices27ReframeUVMapRenderProcessor
+ __DATA__TtC24PhotosGenerativeServices29ReframeGainMapSwitchProcessor
+ __DATA__TtC24PhotosGenerativeServices33ReframeHomographyComputeProcessor
+ __INSTANCE_METHODS_PGSDiagnostics
+ __INSTANCE_METHODS__TtC24PhotosGenerativeServices17TileCropProcessor
+ __INSTANCE_METHODS__TtC24PhotosGenerativeServices20InpaintMaskProcessor
+ __INSTANCE_METHODS__TtC24PhotosGenerativeServices20OutfillMaskProcessor
+ __INSTANCE_METHODS__TtC24PhotosGenerativeServices21OutfillUVMapProcessor
+ __INSTANCE_METHODS__TtC24PhotosGenerativeServices22DivideGainMapProcessor
+ __INSTANCE_METHODS__TtC24PhotosGenerativeServices22InpaintGainMapPipeline
+ __INSTANCE_METHODS__TtC24PhotosGenerativeServices22OutfillGainMapPipeline
+ __INSTANCE_METHODS__TtC24PhotosGenerativeServices22ReframeGainMapPipeline
+ __INSTANCE_METHODS__TtC24PhotosGenerativeServices22TileCompositeProcessor
+ __INSTANCE_METHODS__TtC24PhotosGenerativeServices24MultiplyGainMapProcessor
+ __INSTANCE_METHODS__TtC24PhotosGenerativeServices27ReframeUVMapRenderProcessor
+ __INSTANCE_METHODS__TtC24PhotosGenerativeServices29ReframeGainMapSwitchProcessor
+ __INSTANCE_METHODS__TtC24PhotosGenerativeServices33ReframeHomographyComputeProcessor
+ __IVARS__TtC24PhotosGenerativeServices22InpaintGainMapPipeline
+ __IVARS__TtC24PhotosGenerativeServices22OutfillGainMapPipeline
+ __IVARS__TtC24PhotosGenerativeServices22ReframeGainMapPipeline
+ __METACLASS_DATA_PGSDiagnostics
+ __METACLASS_DATA__TtC24PhotosGenerativeServices17TileCropProcessor
+ __METACLASS_DATA__TtC24PhotosGenerativeServices20InpaintMaskProcessor
+ __METACLASS_DATA__TtC24PhotosGenerativeServices20OutfillMaskProcessor
+ __METACLASS_DATA__TtC24PhotosGenerativeServices21OutfillUVMapProcessor
+ __METACLASS_DATA__TtC24PhotosGenerativeServices22DivideGainMapProcessor
+ __METACLASS_DATA__TtC24PhotosGenerativeServices22InpaintGainMapPipeline
+ __METACLASS_DATA__TtC24PhotosGenerativeServices22OutfillGainMapPipeline
+ __METACLASS_DATA__TtC24PhotosGenerativeServices22ReframeGainMapPipeline
+ __METACLASS_DATA__TtC24PhotosGenerativeServices22TileCompositeProcessor
+ __METACLASS_DATA__TtC24PhotosGenerativeServices24MultiplyGainMapProcessor
+ __METACLASS_DATA__TtC24PhotosGenerativeServices27ReframeUVMapRenderProcessor
+ __METACLASS_DATA__TtC24PhotosGenerativeServices29ReframeGainMapSwitchProcessor
+ __METACLASS_DATA__TtC24PhotosGenerativeServices33ReframeHomographyComputeProcessor
+ __PROPERTIES__TtC24PhotosGenerativeServices17TileCropProcessor
+ __PROPERTIES__TtC24PhotosGenerativeServices20InpaintMaskProcessor
+ __PROPERTIES__TtC24PhotosGenerativeServices20OutfillMaskProcessor
+ __PROPERTIES__TtC24PhotosGenerativeServices21OutfillUVMapProcessor
+ __PROPERTIES__TtC24PhotosGenerativeServices22DivideGainMapProcessor
+ __PROPERTIES__TtC24PhotosGenerativeServices22InpaintGainMapPipeline
+ __PROPERTIES__TtC24PhotosGenerativeServices22OutfillGainMapPipeline
+ __PROPERTIES__TtC24PhotosGenerativeServices22ReframeGainMapPipeline
+ __PROPERTIES__TtC24PhotosGenerativeServices22TileCompositeProcessor
+ __PROPERTIES__TtC24PhotosGenerativeServices24MultiplyGainMapProcessor
+ __PROPERTIES__TtC24PhotosGenerativeServices27ReframeUVMapRenderProcessor
+ __PROPERTIES__TtC24PhotosGenerativeServices29ReframeGainMapSwitchProcessor
+ __PROPERTIES__TtC24PhotosGenerativeServices33ReframeHomographyComputeProcessor
+ __PROTOCOLS__TtC24PhotosGenerativeServices22InpaintGainMapPipeline
+ __PROTOCOLS__TtC24PhotosGenerativeServices22OutfillGainMapPipeline
+ __PROTOCOLS__TtC24PhotosGenerativeServices22ReframeGainMapPipeline
+ ___CGBitmapContextCreate
+ ___swift__destructor.21Tm
+ ___swift_memcpy128_8
+ ___swift_memcpy5_4
+ _associated conformance 24PhotosGenerativeServices15SensitivityZoneOSHAASQ
+ _associated conformance 24PhotosGenerativeServices15SensitivityZoneOSLAASQ
+ _associated conformance So10CGImageRefa14CoreFoundation9_CFObjectSCSH
+ _associated conformance So10CGImageRefaSHSCSQ
+ _associated conformance So21NSAttributedStringKeyaSHSCSQ
+ _associated conformance So21NSAttributedStringKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So21NSAttributedStringKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _kCIInputBackgroundImageKey
+ _kCIInputMaskImageKey
+ _kCTFontAttributeName
+ _kCTForegroundColorAttributeName
+ _kSCMLImageSanitizationSignalIVSNSFWExplicit
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _symbolic SDy_____SfG 24PhotosGenerativeServices15SensitivityZoneO
+ _symbolic Say_____G 24PhotosGenerativeServices12DetectedFaceV
+ _symbolic Say_____G So7CGPointV
+ _symbolic Say_____G5rects______5colort So6CGRectV So10CGColorRefa
+ _symbolic ScTyyt_____GSg s5NeverO
+ _symbolic So35NUCoreImageComputePipelineProcessorC
+ _symbolic So8NSObjectC
+ _symbolic So8NSObjectCIego_
+ _symbolic So8NSObjectCSgIego_
+ _symbolic _____ 10Foundation3URLV
+ _symbolic _____ 24PhotosGenerativeServices12DetectedFaceV
+ _symbolic _____ 24PhotosGenerativeServices14PGSDiagnosticsC
+ _symbolic _____ 24PhotosGenerativeServices15SensitivityZoneO
+ _symbolic _____ 24PhotosGenerativeServices16Depth2UVPipelineV14HomographyDataV
+ _symbolic _____ 24PhotosGenerativeServices17GuardrailDetectorC11WarmUpState33_6D087DCD8B61C7C5CB409A73C07FAD99LLV
+ _symbolic _____ 24PhotosGenerativeServices17GuardrailDetectorC15PreviewSnapshotV
+ _symbolic _____ 24PhotosGenerativeServices17GuardrailDetectorC21runOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in4face8depthmapySo6CGRectV_AA12DetectedFaceVSo10MTLTexture_ptF12QueueElementL_V
+ _symbolic _____ 24PhotosGenerativeServices17GuardrailDetectorC25runBodyOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in15maskBaseAddress0Q11BytesPerRow0Q5Width0Q6Height10instanceId8depthmapySo6CGRectV_SvS3is6UInt16VSo10MTLTexture_ptF12QueueElementL_V
+ _symbolic _____ 24PhotosGenerativeServices17TileCropProcessorC
+ _symbolic _____ 24PhotosGenerativeServices20InpaintMaskProcessorC
+ _symbolic _____ 24PhotosGenerativeServices20OutfillMaskProcessorC
+ _symbolic _____ 24PhotosGenerativeServices21OutfillUVMapProcessorC
+ _symbolic _____ 24PhotosGenerativeServices22DivideGainMapProcessorC
+ _symbolic _____ 24PhotosGenerativeServices22InpaintGainMapPipelineC
+ _symbolic _____ 24PhotosGenerativeServices22OutfillGainMapPipelineC
+ _symbolic _____ 24PhotosGenerativeServices22ReframeGainMapPipelineC
+ _symbolic _____ 24PhotosGenerativeServices22SensitivityScoreResultV
+ _symbolic _____ 24PhotosGenerativeServices22TileCompositeProcessorC
+ _symbolic _____ 24PhotosGenerativeServices24MultiplyGainMapProcessorC
+ _symbolic _____ 24PhotosGenerativeServices25SensitivityZoneThresholdsV
+ _symbolic _____ 24PhotosGenerativeServices27ReframeUVMapRenderProcessorC
+ _symbolic _____ 24PhotosGenerativeServices29ReframeGainMapSwitchProcessorC
+ _symbolic _____ 24PhotosGenerativeServices33ReframeHomographyComputeProcessorC
+ _symbolic _____ So10CGImageRefa
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ So21NSAttributedStringKeya
+ _symbolic _____ s6UInt32V
+ _symbolic _____Sg 6Vision15FaceObservationV11Landmarks2DV
+ _symbolic _____Sg 6Vision23RecognizeAnimalsRequestV8RevisionO
+ _symbolic _____Sg 6Vision26DetectFaceLandmarksRequestV8RevisionO
+ _symbolic _____SgIeAgHr_ So10CGImageRefa
+ _symbolic _____XDXMT 24PhotosGenerativeServices17GuardrailDetectorC
+ _symbolic ___________pIghHTrzr_ 24PhotosGenerativeServices16Depth2UVPipelineV14HomographyDataV s5ErrorP
+ _symbolic ______pIego_ s5ErrorP
+ _symbolic _____ySS______tG s23_ContiguousArrayStorageC So10CGColorRefa
+ _symbolic _____ySay_____G5rects______5colortG s23_ContiguousArrayStorageC So6CGRectV So10CGColorRefa
+ _symbolic _____ySo11NSUnitAngleCG 10Foundation11MeasurementV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 24PhotosGenerativeServices12DetectedFaceV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 24PhotosGenerativeServices17GuardrailDetectorC21runOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in4face8depthmapySo6CGRectV_AC12DetectedFaceVSo10MTLTexture_ptF12QueueElementL_V
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 24PhotosGenerativeServices17GuardrailDetectorC25runBodyOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in15maskBaseAddress0T11BytesPerRow0T5Width0T6Height10instanceId8depthmapySo6CGRectV_SvS3is6UInt16VSo10MTLTexture_ptF12QueueElementL_V
+ _symbolic _____y_____So7CIImageCG s17_NativeDictionaryV 24PhotosGenerativeServices12NetworkUtilsC10NamedImageV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 24PhotosGenerativeServices17GuardrailDetectorC11WarmUpState33_6D087DCD8B61C7C5CB409A73C07FAD99LLV So16os_unfair_lock_sV
+ _symbolic _____y___________pGSg s6ResultOsRi_zRi0_zrlE 24PhotosGenerativeServices16Depth2UVPipelineV14HomographyDataV s5ErrorP
+ _symbolic _____y___________tG s23_ContiguousArrayStorageC 24PhotosGenerativeServices21GuardrailDetectorTypeO So10CGColorRefa
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC So21NSAttributedStringKeya
+ _symbolic _____yxq_GSgz_____________pAER_r0_lXX s6ResultOsRi_zRi0_zrlE 24PhotosGenerativeServices16Depth2UVPipelineV14HomographyDataV s5ErrorP
+ _symbolic q_xRi_zRi0_zRi__Ri0__r0_ly______p_____IseghHrzr_Sg s5ErrorP 24PhotosGenerativeServices16Depth2UVPipelineV14HomographyDataV
+ _symbolic xq_IeghHrzr_Sgz_____________pACR_r0_lXX 24PhotosGenerativeServices16Depth2UVPipelineV14HomographyDataV s5ErrorP
+ _type_layout_string 24PhotosGenerativeServices12DetectedFaceV
+ _type_layout_string 24PhotosGenerativeServices15ReframePipelineV
+ _type_layout_string 24PhotosGenerativeServices16Depth2UVPipelineV14HomographyDataV
+ _type_layout_string 24PhotosGenerativeServices17GuardrailDetectorC11WarmUpState33_6D087DCD8B61C7C5CB409A73C07FAD99LLV
+ _type_layout_string 24PhotosGenerativeServices17GuardrailDetectorC21runOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in4face8depthmapySo6CGRectV_AA12DetectedFaceVSo10MTLTexture_ptF12QueueElementL_V
+ _type_layout_string 24PhotosGenerativeServices22SensitivityScoreResultV
+ _type_layout_string 24PhotosGenerativeServices25SensitivityZoneThresholdsV
+ _type_layout_string So15CIContextOptiona
- _ANSTObjectCategoryCatBody
- _ANSTObjectCategoryCatHead
- _ANSTObjectCategoryDogBody
- _ANSTObjectCategoryDogHead
- _ANSTObjectCategoryFace
- _NSSelectorFromString
- _NUFilterPipelineProcessorOptionInputChannels
- _NUFilterPipelineProcessorOptionMainInput
- _OBJC_CLASS_$_ANSTFace
- _OBJC_CLASS_$_ANSTISPAlgorithm
- _OBJC_CLASS_$_ANSTISPAlgorithmConfiguration
- _OBJC_CLASS_$_ANSTObject
- _OBJC_CLASS_$_ANSTPointEstimate
- _OBJC_CLASS_$_NSArray
- _OBJC_CLASS_$_NUChannelMatching
- _OBJC_CLASS_$_VNGeneratePersonInstanceMaskRequest
- _OBJC_CLASS_$_VNImageRequestHandler
- _OBJC_CLASS_$_VNInstanceMaskObservation
- _OBJC_CLASS_$_VNRequest
- _OBJC_METACLASS_$__TtC24PhotosGenerativeServicesP33_3517498391FD783FC5D8E87B9D0EC49A15OffsetProcessor
- __DATA__TtC24PhotosGenerativeServicesP33_3517498391FD783FC5D8E87B9D0EC49A15OffsetProcessor
- __INSTANCE_METHODS__TtC24PhotosGenerativeServicesP33_3517498391FD783FC5D8E87B9D0EC49A15OffsetProcessor
- __METACLASS_DATA__TtC24PhotosGenerativeServicesP33_3517498391FD783FC5D8E87B9D0EC49A15OffsetProcessor
- __PROPERTIES__TtC24PhotosGenerativeServicesP33_3517498391FD783FC5D8E87B9D0EC49A15OffsetProcessor
- ___swift__destructorTm
- ___swift_memcpy89_8
- ___swift_memcpy96_8
- _associated conformance 24PhotosGenerativeServices30GuardrailBodySegmentationModelOSHAASQ
- _associated conformance 24PhotosGenerativeServices30GuardrailBodySegmentationModelOs12CaseIterableAA8AllCasessADP_Sl
- _associated conformance 24PhotosGenerativeServices30GuardrailBodySegmentationModelOs12IdentifiableAA2IDsADP_SH
- _associated conformance So13VNImageOptionaSHSCSQ
- _associated conformance So13VNImageOptionas20_SwiftNewtypeWrapperSCSY
- _associated conformance So13VNImageOptionas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
- _associated conformance So31NUFilterPipelineProcessorOptionaSHSCSQ
- _associated conformance So31NUFilterPipelineProcessorOptionas20_SwiftNewtypeWrapperSCSY
- _associated conformance So31NUFilterPipelineProcessorOptionas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
- _objc_retain_x11
- _swift_dynamicCastObjCClassUnconditional
- _swift_isUniquelyReferenced_nonNull_bridgeObject
- _swift_release_x9
- _symbolic $ss12IdentifiableP
- _symbolic SaySo10ANSTObjectCG
- _symbolic SaySo8ANSTFaceCG
- _symbolic SaySo9NUChannelCG
- _symbolic Say_____G 24PhotosGenerativeServices30GuardrailBodySegmentationModelO
- _symbolic SbIegd_
- _symbolic _____ 24PhotosGenerativeServices15OffsetProcessor33_3517498391FD783FC5D8E87B9D0EC49ALLC
- _symbolic _____ 24PhotosGenerativeServices17GuardrailDetectorC21runOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in4face8depthmapySo6CGRectV_So8ANSTFaceCSo10MTLTexture_ptF12QueueElementL_V
- _symbolic _____ 24PhotosGenerativeServices17GuardrailDetectorC25runBodyOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in15maskBaseAddress0Q11BytesPerRow0Q5Width0Q6Height7is16Bit10instanceId8depthmapySo6CGRectV_SvS3iSbs6UInt16VSo10MTLTexture_ptF12QueueElementL_V
- _symbolic _____ 24PhotosGenerativeServices30GuardrailBodySegmentationModelO
- _symbolic _____ So13VNImageOptiona
- _symbolic _____ So31NUFilterPipelineProcessorOptiona
- _symbolic _____Iegd_ s5Int32V
- _symbolic _____Iegd_ s5UInt8V
- _symbolic _____Iegr_ s5Int32V
- _symbolic _____Iegr_ s5UInt8V
- _symbolic _____Sg 24PhotosGenerativeServices30GuardrailBodySegmentationModelO
- _symbolic _____y_____4minX_AB4maxXAB0A1YAB0B1YtG s23_ContiguousArrayStorageC 12CoreGraphics7CGFloatV
- _symbolic _____y_____G s16IndexingIteratorV 10Foundation8IndexSetV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 24PhotosGenerativeServices17GuardrailDetectorC21runOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in4face8depthmapySo6CGRectV_So8ANSTFaceCSo10MTLTexture_ptF12QueueElementL_V
- _symbolic _____y_____G s23_ContiguousArrayStorageC 24PhotosGenerativeServices17GuardrailDetectorC25runBodyOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in15maskBaseAddress0T11BytesPerRow0T5Width0T6Height7is16Bit10instanceId8depthmapySo6CGRectV_SvS3iSbs6UInt16VSo10MTLTexture_ptF12QueueElementL_V
- _symbolic _____y______yptG s23_ContiguousArrayStorageC So31NUFilterPipelineProcessorOptiona
- _type_layout_string 24PhotosGenerativeServices17GuardrailDetectorC21runOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in4face8depthmapySo6CGRectV_So8ANSTFaceCSo10MTLTexture_ptF12QueueElementL_V
- _type_layout_string So31NUFilterPipelineProcessorOptiona
CStrings:
+ "%sRect[%s] severity=%s relaxFactor=%s"
+ ":<spatialRefinement"
+ "ADMBlendOutputImage"
+ "ADMRawExclusionMask"
+ "CIBlendWithAlphaMask"
+ "Failed to compute gain map"
+ "Failed to compute light map"
+ "Failed to generate identity UV map"
+ "Failed to generate outfill UV map"
+ "Failed to generate outfill mask"
+ "Failed to generate reframe UV map"
+ "GANBlendBackground"
+ "GANBlendForeground"
+ "GANRawExclusionMask"
+ "GANRawInputImage"
+ "GANRefinementOutput"
+ "GuardrailDetector: Unsupported FSINC mask format: %u"
+ "GuardrailDetector: detectBodyOcclusions requires 16Gray mask format"
+ "Missing gain map with UV input"
+ "Missing gain map without UV input"
+ "Missing homography data"
+ "Missing outfill geometry"
+ "Missing spatial refinement input"
+ "Missing target geometry"
+ "Missing target input"
+ "PGSWriteBlendImagesToDisk"
+ "Seamless compositing failed"
+ "SpatialPhotoReframeEnableDebugMode"
+ "Vision detection failed: %@"
+ "Vision timing - Run Detection: %ldms"
+ "Vision timing - WarmUp Vision: %ldms"
+ "[WARNING] ❌ Error: Homography matrix must have 9 elements"
+ "applyImagePipeline"
+ "applyImagePipeline:<primary"
+ "applyImagePipeline:<tile"
+ "applyImagePipeline:>primary"
+ "com.apple.photos.spatialreframe.depth"
+ "com.apple.photos.spatialreframe.extrinsics"
+ "com.apple.photos.spatialreframe.intrinsics"
+ "com.apple.photos.spatialreframe.originalIntrinsics"
+ "dividePipeline:<gainMap"
+ "dividePipeline:<gainMapGeometry"
+ "dividePipeline:<image"
+ "dividePipeline:<imageGeometry"
+ "dividePipeline:<lightMap"
+ "dividePipeline:<mixFactor"
+ "dividePipeline:<preserveColor"
+ "dividePipeline:>gainMap"
+ "gainMapPipeline:<applyGlobalRecovery"
+ "gainMapPipeline:<gainMap"
+ "gainMapPipeline:<mask"
+ "gainMapPipeline:<primary"
+ "gainMapPipeline:<target"
+ "gainMapPipeline:<uvMap"
+ "gainMapPipeline:>gainMap"
+ "gainMapWithUVPipeline"
+ "gainMapWithUVPipeline:<applyGlobalRecovery"
+ "gainMapWithUVPipeline:<gainMap"
+ "gainMapWithUVPipeline:<primary"
+ "gainMapWithUVPipeline:<target"
+ "gainMapWithUVPipeline:<uvMap"
+ "gainMapWithUVPipeline:>gainMap"
+ "gainMapWithoutUV"
+ "gainMapWithoutUVPipeline"
+ "gainMapWithoutUVPipeline:<applyGlobalRecovery"
+ "gainMapWithoutUVPipeline:<gainMap"
+ "gainMapWithoutUVPipeline:<primary"
+ "gainMapWithoutUVPipeline:<target"
+ "gainMapWithoutUVPipeline:>gainMap"
+ "homographyPipeline"
+ "homographyPipeline:<spatialRefinement"
+ "homographyPipeline:>homography"
+ "inpaintGainMapPipeline"
+ "inpaintMaskPipeline"
+ "inpaintMaskPipeline:<exclusionMask"
+ "inpaintMaskPipeline:<mask"
+ "inpaintMaskPipeline:<primary"
+ "inpaintMaskPipeline:>mask"
+ "kernel vec4 applyHomographyUVMap(float3 h0, float3 h1, float3 h2, float2 invSize)\n    __attribute__((outputFormat(kCIFormatRGh))) {\n    vec3 uv = vec3(destCoord() * invSize, 1.0);\n    float u_prime = dot(h0, uv);\n    float v_prime = dot(h1, uv);\n    float w_prime = dot(h2, uv);\n    float inv_w = 1.0 / w_prime;\n    float out_u = clamp(u_prime * inv_w, 0.0, 1.0);\n    float out_v = clamp(v_prime * inv_w, 0.0, 1.0);\n    return vec4(out_u, out_v, 0.0, 1.0);\n}"
+ "kernel vec4 generateOutpaintingUVMap(float2 delta, float2 invInputScaled)\n    __attribute__((outputFormat(kCIFormatRGh))) {\n    vec2 pos = destCoord();\n    float u = clamp((pos.x - delta.x) * invInputScaled.x, 0.0, 1.0);\n    float v = clamp((pos.y - delta.y) * invInputScaled.y, 0.0, 1.0);\n    return vec4(u, v, 0.0, 1.0);\n}"
+ "kernel vec4 identityUVMap(float2 invSize)\n    __attribute__((outputFormat(kCIFormatRGh))) {\n    vec2 uv = destCoord() * invSize;\n    return vec4(uv.x, uv.y, 0.0, 1.0);\n}"
+ "kernel vec4 replaceSubthresholdPixelsWithBlack(__sample pixel) {    vec4 color = unpremultiply(pixel);    return vec4((color.a < 0.9) ? vec3(0.0, 0.0, 0.0) : color.rgb, 1.0);}"
+ "multiplyPipeline"
+ "multiplyPipeline:<gainMap"
+ "multiplyPipeline:<image"
+ "multiplyPipeline:<mixFactor"
+ "multiplyPipeline:<preserveColor"
+ "multiplyPipeline:>outputImage"
+ "occ d%.2f→%.2f max%.3f"
+ "outfillGainMapPipeline"
+ "outfillMaskPipeline"
+ "outfillMaskPipeline:<outfill"
+ "outfillMaskPipeline:<primary"
+ "outfillMaskPipeline:>mask"
+ "reframeGainMapPipeline"
+ "seamlessBlendingPipeline:<background"
+ "seamlessBlendingPipeline:<input"
+ "seamlessBlendingPipeline:<mask"
+ "spatialRefinement"
+ "styleTransferPipeline:<colorSpace"
+ "switchPipeline:<gainMapWithUV"
+ "switchPipeline:<gainMapWithoutUV"
+ "switchPipeline:<homography"
+ "switchPipeline:>gainMap"
+ "tileCropPipeline"
+ "tileCropPipeline:<generatedTile"
+ "tileCropPipeline:<primary"
+ "tileCropPipeline:>primary"
+ "uvMapPipeline:<homography"
+ "uvMapPipeline:<outfill"
+ "uvMapPipeline:<primary"
+ "uvMapPipeline:<target"
+ "uvMapPipeline:>uvMap"
- "%sRect[%s] x=%s y=%s w=%s h=%s areaRaw=%s areaInFrame=%s outOfFrameRatio=%s"
- "../lightMapPipeline:>outputImage"
- "../styleTransferPipeline:>primary"
- "ANST Cat Body: %s"
- "ANST Cat Head: %s"
- "ANST Dog Body: %s"
- "ANST Dog Head: %s"
- "ANST Human Face: %s"
- "ANST timing - Init ANST: %ldms"
- "ANST timing - Prepare Image Input: %ldms"
- "ANST timing - Run ANST Detection: %ldms"
- "ANST timing - WarmUp ANST: %ldms"
- "ANST warm-up failed in %ldms: %@"
- "ANSTFsinc (10 people)"
- "Missing primary geometry"
- "Missing primary image"
- "Missing reference geometry"
- "Missing reference image"
- "Missing target input for offset computation"
- "PGSDivideGainMapFilter"
- "PGSMultiplyGainMapFilter"
- "PhotosGuardrailBodySegmentationModel"
- "Vision (4 people)"
- "Vision instance mask: output=%ldx%ld instances=%ld"
- "Vision timing - WarmUp Segmentation: %ldms"
- "anst"
- "com.apple.clementine"
- "detectedObjectsForCategory:"
- "gainMapPipeline:<inputImage"
- "gainMapPipeline:<inputLightMap"
- "gainMapPipeline:<inputMixFactor"
- "gainMapPipeline:<inputPreserveColor"
- "inputHDRLightMap"
- "inputPreserveColor"
- "kernel vec4 combineRGBAndAlpha(__sample rgb, __sample alphaGray) {    return vec4(rgb.rgb, alphaGray.r);}"
- "kernel vec4 replaceSubthresholdPixelsWithBlack(__sample pixel) {    return (pixel.a < 0.9) ? vec4(0.0, 0.0, 0.0, 1.0) : pixel;}"
- "lightMapPipeline"
- "lightMapPipeline:<inputGainMap"
- "lightMapPipeline:<inputImage"
- "lightMapPipeline:<inputMixFactor"
- "lightMapPipeline:<inputPreserveColor"
- "lightMapPipeline:>outputImage"
- "offsetOutputGainMap"
- "outputHDRLightMap"
- "seamlessBlendingPipeline:<blendMask"
- "seamlessBlendingPipeline:<inputHDRLightMap"
- "seamlessBlendingPipeline:<outputHDRLightMap"
- "seamlessBlendingPipeline:<target"
- "vision"
```
