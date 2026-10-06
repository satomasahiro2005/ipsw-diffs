## CoreRC

> `/System/Library/PrivateFrameworks/CoreRC.framework/CoreRC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a68c` | `0x4a568` | **`-0x124`** |

### Other Changes

```text
Functions:
~ -[CoreRCManagerProvider(CEC) addDeviceWithBus:logicalAddress:physicalAddress:attributes:message:reason:] : 360 -> 356
~ -[CoreRCManagerProvider createRCOverrideFromPaths:] : 412 -> 408
~ -[CoreRCManagerProvider initOverrides] : 832 -> 824
~ -[CoreRCManagerProvider addDeviceWithBus:transportProperties:error:] : 404 -> 400
~ -[CoreRCInterfaceController(FakeInterfaceListener) fakeInterfaceListener] : 276 -> 272
~ -[CoreIRBusProvider updateAllowHibernation] : 412 -> 408
~ -[CoreIRBusProvider updateLearnedProtocols] : 392 -> 388
~ -[CoreIRBusProvider getExistingDeviceWithType:matching:] : 384 -> 380
~ -[CoreIRBusProvider addMappingsFromRemote:toLearningSession:] : 928 -> 920
~ -[CoreIRBusProvider saveDevicePrefsWithDict:error:] : 1472 -> 1464
~ -[CoreIRBusProvider deleteDevicePrefsWithUUID:UUIDKey:] : 696 -> 692
~ -[CoreIRBusProvider setPrefsPropertyForUUID:UUIDKey:object:key:] : 844 -> 840
~ -[CoreIRBusProvider copyPrefsPropertyForUUID:UUIDKey:key:] : 484 -> 480
~ -[CoreIRBusProvider mergePersistentMappingsFromSession:ofDevice:] : 696 -> 692
~ -[CoreCECBus(Analytics) analyticsContext] : 300 -> 296
~ -[CoreCECBus removeDeviceWithType:] : 420 -> 416
~ -[CoreCECBus deviceOnBusWithLogicalAddress:] : 288 -> 284
~ -[NSMutableSet(CECPhysicalDeviceSet) physicalDeviceWithAddress:] : 260 -> 256
~ -[CoreCECPhysicalDevice description] : 384 -> 380
~ +[CoreCECPhysicalDevice physicalDeviceTreeWithLogicalDevices:] : 700 -> 696
~ __IRDecoder_Initialize : 576 -> 588
~ -[CECFakeInterfaceListener interface:setAddressMask:error:] : 332 -> 328
~ -[CECFakeInterfaceListener interface:sendFrame:withRetryCount:error:] : 424 -> 420
~ -[CECFakeInterfaceListener interface:pingTo:acknowledged:error:] : 320 -> 316
~ -[CoreCECDevice setSupportedAudioFormats:error:] : 556 -> 552
~ -[CoreRCDevice removeAllOwningClients] : 320 -> 316
~ _CoreCECDeviceSourceRCProfileWithSupportedMenuCommands : 212 -> 228
~ -[CoreRCManager managedBusForDevice:] : 284 -> 280
~ -[CoreCECBusProvider updateAllowHibernation] : 420 -> 416
~ -[CoreCECBusProvider areMultipleCECBusses] : 288 -> 284
~ -[CoreCECBusProvider interface:hibernationChanged:] : 360 -> 356
~ -[CoreCECBusProvider reallocateAllCECAddresses:] : 916 -> 908
~ -[CoreRCManagerClient synchBuses:] : 600 -> 592
~ -[CoreRCBus initWithBus:] : 356 -> 352
~ -[CoreRCBus initWithCoder:] : 444 -> 440
~ -[CoreRCBus setManager:] : 244 -> 240
~ -[CoreRCBus removeAllExternalDevices] : 644 -> 632
~ -[CoreRCBus didRemoveFromManager:] : 232 -> 228
~ -[CoreRCBus notifyDelegateAllDevicesRemoved:] : 300 -> 296
~ -[CoreIRDeviceProvider dealloc] : 208 -> 216
~ -[CoreIRDeviceProvider protocolMask] : 300 -> 296
~ -[CoreIRDeviceProvider infraredCommandForCommand:] : 496 -> 492
~ -[CoreIRDeviceProvider dispatchEventsForCommand:toDevice:] : 892 -> 904
~ -[CoreIRDeviceProvider findDuplicateIRCommand:forCommand:device:] : 596 -> 588
~ -[CoreRCInterfaceController dealloc] : 308 -> 304
~ -[CoreRCInterfaceController addBundlesFromPaths:expectedClass:] : 288 -> 284
~ -[CoreRCInterfaceController startOnQueue:] : 708 -> 700
~ -[CoreRCInterfaceController firstInterface] : 236 -> 232
~ _CoreRCCommandForString : 96 -> 116
~ -[CECRouter interface:setAddressMask:error:] : 280 -> 276
~ -[CECRouter interface:setSnoopingMode:error:] : 280 -> 276
~ -[CECRouter interface:sendFrame:withRetryCount:error:] : 428 -> 424
~ -[CoreRCXPCService enumerateClientsHavingEntitlement:usingBlock:] : 312 -> 308
~ -[CoreRCXPCService enumerateClientsUsingBlock:] : 256 -> 252
~ ___42-[CoreRCXPCService connectionInvalidated:]_block_invoke : 384 -> 380
~ -[CoreRCXPCService manager:hasAdded:] : 428 -> 424
~ -[CoreCECDeviceProvider handleRequestShortAudioDescriptorMessage:fromDevice:] : 792 -> 784
~ -[CoreCECTypesInternal stringForDeckControlMode:] : 296 -> 292
~ -[CoreCECTypesInternal deckControlModeForString:] : 304 -> 300
~ -[CoreCECTypesInternal stringForDeckInfo:] : 296 -> 292
~ -[CoreCECTypesInternal deckInfoForString:] : 304 -> 300
~ -[CoreCECTypesInternal stringForPlayMode:] : 296 -> 292
~ -[CoreCECTypesInternal playModeForString:] : 304 -> 300
~ -[CoreCECTypesInternal stringForDeviceType:] : 296 -> 292
~ -[CoreCECTypesInternal deviceTypeForString:] : 304 -> 300
~ -[CoreCECTypesInternal stringForRequestType:] : 296 -> 292
~ -[CoreCECTypesInternal requestTypeForString:] : 304 -> 300
~ -[CoreCECTypesInternal stringForSystemAudioStatus:] : 296 -> 292
~ -[CoreCECTypesInternal systemAudioStatusForString:] : 304 -> 300
~ -[IRCommand initWithCoder:] : 368 -> 364
~ -[IRCommand encodeWithCoder:] : 232 -> 228
~ -[IRCommand description] : 344 -> 340
~ -[CoreCECDeviceClient setSupportedAudioFormats:count:error:] : 420 -> 424
~ -[CoreIRLearningSessionProvider enumerateMappingUsingBlock:] : 356 -> 352
~ -[CoreIRLearningSessionProvider processCapturedPattern] : 1436 -> 1476
~ -[CoreIRLearningSessionProvider _findDuplicateIRCommand:forCommand:device:] : 388 -> 384
~ -[CoreIRBusProvider migrateOldRemotes] : 1200 -> 1196
~ -[CoreIRBusProvider recreateDevices] : 1244 -> 1240
~ -[CoreIRBusProvider copyDevicePrefs:] : 632 -> 628
~ -[CoreIRBusProvider _removeMappingForCommand:from:] : 240 -> 236
~ _IRDecoder_Decode : 2336 -> 2312
~ -[CoreRCDevice mergePropertiesFromDevice:] : 460 -> 456
~ -[CoreCECBusProvider addDeviceWithAttributes:error:] : 1892 -> 1888
~ -[CoreCECBusProvider receivedMessage:] : 652 -> 648
~ -[CoreRCBus mergePropertiesFromBus:] : 608 -> 600
~ -[CoreIRDeviceProvider _removeMappingForCommand:] : 272 -> 268
~ -[CoreIRDeviceProvider _findButtonWithCommand:] : 68 -> 80
~ -[CoreIRDeviceProvider _setInfraredCommandPattern:repeatPattern:forCommand:] : 616 -> 600
~ -[CoreIRDeviceProvider handleIRCommand:] : 608 -> 604
~ -[CoreCECDeviceProvider handleRequestShortAudioDescriptorMessage:fromDevice:].cold.3 : 108 -> 104
~ -[IRInterface receivedFrame:] : 624 -> 616
~ -[CoreIRLearningSessionProvider _removeMappingForCommand:] : 284 -> 280
```
