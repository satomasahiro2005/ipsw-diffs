## IMDaemonCore

> `/System/Library/PrivateFrameworks/IMDaemonCore.framework/IMDaemonCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b5258` | `0x3b7e58` | **`+0x2c00`** |
| `__TEXT.__oslogstring` | `0x54c17` | `0x54f37` | **`+0x320`** |
| `__DATA.__bss` | `0x5170` | `0x53f0` | **`+0x280`** |
| `__TEXT.__eh_frame` | `0x9c1c` | `0x9e54` | **`+0x238`** |
| `__TEXT.__const` | `0x8018` | `0x8238` | **`+0x220`** |
| `__TEXT.__gcc_except_tab` | `0x1f6c0` | `0x1f840` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0xdff8` | `0xe138` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x1b4cc` | `0x1b5fc` | **`+0x130`** |
| `__AUTH_CONST.__objc_const` | `0x23970` | `0x23a80` | **`+0x110`** |
| `__DATA_CONST.__objc_selrefs` | `0x10df0` | `0x10ef0` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x6c70` | `0x6d68` | **`+0xf8`** |
| `__DATA.__data` | `0x6618` | `0x6688` | **`+0x70`** |
| `__TEXT.__swift5_assocty` | `0x778` | `0x7d8` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0xa2d8` | `0xa330` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x3cb0` | `0x3d02` | **`+0x52`** |
| `__AUTH_CONST.__cfstring` | `0xef60` | `0xef20` | **`-0x40`** |
| `__TEXT.__cstring` | `0x145bc` | `0x145ec` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x37e8` | `0x3810` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x1c10` | `0x1c38` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x1c7c` | `0x1ca0` | **`+0x24`** |
| `__DATA_DIRTY.__data` | `0x36f8` | `0x3718` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x2b08` | `0x2b28` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x8d0` | `0x8ec` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0x208` | `0x21c` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x3c8` | `0x3dc` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x48c` | `0x4a0` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x2f10` | `0x2f20` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x12e4` | `0x12f4` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x938` | `0x948` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x3cc` | `0x3d8` | **`+0xc`** |
| `__DATA_CONST.__objc_protorefs` | `0x350` | `0x358` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x274` | `0x278` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-1486.100.5.2.1
+1487.100.6.2.2

