## PowerlogLiteOperators

> `/System/Library/PrivateFrameworks/PowerlogLiteOperators.framework/PowerlogLiteOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x73b40` | `0x74840` | **`+0xd00`** |
| `__TEXT.__cstring` | `0x5d2b7` | `0x5dd2a` | **`+0xa73`** |
| `__TEXT.__oslogstring` | `0x14d7b` | `0x154ca` | **`+0x74f`** |
| `__AUTH_CONST.__objc_const` | `0x36aa0` | `0x36e68` | **`+0x3c8`** |
| `__TEXT.__text` | `0x4cb7c0` | `0x4cb598` | **`-0x228`** |
| `__TEXT.__objc_methlist` | `0x2e0c4` | `0x2e2b4` | **`+0x1f0`** |
| `__DATA_CONST.__objc_arraydata` | `0x16450` | `0x16620` | **`+0x1d0`** |
| `__DATA_CONST.__objc_selrefs` | `0x143e0` | `0x14588` | **`+0x1a8`** |
| `__DATA.__data` | `0x1068` | `0x1128` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x2c20` | `0x2cdc` | **`+0xbc`** |
| `__DATA_DIRTY.__bss` | `0x44f0` | `0x4438` | **`-0xb8`** |
| `__DATA_CONST.__const` | `0x9358` | `0x93f8` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x8158` | `0x81d8` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x2bc0` | `0x2c10` | **`+0x50`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x2f58` | `0x2fa0` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x29b8` | `0x29f8` | **`+0x40`** |
| `__AUTH_CONST.__objc_dictobj` | `0x50a0` | `0x5078` | **`-0x28`** |
| `__TEXT.__const` | `0x2c88` | `0x2cb0` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x1e7c` | `0x1ea0` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x1ac8` | `0x1ae0` | **`+0x18`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x1320` | `0x1310` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x90` | `0xa0` | **`+0x10`** |
| `__DATA_DIRTY.__objc_ivar` | `0x12e8` | `0x12f4` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0xa08` | `0xa10` | **`+0x8`** |

### Other Changes

