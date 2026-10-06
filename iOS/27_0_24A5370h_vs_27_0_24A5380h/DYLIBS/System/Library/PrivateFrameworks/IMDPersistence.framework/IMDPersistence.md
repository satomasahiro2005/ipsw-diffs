## IMDPersistence

> `/System/Library/PrivateFrameworks/IMDPersistence.framework/IMDPersistence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x319010` | `0x32a010` | **`+0x11000`** |
| `__DATA_DIRTY.__data` | `0x6378` | `0xa570` | **`+0x41f8`** |
| `__AUTH.__data` | `0x5958` | `0x1c00` | **`-0x3d58`** |
| `__AUTH.__objc_data` | `0x2848` | `0xbd0` | **`-0x1c78`** |
| `__DATA_DIRTY.__objc_data` | `0x1b50` | `0x37c8` | **`+0x1c78`** |
| `__TEXT.__eh_frame` | `0xb6d0` | `0xbce8` | **`+0x618`** |
| `__TEXT.__oslogstring` | `0x3b72f` | `0x3bd1f` | **`+0x5f0`** |
| `__DATA_DIRTY.__bss` | `0x4cf0` | `0x5280` | **`+0x590`** |
| `__DATA.__bss` | `0xcab8` | `0xc538` | **`-0x580`** |
| `__TEXT.__unwind_info` | `0xb010` | `0xb318` | **`+0x308`** |
| `__AUTH_CONST.__const` | `0xf548` | `0xf830` | **`+0x2e8`** |
| `__TEXT.__cstring` | `0x5e554` | `0x5e2b4` | **`-0x2a0`** |
| `__TEXT.__swift5_typeref` | `0x55bc` | `0x57b6` | **`+0x1fa`** |
| `__TEXT.__const` | `0x10f68` | `0x11148` | **`+0x1e0`** |
| `__DATA.__data` | `0x40b0` | `0x3f60` | **`-0x150`** |
| `__TEXT.__objc_methlist` | `0x98ec` | `0x99d4` | **`+0xe8`** |
| `__DATA_CONST.__const` | `0x66f8` | `0x67d0` | **`+0xd8`** |
| `__DATA_CONST.__objc_selrefs` | `0x65a8` | `0x6680` | **`+0xd8`** |
| `__TEXT.__swift5_capture` | `0x1ec0` | `0x1f68` | **`+0xa8`** |
| `__TEXT.__gcc_except_tab` | `0xc730` | `0xc7d4` | **`+0xa4`** |
| `__TEXT.__swift5_fieldmd` | `0x4998` | `0x4a38` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x787c` | `0x7910` | **`+0x94`** |
| `__DATA.__common` | `0x350` | `0x2d0` | **`-0x80`** |
| `__DATA_DIRTY.__common` | `0x180` | `0x200` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x12b00` | `0x12b60` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x4729` | `0x4789` | **`+0x60`** |
| `__TEXT.__swift_as_cont` | `0x218` | `0x278` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x1bc8` | `0x1c20` | **`+0x58`** |
| `__AUTH_CONST.__auth_got` | `0x2a48` | `0x2a90` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x14a20` | `0x14a40` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x510` | `0x528` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0xe0` | `0xf4` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x4d4` | `0x4e4` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xe4` | `0xf4` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x7c8` | `0x7c0` | **`-0x8`** |

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  Functions: 14906
-  Symbols:   2844
-  CStrings:  7646
+  Functions: 15127
+  Symbols:   2852
+  CStrings:  7670
Symbols:
+ _IMDCNDisplayNameAndShortNameForHandleID
+ _IMDPersistentTaskContentDateKey
+ _IMDPersistentTaskRequestDateKey
+ _OBJC_CLASS_$_IMDCoreSpotlightSelectiveReindexingJob
+ _OBJC_CLASS_$_IMPersistentTaskContentDateDescriptor
+ _OBJC_METACLASS_$_IMDCoreSpotlightSelectiveReindexingJob
+ ___XPCServerIMDCNDisplayNameAndShortNameForHandleID_IPCAction
+ ___syncXPCIMDCNDisplayNameAndShortNameForHandleID_IPCAction
+ _sqlite3_get_auxdata
+ _sqlite3_set_auxdata
+ _swift_release_x11
+ _swift_release_x12
- _IMIsRunningInIMDPersistenceAgent
- __xpc_type_array
- _xpc_array_get_int64
- _xpc_int64_create
CStrings:
+ "\n    ) OR item_type != 0\n)"
+ "\nAND (\n    (\n        associated_message_type != 0 AND associated_message_type NOT IN ("
+ "\nORDER BY cmj.message_date DESC"
+ " FROM persistent_tasks INDEXED BY persistent_tasks_report WHERE retry_count < 5 AND lane =  ?  GROUP BY flag, flag_group, lane, reason"
+ " GROUP BY flag, flag_group, lane, reason"
+ " OR content_date IS NULL"
+ "%K <= %@"
+ "%K IN %@ AND %K = %@"
+ ")\n        AND associated_message_type NOT BETWEEN "
+ ",\n    user_info = im_reconcile_ptask_user_info_with_shadowed_reason(1, persistent_tasks.flag, persistent_tasks.user_info, excluded.user_info, persistent_tasks.reason, excluded.reason),\n    retry_count = excluded.retry_count,\n    request_date = MAX(excluded.request_date, persistent_tasks.request_date)"
+ ", COUNT(CASE WHEN ("
+ "Action: Get contact display name and short name for handle id"
+ "Clearing ptasks filtered by predicate %s"
+ "Completion of late indexing did not satisfy any scheduled messages"
+ "Completion of late indexing satisfies scheduled indexing as it indexes full content"
+ "Could not convert predicate to SQL: "
+ "Could not determine MergedFilteredThreadsV2 migration state with error: %@"
+ "DELETE FROM persistent_tasks\nWHERE "
+ "Failed to clear %lu pending retry task(s) for flag %ld after late Spotlight success: %@"
+ "Failed to clear tasks with error %@"
+ "Failed to load conservative windowed ptask reports: %@"
+ "Failed to load windowed ptask reports: %@"
+ "Finished legacy command IMDCNDisplayNameAndShortNameForHandleID_IPCAction: Action: Get contact display name and short name for handle id async %{bool}d"
+ "Handled message IMDCNDisplayNameAndShortNameForHandleID_IPCAction: Action: Get contact display name and short name for handle id from (%d) wantsReply %{BOOL}d"
+ "Handling message IMDCNDisplayNameAndShortNameForHandleID_IPCAction: Action: Get contact display name and short name for handle id from (%d) wantsReply %{BOOL}d"
+ "IMDCNDisplayNameAndShortNameForHandleID returning total Contact keys: %lu"
+ "IMDPersistentTaskQueryProvider"
+ "INNER JOIN chat_message_join cmj\n    ON cmj.message_id = m.rowid\nWHERE\n    cmj.message_date >= "
+ "INNER JOIN chat_message_join cmj ON cmj.message_id = m.ROWID\nLEFT JOIN persistent_tasks mpt ON mpt.guid = m.guid\nWHERE mpt.guid IS NULL\nLIMIT  ? "
+ "INSERT INTO persistent_tasks\n(guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info, request_date, content_date)\nVALUES "
+ "INSERT INTO persistent_tasks (guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info, request_date, content_date)\nSELECT"
+ "INSERT INTO recoverable_message_part (chat_id, message_id, part_index, delete_date, part_text, ck_sync_state)   SELECT cmj.chat_id, cmj.message_id, ?, ?, ?, 0   FROM chat_message_join AS cmj   JOIN message AS m   ON m.ROWID = cmj.message_id AND m.guid = ?;"
+ "INSERT OR REPLACE INTO chat_recoverable_message_join (chat_id, message_id, delete_date) SELECT chat_id, message_id, message_date FROM chat_message_join WHERE message_date < ? AND chat_id IN ("
+ "INTEGER DEFAULT NULL"
+ "Late indexing of %@ with migration requirements %llu does not satisfy scheduled indexing with migration requirements %llu"
+ "Late indexing of %@ with migration requirements %llu does satisfy scheduled indexing"
+ "Late indexing was a patch, checking if any scheduled patches are fully satisfied"
+ "MergedFilteredThreadsV2 has already been run"
+ "MergedFilteredThreadsV2 migration"
+ "MergedFilteredThreadsV2 migration failed due to: %@"
+ "ROWID INTEGER PRIMARY KEY AUTOINCREMENT UNIQUE, guid TEXT NOT NULL, flag_group INTEGER NOT NULL, flag INTEGER NOT NULL, flag_priority INTEGER NOT NULL, lane INTEGER NOT NULL, reason INTEGER NOT NULL, reason_priority INTEGER NOT NULL, user_info BLOB, retry_count INTEGER DEFAULT 0, request_date INTEGER NOT NULL DEFAULT 0, content_date INTEGER, UNIQUE(guid, flag) "
+ "Recently Deleted | Will begin permanently deleting recoverable messages for %lu chatGUIDs"
+ "Reported progress after late indexing completion"
+ "Reporting progress after late indexing completion"
+ "Reversible MergedFilteredThreadsV2 Migration"
+ "SELECT\n    ROWID, guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info, retry_count, request_date, content_date\nFROM persistent_tasks\nINDEXED BY persistent_tasks_exec_sort\nWHERE"
+ "SELECT\n    ROWID, guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info, retry_count, request_date, content_date\nFROM persistent_tasks\nWHERE "
+ "SELECT\n    flag, flag_group, lane, reason, COUNT(*) AS count\nFROM persistent_tasks INDEXED BY persistent_tasks_report\nWHERE retry_count < 5"
+ "SELECT 1\nFROM persistent_tasks INDEXED BY persistent_tasks_report\nWHERE flag =  ?  AND flag_group =  ?  AND lane =  ?  AND reason =  ?  AND retry_count < 5"
+ "SELECT EXISTS(\n    SELECT 1\n    FROM message m\n    WHERE m.ck_chat_id IS NOT NULL AND m.ck_chat_id != ''\n        AND NOT EXISTS (\n            SELECT 1\n            FROM chat_message_join cmj\n            WHERE cmj.message_id = m.rowid\n        )\n        AND NOT EXISTS (\n            SELECT 1\n            FROM chat_recoverable_message_join crmj\n            WHERE crmj.message_id = m.rowid\n        )\n        AND CASE\n            WHEN instr(m.ck_chat_id, ';') > 0 THEN\n                EXISTS (\n                    SELECT 1\n                    FROM chat\n                    WHERE chat.chat_identifier = SUBSTR(\n                        m.ck_chat_id,\n                        INSTR(SUBSTR(m.ck_chat_id, INSTR(m.ck_chat_id, ';') + 1), ';')\n                            + INSTR(m.ck_chat_id, ';') + 1\n                    )\n                )\n            ELSE\n                EXISTS (\n                    SELECT 1\n                    FROM chat_lookup cl\n                    INNER JOIN chat c ON c.rowid = cl.chat\n                    WHERE cl.identifier = m.ck_chat_id\n                    AND cl.domain = domain_for_service(m.service)\n                )\n        END\n);"
+ "SELECT flag, flag_group, lane, reason"
+ "Sending legacy command IMDCNDisplayNameAndShortNameForHandleID_IPCAction: Action: Get contact display name and short name for handle id async %{bool}d"
+ "Spotlight acknowledged %lu items for flag %ld after we already timed out; clearing pending retry and updating index_state"
+ "UPDATE message\nSET index_state = 0\nWHERE rowid IN "
+ "UPDATE message\nSET index_state = 1\nWHERE index_state = 0 AND rowid IN "
+ "UPDATE message\nSET index_state = 2\nWHERE message.rowid BETWEEN "
+ "UPDATE message SET message_summary_info = NULL, ck_sync_state = 0 WHERE length(message_summary_info) >  ? "
+ "UPDATE persistent_tasks\nSET content_date = m.date\nFROM message m\nWHERE m.guid = persistent_tasks.guid AND persistent_tasks.flag IN "
+ "UPDATE persistent_tasks SET retry_count = 0 WHERE flag_group = 0 AND retry_count = 5"
+ "WHERE c.ROWID <=  ? \nORDER BY c.ROWID DESC\nLIMIT  ? "
+ "WHERE m.guid IN "
+ "WHERE m.rowid BETWEEN "
+ "WHERE m.rowid IN "
+ "clearTasks(with:completionBlock:)"
+ "content_date"
+ "content_date <  ? "
+ "content_date >=  ? "
+ "content_date IS NULL"
+ "o"
+ "persistent_tasks(lane DESC, flag_group ASC, flag_priority DESC, reason_priority DESC, (content_date IS NULL) DESC, content_date DESC, retry_count ASC) WHERE retry_count < 5"
+ "persistent_tasks(lane, flag, flag_group, reason, content_date, retry_count) WHERE retry_count < 5"
+ "request_date"
+ "v32@?0@\"<IMDIndexingIntegration>\"8@\"IMDIndexingContext\"16@?<v@?@\"NSError\">24"
- "\nFROM chat c WHERE c.ROWID <= "
- "\nFROM message m\nINNER JOIN chat_message_join cmj\n    ON cmj.message_id = m.rowid\nWHERE\n    cmj.message_date >= "
- "\nFROM message m\nWHERE m.rowid BETWEEN "
- "\nFROM message m\nWHERE m.rowid IN "
- "\nORDER BY c.ROWID DESC\nLIMIT "
- "\nORDER BY cmj.message_date DESC\n"
- "    INSERT INTO persistent_tasks (guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info)\n    SELECT *,  ? , "
- "    INSERT INTO persistent_tasks (guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info)\n    SELECT *,  ? ,  ? , "
- "    INSERT INTO persistent_tasks (guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info)\n    SELECT *,  ? ,  ? ,  ? , "
- "    INSERT INTO persistent_tasks (guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info)\n    SELECT *,  ? ,  ? ,  ? ,  ? , "
- "    INSERT INTO persistent_tasks (guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info)\n    SELECT *,  ? ,  ? ,  ? ,  ? ,  ? , "
- "    INSERT INTO persistent_tasks (guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info)\n    SELECT *,  ? ,  ? ,  ? ,  ? ,  ? ,  ? , "
- "    INSERT INTO persistent_tasks (guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info)\n    SELECT *,  ? ,  ? ,  ? ,  ? ,  ? ,  ? ,  ?  FROM\n        ( VALUES "
- "    INSERT INTO persistent_tasks (guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info)\n    SELECT m.guid,  ? ,  ? ,  ? ,  ? ,  ? ,  ? ,  ?  FROM message m\n        INNER JOIN chat_message_join cmj ON cmj.message_id = m.ROWID\n        LEFT JOIN persistent_tasks mpt ON mpt.guid = m.guid\n        WHERE mpt.guid IS NULL\n        LIMIT  ? \n    RETURNING guid;"
- " )\n        WHERE 1\n    ON CONFLICT DO NOTHING;"
- "!%"
- ") THEN im_reconcile_ptask_user_info_with_shadowed_reason(persistent_tasks.flag, persistent_tasks.user_info, excluded.user_info, persistent_tasks.reason, excluded.reason)\n            WHEN persistent_tasks.user_info = excluded.user_info THEN persistent_tasks.user_info\n            WHEN coalesce(length(persistent_tasks.user_info), 0) = 0 THEN excluded.user_info\n            WHEN coalesce(length(excluded.user_info), 0) = 0 THEN persistent_tasks.user_info\n            ELSE im_reconcile_ptask_user_info(persistent_tasks.flag, persistent_tasks.user_info, excluded.user_info)\n        END),\n    retry_count = excluded.retry_count"
- ",\n    user_info =\n        (CASE\n            WHEN (persistent_tasks.reason != excluded.reason AND "
- "DELETE FROM unsynced_removed_recoverable_messages WHERE ROWID IN"
- "INSERT INTO persistent_tasks\n(guid, flag_group, flag, flag_priority, lane, reason, reason_priority)\nSELECT m.guid, "
- "INSERT INTO persistent_tasks\n(guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info)\nSELECT c.guid,  ? , "
- "INSERT INTO persistent_tasks\n(guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info)\nSELECT c.guid,  ? ,  ? , "
- "INSERT INTO persistent_tasks\n(guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info)\nVALUES "
- "INSERT INTO persistent_tasks (guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info)\nSELECT m.guid, "
- "INSERT INTO persistent_tasks (guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info)\nSELECT m.guid,  ? ,  ? , "
- "INSERT INTO recoverable_message_part (chat_id, message_id, part_index, delete_date, part_text, ck_sync_state)   SELECT cmj.chat_id, cmj.message_id, ?, ?, ?, ?   FROM chat_message_join AS cmj   JOIN message AS m   ON m.ROWID = cmj.message_id AND m.guid = ?;"
- "INSERT OR REPLACE INTO chat_recoverable_message_join (chat_id, message_id, delete_date) SELECT chat_id, message_id, ? FROM chat_message_join WHERE message_date < ? AND chat_id IN ("
- "Overriding recently deleted expiration to %lld days based on default com.apple.Messages days-to-deleted-cleanup"
- "ROWID INTEGER PRIMARY KEY AUTOINCREMENT UNIQUE, guid TEXT NOT NULL, flag_group INTEGER NOT NULL, flag INTEGER NOT NULL, flag_priority INTEGER NOT NULL, lane INTEGER NOT NULL, reason INTEGER NOT NULL, reason_priority INTEGER NOT NULL, user_info BLOB, retry_count INTEGER DEFAULT 0, UNIQUE(guid, flag) "
- "Recently Deleted | Failed to clear tombstones by ROWIDs: %@"
- "Recently Deleted | Finished clearing %lu specific recoverable message tombstones by ROWID"
- "Recently Deleted | Will begin clearing %lu specific recoverable message tombstones by ROWID"
- "Recently Deleted | Will begin permanently deleting recoverable messages for %lu chatGUIDs, beforeDate: %@"
- "SELECT\n    ROWID, guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info, retry_count\nFROM persistent_tasks\nINDEXED BY persistent_tasks_exec_sort\nWHERE"
- "SELECT\n    ROWID, guid, flag_group, flag, flag_priority, lane, reason, reason_priority, user_info, retry_count\nFROM persistent_tasks\nWHERE "
- "SELECT\n    flag, flag_group, lane, reason, COUNT(*) AS count\nFROM persistent_tasks\nWHERE retry_count < 5\nGROUP BY flag, flag_group, lane, reason"
- "SELECT 1\nFROM persistent_tasks\nWHERE flag =  ?  AND flag_group =  ?  AND lane =  ?  AND reason =  ?  AND retry_count < 5\nLIMIT 1"
- "UPDATE message\nSET index_state = (\n    CASE\n        WHEN (associated_message_type != 0 AND associated_message_type NOT IN ( ? , "
- "UPDATE message\nSET index_state = (\n    CASE\n        WHEN (associated_message_type != 0 AND associated_message_type NOT IN ( ? ,  ? ) AND associated_message_type NOT BETWEEN "
- "UPDATE message\nSET index_state = (\n    CASE\n        WHEN (associated_message_type != 0 AND associated_message_type NOT IN ( ? ,  ? ) AND associated_message_type NOT BETWEEN  ?  AND "
- "UPDATE message\nSET index_state = (\n    CASE\n        WHEN (associated_message_type != 0 AND associated_message_type NOT IN ( ? ,  ? ) AND associated_message_type NOT BETWEEN  ?  AND  ? ) OR item_type != 0 THEN 2\n        WHEN "
- "UPDATE message\nSET index_state = (\n    CASE\n        WHEN (associated_message_type != 0 AND associated_message_type NOT IN ( ? ,  ? ) AND associated_message_type NOT BETWEEN  ?  AND  ? ) OR item_type != 0 THEN 2\n        WHEN  ?  AND (index_state = 1 OR index_state = 3) THEN 0\n        ELSE index_state\n    END\n)\nWHERE message.rowid BETWEEN "
- "days-to-deleted-cleanup"
- "fromSync"
- "im_reconcile_ptask_user_info"
- "im_reconcile_ptask_user_info: wrong number of arguments"
- "persistent_tasks(flag, flag_group, lane, reason, retry_count) WHERE retry_count < 5"
- "persistent_tasks(lane DESC, flag_group ASC, flag_priority DESC, reason_priority DESC, retry_count ASC)"
- "tombstoneRowID"
```
