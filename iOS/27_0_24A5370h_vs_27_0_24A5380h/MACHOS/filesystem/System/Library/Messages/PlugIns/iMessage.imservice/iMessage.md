## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/iMessage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x107280` | `0x109a88` | **`+0x2808`** |
| `__TEXT.__oslogstring` | `0x1c1ab` | `0x1c40b` | **`+0x260`** |
| `__TEXT.__objc_methname` | `0x14c4d` | `0x14de2` | **`+0x195`** |
| `__DATA.__bss` | `0xf60` | `0x1070` | **`+0x110`** |
| `__TEXT.__gcc_except_tab` | `0x9b24` | `0x9a40` | **`-0xe4`** |
| `__TEXT.__eh_frame` | `0x19c8` | `0x1a80` | **`+0xb8`** |
| `__TEXT.__const` | `0x1548` | `0x15f8` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x3d9d` | `0x3e4d` | **`+0xb0`** |
| `__DATA_CONST.__cfstring` | `0x3de0` | `0x3e80` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0xea40` | `0xeae0` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x2520` | `0x2590` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0xdc6` | `0xe26` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x2b58` | `0x2bb8` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x1310` | `0x1358` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0x12a0` | `0x12d8` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x4148` | `0x4178` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x5b0` | `0x5e0` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x3279` | `0x32a9` | **`+0x30`** |
| `__DATA.__data` | `0xdb0` | `0xdd8` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x548` | `0x570` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x994` | `0x9b4` | **`+0x20`** |
| `__DATA.__common` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x53d8` | `0x53e0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x305c` | `0x3064` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x64` | `0x6c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x64` | `0x68` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  Functions: 2379
-  Symbols:   997
-  CStrings:  5279
+  Functions: 2406
+  Symbols:   1000
+  CStrings:  5297
Symbols:
+ _IMMetricsCollectorEventCKVEndpointFailure
+ _IMUTITypeForFilename
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
CStrings:
+ "   Group found, but failed validation. Dropping incoming group message payload %@. senderFailedValidation %{BOOL}d isPlaceholder %{BOOL}d"
+ "   Group found, but sender was not in the set of participants and was rejected. Dropping incoming group message payload %@."
+ "   No group found. A new group chat will get created with the new "
+ "   No group found. Dropping incoming group message payload %@."
+ "@72@0:8@16@24@32@40@48Q56^Q64"
+ "AssignToTransfer skipping stage:Final for transfer %@ — eager upload state is %{public}@, not success"
+ "Attachment preview finished uploading! We're now in preflight preview stage for transfer guid %@ on message guid %@"
+ "B68@0:8@16@24@32@40@48B56@60"
+ "Dropping group photo request -- sender is not a member in the chat."
+ "Early return receiving message before first unlock, ignoring incoming message of type Other from %@"
+ "Group Message Payload is from a known sender %@. The payload will continue processing."
+ "Group Message Payload is incoming on an unknown chat. The message type, %@, is not acceptable for an unknown chat and will be dropped."
+ "Group Message Payload is incoming on chat %@, which is a known chat. The payload will continue processing."
+ "Group Message Payload is incoming, but a chat was not found. The message type, %@, is not acceptable for a non-existant chat and will be dropped."
+ "Group Message Payload is of type %@ that is acceptable for both known and unknown senders. The payload will continue processing."
+ "Incoming group message payload from: %@   payload: %@  isReflection: %{BOOL}d  to: %@, timestamp: %@"
+ "Kickoff gradient send delay of %.0fs for message %@. %@"
+ "Not sending asset as a preview, since isVideo: %{BOOL}d, isOutputURLOfSmallestAttachment: %{BOOL}d, transfer stage: %@ for transfer guid %@ on message guid %@"
+ "Previews"
+ "Successfully configured transfer guid %@"
+ "TransferEagerUploadForceMMCSFailure"
+ "[TEST] Forcing synthetic MMCS upload failure for transfer %s on message %s"
+ "_configurePreviewTransfer:forMessage:usingAttachmentSendContexts:fileSizeKey:"
+ "_findChatFromIdentifier:toIdentifier:displayName:participants:groupID:validationOptions:failedValidations:"
+ "_shouldAcceptGroupMessagePayloadWithFromIdentifier:toIdentifier:displayName:participants:groupID:isKnownSender:type:"
+ "areMyAliases:forService:"
+ "bestCandidateGroupChatWithFromIdentifier:toIdentifier:displayName:participants:updatingToLatestiMessageGroupID:sortedIdentifiers:serviceName:validationOptions:failedValidations:"
+ "ckv_endpoints"
+ "ckv_policy_failed_tag"
+ "extractCKVPerEndpointMetrics"
+ "isOneOfMyAliases:forService:"
+ "ktError"
+ "plas-gradient-preview-delay"
+ "receiver_type"
+ "setCkvUnderlyingErrorCode:"
+ "setCkvUnderlyingErrorDomain:"
+ "transparency"
+ "underlyingErrorCode"
+ "underlyingErrorDomain"
- "   No group found"
- "%ld transfer(s) for message %@ may need to upload a preview. %@"
- "-thumbnail"
- "B36@0:8@16B24@28"
- "Does not have thumbnails for all transfers for message %@, skipping thumbnail upload. %@"
- "Incoming group message payload from: %@   payload: %@  isReflection: %@  to: %@, timestamp: %@"
- "Not uploading a preview for transfer %@ (%lu/%lu) on message %@ because no thumbnail was available for transfer. %@"
- "Not uploading a preview for transfer %@ (%lu/%lu) on message %@ because no transfer was found. Silently ignoring failure. %@"
- "Received GenericGroupCommand from someone who is not in the group. fromIdentifier: %@ chatGuid: %@"
- "Registering for gradient send after 5s delay on message %@. %@"
- "Thumbnail upload failed for transfer %@ (%lu/%lu) on message %@ with error: %@. %@"
- "Thumbnail upload succeeded for transfer %@ (%lu/%lu) (%llu bytes) on message %@. %@"
- "Thumbnail upload succeeded for transfer %@ on message %@ but already in final stage! %@"
- "Thumbnail uploading completed for message %@. Ready to send preview(s), but may wait until gradient send completes if there is a gradient send in progress for this message. %@"
- "Thumbnail uploads complete for %@ success: %@"
- "Uploading thumbnail preview for transfer %@ (%lu/%lu) on message %@. %@"
- "_shouldAcceptGroupMessagePayloadWithExistingChat:isKnownSender:type:"
- "_validateChat:containsFromIdentifier:isReflection:"
- "getNumberOfTimesRespondedToThread"
- "isOneOfMyAliases:"
- "uploadThumbnailPreviewForMessage:recipients:completion:"
```
