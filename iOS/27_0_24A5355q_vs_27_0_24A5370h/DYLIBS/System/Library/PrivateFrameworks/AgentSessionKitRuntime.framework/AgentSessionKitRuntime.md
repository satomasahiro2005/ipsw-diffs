## AgentSessionKitRuntime

> `/System/Library/PrivateFrameworks/AgentSessionKitRuntime.framework/AgentSessionKitRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17e924` | `0x1b8580` | **`+0x39c5c`** |
| `__TEXT.__const` | `0xf1bc` | `0x131dc` | **`+0x4020`** |
| `__DATA.__bss` | `0xb850` | `0xe9b0` | **`+0x3160`** |
| `__AUTH_CONST.__objc_const` | `0x5640` | `0x71c8` | **`+0x1b88`** |
| `__TEXT.__eh_frame` | `0xe0a0` | `0xf320` | **`+0x1280`** |
| `__AUTH.__data` | `0x3308` | `0x42a8` | **`+0xfa0`** |
| `__TEXT.__swift5_reflstr` | `0x3491` | `0x4291` | **`+0xe00`** |
| `__TEXT.__unwind_info` | `0x6518` | `0x72b8` | **`+0xda0`** |
| `__TEXT.__swift5_typeref` | `0x50c1` | `0x5cd9` | **`+0xc18`** |
| `__TEXT.__swift5_fieldmd` | `0x2d40` | `0x3888` | **`+0xb48`** |
| `__AUTH_CONST.__const` | `0x67c8` | `0x7210` | **`+0xa48`** |
| `__DATA.__data` | `0x3280` | `0x3a58` | **`+0x7d8`** |
| `__TEXT.__constg_swiftt` | `0x2434` | `0x2bec` | **`+0x7b8`** |
| `__TEXT.__oslogstring` | `0x721c` | `0x790c` | **`+0x6f0`** |
| `__AUTH.__objc_data` | `0xd00` | `0x1200` | **`+0x500`** |
| `__TEXT.__swift5_assocty` | `0x898` | `0xbb0` | **`+0x318`** |
| `__TEXT.__swift5_capture` | `0x2008` | `0x21f4` | **`+0x1ec`** |
| `__AUTH_CONST.__auth_got` | `0x21c8` | `0x2370` | **`+0x1a8`** |
| `__TEXT.__swift5_proto` | `0x59c` | `0x6f8` | **`+0x15c`** |
| `__TEXT.__swift5_types` | `0x27c` | `0x314` | **`+0x98`** |
| `__DATA_CONST.__got` | `0x1250` | `0x12d0` | **`+0x80`** |
| `__DATA_CONST.__objc_classlist` | `0x1c8` | `0x248` | **`+0x80`** |
| `__DATA.__common` | `0xe0` | `0x148` | **`+0x68`** |
| `__TEXT.__swift_as_cont` | `0x758` | `0x6f0` | **`-0x68`** |
| `__TEXT.__cstring` | `0x1d4e` | `0x1dae` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x770` | `0x738` | **`-0x38`** |
| `__DATA_DIRTY.__data` | `0x13c8` | `0x13f8` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x2b4` | `0x290` | **`-0x24`** |
| `__TEXT.__objc_methlist` | `0x68c` | `0x69c` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x2c4` | `0x2b8` | **`-0xc`** |

### Other Changes

```diff

-279.0.15.0.0
-  - /System/Library/Frameworks/Accounts.framework/Accounts
+284.0.7.0.0

-  Functions: 9840
+  Functions: 11710

