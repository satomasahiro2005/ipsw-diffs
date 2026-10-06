## IMDPersistence

> `/System/Library/PrivateFrameworks/IMDPersistence.framework/IMDPersistence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ffef4` | `0x300800` | **`+0x90c`** |
| `__DATA.__bss` | `0x6768` | `0x64e8` | **`-0x280`** |
| `__DATA_DIRTY.__bss` | `0x2780` | `0x2a00` | **`+0x280`** |
| `__DATA_DIRTY.__data` | `0x62b0` | `0x6500` | **`+0x250`** |
| `__TEXT.__oslogstring` | `0x3c174` | `0x3c3c4` | **`+0x250`** |
| `__TEXT.__cstring` | `0x5d9d4` | `0x5db34` | **`+0x160`** |
| `__AUTH.__data` | `0x1df8` | `0x1cb0` | **`-0x148`** |
| `__AUTH_CONST.__cfstring` | `0x130c0` | `0x131c0` | **`+0x100`** |
| `__DATA.__data` | `0x3b40` | `0x3a70` | **`-0xd0`** |
| `__AUTH.__objc_data` | `0x1038` | `0xfc0` | **`-0x78`** |
| `__DATA_DIRTY.__objc_data` | `0x3040` | `0x30b8` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0xc710` | `0xc764` | **`+0x54`** |
| `__DATA_CONST.__const` | `0x6500` | `0x6528` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0xe248` | `0xe268` | **`+0x20`** |
| `__DATA.__common` | `0x288` | `0x270` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `0x100` | `0x118` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xa48c` | `0xa49c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xa320` | `0xa330` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x6b68` | `0x6b70` | **`+0x8`** |

### Other Changes

```diff

-1491.200.63.2.1
+1491.200.73.0.0

-  Functions: 13781
+  Functions: 13788

-  CStrings:  7534
+  CStrings:  7546
CStrings:
+ "Alert watermark dated in the future: %@"
+ "BOOL __IMDDatabasePerformOneMigration(int, CSDBSqliteDatabase *, CSDBSqliteConnection *, int, int *, NSError *__autoreleasing *, __strong MigratorBlock)"
+ "Copying %lu attachment download info entries beforeDate: %@ earliestDate: %lld limit: %lld"
+ "IMDNotificationsController.futureAlertWatermark"
+ "Last alerted failed message date was stored in the future: [%lld]-[%@], now: [%lld]-[%@]. Clamping to now, which restores alerting for failures dated before it."
+ "Last alerted message date was stored in the future: [%lld]-[%@], now: [%lld]-[%@]. Clamping to now, which restores alerting for messages dated before it."
+ "Notifications"
+ "Refusing to advance last alerted failed message date to a future date: [%lld]-[%@], now: [%lld]-[%@]. Clamping it to now instead."
+ "Refusing to advance last alerted message date to a future date: [%lld]-[%@], now: [%lld]-[%@]. Clamping it to now instead."
+ "SELECT a.ROWID, a.guid, a.total_bytes, a.ck_record_id, m.date FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 AND IFNULL(m.date, 0) >= ? ORDER BY m.date DESC, a.ROWID ASC LIMIT ? "
+ "SELECT a.ROWID, a.guid, a.total_bytes, a.ck_record_id, m.date FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 AND m.date < ? AND IFNULL(m.date, 0) >= ? ORDER BY m.date DESC, a.ROWID ASC LIMIT ? "
+ "advance-failed"
+ "advance-received"
+ "earliestDate"
+ "setupFirstLoad-failed"
+ "setupFirstLoad-received"
+ "void IMDMessageRecordAnonymizedUpdate(IMDMessageRecordRef, CFStringRef, CFDataRef, CFStringRef, CFStringRef, CFStringRef, CFDataRef, CFDataRef, CFStringRef, BOOL, BOOL, CFStringRef, CFStringRef, CFStringRef)"
+ "void _IMDPerformBlock(__strong dispatch_block_t, IMFileLocation_t *)"
+ "void _IMDPerformBlockWithDelay(NSTimeInterval, __strong dispatch_block_t, IMFileLocation_t *)"
+ "void _IMDPerformLockedConnectionBlock(__strong CSDBLockedConnection, IMFileLocation_t *)"
+ "void _IMDPerformLockedDatabaseBlock(__strong CSDBLockedDatabase, IMFileLocation_t *)"
+ "void _IMDPerformLockedMessageStoreBlock(__strong CSDBLockedRecordStore, IMFileLocation_t *)"
+ "void _IMDPerformLockedMessageStoreBlockWithoutInitialize(__strong CSDBLockedRecordStore, IMFileLocation_t *)"
+ "void _IMDPerformLockedStatementBlockWithQuery(CFStringRef, __strong CSDBLockedStatement, IMFileLocation_t *)"
- "BOOL __IMDDatabasePerformOneMigration(int, CSDBSqliteDatabase *, CSDBSqliteConnection *, int, int *, NSError **, MigratorBlock)"
- "Copying %lu attachment download info entries beforeDate: %@ limit: %lld"
- "SELECT a.ROWID, a.guid, a.total_bytes, a.ck_record_id, m.date FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 AND m.date < ? ORDER BY m.date DESC, a.ROWID ASC LIMIT ? "
- "SELECT a.ROWID, a.guid, a.total_bytes, a.ck_record_id, m.date FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 ORDER BY m.date DESC, a.ROWID ASC LIMIT ? "
- "void IMDMessageRecordAnonymizedUpdate(IMDMessageRecordRef, CFStringRef, CFDataRef, CFStringRef, CFStringRef, CFStringRef, CFDataRef, CFDataRef, CFStringRef, BOOL, CFStringRef, CFStringRef, CFStringRef)"
- "void _IMDPerformBlock(dispatch_block_t, IMFileLocation_t *)"
- "void _IMDPerformBlockWithDelay(NSTimeInterval, dispatch_block_t, IMFileLocation_t *)"
- "void _IMDPerformLockedConnectionBlock(CSDBLockedConnection, IMFileLocation_t *)"
- "void _IMDPerformLockedDatabaseBlock(CSDBLockedDatabase, IMFileLocation_t *)"
- "void _IMDPerformLockedMessageStoreBlock(CSDBLockedRecordStore, IMFileLocation_t *)"
- "void _IMDPerformLockedMessageStoreBlockWithoutInitialize(CSDBLockedRecordStore, IMFileLocation_t *)"
- "void _IMDPerformLockedStatementBlockWithQuery(CFStringRef, CSDBLockedStatement, IMFileLocation_t *)"
```
