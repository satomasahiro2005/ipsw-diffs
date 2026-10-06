## backupd

> `/System/Library/PrivateFrameworks/MobileBackup.framework/backupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x247984` | `0x2473c8` | **`-0x5bc`** |
| `__DATA.__objc_const` | `0x23540` | `0x23760` | **`+0x220`** |
| `__TEXT.__gcc_except_tab` | `0x9f44` | `0x9d78` | **`-0x1cc`** |
| `__TEXT.__objc_stubs` | `0x27ea0` | `0x28060` | **`+0x1c0`** |
| `__TEXT.__objc_methname` | `0x376aa` | `0x3775a` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x3116c` | `0x31219` | **`+0xad`** |
| `__DATA.__objc_data` | `0x6a90` | `0x6b30` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x686da` | `0x6863b` | **`-0x9f`** |
| `__TEXT.__objc_methlist` | `0x15e14` | `0x15e84` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0xb758` | `0xb798` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x7dd0` | `0x7e00` | **`+0x30`** |
| `__DATA_CONST.__objc_arrayobj` | `0x558` | `0x528` | **`-0x30`** |
| `__TEXT.__auth_stubs` | `0x32e0` | `0x32b0` | **`-0x30`** |
| `__TEXT.__objc_classname` | `0x211a` | `0x2140` | **`+0x26`** |
| `__DATA.__bss` | `0x1908` | `0x1928` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0xca8` | `0xc88` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x1980` | `0x1968` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x6208` | `0x61f0` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x198c` | `0x199c` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x980` | `0x990` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x690` | `0x6a0` | **`+0x10`** |
| `__TEXT.__const` | `0x1810` | `0x1820` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x65fb` | `0x65ee` | **`-0xd`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3033.0.0.0.0
+3036.0.0.0.0

+  - /System/Library/PrivateFrameworks/NANDFileAlignment.framework/NANDFileAlignment

-  Functions: 8914
-  Symbols:   1320
-  CStrings:  18380
+  Functions: 8923
+  Symbols:   1317
+  CStrings:  18396
Symbols:
+ _OBJC_CLASS_$_NANDTaskSchedulerClient
- _ACAccountStoreDidChangeNotification
- _CFNotificationCenterPostNotificationWithOptions
- _CFPreferencesAppSynchronize
- _CFPreferencesSetAppValue
CStrings:
+ "-[MBServiceAccount(RetryAfter) _clearFailureCountWithKey:]"
+ "-[MBServiceAccount(RetryAfter) _clearRetryAfterDateWithKey:]"
+ "-[MBServiceAccount(RetryAfter) _refreshRetryAfterDateSoftCancelled:]"
+ "-[MBServiceAccount(RetryAfter) _updateRetryAfterDate:forKey:ignoreExistingDate:]"
+ "=backoff= Clearing %{public}@ (%{public}@) for account %{public}@"
+ "=backoff= Clearing %{public}@ for account %{public}@"
+ "=backoff= MissingEncryptionKey failureCount:%lu, backoff:%G"
+ "=backoff= Not updating %{public}@ for account %{public}@: \"%{public}@\" (%.3f, %lu)"
+ "=backoff= QuotaExceeded failureCount:%lu, backoff:%G"
+ "=backoff= Updating %{public}@ based on server response for account %{public}@: %{public}@"
+ "=backoff= Updating %{public}@ for account %{public}@: %lu(%lu)"
+ "=backoff= Updating %{public}@ from \"%{public}@\" to \"%{public}@\" for account %{public}@ (%d)"
+ "=backoff= failureCount:%lu, backoff:%G"
+ "=backoff= softCancelled:%d, backoff:%G, backoffDate:\"%{public}@\", account:%{public}@"
+ "@\"NANDTaskSchedulerClient\""
+ "Failed to set kMBNotUploadedDatabaseIndexFlag for %@:%@: %@"
+ "Ignoring SQLite compaction failure for %@"
+ "MBAtomicBool"
+ "MBAtomicULong"
+ "MBServiceAccount+SchedulerRetryAfter.m"
+ "Quota exceeded (simulated)"
+ "QuotaExceededFailureCount"
+ "QuotaExceededRetryAfter"
+ "Simulated SQLite compaction error"
+ "Starting NAND task scheduler"
+ "Stopping NAND task scheduler"
+ "T@\"MBErrorInjector\",&,N,V_sqliteErrorInjector"
+ "T@\"NANDTaskSchedulerClient\",&,V_nandTaskScheduler"
+ "T@\"NSDate\",R"
+ "[[MBServiceAccount _validFailureCountKeys] containsObject:key]"
+ "[[MBServiceAccount _validRetryAfterKeys] containsObject:key]"
+ "_clearAllFailureCounts"
+ "_clearAllRetryAfterDates"
+ "_clearFailureCountWithKey:"
+ "_clearRetryAfterDateWithKey:"
+ "_markDatabaseWithSQLiteCompactionFailure:error:"
+ "_nandTaskScheduler"
+ "_refreshRetryAfterDateSoftCancelled:"
+ "_sqliteErrorInjector"
+ "_updateFailureCountsWithLastBackupError:lowCellularBudget:"
+ "_updateRetryAfterDate:forKey:"
+ "_updateRetryAfterDate:forKey:ignoreExistingDate:"
+ "_validFailureCountKeys"
+ "_validRetryAfterKeys"
+ "backupPathsToFailSQLiteCompactionRegex"
+ "clearRetryAfterOnBackupSuccess"
+ "exchange:"
+ "fetchAdd:"
+ "increment"
+ "initWithInitialValue:"
+ "isQuotaExceededError:"
+ "nandTaskScheduler"
+ "onBatteryRetryAfterDate"
+ "retryAfterDate"
+ "sendMigrationPing:"
+ "setNandTaskScheduler:"
+ "setSqliteErrorInjector:"
+ "simulateQuotaExceededError"
+ "sqliteErrorInjector"
+ "stopMigrationPing"
+ "updateRetryAfterOnBackupFailureWithError:lowCellularBudget:"
+ "updateRetryAfterOnBackupStart"
+ "updateRetryAfterOnUnlockDuringScheduledBackup"
- "-[MBBackupScheduler _backoffDateForAccount:softCancelled:]"
- "-[MBBackupScheduler _clearFailureCountWithKey:account:]"
- "-[MBBackupScheduler _clearRetryAfterDateWithKey:account:]"
- "-[MBBackupScheduler _updateRetryAfterDate:forKey:account:ignoreExistingDate:]"
- "-[MBBackupScheduler _updateRetryAfterDateAfterUnlockForAccount:]"
- "=scheduler= %{public}@, failureCount:%lu, backoff:%G"
- "=scheduler= Clearing %{public}@ (%{public}@) for account %{public}@"
- "=scheduler= Not updating %{public}@ for account %{public}@: \"%{public}@\" (%.3f, %lu)"
- "=scheduler= Updating %{public}@ based on server response for account %{public}@: %{public}@"
- "=scheduler= Updating %{public}@ for account %{public}@: %lu(%lu)"
- "=scheduler= Updating %{public}@ from \"%{public}@\" to \"%{public}@\" for account %{public}@ (%d)"
- "=scheduler= softCancelled:%d, backoff:%G, backoffDate:\"%{public}@\", account:%{public}@"
- "Coordinator couldn't be found for %@. Couldn't stop tracking it"
- "Coordinator couldn't be found for %@. Couldn't update progress"
- "IsEnabled"
- "Unexpected container type: %d"
- "[key isEqualToString:kMBFailureCountKey] || [key isEqualToString:kMBMissingEncryptionKeyFailureCountKey]"
- "[key isEqualToString:kMBRetryAfterKey] || [key isEqualToString:kMBMissingEncryptionKeyRetryAfterKey] || [key isEqualToString:kMBOnBatteryRetryAfterKey]"
- "[key isEqualToString:kMBRetryAfterKey] || [key isEqualToString:kMBOnBatteryRetryAfterKey] || [key isEqualToString:kMBMissingEncryptionKeyRetryAfterKey]"
- "_backoffDateForAccount:softCancelled:"
- "_clearAllFailureCountsForAccount:"
- "_clearAllRetryAfterDatesForAccount:"
- "_clearFailureCountWithKey:account:"
- "_clearRetryAfterDateWithKey:account:"
- "_failedToCompactSQLiteDatabase:"
- "_onBatteryRetryAfterDateForAccount:"
- "_refreshRetryAfterDateForAccount:softCancelled:"
- "_retryAfterDateForAccount:"
- "_updateFailureCountsForAccount:lastBackupError:canceled:lowCellularBudget:"
- "_updateRetryAfterDate:forKey:account:"
- "_updateRetryAfterDate:forKey:account:ignoreExistingDate:"
- "_updateRetryAfterDateAfterUnlockForAccount:"
- "background app group restore"
- "background app plugin restore"
- "backgroundAppGroupRestoreModeWithBundleID:"
- "backgroundAppPluginRestoreModeWithBundleID:"
- "backgroundAppRestoreModeWithBundleID:errorCode:"
- "backgroundContainerRestoreModeWithContainer:"
- "enableBackupInPreferences"
- "restoreModeWithType:value:"
- "restoreTypeForContainerType:"
- "result.count == 1"
- "stopTrackingCoordinatorWithBundleID:success:"
- "updateProgressForCoordinatorWithBundleID:progress:"
- "v32@?0@\"NSString\"8@\"NSDate\"16^B24"
- "v40@0:8@16@24B32B36"
- "v44@0:8@16@24@32B40"
```
