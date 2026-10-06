## FileIndexerDaemon

> `/System/Library/PrivateFrameworks/FileIndexerDaemon.framework/FileIndexerDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x629c0` | `0x685b0` | **`+0x5bf0`** |
| `__DATA.__bss` | `0x3180` | `0x3500` | **`+0x380`** |
| `__TEXT.__const` | `0x30b4` | `0x33a4` | **`+0x2f0`** |
| `__TEXT.__oslogstring` | `0x20fa` | `0x23ba` | **`+0x2c0`** |
| `__AUTH_CONST.__const` | `0x26c0` | `0x2878` | **`+0x1b8`** |
| `__TEXT.__constg_swiftt` | `0x114c` | `0x1290` | **`+0x144`** |
| `__AUTH.__data` | `0x458` | `0x578` | **`+0x120`** |
| `__TEXT.__swift5_typeref` | `0x10be` | `0x11b2` | **`+0xf4`** |
| `__TEXT.__cstring` | `0x130b` | `0x13fb` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x10d8` | `0x11c8` | **`+0xf0`** |
| `__TEXT.__eh_frame` | `0x1cc0` | `0x1da8` | **`+0xe8`** |
| `__TEXT.__swift5_fieldmd` | `0xe3c` | `0xf14` | **`+0xd8`** |
| `__TEXT.__swift5_reflstr` | `0xc28` | `0xcc8` | **`+0xa0`** |
| `__DATA.__data` | `0x8b0` | `0x920` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x82c` | `0x884` | **`+0x58`** |
| `__DATA_DIRTY.__data` | `0x1828` | `0x1878` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0xee0` | `0xf28` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x1990` | `0x19d0` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0x168` | `0x198` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x24c` | `0x274` | **`+0x28`** |
| `__DATA.__common` | `0x18` | `0x38` | **`+0x20`** |
| `__DATA_DIRTY.__objc_data` | `0x4c8` | `0x4e0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x528` | `0x538` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x448` | `0x458` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x14` | `0x20` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0xec` | `0xf8` | **`+0xc`** |

### Other Changes

```diff

-4780.0.0.502.1
+4838.0.29.502.2

