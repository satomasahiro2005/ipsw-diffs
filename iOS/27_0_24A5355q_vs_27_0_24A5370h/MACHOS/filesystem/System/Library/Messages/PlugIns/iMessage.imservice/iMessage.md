## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/iMessage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x104674` | `0x107280` | **`+0x2c0c`** |
| `__TEXT.__oslogstring` | `0x1bc2b` | `0x1c1ab` | **`+0x580`** |
| `__TEXT.__objc_methname` | `0x148c0` | `0x14c4d` | **`+0x38d`** |
| `__TEXT.__objc_stubs` | `0xe840` | `0xea40` | **`+0x200`** |
| `__DATA_CONST.__const` | `0x52e8` | `0x53d8` | **`+0xf0`** |
| `__DATA.__objc_const` | `0x3798` | `0x3878` | **`+0xe0`** |
| `__DATA_CONST.__cfstring` | `0x3d40` | `0x3de0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x3cfd` | `0x3d9d` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x2fbc` | `0x305c` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0x40b0` | `0x4148` | **`+0x98`** |
| `__TEXT.__swift5_capture` | `0x920` | `0x994` | **`+0x74`** |
| `__DATA_CONST.__got` | `0x12e8` | `0x1310` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2b30` | `0x2b58` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x2500` | `0x2520` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x3d8` | `0x3f0` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0xdd8` | `0xdc6` | **`-0x12`** |
| `__DATA.__objc_ivar` | `0x238` | `0x248` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1290` | `0x12a0` | **`+0x10`** |
| `__TEXT.__const` | `0x1558` | `0x1548` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x9b30` | `0x9b24` | **`-0xc`** |
| `__DATA.__data` | `0xdb8` | `0xdb0` | **`-0x8`** |
| `__TEXT.__eh_frame` | `0x19c0` | `0x19c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1481.100.29.2.9
+1483.100.10.2.4

-  Functions: 2343
-  Symbols:   991
-  CStrings:  5232
+  Functions: 2379
+  Symbols:   997
+  CStrings:  5279
Symbols:
+ _IMFileTransferPreflightGradientKey
+ _IMFileTransferPreflightHeightKey
+ _IMFileTransferPreflightWidthKey
+ _IMMessageItemRequiresLegacyAppleCashReplyFallback
+ _UTTypeGIF
+ _UTTypeMovie
CStrings:
+ " update"
+ "Advanced to final stage but got invalid totalBytes value. Skipping bytes reset."
+ "Applying any pending attachment updates to %@"
+ "Attachment update ignored: empty userInfo for transfer %@: %@"
+ "Aux image %@ is in stage final, but aux video is in stage %@. Downgrading aux image transfer to preview. When the aux video transfer's upload completes, an update attachment should be sent in stage final."
+ "Couldn't send new features to these destinations: %@, [%lu] times we're in fallback for message %@. %@"
+ "Deleteing old stored attachments %@, since we've now received the self-delivered edited message"
+ "EAGER use -- no eager upload status found for transfer %@ eagerUploadKey %@."
+ "Expected to find video transfer guid %@ when determining aux video transfer stage."
+ "Failed to generate gradient for transfer %@ (%lu/%lu) on message %@ with error: %@, gradient %@. %@"
+ "Finished applying any pending attachment updates, retrieving attachments for %@"
+ "Finished applying post-storage pending attachment previews for %@"
+ "Finished sending a preview%@ for message %@ success %{BOOL}d. %@"
+ "Generating gradient(s) for %ld transfer(s) on message %@. %@"
+ "Gradient"
+ "However, transfer %@ on message %@ is missing preflight width or height. This is bad! %@"
+ "None"
+ "Not sending a preview %@ for message %@. asyncAttachmentCapability: %@ didSendPreview: %{BOOL}d uploadComplete: %{BOOL}d. %@"
+ "Not sending gradient for message %@. asyncAttachmentCapability: %@ didSendPreview: %{BOOL}d uploadComplete: %{BOOL}d. %@"
+ "Parser+NBAS"
+ "PrePopulate: Refusing to add cmd-108 entry for partName %lu on message %@: xfer=%@ userInfo=%@. %@"
+ "Preview"
+ "Scheduled message delivered without edits — keeping stored attachments and discarding %lu incoming transfer records"
+ "Sending Apple Cash reply %@ without thread identifier to legacy destinations"
+ "Sending fallback message for %@. %@"
+ "Successfully generated gradient with dimensions (w: %@, h: %@) for transfer %@ (%lu/%lu) on message %@. %@"
+ "T@\"IMDAccount\",&,N,V_idsRoutingIMDAccount"
+ "T@\"NSMutableDictionary\",&,N,V_transcriptBackgroundLastRemoveSender"
+ "T@\"NSMutableDictionary\",&,N,V_transcriptBackgroundLastRemoveVersion"
+ "TB,N,V_didReflectMessageToSelf"
+ "Transfer %@ on message %@ already has gradient colors, skipping its gradient generation in MessageDeliveryController. %@"
+ "Using passed-in message instead of stored message — scheduled message was edited or retracted"
+ "We recieved a remove background request while downloading this background"
+ "[TEST] Transfer %s done waiting %f seconds for eager upload."
+ "[TEST] Transfer %s eager upload waiting %f seconds for testing purposes."
+ "_allowGradientSendForMessageItem:"
+ "_asyncAttachmentCapabilityForMessageItem:"
+ "_didReflectMessageToSelf"
+ "_idsRoutingIMDAccount"
+ "_transcriptBackgroundLastRemoveSender"
+ "_transcriptBackgroundLastRemoveVersion"
+ "acquireFileAndUpdateTransferForTransferGUID:chatGUID:completion:error:"
+ "componentsJoinedByString:"
+ "deleteTransferForGUID:"
+ "didImportScheduledMessageWithGUID:fireDate:"
+ "didReflectMessageToSelf"
+ "idsRoutingIMDAccount"
+ "isOneOfMyAliases:"
+ "msg guid %@ Required reg properties %@ interesting properties %@ newFeature %{BOOL}d sendPropsCompatMsgAsText %{BOOL}d sendAsAttachmentUpdate %{BOOL}d upgradeToOnlyAsyncReceivers %{BOOL}d onlyAsyncReceivers %{BOOL}d %@"
+ "preflightInfo"
+ "setDidReflectMessageToSelf:"
+ "setGradient:"
+ "setIdsRoutingIMDAccount:"
+ "setTranscriptBackgroundLastRemoveSender:"
+ "setTranscriptBackgroundLastRemoveVersion:"
+ "supportedUTTypesForGradient"
+ "supportedUTTypesForPreview"
+ "supports-apple-cash-replies"
+ "supportsFaceTimeForSenderOrigin:"
+ "transcriptBackgroundLastRemoveSender"
+ "transcriptBackgroundLastRemoveVersion"
+ "transfer-eager-upload-delay-sending"
+ "transfer-eager-upload-delay-sending-auxvideo-enabled"
+ "userInfoSafeForLogging"
+ "v28@?0B8@\"IMThumbnailGradient\"12@\"NSError\"20"
- "-allowingPreRaveDevicesForEnforcement"
- "Couldn't send new features to these destinations: %@, [%lu] times we're in fallback for message %@."
- "Deleteing old stored attachments %@, since we've now received the self-delivered message"
- "Failed to generate gradient for transfer %@ (%lu/%lu) on message %@ with error: %@. %@"
- "Finished sending a preview %@ for message %@ success %{BOOL}d. %@"
- "Generating gradients for %ld transfer(s) on message %@. %@"
- "Not sending a preview %@ for message %@. shouldSendPreview: %{BOOL}d didSendPreview: %{BOOL}d uploadComplete: %{BOOL}d. %@"
- "Not sending gradient for message %@. shouldSendPreview: %{BOOL}d didSendPreview: %{BOOL}d uploadComplete: %{BOOL}d. %@"
- "PrePopulate: No existing transferInfo found for transfer %@ on message %@. %@"
- "Sending fallback message for %@."
- "Successfully generated gradient for transfer %@ (%lu/%lu) on message %@. %@"
- "Using passed-in message instead of stored message as it might be an edited scheduled message"
- "acquireFileAndUpdateTransferForTransferGUID:completion:error:"
- "isEqualToDictionary:"
- "msg guid %@ Required reg properties %@ interesting properties %@ newFeature %{BOOL}d sendPropsCompatMsgAsText %{BOOL}d sendAsAttachmentUpdate %{BOOL}d upgradeToOnlyAsyncReceivers %{BOOL}d onlyAsyncReceivers %{BOOL}d"
- "setGradientColors:"
- "supportsFaceTime"
- "v28@?0B8@\"NSArray\"12@\"NSError\"20"
```
