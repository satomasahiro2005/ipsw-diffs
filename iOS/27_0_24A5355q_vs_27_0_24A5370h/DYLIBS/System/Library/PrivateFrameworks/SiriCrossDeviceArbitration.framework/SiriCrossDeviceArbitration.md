## SiriCrossDeviceArbitration

> `/System/Library/PrivateFrameworks/SiriCrossDeviceArbitration.framework/SiriCrossDeviceArbitration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fcb8` | `0x2f498` | **`-0x820`** |
| `__AUTH_CONST.__objc_const` | `0x5678` | `0x5318` | **`-0x360`** |
| `__TEXT.__oslogstring` | `0x5266` | `0x545a` | **`+0x1f4`** |
| `__TEXT.__objc_methlist` | `0x325c` | `0x30d4` | **`-0x188`** |
| `__AUTH_CONST.__cfstring` | `0x2d20` | `0x2e80` | **`+0x160`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f20` | `0x1df0` | **`-0x130`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xd8` | `—` | **`-0xd8`** |
| `__AUTH_CONST.__objc_intobj` | `0x1e0` | `0x108` | **`-0xd8`** |
| `__DATA_DIRTY.__objc_data` | `0xd20` | `0xc80` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x5e38` | `0x5db4` | **`-0x84`** |
| `__DATA_CONST.__const` | `0x10b0` | `0x1068` | **`-0x48`** |
| `__DATA_CONST.__objc_arraydata` | `0xa8` | `0x60` | **`-0x48`** |
| `__TEXT.__unwind_info` | `0xde0` | `0xd98` | **`-0x48`** |
| `__AUTH_CONST.__const` | `0x300` | `0x2c0` | **`-0x40`** |
| `__TEXT.__const` | `0x1e0` | `0x1a8` | **`-0x38`** |
| `__DATA.__objc_ivar` | `0x520` | `0x4f8` | **`-0x28`** |
| `__DATA_CONST.__got` | `0x310` | `0x2e8` | **`-0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x158` | `0x148` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x138` | `0x128` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x39c` | `0x3ac` | **`+0x10`** |

### Other Changes

```diff

-3600.43.3.1.1
+3600.49.5.1.1

