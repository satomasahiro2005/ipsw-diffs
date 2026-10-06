## MobileAssetDaemon

> `/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/MobileAssetDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x261480` | `0x26284c` | **`+0x13cc`** |
| `__AUTH_CONST.__objc_const` | `0x18980` | `0x18e40` | **`+0x4c0`** |
| `__TEXT.__cstring` | `0x3ef36` | `0x3f3f6` | **`+0x4c0`** |
| `__TEXT.__oslogstring` | `0x5de59` | `0x5e2fd` | **`+0x4a4`** |
| `__AUTH_CONST.__cfstring` | `0x32520` | `0x329a0` | **`+0x480`** |
| `__TEXT.__unwind_info` | `0x45c0` | `0x4888` | **`+0x2c8`** |
| `__TEXT.__objc_methlist` | `0x12a1c` | `0x12c84` | **`+0x268`** |
| `__DATA_CONST.__objc_selrefs` | `0xadd0` | `0xaf28` | **`+0x158`** |
| `__AUTH.__objc_data` | `0x8a0` | `0x940` | **`+0xa0`** |
| `__DATA.__objc_ivar` | `0x17b8` | `0x1804` | **`+0x4c`** |
| `__TEXT.__gcc_except_tab` | `0xdbac` | `0xdbf8` | **`+0x4c`** |
| `__DATA_CONST.__const` | `0x31f0` | `0x31c8` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0x11f0` | `0x1210` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x1020` | `0x1040` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1058` | `0x1070` | **`+0x18`** |
| `__DATA.__bss` | `0x588` | `0x598` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x478` | `0x488` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x350` | `0x358` | **`+0x8`** |

### Other Changes

```diff

-2215.0.0.502.1
+2215.0.4.0.0

