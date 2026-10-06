## SoftwareUpdateServices

> `/System/Library/PrivateFrameworks/SoftwareUpdateServices.framework/SoftwareUpdateServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ad9c` | `0x6adfc` | **`+0x60`** |
| `__TEXT.__cstring` | `0x15531` | `0x154e1` | **`-0x50`** |
| `__AUTH_CONST.__cfstring` | `0xdfc0` | `0xdfe0` | **`+0x20`** |

### Other Changes

```diff

-1114.40.9.0.0
+1114.40.10.0.0

-  CStrings:  2225
+  CStrings:  2227
Functions:
~ __requiredBatteryLevelToAutoDownload : 364 -> 472
~ _SURequiredBatteryLevelForAutoDownloadForDescriptor : 464 -> 456
~ -[SUPreferences overrideAllowAutoDownloadOnBattery] : 16 -> 12
CStrings:
+ "\n            Publisher: %@\n            HumanReadableUpdateName: %@\n            ProductSystemName: %@\n            ProductVersion: %@\n            ProductVersionExtra: %@\n            ProductBuildVersion: %@\n            PrerequisiteBuild: %@\n            PrerequisiteOS: %@\n            ReleaseType: %@\n            DownloadSize: %llu\n            UnarchiveSize: %llu\n            MSUPrepareSize: %llu\n            PreparationSize: %llu\n            InstallationSize: %llu\n            PreSUStagingRequiredSize: %llu\n            PreSUStagingOptionalSize: %llu\n            MinFreeSpacePostStageOptionalAssets: %llu\n            UnentitledReserveAmount: %llu\n            PreSUStagingCacheDeleteLevel: %d\n            UpdateType: %@\n            Downloadable: %@\n            DownloadableOverCellular: %@\n            AutoDownloadableOverCellular: %@\n            AutoUpdateEnabled: %@\n            StreamingZipCapable: %@\n            TotalRequiredFreeSpace: %llu\n            Documentation: %@\n            SiriVoiceDeletion: %d\n            CDLevel4DeletionDisabled: %d\n            CDCriticalModeDisabled: %d\n            appDemotionDisabled: %d\n            maSuspensionDisabled: %d\n            installTonightDisabled: %d\n            rampEnabled: %d\n            badgingEnabled: %d\n            granularlyRamped: %d\n            setupCritical: %@\n            criticalOutOfBoxOnly: %d\n            criticalDownloadPolicy: %@\n            releaseDate: %@\n            mdmDelayInterval: %llu\n            assetID: %@\n            hideInstallAlert: %@\n            audienceType: %@\n            preferenceType: %@\n            upgradeType: %@\n            promoteAlternateUpdate: %@\n            isSplatOnly: %@\n            mandatoryUpdateEligible: %@\n            mandatoryUpdateVersionMin: %@\n            mandatoryUpdateVersionMax: %@\n            mandatoryUpdateOptional: %@\n            mandatoryUpdateRestrictedToOutOfTheBox: %@\n            forcePasscodeRequired: %@\n            allowAutoDownloadOnBattery: %@\n            autoDownloadOnBatteryDelay: %u day(s)\n            autoDownloadOnBatteryMinBattery: %u%%\n            isSplombo: %@\n            splatComboBuildVersion: %@\n            splatInstallDate: %@\n            splatRollbackDate: %@\n"
+ "%s: [PREFERENCES] override allowAutoDownloadOnBattery to %d"
+ "%s: [PREFERENCES] override autoDownloadOnBatteryDelay to %.0lf"
+ "%s: autoDownloadOnBatteryDelay = %.0lf sec (~ %.2lf days)"
+ "%s: fullyUnrampedDate = %@ for %@; timeElapsed = %.0lf sec (~ %.2lf days)"
+ "If set, control if the device allows auto-downloading on battery"
+ "SUHasEnoughBatteryForAutoDownloadForDescriptor"
+ "SUHasEnoughBatteryForDownloadForDescriptor"
+ "SURequiredBatteryLevelForAutoDownloadForDescriptor"
+ "SURequiredBatteryLevelForDownloadForDescriptor"
+ "_requiredBatteryLevelToAutoDownload"
+ "getCurrentBatteryLevel"
- "\n            Publisher: %@\n            HumanReadableUpdateName: %@\n            ProductSystemName: %@\n            ProductVersion: %@\n            ProductVersionExtra: %@\n            ProductBuildVersion: %@\n            PrerequisiteBuild: %@\n            PrerequisiteOS: %@\n            ReleaseType: %@\n            DownloadSize: %llu\n            UnarchiveSize: %llu\n            MSUPrepareSize: %llu\n            PreparationSize: %llu\n            InstallationSize: %llu\n            PreSUStagingRequiredSize: %llu\n            PreSUStagingOptionalSize: %llu\n            MinFreeSpacePostStageOptionalAssets: %llu\n            UnentitledReserveAmount: %llu\n            PreSUStagingCacheDeleteLevel: %d\n            UpdateType: %@\n            Downloadable: %@\n            DownloadableOverCellular: %@\n            AutoDownloadableOverCellular: %@\n            AutoUpdateEnabled: %@\n            StreamingZipCapable: %@\n            TotalRequiredFreeSpace: %llu\n            Documentation: %@\n            SiriVoiceDeletion: %d\n            CDLevel4DeletionDisabled: %d\n            CDCriticalModeDisabled: %d\n            appDemotionDisabled: %d\n            maSuspensionDisabled: %d\n            installTonightDisabled: %d\n            rampEnabled: %d\n            badgingEnabled: %d\n            granularlyRamped: %d\n            setupCritical: %@\n            criticalOutOfBoxOnly: %d\n            criticalDownloadPolicy: %@\n            releaseDate: %@\n            mdmDelayInterval: %llu\n            assetID: %@\n            hideInstallAlert: %@\n            audienceType: %@\n            preferenceType: %@\n            upgradeType: %@\n            promoteAlternateUpdate: %@\n            isSplatOnly: %@\n            mandatoryUpdateEligible: %@\n            mandatoryUpdateVersionMin: %@\n            mandatoryUpdateVersionMax: %@\n            mandatoryUpdateOptional: %@\n            mandatoryUpdateRestrictedToOutOfTheBox: %@\n            forcePasscodeRequired: %@\n            allowAutoDownloadOnBattery: %@\n            autoDownloadOnBatteryDelay: %u\n            autoDownloadOnBatteryMinbattery: %u%%\n            isSplombo: %@\n            splatComboBuildVersion: %@\n            splatInstallDate: %@\n            splatRollbackDate: %@\n"
- "BOOL SUHasEnoughBatteryForAutoDownloadForDescriptor(SUDescriptor *__strong _Nonnull, NSDate *__strong _Nonnull)"
- "BOOL SUHasEnoughBatteryForDownloadForDescriptor(SUDescriptor *__strong _Nonnull)"
- "If set to true, allow auto-downloading on battery"
- "NSNumber * _Nonnull SURequiredBatteryLevelForDownloadForDescriptor(SUDescriptor *__strong _Nonnull)"
- "NSNumber *getCurrentBatteryLevel(void)"
- "autoDownloadOnBatteryDelay = %.0lf sec (~ %.2lf days)"
- "autoDownloadOnBatteryDelay is set to %.0lf sec by default"
- "fullyUnrampedDate = %@ for %@; timeElapsed = %.0lf sec (~ %.2lf days)"
- "unsigned int _requiredBatteryLevelToAutoDownload(SUDescriptor *__strong _Nonnull, BOOL, BOOL)"
```
