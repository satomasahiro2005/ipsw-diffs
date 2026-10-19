## CalendarDatabase

> `/System/Library/PrivateFrameworks/CalendarDatabase.framework/CalendarDatabase`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1fa98` | `0x1fb91` | **`+0xf9`** |
| `__AUTH_CONST.__cfstring` | `0xca60` | `0xcb00` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0xce69` | `0xcdd0` | **`-0x99`** |
| `__TEXT.__text` | `0xdc97c` | `0xdc940` | **`-0x3c`** |
| `__TEXT.__unwind_info` | `0x2d38` | `0x2d28` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0xfe0` | `0xfd8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x9a8` | `0x9a0` | **`-0x8`** |

### Other Changes

```diff

-  Symbols:   6564
-  CStrings:  3130
+  Symbols:   6562
+  CStrings:  3131
Symbols:
+ GCC_except_table57
+ __CalAttachmentFileResolveLocalURLReArchivingIfNeeded
- GCC_except_table53
- GCC_except_table56
- _NSURLCreationDateKey
- _UnzipArchive
Functions:
~ _CalAttachmentFileMigrateTables : 132 -> 492
~ __CalAttachmentFileCopyLocalURLForArchivedData : 476 -> 164
~ __CalAttachmentFileSetFileDataWithOpenFile : 2620 -> 2484
~ __CalAttachmentFileCopyLocalURL -> __CalAttachmentFileGetLocalRelativePath : 132 -> 212
~ __CalAttachmentFileGetLocalRelativePath -> __CalAttachmentFileGetCalendarDataContainerForAttachmentFile : 212 -> 292
~ __CalAttachmentFileGetCalendarDataContainerForAttachmentFile -> __CalAttachmentFileResolveLocalURLReArchivingIfNeeded : 292 -> 456
~ _CalDatabaseDeleteOrphanedAttachmentsInDirectory : 1760 -> 1464
CStrings:
+ "%@.zip"
+ "AutoArchivedPathMigrationCompleted"
+ "UPDATE AttachmentFile SET local_path = local_path || '.zip' WHERE (flags & %d) != 0 AND SUBSTR(local_path, -4) != '.zip';"
+ "UPDATE AttachmentFile SET local_path = local_path || '.zip' WHERE (flags & %d) != 0;"
+ "Unable to re-archive attachment data: %@"
- "Attachment cleanup: skipping removing file because it is archived and is too young: %@"
- "Error checking creation date for %@: %@"
- "Failed to unzip attachment (error: %@)."
- "Unable to archive data: %@"
```
