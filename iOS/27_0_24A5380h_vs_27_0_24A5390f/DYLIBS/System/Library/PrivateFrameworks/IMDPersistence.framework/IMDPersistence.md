## IMDPersistence

> `/System/Library/PrivateFrameworks/IMDPersistence.framework/IMDPersistence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32a010` | `0x336548` | **`+0xc538`** |
| `__TEXT.__cstring` | `0x5e2b4` | `0x5f1e4` | **`+0xf30`** |
| `__AUTH_CONST.__const` | `0xf830` | `0x10170` | **`+0x940`** |
| `__AUTH_CONST.__objc_const` | `0x14a40` | `0x15150` | **`+0x710`** |
| `__TEXT.__oslogstring` | `0x3bd1f` | `0x3c38f` | **`+0x670`** |
| `__TEXT.__eh_frame` | `0xbce8` | `0xc2d0` | **`+0x5e8`** |
| `__TEXT.__const` | `0x11148` | `0x11528` | **`+0x3e0`** |
| `__TEXT.__objc_methlist` | `0x99d4` | `0x9cfc` | **`+0x328`** |
| `__TEXT.__unwind_info` | `0xb318` | `0xb610` | **`+0x2f8`** |
| `__DATA.__bss` | `0xc538` | `0xc7d8` | **`+0x2a0`** |
| `__DATA.__data` | `0x3f60` | `0x41d0` | **`+0x270`** |
| `__AUTH_CONST.__cfstring` | `0x12b60` | `0x12da0` | **`+0x240`** |
| `__TEXT.__swift5_typeref` | `0x57b6` | `0x5992` | **`+0x1dc`** |
| `__TEXT.__swift5_fieldmd` | `0x4a38` | `0x4c10` | **`+0x1d8`** |
| `__TEXT.__swift5_capture` | `0x1f68` | `0x2124` | **`+0x1bc`** |
| `__TEXT.__swift5_reflstr` | `0x4789` | `0x4939` | **`+0x1b0`** |
| `__AUTH.__objc_data` | `0xbd0` | `0xd60` | **`+0x190`** |
| `__DATA_CONST.__objc_selrefs` | `0x6680` | `0x6810` | **`+0x190`** |
| `__TEXT.__constg_swiftt` | `0x7910` | `0x7a58` | **`+0x148`** |
| `__DATA_CONST.__const` | `0x67d0` | `0x68a8` | **`+0xd8`** |
| `__TEXT.__swift5_assocty` | `0xa40` | `0xaa0` | **`+0x60`** |
| `__TEXT.__swift_as_cont` | `0x278` | `0x2c8` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0xc7d4` | `0xc818` | **`+0x44`** |
| `__DATA_CONST.__objc_classlist` | `0x7c0` | `0x7e8` | **`+0x28`** |
| `__DATA_CONST.__objc_protolist` | `0x2a0` | `0x2c8` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0xf4` | `0x11c` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x528` | `0x544` | **`+0x1c`** |
| `__TEXT.__swift5_types` | `0x4e4` | `0x500` | **`+0x1c`** |
| `__DATA_CONST.__objc_superrefs` | `0x200` | `0x218` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x348` | `0x35c` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x978` | `0x98c` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x2a90` | `0x2aa0` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0xa570` | `0xa580` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1c20` | `0x1c18` | **`-0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x30` | `0x38` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x128` | `0x130` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xf4` | `0xf8` | **`+0x4`** |

### Other Changes

