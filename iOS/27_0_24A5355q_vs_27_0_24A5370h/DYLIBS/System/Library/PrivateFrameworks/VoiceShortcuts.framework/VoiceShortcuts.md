## VoiceShortcuts

> `/System/Library/PrivateFrameworks/VoiceShortcuts.framework/VoiceShortcuts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x128f30` | `0x12b480` | **`+0x2550`** |
| `__DATA.__bss` | `0x4230` | `0x47c0` | **`+0x590`** |
| `__TEXT.__oslogstring` | `0xe76b` | `0xec26` | **`+0x4bb`** |
| `__TEXT.__cstring` | `0xf714` | `0xfb7f` | **`+0x46b`** |
| `__TEXT.__const` | `0x5ed8` | `0x6188` | **`+0x2b0`** |
| `__AUTH_CONST.__const` | `0x8cb8` | `0x8b88` | **`-0x130`** |
| `__TEXT.__swift5_typeref` | `0x2f7d` | `0x3093` | **`+0x116`** |
| `__AUTH_CONST.__auth_got` | `0x1f08` | `0x2018` | **`+0x110`** |
| `__DATA_DIRTY.__bss` | `0x2660` | `0x2560` | **`-0x100`** |
| `__DATA.__data` | `0x29b0` | `0x2a80` | **`+0xd0`** |
| `__TEXT.__eh_frame` | `0x7ad0` | `0x7b68` | **`+0x98`** |
| `__DATA_DIRTY.__data` | `0x1aa8` | `0x1a20` | **`-0x88`** |
| `__TEXT.__unwind_info` | `0x4a48` | `0x4ad0` | **`+0x88`** |
| `__AUTH_CONST.__objc_const` | `0x9f30` | `0x9fa8` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x5804` | `0x585c` | **`+0x58`** |
| `__TEXT.__swift5_assocty` | `0x570` | `0x5b8` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x26dc` | `0x2698` | **`-0x44`** |
| `__DATA_CONST.__got` | `0x1960` | `0x1990` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x15e4` | `0x15b4` | **`-0x30`** |
| `__TEXT.__swift5_proto` | `0x3a8` | `0x3cc` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0x41e0` | `0x41c0` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4978` | `0x4960` | **`-0x18`** |
| `__DATA_CONST.__objc_catlist` | `0x100` | `0x110` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x2278` | `0x2270` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x1f7c` | `0x1f74` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x708` | `0x70c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-5025.0.25.103.0
+5028.0.21.0.0

-  Functions: 7355
-  Symbols:   5349
-  CStrings:  2294
+  Functions: 7347
+  Symbols:   5352
+  CStrings:  2339
Symbols:
+ +[WFWorkoutTrigger(BiomeContext) registerContextSyncClient]
+ +[WFWorkoutTrigger(BiomeContext) unregisterContextSyncClient]
+ -[WFAppInFocusTrigger(BiomeContext) publisherWithScheduler:]
+ -[WFAppInFocusTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
+ -[WFTriggerEventQueue didFinishRunningWithError:cancelled:triggerKey:eventInfo:runEvent:]
+ -[WFTriggerEventQueue enqueueTriggerWithKey:eventInfo:force:completion:]
+ -[WFTriggerEventQueue notificationManager:didDismissTriggerWithKey:pendingTriggerEventIDs:]
+ -[WFTriggerEventQueue notificationManager:didFailToPostActionRequiredNotificationWithTriggerKey:pendingTriggerEventIDs:]
+ -[WFTriggerEventQueue notificationManager:didRequestDisablementOfTriggersWithKeys:]
+ -[WFTriggerEventQueue notificationManager:receivedConfirmationToRunTriggerWithKey:pendingTriggerEventIDs:]
+ -[WFTriggerEventQueue notificationManager:receivedContinuePotentialLoopForTriggerWithKey:pendingTriggerEventIDs:]
+ -[WFTriggerEventQueue notificationManager:receivedStopPotentialLoopForTriggerWithKey:]
+ -[WFTriggerEventQueue registerDebounceDuration:forTriggerWithKey:]
+ -[WFTriggerEventQueue resumeWithTriggerKey:workflowReference:eventInfo:completion:]
+ -[WFTriggerEventQueue runWithTriggerKey:workflowReference:eventInfo:completion:]
+ -[WFTriggerEventQueue sendRateLimitEncounteredNotificationForTriggerWithKey:]
+ -[WFTriggerEventQueue shouldRunTriggerWithKey:shouldPrompt:forEvent:runEvents:error:]
+ -[WFTriggerEventQueue unregisterDebounceForTriggerWithKey:]
+ -[WFTriggerEventRunner inProgressTriggerKey]
+ -[WFTriggerEventRunner logPowerLogEventForTriggerKey:workflowReference:]
+ -[WFTriggerEventRunner setInProgressTriggerKey:]
+ -[WFTriggerEventRunner startRunningWorkflow:forTriggerKey:eventInfo:completion:]
+ -[WFTriggerNotificationDebouncer addEventsWithIdentifiers:notificationType:triggerKey:workflowReference:]
+ -[WFTriggerNotificationDebouncerItem initWithTriggerKey:notificationType:reference:triggerEventIDs:debouncer:]
+ -[WFTriggerNotificationDebouncerItem triggerKey]
+ -[WFTriggerNotificationScheduler cancelActivitiesFromTriggerKey:]
+ -[WFTriggerNotificationScheduler cancelActivitiesFromTriggerKeyOnQueue:]
+ -[WFTriggerNotificationScheduler initialRunDateForTriggerKey:]
+ -[WFTriggerNotificationScheduler postBackgroundRunningNotificationForTriggerKey:]
+ -[WFTriggerNotificationScheduler registerTriggerWithKey:delay:]
+ -[WFTriggerNotificationScheduler scheduleTriggerForNotificationsWithKey:]
+ -[WFTriggerNotificationScheduler updateTriggerNotificationLevelsForKeys:]
+ -[WFTriggerUserNotificationManager _postNotificationOfType:forTriggerKey:workflowReference:removeDeliveredNotifications:pendingTriggerEventIDs:actionIcons:error:]
+ -[WFTriggerUserNotificationManager postActionRequiredNotificationForTriggerKey:notificationType:workflowReference:pendingTriggerEventIDs:]
+ -[WFTriggerUserNotificationManager postNotificationOfType:forTriggerKey:workflowReference:removeDeliveredNotifications:pendingTriggerEventIDs:actionIcons:error:]
+ -[WFTriggerUserNotificationManager postNotificationThatTriggerWithKey:failedWithError:notificationRequestIdentifier:]
+ -[WFTriggerUserNotificationManager removeNotificationsWithTriggerKey:]
+ -[WFWorkoutTrigger(BiomeContext) hasRemotePublisher]
+ -[WFWorkoutTrigger(BiomeContext) publisherWithScheduler:]
+ -[WFWorkoutTrigger(BiomeContext) remotePublisherWithScheduler:]
+ -[WFWorkoutTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
+ GCC_except_table1004
+ GCC_except_table1010
+ GCC_except_table1012
+ GCC_except_table1030
+ GCC_except_table1109
+ GCC_except_table1122
+ GCC_except_table1150
+ GCC_except_table1211
+ GCC_except_table1217
+ GCC_except_table1222
+ GCC_except_table1223
+ GCC_except_table1228
+ GCC_except_table1281
+ GCC_except_table1352
+ GCC_except_table1380
+ GCC_except_table1392
+ GCC_except_table1397
+ GCC_except_table1399
+ GCC_except_table1411
+ GCC_except_table1413
+ GCC_except_table1415
+ GCC_except_table1416
+ GCC_except_table1418
+ GCC_except_table1419
+ GCC_except_table1432
+ GCC_except_table1466
+ GCC_except_table1470
+ GCC_except_table1484
+ GCC_except_table1489
+ GCC_except_table1499
+ GCC_except_table1505
+ GCC_except_table1537
+ GCC_except_table1541
+ GCC_except_table1559
+ GCC_except_table1563
+ GCC_except_table1577
+ GCC_except_table1579
+ GCC_except_table1583
+ GCC_except_table1601
+ GCC_except_table1604
+ GCC_except_table1618
+ GCC_except_table231
+ GCC_except_table302
+ GCC_except_table316
+ GCC_except_table335
+ GCC_except_table343
+ GCC_except_table370
+ GCC_except_table392
+ GCC_except_table455
+ GCC_except_table474
+ GCC_except_table553
+ GCC_except_table564
+ GCC_except_table635
+ GCC_except_table636
+ GCC_except_table649
+ GCC_except_table660
+ GCC_except_table845
+ GCC_except_table978
+ _HealthKitLibrary.sLib
+ _HealthKitLibrary.sOnce
+ _OBJC_CLASS_$_BMAppInFocus
+ _OBJC_CLASS_$_BMContextSyncWorkout
+ _OBJC_CLASS_$_BMHealthWorkout
+ _OBJC_CLASS_$_WFAppInFocusTrigger
+ _OBJC_CLASS_$_WFUnifiedTriggerKey
+ _OBJC_CLASS_$_WFWorkoutTrigger
+ _OBJC_IVAR_$_WFTriggerEventRunner._inProgressTriggerKey
+ _OBJC_IVAR_$_WFTriggerNotificationDebouncerItem._triggerKey
+ _WFDatabaseErrorDomain
+ _WFDeviceCapabilityWAPI
+ _WFSystemNotificationIdentifierIsForTrigger
+ _WFTriggerKeyFromNotificationUserInfo
+ _WFTriggerKeysToDisableFromNotificationUserInfo
+ _WFTriggerSystemNotificationIdentifier
+ __OBJC_$_CATEGORY_CLASS_METHODS_WFWorkoutTrigger_$_BiomeContext
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_WFAppInFocusTrigger_$_BiomeContext
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_WFWorkoutTrigger_$_BiomeContext
+ __OBJC_$_CATEGORY_WFAppInFocusTrigger_$_BiomeContext
+ __OBJC_$_CATEGORY_WFWorkoutTrigger_$_BiomeContext
+ ___105-[WFTriggerNotificationDebouncer addEventsWithIdentifiers:notificationType:triggerKey:workflowReference:]_block_invoke
+ ___106-[WFTriggerEventQueue notificationManager:receivedConfirmationToRunTriggerWithKey:pendingTriggerEventIDs:]_block_invoke
+ ___106-[WFTriggerEventQueue notificationManager:receivedConfirmationToRunTriggerWithKey:pendingTriggerEventIDs:]_block_invoke_2
+ ___113-[WFTriggerEventQueue notificationManager:receivedContinuePotentialLoopForTriggerWithKey:pendingTriggerEventIDs:]_block_invoke
+ ___113-[WFTriggerEventQueue notificationManager:receivedContinuePotentialLoopForTriggerWithKey:pendingTriggerEventIDs:]_block_invoke_2
+ ___117-[WFTriggerUserNotificationManager postNotificationThatTriggerWithKey:failedWithError:notificationRequestIdentifier:]_block_invoke
+ ___120-[WFTriggerEventQueue notificationManager:didFailToPostActionRequiredNotificationWithTriggerKey:pendingTriggerEventIDs:]_block_invoke
+ ___162-[WFTriggerUserNotificationManager _postNotificationOfType:forTriggerKey:workflowReference:removeDeliveredNotifications:pendingTriggerEventIDs:actionIcons:error:]_block_invoke
+ ___59-[WFTriggerEventQueue unregisterDebounceForTriggerWithKey:]_block_invoke
+ ___63-[WFTriggerNotificationScheduler registerTriggerWithKey:delay:]_block_invoke
+ ___63-[WFTriggerNotificationScheduler registerTriggerWithKey:delay:]_block_invoke_2
+ ___65-[WFTriggerNotificationScheduler cancelActivitiesFromTriggerKey:]_block_invoke
+ ___66-[WFTriggerEventQueue registerDebounceDuration:forTriggerWithKey:]_block_invoke
+ ___70-[WFTriggerUserNotificationManager removeNotificationsWithTriggerKey:]_block_invoke
+ ___70-[WFTriggerUserNotificationManager removeNotificationsWithTriggerKey:]_block_invoke_2
+ ___72-[WFTriggerEventQueue enqueueTriggerWithKey:eventInfo:force:completion:]_block_invoke
+ ___73-[WFTriggerNotificationScheduler scheduleTriggerForNotificationsWithKey:]_block_invoke
+ ___80-[WFTriggerEventQueue runWithTriggerKey:workflowReference:eventInfo:completion:]_block_invoke
+ ___80-[WFTriggerEventRunner startRunningWorkflow:forTriggerKey:eventInfo:completion:]_block_invoke
+ ___83-[WFTriggerEventQueue notificationManager:didRequestDisablementOfTriggersWithKeys:]_block_invoke
+ ___86-[WFTriggerEventQueue notificationManager:receivedStopPotentialLoopForTriggerWithKey:]_block_invoke
+ ___89-[WFTriggerEventQueue didFinishRunningWithError:cancelled:triggerKey:eventInfo:runEvent:]_block_invoke
+ ___91-[WFTriggerEventQueue notificationManager:didDismissTriggerWithKey:pendingTriggerEventIDs:]_block_invoke
+ ___HealthKitLibrary_block_invoke
+ _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationEventStreamVyxG0A9Shortcuts014DaemonXPCEventG0AE0F0AE0iF6SourceP_Se
+ _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationEventStreamVyxG0A9Shortcuts014DaemonXPCEventG0AE10DescriptorAeFP_AE0ifK0
+ _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationEventStreamVyxG0A9Shortcuts06DaemonF6SourceAE0F0AeFP_AE0iF0
+ _associated conformance SC19WFDatabaseErrorCodeLeV10Foundation021_ObjectiveCBridgeableB0SCs0B0
+ _associated conformance SC19WFDatabaseErrorCodeLeV10Foundation13CustomNSErrorSCs0B0
+ _associated conformance SC19WFDatabaseErrorCodeLeV10Foundation21_BridgedStoredNSErrorSC0C0AcDP_8RawValueSYs17FixedWidthInteger
+ _associated conformance SC19WFDatabaseErrorCodeLeV10Foundation21_BridgedStoredNSErrorSC0C0AcDP_AC01_bC8Protocol
+ _associated conformance SC19WFDatabaseErrorCodeLeV10Foundation21_BridgedStoredNSErrorSC0C0AcDP_SY
+ _associated conformance SC19WFDatabaseErrorCodeLeV10Foundation21_BridgedStoredNSErrorSCAC021_ObjectiveCBridgeableB0
+ _associated conformance SC19WFDatabaseErrorCodeLeV10Foundation21_BridgedStoredNSErrorSCAC06CustomG0
+ _associated conformance SC19WFDatabaseErrorCodeLeV10Foundation21_BridgedStoredNSErrorSCSH
+ _associated conformance SC19WFDatabaseErrorCodeLeVSHSCSQ
+ _associated conformance So19WFDatabaseErrorCodeV10Foundation01_bC8ProtocolSC01_B4TypeAcDP_AC21_BridgedStoredNSError
+ _associated conformance So19WFDatabaseErrorCodeV10Foundation01_bC8ProtocolSCSQ
+ _init_HKWorkoutActivityNameForActivityType
+ _softLink_HKWorkoutActivityNameForActivityType
+ _symbolic $s10Foundation18_ErrorCodeProtocolP
+ _symbolic $s10Foundation21_BridgedStoredNSErrorP
+ _symbolic SDySo19WFUnifiedTriggerKeyC_____G 14VoiceShortcuts18WFTriggerRegistrarC19TriggerRegistrationV
+ _symbolic So19WFUnifiedTriggerKeyC
+ _symbolic So19WFUnifiedTriggerKeyC3key______5valuet 14VoiceShortcuts18WFTriggerRegistrarC19TriggerRegistrationV
+ _symbolic So7NSErrorC
+ _symbolic So8NSObjectCIego_
+ _symbolic So8NSObjectCSgIego_
+ _symbolic _____ 11WorkflowKit27ImmediateIndexingControllerC
+ _symbolic _____ 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV
+ _symbolic _____ SC19WFDatabaseErrorCodeLeV
+ _symbolic _____ So19WFDatabaseErrorCodeV
+ _symbolic _____Iegn_ 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV
+ _symbolic _____SbIegnd_ 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV
+ _symbolic __________Iegnr_ 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV 0A9Shortcuts06DaemongF0V014DatabaseChangeG0V
+ _symbolic __________Iegnr_ 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV 0A9Shortcuts06DaemongF0V021ApplicationRegisteredG0V
+ _symbolic __________Iegnr_ 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV 0A9Shortcuts06DaemongF0V026ToolKitLocalDatabaseChangeG0V
+ _symbolic __________Iegnr_ 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV 0A9Shortcuts06DaemongF0V03Apph7ChangedG0V
+ _symbolic ___________pIegHnzo_ 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV s5ErrorP
+ _symbolic _____ySo19WFUnifiedTriggerKeyC_____G s17_NativeDictionaryV 14VoiceShortcuts18WFTriggerRegistrarC19TriggerRegistrationV
+ _symbolic _____ySo19WFUnifiedTriggerKeyC_____G s18_DictionaryStorageC 14VoiceShortcuts18WFTriggerRegistrarC19TriggerRegistrationV
+ _symbolic _____y_____G 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV AA17DistnotedMatchingO
+ _symbolic _____y_____G 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV AA24DistnotedMatchingTrustedO
+ _type_layout_string SC19WFDatabaseErrorCodeLeV
- -[WFTriggerEventQueue didFinishRunningWithError:cancelled:triggerIdentifier:eventInfo:runEvent:]
- -[WFTriggerEventQueue enqueueTriggerWithIdentifier:eventInfo:force:completion:]
- -[WFTriggerEventQueue notificationManager:didDismissTriggerWithIdentifier:pendingTriggerEventIDs:]
- -[WFTriggerEventQueue notificationManager:didFailToPostActionRequiredNotificationWithTriggerIdentifier:pendingTriggerEventIDs:]
- -[WFTriggerEventQueue notificationManager:didRequestDisablementOfTriggersWithIdentifiers:]
- -[WFTriggerEventQueue notificationManager:receivedConfirmationToRunTriggerWithIdentifier:pendingTriggerEventIDs:]
- -[WFTriggerEventQueue notificationManager:receivedContinuePotentialLoopForTriggerWithIdentifier:pendingTriggerEventIDs:]
- -[WFTriggerEventQueue notificationManager:receivedStopPotentialLoopForTriggerWithIdentifier:]
- -[WFTriggerEventQueue registerDebounceDuration:forTriggerWithIdentifier:]
- -[WFTriggerEventQueue resumeWithTriggerIdentifier:workflowReference:eventInfo:completion:]
- -[WFTriggerEventQueue runWithTriggerIdentifier:workflowReference:eventInfo:completion:]
- -[WFTriggerEventQueue sendRateLimitEncounteredNotificationForTriggerIdentifier:]
- -[WFTriggerEventQueue shouldRunTriggerWithIdentifier:shouldPrompt:forEvent:runEvents:error:]
- -[WFTriggerEventQueue unregisterDebounceForTriggerWithIdentifier:]
- -[WFTriggerEventRunner inProgressTriggerIdentifier]
- -[WFTriggerEventRunner logPowerLogEventForTriggerIdentifier:workflowReference:]
- -[WFTriggerEventRunner setInProgressTriggerIdentifier:]
- -[WFTriggerEventRunner startRunningWorkflow:forTriggerIdentifier:eventInfo:completion:]
- -[WFTriggerNotificationDebouncer addEventsWithIdentifiers:notificationType:triggerIdentifier:workflowReference:]
- -[WFTriggerNotificationDebouncerItem initWithTriggerIdentifier:notificationType:reference:triggerEventIDs:debouncer:]
- -[WFTriggerNotificationDebouncerItem triggerIdentifier]
- -[WFTriggerNotificationScheduler cancelActivitiesFromTriggerIdentifier:]
- -[WFTriggerNotificationScheduler cancelActivitiesFromTriggerIdentifierOnQueue:]
- -[WFTriggerNotificationScheduler initialRunDateForTriggerIdentifier:]
- -[WFTriggerNotificationScheduler postBackgroundRunningNotificationForTriggerIdentifier:]
- -[WFTriggerNotificationScheduler registerTriggerWithIdentifier:delay:]
- -[WFTriggerNotificationScheduler scheduleTriggerForNotificationsWithIdentifier:]
- -[WFTriggerNotificationScheduler updateTriggerNotificationLevelsForIdentifiers:]
- -[WFTriggerUserNotificationManager _postNotificationOfType:forTriggerIdentifier:workflowReference:removeDeliveredNotifications:pendingTriggerEventIDs:actionIcons:error:]
- -[WFTriggerUserNotificationManager postActionRequiredNotificationForTriggerIdentifier:notificationType:workflowReference:pendingTriggerEventIDs:]
- -[WFTriggerUserNotificationManager postNotificationOfType:forTriggerIdentifier:workflowReference:removeDeliveredNotifications:pendingTriggerEventIDs:actionIcons:error:]
- -[WFTriggerUserNotificationManager postNotificationThatTriggerWithIdentifier:failedWithError:notificationRequestIdentifier:]
- -[WFTriggerUserNotificationManager removeNotificationsWithTriggerIdentifier:]
- GCC_except_table1001
- GCC_except_table1003
- GCC_except_table1021
- GCC_except_table1100
- GCC_except_table1113
- GCC_except_table1141
- GCC_except_table1202
- GCC_except_table1208
- GCC_except_table1210
- GCC_except_table1213
- GCC_except_table1214
- GCC_except_table1272
- GCC_except_table1343
- GCC_except_table1371
- GCC_except_table1383
- GCC_except_table1388
- GCC_except_table1390
- GCC_except_table1391
- GCC_except_table1398
- GCC_except_table1402
- GCC_except_table1404
- GCC_except_table1406
- GCC_except_table1410
- GCC_except_table1423
- GCC_except_table1457
- GCC_except_table1461
- GCC_except_table1475
- GCC_except_table1480
- GCC_except_table1490
- GCC_except_table1496
- GCC_except_table1528
- GCC_except_table1532
- GCC_except_table1550
- GCC_except_table1554
- GCC_except_table1568
- GCC_except_table1570
- GCC_except_table1574
- GCC_except_table1592
- GCC_except_table1595
- GCC_except_table1609
- GCC_except_table232
- GCC_except_table297
- GCC_except_table311
- GCC_except_table330
- GCC_except_table338
- GCC_except_table361
- GCC_except_table383
- GCC_except_table446
- GCC_except_table465
- GCC_except_table544
- GCC_except_table555
- GCC_except_table626
- GCC_except_table627
- GCC_except_table640
- GCC_except_table651
- GCC_except_table836
- GCC_except_table969
- GCC_except_table995
- _OBJC_CLASS_$_WFEmailTrigger
- _OBJC_CLASS_$_WFMessageTrigger
- _OBJC_IVAR_$_WFTriggerEventRunner._inProgressTriggerIdentifier
- _OBJC_IVAR_$_WFTriggerNotificationDebouncerItem._triggerIdentifier
- _OUTLINED_FUNCTION_215
- _OUTLINED_FUNCTION_216
- _OUTLINED_FUNCTION_217
- _OUTLINED_FUNCTION_218
- _OUTLINED_FUNCTION_219
- _OUTLINED_FUNCTION_220
- _OUTLINED_FUNCTION_221
- _OUTLINED_FUNCTION_222
- _OUTLINED_FUNCTION_223
- _OUTLINED_FUNCTION_224
- _OUTLINED_FUNCTION_225
- _OUTLINED_FUNCTION_226
- _OUTLINED_FUNCTION_227
- _OUTLINED_FUNCTION_228
- _OUTLINED_FUNCTION_229
- _OUTLINED_FUNCTION_230
- _OUTLINED_FUNCTION_231
- _OUTLINED_FUNCTION_232
- _OUTLINED_FUNCTION_233
- _OUTLINED_FUNCTION_234
- _OUTLINED_FUNCTION_235
- _OUTLINED_FUNCTION_236
- _OUTLINED_FUNCTION_237
- _OUTLINED_FUNCTION_238
- _OUTLINED_FUNCTION_239
- _OUTLINED_FUNCTION_240
- _OUTLINED_FUNCTION_241
- _OUTLINED_FUNCTION_242
- _OUTLINED_FUNCTION_243
- _VCXPCEventToolkitDatabaseChanged
- _WFDaemonTaskOutcomeCancelled
- _WFDaemonTaskOutcomeFailed
- _WFDaemonTaskOutcomeFinished
- _WFDaemonTaskOutcomeNotFound
- _WFDaemonTransactionBehaviorConcurrent
- _WFDaemonTransactionBehaviorSuspending
- _WFTriggerIDFromNotificationUserInfo
- _WFTriggerIDsToDisableFromNotificationUserInfo
- _WFTriggerIdentifierFromXPCActivityIdentifier
- _WFTriggerSystemNotificationIdentifierPrefix
- ___112-[WFTriggerNotificationDebouncer addEventsWithIdentifiers:notificationType:triggerIdentifier:workflowReference:]_block_invoke
- ___113-[WFTriggerEventQueue notificationManager:receivedConfirmationToRunTriggerWithIdentifier:pendingTriggerEventIDs:]_block_invoke
- ___113-[WFTriggerEventQueue notificationManager:receivedConfirmationToRunTriggerWithIdentifier:pendingTriggerEventIDs:]_block_invoke_2
- ___120-[WFTriggerEventQueue notificationManager:receivedContinuePotentialLoopForTriggerWithIdentifier:pendingTriggerEventIDs:]_block_invoke
- ___120-[WFTriggerEventQueue notificationManager:receivedContinuePotentialLoopForTriggerWithIdentifier:pendingTriggerEventIDs:]_block_invoke_2
- ___124-[WFTriggerUserNotificationManager postNotificationThatTriggerWithIdentifier:failedWithError:notificationRequestIdentifier:]_block_invoke
- ___127-[WFTriggerEventQueue notificationManager:didFailToPostActionRequiredNotificationWithTriggerIdentifier:pendingTriggerEventIDs:]_block_invoke
- ___169-[WFTriggerUserNotificationManager _postNotificationOfType:forTriggerIdentifier:workflowReference:removeDeliveredNotifications:pendingTriggerEventIDs:actionIcons:error:]_block_invoke
- ___66-[WFTriggerEventQueue unregisterDebounceForTriggerWithIdentifier:]_block_invoke
- ___70-[WFTriggerNotificationScheduler registerTriggerWithIdentifier:delay:]_block_invoke
- ___70-[WFTriggerNotificationScheduler registerTriggerWithIdentifier:delay:]_block_invoke_2
- ___72-[WFTriggerNotificationScheduler cancelActivitiesFromTriggerIdentifier:]_block_invoke
- ___73-[WFTriggerEventQueue registerDebounceDuration:forTriggerWithIdentifier:]_block_invoke
- ___77-[WFTriggerUserNotificationManager removeNotificationsWithTriggerIdentifier:]_block_invoke
- ___77-[WFTriggerUserNotificationManager removeNotificationsWithTriggerIdentifier:]_block_invoke_2
- ___79-[WFTriggerEventQueue enqueueTriggerWithIdentifier:eventInfo:force:completion:]_block_invoke
- ___80-[WFTriggerNotificationScheduler scheduleTriggerForNotificationsWithIdentifier:]_block_invoke
- ___87-[WFTriggerEventQueue runWithTriggerIdentifier:workflowReference:eventInfo:completion:]_block_invoke
- ___87-[WFTriggerEventRunner startRunningWorkflow:forTriggerIdentifier:eventInfo:completion:]_block_invoke
- ___90-[WFTriggerEventQueue notificationManager:didRequestDisablementOfTriggersWithIdentifiers:]_block_invoke
- ___93-[WFTriggerEventQueue notificationManager:receivedStopPotentialLoopForTriggerWithIdentifier:]_block_invoke
- ___96-[WFTriggerEventQueue didFinishRunningWithError:cancelled:triggerIdentifier:eventInfo:runEvent:]_block_invoke
- ___98-[WFTriggerEventQueue notificationManager:didDismissTriggerWithIdentifier:pendingTriggerEventIDs:]_block_invoke
- _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0A9Shortcuts014DaemonXPCEventG0AD0F0AD0iF6SourceP_Se
- _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0A9Shortcuts014DaemonXPCEventG0AD10DescriptorAdEP_AD0ifK0
- _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0A9Shortcuts06DaemonF6SourceAD0F0AdEP_AD0iF0
- _swift_getObjCClassFromObject
- _symbolic SDySS_____G 14VoiceShortcuts18WFTriggerRegistrarC19TriggerRegistrationV
- _symbolic SDySS_____G 14VoiceShortcuts18WFTriggerRegistrarC25LegacyTriggerRegistrationV
- _symbolic SS3key______5valuet 14VoiceShortcuts18WFTriggerRegistrarC19TriggerRegistrationV
- _symbolic SccySo19WFContentCollectionCSg_____G s5NeverO
- _symbolic So19WFConfiguredTriggerC
- _symbolic _____ 14VoiceShortcuts18WFTriggerRegistrarC25LegacyTriggerRegistrationV
- _symbolic _____ 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V
- _symbolic _____ So16WFTriggerBackingV
- _symbolic _____Iegn_ 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V
- _symbolic _____SbIegnd_ 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V
- _symbolic _____Sg 14VoiceShortcuts18WFTriggerRegistrarC25LegacyTriggerRegistrationV
- _symbolic __________Iegnr_ 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V 0A9Shortcuts06DaemonfG0V014DatabaseChangeF0V
- _symbolic __________Iegnr_ 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V 0A9Shortcuts06DaemonfG0V021ApplicationRegisteredF0V
- _symbolic __________Iegnr_ 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V 0A9Shortcuts06DaemonfG0V026ToolKitLocalDatabaseChangeF0V
- _symbolic __________Iegnr_ 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V 0A9Shortcuts06DaemonfG0V03Apph7ChangedF0V
- _symbolic ___________pIegHnzo_ 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V s5ErrorP
- _symbolic _____ySS_____G s17_NativeDictionaryV 14VoiceShortcuts18WFTriggerRegistrarC19TriggerRegistrationV
- _symbolic _____ySS_____G s18_DictionaryStorageC 14VoiceShortcuts18WFTriggerRegistrarC19TriggerRegistrationV
- _type_layout_string 14VoiceShortcuts18WFTriggerRegistrarC25LegacyTriggerRegistrationV
CStrings:
+ " (hasDeltaFromOther: "
+ " DUPLICATE shortcut IDs in previous: "
+ " DUPLICATE shortcut IDs in result: "
+ " REMOVED folders: "
+ " REMOVED shortcuts: "
+ " bytes; context: "
+ " bytes; remote: "
+ " folder diff: localOnly="
+ " shortcut diff: localOnly="
+ " versions: local=["
+ "%s ***WFWorkoutTrigger publisherWithScheduler reached. Candidate for deprecation"
+ "%s ***WFWorkoutTrigger registerContextSyncClient reached. Candidate for deprecation"
+ "%s ***WFWorkoutTrigger remotePublisherWithScheduler reached. Candidate for deprecation"
+ "%s ***WFWorkoutTrigger shouldFireInResponseToEvent reached. Candidate for deprecation"
+ "%s ***WFWorkoutTrigger unregisterContextSyncClient reached. Candidate for deprecation"
+ "%s An automation is already running (%@), so we can't run this newly-triggered one (%@) (%@)."
+ "%s App.InFocus: BundleID: %{public}@, isStarting: %d, launchReason: %{public}@"
+ "%s App.InFocus: Trigger firing. bundleID: %{public}@, isStarting: %d"
+ "%s App.InFocus: Trigger not firing - ignoring launch reason on focus: %{public}@"
+ "%s App.InFocus: Trigger not firing: ignoring launch reason on background: %{public}@"
+ "%s Failed to register workout for updates from context sync client with error: %@"
+ "%s Failed to unregister workout client with error: %@"
+ "%s Found remote workout event from ContextSync"
+ "%s Ignoring third-party workout event; not firing."
+ "%s Missing or invalid trigger key from notification reponse userInfo: %{public}@"
+ "%s No App.InFocus ezvent received for trigger; not firing."
+ "%s No workout event received for trigger; not firing."
+ "%s Received workout event for trigger. activityType: %@; eventType: %d; trigger onStart: %d, onEnd: %d"
+ "%s Successfully registered workout for updates with context sync client"
+ "%s Successfully unregistered workout from context sync client"
+ "+[WFWorkoutTrigger(BiomeContext) registerContextSyncClient]"
+ "+[WFWorkoutTrigger(BiomeContext) unregisterContextSyncClient]"
+ ", hasDeltaFromOriginal: "
+ "-[WFAppInFocusTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]"
+ "-[WFTriggerEventQueue didFinishRunningWithError:cancelled:triggerKey:eventInfo:runEvent:]"
+ "-[WFTriggerEventQueue enqueueTriggerWithKey:eventInfo:force:completion:]_block_invoke"
+ "-[WFTriggerEventQueue enqueueTriggerWithKey:eventInfo:force:completion:]_block_invoke_2"
+ "-[WFTriggerEventQueue notificationManager:didDismissTriggerWithKey:pendingTriggerEventIDs:]"
+ "-[WFTriggerEventQueue notificationManager:didFailToPostActionRequiredNotificationWithTriggerKey:pendingTriggerEventIDs:]"
+ "-[WFTriggerEventQueue notificationManager:didRequestDisablementOfTriggersWithKeys:]"
+ "-[WFTriggerEventQueue notificationManager:receivedConfirmationToRunTriggerWithKey:pendingTriggerEventIDs:]"
+ "-[WFTriggerEventQueue notificationManager:receivedConfirmationToRunTriggerWithKey:pendingTriggerEventIDs:]_block_invoke"
+ "-[WFTriggerEventQueue notificationManager:receivedConfirmationToRunTriggerWithKey:pendingTriggerEventIDs:]_block_invoke_2"
+ "-[WFTriggerEventQueue notificationManager:receivedContinuePotentialLoopForTriggerWithKey:pendingTriggerEventIDs:]"
+ "-[WFTriggerEventQueue notificationManager:receivedContinuePotentialLoopForTriggerWithKey:pendingTriggerEventIDs:]_block_invoke_2"
+ "-[WFTriggerEventQueue notificationManager:receivedStopPotentialLoopForTriggerWithKey:]"
+ "-[WFTriggerEventQueue notificationManager:receivedStopPotentialLoopForTriggerWithKey:]_block_invoke"
+ "-[WFTriggerEventQueue resumeWithTriggerKey:workflowReference:eventInfo:completion:]"
+ "-[WFTriggerEventQueue runWithTriggerKey:workflowReference:eventInfo:completion:]"
+ "-[WFTriggerEventQueue shouldRunTriggerWithKey:shouldPrompt:forEvent:runEvents:error:]"
+ "-[WFTriggerEventRunner logPowerLogEventForTriggerKey:workflowReference:]"
+ "-[WFTriggerEventRunner startRunningWorkflow:forTriggerKey:eventInfo:completion:]"
+ "-[WFTriggerNotificationDebouncer addEventsWithIdentifiers:notificationType:triggerKey:workflowReference:]_block_invoke"
+ "-[WFTriggerNotificationScheduler cancelActivitiesFromTriggerKey:]_block_invoke"
+ "-[WFTriggerNotificationScheduler initialRunDateForTriggerKey:]"
+ "-[WFTriggerNotificationScheduler postBackgroundRunningNotificationForTriggerKey:]"
+ "-[WFTriggerNotificationScheduler registerTriggerWithKey:delay:]"
+ "-[WFTriggerNotificationScheduler registerTriggerWithKey:delay:]_block_invoke"
+ "-[WFTriggerNotificationScheduler registerTriggerWithKey:delay:]_block_invoke_2"
+ "-[WFTriggerNotificationScheduler scheduleTriggerForNotificationsWithKey:]_block_invoke"
+ "-[WFTriggerNotificationScheduler updateTriggerNotificationLevelsForKeys:]"
+ "-[WFTriggerUserNotificationManager _postNotificationOfType:forTriggerKey:workflowReference:removeDeliveredNotifications:pendingTriggerEventIDs:actionIcons:error:]"
+ "-[WFTriggerUserNotificationManager _postNotificationOfType:forTriggerKey:workflowReference:removeDeliveredNotifications:pendingTriggerEventIDs:actionIcons:error:]_block_invoke"
+ "-[WFTriggerUserNotificationManager postActionRequiredNotificationForTriggerKey:notificationType:workflowReference:pendingTriggerEventIDs:]"
+ "-[WFTriggerUserNotificationManager postNotificationThatTriggerWithKey:failedWithError:notificationRequestIdentifier:]"
+ "-[WFTriggerUserNotificationManager postNotificationThatTriggerWithKey:failedWithError:notificationRequestIdentifier:]_block_invoke"
+ "-[WFWorkoutTrigger(BiomeContext) publisherWithScheduler:]"
+ "-[WFWorkoutTrigger(BiomeContext) remotePublisherWithScheduler:]"
+ "-[WFWorkoutTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]"
+ "/System/Library/Frameworks/HealthKit.framework/HealthKit"
+ "<%@: %p, triggerKey: %@, reference: %@, triggerEventIDs: %@, debouncer: %@>"
+ "Couldn't find workflow for trigger with identifier: %@"
+ "Enqueuing workflow for trigger %s %@"
+ "Failed to enqueue trigger %s %@: %@"
+ "Failed to register trigger: (key: %@) - %@"
+ "Failed to unregister trigger: (key: %@): %@"
+ "Library merge FAILED: "
+ "Library reconcile FAILED: "
+ "Re-registering trigger after firing (key: %@)"
+ "Registering trigger: (type: %s, key: %@)"
+ "SBFullScreenSwitcherSceneLiveContentOverlay"
+ "Toggle WLAN"
+ "Unregistering trigger: (type: %s, key: %@)"
+ "XPCDistributedNotificationStreamEvent"
+ "_HKWorkoutActivityNameForActivityType"
+ "com.apple.SpringBoard.backlight.transitionReason.idleTimer"
+ "com.apple.SpringBoard.backlight.transitionReason.lockButton"
+ "com.apple.siriactionsd.TriggerNotification.%@.%@"
+ "com.apple.toolkit.request-immediate-indexing.allow"
+ "held stored value pending MCV: "
+ "manifest compaction is required"
+ "manifest exceeds ceiling for stored value "
+ "nil"
+ "packing inline items cannot keep this record under CK's size limit; "
+ "staged stored value: "
- "%@%@:"
- "%@%@:%@"
- "%s An automation is already running (%@), so we can't run this newly-triggered one (%@)."
- "%s Failed to fire trigger because missing workflow identifier for trigger: %{public}@"
- "%s Missing or invalid triggerID from notification reponse userInfo: %{public}@"
- "-[WFTriggerEventQueue didFinishRunningWithError:cancelled:triggerIdentifier:eventInfo:runEvent:]"
- "-[WFTriggerEventQueue enqueueTriggerWithIdentifier:eventInfo:force:completion:]_block_invoke"
- "-[WFTriggerEventQueue enqueueTriggerWithIdentifier:eventInfo:force:completion:]_block_invoke_2"
- "-[WFTriggerEventQueue notificationManager:didDismissTriggerWithIdentifier:pendingTriggerEventIDs:]"
- "-[WFTriggerEventQueue notificationManager:didFailToPostActionRequiredNotificationWithTriggerIdentifier:pendingTriggerEventIDs:]"
- "-[WFTriggerEventQueue notificationManager:didRequestDisablementOfTriggersWithIdentifiers:]"
- "-[WFTriggerEventQueue notificationManager:receivedConfirmationToRunTriggerWithIdentifier:pendingTriggerEventIDs:]"
- "-[WFTriggerEventQueue notificationManager:receivedConfirmationToRunTriggerWithIdentifier:pendingTriggerEventIDs:]_block_invoke"
- "-[WFTriggerEventQueue notificationManager:receivedConfirmationToRunTriggerWithIdentifier:pendingTriggerEventIDs:]_block_invoke_2"
- "-[WFTriggerEventQueue notificationManager:receivedContinuePotentialLoopForTriggerWithIdentifier:pendingTriggerEventIDs:]"
- "-[WFTriggerEventQueue notificationManager:receivedContinuePotentialLoopForTriggerWithIdentifier:pendingTriggerEventIDs:]_block_invoke_2"
- "-[WFTriggerEventQueue notificationManager:receivedStopPotentialLoopForTriggerWithIdentifier:]"
- "-[WFTriggerEventQueue notificationManager:receivedStopPotentialLoopForTriggerWithIdentifier:]_block_invoke"
- "-[WFTriggerEventQueue resumeWithTriggerIdentifier:workflowReference:eventInfo:completion:]"
- "-[WFTriggerEventQueue runWithTriggerIdentifier:workflowReference:eventInfo:completion:]"
- "-[WFTriggerEventQueue shouldRunTriggerWithIdentifier:shouldPrompt:forEvent:runEvents:error:]"
- "-[WFTriggerEventRunner logPowerLogEventForTriggerIdentifier:workflowReference:]"
- "-[WFTriggerEventRunner startRunningWorkflow:forTriggerIdentifier:eventInfo:completion:]"
- "-[WFTriggerNotificationDebouncer addEventsWithIdentifiers:notificationType:triggerIdentifier:workflowReference:]_block_invoke"
- "-[WFTriggerNotificationScheduler cancelActivitiesFromTriggerIdentifier:]_block_invoke"
- "-[WFTriggerNotificationScheduler initialRunDateForTriggerIdentifier:]"
- "-[WFTriggerNotificationScheduler postBackgroundRunningNotificationForTriggerIdentifier:]"
- "-[WFTriggerNotificationScheduler registerTriggerWithIdentifier:delay:]"
- "-[WFTriggerNotificationScheduler registerTriggerWithIdentifier:delay:]_block_invoke"
- "-[WFTriggerNotificationScheduler registerTriggerWithIdentifier:delay:]_block_invoke_2"
- "-[WFTriggerNotificationScheduler scheduleTriggerForNotificationsWithIdentifier:]_block_invoke"
- "-[WFTriggerNotificationScheduler updateTriggerNotificationLevelsForIdentifiers:]"
- "-[WFTriggerUserNotificationManager _postNotificationOfType:forTriggerIdentifier:workflowReference:removeDeliveredNotifications:pendingTriggerEventIDs:actionIcons:error:]"
- "-[WFTriggerUserNotificationManager _postNotificationOfType:forTriggerIdentifier:workflowReference:removeDeliveredNotifications:pendingTriggerEventIDs:actionIcons:error:]_block_invoke"
- "-[WFTriggerUserNotificationManager postActionRequiredNotificationForTriggerIdentifier:notificationType:workflowReference:pendingTriggerEventIDs:]"
- "-[WFTriggerUserNotificationManager postNotificationThatTriggerWithIdentifier:failedWithError:notificationRequestIdentifier:]"
- "-[WFTriggerUserNotificationManager postNotificationThatTriggerWithIdentifier:failedWithError:notificationRequestIdentifier:]_block_invoke"
- "<%@: %p, triggerIdentifier: %@, reference: %@, triggerEventIDs: %@, debouncer: %@>"
- "Couldn't find workflow (%@) for trigger with identifier: %@"
- "Enqueuing workflow %s for trigger %s %s"
- "Failed to enqueue trigger %s %s: %@"
- "Failed to register trigger: (uuid: %s) - %@"
- "Failed to unregister trigger: (uuid: %s): %@"
- "Missing workflow identifier for trigger with identifier: %@"
- "Re-registering trigger after firing (uuid: %s)"
- "Registering trigger: (id: %s, uuid: %s, workflowID: %s)"
- "TKToolkitDatabaseChangedNotification"
- "Unregistering trigger: (id: %s, uuid: %s, workflowID: %s)"
- "com.apple.siriactionsd.TriggerNotification.%@"
- "triggerIdentifier"
```