-  Functions: 7226
-  Symbols:   11326
-  CStrings:  10915
+  Functions: 7278
+  Symbols:   11420
+  CStrings:  10965
Symbols:
+ +[DownloadManager _throttleCapFromPreference:orDefault:]
+ +[MADAutoAssetControlManager stagerResumed:stagedFromBuildVersion:withSetLookupResults:performingNewOSPromotion:requiringLoadPriorToUse:]
+ +[MADSessionTaskThrottle _nanosecondsBetween:and:]
+ -[DownloadManager cancelDaemonTask:]
+ -[DownloadManager getKnoxURLOverrideForAssetType:]
+ -[DownloadManager inProcessThrottle]
+ -[DownloadManager pallasThrottle]
+ -[DownloadManager resumeTask:onThrottle:]
+ -[DownloadManager setInProcessThrottle:]
+ -[DownloadManager setPallasThrottle:]
+ -[DownloadManager setSplunkThrottle:]
+ -[DownloadManager splunkThrottle]
+ -[MADAnalyticsManager recordThrottleSnapshot:maxKqwlCount:]
+ -[MADAutoAssetControlManager newLatestToVendForEachPSUSFreshness]
+ -[MADAutoAssetControlManagerParam initWithParamType:withSafeSummary:withEventOSTransaction:withScheduledJobs:withClientID:withClientRequestMessage:withClientProgressProxy:withClientReplyCompletion:withResponseMessage:withResponseError:withDownloadsInFlight:withDownloadOptions:withAutoAssetJobID:withAutoAssetCatalog:withLockForUseError:withFinishedError:withDownloadProgress:withJobCurrentStatus:withAutoAssetSelector:withAutoAssetUUID:withSetOfAutoAssetSelectors:withPushNotifications:withSetDescriptor:withAutoAssetDescriptors:withSetPolicy:withAssetTargetOSVersion:withAssetTargetBuildVersion:withAssetTargetTrainName:withAssetTargetRestoreVersion:withStagedToDownloaded:withStagedLookupResults:withStagedFromBuildVersion:withNewOSPromotion:withDownloadingDescriptor:withBaseForPatchDescriptor:withBaseForStagingDescriptors:withSchedulerInvolved:withPotentialNetworkFailure:withRequiringLoadPriorToUse:withClientDomainName:withAssetSetIdentifier:withSetConfiguration:withSetAtomicInstance:withSetJobInformation:withTriggeredSets:]
+ -[MADAutoAssetControlManagerParam initWithPromoted:stagedFromBuildVersion:withSetLookupResults:withNewOSPromotion:withRequiringLoadPriorToUse:]
+ -[MADAutoAssetControlManagerParam setStagedFromBuildVersion:]
+ -[MADAutoAssetControlManagerParam stagedFromBuildVersion]
+ -[MADAutoAssetStager _clearAllTrackingOfActiveOperations:alsoPerformingPurgeAll:removingDetermined:resettingPreviousOTASituation:]
+ -[MADAutoAssetStager _persistRemoveAll:message:removingDetermined:resettingPreviousOTASituation:loggingConfig:]
+ -[MADAutoAssetStager action_RemoveAvailableForStaging:error:]
+ -[MADAutoAssetStager action_ReplyNoCandidatesRemoveAvailForStaging:error:]
+ -[MADAutoSetConfiguration isLatestToVendFreshForProductVersion:forBuildVersion:]
+ -[MADSessionTaskThrottle .cxx_destruct]
+ -[MADSessionTaskThrottle cancelPendingForTask:]
+ -[MADSessionTaskThrottle cancelledPendingTaskIdentifiers]
+ -[MADSessionTaskThrottle cancelledWhilePendingCount]
+ -[MADSessionTaskThrottle cumulativeWaitMs]
+ -[MADSessionTaskThrottle currentDepth]
+ -[MADSessionTaskThrottle deferralCount]
+ -[MADSessionTaskThrottle enqueueCount]
+ -[MADSessionTaskThrottle enqueueSubmit:forTask:onCancel:]
+ -[MADSessionTaskThrottle inFlightCount]
+ -[MADSessionTaskThrottle initWithName:maxConcurrent:]
+ -[MADSessionTaskThrottle maxConcurrent]
+ -[MADSessionTaskThrottle maxInFlightObserved]
+ -[MADSessionTaskThrottle maxPendingObserved]
+ -[MADSessionTaskThrottle maxWaitMs]
+ -[MADSessionTaskThrottle name]
+ -[MADSessionTaskThrottle pendingOrdered]
+ -[MADSessionTaskThrottle setCancelledPendingTaskIdentifiers:]
+ -[MADSessionTaskThrottle setCancelledWhilePendingCount:]
+ -[MADSessionTaskThrottle setCumulativeWaitMs:]
+ -[MADSessionTaskThrottle setDeferralCount:]
+ -[MADSessionTaskThrottle setEnqueueCount:]
+ -[MADSessionTaskThrottle setInFlightCount:]
+ -[MADSessionTaskThrottle setMaxConcurrent:]
+ -[MADSessionTaskThrottle setMaxInFlightObserved:]
+ -[MADSessionTaskThrottle setMaxPendingObserved:]
+ -[MADSessionTaskThrottle setMaxWaitMs:]
+ -[MADSessionTaskThrottle setName:]
+ -[MADSessionTaskThrottle setPendingOrdered:]
+ -[MADSessionTaskThrottle slotDidCloseForTask:]
+ -[MADSessionTaskThrottle snapshotAndReset]
+ -[MobileAssetHealthReport _emitThrottleSnapshotTelemetry]
+ -[_MADThrottlePendingEntry .cxx_destruct]
+ -[_MADThrottlePendingEntry enqueuedAtMachTicks]
+ -[_MADThrottlePendingEntry onCancel]
+ -[_MADThrottlePendingEntry setEnqueuedAtMachTicks:]
+ -[_MADThrottlePendingEntry setOnCancel:]
+ -[_MADThrottlePendingEntry setSubmit:]
+ -[_MADThrottlePendingEntry setTaskIdentifier:]
+ -[_MADThrottlePendingEntry submit]
+ -[_MADThrottlePendingEntry taskIdentifier]
+ GCC_except_table405
+ GCC_except_table408
+ GCC_except_table438
+ GCC_except_table449
+ GCC_except_table526
+ GCC_except_table528
+ GCC_except_table586
+ GCC_except_table624
+ GCC_except_table626
+ GCC_except_table632
+ GCC_except_table647
+ GCC_except_table676
+ GCC_except_table812
+ GCC_except_table815
+ _MADDrainWorkloopPeakAndReset
+ _MADFormatWorkloopStats
+ _OBJC_CLASS_$_MADSessionTaskThrottle
+ _OBJC_CLASS_$__MADThrottlePendingEntry
+ _OBJC_IVAR_$_DownloadManager._inProcessThrottle
+ _OBJC_IVAR_$_DownloadManager._pallasThrottle
+ _OBJC_IVAR_$_DownloadManager._splunkThrottle
+ _OBJC_IVAR_$_MADAutoAssetControlManagerParam._stagedFromBuildVersion
+ _OBJC_IVAR_$_MADSessionTaskThrottle._cancelledPendingTaskIdentifiers
+ _OBJC_IVAR_$_MADSessionTaskThrottle._cancelledWhilePendingCount
+ _OBJC_IVAR_$_MADSessionTaskThrottle._cumulativeWaitMs
+ _OBJC_IVAR_$_MADSessionTaskThrottle._deferralCount
+ _OBJC_IVAR_$_MADSessionTaskThrottle._enqueueCount
+ _OBJC_IVAR_$_MADSessionTaskThrottle._inFlightCount
+ _OBJC_IVAR_$_MADSessionTaskThrottle._maxConcurrent
+ _OBJC_IVAR_$_MADSessionTaskThrottle._maxInFlightObserved
+ _OBJC_IVAR_$_MADSessionTaskThrottle._maxPendingObserved
+ _OBJC_IVAR_$_MADSessionTaskThrottle._maxWaitMs
+ _OBJC_IVAR_$_MADSessionTaskThrottle._name
+ _OBJC_IVAR_$_MADSessionTaskThrottle._pendingOrdered
+ _OBJC_IVAR_$_MADSessionTaskThrottle._stateLock
+ _OBJC_IVAR_$__MADThrottlePendingEntry._enqueuedAtMachTicks
+ _OBJC_IVAR_$__MADThrottlePendingEntry._onCancel
+ _OBJC_IVAR_$__MADThrottlePendingEntry._submit
+ _OBJC_IVAR_$__MADThrottlePendingEntry._taskIdentifier
+ _OBJC_METACLASS_$_MADSessionTaskThrottle
+ _OBJC_METACLASS_$__MADThrottlePendingEntry
+ _OUTLINED_FUNCTION_47
+ _OUTLINED_FUNCTION_72
+ _OUTLINED_FUNCTION_74
+ _OUTLINED_FUNCTION_91
+ __OBJC_$_CLASS_METHODS_MADSessionTaskThrottle
+ __OBJC_$_INSTANCE_METHODS_MADSessionTaskThrottle
+ __OBJC_$_INSTANCE_METHODS__MADThrottlePendingEntry
+ __OBJC_$_INSTANCE_VARIABLES_MADSessionTaskThrottle
+ __OBJC_$_INSTANCE_VARIABLES__MADThrottlePendingEntry
+ __OBJC_$_PROP_LIST_MADSessionTaskThrottle
+ __OBJC_$_PROP_LIST__MADThrottlePendingEntry
+ __OBJC_CLASS_RO_$_MADSessionTaskThrottle
+ __OBJC_CLASS_RO_$__MADThrottlePendingEntry
+ __OBJC_METACLASS_RO_$_MADSessionTaskThrottle
+ __OBJC_METACLASS_RO_$__MADThrottlePendingEntry
+ ___41-[DownloadManager resumeTask:onThrottle:]_block_invoke
+ ___50+[MADSessionTaskThrottle _nanosecondsBetween:and:]_block_invoke
+ ___block_descriptor_184_e8_32s40s48s56s64s72s80s88s96s104s112s120s128s136s144bs152r160r168r_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24lr152l8s32l8s40l8s48l8r160l8s56l8s64l8s72l8s80l8s88l8s144l8s96l8s104l8s112l8s120l8s128l8s136l8r168l8
+ ___block_descriptor_76_e8_32s40s48s56s64bs_e17_v16?0"NSArray"8ls32l8s40l8s48l8s56l8s64l8
+ __nanosecondsBetween:and:.sOnce
+ __nanosecondsBetween:and:.sTimebase
+ _kMobileAssetPreferencesInProcessSessionMaxConcurrent
+ _kMobileAssetPreferencesPallasSessionMaxConcurrent
+ _kMobileAssetPreferencesSplunkSessionMaxConcurrent
+ _mach_timebase_info
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _proc_pidinfo
+ _sMaxKqwlCount
- +[MADAutoAssetControlManager stagerResumed:withSetLookupResults:performingNewOSPromotion:requiringLoadPriorToUse:]
- -[DownloadManager backgroundDiscretionaryConfiguration]
- -[DownloadManager backgroundSession]
- -[DownloadManager getCurrentInflightDownloads:]
- -[DownloadManager setBackgroundDiscretionaryConfiguration:]
- -[DownloadManager setBackgroundSession:]
- -[DownloadManager setCachedMetaDataForAssetType:]
- -[DownloadManager setDelegate:]
- -[DownloadManager setInProcessConfig:]
- -[DownloadManager setKeyManager:]
- -[DownloadManager setPallasDelegate:]
- -[DownloadManager setSplunkDelegate:]
- -[MADAutoAssetControlManagerParam initWithParamType:withSafeSummary:withEventOSTransaction:withScheduledJobs:withClientID:withClientRequestMessage:withClientProgressProxy:withClientReplyCompletion:withResponseMessage:withResponseError:withDownloadsInFlight:withDownloadOptions:withAutoAssetJobID:withAutoAssetCatalog:withLockForUseError:withFinishedError:withDownloadProgress:withJobCurrentStatus:withAutoAssetSelector:withAutoAssetUUID:withSetOfAutoAssetSelectors:withPushNotifications:withSetDescriptor:withAutoAssetDescriptors:withSetPolicy:withAssetTargetOSVersion:withAssetTargetBuildVersion:withAssetTargetTrainName:withAssetTargetRestoreVersion:withStagedToDownloaded:withStagedLookupResults:withNewOSPromotion:withDownloadingDescriptor:withBaseForPatchDescriptor:withBaseForStagingDescriptors:withSchedulerInvolved:withPotentialNetworkFailure:withRequiringLoadPriorToUse:withClientDomainName:withAssetSetIdentifier:withSetConfiguration:withSetAtomicInstance:withSetJobInformation:withTriggeredSets:]
- -[MADAutoAssetControlManagerParam initWithPromoted:withSetLookupResults:withNewOSPromotion:withRequiringLoadPriorToUse:]
- -[MADAutoAssetStager _clearAllTrackingOfActiveOperations:alsoPerformingPurgeAll:removingDetermined:]
- -[MADAutoAssetStager _persistRemoveAll:message:removingDetermined:loggingConfig:]
- GCC_except_table404
- GCC_except_table407
- GCC_except_table437
- GCC_except_table443
- GCC_except_table525
- GCC_except_table527
- GCC_except_table584
- GCC_except_table623
- GCC_except_table625
- GCC_except_table631
- GCC_except_table646
- GCC_except_table675
- GCC_except_table808
- GCC_except_table814
- _OBJC_IVAR_$_DownloadManager._backgroundDiscretionaryConfiguration
- _OBJC_IVAR_$_DownloadManager._backgroundSession
- _OUTLINED_FUNCTION_48
- _OUTLINED_FUNCTION_73
- _OUTLINED_FUNCTION_75
- _OUTLINED_FUNCTION_92
- ___47-[DownloadManager getCurrentInflightDownloads:]_block_invoke
- ___block_descriptor_176_e8_32s40s48s56s64s72s80s88s96s104s112s120s128s136s144bs152r160r_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24lr152l8s32l8s40l8s48l8r160l8s56l8s64l8s72l8s80l8s88l8s144l8s96l8s104l8s112l8s120l8s128l8s136l8
- ___block_descriptor_48_e8_32s40bs_e17_v16?0"NSArray"8ls40l8s32l8
- ___block_descriptor_68_e8_32s40s48s56bs_e17_v16?0"NSArray"8ls32l8s40l8s48l8s56l8
CStrings:
+ "%{public}@\n[AUTO-STAGER] {LoadDecideNewOSPromote} have target lookup results [when no staged content] (and now running target OS) | %{public}@ | %{public}@"
+ "3.1.2"
+ "4.1.2"
+ "ADD_AI_PROMOD_STARTUP_FRESH"
+ "Assertion failed: (session == _downloadManager.inProcessSession), DownloaderSessionDelegate received completion from unexpected session"
+ "Assertion failed: (session == _downloadManager.splunkSession), SplunkSessionDelegate received completion from unexpected session"
+ "AverageWaitMs"
+ "BUG IN MobileAsset: Assertion failed: (session == _downloadManager.inProcessSession), DownloaderSessionDelegate received completion from unexpected session"
+ "BUG IN MobileAsset: Assertion failed: (session == _downloadManager.splunkSession), SplunkSessionDelegate received completion from unexpected session"
+ "CancelledWhilePendingCount"
+ "DeferralCount"
+ "DownloadManager:getCurrentDaemonManagedInFlightDownloads"
+ "EnqueueCount"
+ "FROM_STAGED_PROMOTED_FRESHENED"
+ "KnoxURLOverride"
+ "Loaded built-in MobileAssetDaemon_Framework Jun 16 2026 00:19:07"
+ "MADStager:RemoveAvailableForStaging"
+ "MADStager:ReplyNoCandidatesRemoveAvailForStaging"
+ "MaxConcurrent"
+ "MaxInFlightObserved"
+ "MaxKqwlCount"
+ "MaxPendingObserved"
+ "MaxWaitMs"
+ "RemoveAvailableForStaging"
+ "ReplyNoCandidatesRemoveAvailForStaging"
+ "STAGER_PROMOTED|requiringLoad:%@|stagedToDownloaded:%ld|stagedSetLookupResults:%ld|stagedFromBuildVersion:%@|newOSPromotion:%@"
+ "Throttle cap override: %{public}@=%ld (default was %lu)"
+ "ThrottleName"
+ "Throttle[%{public}@]: cancelled pending taskID=%lu (queued=%lu)"
+ "Throttle[%{public}@]: completed taskID=%lu (inFlight=%lu, queued=%lu, cap=%lu) %{public}@"
+ "Throttle[%{public}@]: deferred taskID=%lu (inFlight=%lu, queued=%lu, cap=%lu) %{public}@"
+ "Throttle[%{public}@]: drained taskID=%lu (waitedMs=%llu, inFlight=%lu, queued=%lu) %{public}@"
+ "Throttle[%{public}@]: enqueueSubmit called with nil submitBlock or task; dropping"
+ "Throttle[%{public}@]: slotDidCloseForTask called with inFlight=0 taskID=%@; ignoring"
+ "WKMSURLOverride"
+ "[KnoxURLOverride]: Using override %{public}@ for asset %{public}@"
+ "[MobileAssetHealthReport]: DownloadManager nil; skipping throttle telemetry"
+ "[PallasNonce:%{public}@] Pallas JWS parsing did not yield 3 elements, elements: %lu bytes: %{public}@"
+ "[WKMSURLOverride]: Ignoring malformed override (class=%{public}@, length=%lu)"
+ "[WKMSURLOverride]: Using override %{public}@ (catalog was %{public}@)"
+ "averageWaitMs"
+ "cancelledWhilePendingCount"
+ "com.apple.mobileassetd.Throttle.Snapshot"
+ "deferralCount"
+ "enqueueCount"
+ "have target lookup results (no staged content)|"
+ "inFlight"
+ "inprocess"
+ "kqwl=%u"
+ "kqwl=?"
+ "loaded persisted-state (nil handedOffAsPromoted; targetLookupResults:%ld)"
+ "maxConcurrent"
+ "maxInFlightObserved"
+ "maxPendingObserved"
+ "maxWaitMs"
+ "name"
+ "newLatestToVendForEachPSUSFreshness"
+ "pallas"
+ "pending"
+ "resumeTask called with nil task; ignoring"
+ "resumeTask called with nil throttle for task %{public}@; resuming directly"
+ "splunk"
+ "target-lookup-results describing Pallas atomicity | targetOTASituation:%@ | trainTargetLookupResults:%@ | setLookupResult:%@"
+ "{newLatestToVendForEachPSUSFreshness} set-configuration with stale latest-to-vend wher PSUS lookup does not satisfy the current set-configuration | nextSetConfiguration:%{public}@"
+ "{newLatestToVendForEachPSUSFreshness} set-configuration with stale latest-to-vend where PSUS lookup satisfies the current set-configuration | nextSetConfiguration:%{public}@ | psusLookupResult:%{public}@ | changedLatestToVend:%{public}@"
- "%{public}@\n[AUTO-STAGER] {%{public}@} persisted target-OTA-situation | targetLookupResultsKey:%{public}@ | targetOTASituation:%{public}@"
- "-[DownloadManager getCurrentInflightDownloads:]"
- "-[DownloadManager getCurrentInflightDownloads:]_block_invoke"
- "2.5.6"
- "4.1.1"
- "DownloadManager:getCurrentInflightDownloads"
- "Loaded built-in MobileAssetDaemon_Framework Jun  1 2026 21:31:05"
- "STAGER_PROMOTED|requiringLoad:%@|stagedToDownloaded:%ld|stagedSetLookupResults:%ld|newOSPromotion:%@"
- "[%{public}s] Downloading: %{public}@"
- "[%{public}s] No background session present for fetching inflight downloads"
- "[%{public}s] Size of self.downloadTasksInFlight: %ld"
- "[%{public}s] Sync with NSURLSession is complete and found %lu tasks"
- "[%{public}s] Sync with NSURLSession is not possible; in-process downloads found %lu tasks"
- "[PallasNonce:%{public}@] Pallas JWS parsing did not yield 3 elements, elements: %lu bytes: %{public}s"
- "target-lookup-results describing Pallas atomicity | targetOTASituation:%@ | trainTargetLookupResults:%@"
```
