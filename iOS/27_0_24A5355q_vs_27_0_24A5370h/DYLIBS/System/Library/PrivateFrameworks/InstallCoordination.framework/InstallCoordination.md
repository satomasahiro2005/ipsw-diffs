## InstallCoordination

> `/System/Library/PrivateFrameworks/InstallCoordination.framework/InstallCoordination`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6c938` | `0x6c874` | **`-0xc4`** |
| `__AUTH_CONST.__cfstring` | `0x6220` | `0x6240` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1e90` | `0x1e98` | **`+0x8`** |
| `__TEXT.__cstring` | `0x102b8` | `0x102c0` | **`+0x8`** |

### Other Changes

```diff

-834.0.0.0.1
+837.0.0.0.0

-  CStrings:  1896
+  CStrings:  1897
Functions:
~ __GetRemovabilityData : 1520 -> 1516
~ __EnumerateAndCheckClass : 272 -> 268
~ _IXFilterArrayForClass : 376 -> 372
~ -[IXFileManager destinationOfSymbolicLinkAtURL:error:] : 360 -> 356
~ -[IXFileManager _validateSymlink:withStartingDepth:andEndingDepth:] : 452 -> 448
~ ___179+[IXAppInstallCoordinator _coordinatorForAppWithIdentity:targetingInstallationDomain:withClientID:intent:createIfNotExisting:requireMatchingIntent:scopeRequirement:created:error:]_block_invoke.24 : 372 -> 368
~ +[IXAppInstallCoordinator _synchronouslyEnumerateCoordinatorsForIntent:error:usingBlock:] : 2252 -> 2248
~ ___89+[IXAppInstallCoordinator _synchronouslyEnumerateCoordinatorsForIntent:error:usingBlock:]_block_invoke.71 : 128 -> 124
~ ___82+[IXAppInstallCoordinator revertAppWithIdentity:resultingApplicationRecord:error:]_block_invoke.109 : 128 -> 124
~ ___65+[IXAppInstallCoordinator removabilityDataWithChangeClock:error:]_block_invoke.117 : 176 -> 172
~ ___66+[IXAppInstallCoordinator defaultAppMetadataForAppIdentity:error:]_block_invoke.119 : 128 -> 124
~ ___59+[IXAppInstallCoordinator defaultAppMetadataListWithError:]_block_invoke.121 : 128 -> 124
~ ___51-[IXAppInstallCoordinator installOptionsWithError:]_block_invoke.218 : 128 -> 124
~ -[IXAppInstallCoordinator setInitialODRAssetPromises:error:] : 840 -> 836
~ -[IXAppInstallCoordinator initialODRAssetPromisesWithError:] : 1440 -> 1436
~ -[IXAppInstallCoordinator setEssentialAssetPromises:error:] : 856 -> 852
~ -[IXAppInstallCoordinator essentialAssetPromisesWithError:] : 1440 -> 1436
~ -[IXAppInstallCoordinator setDataImportPromises:error:] : 856 -> 852
~ -[IXAppInstallCoordinator dataImportPromisesWithError:] : 1440 -> 1436
~ ___72+[IXAppInstallCoordinator(IXTesting) fetchDuplicatedClassInfoWithError:]_block_invoke.706 : 128 -> 124
~ _IXCopyDuplicatedClassInfo : 884 -> 880
~ -[IXAppInstallObserver _oncePerBootUniqueIdentifierForServiceName:] : 312 -> 320
~ __SelectorsRespondedToByDelegate : 380 -> 392
~ -[IXLSApplicationRecordEnumerator _enumerateApplicationRecordsOnModuleAtURL:enumeratorBlock:error:] : 488 -> 484
~ __GatherBundleIDsFromSetOfBundles : 736 -> 732
~ _IXApplicationRecordForRecordPromise : 1192 -> 1188
~ +[IXPlaceholder _iconDataForBundle:atURL:isFromSerializedPlaceholder:error:] : 2520 -> 2516
~ +[IXPlaceholder _infoPlistLocalizationDictionaryForBundleURL:error:] : 892 -> 888
~ +[IXPlaceholder _placeholderForInstallable:client:installType:metadata:isFromSerializedPlaceholder:location:error:] : 1756 -> 1752
~ +[IXPlaceholder _placeholderForBundle:client:withParent:installType:metadata:placeholderType:mayBeDeltaPackage:isFromSerializedPlaceholder:location:error:] : 8108 -> 7980
~ -[IXPlaceholder setAppExtensionPlaceholderPromises:error:] : 1156 -> 1152
~ -[IXPlaceholder appExtensionPlaceholderPromisesWithError:] : 1244 -> 1240
~ -[NSString(InstallCoordinationAdditions) containsDotDotPathComponents] : 280 -> 276
~ -[IXPlaceholderAttributes initWithInfoPlistDictionary:] : 2612 -> 2608
~ -[IXPlaceholderAttributes setRequiredDeviceCapabilitiesWithArray:] : 412 -> 408
~ _IXAppURLFromExtractedPayloadDir : 588 -> 584
~ -[IXServerConnection _onQueue_scanForAndRemoveEmptyHashTables] : 812 -> 804
~ ___75-[IXServerConnection _client_coordinatorDidRegisterForObservationWithUUID:]_block_invoke : 296 -> 292
~ ___66-[IXServerConnection _client_coordinatorShouldPrioritizeWithUUID:]_block_invoke : 296 -> 292
~ ___62-[IXServerConnection _client_coordinatorShouldResumeWithUUID:]_block_invoke : 296 -> 292
~ ___61-[IXServerConnection _client_coordinatorShouldPauseWithUUID:]_block_invoke : 296 -> 292
~ ___87-[IXServerConnection _client_coordinatorWithUUID:configuredPromiseDidBeginFulfillment:]_block_invoke : 300 -> 296
~ ___78-[IXServerConnection _client_coordinatorShouldBeginRestoringUserDataWithUUID:]_block_invoke : 296 -> 292
~ ___88-[IXServerConnection _client_coordinatorDidInstallPlaceholderWithUUID:forRecordPromise:]_block_invoke : 392 -> 388
~ ___92-[IXServerConnection _client_coordinatorShouldBeginPostProcessingWithUUID:forRecordPromise:]_block_invoke : 392 -> 388
~ ___90-[IXServerConnection _client_coordinatorDidCompleteSuccessfullyWithUUID:forRecordPromise:]_block_invoke : 392 -> 388
~ ___77-[IXServerConnection _client_coordinatorWithUUID:didCancelWithReason:client:]_block_invoke : 444 -> 440
~ ___93-[IXServerConnection _client_coordinatorWithUUID:didUpdateProgress:forPhase:overallProgress:]_block_invoke : 308 -> 304
~ ___69-[IXServerConnection _client_promiseDidCompleteSuccessfullyWithUUID:]_block_invoke : 296 -> 292
~ ___73-[IXServerConnection _client_promiseWithUUID:didCancelWithReason:client:]_block_invoke : 300 -> 296
~ +[IXApplicationIdentity identitiesForBundleIdentifiers:] : 344 -> 340
~ -[IXDiskUsageEstimates initWithData:error:] : 404 -> 516
~ -[IXDiskUsageEstimates initWithDictionary:error:] : 972 -> 968
CStrings:
+ "IX Tool"
```
