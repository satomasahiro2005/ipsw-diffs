## MetricsKit

> `/System/Library/PrivateFrameworks/MetricsKit.framework/MetricsKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f38c` | `0x3f274` | **`-0x118`** |

### Other Changes

```text
Functions:
~ -[MTPromiseCompletionBlocks flushCompletionBlocksWithPromiseResult:] : 404 -> 400
~ -[NSArray(Utilities) mt_map:] : 404 -> 400
~ -[NSUUID(Base62) mt_base62String] : 236 -> 240
~ -[NSObject(Utilities) mt_nullableValueForKeyPathArray:index:] : 1008 -> 1004
~ ___50-[MTMetricsDataPredicate evaluateWithMetricsData:]_block_invoke : 440 -> 436
~ -[MTEventRecorderAMSMetricsDelegate setMonitorsLifecycleEvents:] : 380 -> 376
~ -[MTEventRecorderAMSMetricsDelegate lookupItunesAccount:] : 432 -> 428
~ ___58-[MTEventRecorderAMSMetricsDelegate flushUnreportedEvents]_block_invoke_2 : 396 -> 392
~ -[NSArray(Utilities) mt_deepCopy] : 364 -> 356
~ -[NSArray(Utilities) mt_condensedArray] : 572 -> 568
~ -[MTConfig applyDeRes:sources:] : 500 -> 496
~ -[MTIDScheme calculateHash] : 380 -> 376
~ -[MTPerfUtils(DNS) DNSServersIPAddresses] : 440 -> 428
~ -[MTTreatmentAction performAction:context:] : 1172 -> 1164
~ -[MTTreatmentAction performAction:atKeyIndex:context:] : 904 -> 900
~ +[MTReflectUtil mergeAndCleanDictionaries:] : 364 -> 360
~ -[MTPAFActivity addItemsFromPlaylist:pafKit:] : 756 -> 752
~ -[MTPAFActivity updateItemActivities:] : 268 -> 264
~ ___48-[MTStandardIDService resetIDForTopics:options:]_block_invoke : 632 -> 628
~ ___48-[MTStandardIDService resetIDForTopics:options:]_block_invoke_2 : 348 -> 344
~ -[MTStandardIDService generateIDInfo:secret:dsId:correlationIDs:] : 1060 -> 1056
~ ___30-[MTStandardIDService _getIDs]_block_invoke : 640 -> 636
~ -[NSDictionary(Utilities) mt_removingKeys:] : 332 -> 328
~ -[NSDictionary(Utilities) mt_deepCopy] : 640 -> 624
~ -[MTHLSVideoPlaylist addRollInfoItems:] : 244 -> 240
~ ___37-[MTConstraintTreatmentFilter apply:]_block_invoke_2 : 1140 -> 1136
~ ___52-[MTMediaActivityEventHandler didCreateMetricsData:]_block_invoke : 448 -> 444
~ -[MTIDCloudKitStore syncForSchemes:options:] : 564 -> 560
~ ___44-[MTIDCloudKitStore syncForSchemes:options:]_block_invoke : 748 -> 744
~ -[MTIDCloudKitStore resetSchemes:options:] : 532 -> 528
~ ___45-[MTIDCloudKitStore maintainSchemes:options:]_block_invoke : 728 -> 724
~ ___30-[MTIDCache removeNamespaces:]_block_invoke : 536 -> 532
~ -[MTIDCache removeUnsyncedNamespaces] : 436 -> 432
~ +[MTPromise(Composition) _resultOfComposition:errors:] : 864 -> 856
~ +[MTPromise(Composition) _findUnfinishedPromise:] : 608 -> 600
~ +[MTPromise(Composition) cancelPromisesInComposition:] : 524 -> 516
~ -[MTURLDeresAction initWithField:configDictionary:] : 552 -> 548
~ -[MTNumberDeresAction initWithField:configDictionary:] : 564 -> 560
~ ___29-[MTMetricsData toDictionary]_block_invoke : 488 -> 484
~ ___38-[MTMetricsData userAndClientIDFields]_block_invoke : 464 -> 460
~ +[NSURLComponents(Encoding) mt_queryParameterStringForDictionary:] : 484 -> 480
~ +[MTEventFieldsUtil applyFieldsMap:data:sectionName:error:] : 1268 -> 1260
~ -[MTIDConfig initWithDictionary:] : 2296 -> 2288
~ -[MTIDConfig calculateCombinedHashForNamespaces:] : 316 -> 312
~ ___53-[MTIDCloudKitPromiseManager finishPromisesOfRecord:]_block_invoke : 248 -> 244
~ -[MTPAFTracker updateEventData:] : 444 -> 440
~ -[MTPAFTracker forEachVideoTracker:] : 344 -> 340
~ -[MTPAFTracker startActivity:playbackRate:atMilliseconds:triggerType:reason:eventData:] : 564 -> 560
~ ___35-[MTBaseEventDataProvider cookies:]_block_invoke_2 : 500 -> 496
~ -[MTFinalValidationFilter validateFields:] : 536 -> 532
~ -[MTIDCompositeSecretStore schemesGroupedByStore:] : 436 -> 432
~ -[MTIDCompositeSecretStore resetSchemes:options:] : 532 -> 528
~ -[MTIDCompositeSecretStore maintainSchemes:options:] : 560 -> 556
~ -[MTIDCompositeSecretStore syncForSchemes:options:] : 536 -> 532
~ -[MTEventDataProvider knownFieldMethodsForKnownFields:] : 528 -> 524
~ -[MTEventDataProvider processMetricsData:performanceData:] : 824 -> 820
~ -[MTTreatmentProfile initWithConfigDictionary:] : 708 -> 704
~ -[MTIDSyncEngine addRecordIDsToSave:recordIDsToDelete:qualityOfService:] : 972 -> 968
~ ___72-[MTIDSyncEngine addRecordIDsToSave:recordIDsToDelete:qualityOfService:]_block_invoke_2 : 296 -> 292
~ ___45-[MTIDSyncEngine handleFetchedRecords:error:]_block_invoke : 276 -> 272
```
