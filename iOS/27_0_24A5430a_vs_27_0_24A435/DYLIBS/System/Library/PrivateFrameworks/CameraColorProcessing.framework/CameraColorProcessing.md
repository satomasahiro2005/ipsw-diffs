## CameraColorProcessing

> `/System/Library/PrivateFrameworks/CameraColorProcessing.framework/CameraColorProcessing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65a38` | `0x65b08` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x2c20` | `0x2cc0` | **`+0xa0`** |
| `__DATA_CONST.__objc_arraydata` | `0x360` | `0x3b0` | **`+0x50`** |
| `__AUTH_CONST.__objc_intobj` | `0x2b8` | `0x2e8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x54a3` | `0x54b9` | **`+0x16`** |

### Other Changes

```diff

-  CStrings:  986
+  CStrings:  991
Symbols:
+ _kFigCapturePortType_RenoFrontFacingSuperWideCamera
- _kFigCapturePortType_RCamera
Functions:
~ __ZN7CAWBAFE18SetHistogramWeightEhPK38sCIspCmdAppleChAWBHistogramWeightEntry : 132 -> 136
~ __ZN7CAWBAFE18InterpCCMfromBasesEfffPA3_iPK17sTuningCurvePointPA9_Ksf : 616 -> 620
~ -[LTMExtractMetadataV1 extractFrom:toDriverInput:ltmGeometry:] : 8688 -> 8692
~ __ZN15CAWBAFEFDAssist19GetfdHiResWindowRGBEP13fdAWBMetaDataPK23_HighResAWBAE_Stat_ElemPKj : 216 -> 220
~ __ZN15CAWBAFEFDAssist27MapSkinColorToWhiteWeightedEP13fdAWBMetaDataPA4_t : 464 -> 468
~ __ZN15CAWBAFEFDAssist31MapSkinColorToWhiteProbWeightedEP13fdAWBMetaDataPA4_t : 312 -> 316
~ -[AWBAlgorithm configFlashMetadata:cameraInfo:moduleConfig:] : 6548 -> 6556
~ __ZN7CAWBAFE17ComputeProjectionEtPfS0_S0_S0_PA2_KsP18eAWBProjectionTypeS0_ : 1188 -> 1180
~ __ZN7CAWBAFE17postWPCalcTintingEPjtf : 1144 -> 1164
~ __ZN7CAWBAFE28EstimateCurrentSceneLuxLevelEv : 700 -> 712
~ __ZN10CAWBAFEH1415ComputeAWBGainsEtt : 2648 -> 2660
~ __ZN12LTMComputeV210LTMCompute30calculateHighlightSceneModelV2EPK16sLtmComputeInputPKNS_16sLtmTuningParamsEbPKNS_15sLtmFrameParamsEPfSA_SA_ : 2648 -> 2652
~ __ZN12LTMComputeV210LTMCompute18generateSpatialLTCEPK24sLtmComputeInput_SOFTISPPK23sLtmComputeMeta_SOFTISPP17sLtmComputeOutput : 10324 -> 10348
~ __ZN12LTMComputeV210LTMCompute19calculateSceneModelEPK16sLtmComputeInputPKNS_16sLtmTuningParamsEPNS_15sLtmFrameParamsEfPfS9_fPKf : 2836 -> 2884
~ __ZN12LTMComputeV210LTMCompute16levelSmoothHFFCBEPfPKfS3_iiif : 3204 -> 3208
~ __ZN12LTMComputeV210LTMCompute14levelSmoothHFFEPfPKfS3_iii : 2472 -> 2480
~ __ZN12LTMComputeV210LTMCompute17generateLinearLTCEPK16sLtmComputeInputPK15sLtmComputeMetaP17sLtmComputeOutput : 544 -> 548
~ __ZN12LTMComputeV210LTMCompute15LTCGridCalcAlgoEPK16sLtmComputeInputPK15sLtmComputeMetaP17sLtmComputeOutputfPKfSA_fSA_ff : 5116 -> 5132
~ __ZN11LTMDriverV29LTMDriver7ProcessEPK24sCLRProcHITHStat_SOFTISPPK24sRefDriverInputs_SOFTISPP24sLtmComputeInput_SOFTISP : 1296 -> 1304
~ __ZN11LTMDriverV29LTMDriver22ComputeLocalHistogramsEPK24sCLRProcHITHStat_SOFTISPP16sLtmComputeInputf : 716 -> 724
~ __ZN11LTMDriverV29LTMDriver22computeGlobalHistogramEPKjPfttjj : 148 -> 156
~ __ZN11LTMDriverV29LTMDriver29computeFaceWeightForToneHFFV2EPK7sBTRectPK11sCIspFDRectiPfPKi : 248 -> 256
CStrings:
+ "C743"
+ "V63"
+ "V64"
+ "V64s"
+ "V68"
```