-  Functions: 1269
-  Symbols:   2372
-  CStrings:  1037
+  Functions: 1236
+  Symbols:   2308
+  CStrings:  1048
Symbols:
+ -[SCDACoordinator _scheduleTimerLabeled:fireAt:thenExecute:]
+ -[SCDACoordinator _shouldSuppressElectionForTVState]
+ -[SCDACoordinator _writeElectionDataToDefaults]
+ -[SCDADevice overrideLocalConfiguration:productType:deviceAdjust:trumpDelay:]
+ -[SCDAGoodnessScoreEvaluator _setIsOdeon:]
+ -[SCDAGoodnessScoreEvaluator isOdeon]
+ -[SCDAGoodnessScoreEvaluator odeonConfigurationChangeHandler]
+ -[SCDAGoodnessScoreEvaluator setOdeonConfigurationChangeHandler:]
+ -[SCDAGoodnessScoreEvaluator startOdeonObservation]
+ -[SCDAMonitor _readElectionDataWithExpectedGeneration:]
+ -[SCDAMonitor _resultsSeen:generation:]
+ -[SCDAMonitor consumeElectionData]
+ GCC_except_table1010
+ GCC_except_table1031
+ GCC_except_table1095
+ GCC_except_table1123
+ GCC_except_table1126
+ GCC_except_table1138
+ GCC_except_table1212
+ GCC_except_table1213
+ GCC_except_table1219
+ GCC_except_table240
+ GCC_except_table246
+ GCC_except_table502
+ GCC_except_table61
+ GCC_except_table731
+ GCC_except_table777
+ GCC_except_table846
+ GCC_except_table861
+ GCC_except_table909
+ GCC_except_table912
+ GCC_except_table919
+ GCC_except_table946
+ GCC_except_table990
+ _OBJC_CLASS_$_NSUserDefaults
+ _OBJC_IVAR_$_SCDACoordinator._originalDeviceAdjust
+ _OBJC_IVAR_$_SCDACoordinator._originalDeviceClass
+ _OBJC_IVAR_$_SCDACoordinator._originalProductType
+ _OBJC_IVAR_$_SCDACoordinator._originalTrumpDelay
+ _OBJC_IVAR_$_SCDAGoodnessScoreEvaluator._isOdeon
+ _OBJC_IVAR_$_SCDAGoodnessScoreEvaluator._odeonConfigurationChangeHandler
+ _OBJC_IVAR_$_SCDAGoodnessScoreEvaluator._savedPlatformBias
+ _OBJC_IVAR_$_SCDAMonitor._electionData
+ ___34-[SCDAMonitor consumeElectionData]_block_invoke
+ ___60-[SCDACoordinator _scheduleTimerLabeled:fireAt:thenExecute:]_block_invoke
+ ___block_descriptor_40_e8_32w_e8_v12?0B8lw32l8
+ _dispatch_after
- +[SCDAArbitrationParticipationContext _convertBoosts:]
- +[SCDAArbitrationParticipationContext _convertLastActivationTime:]
- +[SCDAArbitrationParticipationContext _convertTriggerType:]
- +[SCDAArbitrationParticipationContext _convertTrumpReason:]
- -[SCDAArbitrationParticipationContext .cxx_destruct]
- -[SCDAArbitrationParticipationContext _processAdvertisements:winnerAdvertisement:]
- -[SCDAArbitrationParticipationContext boosts]
- -[SCDAArbitrationParticipationContext cdaId]
- -[SCDAArbitrationParticipationContext initAdvertisements:decision:requestStartDate:session:voiceTriggerTime:winnerAdvertisement:]
- -[SCDAArbitrationParticipationContext msSinceLastWin]
- -[SCDAArbitrationParticipationContext msSinceTrigger]
- -[SCDAArbitrationParticipationContext myAdvertisement]
- -[SCDAArbitrationParticipationContext rawGoodnessScore]
- -[SCDAArbitrationParticipationContext requestStartDate]
- -[SCDAArbitrationParticipationContext result]
- -[SCDAArbitrationParticipationContext seenAdvertisements]
- -[SCDAArbitrationParticipationContext triggerType]
- -[SCDAArbitrationParticipationContext trumpReasons]
- -[SCDAArbitrationParticipationContext updateBoosts:triggerType:lastWin:lastDecision:]
- -[SCDAArbitrationParticipationContext voiceTriggerDate]
- -[SCDAArbitrationParticipationContext winnerAdvertisement]
- -[SCDAArbitrationParticipationController .cxx_destruct]
- -[SCDAArbitrationParticipationController _publishFeedbackArbitrationRecordForNearMiss]
- -[SCDAArbitrationParticipationController _resetSettingsConnection]
- -[SCDAArbitrationParticipationController dealloc]
- -[SCDAArbitrationParticipationController init]
- -[SCDAArbitrationParticipationController publishArbitrationParticipationContext:]
- -[SCDAArbitrationParticipationController queue]
- -[SCDAArbitrationParticipationController setQueue:]
- -[SCDAArbitrationParticipationController setSettingsConnection:]
- -[SCDAArbitrationParticipationController setXpcConnectionQueue:]
- -[SCDAArbitrationParticipationController settingsConnection]
- -[SCDAArbitrationParticipationController xpcConnectionQueue]
- -[SCDACoordinator _createDispatchTimerFor:toExecute:]
- -[SCDACoordinator _createDispatchTimerForEvent:toExecute:]
- -[SCDACoordinator _createDispatchTimerWithTime:toExecute:]
- -[SCDACoordinator _initializeTimer]
- -[SCDACoordinator _initializeWiProxReadinessTimer]
- -[SCDACoordinator _resumeWiProxReadinessTimer]
- -[SCDACoordinator _suspendWiProxReadinessTimer]
- -[SCDAInstrumentation userFeedbackPublishArbitrationParticipationContext:]
- -[SCDAMonitor _resultsSeen:]
- GCC_except_table1022
- GCC_except_table1045
- GCC_except_table1066
- GCC_except_table1129
- GCC_except_table1156
- GCC_except_table1159
- GCC_except_table1171
- GCC_except_table1245
- GCC_except_table1246
- GCC_except_table1252
- GCC_except_table235
- GCC_except_table241
- GCC_except_table536
- GCC_except_table59
- GCC_except_table805
- GCC_except_table874
- GCC_except_table889
- GCC_except_table941
- GCC_except_table944
- GCC_except_table951
- GCC_except_table978
- _CFNotificationCenterRemoveObserver
- _OBJC_CLASS_$_AFFeatureFlags
- _OBJC_CLASS_$_NSConstantArray
- _OBJC_CLASS_$_SCDAArbitrationParticipationContext
- _OBJC_CLASS_$_SCDAArbitrationParticipationController
- _OBJC_CLASS_$_SCDAFAdvertisement
- _OBJC_CLASS_$_SCDAFBoost
- _OBJC_CLASS_$_SCDAFParticipation
- _OBJC_IVAR_$_SCDAArbitrationParticipationContext._boosts
- _OBJC_IVAR_$_SCDAArbitrationParticipationContext._cdaId
- _OBJC_IVAR_$_SCDAArbitrationParticipationContext._msSinceLastWin
- _OBJC_IVAR_$_SCDAArbitrationParticipationContext._msSinceTrigger
- _OBJC_IVAR_$_SCDAArbitrationParticipationContext._myAdvertisement
- _OBJC_IVAR_$_SCDAArbitrationParticipationContext._rawGoodnessScore
- _OBJC_IVAR_$_SCDAArbitrationParticipationContext._requestStartDate
- _OBJC_IVAR_$_SCDAArbitrationParticipationContext._result
- _OBJC_IVAR_$_SCDAArbitrationParticipationContext._seenAdvertisements
- _OBJC_IVAR_$_SCDAArbitrationParticipationContext._triggerType
- _OBJC_IVAR_$_SCDAArbitrationParticipationContext._trumpReasons
- _OBJC_IVAR_$_SCDAArbitrationParticipationContext._voiceTriggerDate
- _OBJC_IVAR_$_SCDAArbitrationParticipationContext._winnerAdvertisement
- _OBJC_IVAR_$_SCDAArbitrationParticipationController._queue
- _OBJC_IVAR_$_SCDAArbitrationParticipationController._settingsConnection
- _OBJC_IVAR_$_SCDAArbitrationParticipationController._xpcConnectionQueue
- _OBJC_IVAR_$_SCDACoordinator._timer
- _OBJC_IVAR_$_SCDAInstrumentation._arbitrationParticipationController
- _OBJC_METACLASS_$_SCDAArbitrationParticipationContext
- _OBJC_METACLASS_$_SCDAArbitrationParticipationController
- __OBJC_$_CLASS_METHODS_SCDAArbitrationParticipationContext
- __OBJC_$_INSTANCE_METHODS_SCDAArbitrationParticipationContext
- __OBJC_$_INSTANCE_METHODS_SCDAArbitrationParticipationController
- __OBJC_$_INSTANCE_VARIABLES_SCDAArbitrationParticipationContext
- __OBJC_$_INSTANCE_VARIABLES_SCDAArbitrationParticipationController
- __OBJC_$_PROP_LIST_SCDAArbitrationParticipationContext
- __OBJC_$_PROP_LIST_SCDAArbitrationParticipationController
- __OBJC_CLASS_RO_$_SCDAArbitrationParticipationContext
- __OBJC_CLASS_RO_$_SCDAArbitrationParticipationController
- __OBJC_METACLASS_RO_$_SCDAArbitrationParticipationContext
- __OBJC_METACLASS_RO_$_SCDAArbitrationParticipationController
- ___35-[SCDACoordinator _initializeTimer]_block_invoke
- ___50-[SCDACoordinator _initializeWiProxReadinessTimer]_block_invoke
- ___58-[SCDACoordinator _createDispatchTimerWithTime:toExecute:]_block_invoke
- ___74-[SCDAInstrumentation userFeedbackPublishArbitrationParticipationContext:]_block_invoke
- ___81-[SCDAArbitrationParticipationController publishArbitrationParticipationContext:]_block_invoke
- ___82-[SCDAArbitrationParticipationContext _processAdvertisements:winnerAdvertisement:]_block_invoke
- ___86-[SCDAArbitrationParticipationController _publishFeedbackArbitrationRecordForNearMiss]_block_invoke
- ___block_descriptor_56_e8_32s40s48s_e27_v32?0"SCDARecord"8Q16^B24ls32l8s40l8s48l8
- _notificationNearMissCallback
CStrings:
+ "%s #scda Odeon configuration changed: isOdeon = %@, platform bias = %d"
+ "%s #scda Timer %@ skipped: event token cleared (fired token: %@)"
+ "%s #scda Timer %@ skipped: event token mismatch (fired: %@, current: %@)"
+ "%s #scda WiProx readiness timeout skipped: token cleared (fired token: %@)"
+ "%s #scda WiProx readiness timeout skipped: token mismatch (fired: %@, current: %@)"
+ "%s BTLE TV state changed to non-participating: forfeiting won election"
+ "%s BTLE TV state changed to non-participating: skipping suppression broadcast"
+ "%s BTLE in-ear trigger entering election with default goodness"
+ "(empty record / no replies)"
+ "-[SCDACoordinator _scheduleTimerLabeled:fireAt:thenExecute:]_block_invoke"
+ "-[SCDAGoodnessScoreEvaluator _setIsOdeon:]"
+ "-[SCDAMonitor _resultsSeen:generation:]"
+ "SCDAElectionData"
+ "[MultiStage] Generation mismatch: expected %llu, got %llu. Discarding stale data."
+ "[MultiStage] No election data found in defaults."
+ "[MultiStage] Read election data: %lu results, generation: %llu"
+ "[MultiStage] Wrote election data: %lu results, generation: %llu"
+ "deviceClass"
+ "deviceGroup"
+ "deviceName"
+ "idsIdentifier"
+ "isLocalDevice"
+ "isWinner"
+ "monitorDataHandoff"
+ "next action window"
+ "phash"
+ "productType"
+ "results"
+ "v12@?0B8"
- "%s #scda #feedback"
- "%s #scda #feedback near miss!"
- "%s #scda Event token: %@, current event token: %@ for timer: %@"
- "%s #scda WiProx readiness timer initialized"
- "%s #scda WiProx readiness timer suspended"
- "%s BTLE timer %@ cancelled (%@)"
- "%s BTLE trumping from in ear voice trigger"
- "%s Unexpectedly lowering goodness score %du for in ear trigger"
- "-[SCDAArbitrationParticipationController _publishFeedbackArbitrationRecordForNearMiss]_block_invoke"
- "-[SCDACoordinator _createDispatchTimerWithTime:toExecute:]_block_invoke"
- "-[SCDACoordinator _initializeTimer]"
- "-[SCDACoordinator _initializeWiProxReadinessTimer]"
- "-[SCDACoordinator _suspendWiProxReadinessTimer]"
- "-[SCDAMonitor _resultsSeen:]"
- "AFArbitrationParticipationQueue"
- "AFArbitrationParticipationXPCConnectionQueue"
- "com.apple.voicetrigger.NearTrigger"
- "notificationNearMissCallback"
```
