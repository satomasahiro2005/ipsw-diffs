## MobileSync

> `/System/Library/PrivateFrameworks/MobileSync.framework/MobileSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x153c0` | `0x153a0` | **`-0x20`** |

### Other Changes

```diff

-1023.0.0.0.0
+1024.0.0.0.0
Functions:
~ __reallyCopySetOfEmailAddressesFromMessageFramework : 424 -> 420
~ -[ACAccountStore(SyncPrivate) hasMailAccountsForSync] : 312 -> 308
~ -[ACAccountStore(SyncPrivate) mailAccountsForSync] : 344 -> 340
~ _MailAccountsDataSourceProcessChanges : 428 -> 424
~ _MailAccountsDataSourceCommit : 1328 -> 1324
~ ____bestiCloudUsernameFromEmails_block_invoke_2 : 256 -> 252
~ ____bestiCloudUsernameFromEmails_block_invoke_3 : 568 -> 564
~ __processRecord : 1760 -> 1756
```
