## ComputeSafeguards

> `/System/Library/PrivateFrameworks/ComputeSafeguards.framework/ComputeSafeguards`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55c34` | `0x56250` | **`+0x61c`** |
| `__TEXT.__oslogstring` | `0xe4d1` | `0xe2fa` | **`-0x1d7`** |
| `__TEXT.__cstring` | `0x5cd8` | `0x5e0e` | **`+0x136`** |
| `__TEXT.__gcc_except_tab` | `0xe5c` | `0xf10` | **`+0xb4`** |
| `__AUTH_CONST.__objc_const` | `0x5710` | `0x5680` | **`-0x90`** |
| `__AUTH_CONST.__const` | `0x480` | `0x500` | **`+0x80`** |
| `__AUTH_CONST.__objc_intobj` | `0x600` | `0x678` | **`+0x78`** |
| `__DATA_CONST.__const` | `0x9e8` | `0xa60` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x3f1c` | `0x3ed4` | **`-0x48`** |
| `__TEXT.__unwind_info` | `0xef0` | `0xf38` | **`+0x48`** |
| `__DATA.__bss` | `0x98` | `0xc8` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x6060` | `0x6080` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x300` | `0x318` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2608` | `0x25f0` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x4c8` | `0x4d8` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x1f0` | `0x1e0` | **`-0x10`** |
| `__TEXT.__const` | `0x310` | `0x320` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x4a0` | `0x494` | **`-0xc`** |
| `__DATA_CONST.__objc_arraydata` | `0x2528` | `0x2530` | **`+0x8`** |

### Other Changes

