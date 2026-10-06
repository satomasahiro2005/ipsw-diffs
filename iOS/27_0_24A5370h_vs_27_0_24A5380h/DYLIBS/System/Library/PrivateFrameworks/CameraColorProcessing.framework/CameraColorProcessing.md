## CameraColorProcessing

> `/System/Library/PrivateFrameworks/CameraColorProcessing.framework/CameraColorProcessing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8a658` | `0x8a6fc` | **`+0xa4`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x7d0` | `0x820` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0xb949` | `0xb990` | **`+0x47`** |
| `__TEXT.__cstring` | `0x9434` | `0x9471` | **`+0x3d`** |
| `__TEXT.__gcc_except_tab` | `0x5064` | `0x5090` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x488` | `0x4b0` | **`+0x28`** |

### Other Changes

```diff

-753.0.0.122.3
+758.0.0.122.2

-  CStrings:  1886
+  CStrings:  1889
Functions:
~ -[HazeEstimation estimateHaze:] : 1420 -> 1440
~ -[AWBAlgorithm configWithModuleConfig:metadata:cameraInfo:awbParams:] : 6588 -> 7036
~ __ZN12LTMComputeV110LTMCompute18generateSpatialLTCEPK16sLtmComputeInputPK23sLtmComputeMeta_SOFTISPP17sLtmComputeOutput : 4612 -> 4604
~ __ZN12LTMComputeV210LTMCompute11interpolateEPKfS2_iS2_Pfi : 220 -> 216
~ __ZN12LTMComputeV110LTMCompute19computeRGBToneCurveEPK16sLtmComputeInputPKNS_16sLtmTuningParamsEPKNS_15sLtmFrameParamsEP17sLtmComputeOutput : 1388 -> 1384
~ __ZN12LTMComputeV110LTMCompute12makeScaleGTCEPfPKfff : 444 -> 440
~ __ZN12LTMComputeV110LTMCompute16computeLocalLumaEPK16sLtmComputeInputPKNS_16sLtmTuningParamsEPKNS_17sLtmDisplayParamsEPNS_15sLtmFrameParamsE : 552 -> 548
~ __ZN12LTMComputeV210LTMCompute11interpolateEPKfS2_iS2_Pfif : 220 -> 228
~ __ZN12LTMComputeV110LTMCompute28calculateHighlightSceneModelEPK16sLtmComputeInputPKNS_16sLtmTuningParamsEbPNS_15sLtmFrameParamsE : 1864 -> 1860
~ __ZN12LTMComputeV110LTMCompute19calculateSceneFlareEPKfiPiffPfS4_S4_ : 1136 -> 1144
~ __ZN12LTMComputeV110LTMCompute38calculateGlobalLUTandModifySceneModelsEmPK16sLtmComputeInputPK15sLtmComputeMetaPKNS_16sLtmTuningParamsEPKNS_17sLtmDisplayParamsEPNS_15sLtmFrameParamsEP17sLtmComputeOutput : 3320 -> 3268
~ __ZN7CAWBAFE8SetStatsEPK16_FE_3A_Stats_H15PK15_TILE_Stat_ElemPK16_AEAWB_Stat_ElemPKvS2_ : 336 -> 328
~ __ZN7CAWBAFE13TrimHistogramEPjt : 1632 -> 1600
~ __ZN7CAWBAFE19calculateRGBFromCCTEjPt : 676 -> 660
~ __ZN7CAWBAFE24SetFlashProjectionConfigEPK47sCIspCmdAppleChAWBFlashProjectionConfigSetEntry : 3936 -> 3828
~ __ZN28CDualLEDsWhitePointProjector9ParamInitEff13eFlashLEDTypePK22sPerModuleLEDCalibDataPK35sDualLEDsWhitePointProjectionConfig : 520 -> 472
~ __ZN12LTMComputeV210LTMCompute16computeLocalLumaEPK16sLtmComputeInputPKNS_16sLtmTuningParamsEPKNS_17sLtmDisplayParamsEPNS_15sLtmFrameParamsE : 572 -> 568
~ __ZN12LTMComputeV210LTMCompute30calculateHighlightSceneModelV2EPK16sLtmComputeInputPKNS_16sLtmTuningParamsEbPKNS_15sLtmFrameParamsEPfSA_SA_ : 2660 -> 2648
~ __ZN12LTMComputeV210LTMCompute38calculateGlobalLUTandModifySceneModelsEmPK16sLtmComputeInputPK15sLtmComputeMetaPKNS_16sLtmTuningParamsEPKNS_17sLtmDisplayParamsEPNS_15sLtmFrameParamsEP17sLtmComputeOutput : 4220 -> 4208
~ __ZN12LTMComputeV210LTMCompute12allocateToneEPfS1_PKfPKNS_16sLtmTuningParamsEPKNS_17sLtmDisplayParamsEPKNS_15sLtmFrameParamsES3_S3_S3_S3_S3_fffbbb : 3944 -> 3936
~ __ZN12LTMComputeV210LTMCompute12makeScaleGTCEPfPKfff : 444 -> 440
~ __ZN12LTMComputeV210LTMCompute19computeRGBToneCurveEPK24sLtmComputeInput_SOFTISPPKNS_16sLtmTuningParamsEPKNS_15sLtmFrameParamsEP17sLtmComputeOutput : 1424 -> 1436
~ __ZN12LTMComputeV210LTMCompute18generateSpatialLTCEPK24sLtmComputeInput_SOFTISPPK23sLtmComputeMeta_SOFTISPP17sLtmComputeOutput : 10308 -> 10324
~ +[LTMExtractMetadataV1 extractCCMFromMetadata:toDriverInput:] : 904 -> 896
~ +[LTMExtractMetadataV2 extractCCMFromMetadata:toDriverInput:] : 904 -> 896
CStrings:
+ "<<<< AWBAlgorithm >>>> %s: Configuring SoftISP AWB, SetFile origin: %@"
+ "AWB requires a moduleConfig to configure."
+ "moduleConfig.count"
```
