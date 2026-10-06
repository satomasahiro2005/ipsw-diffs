## AgentSessionKitRuntime

> `/System/Library/PrivateFrameworks/AgentSessionKitRuntime.framework/AgentSessionKitRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x205ad4` | `0x263bf8` | **`+0x5e124`** |
| `__TEXT.__const` | `0x19a8c` | `0x2101c` | **`+0x7590`** |
| `__DATA.__bss` | `0x105c0` | `0x16390` | **`+0x5dd0`** |
| `__TEXT.__eh_frame` | `0x11cf8` | `0x15620` | **`+0x3928`** |
| `__AUTH_CONST.__objc_const` | `0xa2f0` | `0xd530` | **`+0x3240`** |
| `__TEXT.__unwind_info` | `0x9458` | `0xb2a8` | **`+0x1e50`** |
| `__AUTH.__data` | `0x47b0` | `0x6548` | **`+0x1d98`** |
| `__TEXT.__swift5_reflstr` | `0x5d91` | `0x792a` | **`+0x1b99`** |
| `__TEXT.__oslogstring` | `0x801c` | `0x9623` | **`+0x1607`** |
| `__TEXT.__swift5_fieldmd` | `0x4bdc` | `0x60b8` | **`+0x14dc`** |
| `__TEXT.__swift5_typeref` | `0x7215` | `0x86df` | **`+0x14ca`** |
| `__DATA.__data` | `0x3760` | `0x4618` | **`+0xeb8`** |
| `__TEXT.__constg_swiftt` | `0x3900` | `0x47b4` | **`+0xeb4`** |
| `__AUTH.__objc_data` | `0x1700` | `0x2010` | **`+0x910`** |
| `__AUTH_CONST.__const` | `0x83c0` | `0x8be0` | **`+0x820`** |
| `__TEXT.__swift5_assocty` | `0x10c0` | `0x1630` | **`+0x570`** |
| `__TEXT.__swift5_proto` | `0x92c` | `0xbcc` | **`+0x2a0`** |
| `__TEXT.__cstring` | `0x200e` | `0x228e` | **`+0x280`** |
| `__AUTH_CONST.__auth_got` | `0x2478` | `0x25d8` | **`+0x160`** |
| `__DATA_CONST.__got` | `0x13b8` | `0x14d8` | **`+0x120`** |
| `__TEXT.__swift5_types` | `0x404` | `0x518` | **`+0x114`** |
| `__DATA.__common` | `0x120` | `0x230` | **`+0x110`** |
| `__TEXT.__swift_as_cont` | `0x77c` | `0x87c` | **`+0x100`** |
| `__DATA_CONST.__objc_classlist` | `0x338` | `0x420` | **`+0xe8`** |
| `__TEXT.__swift_as_ret` | `0x2b4` | `0x358` | **`+0xa4`** |
| `__DATA_DIRTY.__data` | `0x3d18` | `0x3d98` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x270c` | `0x26a0` | **`-0x6c`** |
| `__TEXT.__swift_as_entry` | `0x2e8` | `0x354` | **`+0x6c`** |
| `__TEXT.__objc_methlist` | `0x6e4` | `0x720` | **`+0x3c`** |
| `__DATA_CONST.__objc_selrefs` | `0x7d8` | `0x808` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x140` | `0x150` | **`+0x10`** |
| `__DATA_DIRTY.__common` | `0x108` | `0x100` | **`-0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x5c8` | `0x5d0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x28` | `0x2c` | **`+0x4`** |

### Other Changes

