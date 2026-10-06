## IMDaemonCore

> `/System/Library/PrivateFrameworks/IMDaemonCore.framework/IMDaemonCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b7e58` | `0x3ab9d0` | **`-0xc488`** |
| `__TEXT.__oslogstring` | `0x54f37` | `0x54727` | **`-0x810`** |
| `__TEXT.__cstring` | `0x145ec` | `0x1407c` | **`-0x570`** |
| `__DATA.__bss` | `0x53f0` | `0x5880` | **`+0x490`** |
| `__TEXT.__const` | `0x8238` | `0x8588` | **`+0x350`** |
| `__AUTH_CONST.__objc_const` | `0x23a80` | `0x23798` | **`-0x2e8`** |
| `__TEXT.__objc_methlist` | `0x1b5fc` | `0x1b3e4` | **`-0x218`** |
| `__TEXT.__eh_frame` | `0x9e54` | `0xa054` | **`+0x200`** |
| `__AUTH_CONST.__cfstring` | `0xef20` | `0xee40` | **`-0xe0`** |
| `__AUTH.__data` | `0x6d8` | `0x608` | **`-0xd0`** |
| `__TEXT.__unwind_info` | `0xe138` | `0xe070` | **`-0xc8`** |
| `__TEXT.__constg_swiftt` | `0x2b28` | `0x2bb8` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0xa330` | `0xa3b8` | **`+0x88`** |
| `__TEXT.__gcc_except_tab` | `0x1f840` | `0x1f7bc` | **`-0x84`** |
| `__TEXT.__swift5_typeref` | `0x3d02` | `0x3d78` | **`+0x76`** |
| `__AUTH_CONST.__objc_intobj` | `0xb88` | `0xbe8` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x3810` | `0x37b8` | **`-0x58`** |
| `__DATA.__data` | `0x6688` | `0x66d0` | **`+0x48`** |
| `__TEXT.__swift5_assocty` | `0x7d8` | `0x820` | **`+0x48`** |
| `__AUTH.__objc_data` | `0x30c0` | `0x30f8` | **`+0x38`** |
| `__DATA_DIRTY.__objc_data` | `0x3d68` | `0x3d30` | **`-0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x10ef0` | `0x10ec8` | **`-0x28`** |
| `__TEXT.__swift5_proto` | `0x3dc` | `0x400` | **`+0x24`** |
| `__TEXT.__swift_as_cont` | `0x8ec` | `0x910` | **`+0x24`** |
| `__DATA_CONST.__const` | `0x6d68` | `0x6d88` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x3d8` | `0x3f0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x21c` | `0x230` | **`+0x14`** |
| `__TEXT.__swift5_fieldmd` | `0x1c38` | `0x1c24` | **`-0x14`** |
| `__TEXT.__swift5_reflstr` | `0x18ef` | `0x18df` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x4a0` | `0x4b0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x1ca0` | `0x1c94` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x2f20` | `0x2f18` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xa58` | `0xa50` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x948` | `0x950` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x278` | `0x280` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x12f4` | `0x12f0` | **`-0x4`** |

### Other Changes

```diff

-1487.100.6.2.2
+1491.100.1.2.11

