## BackBoardHIDTouchEventProcessor

> `/System/Library/PrivateFrameworks/BackBoardHIDTouchEventProcessor.framework/BackBoardHIDTouchEventProcessor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5920c` | `0x59e10` | **`+0xc04`** |
| `__TEXT.__gcc_except_tab` | `0x5190` | `0x5320` | **`+0x190`** |
| `__AUTH_CONST.__objc_const` | `0xa9a0` | `0xaa68` | **`+0xc8`** |
| `__TEXT.__unwind_info` | `0x1a70` | `0x1b10` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x3a58` | `0x3ac0` | **`+0x68`** |
| `__DATA.__data` | `0x1028` | `0x1088` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x2660` | `0x26a8` | **`+0x48`** |
| `__TEXT.__cstring` | `0x3495` | `0x34d2` | **`+0x3d`** |
| `__DATA_CONST.__const` | `0x1b88` | `0x1bb0` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0x441a` | `0x4430` | **`+0x16`** |
| `__DATA_CONST.__objc_protolist` | `0x158` | `0x160` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x94c` | `0x950` | **`+0x4`** |

### Other Changes

```diff

-860.0.1.0.0
+866.0.0.0.0

-  Functions: 1574
-  Symbols:   3952
-  CStrings:  970
+  Functions: 1588
+  Symbols:   3979
+  CStrings:  973
Symbols:
+ -[BKHIDDirectTouchEventProcessor(NamespaceResolving) senderDisplayUUIDForAuthenticationMessage:]
+ -[BKMousePointerController(NamespaceResolving) senderDisplayUUIDForAuthenticationMessage:]
+ -[BKTouchDeliveryObservationManager _queue_isAnyPIDObservingIdentifier:]
+ -[BKTouchDeliveryObservationManager _queue_pendDownUpdate:]
+ -[BKTouchDeliveryObservationManager _queue_setProcessPID:observesGeneralOccurrenceKinds:]
+ -[BKTouchDeliveryObservationManager _queue_setProcessPID:observesOccurrenceKinds:withTouchIdentifier:]
+ -[BKTouchDeliveryObservationManager setProcessPID:observesGeneralOccurrenceKinds:]
+ -[BKTouchDeliveryObservationManager setProcessPID:observesOccurrenceKinds:withTouchIdentifier:]
+ -[BKTouchDeliveryObservationManagerServer setObservesGeneralOccurrenceKinds:]
+ -[BKTouchDeliveryObservationManagerServer setObservesOccurrenceKinds:withIdentifier:]
+ -[_BKDeliveryManagerProvider performWhenDeliveryManagerAvailable:]
+ GCC_except_table1056
+ GCC_except_table1062
+ GCC_except_table1086
+ GCC_except_table1088
+ GCC_except_table1114
+ GCC_except_table1115
+ GCC_except_table1117
+ GCC_except_table1122
+ GCC_except_table1125
+ GCC_except_table1130
+ GCC_except_table1131
+ GCC_except_table1136
+ GCC_except_table1147
+ GCC_except_table1153
+ GCC_except_table1155
+ GCC_except_table1161
+ GCC_except_table1162
+ GCC_except_table1163
+ GCC_except_table1164
+ GCC_except_table1166
+ GCC_except_table1168
+ GCC_except_table1169
+ GCC_except_table1170
+ GCC_except_table1189
+ GCC_except_table1252
+ GCC_except_table1253
+ GCC_except_table1254
+ GCC_except_table1255
+ GCC_except_table1256
+ GCC_except_table1257
+ GCC_except_table1258
+ GCC_except_table1259
+ GCC_except_table1260
+ GCC_except_table1261
+ GCC_except_table1265
+ GCC_except_table1335
+ GCC_except_table1339
+ GCC_except_table1379
+ GCC_except_table1380
+ GCC_except_table1455
+ GCC_except_table1460
+ GCC_except_table1463
+ GCC_except_table1464
+ GCC_except_table1465
+ GCC_except_table1466
+ GCC_except_table1468
+ GCC_except_table1484
+ GCC_except_table346
+ GCC_except_table396
+ GCC_except_table403
+ GCC_except_table404
+ GCC_except_table413
+ GCC_except_table416
+ GCC_except_table422
+ GCC_except_table425
+ GCC_except_table430
+ GCC_except_table433
+ GCC_except_table447
+ GCC_except_table448
+ GCC_except_table520
+ GCC_except_table521
+ GCC_except_table524
+ GCC_except_table531
+ GCC_except_table536
+ GCC_except_table537
+ GCC_except_table539
+ GCC_except_table543
+ GCC_except_table544
+ GCC_except_table545
+ GCC_except_table546
+ GCC_except_table547
+ GCC_except_table556
+ GCC_except_table557
+ GCC_except_table559
+ GCC_except_table577
+ GCC_except_table578
+ GCC_except_table579
+ GCC_except_table580
+ GCC_except_table581
+ GCC_except_table583
+ GCC_except_table644
+ GCC_except_table647
+ GCC_except_table648
+ GCC_except_table650
+ GCC_except_table651
+ GCC_except_table653
+ GCC_except_table654
+ GCC_except_table657
+ GCC_except_table668
+ GCC_except_table669
+ GCC_except_table675
+ GCC_except_table678
+ GCC_except_table681
+ GCC_except_table682
+ GCC_except_table685
+ GCC_except_table695
+ GCC_except_table698
+ GCC_except_table700
+ GCC_except_table705
+ GCC_except_table706
+ GCC_except_table708
+ GCC_except_table712
+ GCC_except_table729
+ GCC_except_table732
+ GCC_except_table734
+ GCC_except_table737
+ GCC_except_table740
+ GCC_except_table742
+ GCC_except_table744
+ GCC_except_table745
+ GCC_except_table752
+ GCC_except_table764
+ GCC_except_table765
+ GCC_except_table767
+ GCC_except_table771
+ GCC_except_table773
+ GCC_except_table776
+ GCC_except_table778
+ GCC_except_table779
+ GCC_except_table780
+ GCC_except_table782
+ GCC_except_table850
+ GCC_except_table903
+ GCC_except_table930
+ GCC_except_table945
+ GCC_except_table947
+ GCC_except_table948
+ GCC_except_table949
+ GCC_except_table950
+ GCC_except_table951
+ GCC_except_table952
+ GCC_except_table953
+ GCC_except_table954
+ GCC_except_table956
+ GCC_except_table958
+ GCC_except_table976
+ _BKSTouchDeliveryOccurrenceKindFromUpdateType
+ _OBJC_IVAR_$_BKTouchDeliveryObservationManager._pidToGeneralKinds
+ _OBJC_IVAR_$_BKTouchDeliveryObservationManager._touchIdentifierToDownUpdate
+ _OBJC_IVAR_$_BKTouchDeliveryObservationManager._touchIdentifierToPidKinds
+ _OBJC_IVAR_$_BKTouchDeliveryObservationManager._touchIdentifierToTransducerType
+ __OBJC_$_INSTANCE_METHODS_BKHIDDirectTouchEventProcessor(NamespaceResolving)
+ __OBJC_$_INSTANCE_METHODS_BKMousePointerController(NamespaceResolving)
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BKHIDEventAuthenticationMessageNamespaceResolving
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BKHIDEventAuthenticationMessageNamespaceResolving
+ __OBJC_$_PROTOCOL_REFS_BKHIDEventAuthenticationMessageNamespaceResolving
+ __OBJC_CLASS_PROTOCOLS_$_BKHIDDirectTouchEventProcessor(NamespaceResolving)
+ __OBJC_CLASS_PROTOCOLS_$_BKMousePointerController(NamespaceResolving)
+ __OBJC_LABEL_PROTOCOL_$_BKHIDEventAuthenticationMessageNamespaceResolving
+ __OBJC_PROTOCOL_$_BKHIDEventAuthenticationMessageNamespaceResolving
+ __ZL21sKindsSetFromIndexSetP10NSIndexSet
+ ___50-[BKMousePointerController initWithConfiguration:]_block_invoke_5
+ ___55-[BKTouchDeliveryObservationManager touchDidHIDCancel:]_block_invoke
+ ___56-[BKTouchDeliveryObservationManager touchDidSoftCancel:]_block_invoke
+ ___59-[BKHIDDirectTouchEventProcessor matcher:servicesDidMatch:]_block_invoke
+ ___62-[BKTouchDeliveryObservationManager _queue_postPendingUpdates]_block_invoke_2
+ ___82-[BKTouchDeliveryObservationManager setProcessPID:observesGeneralOccurrenceKinds:]_block_invoke
+ ___95-[BKTouchDeliveryObservationManager setProcessPID:observesOccurrenceKinds:withTouchIdentifier:]_block_invoke
+ ___96-[BKHIDDirectTouchEventProcessor(NamespaceResolving) senderDisplayUUIDForAuthenticationMessage:]_block_invoke
+ ____ZL21sKindsSetFromIndexSetP10NSIndexSet_block_invoke
+ ___block_descriptor_36_e36_v32?0q8"BSMutableIntegerMap"16^B24l
+ ___block_descriptor_40_ea8_32s_e35_v16?0"BKHIDEventDeliveryManager"8ls32l8
+ ___block_descriptor_56_ea8_32s40r_e5_v8?0ls32l8r40l8
+ ___block_descriptor_57_ea8_32s_e5_v8?0ls32l8
+ ___block_descriptor_64_ea8_32s40s48s56s_e22_v32?0q8"NSSet"16^B24ls32l8s40l8s48l8s56l8
+ ___block_descriptor_74_ea8_32s40s_e5_v8?0ls32l8s40l8
- -[BKTouchDeliveryObservationManager _queue_setProcessPID:observesGlobalTouches:]
- -[BKTouchDeliveryObservationManager _queue_setProcessPID:observesTouch:withIdentifier:]
- -[BKTouchDeliveryObservationManager setProcessPID:observesGlobalTouches:]
- -[BKTouchDeliveryObservationManager setProcessPID:observesTouch:withIdentifier:]
- -[BKTouchDeliveryObservationManagerServer setObservesAllTouches:]
- -[BKTouchDeliveryObservationManagerServer setObservesTouch:withIdentifier:]
- GCC_except_table1044
- GCC_except_table1050
- GCC_except_table1074
- GCC_except_table1076
- GCC_except_table1101
- GCC_except_table1102
- GCC_except_table1103
- GCC_except_table1104
- GCC_except_table1105
- GCC_except_table1107
- GCC_except_table1108
- GCC_except_table1109
- GCC_except_table1110
- GCC_except_table1111
- GCC_except_table1112
- GCC_except_table1118
- GCC_except_table1126
- GCC_except_table1129
- GCC_except_table1134
- GCC_except_table1137
- GCC_except_table1139
- GCC_except_table1143
- GCC_except_table1154
- GCC_except_table1177
- GCC_except_table1239
- GCC_except_table1240
- GCC_except_table1241
- GCC_except_table1242
- GCC_except_table1243
- GCC_except_table1244
- GCC_except_table1245
- GCC_except_table1246
- GCC_except_table1247
- GCC_except_table1321
- GCC_except_table1325
- GCC_except_table1365
- GCC_except_table1366
- GCC_except_table1441
- GCC_except_table1446
- GCC_except_table1449
- GCC_except_table1450
- GCC_except_table1451
- GCC_except_table1452
- GCC_except_table1454
- GCC_except_table1470
- GCC_except_table344
- GCC_except_table385
- GCC_except_table388
- GCC_except_table398
- GCC_except_table405
- GCC_except_table406
- GCC_except_table420
- GCC_except_table421
- GCC_except_table428
- GCC_except_table429
- GCC_except_table441
- GCC_except_table446
- GCC_except_table516
- GCC_except_table517
- GCC_except_table522
- GCC_except_table526
- GCC_except_table527
- GCC_except_table533
- GCC_except_table549
- GCC_except_table550
- GCC_except_table552
- GCC_except_table563
- GCC_except_table565
- GCC_except_table571
- GCC_except_table573
- GCC_except_table574
- GCC_except_table576
- GCC_except_table628
- GCC_except_table629
- GCC_except_table637
- GCC_except_table638
- GCC_except_table639
- GCC_except_table640
- GCC_except_table641
- GCC_except_table642
- GCC_except_table656
- GCC_except_table658
- GCC_except_table659
- GCC_except_table660
- GCC_except_table661
- GCC_except_table662
- GCC_except_table663
- GCC_except_table665
- GCC_except_table676
- GCC_except_table686
- GCC_except_table689
- GCC_except_table690
- GCC_except_table691
- GCC_except_table693
- GCC_except_table694
- GCC_except_table696
- GCC_except_table714
- GCC_except_table716
- GCC_except_table717
- GCC_except_table730
- GCC_except_table731
- GCC_except_table733
- GCC_except_table736
- GCC_except_table738
- GCC_except_table743
- GCC_except_table755
- GCC_except_table758
- GCC_except_table759
- GCC_except_table760
- GCC_except_table761
- GCC_except_table763
- GCC_except_table770
- GCC_except_table838
- GCC_except_table891
- GCC_except_table918
- GCC_except_table932
- GCC_except_table933
- GCC_except_table935
- GCC_except_table936
- GCC_except_table937
- GCC_except_table938
- GCC_except_table939
- GCC_except_table940
- GCC_except_table941
- GCC_except_table942
- GCC_except_table946
- GCC_except_table964
- _OBJC_IVAR_$_BKDirectTouchState._gestureProcessorWrapper
- _OBJC_IVAR_$_BKTouchDeliveryObservationManager._globalTouchObserverPIDs
- _OBJC_IVAR_$_BKTouchDeliveryObservationManager._touchIdentifierToPIDs
- __OBJC_$_INSTANCE_METHODS_BKHIDDirectTouchEventProcessor
- __OBJC_$_INSTANCE_METHODS_BKMousePointerController
- __OBJC_$_PROP_LIST_BKHIDDirectTouchEventProcessor
- __OBJC_$_PROP_LIST_BKMousePointerController
- __OBJC_CLASS_PROTOCOLS_$_BKHIDDirectTouchEventProcessor
- __OBJC_CLASS_PROTOCOLS_$_BKMousePointerController
- ___73-[BKTouchDeliveryObservationManager setProcessPID:observesGlobalTouches:]_block_invoke
- ___80-[BKTouchDeliveryObservationManager setProcessPID:observesTouch:withIdentifier:]_block_invoke
- ___block_descriptor_36_e34_v32?0q8"NSMutableIndexSet"16^B24l
- ___block_descriptor_48_ea8_32s40s_e12_v24?0Q8^B16ls32l8s40l8
- ___block_descriptor_49_ea8_32s_e5_v8?0ls32l8
- ___block_descriptor_53_ea8_32s_e5_v8?0ls32l8
- ___block_descriptor_68_ea8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
- _objc_retain_x10
CStrings:
+ "\n"
+ "pid:%d observes kinds:%{public}@ identifier:%X"
+ "process:%{public}@ (ctx:%{public}@) observes general kinds:%{public}@"
+ "touch %X sent to destination pid:%d kind:%{public}@"
+ "v16@?0@\"BKHIDEventDeliveryManager\"8"
+ "v32@?0q8@\"BSMutableIntegerMap\"16^B24"
+ "v32@?0q8@\"NSSet\"16^B24"
- "pid:%d observes touch:%{BOOL}u identifier:%X"
- "process:%{public}@ (ctx:%{public}@) observes all touches:%{BOOL}u"
- "touch %X sent to destination pid:%d"
- "v32@?0q8@\"NSMutableIndexSet\"16^B24"
```
