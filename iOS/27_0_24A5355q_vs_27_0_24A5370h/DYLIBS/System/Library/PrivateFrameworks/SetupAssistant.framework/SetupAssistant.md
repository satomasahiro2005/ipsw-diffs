## SetupAssistant

> `/System/Library/PrivateFrameworks/SetupAssistant.framework/SetupAssistant`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x444c4` | `0x443fc` | **`-0xc8`** |

### Other Changes

```diff

-5403.100.0.0.0
+5405.0.0.0.0
Functions:
~ -[BYLocaleDataSource reloadData] : 1332 -> 1328
~ -[BYManagedAppleIDBootstrap ingestManagedBuddyData] : 1536 -> 1532
~ -[BYTestingSurrogateBehaviorManager _setNamedBehaviorsFromDictionary:forDomain:] : 388 -> 384
~ -[BYGreenController _writeFilesWithPlist:desiredPlistState:] : 556 -> 552
~ -[BYPreferencesController persistKeys:] : 292 -> 288
~ ___34-[BYPreferencesController persist]_block_invoke : 396 -> 392
~ -[BYChronicle initFromBackedUpPreferences:andNotBackedUpPreferences:includeCache:] : 664 -> 660
~ -[BYChronicle _dictionaryRepresentationForBackedUpFeatures:] : 580 -> 576
~ -[BYFlowSkipController _pendingFollowUpItem] : 432 -> 428
~ -[BYFlowSkipController revisePendingFollowUpsForcingRepost:] : 1440 -> 1436
~ +[BYFlowSkipController _localizedStringListingFlowSkipIdentifiers:] : 444 -> 440
~ -[BYAppleIDAccountsManager enableDataClassesForAccount:completion:] : 2876 -> 2868
~ ___33-[BYDeviceMigrationManager start]_block_invoke.4 : 436 -> 432
~ ___33-[BYDeviceMigrationManager start]_block_invoke.6 : 520 -> 516
~ ___33-[BYDeviceMigrationManager start]_block_invoke_2 : 464 -> 460
~ -[BYSIMRegionService cellularNetworkInformation] : 1136 -> 1132
~ -[BFFSettingsManager populatePathsToStash] : 1384 -> 1380
~ -[BFFSettingsManager _stashPaths] : 1948 -> 1940
~ -[BFFSettingsManager _applyStashedPreferences] : 600 -> 596
~ -[BFFSettingsManager _applyStashedManagedConfiguration] : 640 -> 636
~ -[BFFSettingsManager _applyStashedFlowSkipIdentifiers] : 472 -> 468
~ -[BFFSettingsManager _restoreAnalyticsData] : 488 -> 484
~ -[BFFSettingsManager _shovePath:toPath:] : 3844 -> 3840
~ -[BYLocationController _checkForAliasesOrInvalid:] : 744 -> 736
~ ___43-[BYLocationController getCountryFromNVRAM]_block_invoke : 312 -> 308
~ -[BYLocationController guessedLanguages] : 1060 -> 1052
~ -[BYLocationController _languagesForRegionsUsingSIMRegionService:] : 1296 -> 1288
~ -[BYLocationController _subregionLanguagesForRegion:subregionsCodes:] : 712 -> 708
~ -[BYLocationController _scanComplete:error:] : 1296 -> 1284
~ -[BYNetworkMonitor setCurrentNetworkType:] : 528 -> 524
~ ___42-[BYNetworkMonitor setCurrentNetworkType:]_block_invoke : 500 -> 496
~ -[BYSetupStateNotifier _stateChangedTo:] : 772 -> 764
~ -[BYSetupStateNotifier _noLongerExclusiveNotificationFired] : 644 -> 636
~ -[BYSetupStateNotifier _shouldRemainAliveNotificationFired] : 488 -> 484
~ -[BYAnalyticsManager removeEventsUsingBlock:] : 408 -> 404
~ -[BYAnalyticsManager stash:] : 676 -> 672
~ -[BYAnalyticsManager commit] : 1048 -> 1040
~ -[BYAnalyticsManager removeNonPersistentEvents] : 720 -> 712
~ -[BYAnalyticsManager _gatherDataFromProducers] : 740 -> 736
```
