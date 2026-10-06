## EmailAddressing

> `/System/Library/PrivateFrameworks/EmailAddressing.framework/EmailAddressing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68d4` | `0x6888` | **`-0x4c`** |
| `__TEXT.__gcc_except_tab` | `0xaf8` | `0xb00` | **`+0x8`** |

### Other Changes

```diff

-3891.100.17.2.4
+3893.100.7.0.0

-  Symbols:   322
+  Symbols:   323
Symbols:
+ _objc_retain_x27
Functions:
~ +[EAEmailAddressParser _componentsForFullAddress:rawAddressIndexes:localPartIndexes:domainIndexes:] : 1424 -> 1448
~ -[NSString(EmailAddressingAdditions) ea_isLegalEmailAddress] : 1244 -> 1228
~ -[NSString(EmailAddressingAdditions) ea_uncommentedAddress] : 1148 -> 1164
~ _EAAddressComment : 1336 -> 1340
~ +[EAEmailAddressLists addressListFromHeaderValue:] : 2080 -> 1956
~ +[EAEmailAddressLists componentsSeparatedByCharactersRespectingQuotesAndParens:forString:] : 624 -> 632
~ +[EAEmailAddressLists addressStringFromAddressList:] : 1128 -> 1120
~ +[EAEmailAddressLists rawAddressListFromFullAddressList:] : 428 -> 424
~ +[EAEmailAddressLists displayNameFromAddressList:] : 452 -> 448
~ +[EAEmailAddressParser isLegalEmailAddress:] : 1512 -> 1500
~ +[EAEmailAddressParser displayNameFromAddress:cacheResults:] : 1908 -> 1948
~ -[EAEmailAddressSet allObjects] : 396 -> 392
~ -[EAEmailAddressSet countByEnumeratingWithState:objects:count:] : 176 -> 180
```
