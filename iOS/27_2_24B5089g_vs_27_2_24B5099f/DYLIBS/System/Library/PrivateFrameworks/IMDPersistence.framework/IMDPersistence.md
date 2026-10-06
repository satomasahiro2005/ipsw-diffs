## IMDPersistence

> `/System/Library/PrivateFrameworks/IMDPersistence.framework/IMDPersistence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x300800` | `0x3022e4` | **`+0x1ae4`** |
| `__TEXT.__cstring` | `0x5db34` | `0x5eba4` | **`+0x1070`** |
| `__AUTH_CONST.__objc_const` | `0x13b20` | `0x13d80` | **`+0x260`** |
| `__TEXT.__oslogstring` | `0x3c3c4` | `0x3c244` | **`-0x180`** |
| `__TEXT.__gcc_except_tab` | `0xc764` | `0xc5ec` | **`-0x178`** |
| `__DATA.__data` | `0x3a70` | `0x3bb0` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0xa49c` | `0xa584` | **`+0xe8`** |
| `__AUTH_CONST.__const` | `0xe268` | `0xe330` | **`+0xc8`** |
| `__TEXT.__eh_frame` | `0x9d0c` | `0x9dc4` | **`+0xb8`** |
| `__AUTH.__objc_data` | `0xfc0` | `0x1060` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0xa330` | `0xa3a8` | **`+0x78`** |
| `__DATA_DIRTY.__data` | `0x6500` | `0x6560` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x1ff4` | `0x2044` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x594c` | `0x5988` | **`+0x3c`** |
| `__DATA_CONST.__objc_selrefs` | `0x6b70` | `0x6ba8` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x5256` | `0x5278` | **`+0x22`** |
| `__DATA_CONST.__const` | `0x6528` | `0x6548` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x29f8` | `0x2a10` | **`+0x18`** |
| `__DATA.__bss` | `0x64e8` | `0x64f8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1c30` | `0x1c40` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x6e8` | `0x6f8` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x308` | `0x318` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x398` | `0x3a8` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x160` | `0x168` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x568` | `0x56c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x180` | `0x184` | **`+0x4`** |

### Other Changes

```diff

-1491.200.73.0.0
+1491.200.95.0.0

