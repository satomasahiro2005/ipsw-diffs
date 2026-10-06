## AppConduit

> `/System/Library/PrivateFrameworks/AppConduit.framework/AppConduit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e06c` | `0x1dff0` | **`-0x7c`** |
| `__TEXT.__unwind_info` | `0x7b8` | `0x7c0` | **`+0x8`** |

### Other Changes

```text
Functions:
~ +[ACXApplication gizmoApplicationsFromCompanionAppRecord:databaseUUID:startingSequenceNumber:] : 580 -> 576
~ -[ACXApplication initWithApplicationRecord:gizmoBundleIdentifier:databaseUUID:sequenceNumber:] : 7708 -> 7692
~ __ValidateSupportedArchitecturesListForPlaceholder : 1004 -> 1000
~ -[ACXApplication _URLOfFirstItemWithExtension:inDirectory:] : 440 -> 436
~ __FetchLocalizedKeys : 740 -> 736
~ -[ACXSyncedApplication localizedInfoPlistStringsForKeys:fetchingFirstMatchingLocalizationInList:] : 840 -> 836
~ __RemoveUnfilteredKeys : 372 -> 368
~ _ACXArrayContainsOnlyClass : 272 -> 268
~ _ACXCopyDuplicatedClassInfo : 856 -> 852
~ -[ACXRemoteApplication isCompatibleWithDevice:] : 856 -> 852
~ -[LSApplicationRecord(AppConduitAdditions) ACX_watchKitExtension] : 348 -> 344
~ ___66-[ACXDeviceConnection updatedInstallStateForApplicationsWithInfo:]_block_invoke : 600 -> 596
~ ___74-[ACXDeviceConnection updateInstallProgressForApplication:progress:phase:]_block_invoke : 420 -> 416
~ ___67-[ACXDeviceConnection applicationsInstalled:onDeviceWithPairingID:]_block_invoke : 440 -> 436
~ ___65-[ACXDeviceConnection applicationsUpdated:onDeviceWithPairingID:]_block_invoke : 440 -> 436
~ ___69-[ACXDeviceConnection applicationsUninstalled:onDeviceWithPairingID:]_block_invoke : 440 -> 436
~ ___73-[ACXDeviceConnection applicationDatabaseResyncedForDeviceWithPairingID:]_block_invoke : 420 -> 416
~ ___82-[ACXDeviceConnection removabilityDidChangeForApplications:onDeviceWithPairingID:]_block_invoke : 440 -> 436
~ ___53-[ACXDeviceConnection observerRegistrationSuccessful]_block_invoke : 396 -> 392
~ ___87-[ACXDeviceConnection watchAppBundleURLWithinCompanionAppWithWatchAppIdentifier:error:]_block_invoke_2 : 128 -> 124
~ ___69-[ACXDeviceConnection watchAppBundleIDForCompanionAppBundleID:error:]_block_invoke_2 : 128 -> 124
~ -[ACXDeviceConnection _validateAndExtractProfiles:error:] : 712 -> 708
~ ___65-[ACXDeviceConnection provisioningProfilesForPairedDevice:error:]_block_invoke_2 : 128 -> 124
~ ___92-[ACXDeviceConnection provisioningProfilesForApplicationWithBundleID:forPairedDevice:error:]_block_invoke_2 : 128 -> 124
~ ___75-[ACXDeviceConnection applicationOnDeviceWithPairingID:withBundleID:error:]_block_invoke_2 : 128 -> 124
~ ___101-[ACXDeviceConnection _locallyAvailableApplicationWithBundleID:forDeviceWithPairingID:options:error:]_block_invoke_2 : 128 -> 124
~ ___113-[ACXDeviceConnection locallyAvailableApplicationWithContainingApplicationBundleID:forDeviceWithPairingID:error:]_block_invoke_2 : 128 -> 124
~ ___138-[ACXDeviceConnection copyLocalizedValuesFromAllDevicesForInfoPlistKeys:forAppWithBundleID:fetchingFirstMatchingLocalizationInList:error:]_block_invoke_2 : 128 -> 124
~ ___84-[ACXDeviceConnection installableSystemAppWithBundleID:onDeviceWithPairingID:error:]_block_invoke_2 : 128 -> 124
~ ___68-[ACXDeviceConnection applicationRemovabilityForPairedDevice:error:]_block_invoke_2 : 128 -> 124
~ _parse_macho_iterate_slices_fd : 984 -> 976
~ _parse_macho_is_file_runnable_for_apps : 1352 -> 1368
```