-  CStrings:  634
+  CStrings:  661
Symbols:
+ _OBJC_CLASS_$_PHPhotoLibrary
+ _exp2
+ _objc_release_x10
+ _objc_retain_x9
+ _swift_release_x11
+ _swift_task_future_wait_throwing
- _ACAccountDataclassSiri
- _OBJC_CLASS_$_ACAccountStore
- _OBJC_CLASS_$_CKModifyRecordZonesOperation
- _OBJC_CLASS_$_NSLock
- _OBJC_CLASS_$_NSNotificationCenter
- _OBJC_CLASS_$_PHPhotoLibraryAttributesChangeRequest
CStrings:
+ "%{public}s: deleted %{public}ld zones"
+ "%{public}s: deleting %{public}ld zones"
+ "%{public}s: no zones to delete"
+ "AgentSessionStore.sqlite_EXTERNAL_DATA"
+ "Disabled iCPL sync and deleted all assets in agent media photo library"
+ "Failed to delete "
+ "OwnedFileStore.deleteAllFiles: directory already absent: %s"
+ "OwnedFileStore.writeFromURL: identical file already present for artifact %{public}s, skipping copy"
+ "OwnedFileStore.writeFromURL: replacing divergent owned file for artifact %{public}s"
+ "artifact added %{public}s session=%{public}s assetBacked=true"
+ "backfill: %{public}ld persistable session(s) missing sync metadata"
+ "backfill: failed to enumerate sessions missing sync metadata: %@"
+ "cleanupSyncState: Deleted %ld %s zones"
+ "cleanupSyncState: Failed to delete %s zones: %@"
+ "coalescedSend failed: %@"
+ "deleteAllLegacyZones"
+ "deleteAllSessionZones"
+ "device-ID refresh after account change failed (keeping current site identifier): %@"
+ "drain: applying %{public}ld pending markers to engine"
+ "drain: failed to load/stamp pending markers: %@"
+ "failed to clear confirmed pending-sync markers: %@"
+ "failed to re-arm quota-failed pending-sync markers: %@"
+ "failed to set persistence TTL: %@"
+ "fetchDeferredArtifactContent: Failed for %{public}s: %@"
+ "generator init attempt failed: %@. next trigger will retry."
+ "getting size report"
+ "handleFetchedDatabaseChanges: zone deletion session=%{public}s reason=%{public}s"
+ "handleFetchedRecordZoneChanges: ignoring artifact record deletion %{public}s — artifact removal is handled by the delta merge"
+ "handleFetchedRecordZoneChanges: ignoring session record deletion during initial post-signIn fetch %{public}s"
+ "handleFetchedRecordZoneChanges: ignoring unrecognized record deletion %{public}s"
+ "handleSentDatabaseChanges: failed to delete zone %{public}s: %{public}@"
+ "handleSentDatabaseChanges: failed to save zone %{public}s: %{public}@"
+ "handleSentRecordZoneChanges: dropping artifact conflict (already on server) %{public}@"
+ "handleSentRecordZoneChanges: resurrect failed for %{public}s: %@"
+ "handleSentRecordZoneChanges: zone not found for record %{public}@; resurrecting"
+ "initial zone discovery deferred: %@"
+ "isAssetBacked: assetRecordName nil but cloudKitAssetIdentifier set for artifact %{public}s"
+ "nextRecordZoneChangeBatch: quota hold-off active, skipping"
+ "openLibrary(with:using:)"
+ "operationTypeRaw"
+ "processIncomingSessionRecord: failed to merge server into empty record value session=%{public}s: %{public}@"
+ "processIncomingSessionRecord: value ID mismatch session=%{public}s; discarding local mergeable"
+ "quota exceeded — holding off sends for %{public}fs (backoff level %{public}ld)"
+ "quota hold-off expired"
+ "quota hold-off reset"
+ "recordMarker: unrecognized record ID %{public}@"
+ "removePendingSyncChanges: removed %{public}ld pending changes for session %{public}s"
+ "reset timestamp generator site identifier after account change"
+ "setDisableSyncModeDeleteAllAssets()"
+ "startup: failed to reset pending-sync pushedAt: %@"
+ "sync engine init failed: %@. next trigger will retry."
+ "sync engine ready"
+ "timestamp generator ready"
+ "v20ToV21.didMigrate: backfilled assetRecordName for %{public}ld/%{public}ld artifacts"
- "ACAccountStoreDidChangeNotification"
- "Failed to create session zone for "
- "Failed to delete remote zones: "
- "Failed to set cloud sync on agent media photo library: %@"
- "Set cloud sync to %{bool}d on agent media photo library"
- "applyLegacyRemoteDeleteIntent: session=%{public}s"
- "applyToDatabase: legacy deletedAt detected for session %{public}s; deferring to coordinator for hard-delete + zone deletion"
- "artifact added %{public}s session=%{public}s"
- "async initialization complete"
- "cleanupSyncState: Deleted %ld remote zones"
- "cleanupSyncState: Failed to delete remote zones: %@"
- "createSessionZone(sessionId:)"
- "deleteAllSessionZones: deleted %{public}ld session zones"
- "deleteAllSessionZones: deleting %{public}ld session zones"
- "deleteAllSessionZones: fetching all zones from CloudKit"
- "deleteAllSessionZones: found %{public}ld total zones"
- "deleteAllSessionZones: no session zones to delete"
- "drainPendingMigrationZoneDeletions: enqueueing %{public}ld zone deletions from V16→V17 migration"
- "failed to delete expired sessions: %@"
- "fetchDeferredArtifactContent: Failed for %s: %s"
- "handleSentRecordZoneChanges: artifact record saved %{public}s"
- "handleSentRecordZoneChanges: session %{public}s modified during send, re-queuing"
- "handleSentRecordZoneChanges: zone not found for record %{public}@"
- "inital zone discovery deferred: %@"
- "processIncomingSessionRecord: failed to merge server into empty record value: %@"
- "sync init attempt failed: %@. next trigger will retry."
- "sync init complete"
```
