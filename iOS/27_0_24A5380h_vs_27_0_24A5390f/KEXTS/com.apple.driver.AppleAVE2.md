## com.apple.driver.AppleAVE2

> `com.apple.driver.AppleAVE2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1c9a80` | `0x1cd2a0` | **`+0x3820`** |
| `__TEXT.__cstring` | `0x4736f` | `0x47f24` | **`+0xbb5`** |
| `__TEXT.__os_log` | `0x5bc39` | `0x5c7be` | **`+0xb85`** |
| `__DATA_CONST.__const` | `0xb020` | `0xae10` | **`-0x210`** |
| `__TEXT.__const` | `0x4b760` | `0x4b680` | **`-0xe0`** |

### Other Changes

```diff

-913.8.0.0.0
+913.29.1.0.0

-  CStrings:  9759
+  CStrings:  9847
Functions:
~ __ZN13AVE_MD_Crypto14PrepareTaskCmdEPK14_S_AVE_CmdInfoP23_S_AVE_TaskInCmd_Crypto : 756 -> 748
~ __Z22AVE_AXI2AF_GetTunables12_E_AVE_DevIDjiPPK17_S_AVE_AXI2AF_Cfg : 1324 -> 1276
~ sub_fffffff0086b4110 -> sub_fffffff0086c8b88 : 140 -> 444
~ __Z26AVE_CalcBufSizeOfCodedDatai14_E_AVE_DevType14_E_AVE_EncTypeii12_E_ChromaFmtiibb14_E_AVE_EncMode13_E_AVE_RCModeii : 1148 -> 1368
~ sub_fffffff0086b4878 -> sub_fffffff0086c94fc : 172 -> 508
~ sub_fffffff0086b4998 -> sub_fffffff0086c976c : 72 -> 348
~ sub_fffffff0086b49e0 -> sub_fffffff0086c98c8 : 108 -> 400
~ sub_fffffff0086b4b00 -> __Z20AVE_CalcBufSizeOfDPB14_E_AVE_DevType14_E_AVE_EncTypeiiii12_E_ChromaFmtbPi : 1640 -> 1988
~ sub_fffffff0086b51bc -> sub_fffffff0086ca324 : 180 -> 520
~ sub_fffffff0086b5314 -> __Z20AVE_CalcBufSizeOfLRB14_E_AVE_DevType15_E_AVE_WorkType14_E_AVE_EncTypeii12_E_ChromaFmtbiiPi : 900 -> 1168
~ sub_fffffff0086b56b8 -> __Z26AVE_CalcBufSizeOfHSCOutput14_E_AVE_DevType15_E_AVE_WorkTypeii12_E_ChromaFmtibPi : 264 -> 580
~ sub_fffffff0086b5848 -> sub_fffffff0086cad4c : 656 -> 1036
~ sub_fffffff0086b5b48 -> sub_fffffff0086cb1c8 : 144 -> 460
~ sub_fffffff0086b5bec -> sub_fffffff0086cb3a8 : 116 -> 428
~ sub_fffffff0086b5c70 -> sub_fffffff0086cb564 : 76 -> 368
~ sub_fffffff0086b5cd0 -> sub_fffffff0086cb6e8 : 104 -> 368
~ sub_fffffff0086b5d4c -> sub_fffffff0086cb86c : 156 -> 428
~ sub_fffffff0086b5e10 -> __Z34AVE_CalcBufSizeOfSrcNeighborFwData14_E_AVE_EncTypei : 92 -> 360
~ sub_fffffff0086b5e88 -> sub_fffffff0086cbbc4 : 80 -> 360
~ sub_fffffff0086b5ef4 -> sub_fffffff0086cbd48 : 64 -> 348
~ sub_fffffff0086b5f50 -> __Z37AVE_CalcBufSizeOfSrcNeighborLeftPixel14_E_AVE_EncType12_E_ChromaFmtii : 152 -> 436
~ sub_fffffff0086b60a0 -> sub_fffffff0086cc12c : 208 -> 488
~ sub_fffffff0086b6184 -> sub_fffffff0086cc328 : 64 -> 336
~ sub_fffffff0086b629c -> __Z27AVE_CalcBufSizeOfMCTFOutput14_E_AVE_DevTypebiii12_E_ChromaFmtbPi : 736 -> 1052
~ __Z27AVE_CHM_MakeFwCmd_Start_AV1P10_S_AVE_CHMyjP14_S_AVE_TimeOutP16sCAveCmdAv1Start : 1724 -> 1728
~ __Z25AVE_CHM_SetDataInfo_FrameP10_S_AVE_CHMP16_S_AVE_FrameInfoP18AVE_PICMGMT_PARAMS : 616 -> 620
~ __Z25AVE_CHM_SetDataInfo_FwBufP10_S_AVE_CHMP14_S_AVE_CmdInfoP16_S_AVE_FrameInfoP14_S_AVE_DPB_SetP18AVE_PICMGMT_PARAMS : 20540 -> 23124
~ __Z23AVE_Client_Enc_PrintAVCP13_S_AVE_ClientjiPKci : 4236 -> 4232
~ sub_fffffff0086e44c8 -> sub_fffffff0086fb2d4 : 136 -> 132
~ sub_fffffff0086e4c54 -> sub_fffffff0086fba5c : 504 -> 496
~ __Z26AVE_Client_CheckCommonInfoP13_S_AVE_ClientbP35AVE_SessionSettings_UserKernel_Data : 2520 -> 2304
~ __Z20AVE_Client_CheckInfoP13_S_AVE_ClientbP35AVE_SessionSettings_UserKernel_Data : 1356 -> 2020
~ __Z17AVE_Client_VerifyP13_S_AVE_ClientbP35AVE_SessionSettings_UserKernel_Data : 740 -> 752
~ __Z16AVE_Client_StartP13_S_AVE_ClientP14_S_AVE_TimeOutjiP21_S_AVE_SurfaceIDInSetP35AVE_SessionSettings_UserKernel_DataPKc : 7792 -> 7804
~ sub_fffffff0086f1cec -> sub_fffffff008708cc4 : 1456 -> 1468
~ __Z18AVE_Client_ProcessP13_S_AVE_ClientP14_S_AVE_TimeOuti : 1952 -> 1964
~ __Z19AVE_Client_CompleteP13_S_AVE_ClientP14_S_AVE_TimeOuti : 1632 -> 1644
~ __Z16AVE_Client_FlushP13_S_AVE_ClientP14_S_AVE_TimeOuti : 1632 -> 1644
~ __Z16AVE_Client_ResetP13_S_AVE_ClientP14_S_AVE_TimeOuti : 1632 -> 1644
~ __Z20AVE_Client_AppendCmdP13_S_AVE_Client10_E_AVE_Cmd15_E_AVE_Cmd_ModejP14_S_AVE_TimeOutPv : 1368 -> 1444
~ __Z29AVE_Client_VerifyDataResourceP13_S_AVE_ClientP14_S_AVE_CmdInfoiyP16_S_AVE_FrameInfo : 1600 -> 1596
~ sub_fffffff0086f7ea8 -> sub_fffffff00870ef04 : 408 -> 404
~ sub_fffffff0086f8578 -> sub_fffffff00870f5d0 : 388 -> 384
~ __Z27AVE_TaskCmd_LACost_SetInputPK14_S_AVE_CmdInfoiiiPK21_S_AVE_SurfaceInfoSetP23_S_AVE_TaskInCmd_LACost : 404 -> 416
~ __ZL16AVE_LAGOP_DecideP10_S_AVE_CHMP10_S_AVE_Cmd : 3916 -> 3864
~ __ZN7AVE_Drv22ProcessInputCmd_AssignEP13_S_AVE_ClientP10_S_AVE_Cmd : 3016 -> 3008
~ sub_fffffff00873d570 -> sub_fffffff008754594 : 88 -> 84
~ __ZN6AVE_MD13PrintCmdStatsEjjiPKci : 836 -> 832
~ __ZN7AVE_HwC9SendFwCmdEP10_S_AVE_CHMPviS2_ : 1820 -> 2076
~ __ZN7AVE_SwC15ProcessIntr_CmdEm : 3396 -> 3424
~ __ZN8HEVC_VPS24video_parameter_set_rbspEv : 1436 -> 1468
~ sub_fffffff0087ae744 -> sub_fffffff0087c589c : 1668 -> 1724
~ __ZN8HEVC_VPS13vps_extensionEv : 3184 -> 3420
~ __Z23AVE_Prop_Cfg_HEVC_PrintP20_S_AVE_Prop_Cfg_HEVCjiPKci : 46564 -> 48444
~ __Z22AVE_CreateDataSurfacesP14AVE_SurfaceMgrP4taskP23_S_AVE_SurfaceIDDataSetP21_S_AVE_SurfaceInfoSetyjP21_S_AVE_SurfaceDataSet : 4256 -> 5612
~ __Z23AVE_DARTMapDataSurfacesP14AVE_SurfaceMgrP21_S_AVE_SurfaceDataSetP21_S_AVE_SurfaceInfoSetj : 3140 -> 4000
~ sub_fffffff0087efc38 -> sub_fffffff008807eb4 : 96 -> 92
~ __ZN10AVE_MD_SVE23DARTMapExternalSurfacesEy : 1096 -> 1092
~ sub_fffffff0087f27b0 -> sub_fffffff00880aa24 : 604 -> 600
~ __ZN10AVE_MD_SVE23DARTMapInternalSurfacesEy : 1124 -> 1120
~ sub_fffffff0087f2e70 -> sub_fffffff00880b0dc : 604 -> 600
~ __Z22AVE_Work_Enc_TuneParamP13_S_AVE_Clientii : 1848 -> 1860
~ sub_fffffff008810230 -> sub_fffffff0088284a4 : 300 -> 332
~ sub_fffffff008810524 -> sub_fffffff0088287b8 : 272 -> 284
~ sub_fffffff008810a04 -> sub_fffffff008828ca4 : 228 -> 240
~ sub_fffffff008826654 -> sub_fffffff00883e900 : 200 -> 204
~ sub_fffffff00882671c -> sub_fffffff00883e9cc : 320 -> 324
~ sub_fffffff00882685c -> sub_fffffff00883eb10 : 320 -> 324
~ sub_fffffff00882699c -> sub_fffffff00883ec54 : 352 -> 360
~ sub_fffffff008826afc -> sub_fffffff00883edbc : 328 -> 332
~ sub_fffffff0088414e4 -> sub_fffffff0088597a8 : 44 -> 56
CStrings:
+ "%lld %d AVE %s: %p %lld AuxLayer[%d]: profile=%s width=%d height=%d"
+ "%lld %d AVE %s: %p %lld AuxLayer[%d]: profile=%s width=%d height=%d\n"
+ "%lld %d AVE %s: %p %lld AuxiliaryLayerProperties num=%d"
+ "%lld %d AVE %s: %p %lld AuxiliaryLayerProperties num=%d\n"
+ "%lld %d AVE %s: %p %lld EncodesAuxiliaryWithAuxID=%d"
+ "%lld %d AVE %s: %p %lld EncodesAuxiliaryWithAuxID=%d\n"
+ "%lld %d AVE %s: %p %lld HEVCAuxiliaryIDs [%d] %d"
+ "%lld %d AVE %s: %p %lld HEVCAuxiliaryIDs [%d] %d\n"
+ "%lld %d AVE %s: %p %lld HEVCAuxiliaryIDs num=%d"
+ "%lld %d AVE %s: %p %lld HEVCAuxiliaryIDs num=%d\n"
+ "%lld %d AVE %s: %p %lld HEVCAuxiliaryLayerIDs [%d] %d"
+ "%lld %d AVE %s: %p %lld HEVCAuxiliaryLayerIDs [%d] %d\n"
+ "%lld %d AVE %s: %p %lld HEVCAuxiliaryLayerIDs num=%d"
+ "%lld %d AVE %s: %p %lld HEVCAuxiliaryLayerIDs num=%d\n"
+ "%lld %d AVE %s: %s:%d %s | DPB size overflow %d %d %d %d %d %d %d %d %lld"
+ "%lld %d AVE %s: %s:%d %s | DPB size overflow %d %d %d %d %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s:%d %s | EncType mismatch with session %p %lld %d %d %d"
+ "%lld %d AVE %s: %s:%d %s | EncType mismatch with session %p %lld %d %d %d\n"
+ "%lld %d AVE %s: %s:%d %s | HSCOutput size overflow %d %d %d %d %d %d %d %lld"
+ "%lld %d AVE %s: %s:%d %s | HSCOutput size overflow %d %d %d %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s:%d %s | LRB size overflow %d %d %d %d %d %d %d %d %lld"
+ "%lld %d AVE %s: %s:%d %s | LRB size overflow %d %d %d %d %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s:%d %s | MCTFOutput size overflow %d %d %d %d %d %d %d %lld"
+ "%lld %d AVE %s: %s:%d %s | MCTFOutput size overflow %d %d %d %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s:%d %s | frame dimension out of range %p %lld %d %d %d %lld"
+ "%lld %d AVE %s: %s:%d %s | frame dimension out of range %p %lld %d %d %d %lld\n"
+ "%lld %d AVE %s: %s:%d %s | invalid L%d%c low res ref firmware buffer in direct mode %p %d %lld %p %lld | %d %p"
+ "%lld %d AVE %s: %s:%d %s | invalid L%d%c low res ref firmware buffer in direct mode %p %d %lld %p %lld | %d %p\n"
+ "%lld %d AVE %s: %s:%d %s | invalid L%d%c ref firmware buffer in direct mode %p %d %lld %p %lld | %d %p"
+ "%lld %d AVE %s: %s:%d %s | invalid L%d%c ref firmware buffer in direct mode %p %d %lld %p %lld | %d %p\n"
+ "%lld %d AVE %s: %s:%d %s | invalid LRMERC result in direct encode mode %p %d %lld %p %lld | %d"
+ "%lld %d AVE %s: %s:%d %s | invalid LRMERC result in direct encode mode %p %d %lld %p %lld | %d\n"
+ "%lld %d AVE %s: %s:%d %s | pixel area overflow %d %d %d %d %lld"
+ "%lld %d AVE %s: %s:%d %s | pixel area overflow %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s:%d %s | size overflow %d %d %d %d %lld"
+ "%lld %d AVE %s: %s:%d %s | size overflow %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s:%d %s | size overflow %d %d %d %lld"
+ "%lld %d AVE %s: %s:%d %s | size overflow %d %d %d %lld\n"
+ "%lld %d AVE %s: %s:%d %s | size overflow %d %d %d %lld %lld"
+ "%lld %d AVE %s: %s:%d %s | size overflow %d %d %d %lld %lld\n"
+ "%lld %d AVE %s: %s:%d %s | size overflow %d %d %lld"
+ "%lld %d AVE %s: %s:%d %s | size overflow %d %d %lld\n"
+ "%lld %d AVE %s: %s:%d %s | size overflow %d %d %lld %lld"
+ "%lld %d AVE %s: %s:%d %s | size overflow %d %d %lld %lld\n"
+ "%lld %d AVE %s: %s:%d %s | slice number is out of range %p %lld %d %d [%d %d]"
+ "%lld %d AVE %s: %s:%d %s | slice number is out of range %p %lld %d %d [%d %d]\n"
+ "%lld %d AVE %s: %s::%s:%d %s | invalid command slot %p %d %p %p %d %p %d [0, %d)"
+ "%lld %d AVE %s: %s::%s:%d %s | invalid command slot %p %d %p %p %d %p %d [0, %d)\n"
+ "%p %lld AuxLayer[%d]: profile=%s width=%d height=%d"
+ "%p %lld AuxLayer[%d]: profile=%s width=%d height=%d\n"
+ "%p %lld AuxiliaryLayerProperties num=%d"
+ "%p %lld AuxiliaryLayerProperties num=%d\n"
+ "%p %lld EncodesAuxiliaryWithAuxID=%d"
+ "%p %lld EncodesAuxiliaryWithAuxID=%d\n"
+ "%p %lld HEVCAuxiliaryIDs [%d] %d"
+ "%p %lld HEVCAuxiliaryIDs [%d] %d\n"
+ "%p %lld HEVCAuxiliaryIDs num=%d"
+ "%p %lld HEVCAuxiliaryIDs num=%d\n"
+ "%p %lld HEVCAuxiliaryLayerIDs [%d] %d"
+ "%p %lld HEVCAuxiliaryLayerIDs [%d] %d\n"
+ "%p %lld HEVCAuxiliaryLayerIDs num=%d"
+ "%p %lld HEVCAuxiliaryLayerIDs num=%d\n"
+ "0 <= fwCmdSlot && fwCmdSlot < (AVE_Cmd_Max + (((3 + 2) + 2 + 5 + (2 + 1)) * ((2) < ((63 + 1)) ? (2) : ((63 + 1)))))"
+ "0 <= pInfo->sSessionCfg.sEnc.sSliceMap.iNum && pInfo->sSessionCfg.sEnc.sSliceMap.iNum <= ((32) < (256) ? (32) : (256))"
+ "11121111111111111111111111111111111122222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222121222222222222222222222222222222222222222222222222222222222222222222"
+ "21:36:33"
+ "913.29.1"
+ "AVE_CalcBufSizeOfColoFwDataInfo"
+ "AVE_CalcBufSizeOfColocated"
+ "AVE_CalcBufSizeOfDPB"
+ "AVE_CalcBufSizeOfEntropyCoding"
+ "AVE_CalcBufSizeOfEntropyCodingHeader"
+ "AVE_CalcBufSizeOfHSCOutput"
+ "AVE_CalcBufSizeOfLFSOutput"
+ "AVE_CalcBufSizeOfLRB"
+ "AVE_CalcBufSizeOfLRSOutput"
+ "AVE_CalcBufSizeOfMBInputCtrl"
+ "AVE_CalcBufSizeOfMBStats"
+ "AVE_CalcBufSizeOfMCTFOutput"
+ "AVE_CalcBufSizeOfSTFSrcNeighborInfo"
+ "AVE_CalcBufSizeOfSrcNeighborAboveFltPixel"
+ "AVE_CalcBufSizeOfSrcNeighborData"
+ "AVE_CalcBufSizeOfSrcNeighborFwData"
+ "AVE_CalcBufSizeOfSrcNeighborInfo"
+ "AVE_CalcBufSizeOfSrcNeighborLeftInfo"
+ "AVE_CalcBufSizeOfSrcNeighborLeftPixel"
+ "AVE_CalcBufSizeOfSrcNeighborPixel"
+ "AVE_CalcBufSizeOfStaticAreaCBP0Cntr"
+ "Jul 14 2026"
+ "iLumaDataSize >= 0 && iLumaHeaderSize >= 0 && iChromaDataSize >= 0 && iChromaHeaderSize >= 0 && iTotal <= 2147483647"
+ "iPixelArea >= 0 && iPixelArea <= 2147483647"
+ "iSize >= 0 && iSize <= 2147483647"
+ "pInfo->sSessionCfg.sEnc.eType == pClient->eEncType"
+ "size >= 0 && size <= 2147483647"
+ "width >= 0 && height >= 0 && iPixelProduct <= 2147483647"
- "%lld %d AVE %s: %s:%d %s | slice number is out of range %p %lld %d %d (%d %d]"
- "%lld %d AVE %s: %s:%d %s | slice number is out of range %p %lld %d %d (%d %d]\n"
- "0 < pInfo->sSessionCfg.sEnc.sSliceMap.iNum && pInfo->sSessionCfg.sEnc.sSliceMap.iNum <= ((32) < (256) ? (32) : (256))"
- "111211111111111111122222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222121222222222222222222222222222222222222222222222222222222222222222222"
- "21:20:05"
- "913.8.0"
- "Jun 29 2026"
```
