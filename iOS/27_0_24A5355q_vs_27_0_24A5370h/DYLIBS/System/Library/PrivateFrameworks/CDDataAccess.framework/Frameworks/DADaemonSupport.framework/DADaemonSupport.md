## DADaemonSupport

> `/System/Library/PrivateFrameworks/CDDataAccess.framework/Frameworks/DADaemonSupport.framework/DADaemonSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x150e4` | `0x14fc8` | **`-0x11c`** |

### Other Changes

```diff

-4034.15.0.0.0
+4037.1.0.0.0
Functions:
~ -[DADAgentManager _deviceDidWake] : 256 -> 252
~ -[DADAgentManager agentWithAccountID:] : 372 -> 368
~ -[DADAgentManager accountWithAccountID:] : 388 -> 384
~ -[DADAgentManager accountWithAccountID:andClassName:] : 432 -> 428
~ -[DADAgentManager loadAgents:] : 4236 -> 4216
~ -[DADAgentManager saveAndReleaseAgents] : 684 -> 680
~ -[DADAgentManager _deviceWillSleep] : 416 -> 412
~ -[DADAgentManager startMonitoringAccountID:syncKeyMap:] : 652 -> 648
~ -[DADAgentManager stopMonitoringAccountID:folderIDs:] : 524 -> 520
~ -[DADAgentManager suspendMonitoringAccountID:folderIDs:] : 524 -> 520
~ -[DADAgentManager resumeMonitoringAccountID:syncKeyMap:] : 524 -> 520
~ -[DADAgentManager _clearOrphanedStores] : 2156 -> 2136
~ -[DADAgentManager _handleCellularDataUsageChangedNotification] : 1360 -> 1348
~ ___49-[DADAgentManager _loadAndStartMonitoringAgents:]_block_invoke : 824 -> 820
~ -[DADAgentManager _stopMonitoringAndSaveAgents] : 1184 -> 1180
~ -[DADAgentManager _addAccountAggdEntries] : 1012 -> 1008
~ -[DADAgentManager updateFolderListForAccountID:andDataclasses:requireChangedFolders:isUserRequested:] : 396 -> 392
~ -[DADAgentManager updateContentsOfFolders:forAccountID:andDataclasses:isUserRequested:] : 424 -> 420
~ -[DADAgentManager updateContentsOfAllFoldersForAccountID:andDataclasses:isUserRequested:] : 400 -> 396
~ -[DADAgentManager updateContentsOfAllFoldersForAccountIDs:] : 576 -> 568
~ -[DADAgentManager activeAccountBundleIDs] : 372 -> 368
~ -[DADAgentManager hasEASAccountConfigured] : 536 -> 532
~ -[DADAgentManager processMeetingRequestDatas:deliveryIdsToClear:deliveryIdsToSoftClear:inFolderWithId:forAccountWithId:callback:] : 484 -> 480
~ -[DADAgentManager stateString] : 724 -> 720
~ -[DADAgentManager getStatusReportDictsWithCompletionBlock:] : 816 -> 808
~ -[DADAgentManager hasActiveAccounts] : 544 -> 540
~ ___26-[DADMain _shutdownDaemon]_block_invoke.5 : 432 -> 428
~ -[DADMain addSignalHandler] : 304 -> 300
~ ___32-[DADMain _configureAggdLogging]_block_invoke : 712 -> 708
~ ___logState_block_invoke : 320 -> 316
~ ___27-[DARefreshManager dealloc]_block_invoke : 264 -> 260
~ ___31-[DARefreshManager stateString]_block_invoke : 1460 -> 1448
~ -[DARefreshManager _tearDownAllAPSConnectionsUnregisteringTopics:] : 328 -> 324
~ -[DARefreshManager establishAllApsConnections] : 480 -> 476
~ -[DARefreshManager _registerAPSTopicsForDelegates:withConnection:] : 1048 -> 1044
~ -[DARefreshManager _registerAPSTopics] : 500 -> 496
~ -[DARefreshManager _wrapperIsSuspended:] : 588 -> 584
~ -[DARefreshManager _suspendTopicsForDelegate:] : 928 -> 924
~ -[DARefreshManager _resumeTopicsForSuspendedDelegate:] : 836 -> 832
~ -[DARefreshManager pushPreferenceDidChange] : 872 -> 860
~ ___66-[DARefreshManager connection:didReceiveMessageForTopic:userInfo:]_block_invoke : 2092 -> 2080
~ -[DARefreshManager _refreshWrapperForDelegate:] : 320 -> 316
~ -[DARefreshManager _enabledTopicsForWrapper:] : 656 -> 652
~ -[DARefreshManager _suspendedTopicsForWrapper:] : 656 -> 652
~ ___39-[DARefreshManager unregisterDelegate:]_block_invoke : 940 -> 932
~ -[DARefreshManager _dailyRefreshActivityFired] : 304 -> 300
~ -[DARefreshManager _unregisterWrapper:forTopic:inTopicDictionary:] : 420 -> 416
~ -[DARefreshManager _unregisterTopicLocked:forDelegate:inEnvironment:] : 1292 -> 1280
~ -[DARefreshWrapper cancelAllTokenRegistrations] : 348 -> 344
~ -[DARefreshWrapper performTokenRegistrationRequestsWithToken:onBehalfOf:] : 688 -> 684
```
