## WelcomeKitCore

> `/System/Library/PrivateFrameworks/WelcomeKitCore.framework/WelcomeKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3682c` | `0x36704` | **`-0x128`** |

### Other Changes

```diff

-1410.0.0.0.0
+1413.0.0.0.0
Functions:
~ +[WLAuthenticationUtilities dataFromPEMFormattedData:] : 440 -> 436
~ -[WLAppMigrator importDataFromProvider:forSummaries:summaryStart:summaryCompletion:] : 1216 -> 1212
~ -[WLAppMigrator _insertMatchingApps:] : 652 -> 648
~ +[WLAppMigrator _sendStoreDownloadRequestForFreeMigratableApps:completion:] : 1276 -> 1260
~ ___29-[WLAppSearchRequest search:]_block_invoke : 912 -> 908
~ +[WLBookmarksMigrator _bookmarkFolderAtTitlePath:withinBookmarkFolder:] : 624 -> 620
~ -[WLBookmarksMigrator importDataFromProvider:forSummaries:summaryStart:summaryCompletion:] : 1864 -> 1836
~ -[WLContactsMigrator importRecordData:summary:account:completion:] : 1012 -> 1008
~ -[WLMailAccountMigrator init] : 696 -> 692
~ -[WLMailAccountMigrator importRecordData:summary:account:completion:] : 1252 -> 1248
~ -[WLMessage parseMIMEData:sqlController:] : 2084 -> 2064
~ +[WLMessage _fileNameForPart:smilContext:] : 600 -> 596
~ -[WLMessagesMigrator performPreImportPhaseForSummary:data:] : 964 -> 960
~ -[WLMessagesMigrator _insertMessage:] : 2392 -> 2384
~ -[WLMessagesMigrator _uniqueHandleStringsWithMessage:] : 692 -> 688
~ -[WLMessagesMigrator _chatIDForHandleIDs:groupRoomName:groupID:message:] : 2056 -> 2032
~ -[WLMessagesMigrator _messageAttributedBodyDataWithMessage:] : 588 -> 584
~ -[WLFilesMigrator importRecordData:summary:account:completion:] : 1720 -> 1716
~ +[WLSourceDeviceAccount accountInfoArrayContainsNonSyncableAccount:] : 324 -> 320
~ ___159-[WLMigrationDataCoordinator fetchAccountsAndSummariesFromSource:forMigrator:statistics:accountsRequestDurationBlock:summariesRequestDurationBlock:completion:]_block_invoke : 800 -> 796
~ ___89-[WLMigrationDataCoordinator _fetchAccountsFromSource:forMigrator:statistics:completion:]_block_invoke : 536 -> 532
~ ___98-[WLMigrationDataCoordinator _fetchSummariesFromSource:forMigrator:account:statistics:completion:]_block_invoke : 616 -> 612
~ -[WLMigrationDataCoordinator importDataForMigrator:fromProvider:forSummaries:summaryStart:summaryCompletion:] : 1012 -> 1004
~ -[WLMigrator startMigration:usingRetryPolicies:completion:] : 1920 -> 1916
~ -[WLMigrator finishMigration:] : 972 -> 968
~ -[WLMigrator _fetchAccountsAndSummariesWithContext:] : 1184 -> 1180
~ ___52-[WLMigrator _fetchAccountsAndSummariesWithContext:]_block_invoke_3 : 628 -> 620
~ -[WLMigrator _selectDataTypesWithContext:] : 2152 -> 2140
~ +[WLMigrator _dataTypesAndSizesXMLDataFromMap:] : 640 -> 636
~ -[WLMigrator _downloadDataWithContext:failureDetailsBlock:] : 3916 -> 3908
~ -[WLMigrator _importDataWithContext:failureDetailsBlock:] : 1876 -> 1872
~ -[WLMigrator _logStatisticsAndSendStatisticsTelemetryWithContext:] : 1420 -> 1404
~ -[WLTimeEstimateAccuracyTracker estimatesDidResolveAtDate:block:] : 416 -> 412
~ +[NSData(Hex) wl_lengthPrefixedBlobSequenceFromDataArray:] : 360 -> 356
~ ___34-[NSData(Hex) wl_hexEncodedString]_block_invoke : 80 -> 84
~ -[WLServerConnection close] : 352 -> 348
~ -[WLServerConnection _isTerminated:length:] : 104 -> 116
~ ___104-[WLSQLController _totalSummarySegmentCountForAccounts:migrationStateComparisonOperator:migrationState:]_block_invoke : 756 -> 752
~ ___74-[WLSQLController totalSummaryItemSizeForAccounts:addOverhead:completion:]_block_invoke : 808 -> 804
~ -[WLSQLController summariesForAccounts:sortedByModifiedDate:] : 664 -> 660
~ ___61-[WLSQLController summariesForAccounts:sortedByModifiedDate:]_block_invoke : 1580 -> 1576
~ -[NSString(WLSQLController) wl_sqlIDComponentsSeparatedByString:] : 364 -> 360
~ -[WLWiFiDeviceClient hostedNetworkMatchingSSID:] : 348 -> 344
~ -[WLWiFiManager _preferredChannel:network:channels:completion:] : 1968 -> 1940
~ +[NSError(WelcomeKit) _wl_encodableArrayFromArray:] : 352 -> 348
~ +[NSError(WelcomeKit) _wl_encodableSetFromSet:] : 352 -> 348
~ +[NSError(WelcomeKit) _wl_objectIsKindOfNonCollectionPlistClass:] : 300 -> 296
```
