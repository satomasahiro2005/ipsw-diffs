## SOS

> `/System/Library/PrivateFrameworks/SOS.framework/SOS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35688` | `0x355fc` | **`-0x8c`** |
| `__TEXT.__gcc_except_tab` | `0x83c` | `0x85c` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x63b2` | `0x63b8` | **`+0x6`** |

### Other Changes

```diff

-666.100.3.0.0
+668.100.1.0.0
Functions:
~ -[SOSEngine _checkEmergencyCallStatus] : 412 -> 408
~ -[SOSEngine _checkSOSCallStatus] : 420 -> 416
~ +[SOSRecipient handlesFromRecipients:] : 396 -> 392
~ +[SOSRecipient reasonsDictionaryFromRecipients:] : 452 -> 448
~ ___42-[SOSContactsManager SOSContactRecipients]_block_invoke : 1536 -> 1528
~ -[SOSContactsManager _sosRecipientContainingPhoneNumber:inRecipients:] : 356 -> 352
~ ___64-[SOSContactsManager _medicalIDEmergencyContactsWithCompletion:]_block_invoke : 616 -> 612
~ -[SOSContactsManager _updateWithSafetyMonitorHandles:] : 508 -> 504
~ -[SOSLegacyContactsManager SOSLegacyContacts] : 564 -> 560
~ -[SOSLegacyContactsManager SOSLegacyContactsDestinations] : 324 -> 320
~ -[SOSLegacyContactsManager _SOSFormattedDestinationForFriend:withDestinationNumber:] : 460 -> 456
~ +[SOSUtilities hasActiveSIMForClient:] : 1092 -> 1088
~ +[SOSUtilities getKappaThirdPartyActiveAppBundle] : 560 -> 556
~ ___33+[SOSUtilities sosLocationBundle]_block_invoke : 392 -> 388
~ -[SOSAnalyticsEventAccumulator analyticsDataDictForAccumulatedKeys:outputKeyPrefix:summaryKeysDict:] : 496 -> 492
~ -[SOSFlow updateState:] : 512 -> 508
~ -[SOSFlow willHandleEvent:withMetaData:] : 400 -> 396
~ -[SOSEngine SOSSendingLocationUpdateChanged:] : 384 -> 380
~ -[SOSEngine dismissSOSWithCompletion:] : 700 -> 696
~ -[SOSEngine didDismissSOSBeforeSOSCall:] : 364 -> 360
~ -[SOSEngine broadcastUpdatedSOSStatus:] : 472 -> 468
~ -[SOSEngine applicationsDidUninstall:] : 392 -> 388
~ -[SOSCoordinator sendUpdateToObserversWithStatus:progression:shouldHandleThirdParty:] : 304 -> 300
~ -[SOSCoordinator effectivePairedDevice] : 300 -> 296
~ -[VLAR_DTMFCommandsAccumulator analyticsDataDict] : 904 -> 900
~ -[SOSVoiceLoopAnalyticsReporter reportVoiceLoopSupportsDTMF:] : 428 -> 424
~ -[SOSEmergencyCallVoiceLoopManager _preferredVoiceLanguageForCountryCode:] : 1048 -> 1044
~ +[SOSEmergencyCallVoiceLoopManager _activeCallPreferringEmergencyOrSOS] : 456 -> 452
~ -[SOSVoiceUtterer speakUtterances:] : 548 -> 544
~ -[SOSKappaManager updateObserversWithKappaStatus:] : 432 -> 428
~ -[NSURL(SOS) sos_urlActivationReason] : 424 -> 420
~ +[NSString(NSString_StringWithPositionalSpecifiersFormat) stringWithPositionalSpecifiersFormat:arguments:] : 648 -> 644
~ -[SOSManager updateClientCurrentSOSInitiationState:] : 516 -> 512
~ -[SOSManager didDismissClientSOSBeforeSOSCall:] : 400 -> 396
CStrings:
+ "Attempting to update current sos initiation state to %ld for %lu connection(s)"
+ "Attempting to update current sos interactive state to %ld for %lu connection(s)"
+ "SOSEngine,attempting to update current sos button press state to %@ for %lu connection(s)"
- "Attempting to update current sos initiation state to %ld for connections: %@"
- "Attempting to update current sos interactive state to %ld for connections: %@"
- "SOSEngine,attempting to update current sos button press state to %@ for connections: %@"
```
