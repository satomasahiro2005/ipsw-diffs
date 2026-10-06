## dasd

> `/usr/libexec/dasd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x173078` | `0x1728e0` | **`-0x798`** |
| `__TEXT.__objc_methname` | `0x2d86d` | `0x2db0d` | **`+0x2a0`** |
| `__DATA.__objc_const` | `0x33910` | `0x33b70` | **`+0x260`** |
| `__TEXT.__oslogstring` | `0x16089` | `0x16189` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x4ed8` | `0x4fa0` | **`+0xc8`** |
| `__TEXT.__objc_methlist` | `0x12e2c` | `0x12ee4` | **`+0xb8`** |
| `__DATA.__objc_data` | `0x4818` | `0x48b8` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x4e10` | `0x4e98` | **`+0x88`** |
| `__TEXT.__objc_stubs` | `0x1a960` | `0x1a9e0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x100d6` | `0x10146` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0x9a88` | `0x9ae8` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0x114a0` | `0x114e0` | **`+0x40`** |
| `__DATA.__data` | `0x2160` | `0x2180` | **`+0x20`** |
| `__TEXT.__const` | `0x1538` | `0x1558` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x1c68` | `0x1c88` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x4e44` | `0x4e28` | **`-0x1c`** |
| `__DATA.__objc_ivar` | `0x15e8` | `0x15fc` | **`+0x14`** |
| `__DATA.__bss` | `0x1230` | `0x1220` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x6f0` | `0x700` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xc78` | `0xc70` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x5b0` | `0x5b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`
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

-2463.0.0.502.1
+2467.0.9.0.0

-  Functions: 8248
-  Symbols:   1012
-  CStrings:  12257
+  Functions: 8260
+  Symbols:   1011
+  CStrings:  12289
Symbols:
- _OBJC_CLASS_$_NSMutableOrderedSet
CStrings:
+ "@"
+ "@216@0:8{?=QQQQQQQQQQQQQQQQQQQQQQQQQ}16"
+ "B16@?0@\"PPSMetric\"8"
+ "Excluding %@ from freeze candidates: poor freeze quality within %.1fh"
+ "Falling back to default produced result node creation due to unsuccessful node factorization!"
+ "Falling back to default task dependency graph node creation due to unsuccessful node factorization!"
+ "ForcedDeferral"
+ "ForcedRun"
+ "FreezerMaxAppFootprintMB"
+ "FreezerRatioFilterLookbackHours"
+ "FreezerResidentToFrozenRatioThreshold"
+ "Loaded trial parameter FreezerMaxAppFootprintMB: %.1f"
+ "Loaded trial parameter FreezerRatioFilterLookbackHours: %.1f"
+ "Loaded trial parameter FreezerResidentToFrozenRatioThreshold: %.2f"
+ "Pruned %lu stale poor-freeze-quality entries"
+ "Recorded poor freeze quality for %@ (ratio: %.2f > threshold: %.2f)"
+ "Skipping %@ for freezer: footprint %.1f MB exceeds limit %.1f MB"
+ "Skipping %@ suspension because policyBypassEnabled is set"
+ "Stale TaskMetadata refresh expired after activity scan"
+ "T@\"NSMutableDictionary\",&,N,V_entries"
+ "T@\"NSMutableDictionary\",&,N,V_poorFreezeQualityApps"
+ "T@\"NSString\",R,C,N,V_value"
+ "T@,&,N,V_value"
+ "TQ,N,V_frequency"
+ "TQ,N,V_nextSequenceNumber"
+ "TQ,N,V_sequenceNumber"
+ "Td,N,V_freezerMaxAppFootprintMB"
+ "Td,N,V_freezerRatioFilterLookbackHours"
+ "Td,N,V_freezerResidentToFrozenRatioThreshold"
+ "Td,R,N,V_donationTimestamp"
+ "Using default budget mapping"
+ "Using trial budget mapping: %@"
+ "_DASInternedStringRecord"
+ "_DASLFUCacheEntry"
+ "_discoverMetricsMatching:"
+ "_discoverStringIDReferencingColumns"
+ "_donationTimestamp"
+ "_entries"
+ "_evictLeastFrequentEntry"
+ "_freezerMaxAppFootprintMB"
+ "_freezerRatioFilterLookbackHours"
+ "_freezerResidentToFrozenRatioThreshold"
+ "_frequency"
+ "_nextSequenceNumber"
+ "_poorFreezeQualityApps"
+ "_sequenceNumber"
+ "_value"
+ "com.apple.CloudKit.SyncEngine"
+ "discoverCategoriesReferencingTaskID"
+ "discoverCategoriesReferencingTaskID: PPSClientInterface metadata unavailable"
+ "discoverCategoriesReferencingTaskID: found %lu TaskID-bearing categories"
+ "donationTimestamp"
+ "entries"
+ "forceRunActivities:bypassingPolicies:"
+ "freezerMaxAppFootprintMB"
+ "freezerRatioFilterLookbackHours"
+ "freezerResidentToFrozenRatioThreshold"
+ "frequency"
+ "initWithValue:donationTimestamp:"
+ "isPoorFreezeQualityInLookbackWindow:"
+ "isStartEvent:"
+ "isUsed"
+ "nextSequenceNumber"
+ "policyBypassEnabled"
+ "poorFreezeQualityApps"
+ "pruneStalePoorFreezeQualityEntries"
+ "recordPoorFreezeQualityForProcessName:"
+ "refreshStaleStringInterning: discovered %lu *StringID columns across %lu categories"
+ "refreshStaleTaskMetadata: %lu unique active TaskIDs from %lu categories (%lu failed)"
+ "refreshStaleTaskMetadata: %{public}@ returned %lu events"
+ "refreshStaleTaskMetadata: all %lu category queries failed — assuming all stale TaskIDs are active"
+ "refreshStaleTaskMetadata: error querying %{public}@: %{public}@"
+ "refreshStaleTaskMetadata: expired during category scan at %{public}@"
+ "refreshStaleTaskMetadata: querying %lu TaskID-bearing categories"
+ "refreshStaleTaskMetadata: schema discovery unavailable, falling back to hard-coded categories"
+ "removeObjectsForKeys:"
+ "sequenceNumber"
+ "setEntries:"
+ "setFreezerMaxAppFootprintMB:"
+ "setFreezerRatioFilterLookbackHours:"
+ "setFreezerResidentToFrozenRatioThreshold:"
+ "setFrequency:"
+ "setNextSequenceNumber:"
+ "setPolicyBypassEnabled:"
+ "setPoorFreezeQualityApps:"
+ "setSequenceNumber:"
+ "setValue:"
+ "shouldLogActivityToBGSQL:"
+ "unregisterSystemTaskWithIdentifier: Task %{public}@ from UID %d, PID %d not found or already unregistered"
+ "v28@0:8@\"NSArray\"16B24"
+ "v32@0:8Q16^{?=QQQQQQQQQQQQQQQQQQQQQQQQQ}24"
+ "v32@?0@\"<NSCopying>\"8@\"_DASLFUCacheEntry\"16^B24"
+ "{?=QQQQQQQQQQQQQQQQQQQQQQQQQ}"
+ "{?=QQQQQQQQQQQQQQQQQQQQQQQQQ}16@0:8"
- "@\"_DASFeatureDurationTracker\""
- "@200@0:8{?=QQQQQQQQQQQQQQQQQQQQQQQ}16"
- "Activity %{public}@ should suspend, running for %{public}@ mins (remaining feature runtime limit %@) mins"
- "Both activity queries failed — assuming all stale TaskIDs are active"
- "Error querying TaskCheckpoint for stale refresh: %{public}@"
- "Error querying TaskInstanceData for stale refresh: %{public}@"
- "Exceed Feature Runtime %f mins > %f mins"
- "Falling back to default produced result node creation due to unsuccesful node factorization!"
- "Falling back to default task dependency graph node creation due to unsuccesful node factorization!"
- "Feature %@ has consumed %.1fs, remaining run time budget %.1fs"
- "Feature code %d has utilized %f < %f"
- "Invalid budget mapping string from Trial; falling back to default"
- "Rejecting submission of %@ with error: %@!"
- "RequiresWidgetBudget"
- "Stale TaskMetadata refresh expired after checkpoint query"
- "Stale TaskMetadata refresh expired after instance query"
- "T@\"NSMutableDictionary\",&,N,V_freqToKeys"
- "T@\"NSMutableDictionary\",&,N,V_keyToFreq"
- "T@\"NSMutableDictionary\",&,N,V_keyToValue"
- "T@\"_DASFeatureDurationTracker\",&,N,V_featureDurationTracker"
- "TQ,N,V_minFreq"
- "Updated allocation strategy: %u"
- "Using new budget mapping: %@"
- "_discoverStringIDColumns"
- "_featureDurationTracker"
- "_freqToKeys"
- "_keyToFreq"
- "_keyToValue"
- "_minFreq"
- "exhaustedRuntimeFeatureCodes"
- "exhaustedRuntimeFeatureCodesAssociatedWithActivity:"
- "featureDurationLimitAppliesToActivity:"
- "featureHasNoRemainingRuntimeForActivity:"
- "featureHasRunTime:"
- "freqToKeys"
- "keyToFreq"
- "keyToValue"
- "maximumRemainingFeatureDurationForActivity:"
- "minFreq"
- "orderedSet"
- "refreshStaleStringInterning: PPSClientInterface metadata unavailable"
- "refreshStaleStringInterning: discovered %lu categories with %lu *StringID columns"
- "refreshStaleTaskMetadata: %lu unique active TaskIDs from checkpoint+instance"
- "refreshStaleTaskMetadata: TaskCheckpoint returned %lu events"
- "refreshStaleTaskMetadata: TaskInstanceData returned %lu events"
- "refreshStaleTaskMetadata: querying TaskCheckpoint..."
- "refreshStaleTaskMetadata: querying TaskInstanceData..."
- "remainingDurationForFeature:"
- "setFeatureDurationTracker:"
- "setFreqToKeys:"
- "setKeyToFreq:"
- "setKeyToValue:"
- "setMinFreq:"
- "setWidgetID:"
- "shouldLogCheckpointForActivity:"
- "test"
- "unregisterSystemTaskWithIdentifier: Task %{public}@ from UID %d, PID %d not found"
- "updateKeyFrequency:"
- "v32@0:8Q16^{?=QQQQQQQQQQQQQQQQQQQQQQQ}24"
- "widgetImprovedAllocStrat"
- "{?=QQQQQQQQQQQQQQQQQQQQQQQ}"
- "{?=QQQQQQQQQQQQQQQQQQQQQQQ}16@0:8"
```
