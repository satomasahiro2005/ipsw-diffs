## postersyncd

> `/System/Library/Frameworks/Contacts.framework/Support/postersyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x159e8` | `0x1b128` | **`+0x5740`** |
| `__TEXT.__oslogstring` | `0x1128` | `0x1449` | **`+0x321`** |
| `__TEXT.__cstring` | `0x587` | `0x850` | **`+0x2c9`** |
| `__TEXT.__eh_frame` | `0x388` | `0x638` | **`+0x2b0`** |
| `__TEXT.__objc_stubs` | `0x7e0` | `0x940` | **`+0x160`** |
| `__TEXT.__auth_stubs` | `0xe10` | `0xef0` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0xa49` | `0xaf1` | **`+0xa8`** |
| `__TEXT.__const` | `0xb88` | `0xc22` | **`+0x9a`** |
| `__TEXT.__unwind_info` | `0x420` | `0x4b0` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x215` | `0x295` | **`+0x80`** |
| `__DATA_CONST.__auth_got` | `0x710` | `0x780` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0x320` | `0x380` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x418` | `0x478` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x27c` | `0x2c4` | **`+0x48`** |
| `__DATA.__data` | `0xb80` | `0xbb0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x848` | `0x878` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x4ed` | `0x50f` | **`+0x22`** |
| `__DATA_CONST.__got` | `0x280` | `0x2a0` | **`+0x20`** |
| `__DATA.__common` | `0x38` | `0x50` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x29c` | `0x2ac` | **`+0x10`** |
| `__DATA.__objc_const` | `0x658` | `0x660` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x210` | `0x218` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-25.100.1.0.0
+25.200.1.0.0

-  Functions: 378
-  Symbols:   379
-  CStrings:  280
+  Functions: 411
+  Symbols:   397
+  CStrings:  311
Symbols:
+ _$s10Foundation4DateV17timeIntervalSinceySdACF
+ _$s10Foundation4UUIDV10uuidStringSSvg
+ _$s10Foundation4UUIDV36_unconditionallyBridgeFromObjectiveCyACSo6NSUUIDCSgFZ
+ _$s10Foundation4UUIDVMa
+ _$s10Foundation4UUIDVMn
+ _$s10Foundation4UUIDVSQAAMc
+ _$sShyxGs7CVarArg10FoundationMc
+ _$ss10_HashTableV12previousHole6beforeAB6BucketVAF_tF
+ _$ss11_SetStorageC8allocate8capacityAByxGSi_tFZ
+ _$ss15ContiguousArrayV034_makeUniqueAndReserveCapacityIfNotD0yyFyXl_Ts5
+ _$ss15ContiguousArrayV12_endMutationyyFyXl_Ts5
+ _$ss15ContiguousArrayV28_allocateBufferUninitialized15minimumCapacitys01_abD0VyxGSi_tFZ
+ _$ss15ContiguousArrayV36_reserveCapacityAssumingUniqueBuffer8oldCountySi_tFyXl_Ts5
+ _$ss15ContiguousArrayV37_appendElementAssumeUniqueAndCapacity_03newD0ySi_xntFyXl_Ts5
+ _$ss22_minimumMergeRunLengthyS2iF
+ _OBJC_CLASS_$_NSSortDescriptor
+ _swift_release_x3
+ _swift_retain_x22
CStrings:
+ "<CleanupCandidate: .emptyCurrentPosters. ("
+ "<CleanupCandidate: .staleDeletions. ("
+ "<UpdatePlan: .clearDeletion. Clear stale deletionDate on posters/images for contact identifier: "
+ "<UpdatePlan: .promoteRenderablePoster. Promote a renderable poster for contact identifier: "
+ "@\"<CNCancelable>\"48@0:8d16@?<v@?>24d32Q40"
+ "@48@0:8d16@?24d32Q40"
+ "EmptyCurrentPoster: %{public}ld contact(s) have an empty current poster with no renderable poster to promote: %{public}s"
+ "EmptyCurrentPoster: contact %{public}s had %{public}ld posters marked current"
+ "EmptyCurrentPoster: contact %{public}s has an empty current poster and no renderable poster to promote"
+ "EmptyCurrentPoster: demoted poster for %{public}s carried a watch image; watchWallpaperImageData will read nil until it is re-rendered"
+ "EmptyCurrentPoster: nothing to fix for %{public}s; the store changed under the scan"
+ "EmptyCurrentPoster: promoted a poster with a nil identifier for contact %{public}s; sync cannot match it and will duplicate it"
+ "EmptyCurrentPoster: promoted poster %{public}s over an empty current poster for contact %{public}s"
+ "afterDelay:performBlock:delayTolerance:qualityOfService:"
+ "contactIdentifier == %@ AND deletionDate != nil AND (isCurrent == YES OR lastUsedDate > deletionDate)"
+ "contactIdentifier == %@ AND deletionDate == nil"
+ "contactIdentifier IN %@ AND deletionDate == nil"
+ "deletionDate"
+ "deletionDate != nil AND (isCurrent == YES OR lastUsedDate > deletionDate)"
+ "emptyCurrentPoster"
+ "initWithKey:ascending:"
+ "isCurrent == YES AND deletionDate == nil AND contactIdentifier != nil"
+ "lastUsedDate"
+ "posterData"
+ "refreshObject:mergeChanges:"
+ "setDeletionDate:"
+ "setFetchBatchSize:"
+ "setIsCurrent:"
+ "setSortDescriptors:"
+ "staleDeletion"
+ "watchPosterImageData"
```
