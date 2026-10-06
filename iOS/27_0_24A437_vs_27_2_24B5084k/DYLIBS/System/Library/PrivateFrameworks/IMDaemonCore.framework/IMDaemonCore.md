## IMDaemonCore

> `/System/Library/PrivateFrameworks/IMDaemonCore.framework/IMDaemonCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3aba20` | `0x3c1ffc` | **`+0x165dc`** |
| `__AUTH_CONST.__objc_const` | `0x236b0` | `0x276a0` | **`+0x3ff0`** |
| `__TEXT.__objc_methlist` | `0x1b394` | `0x1d694` | **`+0x2300`** |
| `__TEXT.__oslogstring` | `0x546e7` | `0x55692` | **`+0xfab`** |
| `__DATA.__data` | `0x6670` | `0x6d9c` | **`+0x72c`** |
| `__TEXT.__eh_frame` | `0xa068` | `0xa6dc` | **`+0x674`** |
| `__AUTH.__objc_data` | `0x30f8` | `0x3688` | **`+0x590`** |
| `__DATA_CONST.__objc_selrefs` | `0x10ed0` | `0x11350` | **`+0x480`** |
| `__TEXT.__const` | `0x8588` | `0x88d8` | **`+0x350`** |
| `__TEXT.__unwind_info` | `0xe070` | `0xe358` | **`+0x2e8`** |
| `__TEXT.__gcc_except_tab` | `0x1f784` | `0x1fa18` | **`+0x294`** |
| `__TEXT.__cstring` | `0x1407c` | `0x14306` | **`+0x28a`** |
| `__TEXT.__swift5_typeref` | `0x3d78` | `0x3f50` | **`+0x1d8`** |
| `__AUTH_CONST.__const` | `0xa3b8` | `0xa578` | **`+0x1c0`** |
| `__TEXT.__delay_stubs` | `—` | `0x1c0` | **`+0x1c0`** |
| `__TEXT.__delay_helper` | `—` | `0x1bc` | **`+0x1bc`** |
| `__TEXT.__constg_swiftt` | `0x2bb8` | `0x2d6c` | **`+0x1b4`** |
| `__TEXT.__swift5_reflstr` | `0x18cf` | `0x1a0b` | **`+0x13c`** |
| `__TEXT.__swift5_fieldmd` | `0x1c24` | `0x1d50` | **`+0x12c`** |
| `__DATA_CONST.__got` | `0x37b0` | `0x38d8` | **`+0x128`** |
| `__AUTH.__data` | `0x608` | `0x718` | **`+0x110`** |
| `__DATA_CONST.__const` | `0x6d88` | `0x6e70` | **`+0xe8`** |
| `__AUTH_CONST.__auth_got` | `0x2f20` | `0x2fc0` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0xee40` | `0xeee0` | **`+0xa0`** |
| `__DATA_CONST.__objc_protolist` | `0x948` | `0x9e0` | **`+0x98`** |
| `__DATA_CONST.__objc_classlist` | `0xa48` | `0xad8` | **`+0x90`** |
| `__DATA.__bss` | `0x5880` | `0x58e0` | **`+0x60`** |
| `__TEXT.__swift_as_cont` | `0x910` | `0x968` | **`+0x58`** |
| `__DATA.__objc_ivar` | `0x12ec` | `0x133c` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x1c94` | `0x1cc8` | **`+0x34`** |
| `__TEXT.__swift_as_ret` | `0x4b0` | `0x4e4` | **`+0x34`** |
| `__AUTH_CONST.__objc_intobj` | `0xbe8` | `0xbb8` | **`-0x30`** |
| `__DATA_DIRTY.__bss` | `0x2940` | `0x2910` | **`-0x30`** |
| `__DATA_DIRTY.__data` | `0x3718` | `0x36e8` | **`-0x30`** |
| `__DATA_CONST.__objc_superrefs` | `0x608` | `0x630` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x3f0` | `0x414` | **`+0x24`** |
| `__TEXT.__swift5_types` | `0x280` | `0x294` | **`+0x14`** |
| `__DATA_CONST.__objc_catlist` | `0xe8` | `0xf8` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x358` | `0x368` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x400` | `0x410` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x44` | `0x54` | **`+0x10`** |
| `__DATA_DIRTY.__objc_data` | `0x3ce0` | `0x3ce8` | **`+0x8`** |

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

