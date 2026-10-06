## AgentSessionKitRuntime

> `/System/Library/PrivateFrameworks/AgentSessionKitRuntime.framework/AgentSessionKitRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fc0b8` | `0x205ad4` | **`+0x9a1c`** |
| `__TEXT.__eh_frame` | `0x11500` | `0x11cf8` | **`+0x7f8`** |
| `__AUTH_CONST.__const` | `0x7cd8` | `0x83c0` | **`+0x6e8`** |
| `__TEXT.__oslogstring` | `0x79cc` | `0x801c` | **`+0x650`** |
| `__TEXT.__unwind_info` | `0x8e18` | `0x9458` | **`+0x640`** |
| `__AUTH_CONST.__objc_const` | `0xa008` | `0xa2f0` | **`+0x2e8`** |
| `__AUTH.__data` | `0x4500` | `0x47b0` | **`+0x2b0`** |
| `__TEXT.__const` | `0x197ec` | `0x19a8c` | **`+0x2a0`** |
| `__TEXT.__swift5_capture` | `0x2494` | `0x270c` | **`+0x278`** |
| `__TEXT.__constg_swiftt` | `0x37c4` | `0x3900` | **`+0x13c`** |
| `__TEXT.__swift5_fieldmd` | `0x4b24` | `0x4bdc` | **`+0xb8`** |
| `__TEXT.__swift5_typeref` | `0x715d` | `0x7215` | **`+0xb8`** |
| `__TEXT.__swift5_reflstr` | `0x5ce1` | `0x5d91` | **`+0xb0`** |
| `__DATA.__bss` | `0x10520` | `0x105c0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1f7e` | `0x200e` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x750` | `0x7d8` | **`+0x88`** |
| `__TEXT.__swift_as_cont` | `0x708` | `0x77c` | **`+0x74`** |
| `__AUTH_CONST.__auth_got` | `0x2428` | `0x2478` | **`+0x50`** |
| `__DATA_DIRTY.__data` | `0x3d58` | `0x3d18` | **`-0x40`** |
| `__DATA.__data` | `0x3730` | `0x3760` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x2bc` | `0x2e8` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x1390` | `0x13b8` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x28c` | `0x2b4` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x320` | `0x338` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x6cc` | `0x6e4` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x920` | `0x92c` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x3f8` | `0x404` | **`+0xc`** |
| `__TEXT.__swift5_protos` | `0x24` | `0x28` | **`+0x4`** |

### Other Changes

```diff

-287.0.6.0.0
+291.1.0.5.0

+  - /System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels

-  Functions: 14394
-  Symbols:   299
-  CStrings:  678
+  Functions: 14596
+  Symbols:   303
+  CStrings:  704
Symbols:
+ _OBJC_CLASS_$_CKMergeableDeltaMetadata
+ _OBJC_CLASS_$_CKMergeableDeltaVectors
+ _OBJC_CLASS_$_CKReplaceDeltasRequest
+ _OBJC_CLASS_$_CKReplaceMergeableDeltasOperation
CStrings:
+ "%{public}s: expired"
+ "DailyMaintenanceTask: deleted %ld expired sessions"
+ "DailyMaintenanceTask: deleted %ld stale transient sessions"
+ "DailyMaintenanceTask: expired session cleanup failed: %{public}@"
+ "DailyMaintenanceTask: stale transient session cleanup failed: %{public}@"
+ "Reserved cloud identifier (awaiting ingest): %s"
+ "WeeklyMaintenanceTask: delta compaction complete"
+ "WeeklyMaintenanceTask: running delta compaction"
+ "applyToDatabase: promoted transient session to persistable session=%{public}s"
+ "com.apple.GenerativeFunctions.agentstored.WeeklyMaintenance"
+ "compactSession: compacted %{public}ld deltas → 1 session=%{public}s"
+ "compactSession: refusing to compact from empty/degraded state session=%{public}s live=%{public}ld vector=%{public}ld"
+ "compactSession: session=%{public}s failed: %{public}@"
+ "compactSession: skip (%{public}ld < %{public}ld) session=%{public}s"
+ "compactSession: skip (local behind server, not caught up) session=%{public}s"
+ "compactSession: skip (not synced) session=%{public}s"
+ "compactSession: skip (pending local changes) session=%{public}s"
+ "compactSessionDeltas(count: "
+ "delta compaction eligibility query failed: %{public}@"
+ "enhanced siri availability changed"
+ "enqueuing %{public}ld sessions for delta compaction"
+ "fullStateDelta: expected exactly one delta, got %{public}ld"
+ "no eligible sessions found for compaction"
+ "replaceMergeableDeltas(_:sessionId:)"
+ "replaceMergeableDeltas: session=%{public}s operation failed: %{public}@"
+ "replaceMergeableDeltas: session=%{public}s per-replacement failed: %{public}@"
+ "replaceMergeableDeltas: session=%{public}s replace confirmed"
+ "replaceMergeableDeltas: session=%{public}s replacing %{public}ld deltas with %{public}ld"
+ "started enhanced-Siri availability observation"
+ "sync coordinator created (eligible)"
+ "sync coordinator creation skipped, device ineligible"
- "MaintenanceTask: deleted %ld expired sessions"
- "MaintenanceTask: deleted %ld stale transient sessions"
- "MaintenanceTask: expired"
- "MaintenanceTask: expired session cleanup failed: %@"
- "MaintenanceTask: stale transient session cleanup failed: %@"
```
