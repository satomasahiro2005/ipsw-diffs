## NANDInfo

> `/System/Library/PrivateFrameworks/NANDInfo.framework/NANDInfo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_intobj` | `0x10398` | `0x11b50` | **`+0x17b8`** |
| `__AUTH_CONST.__cfstring` | `0xeba0` | `0xfba0` | **`+0x1000`** |
| `__DATA_CONST.__objc_arraydata` | `0xc698` | `0xd660` | **`+0xfc8`** |
| `__TEXT.__cstring` | `0xbb17` | `0xc74c` | **`+0xc35`** |
| `__TEXT.__text` | `0x1c6ac` | `0x1d298` | **`+0xbec`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x8460` | `0x9030` | **`+0xbd0`** |

### Other Changes

```diff

-847.0.0.0.0
+849.0.5.0.0

-  CStrings:  2255
+  CStrings:  2383
Functions:
~ _buildFTLStatsArrayDictionary : 25876 -> 28492
~ _buildMSPStatsArrayDictionary : 7056 -> 7440
~ _createAndLogSMagFTLFieldsToCoreAnalyticsForEvent : 1720 -> 1728
~ _GetSystemInfo : 648 -> 692
CStrings:
+ "AlignedFastReadDisturbs"
+ "AlignedRegularReadDisturbs"
+ "bandCyclesHisto"
+ "bandCyclesHistoStart"
+ "blockMassScanOnRaidConversion"
+ "cbdrStatusHP"
+ "cbdrStatusMP"
+ "com.apple.massStorage.NANDInfo.SM.FTLStatArray_6"
+ "controller_vs_nand_temp_diff_"
+ "dspExceptionParameter170"
+ "dspExceptionParameter171"
+ "ess_segments_"
+ "fairPurgeCompleteCount"
+ "fairPurgeStartCount"
+ "fairPurgeValidityDeltaSectors"
+ "fairPurgeValidityIncreasedCount"
+ "gcDestPurgeable"
+ "gcFastActiveReasons"
+ "gcRoundTime"
+ "gcSlowActiveReasons"
+ "gcSlowInlineT0ReadLatencyHisto"
+ "gcSlowIsT0ReadLatencyHisto"
+ "gcSlowT0ReadLatencyHisto"
+ "hostBandsSinceSquare"
+ "hotBandsClass"
+ "idleStackAvgValidityAtSlowGC"
+ "idleStackBadListLBAs"
+ "idleStackCurrentUrgency"
+ "idleStackFlavorLimited"
+ "idleStackFlowVCurveCDPEnd"
+ "idleStackFlowVCurveCDPStart"
+ "idleStackFullnessAtSlowGC"
+ "idleStackHighWritesDailyHisto"
+ "idleStackNandWritesUrgencyHigh"
+ "idleStackNandWritesUrgencyHighLtd"
+ "idleStackNandWritesUrgencyLow"
+ "idleStackNandWritesUrgencyMed"
+ "idleStackNandWritesUrgencyMedLtd"
+ "idleStackPhaseDurationAlignFast"
+ "idleStackPhaseDurationAlignRegular"
+ "idleStackPhaseDurationCbdr"
+ "idleStackPhaseDurationPurgeable"
+ "idleStackPhaseDurationSquareGC1"
+ "idleStackPhaseDurationSquareGC2"
+ "idleStackPhaseDurationSquareGC3"
+ "idleStackPhaseDurationWearlevel"
+ "idleStackPingResetPhase"
+ "idleStackSectorsToHigh"
+ "idleStackSectorsToSlowGC"
+ "idleStackSlowGCDailyHisto"
+ "idleStackSlowGCSrcRankHisto"
+ "idleStackTimeToSlowGC"
+ "idleStackValidityCurveAtIdleStackStart"
+ "idleStackWearlevelBandErasesDelta"
+ "initialReadStage14_"
+ "isExternalBoot"
+ "istkAvailSpaceSectors"
+ "istkDutyCycleSelfDeferred"
+ "istkHighSnapshotDeferred"
+ "istkHostWritesToHighUrgency"
+ "istkHostWritesToMedUrgency"
+ "istkHoursSinceAlignFast"
+ "istkHoursSinceAlignRegular"
+ "istkHoursSinceSquare"
+ "istkHoursSinceWearLevel"
+ "istkLastAlignFastHr"
+ "istkLastAlignRegularHr"
+ "istkLastCompletedPrio"
+ "istkLastDoneCalTimeHr"
+ "istkLastDoneHr"
+ "istkLastDoneHrAnyFlvr"
+ "istkLastFullDoneHostWrites"
+ "istkLastLowDoneHr"
+ "istkLastSquareHr"
+ "istkLastWearLevelHr"
+ "istkLowNoSUIExpired"
+ "istkOvpSectors"
+ "istkSavedFakeUrg"
+ "istkSecsSinceLastSidebarGen"
+ "istkValidLbasDeltaToHighUrgency"
+ "istkValidLbasDeltaToMedUrgency"
+ "istkWLUrgencyNoDestBand"
+ "lastISHighPingHr"
+ "lastISLowNoSUIPingHr"
+ "lastISLowPingHr"
+ "lastISMedPingHr"
+ "lastISPollingHr"
+ "lastISQueriedTask"
+ "massRefreshThrottleDisable"
+ "massRefreshThrottleEvict"
+ "massRefreshThrottleMassScan"
+ "massScanDeferStart"
+ "massScanDeferStop"
+ "massScanLastDebugInfo"
+ "massScanRequestWhileET"
+ "massScanStatus"
+ "massStorage_NANDInfo_SM_FTLStatArrays_6"
+ "migrationAutoPingCount"
+ "migrationAutoPingMB"
+ "migrationAutoPingStarts"
+ "nandWritesInSLCOnlyMode"
+ "numIdleStackDays"
+ "page_eviction_duration_"
+ "page_fault_load_duration_"
+ "page_swap_distance_"
+ "parallel_slip_hist_"
+ "pgHappyBandReleaseusingDeltaPmx"
+ "progTempDeltaHisto"
+ "purgeableBandCyclesHisto"
+ "purgeableBandCyclesHistoStart"
+ "purgeableVcurve"
+ "purgeableVcurveAtIdleStackSquareUpEnd"
+ "purgeableVcurveAtSlowGC"
+ "qosEventHighLatency"
+ "qosEventSmallReadLatency"
+ "shutdownGCTimeoutQLC"
+ "shutdownGCTimeoutTLC"
+ "shutdownSpbxEvictQLC"
+ "shutdownSpbxEvictTLC"
+ "slowGcMustReasons"
+ "vcurveAtSlowGC"
+ "vref_search_ofw_opt_vref_hist_"
+ "vref_search_pts_wr_vref"
+ "vref_search_pts_wr_win_size_at_opt"
+ "vref_search_rd_retries"
+ "vref_search_wr_retries"
+ "vref_search_wr_win_size_at_opt_hist_"
+ "vref_search_wr_win_size_at_vgh_hist_"
```
