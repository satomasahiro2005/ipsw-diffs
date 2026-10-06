## searchpartyd

> `/usr/libexec/searchpartyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17ea0ac` | `0x181b840` | **`+0x31794`** |
| `__TEXT.__eh_frame` | `0xeb5b0` | `0xecff0` | **`+0x1a40`** |
| `__DATA.__bss` | `0xaa100` | `0xaae80` | **`+0xd80`** |
| `__TEXT.__oslogstring` | `0x4983e` | `0x4a57e` | **`+0xd40`** |
| `__TEXT.__const` | `0x91778` | `0x92328` | **`+0xbb0`** |
| `__DATA_CONST.__const` | `0x6dc78` | `0x6e798` | **`+0xb20`** |
| `__DATA.__data` | `0x3ee08` | `0x3f1f8` | **`+0x3f0`** |
| `__TEXT.__unwind_info` | `0x47cb8` | `0x48038` | **`+0x380`** |
| `__TEXT.__constg_swiftt` | `0x20484` | `0x20798` | **`+0x314`** |
| `__TEXT.__swift5_capture` | `0x19a68` | `0x19d60` | **`+0x2f8`** |
| `__TEXT.__cstring` | `0x3112c` | `0x3140c` | **`+0x2e0`** |
| `__TEXT.__swift5_fieldmd` | `0x24898` | `0x24b50` | **`+0x2b8`** |
| `__TEXT.__swift5_typeref` | `0x23275` | `0x23507` | **`+0x292`** |
| `__TEXT.__swift_as_cont` | `0xd3e8` | `0xd5ec` | **`+0x204`** |
| `__DATA.__objc_const` | `0x1b3e0` | `0x1b580` | **`+0x1a0`** |
| `__TEXT.__swift5_reflstr` | `0x23281` | `0x233a1` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x17688` | `0x17798` | **`+0x110`** |
| `__TEXT.__swift_as_ret` | `0x763c` | `0x771c` | **`+0xe0`** |
| `__TEXT.__objc_stubs` | `0x7060` | `0x7100` | **`+0xa0`** |
| `__TEXT.__objc_methtype` | `0x594e` | `0x59de` | **`+0x90`** |
| `__TEXT.__swift_as_entry` | `0x3784` | `0x380c` | **`+0x88`** |
| `__TEXT.__swift5_proto` | `0x5924` | `0x5994` | **`+0x70`** |
| `__TEXT.__auth_stubs` | `0x8f50` | `0x8fb0` | **`+0x60`** |
| `__DATA.__common` | `0x2f40` | `0x2f88` | **`+0x48`** |
| `__TEXT.__swift5_types` | `0x1e84` | `0x1ec0` | **`+0x3c`** |
| `__DATA_CONST.__auth_got` | `0x47b0` | `0x47e0` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x3360` | `0x3388` | **`+0x28`** |
| `__DATA_CONST.__auth_ptr` | `0x4698` | `0x4680` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0x2b38` | `0x2b50` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x94c` | `0x960` | **`+0x14`** |
| `__TEXT.__objc_classname` | `0x4480` | `0x4490` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3708` | `0x3710` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x8c8` | `0x8d0` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0xa40` | `0xa48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-446.30.5.17.5
+448.30.6.7.2

