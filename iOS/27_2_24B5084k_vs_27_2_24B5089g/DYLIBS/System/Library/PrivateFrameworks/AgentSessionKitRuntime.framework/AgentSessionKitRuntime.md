## AgentSessionKitRuntime

> `/System/Library/PrivateFrameworks/AgentSessionKitRuntime.framework/AgentSessionKitRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x1e010` | `0x1bf90` | **`-0x2080`** |
| `__DATA_DIRTY.__bss` | `0x3900` | `0x5980` | **`+0x2080`** |
| `__DATA_DIRTY.__data` | `0x3a68` | `0x4de8` | **`+0x1380`** |
| `__AUTH.__data` | `0x8f28` | `0x81d0` | **`-0xd58`** |
| `__DATA.__data` | `0x57f8` | `0x5210` | **`-0x5e8`** |
| `__AUTH_CONST.__const` | `0x9748` | `0x9270` | **`-0x4d8`** |
| `__AUTH.__objc_data` | `0x2d30` | `0x29c0` | **`-0x370`** |
| `__DATA_DIRTY.__objc_data` | `0x5d0` | `0x940` | **`+0x370`** |
| `__TEXT.__swift5_capture` | `0x28f8` | `0x26d0` | **`-0x228`** |
| `__TEXT.__text` | `0x2c868c` | `0x2c8474` | **`-0x218`** |
| `__TEXT.__eh_frame` | `0x181e8` | `0x180a8` | **`-0x140`** |
| `__DATA.__common` | `0x2f8` | `0x1e0` | **`-0x118`** |
| `__DATA_DIRTY.__common` | `0x100` | `0x218` | **`+0x118`** |
| `__TEXT.__oslogstring` | `0x96c3` | `0x95e3` | **`-0xe0`** |
| `__TEXT.__swift5_typeref` | `0xa157` | `0xa215` | **`+0xbe`** |
| `__DATA_CONST.__objc_selrefs` | `0x7e8` | `0x820` | **`+0x38`** |
| `__TEXT.__cstring` | `0x21fe` | `0x221e` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2580` | `0x2598` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x84c` | `0x834` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0xd8a0` | `0xd8b8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x15c0` | `0x15d0` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x34c` | `0x340` | **`-0xc`** |
| `__TEXT.__swift_as_entry` | `0x348` | `0x344` | **`-0x4`** |

### Other Changes

```diff

-297.6.0.5.0
+297.8.0.2.0

-  Functions: 21614
-  Symbols:   308
-  CStrings:  785
+  Functions: 21613
+  Symbols:   311
+  CStrings:  783
Symbols:
+ _OBJC_CLASS_$_CCSiriTranscriptTurnInfo
+ _OBJC_CLASS_$_CKFetchDatabaseChangesOperation
+ _objc_retain_x9
CStrings:
+ "backfill deferred: no server zone view this launch"
+ "fetchZoneIDs(matching:)"
+ "initial fetch deferred: %{public}@"
+ "missingZoneIDs: chunk of %{public}ld failed: %{public}@"
+ "missingZoneIDs: no verdict for %{public}s: %{public}@"
+ "reconcileZonesWithServer: %{public}ld zone(s) got no verdict; deferring them to a later reconcile"
+ "reconcileZonesWithServer: candidates=%{public}ld missing=%{public}ld unchecked=%{public}ld"
+ "reconcileZonesWithServer: failed to load candidates: %{public}@"
+ "reconcileZonesWithServer: missing %{public}s"
+ "reconcileZonesWithServer: resurrect failed for %{public}s: %{public}@"
- "CloudKit returned %{public}ld zones"
- "discovered existing session zone %{public}s"
- "failed to discover zones after signIn: %@"
- "initial fetch deferred: %@"
- "initial zone discovery deferred: %@"
- "local database has %{public}ld session zones; skipping CloudKit zone discovery"
- "reconcileZonesWithServer: allRecordZones failed (deferring): %@"
- "reconcileZonesWithServer: missing-but-zone-present (parse drop) %{public}s"
- "reconcileZonesWithServer: missing-zone-absent (incomplete list / real deletion) %{public}s"
- "reconcileZonesWithServer: resurrect failed for %{public}s: %@"
- "reconcileZonesWithServer: serverZonesRaw=%{public}ld serverZonesParsed=%{public}ld localCandidates=%{public}ld missingFromServer=%{public}ld missingButZonePresent=%{public}ld missingZoneAbsent=%{public}ld"
- "signIn reconciliation failed: %@"
```
