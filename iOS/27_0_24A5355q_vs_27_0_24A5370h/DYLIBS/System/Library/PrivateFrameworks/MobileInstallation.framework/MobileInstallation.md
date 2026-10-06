## MobileInstallation

> `/System/Library/PrivateFrameworks/MobileInstallation.framework/MobileInstallation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27564` | `0x274dc` | **`-0x88`** |
| `__TEXT.__objc_methlist` | `0x13b4` | `0x13c4` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x19f8` | `0x1a00` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xd98` | `0xda0` | **`+0x8`** |

### Other Changes

```diff

-1655.0.0.0.0
+1660.0.0.0.0
Functions:
~ ___87-[MIHelperServiceFrameworkClient stagingLocationForSystemContentWithinSubsystem:error:]_block_invoke_2 : 128 -> 124
~ ___85-[MIHelperServiceFrameworkClient stagingLocationForUserContentWithinSubsystem:error:]_block_invoke_2 : 128 -> 124
~ ___75-[MIHelperServiceFrameworkClient allStagingLocationsWithinSubsystem:error:]_block_invoke_2 : 128 -> 124
~ ___101-[MIHelperServiceFrameworkClient stagingLocationForURL:withinStagingSubsystem:usingUniqueName:error:]_block_invoke_2 : 128 -> 124
~ ___113-[MIHelperServiceFrameworkClient stagingLocationForInstallLocation:withinStagingSubsystem:usingUniqueName:error:]_block_invoke_2 : 128 -> 124
~ _MIPurgeExpendableAppsAndDataForRestore : 3992 -> 3972
~ ____OffloadApps_block_invoke : 184 -> 180
~ ___MobileInstallationStageApplicationUpdate_block_invoke : 128 -> 124
~ ___MobileInstallationGetAllStagedUpdateIdentifiers_block_invoke : 128 -> 124
~ ___MobileInstallationRegisterPlaceholderForReference_block_invoke : 128 -> 124
~ ___MIFinalizeReferenceForInstalledAppWithError_block_invoke : 128 -> 124
~ ___MIAcquireReferenceForInstalledAppWithError_block_invoke : 128 -> 124
~ ___MobileInstallationGetContainerizedAppBundleRecordsForLaunchServices_block_invoke : 128 -> 124
~ ___MobileInstallationUpdateSinfDataForInstallCoordination_block_invoke : 200 -> 196
~ ___MobileInstallationWatchKitInstallerSnapshotWKApp_block_invoke : 196 -> 192
~ ___MobileInstallationFetchListOfAppsRequiringPreInstallConsent_block_invoke : 128 -> 124
~ ___MIGetReferencesForBundleWithIdentifier_block_invoke : 128 -> 124
~ ___MobileInstallationLinkedBundleIDsForIdentity_block_invoke : 128 -> 124
~ ____CopySafeHarborsForContainerClass_block_invoke : 200 -> 196
~ _MIGetFirstTrueBooleanEntitlement : 300 -> 296
~ _MIHasRequiredEntitlements : 412 -> 408
~ _MIArrayContainsOnlyClass : 272 -> 268
~ _MIArrayFilteredToContainOnlyClass : 352 -> 348
~ -[MIPlaceholderConstructor firstNetworkExtension] : 328 -> 324
~ -[MIPlaceholderConstructor _populateAppExtensionPlaceholderConstructorsWithError:] : 528 -> 524
~ -[MIPlaceholderConstructor setPerformPlaceholderInstallActions:] : 252 -> 248
~ -[MIPlaceholderConstructor setInstallUUID:] : 280 -> 276
~ -[MIPlaceholderConstructor setInstallSessionUUID:] : 280 -> 276
~ -[MIPlaceholderConstructor _writeInfoPlistToPlaceholder:substitutingIconContent:withError:] : 984 -> 980
~ -[MIPlaceholderConstructor _materializeConstructors:intoBundle:error:] : 788 -> 784
```
