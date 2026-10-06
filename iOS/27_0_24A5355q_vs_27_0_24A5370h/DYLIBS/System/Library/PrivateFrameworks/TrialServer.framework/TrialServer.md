## TrialServer

> `/System/Library/PrivateFrameworks/TrialServer.framework/TrialServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15d3b0` | `0x15e124` | **`+0xd74`** |
| `__TEXT.__oslogstring` | `0x1dcdb` | `0x1e04e` | **`+0x373`** |
| `__TEXT.__delay_helper` | `0x4f4` | `0x794` | **`+0x2a0`** |
| `__AUTH_CONST.__objc_const` | `0x18300` | `0x18418` | **`+0x118`** |
| `__TEXT.__gcc_except_tab` | `0x7dfc` | `0x7ebc` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0xc764` | `0xc814` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x16d72` | `0x16dfb` | **`+0x89`** |
| `__DATA_CONST.__got` | `0x1510` | `0x1578` | **`+0x68`** |
| `__DATA.__data` | `0x2d24` | `0x2d7c` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0xece0` | `0xeca0` | **`-0x40`** |
| `__AUTH_CONST.__const` | `0x16c8` | `0x1708` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x65b8` | `0x65f8` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x68b0` | `0x68d8` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0xf28` | `0xf40` | **`+0x18`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x390` | `0x378` | **`-0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0xe28` | `0xe40` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x3a0` | `0x388` | **`-0x18`** |
| `__DATA_DIRTY.__bss` | `0x3b8` | `0x3c8` | **`+0x10`** |
| `__TEXT.__const` | `0x18fc` | `0x18ec` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x26e` | `0x260` | **`-0xe`** |
| `__DATA.__objc_ivar` | `0x958` | `0x960` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x278` | `0x280` | **`+0x8`** |

### Other Changes

