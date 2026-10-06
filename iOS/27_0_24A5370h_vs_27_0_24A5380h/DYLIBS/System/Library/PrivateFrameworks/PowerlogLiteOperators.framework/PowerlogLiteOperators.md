## PowerlogLiteOperators

> `/System/Library/PrivateFrameworks/PowerlogLiteOperators.framework/PowerlogLiteOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4cb598` | `0x4cea50` | **`+0x34b8`** |
| `__TEXT.__cstring` | `0x5dd2a` | `0x5e5c6` | **`+0x89c`** |
| `__AUTH_CONST.__cfstring` | `0x74840` | `0x74e00` | **`+0x5c0`** |
| `__AUTH.__objc_data` | `0x2c10` | `0x28f0` | **`-0x320`** |
| `__DATA_DIRTY.__objc_data` | `0x3b48` | `0x3e68` | **`+0x320`** |
| `__TEXT.__oslogstring` | `0x154ca` | `0x155b9` | **`+0xef`** |
| `__AUTH_CONST.__objc_const` | `0x36e68` | `0x36f28` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x2e2b4` | `0x2e334` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x14588` | `0x145e8` | **`+0x60`** |
| `__DATA_CONST.__objc_arraydata` | `0x16620` | `0x16670` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x1688` | `0x16d8` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x81d8` | `0x8210` | **`+0x38`** |
| `__DATA.__data` | `0x1128` | `0x10f8` | **`-0x30`** |
| `__DATA_DIRTY.__data` | `0x6f8` | `0x728` | **`+0x30`** |
| `__AUTH_CONST.__objc_dictobj` | `0x5078` | `0x50a0` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x29f8` | `0x2a18` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0xbc` | `0xd0` | **`+0x14`** |
| `__DATA_DIRTY.__objc_ivar` | `0x12f4` | `0x1304` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x93f8` | `0x9400` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1ae0` | `0x1ae8` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x4438` | `0x4440` | **`+0x8`** |

### Other Changes

```diff

-3486.0.21.502.1
+3486.0.46.502.1

