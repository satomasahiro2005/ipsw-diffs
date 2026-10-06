## Message

> `/System/Library/PrivateFrameworks/Message.framework/Message`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb00d64` | `0xb02e8c` | **`+0x2128`** |
| `__TEXT.__eh_frame` | `0x18954` | `0x18a74` | **`+0x120`** |
| `__DATA.__bss` | `0x53950` | `0x53a50` | **`+0x100`** |
| `__TEXT.__gcc_except_tab` | `0x3701c` | `0x370d4` | **`+0xb8`** |
| `__TEXT.__const` | `0x6b7e8` | `0x6b858` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x1ebe8` | `0x1ec58` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x18700` | `0x18740` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x10d0c` | `0x10d48` | **`+0x3c`** |
| `__DATA.__data` | `0xe948` | `0xe978` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0xaccb8` | `0xacce0` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0x27eb0` | `0x27ed0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x314c6` | `0x314d6` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x144ac` | `0x144bc` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xf370` | `0xf380` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xb8c0` | `0xb8c8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x2a38` | `0x2a40` | **`+0x8`** |

### Other Changes

```diff

-3901.200.34.0.0
+3901.200.41.0.0

-  Functions: 48698
-  Symbols:   21364
-  CStrings:  8545
+  Functions: 48719
+  Symbols:   21368
+  CStrings:  8548
Symbols:
+ +[MFMessageCriterion criterionForEmailAddresses:]
+ _associated conformance 15IMAP2Connection6EnableVSHAASQ
+ _symbolic _____7mailbox______7messaget 16IMAP2Persistence15OpaqueMailboxIDV AA0C26PersistedMessageIdentifierV
+ _symbolic ______Say_____G_____t 15IMAP2Connection6EnableV 12NIOIMAPCore210CapabilityV 0A8Protocol8ServerIDV
CStrings:
+ "EXISTS (  SELECT global_message_id     FROM message_attachments LEFT OUTER     JOIN searchable_attachments ON message_attachments.rowid = searchable_attachments.attachment_id     WHERE message_attachments.global_message_id = messages.global_message_id       AND searchable_attachments.attachment_id IS NULL       AND message_attachments.attachment IS NOT NULL )"
+ "[%.*hhx-%{public}s] Did enable capabilities: %{public}s"
+ "[%.*hhx-%{public}s] Received post-auth capabilities from server: %{public}s"
+ "enablingCapabilities"
+ "messages.searchable_message IS NULL"
+ "searchable_messages.message_body_indexed = 0"
+ "searchable_messages.transaction_id IN (%@, %@)"
+ "unauthenticated(enablingCapabilities)"
- "(  messages.searchable_message IS NULL OR   messages.global_message_id IN   (SELECT global_message_id    FROM message_attachments LEFT OUTER    JOIN searchable_attachments       ON ( message_attachments.rowid = searchable_attachments.attachment_id )    WHERE searchable_attachments.attachment_id IS NULL           AND message_attachments.attachment IS NOT NULL   ))"
- "(messages.searchable_message IS NULL OR   searchable_messages.message_body_indexed = 0 OR   searchable_messages.transaction_id IN (%@, %@))"
- "[%.*hhx-%{public}s] Did enable UIDONLY"
- "[%.*hhx-%{public}s] Received capabilities from server"
- "unauthenticated(enablingUIDOnly)"
```
