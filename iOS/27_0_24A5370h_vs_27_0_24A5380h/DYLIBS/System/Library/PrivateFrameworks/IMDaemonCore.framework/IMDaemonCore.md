## IMDaemonCore

> `/System/Library/PrivateFrameworks/IMDaemonCore.framework/IMDaemonCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ae8e0` | `0x3b5258` | **`+0x6978`** |
| `__DATA_DIRTY.__objc_data` | `0x32e8` | `0x3d68` | **`+0xa80`** |
| `__AUTH.__objc_data` | `0x3ad8` | `0x30c0` | **`-0xa18`** |
| `__DATA_DIRTY.__data` | `0x2fb8` | `0x36f8` | **`+0x740`** |
| `__DATA_DIRTY.__bss` | `0x22d0` | `0x2940` | **`+0x670`** |
| `__DATA.__bss` | `0x57d0` | `0x5170` | **`-0x660`** |
| `__TEXT.__oslogstring` | `0x54617` | `0x54c17` | **`+0x600`** |
| `__AUTH.__data` | `0x9e0` | `0x6d8` | **`-0x308`** |
| `__AUTH_CONST.__const` | `0xa000` | `0xa2d8` | **`+0x2d8`** |
| `__DATA.__data` | `0x68a8` | `0x6618` | **`-0x290`** |
| `__TEXT.__eh_frame` | `0x9a70` | `0x9c1c` | **`+0x1ac`** |
| `__AUTH_CONST.__objc_const` | `0x237e8` | `0x23970` | **`+0x188`** |
| `__TEXT.__swift5_typeref` | `0x3b52` | `0x3cb0` | **`+0x15e`** |
| `__TEXT.__const` | `0x7ef8` | `0x8018` | **`+0x120`** |
| `__TEXT.__constg_swiftt` | `0x2a0c` | `0x2b08` | **`+0xfc`** |
| `__TEXT.__cstring` | `0x144dc` | `0x145bc` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x1b3f4` | `0x1b4cc` | **`+0xd8`** |
| `__DATA_CONST.__objc_selrefs` | `0x10d30` | `0x10df0` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0xdf38` | `0xdff8` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x1b78` | `0x1c10` | **`+0x98`** |
| `__TEXT.__swift5_capture` | `0x1be8` | `0x1c7c` | **`+0x94`** |
| `__TEXT.__gcc_except_tab` | `0x1f640` | `0x1f6c0` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x189f` | `0x18ef` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x37a0` | `0x37e8` | **`+0x48`** |
| `__DATA.__common` | `0x1b0` | `0x178` | **`-0x38`** |
| `__DATA_DIRTY.__common` | `0x1e0` | `0x218` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x8a4` | `0x8d0` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x6c48` | `0x6c70` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x170` | `0x198` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x2ef8` | `0x2f10` | **`+0x18`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x1e0` | `0x1f8` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x920` | `0x938` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x21c` | `0x208` | **`-0x14`** |
| `__TEXT.__swift5_proto` | `0x3bc` | `0x3c8` | **`+0xc`** |
| `__TEXT.__swift5_protos` | `0x38` | `0x44` | **`+0xc`** |
| `__DATA_CONST.__objc_catlist` | `0xf0` | `0xe8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xa50` | `0xa58` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x348` | `0x350` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x270` | `0x274` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x3d0` | `0x3cc` | **`-0x4`** |

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  Functions: 14461
-  Symbols:   3249
-  CStrings:  8501
+  Functions: 14537
+  Symbols:   3258
+  CStrings:  8524
Symbols:
+ _IMContactUtilitiesDisplayNameKey
+ _IMContactUtilitiesShortNameKey
+ _IMDCNDisplayNameAndShortNameForHandleID
+ _IMDMessageRecordCloudKitStatisticServerCountsKey
+ _IMMessageCreateThreadIdentifierWithOriginatorGUID
+ _IMSharedBalloonPreviewSummaryForCustomAcknowledgementMessageWithSenderMap
+ _IMSharedBalloonPreviewSummaryForPollAddChoiceMessageWithSenderMap
+ _OBJC_CLASS_$_IMDBackgroundProgressNotificationContent
+ _OBJC_CLASS_$_IMMessagePartGUID
+ _OBJC_CLASS_$_UNNotificationSound
+ _OBJC_METACLASS_$_IMDBackgroundProgressNotificationContent
+ _swift_retain_x10
+ _swift_retain_x3
- _IMSharedBalloonPreviewSummaryForCustomAcknowledgementMessage
- _IMSharedBalloonPreviewSummaryForPollAddChoiceMessage
- _objc_retain_x11
- _swift_retain_x11
CStrings:
+ "     ==> Best candidate group chat %@ failed sender verification: fromIdentifier %@ is not in the chat's participant set %@. Rejecting the chat."
+ "     ==> Best candidate group chat %@ is a known chat, proceeding with further validation if necessary. isFiltered %lld numberOfTimesRespondedToThread %lld"
+ "     ==> Best candidate group chat %@ is a placeholder chat, rejecting the chat."
+ "     ==> Best candidate group chat %@ is an unknown chat, rejecting the chat. isFiltered %lld numberOfTimesRespondedToThread %lld"
+ "     ==> Best candidate group chat %@ is not a placeholder chat, proceeding with further validation if necessary."
+ "     ==> fromIdentifier is a participant in the best candidate group chat %@, proceeding with further validation if necessary."
+ " ==> Requested to only accept known chats."
+ " ==> Requested to only accept non placeholder chats."
+ " ==> Validating that the from identifier %@ is a participant in the best candidate group chat %@."
+ "%{public}s notifications for %{public}s"
+ "<IMDeferAttachmentPreviewPipelineComponent> Allowing instant delivery of message %@, skip is set"
+ "Clearing recoverable message tombstones for recordIDs: %s"
+ "Could not store %ld reparentable messages: %@"
+ "Error while checking if any reparentable messages exist: %@"
+ "Exhausted reprocess attempts (%lu) for message %@; last error %@."
+ "Failed to post notification for %{public}s: %@"
+ "IMDaemonCore.IMDBackgroundProgressNotificationContent"
+ "Missing localized string for key 'USER_NOTIFICATION_PHOTOS_TAB_DOWNLOAD_FAILURE_DESCRIPTION'"
+ "Missing localized string for key 'USER_NOTIFICATION_PHOTOS_TAB_DOWNLOAD_FAILURE_TITLE'"
+ "No reparentable messages found."
+ "Posted user notification for %{public}s"
+ "Restored persisted sync statistics from defaults on launch (%lu local keys, %lu server zones)."
+ "Server.LiveRecords.%@"
+ "Server.TotalRecords.%@"
+ "Starting message pipeline."
+ "USER_NOTIFICATION_PHOTOS_TAB_DOWNLOAD_FAILURE_DESCRIPTION"
+ "USER_NOTIFICATION_PHOTOS_TAB_DOWNLOAD_FAILURE_TITLE"
+ "backgroundProgress:"
+ "fetchAttachmentDataForTransferGUIDs count %lu HQ %@"
+ "fileURLs returned "
+ "flushPendingFileURLRequests: chunk completed in %{public}.*fs — %{public}ld results for %{public}ld identifiers"
+ "flushPendingFileURLRequests: chunk failed in %{public}.*fs — error: %@"
+ "flushPendingFileURLRequests: chunk result count %{public}ld != identifier count %{public}ld"
+ "live_records"
+ "total_records"
- "<IMDeferAttachmentPreviewPipelineComponent> Allowing instant delivery of message %@, skipDeferral is set"
- "Clearing %ld/%ld recoverable message tombstones"
- "Clearing rowid %lld for %s"
- "Couldn't find ROWID for recordName %s %s"
- "Couldn't find local unsynced_removed_recoverable_messages row to delete, for reflected cloudkit record %@"
- "MiC.DASCheckpointBalancedVersion"
- "MiC.SyncResumeBatchProgress"
- "MiC.SyncResumeCompletedStepIndex"
- "MiC.SyncResumePhase"
- "fetchAttachmentDataForTransferGUIDs %@ HQ %@"
- "flushPendingFileURLRequests: batch completed in %{public}.*fs — %{public}ld results for %{public}ld identifiers"
- "flushPendingFileURLRequests: batch failed in %{public}.*fs — error: %@"
```
