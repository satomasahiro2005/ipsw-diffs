## ESDaemonSupport

> `/System/Library/PrivateFrameworks/ExchangeSync.framework/Frameworks/ESDaemonSupport.framework/ESDaemonSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20e50` | `0x20d28` | **`-0x128`** |

### Other Changes

```diff

-2075.0.0.0.0
+2076.0.0.0.0
Functions:
~ -[ESDClientCalendarDirectorySearchResponseDelegate _convertSearchQueryResults:] : 728 -> 716
~ ___42-[ESDAccessManager _setupServerConnection]_block_invoke : 1872 -> 1868
~ -[ESDAccessManager addPersistentClientWithAccountID:clientID:watchedIDs:] : 688 -> 684
~ -[ESDAccessManager isAccountID:folderID:watchedByClientBesides:] : 468 -> 464
~ -[DADClientAccountTimers clientBehaviorForFolderIds:] : 420 -> 416
~ ___26-[ESDMain _shutdownDaemon]_block_invoke.5 : 432 -> 428
~ -[ESDMain addSignalHandler] : 304 -> 300
~ ___32-[ESDMain _configureAggdLogging]_block_invoke : 712 -> 708
~ ___logState_block_invoke : 260 -> 256
~ -[ESDClient _removeBusyFolderIDs:forAccountWithID:] : 372 -> 368
~ -[ESDClient _removeWatchedFolderIDs:forAccountWithID:] : 372 -> 368
~ -[ESDClient disable] : 752 -> 744
~ ___20-[ESDClient disable]_block_invoke : 1320 -> 1316
~ -[ESDClient watchedFolderCount] : 360 -> 356
~ -[ESDClient persistentClientCleanup] : 780 -> 772
~ -[ESDClient isMonitoringAccountID:folderID:] : 352 -> 348
~ ___36-[ESDClient _stopMonitoringFolders:]_block_invoke_2 : 540 -> 536
~ -[ESDClient _clearAllStopMonitoringAgentsTokens] : 308 -> 304
~ -[ESDClient _requestFolderContentsUpdateForFolders:accountId:dataclasses:isUserRequested:] : 1272 -> 1268
~ -[ESDAgentManager agentWithAccountID:] : 372 -> 368
~ -[ESDAgentManager accountWithAccountID:] : 388 -> 384
~ -[ESDAgentManager accountWithAccountID:andClassName:] : 432 -> 428
~ -[ESDAgentManager loadExchangeAgents] : 3460 -> 3444
~ -[ESDAgentManager saveAndReleaseAgents] : 684 -> 680
~ -[ESDAgentManager _deviceWillSleep] : 452 -> 448
~ -[ESDAgentManager _deviceDidWake] : 256 -> 252
~ -[ESDAgentManager currentPolicyKeyForAccount:] : 404 -> 400
~ -[ESDAgentManager requestPolicyUpdateForAccount:] : 600 -> 596
~ -[ESDAgentManager startMonitoringAccountID:folderIDs:] : 636 -> 632
~ -[ESDAgentManager stopMonitoringAccountID:folderIDs:] : 520 -> 516
~ -[ESDAgentManager suspendMonitoringAccountID:folderIDs:] : 520 -> 516
~ -[ESDAgentManager resumeMonitoringAccountID:folderIDs:] : 520 -> 516
~ -[ESDAgentManager addPersistMonitoringAccountID:folderIDs:clientID:] : 696 -> 692
~ -[ESDAgentManager removePersistMonitoringAccountID:folderIDs:clientID:] : 580 -> 576
~ -[ESDAgentManager clearPersistMonitoringAccountID:clientID:] : 508 -> 504
~ -[ESDAgentManager _clearOrphanedStores] : 2364 -> 2344
~ -[ESDAgentManager _clearOrphanedStoresInCalendarDatabase:eventAccountIds:toDoAccountIds:] : 1188 -> 1184
~ -[ESDAgentManager _calDaysToSyncDidChange] : 580 -> 576
~ -[ESDAgentManager _handleCellularDataUsageChangedNotification] : 692 -> 680
~ ___56-[ESDAgentManager _loadAndStartExchangeMonitoringAgents]_block_invoke : 972 -> 968
~ -[ESDAgentManager _stopMonitoringAndSaveAgents] : 1368 -> 1364
~ -[ESDAgentManager _addAccountAggdEntries] : 1100 -> 1096
~ -[ESDAgentManager updateFolderListForAccountID:andDataclasses:requireChangedFolders:isUserRequested:] : 396 -> 392
~ -[ESDAgentManager updateContentsOfFolders:forAccountID:andDataclasses:isUserRequested:] : 612 -> 600
~ -[ESDAgentManager updateContentsOfAllFoldersForAccountID:andDataclasses:isUserRequested:] : 600 -> 596
~ -[ESDAgentManager activeAccountBundleIDs] : 372 -> 368
~ -[ESDAgentManager hasEASAccountConfigured] : 536 -> 532
~ -[ESDAgentManager processMeetingRequestDatas:deliveryIdsToClear:deliveryIdsToSoftClear:inFolderWithId:forAccountWithId:callback:] : 568 -> 564
~ -[ESDAgentManager resetCertWarningsForAccountWithId:andDataclasses:] : 416 -> 412
~ -[ESDAgentManager setFolderIdsThatExternalClientsCareAboutAdded:deleted:foldersTag:forAccountID:] : 532 -> 528
~ -[ESDAgentManager reportFolderItemsSyncSuccess:forFolderWithID:withItemsCount:andAccountWithID:] : 424 -> 420
~ -[ESDAgentManager stateString] : 620 -> 616
~ -[ESDAgentManager processFolderChange:forAccountWithID:completionBlock:] : 404 -> 400
~ -[ESDAgentManager getStatusReportDictsWithCompletionBlock:] : 816 -> 808
~ -[ESDAgentManager hasActiveAccounts] : 544 -> 540
~ -[ESDStatusReportAggregator initWithStatusReports:numOutstandingReports:timeout:completionBlock:] : 556 -> 552
~ -[ESDStatusReportAggregator _coalesceAndReport] : 524 -> 520
~ -[ESDStatusReportAggregator noteAdditionalReportDicts:] : 388 -> 384
```
