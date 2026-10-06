## itunescloudd

> `/System/Library/PrivateFrameworks/iTunesCloud.framework/Support/itunescloudd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x157fe4` | `0x15c6dc` | **`+0x46f8`** |
| `__TEXT.__oslogstring` | `0x2dc50` | `0x2e906` | **`+0xcb6`** |
| `__TEXT.__objc_methname` | `0x23d4f` | `0x24438` | **`+0x6e9`** |
| `__TEXT.__objc_stubs` | `0x169a0` | `0x16e40` | **`+0x4a0`** |
| `__DATA.__objc_const` | `0x16e88` | `0x171a8` | **`+0x320`** |
| `__TEXT.__objc_methlist` | `0xbf14` | `0xc18c` | **`+0x278`** |
| `__TEXT.__gcc_except_tab` | `0x4bd8` | `0x4d58` | **`+0x180`** |
| `__TEXT.__cstring` | `0x11ae2` | `0x11c51` | **`+0x16f`** |
| `__TEXT.__objc_methtype` | `0x4acb` | `0x4c0f` | **`+0x144`** |
| `__DATA.__objc_selrefs` | `0x6b38` | `0x6c68` | **`+0x130`** |
| `__DATA_CONST.__const` | `0x63e8` | `0x6500` | **`+0x118`** |
| `__TEXT.__unwind_info` | `0x3eb8` | `0x3fb8` | **`+0x100`** |
| `__DATA.__data` | `0x1490` | `0x1548` | **`+0xb8`** |
| `__TEXT.__objc_classname` | `0x27c2` | `0x2869` | **`+0xa7`** |
| `__DATA.__objc_data` | `0x5688` | `0x5728` | **`+0xa0`** |
| `__DATA_CONST.__cfstring` | `0xcba0` | `0xcc00` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x19a0` | `0x1960` | **`-0x40`** |
| `__DATA.__objc_ivar` | `0xed8` | `0xf00` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0xce0` | `0xcc0` | **`-0x20`** |
| `__DATA_CONST.__auth_ptr` | `0xd0` | `0xb8` | **`-0x18`** |
| `__DATA.__bss` | `0x728` | `0x738` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x890` | `0x8a0` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x198` | `0x1a8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x618` | `0x628` | **`+0x10`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4026.110.1.0.0
+4026.200.13.0.0

