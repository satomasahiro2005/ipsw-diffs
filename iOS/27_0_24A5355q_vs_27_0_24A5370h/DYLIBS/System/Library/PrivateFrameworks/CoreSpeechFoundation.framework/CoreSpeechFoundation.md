## CoreSpeechFoundation

> `/System/Library/PrivateFrameworks/CoreSpeechFoundation.framework/CoreSpeechFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc9558` | `0xcab8c` | **`+0x1634`** |
| `__DATA.__bss` | `0xa38` | `0x1638` | **`+0xc00`** |
| `__TEXT.__const` | `0xa28` | `0xfb8` | **`+0x590`** |
| `__TEXT.__cstring` | `0x162ad` | `0x165b7` | **`+0x30a`** |
| `__AUTH_CONST.__const` | `0x18a0` | `0x1ac0` | **`+0x220`** |
| `__AUTH_CONST.__objc_const` | `0x14848` | `0x149d8` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0xe0` | `0x270` | **`+0x190`** |
| `__AUTH_CONST.__cfstring` | `0x93c0` | `0x9500` | **`+0x140`** |
| `__TEXT.__swift5_reflstr` | `0x174` | `0x278` | **`+0x104`** |
| `__DATA.__data` | `0x1848` | `0x1948` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x113a8` | `0x1149f` | **`+0xf7`** |
| `__TEXT.__swift5_fieldmd` | `0x174` | `0x244` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0xd640` | `0xd6e8` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x3b20` | `0x3bc0` | **`+0xa0`** |
| `__AUTH_CONST.__objc_intobj` | `0x420` | `0x4b0` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x7308` | `0x7398` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x25c` | `0x2cc` | **`+0x70`** |
| `__TEXT.__swift5_assocty` | `0x18` | `0x78` | **`+0x60`** |
| `__TEXT.__swift5_proto` | `0x14` | `0x74` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x3bd8` | `0x3c24` | **`+0x4c`** |
| `__TEXT.__swift5_typeref` | `0x19d` | `0x1dc` | **`+0x3f`** |
| `__AUTH_CONST.__auth_got` | `0xf98` | `0xfc0` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x27e8` | `0x2810` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x1018` | `0x1030` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x200` | `0x210` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x20` | `0x30` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xd78` | `0xd80` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x560` | `0x558` | **`-0x8`** |

### Other Changes

```diff

-3600.64.114.1.5
+3600.70.8.0.0

+  - /System/Library/PrivateFrameworks/CoreSpeechUtils.framework/CoreSpeechUtils

+  - /System/Library/PrivateFrameworks/Polaris.framework/Polaris
+  - /System/Library/PrivateFrameworks/PolarisExclaveSupport.framework/PolarisExclaveSupport
+  - /System/Library/PrivateFrameworks/PolarisRuntime.framework/PolarisRuntime

+  - /usr/lib/swift/libswiftOSLog.dylib

