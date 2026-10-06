## CoreMediaIO

> `/System/Library/Frameworks/CoreMediaIO.framework/CoreMediaIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3eb8c` | `0x3ea8c` | **`-0x100`** |

### Other Changes

```diff

-5628.0.0.0.0
+5630.0.0.0.1
Functions:
~ +[CMIOExtensionProvider proprietaryDefaultsDomainForAuditToken:] : 3528 -> 3524
~ _CMIOFilename : 76 -> 72
~ ___59-[CMIOExtensionProvider finishProviderContextRegistration:]_block_invoke : 1180 -> 1176
~ ___55-[CMIOExtensionProvider pluginStatesForClientID:reply:]_block_invoke : 2320 -> 2316
~ -[CMIOExtensionProvider _clientQueue_internalPropertyStatesForProperties:] : 548 -> 544
~ ___53-[CMIOExtensionProviderContext pluginStates:message:]_block_invoke : 988 -> 980
~ ___58-[CMIOExtensionSessionProvider initWithEndpoint:delegate:]_block_invoke : 1108 -> 1096
~ ___40-[CMIOExtensionDiscoverySession devices]_block_invoke : 296 -> 292
~ ___107-[CMIOExtensionStream _initWithLocalizedName:streamID:direction:clockType:customClockConfiguration:source:]_block_invoke : 772 -> 768
~ -[CMIOExtensionStream clientQueue_updateMutableStreamPropertiesByPolicy] : 1264 -> 1260
~ -[CMIOExtensionStream sendSampleBuffer:discontinuity:hostTimeInNanoseconds:] : 1444 -> 1440
~ -[CMIOExtensionDevice _clientQueue_internalPropertyStatesForProperties:] : 1112 -> 1108
~ -[CMIOExtensionDevice didRegister:] : 724 -> 712
~ -[CMIOExtensionDevice didUnregister] : 484 -> 480
~ ___49-[CMIOExtensionProvider notifyPropertiesChanged:]_block_invoke : 352 -> 348
~ -[CMIOExtensionProvider removeAllProviderContexts] : 448 -> 444
~ ___47-[CMIOExtensionProvider removeProviderContext:]_block_invoke : 1884 -> 1876
~ -[CMIOExtensionProvider unregisterStream:withDeviceID:notify:error:] : 1624 -> 1620
~ ___64-[CMIOExtensionProvider deviceStatesForClientID:deviceID:reply:]_block_invoke : 2236 -> 2232
~ -[CMIOExtensionProvider setDevicePropertyValuesForClientID:deviceID:propertyValues:reply:] : 892 -> 888
~ ___63-[CMIOExtensionProvider startStreamForClientID:streamID:reply:]_block_invoke : 1912 -> 1908
~ -[CMIOExtensionProvider notifyAvailableDevicesChanged:] : 532 -> 528
~ ___55-[CMIOExtensionProvider notifyAvailableDevicesChanged:]_block_invoke : 320 -> 316
~ -[CMIOExtensionProvider notifyAvailableStreamsChangedWithDeviceID:streamIDs:] : 548 -> 544
~ ___77-[CMIOExtensionProvider notifyAvailableStreamsChangedWithDeviceID:streamIDs:]_block_invoke : 344 -> 340
~ -[CMIOExtensionProvider _clientQueue_notifyDevicePropertiesChangedWithDeviceID:propertyStates:] : 444 -> 440
~ -[CMIOExtensionProvider _clientQueue_notifyStreamPropertiesChangedWithStreamID:propertyStates:] : 444 -> 440
~ -[CMIOExtensionProvider _clientQueue_notifyIsRunningSomewhereForStream:] : 904 -> 900
~ -[CMIOExtensionProvider _clientQueue_sendSampleForStream:sample:] : 1092 -> 1084
~ ___79-[CMIOExtensionProvider notifyScheduledOutputChangedForStream:scheduledOutput:]_block_invoke : 344 -> 340
~ +[CMIOExtensionStreamFormat copyXPCArrayFromFormats:] : 396 -> 392
~ -[CMIOExtensionClient authorizationStatusForMediaType:] : 436 -> 432
~ -[CMIOExtensionClient requestAccessForMediaType:performPreFlightTest:reply:] : 488 -> 484
~ ___76-[CMIOExtensionClient requestAccessForMediaType:performPreFlightTest:reply:]_block_invoke : 488 -> 480
~ _CMIOFormatDescriptionSignifiesDiscontinuity : 564 -> 572
~ -[CMIOExtensionSessionStream cachedPropertyStatesForProperties:] : 572 -> 568
~ -[CMIOExtensionSessionDevice initWithPropertyStates:streamsStates:provider:] : 2208 -> 2204
~ -[CMIOExtensionSessionDevice updateStreamIDs:] : 1024 -> 1016
~ -[CMIOExtensionSessionDevice unregister] : 276 -> 272
~ -[CMIOExtensionSessionDevice cachedPropertyStatesForProperties:] : 572 -> 568
~ -[CMIOExtensionSessionProvider cachedPropertyStatesForProperties:] : 572 -> 568
~ -[CMIOExtensionSessionProvider extension:availableDevicesChanged:] : 976 -> 968
~ -[CMIOExtensionProxyContext dealloc] : 540 -> 536
~ -[CMIOExtensionProxyContext invalidate] : 532 -> 528
~ -[CMIOExtensionProxy invalidate] : 368 -> 364
~ ___53-[CMIOExtensionProviderContext deviceStates:message:]_block_invoke : 804 -> 800
~ _CMIOSampleBufferCopySampleAttachments : 452 -> 408
```
