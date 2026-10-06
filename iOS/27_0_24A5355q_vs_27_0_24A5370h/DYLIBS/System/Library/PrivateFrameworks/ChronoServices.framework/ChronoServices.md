## ChronoServices

> `/System/Library/PrivateFrameworks/ChronoServices.framework/ChronoServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xff1b0` | `0xff318` | **`+0x168`** |
| `__TEXT.__oslogstring` | `0x54ae` | `0x55de` | **`+0x130`** |
| `__TEXT.__const` | `0x7a38` | `0x7a18` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0xaa80` | `0xaa84` | **`+0x4`** |

### Other Changes

```diff

-721.0.0.0.0
+727.0.0.0.0
Symbols:
+ __ZNKSt9type_infoeqB9fqe220106ERKS_
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__110__function12__value_funcIFN5apple4aiml12flatbuffers26OffsetIvEEmEED2B9fqe220106Ev
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIN5apple4aiml12flatbuffers26OffsetIvEEEENS_16allocator_traitsIS7_EEEENS_19__allocation_resultINT0_7pointerENSB_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__125__throw_bad_function_callB9fqe220106Ev
+ __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEEC2B9fqe220106Em
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ _objc_retain_x12
- __ZNKSt9type_infoeqB9fqe220100ERKS_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__110__function12__value_funcIFN5apple4aiml12flatbuffers26OffsetIvEEmEED2B9fqe220100Ev
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIN5apple4aiml12flatbuffers26OffsetIvEEEENS_16allocator_traitsIS7_EEEENS_19__allocation_resultINT0_7pointerENSB_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__125__throw_bad_function_callB9fqe220100Ev
- __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEEC2B9fqe220100Em
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- _objc_retain_x13
Functions:
~ sub_18bbadc88 -> sub_18bcfbc88 : 784 -> 772
~ sub_18bbae0d0 -> sub_18bcfc0c4 : 116 -> 132
~ sub_18bbae70c -> sub_18bcfc710 : 608 -> 592
~ sub_18bbae96c -> sub_18bcfc960 : 1208 -> 1396
~ sub_18bbafedc -> sub_18bcfdf8c : 420 -> 436
~ sub_18bbb0298 -> sub_18bcfe358 : 228 -> 244
~ ___50-[CHSWidgetConfigurationReader _transformResults:]_block_invoke : 516 -> 512
~ sub_18bbb5e24 -> sub_18bd03ef0 : 556 -> 568
~ sub_18bbb903c -> sub_18bd07114 : 800 -> 816
~ sub_18bbb950c -> sub_18bd075f4 : 340 -> 352
~ ___52-[CHSWidgetConfiguration succinctDescriptionBuilder]_block_invoke : 628 -> 624
~ ___64-[CHSWidgetConfiguration descriptionBuilderWithMultilinePrefix:]_block_invoke : 588 -> 584
~ -[CHSWidgetConfiguration encodeWithCoder:] : 1392 -> 1384
~ -[CHSWidgetDescriptorProvider _lock_addNewDescriptorsFromDescriptors:] : 532 -> 516
~ -[CHSWidgetDescriptorProvider _lock_notifyObserversDescriptorsDidChange] : 412 -> 408
~ ___53-[CHSWidgetDescriptor(Deprecated) loadDefaultIntent:]_block_invoke_2 : 588 -> 584
~ -[CHSWidgetExtensionProvider _lock_notifyObserversExtensionsDidChange] : 412 -> 408
~ ___54-[CHSToolServiceConnection taskServiceStateDidChange:]_block_invoke_2 : 324 -> 320
~ -[CHSWidgetExtension initFromExtension:includeIntents:] : 1024 -> 1016
~ -[CHSWidgetExtension controlDescriptorForKind:] : 736 -> 732
~ -[CHSWidgetExtension widgetDescriptorForKind:] : 736 -> 732
~ -[CHSWidgetExtension isLinkedOnOrAfter:] : 640 -> 628
~ -[CHSWidgetExtension copyFilteredToOptions:] : 1136 -> 1124
~ ___45-[CHSWidgetDescriptorsBox _performValidation]_block_invoke : 1420 -> 1416
~ ___41-[CHSWidgetDescriptorsBox initWithCoder:]_block_invoke : 624 -> 620
~ -[CHSIntentRecommendationsContainer _recommendationsWithoutSchemaData] : 356 -> 352
~ -[CHSIntentRecommendationsContainer initWithCoder:] : 616 -> 612
~ -[CHSIntentRecommendationsContainer initWithBSXPCCoder:] : 528 -> 524
~ ___90-[CHSChronoServicesConnection subscribeToExtensions:fromClient:withOptions:outExtensions:]_block_invoke_2 : 820 -> 816
~ ___98-[CHSChronoServicesConnection acquireKeepAliveAssertionForExtensionBundleIdentifier:reason:error:]_block_invoke : 280 -> 276
~ ___61-[CHSChronoServicesConnection _queue_notifyDevicesDidChange:]_block_invoke : 324 -> 320
~ ___85-[CHSChronoServicesConnection _queue_notifyExtensionsDidChange:generatedWithOptions:]_block_invoke : 740 -> 736
~ -[CHSChronoServicesConnection _filterExtensions:toOptions:] : 1176 -> 1172
~ ___76-[CHSChronoServicesConnection _queue_notifyTimelineEntryRelevanceDidChange:]_block_invoke : 324 -> 320
~ ___71-[CHSChronoServicesConnection _queue_notifyHandleWidgetRelevanceEvent:]_block_invoke : 324 -> 320
~ ___79-[CHSChronoServicesConnection _queue_notifyDidReceiveActivityUpdate:payloadID:]_block_invoke : 324 -> 320
~ ___54-[CHSChronoServicesConnection _queue_createConnection]_block_invoke.97 : 500 -> 496
~ ___54-[CHSChronoServicesConnection _queue_createConnection]_block_invoke_5 : 436 -> 432
~ ___54-[CHSChronoServicesConnection _queue_createConnection]_block_invoke_2.101 : 440 -> 436
~ ___51-[CHSControlConfigurationReader _transformResults:]_block_invoke : 580 -> 576
~ -[_CHSRelevanceCacheBuf enumerateArchivedObjectsUsingBlock:] : 312 -> 300
~ __ZN5apple4aiml12flatbuffers217FlatBufferBuilder12CreateVectorINS1_6OffsetIvEEEENS4_INS1_6VectorIT_EEEEmRKNSt3__18functionIFS7_mEEE : 220 -> 216
~ -[_CHSWidgetRelevancePropertiesBuf supportsBackgroundRefresh] : 64 -> 60
~ -[_CHSWidgetRelevancePropertiesBuf isDeletion] : 64 -> 60
~ -[_CHSWidgetRelevancePropertiesBuf lastRelevanceUpdate] : 52 -> 48
~ -[_CHSIntentReferenceBuf stableHash] : 56 -> 52
~ -[_CHSIntentReferenceBuf enumerateIntentDataUsingBlock:] : 312 -> 300
~ -[_CHSIntentReferenceBuf enumerateSchemaDataUsingBlock:] : 312 -> 300
~ -[_CHSIntentReferenceBuf enumeratePartialIntentDataUsingBlock:] : 312 -> 300
~ __ZN5apple4aiml12flatbuffers215vector_downward4fillEm : 88 -> 84
~ __ZN5apple4aiml12flatbuffers217FlatBufferBuilder12CreateVectorIvEENS1_6OffsetINS1_6VectorINS4_IT_EEEEEEPKS7_m : 136 -> 124
~ -[CHSConfiguredWidgetDescriptor hash] : 780 -> 772
~ -[CHSMutableConfiguredWidgetDescriptor setSupportedRenderSchemes:] : 444 -> 440
~ -[CHSConfiguredWidgetContainerDescriptor initWithUniqueIdentifier:location:canAppearInSecureEnvironment:page:family:widgets:activeWidget:] : 924 -> 920
~ -[CHSConfiguredWidgetContainerDescriptor isSystemConfigured] : 292 -> 288
~ ___56-[CHSConfiguredWidgetContainerDescriptor initWithCoder:]_block_invoke : 688 -> 684
~ ___60-[CHSConfiguredWidgetContainerDescriptorsBox initWithCoder:]_block_invoke : 392 -> 388
~ -[CHSScreenshotManager allCachedSnapshotURLs] : 604 -> 600
~ -[CHSWidgetMetricsSpecification families] : 320 -> 316
~ -[CHSWidgetMetrics succinctDescriptionBuilder] : 792 -> 788
~ -[CHSWidgetMetrics filenameSafeSHAFrom:] : 648 -> 644
~ ___49-[CHSRemoteDeviceService nearbyDevicesDidChange:]_block_invoke : 344 -> 340
~ ___34-[CHSWidgetKeysBox initWithCoder:]_block_invoke : 392 -> 388
~ ___createPathByDecodingData : 1132 -> 1148
~ ___encodePathElementIntoData : 268 -> 260
~ sub_18bc18574 -> sub_18bd6654c : 172 -> 176
~ sub_18bc1ae78 -> sub_18bd68e54 : 280 -> 276
~ sub_18bc1d21c -> sub_18bd6b1f4 : 540 -> 552
~ sub_18bc1d438 -> sub_18bd6b41c : 136 -> 144
~ sub_18bc1dc40 -> sub_18bd6bc2c : 236 -> 248
~ sub_18bc1dd2c -> sub_18bd6bd24 : 268 -> 280
~ sub_18bc1f7c8 -> sub_18bd6d7cc : 228 -> 236
~ sub_18bc20978 -> sub_18bd6e984 : 236 -> 256
~ sub_18bc20b04 -> sub_18bd6eb24 : 132 -> 128
~ sub_18bc20c5c -> sub_18bd6ec78 : 92 -> 88
~ sub_18bc20d20 -> sub_18bd6ed38 : 244 -> 252
~ sub_18bc20e14 -> sub_18bd6ee34 : 252 -> 276
~ sub_18bc20f10 -> sub_18bd6ef48 : 256 -> 276
~ sub_18bc21010 -> sub_18bd6f05c : 252 -> 276
~ sub_18bc2110c -> sub_18bd6f170 : 272 -> 276
~ sub_18bc28424 -> sub_18bd7648c : 2228 -> 2220
~ sub_18bc28ee4 -> sub_18bd76f44 : 2872 -> 2860
~ sub_18bc2a2d4 -> sub_18bd78328 : 1464 -> 1480
~ sub_18bc2b37c -> sub_18bd793e0 : 100 -> 96
~ sub_18bc2b460 -> sub_18bd794c0 : 456 -> 464
~ sub_18bc2b628 -> sub_18bd79690 : 256 -> 264
~ sub_18bc2bc18 -> sub_18bd79c88 : 264 -> 268
~ sub_18bc2d1c8 -> sub_18bd7b23c : 564 -> 572
~ sub_18bc2d46c -> sub_18bd7b4e8 : 392 -> 400
~ sub_18bc2d5f4 -> sub_18bd7b678 : 468 -> 456
~ sub_18bc2dd34 -> sub_18bd7bdac : 476 -> 480
~ sub_18bc2e668 -> sub_18bd7c6e4 : 152 -> 164
~ sub_18bc2e730 -> sub_18bd7c7b8 : 700 -> 696
~ sub_18bc2ea40 -> sub_18bd7cac4 : 784 -> 792
~ sub_18bc2f2e8 -> sub_18bd7d374 : 288 -> 256
~ sub_18bc32dd8 -> sub_18bd80e44 : 512 -> 516
~ sub_18bc35180 -> sub_18bd831f0 : 248 -> 252
~ sub_18bc356a0 -> sub_18bd83714 : 984 -> 976
~ sub_18bc35a7c -> sub_18bd83ae8 : 1364 -> 1372
~ sub_18bc361cc -> sub_18bd84240 : 560 -> 564
~ sub_18bc3661c -> sub_18bd84694 : 296 -> 300
~ sub_18bc36c14 -> sub_18bd84c90 : 112 -> 124
~ sub_18bc37c60 -> sub_18bd85ce8 : 1140 -> 1104
~ sub_18bc380d4 -> sub_18bd86138 : 1748 -> 1744
~ sub_18bc3b2e4 -> sub_18bd89344 : 428 -> 432
~ sub_18bc40aa0 -> sub_18bd8eb04 : 232 -> 240
~ sub_18bc40b88 -> sub_18bd8ebf4 : 232 -> 240
~ sub_18bc43fc4 -> sub_18bd92038 : 1140 -> 1148
~ sub_18bc54748 -> sub_18bda27c4 : 588 -> 596
~ sub_18bc54a88 -> sub_18bda2b0c : 588 -> 596
~ sub_18bc5a8b4 -> sub_18bda8940 : 1112 -> 1100
~ ___swift_closure_destructor.3 : 164 -> 172
~ sub_18bc5c274 -> sub_18bdaa2fc : 220 -> 212
~ ___swift_closure_destructor : 172 -> 180
~ sub_18bc5d978 -> sub_18bdaba00 : 120 -> 140
~ sub_18bc5dbd4 -> sub_18bdabc70 : 616 -> 608
~ sub_18bc5df28 -> sub_18bdabfbc : 364 -> 368
~ sub_18bc5e094 -> sub_18bdac12c : 384 -> 388
~ sub_18bc5e214 -> sub_18bdac2b0 : 5436 -> 5484
~ sub_18bc5f758 -> sub_18bdad824 : 3160 -> 3184
~ sub_18bc62f40 -> sub_18bdb1024 : 380 -> 376
~ sub_18bc6321c -> sub_18bdb12fc : 368 -> 364
~ sub_18bc6338c -> sub_18bdb1468 : 404 -> 392
~ sub_18bc63678 -> sub_18bdb1748 : 364 -> 356
~ sub_18bc637e4 -> sub_18bdb18ac : 368 -> 360
~ sub_18bc63c20 -> sub_18bdb1ce0 : 412 -> 400
~ sub_18bc63e34 -> sub_18bdb1ee8 : 632 -> 624
~ sub_18bc65410 -> sub_18bdb34bc : 1332 -> 1312
~ sub_18bc65944 -> sub_18bdb39dc : 272 -> 288
~ sub_18bc65a54 -> sub_18bdb3afc : 652 -> 672
~ sub_18bc6630c -> sub_18bdb43c8 : 1432 -> 1456
~ sub_18bc66a78 -> sub_18bdb4b4c : 524 -> 508
~ sub_18bc66eb8 -> sub_18bdb4f7c : 320 -> 332
~ sub_18bc67060 -> sub_18bdb5130 : 516 -> 536
~ sub_18bc67480 -> sub_18bdb5564 : 428 -> 440
~ sub_18bc67c90 -> sub_18bdb5d80 : 628 -> 592
~ sub_18bc68560 -> sub_18bdb662c : 488 -> 484
~ sub_18bc68b60 -> sub_18bdb6c28 : 328 -> 332
~ sub_18bc73a50 -> sub_18bdc1b1c : 344 -> 340
~ sub_18bc73d34 -> sub_18bdc1dfc : 364 -> 360
~ sub_18bc74510 -> sub_18bdc25d4 : 1328 -> 1336
~ sub_18bc74bd0 -> sub_18bdc2c9c : 1124 -> 1128
~ sub_18bc77754 -> sub_18bdc5824 : 168 -> 188
~ sub_18bc77d14 -> sub_18bdc5df8 : 608 -> 604
~ sub_18bc8d1e4 -> sub_18bddb2c4 : 444 -> 440
~ ___swift_closure_destructor.244 : 140 -> 148
~ sub_18bc8f194 -> sub_18bddd278 : 792 -> 784
~ sub_18bc9826c -> sub_18bde6348 : 768 -> 784
~ sub_18bc9980c -> sub_18bde78f8 : 396 -> 392
~ sub_18bc99fc0 -> sub_18bde80a8 : 4972 -> 4948
~ sub_18bc9da10 -> sub_18bdebae0 : 920 -> 940
~ sub_18bc9dda8 -> sub_18bdebe8c : 2276 -> 2320
~ sub_18bc9f430 -> sub_18bded540 : 4364 -> 4388
~ sub_18bca1944 -> sub_18bdefa6c : 388 -> 404
~ sub_18bca58f8 -> sub_18bdf3a30 : 1228 -> 1268
~ sub_18bca9978 -> sub_18bdf7ad8 : 596 -> 604
CStrings:
+ "<CHSWidgetDescriptorProvider:%p> Added descriptors with count: %lu"
+ "<CHSWidgetDescriptorProvider:%p> Cache descriptors for container identifier: %{public}@ returned error: %{public}@"
+ "<CHSWidgetDescriptorProvider:%p> No descriptor update needed. Already discovered descriptor count: %lu"
+ "CHSWidget initialized with bad bundle identifier (%{public}@) or kind (%{public}@)"
+ "Completing %{public}s failed; unable to obtain the remote target"
+ "Error acquiring monitor assertion %{public}@"
+ "Error encoding %{public}@: %{public}@"
+ "Error encoding object: %{public}@"
+ "Extension subscription updating options to %{public}@, forcing update %{public}@"
+ "Failed to remove widget host with identifier %{public}@; unable to obtain the remote target"
+ "Failed to set configuration for widget host with identifier %{public}@; unable to obtain the remote target"
+ "Notifying %lu clients of %lu widget extensions changed for opt %{public}@."
+ "Notifying of activity update %{public}@ payload ID %{public}@"
+ "Notifying of widget relevance event %{public}@"
+ "Pairing device %{public}@"
+ "Received cache reset request, error: %{public}@"
+ "Received controls reload request for (%{public}@) of kind (%{public}@) with reason (%{public}@), error: %{public}@"
+ "Received extension info (%{public}@) for (%{public}@), error: %{public}@"
+ "Received extension info (%{public}@), error: %{public}@"
+ "Received timeline (%{public}@) for widget: %{public}@, error: %{public}@"
+ "Received timeline reload request for (%{public}@) of kind (%{public}@) with reason (%{public}@), error: %{public}@"
+ "Setting remote widgets to %{public}s"
+ "Unable to obtain extension info for %{public}@; unable to obtain the remote target"
+ "Unable to obtain timeline for widget (%{public}@); unable to obtain the remote target"
+ "Unpairing device %{public}@"
+ "noting foreground launch for %{public}@ with widget extension; trigger metadata query"
+ "xpc: extensions subscription - result: %{public}@"
- "<CHSWidgetDescriptorProvider:%p> Added descriptors: %@ for extension count: %lu"
- "<CHSWidgetDescriptorProvider:%p> Cache descriptors for container identifier: %@ returned error: %@"
- "<CHSWidgetDescriptorProvider:%p> No descriptor update needed. Already discovered descriptors: %@"
- "CHSWidget initialized with bad bundle identifier (%@) or kind (%@)"
- "Completing %s failed; unable to obtain the remote target"
- "Error acquiring monitor assertion %@"
- "Error encoding %@: %{public}@"
- "Error encoding object: %@"
- "Extension subscription updating options to %{public}@, forcing update %@"
- "Failed to remove widget host with identifier %@; unable to obtain the remote target"
- "Failed to set configuration for widget host with identifier %@; unable to obtain the remote target"
- "Notifying %lu clients of %lu widget extensions changed for opt %@."
- "Notifying of activity update %@ payload ID %@"
- "Notifying of widget relevance event %@"
- "Pairing device %@"
- "Received cache reset request, error: %@"
- "Received controls reload request for (%@) of kind (%@) with reason (%@), error: %@"
- "Received extension info (%@) for (%@), error: %@"
- "Received extension info (%@), error: %@"
- "Received timeline (%@) for widget: %@, error: %@"
- "Received timeline reload request for (%@) of kind (%@) with reason (%@), error: %@"
- "Setting remote widgets to %s"
- "Unable to obtain extension info for %@; unable to obtain the remote target"
- "Unable to obtain timeline for widget (%@); unable to obtain the remote target"
- "Unpairing device %@"
- "noting foreground launch for %@ with widget extension; trigger metadata query"
- "xpc: extensions subscription - result: %@"
```
