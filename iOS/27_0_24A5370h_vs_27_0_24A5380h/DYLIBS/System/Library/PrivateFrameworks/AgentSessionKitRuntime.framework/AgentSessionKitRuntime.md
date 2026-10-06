## AgentSessionKitRuntime

> `/System/Library/PrivateFrameworks/AgentSessionKitRuntime.framework/AgentSessionKitRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b8580` | `0x1fc0b8` | **`+0x43b38`** |
| `__TEXT.__const` | `0x131dc` | `0x197ec` | **`+0x6610`** |
| `__DATA_DIRTY.__bss` | `0x600` | `0x3900` | **`+0x3300`** |
| `__AUTH_CONST.__objc_const` | `0x71c8` | `0xa008` | **`+0x2e40`** |
| `__DATA_DIRTY.__data` | `0x13f8` | `0x3d58` | **`+0x2960`** |
| `__TEXT.__eh_frame` | `0xf320` | `0x11500` | **`+0x21e0`** |
| `__DATA.__bss` | `0xe9b0` | `0x10520` | **`+0x1b70`** |
| `__TEXT.__unwind_info` | `0x72b8` | `0x8e18` | **`+0x1b60`** |
| `__TEXT.__swift5_reflstr` | `0x4291` | `0x5ce1` | **`+0x1a50`** |
| `__TEXT.__swift5_typeref` | `0x5cd9` | `0x715d` | **`+0x1484`** |
| `__TEXT.__swift5_fieldmd` | `0x3888` | `0x4b24` | **`+0x129c`** |
| `__TEXT.__constg_swiftt` | `0x2bec` | `0x37c4` | **`+0xbd8`** |
| `__AUTH_CONST.__const` | `0x7210` | `0x7cd8` | **`+0xac8`** |
| `__TEXT.__swift5_assocty` | `0xbb0` | `0x10c0` | **`+0x510`** |
| `__AUTH.__objc_data` | `0x1200` | `0x1700` | **`+0x500`** |
| `__DATA_DIRTY.__objc_data` | `0x260` | `0x5c8` | **`+0x368`** |
| `__DATA.__data` | `0x3a58` | `0x3730` | **`-0x328`** |
| `__TEXT.__swift5_capture` | `0x21f4` | `0x2494` | **`+0x2a0`** |
| `__AUTH.__data` | `0x42a8` | `0x4500` | **`+0x258`** |
| `__TEXT.__swift5_proto` | `0x6f8` | `0x920` | **`+0x228`** |
| `__TEXT.__cstring` | `0x1dae` | `0x1f7e` | **`+0x1d0`** |
| `__TEXT.__swift5_types` | `0x314` | `0x3f8` | **`+0xe4`** |
| `__DATA_CONST.__objc_classlist` | `0x248` | `0x320` | **`+0xd8`** |
| `__DATA_CONST.__got` | `0x12d0` | `0x1390` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x790c` | `0x79cc` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0x2370` | `0x2428` | **`+0xb8`** |
| `__DATA_DIRTY.__common` | `0x50` | `0x108` | **`+0xb8`** |
| `__TEXT.__objc_methlist` | `0x69c` | `0x6cc` | **`+0x30`** |
| `__DATA.__common` | `0x148` | `0x120` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x738` | `0x750` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x6f0` | `0x708` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x2b8` | `0x2bc` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x290` | `0x28c` | **`-0x4`** |

### Other Changes

```diff

-284.0.7.0.0
+287.0.6.0.0

-  - /System/Library/PrivateFrameworks/GenerativeSearch.framework/GenerativeSearch
+  - /System/Library/PrivateFrameworks/HybridSearch.framework/HybridSearch

-  Functions: 11710
-  Symbols:   301
-  CStrings:  661
+  Functions: 14394
+  Symbols:   299
+  CStrings:  678
Symbols:
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "Posting agentSessionStoreDidBecomeAvailable"
+ "Proactively warming up agent media photo library at daemon launch"
+ "backfill: deferring artifact %{public}s, awaiting stable-ID resolution"
+ "crisisTier1Count"
+ "crisisTier2Count"
+ "crisisTier3Count"
+ "crisis_tier1_count"
+ "crisis_tier2_count"
+ "crisis_tier3_count"
+ "enqueueResolutionTaskForUnknownArtifacts: failed %{public}s: %@"
+ "enqueueResolutionTaskForUnknownArtifacts: resolved %{public}ld of %{public}ld for %{public}s, enqueueing anyway"
+ "enqueueResolutionTaskForUnknownArtifacts: resolved all %{public}ld artifacts for session %{public}s"
+ "enqueueResolutionTaskForUnknownArtifacts: resolving %{public}s for session %{public}s"
+ "isSensitiveCondition"
+ "is_sensitive_condition"
+ "personalStrugglesCount"
+ "personal_struggles_count"
+ "reconcileZonesWithServer: missing-but-zone-present (parse drop) %{public}s"
+ "reconcileZonesWithServer: missing-zone-absent (incomplete list / real deletion) %{public}s"
+ "reconcileZonesWithServer: serverZonesRaw=%{public}ld serverZonesParsed=%{public}ld localCandidates=%{public}ld missingFromServer=%{public}ld missingButZonePresent=%{public}ld missingZoneAbsent=%{public}ld"
+ "sensitiveOutputCount"
+ "sensitive_output_count"
+ "sensitivityConditionName"
+ "sensitivity_condition_name"
- "reconcileZonesWithServer: serverZones=%{public}ld localCandidates=%{public}ld missingFromServer=%{public}ld"
- "resolveAndEnqueueArtifactsAddedForSync: failed %{public}s: %@"
- "resolveAndEnqueueArtifactsAddedForSync: resolved %{public}ld of %{public}ld for %{public}s, enqueueing anyway"
- "resolveAndEnqueueArtifactsAddedForSync: resolved all %{public}ld artifacts before sync"
- "resolveAndEnqueueArtifactsAddedForSync: resolving %{public}s before sync"
- "updated metadata for session %{public}s changedFields=%{public}s metadata=AgentSessionMetadata(titleSource: %{public}s, title: %{private}s, summary: %{private}s, isPinned: %{bool,public}d, persistableState: %{public}s, safety: %{bool,public}d)"
- "xpc server instance deallocating, canceling forwarding tasks"
```
