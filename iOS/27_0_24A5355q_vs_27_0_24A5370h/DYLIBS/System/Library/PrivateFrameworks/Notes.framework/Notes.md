## Notes

> `/System/Library/PrivateFrameworks/Notes.framework/Notes`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13ec4` | `0x13e54` | **`-0x70`** |
| `__TEXT.__const` | `0xac` | `0xa4` | **`-0x8`** |

### Other Changes

```diff

-2985.0.0.202.2
+2991.0.0.0.0
Functions:
~ ___41+[NoteContext persistentStoreCoordinator]_block_invoke : 1876 -> 1872
~ -[NoteContext handleMigration] : 1924 -> 1920
~ ___38-[AccountUtilities updateAccountInfos]_block_invoke : 884 -> 880
~ -[NoteContext setUpLocalAccountAndStore] : 840 -> 836
~ -[NoteContext setUpLastIndexTid] : 864 -> 860
~ -[NoteContext deleteChanges:] : 272 -> 268
~ -[NoteContext defaultStoreForNewNote] : 476 -> 472
~ -[NoteContext forceDeleteAccount:] : 1140 -> 1136
~ -[NoteContext deleteStore:] : 344 -> 340
~ -[NoteContext trackChanges:] : 2532 -> 2516
~ -[NoteResurrectionMergePolicy resolveConflicts:error:] : 2660 -> 2616
~ -[ExternalSequenceNumberToAttachmentNoteBodyToAttachmentMigrationPolicy unarchiveObjectWithExternalRepresentation:] : 548 -> 544
~ -[ExternalSequenceNumberToAttachmentNoteBodyToAttachmentMigrationPolicy createDestinationInstancesForSourceInstance:entityMapping:manager:error:] : 1092 -> 1084
~ -[ExternalSequenceNumberToAttachmentNoteBodyToAttachmentMigrationPolicy endEntityMapping:manager:error:] : 1352 -> 1348
~ +[NotesMigrationMapping descriptionStringFromSourceStoreNames:destinationStoreName:] : 472 -> 468
~ +[NotesMigrationMapping inferredMappingFromSourceModelNames:toDestinationModelName:] : 464 -> 460
~ -[NotesMigrationMapping canMigrateStoreMetadata:] : 332 -> 328
~ -[AccountUtilities accountsEnabledForNotes] : 384 -> 380
~ -[ICHTMLSearchIndexerDataSource contextWillSave:] : 792 -> 788
~ -[NoteStoreObject(SearchIndexable) isHiddenFromIndexing] : 56 -> 80
~ +[NoteAttachmentObject migrateAttachmentRelatedFilesInContext:error:] : 396 -> 392
```
