## BackBoardHIDEventFoundation

> `/System/Library/PrivateFrameworks/BackBoardHIDEventFoundation.framework/BackBoardHIDEventFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a3c4` | `0x3c54c` | **`+0x2188`** |
| `__AUTH_CONST.__objc_const` | `0x5cb8` | `0x5e88` | **`+0x1d0`** |
| `__TEXT.__objc_methlist` | `0x2048` | `0x2160` | **`+0x118`** |
| `__DATA_CONST.__objc_selrefs` | `0x1320` | `0x13e8` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0x31c7` | `0x326d` | **`+0xa6`** |
| `__DATA_CONST.__const` | `0x12b8` | `0x1350` | **`+0x98`** |
| `__AUTH_CONST.__cfstring` | `0x2a20` | `0x2a80` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0xb78` | `0xbd8` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2f6a` | `0x2fc9` | **`+0x5f`** |
| `__TEXT.__gcc_except_tab` | `0x3d0` | `0x39c` | **`-0x34`** |
| `__DATA.__objc_ivar` | `0x420` | `0x44c` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x3d8` | `0x3f0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x8f0` | `0x8e8` | **`-0x8`** |

### Other Changes

```diff

-860.0.1.0.0
+866.0.0.0.0

-  Functions: 1016
-  Symbols:   2278
-  CStrings:  658
+  Functions: 1045
+  Symbols:   2325
+  CStrings:  664
Symbols:
+ -[BKEventDeferringEnvironmentGraph _nodeIsReachableFromSupernode:selectionPath:]
+ -[BKHIDEventDeliveryManager _lock_computePendingReachability]
+ -[BKHIDEventDeliveryManager _lock_reachabilityStatusForSelectionTarget:]
+ -[BKHIDEventDeliveryManager addAuthenticationMessageNamespaceResolver:]
+ -[BKHIDEventDeliveryManager authenticationMessage:matchesDeferringNamespacePredicate:]
+ -[BKHIDEventDeliveryManager deferringSelectionTargetIsReachable:]
+ -[BKHIDEventDeliveryManager evaluateReachability]
+ -[BKHIDEventDeliveryManager reachabilityStatusForSelectionTarget:]
+ -[BKHIDEventDeliveryManagerServer authenticationMessage:matchesDeferringNamespacePredicate:]
+ -[BKHIDEventDeliveryObserverServer setReachabilityObservationTargets:]
+ -[BKHIDEventDeliveryObserverService _lock_rebuildAllReachabilityTargets]
+ -[BKHIDEventDeliveryObserverService connection:setReachabilityObservationTargets:]
+ -[BKHIDEventDeliveryObserverService deliveryManager]
+ -[BKHIDEventDeliveryObserverService reachabilityObservationTargets]
+ -[BKHIDEventDeliveryObserverService reachableObservationTargetsDidChange:reason:]
+ -[BKHIDEventDeliveryObserverService setDeliveryManager:]
+ -[BKHIDSystem performWhenDeliveryManagerAvailable:]
+ -[BKIOHIDService _appendFieldsToFormatter:]
+ -[BKIOHIDService appendDescriptionToStream:]
+ -[BKIOHIDService productName]
+ -[BKIOHIDService transport]
+ GCC_except_table213
+ GCC_except_table248
+ GCC_except_table301
+ GCC_except_table359
+ GCC_except_table372
+ GCC_except_table375
+ GCC_except_table381
+ GCC_except_table384
+ GCC_except_table621
+ GCC_except_table624
+ GCC_except_table658
+ GCC_except_table707
+ GCC_except_table768
+ GCC_except_table780
+ GCC_except_table812
+ _OBJC_CLASS_$_BKSHIDEventDeferringReachabilityStatus
+ _OBJC_CLASS_$_CAWindowServer
+ _OBJC_CLASS_$_NSHashTable
+ _OBJC_IVAR_$_BKHIDEventDeliveryManager._authenticationMessageNamespaceResolvers
+ _OBJC_IVAR_$_BKHIDEventDeliveryManager._lock_pendingReachableTargets
+ _OBJC_IVAR_$_BKHIDEventDeliveryObserverService._deliveryManager
+ _OBJC_IVAR_$_BKHIDEventDeliveryObserverService._lock_allReachabilityTargets
+ _OBJC_IVAR_$_BKHIDEventDeliveryObserverService._lock_reachabilityObserverConnections
+ _OBJC_IVAR_$_BKHIDSystem._pendingDeliveryManagerBlocks
+ _OBJC_IVAR_$_BKIOHIDService._productName
+ _OBJC_IVAR_$_BKIOHIDService._transport
+ _OBJC_IVAR_$_BKIOHIDServiceMatcher._dataProviderSupportsHoisting
+ _OBJC_IVAR_$__BKEventObserverConnectionRecord._lastSentTargetStatuses
+ _OBJC_IVAR_$__BKEventObserverConnectionRecord._reachabilityTargets
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_BKIOHIDServiceMatcherDataProviding
+ ___40-[BKIOHIDServiceMatcher _servicesAdded:]_block_invoke
+ ___44-[BKIOHIDService appendDescriptionToStream:]_block_invoke
+ ___52-[BKEventDeferringGraph _setRules:forPID:toDisplay:]_block_invoke_5
+ ___52-[BKEventDeferringGraph _setRules:forPID:toDisplay:]_block_invoke_6
+ ___52-[BKEventDeferringGraph _setRules:forPID:toDisplay:]_block_invoke_7
+ ___56-[BKIOHIDServiceMatcher _lock_asyncNotifyServicesAdded:]_block_invoke_2
+ ___65-[BKEventDeferringGraph environmentGraphsForEnvironment:display:]_block_invoke
+ ___82-[BKHIDEventDeliveryObserverService connection:setReachabilityObservationTargets:]_block_invoke
+ ___block_descriptor_36_e45_16?0"BKSHIDEventDeferringSelectionTarget"8l
+ ___block_descriptor_40_e8_32r_e34_v32?0"NSNumber"8"NSArray"16^B24lr32l8
+ ___block_descriptor_48_e8_32s40r_e34_v32?0"NSNumber"8"NSArray"16^B24ls32l8r40l8
+ ___block_descriptor_48_e8_32s40s_e81_v32?0"BKSEventDeferringChainIdentity"8"BKEventDeferringEnvironmentGraph"16^B24ls32l8s40l8
+ _swift_retain_x25
- GCC_except_table205
- GCC_except_table240
- GCC_except_table286
- GCC_except_table340
- GCC_except_table353
- GCC_except_table356
- GCC_except_table362
- GCC_except_table365
- GCC_except_table597
- GCC_except_table600
- GCC_except_table631
- GCC_except_table679
- GCC_except_table740
- GCC_except_table752
- GCC_except_table783
- _swift_release_x26
- _swift_retain_x26
CStrings:
+ "\"&"
+ "@16@?0@\"BKSHIDEventDeferringSelectionTarget\"8"
+ "Product"
+ "Q"
+ "Transport"
+ "[%{public}@ %p] _nodeIsReachableFromSupernode(%{public}@):%{public}@ NO because sibling predicate group %{public}@ has constraint"
+ "clientTerminated"
+ "evaluateReachability"
+ "name"
+ "reachable observation targets did change (%{public}@) %{public}@"
+ "transport"
+ "\x81"
- "!&"
- "0x%X"
- "0x%llX"
- "A"
- "IOHIDService"
- "IOServices added: %{public}@"
```