-  Functions: 14537
-  Symbols:   3258
-  CStrings:  8524
+  Functions: 14592
+  Symbols:   3264
+  CStrings:  8534
Symbols:
+ _IMDCoreSpotlightDeleteAttachmentGUIDsWithCompletion
+ _IMMetricsCollectorEventFamilyValidationEnded
+ _IMMetricsCollectorEventFamilyValidationFamilyPhoneNumberAvailability
+ _IMMetricsCollectorEventFamilyValidationStarted
+ _IMSharedHelperPathIsInStickerCache
+ _OBJC_CLASS_$_IMMessageAssistantActionCompletionContext
CStrings:
+ "%@ service is not connected yet; deferring Stewie start message until it connects"
+ "%s: IDSCopyBestGuessIDForID was nil for handle %@ (normalized to %@)"
+ "%s: handles was nil"
+ "%s: member-appleID-aliases was nil or empty"
+ "%s: member.appleID was nil"
+ "%s: member.memberPhoneNumbers was nil or empty"
+ "%s: senderCorrelationIdentifier was nil"
+ "-[IMFamilySenderMessageProcessingPipelineComponent _allFamilyMemberHandlesInFamilyCircle:]"
+ "-[IMFamilySenderMessageProcessingPipelineComponent _senderCorrelationIdentifier:correlatesWithHandles:completion:]"
+ "1 Checking handle %@ for child bot exception"
+ "2 Attempting to lookup handle %@ for Family relation directly"
+ "3 Attempting to lookup handle %@ for Family relation using sender correlation identifier"
+ "Allowing mark-as-sent for already-sent message %@ on service %@ — session %@ will downgrade it"
+ "Could not find sender correlation identifier in SCI list derived from handles %@"
+ "Deleted %lu attachments from indexes"
+ "Denying mark-as-sent for message %@ (isSent: %{BOOL}d, isReplicating: %{BOOL}d, service: %@, sessionService: %@)"
+ "Error fetching FamilyCircle: %@"
+ "Failed to verify Family relation. Error: %@"
+ "Family relation verified"
+ "Family validation was required, but Family relation was not verifiable."
+ "Found %lu IDS endpoints for handle %@"
+ "Found child bot exception for handle %@"
+ "Found handle %@ directly within FamilyCircle"
+ "Found handle %@ in child-bot allow list"
+ "Found handle correlation using sender correlation identifier"
+ "Group Photo GUID %@ not found in transfer cache, looking up in db."
+ "Have file transfer matching groupPhotoGuid: %@ with group photo update date %@. FileTransfer: %@"
+ "IDS remote devices lookup result had %lu elements for handles %@"
+ "IMDStickerRegistry. Cached sticker hash mismatch; evicting and re-downloading. path %@"
+ "IMDStickerRegistry. Refusing to evict path outside the sticker cache: %@"
+ "Looking up remote devices for IDS handles %@"
+ "Message does not require Family validation."
+ "Message is a message from me. No Family validation required."
+ "Not preferring %@ over %@ because its group photo update date is not newer."
+ "Preferring %@ over %@ because its group photo update date is newer."
+ "Received SMSFilteringSettings message, but it was not from one of our own devices. Dropping."
+ "Received a Family message from a phone number and Family server contained no phone numbers to compare against"
+ "Service now connected; sending deferred Stewie start message"
+ "Session ended before service connected; failing deferred Stewie start message"
+ "The preferred groupPhotoGuid is %@."
+ "There were %lu sender correlation identifiers found from handles %@"
+ "Timed out waiting for transfer `%s` preview generation; persisting without complete processing."
+ "Transfer GUID %@ should be re-indexed due to preview generation state change; re-indexing %lu owning message(s)"
+ "errorCode"
+ "errorDomain"
+ "familyHasAtLeastOnePhoneNumber"
+ "generatePreviews()"
+ "validatedBy"
- "    Chat %@ has groupPhotoGuid %@"
- "(nil SCI) Message is not from known family member, received from: %@"
- "(with SCI lookup) Message is not from known family member, received from: %@"
- "Alias matches Family member %@"
- "Apple ID matches Family member %@"
- "Could not find sender correlation identifier in SCI list derived from Family"
- "Database read a failed scheduled message with an invalid scheduleState"
- "Deleting attachments with attachment guids from spotlight: %@"
- "Didn't find family member relation using raw handles. Attempting to lookup using SCIs."
- "Empty normalizedFamilyMemberHandles. Dropping Family message received from: %@"
- "FAFetchFamilyCircleRequest failed %@"
- "FAFetchFamilyCircleRequest returned no Family circle, but there was no specific error."
- "Failed to create IMMessageItem for scheduled message from recordRef."
- "Family IDS handles were empty"
- "Family IDS lookup result had %lu elements"
- "FamilyCircle fetch failed with specific error"
- "Found %lu IDS endpoints for Family member with handle %@"
- "Found family member relation using SCI"
- "Found family member relation using raw handles! %@"
- "Found fromHandle in child-bot allow list"
- "Found scheduled message: %@ for chatIdentifier: %@"
- "Have file transfer matching groupPhotoGuid: %@. FileTransfer: %@"
- "IDS data had no sender correlation identifier"
- "IMDChatStore-Database"
- "Message is a message from me: %@"
- "Message is not family extension"
- "Not preferring %@ because it does not have a creation date"
- "Not preferring %@ over %@ because the creation date is older."
- "Phone number matches Family member %@"
- "Preferring %@ over %@ because the creation date is newer."
- "Requested delete of temporary attachmentGUID %@ will also delete permanent attachmentGUID %@"
- "Skipping normalization of empty handle in allFamilyMemberHandles"
- "The preferred groupPhotoGuid is %@. Transfer: %@"
- "There were %lu SCIs in allFamilyMemberSCIs"
- "Transfer GUID %@ from message %@ should be re-indexed due to preview generation state change"
- "Unknown FamilyCircle fetch error"
- "handle could not be normalized for IDS lookup: %@"
- "normalizedFamilyMemberHandles: %@"
```