-  Functions: 14592
-  Symbols:   3264
-  CStrings:  8534
+  Functions: 14525
+  Symbols:   3241
+  CStrings:  8488
Symbols:
+ _IMChatPropertyLastUPIVisibilityCheckDate
+ _IMDCoreSpotlightAddChatGUIDs
+ _IMMetricsCollectorEventAskToMessageReceivedByContact
+ _IMMetricsCollectorEventAskToSenderValidationEnded
+ _IMMetricsCollectorEventAskToSenderValidationFamilyPhoneNumberAvailability
+ _IMMetricsCollectorEventAskToSenderValidationStarted
+ _IMNotificationContextMessageIsNewScreenTimeRequestKey
+ _IMNotificationContextRequestIdentifierKey
+ _NSStringFromIMDChatSyncValidityState
+ _OBJC_CLASS_$_IMAskToSenderValidationPipelineComponent
+ _OBJC_CLASS_$_IMCTChatBotUtilities
+ _OBJC_CLASS_$_IMCTRCSUtilitiesManager
+ _OBJC_CLASS_$_IMDPersistenceContactProvider
+ _OBJC_CLASS_$_IMPersistentTaskContentDateDescriptor
+ _OBJC_CLASS_$_STAskClient
+ _OBJC_METACLASS_$_IMAskToSenderValidationPipelineComponent
+ _PHPhotosErrorDomain
+ _dispatch_block_wait
- _IMChatLookupDomainChatPartChatIdentifier
- _IMChatPartPropertyAccountID
- _IMChatPartPropertyAccountLogin
- _IMChatPartPropertyChatIdentifier
- _IMChatPartPropertyDomainIdentifiers
- _IMChatPartPropertyLastAddressedHandle
- _IMChatPartPropertyLastAddressedSIMID
- _IMChatPartPropertyLastMessageDate
- _IMChatPartPropertyLastReadMessageTimestamp
- _IMChatPartPropertyParticipants
- _IMChatPartPropertyUUID
- _IMChatPartsBugSubTypeChatPartsMissingChatIdentifier
- _IMChatPartsBugSubTypeChatsNotMerged
- _IMChatPartsBugSubTypeChatsNotUnMerged
- _IMChatPartsBugSubTypeClearingChatParts
- _IMChatPartsBugSubTypeMultipleChatsWithGroupID
- _IMChatPartsBugSubTypeOverwritingChatIdentifier
- _IMChatPropertyActiveChatPart
- _IMChatPropertyChatParts
- _IMChatPropertyLatestChatPart
- _IMChatPropertyStableGUID
- _IMDChatPartRecordAddHandle
- _IMDChatPartRecordBulkUpdate
- _IMDChatPartRecordCopyCachedLastMessage
- _IMDChatPartRecordCopyChatIdentifier
- _IMDChatPartRecordCopyChatPartForUUID
- _IMDChatPartRecordCopyChatPartLookupRecords
- _IMDChatPartRecordCopyChatPartRecord
- _IMDChatPartRecordCopyHandles
- _IMDChatPartRecordCreate
- _IMDChatPartRecordGetIdentifier
- _IMDChatPartRecordRemoveHandle
- _IMDChatRecordCopyChatParts
- _IMMetricsCollectorEventFamilyValidationEnded
- _IMMetricsCollectorEventFamilyValidationFamilyPhoneNumberAvailability
- _IMMetricsCollectorEventFamilyValidationStarted
- _OBJC_CLASS_$_IMDChatPart
- _OBJC_CLASS_$_IMFamilySenderMessageProcessingPipelineComponent
- _OBJC_METACLASS_$_IMDChatPart
- _OBJC_METACLASS_$_IMFamilySenderMessageProcessingPipelineComponent
- __IMDChatPartRecordBulkCopy
CStrings:
+ "-[IMAskToSenderValidationPipelineComponent _allFamilyMemberHandlesInFamilyCircle:]"
+ "-[IMAskToSenderValidationPipelineComponent _senderCorrelationIdentifier:correlatesWithHandles:completion:]"
+ "<IMAskToSenderValidationPipelineComponent> Started processing"
+ "AskTo message is not from a known sender. Falling back to Family relation validation."
+ "AskTo sender validation was required, but Family relation was not verifiable."
+ "Attempting to respond to Screen Time request through legacy pathway"
+ "Can't respond to ST request because it's not an old Screen Time request and we're missing required metadata"
+ "Chat fetched for writing up has invalid sync state - %@"
+ "ChatToSyncHasInvalidState-%@"
+ "Could not check for known chat containing handle; nil databaseQueryProvider. NSXPC proxy was likely invalidated mid-flight"
+ "DeferredProcessing: File coordination failed with **unrecoverable** photos error: %s, code: %ld"
+ "DeferredProcessing: File coordination failed with photos error: %s, code: %ld"
+ "DeferredProcessing: File coordination failed with unrecoverable error on attempt %ld/%ld. Will NOT retry acquisition."
+ "Error responding to Screen Time request through legacy pathway %@"
+ "Failed to acquire file for transfer %s: %s (unrecoverable: %{bool}d)"
+ "Failed to respond to ST request through legacy pathway, payloadURL == nil"
+ "Failed to respond to ST request through legacy pathway, requestID == nil"
+ "IMAskToSenderValidationPipelineComponent"
+ "IMAskToSenderValidationPipelineComponent.m"
+ "IMDChatSyncValidityInvalidGUIDSuffix"
+ "IMDChatSyncValidityInvalidSyncState"
+ "IMDChatSyncValidityValid"
+ "IMDReplayEnvelopeContext"
+ "IMDReplayEnvelopePayload"
+ "Message %@ will be the first unencrypted send, force failing.\nisFinal: %{BOOL}d\nisRCS: %{BOOL}d\ndidSupportEncryption: %{BOOL}d\nserviceForSendingResult.bestResult.allSupportEncryption): %{BOOL}d\nretryAsUnencryptedRCS: %{BOOL}d"
+ "Message does not require AskTo sender validation."
+ "Message is from a contact. No AskTo sender validation required."
+ "NOT auto-marking message %@ (fromMe %{BOOL}d) as read — sent recently (messageTime %@, serverTime %@, lastReadMessageTime %@); deferring to normal read-receipt flow"
+ "No message GUID exists in the notification context"
+ "No message URL exists in the notification context"
+ "No messageItem for transfer: %@, can't retrieve security scoped url"
+ "No participant handles were found for chat %@"
+ "No responderHandle was found for chat %@"
+ "Repaired isFiltered for %d of %lu chats"
+ "Repairing isFiltered of %@ from %ld to known sender"
+ "SMSReplay: failed to archive replay envelope, storing raw data: %@"
+ "Setting isRCSSendWithoutEncryption on relayDictionary"
+ "Successfully responded to Screen Time request through legacy pathway"
+ "UPI visibility change for chat: %@ at %@"
+ "Unexpected state! Chat %@ has a filter %@ (isFiltered %lld)"
+ "Unexpected state! Chat %@ to sync has %@ for sync, marking with error."
+ "Unexpected state! Chat %@ to sync has sync state IMDChatCloudKitSyncedSinceLastModification"
+ "Unknown IMDChatSyncValidityState (%ld)"
+ "[%{public}s] failed to honor scheduler-initiated expiration: %@"
+ "[%{public}s] honoring scheduler-initiated expiration for abandoned task"
+ "_TLTonePreferencesDidChangeNotification"
+ "calculateServiceForSending for pushMessageGUID %@ and service result %@:\n"
+ "com.apple.messages.tone-library-refresh"
+ "isFiltered inconsistency detected among merged chats. Attempting to repair"
+ "v20@?0@\"NSURL\"8B16"
- "           chatPart: < chatIdentfier: %@ participants: (%@) >"
- "       >"
- "       chat: < chatIdentifier: %@ displayName: %@"
- "   (pcid: %@"
- "   ),"
- "  Existing domain identifiers prior to malformed domain identifier: %s"
- " [identifier-domain-chatIdentifier]"
- " chatIdentifier: "
- " domainIdentifiers: "
- " for chat part with chat identifier "
- " lastAddressedHandle: "
- " lastAddressedSIMID: "
- " lastMessageDate: "
- " lastReadMessageTimeStamp: "
- " on chat part with uuid "
- " was promoted to the latest identifier in domain "
- "-[IMFamilySenderMessageProcessingPipelineComponent _allFamilyMemberHandlesInFamilyCircle:]"
- "-[IMFamilySenderMessageProcessingPipelineComponent _senderCorrelationIdentifier:correlatesWithHandles:completion:]"
- ". The current service is "
- "1:1 chat was missing participant, re-added %s to %s"
- "<IMFamilySenderMessageProcessingPipelineComponent> Started processing"
- "A historical identifier "
- "AccountID is nil for chat part with uuid (%s) falling back to account for SMS service."
- "Adding handle %@ handleCNID  %@ from chat part %@ to chat registry."
- "An identifier was requested for domain "
- "Attempt to update domain identifiers from CKRecord failed: Failed to assign new identifier %@ to chat part record with rowID %lld for domain %@ : %@"
- "Attempted to update the active chat part of chat with guid %@ with chat identifier hint %@, but failed to find any chat parts with that chat identifier.\n\nChat Parts: %@"
- "Attempting to update the chat identifier to %@ of an existing chat part with chat identifier %@!"
- "Attempting to update the chat identifier to %@ of an existing chat part with chat identifier %@! This should never occur."
- "Can't send response because no message GUID exists in the notification context"
- "Can't send response because no message URL exists in the notification context"
- "Can't send response because no participant handles were found for chat %@"
- "Can't send response because no responderHandle was found for chat %@"
- "Cannot recover participant due to empty chat identifier for chat part with uuid %s"
- "Chat Updated Without Chat Parts"
- "Chat fetched for writing up already has synced state"
- "Chat part from chat identifier hint not found! Chat with guid %@ has %ld chat parts."
- "ChatToSyncHasSyncedState"
- "Chats already exist in the groupID to chat index after removing chat from chats for groupID %@: %@.\n\nChats left in the index: %@"
- "Chats already exist in the groupID to chat index when attempting to add chat %@ from chats for groupID %@.\n\nChats left in the index: %@"
- "Chats still exist in the groupID to chat index after removing chat %@ from chats for groupID %@.\n\nChats left in the index: %@"
- "Chats still exist in the groupID to chat index after removing chat from chats for groupID %@: %@.\n\nChats left in the index: %@"
- "Could not find an accountID for chat part with uuid (%s)."
- "Critical Error! Updating chat parts on chat with guid %@ to nil from chat parts with identifiers %@."
- "Error! Cannot add chat with guid %@ to chatPartGroupID index because chat part with chat identifier %@ has no groupID."
- "Error! Cannot remove chat with guid %@ from chatPartGroupID index because chat part with chat identifier %@ has no groupID."
- "Error! Could not generate guid for chatPart with uuid: %@"
- "Explicitly updating latest chat part to %@"
- "Failed to Find Chat Part From Chat Identifier Hint"
- "Failed to acquire file for transfer %s: acquiredURL is nil or file does not exist at path"
- "Failed to find account for account ID %s"
- "Failed to find chat part by uuid %@, tried rowid %lld instead, found? %{BOOL}d"
- "Failed to find identifier domain for chat part %@ on service name %@"
- "Failed to find original group id for chat part %@ with service name %@"
- "Failed to unassign identifier %s from chat part record with chat identifier %s for domain %s"
- "Failed to update active chat part with chat identifier hint! IMDChat has no chat parts! This is not expected. Please file a radar to the Messages team!"
- "Failed to update lastest chat part! IMDChat with guid %@ has no chat parts!"
- "Family validation was required, but Family relation was not verifiable."
- "IMDaemonCore.IMDChatPart"
- "IMFamilySenderMessageProcessingPipelineComponent"
- "IMFamilySenderMessageProcessingPipelineComponent.m"
- "Malformed domain identifier %s already present in the cache. No metric event will be posted."
- "Malformed domain identifier %s in domain %s being assigned to chat part %s"
- "Message does not require Family validation."
- "Message is a message from me. No Family validation required."
- "Missing latest identifier for domain %s on chat part with uuid %s. The current service is %s"
- "Multiple Chats With Group ID"
- "No identifier domain found for service: %@"
- "No need to update active chat part as the active chat part already matches the chat identifier hint."
- "Not updating active chat part for chat %@ since chat identifier hint is nil."
- "Overwriting Chat Identifier"
- "Reassociated chat part to SMS account: %s"
- "Reassociating chat part to SMS service."
- "Some Chats Not Merged"
- "Some Chats Not UnMerged"
- "Some chats have chat parts still merged that should no longer be merged."
- "Some chats have chat parts that should be un merged that were found to be merged: %@"
- "Some chats remain un-merged:"
- "Some chats that should be merged were found to be unmerged: %@"
- "The chat parts on chat with guid %@ are being updated to nil from %@"
- "Trying to recover participant from a chat part that does not have its chat property populated. (chat identifier: %s)"
- "Trying to remove participant from a group chat part that does not have its chat property populated. (chat identifier: %s)"
- "Trying to remove participant from a group chat part with 2 or less participants %s"
- "Unexpected state! Chat %@ to sync has syncState 1"
- "Updating active chat part from %@ to %@ due to chat identifier hint."
- "Updating active chat part from nil to %@ due to chat identifier hint."
- "Updating active chat part to latest chat part: %{uuid_t}.16P %@"
- "Updating chat part %@ with participants: %@"
- "Updating latest chat part to %@"
- "Warning! Setting latest identifier in domain %s to an existing historical identifier %s."
- "[%{public}s] Task is not eligible to run because it has higher priority work"
- "[IMDChatPart uuid: "
- "calculateServiceForSending for pushMessageGUID %@ and service result %@:\nisFinal: %d\nisRCS: %d\ndidSupportEncryption: %d\nserviceForSendingResult.bestResult.allSupportEncryption): %d\nretryAsUnencryptedRCS: %d"
- "latest chat part chat identifier is nil for chat part with uuid %@"
- "latest chat part guid is nil for chat part with uuid %@"
- "v32@?0@\"NSString\"8@\"NSString\"16@\"NSError\"24"
```
