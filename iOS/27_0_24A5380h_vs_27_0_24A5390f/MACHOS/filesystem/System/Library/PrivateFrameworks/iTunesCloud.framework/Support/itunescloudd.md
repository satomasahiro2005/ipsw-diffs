## itunescloudd

> `/System/Library/PrivateFrameworks/iTunesCloud.framework/Support/itunescloudd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1491b8` | `0x14a0e8` | **`+0xf30`** |
| `__TEXT.__oslogstring` | `0x2b1bd` | `0x2b6b9` | **`+0x4fc`** |
| `__TEXT.__objc_stubs` | `0x15c00` | `0x15de0` | **`+0x1e0`** |
| `__TEXT.__objc_methname` | `0x22a5e` | `0x22c05` | **`+0x1a7`** |
| `__DATA_CONST.__cfstring` | `0xc8a0` | `0xc980` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x11867` | `0x11919` | **`+0xb2`** |
| `__DATA_CONST.__const` | `0x6148` | `0x61f8` | **`+0xb0`** |
| `__DATA.__objc_selrefs` | `0x67b8` | `0x6830` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0x4998` | `0x49d0` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0xb98c` | `0xb9b4` | **`+0x28`** |
| `__DATA.__bss` | `0x6e8` | `0x6f8` | **`+0x10`** |
| `__DATA.__objc_const` | `0x16700` | `0x16710` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1170` | `0x1180` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3ca8` | `0x3cb8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4026.100.72.0.0
+4026.110.81.1.0

+  - /System/Library/PrivateFrameworks/BackgroundSystemTasks.framework/BackgroundSystemTasks

-  Functions: 5318
-  Symbols:   1013
-  CStrings:  9471
+  Functions: 5325
+  Symbols:   1015
+  CStrings:  9509
Symbols:
+ _$s16MusicKitInternal0A22ConcertsRankingServiceV26sendNotificationCandidates_014forgetNotifiedD0ySDySSypG_SbtYaKF
+ _$s16MusicKitInternal0A22ConcertsRankingServiceV26sendNotificationCandidates_014forgetNotifiedD0ySDySSypG_SbtYaKFTu
+ _$s18AppIntentsServices0A20IntentPerformOptionsV19allowLiveActivities019allowsPrepareBeforeE024assistantDismissalPolicy21confirmationCondition26connectionOperationTimeout18donateToTranscript19executionIdentifier19exportedContentType15interactionMode4kind015preferredBundleY024preferNoticePresentation21requestUnlockIfNeeded18snippetEnvironmentACSb_SbSo011LNAssistantnO0VSgSo029LNActionExecutionConfirmationQ0VSdSbSg10Foundation4UUIDVSg22UniformTypeIdentifiers6UTTypeVSgSo17LNInteractionModeVSo22LNTranscriptActionKindVSSSgS2bAA18SnippetEnvironmentVSgtcfC
+ _OBJC_CLASS_$_BGRepeatingSystemTaskRequest
+ _OBJC_CLASS_$_BGSystemTaskScheduler
- _$s16MusicKitInternal0A22ConcertsRankingServiceV26sendNotificationCandidatesyySDySSypGYaKF
- _$s16MusicKitInternal0A22ConcertsRankingServiceV26sendNotificationCandidatesyySDySSypGYaKFTu
- _$s18AppIntentsServices0A20IntentPerformOptionsV19allowLiveActivities019allowsPrepareBeforeE024assistantDismissalPolicy26connectionOperationTimeout18donateToTranscript19executionIdentifier19exportedContentType15interactionMode4kind015preferredBundleW024preferNoticePresentation21requestUnlockIfNeeded18snippetEnvironmentACSb_SbSo011LNAssistantnO0VSgSdSbSg10Foundation4UUIDVSg07UniformZ11Identifiers6UTTypeVSgSo17LNInteractionModeVSo22LNTranscriptActionKindVSSSgS2bAA18SnippetEnvironmentVSgtcfC
CStrings:
+ "%@ (%@)"
+ "Album with storeItemId: %lld, albumPid: %lld, liked_state: %{public}@ is imported and has the correct liked state"
+ "Container with PlaylistGlobalId: %@, persistentID: %lld, liked_state: %{public}@ is imported and has the correct liked state"
+ "Disliked"
+ "Failed to cancel existing task. err=%{public}@"
+ "Finished subscribed container update"
+ "Finished subscribed container update error=%{public}@"
+ "ICDDefaultsKeyShouldUpdateAllSubscribedPlaylists"
+ "Liked"
+ "None"
+ "Track with storeItemID: %lld, subscriptionStoreItemID: %lld, persistenID: %lld, liked_state: %{public}@ for property: %@ is imported and has the correct liked state"
+ "Unrecognized(%ld)"
+ "[Subscribed-Containers] Cancelling existing subscribed-containers refresh task because the interval has changed from %f --> %f"
+ "[Subscribed-Containers] Cancelling subscribed-containers refresh because there's no active user or cloud library is not enabled"
+ "[Subscribed-Containers] Failed to cancel existing task. err=%{public}@"
+ "[Subscribed-Containers] Failed to register a task handler for subscribed container refresh"
+ "[Subscribed-Containers] Failed to submit new task. err=%{public}@"
+ "[Subscribed-Containers] No active configuration - skipping update"
+ "[Subscribed-Containers] Not scheduling subscribed-containers refresh because its disabled in the bag"
+ "[Subscribed-Containers] Not scheduling subscribed-containers refresh because the initial sync hasn't happened yet"
+ "[Subscribed-Containers] Not scheduling subscribed-containers refresh because we couldn't load the active locker account"
+ "[Subscribed-Containers] Not updating subscribed playlists since it hasn't been requested by the music app"
+ "[Subscribed-Containers] Scheduling new periodic refresh task at interval %f"
+ "[Subscribed-Containers] Scheduling periodic refresh of subscribed containers"
+ "[Subscribed-Containers] Skipping scheduling the subscribed-containers refresh because we failed to load the bag. err=%{public}@"
+ "[Subscribed-Containers] Updating all subscribed containers from periodic task..."
+ "_scheduleSubscribedPlaylistRefresh"
+ "cancelTaskRequestWithIdentifier:error:"
+ "com.apple.itunescloudd.ICDServer.subscribedPlaylistsRefresh"
+ "initWithIdentifier:"
+ "interval"
+ "registerForTaskWithIdentifier:usingQueue:launchHandler:"
+ "setInterval:"
+ "setRelatedApplications:"
+ "setRequiresExternalPower:"
+ "setShouldUpdateAllSubscribedPlaylists:"
+ "setTaskCompleted"
+ "sharedScheduler"
+ "shouldUpdateAllSubscribedPlaylists"
+ "submitTaskRequest:error:"
+ "subscribedContainerPollingFrequencySeconds"
+ "taskRequestForIdentifier:"
+ "v16@?0@\"BGSystemTask\"8"
- "Album with storeItemId: %lld, albumPid: %lld, liked_state: %lld is imported and has the correct liked state"
- "Container with PlaylistGlobalId: %@, persistentID: %lld, liked_state: %lld is imported and has the correct liked state"
- "Track with storeItemID: %lld, subscriptionStoreItemID: %lld, persistenID: %lld, liked_state: %d for property: %@ is imported and has the correct liked state"
- "[BecomeActive::Cloud] Skipped cloud library update, updating all subscribed containers now (not ignoring min refresh interval)..."
- "[BecomeActive::Cloud] Update saga library completed successfully, updating all subscribed containers..."
```
