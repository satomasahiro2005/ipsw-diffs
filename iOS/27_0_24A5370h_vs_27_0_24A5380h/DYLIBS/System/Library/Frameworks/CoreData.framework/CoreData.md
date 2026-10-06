## CoreData

> `/System/Library/Frameworks/CoreData.framework/CoreData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3310f0` | `0x32fd90` | **`-0x1360`** |
| `__TEXT.__oslogstring` | `0x37186` | `0x36758` | **`-0xa2e`** |
| `__DATA_CONST.__got` | `0xa18` | `0xca0` | **`+0x288`** |
| `__TEXT.__cstring` | `0x3ba72` | `0x3bceb` | **`+0x279`** |
| `__TEXT.__gcc_except_tab` | `0x18558` | `0x187a0` | **`+0x248`** |
| `__AUTH.__objc_data` | `0x3378` | `0x32d8` | **`-0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x1fc40` | `0x1fce0` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x6328` | `0x63c8` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x7750` | `0x77a0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x4b98` | `0x4bc8` | **`+0x30`** |
| `__TEXT.__const` | `0x2e60` | `0x2e30` | **`-0x30`** |
| `__AUTH.__data` | `0x218` | `0x238` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x5c0` | `0x5a0` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x6b0` | `0x698` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x10888` | `0x108a0` | **`+0x18`** |
| `__DATA.__bss` | `0x16c0` | `0x16d0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x6208` | `0x6218` | **`+0x10`** |
| `__DATA.__common` | `0x648` | `0x650` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x12d6` | `0x12d0` | **`-0x6`** |
| `__DATA.__objc_ivar` | `0x188c` | `0x1890` | **`+0x4`** |
| `__DATA_DIRTY.__objc_ivar` | `0x518` | `0x514` | **`-0x4`** |

### Other Changes

