## Tungsten

> `/System/Library/PrivateFrameworks/Tungsten.framework/Tungsten`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfa344` | `0xfb564` | **`+0x1220`** |
| `__DATA.__bss` | `0x17a0` | `0x1ba0` | **`+0x400`** |
| `__TEXT.__const` | `0x3740` | `0x39c0` | **`+0x280`** |
| `__AUTH_CONST.__objc_const` | `0x22a68` | `0x22c40` | **`+0x1d8`** |
| `__TEXT.__swift5_typeref` | `0x1148` | `0x125e` | **`+0x116`** |
| `__TEXT.__objc_methlist` | `0x11b00` | `0x11c08` | **`+0x108`** |
| `__DATA_CONST.__objc_selrefs` | `0x7da8` | `0x7ea8` | **`+0x100`** |
| `__TEXT.__cstring` | `0xd69f` | `0xd758` | **`+0xb9`** |
| `__DATA.__data` | `0x26f0` | `0x2768` | **`+0x78`** |
| `__TEXT.__eh_frame` | `0x2a4` | `0x304` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x45c0` | `0x4620` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0xd58` | `0xd98` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x2583` | `0x25bb` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x34d4` | `0x3504` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0xe0` | `0x110` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x19c4` | `0x19e4` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xe40` | `0xe60` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x224` | `0x244` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x74` | `0x94` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xa75` | `0xa95` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x7b0` | `0x7c8` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__AUTH_CONST.__objc_floatobj` | `0x10` | `—` | **`-0x10`** |
| `__AUTH.__data` | `0x330` | `0x338` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x18` | `0x1c` | **`+0x4`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Functions: 6690
-  Symbols:   11582
-  CStrings:  1886
+  Functions: 6739
+  Symbols:   11622
+  CStrings:  1892
Symbols:
+ -[PXGColorProgram _generateLegacyProgramWithConversionInfo:cubeSize:cubeOnly:]
+ -[PXGColorProgram _generateMPSColorConversionWithConversionInfo:]
+ -[PXGColorProgram colorConversionFunction]
+ -[PXGColorProgram cube1]
+ -[PXGColorProgram cube2]
+ -[PXGColorProgram lut]
+ -[PXGColorProgram mpsColorConversion]
+ -[PXGColorProgram setMpsColorConversion:]
+ -[PXGDecoratingLayout disablesSelectionIndicator]
+ -[PXGDecoratingLayout lastScrollDirectionDidChange]
+ -[PXGDecoratingLayout scrollSpeedRegimeDidChange]
+ -[PXGDecoratingLayout setDisablesSelectionIndicator:]
+ -[PXGDisplayAssetTextureProvider noThumbnailPlaceholderImageDark]
+ -[PXGDisplayAssetTextureProvider noThumbnailPlaceholderImageLight]
+ -[PXGDisplayAssetTextureProvider setNoThumbnailPlaceholderImageDark:]
+ -[PXGDisplayAssetTextureProvider setNoThumbnailPlaceholderImageLight:]
+ -[PXGReusableAXInfo(PlatformSpecific) focusItemDeferralMode]
+ -[PXGTextureManager textureProviderForMediaKind:]
+ -[PXGView noThumbnailPlaceholderStyleOverride]
+ -[PXGView setNoThumbnailPlaceholderStyleOverride:]
+ GCC_except_table1345
+ GCC_except_table1354
+ GCC_except_table1374
+ GCC_except_table1394
+ GCC_except_table1420
+ GCC_except_table1452
+ GCC_except_table1532
+ GCC_except_table1566
+ GCC_except_table1573
+ GCC_except_table1598
+ GCC_except_table1722
+ GCC_except_table1858
+ GCC_except_table1871
+ GCC_except_table1874
+ GCC_except_table1879
+ GCC_except_table1885
+ GCC_except_table1929
+ GCC_except_table1938
+ GCC_except_table1956
+ GCC_except_table2085
+ GCC_except_table2103
+ GCC_except_table2170
+ GCC_except_table2176
+ GCC_except_table2193
+ GCC_except_table2246
+ GCC_except_table2397
+ GCC_except_table2414
+ GCC_except_table2428
+ GCC_except_table2433
+ GCC_except_table2450
+ GCC_except_table2698
+ GCC_except_table2700
+ GCC_except_table2704
+ GCC_except_table2744
+ GCC_except_table2747
+ GCC_except_table2751
+ GCC_except_table2753
+ GCC_except_table2757
+ GCC_except_table2792
+ GCC_except_table2800
+ GCC_except_table2802
+ GCC_except_table2821
+ GCC_except_table2884
+ GCC_except_table2938
+ GCC_except_table2954
+ GCC_except_table2961
+ GCC_except_table3288
+ GCC_except_table3496
+ GCC_except_table3498
+ GCC_except_table3519
+ GCC_except_table3532
+ GCC_except_table3552
+ GCC_except_table3606
+ GCC_except_table3610
+ GCC_except_table3632
+ GCC_except_table3675
+ GCC_except_table3777
+ GCC_except_table3787
+ GCC_except_table3811
+ GCC_except_table3911
+ GCC_except_table3915
+ GCC_except_table3943
+ GCC_except_table3950
+ GCC_except_table3976
+ GCC_except_table4074
+ GCC_except_table4229
+ GCC_except_table4231
+ GCC_except_table4252
+ GCC_except_table4265
+ GCC_except_table4267
+ GCC_except_table4269
+ GCC_except_table4273
+ GCC_except_table4305
+ GCC_except_table4308
+ GCC_except_table4313
+ GCC_except_table4316
+ GCC_except_table4335
+ GCC_except_table4376
+ GCC_except_table4388
+ GCC_except_table4467
+ GCC_except_table4503
+ GCC_except_table4505
+ GCC_except_table4580
+ GCC_except_table4670
+ GCC_except_table4796
+ GCC_except_table4851
+ GCC_except_table4853
+ GCC_except_table4855
+ GCC_except_table4859
+ GCC_except_table4861
+ GCC_except_table4984
+ GCC_except_table4995
+ GCC_except_table5011
+ GCC_except_table5013
+ GCC_except_table5017
+ GCC_except_table5151
+ GCC_except_table5211
+ GCC_except_table5269
+ GCC_except_table5290
+ GCC_except_table5324
+ GCC_except_table5325
+ GCC_except_table5359
+ GCC_except_table5594
+ GCC_except_table5596
+ GCC_except_table5598
+ GCC_except_table5600
+ GCC_except_table5601
+ GCC_except_table5602
+ GCC_except_table5603
+ GCC_except_table5606
+ GCC_except_table5611
+ GCC_except_table5623
+ GCC_except_table5626
+ GCC_except_table5627
+ GCC_except_table5628
+ GCC_except_table5630
+ GCC_except_table5631
+ GCC_except_table5632
+ GCC_except_table5633
+ GCC_except_table5636
+ GCC_except_table5652
+ GCC_except_table5653
+ GCC_except_table5655
+ GCC_except_table5656
+ GCC_except_table5657
+ GCC_except_table5659
+ GCC_except_table5665
+ GCC_except_table5666
+ GCC_except_table5676
+ GCC_except_table5678
+ GCC_except_table5685
+ GCC_except_table5705
+ GCC_except_table5706
+ GCC_except_table5707
+ GCC_except_table5708
+ GCC_except_table5709
+ GCC_except_table5710
+ GCC_except_table5711
+ GCC_except_table5714
+ GCC_except_table5715
+ GCC_except_table5716
+ GCC_except_table5717
+ GCC_except_table5718
+ GCC_except_table5720
+ GCC_except_table5781
+ GCC_except_table5790
+ _OBJC_CLASS_$_MPSFColorConversion
+ _OBJC_CLASS_$_MTLLinkedFunctions
+ _OBJC_IVAR_$_PXGColorProgram._cube1
+ _OBJC_IVAR_$_PXGColorProgram._cube2
+ _OBJC_IVAR_$_PXGColorProgram._lut
+ _OBJC_IVAR_$_PXGColorProgram._mpsColorConversion
+ _OBJC_IVAR_$_PXGDecoratingLayout._disablesSelectionIndicator
+ _OBJC_IVAR_$_PXGDisplayAssetTextureProvider._noThumbnailPlaceholderImageDark
+ _OBJC_IVAR_$_PXGDisplayAssetTextureProvider._noThumbnailPlaceholderImageLight
+ _OBJC_IVAR_$_PXGView._noThumbnailPlaceholderStyleOverride
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIi17PXGRequestDetailsEENS_22__unordered_map_hasherIiNS_4pairIKiS2_EENS_4hashIiEENS_8equal_toIiEEEENS_21__unordered_map_equalIiS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIijEENS_22__unordered_map_hasherIiNS_4pairIKijEENS_4hashIiEENS_8equal_toIiEEEENS_21__unordered_map_equalIiS6_SA_S8_EENS_9allocatorIS6_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS5_EEENSL_IJEEEEEENS4_INS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlSM_SK_OSN_OSO_E_clESM_SK_SZ_S10_
+ ___78-[PXGColorProgram _generateLegacyProgramWithConversionInfo:cubeSize:cubeOnly:]_block_invoke
+ ___78-[PXGColorProgram _generateLegacyProgramWithConversionInfo:cubeSize:cubeOnly:]_block_invoke_2
+ _associated conformance So19PXGColorProgramModeV15PhotoFoundation15SettingsCodable8TungstenSE
+ _associated conformance So19PXGColorProgramModeV15PhotoFoundation15SettingsCodable8TungstenSe
+ _associated conformance So19PXGColorProgramModeVSHSCSQ
+ _associated conformance So19PXGColorProgramModeVs12CaseIterable8Tungsten8AllCasessACP_Sl
+ _get_witness_table 7SwiftUI4FormVyAA12TupleContentVyAA7SectionVyAA4TextVAEyAA6ToggleVyAIG_AlEyAL_A14LQPGSgQPGAA9EmptyViewVG_AGyAiEyAA6PickerVyAISo28PXGTextLegibilityDimmingTypeVAA7ForEachVySayAVGAvIGG_18PhotosUIFoundation14SettingsSliderVy12CoreGraphics7CGFloatVGQPGAQGAGyAiEyAL_ALSgA3LA2_ySdGA10_A5LA10_A9lTyAISo19PXGColorProgramModeVAXySayA12_GA12_AIGGA2LA6_A6_A2LA10_A10_A10_AlTyAISo08PXScrollJ17SpeedometerRegimeVAXySayA17_GA17_AIGGA20_A20_ATyAISiAEyAA0J0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQOyAI_SiQo__A25_A25_A25_A25_QPGGATyAIA5_AEyA22_AAEA23__A24_Qrqd___SbtSHRd__lFQOyAI_SdQo__A28_A28_A28_QPGGA10_A2LQPGAQGAGyAiEyAL_A10_A2LQPGAQGAGyAiEyATyAISiAEyA25__A25_A25_A25_QPGG_A10_QPGAQGAGyAiEyAL_ALQPGAQGAGyAiEyAL_A3lTyAISiAEyA25__A25_A25_QPGGQPGAQGAGyAiEyAL_AEyA10__A10_A10_QPGSgQPGAQGAGyAilQGA49_A49_AGyAqA6ButtonVyAIGAQGQPGGAAA21_HPyHC
+ _kCGUse100nitsHLGOOTF
+ _kCGUseLegacyHDREcosystem
+ _symbolic Say_____G So19PXGColorProgramModeV
+ _symbolic _____ So19PXGColorProgramModeV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So19PXGColorProgramModeV
+ _symbolic _____y_____G_ACSgA3C_____ySdGAf5cf9C_____yAB__________ySayAHGAhBGGA2cEy_____GAn2c3fcGyAB_____AIySayAOGAoBGGA2rGyABSi_____y_____yAB_SiQo__A4TQPGGAGyAbmSy_____yAB_SdQo__A3WQPGGAf2Ct 7SwiftUI6ToggleV AA4TextV 18PhotosUIFoundation14SettingsSliderV AA6PickerV So19PXGColorProgramModeV AA7ForEachV 12CoreGraphics7CGFloatV So29PXScrollViewSpeedometerRegimeV AA12TupleContentV AA0S0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AwAEAX_AYQrqd___SbtSHRd__lFQO
+ _symbolic _____y__________G s15WritableKeyPathC 8Tungsten0D8SettingsC So19PXGColorProgramModeV
+ _symbolic _____y_______________ySayACGAcBGG 7SwiftUI6PickerV AA4TextV So19PXGColorProgramModeV AA7ForEachV
+ _symbolic _____y__________y_____yABG_AESgA3E_____ySdGAh5eh9E_____yAB__________ySayAJGAjBGGA2eGy_____GAp2e3heIyAB_____AKySayAQGAqBGGA2tIyABSiACy_____yAB_SiQo__A4UQPGGAIyAboCy_____yAB_SdQo__A3XQPGGAh2EQPG_____G 7SwiftUI7SectionV AA4TextV AA12TupleContentV AA6ToggleV 18PhotosUIFoundation14SettingsSliderV AA6PickerV So19PXGColorProgramModeV AA7ForEachV 12CoreGraphics7CGFloatV So29PXScrollViewSpeedometerRegimeV AA0V0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AyAEAZ_A_Qrqd___SbtSHRd__lFQO AA05EmptyV0V
+ _symbolic _____y__________y_____yABG_AeCyAE_A14EQPGSgQPG_____G_AAyAbCy_____yAB__________ySayALGAlBGG______y_____GQPGAIGAAyAbCyAE_AESgA3eQySdGAw5ew9eKyAB_____AMySayAXGAxBGGA2e2s2e3weKyAB_____AMySayA0_GA0_ABGGA3_A3_AKyABSiACy_____yAB_SiQo__A4_A4_A4_A4_QPGGAKyAbrCy_____yAB_SdQo__A7_A7_A7_QPGGAw2EQPGAIGAAyAbCyAE_Aw2EQPGAIGAAyAbCyAKyABSiACyA4__A4_A4_A4_QPGG_AWQPGAIGAAyAbCyAE_AEQPGAIGAAyAbCyAE_A3eKyABSiACyA4__A4_A4_QPGGQPGAIGAAyAbCyAE_ACyAW_A2WQPGSgQPGAIGAAyAbeIGA28_A28_AAyAI_____yABGAIGt 7SwiftUI7SectionV AA4TextV AA12TupleContentV AA6ToggleV AA9EmptyViewV AA6PickerV So28PXGTextLegibilityDimmingTypeV AA7ForEachV 18PhotosUIFoundation14SettingsSliderV 12CoreGraphics7CGFloatV So19PXGColorProgramModeV So08PXScrollI17SpeedometerRegimeV AA0I0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO A1_AAEA2__A3_Qrqd___SbtSHRd__lFQO AA6ButtonV
+ _symbolic _____y_____y_____AAy_____yACG_AeAyAE_A14EQPGSgQPG_____G_AByAcAy_____yAC__________ySayALGAlCGG______y_____GQPGAIGAByAcAyAE_AESgA3eQySdGAw5ew9eKyAC_____AMySayAXGAxCGGA2e2s2e3weKyAC_____AMySayA0_GA0_ACGGA3_A3_AKyACSiAAy_____yAC_SiQo__A4_A4_A4_A4_QPGGAKyAcrAy_____yAC_SdQo__A7_A7_A7_QPGGAw2EQPGAIGAByAcAyAE_Aw2EQPGAIGAByAcAyAKyACSiAAyA4__A4_A4_A4_QPGG_AWQPGAIGAByAcAyAE_AEQPGAIGAByAcAyAE_A3eKyACSiAAyA4__A4_A4_QPGGQPGAIGAByAcAyAE_AAyAW_A2WQPGSgQPGAIGAByAceIGA28_A28_AByAI_____yACGAIGQPG 7SwiftUI12TupleContentV AA7SectionV AA4TextV AA6ToggleV AA9EmptyViewV AA6PickerV So28PXGTextLegibilityDimmingTypeV AA7ForEachV 18PhotosUIFoundation14SettingsSliderV 12CoreGraphics7CGFloatV So19PXGColorProgramModeV So08PXScrollI17SpeedometerRegimeV AA0I0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO A1_AAEA2__A3_Qrqd___SbtSHRd__lFQO AA6ButtonV
+ _symbolic _____y_____y_____G_ADSgA3D_____ySdGAg5dg9D_____yAC__________ySayAIGAiCGGA2dFy_____GAo2d3gdHyAC_____AJySayAPGApCGGA2sHyACSiAAy_____yAC_SiQo__A4TQPGGAHyAcnAy_____yAC_SdQo__A3WQPGGAg2DQPG 7SwiftUI12TupleContentV AA6ToggleV AA4TextV 18PhotosUIFoundation14SettingsSliderV AA6PickerV So19PXGColorProgramModeV AA7ForEachV 12CoreGraphics7CGFloatV So29PXScrollViewSpeedometerRegimeV AA0U0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AwAEAX_AYQrqd___SbtSHRd__lFQO
+ _symbolic _____y_____y_____y_____ABy_____yADG_AfByAF_A14FQPGSgQPG_____G_ACyAdBy_____yAD__________ySayAMGAmDGG______y_____GQPGAJGACyAdByAF_AFSgA3fRySdGAx5fx9fLyAD_____ANySayAYGAyDGGA2f2t2f3xfLyAD_____ANySayA1_GA1_ADGGA4_A4_ALyADSiABy_____yAD_SiQo__A5_A5_A5_A5_QPGGALyAdsBy_____yAD_SdQo__A8_A8_A8_QPGGAx2FQPGAJGACyAdByAF_Ax2FQPGAJGACyAdByALyADSiAByA5__A5_A5_A5_QPGG_AXQPGAJGACyAdByAF_AFQPGAJGACyAdByAF_A3fLyADSiAByA5__A5_A5_QPGGQPGAJGACyAdByAF_AByAX_A2XQPGSgQPGAJGACyAdfJGA29_A29_ACyAJ_____yADGAJGQPGG 7SwiftUI4FormV AA12TupleContentV AA7SectionV AA4TextV AA6ToggleV AA9EmptyViewV AA6PickerV So28PXGTextLegibilityDimmingTypeV AA7ForEachV 18PhotosUIFoundation14SettingsSliderV 12CoreGraphics7CGFloatV So19PXGColorProgramModeV So08PXScrollJ17SpeedometerRegimeV AA0J0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO A3_AAEA4__A5_Qrqd___SbtSHRd__lFQO AA6ButtonV
- -[PXGColorProgram _compactProgramWithConversionInfo:cubeSize:cubeOnly:]
- GCC_except_table1343
- GCC_except_table1352
- GCC_except_table1372
- GCC_except_table1392
- GCC_except_table1418
- GCC_except_table1448
- GCC_except_table1528
- GCC_except_table1562
- GCC_except_table1565
- GCC_except_table1594
- GCC_except_table1718
- GCC_except_table1854
- GCC_except_table1863
- GCC_except_table1870
- GCC_except_table1875
- GCC_except_table1881
- GCC_except_table1925
- GCC_except_table1934
- GCC_except_table1952
- GCC_except_table2081
- GCC_except_table2099
- GCC_except_table2166
- GCC_except_table2172
- GCC_except_table2189
- GCC_except_table2242
- GCC_except_table2393
- GCC_except_table2410
- GCC_except_table2424
- GCC_except_table2429
- GCC_except_table2446
- GCC_except_table2693
- GCC_except_table2695
- GCC_except_table2699
- GCC_except_table2739
- GCC_except_table2742
- GCC_except_table2746
- GCC_except_table2748
- GCC_except_table2752
- GCC_except_table2787
- GCC_except_table2795
- GCC_except_table2797
- GCC_except_table2816
- GCC_except_table2879
- GCC_except_table2933
- GCC_except_table2949
- GCC_except_table2956
- GCC_except_table3278
- GCC_except_table3487
- GCC_except_table3489
- GCC_except_table3510
- GCC_except_table3523
- GCC_except_table3543
- GCC_except_table3597
- GCC_except_table3601
- GCC_except_table3623
- GCC_except_table3666
- GCC_except_table3768
- GCC_except_table3778
- GCC_except_table3802
- GCC_except_table3902
- GCC_except_table3906
- GCC_except_table3934
- GCC_except_table3941
- GCC_except_table3967
- GCC_except_table4065
- GCC_except_table4220
- GCC_except_table4222
- GCC_except_table4243
- GCC_except_table4251
- GCC_except_table4256
- GCC_except_table4258
- GCC_except_table4264
- GCC_except_table4296
- GCC_except_table4299
- GCC_except_table4304
- GCC_except_table4307
- GCC_except_table4326
- GCC_except_table4367
- GCC_except_table4379
- GCC_except_table4458
- GCC_except_table4494
- GCC_except_table4496
- GCC_except_table4571
- GCC_except_table4661
- GCC_except_table4787
- GCC_except_table4842
- GCC_except_table4844
- GCC_except_table4846
- GCC_except_table4850
- GCC_except_table4852
- GCC_except_table4975
- GCC_except_table4986
- GCC_except_table5002
- GCC_except_table5004
- GCC_except_table5008
- GCC_except_table5141
- GCC_except_table5201
- GCC_except_table5258
- GCC_except_table5279
- GCC_except_table5313
- GCC_except_table5314
- GCC_except_table5343
- GCC_except_table5559
- GCC_except_table5560
- GCC_except_table5562
- GCC_except_table5564
- GCC_except_table5565
- GCC_except_table5566
- GCC_except_table5568
- GCC_except_table5569
- GCC_except_table5571
- GCC_except_table5572
- GCC_except_table5573
- GCC_except_table5574
- GCC_except_table5575
- GCC_except_table5576
- GCC_except_table5581
- GCC_except_table5585
- GCC_except_table5588
- GCC_except_table5597
- GCC_except_table5612
- GCC_except_table5614
- GCC_except_table5618
- GCC_except_table5619
- GCC_except_table5620
- GCC_except_table5621
- GCC_except_table5624
- GCC_except_table5634
- GCC_except_table5641
- GCC_except_table5644
- GCC_except_table5645
- GCC_except_table5647
- GCC_except_table5648
- GCC_except_table5649
- GCC_except_table5669
- GCC_except_table5672
- GCC_except_table5673
- GCC_except_table5688
- GCC_except_table5689
- GCC_except_table5692
- GCC_except_table5695
- GCC_except_table5696
- GCC_except_table5701
- GCC_except_table5762
- GCC_except_table5771
- _OBJC_CLASS_$_NSConstantFloatNumber
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIi17PXGRequestDetailsEENS_22__unordered_map_hasherIiNS_4pairIKiS2_EENS_4hashIiEENS_8equal_toIiEEEENS_21__unordered_map_equalIiS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIijEENS_22__unordered_map_hasherIiNS_4pairIKijEENS_4hashIiEENS_8equal_toIiEEEENS_21__unordered_map_equalIiS6_SA_S8_EENS_9allocatorIS6_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJRS5_EEENSL_IJEEEEEENS4_INS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlSM_SK_OSN_OSO_E_clESM_SK_SZ_S10_
- ___71-[PXGColorProgram _compactProgramWithConversionInfo:cubeSize:cubeOnly:]_block_invoke
- ___71-[PXGColorProgram _compactProgramWithConversionInfo:cubeSize:cubeOnly:]_block_invoke_2
- _get_witness_table 7SwiftUI4FormVyAA12TupleContentVyAA7SectionVyAA4TextVAEyAA6ToggleVyAIG_AlEyAL_A14LQPGSgQPGAA9EmptyViewVG_AGyAiEyAA6PickerVyAISo28PXGTextLegibilityDimmingTypeVAA7ForEachVySayAVGAvIGG_18PhotosUIFoundation14SettingsSliderVy12CoreGraphics7CGFloatVGQPGAQGAGyAiEyAL_ALSgA3LA2_ySdGA10_A5LA10_A11LA6_A6_A2LA10_A10_A10_AlTyAISo08PXScrollJ17SpeedometerRegimeVAXySayA12_GA12_AIGGA15_A15_ATyAISiAEyAA0J0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQOyAI_SiQo__A20_A20_A20_A20_QPGGATyAIA5_AEyA17_AAEA18__A19_Qrqd___SbtSHRd__lFQOyAI_SdQo__A23_A23_A23_QPGGA10_A2LQPGAQGAGyAiEyAL_A10_A2LQPGAQGAGyAiEyATyAISiAEyA20__A20_A20_A20_QPGG_A10_QPGAQGAGyAiEyAL_ALQPGAQGAGyAiEyAL_A3lTyAISiAEyA20__A20_A20_QPGGQPGAQGAGyAiEyAL_AEyA10__A10_A10_QPGSgQPGAQGAGyAilQGA44_A44_AGyAqA6ButtonVyAIGAQGQPGGAAA16_HPyHC
- _symbolic _____y_____G_ACSgA3C_____ySdGAf5cf11cEy_____GAh2c3fC_____yAB__________ySayAJGAjBGGA2nIyABSi_____y_____yAB_SiQo__A4PQPGGAIyAbgOy_____yAB_SdQo__A3SQPGGAf2Ct 7SwiftUI6ToggleV AA4TextV 18PhotosUIFoundation14SettingsSliderV 12CoreGraphics7CGFloatV AA6PickerV So29PXScrollViewSpeedometerRegimeV AA7ForEachV AA12TupleContentV AA0N0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AuAEAV_AWQrqd___SbtSHRd__lFQO
- _symbolic _____y__________y_____yABG_AESgA3E_____ySdGAh5eh11eGy_____GAj2e3hE_____yAB__________ySayALGAlBGGA2pKyABSiACy_____yAB_SiQo__A4QQPGGAKyAbiCy_____yAB_SdQo__A3TQPGGAh2EQPG_____G 7SwiftUI7SectionV AA4TextV AA12TupleContentV AA6ToggleV 18PhotosUIFoundation14SettingsSliderV 12CoreGraphics7CGFloatV AA6PickerV So29PXScrollViewSpeedometerRegimeV AA7ForEachV AA0Q0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AwAEAX_AYQrqd___SbtSHRd__lFQO AA05EmptyQ0V
- _symbolic _____y__________y_____yABG_AeCyAE_A14EQPGSgQPG_____G_AAyAbCy_____yAB__________ySayALGAlBGG______y_____GQPGAIGAAyAbCyAE_AESgA3eQySdGAw5ew11e2s2e3weKyAB_____AMySayAXGAxBGGA_A_AKyABSiACy_____yAB_SiQo__A0_A0_A0_A0_QPGGAKyAbrCy_____yAB_SdQo__A3_A3_A3_QPGGAw2EQPGAIGAAyAbCyAE_Aw2EQPGAIGAAyAbCyAKyABSiACyA0__A0_A0_A0_QPGG_AWQPGAIGAAyAbCyAE_AEQPGAIGAAyAbCyAE_A3eKyABSiACyA0__A0_A0_QPGGQPGAIGAAyAbCyAE_ACyAW_A2WQPGSgQPGAIGAAyAbeIGA24_A24_AAyAI_____yABGAIGt 7SwiftUI7SectionV AA4TextV AA12TupleContentV AA6ToggleV AA9EmptyViewV AA6PickerV So28PXGTextLegibilityDimmingTypeV AA7ForEachV 18PhotosUIFoundation14SettingsSliderV 12CoreGraphics7CGFloatV So08PXScrollI17SpeedometerRegimeV AA0I0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO A_AAEA0__A1_Qrqd___SbtSHRd__lFQO AA6ButtonV
- _symbolic _____y_____y_____AAy_____yACG_AeAyAE_A14EQPGSgQPG_____G_AByAcAy_____yAC__________ySayALGAlCGG______y_____GQPGAIGAByAcAyAE_AESgA3eQySdGAw5ew11e2s2e3weKyAC_____AMySayAXGAxCGGA_A_AKyACSiAAy_____yAC_SiQo__A0_A0_A0_A0_QPGGAKyAcrAy_____yAC_SdQo__A3_A3_A3_QPGGAw2EQPGAIGAByAcAyAE_Aw2EQPGAIGAByAcAyAKyACSiAAyA0__A0_A0_A0_QPGG_AWQPGAIGAByAcAyAE_AEQPGAIGAByAcAyAE_A3eKyACSiAAyA0__A0_A0_QPGGQPGAIGAByAcAyAE_AAyAW_A2WQPGSgQPGAIGAByAceIGA24_A24_AByAI_____yACGAIGQPG 7SwiftUI12TupleContentV AA7SectionV AA4TextV AA6ToggleV AA9EmptyViewV AA6PickerV So28PXGTextLegibilityDimmingTypeV AA7ForEachV 18PhotosUIFoundation14SettingsSliderV 12CoreGraphics7CGFloatV So08PXScrollI17SpeedometerRegimeV AA0I0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO A_AAEA0__A1_Qrqd___SbtSHRd__lFQO AA6ButtonV
- _symbolic _____y_____y_____G_ADSgA3D_____ySdGAg5dg11dFy_____GAi2d3gD_____yAC__________ySayAKGAkCGGA2oJyACSiAAy_____yAC_SiQo__A4PQPGGAJyAchAy_____yAC_SdQo__A3SQPGGAg2DQPG 7SwiftUI12TupleContentV AA6ToggleV AA4TextV 18PhotosUIFoundation14SettingsSliderV 12CoreGraphics7CGFloatV AA6PickerV So29PXScrollViewSpeedometerRegimeV AA7ForEachV AA0P0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AuAEAV_AWQrqd___SbtSHRd__lFQO
- _symbolic _____y_____y_____y_____ABy_____yADG_AfByAF_A14FQPGSgQPG_____G_ACyAdBy_____yAD__________ySayAMGAmDGG______y_____GQPGAJGACyAdByAF_AFSgA3fRySdGAx5fx11f2t2f3xfLyAD_____ANySayAYGAyDGGA0_A0_ALyADSiABy_____yAD_SiQo__A1_A1_A1_A1_QPGGALyAdsBy_____yAD_SdQo__A4_A4_A4_QPGGAx2FQPGAJGACyAdByAF_Ax2FQPGAJGACyAdByALyADSiAByA1__A1_A1_A1_QPGG_AXQPGAJGACyAdByAF_AFQPGAJGACyAdByAF_A3fLyADSiAByA1__A1_A1_QPGGQPGAJGACyAdByAF_AByAX_A2XQPGSgQPGAJGACyAdfJGA25_A25_ACyAJ_____yADGAJGQPGG 7SwiftUI4FormV AA12TupleContentV AA7SectionV AA4TextV AA6ToggleV AA9EmptyViewV AA6PickerV So28PXGTextLegibilityDimmingTypeV AA7ForEachV 18PhotosUIFoundation14SettingsSliderV 12CoreGraphics7CGFloatV So08PXScrollJ17SpeedometerRegimeV AA0J0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO A1_AAEA2__A3_Qrqd___SbtSHRd__lFQO AA6ButtonV
CStrings:
+ "-[PXGDecoratingLayout lastScrollDirectionDidChange]"
+ "-[PXGDecoratingLayout scrollSpeedRegimeDidChange]"
+ "17"
+ "Color Conversion Mode"
+ "ColorConvert"
+ "Custom Shader (legacy)"
+ "MPSFColorConversion error converting %@ -> %@, error:%@"
+ "colorConversionMode"
+ "\xa1\xc1"
- "13"
- "kCGHDRMediaReferenceWhite"
- "\x91\xc1"
```