-  Functions: 13788
-  Symbols:   2852
-  CStrings:  7546
+  Functions: 13842
+  Symbols:   2859
+  CStrings:  7543
Symbols:
+ _IMAttachmentPreflightPreviewFileURL
+ _IMCoreSpotlightIndexBehaviorFromReason
+ _IMSharedHelperCurrentRegionForcesFilterUnknownSenders
+ _OBJC_CLASS_$_IMDCoreSpotlightIndexerProvider
+ _OBJC_CLASS_$_IMDCoreSpotlightSearchableItemGeneratorDependencyProvider
+ _OBJC_METACLASS_$_IMDCoreSpotlightIndexerProvider
+ _OBJC_METACLASS_$_IMDCoreSpotlightSearchableItemGeneratorDependencyProvider
CStrings:
+ ")) AND\n        mU.is_finished == 1 AND\n        mU.is_from_me == 0 AND\n        mU.item_type == 0 AND\n        mU.is_system_message == 0\n)"
+ "EXISTS (\n    SELECT 1 FROM chat_message_join cmjU\n    INNER JOIN message mU ON mU.rowid = cmjU.message_id\n    WHERE cmjU.chat_id = c.rowid AND\n        mU.is_read == 0 AND\n        NOT (mU.ROWID in (SELECT message_id FROM "
+ "EXISTS (\n    SELECT 1 FROM chat_part cpU\n    INNER JOIN chat_part_message_join cmjU ON cpU.rowid = cmjU.chat_part_id\n    INNER JOIN message mU ON mU.rowid = cmjU.message_id\n    WHERE cpU.chat_id = c.rowid AND\n        mU.is_read == 0 AND\n        NOT (mU.ROWID in (SELECT message_id FROM "
+ "Filename was null (%@) for file transfer %@ -- did not generate attachment preview"
+ "Final preview unavailable, falling back to preview-stage preview for transfer %{private}@"
+ "INSERT OR IGNORE INTO chat_message_join (chat_id, message_id, message_date, filter_action, filter_sub_action) SELECT ?, ?, ?, ?, ? WHERE NOT EXISTS (SELECT 1 FROM chat_recoverable_message_join WHERE chat_id = ? AND message_id = ?);"
+ "INSERT OR IGNORE INTO chat_part_message_join (chat_part_id, message_id, message_date, filter_action, filter_sub_action)\nSELECT ?, ?, ?, ?, ?\nWHERE NOT EXISTS (SELECT 1 FROM chat_part_recoverable_message_join WHERE chat_part_id = ? AND message_id = ?);"
+ "Not attaching a preview for transfer %@ to the notification (sensitive %{BOOL}d, adaptive image glyph %{BOOL}d, rejected %{BOOL}d); with all three false, no preview was on disk"
+ "PersistentTaskBatchTimeoutSeconds"
+ "SELECT a.ROWID, a.guid, a.created_date, a.start_date, a.filename, a.uti, a.mime_type, a.transfer_state, a.is_outgoing, a.user_info, a.transfer_name, a.total_bytes, a.is_sticker, a.sticker_user_info, a.attribution_info, a.hide_attachment, a.ck_sync_state, a.ck_server_change_token_blob, a.ck_record_id, a.original_guid, a.is_commsafety_sensitive, a.emoji_image_content_identifier, a.emoji_image_short_description, a.preview_generation_state, a.preflight_info, a.sensitivity_analysis, a.fields_needing_sync  FROM attachment a INNER JOIN message_attachment_join ma ON   a.ROWID = ma.attachment_id INNER JOIN chat_message_join cm ON   ma.message_id = cm.message_id INNER JOIN message m ON   ma.message_id = m.ROWID WHERE   m.cache_has_attachments   AND m.expire_state != %d   AND cm.chat_id IN (%@)   AND a.hide_attachment == 0   AND a.ck_sync_state == 1   AND a.transfer_state == 0 ORDER BY m.date DESC limit %d"
+ "SELECT a.ROWID, a.guid, a.created_date, a.start_date, a.filename, a.uti, a.mime_type, a.transfer_state, a.is_outgoing, a.user_info, a.transfer_name, a.total_bytes, a.is_sticker, a.sticker_user_info, a.attribution_info, a.hide_attachment, a.ck_sync_state, a.ck_server_change_token_blob, a.ck_record_id, a.original_guid, a.is_commsafety_sensitive, a.emoji_image_content_identifier, a.emoji_image_short_description, a.preview_generation_state, a.preflight_info, a.sensitivity_analysis, a.fields_needing_sync  FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND (m.balloon_bundle_id IS NULL OR m.balloon_bundle_id != 'com.apple.messages.chatbot') AND a.ROWID > ? ORDER BY a.ROWID LIMIT ? "
+ "SELECT a.ROWID, a.guid, a.created_date, a.start_date, a.filename, a.uti, a.mime_type, a.transfer_state, a.is_outgoing, a.user_info, a.transfer_name, a.total_bytes, a.is_sticker, a.sticker_user_info, a.attribution_info, a.hide_attachment, a.ck_sync_state, a.ck_server_change_token_blob, a.ck_record_id, a.original_guid, a.is_commsafety_sensitive, a.emoji_image_content_identifier, a.emoji_image_short_description, a.preview_generation_state, a.preflight_info, a.sensitivity_analysis, a.fields_needing_sync  FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND (m.balloon_bundle_id IS NULL OR m.balloon_bundle_id != 'com.apple.messages.chatbot') ORDER BY a.ROWID LIMIT ? "
+ "SELECT a.ROWID, a.guid, a.created_date, a.start_date, a.filename, a.uti, a.mime_type, a.transfer_state, a.is_outgoing, a.user_info, a.transfer_name, a.total_bytes, a.is_sticker, a.sticker_user_info, a.attribution_info, a.hide_attachment, a.ck_sync_state, a.ck_server_change_token_blob, a.ck_record_id, a.original_guid, a.is_commsafety_sensitive, a.emoji_image_content_identifier, a.emoji_image_short_description, a.preview_generation_state, a.preflight_info, a.sensitivity_analysis, a.fields_needing_sync  FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND m.balloon_bundle_id == 'com.apple.messages.chatbot' AND a.ROWID > ? ORDER BY a.ROWID LIMIT ? "
+ "SELECT a.ROWID, a.guid, a.created_date, a.start_date, a.filename, a.uti, a.mime_type, a.transfer_state, a.is_outgoing, a.user_info, a.transfer_name, a.total_bytes, a.is_sticker, a.sticker_user_info, a.attribution_info, a.hide_attachment, a.ck_sync_state, a.ck_server_change_token_blob, a.ck_record_id, a.original_guid, a.is_commsafety_sensitive, a.emoji_image_content_identifier, a.emoji_image_short_description, a.preview_generation_state, a.preflight_info, a.sensitivity_analysis, a.fields_needing_sync  FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND m.balloon_bundle_id == 'com.apple.messages.chatbot' ORDER BY a.ROWID LIMIT ? "
+ "SELECT a.ROWID, a.guid, a.created_date, a.start_date, a.filename, a.uti, a.mime_type, a.transfer_state, a.is_outgoing, a.user_info, a.transfer_name, a.total_bytes, a.is_sticker, a.sticker_user_info, a.attribution_info, a.hide_attachment, a.ck_sync_state, a.ck_server_change_token_blob, a.ck_record_id, a.original_guid, a.is_commsafety_sensitive, a.emoji_image_content_identifier, a.emoji_image_short_description, a.preview_generation_state, a.preflight_info, a.sensitivity_analysis, a.fields_needing_sync  FROM attachment a WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 AND a.ROWID > ? ORDER BY a.ROWID LIMIT ? "
+ "SELECT a.ROWID, a.guid, a.created_date, a.start_date, a.filename, a.uti, a.mime_type, a.transfer_state, a.is_outgoing, a.user_info, a.transfer_name, a.total_bytes, a.is_sticker, a.sticker_user_info, a.attribution_info, a.hide_attachment, a.ck_sync_state, a.ck_server_change_token_blob, a.ck_record_id, a.original_guid, a.is_commsafety_sensitive, a.emoji_image_content_identifier, a.emoji_image_short_description, a.preview_generation_state, a.preflight_info, a.sensitivity_analysis, a.fields_needing_sync  FROM attachment a WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 ORDER BY a.ROWID LIMIT ? "
- ")) AND\nm.is_finished == 1 AND\nm.is_from_me == 0 AND\nm.item_type == 0 AND\nm.is_system_message == 0"
- "Bailing early from _IMDCoreSpotlightNicknameForAddress: Shared Name and Photo is not enabled"
- "Bailing early from _IMDKVStoreForHandledNicknames: Shared Name and Photo is not enabled"
- "Bailing early from _IMDKVStoreForPendingNicknames: Shared Name and Photo is not enabled"
- "Bailing early from _IMDNicknameInfoForAddress: Shared Name and Photo is not enabled"
- "Bailing early from _IMNicknameInfoForKVStore: Shared Name and Photo is not enabled"
- "Bailing early from _nicknameDisplayNameForID: Shared Name and Photo is not enabled"
- "Filename was null (%@) or transfer state was not finished (%@) for file transfer %@ -- did not generate attachment preview"
- "INSERT OR IGNORE INTO chat_message_join (chat_id, message_id, message_date, filter_action, filter_sub_action) VALUES (?, ?, ?, ?, ?);"
- "INSERT OR IGNORE INTO chat_part_message_join (chat_part_id, message_id, message_date, filter_action, filter_sub_action)\nVALUES (?, ?, ?, ?, ?);"
- "SELECT * FROM attachment a INNER JOIN message_attachment_join ma ON   a.ROWID = ma.attachment_id INNER JOIN chat_message_join cm ON   ma.message_id = cm.message_id INNER JOIN message m ON   ma.message_id = m.ROWID WHERE   m.cache_has_attachments   AND m.expire_state != %d   AND cm.chat_id IN (%@)   AND a.hide_attachment == 0   AND a.ck_sync_state == 1   AND a.transfer_state == 0 ORDER BY m.date DESC limit %d"
- "SELECT * FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND (m.balloon_bundle_id IS NULL OR m.balloon_bundle_id != 'com.apple.messages.chatbot') AND a.ROWID > ? ORDER BY a.ROWID LIMIT ? "
- "SELECT * FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND (m.balloon_bundle_id IS NULL OR m.balloon_bundle_id != 'com.apple.messages.chatbot') ORDER BY a.ROWID LIMIT ? "
- "SELECT * FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND m.balloon_bundle_id == 'com.apple.messages.chatbot' AND a.ROWID > ? ORDER BY a.ROWID LIMIT ? "
- "SELECT * FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND m.balloon_bundle_id == 'com.apple.messages.chatbot' ORDER BY a.ROWID LIMIT ? "
- "SELECT * FROM attachment a WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 AND a.ROWID > ? ORDER BY a.ROWID LIMIT ? "
- "SELECT * FROM attachment a WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 ORDER BY a.ROWID LIMIT ? "
- "We didn't generate a previewFileURL for transfer %@ to generate a notification preview"
- "m.is_read == 0 AND\nNOT (m.ROWID in (SELECT message_id FROM "
```
