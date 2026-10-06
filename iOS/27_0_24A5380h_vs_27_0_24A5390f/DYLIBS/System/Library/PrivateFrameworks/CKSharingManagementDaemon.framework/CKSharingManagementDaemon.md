## CKSharingManagementDaemon

> `/System/Library/PrivateFrameworks/CKSharingManagementDaemon.framework/CKSharingManagementDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8bee0` | `0x8f174` | **`+0x3294`** |
| `__TEXT.__eh_frame` | `0x7778` | `0x7ae4` | **`+0x36c`** |
| `__TEXT.__oslogstring` | `0x2d61` | `0x2e51` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x28d0` | `0x2990` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x1d10` | `0x1dbe` | **`+0xae`** |
| `__DATA.__data` | `0x1700` | `0x1658` | **`-0xa8`** |
| `__AUTH_CONST.__auth_got` | `0x1030` | `0x10a0` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x3ac` | `0x364` | **`-0x48`** |
| `__AUTH_CONST.__objc_const` | `0xd78` | `0xd38` | **`-0x40`** |
| `__TEXT.__swift5_reflstr` | `0x1225` | `0x1265` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x3590` | `0x35c0` | **`+0x30`** |
| `__TEXT.__cstring` | `0xaf6` | `0xb26` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x548` | `0x578` | **`+0x30`** |
| `__DATA_CONST.__objc_protolist` | `0x80` | `0x60` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x5ac` | `0x5c4` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x17d4` | `0x17ec` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x2cc` | `0x2e4` | **`+0x18`** |
| `__AUTH.__data` | `0x1318` | `0x1328` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x40` | `0x30` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x588` | `0x598` | **`+0x10`** |
| `__TEXT.__const` | `0x61e0` | `0x61f0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x1858` | `0x1868` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x22c` | `0x238` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x148` | `0x150` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x6c0` | `0x6c8` | **`+0x8`** |

### Other Changes

```diff

-22.1.0.0.0
+23.0.0.0.0
+  - /System/Library/Frameworks/Accounts.framework/Accounts

+  - /usr/lib/swift/libswiftCoreAudio.dylib

-  Functions: 2616
-  Symbols:   945
-  CStrings:  241
+  Functions: 2654
+  Symbols:   942
+  CStrings:  242
Symbols:
+ _IDSCopyBestGuessIDForID
+ _IDSSendMessageOptionFromIDKey
+ _OBJC_CLASS_$_ACAccountStore
+ ___swift__destructor
+ ___swift_closure_destructor.17Tm
+ ___swift_memcpy18_8
+ __swift_FORCE_LOAD_$_swiftCoreAudio
+ __swift_FORCE_LOAD_$_swiftCoreAudio_$_CKSharingManagementDaemon
+ _symbolic SDySo24CKUserIdentityLookupInfoCSo18CKShareParticipantCG
+ _symbolic _____ 18AAAFoundationSwift13OSTransactionC
+ _symbolic _____ySo24CKUserIdentityLookupInfoCG s11_SetStorageC
+ _symbolic _____ySo24CKUserIdentityLookupInfoCSo18CKShareParticipantCG s18_DictionaryStorageC
+ _symbolic _____ySo24CKUserIdentityLookupInfoCSo18CKShareParticipantC_G SD5IndexV
+ _symbolic _____yyXlG s23_ContiguousArrayStorageC
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_IDSDestinationProtocol
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCopying
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_IDSDestinationProtocol
- __OBJC_$_PROTOCOL_METHOD_TYPES_IDSDestinationProtocol
- __OBJC_$_PROTOCOL_METHOD_TYPES_NSCopying
- __OBJC_$_PROTOCOL_REFS_IDSDestinationProtocol
- __OBJC_LABEL_PROTOCOL_$_IDSDestinationProtocol
- __OBJC_LABEL_PROTOCOL_$_NSCopying
- __OBJC_PROTOCOL_$_IDSDestinationProtocol
- __OBJC_PROTOCOL_$_NSCopying
- ___swift_allocate_boxed_opaque_existential_2
- ___swift_closure_destructor.16Tm
- ___swift_project_boxed_opaque_existential_1Tm
- _flat unique So22IDSDestinationProtocol_p
- _symbolic _____Sg_ABt 10Foundation3URLV
- _symbolic ______SHpSg 25CKSharingManagementDaemon28IDSPendingInvitationProtocolP
- _symbolic ______p So22IDSDestinationProtocolP
CStrings:
+ "CKShareManagerService.incomingInvitation"
+ "Sending share invite: %{private}s to: %{private}s with options: %s"
+ "[CloudKitContainerFactory] Failed to configure client container %s with operation group %s: %@"
+ "[CloudKitContainerFactory] Failed to configure metadata container with operation group %s: %@"
+ "[RepairShareOperation] Detected pending members after sync, will schedule retry %s"
+ "[StopShareOperation] Failed to cancel repair retry: %@"
+ "[StopShareOperation] Failed to cancel setup retry: %@"
+ "[SyncMembersOperation] Current user no longer in audiences, deleting share record for self-removal %s"
+ "[SyncMembersOperation] Requesting new invitation token for pending Manatee participant %s"
+ "[resolveAudienceParticipants] Fetched %ld participants from server: %{private}s %s"
+ "[resolveAudienceParticipants] Resolving %ld members (%ld cached, %ld to fetch) cached: %{private}s toFetch: %{private}s %s"
+ "sendInvitation(toDestination:expirationDate:context:options:)"
- "Decoded pending invitation: %{private}s"
- "Error decoding pending invitation: %@"
- "Sending share invite: %{private}s to: %{private}s"
- "[StopShareOperation] Failed to cancel retry: %@"
- "[SyncMembersOperation] Fetching participants for %ld members %s"
- "[SyncMembersOperation] Requesting new invitation token %s"
- "[SyncMembersOperation] Skipping IDS invitation existingInvitation: %{private}s %s"
- "[SyncMembersOperation] existingInvitation: %{private}s expirationDate: %s. Do not request new invitation token %s"
- "[SyncMembersOperation] olderInvitationExists: %{bool}d olderInvitationExpirationDate: %s %s"
- "pending invitation: %{private}s"
- "sendInvitation(toDestination:expirationDate:context:)"
```