```diff

-291.1.0.5.0
+291.6.0.5.101

+  - /System/Library/PrivateFrameworks/AuthKit.framework/AuthKit

+  - /System/Library/PrivateFrameworks/MobileStoreDemoKit.framework/MobileStoreDemoKit

-  Functions: 14596
-  Symbols:   303
-  CStrings:  704
+  Functions: 17776
+  Symbols:   315
+  CStrings:  788
Symbols:
+ _OBJC_CLASS_$_AKAccountManager
+ _OBJC_CLASS_$_MSDKDemoState
+ __objc_autoreleasePoolPop
+ __objc_autoreleasePoolPush
+ _objc_retain_x10
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_getEnumCaseMultiPayload
+ _swift_getTupleTypeMetadata2
+ _swift_getTupleTypeMetadata3
+ _swift_retain_x9
+ _swift_storeEnumTagMultiPayload
+ _swift_unknownObjectRetain_n
- _objc_release_x10
- _objc_retain_x9
CStrings:
+ ".capture_metadata"
+ "/var/mobile/Library/AgentSessionKitBackupStaging"
+ "BackupStagingManager: .migration_done absent/unreadable in staging %s; treating as captured (re-import eligible)"
+ "BackupStagingManager: .migration_done has unrecognized value \"%s\" in staging %s; treating as captured (re-import eligible)"
+ "BackupStagingManager: captured %ld entries into staging via capture-to-staging-folder"
+ "BackupStagingManager: press-demo gate rejected import; leaving staging intact for retry"
+ "BackupStagingManager: source device; skipping staging import"
+ "BackupStagingManager: staging import failed: %@"
+ "Cascade ledger: failed to apply confirmation for %{public}s: %@"
+ "Cascade ledger: seed failed for event %{public}s: %@"
+ "Cascade ledger: seed failed for session %{public}s: %@"
+ "Cascade ledger: unknown itemKind %{public}s for %{public}s; skipping"
+ "InternalDaemonDataContainer: backup staging skipped: %@"
+ "MaintenanceTask: Cascade donations are consistent"
+ "MaintenanceTask: Cascade reconcile candidates — %{public}ld undonated sessions, %{public}ld undonated events, %{public}ld session orphans"
+ "MaintenanceTask: Cascade reconcile starting (maxItems=%{public}ld)"
+ "MaintenanceTask: event orphan scan failed: %@"
+ "MaintenanceTask: failed to fetch undonated events: %@"
+ "MaintenanceTask: failed to hydrate %{public}ld events for reconcile: %@"
+ "MaintenanceTask: failed to hydrate %{public}ld sessions for reconcile: %@"
+ "MaintenanceTask: failed to load Cascade bookkeeping: %@"
+ "MaintenanceTask: failed to scan sessions: %@"
+ "MaintenanceTask: reconciled %{public}ld sessions, %{public}ld events; %{public}ld items remain (cancelled=%{bool,public}d)"
+ "MaintenanceTask: removing %{public}ld orphaned Cascade items (%{public}ld deferred to next run)"
+ "MaintenanceTask: skipping artifact %{public}s hydrate failed: %@"
+ "Manatee identity loss detected (trigger=%{public}s) but no local session data to rebuild from; skipping zone-wipe recovery and leaving %{public}ld server-only zone(s) intact"
+ "Manatee identity loss detected (trigger=%{public}s); entering zone-wipe recovery for %{public}ld zone(s) with local data, leaving %{public}ld server-only zone(s) intact"
+ "Nothing to capture: the live AgentSessionKit store directory is empty."
+ "PressDemoModeGate: MSDKDemoState.isSecureDemoModeEnabled threw: %@"
+ "PressDemoModeGate: forced eligible via internal test override"
+ "SwiftData.Schema.Unique"
+ "applyChildEntries session=%{public}s persistable=%{public}s events=%{public}ld artifacts=%{public}ld"
+ "applyTimeShift: shifted %ld sessions, %ld events, %ld artifacts by %fs"
+ "artifact.apply id=%{public}s event=%{public}s kind=%{public}s session=%{public}s incomingState=%{public}hhu"
+ "artifact.created id=%{public}s session=%{public}s eventId=%{public}s"
+ "artifact.existing id=%{public}s session=%{public}s eventId=%{public}s"
+ "artifact.tombstoned id=%{public}s convergedState=%{public}hhu"
+ "attemptedRecoveryDate"
+ "awaitFirstUnlock()"
+ "beginRecoveryIfEligible: %{public}s throttled; last attempt %{public}fs ago (< %{public}fs)"
+ "beginZoneRecovery: enqueued zone deletion for %{public}s"
+ "beginZoneRecovery: failed to begin recovery for %{public}s: %{public}@"
+ "captured"
+ "capturing container backup staging restoreAsOf=%{public}s noShift=%{bool,public}d"
+ "cascade.cross-donation.cache-resupply"
+ "com.apple.agentsessionstore.secure"
+ "containerMigration: %{public}ld/%{public}ld sessions failed to re-mark; they won't re-publish to the new container until edited"
+ "containerMigration: cleared persisted engine state"
+ "containerMigration: container changed %{public}s -> %{public}s"
+ "containerMigration: current container has no identifier; skipping"
+ "containerMigration: engine-state clear failed; deferring to next launch: %{public}@"
+ "containerMigration: failed to enumerate sessions; deferring: %{public}@"
+ "containerMigration: failed to re-mark session %{public}s: %{public}@"
+ "containerMigration: failed to read engine state: %{public}@"
+ "containerMigration: failed to record synced container id: %{public}@"
+ "containerMigration: re-publishing %{public}ld sessions"
+ "containerMigration: session enumeration failed; deferring container stamp to next launch"
+ "donatedModifiedDate"
+ "enterManateeRecovery: engaged recovery for %{public}ld/%{public}ld zone(s)"
+ "enterManateeRecovery: engine not ready; deferring"
+ "enterManateeRecovery: failed to enumerate recoverable zones (%{public}@); skipping recovery this pass"
+ "event"
+ "failed to persist zone recovery state %{public}s: %{public}@"
+ "fetchRemoteChanges: Manatee identity loss on fetch; entering recovery"
+ "finalizePressDemoImportIfNeeded: press-demo gate rejected; leaving flag for retry, not shifting"
+ "finalizePressDemoImportIfNeeded: rewrite failed (flag left at .importPendingShift, will retry): %@"
+ "finalizePressDemoImportIfNeeded: shiftDisabled=true; verbatim import finalized"
+ "finalizePressDemoImportIfNeeded: shifted by %s%fs (capturedAt=%s, restoreAsOf=%s, now=%s); finalized"
+ "finalizePressDemoImportIfNeeded: sidecar absent; verbatim import finalized"
+ "finalized"
+ "finishManateeRecoveryIfSettled: count failed: %{public}@"
+ "full set donation seeded ledger with %{public}ld sessions, %{public}ld events"
+ "handleConflict: value ID mismatch session=%{public}s; discarding local mergeable"
+ "handleFetchedRecordZoneChanges: ignoring session record deletion for actively-recovering zone %{public}s"
+ "handleFetchedRecordZoneChanges: ignoring session record deletion while deletion-suppression active %{public}s"
+ "id kind "
+ "id kind modifiedDate "
+ "ignoring remote zone deletion for actively-recovering zone: %{public}s"
+ "ignoring remote zone deletion while deletion-suppression active: %{public}s"
+ "import_pending_shift"
+ "manatee recovery mode reset (account change)"
+ "manatee recovery settled"
+ "merge: processing delta[%{public}ld] decoded events=%{public}ld artifacts=%{public}ld for session %{public}s"
+ "mergeDiscardingLocal: failed to merge server into empty value session=%{public}s: %{public}@"
+ "nextRecordZoneChangeBatch: %{public}ld pending changes in scope"
+ "nextRecordZoneChangeBatch: byte budget spent at %{public}ld bytes over %{public}ld records — remainder stays pending"
+ "nextRecordZoneChangeBatch: removing session %{public}s from pending changes: %{public}s"
+ "nextRecordZoneChangeBatch: unrecognized pending record %{public}s"
+ "processIncomingSessionArtifactRecord: Failed to create artifact record for %s: %@"
+ "processIncomingSessionArtifactRecord: Failed to create event record for artifact %s: %@"
+ "readResourceData(_:)"
+ "recovery: resurrect failed %{public}s: %{public}@"
+ "recovery: zone delete confirmed %{public}s; recreating + re-uploading"
+ "recovery: zone save confirmed %{public}s; zone recovery complete"
+ "redrive: resurrect failed %{public}s: %{public}@"
+ "redriveInterruptedManateeRecovery: enumeration failed: %{public}@"
+ "redriveInterruptedManateeRecovery: resuming %{public}ld zone(s)"
+ "remote-deletion suppression watchdog fired (%{public}s) — clearing after timeout"
+ "resurrectSessionOnServer: resurrected %{public}s (no session entity; zone only)"
+ "session"
+ "sourceItemIdentifier"
+ "switchAccounts: failed to clear recovery state (%{public}@); a mid-recovery zone may be re-driven next launch"
+ "syncCoordinator:broadcast: resolveUnresolvedArtifacts failed: %@"
+ "syncedContainerIdentifier"
+ "using CloudKit container %{public}s, environment %{public}s"
+ "zoneRecoveryState: read failed for %{public}s: %{public}@; defaulting to .none"
+ "zoneRecoveryStateRaw"
- "Failed to parse XMP metadata for asset %s: %@"
- "handleFetchedRecordZoneChanges: ignoring session record deletion during initial post-signIn fetch %{public}s"
- "handleFetchedRecordZoneChanges: resolveUnresolvedArtifacts: artifactIds: %{public}s"
- "handleFetchedRecordZoneChanges: resolveUnresolvedArtifacts: error: %@"
- "ignoring deletion during initial post-signIn fetch: %{public}s"
- "nextRecordZoneChangeBatch: no records to save or delete, returning nil"
- "nextRecordZoneChangeBatch: pending changes: %{public}s"
- "nextRecordZoneChangeBatch: prepareArtifactRecord returned nil for %{public}@"
- "nextRecordZoneChangeBatch: prepareSessionRecord returned nil for session %{public}s"
- "nextRecordZoneChangeBatch: processing artifact delete IDs: %{public}s"
- "nextRecordZoneChangeBatch: processing artifact save IDs: %{public}s"
- "nextRecordZoneChangeBatch: session %{public}s has no sync metadata, removing from pending changes"
- "nextRecordZoneChangeBatch: session zone IDs: %{public}s"
- "performDataResetIfNeeded: V15 data reset complete"
- "performDataResetIfNeeded: V15 data reset starting"
- "performDataResetIfNeeded: deleted %s"
- "performDataResetIfNeeded: failed to delete %s: %@"
- "performDataResetIfNeeded: failed to enumerate directory: %@"
- "post-signIn filter watchdog fired — clearing after timeout"
- "processIncomingSessionArtifactRecord: Failed to broadcast event update for artifact %s: %@"
- "processIncomingSessionRecord: failed to merge server into empty record value session=%{public}s: %{public}@"
- "resurrectSessionOnServer: resurrected %{public}s (no session entity for artifact re-enqueue)"
- "using CloudKit environment %{public}s"
```
