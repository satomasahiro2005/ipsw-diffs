## AppStoreUtilities

> `/System/Library/PrivateFrameworks/AppStoreUtilities.framework/AppStoreUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfed4` | `0xfe94` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x668` | `0x670` | **`+0x8`** |

### Other Changes

```diff

-13.0.33.0.0
+13.0.36.0.0
Functions:
~ -[ASUSQLiteCursor initWithStatement:] : 560 -> 536
~ -[ASUSQLiteMemoryEntity setValues:forProperties:count:] : 104 -> 120
~ -[ASUSQLiteMemoryEntity setValues:forExternalProperties:count:] : 104 -> 120
~ +[ASUSQLiteEntity _insertValues:intoTable:withPersistentID:onConnection:] : 884 -> 880
~ ___37-[ASUSQLiteEntity deleteFromDatabase]_block_invoke : 432 -> 428
~ -[ASUSQLiteEntity getValuesForProperties:] : 896 -> 892
~ ___43-[ASUSQLiteEntity setValuesWithDictionary:]_block_invoke_5 : 324 -> 320
~ ___73+[ASUSQLiteEntity _insertValues:intoTable:withPersistentID:onConnection:]_block_invoke : 332 -> 328
~ -[ASUSQLiteQuery copySelectSQLWithProperties:] : 348 -> 344
~ -[ASUSQLiteQuery createTemporaryTableWithName:properties:] : 612 -> 608
~ -[ASUSQLiteQuery enumeratePersistentIDsAndProperties:usingBlock:] : 552 -> 548
~ -[ASUSQLiteQueryDescriptor _newSelectSQLWithProperties:columns:] : 1088 -> 1080
~ -[ASUSQLiteContainsPredicate applyBinding:atIndex:] : 312 -> 308
~ +[ASUSQLiteCompoundPredicate predicateWithProperty:values:comparisonType:] : 388 -> 384
~ -[ASUSQLiteCompoundPredicate applyBinding:atIndex:] : 276 -> 272
~ -[ASUSQLiteCompoundPredicate SQLForEntityClass:] : 428 -> 424
~ -[ASUSQLiteCompoundPredicate SQLJoinClausesForEntityClass:] : 348 -> 344
~ ___75-[ASUSQLiteDatabaseStoreSchema _migrateToVersion:usingMapping:isReattempt:]_block_invoke : 608 -> 604
~ -[ASUSQLiteConnection _close] : 372 -> 368
~ ___51-[ASUSQLiteConnection _flushAfterTransactionBlocks]_block_invoke : 248 -> 244
```
