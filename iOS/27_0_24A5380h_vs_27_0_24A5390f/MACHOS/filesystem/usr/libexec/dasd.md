## dasd

> `/usr/libexec/dasd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1736b4` | `0x175bc4` | **`+0x2510`** |
| `__TEXT.__objc_methname` | `0x2dbdd` | `0x2e0ad` | **`+0x4d0`** |
| `__TEXT.__oslogstring` | `0x16599` | `0x16949` | **`+0x3b0`** |
| `__TEXT.__objc_stubs` | `0x1ab00` | `0x1ade0` | **`+0x2e0`** |
| `__TEXT.__cstring` | `0x101f6` | `0x103d6` | **`+0x1e0`** |
| `__DATA_CONST.__cfstring` | `0x11580` | `0x11740` | **`+0x1c0`** |
| `__TEXT.__objc_methlist` | `0x12f0c` | `0x13024` | **`+0x118`** |
| `__DATA.__objc_selrefs` | `0x9b38` | `0x9c28` | **`+0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x4e28` | `0x4ecc` | **`+0xa4`** |
| `__DATA.__objc_const` | `0x33b78` | `0x33c08` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x4e98` | `0x4ed8` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x4fb8` | `0x4ff0` | **`+0x38`** |
| `__DATA.__bss` | `0x1220` | `0x1240` | **`+0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `0x198` | `0x1b0` | **`+0x18`** |
| `__DATA.__data` | `0x2180` | `0x2190` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x470` | `0x480` | **`+0x10`** |
| `__TEXT.__const` | `0x1558` | `0x1568` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x15fc` | `0x1608` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2467.0.14.502.1
+2467.0.23.502.1

-  Functions: 8273
+  Functions: 8302

-  CStrings:  12325
+  CStrings:  12387
CStrings:
+ "Activity has primaryDomain=Default; phased scheduling must declare a real domain"
+ "Activity not BPC-allowlisted with PhasedScheduling=true"
+ "Bulk-path phased gate failed for %{public}@ (allowlisted=%d, hasRealDomain=%d) — degrading to non-phased. BGSystemTask clients should submit via the single-submit path for proper rejection."
+ "Campo"
+ "ConcurrencyBoostingEnabled"
+ "Deferring phased %{public}@ phase=%d, recency frontier=%d"
+ "EnablementPhase0"
+ "EnablementPhase1"
+ "EnablementPhase2"
+ "Freezer resident memory %.1f MB, threshold %.1f MB (%.1f%% of DRAM)"
+ "FreezerDemotionCapDRAMFraction"
+ "Loaded trial parameter FreezerDemotionCapDRAMFraction: %.1f%%"
+ "Loaded trial parameter MLFreezerAllowListCampoEnabled: %d"
+ "MLFreezerAllowListCampoEnabled"
+ "Not running %{public}@ immediately on submission: phase=%d is above the recency frontier; deferring to gated scheduling"
+ "Phase"
+ "Phase-preempting %{public}@ (phase=%d) to unblock frontier-phase %{public}@ (phase=%d)"
+ "Phased activity %{public}@ phase=%ld domainPriority=%ld"
+ "PhasedSchedulingEnabled"
+ "Recorded poor freeze quality for %@ (ratio: %.2f > threshold: %.2f, resident: %.1f MB, frozen: %.3f MB)"
+ "Rejecting phased submission of %{public}@: %{public}@"
+ "T@\"NSMutableDictionary\",&,N,V_intensivePreemptionReservations"
+ "TB,N,V_campoAllowListEnabled"
+ "Td,N,V_freezerDemotionCapDRAMFraction"
+ "Trial parameter MLFreezerAllowListCampoEnabled not found, using default: %d"
+ "Trial: ConcurrencyBoostingEnabled set to %d"
+ "Trial: PhasedSchedulingEnabled set to %d"
+ "_campoAllowListEnabled"
+ "_enqueueStringInterningCachePrepopulation"
+ "_enqueueTaskMetadataCachePrepopulation"
+ "_freezerDemotionCapDRAMFraction"
+ "_intensivePreemptionReservations"
+ "_snapshotTaskMetadataForActivity:"
+ "appstored"
+ "buildFreezerAllowList"
+ "campoAllowListEnabled"
+ "com.apple.appstored.ArcadePostPO"
+ "com.apple.appstored.ArcadePostSummary"
+ "domainPriority"
+ "effectiveDemotionCapMB"
+ "eligiblePendingPhasedActivitiesExcluding:atDate:"
+ "freezerDemotionCapDRAMFraction"
+ "holderHasLiveIntensivePreemptionReservation:atDate:"
+ "intensivePreemptionReservations"
+ "isConcurrencyBoostingEnabled"
+ "isPhaseSchedulingEnabled"
+ "isPhasedProcessingEnabled"
+ "isPhasedSchedulingActivity:"
+ "liveIntensivePreemptionReservationCountExcludingHolder:atDate:"
+ "phase"
+ "phaseFrontierForCandidateActivities:"
+ "phaseFrontierForCandidateActivities:includeRunningAndPrerunning:"
+ "phaseFrontierForGroupScopeWithRequester:runningActivities:"
+ "phaseOrderingForActivity:vs:"
+ "phasedPreemptionVictimInGroup:forFrontierRequester:"
+ "phasedSubmissionShouldDeferImmediateRun:"
+ "priorityForDomain:"
+ "refreshPhaseSchedulingGatesWithTrialManager:"
+ "refreshStaleTaskMetadata: excluded %lu stale rows from known high-frequency appstored activities from re-donation (rdar://181067888)"
+ "reserveIntensivePreemptedSlotForHolder:atDate:"
+ "setCampoAllowListEnabled:"
+ "setDomainPriority:"
+ "setFreezerDemotionCapDRAMFraction:"
+ "setIntensivePreemptionReservations:"
+ "setPhase:"
+ "support_concurrency_boosting"
+ "support_phased_processing"
+ "sweepExpiredIntensivePreemptionReservationsLocked:"
- "Failed to allocate memory for priority entries"
- "Failed to get priority list size"
- "Freezer resident memory %.1f MB, threshold %.1f MB"
- "Recorded poor freeze quality for %@ (ratio: %.2f > threshold: %.2f)"
- "_prepopulateStringInterningCache"
- "_prepopulateTaskMetadataCache"
```
