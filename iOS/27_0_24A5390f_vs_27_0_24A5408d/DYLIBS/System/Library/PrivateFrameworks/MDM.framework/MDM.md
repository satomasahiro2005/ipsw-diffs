## MDM

> `/System/Library/PrivateFrameworks/MDM.framework/MDM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x585d0` | `0x5559c` | **`-0x3034`** |
| `__AUTH_CONST.__cfstring` | `0x52c0` | `0x4bc0` | **`-0x700`** |
| `__TEXT.__oslogstring` | `0x76e4` | `0x70d4` | **`-0x610`** |
| `__TEXT.__cstring` | `0x58c0` | `0x532d` | **`-0x593`** |
| `__DATA_CONST.__objc_selrefs` | `0x35c0` | `0x3478` | **`-0x148`** |
| `__TEXT.__objc_methlist` | `0x43a4` | `0x42d4` | **`-0xd0`** |
| `__DATA_CONST.__const` | `0x1f68` | `0x1eb8` | **`-0xb0`** |
| `__AUTH_CONST.__objc_const` | `0x6c08` | `0x6c58` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1310` | `0x12c0` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x1270` | `0x1230` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x7e8` | `0x7e0` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x2a4` | `0x2ac` | **`+0x8`** |

### Other Changes

```diff

-113.0.2.0.0
+113.2.5.0.0

-  - /System/Library/PrivateFrameworks/SoftwareUpdateServices.framework/SoftwareUpdateServices

-  Functions: 1711
-  Symbols:   3443
-  CStrings:  1370
+  Functions: 1687
+  Symbols:   3409
+  CStrings:  1272
Symbols:
+ -[MDMDEPPushTokenManager cachedLastPushTokenHash]
+ -[MDMDEPPushTokenManager cachedLastSyncedEligibility]
+ -[MDMDEPPushTokenManager setCachedLastPushTokenHash:]
+ -[MDMDEPPushTokenManager setCachedLastSyncedEligibility:]
+ GCC_except_table110
+ GCC_except_table147
+ GCC_except_table189
+ GCC_except_table192
+ GCC_except_table194
+ GCC_except_table208
+ GCC_except_table211
+ GCC_except_table216
+ GCC_except_table227
+ GCC_except_table232
+ GCC_except_table253
+ GCC_except_table287
+ GCC_except_table294
+ GCC_except_table305
+ GCC_except_table318
+ GCC_except_table329
+ GCC_except_table333
+ GCC_except_table344
+ GCC_except_table348
+ GCC_except_table364
+ _OBJC_CLASS_$_DMCProcessAssertion
+ _OBJC_IVAR_$_MDMDEPPushTokenManager._cachedLastPushTokenHash
+ _OBJC_IVAR_$_MDMDEPPushTokenManager._cachedLastSyncedEligibility
- +[MDMParser _dmfAction:fromMDMActionString:]
- +[MDMParser _errorFromDMFSoftwareUpdateError:]
- +[MDMParser _errorWithDomain:code:descriptionKey:underlyingError:type:]
- +[MDMParser _resolvedInstallActionStringForAction:]
- +[MDMParser _shouldUseDelayWithRequest:]
- +[MDMParser _statusFromError:action:]
- +[MDMParser _updateDictionaryFromUpdate:]
- +[MDMParser _useDelayFlagAllowed]
- -[MDMParser _availableOSUpdates:assertion:completionBlock:]
- -[MDMParser _dmfScheduleOSUpdate:assertion:completionBlock:]
- -[MDMParser _mdmScheduleOSUpdate:assertion:completionBlock:]
- -[MDMParser _performSetUpdatePath:]
- -[MDMParser _platformSupportsOSUpdateManagement]
- -[MDMParser _rejectSoftwareUpdateBecauseOfMalformedRequestCompletionBlock:]
- -[MDMParser _rejectSoftwareUpdateBecauseUserLoggedInCompletionBlock:]
- -[MDMParser _responseForMalformedUpdateRequest]
- -[MDMParser _scheduleOSUpdate:assertion:completionBlock:]
- -[MDMParser _scheduleOSUpdateScan:assertion:completionBlock:]
- -[MDMParser _softwareUpdatesNotPermittedWithLoggedInUserError]
- -[MDMParser _statusOfOSUpdates:assertion:completionBlock:]
- -[MDMServerCore softwareUpdatePathFromDisk]
- GCC_except_table111
- GCC_except_table150
- GCC_except_table190
- GCC_except_table193
- GCC_except_table196
- GCC_except_table209
- GCC_except_table212
- GCC_except_table220
- GCC_except_table228
- GCC_except_table233
- GCC_except_table254
- GCC_except_table288
- GCC_except_table295
- GCC_except_table306
- GCC_except_table319
- GCC_except_table330
- GCC_except_table334
- GCC_except_table345
- GCC_except_table349
- GCC_except_table365
- _DMCErrorTypeNeedsRetry
- _DMCInternalErrorDomain
- _DMCSendSettingsChangedNotification
- _OBJC_CLASS_$_MDFFetchAvailableOSUpdatesRequest
- _OBJC_CLASS_$_MDFFetchOSUpdateStatusRequest
- _OBJC_CLASS_$_MDFScheduleOSUpdateRequest
- _OBJC_CLASS_$_SUUtility
- ___35-[MDMParser _performSetUpdatePath:]_block_invoke
- ___57-[MDMParser _scheduleOSUpdate:assertion:completionBlock:]_block_invoke
- ___58-[MDMParser _statusOfOSUpdates:assertion:completionBlock:]_block_invoke
- ___59-[MDMParser _availableOSUpdates:assertion:completionBlock:]_block_invoke
- ___NSArray0__struct
- _kMDMPQuerySoftwareUpdate
- _kMDMPQuerySoftwareUpdateDeviceID
- _kMDMPRequestTypeAvailableOSUpdates
- _kMDMPRequestTypeOSUpdateStatus
- _kMDMPRequestTypeScheduleOSUpdate
- _kMDMPRequestTypeScheduleOSUpdateScan
- _kMDMPSettingsSettingsSoftwareUpdate
- _kSettingsSettingsSoftwareUpdatePathKey
CStrings:
+ "DEP push token sync in flight"
+ "Failed to persist lastPushTokenHash (cache is authoritative) with error: %{public}@"
+ "Failed to persist lastSyncedEligibility (cache is authoritative) with error: %{public}@"
+ "Ignoring deadlineToSync of unexpected class: %{public}@"
+ "Ignoring lastPushTokenHash of unexpected class: %{public}@"
+ "Ignoring lastSyncedEligibility of unexpected class: %{public}@"
+ "Ignoring lastestPushTokenHashToSync of unexpected class: %{public}@"
- "-[MDMParser _availableOSUpdates:assertion:completionBlock:]"
- "-[MDMParser _statusOfOSUpdates:assertion:completionBlock:]"
- "AllowsInstallLater"
- "Available OS update end."
- "Available OS update start."
- "AvailableOSUpdates"
- "Build"
- "Can't fetch OS update status due to user logged in."
- "Can't fetch available updates due to user logged in."
- "Could not check for available iOS updates - %{public}@"
- "Could not check for iOS update status - %{public}@"
- "Could not schedule an update - %{public}@"
- "DMF Schedule OS update end."
- "DMF Schedule OS update start."
- "Did not write to plist!"
- "DownloadFailed"
- "DownloadInsufficientNetwork"
- "DownloadInsufficientPower"
- "DownloadInsufficientSpace"
- "DownloadOnly"
- "DownloadPercentComplete"
- "DownloadRequiresComputer"
- "DownloadSize"
- "Downloading"
- "Failed to get lastPushTokenHash with error: %{public}@"
- "Failed to get lastSyncedEligibility with error: %{public}@"
- "Failed to set lastPushTokenHash with error: %{public}@"
- "Failed to set lastSyncedEligibility with error: %{public}@"
- "HumanReadableName"
- "InstallASAP"
- "InstallAction"
- "InstallFailed"
- "InstallInsufficientPower"
- "InstallInsufficientSpace"
- "InstallSize"
- "IsCritical"
- "IsDownloaded"
- "IsSecurityResponse"
- "MCUseSoftwareUpdateDelayFlagAllowed"
- "MDM Schedule OS update end."
- "MDM Schedule OS update start."
- "MDMParser.m"
- "MDM_ERROR_SU_DEVICE_PASSCODE_MUST_BE_CLEARED"
- "MDM_ERROR_SU_DOWNLOAD_COMPLETE"
- "MDM_ERROR_SU_DOWNLOAD_FAILED"
- "MDM_ERROR_SU_DOWNLOAD_INSUFFICIENT_NETWORK"
- "MDM_ERROR_SU_DOWNLOAD_INSUFFICIENT_POWER"
- "MDM_ERROR_SU_DOWNLOAD_INSUFFICIENT_SPACE"
- "MDM_ERROR_SU_DOWNLOAD_IN_PROGRESS"
- "MDM_ERROR_SU_DOWNLOAD_REQUIRES_COMPUTER"
- "MDM_ERROR_SU_INSTALL_FAILED"
- "MDM_ERROR_SU_INSTALL_INSUFFICIENT_POWER"
- "MDM_ERROR_SU_INSTALL_INSUFFICIENT_SPACE"
- "MDM_ERROR_SU_INSTALL_IN_PROGRESS"
- "MDM_ERROR_SU_INSTALL_REQUIRES_DOWNLOAD"
- "MDM_ERROR_SU_NOT_PERMITTED_WITH_LOGGED_IN_USER"
- "MDM_ERROR_SU_NO_UPDATE_AVAILABLE"
- "MDM_ERROR_SU_SCAN_FAILED"
- "NO"
- "No update available."
- "No updates available."
- "OSUpdateStatus"
- "OSUpdateStatus DMF raw data: %{public}@"
- "OSUpdateStatus response: %{public}@"
- "ProductKey"
- "ProductName"
- "ProductVersion"
- "RecommendationCadence"
- "Rejected software update due to \"use delay\" bad request."
- "Rejected software update due to install action being non-default, non-download only nor immediate install actions."
- "Rejected software update due to malformed OS update action."
- "Rejected software update due to malformed install action."
- "Rejected software update due to malformed product key."
- "Rejected software update due to malformed product version."
- "Rejected software update due to malformed update array."
- "Rejected software update due to malformed update object."
- "Rejected software update due to missing or malformed OS update object."
- "Rejected software update due to missing or malformed update array."
- "Rejected software update due to multiple OS update objects."
- "Rejected software update due to user logged in."
- "Requesting an update with a specific PMV - %{public}@"
- "Requesting an update with any PMV"
- "RestartRequired"
- "Returning updates array: %{public}@"
- "Schedule OS update end."
- "Schedule OS update scan end."
- "Schedule OS update scan start."
- "Schedule OS update start"
- "ScheduleOSUpdate"
- "ScheduleOSUpdateScan"
- "SoftwareUpdateSettings"
- "Status of OS update end."
- "Status of OS update start."
- "SupplementalBuildVersion"
- "SupplementalOSVersionExtra"
- "Unknown software update error"
- "UpdateResults"
- "Updates"
- "UseDelay"
- "Writing Software Update setting to disk."
- "YES"
- "availableOSUpdates useDelay = %{public}@"
- "dmfError != nil"
- "scheduleOSUpdate useDelay = %{public}@"
- "useDelayFlagAllowed = %{public}@"
```
