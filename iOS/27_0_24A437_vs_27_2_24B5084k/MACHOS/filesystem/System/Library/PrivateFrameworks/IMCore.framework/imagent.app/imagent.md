## imagent

> `/System/Library/PrivateFrameworks/IMCore.framework/imagent.app/imagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x61eb8` | `0x63dc8` | **`+0x1f10`** |
| `__TEXT.__objc_methname` | `0xca79` | `0xcdb9` | **`+0x340`** |
| `__TEXT.__eh_frame` | `0x1858` | `0x19a0` | **`+0x148`** |
| `__TEXT.__objc_stubs` | `0x7b60` | `0x7ca0` | **`+0x140`** |
| `__TEXT.__objc_methtype` | `0x349b` | `0x3573` | **`+0xd8`** |
| `__DATA_CONST.__const` | `0x25a8` | `0x2670` | **`+0xc8`** |
| `__TEXT.__auth_stubs` | `0x1ac0` | `0x1b40` | **`+0x80`** |
| `__TEXT.__cstring` | `0x180c` | `0x188c` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x2be0` | `0x2c40` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x6d7b` | `0x6ddb` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1d68` | `0x1dc8` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x7dc` | `0x830` | **`+0x54`** |
| `__DATA_CONST.__auth_got` | `0xd70` | `0xdb0` | **`+0x40`** |
| `__TEXT.__const` | `0x1a40` | `0x1a80` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x3360` | `0x33a0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x3474` | `0x3498` | **`+0x24`** |
| `__DATA_CONST.__got` | `0xb00` | `0xb20` | **`+0x20`** |
| `__DATA.__data` | `0x1810` | `0x1828` | **`+0x18`** |
| `__DATA.__objc_const` | `0x32f8` | `0x3310` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x92e` | `0x93e` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x114` | `0x120` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x118` | `0x124` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x104` | `0x110` | **`+0xc`** |
| `__DATA.__objc_data` | `0x10a0` | `0x10a8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x91c` | `0x924` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

-  Functions: 1529
-  Symbols:   621
-  CStrings:  2564
+  Functions: 1549
+  Symbols:   626
+  CStrings:  2583
Symbols:
+ _IMCopyAnyServiceGUIDForChat
+ _IMServiceBundleFromNSBundle
+ _IMServiceNameAny
+ _OBJC_CLASS_$_IMDBulkChatHistoryQueryHandler
+ _OBJC_CLASS_$_IMDChatForkMerger
+ _OBJC_CLASS_$_IMMessageItem
- _IMDCreateIMMessageItemFromIMDMessageRecordLoadAttachmentIfNeededRef
CStrings:
+ "21:34:30"
+ "Could not find message with GUID %s in %s."
+ "Request from %@ to perform %d bulk history queries"
+ "Sep  8 2026"
+ "createIMMessageItemFromIMDMessageRecordRef:inputHandleString:useAttachmentCache:shouldLoadAttachments:"
+ "editedMessageItemWithOriginalMessageItem:editedPartIndex:newPartText:newPartTranslation:"
+ "editedMessageItemWithOriginalMessageItem:retractedPartIndex:shouldRetractSubject:"
+ "fetchItemsWithBulkHistoryQueryRequests:urgent:completionHandler:"
+ "fetchSerializedItemsWithBulkHistoryQueryRequests:urgent:completionHandler:"
+ "initWithString:"
+ "mergeChatForks(intoLeadChatIdentifier:forkChatIdentifiers:)"
+ "mergeChatForksIntoLeadChatIdentifier:forkChatIdentifiers:completionHandler:"
+ "mergeChatsIntoLeadChatGUID:forkChatGUIDs:completionHandler:"
+ "moveMessagesWithGUIDsToRecentlyDeleted:deleteDate:fromSync:"
+ "reconcileForksToLeadChatIdentifier:forkChatIdentifiers:"
+ "simulateEditMessage(withGUID:replacementText:part:completion:)"
+ "simulateEditMessageWithGUID:replacementText:partIndex:completion:"
+ "storeEditedMessage:editedPartIndex:editType:previousMessage:chat:updatedAssociatedMessageItems:"
+ "storeRecoverableMessagePartWithBody:forMessageWithGUID:deleteDate:fromSync:"
+ "synchronousDatabaseQueryProvider"
+ "v36@0:8@\"NSArray\"16B24@?<v@?@\"NSArray\"@\"NSArray\"@\"NSArray\"@\"NSArray\">28"
+ "v40@0:8@\"NSString\"16@\"NSArray\"24@?<v@?@\"NSError\">32"
+ "v48@0:8@\"NSString\"16@\"NSString\"24q32@?<v@?B>40"
- "21:23:51"
- "Sep  2 2026"
- "moveMessagesWithGUIDsToRecentlyDeleted:deleteDate:"
- "storeRecoverableMessagePartWithBody:forMessageWithGUID:deleteDate:"
```
