## FrontBoardServices

> `/System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x989f0` | `0x987d4` | **`-0x21c`** |
| `__TEXT.__unwind_info` | `0x2b10` | `0x2b18` | **`+0x8`** |

### Other Changes

```diff

-1145.0.0.0.0
+1148.0.0.0.0

-  Functions: 4373
-  Symbols:   6487
+  Functions: 4371
+  Symbols:   6486
Symbols:
- _OUTLINED_FUNCTION_71
Functions:
~ -[FBSDisplayMonitor mainConfiguration] : 284 -> 280
~ -[FBSDisplayConfiguration _initWithImmutableDisplay:originalDisplay:isMainDisplay:assertIfInvalid:] : 1856 -> 1852
~ -[FBSDisplayConfiguration CADisplay] : 472 -> 468
~ _FBSRealizeSubclassExtension : 1604 -> 1596
~ -[FBSSettings _sceneExtensionNames] : 372 -> 368
~ ___66-[FBSApplicationLibrary installedApplicationsForBundleIdentifier:]_block_invoke : 292 -> 288
~ -[_FBSScenesClientHostEvent complete] : 236 -> 232
~ _OUTLINED_FUNCTION_32 : 16 -> 12
~ _OUTLINED_FUNCTION_32 : 20 -> 32
~ -[_FBSDisplayLayoutService updateLayout:withTransition:] : 436 -> 432
~ ___34-[FBSDisplayLayoutPublisher flush]_block_invoke : 536 -> 532
~ __lock_getDefaultExtensions : 500 -> 496
~ ___55-[FBSDisplayMonitor _lock_enumerateConnectedWithBlock:]_block_invoke : 260 -> 256
~ -[FBSDisplayMonitor _lock_enumerateSourcesWithBlock:] : 292 -> 288
~ -[FBSWorkspaceScenesClient _configureReceivedActions:forScene:] : 300 -> 296
~ _OUTLINED_FUNCTION_33 : 12 -> 28
~ -[FBSScene _callOutQueue_updateExtensionsFromSettings:toSettings:withDiff:] : 896 -> 1076
~ ___52-[FBSSettingsDiffInspector inspectDiff:withContext:]_block_invoke_2 : 284 -> 280
~ -[_FBSScenesClientHostEvent coalesceEvents:] : 372 -> 368
~ ___36-[FBSWorkspace sceneWithIdentifier:]_block_invoke : 340 -> 336
~ -[FBSSceneObserver _matchesDiff:] : 264 -> 276
~ -[FBSSettings conformsToExtension:] : 392 -> 388
~ -[FBSDisplayConfigurationBuilder setCurrentMode:preferredMode:otherModes:] : 1172 -> 1164
~ -[FBSScene componentForExtension:ofClass:] : 396 -> 392
~ __gatherProperties : 480 -> 476
~ __gatherMethods : 436 -> 432
~ _OUTLINED_FUNCTION_10 : 36 -> 8
~ _OUTLINED_FUNCTION_10 : 8 -> 24
- _OUTLINED_FUNCTION_10
~ __realizeSettingsExtension : 9148 -> 9156
~ __flushBulkMethods : 804 -> 796
~ +[FBSSceneExtension initialize] : 832 -> 820
~ -[FBSProcessWatchdog invalidate] : 504 -> 500
~ _OUTLINED_FUNCTION_22 : 32 -> 12
~ _OUTLINED_FUNCTION_22 : 12 -> 32
+ _OUTLINED_FUNCTION_22
~ -[FBSWorkspaceScenesClient _queue_sendHandshake] : 1192 -> 1180
~ -[FBSWorkspaceCoupler _setWorkspace:] : 568 -> 564
- _OUTLINED_FUNCTION_35
~ ___FBSRealizeSceneExtension_block_invoke : 688 -> 676
~ -[FBSSettings _addSceneExtension:].cold.2 : 548 -> 544
~ -[FBSSceneObserver _matchesClientDiff:] : 264 -> 276
~ -[FBSSettingsDiff containsPropertyFromExtension:] : 448 -> 444
~ ___52-[FBSSettingsDiffInspector inspectDiff:withContext:]_block_invoke : 268 -> 264
~ -[FBSSettings _clearVolatileSettingsFromSettings:] : 504 -> 500
~ -[FBSScene _lock_allComponents] : 312 -> 308
~ -[FBSDisplayLayoutPublisher flush] : 680 -> 684
~ -[FBSDisplayLayout finalizeLayout] : 800 -> 796
~ -[FBSSettings _allSceneExtensions] : 1240 -> 1236
~ -[FBSDisplayMode pixelSize] : 64 -> 56
~ -[FBSScene _sendUpdate:] : 1652 -> 1644
~ -[FBSProcessWatchdog _beginMonitoringConstraints] : 368 -> 364
~ -[FBSScene _callOutQueue_addExtensions:removeExtensions:fromHost:] : 2268 -> 2256
~ ___95-[FBSScene _callOutQueue_didCreateWithTransitionContext:alternativeCreationCallout:completion:]_block_invoke : 1024 -> 1016
~ _OUTLINED_FUNCTION_36 : 32 -> 24
- _OUTLINED_FUNCTION_36
~ -[FBSScene removeObserver:] : 352 -> 348
~ __ingestPropertiesFromSettingsSubclass : 5812 -> 5808
~ -[FBSProcessWatchdog _stopMonitoringConstraints] : 328 -> 324
~ -[FBSDisplayMonitor _initWithDisplays:mainDisplay:bookendObserver:transformer:] : 1088 -> 1084
~ _OUTLINED_FUNCTION_26 : 28 -> 16
~ -[FBSDisplaySource _transformDisplaysIfNecessaryFromDisplayConfiguration:] : 644 -> 640
~ ___84-[FBSApplicationLibrary _workQueue_executeInstallSynchronizationBlocksIfAppropriate]_block_invoke : 380 -> 376
~ _OUTLINED_FUNCTION_37 : 12 -> 60
~ -[FBSDisplayMonitor updateTransformsWithCompletion:] : 416 -> 412
~ _OUTLINED_FUNCTION_29 : 16 -> 20
~ _OUTLINED_FUNCTION_29 : 36 -> 20
~ -[FBSScene sendActions:toExtension:] : 1240 -> 1236
~ -[FBSDisplayLayoutMonitor invalidate] : 332 -> 328
~ -[FBSScene updater:didReceiveActions:forExtension:] : 1944 -> 1920
~ -[FBSSceneObserver _matchesActions:] : 392 -> 388
~ -[FBSMutableSceneSettings addPropagatedSettings:] : 528 -> 524
~ _OUTLINED_FUNCTION_9 : 32 -> 36
~ -[FBSMutableSceneSettings removePropagatedSettings:] : 436 -> 432
~ +[_FBSDisplayLayoutEndpointServices _checkinService:] : 464 -> 452
~ -[FBSOpenApplicationOptions _sanitizeAndValidatePayload] : 420 -> 416
~ -[FBSScene _callOutQueue_willDestroyWithTransitionContext:completion:] : 496 -> 492
~ -[FBSScene _callOutQueue_invalidate] : 508 -> 500
+ _OUTLINED_FUNCTION_7
- _OUTLINED_FUNCTION_31
~ -[FBSDisplaySource _callOutQueue_postToObservers:includeBookendObserver:connected:] : 804 -> 796
~ _OUTLINED_FUNCTION_30 : 28 -> 16
~ _OUTLINED_FUNCTION_30 : 20 -> 12
+ _OUTLINED_FUNCTION_35
~ _FBSAllSettings : 432 -> 428
~ _FBSAllSettingsFromProtocol : 396 -> 392
~ ___31-[FBSScene addLocalExtensions:]_block_invoke : 260 -> 256
~ ___34-[FBSScene removeLocalExtensions:]_block_invoke : 260 -> 256
~ -[FBSScene _callOutQueue_didUpdateHostHandle:] : 308 -> 304
~ ___76-[FBSScene updater:didUpdateSettings:withDiff:transitionContext:completion:]_block_invoke.144 : 1036 -> 1028
~ -[FBSScene targetForInvocation:] : 384 -> 380
~ -[FBSApplicationDataStoreRepositoryClient removePrefetchedKeys:withCompletion:] : 376 -> 372
~ -[FBSApplicationDataStoreRepositoryClient _calloutQueue_handleValueChanged:] : 500 -> 496
~ -[FBSApplicationDataStoreRepositoryClient _calloutQueue_handleStoreInvalidated:] : 648 -> 644
~ -[FBSServiceFacility sendMessage:withType:toClients:] : 480 -> 476
~ ___59-[FBSApplicationPlaceholder _dispatchToObserversWithBlock:]_block_invoke : 480 -> 476
~ -[FBSWorkspaceCoupler invalidate] : 436 -> 432
~ ___42-[FBSWorkspace _invalidateWithCompletion:]_block_invoke : 360 -> 356
~ -[FBSWorkspace descriptionBuilderWithMultilinePrefix:] : 804 -> 800
~ -[FBSProcessWatchdog succinctDescriptionBuilder] : 492 -> 488
~ -[FBSDisplayConfigurationBuilder buildWithError:] : 2376 -> 2360
~ -[FBSApplicationDataStoreMonitor applicationDataStoreRepositoryClient:application:changedObject:forKey:] : 360 -> 356
~ -[FBSApplicationDataStoreMonitor applicationDataStoreRepositoryClient:storeInvalidatedForApplication:] : 340 -> 336
~ __vetProtocolMethod : 944 -> 940
~ __interfaceFromProtocol : 368 -> 364
~ +[FBSApplicationDataStore applicationsWithAvailableStores] : 316 -> 312
~ +[FBSApplicationDataStore applicationIdentitiesWithAvailableStores] : 344 -> 340
~ +[FBSApplicationDataStore applicationIdentifiersWithAvailableStoresForBundleID:] : 404 -> 400
~ -[FBSApplicationDataStore migrateWithError:] : 976 -> 972
~ ___74-[FBSWorkspaceScenesClient initWithEndpoint:queue:calloutQueue:workspace:]_block_invoke.153 : 900 -> 892
~ -[FBSApplicationPlaceholderProgress _startObservingProgress:withContext:] : 712 -> 704
~ -[FBSApplicationPlaceholderProgress _stopObservingProgress:withContext:] : 668 -> 660
~ ___57-[FBSApplicationLibrary placeholdersForBundleIdentifier:]_block_invoke : 292 -> 288
~ ___71-[FBSApplicationLibrary _notifyForType:synchronously:withCastingBlock:]_block_invoke : 396 -> 392
~ ___71-[FBSApplicationLibrary _notifyForType:synchronously:withCastingBlock:]_block_invoke_2 : 336 -> 332
~ ___30-[FBSApplicationLibrary _load]_block_invoke.182 : 456 -> 452
~ ___30-[FBSApplicationLibrary _load]_block_invoke_2 : 420 -> 416
~ ___30-[FBSApplicationLibrary _load]_block_invoke_3 : 396 -> 388
~ -[FBSApplicationLibrary applicationInstallsDidStart:] : 760 -> 756
~ ___53-[FBSApplicationLibrary applicationInstallsDidStart:]_block_invoke : 572 -> 568
~ -[FBSApplicationLibrary applicationInstallsDidChange:] : 496 -> 492
~ ___54-[FBSApplicationLibrary applicationInstallsDidChange:]_block_invoke : 580 -> 576
~ -[FBSApplicationLibrary applicationInstallsDidUpdateIcon:] : 496 -> 492
~ ___58-[FBSApplicationLibrary applicationInstallsDidUpdateIcon:]_block_invoke : 452 -> 448
~ -[FBSApplicationLibrary applicationsDidInstall:] : 1196 -> 1192
~ -[FBSApplicationLibrary applicationsDidUninstall:] : 852 -> 848
~ -[FBSApplicationLibrary applicationStateDidChange:] : 404 -> 400
~ -[FBSApplicationLibrary deviceManagementPolicyDidChange:] : 404 -> 400
~ -[FBSApplicationLibrary applicationsDidChangePersonas:] : 404 -> 400
~ -[FBSApplicationLibrary applicationInstallsArePrioritized:arePaused:] : 680 -> 672
~ -[FBSApplicationLibrary applicationInstallsDidPause:] : 384 -> 380
~ -[FBSApplicationLibrary applicationInstallsDidResume:] : 384 -> 380
~ -[FBSApplicationLibrary applicationInstallsDidCancel:] : 384 -> 380
~ -[FBSApplicationLibrary applicationInstallsDidPrioritize:] : 384 -> 380
~ -[FBSApplicationLibrary applicationsWillInstall:] : 496 -> 492
~ -[FBSApplicationLibrary applicationsDidFailToInstall:] : 496 -> 492
~ -[FBSApplicationLibrary applicationsWillUninstall:] : 496 -> 492
~ -[FBSApplicationLibrary applicationsDidFailToUninstall:] : 496 -> 492
~ _OUTLINED_FUNCTION_24 : 16 -> 12
~ _OUTLINED_FUNCTION_25 : 12 -> 28
~ _OUTLINED_FUNCTION_28 : 16 -> 28
~ _OUTLINED_FUNCTION_39 : 60 -> 12
~ _OUTLINED_FUNCTION_40 : 12 -> 44
~ _OUTLINED_FUNCTION_41 : 12 -> 16
~ _OUTLINED_FUNCTION_42 : 44 -> 16
~ _OUTLINED_FUNCTION_43 : 16 -> 24
~ _OUTLINED_FUNCTION_44 : 16 -> 12
~ _OUTLINED_FUNCTION_45 : 24 -> 12
~ _OUTLINED_FUNCTION_48 : 12 -> 28
~ _OUTLINED_FUNCTION_50 : 28 -> 24
~ _OUTLINED_FUNCTION_59 : 20 -> 12
~ _OUTLINED_FUNCTION_66 : 24 -> 32
~ _OUTLINED_FUNCTION_68 : 32 -> 24
~ _OUTLINED_FUNCTION_69 : 32 -> 24
- _OUTLINED_FUNCTION_70
~ -[_FBSSnapshot _synchronizedCaptureWithCompletion:] : 1700 -> 1696
~ -[FBSSceneObserver settingNames:] : 420 -> 416
~ -[FBSSceneObserver clientSettingNames:] : 420 -> 416
~ -[FBSSceneClientSettingsCore setLayers:] : 276 -> 272
~ -[FBSDisplayLayoutPublisher _initWithConfiguration:] : 588 -> 584
~ -[FBSSettings _addSceneExtension:applyingSettings:] : 520 -> 516
~ -[FBSSettings _removeSceneExtension:] : 700 -> 692
~ -[FBSDisplayMonitor setAllowsUnknownDisplays:] : 424 -> 420
~ -[FBSDisplayMonitor _postInitialBookendObserverConnections] : 928 -> 924
~ ___32-[FBSDisplayMonitor description]_block_invoke : 288 -> 284
~ -[FBSDisplayMonitor _lock_alwaysConnectedConfigurations] : 444 -> 440
~ ___62-[FBSDisplaySource _lock_noteUpdatedForTransformInvalidation:]_block_invoke : 1272 -> 1264
~ -[FBSWorkspaceScenesClient _queue_invalidate] : 516 -> 508
~ -[FBSApplicationLibrary _workQueue_addApplicationProxy:] : 936 -> 948
~ -[FBSApplicationLibrary _notifyDidRemoveApplications:] : 332 -> 328
~ -[FBSApplicationLibrary _notifyDidDemoteApplications:] : 332 -> 328
~ ___30-[FBSApplicationLibrary _load]_block_invoke : 2632 -> 2636
~ -[FBSApplicationLibrary _workQueue_applicationsForProxies:] : 440 -> 436
~ ___48-[FBSApplicationLibrary applicationsDidInstall:]_block_invoke : 1568 -> 1556
~ ___50-[FBSApplicationLibrary applicationsDidUninstall:]_block_invoke : 568 -> 564
~ ___94-[FBSApplicationLibrary _handleApplicationStateDidChange:notifyForUpdateInsteadOfReplacement:]_block_invoke : 2184 -> 2168
~ ___49-[FBSApplicationLibrary applicationsWillInstall:]_block_invoke : 284 -> 276
~ ___54-[FBSApplicationLibrary applicationsDidFailToInstall:]_block_invoke : 284 -> 276
~ ___51-[FBSApplicationLibrary applicationsWillUninstall:]_block_invoke : 160 -> 168
~ ___56-[FBSApplicationLibrary applicationsDidFailToUninstall:]_block_invoke : 160 -> 168
~ -[FBSDisplaySource _callOutQueue_postToObservers:includeBookendObserver:disconnected:] : 924 -> 912
~ -[FBSDisplaySource _callOutQueue_postToObservers:includeBookendObserver:updated:] : 804 -> 796
```
