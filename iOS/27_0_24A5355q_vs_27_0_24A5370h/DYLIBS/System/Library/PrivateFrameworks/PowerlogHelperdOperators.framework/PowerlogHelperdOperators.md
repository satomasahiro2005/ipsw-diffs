## PowerlogHelperdOperators

> `/System/Library/PrivateFrameworks/PowerlogHelperdOperators.framework/PowerlogHelperdOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d6324` | `0x1d5360` | **`-0xfc4`** |
| `__TEXT.__oslogstring` | `0x141b5` | `0x148f6` | **`+0x741`** |
| `__AUTH_CONST.__cfstring` | `0x32b60` | `0x330e0` | **`+0x580`** |
| `__AUTH_CONST.__objc_const` | `0x15410` | `0x15748` | **`+0x338`** |
| `__DATA_CONST.__objc_arraydata` | `0x15770` | `0x15940` | **`+0x1d0`** |
| `__TEXT.__objc_methlist` | `0x10528` | `0x106c0` | **`+0x198`** |
| `__DATA.__bss` | `0x2250` | `0x20c8` | **`-0x188`** |
| `__DATA_CONST.__objc_selrefs` | `0xa938` | `0xaac0` | **`+0x188`** |
| `__TEXT.__cstring` | `0x26012` | `0x25f10` | **`-0x102`** |
| `__DATA.__data` | `0x4c0` | `0x580` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x23cc` | `0x247c` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x43b0` | `0x4420` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x3a08` | `0x3a78` | **`+0x70`** |
| `__AUTH.__objc_data` | `0xb90` | `0xbe0` | **`+0x50`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x2df0` | `0x2e38` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x19c0` | `0x1a00` | **`+0x40`** |
| `__AUTH_CONST.__objc_dictobj` | `0x3a20` | `0x39f8` | **`-0x28`** |
| `__DATA.__objc_ivar` | `0x156c` | `0x1590` | **`+0x24`** |
| `__AUTH_CONST.__objc_doubleobj` | `0xbb0` | `0xb90` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xf20` | `0xf40` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x60` | `0x70` | **`+0x10`** |
| `__TEXT.__const` | `0x6d0` | `0x6e0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x378` | `0x380` | **`+0x8`** |

### Other Changes

```diff

-3468.0.0.502.1
+3486.0.21.502.1

