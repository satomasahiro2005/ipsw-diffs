## SymptomEvaluator

> `/System/Library/PrivateFrameworks/Symptoms.framework/Frameworks/SymptomEvaluator.framework/SymptomEvaluator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29c618` | `0x29d04c` | **`+0xa34`** |
| `__TEXT.__oslogstring` | `0x470a5` | `0x47375` | **`+0x2d0`** |
| `__TEXT.__objc_methlist` | `0x18950` | `0x18ae0` | **`+0x190`** |
| `__AUTH_CONST.__objc_const` | `0x410a8` | `0x411c8` | **`+0x120`** |
| `__DATA_CONST.__objc_selrefs` | `0xd328` | `0xd420` | **`+0xf8`** |
| `__TEXT.__cstring` | `0x27254` | `0x272c4` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x5224` | `0x527c` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x13a8` | `0x13f8` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x1f060` | `0x1f0a0` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x31d0` | `0x3210` | **`+0x40`** |
| `__DATA.__bss` | `0xff0` | `0x1030` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x6ec8` | `0x6f00` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x79b0` | `0x79d8` | **`+0x28`** |
| `__AUTH_CONST.__objc_intobj` | `0x9f0` | `0xa08` | **`+0x18`** |
| `__DATA.__data` | `0x1f18` | `0x1f28` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xfc8` | `0xfd0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x8a0` | `0x8a8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x312c` | `0x3128` | **`-0x4`** |

### Other Changes

```diff

-2357.0.0.0.2
+2374.0.0.0.0

