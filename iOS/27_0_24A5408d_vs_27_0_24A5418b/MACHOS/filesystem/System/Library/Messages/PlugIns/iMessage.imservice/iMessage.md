## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/iMessage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x1548e` | `0x1552e` | **`+0xa0`** |
| `__TEXT.__text` | `0x10b510` | `0x10b58c` | **`+0x7c`** |
| `__TEXT.__objc_stubs` | `0xee00` | `0xee40` | **`+0x40`** |
| `__DATA.__objc_const` | `0x3db0` | `0x3de0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x32a4` | `0x32bc` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x4248` | `0x4258` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x9918` | `0x9928` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x1c65b` | `0x1c66b` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x270` | `0x274` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1491.100.1.2.11
+1491.100.1.2.23

-  Functions: 2455
+  Functions: 2457

-  CStrings:  5373
+  CStrings:  5378
CStrings:
+ "@128@0:8@16@24@32@40@48B56@60@68@76@84@92B100B104B108@112@120"
+ "PendingUpdate - needsDeliveryReceipt is %{BOOL}d for %@"
+ "Requesting delivery status for message GUID %@ for attachment update, not a group chat"
+ "TB,N,V_needsDeliveryReceipt"
+ "_needsDeliveryReceipt"
+ "_sendMessage:context:deliveryContext:fromID:fromAccount:toID:chatIdentifier:chatStyle:toSessionToken:toGroup:toParticipants:originallyToParticipants:requiredRegProperties:interestingRegProperties:requiresLackOfRegProperties:canInlineAttachments:flushingPLAS:sendAsAttachmentUpdate:suppressDeliveryReceipt:isPreAsyncFallback:type:msgPayloadUploadDictionary:originalPayload:replyToMessageGUID:fallbackCount:willSendBlock:placeholderSentBlock:completionBlock:"
+ "idsOptionsForAttachmentUpdateWithMessageItem:toID:fromID:sendGUIDData:alternateCallbackID:isBusinessMessage:chatIdentifier:requiredRegProperties:interestingRegProperties:requiresLackOfRegProperties:deliveryContext:isGroupChat:suppressDeliveryReceipt:canInlineAttachments:msgPayloadUploadDictionary:messageDictionary:"
+ "idsOptionsWithMessageItem:toID:fromID:sendGUIDData:alternateCallbackID:isBusinessMessage:chatIdentifier:requiredRegProperties:interestingRegProperties:requiresLackOfRegProperties:deliveryContext:isGroupChat:suppressDeliveryReceipt:canInlineAttachments:msgPayloadUploadDictionary:messageDictionary:"
+ "needsDeliveryReceipt"
+ "setNeedsDeliveryReceipt:"
+ "v220@0:8@16@24@32@40@48@56@64C72@76@84@92@100@108@116@124B132@136B144B148B152q156@164@172@180Q188@?196@?204@?212"
- "@124@0:8@16@24@32@40@48B56@60@68@76@84@92B100B104@108@116"
- "Setting needsDeliveryReceipt to %{BOOL}d since allExistingTransfersAreGradients = %{BOOL}d for transfers on message guid %@"
- "_sendMessage:context:deliveryContext:fromID:fromAccount:toID:chatIdentifier:chatStyle:toSessionToken:toGroup:toParticipants:originallyToParticipants:requiredRegProperties:interestingRegProperties:requiresLackOfRegProperties:canInlineAttachments:flushingPLAS:sendAsAttachmentUpdate:isPreAsyncFallback:type:msgPayloadUploadDictionary:originalPayload:replyToMessageGUID:fallbackCount:willSendBlock:placeholderSentBlock:completionBlock:"
- "idsOptionsForAttachmentUpdateWithMessageItem:toID:fromID:sendGUIDData:alternateCallbackID:isBusinessMessage:chatIdentifier:requiredRegProperties:interestingRegProperties:requiresLackOfRegProperties:deliveryContext:isGroupChat:canInlineAttachments:msgPayloadUploadDictionary:messageDictionary:"
- "idsOptionsWithMessageItem:toID:fromID:sendGUIDData:alternateCallbackID:isBusinessMessage:chatIdentifier:requiredRegProperties:interestingRegProperties:requiresLackOfRegProperties:deliveryContext:isGroupChat:canInlineAttachments:msgPayloadUploadDictionary:messageDictionary:"
- "v216@0:8@16@24@32@40@48@56@64C72@76@84@92@100@108@116@124B132@136B144B148q152@160@168@176Q184@?192@?200@?208"
```
