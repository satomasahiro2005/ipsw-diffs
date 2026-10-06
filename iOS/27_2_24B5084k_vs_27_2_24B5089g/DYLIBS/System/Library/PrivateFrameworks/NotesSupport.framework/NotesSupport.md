## NotesSupport

> `/System/Library/PrivateFrameworks/NotesSupport.framework/NotesSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x584fc` | `0x5736c` | **`-0x1190`** |
| `__AUTH_CONST.__objc_const` | `0x6028` | `0x5dc0` | **`-0x268`** |
| `__TEXT.__oslogstring` | `0x4526` | `0x4356` | **`-0x1d0`** |
| `__TEXT.__objc_methlist` | `0x4480` | `0x42f8` | **`-0x188`** |
| `__TEXT.__cstring` | `0x4709` | `0x4619` | **`-0xf0`** |
| `__DATA_DIRTY.__data` | `0x418` | `0x4b8` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x1270` | `0x11d0` | **`-0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x3270` | `0x31d8` | **`-0x98`** |
| `__AUTH.__data` | `0xa0` | `0x18` | **`-0x88`** |
| `__AUTH_CONST.__cfstring` | `0x45e0` | `0x4560` | **`-0x80`** |
| `__AUTH_CONST.__const` | `0x1620` | `0x15a0` | **`-0x80`** |
| `__DATA_CONST.__const` | `0x1390` | `0x1318` | **`-0x78`** |
| `__TEXT.__gcc_except_tab` | `0xef0` | `0xe80` | **`-0x70`** |
| `__TEXT.__unwind_info` | `0x1d30` | `0x1ce0` | **`-0x50`** |
| `__DATA.__bss` | `0x570` | `0x540` | **`-0x30`** |
| `__DATA.__objc_ivar` | `0x230` | `0x220` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1f8` | `0x1e8` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x100` | `0xf0` | **`-0x10`** |
| `__DATA.__data` | `0x704` | `0x70c` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x898` | `0x890` | **`-0x8`** |
| `__TEXT.__const` | `0xb6c` | `0xb68` | **`-0x4`** |
| `__TEXT.__swift5_typeref` | `0x2bb` | `0x2bc` | **`+0x1`** |

### Other Changes