-  Functions: 12135
-  Symbols:   19857
-  CStrings:  12128
+  Functions: 12178
+  Symbols:   19917
+  CStrings:  12142
Symbols:
+ +[CellFallbackHandler appPolicyDenialsScore]
+ +[NetworkAnalyticsEngine getCurrentCellHighThroughputStateOnQueue:reply:]
+ +[TrackedFlow _currentForegroundAppKeys]
+ +[TrackedFlow _currentICEnabled]
+ +[TrackedFlow censusCountsByOwnerForTesting]
+ +[TrackedFlow decrementCensusForFlow:withOwner:]
+ +[TrackedFlow flowCensus]
+ +[TrackedFlow incrementCensusForFlow:withOwner:]
+ +[TrackedFlow resetCensusForTesting]
+ +[TrackedFlow seedCensusFromActiveFlows]
+ +[TrackedFlow setCensusQueueForTesting:]
+ +[TrackedFlow setForegroundAppsOverrideForTesting:]
+ +[TrackedFlow setICEnabledOverrideForTesting:]
+ +[TrackedFlow setRnfAllowedOwners:]
+ -[CellFallbackHandler _appsPolicyCacheForTesting]
+ -[CensusOwnerCounts addFlowWithFlags:]
+ -[CensusOwnerCounts isEmpty]
+ -[CensusOwnerCounts nativeTCPOrQUIC]
+ -[CensusOwnerCounts notOurStack]
+ -[CensusOwnerCounts quicMigratable]
+ -[CensusOwnerCounts quic]
+ -[CensusOwnerCounts rawUDP]
+ -[CensusOwnerCounts removeFlowWithFlags:]
+ -[CensusOwnerCounts setNativeTCPOrQUIC:]
+ -[CensusOwnerCounts setNotOurStack:]
+ -[CensusOwnerCounts setQuic:]
+ -[CensusOwnerCounts setQuicMigratable:]
+ -[CensusOwnerCounts setRawUDP:]
+ -[CensusOwnerCounts setSocketsRawUDP:]
+ -[CensusOwnerCounts setSocketsTCP:]
+ -[CensusOwnerCounts setTotal:]
+ -[CensusOwnerCounts socketsRawUDP]
+ -[CensusOwnerCounts socketsTCP]
+ -[CensusOwnerCounts total]
+ -[FlowAnalyticsEngine _applyCellHighThroughputState:]
+ -[FlowAnalyticsEngine cellThroughputAdviserForUnitTests]
+ -[NetworkAnalyticsEngine _currentCellHighThroughputState]
+ -[NetworkStateRelay bbhState]
+ -[NetworkStateRelay setBbhState:]
+ -[NoBackhaulHandler observeWifiFrictionFastTrack]
+ GCC_except_table121
+ GCC_except_table137
+ GCC_except_table139
+ GCC_except_table161
+ GCC_except_table165
+ GCC_except_table171
+ GCC_except_table175
+ GCC_except_table216
+ GCC_except_table233
+ GCC_except_table239
+ GCC_except_table253
+ GCC_except_table254
+ GCC_except_table259
+ GCC_except_table260
+ GCC_except_table261
+ GCC_except_table264
+ GCC_except_table269
+ GCC_except_table271
+ GCC_except_table286
+ GCC_except_table288
+ GCC_except_table289
+ GCC_except_table293
+ GCC_except_table310
+ GCC_except_table311
+ GCC_except_table319
+ GCC_except_table352
+ GCC_except_table353
+ GCC_except_table367
+ GCC_except_table394
+ GCC_except_table411
+ GCC_except_table417
+ GCC_except_table422
+ GCC_except_table77
+ GCC_except_table81
+ _MVRangeCheck
+ _OBJC_CLASS_$_CensusOwnerCounts
+ _OBJC_IVAR_$_CellFallbackHandler.dynamicAllowList
+ _OBJC_IVAR_$_CellFallbackHandler.fallbackClosedLoop
+ _OBJC_IVAR_$_CensusOwnerCounts._nativeTCPOrQUIC
+ _OBJC_IVAR_$_CensusOwnerCounts._notOurStack
+ _OBJC_IVAR_$_CensusOwnerCounts._quic
+ _OBJC_IVAR_$_CensusOwnerCounts._quicMigratable
+ _OBJC_IVAR_$_CensusOwnerCounts._rawUDP
+ _OBJC_IVAR_$_CensusOwnerCounts._socketsRawUDP
+ _OBJC_IVAR_$_CensusOwnerCounts._socketsTCP
+ _OBJC_IVAR_$_CensusOwnerCounts._total
+ _OBJC_IVAR_$_NetworkStateRelay._bbhState
+ _OBJC_IVAR_$_NoBackhaulHandler._observeWifiFrictionFastTrack
+ _OBJC_METACLASS_$_CensusOwnerCounts
+ __OBJC_$_INSTANCE_METHODS_CensusOwnerCounts
+ __OBJC_$_INSTANCE_VARIABLES_CensusOwnerCounts
+ __OBJC_$_PROP_LIST_CensusOwnerCounts
+ __OBJC_CLASS_RO_$_CensusOwnerCounts
+ __OBJC_METACLASS_RO_$_CensusOwnerCounts
+ __ZNKSt3__119__map_value_compareIKPKcNS_4pairIS3_S3_EEN12_GLOBAL__N_112CmpByContentEEclB9fqe220106ERKS5_SA_
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__127__tree_balance_after_insertB9fqe220106IPNS_16__tree_node_baseIPvEEEEvT_S5_
+ __ZNSt3__16__treeINS_12__value_typeIKPKcS4_EENS_19__map_value_compareIS4_NS_4pairIS4_S4_EEN12_GLOBAL__N_112CmpByContentEEENS_9allocatorIS8_EEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeIS5_PvEE
+ ___25+[TrackedFlow flowCensus]_block_invoke
+ ___25-[AppStateMonitor enable]_block_invoke
+ ___29-[NetworkStateRelay bbhState]_block_invoke
+ ___33-[NetworkStateRelay setBbhState:]_block_invoke
+ ___35+[TrackedFlow setRnfAllowedOwners:]_block_invoke
+ ___36+[TrackedFlow resetCensusForTesting]_block_invoke
+ ___40+[TrackedFlow seedCensusFromActiveFlows]_block_invoke
+ ___44+[TrackedFlow censusCountsByOwnerForTesting]_block_invoke
+ ___44+[TrackedFlow censusCountsByOwnerForTesting]_block_invoke_2
+ ___46+[TrackedFlow setICEnabledOverrideForTesting:]_block_invoke
+ ___51+[TrackedFlow setForegroundAppsOverrideForTesting:]_block_invoke
+ ___53-[FlowAnalyticsEngine _applyCellHighThroughputState:]_block_invoke
+ ___73+[NetworkAnalyticsEngine getCurrentCellHighThroughputStateOnQueue:reply:]_block_invoke
+ ___block_descriptor_40_e8_32s_e18_v16?0"NSNumber"8ls32l8
+ ___block_descriptor_40_e8_32s_e44_v32?0"NSString"8"CensusOwnerCounts"16^B24ls32l8
+ _cellHighThroughputStateInitialized
+ _censusFlowCountsByOwner
+ _enable.pred
+ _foregroundAppsOverrideForTesting
+ _gCensusQueueOverride
+ _icEnabledOverrideForTesting
+ _kFallbackClosedLoopRNF
+ _kSymptomManagedEventKeyCensusNoForegroundApp
+ _rnfAllowedOwners
- +[FlowAnalyticsEngine flowCensus]
- +[FlowAnalyticsEngine idleFlowCounter]
- +[FlowAnalyticsEngine updateRnfCensusEligibilitySplit:]
- -[CellFallbackHandler _flowCensus]
- -[FlowAnalyticsEngine _decrementRnfCensusCountersForFlow:]
- -[FlowAnalyticsEngine _flowCensusCountsByOwner]
- -[FlowAnalyticsEngine _flowCensus]
- -[FlowAnalyticsEngine _incrementRnfCensusCountersForFlow:]
- -[FlowAnalyticsEngine _updateRnfCensusEligibilitySplit:]
- GCC_except_table124
- GCC_except_table157
- GCC_except_table164
- GCC_except_table169
- GCC_except_table173
- GCC_except_table180
- GCC_except_table215
- GCC_except_table224
- GCC_except_table248
- GCC_except_table252
- GCC_except_table256
- GCC_except_table257
- GCC_except_table268
- GCC_except_table270
- GCC_except_table282
- GCC_except_table285
- GCC_except_table290
- GCC_except_table292
- GCC_except_table296
- GCC_except_table329
- GCC_except_table349
- GCC_except_table350
- GCC_except_table351
- GCC_except_table385
- GCC_except_table391
- GCC_except_table408
- GCC_except_table419
- GCC_except_table44
- GCC_except_table53
- GCC_except_table80
- GCC_except_table85
- GCC_except_table93
- _OBJC_IVAR_$_CellFallbackHandler.dynamicDenylist
- _OBJC_IVAR_$_CellFallbackHandler.powerRelay
- _OBJC_IVAR_$_FlowAnalyticsEngine.censusFlowCountsByOwner
- _OBJC_IVAR_$_FlowAnalyticsEngine.censusFlowsIdle
- _OBJC_IVAR_$_FlowAnalyticsEngine.censusFlowsNotOurStack
- _OBJC_IVAR_$_FlowAnalyticsEngine.censusFlowsQuic
- _OBJC_IVAR_$_FlowAnalyticsEngine.censusFlowsQuicMigratable
- _OBJC_IVAR_$_FlowAnalyticsEngine.censusFlowsRawUDP
- _OBJC_IVAR_$_FlowAnalyticsEngine.censusFlowsRnfEligible
- _OBJC_IVAR_$_FlowAnalyticsEngine.censusFlowsRnfIneligible
- _OBJC_IVAR_$_FlowAnalyticsEngine.censusFlowsSocketsRawUDP
- _OBJC_IVAR_$_FlowAnalyticsEngine.censusFlowsSocketsTCP
- _OBJC_IVAR_$_FlowAnalyticsEngine.censusTotalFlows
- __ZNKSt3__119__map_value_compareIKPKcNS_4pairIS3_S3_EEN12_GLOBAL__N_112CmpByContentEEclB9fqe220100ERKS5_SA_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__127__tree_balance_after_insertB9fqe220100IPNS_16__tree_node_baseIPvEEEEvT_S5_
- __ZNSt3__16__treeINS_12__value_typeIKPKcS4_EENS_19__map_value_compareIS4_NS_4pairIS4_S4_EEN12_GLOBAL__N_112CmpByContentEEENS_9allocatorIS8_EEE14__tree_deleterclB9fqe220100EPNS_11__tree_nodeIS5_PvEE
- ___34-[FlowAnalyticsEngine _flowCensus]_block_invoke
- ___47-[FlowAnalyticsEngine _flowCensusCountsByOwner]_block_invoke
- ___56-[FlowAnalyticsEngine _updateRnfCensusEligibilitySplit:]_block_invoke
- ___block_descriptor_40_e8_32s_e18_B16?0"NSString"8ls32l8
CStrings:
+ "  SymptomAnalytics performQueryOnEntity: entity dictionary creation returned nil for description (%@) and managed object (%@) upon insertion"
+ "%s (active%s/primary%s/constrained%s/expensive%s/rssifull%s/rssithresh%s/txthresh%s/arp%s/dns%s/i-dns%s/i-stuck%s/rssiexempt:%d/rnfPoll:%d/rnfFrict%s/rnfDStall%s/rnfFback%s/apsd%s/1ppservconnfric%s/tcphints:%ld/lqm:%ld/assess:%ld/advisory:%d/pwrDL:%ld/pwrUL:%ld/ic:%ld%s/txRate:%.1f/rxRate:%.1f/wfrict:%lu/wfft%s/bbh:%d)"
+ "2\x81!\xd1"
+ "CFSM dynamic deny/allow list returning error %@ in consider alternate update"
+ "CFSM dynamic denylist short [external/async] (value/reason): %@/%@"
+ "CFSM dynamic denylist short [internal/sync] (value/reason): %@/%@"
+ "CTShim: HighThroughput cached (slot=%ld state=%d)"
+ "FAE: CellThroughputAdvisoryCapable observed (isOn=%{BOOL}d)"
+ "FAE: NAE high throughput state received (state=%@)"
+ "RNF census allowed-owners snapshot updated: %lu entries: %@"
+ "SymptomAnalytics performQueryOnEntity: entity dictionary creation returned nil for description (%@) and managed object (%@) upon addition"
+ "SymptomAnalytics performQueryOnEntity: entity dictionary creation returned nil for description (%@) and managed object (%@) upon merge"
+ "bbhState"
+ "dsTshold: %d, dsTimeSecs: %d, dsRefreshSecs: %d, probesFailureFactor: %.2f, packetsFrictionFactor %.2f, progressTimeSecs: %d, historyProgressTimeSecs: %d, maxPreferResidencyMsecs: %llu, rnfToCellRatio: %.2f, fallbackHeavyRatio: %.2f, usePolledScore: %d, rnfPolledScoreWindowSize: %lu, useOpportunistic: %d, usePrefer: %d, fallbackClosedLoop: %d"
+ "eLQM: Dropped high throughput notification (%@), queue not ready"
+ "eLQM: NAE about to process high throughput state (state=%@)"
+ "eLQM: NAE high throughput state polled (state=%@)"
+ "eLQM: NAE priority queue created"
+ "eLQM: NAE registered with CTShim (queueReady=%{BOOL}d)"
+ "fallbackClosedLoop"
+ "no-foreground-app"
+ "v16@?0@\"NSNumber\"8"
+ "v32@?0@\"NSString\"8@\"CensusOwnerCounts\"16^B24"
+ "wifiFriction fast track: last %lu eligible flows all fell back to cell"
- "%s (active%s/primary%s/constrained%s/expensive%s/rssifull%s/rssithresh%s/txthresh%s/arp%s/dns%s/i-dns%s/i-stuck%s/rssiexempt:%d/rnfPoll:%d/rnfFrict%s/rnfDStall%s/rnfFback%s/apsd%s/1ppservconnfric%s/tcphints:%ld/lqm:%ld/assess:%ld/advisory:%d/pwrDL:%ld/pwrUL:%ld/ic:%ld%s/txRate:%.1f/rxRate:%.1f/wfrict:%lu/wfft%s)"
- "2q!\xd1"
- "B16@?0@\"NSString\"8"
- "CFSM dynamic denylist returning error %@ in consider alternate update"
- "CFSM dynamic denylist short returning (value/reason): %@/%@"
- "CFSM: always_on_rnf suspended, LPM"
- "RNF census eligibility split updated: %lu eligible, %lu ineligible (from %lu unique owners)"
- "SymptomAnalytics performQueryOnEntity: entity dictionary creation returned nil for description (%@) and managed object (%@)"
- "dsTshold: %d, dsTimeSecs: %d, dsRefreshSecs: %d, probesFailureFactor: %.2f, packetsFrictionFactor %.2f, progressTimeSecs: %d, historyProgressTimeSecs: %d, maxPreferResidencyMsecs: %llu, rnfToCellRatio: %.2f, fallbackHeavyRatio: %.2f, usePolledScore: %d, rnfPolledScoreWindowSize: %lu, useOpportunistic: %d, usePrefer: %d"
- "wifiFriction fast track: last N eligible flows all fell back to cell"
```
