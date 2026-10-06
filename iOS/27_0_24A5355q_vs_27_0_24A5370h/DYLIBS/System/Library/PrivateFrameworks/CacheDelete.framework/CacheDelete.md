## CacheDelete

> `/System/Library/PrivateFrameworks/CacheDelete.framework/CacheDelete`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x368bc` | `0x36818` | **`-0xa4`** |
| `__TEXT.__oslogstring` | `0x6081` | `0x60bf` | **`+0x3e`** |

### Other Changes

```diff

-901.0.0.0.1
+904.0.0.0.0

-  CStrings:  885
+  CStrings:  886
Functions:
~ _CallBlockWithProxy : 1848 -> 1844
~ _queryCache : 4532 -> 4508
~ _getSiblings : 716 -> 712
~ -[CDRecentInfo initWithRecentInfo:] : 540 -> 536
~ _connectionIsEntitled : 1104 -> 1100
~ -[CacheDeleteServiceListener servicePurgeable:info:replyBlock:] : 916 -> 912
~ ____CacheDeleteEnumerateRemovedFiles_block_invoke.84 : 4860 -> 4848
~ ___80+[AppCache enumerateWithContainerQuery:container_class:options:telemetry:block:]_block_invoke : 1996 -> 1988
~ _recentlyUsedAppsDictionary : 724 -> 720
~ +[AppCache enumerateGroupCachesOnVolume:block:] : 896 -> 892
~ ___89+[AppCache sortedCachesForInstalledAppsOnVolume:urgency:calculate:bytesNeeded:telemetry:]_block_invoke : 1236 -> 1228
~ __logPurgeableResults : 1256 -> 1248
~ -[CDRecentVolumeInfo _recentInfoAtUrgency:validateResults:] : 3932 -> 3928
~ -[CDPurgeableResultCache recentInfoForVolumes:atUrgency:validateResults:targetVolume:] : 884 -> 868
~ -[CDRecentVolumeInfo copyInvalidsAtUrgency:currentlyPushing:] : 828 -> 824
~ -[CDRecentServiceInfo description] : 568 -> 572
~ -[CDRecentVolumeInfo initWithVolumeInfo:] : 1144 -> 1132
~ -[CDRecentVolumeInfo description] : 472 -> 468
~ -[CDRecentInfo description] : 472 -> 468
~ -[AppCache addBundleRecords:] : 244 -> 240
~ _fetchAllPersonas : 496 -> 492
~ +[CacheDeleteVolume volumeWithUUID:] : 380 -> 376
~ _enumerateUserManagedAssetsOnVolume : 1504 -> 1500
~ +[CacheManagementAsset assetFromPath:withIdentifier:createIfAbsent:] : 2648 -> 2644
~ ___57-[CDPurgeableResultCache invalidateAllForgettingPushers:]_block_invoke : 536 -> 528
~ -[CDRecentInfo removeServiceInfo:] : 276 -> 272
~ -[CDRecentInfo isStale] : 344 -> 340
~ -[CDRecentInfo log] : 408 -> 404
~ -[CDRecentServiceInfo updateAmount:atUrgency:withTimestamp:nonPurgeableAmount:deductFromCurrentAmount:info:] : 484 -> 472
~ -[CDRecentServiceInfo isEmpty] : 48 -> 56
~ -[CDRecentVolumeInfo log] : 552 -> 548
~ -[CacheDeleteServiceListener servicePurge:info:replyBlock:] : 1180 -> 1172
~ _getbacktrace : 444 -> 432
~ _getbacktrace_short : 376 -> 372
~ _volumeForUUID : 412 -> 408
~ _getLocalVolumeUUIDs : 340 -> 336
~ _lowSpaceVolumes : 876 -> 872
~ _tallyDict : 588 -> 584
~ _CacheDeleteRegisterPurgeNotification : 948 -> 944
~ _CacheDeleteCopyPurgeHistory : 1464 -> 1460
~ ___35-[CDRemoveEventsConsumer callback:]_block_invoke : 1116 -> 1208
~ _fsEventStreamCallback : 2060 -> 2028
CStrings:
+ "Got a zero historyDone event, using FSEventsGetCurrentEventId: %llu, event: %@"
+ "historyDone matched _since (%llu); advancing marker to %llu"
- "Got a zero historyDone event, using FSEventsGetCurrentEventId: %@, event: %@"
```
