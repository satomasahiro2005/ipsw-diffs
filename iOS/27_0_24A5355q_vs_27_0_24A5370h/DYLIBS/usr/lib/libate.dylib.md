## libate.dylib

> `/usr/lib/libate.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b588` | `0x3bd98` | **`+0x810`** |
| `__TEXT.__cstring` | `0x1b2e` | `0x1ba8` | **`+0x7a`** |
| `__TEXT.__unwind_info` | `0x370` | `0x378` | **`+0x8`** |

### Other Changes

```diff

-3.0.9.0.0
+3.0.10.0.0

-  CStrings:  135
+  CStrings:  136
Functions:
~ _GetBlockInfo : 28 -> 24
~ _at_encoder_create : 524 -> 520
~ _GetTexelInfo : 28 -> 24
~ _GetDualPartitionPatterns : 72 -> 60
~ _freePartitionTables2D : 92 -> 100
~ __ZL9EncodeRowPvmPh : 1280 -> 1300
~ __ZL9EncodeRowPvmPh : 956 -> 948
~ __ZL9ReadBlockPK10SliceStateP13Block_storagePKvPKmml : 476 -> 468
~ __ZL9ReadBlockPK10SliceStateP13Block_storagePKvPKmml : 452 -> 444
~ __ZL19FillBlockStorageRowPK10SliceStateP13Block_storageS3_S3_llPKvPml : 1132 -> 996
~ _EncodeASTC_4x4_RGBA_vec : 800 -> 808
~ __ZL16FindColorVectorsDv8_fPKDv4_fitP26SinglePartitionWeightsInfo : 4460 -> 4384
~ _WeightInfoForSingleLineSingleWeight_4x4 : 100 -> 96
~ _WeightInfoForSingleLineSingleWeight : 404 -> 388
~ __ZL28CheckForReducedColorFidelityP26SinglePartitionWeightsInfoDv4_ftiDv8_fPhPfS4_ : 360 -> 352
~ _EncodeBasicBlock_4x4 : 22668 -> 22700
~ _WeightInfoForSingleLineDualWeight_4x4 : 100 -> 96
~ _WeightInfoForSingleLineDualWeight : 188 -> 176
~ __ZL32EncodeStandardDualPartitionBlockPK9Block_4x4fP28DualPartitionBlockEncodeDataPK20DualPartitionPattern : 15772 -> 15740
~ _GetDualPartitionBlockInfo : 112 -> 108
~ __ZN9ATEncoder16GetBlockFeaturesE17at_block_format_tP17at_block_buffer_t9at_size_tmPm10at_flags_t : 616 -> 648
~ _DecodeASTC_RGBA_vec : 6684 -> 6664
~ __ZL16BlockFeatureScanPvm : 2384 -> 2372
~ _ClampPremultiplied_vec : 172 -> 168
~ _at_encoder_get_version : 272 -> 280
~ _decode_bc3 : 652 -> 648
~ _decode_bc4 : 400 -> 396
~ _decode_bc5 : 684 -> 676
~ _decode_bc6 : 1972 -> 1976
~ _decode_bc7 : 2028 -> 2040
~ _WeightInfoForSingleLineSingleWeight_6x5 : 100 -> 96
~ _WeightInfoForSingleLineDualWeight_6x5 : 100 -> 96
~ _GetDualPartitionBlockInfo_6x5 : 112 -> 108
~ _GetDualPartitionDualWeightBlockInfo : 112 -> 108
~ __ZNK9D3DX_BC6H8RoughMSEEPNS_12EncodeParamsE : 292 -> 288
~ __ZN9D3DX_BC6H6RefineEPNS_12EncodeParamsE : 784 -> 792
~ __ZN9D3DX_BC6H12EndPointsFitEPKNS_12EncodeParamsEPK13INTEndPntPair : 768 -> 772
~ __ZNK9D3DX_BC6H24GeneratePaletteQuantizedEPKNS_12EncodeParamsERK13INTEndPntPairP8INTColor : 576 -> 588
~ __ZNK9D3DX_BC6H10PerturbOneEPKNS_12EncodeParamsEPK8INTColormhRK13INTEndPntPairRS6_fi : 476 -> 472
~ __ZNK9D3DX_BC6H11OptimizeOneEPKNS_12EncodeParamsEPK8INTColormfRK13INTEndPntPairRS6_ : 436 -> 380
~ __ZNK9D3DX_BC6H17OptimizeEndPointsEPKNS_12EncodeParamsEPKfPK13INTEndPntPairPS5_ : 272 -> 268
~ __ZN9D3DX_BC6H11SwapIndicesEPKNS_12EncodeParamsEP13INTEndPntPairPm : 196 -> 184
~ __ZNK9D3DX_BC6H13AssignIndicesEPKNS_12EncodeParamsEPK13INTEndPntPairPmPf : 456 -> 436
~ __ZNK9D3DX_BC6H14QuantizeEndPtsEPKNS_12EncodeParamsEP13INTEndPntPair : 748 -> 756
~ __ZN9D3DX_BC6H9EmitBlockEPKNS_12EncodeParamsEPK13INTEndPntPairPKm : 476 -> 472
~ __ZN9D3DX_BC6H26GeneratePaletteUnquantizedEPKNS_12EncodeParamsEmP8INTColor : 244 -> 256
~ __ZNK9D3DX_BC6H9MapColorsEPKNS_12EncodeParamsEmmPKm : 336 -> 332
~ __ZL11OptimizeRGBPK9HDRColorAPS_S2_jmPKm : 1156 -> 1172
~ __ZN8D3DX_BC76EncodeEjPK9HDRColorA : 1508 -> 1520
~ __ZN8D3DX_BC78RoughMSEEPNS_12EncodeParamsEmm : 2580 -> 2520
~ __ZN8D3DX_BC76RefineEPKNS_12EncodeParamsEmmm : 540 -> 552
~ __ZNK8D3DX_BC724GeneratePaletteQuantizedEPKNS_12EncodeParamsEmRK13LDREndPntPairP9LDRColorA : 336 -> 340
~ __ZNK8D3DX_BC710PerturbOneEPKNS_12EncodeParamsEPK9LDRColorAmmmRK13LDREndPntPairRS6_fh : 376 -> 380
~ __ZNK8D3DX_BC79MapColorsEPKNS_12EncodeParamsEPK9LDRColorAmmRK13LDREndPntPairf : 252 -> 276
~ __ZNK8D3DX_BC710ExhaustiveEPKNS_12EncodeParamsEPK9LDRColorAmmmRfR13LDREndPntPair : 736 -> 740
~ __ZNK8D3DX_BC711OptimizeOneEPKNS_12EncodeParamsEPK9LDRColorAmmfRK13LDREndPntPairRS6_ : 676 -> 680
~ __ZNK8D3DX_BC717OptimizeEndPointsEPKNS_12EncodeParamsEmmPKfPK13LDREndPntPairPS5_ : 292 -> 284
~ __ZNK8D3DX_BC713AssignIndicesEPKNS_12EncodeParamsEmmP13LDREndPntPairPjS5_Pf : 788 -> 736
~ __ZN8D3DX_BC79EmitBlockEPKNS_12EncodeParamsEmmmPK13LDREndPntPairPKjS7_ : 1172 -> 1188
~ __ZN8D3DX_BC716FixEndpointPBitsEPKNS_12EncodeParamsEPK13LDREndPntPairPS3_ : 980 -> 992
~ _encode_bc4 : 172 -> 204
~ __ZL16FindClosestUNORMP9BC4_UNORMPKf : 256 -> 244
~ _encode_bc5 : 220 -> 244
~ __Z13OptimizeAlphaILb0EEvPfS0_PKfj : 664 -> 660
~ _EncodeDXTC_BC7_vec : 14344 -> 14336
~ __ZL22FindDualPartitions_4x4tt : 408 -> 364
~ __ZL32EncodeStandardDualPartitionBlockPK9Block_4x4fP31DualPartitionBlockEncodeData_DXPK20DualPartitionPatternt : 9048 -> 9072
~ __ZL21CheckPartitionRow_4x4PDv4_tPDv4_iS2_PKS_PKstt : 420 -> 408
~ _Read_8x8_RGBA8_vec : 304 -> 332
~ _Read_8x8_BGRA8_vec : 304 -> 332
~ _Read_8x8_RA8_vec : 268 -> 304
~ _Read_8x8_R8_vec : 220 -> 256
~ _Read_8x8_R16_vec : 216 -> 252
~ _Read_8x8_RA16_vec : 204 -> 236
~ _Read_8x8_RGBA16_vec : 264 -> 292
~ _Read_8x8_Rf16_vec : 424 -> 460
~ _Read_8x8_RAf16_vec : 316 -> 344
~ _Read_8x8_RGBAf16_vec : 296 -> 324
~ _SetAlphaOne_8x8_vec : 768 -> 844
~ _FlattenNon_8x8_vec : 916 -> 1020
~ _FlattenPre_8x8_vec : 928 -> 1032
~ _Premultiply_8x8_vec : 788 -> 892
~ _Unpremultiply_8x8_vec : 724 -> 800
~ _ClampPremultiplied_8x8_vec : 752 -> 828
~ _PassThrough_8x8_vec : 680 -> 752
~ _Write_R8_vec : 156 -> 164
~ _Write_RA8_vec : 172 -> 176
~ _Write_RGBA8_vec : 112 -> 116
~ _Write_BGRA8_vec : 140 -> 144
~ _Write_R16_vec : 136 -> 140
~ _Write_RA16_vec : 156 -> 160
~ _Write_RGBA16_vec : 88 -> 92
~ _Write_Rf16_vec : 772 -> 768
~ _Write_RGBAf16_vec : 188 -> 192
~ _FlattenNon_vec : 224 -> 220
~ _FlattenPre_vec : 292 -> 288
~ _Premultiply_vec : 212 -> 208
~ _Unpremultiply_vec : 236 -> 232
~ _SetAlphaOne_vec : 64 -> 68
~ _EncodeASTC_8x8_RGBA_vec : 71476 -> 72856
~ _FindQuantizedColors : 4136 -> 4148
~ _at_texel_format_to_MTLPixelFormat : 28 -> 24
~ _at_block_format_to_MTLPixelFormat : 28 -> 24
~ _DecodeIntegerSequenceEncoding : 688 -> 720
~ __ZL9EncodeBC1P8D3DX_BC1PKDv4_fbfj : 2224 -> 2236
~ _encode_bc2 : 228 -> 232
~ _encode_bc3 : 940 -> 952
~ _Unpremultiply_8x8_vec.cold.1 : 200 -> 232
CStrings:
+ "at_block_get_features Error: src->sliceBytes (%lu) is less than what is required to store a slice of content (%lu bytes)\n"
```
