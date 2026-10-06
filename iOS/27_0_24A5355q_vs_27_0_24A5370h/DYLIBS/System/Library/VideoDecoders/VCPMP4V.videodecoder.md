## VCPMP4V.videodecoder

> `/System/Library/VideoDecoders/VCPMP4V.videodecoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21344` | `0x215ac` | **`+0x268`** |
| `__TEXT.__eh_frame` | `0x48` | `0xa0` | **`+0x58`** |

### Other Changes

```diff
Symbols:
+ __ZNSt3__117__call_once_proxyB9fqe220106INS_5tupleIJOZ15VCPMP4VRegisterE3$_0EEEEEvPv
+ __ZNSt3__117__call_once_proxyB9fqe220106INS_5tupleIJOZ23VCPMP4VRegisterInternalE3$_0EEEEEvPv
- __ZNSt3__117__call_once_proxyB9fqe220100INS_5tupleIJOZ15VCPMP4VRegisterE3$_0EEEEEvPv
- __ZNSt3__117__call_once_proxyB9fqe220100INS_5tupleIJOZ23VCPMP4VRegisterInternalE3$_0EEEEEvPv
Functions:
~ __Z6FillMBPhS_t : 64 -> 68
~ __Z8MC_1H_1VPhiPKhiPKsS1_ : 240 -> 224
~ __Z8MC_2H_1VPhiPKhiPKsiS1_ : 268 -> 288
~ __Z8MC_1H_2VPhiPKhiPKsiS1_ : 224 -> 232
~ __Z8MC_2H_2VPhiPKhiPKsiS1_ : 412 -> 404
~ __Z16AddResidueTo_8x8PsPhS0_iPKh : 232 -> 208
~ __Z11Get_HalfPelPhiiiiiS_ : 680 -> 676
~ __Z18AddResidueTo_16x16PsPhS0_iPKh : 424 -> 376
~ __Z15SetBlockToFramePhiS_i : 52 -> 56
~ __Z15GetBlockToFramePhiS_i : 52 -> 56
~ __Z18GetResidueFrom_8x8PsPhS0_i : 168 -> 184
~ __Z16GetResidue_16x16PsPhS0_iS0_ihhhiPKh : 488 -> 504
~ __Z6MC_8x8PhiS_iiiiS_S_ : 448 -> 556
~ __ZL19Get_QuarterPel_MSFTPhiiiiPKhiS_ : 1144 -> 1168
~ __Z11Blinear_8thPhiiiiiS_ : 3300 -> 3228
~ __Z15Get8x8From16x16PsiS_ : 64 -> 76
~ __Z14Feed8x8To16x16PsiS_ : 64 -> 76
~ __Z16InterpolateFramePhS_S_iiiiil : 4908 -> 5364
~ __ZL18Get_HalfPel_BottomPhS_iiPKhh : 1104 -> 1116
~ _GetPredictor1MV : 184 -> 196
~ _GetPredictor4MV : 352 -> 392
~ __Z12DecHeaderVOLP14CBitStreamDecoP13INSTANCE_DECO : 4648 -> 4652
~ __ZL35DefineVOPComplexityEstimationHeaderP14CBitStreamDecoP12picture_info : 3692 -> 3688
~ __Z12DecHeaderVOPP14CBitStreamDecoP13INSTANCE_DECO : 1780 -> 1792
~ __ZL33ReadVOPComplexityEstimationHeaderP14CBitStreamDecoP13INSTANCE_DECO : 12600 -> 12596
~ __Z16DecMotionVectorsPsS_S_S_S_S_S_S_iiihhhP12picture_infoP14CBitStreamDecoi : 940 -> 968
~ __ZN15CIntraDcDecoderC2Ev : 228 -> 244
~ __Z19InitEncUMVMVDTablesPP15ENCUMVMVDTABLES : 324 -> 316
~ __Z22InitDecodeUMVMVDTablesPP18DECODEUMVMVDTABLES : 540 -> 556
~ __ZN15CIntraPredictor17ResetUpPredictorsEii : 44 -> 52
~ __ZN15CIntraPredictor19ResetUpPredictorsMbEi : 92 -> 104
~ __ZN15CIntraPredictor17ResetPredictorsMbEi : 164 -> 196
~ __ZN15CIntraPredictor20ResetPredictorsMbAllEv : 112 -> 148
~ __ZN15CIntraPredictor18DumpLeftPredictorsEPc : 212 -> 220
~ __Z10idct1DC1ACPsS_jj : 1796 -> 1948
~ __Z12IDct8x8smartPhiPsiiS_ : 1212 -> 1228
~ __Z9IDCT_W8H8PsjPh : 1144 -> 1240
~ __Z15Y420ToY422_yuvsPhS_S_PittttiS_S_ : 280 -> 268
~ __Z15Y420ToY422_2vuyPhS_S_PittttiS_S_ : 288 -> 276
~ __ZL30MPEG4VideoDecoder_StartSessionP20OpaqueVTVideoDecoderP27OpaqueVTVideoDecoderSessionPK25opaqueCMFormatDescription : 1552 -> 1540
~ __ZL13unpack_headerPPKhhS1_ : 140 -> 148
~ __ZL23S_DeblockPlaneFastSmartP13INSTANCE_DECOP9buffer_u8S2_i : 664 -> 648
~ __ZL18S_DeblockPlaneFastP13INSTANCE_DECOP9buffer_u8PK19PostFilterSemaphorej : 208 -> 184
~ __Z15DeringFrameFastP5framePK19PostFilterSemaphore : 1172 -> 1168
~ __Z14DeringBlockAllPhjh : 368 -> 372
~ __Z11DeringBlockPhjhj : 796 -> 828
~ __ZL13S_DeblockEdgeP13INSTANCE_DECOPhjjj : 976 -> 956
~ __Z18InitIntraPredictorPP15intra_predictort : 376 -> 392
~ __Z18KillIntraPredictorPP15intra_predictor : 148 -> 172
~ __Z11CheapyReconP15intra_predictorPsi : 96 -> 84
~ __Z14ReconAndUpdateP15intra_predictorPsiiiii : 508 -> 488
~ __Z10UpdateACUpP15intra_predictorPsiii : 60 -> 52
~ __Z12UpdateACLeftP15intra_predictorPsiii : 52 -> 48
~ __Z18ResetAtBoundaryTopP15intra_predictori : 132 -> 120
~ __Z19ResetAtBoundaryLeftP15intra_predictori : 188 -> 180
~ __Z14ResetAtInterMBP15intra_predictori : 120 -> 112
~ __Z17Set_blockIsOpaqueP27MacroBlock_data_partitionedPh : 76 -> 72
~ __Z19Check_blockIsOpaqueP27MacroBlock_data_partitionedPh : 40 -> 36
~ __Z26RecoverMissingVideoPacketsP5frameS0_iiP13INSTANCE_DECO : 476 -> 568
~ __Z13DecodeMBInteriiPsS_hP16macroblock_stuffP13INSTANCE_DECO : 1348 -> 1308
~ __ZL16ReadAVideoPacketPihP5frameS1_P13INSTANCE_DECO : 9624 -> 9492
~ __ZL16DecodeBlockIntraiP16macroblock_stuffP13INSTANCE_DECO : 1380 -> 1368
~ __ZL21GrabBlockAndIQuantiseP16macroblock_stuffihP13INSTANCE_DECO : 1704 -> 1696
~ __ZL31DecodeBlockIntraDataPartitionedPhPsS0_S_iiiiihiiP13INSTANCE_DECOP15CIntraDcDecoderP14CBitStreamDeco : 472 -> 484
~ __ZL31DecodeBlockInterDataPartitionedPhPsS0_iiihiiP13INSTANCE_DECO : 2116 -> 2124
~ __ZL24GrabAcFromBitStreamIntraPsiiPhS0_hP14CBitStreamDeco : 2176 -> 2184
~ __Z18S_BuildGammaTablesPhS_ii : 836 -> 844
~ __Z8DrawGridP5frame : 224 -> 228
~ __Z15OutlineIntraMbsP5framePhP11source_info : 184 -> 180
~ __Z19OutlineVideoPacketsP5framePhP11source_info : 208 -> 200
~ __Z20HuffmanDecMcbpcIntraP14CBitStreamDeco : 456 -> 448
~ __Z20HuffmanDecMcbpcInterP14CBitStreamDeco : 712 -> 704
~ __Z13HuffmanDecMvdP14CBitStreamDeco : 740 -> 732
~ __Z14HuffmanDecCbpyP14CBitStreamDeco : 292 -> 284
~ __Z24HuffmanDecQCoefFastInterP14CBitStreamDeco : 436 -> 416
~ __Z25HuffmanDecQCoefFastInter2PjS_ : 120 -> 112
~ __Z24HuffmanDecQCoefFastIntraP14CBitStreamDeco : 436 -> 416
~ __Z25HuffmanDecQCoefFastIntra2PjS_ : 120 -> 112
~ __Z12RVLCDecQCoefP14CBitStreamDecoPK9MPEG4_VLC : 324 -> 320
~ __Z12DecWarpingMVP14CBitStreamDeco : 740 -> 736
~ __Z25DecBrightnessChangeFactorP14CBitStreamDeco : 700 -> 696
~ _IQuantizeBlockH263 : 124 -> 120
~ _IQuantizeBlockH263Opt : 184 -> 180
~ _IQuantizeBlockMPEG : 268 -> 256
~ __Z12MC_2H_1V_VecPhiPKhiPKsi : 80 -> 88
~ _InitFrame : 436 -> 440
~ _SideExtendBuffer_U8 : 584 -> 576
~ _SideExtendBuffer_S16 : 600 -> 520
~ _CopyU8BlockToFrame : 240 -> 232
~ _CopyS16BlockToFrame : 144 -> 140
~ _CopyToBuffer_U8 : 108 -> 96
~ _CopyToBuffer_S16 : 104 -> 96
~ _CopyFromBuffer_U8 : 132 -> 128
~ _CopyFromBuffer_S16 : 124 -> 128
~ _GetFrameYChannelMAD : 120 -> 124
~ _GetFramesYChannelDiffMAD : 260 -> 276
~ _GetFramesYChannelDiffPSNR : 172 -> 188
~ _SetBufferAllVal_U8 : 44 -> 40
~ _SetBufferAllVal_S16 : 28 -> 36
~ _SetFrameAllVal : 136 -> 124
~ _View_MV : 604 -> 588
~ _CopyChannelC2Y : 132 -> 136
```