-  Functions: 8442
-  Symbols:   11514
-  CStrings:  8798
+  Functions: 8495
+  Symbols:   11551
+  CStrings:  8872
Symbols:
+ -[PLBatteryAgent batteryHealthDictForPack:inIOPSDict:]
+ -[PLBatteryAgent getBatteryHealthServiceFlagsForPack:]
+ -[PLBatteryAgent getBatteryHealthServiceStateForPack:]
+ -[PLBatteryAgent getBatteryMaximumCapacityPercentForPack:]
+ -[PLBatteryAgent parsedCPMSKeysFromLowBatteryLog]
+ -[PLCoalitionAgent buildPLEntryDiffForObject:withStartDate:withEndDate:]
+ -[PLCoalitionAgent logCoalitionObjectDifference]
+ -[PLCoalitionAgent logOSMetrics:]
+ -[PLCoalitionAgent shouldLogCoalitionObject:]
+ -[PLCoalitionDataObject coalResourceUsage]
+ -[PLCoalitionDataObject hasPrevSample]
+ -[PLCoalitionDataObject prevCoalResourceUsage]
+ -[PLCoalitionDataObject updateWithResourceUsage:]
+ -[PLDisplayAgent builtInCADisplay]
+ -[PLDisplayAgent cbClient]
+ -[PLDisplayAgent cbDisplayClient]
+ -[PLDisplayAgent copyCoreBrightnessPropertyForKey:]
+ -[PLDisplayAgent hasCoreBrightnessClient]
+ -[PLDisplayAgent modernDisplayObserver]
+ -[PLDisplayAgent setCbClient:]
+ -[PLDisplayAgent setCbDisplayClient:]
+ -[PLDisplayAgent setModernDisplayObserver:]
+ -[PLDisplayAgent setupModernCoreBrightnessClient]
+ -[_PLDisplayCBPropertyObserver .cxx_destruct]
+ -[_PLDisplayCBPropertyObserver agent]
+ -[_PLDisplayCBPropertyObserver handle]
+ -[_PLDisplayCBPropertyObserver initWithAgent:properties:]
+ -[_PLDisplayCBPropertyObserver notifyQueue]
+ -[_PLDisplayCBPropertyObserver observeValue:forKey:andHandle:withContext:]
+ -[_PLDisplayCBPropertyObserver properties]
+ -[_PLDisplayCBPropertyObserver setAgent:]
+ -[_PLDisplayCBPropertyObserver setHandle:]
+ -[_PLDisplayCBPropertyObserver setNotifyQueue:]
+ -[_PLDisplayCBPropertyObserver setProperties:]
+ GCC_except_table133
+ GCC_except_table137
+ GCC_except_table156
+ GCC_except_table173
+ GCC_except_table185
+ GCC_except_table190
+ GCC_except_table219
+ GCC_except_table244
+ GCC_except_table256
+ GCC_except_table258
+ GCC_except_table266
+ GCC_except_table267
+ GCC_except_table273
+ GCC_except_table274
+ GCC_except_table278
+ GCC_except_table279
+ GCC_except_table323
+ GCC_except_table327
+ _OBJC_CLASS_$_CBClient
+ _OBJC_CLASS_$_NSRegularExpression
+ _OBJC_CLASS_$_NSScanner
+ _OBJC_CLASS_$__PLDisplayCBPropertyObserver
+ _OBJC_IVAR_$_PLCoalitionDataObject._coalResourceUsage
+ _OBJC_IVAR_$_PLCoalitionDataObject._hasPrevSample
+ _OBJC_IVAR_$_PLCoalitionDataObject._prevCoalResourceUsage
+ _OBJC_IVAR_$_PLDisplayAgent._cbClient
+ _OBJC_IVAR_$_PLDisplayAgent._cbDisplayClient
+ _OBJC_IVAR_$_PLDisplayAgent._modernDisplayObserver
+ _OBJC_IVAR_$__PLDisplayCBPropertyObserver._agent
+ _OBJC_IVAR_$__PLDisplayCBPropertyObserver._handle
+ _OBJC_IVAR_$__PLDisplayCBPropertyObserver._notifyQueue
+ _OBJC_IVAR_$__PLDisplayCBPropertyObserver._properties
+ _OBJC_METACLASS_$__PLDisplayCBPropertyObserver
+ _OUTLINED_FUNCTION_15
+ _OUTLINED_FUNCTION_16
+ _OUTLINED_FUNCTION_17
+ _OUTLINED_FUNCTION_18
+ _OUTLINED_FUNCTION_19
+ _OUTLINED_FUNCTION_20
+ _OUTLINED_FUNCTION_21
+ _PLBatteryAgentCPMSControlSnapshotBaseKeys.keys
+ _PLBatteryAgentCPMSControlSnapshotBaseKeys.once
+ __OBJC_$_INSTANCE_METHODS__PLDisplayCBPropertyObserver
+ __OBJC_$_INSTANCE_VARIABLES__PLDisplayCBPropertyObserver
+ __OBJC_$_PROP_LIST_CBPropertyObserver
+ __OBJC_$_PROP_LIST_CBTargetedPropertyObserver
+ __OBJC_$_PROP_LIST__PLDisplayCBPropertyObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBPropertyObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBTargetedPropertyObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBPropertyObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBTargetedPropertyObserver
+ __OBJC_$_PROTOCOL_REFS_CBPropertyObserver
+ __OBJC_$_PROTOCOL_REFS_CBTargetedPropertyObserver
+ __OBJC_CLASS_PROTOCOLS_$__PLDisplayCBPropertyObserver
+ __OBJC_CLASS_RO_$__PLDisplayCBPropertyObserver
+ __OBJC_LABEL_PROTOCOL_$_CBPropertyObserver
+ __OBJC_LABEL_PROTOCOL_$_CBTargetedPropertyObserver
+ __OBJC_METACLASS_RO_$__PLDisplayCBPropertyObserver
+ __OBJC_PROTOCOL_$_CBPropertyObserver
+ __OBJC_PROTOCOL_$_CBTargetedPropertyObserver
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__110unique_ptrINS_11__hash_nodeINS_17__hash_value_typeIyN12PLProcessCPU12inode_data_tEEEPvEENS_22__hash_node_destructorINS_9allocatorIS7_EEEEED1B9fqe220106Ev
+ __ZNSt3__112__destroy_atB9fqe220106INS_4pairIKyN12PLProcessCPU12inode_data_tEEEEEvPT_
+ __ZNSt3__112__hash_tableINS_17__hash_value_typeIyN12PLProcessCPU12inode_data_tEEENS_22__unordered_map_hasherIyNS_4pairIKyS3_EENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS8_SC_SA_EENS_9allocatorIS8_EEE22__deallocate_node_listB9fqe220106EPNS_16__hash_node_baseIPNS_11__hash_nodeIS4_PvEEEE
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__113__tree_removeB9fqe220106IPNS_16__tree_node_baseIPvEEEEvT_S5_
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIiEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__127__tree_balance_after_insertB9fqe220106IPNS_16__tree_node_baseIPvEEEEvT_S5_
+ __ZNSt3__13setINS_4pairIyyEEN12PLProcessCPU9compare_tENS_9allocatorIS2_EEE6insertB9fqe220106EOS2_
+ __ZNSt3__16__treeINS_4pairIyyEEN12PLProcessCPU9compare_tENS_9allocatorIS2_EEE12__find_equalB9fqe220106IS2_EENS1_IPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERSD_EERKT_
+ __ZNSt3__16__treeINS_4pairIyyEEN12PLProcessCPU9compare_tENS_9allocatorIS2_EEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeIS2_PvEE
+ __ZNSt3__16vectorIiNS_9allocatorIiEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIiN12PLProcessCPU11inode_cpu_tEEENS_22__unordered_map_hasherIiNS_4pairIKiS3_EENS_4hashIiEENS_8equal_toIiEEEENS_21__unordered_map_equalIiS8_SC_SA_EENS_9allocatorIS8_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS7_EEENSN_IJEEEEEENS6_INS_15__hash_iteratorIPNS_11__hash_nodeIS4_PvEEEEbEEDpOT_ENKUlSO_SM_OSP_OSQ_E_clESO_SM_S11_S12_
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIyN12PLProcessCPU12inode_data_tEEENS_22__unordered_map_hasherIyNS_4pairIKyS3_EENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS8_SC_SA_EENS_9allocatorIS8_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS7_EEENSN_IJEEEEEENS6_INS_15__hash_iteratorIPNS_11__hash_nodeIS4_PvEEEEbEEDpOT_ENKUlSO_SM_OSP_OSQ_E_clESO_SM_S11_S12_
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIyyEENS_22__unordered_map_hasherIyNS_4pairIKyyEENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS6_SA_S8_EENS_9allocatorIS6_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS5_EEENSL_IJEEEEEENS4_INS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlSM_SK_OSN_OSO_E_clESM_SK_SZ_S10_
+ __ZZNSt3__112__hash_tableIiNS_4hashIiEENS_8equal_toIiEENS_9allocatorIiEEE16__emplace_uniqueB9fqe220106IJRKiEEENS_4pairINS_15__hash_iteratorIPNS_11__hash_nodeIiPvEEEEbEEDpOT_ENKUlSA_SA_E_clESA_SA_
+ ___46-[PLBatteryAgent logEventPointBatteryShutdown]_block_invoke_2
+ ___48-[PLCoalitionAgent logCoalitionObjectDifference]_block_invoke
+ ___49-[PLBatteryAgent parsedCPMSKeysFromLowBatteryLog]_block_invoke
+ ___49-[PLBatteryAgent parsedCPMSKeysFromLowBatteryLog]_block_invoke_2
+ ___49-[PLDisplayAgent setupModernCoreBrightnessClient]_block_invoke
+ ___PLBatteryAgentCPMSControlSnapshotBaseKeys_block_invoke
+ ___block_descriptor_40_e8_32w_e11_v24?0Q816lw32l8
+ ___block_descriptor_40_e8_32w_e34_v16?0^{?=BBBi{?={?=ii}{?=ii}}QB}8lw32l8
+ ___block_descriptor_48_e8_32s40s_e37_v32?0"NSTextCheckingResult"8Q16^B24ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
+ _logCoalitionObjectDifference.classDebugEnabled
+ _logCoalitionObjectDifference.defaultOnce
+ _objc_release_x2
+ _parsedCPMSKeysFromLowBatteryLog.kvRegex
+ _parsedCPMSKeysFromLowBatteryLog.once
- -[PLCoalitionAgent buildPLEntryDiffWithStartObject:withEndObject:withStartDate:withEndDate:]
- -[PLCoalitionAgent logCoalitionObjectDifference:]
- -[PLCoalitionAgent logOSMetrics:withEndObject:]
- -[PLCoalitionAgent shouldLogCoalitionObject:withEndObject:]
- -[PLCoalitionDataObject coalStruct]
- -[PLCoalitionDataObject dealloc]
- -[PLCoalitionDataObject setCoalStruct:]
- GCC_except_table134
- GCC_except_table138
- GCC_except_table167
- GCC_except_table172
- GCC_except_table178
- GCC_except_table191
- GCC_except_table218
- GCC_except_table243
- GCC_except_table257
- GCC_except_table259
- GCC_except_table264
- GCC_except_table265
- GCC_except_table270
- GCC_except_table271
- GCC_except_table276
- GCC_except_table282
- GCC_except_table318
- GCC_except_table324
- _OBJC_IVAR_$_PLCoalitionDataObject._coalStruct
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__110unique_ptrINS_11__hash_nodeINS_17__hash_value_typeIyN12PLProcessCPU12inode_data_tEEEPvEENS_22__hash_node_destructorINS_9allocatorIS7_EEEEED1B9fqe220100Ev
- __ZNSt3__112__destroy_atB9fqe220100INS_4pairIKyN12PLProcessCPU12inode_data_tEEEEEvPT_
- __ZNSt3__112__hash_tableINS_17__hash_value_typeIyN12PLProcessCPU12inode_data_tEEENS_22__unordered_map_hasherIyNS_4pairIKyS3_EENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS8_SC_SA_EENS_9allocatorIS8_EEE22__deallocate_node_listB9fqe220100EPNS_16__hash_node_baseIPNS_11__hash_nodeIS4_PvEEEE
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__113__tree_removeB9fqe220100IPNS_16__tree_node_baseIPvEEEEvT_S5_
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIiEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__127__tree_balance_after_insertB9fqe220100IPNS_16__tree_node_baseIPvEEEEvT_S5_
- __ZNSt3__13setINS_4pairIyyEEN12PLProcessCPU9compare_tENS_9allocatorIS2_EEE6insertB9fqe220100EOS2_
- __ZNSt3__16__treeINS_4pairIyyEEN12PLProcessCPU9compare_tENS_9allocatorIS2_EEE12__find_equalB9fqe220100IS2_EENS1_IPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERSD_EERKT_
- __ZNSt3__16__treeINS_4pairIyyEEN12PLProcessCPU9compare_tENS_9allocatorIS2_EEE14__tree_deleterclB9fqe220100EPNS_11__tree_nodeIS2_PvEE
- __ZNSt3__16vectorIiNS_9allocatorIiEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIiN12PLProcessCPU11inode_cpu_tEEENS_22__unordered_map_hasherIiNS_4pairIKiS3_EENS_4hashIiEENS_8equal_toIiEEEENS_21__unordered_map_equalIiS8_SC_SA_EENS_9allocatorIS8_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJRS7_EEENSN_IJEEEEEENS6_INS_15__hash_iteratorIPNS_11__hash_nodeIS4_PvEEEEbEEDpOT_ENKUlSO_SM_OSP_OSQ_E_clESO_SM_S11_S12_
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIyN12PLProcessCPU12inode_data_tEEENS_22__unordered_map_hasherIyNS_4pairIKyS3_EENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS8_SC_SA_EENS_9allocatorIS8_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJRS7_EEENSN_IJEEEEEENS6_INS_15__hash_iteratorIPNS_11__hash_nodeIS4_PvEEEEbEEDpOT_ENKUlSO_SM_OSP_OSQ_E_clESO_SM_S11_S12_
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIyyEENS_22__unordered_map_hasherIyNS_4pairIKyyEENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS6_SA_S8_EENS_9allocatorIS6_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJRS5_EEENSL_IJEEEEEENS4_INS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlSM_SK_OSN_OSO_E_clESM_SK_SZ_S10_
- __ZZNSt3__112__hash_tableIiNS_4hashIiEENS_8equal_toIiEENS_9allocatorIiEEE16__emplace_uniqueB9fqe220100IJRKiEEENS_4pairINS_15__hash_iteratorIPNS_11__hash_nodeIiPvEEEEbEEDpOT_ENKUlSA_SA_E_clESA_SA_
- ___36-[PLDisplayAgent modelDisplayPower:]_block_invoke
- ___40-[PLDisplayAgent logEventForwardALSLux:]_block_invoke
- ___43-[PLDisplayAgent modelDynamicDisplayPower:]_block_invoke
- ___44-[PLDisplayAgent logEventBackwardUserTouch:]_block_invoke
- ___45-[PLDisplayAgent modelDisplayPowerFromIOMFB:]_block_invoke
- ___49-[PLCoalitionAgent logCoalitionObjectDifference:]_block_invoke
- ___49-[PLDisplayAgent logBlueLightDataWithDictionary:]_block_invoke_2
- ___56-[PLDisplayAgent logEventPointDisplayForBlock:isActive:]_block_invoke
- ___65-[PLDisplayAgent extractDataWithEntry:withColName:withDataArray:]_block_invoke
- ___70-[PLDisplayAgent logBrightnessDataWithEntryKey:withColName:withValue:]_block_invoke
- ___block_descriptor_40_e8_32s_e21_v24?0"NSString"816ls32l8
- _dispatch_barrier_async
- _extractDataWithEntry:withColName:withDataArray:.classDebugEnabled
- _extractDataWithEntry:withColName:withDataArray:.defaultOnce
- _handleBrightnessClientNotification:withValue:.classDebugEnabled
- _handleBrightnessClientNotification:withValue:.defaultOnce
- _kPLBatteryAgentStringLowBatteryLog
- _kPLBatteryAgentStringUserType_block_invoke.once
- _kPRearNits_block_invoke_4.classDebugEnabled
- _kPRearNits_block_invoke_4.defaultOnce
- _kPRearNits_block_invoke_5.classDebugEnabled
- _kPRearNits_block_invoke_5.defaultOnce
- _kPRearNits_block_invoke_6.classDebugEnabled
- _kPRearNits_block_invoke_6.defaultOnce
- _kPRearNits_block_invoke_7.classDebugEnabled
- _kPRearNits_block_invoke_7.defaultOnce
- _kPRearNits_block_invoke_8.classDebugEnabled
- _kPRearNits_block_invoke_8.defaultOnce
- _logBlueLightDataWithDictionary:.classDebugEnabled
- _logBlueLightDataWithDictionary:.defaultOnce
- _logBrightnessDataWithEntryKey:withColName:withValue:.classDebugEnabled
- _logBrightnessDataWithEntryKey:withColName:withValue:.defaultOnce
- _logCoalitionObjectDifference:.classDebugEnabled
- _logCoalitionObjectDifference:.defaultOnce
- _logEventBackwardUserTouch:.classDebugEnabled
- _logEventBackwardUserTouch:.defaultOnce
- _logEventForwardALSLux:.classDebugEnabled
- _logEventForwardALSLux:.defaultOnce
- _logEventPointDisplayForBlock:isActive:.classDebugEnabled
- _logEventPointDisplayForBlock:isActive:.defaultOnce
- _modelDisplayPower:.classDebugEnabled
- _modelDisplayPower:.defaultOnce
- _modelDisplayPowerFromIOMFB:.classDebugEnabled
- _modelDisplayPowerFromIOMFB:.defaultOnce
- _modelDynamicDisplayPower:.classDebugEnabled
- _modelDynamicDisplayPower:.defaultOnce
CStrings:
+ "                       SELECT BundleID,                               timestamp AS timestampStart,                               timestamp + timeInterval AS timestampEnd,                               timeInterval,                               ScreenOnTime, ScreenOnPluggedInTime,                               BackgroundTime, BackgroundPluggedInTime,                               BackgroundAudioPlayingTime, BackgroundAudioPlayingTimePluggedIn,                               BackgroundLocationTime, BackgroundLocationPluggedInTime,                               BackgroundLocationAudioTime, BackgroundLocationAudioPluggedInTime                        FROM PLAppTimeService_Aggregate_AppRunTime                        WHERE timestamp >= %f AND timestamp < %f                              AND timeInterval = 3600                        ORDER BY BundleID, timestamp;"
+ "                       SELECT BundleId AS BundleID, LocationDesiredAccuracy,                               CASE WHEN timestamp < %f THEN %f ELSE timestamp END AS timestampStart,                               CASE WHEN (timestampEnd > %f OR timestampEnd IS NULL) THEN %f ELSE timestampEnd END AS timestampEnd,                               (CASE WHEN (timestampEnd > %f OR timestampEnd IS NULL) THEN %f ELSE timestampEnd END) -                               (CASE WHEN timestamp < %f THEN %f ELSE timestamp END) AS duration                        FROM PLLocationAgent_EventForward_ClientStatus                        WHERE Type='Location'                          AND timestampEnd >= %f                          AND timestamp < %f                          AND timestampEnd > timestamp                        ORDER BY BundleID, timestamp;"
+ "\"?([A-Za-z_][A-Za-z0-9_]*)\"?\\s*=\\s*\"?(-?\\d+)\"?\\s*;"
+ "%@_%ld"
+ "%{public}s-%d: col=%@, data=%@, entry=%@"
+ "%{public}s-%d: entryKey=%@, col=%@, value=%@"
+ "%{public}s-%d: entryKey=%@, entry=%@"
+ "%{public}s-%d: harmonyParametersEntry=%@, property=%@, value=%@"
+ "%{public}s-%d: property=%@, value=%@"
+ "-[PLCoalitionAgent logCoalitionObjectDifference]"
+ "AllowPolicyRun"
+ "BatteryConfig parse threw %{public}@: %{public}@ — stack: %{public}@"
+ "BatteryHealth"
+ "BatteryPacks"
+ "BrownoutRiskEngaged"
+ "BrownoutRiskPu_Battery0"
+ "BrownoutRiskPu_Battery1"
+ "BrownoutRiskSysCap_Battery0"
+ "BrownoutRiskSysCap_Battery1"
+ "CACHED_PHY_ACTIVE_DURATION_ELNA_HP"
+ "CACHED_PHY_ACTIVE_DURATION_TOTAL"
+ "CBAdaptationClient notification: type=%lu value=%{public}@"
+ "CBBlueLightClient status notification: enabled=%d mode=%d sunSchedulePermitted=%d"
+ "CBClient activate failed: %{public}@"
+ "CBClient init returned nil"
+ "CBDisplayClient created for Display, displayId=%u"
+ "CBDisplayClient observer registered for %lu keys"
+ "CBDisplayClient registerObserver failed: %{public}@; tearing down modern client to avoid partially-initialized state"
+ "CBDisplayClient: no integrated CADisplay found for Display"
+ "CPMS has keys:"
+ "DBG reArmCallback firing, bluelightStatusEntry=%@"
+ "Display callback - userInfo=%@"
+ "DroopCE"
+ "DroopIS"
+ "Dropping CPMS key %{public}@ — snapshot index beyond _%ld"
+ "ELNAHPActiveDuration"
+ "ELNATotalDuration"
+ "Gauge10s_Battery0"
+ "Gauge10s_Battery1"
+ "Gauge1s_Battery0"
+ "Gauge1s_Battery1"
+ "Have not gotten any new accumulation data, skipping until next update"
+ "IBat_Battery0"
+ "IBat_Battery1"
+ "INSTANT_PHY_ACTIVE_DURATION_ELNA_HP"
+ "INSTANT_PHY_ACTIVE_DURATION_TOTAL"
+ "Keyboard brightness: %{public}s=%{public}s\n"
+ "LaneCE_0"
+ "LaneCE_1"
+ "LaneCE_2"
+ "LaneCE_3"
+ "LaneCE_4"
+ "LaneCE_5"
+ "LaneCE_6"
+ "LaneCE_7"
+ "LastDisengagedCritDroopTS"
+ "LastDisengagedPolicyTS"
+ "LastEngagedCritDroopTS"
+ "LastEngagedPolicyTS"
+ "OperationMode"
+ "OverrideFlags"
+ "PMU100ms_Battery0"
+ "PMU100ms_Battery1"
+ "PMU10ms_Battery0"
+ "PMU10ms_Battery1"
+ "PMU10s_Battery0"
+ "PMU10s_Battery1"
+ "PMU1s_Battery0"
+ "PMU1s_Battery1"
+ "Package: GPU=%.3f CPU_old=%.3f CPU_new=%.3f packageV2=%.3f"
+ "PeakPowerPressureLevel"
+ "PowerLogReport - Real: %f mNits\tVirtual: %f mNits"
+ "Relogging screen state - displayState=%d, containsLockScreen=%d"
+ "RemainingCapacity_Battery0"
+ "RemainingCapacity_Battery1"
+ "SecondaryPICE"
+ "SecondaryPIIS"
+ "ServoCE_0"
+ "ServoCE_1"
+ "ServoCE_2"
+ "ServoCE_3"
+ "ServoCE_4"
+ "ServoCE_5"
+ "ServoCE_6"
+ "SnapshotTimestamp"
+ "SystemCapabilitySource_Battery0"
+ "SystemCapabilitySource_Battery1"
+ "SystemLoadFraction"
+ "SystemStressLevel"
+ "VddMon_Battery0"
+ "VddMon_Battery1"
+ "assetLoadedFromCacheKB"
+ "bolt.slash.fill"
+ "com.apple.powerlog.cb-observer"
+ "grant_"
+ "newDisplayClientForID:%u failed for Display: %{public}@"
+ "req_"
+ "self.lastCoalitionObjectDictionary=%@"
+ "sleep"
+ "txE = %f, rxE = %f, csE = %f, scE = %f, slpE = %f"
+ "unexpected DOD format: %{public}@"
+ "unexpected PresentDOD format: %{public}@"
+ "unexpected Qmax format: %{public}@"
+ "unexpected Wom format: %{public}@"
+ "unknown wRa format: %{public}@"
+ "v16@?0^{?=BBBi{?={?=ii}{?=ii}}QB}8"
+ "v24@?0Q8@16"
+ "v32@?0@\"NSTextCheckingResult\"8Q16^B24"
- "                       SELECT BundleID,                               timestamp AS timestampStart,                               timestamp + timeInterval AS timestampEnd,                               timeInterval,                               ScreenOnTime, ScreenOnPluggedInTime,                               BackgroundTime, BackgroundPluggedInTime,                               BackgroundAudioNowPlayingTime, BackgroundAudioNowPlayingPluggedInTime,                               BackgroundLocationTime, BackgroundLocationPluggedInTime,                               BackgroundLocationAudioTime, BackgroundLocationAudioPluggedInTime                        FROM PLAppTimeService_Aggregate_AppRunTime                        WHERE timestamp >= %f AND timestamp < %f                              AND timeInterval = 3600                        ORDER BY BundleID, timestamp;"
- "                       SELECT BundleID, LocationDesiredAccuracy,                               CASE WHEN timestamp < %f THEN %f ELSE timestamp END AS timestampStart,                               CASE WHEN (timestampEnd > %f OR timestampEnd IS NULL) THEN %f ELSE timestampEnd END AS timestampEnd,                               (CASE WHEN (timestampEnd > %f OR timestampEnd IS NULL) THEN %f ELSE timestampEnd END) -                               (CASE WHEN timestamp < %f THEN %f ELSE timestamp END) AS duration                        FROM PLLocationAgent_EventForward_ClientStatus                        WHERE Type='Location'                          AND timestampEnd >= %f                          AND timestamp < %f                          AND timestampEnd > timestamp                        ORDER BY BundleID, timestamp;"
- "%s-%d: col=%@, data=%@, entry=%@"
- "%s-%d: entryKey=%@, col=%@, value=%@"
- "%s-%d: entryKey=%@, entry=%@"
- "%s-%d: harmonyParametersEntry=%@, property=%@, value=%@"
- "%s-%d: property=%@, value=%@"
- "-[PLCoalitionAgent logCoalitionObjectDifference:]"
- "-[PLDisplayAgent initOperatorDependancies]"
- "-[PLDisplayAgent initOperatorDependancies]_block_invoke"
- "-[PLDisplayAgent initOperatorDependancies]_block_invoke_2"
- "-[PLDisplayAgent init]"
- "-[PLDisplayAgent init]_block_invoke"
- "-[PLDisplayAgent init]_block_invoke_2"
- "-[PLDisplayAgent logEventBackwardUserTouch:]"
- "-[PLDisplayAgent logEventForwardALSLux:]"
- "-[PLDisplayAgent logEventPointDisplayForBlock:isActive:]"
- "-[PLDisplayAgent modelDisplayPower:]"
- "-[PLDisplayAgent modelDisplayPowerFromIOMFB:]"
- "-[PLDisplayAgent modelDynamicDisplayPower:]"
- "BatteryConfig data could not be parsed"
- "BrightnessSystemClient init fail!"
- "CBAdaptationClient init fail! Cannot get color adaptation information!"
- "Have not gotten any new accumulation data, using instantaneous value"
- "InactiveScreenHistory"
- "Keyboard brightness: %s=%s\n"
- "LowBatteryLog"
- "Package: GPU=%.3f CPU_old=%.3f CPU_new=%.3f"
- "assetloadedfromCacheKB"
- "bolt.fill"
- "newCoalitionObjectDictionary=%@\nself.lastCoalitionObjectDictionary=%@"
- "self.displayState=%d, self.lastDisplayLayoutContainsLockScreen=%d"
- "unknown wRa format: %@"
- "v24@?0@\"NSString\"8@16"
```
