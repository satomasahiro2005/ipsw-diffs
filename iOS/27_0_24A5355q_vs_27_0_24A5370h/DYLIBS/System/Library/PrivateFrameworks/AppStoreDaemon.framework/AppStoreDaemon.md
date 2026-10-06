## AppStoreDaemon

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/AppStoreDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x82fa8` | `0x82f9c` | **`-0xc`** |
| `__TEXT.__unwind_info` | `0x2788` | `0x2790` | **`+0x8`** |

### Other Changes

```diff

-13.0.33.0.0
+13.0.36.0.0
Functions:
~ _safeUserInfoValue : 1368 -> 1364
~ -[ASDAppQuery _updateCachedResultsWithResults:] : 2672 -> 2668
~ -[ASDAppQuery _removeCachedResultsForBundleIDs:] : 628 -> 624
~ -[ASDAppQuery _handleQueryOptionsWithResults:] : 256 -> 252
~ ___51-[ASDAppQuery notificationCenter:receivedProgress:]_block_invoke : 2516 -> 2496
~ ___55-[ASDAppStoreService _refreshCache:sendActionResponse:]_block_invoke_3 : 1924 -> 1908
~ -[ASDUpdateMetricsStore init] : 788 -> 772
~ -[ASDUpdateMetricsStore synchronize] : 436 -> 432
~ -[ASDAppCapabilities _isCapable:method:] : 1368 -> 1364
~ -[ASDAggregateClusterMappingData writeTo:] : 604 -> 584
~ ___27-[ASDApp setRawUpdateData:]_block_invoke : 12 -> 80
~ ___39-[ASDApp updateCodedPropertiesFromApp:]_block_invoke : 496 -> 564
~ -[ASDApp copyWithZone:] : 920 -> 968
~ +[ASDUpdatesService areAllAppsAuthorizedForAutomaticUpdates] : 884 -> 876
~ -[ASDUpdatesService _failedJobResultsForBundleIDs:] : 460 -> 456
~ +[ASDInstallApps _installApps:onDeviceWithPairingID:withCompletionHandler:] : 1136 -> 1132
~ ___57-[ASDSoftwareUpdatesStore getUpdatesWithCompletionBlock:]_block_invoke_3 : 40 -> 36
~ +[ASDCoding _findNonSecureClassesFromObject:] : 804 -> 800
~ -[ASDCellularIdentity initWithSIMIdentity:roaming:] : 360 -> 368
~ ___46-[ASDNotificationCenter deliverNotifications:]_block_invoke : 476 -> 472
~ ___46-[ASDNotificationCenter deliverNotifications:]_block_invoke_3 : 276 -> 272
~ ___41-[ASDNotificationCenter deliverProgress:]_block_invoke : 972 -> 968
~ ___41-[ASDNotificationCenter deliverProgress:]_block_invoke_2 : 276 -> 272
~ -[ASDRequestBroker description] : 392 -> 388
~ ___31-[ASDPromise resolveWithValue:]_block_invoke : 356 -> 352
~ ___30-[ASDPromise rejectWithError:]_block_invoke : 356 -> 352
~ -[ASDPurchase firstValueForBuyParameter:] : 344 -> 340
~ -[ASDJobManager finishJobs:] : 476 -> 472
~ ___31-[ASDJobManager didChangeJobs:]_block_invoke : 532 -> 528
~ ___45-[ASDJobManager didCompleteJobs:finalPhases:]_block_invoke : 672 -> 668
~ -[ASDJobManager _mapAllJobsToIDs] : 576 -> 568
~ -[ASDJobManager _applyUpdates:usingBlock:] : 936 -> 932
~ ___46-[ASDJobManager applicationInstallsDidChange:]_block_invoke : 584 -> 580
~ ___42-[ASDJobManager _applyUpdates:usingBlock:]_block_invoke : 176 -> 172
~ ___44-[ASDJobManager _getJobsWithIDs:usingBlock:]_block_invoke_3 : 656 -> 652
~ ___34-[ASDJobManager _sendJobsChanged:]_block_invoke : 292 -> 288
~ ___36-[ASDJobManager _sendJobsCompleted:]_block_invoke : 292 -> 288
~ ___38-[ASDJobManager _sendProgressUpdated:]_block_invoke : 292 -> 288
~ ___34-[ASDJobManager _updateActiveIDs:]_block_invoke : 720 -> 716
~ +[ASDGatherLogsRequest clearHARFiles] : 428 -> 424
~ -[ASDGatherLogsRequest _combineAllLogs] : 1504 -> 1500
~ -[ASDGatherLogsRequest _copyDB:fullSourcePath:toDir:datbaseBase:] : 812 -> 808
~ -[ASDGatherLogsRequest _createCombinedHarFile] : 1948 -> 1940
~ sub_1cdf83228 -> sub_1ce80a208 : 832 -> 836
~ sub_1cdf83568 -> sub_1ce80a54c : 116 -> 132
```
