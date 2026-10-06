## DataAccess

> `/System/Library/PrivateFrameworks/DataAccess.framework/DataAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3afbc` | `0x3ae80` | **`-0x13c`** |

### Other Changes

```diff

-2703.0.0.0.0
+2704.0.0.0.0
Functions:
~ -[DAAccount isDisabled] : 272 -> 268
~ -[DAAccount accountContainsEmailAddress:] : 292 -> 288
~ -[DAAccount removeDBSyncDataForAccountChange:] : 1956 -> 1952
~ -[DAAccount canSaveWithAccountProvider:] : 924 -> 920
~ -[DAAccount accountHasSignificantPropertyChangesWithChangeInfo:] : 972 -> 964
~ -[DAAccountLoader init] : 1196 -> 1188
~ +[DAAnalyticsReporter reportActiveExchangeOAuthAccountsCount] : 616 -> 612
~ -[DAKeychain passwordForAccountWithPersistentUUID:expectedAccessibility:shouldSetAccessibility:passwordExpected:] : 968 -> 964
~ ___41-[DAKeychain removePersistentCredentials]_block_invoke : 452 -> 448
~ -[DAKeychain migratePasswordForAccount:] : 1188 -> 1184
~ +[DAAccountChangeHandler _handleAccountAddOrModify:withChangeInfo:inStore:accountUpdater:] : 1156 -> 1152
~ +[DAAccountChangeHandler _sanityCheckChildSubCalAccountsWithParent:inStore:accountUpdater:] : 2716 -> 2676
~ +[DAAccountChangeHandler _findSubscribedCalendarForAccount:inEventStore:] : 376 -> 372
~ +[DAAccountChangeHandler _sanityCheckChildAccountOfType:withParent:accountChangeInfo:inStore:updater:] : 4636 -> 4628
~ +[DAAccountChangeHandler _sanityCheckEnabledDataclassesOnExchangeAccountInfo:] : 348 -> 344
~ -[DAResolveRecipientsRequest hash] : 260 -> 256
~ -[DAResolvedRecipient description] : 1028 -> 1024
~ -[DAAccount(Searching) cancelAllSearchQueries] : 500 -> 496
~ -[ACAccountStore(DAExtensions) _daAccountsWithAccountTypeIdentifiers:enabledForDADataclasses:filterOnDataclasses:withCompletion:] : 1024 -> 1020
~ ___129-[ACAccountStore(DAExtensions) _daAccountsWithAccountTypeIdentifiers:enabledForDADataclasses:filterOnDataclasses:withCompletion:]_block_invoke_3 : 320 -> 316
~ ___129-[ACAccountStore(DAExtensions) _daAccountsWithAccountTypeIdentifiers:enabledForDADataclasses:filterOnDataclasses:withCompletion:]_block_invoke_4 : 776 -> 772
~ ___129-[ACAccountStore(DAExtensions) _daAccountsWithAccountTypeIdentifiers:enabledForDADataclasses:filterOnDataclasses:withCompletion:]_block_invoke_4.42 : 420 -> 416
~ -[ACAccountStore(DAExtensions) da_accountsWithAccountTypeIdentifiers:outError:] : 1024 -> 1016
~ _addNullRunLoopSourceForRunLoopAndModes : 456 -> 452
~ -[NSData(DAHexString) da_hexString] : 368 -> 372
~ -[NSDictionary(DAExtensions) DAObjectForKeyCaseInsensitive:] : 328 -> 324
~ -[NSDictionary(DAExtensions) DAMergeOverrideDictionary:] : 468 -> 464
~ -[NSError(DADAExtendedDescription) DAExtendedDescription] : 592 -> 588
~ -[DATaskManager allTasks] : 976 -> 964
~ -[DATaskManager cancelAllTasks] : 248 -> 244
~ -[DATaskManager _taskInQueueForcesNetworkConnection:] : 272 -> 268
~ -[DATaskManager taskDidFinish:] : 4776 -> 4760
~ -[DATaskManager _requestCancelTasksWithReason:] : 396 -> 392
~ -[DATaskManager _reactivateHeldTasks] : 748 -> 740
~ -[DATaskManager _cancelTasksWithReason:] : 620 -> 616
~ -[DALocalDBHelper executeAllSaveRequests] : 360 -> 356
~ -[DAPowerAssertionManager dropPowerAssertionsForGroupIdentifier:] : 820 -> 816
~ -[DAPowerAssertionManager reattainPowerAssertionsForGroupIdentifier:] : 820 -> 816
~ -[_DAABLegacyContainerProvider allContainers] : 340 -> 336
~ -[_DAABLegacyContainerProvider allContainersForAccountWithExternalIdentifier:] : 368 -> 364
~ +[DAAccountUpgrader _updateFacebookAccountAuthenticationTypes] : 1000 -> 996
~ +[DAAccountUpgrader _upgradeDAAccounts] : 1088 -> 1084
~ -[_DAContactsContainerProvider containerWithExternalIdentifier:forAccountWithExternalIdentifier:] : 644 -> 640
~ -[_DAContactsContainerProvider allContainers] : 424 -> 420
~ -[_DAContactsContainerProvider allContainersForAccountWithExternalIdentifier:] : 572 -> 568
~ +[DAStoreSyncStatusUpdater resetSyncStatusIfNecessaryForStoresOfType:] : 440 -> 436
~ -[DALocalDBWatcher _handleCalChangeNotification] : 1256 -> 1252
~ -[DALocalDBWatcher noteCalDBDirChanged] : 1172 -> 1160
~ -[DALocalDBGateKeeper _abortWaiterForWrappers:] : 768 -> 760
~ -[DALocalDBGateKeeper _notifyWaitersForDataclasses:] : 908 -> 904
~ -[_DAContactsAccountContactsProvider allAccounts] : 388 -> 384
~ ___45-[DAPriorityManager setupProcessStateMonitor]_block_invoke : 592 -> 588
~ -[DABabysitter _reloadBabysitterProperties] : 3340 -> 3320
~ -[DABabysitter _decrementRefreshCountForWaiterID:operationName:] : 648 -> 644
~ -[_DAContactsAccountABLegacyProvider allAccounts] : 336 -> 332
```
