## DiagnosticExtensionsDaemon

> `/System/Library/PrivateFrameworks/DiagnosticExtensionsDaemon.framework/DiagnosticExtensionsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75ca0` | `0x75ab0` | **`-0x1f0`** |

### Other Changes

```text
Functions:
~ -[DEDRequestRecord formattedResponseHeader:] : 472 -> 468
~ -[DEDRequestRecord formattedRequestHeader:session:cookies:] : 1016 -> 1004
~ -[DEDRadarFinisher finishSession:withConfiguration:] : 2688 -> 2676
~ -[DEDRadarFinisher getUploadItemForTask:] : 324 -> 320
~ -[DEDRadarFinisher allUploadsComplete] : 260 -> 256
~ -[DEDRadarFinisher getVerificationTaskForDataTask:] : 324 -> 320
~ -[DEDRadarFinisher allVerificationTasksComplete] : 260 -> 256
~ ___44-[DEDRadarFinisher processVerifyTaskResults]_block_invoke : 708 -> 704
~ -[DEDRadarFinisher URLSession:task:didSendBodyData:totalBytesSent:totalBytesExpectedToSend:] : 612 -> 608
~ +[DEDAttachmentGroup groupWithDictionary:] : 728 -> 724
~ +[DEDAttachmentGroup groupWithDEGroup:identifier:] : 656 -> 652
~ -[DEDAttachmentGroup totalFileSize] : 316 -> 312
~ -[DEDAttachmentGroup serialize] : 756 -> 752
~ -[DEDAttachmentHandler _processAttachments:withSessionIdentifier:extension:shouldAddClassBDataProtection:rootDir:annotatedGroup:useAppleArchive:] : 2072 -> 2064
~ -[DEDAttachmentHandler collectedGroupsWithSessionIdentifier:matchingExtensions:] : 1360 -> 1348
~ -[DEDBugSession resumePendingOperations] : 2096 -> 2092
~ -[DEDBugSession cancelDiagnosticExtensionWithIdentifier:] : 376 -> 372
~ -[DEDBugSession cancelDiagnosticExtensionWithIdentifier:invocationNumber:] : 444 -> 440
~ -[DEDBugSession cancel] : 704 -> 696
~ -[DEDBugSession adoptFiles:withCompletion:] : 448 -> 444
~ -[DEDBugSession hasCollected:isCollecting:identifiers:] : 1412 -> 1404
~ -[DEDBugSession terminateExtension:withInfo:] : 756 -> 752
~ -[DEDBugSession cleanupFinishedUploads:] : 1352 -> 1348
~ -[DEDBugSession populateLocalizedTextDataForExtensions:] : 612 -> 608
~ -[DEDBugSession updateCachedExtensionsWithLocalizedTextData:] : 588 -> 584
~ -[DEDBugSession hashExtensions:] : 376 -> 372
~ -[DEDSeedingFinisher finishSession:withConfiguration:] : 2692 -> 2680
~ -[DEDSeedingFinisher cleanup] : 1024 -> 1020
~ -[DEDSeedingFinisher updateUploadProgressOnSessionIfNeeded] : 572 -> 568
~ -[DEDSeedingFinisher uploadsAreComplete] : 260 -> 256
~ -[DEDSeedingFinisher encryptFilesInDirectory:withKey:] : 624 -> 620
~ -[DEDSeedingFinisher archiveItemsInDirectory:] : 868 -> 864
~ -[NSSet(DEDEnumerable) ded_flatMapWithBlock:] : 392 -> 388
~ -[NSSet(DEDEnumerable) ded_selectItemsPassingTest:] : 384 -> 380
~ -[NSSet(DEDEnumerable) ded_rejectItemsPassingTest:] : 384 -> 380
~ -[NSSet(DEDEnumerable) ded_findWithBlock:] : 312 -> 308
~ -[DEDController start] : 1768 -> 1764
~ ___22-[DEDController start]_block_invoke : 560 -> 552
~ -[DEDController reset] : 360 -> 356
~ ___56-[DEDController xpcInbound_discoverAllAvailableDevices:]_block_invoke : 1924 -> 1920
~ ___56-[DEDController xpcInbound_discoverAllAvailableDevices:]_block_invoke_3 : 276 -> 272
~ ___56-[DEDController xpcInbound_discoverAllAvailableDevices:]_block_invoke.44 : 276 -> 272
~ -[DEDController xpcInbound_didDiscoverDevices:] : 420 -> 416
~ ___54-[DEDController idsInbound_devicesChanged:completion:]_block_invoke : 1264 -> 1256
~ ___54-[DEDController upgradeToClassCDataProtectionIfNeeded]_block_invoke : 788 -> 784
~ ___47-[DEDController purgeStaleSessions:completion:]_block_invoke.112 : 1896 -> 1888
~ -[DEDController logDeviceCounts] : 536 -> 532
~ ___35-[DEDDaemon adoptFiles:forSession:]_block_invoke : 952 -> 948
~ ___27-[DEDDaemon commitSession:]_block_invoke.143 : 1168 -> 1164
~ -[DEDDaemon runAllDeferredExtensionsNowForSession:] : 344 -> 340
~ ___59-[DEDDaemon _syncSessionStatusWithSession:withIdentifiers:]_block_invoke : 1524 -> 1520
~ ___62-[DEDDaemon loadTextDataForExtensions:localization:sessionID:]_block_invoke : 364 -> 360
~ -[DEDCloudKitBaseModel initModelWithDictionary:] : 560 -> 556
~ ___32-[DEDDevice isMoreCompleteThan:]_block_invoke : 404 -> 400
~ -[DEDDiagnosticCollector extensionForIdentifier:] : 380 -> 376
~ -[DEDDiagnosticCollector availableDiagnosticExtensions] : 440 -> 436
~ -[DEDTestingFinisher finishSession:withConfiguration:] : 1860 -> 1848
~ -[DEDTestingFinisher archiveDirectories:progressHandler:] : 1152 -> 1144
~ -[DEDExtensionIdentifierManager JSONRepresentation] : 852 -> 848
~ -[DEDExtensionIdentifierManager initWithJSONString:] : 1120 -> 1116
~ -[DEDExtensionIdentifierManager initWithExtensionIdentifiers:] : 528 -> 524
~ -[DEDExtensionIdentifierManager allIdentifiers] : 392 -> 388
~ ___39-[DEDCloudKitFinisher startCompressing]_block_invoke_2 : 672 -> 668
~ -[DEDCloudKitFinisher uploadAttachments:inAttachmentGroup:completionHandler:] : 1060 -> 1056
~ -[DEDCloudKitFinisher processAttachmentsWithRecord:withProgress:] : 860 -> 856
~ -[DEDCloudKitFinisher getAttachmentURLsWithProgressHandler:] : 1676 -> 1672
~ ___46-[DEDCloudKitFinisher encryptLogsIfNecessary:]_block_invoke : 632 -> 628
~ -[DEDCloudKitFinisher additionalStateInfo] : 692 -> 676
~ ___75+[DEDFBKFeedbackUpload didFinishUploadOnBugSessionIdentifier:withDefaults:]_block_invoke : 508 -> 504
~ +[DEDFBKFeedbackUpload compactMapOnFeedbackUploadsWithUserDefaults:block:] : 1568 -> 1564
~ -[DEDIDSConnection sendMessage:withData:forDevices:isResponse:] : 388 -> 384
~ -[DEDIDSConnection sendMessage:withData:forIDSDeviceIDs:isResponse:] : 752 -> 748
~ ___50-[DEDIDSConnection discoverDevicesWithCompletion:]_block_invoke : 900 -> 896
~ -[NSArray(DEDEnumerable) ded_selectItemsPassingTest:] : 384 -> 380
~ -[NSArray(DEDEnumerable) ded_rejectItemsPassingTest:] : 384 -> 380
~ -[DEDIDSInbound device_supports_diagnostic_extensions:service:account:fromID:context:] : 612 -> 608
~ -[DEDIDSOutbound deviceSupportsDiagnosticExtensions:session:] : 508 -> 504
~ +[DEDDeferredExtensionInfo checkIn] : 468 -> 464
~ -[DEDPersistence loadSavedSessionsFromPlist:] : 700 -> 696
~ -[DEDPersistence loadSavedBugSessions] : 660 -> 656
~ -[DEDSharingInbound handleObject:forSFSession:forBugSession:callingDevice:] : 2392 -> 2388
~ -[DEDSharingOutbound deviceSupportsDiagnosticExtensions:session:] : 412 -> 408
~ -[DEDCloudKitClient handlePartialFailure:records:task:perRecordProgressBlock:perRecordSaveBlock:completionBlock:] : 1472 -> 1464
~ -[DEDCloudKitClient isBackgroundTaskExpiredError:] : 408 -> 404
~ -[DEDSeedingFinisher(SecurityResearchDevice) encryptFiles:toDirectory:] : 508 -> 504
~ -[DEDSeedingFinisher(SecurityResearchDevice) createDEArchiverArchiveFromDirectory:withBaseName:sourceDir:] : 1340 -> 1336
~ -[DEDXPCConnector clientConnections] : 456 -> 452
~ -[DEDXPCInbound xpc_didDiscoverDevices:] : 272 -> 268
~ -[DEDXPCInbound xpc_deviceSupportsDiagnosticExtensions:session:] : 444 -> 440
~ -[DEDSeedingClient cleanup] : 392 -> 388
~ -[DEDSeedingClient _formEncodedBodyForDictionary:] : 660 -> 656
~ -[DEDSeedingClient _keyValuePairsForKey:value:] : 1188 -> 1180
~ -[DEDSeedingClient isLoggedIn] : 644 -> 640
~ -[DEDXPCOutbound deviceSupportsDiagnosticExtensions:session:] : 384 -> 380
~ -[DEDTimberLorryFinisher queueFileUploadWithConfiguration:sessionIdentifier:] : 1184 -> 1180
~ +[DEDCloudKitExtensionsUtil getCompletedExtensionFromAllExtensions:] : 316 -> 312
~ +[DEDCloudKitExtensionsUtil getVerifiedExtensionDirectoriesFromCompletedExtensions:forSession:] : 524 -> 520
~ +[DEDCloudKitExtensionsUtil getOutputDirectories:withProcessingMap:progressHandler:] : 1020 -> 1016
~ ___84+[DEDCloudKitExtensionsUtil getOutputDirectories:withProcessingMap:progressHandler:]_block_invoke : 1784 -> 1780
~ +[DEDCloudKitExtensionsUtil getAllFilesInSessionDirectoryForSessionID:] : 380 -> 376
~ +[DEDCloudKitExtensionsUtil copyFiles:toDirectory:] : 276 -> 272
~ ___85-[DEDSharingConnection _configureService:withLabel:needsSetup:actionType:completion:]_block_invoke_2.cold.2 : 136 -> 132
```