-  Functions: 5117
-  Symbols:   9702
-  CStrings:  3691
+  Functions: 5198
+  Symbols:   9751
+  CStrings:  3718
Symbols:
+ +[CSAudioFileManager createAudioFileWriterForCompanionAudioConsumerWithInputFormat:outputFormat:withLoggingUUID:]
+ +[CSAudioFileManager createAudioFileWriterForCompanionAudioProviderWithInputFormat:outputFormat:withLoggingUUID:]
+ +[CSConfig exclaveCircularBufferDurationInSecs]
+ +[CSExclaveEndpoint endpointNameForEndpointType:]
+ +[CSExclaveEndpoint supportsAlwaysOnExclavesForEndpointType:]
+ +[CSExclaveRecordClient clientForEndpointType:]
+ +[CSUtils deviceTypeFromMGDeviceClass:]
+ +[CSUtils getCSDeviceType]
+ +[CSUtils supportsConfigurationBasedNCThresholds]
+ -[CSAudioStartStreamOption originatingDeviceType]
+ -[CSAudioStartStreamOption recordRoute]
+ -[CSAudioStartStreamOption setOriginatingDeviceType:]
+ -[CSAudioStartStreamOption setRecordRoute:]
+ -[CSDiagnosticReporter submitMitigationIssueReport:withContext:]
+ -[CSDiagnosticReporter submitUresIssueReport:withContext:]
+ -[CSExclaveRecordClient endpointName]
+ -[CSExclaveRecordClient initWithEndpointName:supportsAlwaysOnExclaves:]
+ -[CSExclaveRecordClient setEndpointName:]
+ -[CSFAudioChunkQueue count]
+ -[CSFAudioChunkQueue getWholeChunksFromSampleTime:]
+ -[CSFAudioChunkQueue getWholeChunksFromSampleTime:toSampleTime:]
+ -[CSHardwareLatencyHelper cachedInputLatencySeconds]
+ -[CSHardwareLatencyHelper setCachedInputLatencySeconds:]
+ -[CSLaunchAgentXPCClient setAggressiveECMode:completionBlock:]
+ GCC_except_table1320
+ GCC_except_table1349
+ GCC_except_table1431
+ GCC_except_table1432
+ GCC_except_table1433
+ GCC_except_table1434
+ GCC_except_table1436
+ GCC_except_table1437
+ GCC_except_table1449
+ GCC_except_table1455
+ GCC_except_table1457
+ GCC_except_table1461
+ GCC_except_table1462
+ GCC_except_table1463
+ GCC_except_table1465
+ GCC_except_table1469
+ GCC_except_table1481
+ GCC_except_table1879
+ GCC_except_table1883
+ GCC_except_table1887
+ GCC_except_table1889
+ GCC_except_table1895
+ GCC_except_table1902
+ GCC_except_table1905
+ GCC_except_table1920
+ GCC_except_table1926
+ GCC_except_table2014
+ GCC_except_table2019
+ GCC_except_table2077
+ GCC_except_table2087
+ GCC_except_table2129
+ GCC_except_table2130
+ GCC_except_table2132
+ GCC_except_table2133
+ GCC_except_table2139
+ GCC_except_table2150
+ GCC_except_table2157
+ GCC_except_table2200
+ GCC_except_table2218
+ GCC_except_table2297
+ GCC_except_table2407
+ GCC_except_table2442
+ GCC_except_table2586
+ GCC_except_table2590
+ GCC_except_table2669
+ GCC_except_table2680
+ GCC_except_table2682
+ GCC_except_table2687
+ GCC_except_table2689
+ GCC_except_table2702
+ GCC_except_table2709
+ GCC_except_table2711
+ GCC_except_table2729
+ GCC_except_table2750
+ GCC_except_table2788
+ GCC_except_table2845
+ GCC_except_table2847
+ GCC_except_table2848
+ GCC_except_table3010
+ GCC_except_table3150
+ GCC_except_table3158
+ GCC_except_table3166
+ GCC_except_table3180
+ GCC_except_table3182
+ GCC_except_table3183
+ GCC_except_table3225
+ GCC_except_table3286
+ GCC_except_table3290
+ GCC_except_table3345
+ GCC_except_table3357
+ GCC_except_table3361
+ GCC_except_table3368
+ GCC_except_table3377
+ GCC_except_table3400
+ GCC_except_table3401
+ GCC_except_table3402
+ GCC_except_table3403
+ GCC_except_table3428
+ GCC_except_table3441
+ GCC_except_table3600
+ GCC_except_table3660
+ GCC_except_table3674
+ GCC_except_table3716
+ GCC_except_table3717
+ GCC_except_table374
+ GCC_except_table3747
+ GCC_except_table3749
+ GCC_except_table3752
+ GCC_except_table3753
+ GCC_except_table3754
+ GCC_except_table3779
+ GCC_except_table3783
+ GCC_except_table3784
+ GCC_except_table3785
+ GCC_except_table3788
+ GCC_except_table381
+ GCC_except_table3813
+ GCC_except_table382
+ GCC_except_table3839
+ GCC_except_table3860
+ GCC_except_table3880
+ GCC_except_table3881
+ GCC_except_table3882
+ GCC_except_table3883
+ GCC_except_table3893
+ GCC_except_table3984
+ GCC_except_table3994
+ GCC_except_table4008
+ GCC_except_table4009
+ GCC_except_table4010
+ GCC_except_table4011
+ GCC_except_table4012
+ GCC_except_table4017
+ GCC_except_table4024
+ GCC_except_table4027
+ GCC_except_table4032
+ GCC_except_table4036
+ GCC_except_table4044
+ GCC_except_table4045
+ GCC_except_table4046
+ GCC_except_table4048
+ GCC_except_table4049
+ GCC_except_table4051
+ GCC_except_table4052
+ GCC_except_table4053
+ GCC_except_table4054
+ GCC_except_table4081
+ GCC_except_table4129
+ GCC_except_table4133
+ GCC_except_table4184
+ GCC_except_table4191
+ GCC_except_table4192
+ GCC_except_table4193
+ GCC_except_table4194
+ GCC_except_table4196
+ GCC_except_table4197
+ GCC_except_table4220
+ GCC_except_table4221
+ GCC_except_table4222
+ GCC_except_table4224
+ GCC_except_table4225
+ GCC_except_table4226
+ GCC_except_table4227
+ GCC_except_table4228
+ GCC_except_table4229
+ GCC_except_table4231
+ GCC_except_table4257
+ GCC_except_table4259
+ GCC_except_table4262
+ GCC_except_table4264
+ GCC_except_table4266
+ GCC_except_table4268
+ GCC_except_table4271
+ GCC_except_table4273
+ GCC_except_table4274
+ GCC_except_table4278
+ GCC_except_table4280
+ GCC_except_table4282
+ GCC_except_table4302
+ GCC_except_table4303
+ GCC_except_table4305
+ GCC_except_table4308
+ GCC_except_table4312
+ GCC_except_table4317
+ GCC_except_table4319
+ GCC_except_table4323
+ GCC_except_table4324
+ GCC_except_table4354
+ GCC_except_table4466
+ GCC_except_table4473
+ GCC_except_table4555
+ GCC_except_table4622
+ GCC_except_table4632
+ GCC_except_table4689
+ GCC_except_table4690
+ GCC_except_table4692
+ GCC_except_table4693
+ GCC_except_table4694
+ GCC_except_table4695
+ GCC_except_table4696
+ GCC_except_table4697
+ GCC_except_table4699
+ GCC_except_table4701
+ GCC_except_table4702
+ GCC_except_table4703
+ GCC_except_table4741
+ GCC_except_table4807
+ GCC_except_table4812
+ GCC_except_table4853
+ GCC_except_table487
+ GCC_except_table488
+ GCC_except_table4919
+ GCC_except_table521
+ GCC_except_table561
+ GCC_except_table566
+ GCC_except_table584
+ GCC_except_table652
+ GCC_except_table656
+ GCC_except_table661
+ GCC_except_table663
+ GCC_except_table822
+ GCC_except_table829
+ GCC_except_table892
+ GCC_except_table893
+ GCC_except_table900
+ GCC_except_table915
+ GCC_except_table916
+ GCC_except_table917
+ GCC_except_table923
+ GCC_except_table927
+ GCC_except_table928
+ GCC_except_table932
+ GCC_except_table936
+ GCC_except_table937
+ GCC_except_table938
+ GCC_except_table952
+ _CSSupportsAggressiveEC
+ _OBJC_CLASS_$_CSExclaveEndpoint
+ _OBJC_CLASS_$_SecureAudioConfig
+ _OBJC_IVAR_$_CSAudioStartStreamOption._originatingDeviceType
+ _OBJC_IVAR_$_CSAudioStartStreamOption._recordRoute
+ _OBJC_IVAR_$_CSExclaveRecordClient._endpointName
+ _OBJC_IVAR_$_CSHardwareLatencyHelper._cachedInputLatencySeconds
+ _OBJC_IVAR_$_CSUAFDownloadMonitor._adblockerAssetObserverToken
+ _OBJC_IVAR_$_CSUAFDownloadMonitor._attentionAssetObserverToken
+ _OBJC_METACLASS_$_CSExclaveEndpoint
+ __OBJC_$_CLASS_METHODS_CSExclaveEndpoint
+ __OBJC_$_INSTANCE_VARIABLES_CSHardwareLatencyHelper
+ __OBJC_$_PROP_LIST_CSFirstUnlockMonitor
+ __OBJC_$_PROP_LIST_CSHardwareLatencyHelper
+ __OBJC_$_PROP_LIST_CSSiriEnabledMonitor
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CSFirstUnlockMonitorProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CSSiriEnabledMonitorProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSFirstUnlockMonitorProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSSiriEnabledMonitorProviding
+ __OBJC_$_PROTOCOL_REFS_CSFirstUnlockMonitorProviding
+ __OBJC_$_PROTOCOL_REFS_CSSiriEnabledMonitorProviding
+ __OBJC_CLASS_PROTOCOLS_$_CSFirstUnlockMonitor
+ __OBJC_CLASS_PROTOCOLS_$_CSSiriEnabledMonitor
+ __OBJC_CLASS_RO_$_CSExclaveEndpoint
+ __OBJC_LABEL_PROTOCOL_$_CSFirstUnlockMonitorProviding
+ __OBJC_LABEL_PROTOCOL_$_CSSiriEnabledMonitorProviding
+ __OBJC_METACLASS_RO_$_CSExclaveEndpoint
+ __OBJC_PROTOCOL_$_CSFirstUnlockMonitorProviding
+ __OBJC_PROTOCOL_$_CSSiriEnabledMonitorProviding
+ __ZNKSt3__111__copy_implclB9fqe220106IPNS_6vectorINS2_IfNS_9allocatorIfEEEENS3_IS5_EEEES8_S8_Li0EEENS_4pairIT_T1_EESA_T0_SB_
+ __ZNKSt3__111__copy_implclB9fqe220106IPNS_6vectorIfNS_9allocatorIfEEEES6_S6_Li0EEENS_4pairIT_T1_EES8_T0_S9_
+ __ZNKSt3__114default_deleteI21CSAudioZeroFilterImplItEEclB9fqe220106EPS2_
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt12out_of_rangeC1B9fqe220106EPKc
+ __ZNSt16invalid_argumentC1B9fqe220106EPKc
+ __ZNSt3__110unique_ptrI18BatchBeepCancellerNS_14default_deleteIS1_EEE5resetB9fqe220106EPS1_
+ __ZNSt3__110unique_ptrI22NonlinearBeepCancellerNS_14default_deleteIS1_EEE5resetB9fqe220106EPS1_
+ __ZNSt3__110unique_ptrI24CSAudioSpectralMeterImplNS_14default_deleteIS1_EEE5resetB9fqe220106EPS1_
+ __ZNSt3__110unique_ptrIN10corespeech25CSAudioCircularBufferImplItEENS_14default_deleteIS3_EEE5resetB9fqe220106EPS3_
+ __ZNSt3__116__if_likely_elseB9fqe220106IZNS_6vectorIN21CSAudioZeroFilterImplItE7ZeroRunENS_9allocatorIS4_EEE12emplace_backIJmRmEEEvDpOT_EUlvE_ZNS8_IJmS9_EEEvSC_EUlvE0_EEvbT_T0_
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIN21CSAudioZeroFilterImplItE7ZeroRunEEENS_16allocator_traitsIS5_EEEENS_19__allocation_resultINT0_7pointerENS9_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIPjEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorItEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__120__throw_out_of_rangeB9fqe220106EPKc
+ __ZNSt3__128__exception_guard_exceptionsINS_29_AllocatorDestroyRangeReverseINS_9allocatorINS_6vectorIfNS2_IfEEEEEEPS5_EEED2B9fqe220106Ev
+ __ZNSt3__135__uninitialized_allocator_copy_implB9fqe220106INS_9allocatorINS_6vectorINS2_IfNS1_IfEEEENS1_IS4_EEEEEEPS6_S8_S8_EET2_RT_T0_T1_S9_
+ __ZNSt3__135__uninitialized_allocator_copy_implB9fqe220106INS_9allocatorINS_6vectorIfNS1_IfEEEEEEPS4_S6_S6_EET2_RT_T0_T1_S7_
+ __ZNSt3__16vectorI21bnns_graph_argument_tNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIN21CSAudioZeroFilterImplItE7ZeroRunENS_9allocatorIS3_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS0_INS0_INS0_IfNS_9allocatorIfEEEENS1_IS3_EEEENS1_IS5_EEEENS1_IS7_EEE16__destroy_vectorclB9fqe220106Ev
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
+ __ZNSt3__16vectorINS0_IhNS_9allocatorIhEEEENS1_IS3_EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorINS0_IhNS_9allocatorIhEEEENS1_IS3_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS0_IhNS_9allocatorIhEEEENS1_IS3_EEE5clearB9fqe220106Ev
+ __ZNSt3__16vectorINS0_IjNS_9allocatorIjEEEENS1_IS3_EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorIPKcNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIPKcNS_9allocatorIS2_EEEC2B9fqe220106Em
+ __ZNSt3__16vectorIPKtNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE16__init_with_sizeB9fqe220106IPfS5_EEvT_T0_m
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE18__assign_with_sizeB9fqe220106INS_17_ClassicAlgPolicyEPfS6_EEvT0_T1_l
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220106Em
+ __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220106EmRKf
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE16__init_with_sizeB9fqe220106IPhS5_EEvT_T0_m
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorItNS_9allocatorItEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ __ZZ47+[CSExclaveRecordClient clientForEndpointType:]E8instance
+ __ZZ47+[CSExclaveRecordClient clientForEndpointType:]E9onceToken
+ ___26+[CSUtils getCSDeviceType]_block_invoke
+ ___47+[CSExclaveRecordClient clientForEndpointType:]_block_invoke
+ ___49+[CSUtils supportsConfigurationBasedNCThresholds]_block_invoke
+ ___50-[CSUAFDownloadMonitor _startMonitoringWithQueue:]_block_invoke_2
+ ___62-[CSLaunchAgentXPCClient setAggressiveECMode:completionBlock:]_block_invoke
+ ___71-[CSExclaveRecordClient initWithEndpointName:supportsAlwaysOnExclaves:]_block_invoke
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftOSLog_$_CoreSpeechFoundation
+ _associated conformance 20CoreSpeechFoundation23PolarisGraphIdentifiersOSHAASQ
+ _associated conformance 20CoreSpeechFoundation24PolarisWritersIdentifierOSHAASQ
+ _associated conformance 20CoreSpeechFoundation36PolarisWritersCentralizedIdentifiersOSHAASQ
+ _associated conformance 20CoreSpeechFoundation40PolarisGraphOutputCentralizedIdentifiersOSHAASQ
+ _getCSDeviceType.deviceType
+ _getCSDeviceType.onceToken
+ _kAdBlockerAssetName
+ _kCSAttSiriBPCategoryKey
+ _kCSAttSiriRTSCategoryKey
+ _kCSDiagnosticReporterMitigationSnapshotTime
+ _kCSDiagnosticReporterMitigationSpkrIdPassThrough
+ _kCSDiagnosticReporterMitigationTypeKey
+ _kCSDiagnosticReporterUresConfigInvalid
+ _kUAFAdBlockerAssetSetName
+ _kVTEIInputLatency
+ _supportsConfigurationBasedNCThresholds.onceToken
+ _supportsConfigurationBasedNCThresholds.result
+ _symbolic _____ 20CoreSpeechFoundation23PolarisGraphIdentifiersO
+ _symbolic _____ 20CoreSpeechFoundation24PolarisWritersIdentifierO
+ _symbolic _____ 20CoreSpeechFoundation36PolarisWritersCentralizedIdentifiersO
+ _symbolic _____ 20CoreSpeechFoundation40PolarisGraphOutputCentralizedIdentifiersO
+ _symbolic _____ s6UInt32V
- +[CSExclaveMessageHandlingFactory sharedFactory]
- +[CSExclaveRecordClient sharedClientWithServiceName:supportsAlwaysOnExclaves:]
- +[CSExclaveRecordClient sharedClient]
- +[CSVisionAudioAccessoryAvailabilityMonitor sharedMonitor]
- -[CSExclaveMessageHandlingFactory .cxx_destruct]
- -[CSExclaveMessageHandlingFactory cachedExclaveRecordClientForServiceName:supportsAlwaysOnExclaves:]
- -[CSExclaveMessageHandlingFactory dealloc]
- -[CSExclaveMessageHandlingFactory init]
- -[CSExclaveRecordClient initWithServiceName:supportsAlwaysOnExclaves:]
- -[CSExclaveRecordClient serviceName]
- -[CSExclaveRecordClient setServiceName:]
- -[CSVisionAudioAccessoryAvailabilityMonitor _startMonitoringWithQueue:]
- -[CSVisionAudioAccessoryAvailabilityMonitor _stopMonitoring]
- -[CSVisionAudioAccessoryAvailabilityMonitor isAvailable]
- GCC_except_table1309
- GCC_except_table1338
- GCC_except_table1416
- GCC_except_table1420
- GCC_except_table1421
- GCC_except_table1422
- GCC_except_table1423
- GCC_except_table1424
- GCC_except_table1425
- GCC_except_table1426
- GCC_except_table1428
- GCC_except_table1444
- GCC_except_table1447
- GCC_except_table1451
- GCC_except_table1452
- GCC_except_table1454
- GCC_except_table1471
- GCC_except_table1874
- GCC_except_table1882
- GCC_except_table1885
- GCC_except_table1888
- GCC_except_table1894
- GCC_except_table1901
- GCC_except_table1903
- GCC_except_table1919
- GCC_except_table1925
- GCC_except_table2013
- GCC_except_table2018
- GCC_except_table2072
- GCC_except_table2082
- GCC_except_table2124
- GCC_except_table2125
- GCC_except_table2127
- GCC_except_table2128
- GCC_except_table2134
- GCC_except_table2145
- GCC_except_table2152
- GCC_except_table2195
- GCC_except_table2213
- GCC_except_table2291
- GCC_except_table2401
- GCC_except_table2436
- GCC_except_table2580
- GCC_except_table2584
- GCC_except_table2663
- GCC_except_table2674
- GCC_except_table2676
- GCC_except_table2681
- GCC_except_table2683
- GCC_except_table2696
- GCC_except_table2703
- GCC_except_table2705
- GCC_except_table2723
- GCC_except_table2744
- GCC_except_table2782
- GCC_except_table2839
- GCC_except_table2841
- GCC_except_table2842
- GCC_except_table3004
- GCC_except_table3144
- GCC_except_table3152
- GCC_except_table3160
- GCC_except_table3170
- GCC_except_table3174
- GCC_except_table3177
- GCC_except_table3213
- GCC_except_table3280
- GCC_except_table3284
- GCC_except_table3339
- GCC_except_table3351
- GCC_except_table3355
- GCC_except_table3362
- GCC_except_table3371
- GCC_except_table3394
- GCC_except_table3395
- GCC_except_table3396
- GCC_except_table3397
- GCC_except_table3420
- GCC_except_table3433
- GCC_except_table3592
- GCC_except_table3652
- GCC_except_table3666
- GCC_except_table3708
- GCC_except_table3709
- GCC_except_table372
- GCC_except_table3738
- GCC_except_table3739
- GCC_except_table3741
- GCC_except_table3744
- GCC_except_table3745
- GCC_except_table376
- GCC_except_table3769
- GCC_except_table377
- GCC_except_table3771
- GCC_except_table3775
- GCC_except_table3776
- GCC_except_table3780
- GCC_except_table3805
- GCC_except_table3831
- GCC_except_table3852
- GCC_except_table3872
- GCC_except_table3873
- GCC_except_table3874
- GCC_except_table3875
- GCC_except_table3885
- GCC_except_table3973
- GCC_except_table3974
- GCC_except_table3983
- GCC_except_table3986
- GCC_except_table3987
- GCC_except_table3988
- GCC_except_table3991
- GCC_except_table3992
- GCC_except_table3995
- GCC_except_table4000
- GCC_except_table4001
- GCC_except_table4016
- GCC_except_table4019
- GCC_except_table4021
- GCC_except_table4022
- GCC_except_table4026
- GCC_except_table4031
- GCC_except_table4034
- GCC_except_table4035
- GCC_except_table4038
- GCC_except_table4043
- GCC_except_table4070
- GCC_except_table4118
- GCC_except_table4122
- GCC_except_table4172
- GCC_except_table4173
- GCC_except_table4180
- GCC_except_table4181
- GCC_except_table4182
- GCC_except_table4185
- GCC_except_table4186
- GCC_except_table4207
- GCC_except_table4208
- GCC_except_table4209
- GCC_except_table4211
- GCC_except_table4212
- GCC_except_table4213
- GCC_except_table4214
- GCC_except_table4215
- GCC_except_table4216
- GCC_except_table4217
- GCC_except_table4239
- GCC_except_table4241
- GCC_except_table4242
- GCC_except_table4244
- GCC_except_table4245
- GCC_except_table4246
- GCC_except_table4247
- GCC_except_table4249
- GCC_except_table4251
- GCC_except_table4253
- GCC_except_table4261
- GCC_except_table4263
- GCC_except_table4290
- GCC_except_table4292
- GCC_except_table4293
- GCC_except_table4295
- GCC_except_table4297
- GCC_except_table4298
- GCC_except_table4299
- GCC_except_table4304
- GCC_except_table4341
- GCC_except_table4451
- GCC_except_table4458
- GCC_except_table4540
- GCC_except_table4607
- GCC_except_table4617
- GCC_except_table4673
- GCC_except_table4674
- GCC_except_table4675
- GCC_except_table4677
- GCC_except_table4678
- GCC_except_table4679
- GCC_except_table4680
- GCC_except_table4681
- GCC_except_table4682
- GCC_except_table4684
- GCC_except_table4686
- GCC_except_table4687
- GCC_except_table4726
- GCC_except_table4792
- GCC_except_table4797
- GCC_except_table4838
- GCC_except_table485
- GCC_except_table486
- GCC_except_table4904
- GCC_except_table519
- GCC_except_table555
- GCC_except_table563
- GCC_except_table581
- GCC_except_table649
- GCC_except_table653
- GCC_except_table658
- GCC_except_table660
- GCC_except_table819
- GCC_except_table826
- GCC_except_table889
- GCC_except_table890
- GCC_except_table897
- GCC_except_table912
- GCC_except_table913
- GCC_except_table914
- GCC_except_table918
- GCC_except_table919
- GCC_except_table920
- GCC_except_table926
- GCC_except_table930
- GCC_except_table931
- GCC_except_table935
- GCC_except_table949
- _OBJC_CLASS_$_CSVisionAudioAccessoryAvailabilityMonitor
- _OBJC_IVAR_$_CSExclaveMessageHandlingFactory._cacheQueue
- _OBJC_IVAR_$_CSExclaveMessageHandlingFactory._exclaveRecordClientCache
- _OBJC_IVAR_$_CSExclaveRecordClient._serviceName
- _OBJC_IVAR_$_CSUAFDownloadMonitor._observerToken
- _OBJC_METACLASS_$_CSVisionAudioAccessoryAvailabilityMonitor
- __OBJC_$_CLASS_METHODS_CSVisionAudioAccessoryAvailabilityMonitor
- __OBJC_$_INSTANCE_METHODS_CSExclaveMessageHandlingFactory
- __OBJC_$_INSTANCE_METHODS_CSVisionAudioAccessoryAvailabilityMonitor
- __OBJC_$_INSTANCE_VARIABLES_CSExclaveMessageHandlingFactory
- __OBJC_CLASS_RO_$_CSVisionAudioAccessoryAvailabilityMonitor
- __OBJC_METACLASS_RO_$_CSVisionAudioAccessoryAvailabilityMonitor
- __ZNKSt3__111__copy_implclB9fqe220100IPNS_6vectorINS2_IfNS_9allocatorIfEEEENS3_IS5_EEEES8_S8_Li0EEENS_4pairIT_T1_EESA_T0_SB_
- __ZNKSt3__111__copy_implclB9fqe220100IPNS_6vectorIfNS_9allocatorIfEEEES6_S6_Li0EEENS_4pairIT_T1_EES8_T0_S9_
- __ZNKSt3__114default_deleteI21CSAudioZeroFilterImplItEEclB9fqe220100EPS2_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt12out_of_rangeC1B9fqe220100EPKc
- __ZNSt16invalid_argumentC1B9fqe220100EPKc
- __ZNSt3__110unique_ptrI18BatchBeepCancellerNS_14default_deleteIS1_EEE5resetB9fqe220100EPS1_
- __ZNSt3__110unique_ptrI22NonlinearBeepCancellerNS_14default_deleteIS1_EEE5resetB9fqe220100EPS1_
- __ZNSt3__110unique_ptrI24CSAudioSpectralMeterImplNS_14default_deleteIS1_EEE5resetB9fqe220100EPS1_
- __ZNSt3__110unique_ptrIN10corespeech25CSAudioCircularBufferImplItEENS_14default_deleteIS3_EEE5resetB9fqe220100EPS3_
- __ZNSt3__116__if_likely_elseB9fqe220100IZNS_6vectorIN21CSAudioZeroFilterImplItE7ZeroRunENS_9allocatorIS4_EEE12emplace_backIJmRmEEEvDpOT_EUlvE_ZNS8_IJmS9_EEEvSC_EUlvE0_EEvbT_T0_
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIN21CSAudioZeroFilterImplItE7ZeroRunEEENS_16allocator_traitsIS5_EEEENS_19__allocation_resultINT0_7pointerENS9_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIPjEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorItEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__120__throw_out_of_rangeB9fqe220100EPKc
- __ZNSt3__128__exception_guard_exceptionsINS_29_AllocatorDestroyRangeReverseINS_9allocatorINS_6vectorIfNS2_IfEEEEEEPS5_EEED2B9fqe220100Ev
- __ZNSt3__135__uninitialized_allocator_copy_implB9fqe220100INS_9allocatorINS_6vectorINS2_IfNS1_IfEEEENS1_IS4_EEEEEEPS6_S8_S8_EET2_RT_T0_T1_S9_
- __ZNSt3__135__uninitialized_allocator_copy_implB9fqe220100INS_9allocatorINS_6vectorIfNS1_IfEEEEEEPS4_S6_S6_EET2_RT_T0_T1_S7_
- __ZNSt3__16vectorI21bnns_graph_argument_tNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIN21CSAudioZeroFilterImplItE7ZeroRunENS_9allocatorIS3_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorINS0_INS0_INS0_IfNS_9allocatorIfEEEENS1_IS3_EEEENS1_IS5_EEEENS1_IS7_EEE16__destroy_vectorclB9fqe220100Ev
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
- __ZNSt3__16vectorINS0_IhNS_9allocatorIhEEEENS1_IS3_EEE16__destroy_vectorclB9fqe220100Ev
- __ZNSt3__16vectorINS0_IhNS_9allocatorIhEEEENS1_IS3_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorINS0_IhNS_9allocatorIhEEEENS1_IS3_EEE5clearB9fqe220100Ev
- __ZNSt3__16vectorINS0_IjNS_9allocatorIjEEEENS1_IS3_EEE16__destroy_vectorclB9fqe220100Ev
- __ZNSt3__16vectorIPKcNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIPKcNS_9allocatorIS2_EEEC2B9fqe220100Em
- __ZNSt3__16vectorIPKtNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIfNS_9allocatorIfEEE16__init_with_sizeB9fqe220100IPfS5_EEvT_T0_m
- __ZNSt3__16vectorIfNS_9allocatorIfEEE18__assign_with_sizeB9fqe220100INS_17_ClassicAlgPolicyEPfS6_EEvT0_T1_l
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220100Em
- __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220100EmRKf
- __ZNSt3__16vectorIhNS_9allocatorIhEEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIhNS_9allocatorIhEEE16__init_with_sizeB9fqe220100IPhS5_EEvT_T0_m
- __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorItNS_9allocatorItEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- __ZZ78+[CSExclaveRecordClient sharedClientWithServiceName:supportsAlwaysOnExclaves:]E12sharedClient
- __ZZ78+[CSExclaveRecordClient sharedClientWithServiceName:supportsAlwaysOnExclaves:]E9onceToken
- ___100-[CSExclaveMessageHandlingFactory cachedExclaveRecordClientForServiceName:supportsAlwaysOnExclaves:]_block_invoke
- ___48+[CSExclaveMessageHandlingFactory sharedFactory]_block_invoke
- ___58+[CSVisionAudioAccessoryAvailabilityMonitor sharedMonitor]_block_invoke
- ___70-[CSExclaveRecordClient initWithServiceName:supportsAlwaysOnExclaves:]_block_invoke
- ___78+[CSExclaveRecordClient sharedClientWithServiceName:supportsAlwaysOnExclaves:]_block_invoke
- ___block_descriptor_57_e8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
- _kSiriAttAssetAdBlockerAssetName
- _sharedFactory.onceToken
- _sharedFactory.sharedInstance
CStrings:
+ "%s Cached inputLatency = %{public}f s"
+ "%s Creating CSExclaveRecordClient for endpoint name: %@ [supportsAlwaysOnExclaves: %d]"
+ "%s Invalid CSExclaveEndpointType: %ld"
+ "%s Skipping inputLatency cache — non-built-in audio route active"
+ "%s deactivate called but tap not running, skipping"
+ "+[CSAudioFileManager createAudioFileWriterForCompanionAudioConsumerWithInputFormat:outputFormat:withLoggingUUID:]"
+ "+[CSAudioFileManager createAudioFileWriterForCompanionAudioProviderWithInputFormat:outputFormat:withLoggingUUID:]"
+ "+[CSExclaveRecordClient clientForEndpointType:]"
+ "-[CSAudioRecorder voiceControllerDidSetAudioSessionActive:isActivated:]_block_invoke"
+ "-[CSExclaveRecordClient initWithEndpointName:supportsAlwaysOnExclaves:]"
+ "AttSiriBP"
+ "AttSiriRTS"
+ "Consumer-"
+ "Keyword Second Pass Result is Available"
+ "Provider-"
+ "[originatingDeviceType = %lu]"
+ "[recordRoute = %@]"
+ "aggressiveECMode"
+ "configInvalid"
+ "configuration_based_nc_thresholds"
+ "inputLatency"
+ "originatingDeviceType"
+ "recordRoute"
+ "rtsMotionAnalysis"
+ "rtsMotionAnalyzerResult"
+ "rtsNeuralCombiner"
+ "rtsSpeechAnalysis"
+ "rtsSpeechAnalyzerResult"
+ "secondPassAnalyzerEndHostTime"
+ "secondPassAnalyzerStartHostTime"
+ "spkrIdPassThrough"
+ "\x93"
- "%s Creating CSExclaveRecordClient"
- "-[CSExclaveRecordClient initWithServiceName:supportsAlwaysOnExclaves:]"
- "Keyword Rejected"
- "com.apple.corespeech.exclaveMessageHandlingFactory.cache"
- "\x92"
```
