## CalendarDatabase

> `/System/Library/PrivateFrameworks/CalendarDatabase.framework/CalendarDatabase`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdc30c` | `0xdc97c` | **`+0x670`** |
| `__AUTH.__objc_data` | `0xa00` | `0x550` | **`-0x4b0`** |
| `__DATA_DIRTY.__objc_data` | `0x320` | `0x7d0` | **`+0x4b0`** |
| `__TEXT.__oslogstring` | `0xcbe7` | `0xce69` | **`+0x282`** |
| `__TEXT.__cstring` | `0x1fa45` | `0x1fa98` | **`+0x53`** |
| `__AUTH_CONST.__cfstring` | `0xca40` | `0xca60` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x18e4` | `0x18f0` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x9a0` | `0x9a8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2d30` | `0x2d38` | **`+0x8`** |

### Other Changes

```diff

-1291.1.3.0.0
+1291.2.3.0.0

-  Functions: 4251
-  Symbols:   6560
-  CStrings:  3121
+  Functions: 4253
+  Symbols:   6564
+  CStrings:  3130
Symbols:
+ GCC_except_table342
+ GCC_except_table345
+ _CalDatabaseClearDefaultCalendarIfDefaultIsInAuxDatabaseWithID
+ _CalDatabaseCopyOrCreateDefaultCalendarForNewEventsUpdateIfNeeded
+ _CalPersonaUtilsErrorDomain
- GCC_except_table340
CStrings:
+ "Aux database containing the default calendar was deleted"
+ "CalCalendarRef CalDatabaseCopyDefaultOrAnyReadWriteCalendarForNewEvents(CalDatabaseRef, CalStoreRef, BOOL)"
+ "CalCalendarRef CalDatabaseCopyOrCreateDefaultCalendarForNewEventsUpdateIfNeeded(CalDatabaseRef, BOOL)"
+ "Could not get a container info for account ID %{public}@: %@"
+ "Could not get new calendar data container. store uuid = %{public}@: %@"
+ "Could not open %@: %s"
+ "Couldn't get container info for persona %{public}@. Using main database for this persona. error = %@"
+ "Couldn't look up persona %{public}@: %@"
+ "Couldn't look up persona ID %{public}@: %@"
+ "Failed to get URL for data container of account %{public}@: %@"
+ "Failed to get container info for account [%{public}@]: %@"
+ "Failed to get container info for persona %{public}@: %@"
+ "_CalAttachmentFileGetAttachmentContainerURLsForStoreProperties: Failed to get container for account %{public}@: %@"
+ "_CalAttachmentFileGetCalendarDataContainerForAttachmentFile: Failed to get container for account %{public}@: %@"
+ "_CalAttachmentFileMigrateAttachmentsInStoreFromOldPersistentIDToNewPersistentID: Failed to get container for account %{public}@: %@"
+ "commit at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4352"
+ "write at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4329"
- "CalCalendarRef CalDatabaseCopyDefaultOrAnyReadWriteCalendarForNewEvents(CalDatabaseRef, CalStoreRef)"
- "CalCalendarRef CalDatabaseCopyOrCreateDefaultCalendarForNewEvents(CalDatabaseRef)"
- "Could not get new calendar data container. store uuid = %{public}@"
- "Couldn't get container info for persona %{public}@. Using main database for this persona."
- "Couldn't look up persona %{public}@"
- "Couldn't look up persona ID %{public}@"
- "commit at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4338"
- "write at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4315"
```
