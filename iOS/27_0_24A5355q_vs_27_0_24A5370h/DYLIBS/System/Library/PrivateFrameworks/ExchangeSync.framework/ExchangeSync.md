## ExchangeSync

> `/System/Library/PrivateFrameworks/ExchangeSync.framework/ExchangeSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa750` | `0xa71c` | **`-0x34`** |

### Other Changes

```diff

-2075.0.0.0.0
+2076.0.0.0.0
Functions:
~ -[ESAccountLoader init] : 1480 -> 1472
~ -[ACAccountStore(ESExtensions) _esAccountsWithAccountTypeIdentifiers:enabledForDADataclasses:filterOnDataclasses:withCompletion:] : 1024 -> 1020
~ ___129-[ACAccountStore(ESExtensions) _esAccountsWithAccountTypeIdentifiers:enabledForDADataclasses:filterOnDataclasses:withCompletion:]_block_invoke_3 : 320 -> 316
~ ___129-[ACAccountStore(ESExtensions) _esAccountsWithAccountTypeIdentifiers:enabledForDADataclasses:filterOnDataclasses:withCompletion:]_block_invoke_4 : 776 -> 772
~ ___129-[ACAccountStore(ESExtensions) _esAccountsWithAccountTypeIdentifiers:enabledForDADataclasses:filterOnDataclasses:withCompletion:]_block_invoke_4.13 : 420 -> 416
~ -[ACAccountStore(ESExtensions) es_accountsWithAccountTypeIdentifiers:outError:] : 564 -> 560
~ -[ESLocalDBWatcher _handleCalChangeNotification] : 1256 -> 1252
~ -[ESLocalDBWatcher noteCalDBDirChanged] : 1172 -> 1160
~ -[ESLocalDBHelper executeAllSaveRequests] : 360 -> 356
~ +[ESAccount oneshotListOfAccountIDs] : 532 -> 528
```
