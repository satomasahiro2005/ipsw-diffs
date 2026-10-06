## AVD.videodecoder

> `/System/Library/VideoDecoders/AVD.videodecoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1784b4` | `0x1697d0` | **`-0xece4`** |
| `__AUTH_CONST.__const` | `0x53c0` | `0x4e40` | **`-0x580`** |
| `__TEXT.__const` | `0xc373` | `0xc1d3` | **`-0x1a0`** |
| `__TEXT.__gcc_except_tab` | `0xde0` | `0xd4c` | **`-0x94`** |
| `__TEXT.__cstring` | `0x5635` | `0x5681` | **`+0x4c`** |
| `__TEXT.__unwind_info` | `0x1de0` | `0x1da0` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x15fae` | `0x15fb9` | **`+0xb`** |
| `__AUTH_CONST.__auth_got` | `0x8c0` | `0x8b8` | **`-0x8`** |

### Other Changes

```diff

-988.0.0.0.0
+989.0.0.0.0

-  Functions: 4256
-  Symbols:   3495
-  CStrings:  2060
+  Functions: 4109
+  Symbols:   3337
+  CStrings:  2063
Symbols:
+ __ZNSt3__110unique_ptrI20AVDScaleMetalSessionNS_14default_deleteIS1_EEE5resetB9fqe220106EPS1_
+ __ZNSt3__110unique_ptrI22AVDDeblockMetalSessionNS_14default_deleteIS1_EEE5resetB9fqe220106EPS1_
+ __ZNSt3__110unique_ptrI25AVDBufferFillMetalSessionNS_14default_deleteIS1_EEE5resetB9fqe220106EPS1_
+ __ZNSt3__110unique_ptrI9AsyncInitNS_14default_deleteIS1_EEE5resetB9fqe220106EPS1_
+ __ZNSt3__111make_uniqueB9fqe220106I9AsyncInitJU13block_pointerFvvEELi0EEENS_10unique_ptrIT_NS_14default_deleteIS5_EEEEDpOT0_
+ __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220106Ev
- _VTDecoderSessionGetPixelBufferPool
- __ZL24Default_Comp_Bwd_Ref_Cdf
- __ZN15CAHDecNerineAvc11decHdrCSizeEj
- __ZN15CAHDecNerineAvc11decHdrYSizeEj
- __ZN15CAHDecNerineAvc11initPictureEjjb
- __ZN15CAHDecNerineAvc12decodeBufferEv
- __ZN15CAHDecNerineAvc12getSWRStrideEjjjj
- __ZN15CAHDecNerineAvc13decHdrCStrideEv
- __ZN15CAHDecNerineAvc13decHdrYStrideEv
- __ZN15CAHDecNerineAvc13getTileEndCTUEjj
- __ZN15CAHDecNerineAvc14decHdrCLinAddrEj
- __ZN15CAHDecNerineAvc14decHdrYLinAddrEj
- __ZN15CAHDecNerineAvc14populateSlicesEj
- __ZN15CAHDecNerineAvc14setVPInstrFifoEj
- __ZN15CAHDecNerineAvc15copyScalingListER15AvcScalingListsR13AvcQtMatCoeffPhS4_S4_i
- __ZN15CAHDecNerineAvc15freeWorkBuf_PPSEPv
- __ZN15CAHDecNerineAvc15freeWorkBuf_SPSEv
- __ZN15CAHDecNerineAvc15getTileIdxAboveEj
- __ZN15CAHDecNerineAvc15getTileStartCTUEjj
- __ZN15CAHDecNerineAvc15populateAvdWorkEj
- __ZN15CAHDecNerineAvc16allocWorkBuf_PPSEPvS0_S0_
- __ZN15CAHDecNerineAvc16allocWorkBuf_SPSEPv
- __ZN15CAHDecNerineAvc16decodeBufferSizeEv
- __ZN15CAHDecNerineAvc21updateCommonRegistersEj
- __ZN15CAHDecNerineAvc22populateSliceRegistersEP17AvcSliceRegistersi
- __ZN15CAHDecNerineAvc23populateCommonRegistersEv
- __ZN15CAHDecNerineAvc24populatePictureRegistersEv
- __ZN15CAHDecNerineAvc25AvcPicScalingListFallBackEP7sAvcSPSP7sAvcPPS
- __ZN15CAHDecNerineAvc25AvcSeqScalingListFallBackEP7sAvcSPS
- __ZN15CAHDecNerineAvc25populateSequenceRegistersEv
- __ZN15CAHDecNerineAvc4initEv
- __ZN15CAHDecNerineAvcC2EP14CAVDAvcDecoder
- __ZN15CAHDecNerineAvcD0Ev
- __ZN15CAHDecNerineAvcD1Ev
- __ZN15CAHDecNerineAvcD2Ev
- __ZN15CAHDecNerineAvx10isLfPadDisEv
- __ZN15CAHDecNerineAvx11decHdrCSizeEj
- __ZN15CAHDecNerineAvx11decHdrYSizeEj
- __ZN15CAHDecNerineAvx11initPictureEjjb
- __ZN15CAHDecNerineAvx12decodeBufferEv
- __ZN15CAHDecNerineAvx12startPictureEj
- __ZN15CAHDecNerineAvx13DecodePictureEjj
- __ZN15CAHDecNerineAvx13decHdrCStrideEv
- __ZN15CAHDecNerineAvx13decHdrYStrideEv
- __ZN15CAHDecNerineAvx13getTileEndCTUEjj
- __ZN15CAHDecNerineAvx13populateTilesEv
- __ZN15CAHDecNerineAvx14decHdrCLinAddrEj
- __ZN15CAHDecNerineAvx14decHdrYLinAddrEj
- __ZN15CAHDecNerineAvx14populateSlicesEj
- __ZN15CAHDecNerineAvx14setVPInstrFifoEj
- __ZN15CAHDecNerineAvx15freeWorkBuf_PPSEPv
- __ZN15CAHDecNerineAvx15freeWorkBuf_SPSEv
- __ZN15CAHDecNerineAvx15getTileIdxAboveEj
- __ZN15CAHDecNerineAvx15getTileStartCTUEjj
- __ZN15CAHDecNerineAvx15populateAvdWorkEj
- __ZN15CAHDecNerineAvx16allocWorkBuf_PPSEPvS0_S0_
- __ZN15CAHDecNerineAvx16allocWorkBuf_SPSEPv
- __ZN15CAHDecNerineAvx16decodeBufferSizeEv
- __ZN15CAHDecNerineAvx17getPPSWorkBufSizeEPvS0_
- __ZN15CAHDecNerineAvx18populateClearTilesEv
- __ZN15CAHDecNerineAvx20getUpscaleConvolveX0Eiii
- __ZN15CAHDecNerineAvx21populateTileRegistersEP16AvxTileRegistersj
- __ZN15CAHDecNerineAvx21updateCommonRegistersEj
- __ZN15CAHDecNerineAvx22calc_az_left_tile_sizeEiiiiiiii
- __ZN15CAHDecNerineAvx22calc_lf_left_tile_sizeEiiiiiiiii
- __ZN15CAHDecNerineAvx22calc_lr_left_tile_sizeEiiiiiiiii
- __ZN15CAHDecNerineAvx22getUpscaleConvolveStepEii
- __ZN15CAHDecNerineAvx22ppsWorkBufSizeIncreaseEPvS0_
- __ZN15CAHDecNerineAvx23populateAvxVPDependencyEv
- __ZN15CAHDecNerineAvx23populateCommonRegistersEv
- __ZN15CAHDecNerineAvx24populateAddressRegistersEv
- __ZN15CAHDecNerineAvx24populatePictureRegistersEv
- __ZN15CAHDecNerineAvx25populateSequenceRegistersEv
- __ZN15CAHDecNerineAvx27calc_lf_above_pix_tile_sizeEiiiiiiii
- __ZN15CAHDecNerineAvx27populateDecryptionRegistersEv
- __ZN15CAHDecNerineAvx4initEv
- __ZN15CAHDecNerineAvxC2EP14CAVDAvxDecoder
- __ZN15CAHDecNerineAvxD0Ev
- __ZN15CAHDecNerineAvxD1Ev
- __ZN15CAHDecNerineAvxD2Ev
- __ZN15CAHDecNerineLgh11decHdrCSizeEj
- __ZN15CAHDecNerineLgh11decHdrYSizeEj
- __ZN15CAHDecNerineLgh11initPictureEjjb
- __ZN15CAHDecNerineLgh12decodeBufferEv
- __ZN15CAHDecNerineLgh12getSWRStrideEjjjj
- __ZN15CAHDecNerineLgh12startPictureEj
- __ZN15CAHDecNerineLgh13DecodePictureEj
- __ZN15CAHDecNerineLgh13decHdrCStrideEv
- __ZN15CAHDecNerineLgh13decHdrYStrideEv
- __ZN15CAHDecNerineLgh13getTileEndCTUEjj
- __ZN15CAHDecNerineLgh13populateTilesEv
- __ZN15CAHDecNerineLgh14clearSegBufferEv
- __ZN15CAHDecNerineLgh14decHdrCLinAddrEj
- __ZN15CAHDecNerineLgh14decHdrYLinAddrEj
- __ZN15CAHDecNerineLgh14populateSlicesEj
- __ZN15CAHDecNerineLgh14setVPInstrFifoEj
- __ZN15CAHDecNerineLgh15freeWorkBuf_PPSEPv
- __ZN15CAHDecNerineLgh15freeWorkBuf_SPSEv
- __ZN15CAHDecNerineLgh15getTileIdxAboveEj
- __ZN15CAHDecNerineLgh15getTileStartCTUEjj
- __ZN15CAHDecNerineLgh15populateAvdWorkEj
- __ZN15CAHDecNerineLgh16allocWorkBuf_PPSEPvS0_S0_
- __ZN15CAHDecNerineLgh16allocWorkBuf_SPSEPv
- __ZN15CAHDecNerineLgh16decodeBufferSizeEv
- __ZN15CAHDecNerineLgh21populateTileRegistersEP16LghTileRegisters
- __ZN15CAHDecNerineLgh21updateCommonRegistersEj
- __ZN15CAHDecNerineLgh23populateCommonRegistersEv
- __ZN15CAHDecNerineLgh24populatePictureRegistersEv
- __ZN15CAHDecNerineLgh25populateSequenceRegistersEv
- __ZN15CAHDecNerineLgh4initEv
- __ZN15CAHDecNerineLghC2EP14CAVDLghDecoder
- __ZN15CAHDecNerineLghD0Ev
- __ZN15CAHDecNerineLghD1Ev
- __ZN15CAHDecNerineLghD2Ev
- __ZN16CAHDecNerineHevc11decHdrCSizeEj
- __ZN16CAHDecNerineHevc11decHdrYSizeEj
- __ZN16CAHDecNerineHevc11initPictureEjjb
- __ZN16CAHDecNerineHevc12decodeBufferEv
- __ZN16CAHDecNerineHevc12getMVmemInfoEiP20_avd_client_mem_infoPj
- __ZN16CAHDecNerineHevc12getSWRStrideEjjjj
- __ZN16CAHDecNerineHevc13decHdrCStrideEv
- __ZN16CAHDecNerineHevc13decHdrYStrideEv
- __ZN16CAHDecNerineHevc13getTileEndCTUEjj
- __ZN16CAHDecNerineHevc14decHdrCLinAddrEj
- __ZN16CAHDecNerineHevc14decHdrYLinAddrEj
- __ZN16CAHDecNerineHevc14populateSlicesEj
- __ZN16CAHDecNerineHevc14setVPInstrFifoEj
- __ZN16CAHDecNerineHevc15copyScalingListER16HevcScalingListsR14HevcQtMatCoeffjR24hevc_scaling_list_data_t
- __ZN16CAHDecNerineHevc15freeWorkBuf_PPSEPv
- __ZN16CAHDecNerineHevc15freeWorkBuf_SPSEv
- __ZN16CAHDecNerineHevc15getTileIdxAboveEj
- __ZN16CAHDecNerineHevc15getTileStartCTUEjj
- __ZN16CAHDecNerineHevc15populateAvdWorkEj
- __ZN16CAHDecNerineHevc16allocWorkBuf_PPSEPvS0_S0_
- __ZN16CAHDecNerineHevc16allocWorkBuf_SPSEPv
- __ZN16CAHDecNerineHevc16decodeBufferSizeEv
- __ZN16CAHDecNerineHevc17getTileHdrMemInfoEiP17_Tile_hdr_buffs_t
- __ZN16CAHDecNerineHevc21updateCommonRegistersEj
- __ZN16CAHDecNerineHevc22populateSliceRegistersEP18HevcSliceRegistersi
- __ZN16CAHDecNerineHevc23populateCommonRegistersEv
- __ZN16CAHDecNerineHevc24populatePictureRegistersEv
- __ZN16CAHDecNerineHevc25populateSequenceRegistersEv
- __ZN16CAHDecNerineHevc4initEv
- __ZN16CAHDecNerineHevcD0Ev
- __ZN16CAHDecNerineHevcD1Ev
- __ZN16CAHDecNerineHevcD2Ev
- __ZNSt3__110unique_ptrI20AVDScaleMetalSessionNS_14default_deleteIS1_EEE5resetB9fqe220100EPS1_
- __ZNSt3__110unique_ptrI22AVDDeblockMetalSessionNS_14default_deleteIS1_EEE5resetB9fqe220100EPS1_
- __ZNSt3__110unique_ptrI25AVDBufferFillMetalSessionNS_14default_deleteIS1_EEE5resetB9fqe220100EPS1_
- __ZNSt3__110unique_ptrI9AsyncInitNS_14default_deleteIS1_EEE5resetB9fqe220100EPS1_
- __ZNSt3__111make_uniqueB9fqe220100I9AsyncInitJU13block_pointerFvvEELi0EEENS_10unique_ptrIT_NS_14default_deleteIS5_EEEEDpOT0_
- __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220100Ev
- __ZTI15CAHDecNerineAvc
- __ZTI15CAHDecNerineAvx
- __ZTI15CAHDecNerineLgh
- __ZTI16CAHDecNerineHevc
- __ZTS15CAHDecNerineAvc
- __ZTS15CAHDecNerineAvx
- __ZTS15CAHDecNerineLgh
- __ZTS16CAHDecNerineHevc
- __ZTV15CAHDecNerineAvc
- __ZTV15CAHDecNerineAvx
- __ZTV15CAHDecNerineLgh
- __ZTV16CAHDecNerineHevc
CStrings:
+ "19:45:42"
+ "19:45:43"
+ "19:45:44"
+ "AppleAVD: INFO: %{public}s(): Nerine AVD is not supported in this AppleAVD driver!!!\n"
+ "Jun 18 2026"
+ "createNerineAvcDecoder"
+ "createNerineAvxDecoder"
+ "createNerineHevcDecoder"
+ "createNerineLghDecoder"
- "21:33:49"
- "21:33:50"
- "21:33:51"
- "AppleAVD: ERROR: %{public}s(): VT Failed to get Pixel Buffer Pool! ERROR!\n"
- "Jun  1 2026"
- "~CAHDecNerineLgh"
```
