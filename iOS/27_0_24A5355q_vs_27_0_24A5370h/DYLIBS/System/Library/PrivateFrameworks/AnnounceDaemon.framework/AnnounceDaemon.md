## AnnounceDaemon

> `/System/Library/PrivateFrameworks/AnnounceDaemon.framework/AnnounceDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x560a0` | `0x55ef8` | **`-0x1a8`** |
| `__TEXT.__unwind_info` | `0x16c0` | `0x16c8` | **`+0x8`** |

### Other Changes

```diff

-327.0.0.0.0
+328.0.0.0.0
Functions:
~ -[ANAnnounceReachabilityServiceListener _sendCurrentReachabilityToConnection:] : 1320 -> 1316
~ -[ANAnnounceReachabilityServiceListener reachabilityLevel:didChangeForHome:] : 612 -> 608
~ -[ANAnnounceReachabilityServiceListener reachabilityLevel:didChangeForRoom:inHome:] : 720 -> 716
~ -[ANAnnounceServiceListener getUnplayedAnnouncementsForEndpointID:completionHandler:] : 464 -> 460
~ ___56-[ANPlaybackSessionServiceListener remoteSessionsActive]_block_invoke : 324 -> 320
~ ___54-[ANPlaybackSessionServiceListener _removeConnection:]_block_invoke : 796 -> 788
~ ___57-[ANPlaybackSessionServiceListener _clientForConnection:]_block_invoke : 532 -> 524
~ ___88-[ANPlaybackSessionServiceListener sendPlaybackCommand:forEndpointID:completionHandler:]_block_invoke : 428 -> 424
~ ___96-[ANPlaybackSessionServiceListener coordinator:didUpdateAnnouncements:forGroupID:forEndpointID:]_block_invoke : 448 -> 444
~ ___96-[ANPlaybackSessionServiceListener _updateConnectionForReceivedAnnouncement:groupID:endpointID:]_block_invoke : 448 -> 444
~ ___96-[ANPlaybackSessionServiceListener _updateConnectionForReceivedAnnouncement:groupID:endpointID:]_block_invoke.31 : 476 -> 472
~ ___109-[ANPlaybackSessionServiceListener coordinator:didStartPlayingAnnouncementsAtMachAbsoluteTime:forEndpointID:]_block_invoke : 612 -> 608
~ ___85-[ANPlaybackSessionServiceListener coordinator:didUpdatePlaybackState:forEndpointID:]_block_invoke : 368 -> 364
~ ___84-[ANPlaybackSessionServiceListener coordinator:didUpdatePlaybackInfo:forEndpointID:]_block_invoke : 368 -> 364
~ -[ANMessenger _sendAnnouncement:toDestination:sentHandler:] : 4544 -> 4528
~ -[ANMessenger getScanningDeviceCandidates] : 516 -> 512
~ ___36-[ANMessenger _logDebugInfoForHome:]_block_invoke : 2144 -> 2112
~ -[ANMessenger connectionDidReceiveRequestForHomeLocationStatus:] : 400 -> 396
~ -[ANUserNotificationController cleanForExit] : 816 -> 808
~ -[ANPlaybackManager _playAnnouncements:announceIDToStart:options:completionHandler:] : 936 -> 932
~ -[ANPlaybackManager _nextAnnouncementToPlay] : 1264 -> 1260
~ -[ANAnnouncement(RemotePlaybackSession) remoteSessionDictionary] : 2528 -> 2520
~ +[ANParticipant(Home) participantsFromUsersInHome:] : 424 -> 420
~ -[ANHomeManager(HomeContext) _homeNamesForAccessoryForContext:] : 1256 -> 1252
~ -[ANHomeManager(HomeContext) _findBestHomeNames] : 680 -> 676
~ -[ANHomeManager(HomeContext) _currentHomesWeAreIn] : 1000 -> 996
~ -[ANAnnouncement(AudioProcessing) processAudioWithEffects:error:] : 508 -> 504
~ -[IDSService(AnnounceAdditions) devicesExcludingHomePods] : 312 -> 308
~ -[IDSService(AnnounceAdditions) uniqueIdentifiersForDevicesExcludingAppleAccessories] : 356 -> 352
~ -[ANAnnouncementDestination(Home) zones] : 640 -> 632
~ -[ANAnnouncementDestination(Home) rooms] : 640 -> 632
~ ___55-[ANAnnounceReachabilityManager monitoredRoomsForHome:]_block_invoke : 388 -> 384
~ ___47-[ANAnnounceReachabilityManager monitoredHomes]_block_invoke : 356 -> 352
~ ___62-[ANAnnounceReachabilityManager _initializeReachabilityStatus]_block_invoke : 1356 -> 1348
~ -[ANAnnounceReachabilityManager _reevaluateHomeKitReachabilityForHome:] : 592 -> 588
~ -[ANAnnounceReachabilityManager _reachabilityForHome:] : 408 -> 404
~ -[ANAnnounceReachabilityManager _reachabilityForRoom:inHome:] : 560 -> 556
~ -[ANAnnounceReachabilityManager(ANRapportConnectionDeviceDelegate) connection:didFindDevice:] : 640 -> 636
~ -[ANAnnounceReachabilityManager(ANRapportConnectionDeviceDelegate) connection:didLoseDevice:] : 640 -> 636
~ -[ANAnchorTrackPlayer handleInterruptionDelay:] : 608 -> 604
~ -[ANAnnouncementCoordinator _endpointIDForAnnouncementManager:] : 356 -> 352
~ -[ANAnnouncementCoordinator _endpointIDForPlaybackManager:] : 356 -> 352
~ -[ANAnnouncementCoordinator _handleReceivedAnnouncement:] : 1644 -> 1640
~ ___55-[ANAnnouncementCoordinator _executeBlockForDelegates:]_block_invoke : 456 -> 452
~ ___35-[ANTrackPlayer numberActiveTracks]_block_invoke : 348 -> 344
~ -[ANTrackPlayer _removeItemObserverForPlayer:] : 488 -> 484
~ -[ANTrackPlayer previousInternalSync] : 1300 -> 1296
~ -[ANAnnouncementManager announcementForID:] : 468 -> 464
~ -[ANAnnouncementManager announcementsForIDs:] : 328 -> 324
~ -[ANAnnouncementManager allAnnouncementsSortedByReceipt] : 796 -> 792
~ ___39-[ANAnnouncementManager pauseAllTimers]_block_invoke : 508 -> 504
~ ___40-[ANAnnouncementManager resumeAllTimers]_block_invoke : 508 -> 504
~ ___39-[ANAnnouncementManager resetAllTimers]_block_invoke : 280 -> 276
~ -[ANAnnouncementManager _removeAnnouncementsForGroupID:] : 552 -> 548
~ -[ANAnnouncementManager _removeAnnouncementsHittingStorageAgeLimit] : 1172 -> 1168
~ -[ANAnnouncementManager _removeAnnouncementWithID:] : 584 -> 580
~ ___49-[ANAnnouncementManager _loadStoredAnnouncements]_block_invoke : 764 -> 756
~ -[ANAnnouncementManager _handleExpiredTimer:withID:] : 928 -> 924
~ -[ANAnnouncementStorageManager storedAnnouncementsForEndpointID:] : 956 -> 952
~ -[ANAnnouncementStorageManager deleteAnnouncementsExcludingAnnouncementsForEndpointIDs:] : 504 -> 500
~ -[ANAnnouncementStorageManager removeAnnouncementDataExcludingDataForAnnouncementIDs:endpointID:] : 1368 -> 1352
~ -[ANAnnouncementStorageManager _removeAudioDataForAnnouncementID:endpointID:] : 1208 -> 1204
~ -[ANAnnouncementStorageManager _removeDirectoryForEndpointsExcludingEndpointIDs:] : 1232 -> 1228
~ -[ANMessengerDestination idsIdentifiersForService:] : 692 -> 684
~ -[ANMessengerDestination participantsWithService:] : 900 -> 888
~ -[ANMessengerDestination addDeviceWithID:rapportConnection:] : 472 -> 468
~ -[ANMessengerDestination removeUser:rapportConnection:] : 376 -> 372
~ +[ANMessengerDestination _destinationForAppleAccessories:home:rooms:rapportConnection:] : 612 -> 608
~ +[ANMessengerDestination _bestRemoteRelayAccessoryFromAccessories:inHome:] : 1664 -> 1660
~ +[ANMessenger(Announcement) announcementForDevice:inHome:fromAnnouncement:] : 480 -> 476
~ ___47-[ANRapportConnection addDeviceDelegate:queue:]_block_invoke : 484 -> 480
~ -[ANRapportConnection _executeBlockForDelegates:] : 468 -> 464
~ -[ANAnalyticsDaily _reportEventStorage] : 652 -> 648
~ -[ANAnalyticsDaily _collectForHome:homes:] : 924 -> 944
~ -[ANAnalyticsDaily _collectForAnnouncementsInHome:completion:] : 1720 -> 1716
~ -[ANAnalyticsDailyAnnouncements initWithDictionary:] : 380 -> 376
~ -[ANAnalyticsDailyAnnouncements dictionary] : 408 -> 404
~ -[ANAnalyticsDailyAnnouncements announcementsCount] : 520 -> 516
~ -[ANAnalytics announcementsExpired:ofGroupCount:context:] : 704 -> 700
~ -[ANLocation(Home) containsAccessory:] : 880 -> 872
~ -[NSArray(RPCompanionLinkDevice_Announce) activeAccessoryDevicesSupportingAnnounce] : 384 -> 380
~ -[NSArray(RPCompanionLinkDevice_Announce) activeDevicesSupportingAnnounce] : 408 -> 404
~ -[NSArray(RPCompanionLinkDevice_Announce) activePersonalDevicesSupportingAnnounce] : 312 -> 308
~ -[NSArray(RPCompanionLinkDevice_Announce) pairedCompanion] : 276 -> 272
~ -[NSArray(RPCompanionLinkDevice_Announce) devicesInHome:] : 508 -> 504
~ -[NSArray(RPCompanionLinkDevice_Announce) devicesByRemovingNonAccessoryDevicesNotBelongingToUsers:] : 552 -> 548
~ -[NSArray(RPCompanionLinkDevice_Announce) personalDevicesForUser:] : 388 -> 384
~ +[ANAnnouncement(Home) uniqueAnnouncersInAnnouncements:] : 384 -> 380
~ -[ANCompanionConnection broadcastToMediaGroupAnnouncementPlayed:] : 816 -> 812
~ sub_2213e943c -> sub_22225728c : 4320 -> 4328
~ sub_2213ebeb8 -> sub_222259d10 : 280 -> 276
~ sub_2213ec958 -> sub_22225a7ac : 392 -> 384
~ sub_2213ecae0 -> sub_22225a92c : 1684 -> 1692
~ ___swift_closure_destructor.15 : 168 -> 176
~ sub_2213ef9a8 -> sub_22225d804 : 440 -> 444
~ sub_2213f1da8 -> sub_22225fc08 : 1008 -> 1004
~ sub_2213f28cc -> sub_222260728 : 324 -> 332
~ sub_2213f3530 -> sub_222261394 : 604 -> 596
~ sub_2213f4348 -> sub_2222621a4 : 552 -> 544
~ sub_2213f94fc -> sub_222267350 : 356 -> 364
~ sub_2213f96bc -> sub_222267518 : 256 -> 264
~ sub_2213f97bc -> sub_222267620 : 424 -> 420
~ sub_2213f9964 -> sub_2222677c4 : 424 -> 420
~ sub_2213f9b0c -> sub_222267968 : 424 -> 420
~ sub_2213f9cb4 -> sub_222267b0c : 424 -> 420
~ sub_2213f9e5c -> sub_222267cb0 : 424 -> 420
~ ___swift_closure_destructor : 140 -> 148
```
