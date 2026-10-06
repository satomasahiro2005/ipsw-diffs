## BackBoardHIDTouchEventProcessor

> `/System/Library/PrivateFrameworks/BackBoardHIDTouchEventProcessor.framework/BackBoardHIDTouchEventProcessor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59e10` | `0x5a880` | **`+0xa70`** |
| `__TEXT.__oslogstring` | `0x4430` | `0x471e` | **`+0x2ee`** |
| `__TEXT.__gcc_except_tab` | `0x5320` | `0x5420` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0xaa68` | `0xa978` | **`-0xf0`** |
| `__TEXT.__objc_methlist` | `0x3ac0` | `0x39f0` | **`-0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x3ec0` | `0x3e60` | **`-0x60`** |
| `__DATA.__data` | `0x1088` | `0x1028` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x1bb0` | `0x1c00` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x750` | `0x780` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x26a8` | `0x26d8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x34d2` | `0x34b3` | **`-0x1f`** |
| `__DATA.__objc_ivar` | `0x950` | `0x944` | **`-0xc`** |
| `__DATA_CONST.__objc_protolist` | `0x160` | `0x158` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x48` | `0x40` | **`-0x8`** |

### Other Changes

```diff

-866.0.0.0.0
+868.0.0.0.0

-  Functions: 1588
-  Symbols:   3979
-  CStrings:  973
+  Functions: 1592
+  Symbols:   3980
+  CStrings:  980
Symbols:
+ +[BKTouchDestination destinationWithHitTestTargetID:clientTaskName:clientConnectionIdentifier:]
+ -[BKDirectTouchState ensureHitTestDestinationExistsForTargetID:clientTaskName:clientConnectionIdentifier:]
+ -[BKDirectTouchStateHitTester _addDestinationForTargetID:clientTaskName:clientConnectionIdentifier:toHostingChain:]
+ -[BKHIDEventHitTestDispatcher sendEvent:forTargetID:toClientConnectionIdentifier:]
+ -[BKTargetDestination clientConnectionIdentifier]
+ -[BKTargetDestination initWithTargetID:clientTaskName:clientConnectionIdentifier:]
+ -[BKTargetDestination setClientConnectionIdentifier:]
+ -[BKTouchDeliveryObservationManagerServer acceptIncomingServiceConnection:serviceQueue:clientCalloutContextualizer:]
+ -[BKTouchDestination initWithHitTestTargetID:clientTaskName:clientConnectionIdentifier:]
+ -[BKTouchEventServer acceptIncomingServiceConnection:serviceQueue:clientCalloutContextualizer:]
+ -[BKTouchStreamServer acceptIncomingServiceConnection:serviceQueue:clientCalloutContextualizer:]
+ -[_BKTouchServerClientRecord init]
+ GCC_except_table1057
+ GCC_except_table1063
+ GCC_except_table1087
+ GCC_except_table1089
+ GCC_except_table1118
+ GCC_except_table1126
+ GCC_except_table1129
+ GCC_except_table1134
+ GCC_except_table1137
+ GCC_except_table1139
+ GCC_except_table1142
+ GCC_except_table1148
+ GCC_except_table1154
+ GCC_except_table1159
+ GCC_except_table1165
+ GCC_except_table1167
+ GCC_except_table1171
+ GCC_except_table1190
+ GCC_except_table127
+ GCC_except_table132
+ GCC_except_table1364
+ GCC_except_table1383
+ GCC_except_table1384
+ GCC_except_table145
+ GCC_except_table1459
+ GCC_except_table146
+ GCC_except_table1467
+ GCC_except_table1469
+ GCC_except_table1470
+ GCC_except_table1472
+ GCC_except_table1488
+ GCC_except_table152
+ GCC_except_table166
+ GCC_except_table167
+ GCC_except_table174
+ GCC_except_table191
+ GCC_except_table196
+ GCC_except_table216
+ GCC_except_table222
+ GCC_except_table226
+ GCC_except_table242
+ GCC_except_table343
+ GCC_except_table384
+ GCC_except_table386
+ GCC_except_table388
+ GCC_except_table398
+ GCC_except_table405
+ GCC_except_table406
+ GCC_except_table419
+ GCC_except_table420
+ GCC_except_table427
+ GCC_except_table428
+ GCC_except_table440
+ GCC_except_table442
+ GCC_except_table444
+ GCC_except_table515
+ GCC_except_table516
+ GCC_except_table517
+ GCC_except_table525
+ GCC_except_table526
+ GCC_except_table527
+ GCC_except_table533
+ GCC_except_table541
+ GCC_except_table553
+ GCC_except_table554
+ GCC_except_table567
+ GCC_except_table569
+ GCC_except_table574
+ GCC_except_table575
+ GCC_except_table576
+ GCC_except_table632
+ GCC_except_table633
+ GCC_except_table640
+ GCC_except_table641
+ GCC_except_table642
+ GCC_except_table661
+ GCC_except_table663
+ GCC_except_table665
+ GCC_except_table676
+ GCC_except_table680
+ GCC_except_table689
+ GCC_except_table694
+ GCC_except_table696
+ GCC_except_table707
+ GCC_except_table709
+ GCC_except_table716
+ GCC_except_table717
+ GCC_except_table722
+ GCC_except_table731
+ GCC_except_table736
+ GCC_except_table741
+ GCC_except_table749
+ GCC_except_table753
+ GCC_except_table754
+ GCC_except_table761
+ GCC_except_table762
+ GCC_except_table763
+ GCC_except_table770
+ GCC_except_table775
+ GCC_except_table777
+ GCC_except_table848
+ GCC_except_table901
+ GCC_except_table928
+ GCC_except_table942
+ GCC_except_table943
+ GCC_except_table946
+ GCC_except_table974
+ _BKGetCurrentDirectTouchEventProcessor
+ _BKGetCurrentDisplayRenderSpace
+ _BKGetCurrentTouchDeliveryObservationManager
+ _BKSetCurrentDirectTouchEventProcessor
+ _BKSetCurrentDisplayRenderSpace
+ _BKSetCurrentTouchDeliveryObservationManager
+ _OBJC_CLASS_$_BKHIDDomainClientCalloutContextualizer
+ _OBJC_IVAR_$_BKTargetDestination._clientConnectionIdentifier
+ _OBJC_IVAR_$__BKTouchDeliveryObservationConnectionRecord._domainServiceServer
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_BKHIDEventHitTestDispatcher
+ ___95-[BKTouchEventServer acceptIncomingServiceConnection:serviceQueue:clientCalloutContextualizer:]_block_invoke
+ ___95-[BKTouchEventServer acceptIncomingServiceConnection:serviceQueue:clientCalloutContextualizer:]_block_invoke_2
+ ___block_descriptor_72_e8_32bs40bs48r56r64r_e5_8?0ls32l8r48l8s40l8r56l8r64l8
+ ___block_descriptor_72_e8_32s40bs48r56r64r_e8_v16?08lr48l8r56l8s40l8r64l8s32l8
- +[BKTouchDestination destinationWithHitTestTargetID:clientTaskName:]
- -[BKDirectTouchState ensureHitTestDestinationExistsForTargetID:clientTaskName:]
- -[BKDirectTouchStateHitTester _addDestinationForTargetID:clientTaskName:toHostingChain:]
- -[BKHIDEventHitTestDispatcher sendEvent:toClientTaskName:toTargetID:]
- -[BKTouchDeliveryObservationManagerServer _managerForConnection:]
- -[BKTouchDeliveryObservationManagerServer acceptIncomingServiceConnection:mappedObject:]
- -[BKTouchDestination initWithHitTestTargetID:clientTaskName:]
- -[BKTouchEventServer acceptIncomingServiceConnection:mappedObject:]
- -[BKTouchStreamClientRecord .cxx_destruct]
- -[BKTouchStreamClientRecord setTouchProcessor:]
- -[BKTouchStreamClientRecord touchProcessor]
- -[BKTouchStreamServer acceptIncomingServiceConnection:mappedObject:]
- GCC_except_table1056
- GCC_except_table1062
- GCC_except_table1086
- GCC_except_table1088
- GCC_except_table1113
- GCC_except_table1119
- GCC_except_table1128
- GCC_except_table1130
- GCC_except_table1135
- GCC_except_table1138
- GCC_except_table1140
- GCC_except_table1144
- GCC_except_table1149
- GCC_except_table1155
- GCC_except_table1161
- GCC_except_table1166
- GCC_except_table1168
- GCC_except_table1189
- GCC_except_table1251
- GCC_except_table130
- GCC_except_table1379
- GCC_except_table138
- GCC_except_table1380
- GCC_except_table1455
- GCC_except_table1460
- GCC_except_table1463
- GCC_except_table1465
- GCC_except_table1466
- GCC_except_table148
- GCC_except_table1484
- GCC_except_table149
- GCC_except_table155
- GCC_except_table169
- GCC_except_table170
- GCC_except_table177
- GCC_except_table194
- GCC_except_table199
- GCC_except_table219
- GCC_except_table225
- GCC_except_table229
- GCC_except_table245
- GCC_except_table346
- GCC_except_table395
- GCC_except_table402
- GCC_except_table403
- GCC_except_table412
- GCC_except_table414
- GCC_except_table416
- GCC_except_table423
- GCC_except_table425
- GCC_except_table431
- GCC_except_table433
- GCC_except_table443
- GCC_except_table447
- GCC_except_table448
- GCC_except_table519
- GCC_except_table520
- GCC_except_table524
- GCC_except_table530
- GCC_except_table538
- GCC_except_table545
- GCC_except_table546
- GCC_except_table547
- GCC_except_table557
- GCC_except_table559
- GCC_except_table570
- GCC_except_table572
- GCC_except_table579
- GCC_except_table581
- GCC_except_table583
- GCC_except_table635
- GCC_except_table636
- GCC_except_table649
- GCC_except_table653
- GCC_except_table657
- GCC_except_table673
- GCC_except_table674
- GCC_except_table681
- GCC_except_table683
- GCC_except_table688
- GCC_except_table701
- GCC_except_table706
- GCC_except_table710
- GCC_except_table711
- GCC_except_table712
- GCC_except_table719
- GCC_except_table728
- GCC_except_table735
- GCC_except_table740
- GCC_except_table747
- GCC_except_table748
- GCC_except_table752
- GCC_except_table756
- GCC_except_table757
- GCC_except_table767
- GCC_except_table769
- GCC_except_table771
- GCC_except_table778
- GCC_except_table780
- GCC_except_table782
- GCC_except_table850
- GCC_except_table903
- GCC_except_table930
- GCC_except_table944
- GCC_except_table953
- GCC_except_table958
- GCC_except_table976
- _OBJC_IVAR_$_BKTouchStreamClientRecord._touchProcessor
- _OBJC_IVAR_$__BKTouchDeliveryObservationConnectionRecord._observationManager
- _OBJC_IVAR_$__BKTouchServerClientRecord._clientManager
- _OBJC_IVAR_$__BKTouchServerClientRecord._renderSpace
- _OBJC_IVAR_$__BKTouchServerClientRecord._touchProcessor
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_BKDisplayRenderSpace
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_BKHIDEventHitTestDispatcher
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_BKDisplayRenderSpace
- __OBJC_$_PROTOCOL_METHOD_TYPES_BKDisplayRenderSpace
- __OBJC_$_PROTOCOL_REFS_BKDisplayRenderSpace
- __OBJC_LABEL_PROTOCOL_$_BKDisplayRenderSpace
- __OBJC_PROTOCOL_$_BKDisplayRenderSpace
- __OBJC_PROTOCOL_REFERENCE_$_BKDisplayRenderSpace
CStrings:
+ "\""
+ "-[BKTouchEventServer acceptIncomingServiceConnection:serviceQueue:clientCalloutContextualizer:]_block_invoke_2"
+ "BKHIDClientCalloutContextualizerSetupBlock for %@ stashed info with no teardownBlock to clean it up!"
+ "Failed to create touch stream for for client: %{public}@ - no current touch processor"
+ "Failed to update dispatch mode for client: %{public}@ - no current touch processor"
+ "clientConnectionIdentifier"
+ "not sending queued updates to: %{public}@ - server is gone"
+ "pid:%d failed to observe kinds:%{public}@ identifier:%X - no manager available"
+ "post updates: %{public}@ and bg update: %{public}@ to: %{public}@"
+ "process '%{public}@' failed to look up CA transforms - no render space available"
+ "process:%{public}@ (ctx:%{public}@) failed to observe background touches - token:%llu contexts:%{public}@ timestamp:%f - no manager available"
+ "process:%{public}@ (ctx:%{public}@) failed to observe general kinds:%{public}@ - no manager available"
+ "process:%{public}@ (ctx:%{public}@) failed to stop observing background touches - token:%llu - no manager available"
- "connection %@ is missing touch event processor"
- "failed to find touch observation manager for existing connection: %@"
- "failed to provide touch observation manager for incoming connection: %@"
- "failed to provide touch processor for incoming connection: %@"
- "post updates:%{public}@ and bg update:@{public}%@ to:%{public}@"
- "renderSpace != nil"
```
