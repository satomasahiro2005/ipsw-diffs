## CoreSpeech

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/CoreSpeech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1492e8` | `0x149b80` | **`+0x898`** |
| `__AUTH_CONST.__objc_const` | `0x20a58` | `0x20cd8` | **`+0x280`** |
| `__TEXT.__cstring` | `0x287dd` | `0x28a0d` | **`+0x230`** |
| `__TEXT.__oslogstring` | `0x1fb63` | `0x1fd55` | **`+0x1f2`** |
| `__TEXT.__objc_methlist` | `0x14a64` | `0x14bec` | **`+0x188`** |
| `__DATA_CONST.__objc_selrefs` | `0xabe0` | `0xad00` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x3e80` | `0x3f20` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x30c8` | `0x3140` | **`+0x78`** |
| `__DATA.__data` | `0x39b4` | `0x3a14` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x4ec8` | `0x4f28` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x1ae8` | `0x1b18` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x4240` | `0x4268` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x9660` | `0x9680` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x1e80` | `0x1e60` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x1930` | `0x1940` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x838` | `0x848` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xd98` | `0xda0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x4d8` | `0x4e0` | **`+0x8`** |

### Other Changes

```diff

-3600.64.114.1.5
+3600.70.8.0.0

-  Functions: 8055
-  Symbols:   14029
-  CStrings:  5564
+  Functions: 8087
+  Symbols:   14093
+  CStrings:  5577
Symbols:
+ +[CSAttendingOptions optionForFlexibleFollowupWithAudioRecordType:deviceId:startAttendingSampleCount:shouldPrependAudioBeforeSpeechDetectionOnset:isCanarySampled:]
+ +[CSAttendingSelfLogger emitOSDDetectionReportedWithSpeechStartTimeInMs:minConsecutiveSpeechThresholdInMs:silenceProbabilityThreshold:isCanarySampled:osdModelVersion:withMHUUID:]
+ +[CSSiriAudioActivationInfo _alertDictionaryForRecordRoute:playbackRoute:speechEvent:ringerState:startingAlertBeepOverideID:presentationMode:hasPlayedStartAlert:supportsEchoCancellation:isVoiceOverTouchEnabled:isVibrationEnabled:isVibrationSupported:activationHostTime:isVoiceOverSiriSoundsEnabled:suppressStartAlert:]
+ +[CSVoiceTriggerActivationPolicyFactory policy]
+ -[CSAttendingTriggerInfo initWithAttendingType:detectedToken:triggerMachTime:triggerAbsStartSampleId:audioRecordType:audioRecordDeviceId:amountOfSpeechDetectedInMs:triggerThresholdInMs:speechStartTimeInMs:]
+ -[CSAttendingTriggerInfo speechStartTimeInMs]
+ -[CSContinuousAudioFingerprintProvider audioProviderSelector]
+ -[CSContinuousAudioFingerprintProvider initWithAudioProviderSelector:]
+ -[CSContinuousAudioFingerprintProvider setAudioProviderSelector:]
+ -[CSSpeechManager _cancelConnectionTimer]
+ -[CSSpeechManager _connectToAlwaysOnExclaveServerEndpoint:]
+ -[CSSpeechManager _handleExclaveServerEndpointActiveMessage]
+ -[CSSpeechManager _handleExclaveServerEndpointInactiveMessage]
+ -[CSSpeechManager exclaveServerConnectTimeout]
+ -[CSSpeechManager exclaveServerEndpointConnectionHoldPolicy]
+ -[CSSpeechManager setExclaveServerConnectTimeout:]
+ -[CSSpeechManager setExclaveServerEndpointConnectionHoldPolicy:]
+ -[CSVoiceTriggerHandlerAOE .cxx_destruct]
+ -[CSVoiceTriggerHandlerAOE initWithDelegate:]
+ -[CSVoiceTriggerHandlerAOE initWithDelegate:type:]
+ -[CSVoiceTriggerHandlerAOE inputControlDidEnterBlockingMode:]
+ -[CSVoiceTriggerHandlerAOE inputControlFailedToStart:error:]
+ -[CSVoiceTriggerHandlerAOE inputControlFailedUnexpectedlyForSource:forReason:]
+ -[CSVoiceTriggerHandlerAOE inputControlWillStartStreamingForSource:completion:]
+ -[CSVoiceTriggerHandlerAOE reset]
+ -[CSVoiceTriggerHandlerAOE secondPassFailedUnexpectedlyForSource:forReason:]
+ -[CSVoiceTriggerHandlerAOE secondPassStartFailedForSource:error:]
+ -[CSVoiceTriggerHandlerAOE setAsset:]
+ -[CSVoiceTriggerHandlerAOE setVoiceTriggerDelegate:]
+ -[CSVoiceTriggerHandlerAOE start]
+ -[CSVoiceTriggerHandlerAOE voiceTriggerDelegate]
+ GCC_except_table1272
+ GCC_except_table1284
+ GCC_except_table1490
+ GCC_except_table1558
+ GCC_except_table1582
+ GCC_except_table1586
+ GCC_except_table1602
+ GCC_except_table1605
+ GCC_except_table1635
+ GCC_except_table1733
+ GCC_except_table1735
+ GCC_except_table1737
+ GCC_except_table1743
+ GCC_except_table1803
+ GCC_except_table1829
+ GCC_except_table1835
+ GCC_except_table1916
+ GCC_except_table1936
+ GCC_except_table2052
+ GCC_except_table2201
+ GCC_except_table2231
+ GCC_except_table2234
+ GCC_except_table2237
+ GCC_except_table2242
+ GCC_except_table2254
+ GCC_except_table2259
+ GCC_except_table2262
+ GCC_except_table2352
+ GCC_except_table2358
+ GCC_except_table2398
+ GCC_except_table2401
+ GCC_except_table2405
+ GCC_except_table2423
+ GCC_except_table2454
+ GCC_except_table2557
+ GCC_except_table2616
+ GCC_except_table2628
+ GCC_except_table2659
+ GCC_except_table2684
+ GCC_except_table2695
+ GCC_except_table2729
+ GCC_except_table2732
+ GCC_except_table2733
+ GCC_except_table2737
+ GCC_except_table2743
+ GCC_except_table2744
+ GCC_except_table2747
+ GCC_except_table2757
+ GCC_except_table2763
+ GCC_except_table2765
+ GCC_except_table2766
+ GCC_except_table2836
+ GCC_except_table3102
+ GCC_except_table3180
+ GCC_except_table3217
+ GCC_except_table3228
+ GCC_except_table3250
+ GCC_except_table3253
+ GCC_except_table3256
+ GCC_except_table3287
+ GCC_except_table3347
+ GCC_except_table3579
+ GCC_except_table3605
+ GCC_except_table3666
+ GCC_except_table3667
+ GCC_except_table3669
+ GCC_except_table3671
+ GCC_except_table3687
+ GCC_except_table3689
+ GCC_except_table3691
+ GCC_except_table3695
+ GCC_except_table3697
+ GCC_except_table3699
+ GCC_except_table3721
+ GCC_except_table3729
+ GCC_except_table3732
+ GCC_except_table3734
+ GCC_except_table3735
+ GCC_except_table3736
+ GCC_except_table3740
+ GCC_except_table3741
+ GCC_except_table3742
+ GCC_except_table3743
+ GCC_except_table3748
+ GCC_except_table3756
+ GCC_except_table3761
+ GCC_except_table3762
+ GCC_except_table3763
+ GCC_except_table3764
+ GCC_except_table3899
+ GCC_except_table3923
+ GCC_except_table3989
+ GCC_except_table4005
+ GCC_except_table4026
+ GCC_except_table4118
+ GCC_except_table4368
+ GCC_except_table4435
+ GCC_except_table4436
+ GCC_except_table4440
+ GCC_except_table4443
+ GCC_except_table4447
+ GCC_except_table4472
+ GCC_except_table4525
+ GCC_except_table4531
+ GCC_except_table4601
+ GCC_except_table4804
+ GCC_except_table4811
+ GCC_except_table4818
+ GCC_except_table4824
+ GCC_except_table4907
+ GCC_except_table5067
+ GCC_except_table5077
+ GCC_except_table5101
+ GCC_except_table5121
+ GCC_except_table5204
+ GCC_except_table5218
+ GCC_except_table5227
+ GCC_except_table5234
+ GCC_except_table5240
+ GCC_except_table5245
+ GCC_except_table5253
+ GCC_except_table5259
+ GCC_except_table5272
+ GCC_except_table5278
+ GCC_except_table5296
+ GCC_except_table5297
+ GCC_except_table5298
+ GCC_except_table5299
+ GCC_except_table5301
+ GCC_except_table5302
+ GCC_except_table5303
+ GCC_except_table5304
+ GCC_except_table5305
+ GCC_except_table5307
+ GCC_except_table5308
+ GCC_except_table5311
+ GCC_except_table5326
+ GCC_except_table5400
+ GCC_except_table5404
+ GCC_except_table5458
+ GCC_except_table5488
+ GCC_except_table5491
+ GCC_except_table5581
+ GCC_except_table5595
+ GCC_except_table5602
+ GCC_except_table5614
+ GCC_except_table5618
+ GCC_except_table5628
+ GCC_except_table5857
+ GCC_except_table5890
+ GCC_except_table5895
+ GCC_except_table5932
+ GCC_except_table5941
+ GCC_except_table5971
+ GCC_except_table6039
+ GCC_except_table6181
+ GCC_except_table6284
+ GCC_except_table6292
+ GCC_except_table6312
+ GCC_except_table6317
+ GCC_except_table6423
+ GCC_except_table6478
+ GCC_except_table6558
+ GCC_except_table6580
+ GCC_except_table6581
+ GCC_except_table6591
+ GCC_except_table6592
+ GCC_except_table6604
+ GCC_except_table6635
+ GCC_except_table6646
+ GCC_except_table6651
+ GCC_except_table6656
+ GCC_except_table6684
+ GCC_except_table6756
+ GCC_except_table6768
+ GCC_except_table6791
+ GCC_except_table6802
+ GCC_except_table6805
+ GCC_except_table6828
+ GCC_except_table6840
+ GCC_except_table7120
+ GCC_except_table7156
+ GCC_except_table7229
+ GCC_except_table7283
+ GCC_except_table7306
+ GCC_except_table7347
+ GCC_except_table7358
+ GCC_except_table7498
+ GCC_except_table7506
+ GCC_except_table7622
+ GCC_except_table7623
+ GCC_except_table7624
+ GCC_except_table7625
+ GCC_except_table7626
+ GCC_except_table7631
+ GCC_except_table7694
+ GCC_except_table7740
+ GCC_except_table7748
+ GCC_except_table7754
+ GCC_except_table7779
+ GCC_except_table7785
+ GCC_except_table7791
+ GCC_except_table7929
+ _CSSupportsAggressiveEC
+ _OBJC_CLASS_$_CSExclaveServerEndpointConnectionHoldPolicy
+ _OBJC_CLASS_$_CSFTimer
+ _OBJC_CLASS_$_CSFTimerContext
+ _OBJC_CLASS_$_CSHardwareLatencyHelper
+ _OBJC_CLASS_$_CSVoiceTriggerActivationPolicyFactory
+ _OBJC_CLASS_$_CSVoiceTriggerHandlerAOE
+ _OBJC_CLASS_$_MHSchemaMHOSDDetectionReported
+ _OBJC_IVAR_$_CSAttendingTriggerInfo._speechStartTimeInMs
+ _OBJC_IVAR_$_CSContinuousAudioFingerprintProvider._audioProviderSelector
+ _OBJC_IVAR_$_CSSpeechManager._exclaveServerConnectTimeout
+ _OBJC_IVAR_$_CSSpeechManager._exclaveServerEndpointConnectionHoldPolicy
+ _OBJC_IVAR_$_CSVoiceTriggerHandlerAOE._voiceTriggerDelegate
+ _OBJC_METACLASS_$_CSVoiceTriggerActivationPolicyFactory
+ _OBJC_METACLASS_$_CSVoiceTriggerHandlerAOE
+ __OBJC_$_CLASS_METHODS_CSVoiceTriggerActivationPolicyFactory
+ __OBJC_$_INSTANCE_METHODS_CSVoiceTriggerHandlerAOE
+ __OBJC_$_INSTANCE_VARIABLES_CSVoiceTriggerHandlerAOE
+ __OBJC_$_PROP_LIST_CSVoiceTriggerHandlerAOE
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CSVoiceTriggerAoEInputControlDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSVoiceTriggerAoEInputControlDelegate
+ __OBJC_$_PROTOCOL_REFS_CSVoiceTriggerAoEInputControlDelegate
+ __OBJC_CLASS_PROTOCOLS_$_CSVoiceTriggerHandlerAOE
+ __OBJC_CLASS_RO_$_CSVoiceTriggerActivationPolicyFactory
+ __OBJC_CLASS_RO_$_CSVoiceTriggerHandlerAOE
+ __OBJC_LABEL_PROTOCOL_$_CSVoiceTriggerAoEInputControlDelegate
+ __OBJC_METACLASS_RO_$_CSVoiceTriggerActivationPolicyFactory
+ __OBJC_METACLASS_RO_$_CSVoiceTriggerHandlerAOE
+ __OBJC_PROTOCOL_$_CSVoiceTriggerAoEInputControlDelegate
+ __ZNKSt3__111__copy_implclB9fqe220106IPNS_6vectorINS2_IfNS_9allocatorIfEEEENS3_IS5_EEEES8_S8_Li0EEENS_4pairIT_T1_EESA_T0_SB_
+ __ZNKSt3__111__copy_implclB9fqe220106IPNS_6vectorIfNS_9allocatorIfEEEES6_S6_Li0EEENS_4pairIT_T1_EES8_T0_S9_
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt12out_of_rangeC1B9fqe220106EPKc
+ __ZNSt3__110unique_ptrI15SmartSiriVolumeNS_14default_deleteIS1_EEE5resetB9fqe220106EPS1_
+ __ZNSt3__110unique_ptrIN10corespeech25CSAudioCircularBufferImplIhEENS_14default_deleteIS3_EEE5resetB9fqe220106EPS3_
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorINS_4pairIfjEEEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIPjEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__120__throw_out_of_rangeB9fqe220106EPKc
+ __ZNSt3__128__exception_guard_exceptionsINS_29_AllocatorDestroyRangeReverseINS_9allocatorINS_6vectorIfNS2_IfEEEEEEPS5_EEED2B9fqe220106Ev
+ __ZNSt3__135__uninitialized_allocator_copy_implB9fqe220106INS_9allocatorINS_6vectorINS2_IfNS1_IfEEEENS1_IS4_EEEEEEPS6_S8_S8_EET2_RT_T0_T1_S9_
+ __ZNSt3__135__uninitialized_allocator_copy_implB9fqe220106INS_9allocatorINS_6vectorIfNS1_IfEEEEEEPS4_S6_S6_EET2_RT_T0_T1_S7_
+ __ZNSt3__16vectorINS0_INS0_INS0_IfNS_9allocatorIfEEEENS1_IS3_EEEENS1_IS5_EEEENS1_IS7_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS0_INS0_IfNS_9allocatorIfEEEENS1_IS3_EEEENS1_IS5_EEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorINS0_INS0_IfNS_9allocatorIfEEEENS1_IS3_EEEENS1_IS5_EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorINS0_INS0_IfNS_9allocatorIfEEEENS1_IS3_EEEENS1_IS5_EEE16__init_with_sizeB9fqe220106IPS5_S9_EEvT_T0_m
+ __ZNSt3__16vectorINS0_INS0_IfNS_9allocatorIfEEEENS1_IS3_EEEENS1_IS5_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS0_IfNS_9allocatorIfEEEENS1_IS3_EEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorINS0_IfNS_9allocatorIfEEEENS1_IS3_EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorINS0_IfNS_9allocatorIfEEEENS1_IS3_EEE16__init_with_sizeB9fqe220106IPS3_S7_EEvT_T0_m
+ __ZNSt3__16vectorINS0_IfNS_9allocatorIfEEEENS1_IS3_EEE18__assign_with_sizeB9fqe220106INS_17_ClassicAlgPolicyEPS3_S8_EEvT0_T1_l
+ __ZNSt3__16vectorINS0_IfNS_9allocatorIfEEEENS1_IS3_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS0_IfNS_9allocatorIfEEEENS1_IS3_EEE5clearB9fqe220106Ev
+ __ZNSt3__16vectorINS0_IfNS_9allocatorIfEEEENS1_IS3_EEEC2B9fqe220106EmRKS3_
+ __ZNSt3__16vectorINS_4pairIfjEENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE16__init_with_sizeB9fqe220106IPfS5_EEvT_T0_m
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE18__assign_with_sizeB9fqe220106INS_17_ClassicAlgPolicyEPfS6_EEvT0_T1_l
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220106EmRKf
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ ___31-[CSSpeechManager startManager]_block_invoke_4
+ ___31-[CSSpeechManager startManager]_block_invoke_5
+ ___62-[CSSpeechManager _handleExclaveServerEndpointInactiveMessage]_block_invoke
+ ___62-[CSSpeechManager _handleExclaveServerEndpointInactiveMessage]_block_invoke_2
+ ___65-[CSSpeechManager CSExclaveServerEPStateMonitorEndpointIsActive:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40w_e11_v20?0B8Q12lw40l8s32l8
+ _kVTEIInputLatency
- +[CSSiriAudioActivationInfo _alertDictionaryForRecordRoute:playbackRoute:speechEvent:ringerState:startingAlertBeepOverideID:presentationMode:hasPlayedStartAlert:supportsEchoCancellation:isVoiceOverTouchEnabled:isVibrationEnabled:isVibrationSupported:activationHostTime:isVoiceOverSiriSoundsEnabled:]
- -[CSAttendingTriggerInfo initWithAttendingType:detectedToken:triggerMachTime:triggerAbsStartSampleId:audioRecordType:audioRecordDeviceId:amountOfSpeechDetectedInMs:triggerThresholdInMs:]
- -[CSContinuousAudioFingerprintProvider init]
- -[CSSelfTriggerDetector setSpeechManager:]
- -[CSSelfTriggerDetector speechManager]
- GCC_except_table1271
- GCC_except_table1283
- GCC_except_table1489
- GCC_except_table1557
- GCC_except_table1581
- GCC_except_table1585
- GCC_except_table1601
- GCC_except_table1604
- GCC_except_table1634
- GCC_except_table1732
- GCC_except_table1734
- GCC_except_table1736
- GCC_except_table1742
- GCC_except_table1802
- GCC_except_table1828
- GCC_except_table1834
- GCC_except_table1915
- GCC_except_table1935
- GCC_except_table2051
- GCC_except_table2200
- GCC_except_table2230
- GCC_except_table2233
- GCC_except_table2236
- GCC_except_table2241
- GCC_except_table2253
- GCC_except_table2258
- GCC_except_table2261
- GCC_except_table2385
- GCC_except_table2388
- GCC_except_table2392
- GCC_except_table2410
- GCC_except_table2542
- GCC_except_table2599
- GCC_except_table2611
- GCC_except_table2642
- GCC_except_table2667
- GCC_except_table2678
- GCC_except_table2712
- GCC_except_table2713
- GCC_except_table2714
- GCC_except_table2715
- GCC_except_table2716
- GCC_except_table2720
- GCC_except_table2723
- GCC_except_table2726
- GCC_except_table2727
- GCC_except_table2746
- GCC_except_table2749
- GCC_except_table2819
- GCC_except_table3085
- GCC_except_table3163
- GCC_except_table3200
- GCC_except_table3211
- GCC_except_table3233
- GCC_except_table3236
- GCC_except_table3239
- GCC_except_table3270
- GCC_except_table3330
- GCC_except_table3562
- GCC_except_table3588
- GCC_except_table3649
- GCC_except_table3650
- GCC_except_table3652
- GCC_except_table3654
- GCC_except_table3670
- GCC_except_table3672
- GCC_except_table3674
- GCC_except_table3676
- GCC_except_table3678
- GCC_except_table3680
- GCC_except_table3682
- GCC_except_table3685
- GCC_except_table3696
- GCC_except_table3704
- GCC_except_table3706
- GCC_except_table3708
- GCC_except_table3712
- GCC_except_table3714
- GCC_except_table3715
- GCC_except_table3717
- GCC_except_table3718
- GCC_except_table3722
- GCC_except_table3724
- GCC_except_table3726
- GCC_except_table3728
- GCC_except_table3746
- GCC_except_table3882
- GCC_except_table3906
- GCC_except_table3972
- GCC_except_table3988
- GCC_except_table4009
- GCC_except_table4101
- GCC_except_table4351
- GCC_except_table4418
- GCC_except_table4419
- GCC_except_table4423
- GCC_except_table4426
- GCC_except_table4430
- GCC_except_table4455
- GCC_except_table4508
- GCC_except_table4514
- GCC_except_table4584
- GCC_except_table4787
- GCC_except_table4794
- GCC_except_table4801
- GCC_except_table4807
- GCC_except_table4890
- GCC_except_table5050
- GCC_except_table5060
- GCC_except_table5084
- GCC_except_table5104
- GCC_except_table5187
- GCC_except_table5201
- GCC_except_table5210
- GCC_except_table5217
- GCC_except_table5223
- GCC_except_table5225
- GCC_except_table5228
- GCC_except_table5236
- GCC_except_table5238
- GCC_except_table5244
- GCC_except_table5256
- GCC_except_table5268
- GCC_except_table5275
- GCC_except_table5277
- GCC_except_table5279
- GCC_except_table5280
- GCC_except_table5281
- GCC_except_table5282
- GCC_except_table5284
- GCC_except_table5286
- GCC_except_table5287
- GCC_except_table5288
- GCC_except_table5291
- GCC_except_table5383
- GCC_except_table5387
- GCC_except_table5441
- GCC_except_table5471
- GCC_except_table5474
- GCC_except_table5564
- GCC_except_table5578
- GCC_except_table5585
- GCC_except_table5597
- GCC_except_table5601
- GCC_except_table5611
- GCC_except_table5840
- GCC_except_table5873
- GCC_except_table5878
- GCC_except_table5915
- GCC_except_table5924
- GCC_except_table5954
- GCC_except_table6022
- GCC_except_table6164
- GCC_except_table6267
- GCC_except_table6275
- GCC_except_table6295
- GCC_except_table6300
- GCC_except_table6406
- GCC_except_table6461
- GCC_except_table6540
- GCC_except_table6562
- GCC_except_table6563
- GCC_except_table6573
- GCC_except_table6574
- GCC_except_table6586
- GCC_except_table6617
- GCC_except_table6628
- GCC_except_table6633
- GCC_except_table6638
- GCC_except_table6666
- GCC_except_table6738
- GCC_except_table6750
- GCC_except_table6773
- GCC_except_table6784
- GCC_except_table6787
- GCC_except_table6810
- GCC_except_table6822
- GCC_except_table7101
- GCC_except_table7137
- GCC_except_table7210
- GCC_except_table7264
- GCC_except_table7287
- GCC_except_table7328
- GCC_except_table7339
- GCC_except_table7479
- GCC_except_table7487
- GCC_except_table7602
- GCC_except_table7603
- GCC_except_table7604
- GCC_except_table7605
- GCC_except_table7606
- GCC_except_table7611
- GCC_except_table7674
- GCC_except_table7720
- GCC_except_table7728
- GCC_except_table7734
- GCC_except_table7759
- GCC_except_table7765
- GCC_except_table7771
- GCC_except_table7911
- _OBJC_IVAR_$_CSSelfTriggerDetector._speechManager
- __ZNKSt3__111__copy_implclB9fqe220100IPNS_6vectorINS2_IfNS_9allocatorIfEEEENS3_IS5_EEEES8_S8_Li0EEENS_4pairIT_T1_EESA_T0_SB_
- __ZNKSt3__111__copy_implclB9fqe220100IPNS_6vectorIfNS_9allocatorIfEEEES6_S6_Li0EEENS_4pairIT_T1_EES8_T0_S9_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt12out_of_rangeC1B9fqe220100EPKc
- __ZNSt3__110unique_ptrI15SmartSiriVolumeNS_14default_deleteIS1_EEE5resetB9fqe220100EPS1_
- __ZNSt3__110unique_ptrIN10corespeech25CSAudioCircularBufferImplIhEENS_14default_deleteIS3_EEE5resetB9fqe220100EPS3_
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorINS_4pairIfjEEEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIPjEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__120__throw_out_of_rangeB9fqe220100EPKc
- __ZNSt3__128__exception_guard_exceptionsINS_29_AllocatorDestroyRangeReverseINS_9allocatorINS_6vectorIfNS2_IfEEEEEEPS5_EEED2B9fqe220100Ev
- __ZNSt3__135__uninitialized_allocator_copy_implB9fqe220100INS_9allocatorINS_6vectorINS2_IfNS1_IfEEEENS1_IS4_EEEEEEPS6_S8_S8_EET2_RT_T0_T1_S9_
- __ZNSt3__135__uninitialized_allocator_copy_implB9fqe220100INS_9allocatorINS_6vectorIfNS1_IfEEEEEEPS4_S6_S6_EET2_RT_T0_T1_S7_
- __ZNSt3__16vectorINS0_INS0_INS0_IfNS_9allocatorIfEEEENS1_IS3_EEEENS1_IS5_EEEENS1_IS7_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorINS0_INS0_IfNS_9allocatorIfEEEENS1_IS3_EEEENS1_IS5_EEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorINS0_INS0_IfNS_9allocatorIfEEEENS1_IS3_EEEENS1_IS5_EEE16__destroy_vectorclB9fqe220100Ev
- __ZNSt3__16vectorINS0_INS0_IfNS_9allocatorIfEEEENS1_IS3_EEEENS1_IS5_EEE16__init_with_sizeB9fqe220100IPS5_S9_EEvT_T0_m
- __ZNSt3__16vectorINS0_INS0_IfNS_9allocatorIfEEEENS1_IS3_EEEENS1_IS5_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorINS0_IfNS_9allocatorIfEEEENS1_IS3_EEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorINS0_IfNS_9allocatorIfEEEENS1_IS3_EEE16__destroy_vectorclB9fqe220100Ev
- __ZNSt3__16vectorINS0_IfNS_9allocatorIfEEEENS1_IS3_EEE16__init_with_sizeB9fqe220100IPS3_S7_EEvT_T0_m
- __ZNSt3__16vectorINS0_IfNS_9allocatorIfEEEENS1_IS3_EEE18__assign_with_sizeB9fqe220100INS_17_ClassicAlgPolicyEPS3_S8_EEvT0_T1_l
- __ZNSt3__16vectorINS0_IfNS_9allocatorIfEEEENS1_IS3_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorINS0_IfNS_9allocatorIfEEEENS1_IS3_EEE5clearB9fqe220100Ev
- __ZNSt3__16vectorINS0_IfNS_9allocatorIfEEEENS1_IS3_EEEC2B9fqe220100EmRKS3_
- __ZNSt3__16vectorINS_4pairIfjEENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIfNS_9allocatorIfEEE16__init_with_sizeB9fqe220100IPfS5_EEvT_T0_m
- __ZNSt3__16vectorIfNS_9allocatorIfEEE18__assign_with_sizeB9fqe220100INS_17_ClassicAlgPolicyEPfS6_EEvT0_T1_l
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220100EmRKf
- __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
CStrings:
+ "%s CSVoiceTriggerSecondPass[%{public}@]:secondpass SAT reject but overriding decision with PHS threshold reduced set"
+ "%s Emit OSDDetectionReported speechStartMs=%u thresholdMs=%d silenceProb=%.3f canary=%d modelVersion=%@ mhUUID=%@"
+ "%s Mint a new MHUUID for OSDDetectionReported events"
+ "%s Not handling exclave server endpoint inactive message as the server endpoint connection policy is recommending on demand connection"
+ "%s Resuming timer with uuid %@ to connect to Exclave Server, success: %d"
+ "%s Skipping OSDDetectionReported emit: invalid mhUUID=%{public}@"
+ "%s timer with uuid %@ to connect to Exclave Server triggered"
+ "+[CSAttendingSelfLogger emitOSDDetectionReportedWithSpeechStartTimeInMs:minConsecutiveSpeechThresholdInMs:silenceProbabilityThreshold:isCanarySampled:osdModelVersion:withMHUUID:]"
+ "+[CSSiriAudioActivationInfo _alertDictionaryForRecordRoute:playbackRoute:speechEvent:ringerState:startingAlertBeepOverideID:presentationMode:hasPlayedStartAlert:supportsEchoCancellation:isVoiceOverTouchEnabled:isVibrationEnabled:isVibrationSupported:activationHostTime:isVoiceOverSiriSoundsEnabled:suppressStartAlert:]"
+ "-[CSSpeechManager _cancelConnectionTimer]"
+ "-[CSSpeechManager _handleExclaveServerEndpointActiveMessage]"
+ "-[CSSpeechManager _handleExclaveServerEndpointInactiveMessage]"
+ "-[CSSpeechManager _handleExclaveServerEndpointInactiveMessage]_block_invoke"
+ "-[CSSpeechManager _handleExclaveServerEndpointInactiveMessage]_block_invoke_2"
+ "CSAttendingTriggerInfo:::speechStartTimeInMs"
+ "[speechStartTimeInMs = %u]"
+ "\xa1"
- "!1"
- "%s CSVoiceTriggerSecondPass[%{public}@]:secondpass SAT reject but overriding decision with PHS threshold reduced setted"
- "+[CSSiriAudioActivationInfo _alertDictionaryForRecordRoute:playbackRoute:speechEvent:ringerState:startingAlertBeepOverideID:presentationMode:hasPlayedStartAlert:supportsEchoCancellation:isVoiceOverTouchEnabled:isVibrationEnabled:isVibrationSupported:activationHostTime:isVoiceOverSiriSoundsEnabled:]"
- "com.apple.corespeech.ducking"
```
