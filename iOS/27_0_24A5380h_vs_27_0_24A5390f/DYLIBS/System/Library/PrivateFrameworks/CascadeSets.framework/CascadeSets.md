## CascadeSets

> `/System/Library/PrivateFrameworks/CascadeSets.framework/CascadeSets`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa6ddc` | `0xa7868` | **`+0xa8c`** |
| `__TEXT.__oslogstring` | `0x4d40` | `0x4dd0` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x5ac0` | `0x5b00` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x64f4` | `0x6534` | **`+0x40`** |
| `__TEXT.__cstring` | `0x8967` | `0x8997` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1c28` | `0x1c40` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3170` | `0x3188` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x3188` | `0x31a0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x6d0` | `0x6c8` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x183c` | `0x1840` | **`+0x4`** |

### Other Changes

```diff

-243.0.0.0.0
+247.0.1.0.0

-  Functions: 4553
-  Symbols:   5051
-  CStrings:  1281
+  Functions: 4558
+  Symbols:   5056
+  CStrings:  1285
Symbols:
+ -[CCDataResourceReadAccess resourceGenerationForSet:error:]
+ -[CCDatabaseItemRetriever _enumerateSourceItemIdHashesMatchingIndexedFieldPredicate:error:usingBlock:]
+ -[CCDatabaseItemRetriever _enumerateSourceItemIdHashesWithItemIdentifier:itemIdentifierType:error:usingBlock:]
+ -[CCDatabaseItemRetriever _enumerateSourceItemIdHashesWithSourceItemIdentifier:error:usingBlock:]
+ -[CCDatabaseWriter _compactTombstoneCountBucketRows:error:]
+ -[CCDatabaseWriter _deleteExpiredItemInstances:error:]
+ -[CCSet resourceGenerationWithUseCase:error:]
+ ___102-[CCDatabaseItemRetriever _enumerateSourceItemIdHashesMatchingIndexedFieldPredicate:error:usingBlock:]_block_invoke
+ ___110-[CCDatabaseItemRetriever _enumerateSourceItemIdHashesWithItemIdentifier:itemIdentifierType:error:usingBlock:]_block_invoke
+ ___54-[CCDatabaseWriter _deleteExpiredItemInstances:error:]_block_invoke
+ ___block_descriptor_72_e8_32s40bs48r56r64r_e18_B16?0"NSNumber"8ls40l8r48l8r56l8s32l8r64l8
- -[CCDatabaseWriter _compactTombstoneCountBucketRows:]
- -[CCDatabaseWriter _deleteExpiredItemInstances:]
- _OBJC_CLASS_$__PASDeviceState
- ___48-[CCDatabaseWriter _deleteExpiredItemInstances:]_block_invoke
- ___90-[CCDatabaseItemRetriever _enumerateSourceItemIdHashesMatchingPredicate:error:usingBlock:]_block_invoke
- ___block_descriptor_56_e8_32s40r48r_e18_B16?0"NSNumber"8lr40l8s32l8r48l8
CStrings:
+ "%@: Deferred after deleting %u expired item instance(s)"
+ "%@: Deferring remote device state cleanup"
+ "%@: Deferring remote device state expiry"
+ "%@: Deferring tombstone count bucket compaction"
+ "No local device site in set: %@"
+ "Successfully renamed directory at path %s into %s; cleanup deferred to prune-temporary-files"
+ "itemIdentifier"
- "Can't remove folder at %@ with error %@, isUnlocked: %hhd"
- "Successfully removed folder at %@"
- "Successfully renamed directory at path %s into %s"
```