-  Functions: 1490
-  Symbols:   796
-  CStrings:  275
+  Functions: 1579
+  Symbols:   819
+  CStrings:  285
Symbols:
+ ___swift_closure_destructor.119Tm
+ ___swift_closure_destructor.297Tm
+ ___swift_closure_destructor.331Tm
+ ___swift_closure_destructor.45Tm
+ ___swift_closure_destructor.48Tm
+ ___swift_closure_destructor.94Tm
+ ___swift_closure_destructor.98Tm
+ _associated conformance 17FileIndexerDaemon24IdentifierMismatchDetailV9StaleSideOSHAASQ
+ _associated conformance 17FileIndexerDaemon24IdentifierMismatchDetailV9StaleSideOs12CaseIterableAA8AllCasessAFP_Sl
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
+ _swift_stdlib_random
+ _symbolic $s17FileIndexerDaemon16StateIDGeneratorP
+ _symbolic $s17FileIndexerDaemon20BGSystemTaskProtocolP
+ _symbolic $s17FileIndexerDaemon29BGSystemTaskSchedulerProtocolP
+ _symbolic Say_____G 17FileIndexerDaemon24IdentifierMismatchDetailV9StaleSideO
+ _symbolic _____ 17FileIndexerDaemon18V7StateIDGeneratorV
+ _symbolic _____ 17FileIndexerDaemon24IdentifierMismatchDetailV
+ _symbolic _____ 17FileIndexerDaemon24IdentifierMismatchDetailV9StaleSideO
+ _symbolic _____ 18FileProviderDaemon8FilenameV
+ _symbolic _____Sg 17FileIndexerDaemon24IdentifierMismatchDetailV
+ _symbolic _____Sg_ABt 10Foundation4DateV
+ _symbolic ______p 17FileIndexerDaemon16StateIDGeneratorP
+ _symbolic ______p 17FileIndexerDaemon20BGSystemTaskProtocolP
+ _symbolic ______p 17FileIndexerDaemon29BGSystemTaskSchedulerProtocolP
+ _symbolic ______pIegg_ 17FileIndexerDaemon20BGSystemTaskProtocolP
+ _symbolic ______pSgXw 17FileIndexerDaemon20BGSystemTaskProtocolP
+ _symbolic ______pSgXwz_Xx 17FileIndexerDaemon20BGSystemTaskProtocolP
+ _symbolic _____yYbc 10Foundation4DateV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 17FileIndexerDaemon14IndexDropCauseO
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
+ _type_layout_string 17FileIndexerDaemon18V7StateIDGeneratorV
- ___swift_closure_destructor.128Tm
- ___swift_closure_destructor.132Tm
- ___swift_closure_destructor.50Tm
- ___swift_closure_destructor.79Tm
- ___swift_closure_destructor.82Tm
- ___swift_closure_destructor.97Tm
- _associated conformance 17FileIndexerDaemon14IndexDropCauseOSHAASQ
- _symbolic So12BGSystemTaskC
- _symbolic So12BGSystemTaskCSgXw
- _symbolic So12BGSystemTaskCSgXwz_Xx
CStrings:
+ "\nMismatch classification: "
+ "%ld Changed items %{public}s"
+ "%ld Deleted item IDs %{public}s"
+ "%{public}s (fileID: %llu) is not in any known root"
+ "%{public}s failed to index: %{public}@"
+ "%{public}s | E: event %{public}s fileID %llu flags %{public}s"
+ "%{public}s | E: ignored %{public}s fileID %llu flags %{public}s"
+ "%{public}s | failed to remove items from index: %{public}@"
+ "%{public}s: force stopping mid-step"
+ "Added container root for %{public}s to scan batch"
+ "Added scan for %{public}s"
+ "Adding local root at %{public}s"
+ "App %{public}s at %{public}s already known"
+ "Cannot lookup deviceID for managed app %{public}s at path %s: %@"
+ "Error getting parent identifier for %{public}s: %{public}@"
+ "Error retrieving capabilities for %{public}s : %{public}@"
+ "Error retrieving content type for %{public}s: %{public}@"
+ "Failed to construct URL from path='%{public}s' for fileID=%llu"
+ "Failed to create container metadata for root: %{public}@"
+ "Failed to create listener for app %{public}s: %{public}@"
+ "Failed to fetch metadata for file %{public}s"
+ "Failed to fetch metadata for root at %{public}s"
+ "Failed to load state for %s. Forcing re-indexing with stateID %s%s"
+ "Failed to register LS root %{public}s to %s in SAF: %{public}@"
+ "Failed to stat URL %{public}s: %{public}@"
+ "Failed to subscribe to root %{public}s, registering it for removal"
+ "Forcing re-indexing by setting stateID to %s"
+ "Generation count changed while listing %{public}s, restarting its listing"
+ "Local root at %{public}s"
+ "No root found for URL: %{public}s"
+ "On personal volume? %{bool}d for app %{public}s"
+ "Pruning stale app root for %s at %{public}s, current is %{public}s"
+ "Pruning stale local root at %{public}s, current is %{public}s"
+ "Rejecting XPC connection: missing entitlement %{public}s"
+ "Reposition failed in %{public}s, remainingBytes=%ld, restarting its listing"
+ "Resume entry '%{public}s' not found in %{public}s, restarting its listing"
+ "Skipping app %{public}s (%{public}s)"
+ "Spotlight reindex requested for bundleID: %s, reason: %s"
+ "Start monitoring app %{public}s (%{public}s) at %{public}s"
+ "Stopped monitoring app %{public}s at %{public}s"
+ "Successfully created searchable item for %{public}s"
+ "[%ld/%ld] Created local root at %{public}s"
+ "[%ld/%ld] Failed to create local root at %{public}s: %{public}@"
+ "[DiskStateStore] identifier mismatch -- %s spotlight=%s disk=%s"
+ "[StateManager] Spotlight clientState is nil -- fresh device, no prior index"
+ "[StateManager] Spotlight clientState is nil but cookie exists -- unexpected"
+ "can't scan a url not in one of our roots: %{public}s"
+ "com.apple.private.FileIndexer.client"
+ "error in package translation - path: %{public}s fileID: %llu - error: %{public}@"
+ "failed to copy favorite rank: %{public}@"
+ "failed to copy last used date: %{public}@"
+ "failed to copy tagData: %{public}@"
+ "failed to get metadata for (%llu, in: %d): %{public}@"
+ "failed to index while listing %{public}s: %{public}@"
+ "failed to open %{public}s: %{public}@"
+ "failed to scan %{public}s: %{public}@"
+ "failed to subscribe to events in %{public}s with %{public}@"
+ "found ignored path while listing, %{public}s"
+ "identifierMismatch"
+ "isPackage(%{public}s) failed %{public}@"
+ "lister for %{public}s completed"
+ "lister for %{public}s failed: %{public}@"
+ "mismatchStaleSide"
+ "searchableItem requested for %{public}s"
+ "skipping non-indexable file %{public}s, (type: %s)"
+ "spotlightOlder(lag: "
+ "spotlightStateNilUnexpected"
+ "unknownAge(pre-v7 identifiers)"
- "%ld Changed items %s"
- "%ld Deleted item IDs %s"
- "%s (fileID: %llu is not in any known root"
- "%s | E: event path %s fileID %llu flags %s"
- "%s | E: ignored event path %s fileID %llu flags %s"
- "%s | failed to remove items from index: %@"
- "%s: force stopping mid-step"
- "Added container root for %s to scan batch"
- "Added scan for %s"
- "Adding local root at %s"
- "App %s at %s already known"
- "Cannot lookup deviceID for managed app %s at path %s: %@"
- "Error getting parent identifier for %s: %@"
- "Error retrieving capabilities for %s : %@"
- "Error retrieving content type for %s: %@"
- "Event handling failed to index: %@"
- "Failed to construct URL from path='%s' for fileID=%llu"
- "Failed to create container metadata for root: %@"
- "Failed to create listener for app %@: %@"
- "Failed to fetch metadata for file %s"
- "Failed to fetch metadata for root at %s"
- "Failed to load state for %s. Forcing re-indexing by setting stateID to %s"
- "Failed to register LS root %s to %s in SAF: %@"
- "Failed to stat URL %s: %@"
- "Failed to subscribe to root %s, registering it for removal"
- "Generation count changed while listing %s, restarting its listing"
- "Local root at %s"
- "No root found for URL: %s"
- "On personal volume? %{bool}d for app %s"
- "Pruning stale app root for %s at %s, current is %s"
- "Pruning stale local root at %s, current is %s"
- "Reposition failed in %s, remainingBytes=%ld, restarting its listing"
- "Resume entry '%s' not found in %s, restarting its listing"
- "Skipping app %s (%s)"
- "Start monitoring app %s (%s) at %s"
- "Stopped monitoring app %s at %s"
- "Successfully created searchable item for %s"
- "[%ld/%ld] Created local root at %s"
- "[%ld/%ld] Failed to create local root at %s: %@"
- "[DiskStateStore] identifier mismatch — crash between Spotlight write and cookie write"
- "[StateManager] Spotlight clientState is nil but cookie exists — unexpected"
- "[StateManager] Spotlight clientState is nil — fresh device, no prior index"
- "can't scan a url not in one of our roots: %s"
- "error while attempting package translation - path: %s fileID: %llu - error: %@"
- "failed to copy favorite rank: %@"
- "failed to copy last used date: %@"
- "failed to copy tagData: %@"
- "failed to get metadata for (%llu, in: %d): %@"
- "failed to index while listing %s: %@"
- "failed to open %s, %@"
- "failed to scan of %s: %@"
- "failed to subscribe to events in %s with %@"
- "found ignored path while listing, %s"
- "isPackage(%s) failed %@"
- "lister for %s completed"
- "lister for %s failed: %@"
- "searchableItem requested for %s"
- "skipping non-indexable file %s, (type: %s)"
```