```diff

-501.0.0.0.0
+505.0.0.0.0

-  Functions: 5238
-  Symbols:   9485
-  CStrings:  4246
+  Functions: 5242
+  Symbols:   9533
+  CStrings:  4255
Symbols:
+ +[TRISystemInfo createSystemInfoWithFactorProvider:covariateFetcher:]
+ -[TRIBAACertManager _isTransientError:]
+ -[TRIExperimentRollbackProcessor _updateEndDateToNowForExperimentRecord:andTransitionToFinished:]
+ -[TRIFetchExperimentTask _nextTasksForRunStatus:needsDecryption:]
+ -[TRIPushNotificationHandler client]
+ -[TRIPushNotificationHandler initWithNotificationChecker:hotfixScheduler:rollbackScheduler:experimentUpdateScheduler:client:]
+ -[TRIServerContext covariateFetcher]
+ -[TRIServerContext setCovariateFetcher:]
+ -[TRISystemConfiguration isPortableMac]
+ -[TRISystemInfo initFromSystemWithFactorProvider:covariateFetcher:]
+ _MobileGestalt_copy_hwModelDescriptionForAnalytics_obj
+ _MobileGestalt_copy_productTypeDescForAnalytics_obj
+ _MobileGestalt_get_current_device
+ _NSOSStatusErrorDomain
+ _NSURLErrorDomain
+ _OBJC_IVAR_$_TRIPushNotificationHandler._client
+ _OBJC_IVAR_$_TRIServerContext._covariateFetcher
+ _TRIMetricName_HotfixPushNotificationReceived
+ _TRIMetricName_UpdateEndDate
+ _TRIMetricName_UrgentRollbackPushNotificationReceived
+ _TRISystemCovariate_IsPortableMac
+ __OBJC_$_PROP_LIST_TRIXPCCovariateFetcher
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_TRICovariateFetching
+ __OBJC_$_PROTOCOL_METHOD_TYPES_TRICovariateFetching
+ __OBJC_$_PROTOCOL_REFS_TRICovariateFetching
+ __OBJC_CLASS_PROTOCOLS_$_TRIXPCCovariateFetcher
+ __OBJC_LABEL_PROTOCOL_$_TRICovariateFetching
+ __OBJC_PROTOCOL_$_TRICovariateFetching
+ ___39-[TRISystemConfiguration isPortableMac]_block_invoke
+ ___97-[TRIExperimentRollbackProcessor _updateEndDateToNowForExperimentRecord:andTransitionToFinished:]_block_invoke
+ ___block_descriptor_104_e8_32s40s48s56s64r72r80r88r96r_e63_v40?0Q8"TRIClientExperimentArtifact"16"NSDate"24"NSError"32lr64l8r72l8r80l8s32l8r88l8r96l8s40l8s48l8s56l8
+ ___block_descriptor_57_e8_32s40s48s_e64_{_PASDBTransactionCompletion_=B}16?0"_PASSqlWriteTransaction"8ls32l8s40l8s48l8
+ ___block_descriptor_92_e8_32s40s48s56s64r72r80r_e63_{_PASDBTransactionCompletion_=B}16?0"_PASSqlReadTransaction"8ls32l8s40l8r64l8s48l8r72l8r80l8s56l8
+ _kMAOptionsBAAAccessControls
+ _kMAOptionsBAAAccessControls$loadHelper_x8
+ _kMAOptionsBAADeleteExistingKeysAndCerts
+ _kMAOptionsBAADeleteExistingKeysAndCerts$loadHelper_x8
+ _kMAOptionsBAAKeychainAccessGroup
+ _kMAOptionsBAAKeychainAccessGroup$loadHelper_x8
+ _kMAOptionsBAAKeychainLabel
+ _kMAOptionsBAAKeychainLabel$loadHelper_x8
+ _kMAOptionsBAANetworkTimeoutInterval
+ _kMAOptionsBAANetworkTimeoutInterval$loadHelper_x8
+ _kMAOptionsBAAOIDDeviceOSInformation
+ _kMAOptionsBAAOIDDeviceOSInformation$loadHelper_x9
+ _kMAOptionsBAAOIDHardwareProperties
+ _kMAOptionsBAAOIDHardwareProperties$loadHelper_x8
+ _kMAOptionsBAAOIDProductType
+ _kMAOptionsBAAOIDProductType$loadHelper_x8
+ _kMAOptionsBAAOIDSToInclude
+ _kMAOptionsBAAOIDSToInclude$loadHelper_x8
+ _kMAOptionsBAASCRTAttestation
+ _kMAOptionsBAASCRTAttestation$loadHelper_x8
+ _kMAOptionsBAASkipNetworkRequest
+ _kMAOptionsBAASkipNetworkRequest$loadHelper_x8
+ _kMAOptionsBAAValidity
+ _kMAOptionsBAAValidity$loadHelper_x8
+ _kSecUseDataProtectionKeychain
- -[TRIExperimentRollbackProcessor _updateEndDateToNowForDeployment:andTransitionToFinished:]
- -[TRIFetchExperimentTask _nextTasksForRunStatus:]
- -[TRIPushNotificationHandler initWithNotificationChecker:hotfixScheduler:rollbackScheduler:experimentUpdateScheduler:]
- -[TRISystemInfo initFromSystemWithFactorProvider:]
- ___91-[TRIExperimentRollbackProcessor _updateEndDateToNowForDeployment:andTransitionToFinished:]_block_invoke
- ___block_descriptor_49_e8_32s40s_e64_{_PASDBTransactionCompletion_=B}16?0"_PASSqlWriteTransaction"8ls32l8s40l8
- ___block_descriptor_92_e8_32s40s48s56s64r72r80r_e63_{_PASDBTransactionCompletion_=B}16?0"_PASSqlReadTransaction"8ls32l8r64l8s40l8s48l8r72l8r80l8s56l8
- ___block_descriptor_96_e8_32s40s48s56s64r72r80r88r_e63_v40?0Q8"TRIClientExperimentArtifact"16"NSDate"24"NSError"32lr64l8r72l8r80l8s32l8r88l8s40l8s48l8s56l8
- _kTRIBundleIdentifierTrialcontroller
- _symbolic _____y_____G s15CollectionOfOneV s5UInt8V
CStrings:
+ "    AND rampId = :ramp_id"
+ "    AND rampId IS NULL"
+ " CREATE INDEX ix_rolloutHistory_lookup ON rolloutHistory(rolloutId, deploymentId, rampId, factorPackSetId);"
+ "Creating activate treatment task with FPS: %@, counterfactuals: %@"
+ "Database update %@"
+ "DeviceIsPortableMac"
+ "Failed to update database - cannot proceed with treatment switch"
+ "IsPortableMac"
+ "Jun 12 2026"
+ "NSOSStatusErrorDomain"
+ "Re-activating experiment %{public}@ with different treatment %@"
+ "SELECT * FROM rolloutHistory WHERE         rolloutId = :rollout_id    AND deploymentId = :deployment_id"
+ "SUCCESS"
+ "Scheduling stage task"
+ "TRIBAACertManager: Certificate generation returned incomplete results due to transient error. Error: %@ (domain: %@, code: %ld)"
+ "TRIBAACertManager: DeviceIdentity certificate issuance failed due to transient error. Error: %@ (domain: %@, code: %ld)"
+ "TRIBAACertManager: Timed out after %llds waiting for DeviceIdentity certificate completion — returning nil to avoid blocking callers"
+ "TRIXPCCovariateFetcher: Timed out after %llds waiting for TrialArchivingService reply — returning to avoid wedging triald"
+ "Treatment switching enabled for %@. Will attempt to update the database."
+ "TrialXP-505"
+ "com.apple.MobileActivation.ErrorDomain"
+ "failed to update experiment database with a different treatment"
+ "hotfix_push_notification_received"
+ "skipping targeting for %{public}@ -- artifact requires decryption"
+ "update_end_date"
+ "urgent_rollback_push_notification_received"
+ "\xf01"
- "1.2.840.113635.100.8.9.1"
- "1.2.840.113635.100.8.9.2"
- "1.2.840.113635.100.8.9.3"
- "AccessControls"
- "DeleteExistingKeysAndCerts"
- "HWModelStr"
- "KeychainAccessGroup"
- "KeychainLabel"
- "May 21 2026"
- "NetworkTimeoutInterval"
- "OIDsToInclude"
- "ProductType"
- "SCRTAttestation"
- "SELECT * FROM rolloutHistory WHERE         rolloutId = :rollout_id    AND rampId = :ramp_id    AND deploymentId = :deployment_id"
- "SkipNetworkRequest"
- "TrialXP-501"
- "Validity"
- "\xf0!"
```