-  Functions: 19329
-  Symbols:   25233
-  CStrings:  19235
+  Functions: 19348
+  Symbols:   25250
+  CStrings:  19338
Symbols:
+ +[PLBatteryAgent entryEventBackwardDefinitionPowerDistribution]
+ +[PLDisplayAgent hasAppleARMBacklightPublisher]
+ -[PLAudioAgent activeMediaPlaybackAssertions]
+ -[PLAudioAgent handleMediaPlaybackAssertionEntry:]
+ -[PLAudioAgent mediaPlaybackAssertionListener]
+ -[PLAudioAgent setActiveMediaPlaybackAssertions:]
+ -[PLAudioAgent setMediaPlaybackAssertionListener:]
+ -[PLBatteryAgent lastPowerDistribution]
+ -[PLBatteryAgent logInputPowerDistribution:]
+ -[PLBatteryAgent logInputPowerDistributionToCA:]
+ -[PLBatteryAgent setLastPowerDistribution:]
+ -[PLXPCAgent clientDroppedEventsXPCListener]
+ -[PLXPCAgent logEventBackwardClientDroppedEvents:]
+ -[PLXPCAgent setClientDroppedEventsXPCListener:]
+ GCC_except_table134
+ GCC_except_table138
+ GCC_except_table154
+ GCC_except_table157
+ GCC_except_table174
+ GCC_except_table186
+ GCC_except_table191
+ GCC_except_table247
+ GCC_except_table257
+ GCC_except_table259
+ GCC_except_table268
+ GCC_except_table275
+ GCC_except_table282
+ GCC_except_table321
+ GCC_except_table324
+ GCC_except_table328
+ GCC_except_table433
+ ___40-[PLAudioAgent initOperatorDependancies]_block_invoke_2
+ ___47+[PLDisplayAgent hasAppleARMBacklightPublisher]_block_invoke
+ ___48-[PLBatteryAgent logInputPowerDistributionToCA:]_block_invoke
+ ___block_descriptor_120_e8_32s40s_e19_"NSDictionary"8?0ls32l8s40l8
+ _kPLBatteryAgentEventBackwardNamePowerDistribution
- -[PLDebugService fireSignificantBatteryChangeNotification]
- -[PLDebugService testArchive]
- GCC_except_table109
- GCC_except_table133
- GCC_except_table137
- GCC_except_table156
- GCC_except_table185
- GCC_except_table190
- GCC_except_table244
- GCC_except_table253
- GCC_except_table258
- GCC_except_table266
- GCC_except_table272
- GCC_except_table278
- GCC_except_table320
- GCC_except_table323
- GCC_except_table327
- GCC_except_table431
- ___block_descriptor_108_e8_32s40s_e19_"NSDictionary"8?0ls32l8s40l8
CStrings:
+ "ANE0"
+ "ANE1"
+ "AlignedFastReadDisturbs"
+ "AlignedRegularReadDisturbs"
+ "ChargerAccumEfficiencyCount"
+ "ChargerAccumulatedEfficiency"
+ "ChargerCount"
+ "ChargerEfficiency"
+ "ChargerHwIlimBackoffReason"
+ "ChargerIBUS"
+ "ChargerPower"
+ "ChargerVBUS"
+ "ClientDroppedEvents"
+ "ClientDroppedEvents payload: %@"
+ "ECPU_CORE0_NRG"
+ "ECPU_CORE0_SRM_NRG"
+ "ECPU_CORE1_NRG"
+ "ECPU_CORE1_SRM_NRG"
+ "ECPU_CORE2_NRG"
+ "ECPU_CORE2_SRM_NRG"
+ "ECPU_CORE3_NRG"
+ "ECPU_CORE3_SRM_NRG"
+ "ECPU_CPM_NRG"
+ "ECPU_CPM_SRM_NRG"
+ "ECPU_NRG"
+ "IPDChargingAllowed"
+ "IPDInputCurrent"
+ "IPDInputPower"
+ "IPDInputVoltage"
+ "IPDRatioOverride"
+ "IPDWattageOverride"
+ "InstantBootAdapterReady"
+ "InstantBootCount"
+ "InstantBootFailure"
+ "InstantBootGGReady"
+ "OPDDualChargerState"
+ "PCPU0_CORE0_NRG"
+ "PCPU0_CORE0_SRM_NRG"
+ "PCPU0_CORE1_NRG"
+ "PCPU0_CORE1_SRM_NRG"
+ "PCPU0_CPM_NRG"
+ "PCPU0_CPM_SRM_NRG"
+ "PCPU_NRG"
+ "PLPowerAssertionAgent_EventForward_Assertion"
+ "PowerDistribution"
+ "Pushing InputPowerDistribution to CA: %@"
+ "SystemCapability100ms_Battery0"
+ "SystemCapability100ms_Battery1"
+ "SystemCapability1sec_Battery0"
+ "SystemCapability1sec_Battery1"
+ "SystemCapabilityInsta_Battery0"
+ "SystemCapabilityInsta_Battery1"
+ "XPCMetrics::ClientDroppedEvents"
+ "[OnDeviceACAMSBC] Skipping offset %@: payload entry is %{public}@, expected NSDictionary"
+ "[OnDeviceACAMSBC] Skipping offset %@: timeSinceLastSBC is %{public}@, expected NSNumber/NSString"
+ "bandCyclesHisto"
+ "bandCyclesHistoStart"
+ "cbdrRefreshGradesHP"
+ "cbdrRefreshGradesMP"
+ "cbdrStatusHP"
+ "cbdrStatusMP"
+ "com.apple.power.battery.InputPowerDistribution"
+ "fairPurgeCompleteCount"
+ "fairPurgeStartCount"
+ "fairPurgeValidityDeltaSectors"
+ "fairPurgeValidityIncreasedCount"
+ "gcSlowInlineT0ReadLatencyHisto"
+ "gcSlowInlineT0Reads"
+ "gcSlowIsT0ReadLatencyHisto"
+ "gcSlowIsT0Reads"
+ "gcSlowT0ReadLatencyHisto"
+ "gcSlowT0Reads"
+ "hotBandsClass"
+ "idleStackAvgValidityAtSlowGC"
+ "idleStackCurrentUrgency"
+ "idleStackFullnessAtSlowGC"
+ "idleStackHighWritesDailyHisto"
+ "idleStackPhaseDurationAlignFast"
+ "idleStackPhaseDurationAlignRegular"
+ "idleStackPhaseDurationCbdr"
+ "idleStackPhaseDurationPurgeable"
+ "idleStackPhaseDurationSquareGC1"
+ "idleStackPhaseDurationSquareGC2"
+ "idleStackPhaseDurationSquareGC3"
+ "idleStackPhaseDurationWearlevel"
+ "idleStackSectorsToHigh"
+ "idleStackSectorsToSlowGC"
+ "idleStackSlowGCDailyHisto"
+ "idleStackSlowGCSrcRankHisto"
+ "idleStackTimeToSlowGC"
+ "idleStackValidityCurveAtIdleStackStart"
+ "istkHostWritesToHighUrgency"
+ "istkHostWritesToMedUrgency"
+ "istkHoursSinceAlignFast"
+ "istkHoursSinceAlignRegular"
+ "istkHoursSinceSquare"
+ "istkHoursSinceWearLevel"
+ "istkLastAlignFastHr"
+ "istkLastAlignRegularHr"
+ "istkLastFullDoneHostWrites"
+ "istkLastSquareHr"
+ "istkLastWearLevelHr"
+ "istkSecsSinceLastSidebarGen"
+ "istkValidLbasDeltaToHighUrgency"
+ "istkValidLbasDeltaToMedUrgency"
+ "massScanLastDebugInfo"
+ "massScanStatus"
+ "numIdleStackDays"
+ "progTempDeltaHisto"
+ "purgeableBandCyclesHisto"
+ "purgeableBandCyclesHistoStart"
+ "purgeableVcurve"
+ "purgeableVcurveAtIdleStackSquareUpEnd"
+ "purgeableVcurveAtSlowGC"
+ "qosEventHighLatency"
+ "qosEventSmallReadLatency"
+ "sidebarLastValidWallTime"
+ "slowGcMustReasons"
+ "totalReadAmpAtBoot"
+ "unalignedPageReads"
+ "vcurveAtSlowGC"
- "-[PLDebugService testArchive]"
- "HERE: Line: %d"
- "Manually firing SBC"
- "PLDebugService::testArchive"
- "cbdrAborts"
- "cbdrInvalidGrade"
- "cbdrNeedToRefresh"
- "cbdrNoNeedToRefresh"
- "cbdrNotEnoughReads"
- "cbdrRefreshGrades"
- "com.apple.powerlogd.archive"
- "com.apple.powerlogd.fireSBC"
- "idleStackNandWritesPerRoundHigh"
- "idleStackNandWritesPerRoundLow"
- "idleStackNandWritesPerRoundMed"
- "idleStackNandWritesRoundHighIdx"
- "idleStackNandWritesRoundLowIdx"
- "idleStackNandWritesRoundMedIdx"
```
