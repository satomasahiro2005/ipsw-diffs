## postersyncd

> `/System/Library/Frameworks/Contacts.framework/Support/postersyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b128` | `0x1cbec` | **`+0x1ac4`** |
| `__TEXT.__oslogstring` | `0x1449` | `0x1219` | **`-0x230`** |
| `__DATA.__bss` | `0xc00` | `0xd00` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x878` | `0x948` | **`+0xd0`** |
| `__TEXT.__const` | `0xc22` | `0xcb2` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0xef0` | `0xf60` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x50f` | `0x563` | **`+0x54`** |
| `__TEXT.__objc_methname` | `0xaf1` | `0xb41` | **`+0x50`** |
| `__DATA.__objc_const` | `0x660` | `0x6a0` | **`+0x40`** |
| `__DATA_CONST.__auth_ptr` | `0x218` | `0x258` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x940` | `0x980` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x2c4` | `0x304` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x295` | `0x2d5` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x780` | `0x7b8` | **`+0x38`** |
| `__TEXT.__cstring` | `0x850` | `0x885` | **`+0x35`** |
| `__TEXT.__constg_swiftt` | `0x3fc` | `0x430` | **`+0x34`** |
| `__DATA.__objc_data` | `0x3c0` | `0x3e8` | **`+0x28`** |
| `__DATA.__data` | `0xbb0` | `0xbd0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2a0` | `0x2c0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x380` | `0x398` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x120` | `0x130` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4b0` | `0x4c0` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x40` | `0x44` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-25.200.1.0.0
+25.200.12.0.0

-  - /System/Library/PrivateFrameworks/AtomicsInternal.framework/AtomicsInternal

-  Functions: 411
-  Symbols:   397
-  CStrings:  311
+  Functions: 427
+  Symbols:   408
+  CStrings:  309
Symbols:
+ _$s10Foundation4DataVN
+ _$s18ContactsFoundation11CNDebouncerC4mode14windowStrategy11maxInterval9scheduler10downstream4sinkACyxGAA14CNDebounceModeV_AA0l6WindowF0_pSdSgSo11CNScheduler_pSoAO_pyxctcfc
+ _$s18ContactsFoundation11CNDebouncerCAAytRszlE11handleEventyyF
+ _$s18ContactsFoundation11CNDebouncerCMn
+ _$s18ContactsFoundation14CNDebounceModeV6settleACvgZ
+ _$s18ContactsFoundation14CNDebounceModeVMa
+ _$s18ContactsFoundation29CNDebounceFixedWindowStrategyCMa
+ _$s18ContactsFoundation29CNDebounceFixedWindowStrategyCyACSdcfc
+ _$sSD10FoundationE34_conditionallyBridgeFromObjectiveC_6resultSbSo12NSDictionaryC_SDyxq_GSgztFZ
+ _OBJC_CLASS_$_CNUnfairLock
+ _OBJC_CLASS_$_NSExpression
+ _OBJC_CLASS_$_NSExpressionDescription
+ _OBJC_CLASS_$_NSManagedObjectID
+ _objc_retain_x24
+ _swift_release_x1
+ _swift_retain_x1
+ _swift_retain_x19
+ _swift_unknownObjectRetain_n
- _$s15AtomicsInternal13ManagedAtomicCMn
- _$sShyxGs7CVarArg10FoundationMc
- _$ss15ContiguousArrayV034_makeUniqueAndReserveCapacityIfNotD0yyFyXl_Ts5
- _$ss15ContiguousArrayV12_endMutationyyFyXl_Ts5
- _$ss15ContiguousArrayV36_reserveCapacityAssumingUniqueBuffer8oldCountySi_tFyXl_Ts5
- _$ss15ContiguousArrayV37_appendElementAssumeUniqueAndCapacity_03newD0ySi_xntFyXl_Ts5
- _objc_retain_x9
CStrings:
+ "Debouncing a contact store change notification for background cleanup handling"
+ "Debouncing a poster store change notification for background cleanup handling"
+ "debouncer"
+ "existingObjectWithID:error:"
+ "expressionForEvaluatedObject"
+ "isCurrent == YES AND deletionDate == nil AND contactIdentifier == %@"
+ "lock"
+ "pendingTriggers"
+ "pendingTriggersLock"
+ "setExpression:"
+ "setExpressionResultType:"
+ "setName:"
+ "unlock"
- "Dispatching a contact store change notification for background cleanup handling"
- "Dispatching a poster store change notification for background cleanup handling"
- "END: Background cleanup for a contact store change notification"
- "END: Background cleanup for a poster store change notification"
- "Ignoring contact store change notification overlapping with a queued cleanup request"
- "Ignoring poster store change notification overlapping with a queued cleanup request"
- "START: Background cleanup for a contact store change notification"
- "START: Background cleanup for a poster store change notification"
- "Unexpectedly started cleanup with request flag unset, returning early"
- "cleanupRequested"
- "contactIdentifier IN %@ AND deletionDate == nil"
- "posterData"
- "refreshObject:mergeChanges:"
- "setFetchBatchSize:"
- "v8@?0"
```
