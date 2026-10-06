## PhotoImaging

> `/System/Library/PrivateFrameworks/PhotoImaging.framework/PhotoImaging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x275c1c` | `0x278560` | **`+0x2944`** |
| `__TEXT.__cstring` | `0x46215` | `0x46738` | **`+0x523`** |
| `__AUTH_CONST.__cfstring` | `0x26560` | `0x26a20` | **`+0x4c0`** |
| `__TEXT.__objc_methlist` | `0x16258` | `0x163d0` | **`+0x178`** |
| `__AUTH_CONST.__objc_const` | `0x280e8` | `0x28240` | **`+0x158`** |
| `__DATA_CONST.__objc_selrefs` | `0xb380` | `0xb478` | **`+0xf8`** |
| `__AUTH.__objc_data` | `0x6a0` | `0x788` | **`+0xe8`** |
| `__TEXT.__oslogstring` | `0x6b87` | `0x6c3f` | **`+0xb8`** |
| `__DATA_CONST.__objc_arraydata` | `0x92b0` | `0x9350` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x5780` | `0x5800` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x14d8` | `0x1530` | **`+0x58`** |
| `__AUTH.__data` | `—` | `0x50` | **`+0x50`** |
| `__AUTH_CONST.__objc_dictobj` | `0x5aa0` | `0x5af0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x4098` | `0x4050` | **`-0x48`** |
| `__AUTH_CONST.__const` | `0x5410` | `0x5450` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x2558` | `0x2598` | **`+0x40`** |
| `__TEXT.__delay_helper` | `0x1bc` | `0x1f4` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x49e0` | `0x4a18` | **`+0x38`** |
| `__AUTH_CONST.__objc_intobj` | `0x1428` | `0x1458` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x9c0` | `0x9f0` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x148` | `0x120` | **`-0x28`** |
| `__DATA_DIRTY.__objc_data` | `0xa2c8` | `0xa2a0` | **`-0x28`** |
| `__TEXT.__const` | `0x8aac` | `0x8a8c` | **`-0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x10c8` | `0x10d8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1550` | `0x1558` | **`+0x8`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

+  - /System/Library/Frameworks/CoreML.framework/CoreML

