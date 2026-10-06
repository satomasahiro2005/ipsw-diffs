## CoreData

> `/System/Library/Frameworks/CoreData.framework/CoreData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x36192` | `0x37186` | **`+0xff4`** |
| `__TEXT.__text` | `0x330450` | `0x3310f0` | **`+0xca0`** |
| `__TEXT.__cstring` | `0x3b2aa` | `0x3ba72` | **`+0x7c8`** |
| `__TEXT.__gcc_except_tab` | `0x182c4` | `0x18558` | **`+0x294`** |
| `__AUTH_CONST.__cfstring` | `0x1fac0` | `0x1fc40` | **`+0x180`** |
| `__AUTH_CONST.__objc_const` | `0x25c38` | `0x25d78` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x7660` | `0x7750` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x10830` | `0x10888` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x3328` | `0x3378` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x2dd8` | `0x2db8` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x187c` | `0x188c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x61f8` | `0x6208` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x17e8` | `0x17e0` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x4ba0` | `0x4b98` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xed0` | `0xed8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xbb0` | `0xbb8` | **`+0x8`** |

### Other Changes

```diff

-1621.2.0.0.0
+1622.2.0.0.0

-  Functions: 9299
-  Symbols:   17561
-  CStrings:  8241
+  Functions: 9304
+  Symbols:   17577
+  CStrings:  8334
Symbols:
+ -[NSCoreDataCoreSpotlightDelegate _flushSearchableItemsBatch:identifiersToDelete:toIndex:indexGroup:opResults:]
+ -[NSCoreDataCoreSpotlightDelegate _processObjectIDsForUpdate:searchableItems:identifiersToDelete:batchSize:index:indexGroup:opResults:]
+ -[NSCoreDataCoreSpotlightDelegate _submitFullReindexBatchToIndex:searchableItems:identifiersToDelete:clientState:entityName:]
+ -[NSFetchIndexDescription _coveredPropertyName]
+ -[NSPersistentCacheRow ancillaryOrderKeysForProperty:]
+ -[NSSQLCore supportsGenerationalQueryingAndLog:]
+ -[PFCoreDataCoreSpotlightErrorDelegate resetRetryState]
+ -[PFSpotlightOpResult dealloc]
+ -[PFSpotlightOpResult error]
+ -[PFSpotlightOpResult setError:]
+ -[PFSpotlightOpResult setValue:]
+ -[PFSpotlightOpResult value]
+ GCC_except_table154
+ GCC_except_table156
+ GCC_except_table162
+ GCC_except_table181
+ _OBJC_CLASS_$_PFSpotlightOpResult
+ _OBJC_IVAR_$_NSCoreDataCoreSpotlightDelegate._isReimporting
+ _OBJC_IVAR_$_PFSpotlightOpResult._error
+ _OBJC_IVAR_$_PFSpotlightOpResult._value
+ _OBJC_IVAR_$__NSSQLiteStoreMigrator._phantomIndexDropStatements
+ _OBJC_METACLASS_$_PFSpotlightOpResult
+ __OBJC_$_INSTANCE_METHODS_PFSpotlightOpResult
+ __OBJC_$_INSTANCE_VARIABLES_PFSpotlightOpResult
+ __OBJC_$_PROP_LIST_PFSpotlightOpResult
+ __OBJC_CLASS_RO_$_PFSpotlightOpResult
+ __OBJC_METACLASS_RO_$_PFSpotlightOpResult
+ ___111-[NSCoreDataCoreSpotlightDelegate _flushSearchableItemsBatch:identifiersToDelete:toIndex:indexGroup:opResults:]_block_invoke
+ ___125-[NSCoreDataCoreSpotlightDelegate _submitFullReindexBatchToIndex:searchableItems:identifiersToDelete:clientState:entityName:]_block_invoke
+ ___block_descriptor_48_e8_32o40o_e28_v24?0"NSData"8"NSError"16ls32l8s40l8
+ ___block_descriptor_64_e8_32o40o48o56o_e17_v16?0"NSError"8ls32l8s40l8s48l8s56l8
+ _method_getName
- -[NSCoreDataCoreSpotlightDelegate _flushSearchableItemsBatch:identifiersToDelete:toIndex:indexGroup:]
- -[NSCoreDataCoreSpotlightDelegate _processObjectIDsForUpdate:searchableItems:identifiersToDelete:batchSize:index:indexGroup:]
- GCC_except_table141
- GCC_except_table151
- GCC_except_table155
- GCC_except_table171
- GCC_except_table180
- ___101-[NSCoreDataCoreSpotlightDelegate _flushSearchableItemsBatch:identifiersToDelete:toIndex:indexGroup:]_block_invoke
- ___50-[NSCoreDataCoreSpotlightDelegate _doFullReimport]_block_invoke_2
- ___91-[NSCoreDataCoreSpotlightDelegate _updateSpotlightIndexForObjectsWithIDs:updatedSpotlight:]_block_invoke
- ___block_descriptor_48_e8_32o40r_e17_v16?0"NSError"8lr40l8s32l8
- ___block_descriptor_64_e8_32o40o48r56r_e17_v16?0"NSError"8lr48l8s32l8r56l8s40l8
- ___block_descriptor_64_e8_32o40r48r56r_e28_v24?0"NSData"8"NSError"16lr40l8r48l8r56l8s32l8
- ___block_descriptor_72_e8_32o40o48o56r64r_e17_v16?0"NSError"8lr56l8r64l8s32l8s40l8s48l8
- _dispatch_group_notify
- _method_getDescription
CStrings:
+ "-[NSCoreDataCoreSpotlightDelegate _flushSearchableItemsBatch:identifiersToDelete:toIndex:indexGroup:opResults:]"
+ "-[NSCoreDataCoreSpotlightDelegate _flushSearchableItemsBatch:identifiersToDelete:toIndex:indexGroup:opResults:]_block_invoke"
+ "-[NSCoreDataCoreSpotlightDelegate _processObjectIDsForDeletion:identifiersToDelete:batchSize:index:indexGroup:opResults:]"
+ "-[NSCoreDataCoreSpotlightDelegate _processObjectIDsForUpdate:searchableItems:identifiersToDelete:batchSize:index:indexGroup:opResults:]"
+ "<none>"
+ "<unknown>"
+ "Active"
+ "BackOff"
+ "Begin dropping phantom indices."
+ "CDCS OS-driven reindex (%lu identifiers) acknowledged for index %@"
+ "CDCS OS-driven reindex (%lu identifiers) requested for index %@"
+ "CDCS OS-driven reindex (%lu identifiers) skipped — operations not allowed (index %@)"
+ "CDCS OS-driven reindex (all items) acknowledged for index %@"
+ "CDCS OS-driven reindex (all items) requested for index %@"
+ "CDCS OS-driven reindex (all items) skipped — operations not allowed (index %@)"
+ "CDCS aborting full reimport after state reset — operations not allowed (index %@)"
+ "CDCS aborting full reimport before index reset — operations not allowed (index %@)"
+ "CDCS aborting full reimport — Spotlight disabled, store nil, or read-only (index %@)"
+ "CDCS caught-up metadata stamped: importComplete=YES frameworkVersion=%@ (index %@)"
+ "CDCS client state token write begin (index %@): %@"
+ "CDCS donation count (%lu) exceeded allKnownItems (%lu) — clamping (index %@)"
+ "CDCS donation progress: donated=%lu / allKnown=%lu (needing=%lu, index %@)"
+ "CDCS dropping batch result (full reimport in progress, index %@)"
+ "CDCS dropping save (full reimport in progress, index %@)"
+ "CDCS error routed → fatal: domain=%@ code=%ld (index %@): %@"
+ "CDCS error routed → retry: domain=%@ code=%ld (index %@): %@"
+ "CDCS full reimport baseline: allKnownItems=%lu (index %@)"
+ "CDCS full reimport completed (index %@)"
+ "CDCS invalid state transition rejected: %@ → %@ (index %@)"
+ "CDCS pre-reindex wipe reported error; continuing to reindex anyway (index %@)"
+ "CDCS reimport gate ENTER (index %@)"
+ "CDCS reimport gate EXIT (index %@)"
+ "CDCS reindex bailed mid-stream (state flipped) — withholding caught-up metadata (index %@)"
+ "CDCS reindex committed caught-up client-state token (index %@)"
+ "CDCS reindex had at least one failed batch (index %@)"
+ "CDCS starting full reimport (index %@)"
+ "CDCS state transition: %@ → %@ (index %@)"
+ "CDCS storeRequiresFullReindex: fullReindex=%d reason=%@ (index %@)"
+ "Cannot use `currentQueryGeneration` in this store configuration"
+ "Cannot use `reopenQueryGenerationWithIdentifier` in this store configuration"
+ "Cannot use query generations with a store backing an XPC client.  URL = %s"
+ "Cannot use query generations with a store that doesn't have a PSC.  URL = %s"
+ "Cannot use query generations with an in-memory store.  URL = %s"
+ "CoreData+CoreSpotlight <%p>: %s(%d): Invalid state transition from %@ to %@ (index %@)"
+ "CoreData: Invalid default value type for '%@'. Expected '%@' but found '%@'."
+ "CoreData: annotation: Begin dropping phantom indices.\n"
+ "CoreData: annotation: CDCS client state token write begin (index %@): %@\n"
+ "CoreData: annotation: CDCS donation progress: donated=%lu / allKnown=%lu (needing=%lu, index %@)\n"
+ "CoreData: annotation: CDCS dropping batch result (full reimport in progress, index %@)\n"
+ "CoreData: annotation: CDCS dropping save (full reimport in progress, index %@)\n"
+ "CoreData: annotation: CDCS reimport gate ENTER (index %@)\n"
+ "CoreData: annotation: CDCS reimport gate EXIT (index %@)\n"
+ "CoreData: annotation: CoreData+CoreSpotlight <%p>: %s(%d): Invalid state transition from %@ to %@ (index %@)\n"
+ "CoreData: annotation: Executing drop phantom index statement: %@\n"
+ "CoreData: error: Begin dropping phantom indices.\n"
+ "CoreData: error: CDCS OS-driven reindex (%lu identifiers) acknowledged for index %@\n"
+ "CoreData: error: CDCS OS-driven reindex (%lu identifiers) requested for index %@\n"
+ "CoreData: error: CDCS OS-driven reindex (%lu identifiers) skipped — operations not allowed (index %@)\n"
+ "CoreData: error: CDCS OS-driven reindex (all items) acknowledged for index %@\n"
+ "CoreData: error: CDCS OS-driven reindex (all items) requested for index %@\n"
+ "CoreData: error: CDCS OS-driven reindex (all items) skipped — operations not allowed (index %@)\n"
+ "CoreData: error: CDCS aborting full reimport after state reset — operations not allowed (index %@)\n"
+ "CoreData: error: CDCS aborting full reimport before index reset — operations not allowed (index %@)\n"
+ "CoreData: error: CDCS aborting full reimport — Spotlight disabled, store nil, or read-only (index %@)\n"
+ "CoreData: error: CDCS caught-up metadata stamped: importComplete=YES frameworkVersion=%@ (index %@)\n"
+ "CoreData: error: CDCS client state token write begin (index %@): %@\n"
+ "CoreData: error: CDCS donation count (%lu) exceeded allKnownItems (%lu) — clamping (index %@)\n"
+ "CoreData: error: CDCS donation progress: donated=%lu / allKnown=%lu (needing=%lu, index %@)\n"
+ "CoreData: error: CDCS dropping batch result (full reimport in progress, index %@)\n"
+ "CoreData: error: CDCS dropping save (full reimport in progress, index %@)\n"
+ "CoreData: error: CDCS error routed → fatal: domain=%@ code=%ld (index %@): %@\n"
+ "CoreData: error: CDCS error routed → retry: domain=%@ code=%ld (index %@): %@\n"
+ "CoreData: error: CDCS full reimport baseline: allKnownItems=%lu (index %@)\n"
+ "CoreData: error: CDCS full reimport completed (index %@)\n"
+ "CoreData: error: CDCS invalid state transition rejected: %@ → %@ (index %@)\n"
+ "CoreData: error: CDCS pre-reindex wipe reported error; continuing to reindex anyway (index %@)\n"
+ "CoreData: error: CDCS reimport gate ENTER (index %@)\n"
+ "CoreData: error: CDCS reimport gate EXIT (index %@)\n"
+ "CoreData: error: CDCS reindex bailed mid-stream (state flipped) — withholding caught-up metadata (index %@)\n"
+ "CoreData: error: CDCS reindex committed caught-up client-state token (index %@)\n"
+ "CoreData: error: CDCS reindex had at least one failed batch (index %@)\n"
+ "CoreData: error: CDCS starting full reimport (index %@)\n"
+ "CoreData: error: CDCS state transition: %@ → %@ (index %@)\n"
+ "CoreData: error: CDCS storeRequiresFullReindex: fullReindex=%d reason=%@ (index %@)\n"
+ "CoreData: error: Cannot use query generations with a store backing an XPC client.  URL = %s\n"
+ "CoreData: error: Cannot use query generations with a store that doesn't have a PSC.  URL = %s\n"
+ "CoreData: error: Cannot use query generations with an in-memory store.  URL = %s\n"
+ "CoreData: error: CoreData+CoreSpotlight <%p>: %s(%d): Invalid state transition from %@ to %@ (index %@)\n"
+ "CoreData: error: Executing drop phantom index statement: %@\n"
+ "CoreData: error: Full re-import SKIPPING entity %@ after fetch failure — items not donated this pass; store left needing reindex (index %@): %@\n"
+ "CoreData: error: Timed out waiting for full re-import batch to drain for entity %@, index %@\n"
+ "CoreData: error: Timed out waiting for indexing batch to drain, index %@\n"
+ "CoreData: fault: Invalid default value type for '%@'. Expected '%@' but found '%@'.\n"
+ "CoreData: warning: CDCS OS-driven reindex (%lu identifiers) acknowledged for index %@\n"
+ "CoreData: warning: CDCS OS-driven reindex (%lu identifiers) requested for index %@\n"
+ "CoreData: warning: CDCS OS-driven reindex (%lu identifiers) skipped — operations not allowed (index %@)\n"
+ "CoreData: warning: CDCS OS-driven reindex (all items) acknowledged for index %@\n"
+ "CoreData: warning: CDCS OS-driven reindex (all items) requested for index %@\n"
+ "CoreData: warning: CDCS OS-driven reindex (all items) skipped — operations not allowed (index %@)\n"
+ "CoreData: warning: CDCS aborting full reimport after state reset — operations not allowed (index %@)\n"
+ "CoreData: warning: CDCS aborting full reimport before index reset — operations not allowed (index %@)\n"
+ "CoreData: warning: CDCS aborting full reimport — Spotlight disabled, store nil, or read-only (index %@)\n"
+ "CoreData: warning: CDCS caught-up metadata stamped: importComplete=YES frameworkVersion=%@ (index %@)\n"
+ "CoreData: warning: CDCS error routed → fatal: domain=%@ code=%ld (index %@): %@\n"
+ "CoreData: warning: CDCS error routed → retry: domain=%@ code=%ld (index %@): %@\n"
+ "CoreData: warning: CDCS full reimport baseline: allKnownItems=%lu (index %@)\n"
+ "CoreData: warning: CDCS full reimport completed (index %@)\n"
+ "CoreData: warning: CDCS invalid state transition rejected: %@ → %@ (index %@)\n"
+ "CoreData: warning: CDCS pre-reindex wipe reported error; continuing to reindex anyway (index %@)\n"
+ "CoreData: warning: CDCS reindex bailed mid-stream (state flipped) — withholding caught-up metadata (index %@)\n"
+ "CoreData: warning: CDCS reindex committed caught-up client-state token (index %@)\n"
+ "CoreData: warning: CDCS reindex had at least one failed batch (index %@)\n"
+ "CoreData: warning: CDCS starting full reimport (index %@)\n"
+ "CoreData: warning: CDCS state transition: %@ → %@ (index %@)\n"
+ "CoreData: warning: CDCS storeRequiresFullReindex: fullReindex=%d reason=%@ (index %@)\n"
+ "Disabled"
+ "Executing drop phantom index statement: %@"
+ "FatalError"
+ "Full re-import SKIPPING entity %@ after fetch failure — items not donated this pass; store left needing reindex (index %@): %@"
+ "Initializing"
+ "Timed out waiting for CoreSpotlight full re-import batch"
+ "Timed out waiting for CoreSpotlight indexing batch"
+ "Timed out waiting for full re-import batch to drain for entity %@, index %@"
+ "Timed out waiting for indexing batch to drain, index %@"
+ "framework-version mismatch (stored=%@ current=%@)"
+ "no framework-version metadata"
- "-[NSCoreDataCoreSpotlightDelegate _doFullReimport]"
- "-[NSCoreDataCoreSpotlightDelegate _flushSearchableItemsBatch:identifiersToDelete:toIndex:indexGroup:]"
- "-[NSCoreDataCoreSpotlightDelegate _flushSearchableItemsBatch:identifiersToDelete:toIndex:indexGroup:]_block_invoke"
- "-[NSCoreDataCoreSpotlightDelegate _handleCoreSpotlightError:]_block_invoke"
- "-[NSCoreDataCoreSpotlightDelegate _processObjectIDsForDeletion:identifiersToDelete:batchSize:index:indexGroup:]"
- "-[NSCoreDataCoreSpotlightDelegate _processObjectIDsForUpdate:searchableItems:identifiersToDelete:batchSize:index:indexGroup:]"
- "CoreData+CoreSpotlight <%p>: %s(%d): Aborting full re-import after state reset — operations not allowed"
- "CoreData+CoreSpotlight <%p>: %s(%d): Aborting full re-import before index reset — operations not allowed"
- "CoreData+CoreSpotlight <%p>: %s(%d): Invalid state transition from %d to %d"
- "CoreData+CoreSpotlight <%p>: %s(%d): Not performing full re-import because Spotlight was disabled, store was nil, or store is read-only."
- "CoreData+CoreSpotlight <%p>: %s(%d): Performing full Spotlight re-import"
- "CoreData+CoreSpotlight <%p>: %s(%d): Spotlight Delegate encountered a fatal error, %@"
- "CoreData+CoreSpotlight <%p>: %s(%d): Spotlight Delegate encountered a recoverable/retryable error %@"
- "CoreData+CoreSpotlight <%p>: %s(%d): State transition: %d -> %d"
- "CoreData: annotation: CoreData+CoreSpotlight <%p>: %s(%d): Aborting full re-import after state reset — operations not allowed\n"
- "CoreData: annotation: CoreData+CoreSpotlight <%p>: %s(%d): Aborting full re-import before index reset — operations not allowed\n"
- "CoreData: annotation: CoreData+CoreSpotlight <%p>: %s(%d): Invalid state transition from %d to %d\n"
- "CoreData: annotation: CoreData+CoreSpotlight <%p>: %s(%d): Not performing full re-import because Spotlight was disabled, store was nil, or store is read-only.\n"
- "CoreData: annotation: CoreData+CoreSpotlight <%p>: %s(%d): Performing full Spotlight re-import\n"
- "CoreData: annotation: CoreData+CoreSpotlight <%p>: %s(%d): Spotlight Delegate encountered a fatal error, %@\n"
- "CoreData: annotation: CoreData+CoreSpotlight <%p>: %s(%d): Spotlight Delegate encountered a recoverable/retryable error %@\n"
- "CoreData: annotation: CoreData+CoreSpotlight <%p>: %s(%d): State transition: %d -> %d\n"
- "CoreData: error: CoreData+CoreSpotlight <%p>: %s(%d): Aborting full re-import after state reset — operations not allowed\n"
- "CoreData: error: CoreData+CoreSpotlight <%p>: %s(%d): Aborting full re-import before index reset — operations not allowed\n"
- "CoreData: error: CoreData+CoreSpotlight <%p>: %s(%d): Invalid state transition from %d to %d\n"
- "CoreData: error: CoreData+CoreSpotlight <%p>: %s(%d): Not performing full re-import because Spotlight was disabled, store was nil, or store is read-only.\n"
- "CoreData: error: CoreData+CoreSpotlight <%p>: %s(%d): Performing full Spotlight re-import\n"
- "CoreData: error: CoreData+CoreSpotlight <%p>: %s(%d): Spotlight Delegate encountered a fatal error, %@\n"
- "CoreData: error: CoreData+CoreSpotlight <%p>: %s(%d): Spotlight Delegate encountered a recoverable/retryable error %@\n"
- "CoreData: error: CoreData+CoreSpotlight <%p>: %s(%d): State transition: %d -> %d\n"
- "CoreData: error: Full re-import failed for: %@ due to %@.\n"
- "Full re-import failed for: %@ due to %@."
- "Unsupported feature in this configuration"
```