-  Functions: 5474
-  Symbols:   1030
-  CStrings:  9784
+  Functions: 5542
+  Symbols:   1025
+  CStrings:  9879
Symbols:
+ _$s18AppIntentsServices0bC0O15localDispatcher11clientLabel6source11environment7optionsAA0A17IntentDispatching_pSS_So24LNTranscriptActionSourceVAA0aK11Environment_pAC14OptionsBuilderVy_AC0eQ0VGdtFZ
+ _OBJC_CLASS_$_NSMutableIndexSet
- _$s18AppIntentsServices0bC0O14InterfaceIdiomO23defaultForCurrentDeviceAESgvgZ
- _$s18AppIntentsServices0bC0O14InterfaceIdiomOMa
- _$s18AppIntentsServices0bC0O14PayloadPrivacyO7defaultyA2EmFWC
- _$s18AppIntentsServices0bC0O14PayloadPrivacyOMa
- _$s18AppIntentsServices0bC0O15localDispatcher11clientLabel6source11environment7optionsAA0A17IntentDispatching_pSS_So24LNTranscriptActionSourceVAA0aK11Environment_pAC0E7OptionsVtFZ
- _$s18AppIntentsServices0bC0O17DispatcherOptionsV14interfaceIdiom14payloadPrivacyAeC09InterfaceG0OSg_AC07PayloadI0OtcfC
- _$s18AppIntentsServices0bC0O17DispatcherOptionsVMa
CStrings:
+ "%{public}@ - enqueueing monitored entity import channelID=%{public}@"
+ "%{public}@ - finished with error=%{public}@, stashedResponsePath=%{public}@"
+ "%{public}@ - not enqueueing monitored entity import; no SagaRequestHandler channelID=%{public}@"
+ "%{public}@ - running SagaCloudMonitoredEntityImportOperation channelID=%{public}@"
+ "%{public}@ - sending cloud library item updates request<%{public}@: %p>"
+ "%{public}@ - starting monitored entity import operation for message=%{public}@"
+ "%{public}@ updating opportunistic enabled topics from %{public}@ to %{public}@"
+ "<%@: %p method=%@ sagaIDs.count=%lu>"
+ "@\"<CloudChannelLibraryUpdateCoordinatorDelegate>\""
+ "@\"<CloudChannelLibraryUpdateCoordinatorRegistry>\""
+ "@\"NSDictionary\"24@0:8@\"NSArray\"16"
+ "CloudChannelItemUpdate"
+ "CloudChannelLibraryUpdateCoordinator"
+ "CloudChannelLibraryUpdateCoordinator - arming pending-import timer fireTime=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - arming scheduled-update timer fireTime=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - cancelled pending imports channelID=%{public}@ dsid=%{public}@ count=%lu"
+ "CloudChannelLibraryUpdateCoordinator - disarming pending-import timer"
+ "CloudChannelLibraryUpdateCoordinator - disarming scheduled-update timer"
+ "CloudChannelLibraryUpdateCoordinator - discarding fetched response; channelID no longer subscribed channelID=%{public}@ dsid=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - dropping malformed pending import channelID=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - dropping malformed scheduled update channelID=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - dropping pending import with no subscriber channelID=%{public}@ dsid=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - dropping pending import; stash missing channelID=%{public}@ path=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - dropping pending imports for %lu channels; feature not enabled"
+ "CloudChannelLibraryUpdateCoordinator - dropping scheduled updates for %lu channels; feature not enabled"
+ "CloudChannelLibraryUpdateCoordinator - evicting least imminent pending-import entry channelID=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - evicting least imminent scheduled-update entry channelID=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - fetch failed channelID=%{public}@ dsid=%{public}@ err=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - firing pending import channelID=%{public}@ dsid=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - firing scheduled update channelID=%{public}@ dsid=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - holding pending imports for %lu channels until configured"
+ "CloudChannelLibraryUpdateCoordinator - holding scheduled updates for %lu channels until configured"
+ "CloudChannelLibraryUpdateCoordinator - no configuration for pending import dsid=%{public}@ channelID=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - no delegate to notify about push handling channelID=%{public}@ dsid=%{public}@ err=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - no subscribers for channelID=%{public}@; dropping %lu scheduled update(s)"
+ "CloudChannelLibraryUpdateCoordinator - not recording pending import; channelID=%{public}@ at per-channel limit"
+ "CloudChannelLibraryUpdateCoordinator - not recording pending import; failed to archive channelID=%{public}@ err=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - not scheduling duplicate update channelID=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - not scheduling update; channelID=%{public}@ at per-channel limit"
+ "CloudChannelLibraryUpdateCoordinator - not scheduling update; failed to archive channelID=%{public}@ err=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - not scheduling update; pending import exists channelID=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - purged pending imports for channels=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - purged scheduled updates for channels=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - recording pending import channelID=%{public}@ dsid=%{public}@ goLive=%{public}@ fireTime=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator - scheduling update channelID=%{public}@ fireTime=%{public}@"
+ "CloudChannelLibraryUpdateCoordinator.pendingImports"
+ "CloudChannelLibraryUpdateCoordinator.scheduledUpdates"
+ "CloudChannelLibraryUpdateCoordinatorDelegate"
+ "CloudChannelLibraryUpdateCoordinatorRegistry"
+ "DSIDsByChannelIDForChannels:"
+ "ICDCloudAPNSChannelRegistry - push handling finished channelID=%{public}@ dsid=%{public}@ err=%{public}@"
+ "SagaCloudMonitoredEntityImportOperation"
+ "SagaCloudMonitoredEntityImportOperation - import complete channelID=%{public}@ success=%{BOOL}u"
+ "SagaCloudMonitoredEntityImportOperation - import complete channelID=%{public}@ success=%{BOOL}u error=%{public}@"
+ "SagaCloudMonitoredEntityImportOperation - no import data channelID=%{public}@ path=%{public}@"
+ "SagaCloudMonitoredEntityImportOperation - not running; feature unavailable channelID=%{public}@"
+ "SagaCloudMonitoredEntityImportOperation - not running; invalid args pushMessage=%{public}@ cloudUpdateResponsePath=%{public}@"
+ "SagaCloudMonitoredEntityImportOperation - not running; stash missing channelID=%{public}@ path=%{public}@"
+ "SagaCloudMonitoredEntityImportOperation - starting import channelID=%{public}@"
+ "T@\"<CloudChannelLibraryUpdateCoordinatorDelegate>\",W,V_delegate"
+ "T@\"<CloudChannelLibraryUpdateCoordinatorRegistry>\",W,V_registry"
+ "T@\"NSString\",R,C,N,V_stashedResponsePath"
+ "_cancelPendingImportsForChannelID:DSID:error:"
+ "_cloudUpdateResponsePath"
+ "_dropPendingImportForPushMessage:DSID:"
+ "_dropPendingImportsMatchingPushMessage:DSID:inEntries:"
+ "_dropScheduledUpdateForPushMessage:"
+ "_earliestFireTimeForMap:"
+ "_enforceCacheLimitForMap:"
+ "_enqueueFetchForPushMessage:toDSIDs:accountManager:"
+ "_enqueueImportForPushMessage:cloudUpdateResponsePath:DSID:accountManager:"
+ "_fireDelegateForPushMessage:DSID:error:"
+ "_fireDueImports"
+ "_fireDueUpdates"
+ "_handleFetchCompletionForPushMessage:DSID:error:cloudUpdateResponsePath:"
+ "_handleImportCompletionForPushMessage:DSID:error:"
+ "_importBackstopFireTimeSeconds"
+ "_importTimer"
+ "_loadEntriesForDefaultsKey:"
+ "_pendingImports"
+ "_purgePendingImportsForChannelIDs:"
+ "_purgeScheduledUpdatesForChannelIDs:"
+ "_pushMessage:isAlreadyScheduledInEntries:"
+ "_pushMessageFromEntry:"
+ "_reconcileImports"
+ "_reconcileUpdates"
+ "_recordPendingImportForPushMessage:cloudUpdateResponsePath:DSID:"
+ "_registry"
+ "_sanitizedEntryFromStoredEntry:"
+ "_savePendingImports"
+ "_saveScheduledUpdates"
+ "_scheduleUpdateForPushMessage:"
+ "_scheduledUpdates"
+ "_setBackstop:tracked:toFireAt:"
+ "_setOpportunisticTopics:"
+ "_setTimer:toFireAt:"
+ "_stashedResponsePath"
+ "_updateBackstopFireTimeSeconds"
+ "_updateTimer"
+ "addIndex:"
+ "cloudChannelSubscriptionsRegistrationOffsetsChanged:"
+ "cloudUpdateResponsePath"
+ "com.apple.itunescloudd.CloudChannelLibraryUpdateCoordinator.state"
+ "com.apple.itunescloudd.SagaRequestHandler.cloudMonitoredEntityImportOperation"
+ "com.apple.itunescloudd.cloud-channel-import-backstop"
+ "configureWithRegistry:accountManager:delegate:"
+ "coordinator:didFinishHandlingPushMessage:forDSID:error:"
+ "enqueueLibraryUpdateForPushMessage:completionHandler:"
+ "enqueueMonitoredEntityImportForPushMessage:cloudUpdateResponsePath:completionHandler:"
+ "enqueueMonitoredEntityImportOperationForPushMessage:cloudUpdateResponsePath:clientIdentity:completionHandler:"
+ "fireDueUpdates"
+ "handlersDidCompleteInitialReporting"
+ "indexSet"
+ "initWithConfiguration:clientIdentity:pushMessage:cloudUpdateResponsePath:"
+ "initWithLibraryPath:trackData:playlistData:albumArtistData:albumData:libraryPinsData:albumCloudChannelID:isDeferredItemUpdateImport:clientIdentity:"
+ "libraryChannelsDidChangeForDSID:added:removed:"
+ "opportunisticTopics"
+ "purgeAllUpdates"
+ "purgeUpdatesForChannelIDs:"
+ "registry"
+ "removeObjectsAtIndexes:"
+ "scheduleLibraryUpdateForPushMessage:"
+ "setFailureCount:"
+ "setRegistry:"
+ "stashedResponsePath"
+ "v24@?0@\"NSError\"8@\"NSString\"16"
+ "v32@?0@\"NSDictionary\"8Q16^B24"
+ "v40@0:8@16^d24d32"
+ "v48@0:8@\"CloudChannelLibraryUpdateCoordinator\"16@\"ICCloudAPNSChannelPushMessage\"24@\"NSNumber\"32@\"NSError\"40"
+ "v48@0:8@\"NSArray\"16@\"NSArray\"24@\"NSNumber\"32@?<v@?@\"NSError\">40"
+ "\x83"
+ "\xe2"
- "%{public}@ - sending cloud library item updates request <%{public}@: %p method=%{public}@ action=%{public}@>"
- "<%@: %p sagaIDs.count=%lu>"
- "ICDCloudAPNSChannelRegistry - arming backstop fireTime=%{public}@"
- "ICDCloudAPNSChannelRegistry - arming timer for earliest update fireTime=%{public}@ leadTime=%.1fs pendingCount=%lu"
- "ICDCloudAPNSChannelRegistry - cancelling backstop"
- "ICDCloudAPNSChannelRegistry - dropping scheduled library update; failed to decode channelID=%{public}@"
- "ICDCloudAPNSChannelRegistry - dropping scheduled library updates for %lu channels; feature not enabled"
- "ICDCloudAPNSChannelRegistry - evicting least imminent scheduled library update channelID=%{public}@"
- "ICDCloudAPNSChannelRegistry - firing scheduled library update channelID=%{public}@ dsid=%{public}@"
- "ICDCloudAPNSChannelRegistry - holding scheduled library updates for %lu channels until the daemon is configured"
- "ICDCloudAPNSChannelRegistry - no scheduled library update to arm; disarming timer pendingCount=%lu"
- "ICDCloudAPNSChannelRegistry - no subscribers for channelID=%{public}@; dropping %lu update(s)"
- "ICDCloudAPNSChannelRegistry - not scheduling duplicate library update channelID=%{public}@"
- "ICDCloudAPNSChannelRegistry - not scheduling update; channelID=%{public}@ at per-channel limit"
- "ICDCloudAPNSChannelRegistry - not scheduling update; failed to archive channelID=%{public}@ err=%{public}@"
- "ICDCloudAPNSChannelRegistry - scheduling library update channelID=%{public}@ fireTime=%{public}@"
- "ICDCloudAPNSChannelRegistry.pendingChannelUpdates"
- "Store"
- "System"
- "_backstopFireTimeSeconds"
- "_enforceScheduledLibraryUpdateCacheLimit"
- "_entryFromStoredEntry:"
- "_fanOutLibraryUpdate:toDSIDs:accountManager:"
- "_fireDueScheduledLibraryUpdates"
- "_loadScheduledLibraryUpdates"
- "_pushMessageAlreadyScheduled:inEntries:"
- "_reconcileScheduledLibraryUpdates"
- "_saveScheduledLibraryUpdates"
- "_scheduleLibraryUpdateForPushMessage:"
- "_scheduledLibraryUpdateTimer"
- "_scheduledLibraryUpdates"
- "_soonestFireTimeForChannelID:"
- "cloud-library-item-updates.daap"
- "enqueueLibraryUpdateForPushMessage:"
- "setShouldExcludeFromBackgroundRefresh:"
- "shouldExcludeFromBackgroundRefresh"
- "\xf02"
```
