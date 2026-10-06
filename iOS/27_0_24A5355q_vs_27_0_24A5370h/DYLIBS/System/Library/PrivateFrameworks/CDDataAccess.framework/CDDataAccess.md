## CDDataAccess

> `/System/Library/PrivateFrameworks/CDDataAccess.framework/CDDataAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27560` | `0x274a0` | **`-0xc0`** |

### Other Changes

```diff

-4034.15.0.0.0
+4037.1.0.0.0
Functions:
~ -[DAAccount isDisabled] : 272 -> 268
~ -[DAAccount accountContainsEmailAddress:] : 292 -> 288
~ -[DAAccount accountHasSignificantPropertyChangesFromOldAccountInfo:] : 908 -> 900
~ +[DAAccount(AuthenticationExtensions) oneshotListOfAccountIDs] : 532 -> 528
~ +[DAAccount(AuthenticationExtensions) reacquireClientRestrictions:] : 296 -> 292
~ -[DAAccountLoader init] : 1168 -> 1160
~ -[DAKeychain passwordForAccountWithPersistentUUID:expectedAccessibility:shouldSetAccessibility:passwordExpected:] : 968 -> 964
~ -[DAKeychain migratePasswordForAccount:] : 1188 -> 1184
~ -[DAResolveRecipientsRequest hash] : 260 -> 256
~ -[DAResolvedRecipient description] : 1028 -> 1024
~ -[DAAccount(Searching) cancelAllSearchQueries] : 500 -> 496
~ -[ACAccountStore(DAExtensions) _daAccountsWithAccountTypeIdentifiers:enabledForDADataclasses:filterOnDataclasses:withCompletion:] : 1024 -> 1020
~ ___129-[ACAccountStore(DAExtensions) _daAccountsWithAccountTypeIdentifiers:enabledForDADataclasses:filterOnDataclasses:withCompletion:]_block_invoke_3 : 320 -> 316
~ ___129-[ACAccountStore(DAExtensions) _daAccountsWithAccountTypeIdentifiers:enabledForDADataclasses:filterOnDataclasses:withCompletion:]_block_invoke_4 : 776 -> 772
~ ___129-[ACAccountStore(DAExtensions) _daAccountsWithAccountTypeIdentifiers:enabledForDADataclasses:filterOnDataclasses:withCompletion:]_block_invoke_4.40 : 420 -> 416
~ -[ACAccountStore(DAExtensions) da_accountsWithAccountTypeIdentifiers:outError:] : 564 -> 560
~ _addNullRunLoopSourceForRunLoopAndModes : 456 -> 452
~ -[NSData(DAHexString) da_hexString] : 368 -> 372
~ -[NSDictionary(DAExtensions) DAObjectForKeyCaseInsensitive:] : 328 -> 324
~ -[NSDictionary(DAExtensions) DAMergeOverrideDictionary:] : 468 -> 464
~ -[NSError(DADAExtendedDescription) DAExtendedDescription] : 592 -> 588
~ -[DATaskManager allTasks] : 960 -> 948
~ -[DATaskManager cancelAllTasks] : 248 -> 244
~ -[DATaskManager _taskInQueueForcesNetworkConnection:] : 272 -> 268
~ -[DATaskManager taskDidFinish:] : 4492 -> 4476
~ -[DATaskManager _requestCancelTasksWithReason:] : 396 -> 392
~ -[DATaskManager _reactivateHeldTasks] : 704 -> 696
~ -[DATaskManager _cancelTasksWithReason:] : 612 -> 608
~ -[DAPowerAssertionManager dropPowerAssertionsForGroupIdentifier:] : 820 -> 816
~ -[DAPowerAssertionManager reattainPowerAssertionsForGroupIdentifier:] : 820 -> 816
~ -[DALocalDBGateKeeper _abortWaiterForWrappers:] : 744 -> 736
~ -[DALocalDBGateKeeper _notifyWaitersForDataclasses:] : 844 -> 840
~ -[_DAContactsAccountContactsProvider allAccounts] : 388 -> 384
~ -[DABabysitter _l_reloadBabysitterWaitersWithRefreshingWaitersPrefs:failedWaitersPrefs:restrictedWaitersPrefs:] : 3216 -> 3196
~ -[DABabysitter _l_decrementRefreshCountForWaiterID:operationName:] : 592 -> 588
~ -[DABabysitter _populatedStringDictionaryWithWaitersDictionary:] : 456 -> 452
~ -[_DAContactsAccountABLegacyProvider allAccounts] : 336 -> 332
```
