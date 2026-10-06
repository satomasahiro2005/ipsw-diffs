## HDRProcessing

> `/System/Library/PrivateFrameworks/HDRProcessing.framework/HDRProcessing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa6e80` | `0xa74e4` | **`+0x664`** |
| `__AUTH_CONST.__objc_const` | `0x7dc0` | `0x7de0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x560` | `0x568` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x25a4` | `0x25ac` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xb7c` | `0xb80` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-1.512.1.0.0
+1.513.1.0.0

-  Symbols:   2905
+  Symbols:   2907
Symbols:
+ OBJC_IVAR_$_AdaptiveTM._atmEnabled
+ _objc_retain_x26
Functions:
~ -[MSRHDRProcessing dealloc] : 408 -> 424
~ -[MSRHDRProcessing createAdaptationLut] : 124 -> 136
~ -[MSRHDRProcessing getDegammaLutInput:] : 40 -> 36
~ -[MSRHDRProcessing setDegammaBuffer:Buffer:TableSize:LutInput:Type:scalerForSrgbBeyondMax:InputScale:OutputScale:] : 792 -> 808
~ -[MSRHDRProcessing updateDegammaTable:Table:TableSize:Type:Scaler:] : 236 -> 260
~ -[MSRHDRProcessing updateRegammaTable:Table:TableSize:] : 108 -> 140
~ -[MSRHDRProcessing setupMSRPolynomialTableForHDR10:TableLength:] : 100 -> 104
~ -[MSRHDRProcessing updatePolynomialTables:TableSize:] : 108 -> 112
~ -[MSRHDRProcessing setSat2FactorTable:TableSize:DMConfig:LLDoVi:] : 72 -> 80
~ -[MSRHDRProcessing hdr10_getTmLutInput:lutInput:] : 60 -> 56
~ -[MSRHDRProcessing dovi_getTmLutInput:lutInput:] : 48 -> 56
~ -[MSRHDRProcessing hdr10_mixLUTFromTCControl:TCControlConstr:withFactor:] : 212 -> 220
~ -[MSRHDRProcessing hdr10_tm_updateLUT:ScalingFactorBuffer:LumaMixFactorBuffer:] : 180 -> 172
~ -[MSRHDRProcessing hlg_getTmLutInput:lutInput:] : 64 -> 60
~ -[MSRHDRProcessing hlg_mixLUTFromTCControl:TCControlConstr:withFactor:] : 288 -> 292
~ -[MSRHDRProcessing hlg_tm_updateLUT:ScalingFactorBuffer:] : 148 -> 140
~ -[MSRHDRProcessing smpte_st_2094_50_tm_createLUTFromDMConfig:TCControl:TMParam:EdrAdaptationParam:AmbAdaptationParam:] : 356 -> 364
~ -[MSRHDRProcessing smpte_st_2094_50_getTmLutInput:lutInput:] : 64 -> 60
~ -[MSRHDRProcessing smpte_st_2094_50_tm_updateLUT:ScalingFactorBuffer:LumaMixFactorBuffer:] : 252 -> 232
~ -[MSRHDRProcessing smpte_st_2094_50_mixLUTFromTCControl:TCControlConstr:withFactor:] : 324 -> 328
~ -[MSRHDRProcessing sdr_getTmLutInput:lutInput:] : 60 -> 56
~ -[MSRHDRProcessing sdr_mixLUTFromTCControl:TCControlConstr:withFactor:] : 288 -> 292
~ -[MSRHDRProcessing sdr_tm_updateLUT:ScalingFactorBuffer:] : 148 -> 140
~ -[MSRHDRProcessing dovi_mixLUTFromTCControl:TCControlConstr:withFactor:] : 232 -> 216
~ -[MSRHDRProcessing dovi_tm_updateLUT:ScalingFactorBuffer:ScalingFactorBufferSize:Sat2FactorBuffer:Sat2FactorBufferSize:dmConfig:HlgOOTFCombined:] : 588 -> 636
~ -[MSRHDRProcessing decideStageStatus:MSRHDRContext:DMConfig:] : 4064 -> 4060
~ -[MSRHDRProcessing populateMSRColorConfigStageB01_01:Enabled:Prefix:DMConfig:DMData:tcControl:hdrControl:MSRHDRContext:] : 1512 -> 1504
~ -[MSRHDRProcessing populateMSRColorConfigStageB01_02:Enabled:Prefix:DMConfig:DMData:tcControl:hdrControl:MSRHDRContext:] : 3184 -> 3120
~ -[MSRHDRProcessing populateMSRColorConfigStageB01_04:Enabled:Prefix:DMConfig:DMData:tcControl:hdrControl:MSRHDRContext:] : 2564 -> 2504
~ -[MSRHDRProcessing populateMSRColorConfigStageB01_06:Enabled:Prefix:DMConfig:DMData:tcControl:hdrControl:MSRHDRContext:] : 1092 -> 1068
~ -[MSRHDRProcessing populateMSRColorConfigStageB02HDR10:DMConfig:] : 596 -> 604
~ -[MSRHDRProcessing populateMSRColorConfigStageB02HLG:DMConfig:hdrControl:] : 804 -> 808
~ -[MSRHDRProcessing populateMSRColorConfigStageB04_01:Enabled:Prefix:DMConfig:DMData:tcControl:hdrControl:MSRHDRContext:] : 1116 -> 1092
~ -[MSRHDRProcessing populateMSRColorConfigStageB04_03:Enabled:Prefix:DMConfig:DMData:tcControl:hdrControl:MSRHDRContext:] : 3776 -> 3744
~ -[MSRHDRProcessing populateMSRColorConfigStageB04_04:Enabled:Prefix:DMConfig:DMData:tcControl:hdrControl:MSRHDRContext:] : 1188 -> 1228
~ -[MSRHDRProcessing populateMSRColorConfigStageB04_05:Enabled:Prefix:DMConfig:DMData:tcControl:hdrControl:MSRHDRContext:] : 2296 -> 2276
~ -[MSRHDRProcessing runPostFrameDumpActions:] : 160 -> 180
~ _DumpVDbl : 288 -> 280
~ _DumpVDblMatlab : 244 -> 240
~ _hasHdr10TonemapConfigChanged : 1396 -> 1420
~ _hasDoviTonemapConfigChanged : 560 -> 592
~ _has_SMPTE_ST_2094_50_TonemapConfigChanged : 568 -> 600
~ -[DISPHDRProcessing populateDISPToneMapConfig:DMConfig:DMData:tcControl:hdrControl:DISPHDRContext:] : 760 -> 764
~ -[DISPHDRProcessing populateDISPColorConfigPreToneMapCSC:AlgoMode:Prefix:DMConfig:DMData:tcControl:hdrControl:DISPHDRContext:] : 400 -> 396
~ -[DISPHDRProcessing populateDISPColorConfigToneMapParametric:Prefix:DMConfig:DMData:tcControl:hdrControl:DISPHDRContext:] : 1864 -> 1880
~ -[DISPHDRProcessing hdr10_tm_createLUTFromDMConfig:TMParam:TMParam:TCControl:EdrAdaptationParam:AmbAdaptationParam:DM:] : 444 -> 440
~ -[DISPHDRProcessing hdr10_mixLUTFromTCControl:TCControlConstr:withFactor:] : 232 -> 212
~ -[DISPHDRProcessing hlg_mixLUTFromTCControl:TCControlConstr:withFactor:] : 288 -> 292
~ -[DISPHDRProcessing smpte_st_2094_50_mixLUTFromTCControl:TCControlConstr:withFactor:] : 324 -> 328
~ -[DISPHDRProcessing setDisplayManagementParametricConfigToneMapBezier:TMSendC:] : 92 -> 100
~ -[DISPHDRProcessing setDisplayManagementParametricConfigToneMapSpline:] : 304 -> 316
~ -[DISPHDRProcessing setDisplayManagementParametricConfig:HDRControl:] : 580 -> 612
~ -[HDRProcessor initWithConfig:] : 1872 -> 1868
~ -[HDRProcessor processFrameInternalWithLayer0:layer1:outout:metadata:commandbuffer:operation:config:histogram:data:] : 7420 -> 7184
~ -[HDRProcessor logConstraintWithValue:fromCA:onExit:] : 692 -> 688
~ __Z18floatCopyWithCountPfS_j : 32 -> 40
~ -[HDRProcessor setCSCMatrixInHDRControl:forIndex:] : 172 -> 164
~ -[HDRBackwardDisplayManagement createKernels] : 10884 -> 11056
~ -[HDRBackwardDisplayManagement createBuffers] : 400 -> 416
~ -[HDRBackwardDisplayManagement createMetadataTexture] : 512 -> 520
~ -[HDRBackwardDisplayManagement createMetadataVertexBuffer] : 592 -> 588
~ -[HDRBackwardDisplayManagement updateConfigFromMetadata:uiScaleFactor:width:background:hdrVideoOnly:hdr10TV:sdrOnly:] : 1932 -> 1924
~ -[HDRBackwardDisplayManagement generateMetaAndConfig:inputSurface:outputSurface:payLoad:dmCfg:] : 1288 -> 1292
~ -[HDRBackwardDisplayManagement drawMetaWithEncoder:widthScale:dmPayLoadLength:] : 352 -> 360
~ -[HDRBackwardDisplayManagement packetizeMetadata:length:into:onSurface:] : 476 -> 488
~ -[HDRBackwardDisplayManagement setupTexturesWithInput:VideoSRGB:UI:UISRGB:Output:PixelPerThread:ptvMode:] : 736 -> 732
~ -[MSRHDRProcessingT2 updatePolynomialTablesForComponent:Component:TableSize:] : 104 -> 112
~ -[MSRHDRProcessingT2 updateMmrTableForComponent:mmrClipValMin:mmrClipValMax:mmrCoeff:] : 124 -> 136
~ -[MSRHDRProcessingT2 setupMSRMappingTableWithMetadata:] : 996 -> 980
~ _BuildDisplayIdxTbl : 48 -> 56
~ _GetXyz2LmsM33 : 48 -> 44
~ _GetLms2IctcpDmM33 : 56 -> 64
~ _APPLY_CT2RIGHT : 236 -> 232
~ -[HistStatLinkedListNode initWithStreamId:bufferSize:] : 2172 -> 2184
~ -[HistStatLinkedListNode dealloc] : 228 -> 236
~ __ZN16EDRMetaData_RBSP12copy_dm_dataEP11DM_MetaData : 560 -> 576
~ __ZN16EDRMetaData_RBSP13copy_rpu_dataEP12RPU_MetaData : 2492 -> 2804
~ __ZN16EDRMetaData_RBSP15rpu_data_headerEv : 3524 -> 3540
~ __ZN16EDRMetaData_RBSP18vdr_dm_set_defaultEv : 320 -> 340
~ __ZN16EDRMetaData_RBSP19vdr_dm_data_payloadEv : 2276 -> 2264
~ __Z21set_dm_data_for_hdr10P11DM_MetaData : 192 -> 196
~ __ZN16EDRMetaData_RBSP19assign_pivot_valuesEv : 120 -> 100
~ __ZN16EDRMetaData_RBSP23assign_nlq_pivot_valuesEv : 52 -> 64
~ __ZN16EDRMetaData_RBSP16rpu_data_mappingEjj : 2008 -> 1976
~ __ZN16EDRMetaData_RBSP27rpu_data_spatial_resamplingEjj : 280 -> 276
~ __ZN16EDRMetaData_RBSP12rpu_data_nlqEjj : 1156 -> 1368
~ __ZN16EDRMetaData_RBSP22rpu_data_mapping_paramEjjjj : 2036 -> 2420
~ __ZN16EDRMetaData_RBSP45rpu_data_chroma_resampling_filter_1D_exp_coefEjjjj : 220 -> 236
~ __ZN16EDRMetaData_RBSP38rpu_data_spatial_resampling_filter_expEjjj : 232 -> 284
~ __ZN16EDRMetaData_RBSP13cal_rpu_crc32Ev : 92 -> 80
~ __Z11BezierCurvePfiS_S_iS_S_ : 504 -> 480
~ __Z23getBezierCurvePolyCoeffPfS_iS_S_ : 136 -> 128
~ __Z23getBezierCurvePolyCoeffPfiS_ : 108 -> 104
~ __Z15BezierCurvePolyPfiS_S_iS_S_ : 404 -> 388
~ __Z15BezierCurvePolyPfiS_iS_ : 288 -> 276
~ __Z33convertTonemapCurveS_C_Bezier_absP14_ebzCurveParamf : 28 -> 44
~ __Z16getBezierAnchorsP14_ebzCurveParam : 156 -> 144
~ __Z19convertBezierToPolyP14_ebzCurveParam : 312 -> 292
~ -[DolbyVisionComposer embeddedSetupEncoderForCommandBuffer:DMData:dmConfig:isInput422:hasThreeOutputPlane:isSdrOnDolbyOrHDR10:isHDR10OnHDR10TV:isDolbyOnHDR10TV:isHDR10OnDolby:isHDR10OnPad:isHLGOnPad:isDoviOnPad:isDoviOnLLDovi:isHDR10OnLLDovi:isHLGOnHDR10TV:isHLGOnDolbyTV:isHLGOnLLDovi:isPtvMode:orientation:isDolby84:dovi50toHDR10TVMode:isDM4:isGpuTmRefMode:] : 7304 -> 7128
~ -[DolbyVisionComposer embeddedSetupEncoderForGpuMatchMsrCommandBuffer:DMData:dmConfig:isInput422:orientation:isDolby84:dovi50toHDR10TVMode:isDM4:dpcParam:tcControl:hdrControl:isHDR10Content:isHLGContent:isDOVIContent:] : 3172 -> 3156
~ -[DolbyVisionComposer initBuffers] : 416 -> 424
~ -[DolbyVisionComposer encodeComposeChromaToCommandBuffer:withMetaData:] : 420 -> 416
~ _createMMRCoefficients : 260 -> 292
~ _setupNlqParameters : 160 -> 216
~ -[DolbyVisionComposer hdr10_tm_createLUTFromDMConfig:TMParam:TMParam:EdrAdaptationParam:AmbAdaptationParam:HDRControl:DM:] : 360 -> 364
~ -[DolbyVisionComposer getTmLutInput:lutInput:] : 64 -> 60
~ -[DolbyVisionComposer getTmLutInput_C:lutInput:] : 48 -> 56
~ -[DolbyVisionComposer smpte_st_2094_50_tm_createLUTFromDMConfig:TMParam:EdrAdaptationParam:AmbAdaptationParam:] : 296 -> 300
~ -[DolbyVisionComposer dovi_dm4_updateInterleavedLUT] : 440 -> 460
~ -[DolbyVisionComposer .cxx_destruct] : 2732 -> 2708
~ _createPolynomialTableForComponent : 336 -> 320
~ _createNlqTableForComponent : 276 -> 284
~ -[AdaptiveTM init:] : 340 -> 348
~ -[AdaptiveTM adaptiveToneMappingAveragePixelLevel:DM:TCControl:HDRControl:LLDoVi:] : 1404 -> 1384
~ -[AdaptiveTM adaptiveToneMappingTemporalProcess:DMConfig:DM:TCControl:HDRControl:hdr10InfoFrame:] : 692 -> 708
~ -[AdaptiveTM adaptiveToneMappingManagement:DMConfig:DM:TCControl:HDRControl:hdr10InfoFrame:LLDoVi:frameNumber:] : 640 -> 656
~ -[SpatialResampler encodeSpatialResampleVertical:Input:Output:isChroma:] : 500 -> 496
~ -[DolbyVisionDM4 applyL9:] : 600 -> 596
~ -[DolbyVisionDM4 BuildLumaXInfo:TrimSetAct:Luma:Idxa:IdxMax:X2Interp:DmMetaData:] : 748 -> 752
~ -[DolbyVisionDM4 BuildChromaXInfo:TrimSetAct:Luma:Idxa:IdxMax:X2Interp:DmMetaData:] : 1308 -> 1328
~ -[DolbyVisionDM4 BuildInterpInfo:Xa:Idxa:TIdxMax:X2Interp:Alpha:U16a:U16L:U16R:DmMetaData:] : 872 -> 888
~ -[DolbyVisionDM4 DecodeL2L8:CodeBias2:TrimData8:CodeBias8:Default8:UseDftLuma:UseDftChroma:] : 724 -> 748
~ -[DolbyVisionDM4 SetL2L8L10:TrimData8:Default8:UseDftLuma:UseDftChroma:] : 252 -> 264
~ -[DolbyVisionDM4 initTrimData:] : 1280 -> 1288
~ __Z17InterpChromaTrim8PK14DM_MetaData_L8S1_S1_dP10trimData_t11_TrimSetAct : 164 -> 172
~ -[DolbyVisionDM4 initToneMapMatrices:outbits:srcRgb2LmsTm:tgtRgb2LmsTm:] : 468 -> 504
~ __Z13RgbLinear2ItpfffPA3_KfS1_Pf : 752 -> 784
~ -[DolbyVisionDM4 getDM4Params:] : 88 -> 104
~ -[DolbyVisionDM4 createToneCurve:srcMaxPQ:tgtMinPQ:tgtMaxPQ:srcCrushPQ:srcMidPQ:srcClipPQ:targetMaxLinear:DM_MetaData:tcCtrl:dm4TmMode:] : 1588 -> 1600
~ -[DolbyVisionDM4 createTmLuts:tLutS:sLutI:sLutS:tLutISize:tLutSSize:sLutISize:sLutSSize:] : 544 -> 528
~ -[DolbyVisionDM4 createTmLutsEx:tLutS:sLutI:sLutS:tLutISize:tLutSSize:sLutISize:sLutSSize:config:TmParam:EdrAdaptationParam:AmbAdaptationParam:IsDoVi84:HlgOOTFCombined:] : 2344 -> 2324
~ -[DolbyVisionDM4 ToneMapping:pX1:pX2:pAdm:] : 476 -> 524
~ -[DolbyVisionDM4 hasDM4TonemapConfigChanged:TonemapConfig:TCControl:EdrAdaptationParam:AmbAdaptationParam:] : 576 -> 612
~ _SMPTE_ST_2094_50_DeriveKValuesFromMixType : 292 -> 284
~ _SMPTE_ST_2094_50_EncodeKValuesToCoefficients : 204 -> 196
~ _SMPTE_ST_2094_50_ValidateMetadataSet : 492 -> 488
~ __Z48SMPTE_ST_2094_50_ValidateChromaticityCoordinatesPKf : 72 -> 80
~ _SMPTE_ST_2094_50_DecodeBinaryDataToSyntaxElements : 1148 -> 1104
~ _SMPTE_ST_2094_50_ConvertSyntaxElementsToMetadataSet : 1816 -> 1652
~ _SMPTE_ST_2094_50_DbgPrintMetadataItems : 640 -> 584
~ _SMPTE_ST_2094_50_ConvertMetadataSetToSyntaxElements : 1196 -> 1096
~ _SMPTE_ST_2094_50_AnnexFGenerateAdaptiveToneMap : 284 -> 296
~ _SMPTE_ST_2094_50_EvaluateGainCurve : 564 -> 552
~ _SMPTE_ST_2094_50_ComputeWeightedGain : 1096 -> 1004
~ _SMPTE_ST_2094_50_GenerateRWTMOMetadata : 464 -> 508
~ _SMPTE_ST_2094_50_AnnexFGenerateControlPoints : 600 -> 632
~ _SMPTE_ST_2094_50_ComputeColorPrimaryMatrix : 648 -> 652
~ _SMPTE_ST_2094_50_InitializeMetadataSetWithCurve : 372 -> 376
~ _SMPTE_ST_2094_50_PrintSyntaxApplicationInfo : 304 -> 320
~ _SMPTE_ST_2094_50_ApplyAdaptiveToneMapSingleChannel : 840 -> 816
~ __ZL14packHCUInPlaceP13NSMutableDataPK29hcuApiHdrConfigurationUnitsV3 : 420 -> 424
~ __ZN9HDRConfig15ReadConfigEntryE11HDRConfigID : 1444 -> 1460
~ __ZN9HDRConfig20ReadAllConfigEntriesE18HDRConfigFrequency : 140 -> 156
~ __ZN9HDRConfig26InvalidateAllConfigEntriesEv : 56 -> 76
~ __ZN9HDRConfig19LogAllConfigEntriesE14HDRConfigLeveljj : 832 -> 836
~ __Z23getScalingFactorByTablePfiff : 68 -> 64
~ __Z21generateHeadroomCurvePfifffP11dm_config_tP14headRoomConfig : 236 -> 248
~ __Z10check1DLutiPff : 132 -> 164
~ __Z13adjustMidToneffPKfS0_iiS0_ : 544 -> 540
~ __Z24findL2MinTargetInPQ12BitP14DM_MetaData_L2 : 48 -> 56
~ __Z13createTrimSetP14DM_MetaData_L2P11DM_MetaDatafPi : 444 -> 456
~ _convertMetaDataToPayLoad : 1684 -> 1692
~ _metaDataReduceL2 : 404 -> 444
~ _attachBackwardDisplayManagementMetaDataToBuffer : 1360 -> 1368
~ _setPQ2LBufferFP16 : 300 -> 308
~ _setPQ2LBuffer : 296 -> 304
~ _setHLG2LBuffer : 220 -> 228
~ _setLinearBuffer : 60 -> 68
~ _setL2PQBuffer : 552 -> 548
~ _setInverseScalingFactorTable : 248 -> 264
~ __Z18GetRelative_YUV_TMPfmffb : 1116 -> 1088
~ __Z20GetToneMap_SDR_DOLBYPfmfffff : 676 -> 680
~ _GetToneMap_YUV_TM : 820 -> 824
~ _hlg_setScalingFactorTable_C : 736 -> 744
~ _sdr_setScalingFactorTable : 960 -> 972
~ _sdr_setScalingFactorTable_C : 724 -> 732
~ _hdr10_setupTmParams : 6184 -> 6188
~ __Z17sdr_setupTmParamsP11dm_config_tP17hdrForwardControlP17ToneCurve_ControlP14DolbyVisionDM4PbPK20HistBasedToneMapping : 2160 -> 2152
~ -[DolbyVisionDisplayManagement hlg_setupTmParams:hdrCtrl:tcCtrl:dm40:applyPostRGBtoRGBMatrixScaler:pHistBasedToneMapping:] : 3556 -> 3552
~ __ZL17setupPreCSCMatrixP11dm_config_tjj : 300 -> 296
~ __ZL18setupPostCSCMatrixP11dm_config_tjj : 300 -> 296
~ -[DolbyVisionDisplayManagement smpte_st_2094_50_setupTmParams:hdrCtrl:tcCtrl:dm40:applyPostRGBtoRGBMatrixScaler:pHistBasedToneMapping:] : 1588 -> 1576
~ _setSRGBDegammaBuffer : 260 -> 268
~ _setGAMMADegammaBuffer : 200 -> 208
~ -[DolbyVisionDisplayManagement setConvertConfig:tcCtrl:hdrCtrl:auxData:tmData:] : 2048 -> 2052
~ -[DolbyVisionDisplayManagement setDisplayManagementToneMappingConfigFromMetaData:config:tcCtrl:hdrCtrl:auxData:dpcParam:] : 14256 -> 14276
~ -[DolbyVisionDisplayManagement getSat2Parameters:] : 144 -> 152
~ _spl_apply : 196 -> 208
~ _spl_apply_with_linear_extension : 232 -> 240
~ __Z45spl_apply_with_linear_extension_and_high_clipfiPKfS0_S0_ : 224 -> 232
~ __Z55spl_apply_with_linear_extension_and_high_clip_monotonicfiPKfS0_S0_ : 292 -> 300
~ __Z13spl_calculatefiPKfPA2_S_PA4_S_ : 232 -> 228
~ _ebz_norm : 296 -> 308
~ _piecewiseLinearInterp : 136 -> 132
~ _calculateEdrAdaptationParamS : 19668 -> 19652
~ _histogram_HLG2PQ : 540 -> 548
~ _histogram_SDR2PQ : 436 -> 452
~ _histogram_generate_percentiles : 188 -> 184
~ _firFilter : 52 -> 60
~ -[MSRHDRProcessingT1 getDegammaLutInput:] : 72 -> 64
~ -[HistBasedToneMapping init] : 3868 -> 3876
~ -[HistBasedToneMapping normalizeHistDataForHDR10Input] : 164 -> 168
~ -[HistBasedToneMapping normalizeHistDataAndMapToPQForHLGInput:] : 332 -> 328
~ -[HistBasedToneMapping normalizeHistDataForDoViInput] : 80 -> 88
~ -[HistBasedToneMapping normalizeHistDataAndMapToPQForSDRInput:transferFunction:bitDepth:] : 424 -> 420
~ -[HistBasedToneMapping normalizeHistData:transferFunction:videoFullRangeFlag:bitDepth:] : 368 -> 372
~ -[HistBasedToneMapping computeFrameAPLFromPQHistData:] : 528 -> 544
~ -[HistBasedToneMapping testpatchDetection:] : 656 -> 660
~ -[HistBasedToneMapping temporalProcessHistStat:iirAlpha:] : 1252 -> 1212
~ -[HistBasedToneMapping getSdrHdrMlmLut] : 484 -> 492
~ -[HistBasedToneMapping interpSdrHdrMlmLut:] : 192 -> 196
~ -[HistBasedToneMapping interpSdrHdrMlmLut:outarray:size:] : 248 -> 240
~ -[HistBasedToneMapping getHistStatFromLayer:HDRMode:transferFunction:videoFullRangeFlag:bitDepth:temporalMode:iirAlpha:frameNumber:] : 1092 -> 1100
~ -[HistBasedToneMapping copyHistStatFromObject:] : 276 -> 260
~ -[MSRHDRProcessingT5 getDegammaLutInput:] : 92 -> 88
~ __Z27getCurvatureDegammaLutInputPf : 92 -> 88
~ -[MSRHDRProcessingT3 hdr10_tm_updateLUT:ScalingFactorBuffer:LumaMixFactorBuffer:] : 316 -> 312
~ -[MSRHDRProcessingT3 populateMSRColorConfigStageB02HDR10:DMConfig:] : 808 -> 820
~ -[MSRHDRProcessingT3 populateMSRColorConfigStageB02HLG:DMConfig:hdrControl:] : 964 -> 960
~ _hdrpMrToneCurve : 268 -> 272
~ _TmDm4 : 444 -> 452
~ _BuildInterpInfo : 536 -> 532
~ __Z17adjustMidTone_dupffPKfS0_iiS0_ : 544 -> 540
~ _dovi84_setScalingFactorTableS_C : 536 -> 528
~ _hdr10_calculateTonemapCurveParamS : 12448 -> 12436
~ _hdr10_applyTonemapCurveS : 448 -> 484
~ __Z33hdr10_applyTonemapCurveS_C_BezierfPK13_HDR10TMParam : 220 -> 240
~ __Z37hdr10_applyTonemapCurveS_C_Bezier_absfPK13_HDR10TMParam : 212 -> 232
~ __Z38hdr10_applyTonemapCurveS_C_PolyGenericfPK13_HDR10TMParam : 368 -> 376
~ __Z34hdr10_applyTonemapCurveS_C_PolyStdfPK13_HDR10TMParam : 220 -> 232
~ _hdr10_applyTonemapCurveS_C : 560 -> 580
~ _hdr10_setLumaMixFactorTableS_L : 152 -> 160
~ -[MSRHDRProcessingByCapabilities setupMSRMappingTableWithMetadata:] : 1044 -> 1028
~ -[MSRHDRProcessingByCapabilities updatePolynomialTablesForComponent:Component:TableSize:] : 116 -> 124
~ -[MSRHDRProcessingByCapabilities updateMmrTableForComponent:mmrClipValMin:mmrClipValMax:mmrCoeff:] : 136 -> 148
~ -[MSRHDRProcessingByCapabilities getDegammaLutInput:] : 256 -> 244
~ -[MSRHDRProcessingByCapabilities hdr10_tm_updateLUT:ScalingFactorBuffer:LumaMixFactorBuffer:] : 316 -> 312
~ -[MSRHDRProcessingByCapabilities populateMSRColorConfigStageB02HDR10:DMConfig:] : 808 -> 820
~ -[MSRHDRProcessingByCapabilities populateMSRColorConfigStageB02HLG:DMConfig:hdrControl:] : 964 -> 960
~ -[MSRHDRProcessingByCapabilities populateMSRColorConfigStageB02SDR:hdrControl:] : 444 -> 440
~ -[MSRHDRProcessingByCapabilities populateMSRColorConfigStageHwOOTF:Enabled:Prefix:DMConfig:DMData:tcControl:hdrControl:MSRHDRContext:] : 336 -> 352
~ -[MSRHDRProcessingT4 populateMSRColorConfigStageHwOOTF:Enabled:Prefix:DMConfig:DMData:tcControl:hdrControl:MSRHDRContext:] : 312 -> 328
~ __ZN22HDR10PlusMetaData_RBSP20range_check_metadataEv : 4492 -> 4500
~ _MrParseMds : 3364 -> 3052
~ _AppenddDefaultL2L8Trim : 144 -> 128
~ _MrGetMdsExtFxpMr : 3284 -> 3168
~ -[HDRProcessorEx generateMSRColorConfigExWithOperation:InputSurfaces:OutputSurfaces:Metadatas:Histograms:Configs:NumOfGroup:MVImageLayout:] : 204 -> 212
~ -[HDRProcessorEx processWithMSRColorConfigs:MSRScaler:InputSurfaces:OutputSurfaces:CropRects:NumOfCropRectsInAGroup:NumOfGroup:] : 680 -> 672
~ __Z19PolyGeneric2PolyStdPfiifS_i : 444 -> 448
~ __Z19PolyGeneric2PolyStdPfififS_i : 124 -> 132
~ __Z16calculatePolyStdfPKfi : 128 -> 124
~ __Z20calculatePolyGenericfPfiif : 148 -> 144
~ __Z20calculatePolyGenericfPfiiS_ : 212 -> 208
~ __Z20calculatePolyGenericfPffiif : 160 -> 156
~ __Z20calculatePolyGenericfPffiiPKf : 216 -> 212
~ -[HDRMetadataManager multiviewAddDoViHDMIMetadata:width:height:priority:] : 2276 -> 2220
~ -[HDRMetadataManager multiviewGenerateDoViHDMIMetadata:] : 4440 -> 5392
~ _adjustL2MetaData : 720 -> 724
~ _Matrix3x3_invert : 356 -> 348
~ _Matrix3x3_multvector : 72 -> 88
~ _Matrix3x3_multvectorDbl : 72 -> 88
~ _Matrix3x3_multmatrix : 136 -> 140
~ _Matrix3x3_multmatrixWithScale : 156 -> 160
~ _createRGB2XYZ3x3Matrix : 332 -> 348
~ _hdrpMetadataReconstruction : 5828 -> 5744
~ -[DolbyVisionMR init] : 300 -> 308
~ -[DolbyVisionMR metadataReconstruction:dmData:maxDisplayBrightnessNits:targetMaxNits:targetMinNits:displayPrimaries:baseMax:baseMin:videoFullRangeFlag:colourPrimaries:matrixCoeffs:numFrames:] : 6544 -> 6600
~ __ZL29invalidateDMDataL2L4L5L6L8L10P11DM_MetaData : 248 -> 272
~ _FindInt64M33Precision : 116 -> 120
~ _Dm4Tc : 3892 -> 3884
~ _Dm23Tc : 2344 -> 2352
CStrings:
+ " [1.513.1] \n"
+ " [1.513.1]      No entries to dump!\n"
+ " [1.513.1]     %s : Error: Unsupported config! retVal = %d"
+ " [1.513.1]     %s : Warning: after md reduction, payLoadLength=%d, max packet size=%d"
+ " [1.513.1]     %s : error max=%f <= min=%f, metaData=%p"
+ " [1.513.1]     %s: illegal HDR10Plus SEI, fall back to HDR10"
+ " [1.513.1]     %s: illegal SEI"
+ " [1.513.1]     %s: input=%p"
+ " [1.513.1]     %s: layer0=%p, output=%p, metatdata=%p, config=%p, histogram=%p"
+ " [1.513.1]     %s: metatdata= %p, bailout!!!\n"
+ " [1.513.1]     %s: missing SEI"
+ " [1.513.1]     %s: output=%p, bailout!!!\n"
+ " [1.513.1]     ERROR: Not supported operation %d !!!"
+ " [1.513.1]    %s : Error: Unsupported MSR input: operation=0x%x, input=%c%c%c%c [%c%c%c%c], output=%c%c%c%c [%c%c%c%c]"
+ " [1.513.1]    %s : Failed to create directory \"%s\".\n"
+ " [1.513.1]    %s : failed with error %ld\n"
+ " [1.513.1]    %s : instance=%p"
+ " [1.513.1]    %s : instance=%p\n"
+ " [1.513.1]    %s : invalid dump dir[%p] length"
+ " [1.513.1]    %s : metalDevice has changed!\n"
+ " [1.513.1]    %s : processor=%p\n"
+ " [1.513.1]    %s: ERROR: Failed to allocate memory! size = %lu bytes"
+ " [1.513.1]   !isMultipleOf2(region.origin.x=%d)"
+ " [1.513.1]   !isMultipleOf2(region.size.width=%d)"
+ " [1.513.1]   commanBuffer=%p, output=%p, input=%p ui=%p"
+ " [1.513.1]   region.origin.x=%d + region.size.width=%d > texWidth=%d"
+ " [1.513.1]   region.origin.x=%d >= texWidth=%d && region.origin.y=%d >= texHeight=%d"
+ " [1.513.1]   region.origin.y=%d + region.size.height=%d > texHeight=%d"
+ " [1.513.1]   videoSrcWidth=%d, videoSrcHeight=%d, dstWidth=%d, dstHeight=%d"
+ " [1.513.1]   warning: unknown matrix_coeffs=%d, sets to Rec709=%d"
+ " [1.513.1]   warning: unknown transfer_characteristics=%d, sets to PQ=%d"
+ " [1.513.1]  %30@: %-12s\n"
+ " [1.513.1]  %30@: %-12s    (value=%s, default=%s)\n"
+ " [1.513.1]  %30s %12s\n"
+ " [1.513.1]  %8d %30@ %12s %12s %12s\n"
+ " [1.513.1]  %8s %30s %12s %12s %12s\n"
+ " [1.513.1]  %s : Not supported type=%d\n"
+ " [1.513.1]  %s : newprocessor=%p\n"
+ " [1.513.1]  %s:%d: ERROR: Neither value nor defaults value is available! Key = \"%@\".\n"
+ " [1.513.1] #%04llx \n"
+ " [1.513.1] #%04llx      No entries to dump!\n"
+ " [1.513.1] #%04llx     %s : Error: Unsupported config! retVal = %d"
+ " [1.513.1] #%04llx     %s : Warning: after md reduction, payLoadLength=%d, max packet size=%d"
+ " [1.513.1] #%04llx     %s : error max=%f <= min=%f, metaData=%p"
+ " [1.513.1] #%04llx     %s: illegal HDR10Plus SEI, fall back to HDR10"
+ " [1.513.1] #%04llx     %s: illegal SEI"
+ " [1.513.1] #%04llx     %s: input=%p"
+ " [1.513.1] #%04llx     %s: layer0=%p, output=%p, metatdata=%p, config=%p, histogram=%p"
+ " [1.513.1] #%04llx     %s: metatdata= %p, bailout!!!\n"
+ " [1.513.1] #%04llx     %s: missing SEI"
+ " [1.513.1] #%04llx     %s: output=%p, bailout!!!\n"
+ " [1.513.1] #%04llx     ERROR: Not supported operation %d !!!"
+ " [1.513.1] #%04llx    %s : Error: Unsupported MSR input: operation=0x%x, input=%c%c%c%c [%c%c%c%c], output=%c%c%c%c [%c%c%c%c]"
+ " [1.513.1] #%04llx    %s : Failed to create directory \"%s\".\n"
+ " [1.513.1] #%04llx    %s : failed with error %ld\n"
+ " [1.513.1] #%04llx    %s : instance=%p"
+ " [1.513.1] #%04llx    %s : instance=%p\n"
+ " [1.513.1] #%04llx    %s : invalid dump dir[%p] length"
+ " [1.513.1] #%04llx    %s : metalDevice has changed!\n"
+ " [1.513.1] #%04llx    %s : processor=%p\n"
+ " [1.513.1] #%04llx    %s: ERROR: Failed to allocate memory! size = %lu bytes"
+ " [1.513.1] #%04llx   !isMultipleOf2(region.origin.x=%d)"
+ " [1.513.1] #%04llx   !isMultipleOf2(region.size.width=%d)"
+ " [1.513.1] #%04llx   commanBuffer=%p, output=%p, input=%p ui=%p"
+ " [1.513.1] #%04llx   region.origin.x=%d + region.size.width=%d > texWidth=%d"
+ " [1.513.1] #%04llx   region.origin.x=%d >= texWidth=%d && region.origin.y=%d >= texHeight=%d"
+ " [1.513.1] #%04llx   region.origin.y=%d + region.size.height=%d > texHeight=%d"
+ " [1.513.1] #%04llx   videoSrcWidth=%d, videoSrcHeight=%d, dstWidth=%d, dstHeight=%d"
+ " [1.513.1] #%04llx   warning: unknown matrix_coeffs=%d, sets to Rec709=%d"
+ " [1.513.1] #%04llx   warning: unknown transfer_characteristics=%d, sets to PQ=%d"
+ " [1.513.1] #%04llx  %30@: %-12s\n"
+ " [1.513.1] #%04llx  %30@: %-12s    (value=%s, default=%s)\n"
+ " [1.513.1] #%04llx  %30s %12s\n"
+ " [1.513.1] #%04llx  %8d %30@ %12s %12s %12s\n"
+ " [1.513.1] #%04llx  %8s %30s %12s %12s %12s\n"
+ " [1.513.1] #%04llx  %s : Not supported type=%d\n"
+ " [1.513.1] #%04llx  %s : newprocessor=%p\n"
+ " [1.513.1] #%04llx  %s:%d: ERROR: Neither value nor defaults value is available! Key = \"%@\".\n"
+ " [1.513.1] #%04llx %s : ERROR: Failed creating a new fragment function: %@ with error: %@"
+ " [1.513.1] #%04llx %s : ERROR: Failed creating a new function with _useCustomMatrix=%d, _p3CSC=%d, _applyYGamma=%d"
+ " [1.513.1] #%04llx %s : ERROR: Failed creating a new function with dolby84=%d, forLLDoVi=%d input=%d output=%d"
+ " [1.513.1] #%04llx %s : ERROR: Failed creating a new function: %@"
+ " [1.513.1] #%04llx %s : ERROR: Failed creating a new function: %@ with error: %@"
+ " [1.513.1] #%04llx %s : ERROR: Failed creating a new vertex function: %@ with error: %@"
+ " [1.513.1] #%04llx %s : ERROR: Failed to create backward DM Kernel: fragment[%p]=%@, vertex[%p]=%@, with error: %@"
+ " [1.513.1] #%04llx %s : ERROR: Failed to create forward DM Kernel: %@ with error: %@"
+ " [1.513.1] #%04llx %s : Error: Unsupported DoVi81 state: _hdrMode = %d, _displayType = %d, hasRPUData = %d, hasHDR10PlusSEIData = %d"
+ " [1.513.1] #%04llx %s : Error: Unsupported input: operation=0x%x, input=%c%c%c%c [%c%c%c%c]"
+ " [1.513.1] #%04llx %s : Failed to create HDRProcessorImpl\n"
+ " [1.513.1] #%04llx %s : Failed to create sampler for composer"
+ " [1.513.1] #%04llx %s : Failed with setupInputTexturesWithBL\n"
+ " [1.513.1] #%04llx %s : Failed with setupOutputTexturesWithBuffer\n"
+ " [1.513.1] #%04llx %s : HDR error: Failed to create MTLTexture For _metadataTextures[%d][%d]=%p\n"
+ " [1.513.1] #%04llx %s : Initialization Failed, self = %p\n"
+ " [1.513.1] #%04llx %s : Initialization Failed, self=%p\n"
+ " [1.513.1] #%04llx %s : encoder=%p, out of encoder resource"
+ " [1.513.1] #%04llx %s : error, device = %p, _device=%p\n"
+ " [1.513.1] #%04llx %s : error, self = %p \n"
+ " [1.513.1] #%04llx %s : failed with error %d\n"
+ " [1.513.1] #%04llx %s : format (%d) %c%c%c%c [%c%c%c%c]is not supported yet\n"
+ " [1.513.1] #%04llx %s : layer0=%p, layer1=%p, output=%p, metatdata=%p"
+ " [1.513.1] #%04llx %s : unknown HDRProcessing hw type %d, switching to GPU"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error ext_block_len[%u] > 256, bail!\n"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error in ext_content_adaptive_metadata, EXT_BLOCK_PAYLOAD, bail!\n"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error in ext_content_adaptive_metadata, EXT_BLOCK_PAYLOAD2, bail!\n"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error in vdr_dm_data_payload, bail!\n"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error level=%d, length=%d: invalid!"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error map_idc = %d, bail!\n"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error nal_unit_type = %d, bail!\n"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error num_blocks_payload2[%d] + num_ext_blocks[%d] > 255, bail!\n"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error num_ext_blocks = %d > 254, bail!\n"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error remaining_bits[%lu] < length[%u], bail!\n"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error reserved_zero_3bits=1, first frame, bail!\n"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error rpu_type = %d, bail!\n"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error signal_bit_depth = %d, bail!\n"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error vdr_rpu_level = %d, nlq_num_pivots_minus2 = %d, bail!\n"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error vdr_rpu_level = %d, num_x_partitions_minus1 = %d, bail!\n"
+ " [1.513.1] #%04llx %s: EDRMetaData_RBSP error vdr_rpu_level = %d, num_y_partitions_minus1 = %d, bail!\n"
+ " [1.513.1] #%04llx %s: ERROR: Out of bound! curr_part_idx = %d, y = %d, x = %d, bail!\n"
+ " [1.513.1] #%04llx %s: ERROR: Out of bound! mapping_chroma_format_idc = %d, bail!\n"
+ " [1.513.1] #%04llx %s: ERROR: Out of bound! mmr_order_minus1 = %d, bail!\n"
+ " [1.513.1] #%04llx %s: ERROR: Out of bound! poly_order_minus1 = %d, bail!\n"
+ " [1.513.1] #%04llx %s: ERROR: Out of bound! vdr_rpu_level = %d, num_pivots_minus2[%d] = %d, bail!\n"
+ " [1.513.1] #%04llx %s: calloc failed!\n"
+ " [1.513.1] #%04llx %s: input=%p, options=%p, configCallback=%p"
+ " [1.513.1] #%04llx %s: parsing error remaining_bits = %d, bail!\n"
+ " [1.513.1] #%04llx %s: parsing error, bail!\n"
+ " [1.513.1] #%04llx %s: parsing error: first_byte = %u [legal value = 4 or 181], bail!\n"
+ " [1.513.1] #%04llx %s: parsing error: num_bezier_curve_anchors = %d, bail!\n"
+ " [1.513.1] #%04llx %s: parsing error: num_distributions = %d [legal value = 9], bail!\n"
+ " [1.513.1] #%04llx %s: parsing error: num_windows = %d [legal value = 1], bail!\n"
+ " [1.513.1] #%04llx %s: parsing error: sei_payload_type = %u [legal value = 4], sei_payload_length = %u, actual seiLength = %u, bail!\n"
+ " [1.513.1] #%04llx %s: syntax error: application_identifier = %d"
+ " [1.513.1] #%04llx %s: syntax error: application_version = %d"
+ " [1.513.1] #%04llx %s: syntax error: average_maxrgb = %08x"
+ " [1.513.1] #%04llx %s: syntax error: color_saturation_mapping_flag = %d"
+ " [1.513.1] #%04llx %s: syntax error: distribution_index[%d]:%d != k_distribution_index[%d]:%d"
+ " [1.513.1] #%04llx %s: syntax error: distribution_values[%d] = %08x"
+ " [1.513.1] #%04llx %s: syntax error: itu_t_t35_country_code = %02x"
+ " [1.513.1] #%04llx %s: syntax error: itu_t_t35_terminal_provider_code = %04x"
+ " [1.513.1] #%04llx %s: syntax error: itu_t_t35_terminal_provider_oriented_code = %d"
+ " [1.513.1] #%04llx %s: syntax error: mastering_display_actual_peak_luminance_flag = %d"
+ " [1.513.1] #%04llx %s: syntax error: maxscl[%d] = %08x"
+ " [1.513.1] #%04llx %s: syntax error: targeted_system_display_actual_peak_luminance_flag = %d"
+ " [1.513.1] #%04llx %s: warning: fraction_bright_pixels = %d"
+ " [1.513.1] #%04llx ++ %s : MSR created! instance=%p, platform=0x%x\n"
+ " [1.513.1] #%04llx ++ %s : instance=%p _composer=%p _msr=%p"
+ " [1.513.1] #%04llx ++ %s: MSRApiVer=%d\n"
+ " [1.513.1] #%04llx -- %s : Failed with error %d, _numberOfScheduledFrames=%ld\n"
+ " [1.513.1] #%04llx -- %s: HDRProcessor exit! instance=%p\n"
+ " [1.513.1] #%04llx -- %s: MSR exit! instance=%p\n"
+ " [1.513.1] #%04llx --------------------------------------------------------\n"
+ " [1.513.1] #%04llx -----------------------------------------------------------------------------------\n"
+ " [1.513.1] #%04llx <<smpte_st_2094_50:dbg>> warning: Failed to parse SMPTE ST 2094-50 metadata, error=%d"
+ " [1.513.1] #%04llx Assertion: \"!_hist\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/hist_based_tone_mapping.mm\" at line 308\n"
+ " [1.513.1] #%04llx Assertion: \"!inputP422\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1814\n"
+ " [1.513.1] #%04llx Assertion: \"!inputP422\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1988\n"
+ " [1.513.1] #%04llx Assertion: \"!ptvMode\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 3613\n"
+ " [1.513.1] #%04llx Assertion: \"(msrHC->operation == ((HDRProcessingOperation)(kHDRProcessingReshape | kHDRProcessingToneMap)))\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 3019\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1228\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1379\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1406\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1439\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 477\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 860\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1818\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1821\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1827\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1983\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1998\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2002\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2005\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2011\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2020\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/SpatialResampler.m\" at line 212\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/SpatialResampler.m\" at line 243\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 3441\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 3539\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 3778\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 4859\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 5119\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6803\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6833\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 2653\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 4266\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/MetaPacket/DolbyVisionHDMIPacket.mm\" at line 619\n"
+ " [1.513.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/MetaPacket/DolbyVisionHDMIPacket.mm\" at line 678\n"
+ " [1.513.1] #%04llx Assertion: \"HDR10OnHDR10TV || DolbyOnHDR10TV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2032\n"
+ " [1.513.1] #%04llx Assertion: \"HLGOnHDR10TV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1804\n"
+ " [1.513.1] #%04llx Assertion: \"_currentPolynomialTable\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2027\n"
+ " [1.513.1] #%04llx Assertion: \"_displayType != kHDRDestinationSDRTV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 2921\n"
+ " [1.513.1] #%04llx Assertion: \"_hdrMode == kHDRContentDolbyVision\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 1902\n"
+ " [1.513.1] #%04llx Assertion: \"_hdrMode == kHDRContentDolbyVision\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 1934\n"
+ " [1.513.1] #%04llx Assertion: \"_metadataVertexBuffer\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 2515\n"
+ " [1.513.1] #%04llx Assertion: \"_msrHC.processingType == kHDRProcessingTypeConvert\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 785\n"
+ " [1.513.1] #%04llx Assertion: \"_vertsBuffer\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 2476\n"
+ " [1.513.1] #%04llx Assertion: \"bufferT && bufferS\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 2640\n"
+ " [1.513.1] #%04llx Assertion: \"bufferT && bufferS\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 2688\n"
+ " [1.513.1] #%04llx Assertion: \"chromaPixelFormat != MTLPixelFormatInvalid\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 3874\n"
+ " [1.513.1] #%04llx Assertion: \"cmp != 0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingByCapabilities.mm\" at line 328\n"
+ " [1.513.1] #%04llx Assertion: \"cmp != 0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingT2.mm\" at line 185\n"
+ " [1.513.1] #%04llx Assertion: \"dm_config_ptr->dmVersion == 4\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 3040\n"
+ " [1.513.1] #%04llx Assertion: \"hasThreeOutputPlane || has10BitOutput\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1181\n"
+ " [1.513.1] #%04llx Assertion: \"hdrCtrl->colourPrimaries == kIOSurfaceTagColorPrimaries_ITU_R_2020\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6950\n"
+ " [1.513.1] #%04llx Assertion: \"hdrCtrl->colourPrimaries == kIOSurfaceTagColorPrimaries_ITU_R_709_2\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 8656\n"
+ " [1.513.1] #%04llx Assertion: \"hdrCtrl->displayPipelineCompensationType != kDisplayPipelineCompensationTypeNoneHeadrooomDependent && hdrCtrl->displayPipelineCompensationType != kDisplayPipelineCompensationTypeHeadroomDependent\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6070\n"
+ " [1.513.1] #%04llx Assertion: \"hdrCtrl->transferFunction != kIOSurfaceTagColorTransferFunction_ITU_R_2100_HLG\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Engine/ProcessingEngine.mm\" at line 356\n"
+ " [1.513.1] #%04llx Assertion: \"hdrCtrl->transferFunction != kIOSurfaceTagColorTransferFunction_ITU_R_2100_HLG\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2225\n"
+ " [1.513.1] #%04llx Assertion: \"isConversionInputRgb(msrHC) || isConversionInputYuv(msrHC) || isConversionInputIpt(msrHC)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2994\n"
+ " [1.513.1] #%04llx Assertion: \"isConversionOutputYuv(msrHC)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 5539\n"
+ " [1.513.1] #%04llx Assertion: \"isGPUtoHDR10TV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 1460\n"
+ " [1.513.1] #%04llx Assertion: \"isTonemappingEnabled(msrHC)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 4562\n"
+ " [1.513.1] #%04llx Assertion: \"metadata->mapping_idc[0][0][cmp][0] == 0 || metadata->mapping_idc[0][0][cmp][0] == 1\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingByCapabilities.mm\" at line 313\n"
+ " [1.513.1] #%04llx Assertion: \"metadata->mapping_idc[0][0][cmp][0] == 0 || metadata->mapping_idc[0][0][cmp][0] == 1\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingT2.mm\" at line 170\n"
+ " [1.513.1] #%04llx Assertion: \"mid_tap_h >= 4 && mid_tap_v >= 1\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 252\n"
+ " [1.513.1] #%04llx Assertion: \"msrHC->enableConverting && !msrHC->enableToneMapping\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2993\n"
+ " [1.513.1] #%04llx Assertion: \"msrHC->processingType == kHDRProcessingTypeDoVi || msrHC->processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 4608\n"
+ " [1.513.1] #%04llx Assertion: \"msrHC->processingType == kHDRProcessingTypeDoVi || msrHC->processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 5161\n"
+ " [1.513.1] #%04llx Assertion: \"overrideHLGOOTFMixingStartTdivNits >= 100.0f\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/dovi_display_management_host.mm\" at line 717\n"
+ " [1.513.1] #%04llx Assertion: \"overrideHLGOOTFMixingStartTdivNits >= 100.0f\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/hlg_display_management_host.mm\" at line 121\n"
+ " [1.513.1] #%04llx Assertion: \"polyBuf && mmrCoefBuf\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingByCapabilities.mm\" at line 310\n"
+ " [1.513.1] #%04llx Assertion: \"polyBuf && mmrCoefBuf\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingT2.mm\" at line 167\n"
+ " [1.513.1] #%04llx Assertion: \"processingType == kHDRProcessingTypeDoVi || processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Engine/ProcessingEngine.mm\" at line 370\n"
+ " [1.513.1] #%04llx Assertion: \"processingType == kHDRProcessingTypeDoVi || processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Engine/ProcessingEngine.mm\" at line 425\n"
+ " [1.513.1] #%04llx Assertion: \"processingType == kHDRProcessingTypeDoVi || processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2228\n"
+ " [1.513.1] #%04llx Assertion: \"retVal == 0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 4500\n"
+ " [1.513.1] #%04llx Assertion: \"sMaxPq <= L2PqNorm(4000)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 7468\n"
+ " [1.513.1] #%04llx Assertion: \"sMinPq >= L2PqNorm(0.005)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 7469\n"
+ " [1.513.1] #%04llx Assertion: \"sdrOnDolbyOrHDR10 == __objc_no\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1775\n"
+ " [1.513.1] #%04llx Assertion: \"sdrOnDolbyOrHDR10 == __objc_no\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1782\n"
+ " [1.513.1] #%04llx Assertion: \"tableSize == 1024\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/common_display_management_host.mm\" at line 3730\n"
+ " [1.513.1] #%04llx Assertion: \"y1 == y2\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 2613\n"
+ " [1.513.1] #%04llx Constraint changed to: %s"
+ " [1.513.1] #%04llx Constraint: #=%d F=%d C=%d T=%d NP=%d(%2.4f - %2.4f)"
+ " [1.513.1] #%04llx Constraint: %s"
+ " [1.513.1] #%04llx ContentType: %s, sr=%d"
+ " [1.513.1] #%04llx HDRConfig: Frame #%d: configDumpStyle = %d (%s), configDumpLevel = %d, configDumpFlag = %d\n"
+ " [1.513.1] #%04llx Incorrect mode usage : %d _hdrMode = %d"
+ " [1.513.1] #%04llx MR81: Error: BuildInterpInfo TrimLevel must be 8"
+ " [1.513.1] #%04llx MR81: Error: BuildLumaXInfo trimNum=0"
+ " [1.513.1] #%04llx MR81: Error: GetMdsExtMr mr->mdsBase.mdsLen < 71"
+ " [1.513.1] #%04llx MR81: Error: GetRgb2XyzM33, unsupported rgbDef:%d"
+ " [1.513.1] #%04llx MR81: Error: InterpL2 MDSEXT_HAVE_LVL_L0 is false"
+ " [1.513.1] #%04llx MR81: Error: InterpL8 MDSEXT_HAVE_LVL_L0 is false"
+ " [1.513.1] #%04llx MR81: Error: MrGetMdsExtFxpMr extLen < 0"
+ " [1.513.1] #%04llx MR81: Error: MrGetMdsExtFxpMr mdsLen < 0"
+ " [1.513.1] #%04llx MR81: Error: PrepareL2 MDSEXT_HAVE_LVL_L0 is false"
+ " [1.513.1] #%04llx MR81: Error: PrepareL8 MDSEXT_HAVE_LVL_L0 is false"
+ " [1.513.1] #%04llx MR81: metadataReconstruction: Error: GetMdsExtFxpMr ret = %d"
+ " [1.513.1] #%04llx MR81: metadataReconstruction: Error: ParseMds ret = %d"
+ " [1.513.1] #%04llx MR81: metadataReconstruction: Error: ret = %d"
+ " [1.513.1] #%04llx MR81: metadataReconstruction: Error: unmapped, hasMMRData=%d"
+ " [1.513.1] #%04llx MR81: metadataReconstruction: Warning: GetMdsExtFxpMr ret = %d [no change]"
+ " [1.513.1] #%04llx MR81: metadataReconstruction: Warning: RGBtoLMS_coef [%d][%d] changed, %d/%d"
+ " [1.513.1] #%04llx MR81: metadataReconstruction: Warning: YCCtoRGB_coef [%d][%d] changed, %d/%d"
+ " [1.513.1] #%04llx MR81: metadataReconstruction: Warning: YCCtoRGB_offset[%d] changed, %u/%u"
+ " [1.513.1] #%04llx MR81: metadataReconstruction: Warning: ret = %d [no change]"
+ " [1.513.1] #%04llx Memory allocation for  histBinCentroidInLinear failed"
+ " [1.513.1] #%04llx Memory allocation for _cdf failed"
+ " [1.513.1] #%04llx Memory allocation for _fullRangeBinIdx8bit failed"
+ " [1.513.1] #%04llx Memory allocation for _histBinMlmInPQ failed"
+ " [1.513.1] #%04llx Memory allocation for _sdrHdrMlmLut_x failed"
+ " [1.513.1] #%04llx Memory allocation for _sdrHdrMlmLut_y failed"
+ " [1.513.1] #%04llx Memory allocation for avgValBuffer failed"
+ " [1.513.1] #%04llx Memory allocation for fullRangeBinIdx failed"
+ " [1.513.1] #%04llx Memory allocation for histBinCenter failed"
+ " [1.513.1] #%04llx Memory allocation for histBuff failed"
+ " [1.513.1] #%04llx Memory allocation for hlgBinCenterInPQ failed"
+ " [1.513.1] #%04llx Memory allocation for maxValBuffer failed"
+ " [1.513.1] #%04llx Memory allocation for minValBuffer failed"
+ " [1.513.1] #%04llx Memory allocation for normHist failed"
+ " [1.513.1] #%04llx Memory allocation for pcntVal failed"
+ " [1.513.1] #%04llx Memory allocation for pqBinCenterInPQ failed"
+ " [1.513.1] #%04llx Memory allocation for prctVal failed"
+ " [1.513.1] #%04llx Memory allocation for prctValBuffer failed"
+ " [1.513.1] #%04llx Memory allocation for prctValBuffer[i] failed"
+ " [1.513.1] #%04llx Memory allocation for prevNormHistHeight failed"
+ " [1.513.1] #%04llx Memory allocation for sdrBinCenterInPQ failed"
+ " [1.513.1] #%04llx Memory allocation for stdValBuffer failed"
+ " [1.513.1] #%04llx Memory allocation for targetMaxBuffer failed"
+ " [1.513.1] #%04llx Memory allocation for testpatchHistBuff failed"
+ " [1.513.1] #%04llx Not supported type=%d\n"
+ " [1.513.1] #%04llx ToneMapLUT_xsamples memory allocation failed!"
+ " [1.513.1] #%04llx ToneMapLUT_ysamples memory allocation failed!"
+ " [1.513.1] #%04llx ToneMapMixFactorLUT_xsamples memory allocation failed!"
+ " [1.513.1] #%04llx ToneMapMixFactorLUT_ysamples memory allocation failed!"
+ " [1.513.1] #%04llx WARNING: calcCubicSplineParam: delta == 0"
+ " [1.513.1] #%04llx WARNING: cubicSplineInterp: delta == 0"
+ " [1.513.1] #%04llx Warning: Attempting to read defaults writes in release builds! key = \"%@\"\n"
+ " [1.513.1] #%04llx [frame_%llu] scheduled2completed: avg: %5.1f, max: %5.1f [in ms], [ %d : %d ]\n"
+ " [1.513.1] #%04llx _width=%d, _targetWidth=%d, _height=%d, _targetHeight=%d"
+ " [1.513.1] #%04llx checkInputOutputIOSurface() failed!"
+ " [1.513.1] #%04llx commanBuffer=%p, output=%p, input=%p, ui=%p"
+ " [1.513.1] #%04llx failed due to metalDevice change!"
+ " [1.513.1] #%04llx hcr : %s"
+ " [1.513.1] #%04llx hcr changes to: %s"
+ " [1.513.1] #%04llx hcrUseSystemBrightnessForCaptureContent : %s"
+ " [1.513.1] #%04llx hcrUseSystemBrightnessForCaptureContent changes to: %s"
+ " [1.513.1] #%04llx hcrUseSystemBrightnessForProContent : %s"
+ " [1.513.1] #%04llx hcrUseSystemBrightnessForProContent changes to: %s"
+ " [1.513.1] #%04llx hdrMaxBrightnessInNits was forced to %f!"
+ " [1.513.1] #%04llx sdrMaxBrightnessInNits was forced to %f!"
+ " [1.513.1] %s : ERROR: Failed creating a new fragment function: %@ with error: %@"
+ " [1.513.1] %s : ERROR: Failed creating a new function with _useCustomMatrix=%d, _p3CSC=%d, _applyYGamma=%d"
+ " [1.513.1] %s : ERROR: Failed creating a new function with dolby84=%d, forLLDoVi=%d input=%d output=%d"
+ " [1.513.1] %s : ERROR: Failed creating a new function: %@"
+ " [1.513.1] %s : ERROR: Failed creating a new function: %@ with error: %@"
+ " [1.513.1] %s : ERROR: Failed creating a new vertex function: %@ with error: %@"
+ " [1.513.1] %s : ERROR: Failed to create backward DM Kernel: fragment[%p]=%@, vertex[%p]=%@, with error: %@"
+ " [1.513.1] %s : ERROR: Failed to create forward DM Kernel: %@ with error: %@"
+ " [1.513.1] %s : Error: Unsupported DoVi81 state: _hdrMode = %d, _displayType = %d, hasRPUData = %d, hasHDR10PlusSEIData = %d"
+ " [1.513.1] %s : Error: Unsupported input: operation=0x%x, input=%c%c%c%c [%c%c%c%c]"
+ " [1.513.1] %s : Failed to create HDRProcessorImpl\n"
+ " [1.513.1] %s : Failed to create sampler for composer"
+ " [1.513.1] %s : Failed with setupInputTexturesWithBL\n"
+ " [1.513.1] %s : Failed with setupOutputTexturesWithBuffer\n"
+ " [1.513.1] %s : HDR error: Failed to create MTLTexture For _metadataTextures[%d][%d]=%p\n"
+ " [1.513.1] %s : Initialization Failed, self = %p\n"
+ " [1.513.1] %s : Initialization Failed, self=%p\n"
+ " [1.513.1] %s : encoder=%p, out of encoder resource"
+ " [1.513.1] %s : error, device = %p, _device=%p\n"
+ " [1.513.1] %s : error, self = %p \n"
+ " [1.513.1] %s : failed with error %d\n"
+ " [1.513.1] %s : format (%d) %c%c%c%c [%c%c%c%c]is not supported yet\n"
+ " [1.513.1] %s : layer0=%p, layer1=%p, output=%p, metatdata=%p"
+ " [1.513.1] %s : unknown HDRProcessing hw type %d, switching to GPU"
+ " [1.513.1] %s: EDRMetaData_RBSP error ext_block_len[%u] > 256, bail!\n"
+ " [1.513.1] %s: EDRMetaData_RBSP error in ext_content_adaptive_metadata, EXT_BLOCK_PAYLOAD, bail!\n"
+ " [1.513.1] %s: EDRMetaData_RBSP error in ext_content_adaptive_metadata, EXT_BLOCK_PAYLOAD2, bail!\n"
+ " [1.513.1] %s: EDRMetaData_RBSP error in vdr_dm_data_payload, bail!\n"
+ " [1.513.1] %s: EDRMetaData_RBSP error level=%d, length=%d: invalid!"
+ " [1.513.1] %s: EDRMetaData_RBSP error map_idc = %d, bail!\n"
+ " [1.513.1] %s: EDRMetaData_RBSP error nal_unit_type = %d, bail!\n"
+ " [1.513.1] %s: EDRMetaData_RBSP error num_blocks_payload2[%d] + num_ext_blocks[%d] > 255, bail!\n"
+ " [1.513.1] %s: EDRMetaData_RBSP error num_ext_blocks = %d > 254, bail!\n"
+ " [1.513.1] %s: EDRMetaData_RBSP error remaining_bits[%lu] < length[%u], bail!\n"
+ " [1.513.1] %s: EDRMetaData_RBSP error reserved_zero_3bits=1, first frame, bail!\n"
+ " [1.513.1] %s: EDRMetaData_RBSP error rpu_type = %d, bail!\n"
+ " [1.513.1] %s: EDRMetaData_RBSP error signal_bit_depth = %d, bail!\n"
+ " [1.513.1] %s: EDRMetaData_RBSP error vdr_rpu_level = %d, nlq_num_pivots_minus2 = %d, bail!\n"
+ " [1.513.1] %s: EDRMetaData_RBSP error vdr_rpu_level = %d, num_x_partitions_minus1 = %d, bail!\n"
+ " [1.513.1] %s: EDRMetaData_RBSP error vdr_rpu_level = %d, num_y_partitions_minus1 = %d, bail!\n"
+ " [1.513.1] %s: ERROR: Out of bound! curr_part_idx = %d, y = %d, x = %d, bail!\n"
+ " [1.513.1] %s: ERROR: Out of bound! mapping_chroma_format_idc = %d, bail!\n"
+ " [1.513.1] %s: ERROR: Out of bound! mmr_order_minus1 = %d, bail!\n"
+ " [1.513.1] %s: ERROR: Out of bound! poly_order_minus1 = %d, bail!\n"
+ " [1.513.1] %s: ERROR: Out of bound! vdr_rpu_level = %d, num_pivots_minus2[%d] = %d, bail!\n"
+ " [1.513.1] %s: calloc failed!\n"
+ " [1.513.1] %s: input=%p, options=%p, configCallback=%p"
+ " [1.513.1] %s: parsing error remaining_bits = %d, bail!\n"
+ " [1.513.1] %s: parsing error, bail!\n"
+ " [1.513.1] %s: parsing error: first_byte = %u [legal value = 4 or 181], bail!\n"
+ " [1.513.1] %s: parsing error: num_bezier_curve_anchors = %d, bail!\n"
+ " [1.513.1] %s: parsing error: num_distributions = %d [legal value = 9], bail!\n"
+ " [1.513.1] %s: parsing error: num_windows = %d [legal value = 1], bail!\n"
+ " [1.513.1] %s: parsing error: sei_payload_type = %u [legal value = 4], sei_payload_length = %u, actual seiLength = %u, bail!\n"
+ " [1.513.1] %s: syntax error: application_identifier = %d"
+ " [1.513.1] %s: syntax error: application_version = %d"
+ " [1.513.1] %s: syntax error: average_maxrgb = %08x"
+ " [1.513.1] %s: syntax error: color_saturation_mapping_flag = %d"
+ " [1.513.1] %s: syntax error: distribution_index[%d]:%d != k_distribution_index[%d]:%d"
+ " [1.513.1] %s: syntax error: distribution_values[%d] = %08x"
+ " [1.513.1] %s: syntax error: itu_t_t35_country_code = %02x"
+ " [1.513.1] %s: syntax error: itu_t_t35_terminal_provider_code = %04x"
+ " [1.513.1] %s: syntax error: itu_t_t35_terminal_provider_oriented_code = %d"
+ " [1.513.1] %s: syntax error: mastering_display_actual_peak_luminance_flag = %d"
+ " [1.513.1] %s: syntax error: maxscl[%d] = %08x"
+ " [1.513.1] %s: syntax error: targeted_system_display_actual_peak_luminance_flag = %d"
+ " [1.513.1] %s: warning: fraction_bright_pixels = %d"
+ " [1.513.1] ++ %s : MSR created! instance=%p, platform=0x%x\n"
+ " [1.513.1] ++ %s : instance=%p _composer=%p _msr=%p"
+ " [1.513.1] ++ %s: MSRApiVer=%d\n"
+ " [1.513.1] -- %s : Failed with error %d, _numberOfScheduledFrames=%ld\n"
+ " [1.513.1] -- %s: HDRProcessor exit! instance=%p\n"
+ " [1.513.1] -- %s: MSR exit! instance=%p\n"
+ " [1.513.1] --------------------------------------------------------\n"
+ " [1.513.1] -----------------------------------------------------------------------------------\n"
+ " [1.513.1] <<smpte_st_2094_50:dbg>> warning: Failed to parse SMPTE ST 2094-50 metadata, error=%d"
+ " [1.513.1] Assertion: \"!_hist\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/hist_based_tone_mapping.mm\" at line 308\n"
+ " [1.513.1] Assertion: \"!inputP422\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1814\n"
+ " [1.513.1] Assertion: \"!inputP422\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1988\n"
+ " [1.513.1] Assertion: \"!ptvMode\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 3613\n"
+ " [1.513.1] Assertion: \"(msrHC->operation == ((HDRProcessingOperation)(kHDRProcessingReshape | kHDRProcessingToneMap)))\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 3019\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1228\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1379\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1406\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1439\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 477\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 860\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1818\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1821\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1827\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1983\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1998\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2002\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2005\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2011\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2020\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/SpatialResampler.m\" at line 212\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/SpatialResampler.m\" at line 243\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 3441\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 3539\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 3778\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 4859\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 5119\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6803\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6833\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 2653\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 4266\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/MetaPacket/DolbyVisionHDMIPacket.mm\" at line 619\n"
+ " [1.513.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/MetaPacket/DolbyVisionHDMIPacket.mm\" at line 678\n"
+ " [1.513.1] Assertion: \"HDR10OnHDR10TV || DolbyOnHDR10TV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2032\n"
+ " [1.513.1] Assertion: \"HLGOnHDR10TV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1804\n"
+ " [1.513.1] Assertion: \"_currentPolynomialTable\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2027\n"
+ " [1.513.1] Assertion: \"_displayType != kHDRDestinationSDRTV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 2921\n"
+ " [1.513.1] Assertion: \"_hdrMode == kHDRContentDolbyVision\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 1902\n"
+ " [1.513.1] Assertion: \"_hdrMode == kHDRContentDolbyVision\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 1934\n"
+ " [1.513.1] Assertion: \"_metadataVertexBuffer\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 2515\n"
+ " [1.513.1] Assertion: \"_msrHC.processingType == kHDRProcessingTypeConvert\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 785\n"
+ " [1.513.1] Assertion: \"_vertsBuffer\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 2476\n"
+ " [1.513.1] Assertion: \"bufferT && bufferS\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 2640\n"
+ " [1.513.1] Assertion: \"bufferT && bufferS\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 2688\n"
+ " [1.513.1] Assertion: \"chromaPixelFormat != MTLPixelFormatInvalid\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 3874\n"
+ " [1.513.1] Assertion: \"cmp != 0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingByCapabilities.mm\" at line 328\n"
+ " [1.513.1] Assertion: \"cmp != 0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingT2.mm\" at line 185\n"
+ " [1.513.1] Assertion: \"dm_config_ptr->dmVersion == 4\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 3040\n"
+ " [1.513.1] Assertion: \"hasThreeOutputPlane || has10BitOutput\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1181\n"
+ " [1.513.1] Assertion: \"hdrCtrl->colourPrimaries == kIOSurfaceTagColorPrimaries_ITU_R_2020\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6950\n"
+ " [1.513.1] Assertion: \"hdrCtrl->colourPrimaries == kIOSurfaceTagColorPrimaries_ITU_R_709_2\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 8656\n"
+ " [1.513.1] Assertion: \"hdrCtrl->displayPipelineCompensationType != kDisplayPipelineCompensationTypeNoneHeadrooomDependent && hdrCtrl->displayPipelineCompensationType != kDisplayPipelineCompensationTypeHeadroomDependent\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6070\n"
+ " [1.513.1] Assertion: \"hdrCtrl->transferFunction != kIOSurfaceTagColorTransferFunction_ITU_R_2100_HLG\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Engine/ProcessingEngine.mm\" at line 356\n"
+ " [1.513.1] Assertion: \"hdrCtrl->transferFunction != kIOSurfaceTagColorTransferFunction_ITU_R_2100_HLG\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2225\n"
+ " [1.513.1] Assertion: \"isConversionInputRgb(msrHC) || isConversionInputYuv(msrHC) || isConversionInputIpt(msrHC)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2994\n"
+ " [1.513.1] Assertion: \"isConversionOutputYuv(msrHC)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 5539\n"
+ " [1.513.1] Assertion: \"isGPUtoHDR10TV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 1460\n"
+ " [1.513.1] Assertion: \"isTonemappingEnabled(msrHC)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 4562\n"
+ " [1.513.1] Assertion: \"metadata->mapping_idc[0][0][cmp][0] == 0 || metadata->mapping_idc[0][0][cmp][0] == 1\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingByCapabilities.mm\" at line 313\n"
+ " [1.513.1] Assertion: \"metadata->mapping_idc[0][0][cmp][0] == 0 || metadata->mapping_idc[0][0][cmp][0] == 1\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingT2.mm\" at line 170\n"
+ " [1.513.1] Assertion: \"mid_tap_h >= 4 && mid_tap_v >= 1\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 252\n"
+ " [1.513.1] Assertion: \"msrHC->enableConverting && !msrHC->enableToneMapping\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2993\n"
+ " [1.513.1] Assertion: \"msrHC->processingType == kHDRProcessingTypeDoVi || msrHC->processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 4608\n"
+ " [1.513.1] Assertion: \"msrHC->processingType == kHDRProcessingTypeDoVi || msrHC->processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 5161\n"
+ " [1.513.1] Assertion: \"overrideHLGOOTFMixingStartTdivNits >= 100.0f\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/dovi_display_management_host.mm\" at line 717\n"
+ " [1.513.1] Assertion: \"overrideHLGOOTFMixingStartTdivNits >= 100.0f\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/hlg_display_management_host.mm\" at line 121\n"
+ " [1.513.1] Assertion: \"polyBuf && mmrCoefBuf\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingByCapabilities.mm\" at line 310\n"
+ " [1.513.1] Assertion: \"polyBuf && mmrCoefBuf\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingT2.mm\" at line 167\n"
+ " [1.513.1] Assertion: \"processingType == kHDRProcessingTypeDoVi || processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Engine/ProcessingEngine.mm\" at line 370\n"
+ " [1.513.1] Assertion: \"processingType == kHDRProcessingTypeDoVi || processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Engine/ProcessingEngine.mm\" at line 425\n"
+ " [1.513.1] Assertion: \"processingType == kHDRProcessingTypeDoVi || processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2228\n"
+ " [1.513.1] Assertion: \"retVal == 0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 4500\n"
+ " [1.513.1] Assertion: \"sMaxPq <= L2PqNorm(4000)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 7468\n"
+ " [1.513.1] Assertion: \"sMinPq >= L2PqNorm(0.005)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 7469\n"
+ " [1.513.1] Assertion: \"sdrOnDolbyOrHDR10 == __objc_no\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1775\n"
+ " [1.513.1] Assertion: \"sdrOnDolbyOrHDR10 == __objc_no\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1782\n"
+ " [1.513.1] Assertion: \"tableSize == 1024\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/common_display_management_host.mm\" at line 3730\n"
+ " [1.513.1] Assertion: \"y1 == y2\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 2613\n"
+ " [1.513.1] Constraint changed to: %s"
+ " [1.513.1] Constraint: #=%d F=%d C=%d T=%d NP=%d(%2.4f - %2.4f)"
+ " [1.513.1] Constraint: %s"
+ " [1.513.1] ContentType: %s, sr=%d"
+ " [1.513.1] HDRConfig: Frame #%d: configDumpStyle = %d (%s), configDumpLevel = %d, configDumpFlag = %d\n"
+ " [1.513.1] Incorrect mode usage : %d _hdrMode = %d"
+ " [1.513.1] MR81: Error: BuildInterpInfo TrimLevel must be 8"
+ " [1.513.1] MR81: Error: BuildLumaXInfo trimNum=0"
+ " [1.513.1] MR81: Error: GetMdsExtMr mr->mdsBase.mdsLen < 71"
+ " [1.513.1] MR81: Error: GetRgb2XyzM33, unsupported rgbDef:%d"
+ " [1.513.1] MR81: Error: InterpL2 MDSEXT_HAVE_LVL_L0 is false"
+ " [1.513.1] MR81: Error: InterpL8 MDSEXT_HAVE_LVL_L0 is false"
+ " [1.513.1] MR81: Error: MrGetMdsExtFxpMr extLen < 0"
+ " [1.513.1] MR81: Error: MrGetMdsExtFxpMr mdsLen < 0"
+ " [1.513.1] MR81: Error: PrepareL2 MDSEXT_HAVE_LVL_L0 is false"
+ " [1.513.1] MR81: Error: PrepareL8 MDSEXT_HAVE_LVL_L0 is false"
+ " [1.513.1] MR81: metadataReconstruction: Error: GetMdsExtFxpMr ret = %d"
+ " [1.513.1] MR81: metadataReconstruction: Error: ParseMds ret = %d"
+ " [1.513.1] MR81: metadataReconstruction: Error: ret = %d"
+ " [1.513.1] MR81: metadataReconstruction: Error: unmapped, hasMMRData=%d"
+ " [1.513.1] MR81: metadataReconstruction: Warning: GetMdsExtFxpMr ret = %d [no change]"
+ " [1.513.1] MR81: metadataReconstruction: Warning: RGBtoLMS_coef [%d][%d] changed, %d/%d"
+ " [1.513.1] MR81: metadataReconstruction: Warning: YCCtoRGB_coef [%d][%d] changed, %d/%d"
+ " [1.513.1] MR81: metadataReconstruction: Warning: YCCtoRGB_offset[%d] changed, %u/%u"
+ " [1.513.1] MR81: metadataReconstruction: Warning: ret = %d [no change]"
+ " [1.513.1] Memory allocation for  histBinCentroidInLinear failed"
+ " [1.513.1] Memory allocation for _cdf failed"
+ " [1.513.1] Memory allocation for _fullRangeBinIdx8bit failed"
+ " [1.513.1] Memory allocation for _histBinMlmInPQ failed"
+ " [1.513.1] Memory allocation for _sdrHdrMlmLut_x failed"
+ " [1.513.1] Memory allocation for _sdrHdrMlmLut_y failed"
+ " [1.513.1] Memory allocation for avgValBuffer failed"
+ " [1.513.1] Memory allocation for fullRangeBinIdx failed"
+ " [1.513.1] Memory allocation for histBinCenter failed"
+ " [1.513.1] Memory allocation for histBuff failed"
+ " [1.513.1] Memory allocation for hlgBinCenterInPQ failed"
+ " [1.513.1] Memory allocation for maxValBuffer failed"
+ " [1.513.1] Memory allocation for minValBuffer failed"
+ " [1.513.1] Memory allocation for normHist failed"
+ " [1.513.1] Memory allocation for pcntVal failed"
+ " [1.513.1] Memory allocation for pqBinCenterInPQ failed"
+ " [1.513.1] Memory allocation for prctVal failed"
+ " [1.513.1] Memory allocation for prctValBuffer failed"
+ " [1.513.1] Memory allocation for prctValBuffer[i] failed"
+ " [1.513.1] Memory allocation for prevNormHistHeight failed"
+ " [1.513.1] Memory allocation for sdrBinCenterInPQ failed"
+ " [1.513.1] Memory allocation for stdValBuffer failed"
+ " [1.513.1] Memory allocation for targetMaxBuffer failed"
+ " [1.513.1] Memory allocation for testpatchHistBuff failed"
+ " [1.513.1] Not supported type=%d\n"
+ " [1.513.1] ToneMapLUT_xsamples memory allocation failed!"
+ " [1.513.1] ToneMapLUT_ysamples memory allocation failed!"
+ " [1.513.1] ToneMapMixFactorLUT_xsamples memory allocation failed!"
+ " [1.513.1] ToneMapMixFactorLUT_ysamples memory allocation failed!"
+ " [1.513.1] WARNING: calcCubicSplineParam: delta == 0"
+ " [1.513.1] WARNING: cubicSplineInterp: delta == 0"
+ " [1.513.1] Warning: Attempting to read defaults writes in release builds! key = \"%@\"\n"
+ " [1.513.1] [frame_%llu] scheduled2completed: avg: %5.1f, max: %5.1f [in ms], [ %d : %d ]\n"
+ " [1.513.1] _width=%d, _targetWidth=%d, _height=%d, _targetHeight=%d"
+ " [1.513.1] checkInputOutputIOSurface() failed!"
+ " [1.513.1] commanBuffer=%p, output=%p, input=%p, ui=%p"
+ " [1.513.1] failed due to metalDevice change!"
+ " [1.513.1] hcr : %s"
+ " [1.513.1] hcr changes to: %s"
+ " [1.513.1] hcrUseSystemBrightnessForCaptureContent : %s"
+ " [1.513.1] hcrUseSystemBrightnessForCaptureContent changes to: %s"
+ " [1.513.1] hcrUseSystemBrightnessForProContent : %s"
+ " [1.513.1] hcrUseSystemBrightnessForProContent changes to: %s"
+ " [1.513.1] hdrMaxBrightnessInNits was forced to %f!"
+ " [1.513.1] sdrMaxBrightnessInNits was forced to %f!"
- " [1.512.1] \n"
- " [1.512.1]      No entries to dump!\n"
- " [1.512.1]     %s : Error: Unsupported config! retVal = %d"
- " [1.512.1]     %s : Warning: after md reduction, payLoadLength=%d, max packet size=%d"
- " [1.512.1]     %s : error max=%f <= min=%f, metaData=%p"
- " [1.512.1]     %s: illegal HDR10Plus SEI, fall back to HDR10"
- " [1.512.1]     %s: illegal SEI"
- " [1.512.1]     %s: input=%p"
- " [1.512.1]     %s: layer0=%p, output=%p, metatdata=%p, config=%p, histogram=%p"
- " [1.512.1]     %s: metatdata= %p, bailout!!!\n"
- " [1.512.1]     %s: missing SEI"
- " [1.512.1]     %s: output=%p, bailout!!!\n"
- " [1.512.1]     ERROR: Not supported operation %d !!!"
- " [1.512.1]    %s : Error: Unsupported MSR input: operation=0x%x, input=%c%c%c%c [%c%c%c%c], output=%c%c%c%c [%c%c%c%c]"
- " [1.512.1]    %s : Failed to create directory \"%s\".\n"
- " [1.512.1]    %s : failed with error %ld\n"
- " [1.512.1]    %s : instance=%p"
- " [1.512.1]    %s : instance=%p\n"
- " [1.512.1]    %s : invalid dump dir[%p] length"
- " [1.512.1]    %s : metalDevice has changed!\n"
- " [1.512.1]    %s : processor=%p\n"
- " [1.512.1]    %s: ERROR: Failed to allocate memory! size = %lu bytes"
- " [1.512.1]   !isMultipleOf2(region.origin.x=%d)"
- " [1.512.1]   !isMultipleOf2(region.size.width=%d)"
- " [1.512.1]   commanBuffer=%p, output=%p, input=%p ui=%p"
- " [1.512.1]   region.origin.x=%d + region.size.width=%d > texWidth=%d"
- " [1.512.1]   region.origin.x=%d >= texWidth=%d && region.origin.y=%d >= texHeight=%d"
- " [1.512.1]   region.origin.y=%d + region.size.height=%d > texHeight=%d"
- " [1.512.1]   videoSrcWidth=%d, videoSrcHeight=%d, dstWidth=%d, dstHeight=%d"
- " [1.512.1]   warning: unknown matrix_coeffs=%d, sets to Rec709=%d"
- " [1.512.1]   warning: unknown transfer_characteristics=%d, sets to PQ=%d"
- " [1.512.1]  %30@: %-12s\n"
- " [1.512.1]  %30@: %-12s    (value=%s, default=%s)\n"
- " [1.512.1]  %30s %12s\n"
- " [1.512.1]  %8d %30@ %12s %12s %12s\n"
- " [1.512.1]  %8s %30s %12s %12s %12s\n"
- " [1.512.1]  %s : Not supported type=%d\n"
- " [1.512.1]  %s : newprocessor=%p\n"
- " [1.512.1]  %s:%d: ERROR: Neither value nor defaults value is available! Key = \"%@\".\n"
- " [1.512.1] #%04llx \n"
- " [1.512.1] #%04llx      No entries to dump!\n"
- " [1.512.1] #%04llx     %s : Error: Unsupported config! retVal = %d"
- " [1.512.1] #%04llx     %s : Warning: after md reduction, payLoadLength=%d, max packet size=%d"
- " [1.512.1] #%04llx     %s : error max=%f <= min=%f, metaData=%p"
- " [1.512.1] #%04llx     %s: illegal HDR10Plus SEI, fall back to HDR10"
- " [1.512.1] #%04llx     %s: illegal SEI"
- " [1.512.1] #%04llx     %s: input=%p"
- " [1.512.1] #%04llx     %s: layer0=%p, output=%p, metatdata=%p, config=%p, histogram=%p"
- " [1.512.1] #%04llx     %s: metatdata= %p, bailout!!!\n"
- " [1.512.1] #%04llx     %s: missing SEI"
- " [1.512.1] #%04llx     %s: output=%p, bailout!!!\n"
- " [1.512.1] #%04llx     ERROR: Not supported operation %d !!!"
- " [1.512.1] #%04llx    %s : Error: Unsupported MSR input: operation=0x%x, input=%c%c%c%c [%c%c%c%c], output=%c%c%c%c [%c%c%c%c]"
- " [1.512.1] #%04llx    %s : Failed to create directory \"%s\".\n"
- " [1.512.1] #%04llx    %s : failed with error %ld\n"
- " [1.512.1] #%04llx    %s : instance=%p"
- " [1.512.1] #%04llx    %s : instance=%p\n"
- " [1.512.1] #%04llx    %s : invalid dump dir[%p] length"
- " [1.512.1] #%04llx    %s : metalDevice has changed!\n"
- " [1.512.1] #%04llx    %s : processor=%p\n"
- " [1.512.1] #%04llx    %s: ERROR: Failed to allocate memory! size = %lu bytes"
- " [1.512.1] #%04llx   !isMultipleOf2(region.origin.x=%d)"
- " [1.512.1] #%04llx   !isMultipleOf2(region.size.width=%d)"
- " [1.512.1] #%04llx   commanBuffer=%p, output=%p, input=%p ui=%p"
- " [1.512.1] #%04llx   region.origin.x=%d + region.size.width=%d > texWidth=%d"
- " [1.512.1] #%04llx   region.origin.x=%d >= texWidth=%d && region.origin.y=%d >= texHeight=%d"
- " [1.512.1] #%04llx   region.origin.y=%d + region.size.height=%d > texHeight=%d"
- " [1.512.1] #%04llx   videoSrcWidth=%d, videoSrcHeight=%d, dstWidth=%d, dstHeight=%d"
- " [1.512.1] #%04llx   warning: unknown matrix_coeffs=%d, sets to Rec709=%d"
- " [1.512.1] #%04llx   warning: unknown transfer_characteristics=%d, sets to PQ=%d"
- " [1.512.1] #%04llx  %30@: %-12s\n"
- " [1.512.1] #%04llx  %30@: %-12s    (value=%s, default=%s)\n"
- " [1.512.1] #%04llx  %30s %12s\n"
- " [1.512.1] #%04llx  %8d %30@ %12s %12s %12s\n"
- " [1.512.1] #%04llx  %8s %30s %12s %12s %12s\n"
- " [1.512.1] #%04llx  %s : Not supported type=%d\n"
- " [1.512.1] #%04llx  %s : newprocessor=%p\n"
- " [1.512.1] #%04llx  %s:%d: ERROR: Neither value nor defaults value is available! Key = \"%@\".\n"
- " [1.512.1] #%04llx %s : ERROR: Failed creating a new fragment function: %@ with error: %@"
- " [1.512.1] #%04llx %s : ERROR: Failed creating a new function with _useCustomMatrix=%d, _p3CSC=%d, _applyYGamma=%d"
- " [1.512.1] #%04llx %s : ERROR: Failed creating a new function with dolby84=%d, forLLDoVi=%d input=%d output=%d"
- " [1.512.1] #%04llx %s : ERROR: Failed creating a new function: %@"
- " [1.512.1] #%04llx %s : ERROR: Failed creating a new function: %@ with error: %@"
- " [1.512.1] #%04llx %s : ERROR: Failed creating a new vertex function: %@ with error: %@"
- " [1.512.1] #%04llx %s : ERROR: Failed to create backward DM Kernel: fragment[%p]=%@, vertex[%p]=%@, with error: %@"
- " [1.512.1] #%04llx %s : ERROR: Failed to create forward DM Kernel: %@ with error: %@"
- " [1.512.1] #%04llx %s : Error: Unsupported DoVi81 state: _hdrMode = %d, _displayType = %d, hasRPUData = %d, hasHDR10PlusSEIData = %d"
- " [1.512.1] #%04llx %s : Error: Unsupported input: operation=0x%x, input=%c%c%c%c [%c%c%c%c]"
- " [1.512.1] #%04llx %s : Failed to create HDRProcessorImpl\n"
- " [1.512.1] #%04llx %s : Failed to create sampler for composer"
- " [1.512.1] #%04llx %s : Failed with setupInputTexturesWithBL\n"
- " [1.512.1] #%04llx %s : Failed with setupOutputTexturesWithBuffer\n"
- " [1.512.1] #%04llx %s : HDR error: Failed to create MTLTexture For _metadataTextures[%d][%d]=%p\n"
- " [1.512.1] #%04llx %s : Initialization Failed, self = %p\n"
- " [1.512.1] #%04llx %s : Initialization Failed, self=%p\n"
- " [1.512.1] #%04llx %s : encoder=%p, out of encoder resource"
- " [1.512.1] #%04llx %s : error, device = %p, _device=%p\n"
- " [1.512.1] #%04llx %s : error, self = %p \n"
- " [1.512.1] #%04llx %s : failed with error %d\n"
- " [1.512.1] #%04llx %s : format (%d) %c%c%c%c [%c%c%c%c]is not supported yet\n"
- " [1.512.1] #%04llx %s : layer0=%p, layer1=%p, output=%p, metatdata=%p"
- " [1.512.1] #%04llx %s : unknown HDRProcessing hw type %d, switching to GPU"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error ext_block_len[%u] > 256, bail!\n"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error in ext_content_adaptive_metadata, EXT_BLOCK_PAYLOAD, bail!\n"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error in ext_content_adaptive_metadata, EXT_BLOCK_PAYLOAD2, bail!\n"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error in vdr_dm_data_payload, bail!\n"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error level=%d, length=%d: invalid!"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error map_idc = %d, bail!\n"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error nal_unit_type = %d, bail!\n"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error num_blocks_payload2[%d] + num_ext_blocks[%d] > 255, bail!\n"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error num_ext_blocks = %d > 254, bail!\n"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error remaining_bits[%lu] < length[%u], bail!\n"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error reserved_zero_3bits=1, first frame, bail!\n"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error rpu_type = %d, bail!\n"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error signal_bit_depth = %d, bail!\n"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error vdr_rpu_level = %d, nlq_num_pivots_minus2 = %d, bail!\n"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error vdr_rpu_level = %d, num_x_partitions_minus1 = %d, bail!\n"
- " [1.512.1] #%04llx %s: EDRMetaData_RBSP error vdr_rpu_level = %d, num_y_partitions_minus1 = %d, bail!\n"
- " [1.512.1] #%04llx %s: ERROR: Out of bound! curr_part_idx = %d, y = %d, x = %d, bail!\n"
- " [1.512.1] #%04llx %s: ERROR: Out of bound! mapping_chroma_format_idc = %d, bail!\n"
- " [1.512.1] #%04llx %s: ERROR: Out of bound! mmr_order_minus1 = %d, bail!\n"
- " [1.512.1] #%04llx %s: ERROR: Out of bound! poly_order_minus1 = %d, bail!\n"
- " [1.512.1] #%04llx %s: ERROR: Out of bound! vdr_rpu_level = %d, num_pivots_minus2[%d] = %d, bail!\n"
- " [1.512.1] #%04llx %s: calloc failed!\n"
- " [1.512.1] #%04llx %s: input=%p, options=%p, configCallback=%p"
- " [1.512.1] #%04llx %s: parsing error remaining_bits = %d, bail!\n"
- " [1.512.1] #%04llx %s: parsing error, bail!\n"
- " [1.512.1] #%04llx %s: parsing error: first_byte = %u [legal value = 4 or 181], bail!\n"
- " [1.512.1] #%04llx %s: parsing error: num_bezier_curve_anchors = %d, bail!\n"
- " [1.512.1] #%04llx %s: parsing error: num_distributions = %d [legal value = 9], bail!\n"
- " [1.512.1] #%04llx %s: parsing error: num_windows = %d [legal value = 1], bail!\n"
- " [1.512.1] #%04llx %s: parsing error: sei_payload_type = %u [legal value = 4], sei_payload_length = %u, actual seiLength = %u, bail!\n"
- " [1.512.1] #%04llx %s: syntax error: application_identifier = %d"
- " [1.512.1] #%04llx %s: syntax error: application_version = %d"
- " [1.512.1] #%04llx %s: syntax error: average_maxrgb = %08x"
- " [1.512.1] #%04llx %s: syntax error: color_saturation_mapping_flag = %d"
- " [1.512.1] #%04llx %s: syntax error: distribution_index[%d]:%d != k_distribution_index[%d]:%d"
- " [1.512.1] #%04llx %s: syntax error: distribution_values[%d] = %08x"
- " [1.512.1] #%04llx %s: syntax error: itu_t_t35_country_code = %02x"
- " [1.512.1] #%04llx %s: syntax error: itu_t_t35_terminal_provider_code = %04x"
- " [1.512.1] #%04llx %s: syntax error: itu_t_t35_terminal_provider_oriented_code = %d"
- " [1.512.1] #%04llx %s: syntax error: mastering_display_actual_peak_luminance_flag = %d"
- " [1.512.1] #%04llx %s: syntax error: maxscl[%d] = %08x"
- " [1.512.1] #%04llx %s: syntax error: targeted_system_display_actual_peak_luminance_flag = %d"
- " [1.512.1] #%04llx %s: warning: fraction_bright_pixels = %d"
- " [1.512.1] #%04llx ++ %s : MSR created! instance=%p, platform=0x%x\n"
- " [1.512.1] #%04llx ++ %s : instance=%p _composer=%p _msr=%p"
- " [1.512.1] #%04llx ++ %s: MSRApiVer=%d\n"
- " [1.512.1] #%04llx -- %s : Failed with error %d, _numberOfScheduledFrames=%ld\n"
- " [1.512.1] #%04llx -- %s: HDRProcessor exit! instance=%p\n"
- " [1.512.1] #%04llx -- %s: MSR exit! instance=%p\n"
- " [1.512.1] #%04llx --------------------------------------------------------\n"
- " [1.512.1] #%04llx -----------------------------------------------------------------------------------\n"
- " [1.512.1] #%04llx <<smpte_st_2094_50:dbg>> warning: Failed to parse SMPTE ST 2094-50 metadata, error=%d"
- " [1.512.1] #%04llx Assertion: \"!_hist\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/hist_based_tone_mapping.mm\" at line 308\n"
- " [1.512.1] #%04llx Assertion: \"!inputP422\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1814\n"
- " [1.512.1] #%04llx Assertion: \"!inputP422\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1988\n"
- " [1.512.1] #%04llx Assertion: \"!ptvMode\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 3613\n"
- " [1.512.1] #%04llx Assertion: \"(msrHC->operation == ((HDRProcessingOperation)(kHDRProcessingReshape | kHDRProcessingToneMap)))\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 3019\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1228\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1379\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1406\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1439\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 477\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 860\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1818\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1821\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1827\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1983\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1998\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2002\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2005\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2011\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2020\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/SpatialResampler.m\" at line 212\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/SpatialResampler.m\" at line 243\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 3441\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 3539\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 3778\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 4859\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 5119\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6803\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6833\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 2641\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 4254\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/MetaPacket/DolbyVisionHDMIPacket.mm\" at line 619\n"
- " [1.512.1] #%04llx Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/MetaPacket/DolbyVisionHDMIPacket.mm\" at line 678\n"
- " [1.512.1] #%04llx Assertion: \"HDR10OnHDR10TV || DolbyOnHDR10TV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2032\n"
- " [1.512.1] #%04llx Assertion: \"HLGOnHDR10TV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1804\n"
- " [1.512.1] #%04llx Assertion: \"_currentPolynomialTable\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2027\n"
- " [1.512.1] #%04llx Assertion: \"_displayType != kHDRDestinationSDRTV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 2921\n"
- " [1.512.1] #%04llx Assertion: \"_hdrMode == kHDRContentDolbyVision\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 1890\n"
- " [1.512.1] #%04llx Assertion: \"_hdrMode == kHDRContentDolbyVision\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 1922\n"
- " [1.512.1] #%04llx Assertion: \"_metadataVertexBuffer\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 2515\n"
- " [1.512.1] #%04llx Assertion: \"_msrHC.processingType == kHDRProcessingTypeConvert\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 785\n"
- " [1.512.1] #%04llx Assertion: \"_vertsBuffer\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 2476\n"
- " [1.512.1] #%04llx Assertion: \"bufferT && bufferS\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 2640\n"
- " [1.512.1] #%04llx Assertion: \"bufferT && bufferS\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 2688\n"
- " [1.512.1] #%04llx Assertion: \"chromaPixelFormat != MTLPixelFormatInvalid\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 3874\n"
- " [1.512.1] #%04llx Assertion: \"cmp != 0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingByCapabilities.mm\" at line 328\n"
- " [1.512.1] #%04llx Assertion: \"cmp != 0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingT2.mm\" at line 185\n"
- " [1.512.1] #%04llx Assertion: \"dm_config_ptr->dmVersion == 4\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 3040\n"
- " [1.512.1] #%04llx Assertion: \"hasThreeOutputPlane || has10BitOutput\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1181\n"
- " [1.512.1] #%04llx Assertion: \"hdrCtrl->colourPrimaries == kIOSurfaceTagColorPrimaries_ITU_R_2020\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6950\n"
- " [1.512.1] #%04llx Assertion: \"hdrCtrl->colourPrimaries == kIOSurfaceTagColorPrimaries_ITU_R_709_2\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 8656\n"
- " [1.512.1] #%04llx Assertion: \"hdrCtrl->displayPipelineCompensationType != kDisplayPipelineCompensationTypeNoneHeadrooomDependent && hdrCtrl->displayPipelineCompensationType != kDisplayPipelineCompensationTypeHeadroomDependent\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6070\n"
- " [1.512.1] #%04llx Assertion: \"hdrCtrl->transferFunction != kIOSurfaceTagColorTransferFunction_ITU_R_2100_HLG\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Engine/ProcessingEngine.mm\" at line 356\n"
- " [1.512.1] #%04llx Assertion: \"hdrCtrl->transferFunction != kIOSurfaceTagColorTransferFunction_ITU_R_2100_HLG\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2225\n"
- " [1.512.1] #%04llx Assertion: \"isConversionInputRgb(msrHC) || isConversionInputYuv(msrHC) || isConversionInputIpt(msrHC)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2994\n"
- " [1.512.1] #%04llx Assertion: \"isConversionOutputYuv(msrHC)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 5539\n"
- " [1.512.1] #%04llx Assertion: \"isGPUtoHDR10TV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 1460\n"
- " [1.512.1] #%04llx Assertion: \"isTonemappingEnabled(msrHC)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 4562\n"
- " [1.512.1] #%04llx Assertion: \"metadata->mapping_idc[0][0][cmp][0] == 0 || metadata->mapping_idc[0][0][cmp][0] == 1\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingByCapabilities.mm\" at line 313\n"
- " [1.512.1] #%04llx Assertion: \"metadata->mapping_idc[0][0][cmp][0] == 0 || metadata->mapping_idc[0][0][cmp][0] == 1\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingT2.mm\" at line 170\n"
- " [1.512.1] #%04llx Assertion: \"mid_tap_h >= 4 && mid_tap_v >= 1\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 252\n"
- " [1.512.1] #%04llx Assertion: \"msrHC->enableConverting && !msrHC->enableToneMapping\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2993\n"
- " [1.512.1] #%04llx Assertion: \"msrHC->processingType == kHDRProcessingTypeDoVi || msrHC->processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 4608\n"
- " [1.512.1] #%04llx Assertion: \"msrHC->processingType == kHDRProcessingTypeDoVi || msrHC->processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 5161\n"
- " [1.512.1] #%04llx Assertion: \"overrideHLGOOTFMixingStartTdivNits >= 100.0f\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/dovi_display_management_host.mm\" at line 717\n"
- " [1.512.1] #%04llx Assertion: \"overrideHLGOOTFMixingStartTdivNits >= 100.0f\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/hlg_display_management_host.mm\" at line 121\n"
- " [1.512.1] #%04llx Assertion: \"polyBuf && mmrCoefBuf\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingByCapabilities.mm\" at line 310\n"
- " [1.512.1] #%04llx Assertion: \"polyBuf && mmrCoefBuf\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingT2.mm\" at line 167\n"
- " [1.512.1] #%04llx Assertion: \"processingType == kHDRProcessingTypeDoVi || processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Engine/ProcessingEngine.mm\" at line 370\n"
- " [1.512.1] #%04llx Assertion: \"processingType == kHDRProcessingTypeDoVi || processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Engine/ProcessingEngine.mm\" at line 425\n"
- " [1.512.1] #%04llx Assertion: \"processingType == kHDRProcessingTypeDoVi || processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2228\n"
- " [1.512.1] #%04llx Assertion: \"retVal == 0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 4500\n"
- " [1.512.1] #%04llx Assertion: \"sMaxPq <= L2PqNorm(4000)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 7468\n"
- " [1.512.1] #%04llx Assertion: \"sMinPq >= L2PqNorm(0.005)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 7469\n"
- " [1.512.1] #%04llx Assertion: \"sdrOnDolbyOrHDR10 == __objc_no\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1775\n"
- " [1.512.1] #%04llx Assertion: \"sdrOnDolbyOrHDR10 == __objc_no\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1782\n"
- " [1.512.1] #%04llx Assertion: \"tableSize == 1024\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/common_display_management_host.mm\" at line 3730\n"
- " [1.512.1] #%04llx Assertion: \"y1 == y2\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 2613\n"
- " [1.512.1] #%04llx Constraint changed to: %s"
- " [1.512.1] #%04llx Constraint: #=%d F=%d C=%d T=%d NP=%d(%2.4f - %2.4f)"
- " [1.512.1] #%04llx Constraint: %s"
- " [1.512.1] #%04llx ContentType: %s, sr=%d"
- " [1.512.1] #%04llx HDRConfig: Frame #%d: configDumpStyle = %d (%s), configDumpLevel = %d, configDumpFlag = %d\n"
- " [1.512.1] #%04llx Incorrect mode usage : %d _hdrMode = %d"
- " [1.512.1] #%04llx MR81: Error: BuildInterpInfo TrimLevel must be 8"
- " [1.512.1] #%04llx MR81: Error: BuildLumaXInfo trimNum=0"
- " [1.512.1] #%04llx MR81: Error: GetMdsExtMr mr->mdsBase.mdsLen < 71"
- " [1.512.1] #%04llx MR81: Error: GetRgb2XyzM33, unsupported rgbDef:%d"
- " [1.512.1] #%04llx MR81: Error: InterpL2 MDSEXT_HAVE_LVL_L0 is false"
- " [1.512.1] #%04llx MR81: Error: InterpL8 MDSEXT_HAVE_LVL_L0 is false"
- " [1.512.1] #%04llx MR81: Error: MrGetMdsExtFxpMr extLen < 0"
- " [1.512.1] #%04llx MR81: Error: MrGetMdsExtFxpMr mdsLen < 0"
- " [1.512.1] #%04llx MR81: Error: PrepareL2 MDSEXT_HAVE_LVL_L0 is false"
- " [1.512.1] #%04llx MR81: Error: PrepareL8 MDSEXT_HAVE_LVL_L0 is false"
- " [1.512.1] #%04llx MR81: metadataReconstruction: Error: GetMdsExtFxpMr ret = %d"
- " [1.512.1] #%04llx MR81: metadataReconstruction: Error: ParseMds ret = %d"
- " [1.512.1] #%04llx MR81: metadataReconstruction: Error: ret = %d"
- " [1.512.1] #%04llx MR81: metadataReconstruction: Error: unmapped, hasMMRData=%d"
- " [1.512.1] #%04llx MR81: metadataReconstruction: Warning: GetMdsExtFxpMr ret = %d [no change]"
- " [1.512.1] #%04llx MR81: metadataReconstruction: Warning: RGBtoLMS_coef [%d][%d] changed, %d/%d"
- " [1.512.1] #%04llx MR81: metadataReconstruction: Warning: YCCtoRGB_coef [%d][%d] changed, %d/%d"
- " [1.512.1] #%04llx MR81: metadataReconstruction: Warning: YCCtoRGB_offset[%d] changed, %u/%u"
- " [1.512.1] #%04llx MR81: metadataReconstruction: Warning: ret = %d [no change]"
- " [1.512.1] #%04llx Memory allocation for  histBinCentroidInLinear failed"
- " [1.512.1] #%04llx Memory allocation for _cdf failed"
- " [1.512.1] #%04llx Memory allocation for _fullRangeBinIdx8bit failed"
- " [1.512.1] #%04llx Memory allocation for _histBinMlmInPQ failed"
- " [1.512.1] #%04llx Memory allocation for _sdrHdrMlmLut_x failed"
- " [1.512.1] #%04llx Memory allocation for _sdrHdrMlmLut_y failed"
- " [1.512.1] #%04llx Memory allocation for avgValBuffer failed"
- " [1.512.1] #%04llx Memory allocation for fullRangeBinIdx failed"
- " [1.512.1] #%04llx Memory allocation for histBinCenter failed"
- " [1.512.1] #%04llx Memory allocation for histBuff failed"
- " [1.512.1] #%04llx Memory allocation for hlgBinCenterInPQ failed"
- " [1.512.1] #%04llx Memory allocation for maxValBuffer failed"
- " [1.512.1] #%04llx Memory allocation for minValBuffer failed"
- " [1.512.1] #%04llx Memory allocation for normHist failed"
- " [1.512.1] #%04llx Memory allocation for pcntVal failed"
- " [1.512.1] #%04llx Memory allocation for pqBinCenterInPQ failed"
- " [1.512.1] #%04llx Memory allocation for prctVal failed"
- " [1.512.1] #%04llx Memory allocation for prctValBuffer failed"
- " [1.512.1] #%04llx Memory allocation for prctValBuffer[i] failed"
- " [1.512.1] #%04llx Memory allocation for prevNormHistHeight failed"
- " [1.512.1] #%04llx Memory allocation for sdrBinCenterInPQ failed"
- " [1.512.1] #%04llx Memory allocation for stdValBuffer failed"
- " [1.512.1] #%04llx Memory allocation for targetMaxBuffer failed"
- " [1.512.1] #%04llx Memory allocation for testpatchHistBuff failed"
- " [1.512.1] #%04llx Not supported type=%d\n"
- " [1.512.1] #%04llx ToneMapLUT_xsamples memory allocation failed!"
- " [1.512.1] #%04llx ToneMapLUT_ysamples memory allocation failed!"
- " [1.512.1] #%04llx ToneMapMixFactorLUT_xsamples memory allocation failed!"
- " [1.512.1] #%04llx ToneMapMixFactorLUT_ysamples memory allocation failed!"
- " [1.512.1] #%04llx WARNING: calcCubicSplineParam: delta == 0"
- " [1.512.1] #%04llx WARNING: cubicSplineInterp: delta == 0"
- " [1.512.1] #%04llx Warning: Attempting to read defaults writes in release builds! key = \"%@\"\n"
- " [1.512.1] #%04llx [frame_%llu] scheduled2completed: avg: %5.1f, max: %5.1f [in ms], [ %d : %d ]\n"
- " [1.512.1] #%04llx _width=%d, _targetWidth=%d, _height=%d, _targetHeight=%d"
- " [1.512.1] #%04llx checkInputOutputIOSurface() failed!"
- " [1.512.1] #%04llx commanBuffer=%p, output=%p, input=%p, ui=%p"
- " [1.512.1] #%04llx failed due to metalDevice change!"
- " [1.512.1] #%04llx hcr : %s"
- " [1.512.1] #%04llx hcr changes to: %s"
- " [1.512.1] #%04llx hcrUseSystemBrightnessForCaptureContent : %s"
- " [1.512.1] #%04llx hcrUseSystemBrightnessForCaptureContent changes to: %s"
- " [1.512.1] #%04llx hcrUseSystemBrightnessForProContent : %s"
- " [1.512.1] #%04llx hcrUseSystemBrightnessForProContent changes to: %s"
- " [1.512.1] #%04llx hdrMaxBrightnessInNits was forced to %f!"
- " [1.512.1] #%04llx sdrMaxBrightnessInNits was forced to %f!"
- " [1.512.1] %s : ERROR: Failed creating a new fragment function: %@ with error: %@"
- " [1.512.1] %s : ERROR: Failed creating a new function with _useCustomMatrix=%d, _p3CSC=%d, _applyYGamma=%d"
- " [1.512.1] %s : ERROR: Failed creating a new function with dolby84=%d, forLLDoVi=%d input=%d output=%d"
- " [1.512.1] %s : ERROR: Failed creating a new function: %@"
- " [1.512.1] %s : ERROR: Failed creating a new function: %@ with error: %@"
- " [1.512.1] %s : ERROR: Failed creating a new vertex function: %@ with error: %@"
- " [1.512.1] %s : ERROR: Failed to create backward DM Kernel: fragment[%p]=%@, vertex[%p]=%@, with error: %@"
- " [1.512.1] %s : ERROR: Failed to create forward DM Kernel: %@ with error: %@"
- " [1.512.1] %s : Error: Unsupported DoVi81 state: _hdrMode = %d, _displayType = %d, hasRPUData = %d, hasHDR10PlusSEIData = %d"
- " [1.512.1] %s : Error: Unsupported input: operation=0x%x, input=%c%c%c%c [%c%c%c%c]"
- " [1.512.1] %s : Failed to create HDRProcessorImpl\n"
- " [1.512.1] %s : Failed to create sampler for composer"
- " [1.512.1] %s : Failed with setupInputTexturesWithBL\n"
- " [1.512.1] %s : Failed with setupOutputTexturesWithBuffer\n"
- " [1.512.1] %s : HDR error: Failed to create MTLTexture For _metadataTextures[%d][%d]=%p\n"
- " [1.512.1] %s : Initialization Failed, self = %p\n"
- " [1.512.1] %s : Initialization Failed, self=%p\n"
- " [1.512.1] %s : encoder=%p, out of encoder resource"
- " [1.512.1] %s : error, device = %p, _device=%p\n"
- " [1.512.1] %s : error, self = %p \n"
- " [1.512.1] %s : failed with error %d\n"
- " [1.512.1] %s : format (%d) %c%c%c%c [%c%c%c%c]is not supported yet\n"
- " [1.512.1] %s : layer0=%p, layer1=%p, output=%p, metatdata=%p"
- " [1.512.1] %s : unknown HDRProcessing hw type %d, switching to GPU"
- " [1.512.1] %s: EDRMetaData_RBSP error ext_block_len[%u] > 256, bail!\n"
- " [1.512.1] %s: EDRMetaData_RBSP error in ext_content_adaptive_metadata, EXT_BLOCK_PAYLOAD, bail!\n"
- " [1.512.1] %s: EDRMetaData_RBSP error in ext_content_adaptive_metadata, EXT_BLOCK_PAYLOAD2, bail!\n"
- " [1.512.1] %s: EDRMetaData_RBSP error in vdr_dm_data_payload, bail!\n"
- " [1.512.1] %s: EDRMetaData_RBSP error level=%d, length=%d: invalid!"
- " [1.512.1] %s: EDRMetaData_RBSP error map_idc = %d, bail!\n"
- " [1.512.1] %s: EDRMetaData_RBSP error nal_unit_type = %d, bail!\n"
- " [1.512.1] %s: EDRMetaData_RBSP error num_blocks_payload2[%d] + num_ext_blocks[%d] > 255, bail!\n"
- " [1.512.1] %s: EDRMetaData_RBSP error num_ext_blocks = %d > 254, bail!\n"
- " [1.512.1] %s: EDRMetaData_RBSP error remaining_bits[%lu] < length[%u], bail!\n"
- " [1.512.1] %s: EDRMetaData_RBSP error reserved_zero_3bits=1, first frame, bail!\n"
- " [1.512.1] %s: EDRMetaData_RBSP error rpu_type = %d, bail!\n"
- " [1.512.1] %s: EDRMetaData_RBSP error signal_bit_depth = %d, bail!\n"
- " [1.512.1] %s: EDRMetaData_RBSP error vdr_rpu_level = %d, nlq_num_pivots_minus2 = %d, bail!\n"
- " [1.512.1] %s: EDRMetaData_RBSP error vdr_rpu_level = %d, num_x_partitions_minus1 = %d, bail!\n"
- " [1.512.1] %s: EDRMetaData_RBSP error vdr_rpu_level = %d, num_y_partitions_minus1 = %d, bail!\n"
- " [1.512.1] %s: ERROR: Out of bound! curr_part_idx = %d, y = %d, x = %d, bail!\n"
- " [1.512.1] %s: ERROR: Out of bound! mapping_chroma_format_idc = %d, bail!\n"
- " [1.512.1] %s: ERROR: Out of bound! mmr_order_minus1 = %d, bail!\n"
- " [1.512.1] %s: ERROR: Out of bound! poly_order_minus1 = %d, bail!\n"
- " [1.512.1] %s: ERROR: Out of bound! vdr_rpu_level = %d, num_pivots_minus2[%d] = %d, bail!\n"
- " [1.512.1] %s: calloc failed!\n"
- " [1.512.1] %s: input=%p, options=%p, configCallback=%p"
- " [1.512.1] %s: parsing error remaining_bits = %d, bail!\n"
- " [1.512.1] %s: parsing error, bail!\n"
- " [1.512.1] %s: parsing error: first_byte = %u [legal value = 4 or 181], bail!\n"
- " [1.512.1] %s: parsing error: num_bezier_curve_anchors = %d, bail!\n"
- " [1.512.1] %s: parsing error: num_distributions = %d [legal value = 9], bail!\n"
- " [1.512.1] %s: parsing error: num_windows = %d [legal value = 1], bail!\n"
- " [1.512.1] %s: parsing error: sei_payload_type = %u [legal value = 4], sei_payload_length = %u, actual seiLength = %u, bail!\n"
- " [1.512.1] %s: syntax error: application_identifier = %d"
- " [1.512.1] %s: syntax error: application_version = %d"
- " [1.512.1] %s: syntax error: average_maxrgb = %08x"
- " [1.512.1] %s: syntax error: color_saturation_mapping_flag = %d"
- " [1.512.1] %s: syntax error: distribution_index[%d]:%d != k_distribution_index[%d]:%d"
- " [1.512.1] %s: syntax error: distribution_values[%d] = %08x"
- " [1.512.1] %s: syntax error: itu_t_t35_country_code = %02x"
- " [1.512.1] %s: syntax error: itu_t_t35_terminal_provider_code = %04x"
- " [1.512.1] %s: syntax error: itu_t_t35_terminal_provider_oriented_code = %d"
- " [1.512.1] %s: syntax error: mastering_display_actual_peak_luminance_flag = %d"
- " [1.512.1] %s: syntax error: maxscl[%d] = %08x"
- " [1.512.1] %s: syntax error: targeted_system_display_actual_peak_luminance_flag = %d"
- " [1.512.1] %s: warning: fraction_bright_pixels = %d"
- " [1.512.1] ++ %s : MSR created! instance=%p, platform=0x%x\n"
- " [1.512.1] ++ %s : instance=%p _composer=%p _msr=%p"
- " [1.512.1] ++ %s: MSRApiVer=%d\n"
- " [1.512.1] -- %s : Failed with error %d, _numberOfScheduledFrames=%ld\n"
- " [1.512.1] -- %s: HDRProcessor exit! instance=%p\n"
- " [1.512.1] -- %s: MSR exit! instance=%p\n"
- " [1.512.1] --------------------------------------------------------\n"
- " [1.512.1] -----------------------------------------------------------------------------------\n"
- " [1.512.1] <<smpte_st_2094_50:dbg>> warning: Failed to parse SMPTE ST 2094-50 metadata, error=%d"
- " [1.512.1] Assertion: \"!_hist\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/hist_based_tone_mapping.mm\" at line 308\n"
- " [1.512.1] Assertion: \"!inputP422\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1814\n"
- " [1.512.1] Assertion: \"!inputP422\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1988\n"
- " [1.512.1] Assertion: \"!ptvMode\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 3613\n"
- " [1.512.1] Assertion: \"(msrHC->operation == ((HDRProcessingOperation)(kHDRProcessingReshape | kHDRProcessingToneMap)))\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 3019\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1228\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1379\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1406\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Config/HDRConfig.cpp\" at line 1439\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 477\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 860\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1818\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1821\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1827\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1983\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1998\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2002\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2005\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2011\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2020\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/SpatialResampler.m\" at line 212\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/SpatialResampler.m\" at line 243\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 3441\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 3539\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 3778\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 4859\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 5119\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6803\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6833\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 2641\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 4254\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/MetaPacket/DolbyVisionHDMIPacket.mm\" at line 619\n"
- " [1.512.1] Assertion: \"0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/MetaPacket/DolbyVisionHDMIPacket.mm\" at line 678\n"
- " [1.512.1] Assertion: \"HDR10OnHDR10TV || DolbyOnHDR10TV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2032\n"
- " [1.512.1] Assertion: \"HLGOnHDR10TV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1804\n"
- " [1.512.1] Assertion: \"_currentPolynomialTable\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 2027\n"
- " [1.512.1] Assertion: \"_displayType != kHDRDestinationSDRTV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 2921\n"
- " [1.512.1] Assertion: \"_hdrMode == kHDRContentDolbyVision\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 1890\n"
- " [1.512.1] Assertion: \"_hdrMode == kHDRContentDolbyVision\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/HDRProcessorMetal.mm\" at line 1922\n"
- " [1.512.1] Assertion: \"_metadataVertexBuffer\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 2515\n"
- " [1.512.1] Assertion: \"_msrHC.processingType == kHDRProcessingTypeConvert\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 785\n"
- " [1.512.1] Assertion: \"_vertsBuffer\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 2476\n"
- " [1.512.1] Assertion: \"bufferT && bufferS\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 2640\n"
- " [1.512.1] Assertion: \"bufferT && bufferS\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 2688\n"
- " [1.512.1] Assertion: \"chromaPixelFormat != MTLPixelFormatInvalid\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 3874\n"
- " [1.512.1] Assertion: \"cmp != 0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingByCapabilities.mm\" at line 328\n"
- " [1.512.1] Assertion: \"cmp != 0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingT2.mm\" at line 185\n"
- " [1.512.1] Assertion: \"dm_config_ptr->dmVersion == 4\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 3040\n"
- " [1.512.1] Assertion: \"hasThreeOutputPlane || has10BitOutput\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1181\n"
- " [1.512.1] Assertion: \"hdrCtrl->colourPrimaries == kIOSurfaceTagColorPrimaries_ITU_R_2020\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6950\n"
- " [1.512.1] Assertion: \"hdrCtrl->colourPrimaries == kIOSurfaceTagColorPrimaries_ITU_R_709_2\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 8656\n"
- " [1.512.1] Assertion: \"hdrCtrl->displayPipelineCompensationType != kDisplayPipelineCompensationTypeNoneHeadrooomDependent && hdrCtrl->displayPipelineCompensationType != kDisplayPipelineCompensationTypeHeadroomDependent\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 6070\n"
- " [1.512.1] Assertion: \"hdrCtrl->transferFunction != kIOSurfaceTagColorTransferFunction_ITU_R_2100_HLG\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Engine/ProcessingEngine.mm\" at line 356\n"
- " [1.512.1] Assertion: \"hdrCtrl->transferFunction != kIOSurfaceTagColorTransferFunction_ITU_R_2100_HLG\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2225\n"
- " [1.512.1] Assertion: \"isConversionInputRgb(msrHC) || isConversionInputYuv(msrHC) || isConversionInputIpt(msrHC)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2994\n"
- " [1.512.1] Assertion: \"isConversionOutputYuv(msrHC)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 5539\n"
- " [1.512.1] Assertion: \"isGPUtoHDR10TV\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 1460\n"
- " [1.512.1] Assertion: \"isTonemappingEnabled(msrHC)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 4562\n"
- " [1.512.1] Assertion: \"metadata->mapping_idc[0][0][cmp][0] == 0 || metadata->mapping_idc[0][0][cmp][0] == 1\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingByCapabilities.mm\" at line 313\n"
- " [1.512.1] Assertion: \"metadata->mapping_idc[0][0][cmp][0] == 0 || metadata->mapping_idc[0][0][cmp][0] == 1\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingT2.mm\" at line 170\n"
- " [1.512.1] Assertion: \"mid_tap_h >= 4 && mid_tap_v >= 1\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 252\n"
- " [1.512.1] Assertion: \"msrHC->enableConverting && !msrHC->enableToneMapping\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2993\n"
- " [1.512.1] Assertion: \"msrHC->processingType == kHDRProcessingTypeDoVi || msrHC->processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 4608\n"
- " [1.512.1] Assertion: \"msrHC->processingType == kHDRProcessingTypeDoVi || msrHC->processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 5161\n"
- " [1.512.1] Assertion: \"overrideHLGOOTFMixingStartTdivNits >= 100.0f\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/dovi_display_management_host.mm\" at line 717\n"
- " [1.512.1] Assertion: \"overrideHLGOOTFMixingStartTdivNits >= 100.0f\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/hlg_display_management_host.mm\" at line 121\n"
- " [1.512.1] Assertion: \"polyBuf && mmrCoefBuf\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingByCapabilities.mm\" at line 310\n"
- " [1.512.1] Assertion: \"polyBuf && mmrCoefBuf\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingT2.mm\" at line 167\n"
- " [1.512.1] Assertion: \"processingType == kHDRProcessingTypeDoVi || processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Engine/ProcessingEngine.mm\" at line 370\n"
- " [1.512.1] Assertion: \"processingType == kHDRProcessingTypeDoVi || processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Engine/ProcessingEngine.mm\" at line 425\n"
- " [1.512.1] Assertion: \"processingType == kHDRProcessingTypeDoVi || processingType == kHDRProcessingTypeDoVi84\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/MSR/MSRHDRProcessingImpl.mm\" at line 2228\n"
- " [1.512.1] Assertion: \"retVal == 0\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/BackwardDisplayManagement/HDRBackwardDisplayManagement.mm\" at line 4500\n"
- " [1.512.1] Assertion: \"sMaxPq <= L2PqNorm(4000)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 7468\n"
- " [1.512.1] Assertion: \"sMinPq >= L2PqNorm(0.005)\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 7469\n"
- " [1.512.1] Assertion: \"sdrOnDolbyOrHDR10 == __objc_no\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1775\n"
- " [1.512.1] Assertion: \"sdrOnDolbyOrHDR10 == __objc_no\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/Composer/DolbyVisionComposer.mm\" at line 1782\n"
- " [1.512.1] Assertion: \"tableSize == 1024\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/common_display_management_host.mm\" at line 3730\n"
- " [1.512.1] Assertion: \"y1 == y2\" warned in \"/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HDRProcessing/Metal/DisplayManagement/DolbyVisionDisplayManagement.mm\" at line 2613\n"
- " [1.512.1] Constraint changed to: %s"
- " [1.512.1] Constraint: #=%d F=%d C=%d T=%d NP=%d(%2.4f - %2.4f)"
- " [1.512.1] Constraint: %s"
- " [1.512.1] ContentType: %s, sr=%d"
- " [1.512.1] HDRConfig: Frame #%d: configDumpStyle = %d (%s), configDumpLevel = %d, configDumpFlag = %d\n"
- " [1.512.1] Incorrect mode usage : %d _hdrMode = %d"
- " [1.512.1] MR81: Error: BuildInterpInfo TrimLevel must be 8"
- " [1.512.1] MR81: Error: BuildLumaXInfo trimNum=0"
- " [1.512.1] MR81: Error: GetMdsExtMr mr->mdsBase.mdsLen < 71"
- " [1.512.1] MR81: Error: GetRgb2XyzM33, unsupported rgbDef:%d"
- " [1.512.1] MR81: Error: InterpL2 MDSEXT_HAVE_LVL_L0 is false"
- " [1.512.1] MR81: Error: InterpL8 MDSEXT_HAVE_LVL_L0 is false"
- " [1.512.1] MR81: Error: MrGetMdsExtFxpMr extLen < 0"
- " [1.512.1] MR81: Error: MrGetMdsExtFxpMr mdsLen < 0"
- " [1.512.1] MR81: Error: PrepareL2 MDSEXT_HAVE_LVL_L0 is false"
- " [1.512.1] MR81: Error: PrepareL8 MDSEXT_HAVE_LVL_L0 is false"
- " [1.512.1] MR81: metadataReconstruction: Error: GetMdsExtFxpMr ret = %d"
- " [1.512.1] MR81: metadataReconstruction: Error: ParseMds ret = %d"
- " [1.512.1] MR81: metadataReconstruction: Error: ret = %d"
- " [1.512.1] MR81: metadataReconstruction: Error: unmapped, hasMMRData=%d"
- " [1.512.1] MR81: metadataReconstruction: Warning: GetMdsExtFxpMr ret = %d [no change]"
- " [1.512.1] MR81: metadataReconstruction: Warning: RGBtoLMS_coef [%d][%d] changed, %d/%d"
- " [1.512.1] MR81: metadataReconstruction: Warning: YCCtoRGB_coef [%d][%d] changed, %d/%d"
- " [1.512.1] MR81: metadataReconstruction: Warning: YCCtoRGB_offset[%d] changed, %u/%u"
- " [1.512.1] MR81: metadataReconstruction: Warning: ret = %d [no change]"
- " [1.512.1] Memory allocation for  histBinCentroidInLinear failed"
- " [1.512.1] Memory allocation for _cdf failed"
- " [1.512.1] Memory allocation for _fullRangeBinIdx8bit failed"
- " [1.512.1] Memory allocation for _histBinMlmInPQ failed"
- " [1.512.1] Memory allocation for _sdrHdrMlmLut_x failed"
- " [1.512.1] Memory allocation for _sdrHdrMlmLut_y failed"
- " [1.512.1] Memory allocation for avgValBuffer failed"
- " [1.512.1] Memory allocation for fullRangeBinIdx failed"
- " [1.512.1] Memory allocation for histBinCenter failed"
- " [1.512.1] Memory allocation for histBuff failed"
- " [1.512.1] Memory allocation for hlgBinCenterInPQ failed"
- " [1.512.1] Memory allocation for maxValBuffer failed"
- " [1.512.1] Memory allocation for minValBuffer failed"
- " [1.512.1] Memory allocation for normHist failed"
- " [1.512.1] Memory allocation for pcntVal failed"
- " [1.512.1] Memory allocation for pqBinCenterInPQ failed"
- " [1.512.1] Memory allocation for prctVal failed"
- " [1.512.1] Memory allocation for prctValBuffer failed"
- " [1.512.1] Memory allocation for prctValBuffer[i] failed"
- " [1.512.1] Memory allocation for prevNormHistHeight failed"
- " [1.512.1] Memory allocation for sdrBinCenterInPQ failed"
- " [1.512.1] Memory allocation for stdValBuffer failed"
- " [1.512.1] Memory allocation for targetMaxBuffer failed"
- " [1.512.1] Memory allocation for testpatchHistBuff failed"
- " [1.512.1] Not supported type=%d\n"
- " [1.512.1] ToneMapLUT_xsamples memory allocation failed!"
- " [1.512.1] ToneMapLUT_ysamples memory allocation failed!"
- " [1.512.1] ToneMapMixFactorLUT_xsamples memory allocation failed!"
- " [1.512.1] ToneMapMixFactorLUT_ysamples memory allocation failed!"
- " [1.512.1] WARNING: calcCubicSplineParam: delta == 0"
- " [1.512.1] WARNING: cubicSplineInterp: delta == 0"
- " [1.512.1] Warning: Attempting to read defaults writes in release builds! key = \"%@\"\n"
- " [1.512.1] [frame_%llu] scheduled2completed: avg: %5.1f, max: %5.1f [in ms], [ %d : %d ]\n"
- " [1.512.1] _width=%d, _targetWidth=%d, _height=%d, _targetHeight=%d"
- " [1.512.1] checkInputOutputIOSurface() failed!"
- " [1.512.1] commanBuffer=%p, output=%p, input=%p, ui=%p"
- " [1.512.1] failed due to metalDevice change!"
- " [1.512.1] hcr : %s"
- " [1.512.1] hcr changes to: %s"
- " [1.512.1] hcrUseSystemBrightnessForCaptureContent : %s"
- " [1.512.1] hcrUseSystemBrightnessForCaptureContent changes to: %s"
- " [1.512.1] hcrUseSystemBrightnessForProContent : %s"
- " [1.512.1] hcrUseSystemBrightnessForProContent changes to: %s"
- " [1.512.1] hdrMaxBrightnessInNits was forced to %f!"
- " [1.512.1] sdrMaxBrightnessInNits was forced to %f!"
```
