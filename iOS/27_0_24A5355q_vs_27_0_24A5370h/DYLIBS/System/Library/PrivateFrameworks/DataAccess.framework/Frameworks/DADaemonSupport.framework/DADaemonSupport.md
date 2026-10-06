## DADaemonSupport

> `/System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DADaemonSupport.framework/DADaemonSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37580` | `0x373d0` | **`-0x1b0`** |

### Other Changes

```diff

-2703.0.0.0.0
+2704.0.0.0.0
Functions:
~ ___42-[DADAccessManager _setupServerConnection]_block_invoke : 2072 -> 2068
~ -[DADAccessManager addPersistentClientWithAccountID:clientID:watchedIDs:] : 688 -> 684
~ -[DADAccessManager isAccountID:folderID:watchedByClientBesides:] : 468 -> 464
~ -[DADAccessManager stateString] : 444 -> 440
~ -[DADAgentManager agentWithAccountID:] : 372 -> 368
~ -[DADAgentManager accountWithAccountID:] : 388 -> 384
~ -[DADAgentManager accountWithAccountID:andClassName:] : 432 -> 428
~ -[DADAgentManager loadAgents] : 2276 -> 2268
~ -[DADAgentManager releaseAgents] : 328 -> 324
~ -[DADAgentManager _deviceWillSleep] : 416 -> 412
~ -[DADAgentManager _deviceDidWake] : 256 -> 252
~ -[DADAgentManager startMonitoringAccountID:folderIDs:] : 636 -> 632
~ -[DADAgentManager stopMonitoringAccountID:folderIDs:] : 520 -> 516
~ -[DADAgentManager suspendMonitoringAccountID:folderIDs:] : 520 -> 516
~ -[DADAgentManager resumeMonitoringAccountID:folderIDs:] : 520 -> 516
~ -[DADAgentManager _clearOrphanedStoresInCalendarDatabase:eventAccountIds:] : 1052 -> 1048
~ -[DADAgentManager _clearOrphanedSubscribedCalendars:eventAccountIds:] : 1036 -> 1024
~ -[DADAgentManager appleAccountsMatchingClass:errror:] : 528 -> 524
~ -[DADAgentManager _clearOrphanedStoresAndTrafficLogFiles] : 7064 -> 7032
~ -[DADAgentManager _cleanOrphanedTrafficLogFilesWithCurrentEventAccountIdentifiers:] : 912 -> 908
~ -[DADAgentManager _calDaysToSyncDidChange] : 580 -> 576
~ -[DADAgentManager _handleCellularDataUsageChangedNotification] : 1380 -> 1368
~ ___48-[DADAgentManager _loadAndStartMonitoringAgents]_block_invoke : 832 -> 828
~ -[DADAgentManager _stopMonitoringAndSaveAgents] : 1216 -> 1212
~ -[DADAgentManager _sendAccountAnalytics] : 380 -> 376
~ -[DADAgentManager updateFolderListForAccountID:andDataclasses:requireChangedFolders:isUserRequested:] : 332 -> 328
~ -[DADAgentManager updateContentsOfFolders:forAccountID:andDataclasses:isUserRequested:] : 360 -> 356
~ -[DADAgentManager agentsToSyncForAccountID:] : 528 -> 516
~ -[DADAgentManager activeAccountBundleIDs] : 372 -> 368
~ -[DADAgentManager hasEASAccountConfigured] : 536 -> 532
~ -[DADAgentManager processMeetingRequestDatas:deliveryIdsToClear:deliveryIdsToSoftClear:inFolderWithId:forAccountWithId:callback:] : 484 -> 480
~ -[DADAgentManager resetCertWarningsForAccountWithId:andDataclasses:] : 416 -> 412
~ -[DADAgentManager stateString] : 772 -> 768
~ -[DADAgentManager getStatusReportDictsWithCompletionBlock:] : 816 -> 808
~ -[DADAgentManager hasActiveAccounts] : 544 -> 540
~ -[DADClient _removeBusyFolderIDs:forAccountWithID:] : 372 -> 368
~ -[DADClient _removeWatchedFolderIDs:forAccountWithID:] : 372 -> 368
~ -[DADClient disable] : 784 -> 776
~ ___20-[DADClient disable]_block_invoke : 1328 -> 1324
~ -[DADClient watchedFolderCount] : 360 -> 356
~ -[DADClient persistentClientCleanup] : 808 -> 800
~ -[DADClient isMonitoringAccountID:folderID:] : 352 -> 348
~ ___36-[DADClient _stopMonitoringFolders:]_block_invoke_2 : 540 -> 536
~ -[DADClient _restartAgentsDueToTimeout] : 448 -> 444
~ -[DADClient _clearAllStopMonitoringAgentsTokens] : 320 -> 316
~ -[DADClient _requestFolderContentsUpdateForFolders:accountId:dataclasses:isUserRequested:] : 1276 -> 1272
~ -[DADClient _endAllServerSimulations] : 268 -> 264
~ -[DADClientAccountTimers clientBehaviorForFolderIds:] : 436 -> 432
~ ___26-[DADMain _shutdownDaemon]_block_invoke.5 : 432 -> 428
~ -[DADMain addSignalHandler] : 304 -> 300
~ ___logState_block_invoke : 260 -> 256
~ -[DADAgentStopStartController callBlocks:] : 244 -> 240
~ ___27-[DARefreshManager dealloc]_block_invoke : 260 -> 256
~ ___31-[DARefreshManager stateString]_block_invoke : 1460 -> 1448
~ -[DARefreshManager _tearDownAllApsConnections] : 248 -> 244
~ -[DARefreshManager establishAllApsConnections] : 480 -> 476
~ -[DARefreshManager _registerAPSTopicsForDelegates:withConnection:] : 1236 -> 1232
~ -[DARefreshManager _nextPushRegistrationRefreshDeadline] : 792 -> 788
~ -[DARefreshManager _registerAPSTopics] : 408 -> 404
~ -[DARefreshManager _wrapperIsSuspended:] : 588 -> 584
~ -[DARefreshManager _suspendTopicsForDelegate:] : 928 -> 924
~ -[DARefreshManager _resumeTopicsForSuspendedDelegate:] : 836 -> 832
~ ___66-[DARefreshManager connection:didReceiveMessageForTopic:userInfo:]_block_invoke : 2000 -> 1988
~ -[DARefreshManager _refreshWrapperForDelegate:] : 320 -> 316
~ -[DARefreshManager _enabledTopicsForWrapper:] : 656 -> 652
~ -[DARefreshManager _suspendedTopicsForWrapper:] : 656 -> 652
~ ___39-[DARefreshManager unregisterDelegate:]_block_invoke : 940 -> 932
~ -[DARefreshManager _dailyRefreshActivityFired] : 304 -> 300
~ -[DARefreshManager _unregisterWrapper:forTopic:inTopicDictionary:] : 420 -> 416
~ -[DARefreshManager _unregisterTopicLocked:forDelegate:inEnvironment:] : 1276 -> 1264
~ ___75-[DARefreshManager delegateDidSuccessfullyRecoverFromBeingUnauthenticated:]_block_invoke : 760 -> 748
~ -[DADClientHolidayCalendarFetchDelegate _handleCalendarSearchResults:] : 836 -> 828
~ -[DADClientHolidayCalendarFetchDelegate syncingAccount] : 852 -> 848
~ ___50-[DAReachability _notifyDelegatesNetworkReachable]_block_invoke : 240 -> 236
~ ___48-[DAReachability _notifyDelegatesHostReachable:]_block_invoke : 240 -> 236
~ -[DARefreshWrapper cancelAllTokenRegistrations] : 348 -> 344
~ -[DARefreshWrapper performTokenRegistrationRequestsWithToken:onBehalfOf:] : 688 -> 684
~ -[DADClientCalendarDirectorySearchResponseDelegate _convertSearchQueryResults:] : 544 -> 540
~ -[DADStatusReportAggregator initWithStatusReports:numOutstandingReports:timeout:completionBlock:] : 556 -> 552
~ -[DADStatusReportAggregator _coalesceAndReport] : 524 -> 520
~ -[DADStatusReportAggregator noteAdditionalReportDicts:] : 388 -> 384
```
