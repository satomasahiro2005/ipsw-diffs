## CalendarDaemon

> `/System/Library/PrivateFrameworks/CalendarDaemon.framework/CalendarDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77890` | `0x77974` | **`+0xe4`** |
| `__TEXT.__oslogstring` | `0x8da3` | `0x8ddb` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x1c70` | `0x1c80` | **`+0x10`** |

### Other Changes

```diff

-1246.1.4.0.0
+1246.2.1.0.0

-  Symbols:   5612
-  CStrings:  1818
+  Symbols:   5614
+  CStrings:  1819
Symbols:
+ +[CADOperationGroupUtil _defaultCalendarIDForNewEventsInStoreWithID:connection:inDatabase:updateDefaultIfNeeded:defaultExists:]
+ _CalDatabaseClearDefaultCalendarIfDefaultIsInAuxDatabaseWithID
+ _CalDatabaseCopyOrCreateDefaultCalendarForNewEventsUpdateIfNeeded
- +[CADOperationGroupUtil defaultCalendarIDForNewEventsInStoreWithID:connection:inDatabase:defaultExists:]
Functions:
~ ___142-[CADXPCImplementation(CADDatabaseOperationGroup) CADDatabaseCommitDeletes:updatesAndInserts:options:andFetchChangesSinceTimestamp:withReply:]_block_invoke_2.38 : 1400 -> 1428
~ ___116-[CADXPCImplementation(CADDatabaseOperationGroup) findDatabaseForObject:withUpdates:personas:accounts:nextTempDBID:]_block_invoke : 852 -> 984
~ +[CADOperationGroupUtil defaultCalendarIDForNewEventsInStoreWithID:connection:inDatabase:defaultExists:] -> +[CADOperationGroupUtil _defaultCalendarIDForNewEventsInStoreWithID:connection:inDatabase:updateDefaultIfNeeded:defaultExists:] : 968 -> 980
~ ___98+[CADOperationGroupUtil defaultCalendarForNewEventsInDelegateSource:withConnection:limitedAccess:]_block_invoke_2 : 324 -> 368
~ ___98+[CADOperationGroupUtil defaultCalendarForNewEventsInDelegateSource:withConnection:limitedAccess:]_block_invoke_3 : 100 -> 104
~ ___98+[CADOperationGroupUtil defaultCalendarForNewEventsInDelegateSource:withConnection:limitedAccess:]_block_invoke_4 : 336 -> 340
~ ___98+[CADOperationGroupUtil defaultCalendarForNewEventsInDelegateSource:withConnection:limitedAccess:]_block_invoke_5 : 88 -> 92
CStrings:
+ "Failed to get container info for account %{public}@: %@"
```