```diff

-1486.100.5.2.1
+1487.100.6.2.2

-  Functions: 15127
-  Symbols:   2852
-  CStrings:  7670
+  Functions: 15369
+  Symbols:   2860
+  CStrings:  7726
Symbols:
+ _IMCopyIndexableItemDictionaryForRecordWithContactCache
+ _IMDCoreSpotlightDeleteAttachmentGUIDsWithCompletion
+ _IMDNotificationsAdvanceAlertDatesAfterDatabaseSwitch
+ _IMFileTransferGUIDForGenmojiWithContentIdentifierInMessageGUID
+ _OBJC_CLASS_$_IMDCoreRecentsController
+ _OBJC_CLASS_$_IMDIndexingDiagnosticPopulator
+ _OBJC_CLASS_$_IMDPersistentTaskDiagnosticPopulator
+ _OBJC_METACLASS_$_IMDCoreRecentsController
+ _OBJC_METACLASS_$_IMDIndexingDiagnosticPopulator
+ _OBJC_METACLASS_$_IMDPersistentTaskDiagnosticPopulator
+ ___XPCServerIMDNotificationsAdvanceAlertDatesAfterDatabaseSwitch_IPCAction
+ ___syncXPCIMDNotificationsAdvanceAlertDatesAfterDatabaseSwitch_IPCAction
+ _printf
- _IMBalloonPluginIdentifierPhotos
- _IMCopyIndexableItemDictionaryForRecord
- _IMDCoreSpotlightDeleteAttachmentGUIDs
- _OBJC_CLASS_$_IMDCoreSpotlightDonationProgressReportingJob
- _OBJC_METACLASS_$_IMDCoreSpotlightDonationProgressReportingJob
CStrings:
+ "\nAND loser.ck_record_id IS NOT NULL \nAND loser.original_guid IS NOT NULL \nAND EXISTS (\n    SELECT 1 \n    FROM sync_chat_slice w \n    WHERE w.chat = "
+ " \n    AND w.service_name = loser.service_name \n    AND w.filter_action = loser.filter_action \n    AND w.filter_sub_action = loser.filter_sub_action \n    AND w.original_guid = loser.original_guid\n)"
+ "      ==> retiring redundant loser slice ck record %s under guid %s — winning chat %ld already holds this tuple (rdar://181627513)"
+ " AND cmj.chat_id IN "
+ " AND m.date <=  ? "
+ " AND m.date >=  ? "
+ " AND m.date BETWEEN  ?  AND  ? "
+ "(com_apple_mobilesms_partIndex = 9223372036854775807) && !(com_apple_mobilesms_isInlineGlyph = 1) && FieldMatch(_kMDItemDomainIdentifier, \"attachmentDomain\")"
+ ".plist"
+ "Asked to vacuum but no integration supports it, no-op"
+ "DELETE FROM sync_chat_slice WHERE rowid =  ? "
+ "Deriving attachment index because attachment GUID in item dictionary is in legacy format or is for another message. attachmentGUID: %@ message GUID: %@"
+ "Deriving inline emoji GUID because attachment GUID in item dictionary is in legacy format. attachmentGUID: %@"
+ "DiagnosticExtension"
+ "Failed to encode descriptors for adaptive image glyph with attachment GUID %@ error %@"
+ "Failed to fetch Spotlight client state with error %@"
+ "Failed to generate syndication identifier for attachment GUID %@, can't index this attachment"
+ "Failed to report updated donation progress to Spotlight with error %@"
+ "Failed to resolve syndication identifiers for deletion: %@"
+ "Found invalid attachment in Spotlight with message GUID %s and Spotlight identifier %s"
+ "Found no items to vacuum, no more work to do"
+ "Got Spotlight client state back from IMDPersistence %@"
+ "Got task reports back from IMDPersistence"
+ "IMCSPreviousClientStateData_decodeError"
+ "IMCSPreviousClientStateData_decoded"
+ "IMDPersistentTaskDump-%ld.plist"
+ "INSERT INTO sync_deleted_chats (guid, recordID, timestamp)\nVALUES ( ? ,  ? , 0)"
+ "No Spotlight client state fetched, but no error"
+ "No vacuum requirements, nothing to do"
+ "PTaskDump.aar"
+ "SELECT EXISTS(\n    SELECT 1 FROM message\n    WHERE message.schedule_type = 2\n    AND message.item_type = 0\n    AND (message.schedule_state = 1 OR message.schedule_state = 2)\n    AND (message.error = 0 OR message.error IS NULL)\n    AND EXISTS (\n        SELECT 1 FROM chat_message_join\n        WHERE chat_message_join.message_id = message.ROWID\n        AND chat_message_join.chat_id = (SELECT ROWID FROM chat WHERE guid = ?)\n    )\n)"
+ "SELECT EXISTS(\n    SELECT 1 FROM message\n    WHERE message.schedule_type = 2\n    AND message.item_type = 0\n    AND (message.schedule_state = 1 OR message.schedule_state = 2)\n    AND (message.error = 0 OR message.error IS NULL)\n    AND EXISTS (\n        SELECT 1 FROM chat_part_message_join cpmj\n        INNER JOIN chat_part cp ON cp.rowid = cpmj.chat_part_id\n        INNER JOIN chat c ON c.ROWID = cp.chat_id\n        WHERE cpmj.message_id = message.ROWID\n        AND c.guid = ?\n    )\n)"
+ "SELECT EXISTS(\n    SELECT 1 FROM message\n    WHERE message.schedule_type = 2\n    AND message.item_type = 0\n    AND (message.schedule_state = 1 OR message.schedule_state = 2)\n    AND EXISTS (\n        SELECT 1 FROM chat_message_join\n        WHERE chat_message_join.message_id = message.ROWID\n        AND chat_message_join.chat_id = (SELECT ROWID FROM chat WHERE guid = ?)\n    )\n)"
+ "SELECT EXISTS(\n    SELECT 1 FROM message\n    WHERE message.schedule_type = 2\n    AND message.item_type = 0\n    AND (message.schedule_state = 1 OR message.schedule_state = 2)\n    AND EXISTS (\n        SELECT 1 FROM chat_part_message_join cpmj\n        INNER JOIN chat_part cp ON cp.rowid = cpmj.chat_part_id\n        INNER JOIN chat c ON c.ROWID = cp.chat_id\n        WHERE cpmj.message_id = message.ROWID\n        AND c.guid = ?\n    )\n)"
+ "SELECT a.guid, a.emoji_image_content_identifier, m.guid, m.attributedBody\nFROM attachment a\nINNER JOIN message_attachment_join maj ON maj.attachment_id = a.ROWID\nINNER JOIN message m ON m.ROWID = maj.message_id\nWHERE "
+ "SELECT loser.rowid, loser.original_guid, loser.ck_record_id \nFROM sync_chat_slice loser \nWHERE "
+ "SELECT m.ROWID, m.guid, m.attributedBody, m.balloon_bundle_id, m.message_summary_info, m.is_from_me, coalesce(h.id, h.uncanonicalized_id), m.associated_message_type\nFROM chat_message_join cmj\n    INNER JOIN message m ON m.ROWID = cmj.message_id\n    INNER JOIN chat c ON c.ROWID = cmj.chat_id\n    LEFT JOIN handle h ON m.handle_id = h.rowid\nWHERE\n    cmj.message_id BETWEEN  ?  AND  ? \n    AND m.item_type = 0\n    AND m.group_action_type = 0\n    AND (\n        m.associated_message_type = 0\n        OR m.associated_message_type IN ( ? ,  ? )\n        OR m.associated_message_type BETWEEN  ?  AND  ? \n    )\n    AND c.is_blackholed = 0\n    AND COALESCE(c.is_filtered, 0) !=  ? "
+ "SELECT m.guid\nFROM attachment a\nINNER JOIN message_attachment_join maj ON maj.attachment_id = a.ROWID\nINNER JOIN message m ON m.ROWID = maj.message_id\nWHERE "
+ "SELECT maj.message_id, a.ROWID, a.guid, a.emoji_image_content_identifier\nFROM message_attachment_join maj\nINNER JOIN attachment a ON maj.attachment_id = a.ROWID\nWHERE maj.message_id BETWEEN  ?  AND  ? "
+ "SELECT rowID, guid, preview_generation_state, uti, is_commsafety_sensitive, hide_attachment, transfer_name, preflight_info, transfer_state FROM attachment WHERE "
+ "Scheduling full re-donation of message %s due to missing message part GUID %s"
+ "Scheduling full re-donation of message %s due to missing root item %s"
+ "Scheduling full re-donation of message %s due to missing syndication identifier %s / attachment GUID %s"
+ "UPDATE OR IGNORE sync_chat_slice\nSET filter_action =  ? , filter_sub_action =  ? \nWHERE chat =  ?  AND filter_action = 0 AND filter_sub_action = 0"
+ "Unexpectedly missing pre-cached stable chat GUID for chat GUID %@, indexing will fail for message %@"
+ "Vacuum query found %ld invalid attachment item(s), deleting"
+ "Vacuumed items, more work to do"
+ "Vacuuming complete!"
+ "Vacuuming interrupted by task cancellation"
+ "[txn-%@] Batch is too big (%ld items), rolling excess over to next batch"
+ "_"
+ "a.guid"
+ "advanceAlertDatesAfterDatabaseSwitch: DB has no messages, skipping"
+ "advanceAlertDatesAfterDatabaseSwitch: anchoring both cursors to %lld"
+ "aig:%@/%@"
+ "asdf %p"
+ "com.apple.IMCoreSpotlight.IMDKV.plist"
+ "com.apple.IMDPTaskReport.plist"
+ "com.apple.SpotlightClientState.plist"
+ "encountered error while vacuuming invalid items: %@"
+ "isAdaptiveImageGlyph"
+ "knownSender"
+ "loser.chat"
+ "message(date) where syndication_ranges IS NOT NULL AND (synced_syndication_ranges IS NULL OR syndication_ranges != synced_syndication_ranges) AND (service = 'iMessage' OR service = 'SMS')"
+ "message_idx_pending_syndication_sync"
+ "reports"
+ "tasks"
+ "v16@?0@?<v@?>8"
+ "vr"
- " FROM chat_message_join cmj INNER JOIN message m ON m.ROWID = cmj.message_id INNER JOIN chat c ON c.ROWID = cmj.chat_id LEFT JOIN handle h ON m.handle_id = h.rowid WHERE "
- "COALESCE(c.is_filtered, 0) !=  ? "
- "Deriving attachment index because attachment GUID in item dictionary is in legacy format. attachmentGUID: %@"
- "Failed to delete %lu transfers from Spotlight: %@"
- "Failed to report updated donation progress to Spotlight"
- "SELECT guid, preview_generation_state, uti, is_commsafety_sensitive, hide_attachment, transfer_name, preflight_info, transfer_state FROM attachment WHERE "
- "SELECT m.ROWID, m.guid, m.attributedBody, m.balloon_bundle_id, m.message_summary_info, m.is_from_me, coalesce(h.id, h.uncanonicalized_id), m.associated_message_type"
- "UPDATE sync_chat_slice\nSET filter_action =  ? , filter_sub_action =  ? \nWHERE chat =  ? "
- "[txn-%@] Excessive amount of deferred searchable item indexing, refusing to go deeper, indexing %@ together in one remaining batch"
- "c.is_blackholed = 0"
- "cmj.message_id BETWEEN  ?  AND  ? "
- "m.date BETWEEN  ?  AND  ? "
- "m.item_type = 0 AND m.group_action_type = 0 AND (m.associated_message_type = 0 OR m.associated_message_type IN ( ? ,  ? ) OR m.associated_message_type BETWEEN  ?  AND  ? )"
```