```diff

-3001.40.8.100.1
+3001.40.9.100.1

-  Functions: 2565
-  Symbols:   3768
-  CStrings:  1068
+  Functions: 2519
+  Symbols:   3699
+  CStrings:  1054
Symbols:
- +[ICCDCSIReindexer searchableIndex]
- +[ICCDCSIReindexer sharedReindexer]
- -[ICCDCSIReindexer .cxx_destruct]
- -[ICCDCSIReindexer _reindexSearchableItemsWithIdentifiers:completionHandler:]
- -[ICCDCSIReindexer deleteAllSearchableItemsWithCompletionHandler:]
- -[ICCDCSIReindexer forceDeleteAllProgressState]
- -[ICCDCSIReindexer fullyStagedSinceLastReindex]
- -[ICCDCSIReindexer init]
- -[ICCDCSIReindexer registerCoreDataCoreSpotlightDelegate:]
- -[ICCDCSIReindexer registeredDelegates]
- -[ICCDCSIReindexer reindexAllSearchableItemsWithCompletionHandler:]
- -[ICCDCSIReindexer reindexAllSearchableItemsWithScope:completionHandler:]
- -[ICCDCSIReindexer reindexSearchableItemsWithObjectIDURIs:completionHandler:]
- -[ICCDCSIReindexer reindexSearchableItemsWithObjectIDURIs:scope:completionHandler:]
- -[ICCDCSIReindexer setRegisteredDelegates:]
- -[ICCDCSIReindexer stopIndexing]
- -[ICCDCSIReindexer unregisterCoreDataCoreSpotlightDelegate:]
- -[ICCoreDataCoreSpotlightDelegate attributeSetForObject:]
- -[ICCoreDataCoreSpotlightDelegate bundleIdentifier]
- -[ICCoreDataCoreSpotlightDelegate dealloc]
- -[ICCoreDataCoreSpotlightDelegate indexName]
- -[ICCoreDataCoreSpotlightDelegate indexingPriority]
- -[ICCoreDataCoreSpotlightDelegate initForStoreWithDescription:coordinator:indexingPriority:]
- -[ICCoreDataCoreSpotlightDelegate isCheckingObjectConsistency]
- -[ICCoreDataCoreSpotlightDelegate setIndexingPriority:]
- -[ICCoreDataCoreSpotlightDelegate setIsCheckingObjectConsistency:]
- -[ICCoreDataCoreSpotlightDelegate shouldIndexableObjectExistInIndexing:]
- -[ICCoreDataCoreSpotlightDelegate shouldPerformConsistencyCheck]
- -[ICCoreDataCoreSpotlightDelegate startSpotlightIndexing]
- -[ICCoreDataCoreSpotlightDelegate stopSpotlightIndexing]
- _ICUseCoreDataCoreSpotlightIntegration
- _ICUseCoreDataCoreSpotlightIntegration.onceToken
- _OBJC_CLASS_$_ICCDCSIReindexer
- _OBJC_CLASS_$_ICCoreDataCoreSpotlightDelegate
- _OBJC_CLASS_$_NSCoreDataCoreSpotlightDelegate
- _OBJC_IVAR_$_ICCDCSIReindexer._registeredDelegates
- _OBJC_IVAR_$_ICCoreDataCoreSpotlightDelegate._indexingPriority
- _OBJC_IVAR_$_ICCoreDataCoreSpotlightDelegate._isCheckingObjectConsistency
- _OBJC_IVAR_$_ICCoreDataCoreSpotlightDelegate._shouldPerformConsistencyCheck
- _OBJC_METACLASS_$_ICCDCSIReindexer
- _OBJC_METACLASS_$_ICCoreDataCoreSpotlightDelegate
- _OBJC_METACLASS_$_NSCoreDataCoreSpotlightDelegate
- __OBJC_$_CLASS_METHODS_ICCDCSIReindexer
- __OBJC_$_INSTANCE_METHODS_ICCDCSIReindexer
- __OBJC_$_INSTANCE_METHODS_ICCoreDataCoreSpotlightDelegate
- __OBJC_$_INSTANCE_VARIABLES_ICCDCSIReindexer
- __OBJC_$_INSTANCE_VARIABLES_ICCoreDataCoreSpotlightDelegate
- __OBJC_$_PROP_LIST_ICCDCSIReindexer
- __OBJC_$_PROP_LIST_ICCoreDataCoreSpotlightDelegate
- __OBJC_CLASS_PROTOCOLS_$_ICCDCSIReindexer
- __OBJC_CLASS_RO_$_ICCDCSIReindexer
- __OBJC_CLASS_RO_$_ICCoreDataCoreSpotlightDelegate
- __OBJC_METACLASS_RO_$_ICCDCSIReindexer
- __OBJC_METACLASS_RO_$_ICCoreDataCoreSpotlightDelegate
- ___35+[ICCDCSIReindexer searchableIndex]_block_invoke
- ___35+[ICCDCSIReindexer sharedReindexer]_block_invoke
- ___66-[ICCDCSIReindexer deleteAllSearchableItemsWithCompletionHandler:]_block_invoke
- ___77-[ICCDCSIReindexer _reindexSearchableItemsWithIdentifiers:completionHandler:]_block_invoke
- ___77-[ICCDCSIReindexer _reindexSearchableItemsWithIdentifiers:completionHandler:]_block_invoke_2
- ___ICUseCoreDataCoreSpotlightIntegration_block_invoke
- ___block_descriptor_32_e77_q24?0"ICCoreDataCoreSpotlightDelegate"8"ICCoreDataCoreSpotlightDelegate"16l
- ___block_descriptor_40_e8_32bs_e17_v16?0"NSError"8ls32l8
- ___block_descriptor_56_e8_32bs40r48r_e5_v8?0lr40l8r48l8s32l8
- _kICSearchInternalSettingsUseCoreDataCoreSpotlightIntegration
- _searchableIndex.s_instance
- _searchableIndex.s_token_for_searchable_index
- _sharedReindexer.onceToken
- _sharedReindexer.sSharedReindexer
- _useCoreSpotlightCoreDataIntegration
CStrings:
- "-[ICCDCSIReindexer _reindexSearchableItemsWithIdentifiers:completionHandler:]"
- "-attributeSetForObject: NO need to index ICSearchIndexable: %@"
- "-attributeSetForObject: called with a non-ICSearchIndexable object"
- "-attributeSetForObject: need to index ICSearchIndexable: %@"
- "About to reindex all searchable items"
- "About to reindex searchable items: %@"
- "Searchable index of %@ is unexpectately not of type %@."
- "completedReindexes = %lu, triggering completionHandler"
- "completionHandler is %@, completedReindexes = %lu, countOfRegisteredDelegates = %lu"
- "internalSettings.useCDCSI"
- "nil"
- "non-nil"
- "q24@?0@\"ICCoreDataCoreSpotlightDelegate\"8@\"ICCoreDataCoreSpotlightDelegate\"16"
- "reindexing with ICCoreDataCoreSpotlightDelegate: %@"
```
