## CKSharingManagementDaemon

> `/System/Library/PrivateFrameworks/CKSharingManagementDaemon.framework/CKSharingManagementDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9812c` | `0x9a3cc` | **`+0x22a0`** |
| `__TEXT.__eh_frame` | `0x79b4` | `0x7cd0` | **`+0x31c`** |
| `__TEXT.__oslogstring` | `0x2ae1` | `0x2bc1` | **`+0xe0`** |
| `__TEXT.__const` | `0x6030` | `0x60f0` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x2868` | `0x2920` | **`+0xb8`** |
| `__TEXT.__swift5_reflstr` | `0x10cf` | `0x1175` | **`+0xa6`** |
| `__DATA.__bss` | `0x8880` | `0x8900` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x16b8` | `0x1734` | **`+0x7c`** |
| `__AUTH_CONST.__const` | `0x4988` | `0x49c8` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0xbbc` | `0xb80` | **`-0x3c`** |
| `__AUTH.__data` | `0x1200` | `0x1230` | **`+0x30`** |
| `__TEXT.__cstring` | `0xaf6` | `0xb26` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x1b20` | `0x1b44` | **`+0x24`** |
| `__DATA.__data` | `0x16f0` | `0x1710` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x1720` | `0x173c` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0xfe8` | `0x1000` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x2e8` | `0x300` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x698` | `0x6a8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x598` | `0x588` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x4a4` | `0x4a8` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x1c4` | `0x1c8` | **`+0x4`** |

### Other Changes

```diff

-18.0.0.0.0
+20.0.0.0.0

-  Functions: 2793
-  Symbols:   933
-  CStrings:  237
+  Functions: 2837
+  Symbols:   939
+  CStrings:  240
Symbols:
+ _CKRecordNameZoneWideShare
+ ___swift_memcpy24_8
+ ___swift_memcpy265_8
+ _associated conformance 25CKSharingManagementDaemon27IDSInvitationManagerWrapperVAA16InvitationSenderAA07PendingG0AaDP_AA010IDSPendingG8Protocol
+ _associated conformance 25CKSharingManagementDaemon27IDSInvitationManagerWrapperVAA16InvitationSenderAA07PendingG0AaDP_SH
+ _swift_retain_x1
+ _symbolic ShySo17IDSSentInvitationCG
+ _symbolic ShySo21IDSReceivedInvitationCG
+ _symbolic So21IDSReceivedInvitationCSg
+ _symbolic So7CKShareCSg
+ _symbolic _____ 25CKSharingManagementDaemon27IDSInvitationManagerWrapperV
+ _symbolic _____ySSG 8Dispatch0A11SpecificKeyC
+ _type_layout_string 25CKSharingManagementDaemon27IDSInvitationManagerWrapperV
- _OBJC_CLASS_$_CKFetchShareParticipantsOperation
- ___swift__destructor
- ___swift_memcpy217_8
- _objc_retain_x1
- _symbolic SaySo18CKShareParticipantCG
- _symbolic SaySo18CKShareParticipantCGz_Xx
- _symbolic ScCySaySo18CKShareParticipantCG______pG s5ErrorP
CStrings:
+ "[AudienceChangeOperation] Complete: updated %ld shares of %ld matched descriptors, scope %s"
+ "[CKShareManagerService] Setup failed %s"
+ "[RepairShareOperation] Descriptor sync returned nil share (owner not in all audiences) %s"
+ "[SyncMembersOperation] Adding participant: %{private}@ %s"
+ "[SyncMembersOperation] Completed with %ld invitation attempts and %ld skipped participants %s"
+ "[SyncMembersOperation] Skipping owner: %{private}@ %s"
+ "[SyncMembersOperation] ⚠️ Skipping adding participant without lookupInfo: %{private}@ - will retry. %s"
+ "[SyncMembersOperation] ⚠️ Skipping adding participant without publicKey: %{private}@ - will retry. %s"
+ "[UpdateSharesOperation] Audience Update complete: %ld shares updated of %ld matched descriptors"
+ "[UpdateSharesOperation] Scope %s audience update complete: %ld shares updated of %ld matched descriptors"
+ "[fetchShareParticipants] Failed to get participant for %{private}@: %@ %s"
+ "[fetchShareParticipants] failed: %@ %s"
+ "privateDatabaseDescriptorCount"
+ "sharedDatabaseDescriptorCount"
- "[AudienceChangeOperation] Complete: updated %ld shares, scope %s"
- "[CKFetchShareParticipantsOperation] Failed to get participant for %{private}@: %@ %s"
- "[CKFetchShareParticipantsOperation] failed: %@ %s"
- "[SetupShareOperation] Adding participant: %{private}@ %s"
- "[SetupShareOperation] Skipping owner: %{private}@ %s"
- "[SyncMembersOperation] databaseScope is %s. This is unexpected! %s"
- "[SyncMembersOperation] ⚠️ Skipping adding participant without lookupInfo: %{private}@ %s"
- "[SyncMembersOperation] ⚠️ Skipping adding participant without publicKey: %{private}@ %s"
- "[UpdateSharesOperation] Audience Update complete: %ld shares updated"
- "[UpdateSharesOperation] Scope %s audience update complete: %ld shares updated"
- "fetchShareParticipants(for:)"
```
