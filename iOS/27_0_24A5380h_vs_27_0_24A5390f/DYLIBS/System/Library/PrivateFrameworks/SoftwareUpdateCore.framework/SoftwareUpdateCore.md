## SoftwareUpdateCore

> `/System/Library/PrivateFrameworks/SoftwareUpdateCore.framework/SoftwareUpdateCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaed2c` | `0xaf128` | **`+0x3fc`** |
| `__TEXT.__cstring` | `0x1618d` | `0x1620d` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0xbb28` | `0xbb88` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x83e4` | `0x842c` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x13760` | `0x137a0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xb00` | `0xb30` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x4a30` | `0x4a58` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0xab0` | `0xab8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x200` | `0x208` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1910` | `0x1918` | **`+0x8`** |

### Other Changes

```diff

-2718.0.5.0.0
+2718.0.12.0.0

-  Functions: 3285
-  Symbols:   5733
-  CStrings:  3298
+  Functions: 3291
+  Symbols:   5748
+  CStrings:  3300
Symbols:
+ -[SUCoreDescriptor preSUStagingOptionalCount]
+ -[SUCoreDescriptor preSUStagingRequiredCount]
+ -[SUCoreDescriptor setPreSUStagingOptionalCount:]
+ -[SUCoreDescriptor setPreSUStagingRequiredCount:]
+ -[SUCoreScanPSUSDetermineResult assignToUpdate:]
+ -[SUCoreScanPSUSDetermineResult init]
+ GCC_except_table51
+ GCC_except_table58
+ GCC_except_table66
+ _OBJC_IVAR_$_SUCoreDescriptor._preSUStagingOptionalCount
+ _OBJC_IVAR_$_SUCoreDescriptor._preSUStagingRequiredCount
+ _kSUCoreControllerPreSUStagingOptionalCountKey
+ _kSUCoreControllerPreSUStagingOptionalStagedCountKey
+ _kSUCoreControllerPreSUStagingOptionalStagedSizeKey
+ _kSUCoreControllerPreSUStagingRequiredCountKey
+ _kSUCoreControllerPreSUStagingRequiredStagedCountKey
+ _kSUCoreControllerPreSUStagingRequiredStagedSizeKey
- GCC_except_table49
- GCC_except_table64
CStrings:
+ "                             enablePSUS: %@\n            enablePSUSForOptionalAssets: %@\n    minFreeSpacePostStageOptionalAssets: %llu\n           preSUStagingCacheDeleteLevel: %d\n              preSUStagingRequiredCount: %lu\n              preSUStagingOptionalCount: %lu\n      autoDownloadAllowableOverCellular: %@\n          downloadAllowableOverCellular: %@\n                           downloadable: %@\n               disableSiriVoiceDeletion: %@\n                        disableCDLevel4: %@\n                  disableCDCriticalMode: %@\n                     disableAppDemotion: %@\n                    disableMASuspension: %@\n                  disableInstallTonight: %@\n                  forcePasscodeRequired: %@\n                            rampEnabled: %@\n                         badgingEnabled: %@\n                       granularlyRamped: %@\n                       mdmDelayInterval: %llu\n                      autoUpdateEnabled: %@\n                       hideInstallAlert: %@\n                     containsSFRContent: %@\n                   installAlertInterval: %llu\n             allowAutoDownloadOnBattery: %@\n             autoDownloadOnBatteryDelay: %llu\n        autoDownloadOnBatteryMinBattery: %llu\n                         disableSplombo: %@\n                          setupCritical: %@\n               criticalCellularOverride: %@\n                   criticalOutOfBoxOnly: %@\n                     lastEmergencyBuild: %@\n                 lastEmergencyOSVersion: %@\n                mandatoryUpdateEligible: %@\n              mandatoryUpdateVersionMin: %@\n              mandatoryUpdateVersionMax: %@\n                mandatoryUpdateOptional: %@\n mandatoryUpdateRestrictedToOutOfTheBox: %@\n                   oneShotBuddyDisabled: %@\n             oneShotBuddyDisabledBuilds: %@\n"
+ "PSUSOptionalCount"
+ "PSUSRequiredCount"
- "                             enablePSUS: %@\n            enablePSUSForOptionalAssets: %@\n    minFreeSpacePostStageOptionalAssets: %llu\n           preSUStagingCacheDeleteLevel: %d\n      autoDownloadAllowableOverCellular: %@\n          downloadAllowableOverCellular: %@\n                           downloadable: %@\n               disableSiriVoiceDeletion: %@\n                        disableCDLevel4: %@\n                  disableCDCriticalMode: %@\n                     disableAppDemotion: %@\n                    disableMASuspension: %@\n                  disableInstallTonight: %@\n                  forcePasscodeRequired: %@\n                            rampEnabled: %@\n                         badgingEnabled: %@\n                       granularlyRamped: %@\n                       mdmDelayInterval: %llu\n                      autoUpdateEnabled: %@\n                       hideInstallAlert: %@\n                     containsSFRContent: %@\n                   installAlertInterval: %llu\n             allowAutoDownloadOnBattery: %@\n             autoDownloadOnBatteryDelay: %llu\n        autoDownloadOnBatteryMinBattery: %llu\n                         disableSplombo: %@\n                          setupCritical: %@\n               criticalCellularOverride: %@\n                   criticalOutOfBoxOnly: %@\n                     lastEmergencyBuild: %@\n                 lastEmergencyOSVersion: %@\n                mandatoryUpdateEligible: %@\n              mandatoryUpdateVersionMin: %@\n              mandatoryUpdateVersionMax: %@\n                mandatoryUpdateOptional: %@\n mandatoryUpdateRestrictedToOutOfTheBox: %@\n                   oneShotBuddyDisabled: %@\n             oneShotBuddyDisabledBuilds: %@\n"
```
