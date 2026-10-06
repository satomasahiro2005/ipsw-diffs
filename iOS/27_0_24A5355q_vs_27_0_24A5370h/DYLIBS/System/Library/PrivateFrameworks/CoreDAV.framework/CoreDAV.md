## CoreDAV

> `/System/Library/PrivateFrameworks/CoreDAV.framework/CoreDAV`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x520cc` | `0x51eb0` | **`-0x21c`** |

### Other Changes

```diff

-1247.0.0.0.0
+1248.0.0.0.0
Functions:
~ -[CardDAVGetAccountPropertiesTaskGroup _setPropertiesFromParsedResponses:] : 492 -> 488
~ -[CoreDAVContainer privilegesAsStringSet] : 560 -> 556
~ -[CoreDAVContainer _anyPrivilegesMatches:] : 444 -> 440
~ -[CoreDAVContainer supportedReportsAsStringSet] : 580 -> 576
~ +[CoreDAVContainer convertPushTransportsForNSServerNotificationCenter:] : 1500 -> 1492
~ -[CoreDAVContainerInfoTaskGroup _getContainerTopLevelInfo] : 504 -> 500
~ -[CoreDAVContainerInfoTaskGroup propFindTask:parsedResponses:error:] : 2776 -> 2760
~ -[CoreDAVContainerMultiGetTask requestBody] : 1060 -> 1052
~ -[CoreDAVContainerMultiGetTask finishCoreDAVTaskWithError:] : 1804 -> 1820
~ -[CoreDAVContainerQueryTask finishCoreDAVTaskWithError:] : 1648 -> 1632
~ -[CardDAVFolderQueryTask addFiltersToXMLData:] : 956 -> 952
~ -[CoreDAVContainerSyncTaskGroup _tearDownAllUnsubmittedTasks] : 320 -> 316
~ -[CoreDAVContainerSyncTaskGroup _submitTasks] : 1176 -> 1164
~ -[CoreDAVContainerSyncTaskGroup _pushActions] : 1416 -> 1412
~ -[CoreDAVContainerSyncTaskGroup _bulkChange] : 1120 -> 1116
~ -[CoreDAVContainerSyncTaskGroup _getETags] : 572 -> 568
~ -[CoreDAVContainerSyncTaskGroup _getDataPayloads] : 2040 -> 2028
~ -[CoreDAVContainerSyncTaskGroup _syncReportTask:didFinishWithError:] : 2160 -> 2156
~ -[CoreDAVContainerSyncTaskGroup propFindTask:parsedResponses:error:] : 2800 -> 2788
~ -[CoreDAVContainerSyncTaskGroup getTask:data:error:] : 1052 -> 1048
~ -[CoreDAVDiscoveryTaskGroup cancelTaskGroup] : 288 -> 284
~ -[CoreDAVDiscoveryTaskGroup startTaskGroup] : 3660 -> 3644
~ -[CoreDAVDiscoveryTaskGroup setupDiscoveries:withSchemes:] : 1144 -> 1132
~ ___64-[CoreDAVDiscoveryTaskGroup startWellKnownLocationTask:withURL:]_block_invoke : 856 -> 852
~ ___68-[CoreDAVDiscoveryTaskGroup startWellKnownFallbackHeadTask:withURL:]_block_invoke : 1144 -> 1140
~ -[CoreDAVDiscoveryTaskGroup srvLookupTask:error:] : 2348 -> 2336
~ -[CoreDAVDiscoveryTaskGroup completeDiscovery:error:] : 3860 -> 3852
~ ___53-[CoreDAVDiscoveryTaskGroup completeDiscovery:error:]_block_invoke.315 : 560 -> 556
~ -[CoreDAVDiscoveryTaskGroup noteDefinitiveAuthFailureFromTask:] : 508 -> 504
~ -[CoreDAVDiscoveryTaskGroup cleanedStringsFromResponseHeaders:forHeader:] : 476 -> 472
~ -[CoreDAVDiscoveryTaskGroup getDiscoveryStatus:priorFailed:subsequentFailed:priorIncomplete:subsequentIncomplete:priorSuccess:subsequentSuccess:] : 560 -> 556
~ -[CoreDAVGetAccountPropertiesTaskGroup _setPropertiesFromParsedResponses:] : 1124 -> 1120
~ ___59-[CoreDAVLogging removeLogDelegate:forAccountInfoProvider:]_block_invoke : 408 -> 404
~ -[CoreDAVLogging shouldLogAtLevel:forAccountInfoProvider:] : 324 -> 320
~ -[CoreDAVLogging _shouldOutputAtLevel:forAccountInfoProvider:] : 324 -> 320
~ -[CoreDAVLogging logDiagnosticForProvider:withLevel:format:args:] : 584 -> 580
~ -[CoreDAVPropFindTask requestBody] : 656 -> 652
~ -[CoreDAVResponseItem successfulPropertiesToValues] : 636 -> 632
~ -[CoreDAVResponseItem hasPropertyError] : 424 -> 420
~ -[CoreDAVTask _assignConnectionProperties:toSessionConfiguration:] : 592 -> 588
~ -[CoreDAVTask performCoreDAVTask] : 6972 -> 6968
~ -[CoreDAVTaskGroup _tearDownAllTasks] : 316 -> 312
~ -[NSDictionary(CoreDAVExtensions) CDVMergeOverrideDictionary:] : 468 -> 464
~ -[NSString(CoreDAVExtensions) CDVStringByXMLQuoting] : 700 -> 696
~ -[NSString(CoreDAVExtensions) CDVStringByXMLUnquoting] : 2112 -> 2068
~ _CDVCleanedStringsFromResponseHeaders : 476 -> 472
~ -[CoreDAVRequestLogger logCoreDAVRequest:withTaskIdentifier:] : 2184 -> 2180
~ +[CoreDAVRequestLogger _redactedHeadersFromHeaders:] : 416 -> 412
~ -[CoreDAVRequestLogger logCoreDAVResponseHeaders:andStatusCode:withTaskIdentifier:] : 1144 -> 1140
~ -[CoreDAVRequestLogger logCoreDAVResponseSnippet:withTaskIdentifier:isBody:] : 520 -> 516
~ -[CoreDAVRequestLogger finishCoreDAVResponse] : 384 -> 380
~ -[CoreDAVMkcolTask requestBody] : 592 -> 588
~ -[CoreDAVPropPatchTask requestBody] : 848 -> 840
~ -[CoreDAVACLItem notGrantedSubsetOfACEs:] : 1188 -> 1180
~ ___41-[CoreDAVACLItem notGrantedSubsetOfACEs:]_block_invoke : 420 -> 416
~ -[CoreDAVGrantItem write:] : 388 -> 384
~ -[CoreDAVDenyItem write:] : 388 -> 384
~ -[CoreDAVACLTask requestBody] : 372 -> 368
~ -[CoreDAVUpdateACLTaskGroup task:didFinishWithError:] : 676 -> 672
~ -[CoreDAVItem write:] : 508 -> 504
~ -[CoreDAVCurrentUserPrivilegeSetItem hasPrivilegeWithNameSpace:andName:] : 616 -> 612
~ -[CoreDAVMkcolResponseItem hasPropertyError] : 304 -> 300
~ -[CoreDAVSupportedReportSetItem supportsReportWithNameSpace:andName:] : 560 -> 556
~ -[CoreDAVResourceTypeItem write:] : 556 -> 552
~ -[CoreDAVResourceTypeItem stringSet] : 1128 -> 1124
~ -[CoreDAVResourceTypeItem isTypeWithNameSpace:andName:] : 708 -> 704
~ -[CoreDAVContainerInfoSyncTaskGroup task:didFinishWithError:] : 1380 -> 1376
~ -[CoreDAVItemWithHrefChildren hrefsAsFullURLs] : 520 -> 516
~ -[CoreDAVItemWithHrefChildren hrefsAsOriginalURLs] : 508 -> 504
~ -[CoreDAVItemWithHrefChildren hrefsAsStrings] : 508 -> 504
~ -[CoreDAVSyncReportTask requestBody] : 668 -> 664
~ -[CoreDAVSyncReportTask notFoundHREFs] : 608 -> 604
~ -[CoreDAVSyncReportTask finishCoreDAVTaskWithError:] : 664 -> 660
~ -[CoreDAVRecursiveContainerSyncTaskGroup _tearDownAllUnsubmittedTasks] : 344 -> 340
~ -[CoreDAVRecursiveContainerSyncTaskGroup _submitTasks] : 644 -> 628
~ -[CoreDAVRecursiveContainerSyncTaskGroup _pushActions] : 1776 -> 1788
~ -[CoreDAVRecursiveContainerSyncTaskGroup _getDataPayloads] : 3072 -> 3052
~ -[CoreDAVRecursiveContainerSyncTaskGroup _syncReportTask:didFinishWithError:] : 1688 -> 1672
~ -[CoreDAVRecursiveContainerSyncTaskGroup propFindTask:parsedResponses:error:] : 1452 -> 1448
~ -[CoreDAVRecursiveContainerSyncTaskGroup _getTask:finishedWithParsedContents:deletedItems:error:] : 1480 -> 1476
~ -[CoreDAVPrincipalPropertySearchTask requestBody] : 688 -> 680
~ -[CoreDAVPropertyFindBaseTask successfulValueForNameSpace:elementName:] : 364 -> 360
~ -[CoreDAVPropertyFindBaseTask getTotalFailureError] : 636 -> 628
~ -[CoreDAVExpandPropertiesTask requestBody] : 768 -> 764
~ -[CoreDAVExpandPropertiesTask parseHints] : 860 -> 852
~ -[CoreDAVBulkUploadTaskGroup _sendNextBatch] : 1652 -> 1620
~ -[CoreDAVMultiPutTask fillOutDataWithUUIDsToAddActions:hrefsToModDeleteActions:] : 1428 -> 1412
~ -[CoreDAVMultiPutTask finishCoreDAVTaskWithError:] : 1664 -> 1656
~ -[CoreDAVBulkRequestsItem supportsItemWithNameSpace:name:] : 908 -> 904
~ -[CoreDAVBulkChangeTask fillOutDataWithUUIDsToAddActions:hrefsToModDeleteActions:] : 1776 -> 1804
~ -[CoreDAVBulkChangeTask finishCoreDAVTaskWithError:] : 1500 -> 1496
~ -[CoreDAVXMLElementGenerator notifyElement:ofAttributesFound:] : 420 -> 416
~ -[CoreDAVXMLElementGenerator parser:didStartElement:namespaceURI:qualifiedName:attributes:] : 1488 -> 1484
~ -[CoreDAVMultiMoveWithFallbackTaskGroup initWithSourceURLs:destinationURL:overwrite:useFallback:sourceEntityDataPayloads:sourceEntityDataContentTypes:sourceEntityETags:accountInfoProvider:taskManager:] : 1092 -> 1088
```