-  Functions: 9057
-  Symbols:   15706
-  CStrings:  7010
+  Functions: 9098
+  Symbols:   15753
+  CStrings:  7056
Symbols:
+ +[PIPhotosPipeline _buildPhotosPipelineWithDescriptor:error:]
+ +[PIPlaybackRate_v1 adjustmentDescriptor]
+ +[PISegmentationHelper sideEdgesHaveContactWithInspectionMatte:context:]
+ +[_PILivePhotoEffectMirrorTransformsExpressionFunction transformArrayDescriptor]
+ -[NUGlobalSettings(PIGlobalSettings) setUseEditAIHDRModularPipeline:]
+ -[NUGlobalSettings(PIGlobalSettings) useEditAIHDRModularPipeline]
+ -[PICleanup _buildMetadataPipeline:input:error:]
+ -[PIGlobalSettings setUseEditAIHDRModularPipeline:]
+ -[PIGlobalSettings useEditAIHDRModularPipeline]
+ -[PIParallaxLayerStackRequest originalPixelLayoutLacksHeadroom]
+ -[PIParallaxLayerStackRequest savedLayoutUsesHeadroom]
+ -[PIParallaxLayerStackRequest setSavedLayoutUsesHeadroom:]
+ -[PIPrivatePhotosPipeline_v1 _rewireHDRColorVolumePipeline:]
+ -[PIPrivatePhotosPipeline_v1 rewireHDRColorVolumePipeline:]
+ -[_PICleanupMetadataProcessor inputChannels]
+ -[_PICleanupMetadataProcessor mainInput]
+ -[_PICleanupMetadataProcessor outputChannel]
+ -[_PICleanupMetadataProcessor outputMetadataWithInputMetadata:settings:error:]
+ -[_PIParallaxLayerStackJob _adjustForSpatialModeWithVisibleFrame:needHeadroom:layout:auxiliaryLayout:item:error:]
+ -[_PIParallaxLayerStackJob _applyHeadroomFilterToBackground:flags:item:style:layout:renderScale:scaledVisibleFrameUnion:]
+ -[_PIParallaxLayerStackJob _cropRectForVisibleFrame:layout:item:renderScale:flags:]
+ -[_PIParallaxLayerStackJob _makePrepareFlagsForStyle:item:]
+ -[_PIParallaxLayerStackJob _runStyleFilterForStyle:flags:item:inputImage:backgroundImage:matteImage:scaledVisibleFrame:screenScale:]
+ GCC_except_table1098
+ GCC_except_table1694
+ GCC_except_table1708
+ GCC_except_table1875
+ GCC_except_table2051
+ GCC_except_table2203
+ GCC_except_table2213
+ GCC_except_table2219
+ GCC_except_table2227
+ GCC_except_table2234
+ GCC_except_table2242
+ GCC_except_table2320
+ GCC_except_table2360
+ GCC_except_table2389
+ GCC_except_table2394
+ GCC_except_table2409
+ GCC_except_table2425
+ GCC_except_table2430
+ GCC_except_table2436
+ GCC_except_table2522
+ GCC_except_table2744
+ GCC_except_table309
+ GCC_except_table3090
+ GCC_except_table3095
+ GCC_except_table3125
+ GCC_except_table3132
+ GCC_except_table3134
+ GCC_except_table3136
+ GCC_except_table3138
+ GCC_except_table3144
+ GCC_except_table3149
+ GCC_except_table3158
+ GCC_except_table3251
+ GCC_except_table3316
+ GCC_except_table3317
+ GCC_except_table3424
+ GCC_except_table3466
+ GCC_except_table3474
+ GCC_except_table3526
+ GCC_except_table3738
+ GCC_except_table3751
+ GCC_except_table3752
+ GCC_except_table3764
+ GCC_except_table3811
+ GCC_except_table3820
+ GCC_except_table3848
+ GCC_except_table3871
+ GCC_except_table4098
+ GCC_except_table4350
+ GCC_except_table4451
+ GCC_except_table4479
+ GCC_except_table4598
+ GCC_except_table4636
+ GCC_except_table4642
+ GCC_except_table4644
+ GCC_except_table4668
+ GCC_except_table4690
+ GCC_except_table4913
+ GCC_except_table4936
+ GCC_except_table494
+ GCC_except_table4943
+ GCC_except_table4946
+ GCC_except_table4957
+ GCC_except_table4964
+ GCC_except_table5111
+ GCC_except_table5203
+ GCC_except_table5264
+ GCC_except_table5267
+ GCC_except_table5279
+ GCC_except_table5280
+ GCC_except_table5284
+ GCC_except_table5285
+ GCC_except_table5286
+ GCC_except_table5291
+ GCC_except_table5299
+ GCC_except_table5392
+ GCC_except_table5739
+ GCC_except_table5758
+ GCC_except_table5759
+ GCC_except_table5765
+ GCC_except_table5770
+ GCC_except_table5822
+ GCC_except_table5827
+ GCC_except_table5828
+ GCC_except_table5838
+ GCC_except_table5840
+ GCC_except_table5864
+ GCC_except_table5867
+ GCC_except_table5872
+ GCC_except_table5874
+ GCC_except_table5877
+ GCC_except_table5880
+ GCC_except_table5882
+ GCC_except_table5883
+ GCC_except_table5884
+ GCC_except_table5885
+ GCC_except_table5887
+ GCC_except_table5892
+ GCC_except_table5925
+ GCC_except_table6028
+ GCC_except_table6067
+ GCC_except_table6141
+ GCC_except_table6460
+ GCC_except_table6708
+ GCC_except_table6709
+ GCC_except_table6797
+ GCC_except_table6800
+ GCC_except_table6804
+ GCC_except_table6809
+ GCC_except_table6810
+ GCC_except_table6812
+ GCC_except_table6818
+ GCC_except_table6827
+ GCC_except_table6843
+ GCC_except_table6894
+ GCC_except_table6946
+ GCC_except_table6947
+ GCC_except_table6948
+ GCC_except_table6949
+ GCC_except_table6979
+ GCC_except_table6982
+ GCC_except_table7050
+ GCC_except_table7060
+ GCC_except_table7164
+ GCC_except_table7217
+ GCC_except_table7219
+ GCC_except_table7322
+ GCC_except_table7324
+ GCC_except_table7325
+ GCC_except_table7326
+ GCC_except_table7327
+ GCC_except_table7329
+ GCC_except_table7332
+ GCC_except_table7333
+ GCC_except_table7334
+ GCC_except_table7335
+ GCC_except_table7337
+ GCC_except_table7338
+ GCC_except_table7340
+ GCC_except_table7341
+ GCC_except_table7342
+ GCC_except_table7343
+ GCC_except_table7406
+ GCC_except_table7420
+ GCC_except_table7421
+ GCC_except_table7422
+ GCC_except_table7456
+ GCC_except_table7457
+ GCC_except_table7458
+ GCC_except_table7461
+ GCC_except_table7464
+ GCC_except_table7509
+ GCC_except_table7511
+ GCC_except_table765
+ GCC_except_table7663
+ GCC_except_table7670
+ GCC_except_table7671
+ GCC_except_table7672
+ GCC_except_table7673
+ GCC_except_table7674
+ GCC_except_table7675
+ GCC_except_table7676
+ GCC_except_table7719
+ GCC_except_table776
+ GCC_except_table786
+ GCC_except_table7904
+ GCC_except_table806
+ GCC_except_table8132
+ GCC_except_table8134
+ GCC_except_table8135
+ GCC_except_table8197
+ GCC_except_table8199
+ GCC_except_table8201
+ GCC_except_table8294
+ GCC_except_table8299
+ GCC_except_table8303
+ GCC_except_table8305
+ GCC_except_table8338
+ GCC_except_table8346
+ GCC_except_table8351
+ GCC_except_table8359
+ GCC_except_table8370
+ GCC_except_table8373
+ GCC_except_table8375
+ GCC_except_table8379
+ GCC_except_table8381
+ GCC_except_table8382
+ GCC_except_table8394
+ GCC_except_table853
+ GCC_except_table856
+ _NUGainMapComputePipelineOptionRGBGainMap
+ _NUMediaAttachmentKeyContentHeadroom
+ _NUMemoryCachePipelineOptionDisableSubsampling
+ _NUMemoryCachePipelineOptionUseProcessor
+ _NUVisionVMApplyComputeDeviceOverride
+ _OBJC_CLASS_$_PIGenerativeGainMapPipeline
+ _OBJC_CLASS_$_PISensitivityDelta
+ _OBJC_CLASS_$__PICleanupMetadataProcessor
+ _OBJC_IVAR_$_PIParallaxLayerStackRequest._originalPixelLayoutLacksHeadroom
+ _OBJC_IVAR_$_PIParallaxLayerStackRequest._savedLayoutUsesHeadroom
+ _OBJC_METACLASS_$_PIGenerativeGainMapPipeline
+ _OBJC_METACLASS_$_PISensitivityDelta
+ _OBJC_METACLASS_$__PICleanupMetadataProcessor
+ _OUTLINED_FUNCTION_51
+ _OUTLINED_FUNCTION_52
+ _PFIsPhotosPosterProvider
+ __CLASS_METHODS_PIGenerativeGainMapPipeline
+ __CLASS_METHODS_PISensitivityDelta
+ __DATA_PIGenerativeGainMapPipeline
+ __DATA_PISensitivityDelta
+ __INSTANCE_METHODS_PIGenerativeGainMapPipeline
+ __INSTANCE_METHODS_PISensitivityDelta
+ __METACLASS_DATA_PIGenerativeGainMapPipeline
+ __METACLASS_DATA_PISensitivityDelta
+ __NUPipelineLogger
+ __NUUILogger
+ __OBJC_$_INSTANCE_METHODS__PICleanupMetadataProcessor
+ __OBJC_CLASS_RO_$__PICleanupMetadataProcessor
+ __OBJC_METACLASS_RO_$__PICleanupMetadataProcessor
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIDv2_sEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIdEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__123mersenne_twister_engineIjLm32ELm624ELm397ELm31ELj2567483615ELm11ELj4294967295ELm7ELj2636928640ELm15ELj4022730752ELm18ELj1812433253EEclB9fqe220106Ev
+ __ZNSt3__16vectorI5SKnotNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIDv2_sNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIDv4_fNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIdNS_9allocatorIdEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIdNS_9allocatorIdEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIdNS_9allocatorIdEEEC2B9fqe220106Em
+ __ZNSt3__16vectorIdNS_9allocatorIdEEEC2B9fqe220106EmRKd
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220106EmRKf
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ ___59-[PIPrivatePhotosPipeline_v1 rewireHDRColorVolumePipeline:]_block_invoke
+ ___63-[PIPrivatePhotosPipeline_v0 _addVideoThumbnailPipeline:error:]_block_invoke_2
+ ___63-[PIPrivatePhotosPipeline_v1 _addVideoThumbnailPipeline:error:]_block_invoke_2
+ ___65-[NUGlobalSettings(PIGlobalSettings) useEditAIHDRModularPipeline]_block_invoke
+ ___NUPipelineLogger_block_invoke
+ ___NUUILogger_block_invoke
+ ___block_descriptor_114_e8_32s40s48s56s64s72bs80bs88r_e5_v8?0ls32l8r88l8s40l8s48l8s56l8s64l8s72l8s80l8
+ ___block_descriptor_56_e8_32s40s_e48_"NUChannelPortRef"24?0"NUChannelPortRef"8^16ls32l8s40l8
+ _kSCMLImageSanitizationSignalIVSNSFWExplicit
+ _kSCMLImageSanitizationSignalIVSNSFWExplicit$loadHelper_x27
+ _swift_retain_x27
- +[PIPlaybackRate_v1 adjustmentSchema]
- +[_PILivePhotoEffectMirrorTransformsExpressionFunction transformArraySetting]
- GCC_except_table1099
- GCC_except_table1695
- GCC_except_table1709
- GCC_except_table1876
- GCC_except_table2052
- GCC_except_table2204
- GCC_except_table2214
- GCC_except_table2220
- GCC_except_table2228
- GCC_except_table2235
- GCC_except_table2243
- GCC_except_table2321
- GCC_except_table2361
- GCC_except_table2390
- GCC_except_table2395
- GCC_except_table2410
- GCC_except_table2426
- GCC_except_table2431
- GCC_except_table2437
- GCC_except_table2520
- GCC_except_table2741
- GCC_except_table3087
- GCC_except_table3092
- GCC_except_table311
- GCC_except_table3122
- GCC_except_table3126
- GCC_except_table3128
- GCC_except_table3133
- GCC_except_table3135
- GCC_except_table3141
- GCC_except_table3146
- GCC_except_table3155
- GCC_except_table3248
- GCC_except_table3313
- GCC_except_table3314
- GCC_except_table3420
- GCC_except_table3462
- GCC_except_table3470
- GCC_except_table3522
- GCC_except_table3734
- GCC_except_table3744
- GCC_except_table3747
- GCC_except_table3760
- GCC_except_table3807
- GCC_except_table3816
- GCC_except_table3844
- GCC_except_table3867
- GCC_except_table4094
- GCC_except_table4346
- GCC_except_table4447
- GCC_except_table4471
- GCC_except_table4594
- GCC_except_table4632
- GCC_except_table4638
- GCC_except_table4640
- GCC_except_table4664
- GCC_except_table4686
- GCC_except_table4904
- GCC_except_table4927
- GCC_except_table4934
- GCC_except_table4937
- GCC_except_table4948
- GCC_except_table4955
- GCC_except_table496
- GCC_except_table5102
- GCC_except_table5194
- GCC_except_table5255
- GCC_except_table5258
- GCC_except_table5270
- GCC_except_table5271
- GCC_except_table5275
- GCC_except_table5276
- GCC_except_table5277
- GCC_except_table5282
- GCC_except_table5290
- GCC_except_table5383
- GCC_except_table5725
- GCC_except_table5744
- GCC_except_table5745
- GCC_except_table5751
- GCC_except_table5756
- GCC_except_table5808
- GCC_except_table5813
- GCC_except_table5814
- GCC_except_table5824
- GCC_except_table5826
- GCC_except_table5850
- GCC_except_table5852
- GCC_except_table5853
- GCC_except_table5854
- GCC_except_table5856
- GCC_except_table5858
- GCC_except_table5860
- GCC_except_table5863
- GCC_except_table5869
- GCC_except_table5871
- GCC_except_table5873
- GCC_except_table5878
- GCC_except_table5911
- GCC_except_table6014
- GCC_except_table6053
- GCC_except_table6127
- GCC_except_table6438
- GCC_except_table6686
- GCC_except_table6687
- GCC_except_table6775
- GCC_except_table6778
- GCC_except_table6782
- GCC_except_table6783
- GCC_except_table6787
- GCC_except_table6788
- GCC_except_table6790
- GCC_except_table6796
- GCC_except_table6821
- GCC_except_table6872
- GCC_except_table6924
- GCC_except_table6925
- GCC_except_table6926
- GCC_except_table6927
- GCC_except_table6957
- GCC_except_table6960
- GCC_except_table7028
- GCC_except_table7038
- GCC_except_table7142
- GCC_except_table7195
- GCC_except_table7197
- GCC_except_table7291
- GCC_except_table7297
- GCC_except_table7300
- GCC_except_table7302
- GCC_except_table7303
- GCC_except_table7304
- GCC_except_table7305
- GCC_except_table7307
- GCC_except_table7310
- GCC_except_table7311
- GCC_except_table7312
- GCC_except_table7315
- GCC_except_table7316
- GCC_except_table7318
- GCC_except_table7320
- GCC_except_table7321
- GCC_except_table7376
- GCC_except_table7384
- GCC_except_table7399
- GCC_except_table7400
- GCC_except_table7434
- GCC_except_table7435
- GCC_except_table7436
- GCC_except_table7439
- GCC_except_table7442
- GCC_except_table7487
- GCC_except_table7489
- GCC_except_table7631
- GCC_except_table7641
- GCC_except_table7648
- GCC_except_table7649
- GCC_except_table7650
- GCC_except_table7651
- GCC_except_table7652
- GCC_except_table7654
- GCC_except_table767
- GCC_except_table7695
- GCC_except_table778
- GCC_except_table788
- GCC_except_table7880
- GCC_except_table808
- GCC_except_table8107
- GCC_except_table8109
- GCC_except_table8110
- GCC_except_table8172
- GCC_except_table8174
- GCC_except_table8176
- GCC_except_table8246
- GCC_except_table8269
- GCC_except_table8274
- GCC_except_table8278
- GCC_except_table8280
- GCC_except_table8313
- GCC_except_table8325
- GCC_except_table8326
- GCC_except_table8334
- GCC_except_table8344
- GCC_except_table8345
- GCC_except_table8348
- GCC_except_table8354
- GCC_except_table8356
- GCC_except_table8357
- GCC_except_table855
- GCC_except_table858
- _OBJC_CLASS_$_NUProcessorCache
- _OBJC_CLASS_$_PIHDRPipeline
- _OBJC_METACLASS_$_PIHDRPipeline
- __DATA_PIHDRPipeline
- __INSTANCE_METHODS_PIHDRPipeline
- __METACLASS_DATA_PIHDRPipeline
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIDv2_sEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIdEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__123mersenne_twister_engineIjLm32ELm624ELm397ELm31ELj2567483615ELm11ELj4294967295ELm7ELj2636928640ELm15ELj4022730752ELm18ELj1812433253EEclB9fqe220100Ev
- __ZNSt3__16vectorI5SKnotNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIDv2_sNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIDv4_fNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIdNS_9allocatorIdEEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIdNS_9allocatorIdEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIdNS_9allocatorIdEEEC2B9fqe220100Em
- __ZNSt3__16vectorIdNS_9allocatorIdEEEC2B9fqe220100EmRKd
- __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220100EmRKf
- __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- ___94+[PISensitiveContentAnalysisRequest currentSensitivityExceedsThresholdsV2:initialSensitivity:]_block_invoke
- ___94+[PISensitiveContentAnalysisRequest currentSensitivityExceedsThresholdsV2:initialSensitivity:]_block_invoke_2
- ___block_descriptor_106_e8_32s40s48s56s64bs72bs80r_e5_v8?0ls32l8r80l8s40l8s48l8s56l8s64l8s72l8
- ___block_descriptor_32_e8_i16?0d8l
- ___block_descriptor_40_e8_32bs_e11_B24?0d8d16ls32l8
- ___block_descriptor_48_e8_32s_e48_"NUChannelPortRef"24?0"NUChannelPortRef"8^16ls32l8
- _objc_release_x6
- _swift_release_x21
CStrings:
+ "#\""
+ "-[_PICleanupMetadataProcessor outputMetadataWithInputMetadata:settings:error:]"
+ "-[_PIParallaxLayerStackJob _runStyleFilterForStyle:flags:item:inputImage:backgroundImage:matteImage:scaledVisibleFrame:screenScale:]"
+ "../outputCachePipeline:>media"
+ "..:<exclusionMask"
+ "/:<debug.hdr_maximumHeadroom"
+ "/:<debug.hdr_showClipping"
+ ":<useCaseIdentifier"
+ ":>original+geometry.sceneIllumination"
+ "Bad composition data: expected dictionary"
+ "Bad composition data: expected dictionary, but got %{public}@"
+ "Composition data deserialization failed"
+ "Failed to create cleanup metadata processor pipeline"
+ "Failed to deserialize adjustment data: %{public}@"
+ "PIPhotosPipeline.buildPhotosPipeline"
+ "PI_USE_EDITAI_HDR_MODULAR_PIPELINE"
+ "VisualGeneration.PhotosEdit.Infill.1p"
+ "VisualGeneration.PhotosEdit.Outfill.1p"
+ "VisualGeneration.PhotosEdit.SpatialReframing.1p"
+ "adjust:<<primary"
+ "asset:>media.sceneIllumination"
+ "assetHasOutfillEdit"
+ "colorVolume:<headroom"
+ "colorVolume:<primary"
+ "colorVolume:<showClipping"
+ "colorVolume:>primary"
+ "colorVolumePreTM"
+ "colorVolumePreTM:<headroom"
+ "colorVolumePreTM:<primary"
+ "colorVolumePreTM:>primary"
+ "gainMapCompute:<hdrImage"
+ "gainMapCompute:<sdrImage"
+ "gainMapCompute:>gainMap"
+ "gainMapProcessor:<exclusionMask"
+ "hdr_maximumHeadroom"
+ "hdr_showClipping"
+ "headroomUpdate:<headroom"
+ "headroomUpdate:<primary"
+ "headroomUpdate:>primary"
+ "metadataProcessor"
+ "metadataProcessor:<primary"
+ "metadataProcessor:>primary"
+ "opticalScale:<headroom"
+ "opticalScaleInv:<headroom"
+ "outputCachePipeline"
+ "outputCachePipeline:<media"
+ "outputCachePipeline:>media"
+ "processor:<useCaseIdentifier"
+ "refinementMaxPixelCount"
+ "sceneRefinementCachePipeline"
+ "toneMapApply:<intensity"
+ "unadjustedThumbnailSelector"
+ "useCaseIdentifier"
+ "version: %{public}@, assetId: '%@'"
- "B24@?0d8d16"
- "Composition for Editing Input resource not supported"
- "cinematicVideo:<opticalScale"
- "gainMapLearn:<hdrImage"
- "gainMapLearn:<sdrImage"
- "gainMapLearn:>gainMap"
- "i16@?0d8"
- "ivs.nsfw_explicit"
```
