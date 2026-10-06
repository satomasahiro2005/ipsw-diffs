## MessagesCloudSync

> `/System/Library/PrivateFrameworks/MessagesCloudSync.framework/MessagesCloudSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x8400` | `0x8100` | **`-0x300`** |
| `__DATA_DIRTY.__bss` | `0x4800` | `0x4b00` | **`+0x300`** |
| `__TEXT.__text` | `0xfc370` | `0xfc1a8` | **`-0x1c8`** |
| `__TEXT.__cstring` | `0x3ec1` | `0x3e01` | **`-0xc0`** |
| `__DATA.__data` | `0x10a0` | `0xff0` | **`-0xb0`** |
| `__TEXT.__eh_frame` | `0x9d94` | `0x9cf4` | **`-0xa0`** |
| `__DATA_DIRTY.__data` | `0x26a0` | `0x2710` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x5703` | `0x5763` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x1014` | `0xfd8` | **`-0x3c`** |
| `__TEXT.__swift5_typeref` | `0x2842` | `0x2826` | **`-0x1c`** |
| `__DATA.__common` | `0x28` | `0x10` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `0x258` | `0x270` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x3738` | `0x3720` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x10d8` | `0x10e0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x7d8` | `0x7e0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xff8` | `0xff0` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x42c` | `0x430` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x4c8` | `0x4cc` | **`+0x4`** |

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  Functions: 3822
-  Symbols:   441
-  CStrings:  860
+  Functions: 3817
+  Symbols:   442
+  CStrings:  856
Symbols:
+ _IMCloudKitAttachmentDownloadHistoryFinished
CStrings:
+ "Business chat is not supported for message %s, dropping"
+ "Dropped %ld/%ld records of type %s during import from syncStore! Failed GUIDs: %s"
+ "Error importing transfer %s - %@"
+ "Error importing: %@ for recordType %s, guid = %s, record.recordType %s, record.recordName = %s)"
+ "Existing item with no guid, dropping"
+ "Import was .unsupported for recordType %s, guid %s"
+ "Item is an emojiTapBack but emojiTapbacks are not enabled, dropping"
+ "Item is not compatible with MIC %s"
+ "Item is not compatible with MIC %s, dropping"
+ "No record type for recordType %s guid %s"
+ "Record is .unknown for recordType %s guid %s"
+ "Should not store message record for %s, account or alias mismatch, dropping"
- "Business chat is not supported, do not import message %s"
- "Clearing stale resume state from phase %s (now running %s)"
- "Error importing: %@ for record(guid = %s, recordType = %s, recordName = %s)"
- "Existing item with no guid, do not store"
- "Failed to report stopped to BackgroundSystemTasks: %@"
- "Found %ld records without GUIDs!"
- "MiC.DASCheckpointBalancedVersion"
- "MiC.SyncResumeBatchProgress"
- "MiC.SyncResumeCompletedStepIndex"
- "MiC.SyncResumePhase"
- "No record type for record guid %s"
- "Resuming %s from batch %lld/%ld"
- "Resuming sync from step %ld, skipping %ld completed steps"
- "Should not store message record for %s, account or alias mismatch"
- "Skipping save: persistent store coordinator has no stores attached"
- "com.apple.messages.sync.Initial"
```
