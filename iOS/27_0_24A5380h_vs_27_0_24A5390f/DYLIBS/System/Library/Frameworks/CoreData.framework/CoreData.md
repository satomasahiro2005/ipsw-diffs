## CoreData

> `/System/Library/Frameworks/CoreData.framework/CoreData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32fd90` | `0x331154` | **`+0x13c4`** |
| `__TEXT.__cstring` | `0x3bceb` | `0x3bf28` | **`+0x23d`** |
| `__TEXT.__oslogstring` | `0x36758` | `0x36910` | **`+0x1b8`** |
| `__AUTH_CONST.__cfstring` | `0x1fce0` | `0x1fdc0` | **`+0xe0`** |
| `__AUTH_CONST.__objc_const` | `0x25d78` | `0x25dc8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x108a0` | `0x108d8` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x77a0` | `0x77d8` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x6218` | `0x6240` | **`+0x28`** |
| `__DATA_DIRTY.__bss` | `0x698` | `0x6c0` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x187a0` | `0x187c8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x2db8` | `0x2dd8` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x4bc8` | `0x4be8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x1890` | `0x1898` | **`+0x8`** |

### Other Changes

```diff

-1624.0.0.0.0
+1627.0.0.0.0

-  Functions: 9325
-  Symbols:   17595
-  CStrings:  8316
+  Functions: 9338
+  Symbols:   17613
+  CStrings:  8339
Symbols:
+ +[NSManagedObject(_PFDynamicAccessorsAndPropertySupport) allocBatch:withEntity:andContext:count:]
+ +[NSManagedObject(_PFDynamicAccessorsAndPropertySupport) allocWithEntity:context:]
+ +[NSManagedObjectModel _invalidateStaticCaches]
+ +[NSManagedObjectModel initialize]
+ +[_PFRoutines stringByStrippingLeadingByteOrderMark:]
+ -[NSCoreDataCoreSpotlightDelegate _asyncContextBlock:completion:]
+ -[NSCoreDataCoreSpotlightDelegate _deletionErrorToReturn]
+ -[NSCoreDataFullTextNaturalLanguageTokenizerProvider tokenizerIdentifier]
+ -[NSEntityDescription _createCachesForNoClassesVariant]
+ -[NSEntityDescription _entityClassForContext:]
+ -[NSManagedObjectContext _setXPCServerContext:]
+ -[NSManagedObjectModel _createCachesForNoClassesVariant]
+ -[NSManagedObjectModel(CoreDataSPI) initWithContentsOfURL:allowCaching:]
+ GCC_except_table111
+ GCC_except_table124
+ GCC_except_table134
+ GCC_except_table137
+ GCC_except_table143
+ GCC_except_table154
+ GCC_except_table243
+ GCC_except_table247
+ GCC_except_table260
+ GCC_except_table268
+ GCC_except_table290
+ GCC_except_table298
+ GCC_except_table300
+ GCC_except_table303
+ GCC_except_table312
+ GCC_except_table317
+ GCC_except_table43
+ GCC_except_table66
+ _OBJC_IVAR_$_NSEntityDescription._propertyAccessors
+ _OBJC_IVAR_$_NSSQLEntity_DerivedAttributesExtension._triggerSQLLock
+ _OBJC_IVAR_$__NSSQLiteStoreMigrator._historyModel
+ ___30-[NSEntityDescription dealloc]_block_invoke
+ ___65-[NSCoreDataCoreSpotlightDelegate _asyncContextBlock:completion:]_block_invoke
+ ___77-[NSCoreDataCoreSpotlightDelegate deleteSpotlightIndexWithCompletionHandler:]_block_invoke_2
+ ____PFBackgroundRuntimeProviderCacheUIApplicationInstance_block_invoke
+ ___block_descriptor_40_e9_v16?0^8l
+ ___block_descriptor_64_e8_32o40b48b56w_e5_v8?0lw56l8s32l8s40l8s48l8
+ ___pf_isProcess_partlycloudd
+ ___pf_isProcess_partlycloudd_debug
+ ___pf_isProcess_voicebankingd
+ __kvcPropertysPublicValidationMethods
- +[NSManagedObject(_PFDynamicAccessorsAndPropertySupport) allocBatch:withEntity:count:]
- +[NSManagedObject(_PFDynamicAccessorsAndPropertySupport) allocWithEntity:]
- -[NSCoreDataCoreSpotlightDelegate _asyncContextBlock:]
- -[NSEntityDescription _entityClass]
- -[NSPersistentStoreCoordinator _repairFullTextIndiciesForStoreWithIdentifier:synchronous:]
- GCC_except_table114
- GCC_except_table138
- GCC_except_table146
- GCC_except_table152
- GCC_except_table177
- GCC_except_table196
- GCC_except_table241
- GCC_except_table246
- GCC_except_table259
- GCC_except_table267
- GCC_except_table288
- GCC_except_table295
- GCC_except_table299
- GCC_except_table301
- GCC_except_table311
- GCC_except_table316
- GCC_except_table42
- GCC_except_table80
- _OBJC_IVAR_$_NSEntityDescription._kvcPropertyAccessors
- ___54-[NSCoreDataCoreSpotlightDelegate _asyncContextBlock:]_block_invoke
- ___block_descriptor_56_e8_32o40b48w_e5_v8?0lw48l8s32l8s40l8
CStrings:
+ "%%"
+ "%K"
+ "CDCS OS-driven index deletion abandoned; delivering completion for index %@"
+ "CDCS OS-driven reindex (%lu identifiers) acknowledged without reindexing (reindex abandoned) for index %@"
+ "CDCS OS-driven reindex (all items) acknowledged without reindexing (reindex abandoned) for index %@"
+ "CoreData: error: CDCS OS-driven index deletion abandoned; delivering completion for index %@\n"
+ "CoreData: error: CDCS OS-driven reindex (%lu identifiers) acknowledged without reindexing (reindex abandoned) for index %@\n"
+ "CoreData: error: CDCS OS-driven reindex (all items) acknowledged without reindexing (reindex abandoned) for index %@\n"
+ "CoreData: error: Finished rebuilding full-text indicies for store - %@ (tokenizer=%@)\n"
+ "CoreData: error: Rebuilding full-text indexes for store - %@ (storedTokenizer=%@, currentTokenizer=%@)\n"
+ "CoreData: error: sqlite3_db_config for SQLITE_DBCONFIG_FP_DIGITS failed: %d\n"
+ "CoreData: warning: CDCS OS-driven index deletion abandoned; delivering completion for index %@\n"
+ "CoreData: warning: CDCS OS-driven reindex (%lu identifiers) acknowledged without reindexing (reindex abandoned) for index %@\n"
+ "CoreData: warning: CDCS OS-driven reindex (all items) acknowledged without reindexing (reindex abandoned) for index %@\n"
+ "CoreData: warning: Finished rebuilding full-text indicies for store - %@ (tokenizer=%@)\n"
+ "CoreData: warning: Rebuilding full-text indexes for store - %@ (storedTokenizer=%@, currentTokenizer=%@)\n"
+ "Finished rebuilding full-text indicies for store - %@ (tokenizer=%@)"
+ "NSPersistentStoreFullTextTokenizerIdentifier"
+ "Predicate string '%@' contains unresolved format specifiers"
+ "Rebuilding full-text indexes for store - %@ (storedTokenizer=%@, currentTokenizer=%@)"
+ "_PFManagedObject_coerceValueForKeyWithDescription"
+ "_allocWithEntity"
+ "_batchRetainedObjects:"
+ "_implicitObservationInfoForEntity:"
+ "_retainedObjectWithID:"
+ "allocBatch:"
+ "com.apple.coredata.tokenizer.default.v1"
+ "initWithEntity:"
+ "partlycloudd"
+ "partlycloudd_debug"
+ "sqlite3_db_config for SQLITE_DBCONFIG_FP_DIGITS failed: %d"
+ "v16@?0^@8"
+ "voicebankingd"
- "CoreData: annotation: Deferring full-text index repair until after migration is complete (NSPersistentStoreCoordinatorIsMigratingStoreWithStagedMigrationOptionKey is set).\n"
- "CoreData: error: Deferring full-text index repair until after migration is complete (NSPersistentStoreCoordinatorIsMigratingStoreWithStagedMigrationOptionKey is set).\n"
- "CoreData: error: Finished rebuilding full-text indicies for store - %@\n"
- "CoreData: error: Rebuilding full-text indexes for store created by older framework version (fvk=%@) - %@\n"
- "CoreData: warning: Finished rebuilding full-text indicies for store - %@\n"
- "CoreData: warning: Rebuilding full-text indexes for store created by older framework version (fvk=%@) - %@\n"
- "Deferring full-text index repair until after migration is complete (NSPersistentStoreCoordinatorIsMigratingStoreWithStagedMigrationOptionKey is set)."
- "Finished rebuilding full-text indicies for store - %@"
- "NSApplication"
- "Rebuilding full-text indexes for store created by older framework version (fvk=%@) - %@"
```
