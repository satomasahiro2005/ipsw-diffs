## PBBridgeSupport

> `/System/Library/PrivateFrameworks/PBBridgeSupport.framework/PBBridgeSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43650` | `0x435d4` | **`-0x7c`** |
| `__TEXT.__cstring` | `0x5e10` | `0x5e49` | **`+0x39`** |
| `__TEXT.__const` | `0x9d8` | `0x9e0` | **`+0x8`** |

### Other Changes

```diff

-1350.1.0.0.0
+1355.0.0.1.0

-  Symbols:   3262
-  CStrings:  1131
+  Symbols:   3263
+  CStrings:  1132
Symbols:
+ -[PBBridgeIDSServiceDelegate _sendProtoBuf:service:priority:responseIdentifier:expectsResponse:willRetryOnFailure:]
+ _PBBridgeMaxIDSMessageRetryCount
+ ___115-[PBBridgeIDSServiceDelegate _sendProtoBuf:service:priority:responseIdentifier:expectsResponse:willRetryOnFailure:]_block_invoke
+ ___block_descriptor_57_e8_32s40s48s_e17_v16?0"NSError"8ls32l8s40l8s48l8
+ ___block_descriptor_73_e8_32s40s48s56s_e18_"NSString"12?0B8ls32l8s40l8s48l8s56l8
- -[PBBridgeIDSServiceDelegate _sendProtoBuf:service:priority:responseIdentifier:expectsResponse:]
- ___96-[PBBridgeIDSServiceDelegate _sendProtoBuf:service:priority:responseIdentifier:expectsResponse:]_block_invoke
- ___block_descriptor_56_e8_32s40s48s_e17_v16?0"NSError"8ls32l8s40l8s48l8
- ___block_descriptor_73_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
Functions:
~ -[PBBridgeIDSReachability _processDevices:] : 452 -> 448
~ +[PBBridgeIDSReachability nrDevices] : 384 -> 380
~ +[PBBridgeIDSReachability deviceStatusFromIDSDevices:nrDevices:] : 472 -> 468
~ -[PBBridgeCursiveTextPath pathForFraction:calculateLength:startFraction:] : 2504 -> 2496
~ _PBHexStringFromOOBData : 288 -> 284
~ _PBOOBDataFromHexString : 352 -> 348
~ _PBCurrentWindowScene : 604 -> 596
~ -[PBBProtoSendLanguageAndLocale writeTo:] : 348 -> 344
~ -[PBBProtoSendLanguageAndLocale copyWithZone:] : 404 -> 400
~ -[PBBProtoSendLanguageAndLocale mergeFrom:] : 336 -> 332
~ -[PBBridgeAssetsManager _runQueries:withCompletion:] : 556 -> 552
~ ___52-[PBBridgeAssetsManager _runQueries:withCompletion:]_block_invoke_2 : 404 -> 400
~ -[PBBridgeAssetsManager _beginAssetDownloads:] : 536 -> 532
~ ___46-[PBBridgeAssetsManager _beginAssetDownloads:]_block_invoke.378 -> ___46-[PBBridgeAssetsManager _beginAssetDownloads:]_block_invoke.384 : 360 -> 356
~ -[PBBridgeAssetsManager _linkDownloadedAsset:] : 764 -> 768
~ ___49-[PBBridgeAssetsManager purgeAllAssetsLocalOnly:]_block_invoke : 560 -> 556
~ -[PBBProtoSendWirelessCredentialsToWatch writeTo:] : 276 -> 272
~ -[PBBProtoSendWirelessCredentialsToWatch copyWithZone:] : 316 -> 312
~ -[PBBProtoSendWirelessCredentialsToWatch mergeFrom:] : 260 -> 256
~ _PBBridgeMagicCodeString : 916 -> 912
~ -[PBBProtoWarrantySentinel writeTo:] : 432 -> 428
~ -[PBBProtoWarrantySentinel copyWithZone:] : 504 -> 500
~ -[PBBProtoWarrantySentinel mergeFrom:] : 436 -> 432
~ -[PBBridgeResponsePerformanceMonitor _logLocalMeasurements:] : 1332 -> 1336
~ -[PBBridgeResponsePerformanceMonitor _logMacroActivitiesLocal:] : 456 -> 448
~ -[PBBridgeResponsePerformanceMonitor _logMilestones] : 400 -> 396
~ -[PBBProtoTinkerWirelessCredentials writeTo:] : 276 -> 272
~ -[PBBProtoTinkerWirelessCredentials copyWithZone:] : 316 -> 312
~ -[PBBProtoTinkerWirelessCredentials mergeFrom:] : 260 -> 256
~ -[PBBProtoOfflineTerms writeTo:] : 436 -> 432
~ -[PBBProtoOfflineTerms copyWithZone:] : 516 -> 512
~ -[PBBProtoOfflineTerms mergeFrom:] : 420 -> 416
~ -[PBBridgeIDSReachabilityObserverWrapper fireReachability:deviceStatus:devices:] : 396 -> 392
~ -[PBBridgeIDSReachability removeObserver:] : 436 -> 432
~ -[PBBridgeGizmoController _sendResponseToMessage:withResponseMessageID:withArguments:] : 4352 -> 4360
~ -[PBBridgeGizmoController setPasscodeRestrictions:] : 1204 -> 1196
~ -[PBBridgeIDSServiceDelegate _sendProtoBuf:service:priority:responseIdentifier:expectsResponse:] -> -[PBBridgeIDSServiceDelegate _sendProtoBuf:service:priority:responseIdentifier:expectsResponse:willRetryOnFailure:] : 324 -> 332
~ ___96-[PBBridgeIDSServiceDelegate _sendProtoBuf:service:priority:responseIdentifier:expectsResponse:]_block_invoke -> ___115-[PBBridgeIDSServiceDelegate _sendProtoBuf:service:priority:responseIdentifier:expectsResponse:willRetryOnFailure:]_block_invoke : 160 -> 168
~ -[PBBridgeIDSServiceDelegate sendProtoBuf:service:priority:responseIdentifier:expectsResponse:retryCount:retryInterval:] : 500 -> 512
~ ___120-[PBBridgeIDSServiceDelegate sendProtoBuf:service:priority:responseIdentifier:expectsResponse:retryCount:retryInterval:]_block_invoke : 52 -> 28
~ -[PBBridgeIDSServiceDelegate connectionStateWithDevices:accounts:] : 700 -> 692
~ -[PBBridgeIDSServiceDelegate checkReachability] : 304 -> 300
~ -[PBBridgeIDSServiceDelegate service:account:identifier:didSendWithSuccess:error:] : 1376 -> 1400
~ ___82-[PBBridgeIDSServiceDelegate service:account:identifier:didSendWithSuccess:error:]_block_invoke : 344 -> 396
~ -[PBBProtoTransferPerformanceResults dictionaryRepresentation] : 916 -> 904
~ -[PBBProtoTransferPerformanceResults writeTo:] : 612 -> 600
~ -[PBBProtoTransferPerformanceResults copyWithZone:] : 684 -> 672
~ -[PBBProtoTransferPerformanceResults mergeFrom:] : 600 -> 588
~ -[PBBridgeCompanionController _sendRemoteCommandWithMessageID:withArguments:] : 4744 -> 4740
~ -[PBBridgeCompanionController _sendResponseToMessage:withResponseMessageID:withArguments:] : 416 -> 424
~ -[PBBridgeCompanionController handlePerformanceResults:] : 920 -> 912
~ -[PBBridgeCompanionController sendGizmoPasscodeRestrictions] : 704 -> 696
CStrings:
+ "-[PBBridgeIDSServiceDelegate _sendProtoBuf:service:priority:responseIdentifier:expectsResponse:willRetryOnFailure:]"
+ "-[PBBridgeIDSServiceDelegate _sendProtoBuf:service:priority:responseIdentifier:expectsResponse:willRetryOnFailure:]_block_invoke"
+ "@\"NSString\"12@?0B8"
- "-[PBBridgeIDSServiceDelegate _sendProtoBuf:service:priority:responseIdentifier:expectsResponse:]"
- "-[PBBridgeIDSServiceDelegate _sendProtoBuf:service:priority:responseIdentifier:expectsResponse:]_block_invoke"
```
