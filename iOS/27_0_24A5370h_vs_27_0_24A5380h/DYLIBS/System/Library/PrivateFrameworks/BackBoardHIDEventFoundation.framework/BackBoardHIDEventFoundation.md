## BackBoardHIDEventFoundation

> `/System/Library/PrivateFrameworks/BackBoardHIDEventFoundation.framework/BackBoardHIDEventFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c54c` | `0x3cdc4` | **`+0x878`** |
| `__TEXT.__cstring` | `0x2fc9` | `0x3392` | **`+0x3c9`** |
| `__DATA_CONST.__const` | `0x1350` | `0x15f8` | **`+0x2a8`** |
| `__AUTH_CONST.__objc_const` | `0x5e88` | `0x6098` | **`+0x210`** |
| `__TEXT.__objc_methlist` | `0x2160` | `0x22c8` | **`+0x168`** |
| `__AUTH_CONST.__const` | `0xa18` | `0xb58` | **`+0x140`** |
| `__AUTH_CONST.__cfstring` | `0x2a80` | `0x2b40` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x450` | `0x4f0` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x13e8` | `0x1480` | **`+0x98`** |
| `__TEXT.__oslogstring` | `0x326d` | `0x32e0` | **`+0x73`** |
| `__TEXT.__unwind_info` | `0xbd8` | `0xc28` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x39c` | `0x3bc` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x44c` | `0x45c` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3f0` | `0x400` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1a8` | `0x1b8` | **`+0x10`** |

### Other Changes