```diff

-1622.2.0.0.0
+1624.0.0.0.0

-  Functions: 9304
-  Symbols:   17577
-  CStrings:  8334
+  Functions: 9325
+  Symbols:   17595
+  CStrings:  8316
Symbols:
+ -[NSCloudKitMirroringActivityVoucherManager _locked_vouchersForEventType:]
+ -[NSCloudKitMirroringActivityVoucherManager _withLock:]
+ -[NSPersistentStore(_NSInternalMethods) _rebuildFullTextIndiciesSynchronously:]
+ -[NSPersistentStoreCoordinator _repairFullTextIndiciesForStoreWithIdentifier:synchronous:]
+ -[NSSQLCore _rebuildFullTextIndiciesSynchronously:]
+ -[NSSQLEntity fts5Indexes]
+ -[NSSQLiteConnection _cleanupUnreferencedGenerations]
+ -[NSSQLiteConnection recreateFullTextIndices]
+ -[NSXPCStoreConnection _teardownConnection]
+ GCC_except_table119
+ GCC_except_table141
+ GCC_except_table151
+ GCC_except_table155
+ GCC_except_table166
+ GCC_except_table168
+ GCC_except_table171
+ GCC_except_table175
+ GCC_except_table177
+ GCC_except_table184
+ GCC_except_table191
+ GCC_except_table194
+ GCC_except_table196
+ GCC_except_table197
+ GCC_except_table201
+ GCC_except_table206
+ GCC_except_table213
+ GCC_except_table215
+ GCC_except_table217
+ GCC_except_table231
+ GCC_except_table233
+ GCC_except_table85
+ GCC_except_table94
+ _NSPersistentCloudKitContainerExternalizedAttributeKey
+ _OBJC_IVAR_$_NSCloudKitMirroringActivityVoucherManager._vouchersLock
+ ___33-[NSXPCStoreConnection reconnect]_block_invoke
+ ___34-[NSXPCStoreConnection disconnect]_block_invoke
+ ___51-[NSSQLCore _rebuildFullTextIndiciesSynchronously:]_block_invoke
+ ___51-[PFCloudKitModelValidator validateEntities:error:]_block_invoke_19
+ ___51-[PFCloudKitModelValidator validateEntities:error:]_block_invoke_20
+ ___55-[NSCloudKitMirroringActivityVoucherManager _withLock:]_block_invoke
+ ___56-[NSCloudKitMirroringActivityVoucherManager addVoucher:]_block_invoke
+ ___58-[NSCloudKitMirroringActivityVoucherManager countVouchers]_block_invoke
+ ___59-[NSCloudKitMirroringActivityVoucherManager expireVoucher:]_block_invoke
+ ___71-[NSCloudKitMirroringActivityVoucherManager usableVoucherForEventType:]_block_invoke
+ ___72-[NSCloudKitMirroringActivityVoucherManager expireVouchersForEventType:]_block_invoke
+ ___block_descriptor_112_e8_32o40o48o56o64o72o80o88o96o104o_e49_v32?0"NSString"8"NSAttributeDescription"16^B24ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8
+ ___block_descriptor_112_e8_32o40o48o56o64o72o80o88o96o104o_e52_v32?0"NSString"8"NSRelationshipDescription"16^B24ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8
+ ___block_descriptor_56_e8_32o40r_e5_v8?0lr40l8s32l8
+ _swift_release_x11
- -[NSCloudKitMirroringActivityVoucherManager _vouchersForEventType:]
- GCC_except_table111
- GCC_except_table124
- GCC_except_table134
- GCC_except_table140
- GCC_except_table142
- GCC_except_table144
- GCC_except_table154
- GCC_except_table160
- GCC_except_table167
- GCC_except_table169
- GCC_except_table179
- GCC_except_table185
- GCC_except_table193
- GCC_except_table198
- GCC_except_table199
- GCC_except_table204
- GCC_except_table205
- GCC_except_table212
- GCC_except_table214
- GCC_except_table228
- GCC_except_table230
- GCC_except_table66
- _$sSo9NSDecimala10FoundationE14integerLiteralABSi_tcfC
- _NSStringTransformStripDiacritics
- __PFBatchFaultingArray_DumpStateForNotes
- __PFBatchFaultingArray__FaultyFaultingState__
- ___block_descriptor_104_e8_32o40o48o56o64o72o80o88o96o_e49_v32?0"NSString"8"NSAttributeDescription"16^B24ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8
- ___block_descriptor_104_e8_32o40o48o56o64o72o80o88o96o_e52_v32?0"NSString"8"NSRelationshipDescription"16^B24ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8
- _get_type_metadata So15FetchColumnPlana noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "%@.%@ - '%@' is not a variable length attribute type."
+ "'%@' is not supported on relationships but it is set on these:"
+ "CoreData: Exception caught during full-text index recreation %@"
+ "CoreData: Unable to rebuild full-text index: %@ due to exception (%@)"
+ "CoreData: Unhandled unknown exception encountered during change request: %@ with userInfo %@"
+ "CoreData: annotation: Deferring full-text index repair until after migration is complete (NSPersistentStoreCoordinatorIsMigratingStoreWithStagedMigrationOptionKey is set).\n"
+ "CoreData: annotation: Unable to reindex full-text store(%@) - %@\n"
+ "CoreData: annotation: re-tokenizing all full-text indices\n"
+ "CoreData: error: Deferring full-text index repair until after migration is complete (NSPersistentStoreCoordinatorIsMigratingStoreWithStagedMigrationOptionKey is set).\n"
+ "CoreData: error: Error encountered during full-text index recreation %@ with userInfo %@\n"
+ "CoreData: error: Failed to persist cleared full-text rebuild flag for store %@: %@\n"
+ "CoreData: error: Finished rebuilding full-text indicies for store - %@\n"
+ "CoreData: error: Full-text index recreation failed\n"
+ "CoreData: error: Rebuilding full-text indexes for store created by older framework version (fvk=%@) - %@\n"
+ "CoreData: error: Unable to rebuild full-text index: %@ due to error (%@)\n"
+ "CoreData: error: Unable to reindex full-text store(%@) - %@\n"
+ "CoreData: error: Unhandled CoreData error encountered during change request %@ with userInfo %@\n"
+ "CoreData: error: Unhandled optimistic locking error encountered during change request %@ with userInfo %@\n"
+ "CoreData: error: no NSValueTransformer with name '%@' was found for attribute '%@' on entity '%@'\n"
+ "CoreData: error: re-tokenizing all full-text indices\n"
+ "CoreData: fault: Exception caught during full-text index recreation %@\n"
+ "CoreData: fault: Unable to rebuild full-text index: %@ due to exception (%@)\n"
+ "CoreData: fault: Unhandled unknown exception encountered during change request: %@ with userInfo %@\n"
+ "CoreData: warning: Finished rebuilding full-text indicies for store - %@\n"
+ "CoreData: warning: Rebuilding full-text indexes for store created by older framework version (fvk=%@) - %@\n"
+ "CoreData: warning: no NSValueTransformer with name '%@' was found for attribute '%@' on entity '%@'\n"
+ "Deferring full-text index repair until after migration is complete (NSPersistentStoreCoordinatorIsMigratingStoreWithStagedMigrationOptionKey is set)."
+ "Error encountered during full-text index recreation %@ with userInfo %@"
+ "Failed to persist cleared full-text rebuild flag for store %@: %@"
+ "Finished rebuilding full-text indicies for store - %@"
+ "Full-text index recreation failed"
+ "Latin-ASCII"
+ "NSPersistentCloudKitContainerExternalizedAttributeKey"
+ "NSPersistentStoreRebuildFullTextIndicies"
+ "Rebuilding full-text indexes for store created by older framework version (fvk=%@) - %@"
+ "Unable to rebuild full-text index: %@ due to error (%@)"
+ "Unable to reindex full-text store(%@) - %@"
+ "Unhandled CoreData error encountered during change request %@ with userInfo %@"
+ "Unhandled optimistic locking error encountered during change request %@ with userInfo %@"
+ "no NSValueTransformer with name '%@' was found for attribute '%@' on entity '%@'"
+ "re-tokenizing all full-text indices"
- " (current)"
- "(nil)"
- "CoreData: LRU[%u] = batch %u%s"
- "CoreData: Unhandled exception encountered during change request: %@ with userInfo %@"
- "CoreData: _PFBatchFaultingArray pre-fault: _array is nil (self=%p count=%u origBatch=%u)"
- "CoreData: _PFBatchFaultingArray pre-fault: _entryFlags is NULL (self=%p count=%u origBatch=%u)"
- "CoreData: _PFBatchFaultingArray pre-fault: _moc is nil (self=%p count=%u origBatch=%u)"
- "CoreData: _PFBatchFaultingArray pre-fault: slot %u is NSManagedObject %p (class=%s) but batch %u bit is clear (self=%p count=%u)"
- "CoreData: _PFBatchFaultingArray pre-fault: slot %u is nil before faulting (self=%p origBatch=%u count=%u)"
- "CoreData: _PFBatchFaultingArray(%s): _array is nil (self=%p count=%u idx=%u)"
- "CoreData: _PFBatchFaultingArray(%s): _entryFlags is NULL (self=%p count=%u idx=%u)"
- "CoreData: _PFBatchFaultingArray(%s): batch %u marked faulted but entry at idx %u is still NSManagedObjectID %p (self=%p count=%u)"
- "CoreData: _PFBatchFaultingArray(%s): batch %u not faulted after fault request (self=%p count=%u idx=%u batchSize=%u)"
- "CoreData: _faultBatchAtIndex: REENTRANT call detected (self=%p origBatch=%u idx=%u count=%u)"
- "CoreData: _faultBatchAtIndex: _array mutated before executeFetchRequest (self=%p origBatch=%u snapshot=%p current=%p)"
- "CoreData: _faultBatchAtIndex: _count mutated before executeFetchRequest (self=%p origBatch=%u snapshot=%u current=%u)"
- "CoreData: _faultBatchAtIndex: about to call objectWithID: with non-ObjectID at idx=%u (ancillary, self=%p origBatch=%u old=%p class=%s)"
- "CoreData: _faultBatchAtIndex: about to call objectWithID: with non-ObjectID at idx=%u (self=%p origBatch=%u old=%p class=%s)"
- "CoreData: _faultBatchAtIndex: empty batch before executeFetchRequest (self=%p origBatch=%u idx=%u count=%u batchOids=%lu _count=%u)"
- "CoreData: _releaseStaleBatch: batch %u entry at idx %u is already NSManagedObjectID %p (self=%p count=%u)"
- "CoreData: batch %u: bit=%d range=[%u,%u)"
- "CoreData: error: Unhandled error encountered during change request %@ with userInfo %@\n"
- "CoreData: error: disconnectAllConnections reconnect failed with exception: %@\n"
- "CoreData: error: no NSValueTransformer with class name '%@' was found for attribute '%@' on entity '%@'\n"
- "CoreData: fault: LRU[%u] = batch %u%s\n"
- "CoreData: fault: Unhandled exception encountered during change request: %@ with userInfo %@\n"
- "CoreData: fault: _PFBatchFaultingArray pre-fault: _array is nil (self=%p count=%u origBatch=%u)\n"
- "CoreData: fault: _PFBatchFaultingArray pre-fault: _entryFlags is NULL (self=%p count=%u origBatch=%u)\n"
- "CoreData: fault: _PFBatchFaultingArray pre-fault: _moc is nil (self=%p count=%u origBatch=%u)\n"
- "CoreData: fault: _PFBatchFaultingArray pre-fault: slot %u is NSManagedObject %p (class=%s) but batch %u bit is clear (self=%p count=%u)\n"
- "CoreData: fault: _PFBatchFaultingArray pre-fault: slot %u is nil before faulting (self=%p origBatch=%u count=%u)\n"
- "CoreData: fault: _PFBatchFaultingArray(%s): _array is nil (self=%p count=%u idx=%u)\n"
- "CoreData: fault: _PFBatchFaultingArray(%s): _entryFlags is NULL (self=%p count=%u idx=%u)\n"
- "CoreData: fault: _PFBatchFaultingArray(%s): batch %u marked faulted but entry at idx %u is still NSManagedObjectID %p (self=%p count=%u)\n"
- "CoreData: fault: _PFBatchFaultingArray(%s): batch %u not faulted after fault request (self=%p count=%u idx=%u batchSize=%u)\n"
- "CoreData: fault: _faultBatchAtIndex: REENTRANT call detected (self=%p origBatch=%u idx=%u count=%u)\n"
- "CoreData: fault: _faultBatchAtIndex: _array mutated before executeFetchRequest (self=%p origBatch=%u snapshot=%p current=%p)\n"
- "CoreData: fault: _faultBatchAtIndex: _count mutated before executeFetchRequest (self=%p origBatch=%u snapshot=%u current=%u)\n"
- "CoreData: fault: _faultBatchAtIndex: about to call objectWithID: with non-ObjectID at idx=%u (ancillary, self=%p origBatch=%u old=%p class=%s)\n"
- "CoreData: fault: _faultBatchAtIndex: about to call objectWithID: with non-ObjectID at idx=%u (self=%p origBatch=%u old=%p class=%s)\n"
- "CoreData: fault: _faultBatchAtIndex: empty batch before executeFetchRequest (self=%p origBatch=%u idx=%u count=%u batchOids=%lu _count=%u)\n"
- "CoreData: fault: _releaseStaleBatch: batch %u entry at idx %u is already NSManagedObjectID %p (self=%p count=%u)\n"
- "CoreData: fault: batch %u: bit=%d range=[%u,%u)\n"
- "CoreData: fault: slot[%u] = %p (%s) isOID=%d isMO=%d MISMATCH=%d\n"
- "CoreData: fault: state dump @ %s: self=%p count=%u batchSize=%u suspectBatch=%u suspectIdx=%u faultInProgress=%u LRUIndex=%u LRUEntryCount=%u\n"
- "CoreData: slot[%u] = %p (%s) isOID=%d isMO=%d MISMATCH=%d"
- "CoreData: state dump @ %s: self=%p count=%u batchSize=%u suspectBatch=%u suspectIdx=%u faultInProgress=%u LRUIndex=%u LRUEntryCount=%u"
- "CoreData: warning: no NSValueTransformer with class name '%@' was found for attribute '%@' on entity '%@'\n"
- "Unhandled error encountered during change request %@ with userInfo %@"
- "_faultBatchAtIndex"
- "countByEnumeratingWithState:"
- "disconnectAllConnections reconnect failed with exception: %@"
- "getObjects:range:(first)"
- "getObjects:range:(last)"
- "no NSValueTransformer with class name '%@' was found for attribute '%@' on entity '%@'"
- "objectAtIndexedSubscript:"
- "objectWithID: ancillary fetch"
- "objectWithID: regular fetch"
- "retainedObjectAtIndex:"
```
