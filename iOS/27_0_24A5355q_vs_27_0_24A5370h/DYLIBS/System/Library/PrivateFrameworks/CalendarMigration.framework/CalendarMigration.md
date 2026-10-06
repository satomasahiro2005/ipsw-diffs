## CalendarMigration

> `/System/Library/PrivateFrameworks/CalendarMigration.framework/CalendarMigration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf594` | `0xf54c` | **`-0x48`** |

### Other Changes

```diff

-1287.0.0.0.0
+1289.0.0.0.0
Functions:
~ +[CalMigrationToolArgumentParser parseOptionsFromCommandLineArguments:printUsage:error:] : 1172 -> 1168
~ -[CalPlistSavingMigrationAccountStore topLevelAccountsWithAccountTypeIdentifier:error:] : 676 -> 668
~ -[CalPlistSavingMigrationAccountStore childAccountsForAccount:withTypeIdentifier:] : 1072 -> 1064
~ -[CalCalendarMigrationCalDAVPrincipal _packedPreferredCalendarUserAddresses] : 384 -> 380
~ -[CalCalendarMigrationCalDAVPrincipal _anyCalendarUserAddressIsEquivalentToURL:] : 280 -> 276
~ -[CalAggregateMigrationController shouldPerformMigration] : 256 -> 252
~ -[CalAggregateMigrationController migrationDidFinishWithResult:] : 248 -> 244
~ +[CalMigrationUtilities subdirectoriesInDirectory:withPrivacySafePathProvider:error:] : 700 -> 696
~ -[CalCompositeCalendarMigrationFailureRecorder recordMigrationFailure:] : 264 -> 260
~ -[CalCompositeCalendarMigrationFailureRecorder reportRecordedFailures] : 240 -> 236
~ -[CalReminderMigrationContext _loadAccountsIfNeeded] : 752 -> 740
~ -[CalReminderMigrationContext _sortAddedReminderListsInAccountChangeItem:] : 616 -> 612
~ -[CalCalendarMigrationSubscriptionInfo dictionaryForParentAccountProperties] : 404 -> 400
~ +[CalMigrationBackup shouldBackupCalendarDirectory:withPrivacySafePathProvider:] : 1088 -> 1084
```