```diff

-145.0.0.0.0
+163.0.0.0.0

-  Functions: 1899
-  Symbols:   2436
-  CStrings:  1794
+  Functions: 1908
+  Symbols:   2444
+  CStrings:  1792
Symbols:
+ -[CSMitigationManager logCPUViolationToPowerLog:pid:coalitionID:coalitionName:endTime:observedValue:observationWindow:limitValue:limitWindow:fatal:issueType:mitigationType:mitigationReason:withError:]
+ -[CSPowerlogDBReader getFastPassIntervalsWithLaunchdName:processName:andStartDate:andEndDate:]
+ -[CSTriggerManager _updateSlidingWindowWithCoalitionData:collectionTime:dasCIDs:]
+ GCC_except_table102
+ GCC_except_table33
+ GCC_except_table76
+ GCC_except_table83
+ GCC_except_table89
+ GCC_except_table97
+ _OBJC_CLASS_$_NSMutableString
+ ___41-[CSTriggerManager _collectTopCoalitions]_block_invoke
+ ___46-[CSTriggerManager transitionToGameModeActive]_block_invoke
+ ___48-[CSTriggerManager transitionToGameModeInactive]_block_invoke
+ ___56-[CSTriggerManager updateAudioRecognitionExemptionState]_block_invoke
+ ___block_descriptor_33_e5_v8?0l
+ ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48r56r64r_e5_v8?0ls32l8r48l8s40l8r56l8r64l8
+ ___getDetectionQueue_block_invoke
+ ___getStateQueue_block_invoke
+ ___temporaryLiftRestoreReasons_block_invoke
+ _dispatchAsyncOnDetectionQueue
+ _dispatchAsyncOnStateQueue
+ _dispatchSyncOnDetectionQueue
+ _dispatchSyncOnStateQueue
+ _dispatch_assert_queue_not$V2
+ _dispatch_queue_attr_make_with_qos_class
+ _getDetectionQueue
+ _getDetectionQueue.q
+ _getDetectionQueue.token
+ _getStateQueue
+ _getStateQueue.q
+ _getStateQueue.token
+ _temporaryLiftRestoreReasons
+ _temporaryLiftRestoreReasons.onceToken
+ _temporaryLiftRestoreReasons.reasons
- -[CSMitigationManager logCPUViolationToPowerLog:pid:coalitionID:coalitionName:endTime:observedValue:observationWindow:limitValue:limitWindow:fatal:mitigationType:mitigationReason:withError:]
- -[CSPowerlogDBReader getFastPassIntervalsWithProcessName:andStartDate:andEndDate:]
- -[CSRestrictionManager currentExemptedProcesses]
- -[CSRestrictionManager previouslyMitigatedAudioRecognitionProcesses]
- -[CSRestrictionManager previouslyMitigatedDASProcesses]
- -[CSRestrictionManager setCurrentExemptedProcesses:]
- -[CSRestrictionManager setPreviouslyMitigatedAudioRecognitionProcesses:]
- -[CSRestrictionManager setPreviouslyMitigatedDASProcesses:]
- -[CSTriggerManager _updateSlidingWindowWithCoalitionData:collectionTime:]
- GCC_except_table100
- GCC_except_table34
- GCC_except_table50
- GCC_except_table54
- GCC_except_table56
- GCC_except_table64
- GCC_except_table74
- GCC_except_table87
- GCC_except_table95
- _OBJC_IVAR_$_CSRestrictionManager._currentExemptedProcesses
- _OBJC_IVAR_$_CSRestrictionManager._previouslyMitigatedAudioRecognitionProcesses
- _OBJC_IVAR_$_CSRestrictionManager._previouslyMitigatedDASProcesses
- ___43-[CSTriggerManager processTimerFiredAction]_block_invoke_2
- ___49-[CSIssueDetector clearFatalMitigatedProcessList]_block_invoke
- ___getMainQueue_block_invoke
- __dispatch_main_q
- _getMainQueue.onceToken
- _mainQueue
CStrings:
+ "(ProcessName = '%@' OR ProcessName = '%@' OR ',' || REPLACE(InvolvedProcesses, ' ', '') || ',' LIKE '%%,%@,%%' OR ',' || REPLACE(InvolvedProcesses, ' ', '') || ',' LIKE '%%,%@,%%')"
+ "C"
+ "Invalid charging deny regex pattern: %@, error: %@"
+ "SELECT * FROM (SELECT * FROM PLDuetService_EventNone_DASActivityLifecycle WHERE %@%@ AND StartDate < %f ORDER BY StartDate DESC LIMIT 1) AS pre UNION SELECT * FROM PLDuetService_EventNone_DASActivityLifecycle WHERE %@%@ AND StartDate >= %f AND StartDate < %f ORDER BY StartDate"
+ "SELECT m.* FROM (SELECT m.* FROM XPCMetrics_OngoingRestore_14_2 AS m JOIN XPCMetrics_OngoingRestore_14_2_Array_processName AS p ON m.ID = p.FK_ID WHERE (p.processName = '%@' OR p.processName = '%@') AND m.timestamp < %f ORDER BY m.timestamp DESC LIMIT 1) AS m UNION SELECT m.* FROM XPCMetrics_OngoingRestore_14_2 AS m JOIN XPCMetrics_OngoingRestore_14_2_Array_processName AS p ON m.ID = p.FK_ID WHERE (p.processName = '%@' OR p.processName = '%@') AND m.timestamp >= %f AND m.timestamp < %f ORDER BY timestamp"
+ "TelemetryMode"
+ "audio-recognition"
+ "com.apple.BatteryDischargeService"
+ "com.apple.computesafeguards.detection"
+ "com.apple.computesafeguards.state"
+ "das-intensive"
+ "handleDetectedIssues: Found issue with rule %d (%@) for process %@ with coalitionID: %llu from time %s to %s"
+ "handleDetectionViolation: plugged-in exemption does not cover thermal violation for process:%@, falling through"
+ "handleDetectorViolation: rule %d disabled by policy, skipping mitigation"
+ "handleUserActivityLevelChanged: %@ not found, skipping"
+ "liftMitigationsForDaemons: Skipping %@ (issueType: %s) — not lifted by plugged-in"
+ "plugged-in"
+ "removeProcessFromPenaltyBox: Stopped timer and exit monitoring for %@"
+ "restoreMitigationsForAudioRecognitionEnd: Restoring mitigations for audio recognition processes"
+ "shouldTransitionPenalty: Lift source ended with thermal penalty - saved CPU state exists, transition needed for %@"
+ "|^(com\\.apple\\.)?driver\\."
- "Display turned off, restoring mitigations for exempted processes: %@"
- "Display turned on, re-lifting BG exemptions for %@"
- "Display turned on, re-lifting FG exemptions for %@"
- "Display turned on, re-lifting mitigations for Siri-active daemon %@"
- "Process %@ was not previously mitigated, no restoration needed"
- "Process %@ was previously mitigated (penaltyBox:%d), tracking for restoration"
- "Restoring mitigations for process %@ after DAS work completion"
- "SELECT * FROM PLDuetService_EventNone_DASActivityLifecycle WHERE (ProcessName = '%@' OR ProcessName = '%@' OR ',' || REPLACE(InvolvedProcesses, ' ', '') || ',' LIKE '%%,%@,%%' OR ',' || REPLACE(InvolvedProcesses, ' ', '') || ',' LIKE '%%,%@,%%') AND StartDate < %f AND EndDate > %f"
- "SELECT m.* FROM (SELECT m.* FROM XPCMetrics_OngoingRestore_14_2 AS m JOIN XPCMetrics_OngoingRestore_14_2_Array_processName AS p ON m.ID = p.FK_ID WHERE p.processName = '%@' AND m.timestamp < %f ORDER BY m.timestamp DESC LIMIT 1) AS m UNION SELECT m.* FROM XPCMetrics_OngoingRestore_14_2 AS m JOIN XPCMetrics_OngoingRestore_14_2_Array_processName AS p ON m.ID = p.FK_ID WHERE p.processName = '%@' AND m.timestamp >= %f AND m.timestamp < %f ORDER BY timestamp"
- "com.apple.computesafeguards.mainqueue"
- "com.apple.generativesearchd"
- "handleDetectedIssues: Found issues with rule %d (%@) issue for process %@ with coalitionID: %llu from time %s to %s [%@]"
- "handleUserActivityLevelChanged: searchd not found, skipping"
- "liftMitigationsForAudioRecognitionStart: Keeping process %@ (issueType: %s)"
- "liftMitigationsForAudioRecognitionStart: Tracking process %@ for restoration"
- "liftMitigationsForDASProcesses: Could not locate object for processIdentifier:%@"
- "mitigation-allowed"
- "removeProcessFromPenaltyBox: Lifted mitigation for %@ due to scenario (reason: %s), stopped timer and exit monitoring"
- "restoreMitigationsForAudioRecognitionEnd: No previously mitigated audio recognition processes to restore"
- "restoreMitigationsForAudioRecognitionEnd: Restoring mitigations for %lu process(es)"
- "restoreMitigationsForAudioRecognitionEnd: Restoring penalty box for %@"
- "telemetry-only"
- "ursa-only"
```
