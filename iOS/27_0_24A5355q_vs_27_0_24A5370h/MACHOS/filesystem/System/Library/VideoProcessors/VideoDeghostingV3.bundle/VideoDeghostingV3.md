## VideoDeghostingV3

> `/System/Library/VideoProcessors/VideoDeghostingV3.bundle/VideoDeghostingV3`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f3a0` | `0x2f4bc` | **`+0x11c`** |
| `__TEXT.__unwind_info` | `0x830` | `0x838` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3
Functions:
~ -[VEVideoDeghostingRepairV3 collectDetectionResultsForLookAheadBuffer:] : 420 -> 416
~ _ColorsWheelContext_create : 1484 -> 1460
~ _ColorsWheelContext_drawMatrix_f32 : 440 -> 456
~ -[disparityDebugUtils saveF16Texture:AsPPMFile:] : 464 -> 460
~ -[disparityDebugUtils convertRGB10A2ToRGBA8:rbs:ToRGBA:outWidth:outHeight:] : 120 -> 132
~ -[disparityDebugUtils saveF16DisparityBuffer:AsPPMFile:] : 296 -> 288
~ -[disparityDebugUtils computeRobustMinMaxForF16DisparityBuffer:WithDisparityScale:AndPercentile:OutSignalMin:OutSignalMax:] : 560 -> 568
~ -[disparityDebugUtils saveF16DisparityBuffer:AsGrayScalePPMFile:range:] : 564 -> 552
~ -[disparityDebugUtils saveF16Texture:AsGrayScalePPMFile:range:] : 632 -> 620
~ -[disparityDebugUtils saveU16Texture:AsPGMFile:] : 344 -> 348
~ -[disparityDebugUtils saveF16DisparityTexture:AsPPMFile:] : 356 -> 344
~ -[disparityDebugUtils saveRGF16Texture:AsF32BinaryFile0:AsF32BinaryFile1:] : 608 -> 604
~ -[disparityDebugUtils saveRgbaF32PixelBuffer:AsPPMFile:] : 564 -> 560
~ -[disparityDebugUtils saveRGBAF16PixelBuffer:out_width:out_height:AsPPMFile:] : 564 -> 560
~ -[disparityDebugUtils saveF16Texture:AsF32BinaryFile:] : 364 -> 360
~ -[disparityDebugUtils saveNCCOutputFrom:asBinaryFiles:] : 1512 -> 1480
~ -[disparityDebugUtils saveAccumulationFrom:asBinaryFiles:forSize:costLineSize:] : 1060 -> 1048
~ -[disparityDebugUtils saveF32Texture:AsF32BinaryFile:] : 404 -> 400
~ -[disparityDebugUtils saveRGBA16FTexture:AsPPMFile:] : 536 -> 532
~ -[disparityDebugUtils saveRGB10A2Texture:AsPPMFile:] : 520 -> 516
~ -[MitigationHW createTemporalBuffersWithImageDimension:] : 188 -> 208
~ -[MitigationHW dealloc] : 160 -> 176
~ -[MitigationHW combineHWWeights:withGPUWeights:] : 60 -> 68
~ -[MitigationHW spatialTemporalRepairThenFuseInplaceYUVInputBuf:frmIdx:frRef0Buf:frRef1Buf:metaBuf:ref0MetaBuf:ref1MetaBuf:metaBufHW:info:infoTPlusOrMinus1:infoTPlusOrMinus2:usePastAsRef:] : 3980 -> 3984
~ -[GGMController updateConfig:withConfigureDict:] : 884 -> 880
~ _packDetectionResult : 2856 -> 2864
~ _createBBoxArrayWithMeta : 188 -> 200
~ _HomographyToBuffer : 212 -> 188
~ _BoundingBoxToBuffer : 224 -> 228
~ -[RepairWeightsGenerator createTemporalBuffersWithImageDimension:] : 188 -> 208
~ -[RepairWeightsGenerator dealloc] : 212 -> 232
~ ___167-[RepairWeightsGenerator computeBlendingWeightsYUVInputBuf:frRef0Buf:frRef1Buf:hmgrphy0:hmgrphy1:frmIdx:metadataBuf:meta_HW:metaTPlusOrMinus1_HW:metaTPlusOrMinus2_HW:]_block_invoke : 1804 -> 1800
~ -[RepairWeightsGenerator _computeBlendingWeightsYUVInputBuf:frRefTPlusOrMinus1Buf:frRefTPlusOrMinus2Buf:meta:metaTPlusOrMinus1:metaTPlusOrMinus2:meta_HW:metaTPlusOrMinus1_HW:metaTPlusOrMinus2_HW:info:infoTPlusOrMinus1:infoTPlusOrMinus2:config:usePastAsRef:] : 632 -> 628
~ -[RepairWeightsGenerator updateQueuesWithTwoFutureFrames:atBaseIndex:] : 200 -> 192
~ -[RepairWeightsProcessor temporalFilterMetaContainerAtIndex_PA_L:ofQueue:ofQueue_HW:lookaheadBufferLen:] : 1556 -> 1544
~ -[RepairWeightsProcessor _temporalFilterMetaContainerAtIndex:ofQueue:lookaheadBufferLen:] : 2496 -> 2556
~ -[VideoMitigation initWithConfig:metalContext:imageDimensions:tuningParameters:] : 772 -> 776
~ -[VideoMitigation _resetIntermediateVariables] : 88 -> 108
~ -[MaskToRoi convertInternalBBoxesToROI:] : 180 -> 176
~ -[MaskToRoi convertInternalBBoxes:] : 232 -> 228
~ -[MaskToRoi getLSBBoxesUsingGraphTraversalFrom:roi:pixValThreshold:bboxSizeThreshold:scaleFactorInv:validWidth:validHeight:lightSourceBBox:] : 1052 -> 1044
~ -[MaskToRoi convertPackedMaskToRegular:output:] : 452 -> 436
~ -[VideoDeghostingDetectionV3 initWithMetalContext:config:tuningParamDict:imageDimensions:] : 4000 -> 4112
~ -[VideoDeghostingDetectionV3 dealloc] : 388 -> 432
~ -[VideoDeghostingDetectionV3 releaseHWMetadata] : 88 -> 96
~ -[VideoDeghostingDetectionV3 prepareDataForNextFrameWithFrameData:outputFutureOpticalCenter:outputFutureLightSourceMaskTotalArea:doLite:] : 1280 -> 1276
~ -[VideoDeghostingDetectionV3 getFutureRoisFutureOpticalCenter:futureLightSourceMaskTotalArea:currFrameMetaContainer:futureFrameMetaBuf:] : 444 -> 436
~ -[VideoDeghostingDetectionV3 process:metaData:ispTimeStamp:keypoints:lightSourceMask:futureFrames:] : 3760 -> 3768
~ -[VideoDeghostingDetectionV3 warpTrackingRefProbMap:refSpaProbMap:refReflLs:refinedReflLsMap:target:motionCueRef:motionCueRepairedRef:metaBuf:motionCueRefMetaBuf:metaBufArray:commandBuffer:] : 644 -> 636
~ -[VideoDeghostingDetectionV3 _getRefinedLsMapsTarget:refLsMap:refRefinedLsMap:lsMap:refinedLsMap:metaBuf:metaBufArray:doLite:commandBuffer:] : 392 -> 384
~ -[VideoDeghostingDetectionV3 _getProbMapsLiteTarget:refProbMap:refProbMapStash4FutureTracking:refRawRefinedProbMap:refRefinedProbMap:probMap:refinedLsMap:probMapStash4FutureTracking:rawRefinedProbMap:refinedProbMap:probMapRepairRef0:probMapRepairRef1:metaBuf:metaBufArray:commandBuffer:] : 828 -> 816
~ -[VideoDeghostingDetectionV3 getProbMapsTarget:rawProbMap:probMap:rawRefinedProbMap:refinedProbMap:refinedReflLsMap:reflLsMap4TrackingRef:probMapRepairRef0:probMapRepairRef1:metaBuf:metaBufArray:commandBuffer:] : 996 -> 1036
~ -[VideoDeghostingDetectionV3 repairTarget:frRef0:frRef1:trRef0:trRef1:hwSimRef0:hwSimRef1:probMap:refinedProbMap:rawRefinedProbMap:metaBuf:metaRef0Buf:metaRef1Buf:metaBufArray:trOutput:hwSimOutput:commandBuffer:addEndOfDetectionSignPost:] : 1424 -> 1396
~ -[VideoDeghostingDetectionV3 _initDetection:metaData:futureFrames:] : 1140 -> 1132
~ -[VideoDeghostingDetectionV3 extractLightSourceBBoxFromBuffer:BoxCount:] : 160 -> 168
~ _warpPrevMetaBuffer : 412 -> 424
~ _syncWeightsSpatialForSWWeights : 216 -> 232
~ _syncRoiMotions : 192 -> 204
~ -[HWGPUSimBridge getWSpatialUsingGhostMotion_HWGPU:ref0Meta:ref1Meta:metaTPlusOrMinus1_HW:metaTPlusOrMinus2_HW:lowLight:ghostSize:] : 752 -> 744
~ -[HWGPUSimBridge getDistWithGGCoord:GGCount:location:ggIdx:] : 600 -> 624
~ -[HWGPUSimBridge getWSpatialUsingTempAlignQualityLowLight_HWGPUWithGGCoord:GGCount:GGCountRef0:GGCountRef1:ggIndex:input:ref0:ref1:diffMax:] : 1048 -> 1044
~ -[HWGPUSimBridge hwStatisticsFromVT:homography1:BBoxCur:warpedBBox0:warpedMeta1:inputBuf:ref0Buf:ref1Buf:borderPixels:outputStruct:] : 780 -> 756
~ _extractFutureReferenceFrames : 1732 -> 1744
~ _freeLookAheadFrameArray : 204 -> 200
~ -[CalcHomography _scaleHomography:scaleX:scaleY:] : 260 -> 252
~ -[CalcHomography _ispHomographyFromISPInfoFunc:] : 604 -> 588
~ -[CalcHomography cascadeHomographyMatricesArray:] : 304 -> 300
~ -[GGMMetalToolBox initWithMetalContext:] : 636 -> 640
~ -[GGMMetalToolBox updateMetaContainerBuffer:withDetectedROI:isLowLight:opticalCenter:ispBaseOpticalCenter:opticalCenterEstConf:frameDim:lightSourceMaskTotalArea:] : 2084 -> 2072
~ -[GGMMetalToolBox generateMetaContainerArrayBufFromMetaContainerBuf:imageRect:] : 1476 -> 1604
~ -[GGMMetalToolBox encodeBMTransferGrayMultiRefsLowLightToCommandEncoder:ref0:ref1:ref2:ref3:warpedRef0:warpedRef1:warpedRef2:warpedRef3:meta:] : 656 -> 652
~ -[GGMMetalToolBox encodeDilateProbMap:input:output:hardDilationRadius:softDilationRadius:meta:] : 416 -> 412
~ -[GGMMetalToolBox encodeConditionalDilateProbMapYUV:inputYUV:probMap:dilatedProbMap:hardDilationRadius:softDilationRadius:meta:] : 456 -> 452
~ -[CMIVideoDeghostingV3 purgeResources] : 136 -> 128
~ -[RawMetaDataReader ExtractClippingInfoFromRawMetaData:] : 412 -> 408
~ -[RawMetaDataReader readIspRegInfoFromSei:simMatrix:] : 420 -> 416
~ -[RawMetaDataReader readIspOisInfoFromSei:] : 132 -> 156
~ -[RawMetaDataReader readMetaDataInfoFromSimulation:] : 1460 -> 1480
~ +[RawMetaDataReader _getRegistrationInfo:validWidth:validHeight:keypointDictionary:ispInfo:] : 864 -> 856
~ -[PixelMemory initWithCvPixelBuffer:skipClamp:readOnly:] : 740 -> 732
~ -[PixelMemory readYCbCrValueAtX:Y:] : 92 -> 104
~ -[PixelMemory readYCbCrValueAtArrayX:ArrayY:] : 376 -> 388
~ -[PixelMemory readBlurredYValueAtX:Y:] : 232 -> 224
~ _getWSpatialFromOverlap : 588 -> 584
```
