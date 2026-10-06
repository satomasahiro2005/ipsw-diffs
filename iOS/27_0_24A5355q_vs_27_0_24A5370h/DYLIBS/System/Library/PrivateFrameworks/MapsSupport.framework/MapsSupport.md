## MapsSupport

> `/System/Library/PrivateFrameworks/MapsSupport.framework/MapsSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x843dc` | `0x842bc` | **`-0x120`** |
| `__TEXT.__oslogstring` | `0x859d` | `0x863d` | **`+0xa0`** |

### Other Changes

```diff

-2966.30.5.15.8
+2970.30.6.5.7

-  CStrings:  1392
+  CStrings:  1394
Functions:
~ _MapsMap : 400 -> 396
~ -[MSPSharedTripCapabilityFetchingServer fetchCapabilitiesForContacts:] : 1516 -> 1508
~ -[MSPSharedTripCapabilityFetchingServer _performBlockOnAllQueues:] : 308 -> 304
~ -[MSPSharedTripCapabilityFetchingQueue _updateRequestedHandlesWithAdditions:subtractions:] : 632 -> 628
~ -[MSPCountedOrderedSet unionSet:] : 288 -> 284
~ -[MSPCountedOrderedSet minusSet:] : 288 -> 284
~ -[MSPSharedTripServer cleanConnections] : 372 -> 368
~ -[MSPSharedTripServer _purgeSubscriptionsForConnection:] : 780 -> 776
~ -[MSPSharedTripServer etaController:didUpdateDestinationForSharedTrip:] : 540 -> 536
~ -[MSPSharedTripServer etaController:didUpdateReachedDestinationForSharedTrip:] : 540 -> 536
~ -[MSPSharedTripServer etaController:didUpdateETAForSharedTrip:] : 540 -> 536
~ -[MSPSharedTripServer etaController:didUpdateRouteForSharedTrip:] : 540 -> 536
~ -[MSPSharedTripServer etaController:sharedTripDidBecomeAvailable:] : 540 -> 536
~ -[MSPSharedTripServer etaController:sharedTripDidBecomeUnavailable:] : 540 -> 536
~ -[MSPSharedTripServer etaController:sharedTripDidClose:] : 540 -> 536
~ -[MSPSharedTripServer senderController:didStartSharingWithGroupIdentifier:] : 540 -> 536
~ -[MSPSharedTripServer senderController:didInvalidateSharedTripWithError:] : 540 -> 536
~ -[MSPSharedTripServer invalidateActiveHandlesForSenderController:] : 600 -> 596
~ -[MSPSharedTripServer relay:accountStatusChanged:] : 572 -> 568
~ -[MSPReceiverETAController allTrips] : 396 -> 392
~ -[MSPReceiverETAController blockSharedTrip:] : 564 -> 560
~ -[MSPReceiverETAController updateContacts] : 564 -> 560
~ -[MSPReceiverETAController _cleanupIfNecessary] : 280 -> 276
~ -[MSPReceiverETAController storageController:updatedSharedTripGroupStorage:] : 756 -> 752
~ -[MSPSenderIDSStrategy setState:forEvent:] : 1168 -> 1164
~ -[MSPSenderIDSStrategy _sendETAUpdateIfNeededTo:] : 572 -> 568
~ ___40-[MSPSenderIDSStrategy addParticipants:]_block_invoke_2 : 404 -> 400
~ -[MSPSenderIDSStrategy _sendCompatibleInstancesOfState:to:] : 788 -> 784
~ -[MSPSenderIDSStrategy _sendUpdatedWaypoints:to:] : 844 -> 840
~ -[MSPSenderIDSStrategy _sendETAUpdate:to:] : 736 -> 732
~ -[MSPSenderMinimalStrategy _sendInitialStateIfNeeded] : 1124 -> 1120
~ -[MSPSenderLiveStrategy addParticipants:] : 308 -> 304
~ -[MSPSenderLiveStrategy removeParticipants:] : 248 -> 244
~ -[MSPSenderLiveStrategy _sendInitialRouteIfNeeded] : 1056 -> 1052
~ -[MSPSenderMessageStrategy sendMessageIfNeeded] : 2256 -> 2272
~ -[MSPSenderVirtualMinimalStrategy fetchCapabilitiesForParticipants:completion:] : 368 -> 364
~ -[MSPSenderVirtualLiveStrategy fetchCapabilitiesForParticipants:completion:] : 368 -> 364
~ -[MSPTransitStorageIncident(MSPExtra) initWithIncident:] : 844 -> 840
~ -[MSPTransitStorageIncidentEntity(MSPExtra) initWithIncidentEntity:] : 340 -> 336
~ -[MSPTransitStorageLineItem(MSPExtra) initWithLineItem:] : 524 -> 520
~ -[MSPTransitStorageAttribution(MSPExtra) initWithAttribution:] : 320 -> 316
~ -[MSPTransitStorageLineItem dictionaryRepresentation] : 636 -> 632
~ -[MSPTransitStorageLineItem writeTo:] : 404 -> 400
~ -[MSPTransitStorageLineItem copyWithZone:] : 468 -> 464
~ -[MSPTransitStorageLineItem mergeFrom:] : 436 -> 432
~ -[GEOPDBankTransactionInformation(MSPWallet) initWithMSPWalletBankTransactionInformation:rawMerchantCode:industryCategory:] : 632 -> 628
~ -[MSPSharedTripBlocklist description] : 660 -> 656
~ -[MSPSharedTripBlocklist blockIdentifiers:] : 1348 -> 1344
~ -[MSPSharedTripBlocklist unblockIdentifiers:] : 1116 -> 1112
~ -[MSPSharedTripBlocklist _purgeExpiredIdentifiersIn:] : 1876 -> 1868
~ -[MSPSharedTripBlocklist _reloadBlockedIdentifiersFromSync] : 820 -> 816
~ -[GEOSharedNavState(MSPExtras) truncatePointDataForPrivacy] : 1852 -> 1848
~ -[GEOSharedNavState(MSPExtras) updateWaypointsFromComposedRoute:] : 1128 -> 1124
~ -[GEOSharedNavState(MSPExtras) composedRoute] : 2028 -> 2024
~ -[MSPSharedTripContact _populateFromContactUsingHandle:] : 648 -> 640
~ +[MSPSharedTripContact contactsFromCNContact:matchingHandles:] : 1152 -> 1144
~ +[MSPSharedTripContact contactsFromCNContact:] : 660 -> 652
~ -[MSPSharedTripContact isHandleBlocked] : 528 -> 524
~ -[MSPSharedTripMessagesCapabilityFetchingQueue _fetchTextMessageReachability:] : 760 -> 748
~ -[MSPTransitStorageAttribution writeTo:] : 308 -> 304
~ -[MSPTransitStorageAttribution copyWithZone:] : 348 -> 344
~ -[MSPTransitStorageAttribution mergeFrom:] : 260 -> 256
~ -[MSPPinnedPlaceStorage dictionaryRepresentation] : 816 -> 812
~ -[MSPPinnedPlaceStorage writeTo:] : 520 -> 516
~ -[MSPPinnedPlaceStorage copyWithZone:] : 608 -> 604
~ -[MSPPinnedPlaceStorage mergeFrom:] : 516 -> 512
~ _MSPSharedTripVirtualReceiverHandleGetName : 732 -> 728
~ _MSPSharedTripVirtualReceiverHandleGetReceiverCapabilities : 444 -> 440
~ _MSPSharedTripVirtualReceiverHandleGetReceiverCapabilityVersions : 796 -> 792
~ _MSPSharedTripVirtualReceiverHandleGetCapabilityType : 668 -> 664
~ _MSPSharedTripVirturalReceiverDeviceHandleGetReceiverCapabilityVersion : 348 -> 344
~ _MSPSharedTripVirtualReceiverHandleGetServiceName : 500 -> 496
~ _MSPSharedTripVirtualReceiverHandleMake : 796 -> 792
~ _MSPSharedTripGetVirtualReceivers : 332 -> 328
~ _MSPSharedTripGetRealReceivers : 332 -> 328
~ -[MSPTransitStorageIncident dictionaryRepresentation] : 1212 -> 1208
~ -[MSPTransitStorageIncident writeTo:] : 788 -> 784
~ -[MSPTransitStorageIncident copyWithZone:] : 932 -> 928
~ -[MSPTransitStorageIncident mergeFrom:] : 792 -> 788
~ ___97-[MSPMapsPushDaemonRemoteProxy pushDaemonProxyReceivedNotificationData:forType:recordIdentifier:]_block_invoke : 252 -> 248
~ -[MSPCollectionItemReplicaStorage dictionaryRepresentation] : 504 -> 500
~ -[MSPCollectionItemReplicaStorage writeTo:] : 340 -> 336
~ -[MSPCollectionItemReplicaStorage copyWithZone:] : 388 -> 384
~ -[MSPCollectionItemReplicaStorage mergeFrom:] : 308 -> 304
~ -[MSPSharedTripIDSCapabilityFetchingQueue batchQueryController:updatedDestinationsStatus:onService:error:] : 1648 -> 1644
~ -[MSPSharedTripContactController _updateActiveSharingHandles:serviceNames:] : 1200 -> 1192
~ -[MSPSharedTripContactController _archivedSharingStorage] : 856 -> 848
~ -[MSPSharedTripGroupSession sendCommand:fromHandle:fromAccountID:error:] : 728 -> 980
~ -[MSPSharedTripGroupSession _isValidParticipant:] : 524 -> 520
~ -[MSPSharedTripCapabilityFetchingServer cleanConnections] : 388 -> 384
~ -[MSPSharedTripCapabilityFetchingServer capabilityFetchingQueue:didFetchStatusForHandles:] : 232 -> 228
~ -[MSPQuerySource _didReceiveContainerContents:context:] : 444 -> 440
~ -[MSPQuerySource _didChangeSourceWithNewState:context:inContainer:] : 432 -> 428
~ ___54-[MSPEditableQuery moveContentsObjectAtIndex:toIndex:]_block_invoke_2 : 492 -> 488
~ -[_MSPQueryState initWithContainerContents:] : 412 -> 408
~ -[_MSPQueryState stateByInvokingPreprocessingBlock:mappingBlock:] : 564 -> 560
~ ___64-[NSObject(MapsSharedExtras) _maps_setNeedsUpdate:withSelector:]_block_invoke : 344 -> 340
~ -[NSString(MapsSharedExtras) _maps_prefixMatchesForSearchString:] : 992 -> 988
~ -[MSPSyncManager service:startSession:error:] : 608 -> 604
~ -[MSPSyncManager syncSession:enqueueChanges:error:] : 1188 -> 1180
~ -[MSPSyncManager syncSession:applyChanges:completion:] : 500 -> 496
~ -[MSPSyncManager _updateFromDisk] : 388 -> 384
~ -[MSPSyncManager setDroppedPin:] : 504 -> 500
~ _MSPBookmarkStorageArrayFromPropertyList : 648 -> 644
~ _MSPHistoryEntryStorageArrayFromPropertyList : 648 -> 644
~ -[MSPSharingRestorationStorage writeTo:] : 552 -> 544
~ -[MSPSharingRestorationStorage copyWithZone:] : 624 -> 616
~ -[MSPSharingRestorationStorage mergeFrom:] : 524 -> 516
~ -[IDSService(MSPExtras) _msp_currentAccountIdentifier] : 828 -> 820
~ -[IDSService(MSPExtras) _msp_removeSelfFrom:] : 508 -> 504
~ +[IDSService(MSPExtras) _msp_IDSIdentifiersFor:] : 368 -> 364
~ ___63-[MSPStorageTipsManager fetchProposedTipWithCompletionHandler:]_block_invoke_2 : 1180 -> 1176
~ ___86-[MSPContainer _performInitialLoadNotifyingObservers:kickOffSynchronously:completion:]_block_invoke.59 : 1052 -> 1048
~ -[MSPContainer _processedContentsForPersisterContents:] : 576 -> 572
~ -[MSPContainer _objectsWithDuplicateStorageIdentifiersFromArray:] : 856 -> 844
~ ___91-[MSPContainer editByMergingStateSnapshot:mergeOptions:context:completionQueue:completion:]_block_invoke.85 : 1784 -> 1772
~ ___81-[MSPContainer editContentsUsingBarrierBlock:context:completionQueue:completion:]_block_invoke.121 : 1964 -> 1956
~ ___96-[MSPContainer editObjectsWithIdentifiers:usingBarrierBlock:context:completionQueue:completion:]_block_invoke : 312 -> 308
~ -[MSPContainer _forEachObserver:] : 536 -> 532
~ ___49-[MSPContainer _commitPendingCoalescedEditsIfAny]_block_invoke : 272 -> 268
~ ___49-[MSPContainer _commitPendingCoalescedEditsIfAny]_block_invoke_2 : 268 -> 264
~ ___49-[MSPContainer _commitPendingCoalescedEditsIfAny]_block_invoke_3 : 272 -> 268
~ ___49-[MSPContainer _commitPendingCoalescedEditsIfAny]_block_invoke_4 : 268 -> 264
~ -[NSArray(MSPContainerAdditions) _maps_indexesOfObjectsCorrespondingToIdentifiableObjects:] : 464 -> 460
~ -[NSArray(MSPContainerAdditions) _maps_indexOfObjectCorrespondingToIdentifiableObject:] : 344 -> 340
~ -[NSArray(MSPContainerAdditions) _maps_arrayWithObjectsConformingToProtocols:] : 460 -> 456
~ -[MSPTransitStorageIncidentEntity writeTo:] : 220 -> 216
~ -[MSPSenderETAController stopSharingWith:reason:error:] : 1544 -> 1540
~ ___52-[MSPSenderETAController serviceNamesByActiveHandle]_block_invoke : 280 -> 276
~ -[_MSPContainerEditsRecorder useImmutableObjectsForEditsFromMap:intermediateMutableObjectTransferBlock:] : 292 -> 288
~ -[_MSPContainerEditAddition initWithObjects:indexes:identifiersAtop:] : 528 -> 524
~ -[_MSPContainerEditAddition useImmutableObjectsFromMap:intermediateMutableObjectTransferBlock:] : 548 -> 544
~ -[_MSPContainerEditRemoval useImmutableObjectsFromMap:intermediateMutableObjectTransferBlock:] : 548 -> 544
~ -[_MSPContainerEditReplacement useImmutableObjectsFromMap:intermediateMutableObjectTransferBlock:] : 952 -> 944
~ -[MSPSharedTripSenderStrategyController _currentSendersByServiceName] : 76 -> 72
~ -[MSPSharedTripReceiverCapabilities initWithIDSEndpointCapabilities:] : 448 -> 444
~ +[MSPSharedTripReceiverCapabilities fetchReceiverCapabilitiesForDestinations:completion:] : 892 -> 888
~ ___89+[MSPSharedTripReceiverCapabilities fetchReceiverCapabilitiesForDestinations:completion:]_block_invoke_2 : 688 -> 684
~ -[MSPGroupSessionStorage writeTo:] : 1040 -> 1024
~ -[MSPGroupSessionStorage copyWithZone:] : 1184 -> 1168
~ -[MSPGroupSessionStorage mergeFrom:] : 1008 -> 992
~ -[MSPSharedTripRelay userHasAcceptedShareFrom:] : 440 -> 436
~ -[MSPSharedTripRelay _handleChunk:fromID:receivingHandle:receivingAccountIdentifier:] : 2036 -> 2032
~ -[MSPSharedTripRelay _handleIncomingMessage:info:fromID:receivingHandle:receivingAccountIdentifier:] : 424 -> 536
~ -[MSPSharedTripService _checkBlockList] : 792 -> 788
~ sub_1c91a1260 -> sub_1c99f9130 : 280 -> 276
~ sub_1c91a18d4 -> sub_1c99f97a0 : 256 -> 276
CStrings:
+ "[GS] sendCommand: %@ aborting — missing fromHandle (account: %@)"
+ "[RELAY] add new session %@ with nil receivingHandle from IDS context (account: %@, fromID: %@)"
```
