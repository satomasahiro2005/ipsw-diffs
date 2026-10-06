## DASubCal

> `/System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DASubCal.framework/DASubCal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8504` | `0x84ec` | **`-0x18`** |

### Other Changes

```diff

-2703.0.0.0.0
+2704.0.0.0.0
Functions:
~ -[SubCalAccount upgradeAccountSpecificPropertiesOnAccount:inStore:parentAccount:] : 476 -> 472
~ -[SubCalAccount removeDBSyncDataForAccountChange:] : 564 -> 560
~ -[SubCalAccount removeDataFromCalendar:forAccountChange:] : 1548 -> 1540
~ +[SubCalLocalDBHelper _existingCalendarInCalDAVSourceWithExternalID:inSource:] : 532 -> 528
~ ___40+[SubCalURLRequest _initializeFileCache]_block_invoke : 988 -> 984
```
