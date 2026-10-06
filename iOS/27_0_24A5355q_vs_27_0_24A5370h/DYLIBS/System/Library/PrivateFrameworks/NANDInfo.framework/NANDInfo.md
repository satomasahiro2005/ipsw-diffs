## NANDInfo

> `/System/Library/PrivateFrameworks/NANDInfo.framework/NANDInfo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_intobj` | `0xed90` | `0x10158` | **`+0x13c8`** |
| `__AUTH_CONST.__cfstring` | `0xdce0` | `0xea20` | **`+0xd40`** |
| `__DATA_CONST.__objc_arraydata` | `0xb7e0` | `0xc518` | **`+0xd38`** |
| `__TEXT.__cstring` | `0xaf90` | `0xb9d8` | **`+0xa48`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x7950` | `0x8340` | **`+0x9f0`** |
| `__TEXT.__text` | `0x1bccc` | `0x1c5a4` | **`+0x8d8`** |

### Other Changes

```diff

-835.0.0.0.0
+843.0.0.0.0

-  CStrings:  2137
+  CStrings:  2243
Functions:
~ _buildFTLStatsArrayDictionary : 23044 -> 25588
~ _createAndLogSMagMSPFieldsToCoreAnalyticsForEvent : 2472 -> 2460
~ _copySMagMSPInfoRaw : 3208 -> 3204
~ _ASPParseSnapshotBufferWithInplaceParser : 2160 -> 2056
~ _ASPParseSnapshotBuffer : 1260 -> 1256
~ _ASPFTLParseBufferToDict : 856 -> 852
~ _ASPMSPParseBufferToDict : 1096 -> 1044
~ _ASPMSPParseSMBufferToDict : 1004 -> 1000
~ _createAndLogSMagHistoryFTLFieldsToCoreAnalyticsForEvent : 2028 -> 2024
~ _createAndLogSMagFTLFieldsToCoreAnalyticsForEvent : 1700 -> 1720
~ _findNandExporter : 388 -> 412
~ _NandInfoExtractToCA_runAllSteps : 7208 -> 7200
~ _CopyWhitelistedNANDMSPInfo : 664 -> 660
~ _gatherASPOtherData : 452 -> 448
~ _gatherNANDHealthInfo : 1260 -> 1248
~ _LogStorageUIDatatoCA : 560 -> 556
~ _CopySMagMSPInfo : 396 -> 392
~ _isASPFeatureSupported : 216 -> 212
~ -[NANDInfo_GeomErrorPayloadManager initWithPayloadBuf:bufSize:prevNumErrors:] : 404 -> 408
~ -[NANDInfo_GeomErrorPayloadManager populateOtherStats:] : 440 -> 436
~ -[NANDInfo_GeomErrorPayloadManager iteratePerPageDictsForMaxPagesWithStatus:iteratorCallBack:] : 1452 -> 1428
~ -[NANDInfo_GeomErrorPayloadManager dictionaryRepresentation] : 748 -> 744
~ _GetXNUSystemInfo : 1168 -> 1160
~ _GetXNUStatsForCA : 3824 -> 3748
~ _ReorderAppSpaceDictionary : 4840 -> 4856
~ _hexStringToByte : 172 -> 188
~ _hexStringToInt32 : 168 -> 164
~ _populatePerDeviceStatsDictionary : 464 -> 448
~ _gatherMassStorageStats : 584 -> 596
~ _printDeviceStats : 308 -> 304
~ _printDeviceStatsArray : 292 -> 288
CStrings:
+ "SleepAllVotes"
+ "SleepForcedShutdowns"
+ "SleepMaximumNoVoteSeconds"
+ "SleepNoHisto"
+ "SleepNoVotes"
+ "SleepTimeOuts"
+ "SleepWillNotSleepsNotUs"
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
+ "activeThrottleSamples"
+ "autoReadXacts"
+ "autoReads"
+ "autoreadPrefetches"
+ "cbdrRefreshType"
+ "gcSlowInlineWritesGCMust"
+ "gcSlowInlineWritesVCCAutoHint"
+ "gcSlowInlineWritesVCCNonRec"
+ "gcSlowInlineWritesVCCRec"
+ "idleStackActivationsHighDone"
+ "idleStackActivationsHighLtdDone"
+ "idleStackActivationsLowDone"
+ "idleStackActivationsLowNoSUIDone"
+ "idleStackActivationsMedDone"
+ "idleStackActivationsMedLtdDone"
+ "idleStackActivationsUrgencyHigh"
+ "idleStackActivationsUrgencyHighLtd"
+ "idleStackActivationsUrgencyLow"
+ "idleStackActivationsUrgencyLowNoSUI"
+ "idleStackActivationsUrgencyMed"
+ "idleStackActivationsUrgencyMedLtd"
+ "idleStackActiveAvgTemp"
+ "idleStackActiveDuration"
+ "idleStackActiveDurationHistogram"
+ "idleStackActiveMaxTemp"
+ "idleStackContinuesPingDefer"
+ "idleStackDriveFullnessAtCompletion"
+ "idleStackFullyPurgedBands"
+ "idleStackHostActivationsDropped"
+ "idleStackHostActiveStartDefer"
+ "idleStackHostWritesBetweenFull"
+ "idleStackLowAfterMedHighHisto"
+ "idleStackNonSrcPurgeableBands"
+ "idleStackPartialPurgedBands"
+ "idleStackPingResetWhileDeferred"
+ "idleStackPurgeableBudgetExhausted"
+ "idleStackSelfActivationBDRCollisions"
+ "idleStackSelfActiveStartDefer"
+ "idleStackSquareBudgetExhausted"
+ "idleStackSquareExitedHighUrgency"
+ "idleStackSrcPurgeableBands"
+ "idleStackStartTempAtActivation"
+ "idleStackSyncedTimeSelfActivations"
+ "idleStackThrottleStart"
+ "idleStackTimeToHighUrgency"
+ "idleStackTimeToMedUrgency"
+ "idleStackValidityLeftOverAlignFast"
+ "idleStackValidityLeftOverAlignRegular"
+ "idleStackValidityLeftOverPurgeable"
+ "iologQosEntries"
+ "istkCrossTempDeferred"
+ "istkPollingIntervals"
+ "istkPollingQuery"
+ "istkResumeHighToLow"
+ "istkResumeHighToMed"
+ "istkResumeLowToHigh"
+ "istkResumeLowToMed"
+ "istkResumeMedToHigh"
+ "istkResumeMedToLow"
+ "istkResumeNoChange"
+ "istkSelfActSyncedWallDiff"
+ "istkWLNoDestBand"
+ "purgeableAgeHistogramSectors"
+ "purgeableFromGc1DataSectors"
+ "purgeableFromGc2DataSectors"
+ "purgeableFromGc3DataSectors"
+ "purgeableFromHostDataSectors"
+ "vccAutoGCNonRecCount"
+ "vccAutoGCRecCount"
+ "vccAutoSizeHintCount"
+ "vccGCWritesAutoHint"
+ "vccGCWritesNonRec"
+ "vccGCWritesRec"
+ "vccMaxSessionMBytes"
+ "vccMaxSessionTime"
+ "vccMaxVccMBytes"
+ "vccNonProResBW1s"
+ "vccNonProResBW5s"
+ "vccQualGCSessions"
+ "vccQualLowEBSessions"
+ "vccQualModel95pChoke"
+ "vccQualModel95pNoChoke"
+ "vccQualModel98pChoke"
+ "vccQualSessions"
+ "vccQualThrottledHostHigh"
+ "vccQualThrottledHostLow"
+ "vccSessionsCount"
+ "vccTotalSessionMBytes"
+ "vccTotalSessionTime"
```
