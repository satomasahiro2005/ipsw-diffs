## BackBoardServices

> `/System/Library/PrivateFrameworks/BackBoardServices.framework/BackBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x87258` | `0x897a4` | **`+0x254c`** |
| `__AUTH_CONST.__objc_const` | `0x11a08` | `0x121b8` | **`+0x7b0`** |
| `__TEXT.__objc_methlist` | `0x88ac` | `0x8ca4` | **`+0x3f8`** |
| `__TEXT.__cstring` | `0xb6ad` | `0xb8c3` | **`+0x216`** |
| `__AUTH_CONST.__cfstring` | `0xa0a0` | `0xa2a0` | **`+0x200`** |
| `__DATA_CONST.__objc_selrefs` | `0x2ef8` | `0x3078` | **`+0x180`** |
| `__AUTH.__objc_data` | `0x2378` | `0x24b8` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x2248` | `0x2330` | **`+0xe8`** |
| `__TEXT.__gcc_except_tab` | `0x5d8` | `0x558` | **`-0x80`** |
| `__AUTH_CONST.__const` | `0x15a8` | `0x1608` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0x8cc` | `0x918` | **`+0x4c`** |
| `__TEXT.__oslogstring` | `0x260a` | `0x2651` | **`+0x47`** |
| `__DATA_CONST.__const` | `0x18f8` | `0x1938` | **`+0x40`** |
| `__AUTH_CONST.__objc_intobj` | `0x180` | `0x1b0` | **`+0x30`** |
| `__DATA.__bss` | `0x5f0` | `0x620` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x7a8` | `0x7d0` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x5c0` | `0x5e0` | **`+0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0x400` | `0x418` | **`+0x18`** |
| `__TEXT.__const` | `0x3d0` | `0x3e8` | **`+0x18`** |

### Other Changes

