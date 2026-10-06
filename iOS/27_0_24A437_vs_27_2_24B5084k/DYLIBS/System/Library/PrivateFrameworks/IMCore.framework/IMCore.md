## IMCore

> `/System/Library/PrivateFrameworks/IMCore.framework/IMCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__const` | `0xc3f8` | `0xbef8` | **`-0x500`** |
| `__AUTH_CONST.__objc_const` | `0x22418` | `0x22778` | **`+0x360`** |
| `__TEXT.__text` | `0x2fd2ac` | `0x2fd5d4` | **`+0x328`** |
| `__DATA.__bss` | `0x1eae0` | `0x1e870` | **`-0x270`** |
| `__TEXT.__objc_methlist` | `0x18e4c` | `0x1906c` | **`+0x220`** |
| `__TEXT.__cstring` | `0x13355` | `0x13175` | **`-0x1e0`** |
| `__DATA_CONST.__objc_selrefs` | `0xeb20` | `0xeca0` | **`+0x180`** |
| `__AUTH_CONST.__cfstring` | `0xbac0` | `0xbbe0` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x23d1b` | `0x23dbb` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x119c4` | `0x11928` | **`-0x9c`** |
| `__AUTH_CONST.__auth_got` | `0x21a8` | `0x2228` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0xc3c0` | `0xc348` | **`-0x78`** |
| `__DATA.__data` | `0x6558` | `0x65b8` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x58a8` | `0x5908` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x40c0` | `0x4110` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x2890` | `0x28d0` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x12c4` | `0x12f8` | **`+0x34`** |
| `__AUTH_CONST.__objc_intobj` | `0x168` | `0x180` | **`+0x18`** |
| `__DATA.__common` | `0x7e0` | `0x7f8` | **`+0x18`** |
| `__TEXT.__eh_frame` | `0x72b0` | `0x72c0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x918` | `0x920` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x580` | `0x588` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x5b8` | `0x5c0` | **`+0x8`** |

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

-  Functions: 15223
-  Symbols:   2696
-  CStrings:  5025
+  Functions: 15190
+  Symbols:   2726
+  CStrings:  5014
Symbols:
+ _IMBalloonPluginIdentifierIsAppleCash
+ _IMConversationListSortingLogHandle
+ _IMCreateReplyThreadGroupingIdentifierForMessagePartChatItem
+ _IMCreateReplyThreadGroupingIdentifierForRetractedMessagePartChatItem
+ _IMCreateReplyThreadGroupingIdentifierForTranscriptPluginBreadcrumbChatItem
+ _IMDAttachmentRecordCopyAttachmentGUIDsAndPathsForChatIdentifiersOnServices
+ _IMDChatRecordCopyAllChats
+ _IMDChatRecordCopyChatForGUID
+ _IMDChatRecordCopyChatGUIDsWithUnplayedAudioMessages
+ _IMDChatRecordCopyChatsWithGroupID
+ _IMDCreateIMItemFromIMDMessageRecordRefWithAccountLookup
+ _IMDMessageRecordCopyChats
+ _IMDMessageRecordCopyLastReadMessageForChatIdentifier
+ _IMDMessageRecordCopyLastReceivedMessage
+ _IMDMessageRecordCopyLastReceivedMessageLimit
+ _IMDMessageRecordCopyMessageForRowID
+ _IMDMessageRecordCopyMessagesDataDetectionResults
+ _IMDMessageRecordCopyMessagesForGUIDs
+ _IMDMessageRecordCopyMessagesForRowIDs
+ _IMDMessageRecordCopyMessagesWithHandlesOnServicesLimit
+ _IMDMessageRecordCopyNewestUnreadIncomingMessagesToLimitAfterRowID
+ _IMDMessageRecordLastFailedMessageDate
+ _IMFileTransferPreflightGradientKey
+ _IMMessageSummaryInfoContentType
+ _IMMessageThreadIdentifierGetAllComponents
+ _IMSPILoadMessageGUIDsWithSurroundingContext
+ _IMSPISimulateEditMessage
+ _IMSceneStateManagerDidLeaveForegroundNotification
+ _IMTranscriptBackgroundSenderHandleKey
+ _NSRangeFromString
+ _OBJC_CLASS_$_IMCommSafetyUIUtilities
+ _OBJC_CLASS_$_IMMessagePartUtilities
+ _OBJC_CLASS_$_IMMobileNetworkManager
+ _OBJC_CLASS_$_IMReplyThreadGroupingIdentifier
+ _OBJC_CLASS_$_IMSharedPollDefinition
+ _OBJC_METACLASS_$_IMReplyThreadGroupingIdentifier
- _IMDAttachmentRecordCopyFilename
- _IMDAttachmentRecordCopyUTIType
- _IMDAttachmentRecordGetIsOutgoing
- _IMDAttachmentRecordIsSticker
- _IMDHandleRecordGetIdentifier
- _IMDMessageRecordGetIdentifier
CStrings:
+ "-[IMNicknameController initializeLocalNicknameStore]_block_invoke"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MessagesCore/IMCore/IMCore/Source/Accounts/IMNicknameController.m"
+ "Could not find cached subscription for handle: \"%@\". Not observing (yet)."
+ "Failed to find login IMHandle, using IMHandle generated with meHandle"
+ "Falling back to using last addressed handle"
+ "Forcing archived items to prepend to item array due to load context. MessageIDs did not match. De-duping GUIDs"
+ "Found a login IMHandle, using that as the handle"
+ "IMCoreSPI_EditMessage"
+ "IMSceneStateManagerDidLeaveForegroundNotification"
+ "IMSharedPollHelper"
+ "Not beginning observing availability in Apple Store Demo mode."
+ "Refusing to store a watermark dated in the future for %@: %{public}@. Leaving the existing watermark alone."
+ "Running initial load code after initial load has completed. This should not be possible."
+ "StatusKit subscription fetched %@, checking if a release is still necessary"
+ "This device can't report RCS spam locally for %@; relying on the carrier-junk relay path instead"
+ "_fileTransferFinished:reaggregate"
+ "associatedMessageRange"
+ "condition"
+ "mentionedHandlesByText"
+ "p:%lu/%@"
+ "self.isInitialLoad"
+ "textEffectType"
+ "v16@?0@\"IMDBulkChatHistoryQueryResult\"8"
+ "v32@?0@\"NSString\"8@\"NSString\"16^B24"
- "(p:(\\d+)\\/)?([\\dA-F]{8}-[\\dA-F]{4}-[\\dA-F]{4}-[\\dA-F]{4}-[\\dA-F]{12})"
- "B32@?0@\"NSString\"8^@16^@24"
- "Could not create IMSPIMessage from message record"
- "Could not find cached subscription for handle: \"%@\". Not observing availability (yet)."
- "Could not find cached subscription for handle: \"%@\". Not observing offgrid status (yet)."
- "Exception caught creating IMMessageItem from IMDMessageRecordRef: %@"
- "Failed to retrieve message %@"
- "Forcing archived items to prepend to item array due to load context. MessageIDs did not match"
- "IMDAttachmentRecordCopyAttachmentForGUID"
- "IMDAttachmentRecordCopyAttachmentGUIDsAndPathsForChatIdentifiersOnServices"
- "IMDChatRecordCopyAllChats"
- "IMDChatRecordCopyChatForGUID"
- "IMDChatRecordCopyChatGUIDsWithUnplayedAudioMessages"
- "IMDChatRecordCopyChatsWithGroupID"
- "IMDChatRecordCopyGUID"
- "IMDChatRecordCopyHandles"
- "IMDCreateIMItemFromIMDMessageRecordRefWithAccountLookup"
- "IMDHandleRecordBulkCopy"
- "IMDMessageRecordCopyChats"
- "IMDMessageRecordCopyHandle"
- "IMDMessageRecordCopyLastReadMessageForChatIdentifier"
- "IMDMessageRecordCopyLastReceivedMessage"
- "IMDMessageRecordCopyLastReceivedMessageLimit"
- "IMDMessageRecordCopyMessageForRowID"
- "IMDMessageRecordCopyMessagesDataDetectionResults"
- "IMDMessageRecordCopyMessagesForGUIDs"
- "IMDMessageRecordCopyMessagesForRowIDs"
- "IMDMessageRecordCopyMessagesWithChatIdentifiersOnServicesWithOnlyUnreadAndLimit"
- "IMDMessageRecordCopyMessagesWithHandlesOnServicesLimit"
- "IMDMessageRecordCopyNewestUnreadIncomingMessagesToLimitAfterRowID"
- "IMDMessageRecordLastFailedMessageDate"
- "Not beginnign observing availability in Apple Store Demo mode."
- "StatusKit Subscription fetched %@, checking if a retain is still necessary"
- "_IMDAttachmentRecordBulkCopy"
- "_IMDChatRecordBulkCopy"
```
