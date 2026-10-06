## ToneLibrary

> `/System/Library/PrivateFrameworks/ToneLibrary.framework/ToneLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x49f48` | `0x49dfc` | **`-0x14c`** |
| `__DATA_CONST.__const` | `0x1950` | `0x1998` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x380` | `0x3a0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1370` | `0x1354` | **`-0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x22d8` | `0x22e0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x12f8` | `0x1300` | **`+0x8`** |

### Other Changes

```diff

-670.1.0.0.0
+671.0.0.0.0

-  Symbols:   2637
+  Symbols:   2639
Symbols:
+ ___block_descriptor_32_e17_v16?0"NSError"8l
+ ___block_descriptor_40_e8_32r_e34_v24?0"NSDictionary"8"NSError"16lr32l8
Functions:
~ _TLAlertTargetDeviceFromString : 104 -> 100
~ -[TLToneManager _loadITunesRingtoneInfoPlistAtPath:] : 920 -> 916
~ -[TLToneManager _tonesFromManifestPath:mediaDirectoryPath:] : 1520 -> 1512
~ -[TLToneManager _installedTonesSize] : 552 -> 548
~ -[TLToneManager _addToneEntries:toManifestAtPath:mediaDirectory:shouldSkipReload:] : 2664 -> 2656
~ -[TLToneManager _removeTonesFromManifestAtPath:fileNames:shouldSkipReload:alreadyLockedManifest:removedEntries:] : 768 -> 764
~ ___32-[TLToneManager _removeAllTones]_block_invoke : 1120 -> 1112
~ -[TLToneManager _loadSystemTones] : 2752 -> 2772
~ -[TLToneManager _tonePreferencesFromService] : 636 -> 508
~ ___44-[TLToneManager _tonePreferencesFromService]_block_invoke_2 : 104 -> 84
~ ___44-[TLToneManager _tonePreferencesFromService]_block_invoke.788 -> ___44-[TLToneManager _tonePreferencesFromService]_block_invoke.790 : 156 -> 148
~ ___43-[TLToneManager toneWithIdentifierIsValid:]_block_invoke : 392 -> 388
~ -[TLToneManager _removeAllSyncedData] : 808 -> 804
~ -[TLToneManager _removeOrphanedPlistEntriesInManifestAtPath:mediaDirectory:] : 584 -> 580
~ -[TLAttentionAwarenessEffectCoordinator audioMixForAsset:] : 1036 -> 1032
~ -[TLAttentionAwarenessEffectCoordinator setEffectMix:] : 356 -> 352
~ -[TLAttentionAwarenessEffectCoordinator setEffectMix:effectMixFadeDuration:completion:] : 400 -> 396
~ -[TLAttentionAwarenessEffectCoordinator _processAudioWithEffectAudioTapContext:bufferList:numberOfFramesRequested:numberOfFramesToProcess:] : 432 -> 440
~ +[TLPreferencesUtilities _existingPerTopicPreferenceKeyPrefixesWithRegularPreferenceKeys:regularPreferenceKeysCount:] : 148 -> 156
~ ___114+[TLPreferencesUtilities _enumerateKeysAndValuesWithEligibleKeyPrefixes:inDomain:usingPreferencesScope:withBlock:]_block_invoke : 408 -> 404
~ ___85+[TLVibrationPersistenceUtilities _objectIsValidUserGeneratedVibrationPattern:error:]_block_invoke : 892 -> 888
~ ___95+[TLVibrationPersistenceUtilities objectIsValidUserGeneratedVibrationPatternsDictionary:error:]_block_invoke : 888 -> 884
~ _TLAlertPlaybackCompletionTypeFromString : 88 -> 96
~ ___88-[TLToneStoreDownloadStoreServicesController _notifyObserversOfUpdatedStoreAccountName:]_block_invoke : 292 -> 288
~ ___121-[TLToneStoreDownloadStoreServicesController _notifyObserversOfCheckingForDownloadsFinishedWithoutNeedToIssueAnyDownload]_block_invoke : 280 -> 276
~ ___145-[TLToneStoreDownloadStoreServicesController _notifyObserversOfStartedToneStoreDownloads:progressedToneStoreDownload:finishedToneStoreDownloads:]_block_invoke : 436 -> 432
~ ___86-[TLToneStoreDownloadStoreServicesController downloadManager:downloadStatesDidChange:]_block_invoke : 1168 -> 1164
~ -[TLToneStoreDownloadStoreServicesController purchaseManager:didFinishPurchasesWithResponses:] : 2784 -> 2780
~ ___94-[TLToneStoreDownloadStoreServicesController _handleToneManagerContentsDidChangeNotification:]_block_invoke_2 : 400 -> 396
~ _TLAlertTypeFromString : 92 -> 88
~ ___65-[TLVibrationManager _systemVibrationIdentifiersForSubdirectory:]_block_invoke : 996 -> 988
~ -[TLVibrationManager _migrateLegacySettings] : 448 -> 452
~ +[TLVibrationPattern isValidVibrationPatternPropertyListRepresentation:] : 804 -> 800
~ -[TLAlertSystemSoundController dealloc] : 544 -> 540
~ -[TLAlertSystemSoundController _processPlayTaskDescriptors:] : 1688 -> 1680
~ ___60-[TLAlertSystemSoundController _processPlayTaskDescriptors:]_block_invoke.9 : 416 -> 412
~ ___60-[TLAlertSystemSoundController _processPlayTaskDescriptors:]_block_invoke_2 : 332 -> 328
~ -[TLAlertSystemSoundController _prepareForStoppingAlerts:withOptions:playbackCompletionType:] : 1356 -> 1352
~ -[TLAlertSystemSoundController _processStopTasksDescriptor:] : 624 -> 612
~ -[TLAlertSystemSoundController _prepareForPreemptingAlertsBeforeBeginningPlaybackOfAlert:withSound:playbackCompletionType:] : 636 -> 632
~ ___67-[TLAlertSystemSoundController _processPlaybackCompletionContexts:]_block_invoke : 468 -> 464
~ -[TLAlertSystemSoundController backlightStatusDidChange:] : 1492 -> 1484
~ -[TLAlertQueuePlayerAnalyticsRecorder _updateWithDisplayLayout:] : 472 -> 468
~ -[AVPlayerItem(TLExtensions) tl_hapticTracks] : 740 -> 736
~ ___82-[TLAttentionAwarenessObserver _invokePollingForAttentionEventHandlers:eventType:]_block_invoke : 256 -> 252
~ ___66-[TLContentProtectionStateObserver _updateUnlockedSinceBootStatus]_block_invoke : 248 -> 244
~ _TLToneImportStatusCodeFromString : 92 -> 88
~ -[TLBacklight _notifyObservers:ofUpdatedBacklightStatus:] : 312 -> 308
~ _TLAlertOverridePolicyFromString : 104 -> 100
~ _TLWatchAlertPolicyFromString : 92 -> 88
~ -[TLAlertController _stopPlayingAlerts:withOptions:playbackCompletionType:] : 928 -> 920
~ -[TLAlertController _stopAllAlertsInCurrentProcessWithUserInterruptionDate:] : 816 -> 812
~ -[TLAlertQueuePlayerController stopPlayingAlerts:withOptions:playbackCompletionType:] : 1316 -> 1312
~ -[TLAlertQueuePlayerController _canPlayToneAsset:] : 1140 -> 1136
~ -[TLAlertQueuePlayerController _enableAttenuatedHapticTrack:] : 840 -> 836
```