```diff

-860.0.1.0.0
+866.0.0.0.0

-  Functions: 3377
-  Symbols:   6403
-  CStrings:  1925
+  Functions: 3466
+  Symbols:   6553
+  CStrings:  1944
Symbols:
+ +[BKSHIDEventDeferringNamespacePredicate anyContinuityDisplay]
+ +[BKSHIDEventDeferringNamespacePredicate protobufSchema]
+ +[BKSHIDEventDeferringNamespacePredicate supportsSecureCoding]
+ +[BKSHIDEventDeferringReachabilityStatus new]
+ +[BKSHIDEventDeferringReachabilityStatus supportsSecureCoding]
+ +[BKSTouchDeliveryOccurrence supportsSecureCoding]
+ -[BKSHIDEventAuthenticationMessage senderID]
+ -[BKSHIDEventDeferringNamespacePredicate _descriptorType]
+ -[BKSHIDEventDeferringNamespacePredicate _initWithType:]
+ -[BKSHIDEventDeferringNamespacePredicate copyWithZone:]
+ -[BKSHIDEventDeferringNamespacePredicate description]
+ -[BKSHIDEventDeferringNamespacePredicate encodeWithCoder:]
+ -[BKSHIDEventDeferringNamespacePredicate hash]
+ -[BKSHIDEventDeferringNamespacePredicate initForProtobufDecoding]
+ -[BKSHIDEventDeferringNamespacePredicate initWithCoder:]
+ -[BKSHIDEventDeferringNamespacePredicate init]
+ -[BKSHIDEventDeferringNamespacePredicate isEqual:]
+ -[BKSHIDEventDeferringReachabilityStatus appendDescriptionToStream:]
+ -[BKSHIDEventDeferringReachabilityStatus deferringGraphGeneration]
+ -[BKSHIDEventDeferringReachabilityStatus description]
+ -[BKSHIDEventDeferringReachabilityStatus encodeWithCoder:]
+ -[BKSHIDEventDeferringReachabilityStatus hash]
+ -[BKSHIDEventDeferringReachabilityStatus initWithCoder:]
+ -[BKSHIDEventDeferringReachabilityStatus initWithReachability:deferringGraphGeneration:]
+ -[BKSHIDEventDeferringReachabilityStatus init]
+ -[BKSHIDEventDeferringReachabilityStatus isEqual:]
+ -[BKSHIDEventDeferringReachabilityStatus isReachableRespectingConstraints]
+ -[BKSHIDEventDeferringReachabilityStatus isReachable]
+ -[BKSHIDEventDeferringReachabilityStatus reachability]
+ -[BKSHIDEventDeliveryManager authenticationMessage:matchesDeferringNamespacePredicate:]
+ -[BKSHIDEventDeliveryManager observeReachabilityOfSelectionTarget:handler:]
+ -[BKSHIDEventDeliveryManager observeReachabilityOfSelectionTarget:respectingConstraints:handler:]
+ -[BKSHIDEventObserver _lock_dispatchReachabilityForStatuses:callouts:]
+ -[BKSHIDEventObserver _lock_postReachabilityTargetsToServer]
+ -[BKSHIDEventObserver addReachabilityObservationForTarget:handler:]
+ -[BKSHIDEventObserver addReachabilityObservationForTarget:respectingConstraints:handler:]
+ -[BKSHIDEventObserver reachableObservedTargetsDidChange:forTargets:]
+ -[BKSMutableHIDEventAuthenticationMessage setSenderID:]
+ -[BKSTouchDeliveryObservationService _deliverOccurrence:toObserver:]
+ -[BKSTouchDeliveryObservationService _queue_addObserver:forTouchIdentifier:kinds:]
+ -[BKSTouchDeliveryObservationService _queue_aggregateGeneralKinds]
+ -[BKSTouchDeliveryObservationService _queue_aggregateKindsForTouchIdentifier:]
+ -[BKSTouchDeliveryObservationService _queue_aggregateKindsFromMapTable:]
+ -[BKSTouchDeliveryObservationService _queue_observerKindsForTouchIdentifier:]
+ -[BKSTouchDeliveryObservationService _queue_syncGeneralKindsToRemote]
+ -[BKSTouchDeliveryObservationService _queue_syncKindsForTouchIdentifier:]
+ -[BKSTouchDeliveryObservationService addObserver:forOccurrenceKinds:]
+ -[BKSTouchDeliveryObservationService addObserver:forTouchIdentifier:occurrenceKinds:]
+ -[BKSTouchDeliveryObservationService generalObserverToKinds]
+ -[BKSTouchDeliveryObservationService lastGeneralKindsSent]
+ -[BKSTouchDeliveryObservationService lastKindsSentForTouchIdentifier]
+ -[BKSTouchDeliveryObservationService setGeneralObserverToKinds:]
+ -[BKSTouchDeliveryObservationService setLastGeneralKindsSent:]
+ -[BKSTouchDeliveryObservationService setLastKindsSentForTouchIdentifier:]
+ -[BKSTouchDeliveryObservationService setTouchIdentifierToObserverKinds:]
+ -[BKSTouchDeliveryObservationService touchIdentifierToObserverKinds]
+ -[BKSTouchDeliveryOccurrence appendDescriptionToStream:]
+ -[BKSTouchDeliveryOccurrence contextID]
+ -[BKSTouchDeliveryOccurrence copyWithZone:]
+ -[BKSTouchDeliveryOccurrence description]
+ -[BKSTouchDeliveryOccurrence detached]
+ -[BKSTouchDeliveryOccurrence encodeWithCoder:]
+ -[BKSTouchDeliveryOccurrence hash]
+ -[BKSTouchDeliveryOccurrence initWithCoder:]
+ -[BKSTouchDeliveryOccurrence initWithKind:touchIdentifier:transducerType:detached:contextID:pid:]
+ -[BKSTouchDeliveryOccurrence isEqual:]
+ -[BKSTouchDeliveryOccurrence kind]
+ -[BKSTouchDeliveryOccurrence pid]
+ -[BKSTouchDeliveryOccurrence touchIdentifier]
+ -[BKSTouchDeliveryOccurrence transducerType]
+ -[BKSTouchDeliveryUpdate setTransducerType:]
+ -[BKSTouchDeliveryUpdate transducerType]
+ -[_BKDeferringReachabilitySubscription .cxx_destruct]
+ -[_BKDeferringReachabilitySubscription handler]
+ -[_BKDeferringReachabilitySubscription hasDeliveredInitialState]
+ -[_BKDeferringReachabilitySubscription lastStatus]
+ -[_BKDeferringReachabilitySubscription respectsConstraints]
+ -[_BKDeferringReachabilitySubscription setHandler:]
+ -[_BKDeferringReachabilitySubscription setHasDeliveredInitialState:]
+ -[_BKDeferringReachabilitySubscription setLastStatus:]
+ -[_BKDeferringReachabilitySubscription setRespectsConstraints:]
+ -[_BKDeferringReachabilitySubscription setTarget:]
+ -[_BKDeferringReachabilitySubscription target]
+ GCC_except_table1209
+ GCC_except_table1226
+ GCC_except_table1228
+ GCC_except_table1229
+ GCC_except_table134
+ GCC_except_table1345
+ GCC_except_table1369
+ GCC_except_table1392
+ GCC_except_table1566
+ GCC_except_table1571
+ GCC_except_table1581
+ GCC_except_table1719
+ GCC_except_table1828
+ GCC_except_table1961
+ GCC_except_table2089
+ GCC_except_table2098
+ GCC_except_table2227
+ GCC_except_table2341
+ GCC_except_table2343
+ GCC_except_table2389
+ GCC_except_table2620
+ GCC_except_table2814
+ GCC_except_table2821
+ GCC_except_table283
+ GCC_except_table284
+ GCC_except_table285
+ GCC_except_table3135
+ GCC_except_table3161
+ GCC_except_table3323
+ GCC_except_table3357
+ GCC_except_table3358
+ OBJC_IVAR_$_BKSHIDEventAuthenticationMessage._senderID
+ _BKSTouchDeliveryOccurrenceKindFromUpdateType
+ _NSStringFromBKSHIDEventDeferringReachability
+ _NSStringFromBKSTouchDeliveryOccurrenceKind
+ _OBJC_CLASS_$_BKSHIDEventDeferringNamespacePredicate
+ _OBJC_CLASS_$_BKSHIDEventDeferringReachabilityStatus
+ _OBJC_CLASS_$_BKSTouchDeliveryOccurrence
+ _OBJC_CLASS_$_NSMutableIndexSet
+ _OBJC_CLASS_$__BKDeferringReachabilitySubscription
+ _OBJC_IVAR_$_BKSHIDEventDeferringNamespacePredicate._descriptorType
+ _OBJC_IVAR_$_BKSHIDEventDeferringReachabilityStatus._deferringGraphGeneration
+ _OBJC_IVAR_$_BKSHIDEventDeferringReachabilityStatus._reachability
+ _OBJC_IVAR_$_BKSHIDEventObserver._lock_reachabilitySubscriptions
+ _OBJC_IVAR_$_BKSTouchDeliveryObservationService._generalObserverToKinds
+ _OBJC_IVAR_$_BKSTouchDeliveryObservationService._lastGeneralKindsSent
+ _OBJC_IVAR_$_BKSTouchDeliveryObservationService._lastKindsSentForTouchIdentifier
+ _OBJC_IVAR_$_BKSTouchDeliveryObservationService._touchIdentifierToObserverKinds
+ _OBJC_IVAR_$_BKSTouchDeliveryOccurrence._contextID
+ _OBJC_IVAR_$_BKSTouchDeliveryOccurrence._detached
+ _OBJC_IVAR_$_BKSTouchDeliveryOccurrence._kind
+ _OBJC_IVAR_$_BKSTouchDeliveryOccurrence._pid
+ _OBJC_IVAR_$_BKSTouchDeliveryOccurrence._touchIdentifier
+ _OBJC_IVAR_$_BKSTouchDeliveryOccurrence._transducerType
+ _OBJC_IVAR_$_BKSTouchDeliveryUpdate._transducerType
+ _OBJC_IVAR_$__BKDeferringReachabilitySubscription._handler
+ _OBJC_IVAR_$__BKDeferringReachabilitySubscription._hasDeliveredInitialState
+ _OBJC_IVAR_$__BKDeferringReachabilitySubscription._lastStatus
+ _OBJC_IVAR_$__BKDeferringReachabilitySubscription._respectsConstraints
+ _OBJC_IVAR_$__BKDeferringReachabilitySubscription._target
+ _OBJC_METACLASS_$_BKSHIDEventDeferringNamespacePredicate
+ _OBJC_METACLASS_$_BKSHIDEventDeferringReachabilityStatus
+ _OBJC_METACLASS_$_BKSTouchDeliveryOccurrence
+ _OBJC_METACLASS_$__BKDeferringReachabilitySubscription
+ __OBJC_$_CLASS_METHODS_BKSHIDEventDeferringNamespacePredicate
+ __OBJC_$_CLASS_METHODS_BKSHIDEventDeferringReachabilityStatus
+ __OBJC_$_CLASS_METHODS_BKSTouchDeliveryOccurrence
+ __OBJC_$_CLASS_PROP_LIST_BKSHIDEventDeferringNamespacePredicate
+ __OBJC_$_CLASS_PROP_LIST_BKSHIDEventDeferringReachabilityStatus
+ __OBJC_$_CLASS_PROP_LIST_BKSTouchDeliveryOccurrence
+ __OBJC_$_INSTANCE_METHODS_BKSHIDEventDeferringNamespacePredicate
+ __OBJC_$_INSTANCE_METHODS_BKSHIDEventDeferringReachabilityStatus
+ __OBJC_$_INSTANCE_METHODS_BKSTouchDeliveryOccurrence
+ __OBJC_$_INSTANCE_METHODS__BKDeferringReachabilitySubscription
+ __OBJC_$_INSTANCE_VARIABLES_BKSHIDEventDeferringNamespacePredicate
+ __OBJC_$_INSTANCE_VARIABLES_BKSHIDEventDeferringReachabilityStatus
+ __OBJC_$_INSTANCE_VARIABLES_BKSTouchDeliveryOccurrence
+ __OBJC_$_INSTANCE_VARIABLES__BKDeferringReachabilitySubscription
+ __OBJC_$_PROP_LIST_BKSHIDEventDeferringNamespacePredicate
+ __OBJC_$_PROP_LIST_BKSHIDEventDeferringReachabilityStatus
+ __OBJC_$_PROP_LIST_BKSTouchDeliveryOccurrence
+ __OBJC_$_PROP_LIST__BKDeferringReachabilitySubscription
+ __OBJC_CLASS_PROTOCOLS_$_BKSHIDEventDeferringNamespacePredicate
+ __OBJC_CLASS_PROTOCOLS_$_BKSHIDEventDeferringReachabilityStatus
+ __OBJC_CLASS_PROTOCOLS_$_BKSTouchDeliveryOccurrence
+ __OBJC_CLASS_RO_$_BKSHIDEventDeferringNamespacePredicate
+ __OBJC_CLASS_RO_$_BKSHIDEventDeferringReachabilityStatus
+ __OBJC_CLASS_RO_$_BKSTouchDeliveryOccurrence
+ __OBJC_CLASS_RO_$__BKDeferringReachabilitySubscription
+ __OBJC_METACLASS_RO_$_BKSHIDEventDeferringNamespacePredicate
+ __OBJC_METACLASS_RO_$_BKSHIDEventDeferringReachabilityStatus
+ __OBJC_METACLASS_RO_$_BKSTouchDeliveryOccurrence
+ __OBJC_METACLASS_RO_$__BKDeferringReachabilitySubscription
+ ___56+[BKSHIDEventDeferringNamespacePredicate protobufSchema]_block_invoke
+ ___56+[BKSHIDEventDeferringNamespacePredicate protobufSchema]_block_invoke_2
+ ___56-[BKSTouchDeliveryOccurrence appendDescriptionToStream:]_block_invoke
+ ___62+[BKSHIDEventDeferringNamespacePredicate anyContinuityDisplay]_block_invoke
+ ___68-[BKSHIDEventDeferringReachabilityStatus appendDescriptionToStream:]_block_invoke
+ ___69-[BKSTouchDeliveryObservationService addObserver:forOccurrenceKinds:]_block_invoke
+ ___70-[BKSHIDEventObserver _lock_dispatchReachabilityForStatuses:callouts:]_block_invoke
+ ___85-[BKSTouchDeliveryObservationService addObserver:forTouchIdentifier:occurrenceKinds:]_block_invoke
+ ___89-[BKSHIDEventObserver addReachabilityObservationForTarget:respectingConstraints:handler:]_block_invoke
+ ___block_descriptor_60_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_74_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_77_e8_32s40r48r56r64r_e5_v8?0ls32l8r40l8r48l8r56l8r64l8
+ ___sLegacyDefaultKinds_block_invoke
+ _anyContinuityDisplay.__continuity
+ _anyContinuityDisplay.onceToken
+ _sIndexSetFromKinds
+ _sLegacyDefaultKinds
+ _sLegacyDefaultKinds.once
+ _sLegacyDefaultKinds.set
- -[BKSTouchDeliveryObservationService _queue_addObserver:forTouchIdentifier:]
- -[BKSTouchDeliveryObservationService _queue_observersForTouchIdentifier:]
- -[BKSTouchDeliveryObservationService _queue_removeObserversForTouchIdentifier:]
- -[BKSTouchDeliveryObservationService generalObservers]
- -[BKSTouchDeliveryObservationService setGeneralObservers:]
- -[BKSTouchDeliveryObservationService setTouchIdentifierToObserverLists:]
- -[BKSTouchDeliveryObservationService touchIdentifierToObserverLists]
- GCC_except_table118
- GCC_except_table1181
- GCC_except_table1192
- GCC_except_table1194
- GCC_except_table1195
- GCC_except_table1311
- GCC_except_table1335
- GCC_except_table1358
- GCC_except_table1532
- GCC_except_table1537
- GCC_except_table1547
- GCC_except_table1685
- GCC_except_table1794
- GCC_except_table1927
- GCC_except_table2055
- GCC_except_table2064
- GCC_except_table2193
- GCC_except_table2305
- GCC_except_table2307
- GCC_except_table2348
- GCC_except_table2552
- GCC_except_table267
- GCC_except_table268
- GCC_except_table269
- GCC_except_table2727
- GCC_except_table2734
- GCC_except_table3046
- GCC_except_table3072
- GCC_except_table3234
- GCC_except_table3268
- GCC_except_table3269
- _OBJC_IVAR_$_BKSTouchDeliveryObservationService._generalObservers
- _OBJC_IVAR_$_BKSTouchDeliveryObservationService._touchIdentifierToObserverLists
- ___50-[BKSTouchDeliveryObservationService addObserver:]_block_invoke
- ___69-[BKSTouchDeliveryObservationService addObserver:forTouchIdentifier:]_block_invoke
- ___block_descriptor_52_e8_32s40s_e5_v8?0ls32l8s40l8
- ___block_descriptor_60_e8_32s40r48r_e5_v8?0lr40l8s32l8r48l8
- ___block_descriptor_77_e8_32s40s_e5_v8?0ls32l8s40l8
CStrings:
+ "\n"
+ "("
+ "+[BKSHIDEventDeferringReachabilityStatus new]"
+ "-[BKSHIDEventDeferringReachabilityStatus init]"
+ "-init is not allowed on BKSHIDEventDeferringNamespacePredicate"
+ "BKSHIDEventDeferringNamespacePredicate cannot be subclassed"
+ "BKSHIDEventDeferringNamespacePredicate.m"
+ "BKSHIDEventDeferringReachabilityStatus.m"
+ "BKSSystemShellDidReconnect-21000323"
+ "Ba"
+ "[BKSHIDEventObserver] reachability for target %{public}@ -> %{public}@ (generation: %ld)"
+ "_descriptorType"
+ "add general observer kinds:%{public}@"
+ "add observer:%{public}@ for touch:%X kinds:%{public}@"
+ "backboardd-attr-cache-21000323"
+ "blockedByConstraints"
+ "cannot directly allocate BKSHIDEventDeferringReachabilityStatus"
+ "deferringGraphGeneration"
+ "descriptorType"
+ "downEvent"
+ "handler"
+ "isReachable"
+ "isReachableRespectingConstraints"
+ "kind"
+ "reachability"
+ "reachability<%@>"
+ "reachable"
+ "remove observer:%{public}@"
+ "transducerType"
+ "unreachable"
+ "update: occurrence %{public}@ to %{public}@"
+ "update: up for %X to %{public}@"
- "'"
- "BKSSystemShellDidReconnect-21000319"
- "BKSTouchDeliveryObservationService.m"
- "BQ"
- "NO"
- "add observer"
- "add observer:%{public}@"
- "add observer:%{public}@ for touch:%X"
- "addObserver:forTouchIdentifier: table:%{public}@"
- "backboardd-attr-cache-21000319"
- "update: detach to %{public}@"
- "update: up for %X to pid:%{public}@"
- "update: up to %{public}@"
```
