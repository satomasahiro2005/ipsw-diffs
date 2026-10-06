## DiagnosticRequestService

> `/System/Library/PrivateFrameworks/DiagnosticRequestService.framework/DiagnosticRequestService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6a4dc` | `0x6a2d0` | **`-0x20c`** |

### Other Changes

```diff

-460.0.0.0.0
+464.0.0.0.0
Functions:
~ -[DRSRequest totalLogSizeBytes] : 260 -> 256
~ -[DRSRequest _markLogsAsPurgeableWithUrgencyWithDeleteFallback:] : 1572 -> 1568
~ -[DRSRequest _logsDescription] : 408 -> 404
~ -[DRSRequest jsonCompatibleDictionaryRepresentationVerbose:] : 1984 -> 1980
~ -[DRSRequest _addLogMOs:] : 352 -> 348
~ -[DRSRequest performClientOnReceiptWork:dampeningOutcome:] : 980 -> 968
~ -[DRSRequest hasUploadableContent] : 304 -> 300
~ -[DRSRequest _deleteLogs] : 428 -> 424
~ -[DRSRequest _populateLogsArray_ON_MOC_QUEUE:] : 1124 -> 1120
~ ___85+[DRSRequest requestsForFilterPredicate:context:sortDescriptors:fetchLimit:errorOut:]_block_invoke : 700 -> 696
~ +[DRSRequest uploadedBytesSinceDate:context:errorOut:] : 452 -> 448
~ ___109+[DRSRequest cleanRequestRecordsFromPersistentContainer:removeFiles:removeRecord:matchingPredicate:errorOut:]_block_invoke : 1232 -> 1228
~ ___78+[DRSRequest unblockStrandedUploadingRecordsFromPersistentContainer:errorOut:]_block_invoke : 1168 -> 1164
~ ___53+[DRSRequest migrateRequestDataStoreAtPath:errorOut:]_block_invoke : 556 -> 552
~ -[DRSSubmitLogToCKContainerRequest initWithXPCDict:] : 924 -> 920
~ -[DRSProtoDiagnosticRequestStatsBatch dictionaryRepresentation] : 460 -> 456
~ -[DRSProtoDiagnosticRequestStatsBatch writeTo:] : 308 -> 304
~ -[DRSProtoDiagnosticRequestStatsBatch copyWithZone:] : 356 -> 352
~ -[DRSProtoDiagnosticRequestStatsBatch mergeFrom:] : 332 -> 328
~ _DRValidateCKRecordDictionary : 1124 -> 1120
~ -[DRSProtoDiagnosticUploadRequest dictionaryRepresentation] : 496 -> 492
~ -[DRSProtoDiagnosticUploadRequest writeTo:] : 340 -> 336
~ -[DRSProtoDiagnosticUploadRequest copyWithZone:] : 396 -> 392
~ -[DRSProtoDiagnosticUploadRequest mergeFrom:] : 360 -> 356
~ -[DRSProtoEnableDataGatheringRequestBatch dictionaryRepresentation] : 460 -> 456
~ -[DRSProtoEnableDataGatheringRequestBatch writeTo:] : 308 -> 304
~ -[DRSProtoEnableDataGatheringRequestBatch copyWithZone:] : 356 -> 352
~ -[DRSProtoEnableDataGatheringRequestBatch mergeFrom:] : 332 -> 328
~ -[DRSProtoDiagnosticRequestStats dictionaryRepresentation] : 548 -> 544
~ -[DRSProtoDiagnosticRequestStats writeTo:] : 404 -> 400
~ -[DRSProtoDiagnosticRequestStats copyWithZone:] : 476 -> 472
~ -[DRSProtoDiagnosticRequestStats mergeFrom:] : 392 -> 388
~ -[DRSRequest(CKRecord_Private) fileURLs] : 328 -> 324
~ -[DRSRequest(CKRecord_Private) fileNames] : 316 -> 312
~ -[DRSRequest(CKRecord_Private) filePaths] : 316 -> 312
~ -[DRSRequest(CKRecord_Private) fileAssets] : 328 -> 324
~ -[DRSRequest(CKRecord_Private) protoFileDescriptions] : 492 -> 488
~ -[DRSRequestAllStats(CKSupport) terminalRequestProtobufRepresentation] : 1744 -> 1740
~ -[DRSRequestAllStats(CKSupport) generateCoreAnalyticsEvents:] : 1748 -> 1744
~ -[DRSCloudKitHelper _handleRAPIDRequests:xpcActivity:errorsOut:] : 752 -> 748
~ -[DRSCloudKitHelper _requestsPassingUploadSizeCap:remainingQuota:] : 516 -> 512
~ -[DRSCloudKitHelper uploadRequests:contactDecisionServer:xpcActivity:remainingUploadQuota:backingPersistentContainer:completionHandler:] : 1584 -> 1576
~ ___136-[DRSCloudKitHelper uploadRequests:contactDecisionServer:xpcActivity:remainingUploadQuota:backingPersistentContainer:completionHandler:]_block_invoke : 304 -> 300
~ ___136-[DRSCloudKitHelper uploadRequests:contactDecisionServer:xpcActivity:remainingUploadQuota:backingPersistentContainer:completionHandler:]_block_invoke.232 : 1960 -> 1952
~ ___136-[DRSCloudKitHelper uploadRequests:contactDecisionServer:xpcActivity:remainingUploadQuota:backingPersistentContainer:completionHandler:]_block_invoke.237 : 1156 -> 1144
~ ___136-[DRSCloudKitHelper uploadRequests:contactDecisionServer:xpcActivity:remainingUploadQuota:backingPersistentContainer:completionHandler:]_block_invoke.242 : 984 -> 980
~ -[DRSCloudKitHelper shouldUploadRequests:xpcActivity:replyHandler:] : 360 -> 356
~ -[DRSCloudKitHelper shouldEnableDataGathering:xpcActivity:replyHandler:] : 496 -> 492
~ ___72-[DRSCloudKitHelper shouldEnableDataGathering:xpcActivity:replyHandler:]_block_invoke : 592 -> 584
~ -[DRSCloudKitHelper _sendDecisionServerRequests:xpcActivity:replyHandler:] : 2148 -> 2136
~ ___74-[DRSCloudKitHelper _sendDecisionServerRequests:xpcActivity:replyHandler:]_block_invoke : 1276 -> 1268
~ -[DRSCKConfigStore _currentConfig_ON_MOC_QUEUE:] : 1288 -> 1284
~ -[DRSService _cleanupLogsForDRSRequest:state:transaction:] : 416 -> 412
~ ___116-[DRSService _ckQueueDownstreamOnly_uploadInFlightWithTransaction:xpcActivity:ckHelper:isExpedited:completionBlock:]_block_invoke : 1148 -> 1144
~ ___116-[DRSService _ckQueueDownstreamOnly_uploadInFlightWithTransaction:xpcActivity:ckHelper:isExpedited:completionBlock:]_block_invoke.122 : 1408 -> 1400
~ ___116-[DRSService _ckQueueDownstreamOnly_uploadInFlightWithTransaction:xpcActivity:ckHelper:isExpedited:completionBlock:]_block_invoke_2 : 296 -> 292
~ ___125-[DRSService _ckQueueOnly_submitOutstandingEnableDataGatheringQueriesWithTransaction:xpcActivity:ckHelper:followupWorkBlock:]_block_invoke_2 : 296 -> 292
~ ___62-[DRSService _runReportingSessionWithTransaction:xpcActivity:]_block_invoke_3 : 548 -> 544
~ +[DRSService _currentUploadSession_ON_MOC_QUEUE:errorOut:] : 956 -> 952
~ -[DRSProtoDiagnosticUploadRequestBatch dictionaryRepresentation] : 460 -> 456
~ -[DRSProtoDiagnosticUploadRequestBatch writeTo:] : 308 -> 304
~ -[DRSProtoDiagnosticUploadRequestBatch copyWithZone:] : 356 -> 352
~ -[DRSProtoDiagnosticUploadRequestBatch mergeFrom:] : 332 -> 328
~ -[DRSProtoEnableDataGatheringRequestResponseBatch dictionaryRepresentation] : 404 -> 400
~ -[DRSProtoEnableDataGatheringRequestResponseBatch writeTo:] : 276 -> 272
~ -[DRSProtoEnableDataGatheringRequestResponseBatch copyWithZone:] : 316 -> 312
~ -[DRSProtoEnableDataGatheringRequestResponseBatch mergeFrom:] : 260 -> 256
~ ___70-[DRSTaskingEventPublisher publishConfigUpdateForTeamID:state:config:]_block_invoke : 428 -> 424
~ ___58-[DRSTaskingEventPublisher publishCurrentConfigForTeamID:]_block_invoke : 752 -> 744
~ -[DRSTaskingEventPublisher _removeSubscriber:] : 416 -> 412
~ -[DRSTaskingDecisionMaker _teamTaskingsPassingBuild:logTelemetry:allowWildcardBuild:] : 1220 -> 1200
~ -[DRSTaskingDecisionMaker _configsPassingSampling:logTelemetry:] : 1836 -> 1840
~ -[DRSTaskingDecisionMaker _configsPassingPerTeamHysteresis:logTelemetry:] : 340 -> 336
~ -[DRSTaskingDecisionMaker _configsPassingOverallHysteresis:logTelemetry:] : 2488 -> 2472
~ -[DRSTaskingDecisionMaker acceptedConfigs:logTelemetry:allowWildcardBuild:] : 2688 -> 2708
~ ___43-[DRSTaskingDecisionMaker acceptedCancels:]_block_invoke : 1060 -> 1056
~ -[DRSRequestStats logSizeBytes] : 260 -> 256
~ -[DRSRequestStats _debugDescription:] : 588 -> 584
~ +[DRSRequestAllStats statsForRequests:] : 320 -> 316
~ +[DRSSystemProfile hashForSHA256Digest:] : 168 -> 176
~ ___120+[DRSEnableDataGatheringQuery enableDataGatheringQueriesForFilterPredicate:context:sortDescriptors:fetchLimit:errorOut:]_block_invoke : 552 -> 548
~ +[DRSEnableDataGatheringQuery cachedQueryResponseForQuery:inContext:errorOut:] : 604 -> 600
~ ___96-[DRSTaskingManager processTaskingMessage:cloudChannelConfig:transaction:shouldEmitCATelemetry:]_block_invoke : 612 -> 608
~ ___95-[DRSTaskingManager processCancelMessage:cloudChannelConfig:transaction:shouldEmitCATelemetry:]_block_invoke.46 : 444 -> 440
~ -[DRSTaskingManager checkConfigsForInvalidation:] : 2444 -> 2436
~ ___49-[DRSTaskingManager checkConfigsForInvalidation:]_block_invoke : 968 -> 964
~ ___38-[DRSTaskingMessageChannel subscribe:]_block_invoke : 1736 -> 1732
~ -[DRSTaskingMessageChannel connection:channelSubscriptionsFailedWithFailures:] : 492 -> 488
~ -[DRSProtoDiagnosticUploadRequestResponseBatch dictionaryRepresentation] : 404 -> 400
~ -[DRSProtoDiagnosticUploadRequestResponseBatch writeTo:] : 276 -> 272
~ -[DRSProtoDiagnosticUploadRequestResponseBatch copyWithZone:] : 316 -> 312
~ -[DRSProtoDiagnosticUploadRequestResponseBatch mergeFrom:] : 260 -> 256
~ ___91-[DRSConfigPersistedStore configMetadatasForPredicate:sortDescriptors:fetchLimit:errorOut:]_block_invoke : 600 -> 596
~ ___50-[DRSConfigPersistedStore clearStoreWithErrorOut:]_block_invoke : 1280 -> 1272
~ -[DRSConfigPersistedStore _ON_MOC_deleteCloudChannelConfigMOs:] : 468 -> 464
~ ___49-[DRSCancelTaskingMessage jsonDictRepresentation]_block_invoke : 348 -> 344
~ ___44-[DRSCancelTaskingMessage initWithJSONDict:]_block_invoke : 756 -> 752
~ +[DRSTeamDampeningConfiguration teamIdToTeamDampeningConfigFromPlistDirectoryPath:errorOut:] : 1928 -> 1912
~ -[DRSTeamDampeningConfiguration _initWithTeamDampeningConfigMO_ON_MOC_QUEUE:] : 604 -> 600
~ ___92+[DRSDampeningManager removeExistingDampeningManagerStateFromManagedObjectContext:errorOut:]_block_invoke : 368 -> 364
~ ___87+[DRSDampeningManager dampeningManagerFromPersistentContainer:deleteBadState:errorOut:]_block_invoke.572 : 532 -> 528
~ -[DRSDampeningManager _ON_MOC_QUEUE_initWith:persistentContainer:] : 1016 -> 1008
~ sub_258860f70 -> sub_259c52da0 : 588 -> 584
~ sub_2588616c4 -> sub_259c534f0 : 660 -> 644
~ sub_258861f44 -> sub_259c53d60 : 528 -> 516
~ sub_258862610 -> sub_259c54420 : 664 -> 648
~ sub_258863190 -> sub_259c54f90 : 540 -> 528
```