-  Functions: 64204
-  Symbols:   4612
-  CStrings:  13233
+  Functions: 64675
+  Symbols:   4619
+  CStrings:  13302
Symbols:
+ _$s10FindMyBase25abandonTaskOnCancellation5blockxxyYaYbKc_tYaKs8SendableRzlF
+ _$s10FindMyBase25abandonTaskOnCancellation5blockxxyYaYbKc_tYaKs8SendableRzlFTu
+ _$s10Foundation4DataV5write2to7optionsyAA3URLV_So20NSDataWritingOptionsVtKF
+ _$s18FindMyFeatureFlags0C0O0aB0O15airlineTravelV2AC0C3KeyVvgZ
+ _$sScCMa
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
CStrings:
+ ".sharedLocalFindable("
+ "Activation completed for session %{private,mask.hash}s but the session was removed mid-activation."
+ "BeaconStore service unavailable"
+ "Begin rawSearchResultsForImportedLocations for beaconIdentifier %{private,mask.hash}s."
+ "Cache is empty: beaconStoreHasRecords=%{bool}d, findMyServiceHasDevices=%{bool}d, beaconStoreAvailable=%{bool}d, devicesAvailable=%{bool}d, decision=%{public}s."
+ "CloudKitCoordinator requested flushCache (alreadyHaveExclusiveAccess: %{bool,public}d)"
+ "Dropping coalesced delivery for session %{private,mask.hash}s: session is no longer registered. count=%{public}ld"
+ "EmptyCacheSubscribeRecovery"
+ "Exhausted retries modifying OwnedBeaconGroup %{private,mask.hash}s after etag conflicts."
+ "Failed to fetch imported item locations: %@."
+ "Failed to map group for beacon record: %{private,mask.hash}s."
+ "Failed to persist userAck for BFU at %{public}s: %{public}@"
+ "Failed to remove imported share with share id %{private,mask.hash}s, error: %@"
+ "Failed to set Class D protection on dir %{public}s: %{public}@"
+ "Failed to set Class D protection on file %{public}s: %{public}@"
+ "Failed to stop imported share for share id %{private,mask.hash}s, beacon: %{private,mask.hash}s: %@."
+ "Failure in fetching latest attached to device. No beacon for identifier: %{private,mask.hash}s."
+ "Fetch token missing for imported beacon %{private,mask.hash}s. Cannot fetch locations."
+ "FetchImportedBeaconsLocations.FromServer"
+ "Final delivery: %{public}s."
+ "Ignoring beacon location updates while not processing - beacon: %{private,mask.hash}s source=%{public}s ageSeconds=%{public}f."
+ "KeyDropImportedLocationFetchRequest"
+ "KeyDropImportedLocationFetchRequest: %s"
+ "KeyDropImportedLocationFetchResponse"
+ "LPEM session delivered after abandonment; ending to release NF hardware"
+ "Location Fetch request for imported beacon"
+ "No imported beacons to fetch locations for."
+ "No member sharing circle found for imported beacon %{private,mask.hash}s."
+ "Per-type fetch dispatch for %{public}s."
+ "Persisted userAck for BFU: %{bool,public}d at %{public}s"
+ "Retrying modify of OwnedBeaconGroup %{private,mask.hash}s after etag conflict (attempt %ld/%ld)."
+ "Schema healing addColumn(%s.%s): column already added by peer."
+ "Schema inconsistency detected: %s.%s column missing. Re-adding."
+ "Shared beacon fetcher not available — skipping imported fetch."
+ "Skipped activation: location fetch subscription %{private,mask.hash}s was already removed."
+ "Skipping activation work for session %{private,mask.hash}s for context %{public}s: session was removed before activation could run."
+ "Skipping fetching locations from server. No beacons remaining to fetch."
+ "Suspended-clients breakdown: clients=[%{public}s] intentContext=%{bool,public}d"
+ "Timed out modifying beacon group"
+ "Unable to pair beacon onto refreshed group (attempt %ld/%ld)."
+ "Unable to refresh OwnedBeaconGroup %{private,mask.hash}s for modify."
+ "_TtC12searchpartyd18RebuildCoordinator"
+ "applyFindMyFeature(enabled:false) error: %{public}@"
+ "applyFindMyFeature(enabled:true) error: %{public}@"
+ "awaitHardwareReady()"
+ "cacheRepopulated"
+ "cancelled"
+ "fetchImportedBeaconLocation for shareIdentifier %{private,mask.hash}s,\nbeaconIdentifier %{private,mask.hash}s."
+ "fetchImportedItemsLocationsFromServerAsync(importedBeaconRecordsToFetch:policy:)"
+ "fetchSharedItemsLocationsFromServerAsync(sharedBeaconRecordsToFetch:policy:)"
+ "importedLocationFetch"
+ "initWithTitle:description:percentageX:percentageY:image:image2x:image3x:video:"
+ "instructionsToDisableVideoURL"
+ "instructionsToDisableVideoUrl"
+ "isActivationLocked"
+ "lastStartedEpoch"
+ "learnMoreVideoURL"
+ "learnMoreVideoUrl"
+ "locationTs"
+ "lostModeInfo"
+ "lpemToggleTask"
+ "maskedAppleID"
+ "nextFinderPublishDate: powerMode %{public}s, budget window elapsed (lastPublishDate %{public}s >= endOfDay %{public}s); scheduling for next day boundary %{public}s."
+ "rawSearchResultsForImportedLocations for beaconIdentifier %{private,mask.hash}s complete.%s"
+ "rebuildCoordinator"
+ "recoveryFallback"
+ "run(acquire:cleanup:)"
+ "setTheftDeterranceDisabled cancelled (superseded)"
+ "setTheftDeterranceDisabled: NF hardware ready, starting transaction"
+ "setTheftDeterranceDisabled: awaiting NF hardware ready (no transaction)"
+ "setTheftDeterranceDisabled: cancelled during HW wait"
+ "setTheftDeterranceEnabled cancelled (superseded)"
+ "setTheftDeterranceEnabled: NF hardware ready, starting transaction"
+ "setTheftDeterranceEnabled: awaiting NF hardware ready (no transaction)"
+ "setTheftDeterranceEnabled: cancelled during HW wait"
+ "sharedHardwareManager:"
+ "v16@?0@\"NFHardwareManager\"8"
+ "video"
+ "waitForNextRebuild()"
+ "waiters"
- "Cache is empty, services are loaded: %{bool}d."
- "CloudKitCoordinator requested flushCache"
- "Ignoring beacon location updates while not processing - beacon: %{private,mask.hash}s."
- "Missing NFLPEMConfigSession"
- "Schema inconsistency detected: deliverySource column missing. Rebuilding database."
- "com.apple.searchpartyd.lpem"
- "configureHardwareForLPEM error: %{public}@"
- "configureHardwareForLPEM succeeded, triggering state re-evaluation"
- "disableFindMyFeature error: %{public}@"
- "enableFindMyFeature error: %{public}@"
- "initWithTitle:description:percentageX:percentageY:image:image2x:image3x:"
```
