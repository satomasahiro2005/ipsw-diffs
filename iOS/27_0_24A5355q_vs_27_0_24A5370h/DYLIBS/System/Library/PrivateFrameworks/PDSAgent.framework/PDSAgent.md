## PDSAgent

> `/System/Library/PrivateFrameworks/PDSAgent.framework/PDSAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b340` | `0x1b224` | **`-0x11c`** |

### Other Changes

```diff

-1992.100.7.2.1
+1996.100.2.2.2
Functions:
~ ___51-[PDSXPCServer listener:shouldAcceptNewConnection:]_block_invoke -> -[PDSXPCServer XPCClients] : 188 -> 8
~ -[PDSXPCServer XPCClients] -> -[PDSXPCClient .cxx_destruct] : 8 -> 92
~ -[PDSXPCClient .cxx_destruct] -> -[PDSDaemonListener .cxx_destruct] : 92 -> 80
~ -[PDSDaemonListener .cxx_destruct] -> ___51-[PDSXPCServer listener:shouldAcceptNewConnection:]_block_invoke : 80 -> 188
~ -[PDSUserTracker validUser:withError:] : 788 -> 784
~ -[PDSUserTracker tokenAndIdentifier:forUser:withError:] : 848 -> 844
~ -[PDSUserTracker _accountForUser:withError:] : 788 -> 784
~ ___35-[PDSCDCacheContainer loadAllUsers]_block_invoke : 616 -> 608
~ ___76-[PDSCDCacheContainer storeEntries:transitionBlock:deleteEntries:withError:]_block_invoke : 584 -> 576
~ ___64-[PDSCDCacheContainer deleteEntriesForUser:withState:withError:]_block_invoke : 464 -> 460
~ -[PDSCDCacheContainer deleteCache] : 428 -> 424
~ -[PDSCDCacheContainer _storeEntry:transitionBlock:context:withError:] : 1664 -> 1660
~ -[PDSCDCacheContainer _deleteEntry:context:withError:] : 852 -> 844
~ ___38-[PDSCDCacheContainer allStoredValues]_block_invoke : 468 -> 464
~ -[PDSCDCacheContainer _entriesFromRegistrations:inContext:] : 596 -> 588
~ ___68-[PDSCDCacheContainer _updateEntryState:forUser:clientID:withError:]_block_invoke : 336 -> 332
~ ___68-[PDSCDCacheContainer _updateAllEntriesWithState:toState:withError:]_block_invoke : 396 -> 392
~ -[PDSCDCacheContainer _cdRegistrationsMatchingUser:withClientID:inContext:] : 608 -> 600
~ ___53-[PDSCDCacheContainer _loadUsersIncludingOnlyActive:]_block_invoke : 616 -> 608
~ ___52-[PDSCDCacheContainer _usersForClientID:activeOnly:]_block_invoke : 740 -> 732
~ ___48-[PDSCDCacheContainer _KVEntryForKey:withBlock:]_block_invoke : 620 -> 616
~ -[PDSEntryStore storeEntries:deleteEntries:withError:] : 716 -> 708
~ -[PDSProtoBatchRegisterReq dictionaryRepresentation] : 492 -> 488
~ -[PDSProtoBatchRegisterReq writeTo:] : 332 -> 328
~ -[PDSProtoBatchRegisterReq copyWithZone:] : 380 -> 376
~ -[PDSProtoBatchRegisterReq mergeFrom:] : 336 -> 332
~ -[PDSProtoBatchRegisterResp dictionaryRepresentation] : 724 -> 720
~ -[PDSProtoBatchRegisterResp writeTo:] : 472 -> 468
~ -[PDSProtoBatchRegisterResp copyWithZone:] : 544 -> 540
~ -[PDSProtoBatchRegisterResp mergeFrom:] : 488 -> 484
~ -[PDSProtoTopic dictionaryRepresentation] : 476 -> 472
~ -[PDSProtoTopic writeTo:] : 344 -> 340
~ -[PDSProtoTopic copyWithZone:] : 396 -> 392
~ -[PDSProtoTopic mergeFrom:] : 336 -> 332
~ -[PDSProtoUserPushTokenRegRequest dictionaryRepresentation] : 800 -> 792
~ -[PDSProtoUserPushTokenRegRequest writeTo:] : 528 -> 520
~ -[PDSProtoUserPushTokenRegRequest copyWithZone:] : 600 -> 592
~ -[PDSProtoUserPushTokenRegRequest mergeFrom:] : 548 -> 540
~ -[PDSRequest hash] : 260 -> 256
~ ___34-[PDSRequestQueue _flightRequest:]_block_invoke_2 : 1056 -> 1052
~ -[PDSRequestQueue _cancelPendingRequests] : 364 -> 360
~ -[PDSRequestQueue _logEntries:] : 676 -> 668
~ -[PDSCoordinator _processEntryStore] : 2072 -> 2068
~ -[PDSCoordinator _updateEntriesForResponse:fromRequest:] : 908 -> 904
~ -[PDSCoordinator _entries:includeState:] : 272 -> 268
~ -[PDSCoordinator _matchingEntryExistsFor:inStore:] : 364 -> 360
~ -[PDSCoordinator _timeToDelayRequestForTopics:] : 564 -> 560
~ -[PDSXPCClient _connectionEntitledClientIDs] : 440 -> 436
~ -[PDSDaemonListener storeEntries:deleteEntries:withCompletion:] : 1604 -> 1584
~ -[PDSDaemonListener batchUpdateEntries:forClientID:withCompletion:] : 1344 -> 1328
~ -[PDSInternalDaemonListener kvStateDumpWithCompletion:] : 528 -> 524
~ -[IDSServerBag(CoordinatorAccessors) nonCoalescingTopicsFromBag] : 388 -> 384
~ -[IDSServerBag(CoordinatorAccessors) _valuesDefinedAsNumbersInBagForKeys:] : 324 -> 320
~ ___34-[PDSDaemon _setupSysdiagnoseDump]_block_invoke : 536 -> 528
```