+  - /System/Library/PrivateFrameworks/IMCore.framework/IMCore

+  - /System/Library/PrivateFrameworks/ShareReporting.framework/ShareReporting

-  Functions: 14522
-  Symbols:   3240
-  CStrings:  8488
+  Functions: 15151
+  Symbols:   3289
+  CStrings:  8538
Symbols:
+ _BlastDoorInstanceTypeLockDownMode
+ _CFPhoneNumberGetITUCountryCodeForISOCountryCode
+ _IMAssertNotRunningInUnitTesting
+ _IMChatVocabularyUpdaterDefinesDomain
+ _IMChatVocabularyUpdaterDidPerformInitialUpdateKey
+ _IMDCreateIMItemFromIMDMessageRecordRefCopyAttachmentsIfNeededWithAccountLookupAndBatchResult
+ _IMDIsValidPhoneNumber
+ _IMDRelayMessageItemDictionaryReplicatedFallbackGUIDs
+ _IMGetDarwinCFNotificationCenter
+ _IMGetDarwinNotificationCenter
+ _IMGetDefaultNotificationCenter
+ _IMGetDistributedCFNotificationCenter
+ _IMGetDistributedNotificationCenter
+ _IMMetricsCollectorEventCriticalMessagingApprovedCountKey
+ _IMMetricsCollectorEventCriticalMessagingAuthorizationResult
+ _IMMetricsCollectorEventCriticalMessagingDeniedCountKey
+ _IMMetricsCollectorEventCriticalMessagingFailureReasonKey
+ _IMMetricsCollectorEventCriticalMessagingRecipientCountKey
+ _IMMetricsCollectorEventCriticalMessagingSendRequested
+ _IMMetricsCollectorEventCriticalMessagingSendResult
+ _IMMetricsCollectorEventCriticalMessagingSendSuccessKey
+ _IMMetricsCollectorEventCriticalMessagingValidationFailure
+ _OBJC_CLASS_$_IMCloudKitShareURLProcessingComponent
+ _OBJC_CLASS_$_IMDAccountControllerDependencyProvider
+ _OBJC_CLASS_$_IMDAttachmentDownloadPolicyFilter
+ _OBJC_CLASS_$_IMDAttachmentStoreDependencyProvider
+ _OBJC_CLASS_$_IMDBulkChatHistoryQueryHandler
+ _OBJC_CLASS_$_IMDBulkChatHistoryQueryHandlerDependencyProvider
+ _OBJC_CLASS_$_IMDChatDependencyProvider
+ _OBJC_CLASS_$_IMDChatForkMerger
+ _OBJC_CLASS_$_IMDChatRegistryDependencyProvider
+ _OBJC_CLASS_$_IMDChatStoreDependencyProvider
+ _OBJC_CLASS_$_IMDFileTransferCenterDependencyProvider
+ _OBJC_CLASS_$_IMDFilteringControllerDependencyProvider
+ _OBJC_CLASS_$_IMDIncomingRecipientCanonicalization
+ _OBJC_CLASS_$_IMDMessageStoreDependencyProvider
+ _OBJC_CLASS_$_IMDNoEligibleDestinationsCache
+ _OBJC_CLASS_$_IMDPersistentTaskBulkSchedulingContext
+ _OBJC_CLASS_$_IMDRetryReasonCache
+ _OBJC_CLASS_$_IMDServiceControllerDependencyProvider
+ _OBJC_CLASS_$_IMDServiceSessionDependencyProvider
+ _OBJC_CLASS_$_IMDSpamMessageCreatorDependencyProvider
+ _OBJC_CLASS_$_IMMessagePartUtilities
+ _OBJC_METACLASS_$_IMCloudKitShareURLProcessingComponent
+ _OBJC_METACLASS_$_IMDAccountControllerDependencyProvider
+ _OBJC_METACLASS_$_IMDAttachmentDownloadPolicyFilter
+ _OBJC_METACLASS_$_IMDAttachmentStoreDependencyProvider
+ _OBJC_METACLASS_$_IMDBulkChatHistoryQueryHandler
+ _OBJC_METACLASS_$_IMDBulkChatHistoryQueryHandlerDependencyProvider
+ _OBJC_METACLASS_$_IMDChatDependencyProvider
+ _OBJC_METACLASS_$_IMDChatForkMerger
+ _OBJC_METACLASS_$_IMDChatRegistryDependencyProvider
+ _OBJC_METACLASS_$_IMDChatStoreDependencyProvider
+ _OBJC_METACLASS_$_IMDFileTransferCenterDependencyProvider
+ _OBJC_METACLASS_$_IMDFilteringControllerDependencyProvider
+ _OBJC_METACLASS_$_IMDIncomingRecipientCanonicalization
+ _OBJC_METACLASS_$_IMDMessageStoreDependencyProvider
+ _OBJC_METACLASS_$_IMDNoEligibleDestinationsCache
+ _OBJC_METACLASS_$_IMDRetryReasonCache
+ _OBJC_METACLASS_$_IMDServiceControllerDependencyProvider
+ _OBJC_METACLASS_$_IMDServiceSessionDependencyProvider
+ _OBJC_METACLASS_$_IMDSpamMessageCreatorDependencyProvider
+ _PNCopyBestGuessCountryCodeForNumber
+ _UNNotificationDefaultActionIdentifier
+ _dlopen
+ _object_getClassName
- _CFPreferencesSetAppValue
- _CFPreferencesSetMultiple
- _IMDAttachmentRecordRefFromIMFileTransfer
- _IMDCreateIMItemFromIMDMessageRecordRefCopyAttachmentsIfNeededWithAccountLookup
- _IMDCreateIMMessageItemFromIMDMessageRecordLoadAttachmentIfNeededRef
- _IMDCreateIMMessageItemFromIMDMessageRecordRef
- _IMDUpdateIMFileTransferFromIMFileTransfer
- _IMDidPerformInitialChatVocabularyUpdate
- _IMEnableSingletonTestAssertions
- _IMGetAppBoolForKey
- _IMMetricsCollectorEventAskToMessageReceivedByContact
- _IMMetricsCollectorEventAskToSenderValidationFamilyPhoneNumberAvailability
- _IMSetHavePerformedInitialChatVocabularyUpdate
- _OBJC_CLASS_$_CKDatabase
- _OBJC_METACLASS_$_CKDatabase
- __CFPreferencesFlushCachesForIdentifier
- _notify_cancel
CStrings:
+ "\t"
+ "      ** Handle does not fit any country's numbering plan as an international number, leaving it as-is"
+ "      ** Handle reads as a NANP number on a non-NANP receiver, which is ambiguous. Leaving it as-is"
+ "      ** Reinterpreted as an international number in %@"
+ "   Stored message has transfers %@ but we were asked for %@, re-downloading."
+ "%s: callerID %@ guid %@ service %@ -> relay instead of telephony: %{BOOL}d (%@)"
+ "%s: not applicable for service %@"
+ "-[IMDServiceSession initWithAccount:service:replicatingForSession:]"
+ "-[IMDTelephonyServiceSession _shouldRelaySMSForQuickSwitchForCallerID:messageGUID:]"
+ "/System/Library/PrivateFrameworks/ShareReporting.framework/ShareReporting"
+ "<IMDeferAttachmentPreviewPipelineComponent> A blocking transfer has a gradient on message %@, will defer"
+ "<IMDeferAttachmentPreviewPipelineComponent> No blocking transfers have a gradient on message %@, will not defer"
+ "AskTo answer choice send completion called. Error: %@"
+ "AskTo message is from a contact. No sender validation required."
+ "AskTo message is not from a contact. Falling back to Family relation validation."
+ "Associated message item %@ refers to itself via %@. Refusing to delete the message being edited."
+ "Can't respond to action identifier %@ because the AskTo metadata is incomplete"
+ "Cannot update Spotlight for blocklist change; nil pTaskQueryProvider."
+ "Clearing %ld/%ld recoverable message tombstones"
+ "Clearing rowid %lld for %s"
+ "CloudKitShareJunkReporting"
+ "Could not derive From Display ID for chat, from %{private}@ to %{private}@ participant count %lu countMinusMe %lu isGroup %{BOOL}d (groupID %@ groupName %@) hasV1Data %{BOOL}d QOI %{BOOL}d.\nParticipants: %{private}@"
+ "Couldn't find ROWID for recordName %s %s"
+ "Couldn't find local unsynced_removed_recoverable_messages row to delete, for reflected cloudkit record %@"
+ "Failed to create a Message Dictionary from the IM Message, cannot hand off %@ to be sent"
+ "Failed to get nickname record because we are missing recordName (%@). preKeyData.length > 0: (%@)"
+ "File does not exist at path"
+ "File exists at path"
+ "IMDBackwardCompatibilityMessageIdentifier.sharedIdentifier"
+ "IMDCKChatSyncController.sharedInstance"
+ "IMDCKUtilities.sharedInstance"
+ "IMDEmergencyContactsManager.sharedManager"
+ "IMDFamilyManager.sharedManager"
+ "IMDServiceSession fell back to live dependencies under test. account=%@ (%@), accountDependencies=%@"
+ "IMDServiceSession.m"
+ "IMDSpamFilteringHelper.sharedHelper"
+ "IMDaemonCore_Internal.IMDMutedChatListRebuilder"
+ "IMDaemonCore_Private.IMDAttachmentDownloadPolicyFilter"
+ "InternalPayload"
+ "Message %@ came back on %@ but our copy is on %@, carrying the downgrade over"
+ "Messages in iCloud is already %@; reconciling the iCloud Settings switch instead of changing state"
+ "Muted state inconsistency detected among merged chats. Muting %lu additional identifier(s) until %@"
+ "Nickname reconstructed from dictionary is missing handle ID. Assigning: %@"
+ "No record ID for nickname %@, skipping active list update"
+ "No user notification center available, TTR will not proceed"
+ "Not handing off %@ to be sent, messages with attachments are not supported on this path"
+ "Not responding to action identifier %@"
+ "Not routing message %@ — blocked pending unresolved CommSafety decision"
+ "Passive device with selective delivery for callerID %@: handed locally-composed outgoing SMS %@ to the device for that caller ID: %{BOOL}d"
+ "Passive device with selective delivery for callerID %@: handing outgoing SMS %@ back to be sent by the device for that caller ID"
+ "Passive device with selective delivery for callerID %@: overriding sending decision to relay (now %x) for guid %@"
+ "Payload capture: command %ld guid %@ replay --from-id token:%@/%@"
+ "Push of read state marked %ld message guids in chat %s as read: %s"
+ "Received a name only update but no information was provided"
+ "Recently Deleted | Message %@ cannot be found, skipping part update."
+ "Recipient handle %@ is not a valid national number for the receiving country code %@. Reinterpreting it as an international number."
+ "Refusing to enable Messages in iCloud: the account is not eligible for the truth zone (account status %@)"
+ "Refusing to enable Messages in iCloud: the iCloud and iMessage accounts do not match"
+ "Relayed outgoing send request for %@ to the device for callerID %@: %{BOOL}d"
+ "Responding with AskTo answer choice identifier %@"
+ "Scheduling Spotlight walk for a blocklist change."
+ "Sending device requested no persistence for message %@, but we already sent it on %@, not sending again"
+ "Successfully fetched FamilyCircle"
+ "Transfer does not have a localURL, File does not exist"
+ "Unable to apply edits, message with GUID=%@ is an associated message and cannot be edited or retracted"
+ "We attempted to download attachments for a fixed number of chat identifiers but there were no transfers needing download."
+ "[%{public}s] DAS resumed us but the handle is already %{public}s — abandoning resume instead of running a batch on a dead handle"
+ "[%{public}s] failed to acknowledge expiration that preceded our resume: %@"
+ "[%{public}s] task yielded to cancellation, leaving it queued to resume"
+ "[CloudKitShareReport] Found %ld CloudKit share URLs in junk report"
+ "[CloudKitShareReport] Included %ld share reports in TrustKit junk report"
+ "[CloudKitShareReport] Submitted remaining share report data"
+ "[CloudKitShareURLProcessing] No sender identifier on message; skipping CloudKit share registration"
+ "[CloudKitShareURLProcessing] Registered CloudKit share URL with ShareReporting"
+ "[CloudKitShareURLProcessing] Registering %ld CloudKit share URLs from unknown sender with ShareReporting"
+ "[CloudKitShareURLProcessing] ShareReporting fetch failed: %@"
+ "[CloudKitShareURLProcessing] ShareReporting register failed: %@"
+ "[CloudKitShareURLProcessing] ShareReporting shouldReport failed: %@"
+ "[CloudKitShareURLProcessing] ShareReporting submit failed: %@"
+ "[CloudKitShareURLProcessing] Unable to convert input into IMCloudKitShareURLProcessingParameter. Bailing and passing input to next pipeline"
+ "bulk history query"
+ "bulk history query timing (%d queries): %@"
+ "didFamilyFetchSucceed"
+ "mergeGroupForks failed: %@"
+ "rfgs"
+ "senderHandleType"
+ "share-report-info"
+ "v16@?0@\"IMDBulkChatHistoryQueryResult\"8"
+ "\x91"
- "%@ Error deleting from MOCK store %@ "
- "%@ Error reading from MOCK store %@ "
- "%@/%@"
- "%s No broadcaster for messages with GUIDs %s"
- "%s: Unable to archive record %@, error %@"
- "+[IMDBadgeUtilities sharedInstance]_block_invoke"
- "+[IMDMessageStore sharedInstance]_block_invoke"
- "-[IMDCKMockRecordZone _serializedCKRecordData:]"
- "/var/mobile/Library/SMS/CloudKitMockStore/"
- "About to give back %@ records moreComing %@ fetchAllChanges %@"
- "Adding operation %@"
- "Adding random delay of %@ seconds"
- "AskTo message is not from a known sender. Falling back to Family relation validation."
- "Clearing recoverable message tombstones for recordIDs: %s"
- "Could not derive From Display ID for chat identification"
- "Did not find mock database for operation %@ zoneID %@"
- "Dispatching operation %@"
- "Error persisting record %@ error %@"
- "Failed to unarchive mock ck record data. Error: %@"
- "Finished repairing a batch of duplicate chats"
- "ID %@ MOCK Handling fetchRecordZoneChangesOperation"
- "ID %@ MOCK Handling modifyRecordsOperation"
- "IMDBadgeUtilities.m"
- "IMDCKMockDatabase"
- "IMDCKMockRecordKeyZone"
- "IMDCKMockRecordZone"
- "Introducing random error %@"
- "Message is from a contact. No AskTo sender validation required."
- "Mock Handle operation %@ identifier %@"
- "Mock fetching exit record"
- "Mocking writing up Cloudkit metrics"
- "Push of read state marked message guids in chat %s as read: %s"
- "Received a Family message from a phone number and Family server contained no phone numbers to compare against"
- "Received a name only update but no information were provided"
- "ServiceProperties"
- "Successfully persisted record %@ "
- "forbidden singleton called within a unit test"
- "handleOperation : %@"
- "recordKeyZone"
```
