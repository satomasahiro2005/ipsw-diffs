## MDM

> `/System/Library/PrivateFrameworks/MDM.framework/MDM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55554` | `0x5632c` | **`+0xdd8`** |
| `__TEXT.__oslogstring` | `0x70a5` | `0x727e` | **`+0x1d9`** |
| `__AUTH_CONST.__objc_const` | `0x6c58` | `0x6dd0` | **`+0x178`** |
| `__TEXT.__cstring` | `0x532d` | `0x5439` | **`+0x10c`** |
| `__TEXT.__objc_methlist` | `0x42d4` | `0x43d4` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x4bc0` | `0x4c40` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x3478` | `0x34f0` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x12c0` | `0x1308` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x1230` | `0x11f8` | **`-0x38`** |
| `__TEXT.__gcc_except_tab` | `0xf08` | `0xf34` | **`+0x2c`** |
| `__DATA.__objc_ivar` | `0x2ac` | `0x2c8` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x7e0` | `0x7e8` | **`+0x8`** |

### Other Changes

```diff

-113.2.5.0.0
+113.40.17.0.0

-  Functions: 1687
-  Symbols:   3409
-  CStrings:  1271
+  Functions: 1718
+  Symbols:   3439
+  CStrings:  1282
Symbols:
+ -[MDMMigrationManager _isDeviceEligibleForMigration]
+ -[MDMMigrationManager _queue_clearConfigFetchRetryState]
+ -[MDMMigrationManager _queue_isConfigFetchPending]
+ -[MDMMigrationManager _queue_retryConfigFetchFromReason:backgroundTask:]
+ -[MDMMigrationManager _queue_scheduleConfigFetchRetry]
+ -[MDMMigrationManager _queue_setConfigFetchPending:]
+ -[MDMMigrationManager _retrieveAndStorePendingCloudConfigurationWithCompletionHandler:]
+ -[MDMMigrationManager configFetchPending]
+ -[MDMMigrationManager configFetchRetryInterval]
+ -[MDMMigrationManager configFetchRetryTask]
+ -[MDMMigrationManager initWithNetworkMonitor:]
+ -[MDMMigrationManager isFetchingConfig]
+ -[MDMMigrationManager networkMonitor]
+ -[MDMMigrationManager retryInfoPlist]
+ -[MDMMigrationManager setConfigFetchPending:]
+ -[MDMMigrationManager setConfigFetchRetryInterval:]
+ -[MDMMigrationManager setConfigFetchRetryTask:]
+ -[MDMMigrationManager setIsFetchingConfig:]
+ -[MDMMigrationManager setNetworkMonitor:]
+ -[MDMMigrationManager setRetryInfoPlist:]
+ -[MDMMigrationManager setWorkerQueue:]
+ -[MDMMigrationManager workerQueue]
+ -[MDMServerCore _errorFromTransaction:assertion:rmAccountID:enrollmentMode:reauthQueue:outHandling:]
+ -[MDMServerCore _executionQueueErrorFromTransactionHandlingError:assertion:rmAccountID:enrollmentMode:reauthQueue:]
+ -[MDMServerCore _processAccountDrivenUnauthorizedFromTransaction:rmAccountID:reauthQueue:outHandling:]
+ -[MDMServerCore _processUnauthorizedFromTransaction:authParams:rmAccountID:rmAccountUsername:reauthQueue:outHandling:]
+ -[MDMServerCore _triggerRefreshTokenForTransaction:authenticator:authParams:rmAccountID:rmAccountUsername:reauthQueue:outHandling:]
+ -[MDMServerCore executeDeclarativeManagementRequestForEndpoint:requestData:completion:]
+ -[MDMServicerCore executeDeclarativeManagementRequestForEndpoint:requestData:completion:]
+ GCC_except_table231
+ GCC_except_table236
+ GCC_except_table238
+ GCC_except_table25
+ GCC_except_table258
+ GCC_except_table292
+ GCC_except_table299
+ GCC_except_table310
+ GCC_except_table323
+ GCC_except_table335
+ GCC_except_table339
+ GCC_except_table350
+ GCC_except_table354
+ GCC_except_table37
+ GCC_except_table370
+ _DMCMigrationErrorDomain
+ _MDMMigrationConfigFetchRetryInfoFilePath
+ _MDMShouldAllowEscrowCreationForPasscode
+ _OBJC_CLASS_$_DMCDeviceEligibility
+ _OBJC_IVAR_$_MDMMigrationManager._configFetchPending
+ _OBJC_IVAR_$_MDMMigrationManager._configFetchRetryInterval
+ _OBJC_IVAR_$_MDMMigrationManager._configFetchRetryTask
+ _OBJC_IVAR_$_MDMMigrationManager._isFetchingConfig
+ _OBJC_IVAR_$_MDMMigrationManager._networkMonitor
+ _OBJC_IVAR_$_MDMMigrationManager._retryInfoPlist
+ _OBJC_IVAR_$_MDMMigrationManager._workerQueue
+ ___100-[MDMServerCore _errorFromTransaction:assertion:rmAccountID:enrollmentMode:reauthQueue:outHandling:]_block_invoke
+ ___100-[MDMServerCore _errorFromTransaction:assertion:rmAccountID:enrollmentMode:reauthQueue:outHandling:]_block_invoke_2
+ ___131-[MDMServerCore _triggerRefreshTokenForTransaction:authenticator:authParams:rmAccountID:rmAccountUsername:reauthQueue:outHandling:]_block_invoke
+ ___131-[MDMServerCore _triggerRefreshTokenForTransaction:authenticator:authParams:rmAccountID:rmAccountUsername:reauthQueue:outHandling:]_block_invoke_2
+ ___131-[MDMServerCore _triggerRefreshTokenForTransaction:authenticator:authParams:rmAccountID:rmAccountUsername:reauthQueue:outHandling:]_block_invoke_3
+ ___50-[MDMMigrationManager stopMonitoringDEPServerPush]_block_invoke
+ ___54-[MDMMigrationManager _queue_scheduleConfigFetchRetry]_block_invoke
+ ___59-[MDMMigrationManager startMonitoringDEPServerPushIfNeeded]_block_invoke
+ ___59-[MDMMigrationManager startMonitoringDEPServerPushIfNeeded]_block_invoke_2
+ ___87-[MDMMigrationManager _retrieveAndStorePendingCloudConfigurationWithCompletionHandler:]_block_invoke
+ ___87-[MDMMigrationManager _retrieveAndStorePendingCloudConfigurationWithCompletionHandler:]_block_invoke_2
+ ___87-[MDMServerCore executeDeclarativeManagementRequestForEndpoint:requestData:completion:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e34_v24?0"NSError"8"NSDictionary"16ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e17_v16?0"NSError"8ls32l8s48l8s40l8
+ _kMDMDataKey
+ _kMDMEndpointKey
+ _kMDMMessageTypeDeclarativeManagement
- -[MDMMigrationManager _retrieveAndStorePendingCloudConfigurationWithRetryCount:completionHandler:]
- -[MDMMigrationManager init]
- -[MDMRequestTriggerEnhancedLogCollectionCommand(Handler) _areAccountsPresentWithAccountTypeIdentifiers:]
- -[MDMRequestTriggerEnhancedLogCollectionCommand(Handler) _isDeviceWithoutUserData]
- -[MDMRequestTriggerEnhancedLogCollectionCommand(Handler) _isPasscodePresent]
- -[MDMServerCore _httpErrorFromTransaction:assertion:rmAccountID:enrollmentMode:reauthQueue:]
- -[MDMServerCore _processAccountDrivenUnauthorizedFromTransaction:rmAccountID:reauthQueue:]
- -[MDMServerCore _processUnauthorizedFromTransaction:authParams:rmAccountID:rmAccountUsername:reauthQueue:]
- -[MDMServerCore _triggerRefreshTokenForTransaction:authenticator:authParams:rmAccountID:rmAccountUsername:reauthQueue:]
- -[MDMUserParser _originator]
- GCC_except_table227
- GCC_except_table232
- GCC_except_table24
- GCC_except_table253
- GCC_except_table287
- GCC_except_table294
- GCC_except_table305
- GCC_except_table318
- GCC_except_table329
- GCC_except_table333
- GCC_except_table344
- GCC_except_table348
- GCC_except_table36
- GCC_except_table364
- _ACAccountTypeIdentifierAppleAccount
- _ACAccountTypeIdentifierCalDAV
- _ACAccountTypeIdentifierCardDAV
- _ACAccountTypeIdentifierExchange
- _ACAccountTypeIdentifierGmail
- _ACAccountTypeIdentifierHotmail
- _ACAccountTypeIdentifierIMAP
- _ACAccountTypeIdentifierIMAPMail
- _ACAccountTypeIdentifierIMAPNotes
- _ACAccountTypeIdentifierPOP
- _ACAccountTypeIdentifierYahoo
- _ACAccountTypeIdentifieriTunesStore
- ___119-[MDMServerCore _triggerRefreshTokenForTransaction:authenticator:authParams:rmAccountID:rmAccountUsername:reauthQueue:]_block_invoke
- ___119-[MDMServerCore _triggerRefreshTokenForTransaction:authenticator:authParams:rmAccountID:rmAccountUsername:reauthQueue:]_block_invoke_2
- ___95-[MDMServerCore _sendCheckInRequestAndHandleErrorForMessageType:requestDict:completionHandler:]_block_invoke_3
- ___98-[MDMMigrationManager _retrieveAndStorePendingCloudConfigurationWithRetryCount:completionHandler:]_block_invoke
- ___block_descriptor_40_e8_32bs_e34_v24?0"NSError"8"NSDictionary"16ls32l8
- ___block_descriptor_56_e8_32s40bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8s40l8
CStrings:
+ "-[MDMServerCore executeDeclarativeManagementRequestForEndpoint:requestData:completion:]"
+ "A cloud config fetch is already in progress"
+ "Device is on seed build. Skip the random delay"
+ "MDMMigrationManager: A cloud config fetch is still pending, re-attempting when network is available"
+ "MDMMigrationManager: Cloud config fetch already in progress, coalescing"
+ "MDMMigrationManager: Cloud config fetch already in progress, skipping retry (%{public}@)"
+ "MDMMigrationManager: Device no longer eligible for migration, stopping cloud config fetch retry"
+ "MDMMigrationManager: Failed to read pending config fetch flag with error: %{public}@"
+ "MDMMigrationManager: Failed to write pending config fetch flag with error: %{public}@"
+ "MDMMigrationManager: Retrying cloud config fetch (%{public}@)"
+ "MDMMigrationManager: Scheduling cloud config fetch retry after %.1f seconds"
+ "MDMMigrationManager_worker_queue"
+ "Pending fetch on daemon start"
+ "PendingConfigFetchNeeded"
+ "Scheduled retry"
+ "com.apple.mdmd.MDMMigrationManager.configFetchRetry"
- "Account found - Type: %{public}@, Username: %{private}@, Description: %{private}@"
- "Checking for accounts with type identifiers: %{public}@"
- "Failed to fetch accounts with error: %{public}@"
- "MDMMigrationManager: Retry retrieving cloud config..."
- "ORGANIZATION_QUOTED_%@"
```
