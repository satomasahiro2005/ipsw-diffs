## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/iMessage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10b658` | `0x1106fc` | **`+0x50a4`** |
| `__TEXT.__objc_methname` | `0x1552e` | `0x15d0e` | **`+0x7e0`** |
| `__TEXT.__objc_stubs` | `0xee40` | `0xf200` | **`+0x3c0`** |
| `__DATA.__objc_const` | `0x3de0` | `0x4138` | **`+0x358`** |
| `__TEXT.__oslogstring` | `0x1c66b` | `0x1c89b` | **`+0x230`** |
| `__DATA.__objc_data` | `0xdc8` | `0xf30` | **`+0x168`** |
| `__TEXT.__objc_methlist` | `0x32bc` | `0x3414` | **`+0x158`** |
| `__TEXT.__gcc_except_tab` | `0x9928` | `0x97e0` | **`-0x148`** |
| `__DATA.__objc_selrefs` | `0x4258` | `0x4368` | **`+0x110`** |
| `__TEXT.__cstring` | `0x3ebd` | `0x3fcd` | **`+0x110`** |
| `__DATA_CONST.__const` | `0x5480` | `0x5550` | **`+0xd0`** |
| `__TEXT.__objc_methtype` | `0x355e` | `0x362e` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x2c08` | `0x2cb0` | **`+0xa8`** |
| `__TEXT.__auth_stubs` | `0x2590` | `0x2620` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x5e0` | `0x654` | **`+0x74`** |
| `__DATA.__data` | `0xe98` | `0xef8` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x503` | `0x563` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x57c` | `0x5d4` | **`+0x58`** |
| `__TEXT.__objc_classname` | `0x7ef` | `0x83f` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x12d8` | `0x1320` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0xe26` | `0xe6e` | **`+0x48`** |
| `__DATA.__common` | `0x8` | `0x38` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1360` | `0x1388` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x3e80` | `0x3e60` | **`-0x20`** |
| `__TEXT.__const` | `0x15f8` | `0x1618` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x274` | `0x28c` | **`+0x18`** |
| `__DATA.__bss` | `0x1070` | `0x1080` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x128` | `0x138` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x330` | `0x338` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xb0` | `0xb8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x68` | `0x6c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

-  Functions: 2457
-  Symbols:   1000
-  CStrings:  5378
+  Functions: 2520
+  Symbols:   1003
+  CStrings:  5443
Symbols:
+ _IMTranscriptBackgroundSenderHandleKey
+ _OBJC_CLASS_$_IMDAttachmentDownloadPolicyFilter
+ _swift_deallocPartialClassInstance
CStrings:
+ "    user info: %s"
+ " => Settled on signatures: %s"
+ " urlStrings: %s   owners: %s    signatures: %s  keys: %s  fileSizeStrings: %s"
+ "?8E"
+ "?;E"
+ "?E"
+ "@\"AttachmentDownloadRestriction\""
+ "@\"IMDAttachmentDownloadPolicyFilter\""
+ "@40@0:8B16B20q24q32"
+ "@44@0:8@16^B24B32@?36"
+ "Attachment download context is missing entries (signature = %s, ownerID = %s, fileSizeString = %s, encryptionKey = %{private}s)"
+ "B20@?0@\"_TtC8iMessage24MessageAttachmentRequest\"8B16"
+ "Download progress updated to for transferID %@ %lld of %lld (%lld bps)"
+ "Failed to remap guids after scheduled message sent, will fall back to stored message"
+ "Failed type check! {key: %@, class: %@}"
+ "Ignoring this file (fileSizeString: %s), download not allowed"
+ "Ignoring this file for smallest (fileSizeString: %s), file is invalid or missing size"
+ "Ignoring this file, file is larger than current smallest (fileSizeString: %s), (smallestFileSizeString: %s)"
+ "Message %@ found sensitive after acquisition; failing send."
+ "Message %@ is blocked pending unresolved CommSafety decision"
+ "MessageSpamDecisionResults"
+ "No files are acceptable to download"
+ "Not downloading attachments for message %@ as it is a typing message"
+ "Released pending attachment preview for %@ (%{BOOL}d)"
+ "Scheduled message delivered without edits — keeping stored attachments and remapping %lu incoming transfer records %@"
+ "Scheduled message was delivered with %lu transfers but %lu were stored, can't map them onto each other. Using the incoming attachments instead"
+ "Send of %@ was attempted on airplane mode without wifi enabled, not actually sending the message"
+ "T@\"AttachmentDownloadRestriction\",N,&,VdownloadRestriction"
+ "T@\"IMDAttachmentDownloadPolicyFilter\",R,N,V_attachmentDownloadPolicyFilter"
+ "T@\"NSNumber\",N,R,VfileSize"
+ "TB,N,V_sentWithoutNetwork"
+ "TB,R,N,V_isBlackholed"
+ "TB,R,N,V_shouldTrackForRequery"
+ "Taking this file, we're good to grab it (this: %s)"
+ "Tq,R,N,V_isFiltered"
+ "Tq,R,N,V_spamDetectionSource"
+ "Will download file(s) of size: %s"
+ "_TtC8iMessage24MessageAttachmentRequest"
+ "_attachmentDownloadPolicyFilter"
+ "_automation_messageContextFromTopLevelMessage:"
+ "_generateSURFSnapshotForMessage:completion:"
+ "_handleTransferDownloadFinishedForMessage:messageID:attachmentSuccess:errorType:fileTransferError:failedFileSize:additionalErrorInfo:downloadStartTime:token:toIdentifier:fromIdentifier:account:"
+ "_isBlackholed"
+ "_isFiltered"
+ "_sentWithoutNetwork"
+ "_shouldTrackForRequery"
+ "_spamDetectionSource"
+ "addActiveDownloadForStage:"
+ "attachmentDownloadPolicyFilter"
+ "attachmentRequestsFor:foundAnyFile:isLowQualityModeEnabled:isDownloadAllowed:"
+ "blockingTransferGUIDs:reason:"
+ "copyByStrippingReplyThreadingForBackwardsCompatibility"
+ "deviceIsLockedDownFor:senderOrigin:"
+ "downloadRestriction"
+ "fileExistsForTransfer:"
+ "fileSizeString"
+ "fileTransferCenter"
+ "hasActiveDownloadForStage:"
+ "hasNoNetworkForSending"
+ "hasUnresolvedCommSafetySendDecision"
+ "hasUnresolvedCommSafetySendDecisionWithFileTransferCenter:"
+ "iMessage.MessageAttachmentRequest"
+ "initWithFileTransferCenter:"
+ "initWithIsBlackholed:shouldTrackForRequery:isFiltered:spamDetectionSource:"
+ "initWithRequestURLString:signature:ownerID:fileSize:encryptionKey:"
+ "initWithUserInfo:"
+ "initWithUserInfo:index:"
+ "isNonBlockingAttachmentReceiveEnabled"
+ "isValid"
+ "logAttachmentRequests:forTransfer:"
+ "noEligibleDestinationsCache"
+ "ownerID"
+ "receiveFileTransfer:topic:path:requestURLString:ownerID:sourceAppID:senderExemptFromLDM:signature:decryptionKey:fileSize:priority:progressBlock:completionBlock:"
+ "receiveFileTransfer:transferGUID:topic:path:requestURLString:ownerID:signature:decryptionKey:fileSize:balloonBundleID:senderContext:senderID:priority:progressBlock:completionBlock:"
+ "removeActiveDownloadForStage:"
+ "requestURLString"
+ "retrieveAttachmentsForMessage:inChat:inlineAttachments:displayID:topic:comingFromStorage:shouldForceAutoDownload:senderContext:blockingTransferGUIDs:individualAttachmentFinishedBlock:completionBlock:lateDownloadCompletionBlock:"
+ "send message: %@  guid: %@  to identifier: %@   chat: %@   callerURI: %@   self: %@   account: %@ associatedMessageGUID: %@  associatedMessageType: %lld  messageItemClass: %@ fileTransferGUID %@ network: %{BOOL}d"
+ "sentWithoutNetwork"
+ "setDownloadRestriction:"
+ "setHadNoEligibleDestinations:forMessageGUID:"
+ "setSentWithoutNetwork:"
+ "shouldTrackForRequery"
+ "updateTemporaryFileTransferGUIDsWithPermanentFileTransferGUIDs:"
+ "v104@0:8@16@24@32@40@48B56B60@64@72@?80@?88@?96"
+ "v104@0:8@16@24B32I36@40Q48@56@64@72@80@88@96"
+ "v16@?0@\"MessageSpamDecisionResults\"8"
+ "v28@?0@\"IMMessageItem\"8@\"NSString\"16B24"
+ "v72@?0@\"IMMessageItem\"8@\"NSString\"16B24I28@\"NSError\"32Q40@\"NSString\"48@\"MessageSpamDecisionResults\"56@?<v@?>64"
- "    user info: %@"
- " => Assigning this one: %@ fileSize: %@"
- " => Settled on signatures: %@"
- " urlStrings: %@   owners: %@    signatures: %@  keys: %@  fileSizeStrings: %@"
- "%@-%d"
- "?2E"
- "?8I"
- "?:I"
- "Downlaod progress updated to for transferID %@ %lld of %lld (%lld bps)"
- "Grabbing the largest file we can find (size: %@)"
- "Ignoring this file, still not allowed to auto download (localFileSizeString: %@), (fileSizeString:%@), shouldAutoDownload:%@ "
- "MessageService: Attachment download context is missing entries (signature = %@, ownerID = %@, fileSizeString = %@, encryptionKey = %@)"
- "Released pending attachment preview for %@ (%b)"
- "Scheduled message delivered without edits — keeping stored attachments and discarding %lu incoming transfer records"
- "Taking this file, we're good to grab it (this: %@ vs fileSizeString: %@)"
- "The first file wasn't allowed to auto download, let's look and see what we have... shouldAutoDownloadFile %@, lowQualityModeEnabled %@"
- "Will download file of size %@ "
- "__imFirstObject"
- "deviceIsLockedDown"
- "receiveFileTransfer:transferGUID:topic:path:requestURLString:ownerID:signature:decryptionKey:fileSize:balloonBundleID:senderContext:senderID:progressBlock:completionBlock:"
- "retrieveAttachmentsForMessage:inChat:inlineAttachments:displayID:topic:comingFromStorage:shouldForceAutoDownload:senderContext:completionBlock:lateDownloadCompletionBlock:"
- "send message: %@  guid: %@  to identifier: %@   chat: %@   callerURI: %@   self: %@   account: %@ associatedMessageGUID: %@  associatedMessageType: %lld  messageItemClass: %@ fileTransferGUID %@"
- "v36@?0B8B12B16q20q28"
- "v88@0:8@16@24@32@40@48B56B60@64@?72@?80"
```
