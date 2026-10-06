## CarouselPreferenceServices

> `/System/Library/PrivateFrameworks/CarouselPreferenceServices.framework/CarouselPreferenceServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x287bc` | `0x286dc` | **`-0xe0`** |

### Other Changes

```diff

-1115.0.87.0.0
+1115.0.93.0.0
Functions:
~ -[CSLPRFLocalApplicationLibrary allApplicationsDictionary] : 524 -> 520
~ -[CSLPRFLocalApplicationLibrary applicationsDidInstall:] : 1192 -> 1188
~ -[CSLPRFLocalApplicationLibrary _applicationsUninstalledWithRecords:] : 672 -> 668
~ -[CSLPRFStingQuickSwitchModel lock_restoreFromSettings] : 796 -> 792
~ -[CSLPRFStingQuickSwitchModel existingItemForActionType:] : 360 -> 356
~ -[CSLPRFStingQuickSwitchModel availableQuickSwitchActions] : 384 -> 380
~ -[CSLPRFStingQuickSwitchModel quickSwitchItemDidChange:] : 568 -> 564
~ -[CSLPRFObservationHelper notifyObserversWithBlock:] : 308 -> 304
~ ___CSLIdentifierToLinkActionType_block_invoke : 256 -> 264
~ ___CSLPRFIdentifierToStingAccessibilityActionType_block_invoke : 220 -> 216
~ -[CSLPRFAppConduitApplicationLibrary applicationsInstalled:onDeviceWithPairingID:] : 508 -> 504
~ -[CSLPRFAppConduitApplicationLibrary applicationsUpdated:onDeviceWithPairingID:] : 508 -> 504
~ -[CSLPRFAppConduitApplicationLibrary applicationsUninstalled:onDeviceWithPairingID:] : 440 -> 436
~ ___54-[CSLPRFCompositeApplicationLibrary _loadApplications]_block_invoke_2 : 856 -> 852
~ -[CSLPRFCompositeApplicationLibrary _applicationLibrary:didAddOrUpdateApplications:] : 1904 -> 1892
~ -[CSLPRFCompositeApplicationLibrary applicationLibrary:didRemoveApplications:] : 2084 -> 2072
~ -[CSLPRFCompositeApplicationLibrary _applicationOrCounterpartsForApplication:inApplications:orApplicationsByCounterpart:] : 608 -> 604
~ ___95-[CSLPRFCompositeApplicationLibrary _notifyObserversOfChangesWithApplications:oldApplications:]_block_invoke : 152 -> 148
~ ___80-[CSLPRFCompositeApplicationLibrary _applicationsByCounterpartFromApplications:]_block_invoke : 272 -> 268
~ -[CSLPRFConcurrentObserverStore enumerateObserversWithBlock:] : 492 -> 488
~ -[CSLPRFIconFetcher _completeLoadForBundleID:image:error:] : 352 -> 348
~ -[CSLPRFApp supportsSmartStack] : 664 -> 660
~ -[CSLPRFStingConfigurationHistoryData hash] : 460 -> 456
~ -[CSLPRFStingSettingsModelData hash] : 1100 -> 1076
~ ___44-[CSLPRFStingSettingsModel quickActionItems]_block_invoke : 332 -> 328
~ ___74-[CSLPRFStingSettingsModel _buildActionIdentifierToSupportedBundleIDsMap:]_block_invoke : 540 -> 536
~ -[CSLPRFLegacyWatchApplicationLibrary nanoRegistrySource:updatedWithAllApplications:] : 1364 -> 1356
~ -[CSLPRFLegacyWatchApplicationLibrary applicationsInstalled:onDeviceWithPairingID:] : 496 -> 492
~ -[CSLPRFLegacyWatchApplicationLibrary applicationsUpdated:onDeviceWithPairingID:] : 496 -> 492
~ -[CSLPRFLegacyWatchApplicationLibrary applicationsUninstalled:onDeviceWithPairingID:] : 428 -> 424
~ ___108-[CSLPRFLegacyWatchApplicationLibrary _withFirstPartyApplications:loadAppConduitApplicationsWithCompletion:]_block_invoke : 684 -> 680
~ -[CSLPRFPerApplicationSettingsModel _processAddedOrUpdatedApplications:] : 1144 -> 1136
~ -[CSLPRFPerApplicationSettingsModel applicationLibrary:didRemoveApplications:] : 376 -> 372
~ -[CSLPRFPerApplicationSettingsModel twoWaySyncSettingDidUpdate:] : 1156 -> 1148
~ -[CSLPRFStingConfigurationHistory addHistoryItem:] : 1412 -> 1408
~ -[CSLPRFStingConfigurationHistory itemForActionType:] : 4708 -> 4696
~ -[CSLPRFStingConfigurationHistory itemForWorkoutWithBundleID:] : 572 -> 568
~ -[CSLPRFStingConfigurationHistory _itemForActionType:withBundleID:] : 464 -> 460
~ -[CSLPRFStingConfigurationHistory _historyItemForActionType:] : 1180 -> 1176
~ -[CSLPRFBulletinBoardApplicationLibrary _loadApplications] : 840 -> 836
~ ___58-[CSLPRFBulletinBoardApplicationLibrary _loadApplications]_block_invoke : 856 -> 852
~ ___99-[CSLPRFBulletinBoardApplicationLibrary _notifyObserversOfChangesWithApplications:oldApplications:]_block_invoke : 152 -> 148
~ -[CSLPRFAppIconCellHelper didCompleteLoadForIdentifier:] : 384 -> 380
~ -[CSLPRFAppViewChoiceView setHorizontalOffset:] : 296 -> 292
~ ___55+[CSLPRFLiveActivitiesAppSettings _stateDataWithHints:]_block_invoke_2 : 428 -> 424
```
