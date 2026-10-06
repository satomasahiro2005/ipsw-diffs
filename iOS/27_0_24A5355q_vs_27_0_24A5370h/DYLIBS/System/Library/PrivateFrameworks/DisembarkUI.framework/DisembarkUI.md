## DisembarkUI

> `/System/Library/PrivateFrameworks/DisembarkUI.framework/DisembarkUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f238` | `0x1f874` | **`+0x63c`** |
| `__AUTH_CONST.__cfstring` | `0x1460` | `0x1660` | **`+0x200`** |
| `__TEXT.__cstring` | `0x1d14` | `0x1e04` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x2810` | `0x28c8` | **`+0xb8`** |
| `__AUTH_CONST.__objc_const` | `0x4ef8` | `0x4fa0` | **`+0xa8`** |
| `__DATA_CONST.__objc_selrefs` | `0x19c0` | `0x1a50` | **`+0x90`** |
| `__DATA_CONST.__const` | `0xf18` | `0xf60` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0xd77` | `0xda5` | **`+0x2e`** |
| `__TEXT.__const` | `0x184` | `0x194` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7f8` | `0x808` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2b8` | `0x2c4` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x5d8` | `0x5e0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x4c8` | `0x4d0` | **`+0x8`** |

### Other Changes

```diff

-277.0.0.0.0
+279.0.0.0.0

-  Functions: 934
-  Symbols:   1857
-  CStrings:  344
+  Functions: 947
+  Symbols:   1877
+  CStrings:  361
Symbols:
+ +[DKAnalyticsHandler _stringForBackupDecisionOutcome:]
+ +[DKAnalyticsHandler _stringForConfigurationSource:]
+ +[DKDateFormatter formattedLastBackupDateFrom:locale:timeZone:]
+ +[DKEraseConfirmationAlertController alertControllerWithCellularPlans:physicalSIMModeActive:completion:]
+ -[DKAnalyticsHandler pendingBackupDecisionAgeDays]
+ -[DKAnalyticsHandler pendingBackupDecisionConfigurationSource]
+ -[DKAnalyticsHandler pendingBackupDecisionOutcome]
+ -[DKAnalyticsHandler setPendingBackupDecisionAgeDays:]
+ -[DKAnalyticsHandler setPendingBackupDecisionConfigurationSource:]
+ -[DKAnalyticsHandler setPendingBackupDecisionOutcome:]
+ -[DKAnalyticsHandler setPendingBackupDecisionOutcome:configurationSource:backupAgeDays:]
+ -[DKConfiguration setSource:]
+ -[DKConfiguration source]
+ -[DKEraseFlow _backupAgeDays]
+ -[DKEraseFlow _queueBackupAnalyticsWithOutcome:]
+ -[DKEraseFlow cloudUploadState]
+ -[DKEraseFlow setCloudUploadState:]
+ -[DKNotableUserDataProvider fetchNotableUserDataWithInternetConnected:completion:]
+ -[DKTelephonyProvider isPhysicalSIMModeActive]
+ GCC_except_table10
+ GCC_except_table47
+ GCC_except_table57
+ _OBJC_CLASS_$_NSTimeZone
+ _OBJC_IVAR_$_DKAnalyticsHandler._pendingBackupDecisionAgeDays
+ _OBJC_IVAR_$_DKAnalyticsHandler._pendingBackupDecisionConfigurationSource
+ _OBJC_IVAR_$_DKAnalyticsHandler._pendingBackupDecisionOutcome
+ _OBJC_IVAR_$_DKConfiguration._source
+ _OBJC_IVAR_$_DKEraseFlow._cloudUploadState
+ __OBJC_$_CLASS_METHODS_DKAnalyticsHandler
+ __OBJC_$_INSTANCE_VARIABLES_DKAnalyticsHandler
+ ___104+[DKEraseConfirmationAlertController alertControllerWithCellularPlans:physicalSIMModeActive:completion:]_block_invoke
+ ___104+[DKEraseConfirmationAlertController alertControllerWithCellularPlans:physicalSIMModeActive:completion:]_block_invoke_2
+ ___104+[DKEraseConfirmationAlertController alertControllerWithCellularPlans:physicalSIMModeActive:completion:]_block_invoke_3
+ ___104+[DKEraseConfirmationAlertController alertControllerWithCellularPlans:physicalSIMModeActive:completion:]_block_invoke_4
+ ___104+[DKEraseConfirmationAlertController alertControllerWithCellularPlans:physicalSIMModeActive:completion:]_block_invoke_5
+ ___82-[DKNotableUserDataProvider fetchNotableUserDataWithInternetConnected:completion:]_block_invoke
+ _objc_retain_x26
- +[DKEraseConfirmationAlertController alertControllerWithCellularPlans:completion:]
- -[DKEraseFlow cloudUploadSucceeded]
- -[DKEraseFlow isCloudUploadInProgress]
- -[DKEraseFlow setCloudUploadInProgress:]
- -[DKEraseFlow setCloudUploadSucceeded:]
- -[DKNotableUserDataProvider fetchNotableUserData:]
- GCC_except_table45
- GCC_except_table55
- GCC_except_table7
- _OBJC_IVAR_$_DKEraseFlow._cloudUploadInProgress
- _OBJC_IVAR_$_DKEraseFlow._cloudUploadSucceeded
- ___50-[DKNotableUserDataProvider fetchNotableUserData:]_block_invoke
- ___82+[DKEraseConfirmationAlertController alertControllerWithCellularPlans:completion:]_block_invoke
- ___82+[DKEraseConfirmationAlertController alertControllerWithCellularPlans:completion:]_block_invoke_2
- ___82+[DKEraseConfirmationAlertController alertControllerWithCellularPlans:completion:]_block_invoke_3
- ___82+[DKEraseConfirmationAlertController alertControllerWithCellularPlans:completion:]_block_invoke_4
- ___82+[DKEraseConfirmationAlertController alertControllerWithCellularPlans:completion:]_block_invoke_5
CStrings:
+ ", "
+ "-[DKNotableUserDataProvider fetchNotableUserDataWithInternetConnected:completion:]"
+ "BACKUP_NO_INTERNET_ALERT_MESSAGE"
+ "BACKUP_NO_INTERNET_ALERT_MESSAGE_APPLE_ACCOUNT"
+ "BACKUP_NO_INTERNET_ALERT_MESSAGE_APPLE_ACCOUNTS"
+ "BACKUP_NO_INTERNET_ALERT_TITLE"
+ "ERASE_WITHOUT_BACKUP"
+ "MMMMd jmm"
+ "Skipping repair mode check, device is offline"
+ "alreadyCompleted"
+ "backupAgeDays"
+ "backupOutcome"
+ "cancelledDuringUpload"
+ "configurationSkipped"
+ "configurationSource"
+ "failedUserCancelled"
+ "failedUserSkipped"
+ "notNeeded"
+ "notReached"
+ "settings"
+ "setupAssistant"
+ "skippedAtPrompt"
+ "skippedDuringUpload"
+ "uploadCompleted"
- "-[DKNotableUserDataProvider fetchNotableUserData:]"
- "CLOUD_UPLOAD_GENERIC_FAILURE_ALERT_MESSAGE_WIFI"
- "CLOUD_UPLOAD_GENERIC_FAILURE_ALERT_MULTIPLE_ACCOUNT_TITLE"
- "CLOUD_UPLOAD_GENERIC_FAILURE_ALERT_SINGLE_ACCOUNT_TITLE"
- "CLOUD_UPLOAD_GENERIC_FAILURE_ALERT_TITLE"
- "DONT_ERASE"
- "MMMMd h:mm a"
```