```diff

-3468.0.0.502.1
+3486.0.21.502.1

-  Functions: 19311
-  Symbols:   25166
-  CStrings:  19066
+  Functions: 19329
+  Symbols:   25233
+  CStrings:  19235
Symbols:
+ +[PLEnergyIssuesService(AWDLTimeoutHandler) shouldPopUpForPowerExceptionWithFatalCount:withNonFatalCount:withMitigationsEnabled:withIssueType:]
+ +[PLIOReportAgent entryEventBackwardDefinitionMultitouchTouch]
+ -[PLBBAgent logSDMAtInit]
+ -[PLBatteryAgent batteryHealthDictForPack:inIOPSDict:]
+ -[PLBatteryAgent getBatteryHealthServiceFlagsForPack:]
+ -[PLBatteryAgent getBatteryHealthServiceStateForPack:]
+ -[PLBatteryAgent getBatteryMaximumCapacityPercentForPack:]
+ -[PLBatteryAgent parsedCPMSKeysFromLowBatteryLog]
+ -[PLBluetoothAgent lastBTENPower]
+ -[PLBluetoothAgent lastBTITPower]
+ -[PLBluetoothAgent lastBTPower]
+ -[PLBluetoothAgent setLastBTENPower:]
+ -[PLBluetoothAgent setLastBTITPower:]
+ -[PLBluetoothAgent setLastBTPower:]
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
+ _OBJC_CLASS_$_NSScanner
+ _OBJC_CLASS_$__PLDisplayCBPropertyObserver
+ _OBJC_IVAR_$_PLBluetoothAgent._lastBTENPower
+ _OBJC_IVAR_$_PLBluetoothAgent._lastBTITPower
+ _OBJC_IVAR_$_PLBluetoothAgent._lastBTPower
+ _OBJC_IVAR_$_PLCoalitionDataObject._coalResourceUsage
+ _OBJC_IVAR_$_PLCoalitionDataObject._hasPrevSample
+ _OBJC_IVAR_$_PLCoalitionDataObject._prevCoalResourceUsage
+ _OBJC_IVAR_$__PLDisplayCBPropertyObserver._agent
+ _OBJC_IVAR_$__PLDisplayCBPropertyObserver._handle
+ _OBJC_IVAR_$__PLDisplayCBPropertyObserver._notifyQueue
+ _OBJC_IVAR_$__PLDisplayCBPropertyObserver._properties
+ _OBJC_METACLASS_$__PLDisplayCBPropertyObserver
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
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIiEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16__treeINS_4pairIyyEEN12PLProcessCPU9compare_tENS_9allocatorIS2_EEE12__find_equalB9fqe220106IS2_EENS1_IPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERSD_EERKT_
+ __ZNSt3__16__treeINS_4pairIyyEEN12PLProcessCPU9compare_tENS_9allocatorIS2_EEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeIS2_PvEE
+ __ZNSt3__16vectorIiNS_9allocatorIiEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIiN12PLProcessCPU11inode_cpu_tEEENS_22__unordered_map_hasherIiNS_4pairIKiS3_EENS_4hashIiEENS_8equal_toIiEEEENS_21__unordered_map_equalIiS8_SC_SA_EENS_9allocatorIS8_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS7_EEENSN_IJEEEEEENS6_INS_15__hash_iteratorIPNS_11__hash_nodeIS4_PvEEEEbEEDpOT_ENKUlSO_SM_OSP_OSQ_E_clESO_SM_S11_S12_
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIyN12PLProcessCPU12inode_data_tEEENS_22__unordered_map_hasherIyNS_4pairIKyS3_EENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS8_SC_SA_EENS_9allocatorIS8_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS7_EEENSN_IJEEEEEENS6_INS_15__hash_iteratorIPNS_11__hash_nodeIS4_PvEEEEbEEDpOT_ENKUlSO_SM_OSP_OSQ_E_clESO_SM_S11_S12_
+ ___25-[PLBBAgent logSDMAtInit]_block_invoke
+ ___25-[PLBBAgent logSDMAtInit]_block_invoke_2
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
+ _kPLIOReportAgentEventBackwardNameMultitouchTouch
+ _objc_release_x2
- +[PLEnergyIssuesService(AWDLTimeoutHandler) shouldPopUpForPowerExceptionWithFatalCount:withNonFatalCount:withMitigationsEnabled:]
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
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIiEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16__treeINS_4pairIyyEEN12PLProcessCPU9compare_tENS_9allocatorIS2_EEE12__find_equalB9fqe220100IS2_EENS1_IPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERSD_EERKT_
- __ZNSt3__16__treeINS_4pairIyyEEN12PLProcessCPU9compare_tENS_9allocatorIS2_EEE14__tree_deleterclB9fqe220100EPNS_11__tree_nodeIS2_PvEE
- __ZNSt3__16vectorIiNS_9allocatorIiEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIiN12PLProcessCPU11inode_cpu_tEEENS_22__unordered_map_hasherIiNS_4pairIKiS3_EENS_4hashIiEENS_8equal_toIiEEEENS_21__unordered_map_equalIiS8_SC_SA_EENS_9allocatorIS8_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJRS7_EEENSN_IJEEEEEENS6_INS_15__hash_iteratorIPNS_11__hash_nodeIS4_PvEEEEbEEDpOT_ENKUlSO_SM_OSP_OSQ_E_clESO_SM_S11_S12_
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIyN12PLProcessCPU12inode_data_tEEENS_22__unordered_map_hasherIyNS_4pairIKyS3_EENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS8_SC_SA_EENS_9allocatorIS8_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJRS7_EEENSN_IJEEEEEENS6_INS_15__hash_iteratorIPNS_11__hash_nodeIS4_PvEEEEbEEDpOT_ENKUlSO_SM_OSP_OSQ_E_clESO_SM_S11_S12_
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
- _dispatch_barrier_async
- _kPLBatteryAgentStringLowBatteryLog
CStrings:
+ "\"?([A-Za-z_][A-Za-z0-9_]*)\"?\\s*=\\s*\"?(-?\\d+)\"?\\s*;"
+ "%@_%ld"
+ "%{public}s-%d: col=%@, data=%@, entry=%@"
+ "%{public}s-%d: entryKey=%@, col=%@, value=%@"
+ "%{public}s-%d: entryKey=%@, entry=%@"
+ "%{public}s-%d: harmonyParametersEntry=%@, property=%@, value=%@"
+ "%{public}s-%d: property=%@, value=%@"
+ "-[PLBBAgent logSDMAtInit]"
+ "-[PLBBAgent logSDMAtInit]_block_invoke"
+ "-[PLCoalitionAgent logCoalitionObjectDifference]"
+ "A2DPNAKPercentage"
+ "A2DPReTxPercentage"
+ "A2DPTxBFPercentage"
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
+ "Could not determine CoreTelephony Subscription Info for SDM init. Error: %@"
+ "DBG reArmCallback firing, bluelightStatusEntry=%@"
+ "Display callback - userInfo=%@"
+ "DroopCE"
+ "DroopIS"
+ "Dropping CPMS key %{public}@ — snapshot index beyond _%ld"
+ "ELNAHPActiveDuration"
+ "ELNATotalDuration"
+ "Failed to query SDM state at init. Error: %@"
+ "Gauge10s_Battery0"
+ "Gauge10s_Battery1"
+ "Gauge1s_Battery0"
+ "Gauge1s_Battery1"
+ "HFPNAKPercentage"
+ "HFPReTxPercentage"
+ "HFPTxBFPercentage"
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
+ "MainCoreRxRxPercentage"
+ "Multitouch,touch"
+ "Multitouchtouch"
+ "NAKPercentage"
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
+ "PeakPowerPressureLevel"
+ "PercentageTxBF"
+ "PowerLogReport - Real: %f mNits\tVirtual: %f mNits"
+ "ReTxPercentage"
+ "Relogging screen state - displayState=%d, containsLockScreen=%d"
+ "RemainingCapacity_Battery0"
+ "RemainingCapacity_Battery1"
+ "ScanCoreLeScanOffloadingPercentage"
+ "ScanCoreLeScanPercentage"
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
+ "TPB_maxPower"
+ "TPB_minPower"
+ "TPB_perExtLoopPerLevel_100ms"
+ "TPB_perExtLoopPerLevel_count"
+ "TPB_perExtLoopPerLevel_throttled"
+ "TPB_perIntLoopPerLevel_100ms"
+ "TPB_perIntLoopPerLevel_count"
+ "TPB_perIntLoopPerLevel_throttled"
+ "TPB_unblockGcThrottlingBP"
+ "TPB_unblockGcThrottlingStarve"
+ "VddMon_Battery0"
+ "VddMon_Battery1"
+ "[BT_DEBUG PLBluetoothAgent:%d] Creating SBC-triggered BT heartbeat at %@ with power %f"
+ "[BT_DEBUG PLBluetoothAgent:%d] Creating SBC-triggered BTEN heartbeat at %@ with power %f"
+ "[BT_DEBUG PLBluetoothAgent:%d] Creating SBC-triggered BTIT heartbeat at %@ with power %f"
+ "[BT_DEBUG PLBluetoothAgent:%d] Skipping SBC BT heartbeat - real flush occurred since last SBC"
+ "[BT_DEBUG PLBluetoothAgent:%d] Skipping SBC BTEN heartbeat - real flush occurred since last SBC"
+ "[BT_DEBUG PLBluetoothAgent:%d] Skipping SBC BTIT heartbeat - real flush occurred since last SBC"
+ "assetLoadedFromCacheKB"
+ "coefficientTxPower = %f, coefficientTxPower = %f, coefficientOtherPower = %f, coefficientSleepPower = %f"
+ "com.apple.powerlog.cb-observer"
+ "gcRoundTime"
+ "gcSlowInlineWritesVCCAutoHint"
+ "gcSlowInlineWritesVCCNonRec"
+ "gcSlowInlineWritesVCCRec"
+ "grant_"
+ "idleStackActiveStatus"
+ "idleStackBadListLBAs"
+ "idleStackHistory"
+ "idleStackPingResetPhase"
+ "massRefreshThrottleDisable"
+ "massRefreshThrottleEvict"
+ "massRefreshThrottleMassScan"
+ "massScanRequestWhileET"
+ "newDisplayClientForID:%u failed for Display: %{public}@"
+ "numOfThrottlingEntriesPerReadLevel"
+ "numOfThrottlingEntriesPerWriteLevel"
+ "req_"
+ "self.lastCoalitionObjectDictionary=%@"
+ "shutdownGCTimeoutQLC"
+ "shutdownGCTimeoutTLC"
+ "shutdownSpbxEvictQLC"
+ "shutdownSpbxEvictTLC"
+ "timeOfThrottlingPerLevel"
+ "timeOfThrottlingPerReadLevel"
+ "timeOfThrottlingPerWriteLevel"
+ "touch.timing.F0.active-active-frames"
+ "touch.timing.F0.active-clean-frames"
+ "touch.timing.F0.active-dirty-frames"
+ "touch.timing.F0.andromeda-active-frames"
+ "touch.timing.F0.andromeda-clean-frames"
+ "touch.timing.F0.andromeda-dirty-frames"
+ "touch.timing.F0.ttw-active-frames"
+ "touch.timing.F0.ttw-clean-frames"
+ "touch.timing.F0.ttw-dirty-frames"
+ "touch.timing.F1.active-active-frames"
+ "touch.timing.F1.active-clean-frames"
+ "touch.timing.F1.active-dirty-frames"
+ "touch.timing.F1.andromeda-active-frames"
+ "touch.timing.F1.andromeda-clean-frames"
+ "touch.timing.F1.andromeda-dirty-frames"
+ "touch.timing.F1.ttw-active-frames"
+ "touch.timing.F1.ttw-clean-frames"
+ "touch.timing.F1.ttw-dirty-frames"
+ "touch.timing.F2.active-active-frames"
+ "touch.timing.F2.active-clean-frames"
+ "touch.timing.F2.active-dirty-frames"
+ "touch.timing.F2.andromeda-active-frames"
+ "touch.timing.F2.andromeda-clean-frames"
+ "touch.timing.F2.andromeda-dirty-frames"
+ "touch.timing.F2.ttw-active-frames"
+ "touch.timing.F2.ttw-clean-frames"
+ "touch.timing.F2.ttw-dirty-frames"
+ "touch.timing.F3.active-active-frames"
+ "touch.timing.F3.active-clean-frames"
+ "touch.timing.F3.active-dirty-frames"
+ "touch.timing.F3.andromeda-active-frames"
+ "touch.timing.F3.andromeda-clean-frames"
+ "touch.timing.F3.andromeda-dirty-frames"
+ "touch.timing.F3.ttw-active-frames"
+ "touch.timing.F3.ttw-clean-frames"
+ "touch.timing.F3.ttw-dirty-frames"
+ "touch.timing.F4.active-active-frames"
+ "touch.timing.F4.active-clean-frames"
+ "touch.timing.F4.active-dirty-frames"
+ "touch.timing.F4.andromeda-active-frames"
+ "touch.timing.F4.andromeda-clean-frames"
+ "touch.timing.F4.andromeda-dirty-frames"
+ "touch.timing.F4.ttw-active-frames"
+ "touch.timing.F4.ttw-clean-frames"
+ "touch.timing.F4.ttw-dirty-frames"
+ "txE = %f, rxE = %f, csE = %f, scE = %f, slpE = %f"
+ "unexpected DOD format: %{public}@"
+ "unexpected PresentDOD format: %{public}@"
+ "unexpected Qmax format: %{public}@"
+ "unexpected Wom format: %{public}@"
+ "unknown wRa format: %{public}@"
+ "v16@?0^{?=BBBi{?={?=ii}{?=ii}}QB}8"
+ "v24@?0Q8@16"
+ "v32@?0@\"NSTextCheckingResult\"8Q16^B24"
+ "vccGCWritesAutoHint"
+ "vccGCWritesNonRec"
+ "vccGCWritesRec"
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
- "InactiveScreenHistory"
- "Keyboard brightness: %s=%s\n"
- "LowBatteryLog"
- "[BT_DEBUG PLBluetoothAgent:%d] Creating SBC-triggered BT 0-energy event at %@"
- "[BT_DEBUG PLBluetoothAgent:%d] Creating SBC-triggered BTEN 0-energy event at %@"
- "[BT_DEBUG PLBluetoothAgent:%d] Creating SBC-triggered BTIT 0-energy event at %@"
- "[BT_DEBUG PLBluetoothAgent:%d] Skipping SBC BT 0-energy - real flush occurred since last SBC"
- "[BT_DEBUG PLBluetoothAgent:%d] Skipping SBC BTEN 0-energy - real flush occurred since last SBC"
- "[BT_DEBUG PLBluetoothAgent:%d] Skipping SBC BTIT 0-energy - real flush occurred since last SBC"
- "assetloadedfromCacheKB"
- "coefficientTxPower = %f, coefficientTxPower = %f, coefficientOtherPower = %f"
- "newCoalitionObjectDictionary=%@\nself.lastCoalitionObjectDictionary=%@"
- "ricMPRVFail"
- "ricSPRVFail"
- "self.displayState=%d, self.lastDisplayLayoutContainsLockScreen=%d"
- "unknown wRa format: %@"
```
