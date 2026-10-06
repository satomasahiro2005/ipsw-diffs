## DALDAP

> `/System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DALDAP.framework/DALDAP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55a8` | `0x557c` | **`-0x2c`** |

### Other Changes

```diff

-2703.0.0.0.0
+2704.0.0.0.0
Functions:
~ -[LDAPAccount ingestBackingAccountInfoProperties] : 560 -> 556
~ ___49-[LDAPAccount ingestBackingAccountInfoProperties]_block_invoke : 368 -> 364
~ -[LDAPAccount _reallyCancelSearchQuery:] : 456 -> 452
~ -[LDAPAccount _reallyCancelAllSearchQueries] : 292 -> 288
~ -[LDAPAccount ldapGetDefaultSearchBaseTask:completedWithStatus:error:defaultSearchBase:] : 512 -> 508
~ -[LDAPSearchTask _copySearchStringForQueryInput:] : 716 -> 712
~ ___31-[LDAPSearchTask _performQuery]_block_invoke_3 : 924 -> 912
~ ___45-[LDAPGetDefaultSearchBaseTask _performQuery]_block_invoke_3 : 984 -> 980
~ -[NSString(LDAPExtensions) ldapHumanReadableStringFromSearchBase] : 528 -> 524
```