```diff

-866.0.0.0.0
+868.0.0.0.0

-  Functions: 1045
-  Symbols:   2325
-  CStrings:  664
+  Functions: 1086
+  Symbols:   2416
+  CStrings:  686
Symbols:
+ +[BKHIDDomainClientCalloutContextualizer(ClientEnvironment) _contextualizerWrappingClientProvidedContextualizer:connection:getCurrent:setCurrent:]
+ +[BKHIDDomainServiceServer(ClientEnvironment) _currentClientEnvironmentObjectForKey:]
+ +[BKHIDDomainServiceServer(ClientEnvironment) _currentDirectTouchEventProcessor]
+ +[BKHIDDomainServiceServer(ClientEnvironment) _currentDisplayRenderSpace]
+ +[BKHIDDomainServiceServer(ClientEnvironment) _currentHIDEventDeliveryManager]
+ +[BKHIDDomainServiceServer(ClientEnvironment) _currentHIDEventDeliveryObserverService]
+ +[BKHIDDomainServiceServer(ClientEnvironment) _currentTouchDeliveryObservationManager]
+ +[BKHIDDomainServiceServer(ClientEnvironment) _setCurrentClientEnvironmentObject:forKey:]
+ +[BKHIDDomainServiceServer(ClientEnvironment) _setCurrentDirectTouchEventProcessor:]
+ +[BKHIDDomainServiceServer(ClientEnvironment) _setCurrentDisplayRenderSpace:]
+ +[BKHIDDomainServiceServer(ClientEnvironment) _setCurrentHIDEventDeliveryManager:]
+ +[BKHIDDomainServiceServer(ClientEnvironment) _setCurrentHIDEventDeliveryObserverService:]
+ +[BKHIDDomainServiceServer(ClientEnvironment) _setCurrentTouchDeliveryObservationManager:]
+ -[BKHIDClientCalloutContextualizer .cxx_destruct]
+ -[BKHIDClientCalloutContextualizer contextualizedMappedObjectFetcher]
+ -[BKHIDClientCalloutContextualizer setContextualizedMappedObjectFetcher:]
+ -[BKHIDClientCalloutContextualizer setSetupBlock:]
+ -[BKHIDClientCalloutContextualizer setTeardownBlock:]
+ -[BKHIDClientCalloutContextualizer setupBlock]
+ -[BKHIDClientCalloutContextualizer teardownBlock]
+ -[BKHIDDomainClientCalloutContextualizer .cxx_destruct]
+ -[BKHIDDomainClientCalloutContextualizer setSetupBlock:]
+ -[BKHIDDomainClientCalloutContextualizer setTeardownBlock:]
+ -[BKHIDDomainClientCalloutContextualizer setupBlock]
+ -[BKHIDDomainClientCalloutContextualizer teardownBlock]
+ -[BKHIDDomainIncomingServiceConnection acceptConnectionUsingServiceQueue:clientCalloutContextualizer:]
+ -[BKHIDDomainServiceServer acceptIncomingServiceConnection:serviceQueue:clientCalloutContextualizer:]
+ -[BKHIDEventDeliveryManagerServer acceptIncomingServiceConnection:serviceQueue:clientCalloutContextualizer:]
+ -[BKHIDEventDeliveryObserverServer acceptIncomingServiceConnection:serviceQueue:clientCalloutContextualizer:]
+ -[BKHIDIncomingServiceConnection acceptConnectionWithServiceQueue:clientCalloutContextualizer:]
+ GCC_except_table241
+ GCC_except_table281
+ GCC_except_table334
+ GCC_except_table392
+ GCC_except_table405
+ GCC_except_table408
+ GCC_except_table414
+ GCC_except_table417
+ GCC_except_table43
+ GCC_except_table662
+ GCC_except_table665
+ GCC_except_table69
+ GCC_except_table699
+ GCC_except_table748
+ GCC_except_table809
+ GCC_except_table821
+ GCC_except_table853
+ _BKGetCurrentDirectTouchEventProcessor
+ _BKGetCurrentDirectTouchEventProcessor_block_invoke
+ _BKGetCurrentDisplayRenderSpace
+ _BKGetCurrentDisplayRenderSpace_block_invoke_3
+ _BKGetCurrentHIDEventDeliveryManager
+ _BKGetCurrentHIDEventDeliveryManager_block_invoke_5
+ _BKGetCurrentHIDEventDeliveryObserverService
+ _BKGetCurrentHIDEventDeliveryObserverService_block_invoke_7
+ _BKGetCurrentTouchDeliveryObservationManager
+ _BKGetCurrentTouchDeliveryObservationManager_block_invoke_9
+ _BKSetCurrentDirectTouchEventProcessor
+ _BKSetCurrentDirectTouchEventProcessor_block_invoke_2
+ _BKSetCurrentDisplayRenderSpace
+ _BKSetCurrentDisplayRenderSpace_block_invoke_4
+ _BKSetCurrentHIDEventDeliveryManager
+ _BKSetCurrentHIDEventDeliveryManager_block_invoke_6
+ _BKSetCurrentHIDEventDeliveryObserverService
+ _BKSetCurrentHIDEventDeliveryObserverService_block_invoke_8
+ _BKSetCurrentTouchDeliveryObservationManager
+ _BKSetCurrentTouchDeliveryObservationManager_block_invoke_10
+ _OBJC_CLASS_$_BKHIDClientCalloutContextualizer
+ _OBJC_CLASS_$_BKHIDDomainClientCalloutContextualizer
+ _OBJC_CLASS_$_BSServiceConnectionCalloutContextualizer
+ _OBJC_CLASS_$_NSThread
+ _OBJC_IVAR_$_BKHIDClientCalloutContextualizer._contextualizedMappedObjectFetcher
+ _OBJC_IVAR_$_BKHIDClientCalloutContextualizer._setupBlock
+ _OBJC_IVAR_$_BKHIDClientCalloutContextualizer._teardownBlock
+ _OBJC_IVAR_$_BKHIDDomainClientCalloutContextualizer._setupBlock
+ _OBJC_IVAR_$_BKHIDDomainClientCalloutContextualizer._teardownBlock
+ _OBJC_METACLASS_$_BKHIDClientCalloutContextualizer
+ _OBJC_METACLASS_$_BKHIDDomainClientCalloutContextualizer
+ __OBJC_$_CLASS_METHODS_BKHIDDomainClientCalloutContextualizer(ClientEnvironment)
+ __OBJC_$_CLASS_METHODS_BKHIDDomainServiceServer(ClientEnvironment)
+ __OBJC_$_INSTANCE_METHODS_BKHIDClientCalloutContextualizer
+ __OBJC_$_INSTANCE_METHODS_BKHIDDomainClientCalloutContextualizer
+ __OBJC_$_INSTANCE_VARIABLES_BKHIDClientCalloutContextualizer
+ __OBJC_$_INSTANCE_VARIABLES_BKHIDDomainClientCalloutContextualizer
+ __OBJC_$_PROP_LIST_BKHIDClientCalloutContextualizer
+ __OBJC_$_PROP_LIST_BKHIDDomainClientCalloutContextualizer
+ __OBJC_CLASS_RO_$_BKHIDClientCalloutContextualizer
+ __OBJC_CLASS_RO_$_BKHIDDomainClientCalloutContextualizer
+ __OBJC_METACLASS_RO_$_BKHIDClientCalloutContextualizer
+ __OBJC_METACLASS_RO_$_BKHIDDomainClientCalloutContextualizer
+ ___101-[BKHIDDomainServiceServer acceptIncomingServiceConnection:serviceQueue:clientCalloutContextualizer:]_block_invoke
+ ___101-[BKHIDDomainServiceServer acceptIncomingServiceConnection:serviceQueue:clientCalloutContextualizer:]_block_invoke_2
+ ___101-[BKHIDDomainServiceServer acceptIncomingServiceConnection:serviceQueue:clientCalloutContextualizer:]_block_invoke_3
+ ___101-[BKHIDDomainServiceServer acceptIncomingServiceConnection:serviceQueue:clientCalloutContextualizer:]_block_invoke_4
+ ___101-[BKHIDDomainServiceServer acceptIncomingServiceConnection:serviceQueue:clientCalloutContextualizer:]_block_invoke_5
+ ___146+[BKHIDDomainClientCalloutContextualizer(ClientEnvironment) _contextualizerWrappingClientProvidedContextualizer:connection:getCurrent:setCurrent:]_block_invoke
+ ___146+[BKHIDDomainClientCalloutContextualizer(ClientEnvironment) _contextualizerWrappingClientProvidedContextualizer:connection:getCurrent:setCurrent:]_block_invoke_2
+ ___67-[BKHIDIncomingServiceConnection acceptConnectionWithMappedObject:]_block_invoke
+ ___block_descriptor_32_e29_"<BKDisplayRenderSpace>"8?0l
+ ___block_descriptor_32_e32_"BKHIDEventDeliveryManager"8?0l
+ ___block_descriptor_32_e32_v16?0"<BKDisplayRenderSpace>"8l
+ ___block_descriptor_32_e35_v16?0"BKHIDEventDeliveryManager"8l
+ ___block_descriptor_32_e37_"BKHIDDirectTouchEventProcessor"8?0l
+ ___block_descriptor_32_e40_"BKHIDEventDeliveryObserverService"8?0l
+ ___block_descriptor_32_e40_"BKTouchDeliveryObservationManager"8?0l
+ ___block_descriptor_32_e40_v16?0"BKHIDDirectTouchEventProcessor"8l
+ ___block_descriptor_32_e43_v16?0"BKHIDEventDeliveryObserverService"8l
+ ___block_descriptor_32_e43_v16?0"BKTouchDeliveryObservationManager"8l
+ ___block_descriptor_40_e8_32bs_e42_16?0"<BSServiceConnectionCalloutType>"8ls32l8
+ ___block_descriptor_40_e8_32bs_e45_v24?0"<BSServiceConnectionCalloutType>"816ls32l8
+ ___block_descriptor_40_e8_32s_e50_v16?0"<BSServiceListenerConnectionConfiguring>"8ls32l8
+ ___block_descriptor_40_e8_32s_e5_8?0ls32l8
+ ___block_descriptor_64_e8_32s40bs48bs56r_e8_v16?08ls40l8s48l8r56l8s32l8
+ ___block_descriptor_64_e8_32s40s48bs56bs_e5_v8?0ls48l8s32l8s40l8s56l8
+ ___block_descriptor_72_e8_32bs40bs48bs56bs64r_e5_8?0ls32l8r64l8s40l8s48l8s56l8
- -[BKHIDDomainIncomingServiceConnection acceptConnection]
- -[BKHIDDomainServiceServer acceptIncomingServiceConnection:]
- -[BKHIDEventDeliveryManagerServer _deliveryManagerForEstablishedConnection:]
- -[BKHIDEventDeliveryManagerServer acceptIncomingServiceConnection:mappedObject:]
- -[BKHIDEventDeliveryObserverServer _deliveryObserverServiceForEstablishedConnection:]
- -[BKHIDEventDeliveryObserverServer acceptIncomingServiceConnection:mappedObject:]
- GCC_except_table213
- GCC_except_table248
- GCC_except_table301
- GCC_except_table359
- GCC_except_table372
- GCC_except_table375
- GCC_except_table381
- GCC_except_table384
- GCC_except_table39
- GCC_except_table621
- GCC_except_table624
- GCC_except_table658
- GCC_except_table707
- GCC_except_table768
- GCC_except_table780
- GCC_except_table812
- _OBJC_IVAR_$__BKEventObserverConnectionRecord._observerService
- ___60-[BKHIDDomainServiceServer acceptIncomingServiceConnection:]_block_invoke
CStrings:
+ "+[BKHIDDomainClientCalloutContextualizer(ClientEnvironment) _contextualizerWrappingClientProvidedContextualizer:connection:getCurrent:setCurrent:]_block_invoke_2"
+ "+[BKHIDDomainServiceServer(ClientEnvironment) _setCurrentClientEnvironmentObject:forKey:]"
+ "@\"<BKDisplayRenderSpace>\"8@?0"
+ "@\"BKHIDDirectTouchEventProcessor\"8@?0"
+ "@\"BKHIDEventDeliveryManager\"8@?0"
+ "@\"BKHIDEventDeliveryObserverService\"8@?0"
+ "@\"BKTouchDeliveryObservationManager\"8@?0"
+ "@16@?0@\"<BSServiceConnectionCalloutType>\"8"
+ "BKHIDClientCalloutContextualizerSetupBlock for %@ stashed info with no teardownBlock to clean it up!"
+ "BKHIDDomainServiceServer_CurrentDeliveryManager"
+ "BKHIDDomainServiceServer_CurrentDisplayRenderSpace"
+ "BKHIDDomainServiceServer_CurrentHIDEventDeliveryObserverService"
+ "BKHIDDomainServiceServer_CurrentTouchDeliveryObservationManager"
+ "BKHIDDomainServiceServer_CurrentTouchProcessor"
+ "Delivery manager isn't configured"
+ "HID Event delivery observer service isn't configured"
+ "clientContextualizer"
+ "configuring connection (%{public}@) - %{public}@ with queue: %@"
+ "failed to provide a clientCalloutContextualizer for %@ while activating incoming connection: %@"
+ "failure in %{public}@ (%{public}@:%i) : %{public}@"
+ "getter"
+ "key"
+ "missing thread-local storage on %@"
+ "setter"
+ "v16@?0@\"<BKDisplayRenderSpace>\"8"
+ "v16@?0@\"BKHIDDirectTouchEventProcessor\"8"
+ "v16@?0@\"BKHIDEventDeliveryManager\"8"
+ "v16@?0@\"BKHIDEventDeliveryObserverService\"8"
+ "v16@?0@\"BKTouchDeliveryObservationManager\"8"
+ "v24@?0@\"<BSServiceConnectionCalloutType>\"8@16"
- "deliveryManager"
- "failed to find delivery manager for established connection: %@"
- "failed to find delivery observer service for established connection: %@"
- "failed to provide %@ while activating incoming connection: %@"
- "failed to provide delivery manager for incoming connection: %@"
- "failed to provide delivery observer service for incoming connection: %@"
- "no delivery observer service"
- "service"
```
