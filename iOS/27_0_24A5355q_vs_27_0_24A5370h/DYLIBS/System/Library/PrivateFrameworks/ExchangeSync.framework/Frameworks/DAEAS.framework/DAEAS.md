## DAEAS

> `/System/Library/PrivateFrameworks/ExchangeSync.framework/Frameworks/DAEAS.framework/DAEAS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x94330` | `0x94154` | **`-0x1dc`** |

### Other Changes

```diff

-2075.0.0.0.0
+2076.0.0.0.0
Functions:
~ ___119-[ASConcreteAccountActor performMailboxRequests:mailbox:previousTag:clientWinsOnSyncConflict:isUserRequested:consumer:]_block_invoke : 500 -> 496
~ -[DAConvertCRtoCRLFStream read:maxLength:] : 1308 -> 1312
~ -[ASWAPXMLPolicy _wbxmlPolicyDict] : 1344 -> 1340
~ -[ASMeetingResponseTask requestBody] : 1080 -> 1076
~ -[ASMeetingResponseTask finishWithError:] : 2500 -> 2492
~ -[ASEventUID uidFromGlobalObjId:outIsOutlookCreatedUid:] : 1012 -> 1020
~ +[ASTimeZone _fillOutCurrentTimeZoneInfo] : 4740 -> 4728
~ -[ASTimeZone _bestGuessAtOlsonTimeZoneForOffsetInMinutes:daylightBiasInMinutes:standardTransitionDate:daylightTransitionDate:] : 1744 -> 1732
~ -[ASToDo appendActiveSyncDataForTask:toWBXMLData:] : 1208 -> 1204
~ -[ASMailboxSearchTask finishWithError:] : 1272 -> 1268
~ -[ASSettingsTask requestBody] : 2204 -> 2184
~ -[ASSettingsTaskUserInformationGetResponse parseASParseContext:root:parent:callbackDict:streamCallbackDict:account:] : 828 -> 824
~ -[ASSettingsTaskOofGetResponse convertToDAOofParams] : 992 -> 988
~ -[ASItemOperationsTask requestBody] : 848 -> 844
~ -[ASAccount setEnabled:forDADataclass:] : 500 -> 496
~ -[ASAccount _visibleASFolders] : 852 -> 848
~ -[ASAccount sniffableTypeForFolder:] : 540 -> 536
~ -[ASAccount defaultContactsFolder] : 532 -> 528
~ -[ASAccount contactsFolders] : 364 -> 360
~ -[ASAccount defaultEventsFolder] : 532 -> 528
~ -[ASAccount eventsFolders] : 364 -> 360
~ -[ASAccount defaultToDosFolder] : 532 -> 528
~ -[ASAccount toDosFolders] : 364 -> 360
~ -[ASAccount defaultNotesFolder] : 532 -> 528
~ -[ASAccount notesFolders] : 364 -> 360
~ -[ASAccount _defaultMailFolderWithDefaultType:fallbackType:fallbackName:] : 492 -> 488
~ -[ASAccount itemOperationsTask:completedWithStatus:error:responses:] : 604 -> 600
~ -[ASAccount itemOperationsTask:hasPartialResponses:] : 568 -> 564
~ -[ASAccount applyNewAccountProperties:saveIfDifferent:] : 396 -> 392
~ -[ASAccount moveItemsTask:completedWithStatus:error:movedItems:] : 1244 -> 1236
~ -[ASAccount _reallyCancelSearchQuery:] : 472 -> 468
~ -[ASAccount _reallyCancelAllSearchQueries] : 296 -> 292
~ -[ASAccount performCalendarDirectorySearchForTerms:recordTypes:resultLimit:consumer:] : 696 -> 692
~ -[ASAccount _generateAutodiscoverURLsForEmailAddress:explicitUsername:withConsumer:] : 1340 -> 1336
~ -[ASAccount _silentlyTearDownAutodiscoveryTasks] : 500 -> 492
~ -[ASClientAccount resumeMonitoringFoldersWithIDs:] : 324 -> 320
~ -[ASClientAccount _removeFoldersFromDaemonMonitoring:] : 264 -> 260
~ -[ASClientAccount performMoveRequests:consumer:] : 796 -> 788
~ -[ASClientAccount performFetchMessageSearchResultRequests:consumer:] : 668 -> 664
~ -[ASClientAccount performMailboxRequests:mailbox:previousTag:clientWinsOnSyncConflict:consumer:] : 1396 -> 1384
~ -[ASClientAccount mailboxes] : 364 -> 360
~ -[ASMailboxEnhancedSearchTask finishWithError:] : 1240 -> 1236
~ -[ASDraftEmailAction appendApplicationDataForTask:toWBXMLData:] : 1340 -> 1332
~ -[ASAutodiscoverV2Task finishWithError:] : 912 -> 908
~ -[ASContact _savePhoneNumbersToAddressBookWithExistingRecord:shouldMergeProperties:] : 2740 -> 2732
~ -[ASContact _saveEmailsToAddressBookWithExistingRecord:shouldMergeProperties:] : 1116 -> 1112
~ -[ASContact _saveIMsToAddressBookWithExistingRecord:shouldMergeProperties:] : 1124 -> 1120
~ -[ASContact appendActiveSyncDataForTask:toWBXMLData:] : 3980 -> 3972
~ -[ASTrafficLogger logWBXMLData:] : 424 -> 420
~ -[ASEmailItem parseASParseContext:root:parent:callbackDict:streamCallbackDict:account:] : 1452 -> 1448
~ -[ASMailboxSearchPredicate _getStringForCompoundPredicate:] : 912 -> 908
~ -[ASMailboxSearchPredicate _isQueryTextLengthSufficientForCompoundPredicate:] : 580 -> 576
~ -[ASEvent saveToCalendarWithExistingRecord:intoCalendar:shouldMergeProperties:outMergeDidChooseLocalProperties:account:] : 9760 -> 9744
~ -[ASEvent updateAttachmentsForAccountID:] : 380 -> 376
~ -[ASEvent _sanitizeLocalExceptionsForAccount:] : 952 -> 948
~ -[ASEvent saveDetachedEventsWithExistingRecord:intoCalendar:shouldMergeProperties:outMergeDidChooseLocalProperties:account:] : 364 -> 360
~ -[ASEvent informExceptionsThatParentIsReadyForAccount:] : 272 -> 268
~ -[ASEvent deleteFromCalendar] : 284 -> 280
~ -[ASEvent appendActiveSyncDataForTask:toWBXMLData:] : 5288 -> 5264
~ -[ASEvent setCalEvent:] : 320 -> 316
~ -[ASEvent verifyExternalIdsForAccountID:] : 548 -> 544
~ -[ASEvent fillOutMissingExternalIdsForAccountID:] : 688 -> 684
~ -[ASEvent loadClientIDs] : 360 -> 356
~ -[ASEvent purgeAttendeesPendingDeletionForAccountID:] : 596 -> 592
~ -[ASEvent hasOccurrenceInTheFuture] : 732 -> 728
~ -[ASEvent eventByMergingInLosingEvent:account:] : 1756 -> 1748
~ -[ASEvent setExceptions:] : 300 -> 296
~ -[ASEventException verifyExternalIdsForAccountID:] : 676 -> 672
~ -[ASEventException takeValuesFromParentForAccount:] : 2084 -> 2080
~ -[ASEventException appendActiveSyncDataForTask:toWBXMLData:] : 2868 -> 2864
~ -[ASWBXMLToXMLConverter _consumeBytes] : 4100 -> 4120
~ -[ASFolderItemsSyncTask _setSpinning:] : 564 -> 560
~ -[ASFolderItemsSyncTask _bodyTruncationCode] : 132 -> 144
~ -[ASFolderItemsSyncTask _mimeTruncationCode] : 132 -> 144
~ -[ASFolderHierarchy _setFolderByIdCacheFromCurrentCache] : 644 -> 640
~ -[ASFolderHierarchy _setFolderPathsFromCurrentCache] : 476 -> 472
~ -[ASFolderHierarchy _pathForFolder:usingCache:foldersById:] : 840 -> 836
~ -[ASFolderHierarchy _identityMatchAndSetFoldersThatExternalClientsCareAbout:] : 740 -> 732
~ -[ASFolderHierarchy _pruneBadFolderIdsThatExternalClientsCareAbout] : 360 -> 356
~ -[ASFolderHierarchy folderIdsThatExternalClientsCareAboutForDataclasses:] : 408 -> 404
~ -[ASFolderHierarchy folderIdsForPersistentPushForDataclasses:clientID:] : 412 -> 408
~ -[ASFolderSyncTask _setSpinning:] : 568 -> 564
~ -[ASGALSearchTask finishWithError:] : 1192 -> 1188
~ -[ASItem _copyStreamingBlockForStreamingCallbackDict:dccpt:] : 460 -> 456
~ -[ASMeetingRequest saveForwardeesToCalendarWithExistingRecord:account:] : 864 -> 860
~ -[ASMeetingRequest takeValuesFromParentEmailForAccount:] : 1296 -> 1288
~ -[ASMoveItemsTask requestBody] : 516 -> 512
~ -[ASParseContext bufferWithAllData] : 288 -> 284
~ -[ASParseContext byteAtOffsetFromCurrentByte:] : 388 -> 384
~ -[ASPingTask requestBody] : 776 -> 772
~ _managedConfigurationPoliciesFromEASWBXMLPolicies : 2476 -> 2468
~ _perAccountEASPoliciesFromEASWBXMLPolicies : 600 -> 596
~ -[ASProvisionTask requestBody] : 1312 -> 1304
~ -[ASTask _assignConnectionProperties:toSessionConfiguration:] : 524 -> 520
~ -[ASTask _continuePerformTask] : 1928 -> 1924
~ -[ASTask URLSession:task:didFinishCollectingMetrics:] : 600 -> 596
~ -[ASTask _handleCompletionError:] : 1688 -> 1684
~ -[ASTaskManager _finishAllTasksWithError:] : 292 -> 288
~ -[ASTaskManager _hasTasksIndicatingARunningSync] : 284 -> 280
~ _uint16len : 52 -> 44
~ _uint16strncpy : 96 -> 100
~ _DAFolderArrayForASFolderArray : 340 -> 336
~ _ASFolderArrayForDAFolderArray : 340 -> 336
~ _ASFilterCodeForNumPastDays : 100 -> 96
~ _bestProtocolVersionFromVersions : 576 -> 572
~ +[ASUtilsLazyClass fillOutASDeviceID] : 772 -> 768
~ ___asDeviceIDWithHintedID_block_invoke.131 : 1096 -> 1100
~ -[ASResolveRecipientsTask requestBody] : 868 -> 864
~ -[ASResolveRecipientsTask finishWithError:] : 2196 -> 2192
~ -[ASResolveRecipientsCertificatesItem description] : 512 -> 508
~ -[ASNote appendActiveSyncDataForTask:toWBXMLData:] : 604 -> 600
```
