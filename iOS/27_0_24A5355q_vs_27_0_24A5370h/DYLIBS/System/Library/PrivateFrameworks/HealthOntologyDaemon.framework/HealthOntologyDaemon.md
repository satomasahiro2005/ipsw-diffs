## HealthOntologyDaemon

> `/System/Library/PrivateFrameworks/HealthOntologyDaemon.framework/HealthOntologyDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d980` | `0x2d32c` | **`-0x654`** |
| `__AUTH_CONST.__objc_const` | `0x3d50` | `0x3f20` | **`+0x1d0`** |
| `__AUTH_CONST.__cfstring` | `0x2380` | `0x2220` | **`-0x160`** |
| `__TEXT.__oslogstring` | `0x1c6a` | `0x1d5a` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x342c` | `0x33bc` | **`-0x70`** |
| `__AUTH.__objc_data` | `0xf0` | `0x140` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x430` | `0x3e0` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xc80` | `0xc30` | **`-0x50`** |
| `__AUTH_CONST.__auth_got` | `0x4e0` | `0x4a0` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x1950` | `0x1978` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x1d0` | `0x1e8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1810` | `0x1828` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xe50` | `0xe68` | **`+0x18`** |
| `__TEXT.__const` | `0x272` | `0x282` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x219c` | `0x21ac` | **`+0x10`** |
| `__DATA_CONST.__objc_catlist` | `0x50` | `0x58` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xf0` | `0xf8` | **`+0x8`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

+  - /System/Library/PrivateFrameworks/BackgroundSystemTasks.framework/BackgroundSystemTasks

-  Functions: 1091
-  Symbols:   2141
-  CStrings:  457
+  Functions: 1093
+  Symbols:   2137
+  CStrings:  451
Symbols:
+ +[HDOntologyManifestUpdater _downloadManifestWithEntry:session:updateCoordinator:cancellationHandler:completion:]
+ +[HDOntologyManifestUpdater _updateManifestWithEntry:session:updateCoordinator:cancellationHandler:completion:]
+ +[HDOntologyUpdateCoordinator _errorForCompletedGatedActivityResult:error:]
+ -[HDOntologyManifestUpdater updateManifestWithURL:session:cancellationHandler:completion:]
+ -[HDOntologyShardDownloader _downloadFilesForEntries:session:cancellationHandler:completion:]
+ -[HDOntologyShardDownloader _downloadRequiredShardFilesWithSession:requiredEntries:cancellationHandler:completion:]
+ -[HDOntologyShardDownloader downloadRequiredShardFilesWithSession:cancellationHandler:completion:]
+ -[HDOntologyUpdateCancellationHandler .cxx_destruct]
+ -[HDOntologyUpdateCancellationHandler addCancellable:]
+ -[HDOntologyUpdateCancellationHandler cancel]
+ -[HDOntologyUpdateCancellationHandler init]
+ -[HDOntologyUpdateCancellationHandler isCancelled]
+ -[HDOntologyUpdateCoordinator _enqueueUpdateOntologyWithReason:cancellationHandler:completion:]
+ -[HDOntologyUpdateCoordinator _makeFallbackTaskWithScheduler:]
+ -[HDOntologyUpdateCoordinator _makeGatedTaskWithScheduler:]
+ -[HDOntologyUpdateCoordinator _makeOneShotTaskWithIdentifier:reason:scheduler:]
+ -[HDOntologyUpdateCoordinator _makePeriodicTaskWithScheduler:]
+ -[HDOntologyUpdateCoordinator _runOntologyUpdateForOneShotTask:reason:completion:]
+ -[HDOntologyUpdateCoordinator _runOntologyUpdateForRepeatingTask:reason:completion:]
+ -[HDOntologyUpdateCoordinator _runOntologyUpdateWithReason:cancellationHandler:completion:]
+ -[HDOntologyUpdateCoordinator _runOntologyUpdateWithShouldDefer:addExpirationHandler:reason:activityName:completion:]
+ -[HDOntologyUpdateCoordinator _updateOntologyWithReason:updateID:cancellationHandler:completion:]
+ -[HDOntologyUpdateCoordinator initWithDaemon:scheduler:]
+ -[HDOntologyUpdateCoordinator invalidate]
+ -[HDOntologyUpdateCoordinator setUnitTesting_willStartShardDownloadPhase:]
+ -[HDOntologyUpdateCoordinator unitTesting_runOntologyUpdateWithShouldDefer:addExpirationHandler:reason:activityName:completion:]
+ -[HDOntologyUpdateCoordinator unitTesting_updateOntologyWithReason:cancellationHandler:completion:]
+ -[HDOntologyUpdateCoordinator unitTesting_willStartShardDownloadPhase]
+ -[_HDOntologyDownloadTask initForDownloader:session:queue:cancellationHandler:]
+ -[_HDOntologyShardDownloadTask initForEntry:downloader:session:group:cancellationHandler:]
+ GCC_except_table79
+ _OBJC_CLASS_$_BGNonRepeatingSystemTaskRequest
+ _OBJC_CLASS_$_BGRepeatingSystemTaskRequest
+ _OBJC_CLASS_$_HDOneShotBackgroundTask
+ _OBJC_CLASS_$_HDOntologyUpdateCancellationHandler
+ _OBJC_CLASS_$_HDRepeatingBackgroundTask
+ _OBJC_CLASS_$_NSHashTable
+ _OBJC_CLASS_$_NSURLSessionTask
+ _OBJC_IVAR_$_HDOntologyUpdateCancellationHandler._lock
+ _OBJC_IVAR_$_HDOntologyUpdateCancellationHandler._lock_cancellables
+ _OBJC_IVAR_$_HDOntologyUpdateCancellationHandler._lock_cancelled
+ _OBJC_IVAR_$_HDOntologyUpdateCoordinator._fallbackTask
+ _OBJC_IVAR_$_HDOntologyUpdateCoordinator._gatedTask
+ _OBJC_IVAR_$_HDOntologyUpdateCoordinator._periodicTask
+ _OBJC_IVAR_$_HDOntologyUpdateCoordinator._unitTesting_willStartShardDownloadPhase
+ _OBJC_IVAR_$__HDOntologyDownloadTask._cancellationHandler
+ _OBJC_IVAR_$__HDOntologyShardDownloadTask._cancellationHandler
+ _OBJC_METACLASS_$_HDOntologyUpdateCancellationHandler
+ _OUTLINED_FUNCTION_14
+ _OUTLINED_FUNCTION_15
+ _OUTLINED_FUNCTION_16
+ __OBJC_$_CATEGORY_NSURLSessionTask_$_HDOntologyUpdateCancellable
+ __OBJC_$_CLASS_METHODS_HDOntologyUpdateCoordinator
+ __OBJC_$_INSTANCE_METHODS_HDOntologyUpdateCancellationHandler
+ __OBJC_$_INSTANCE_VARIABLES_HDOntologyUpdateCancellationHandler
+ __OBJC_$_PROP_LIST_HDOntologyUpdateCancellationHandler
+ __OBJC_$_PROP_LIST_NSURLSessionTask_$_HDOntologyUpdateCancellable
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HDOntologyUpdateCancellable
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HDOntologyUpdateCancellable
+ __OBJC_$_PROTOCOL_REFS_HDOntologyUpdateCancellable
+ __OBJC_CATEGORY_PROTOCOLS_$_NSURLSessionTask_$_HDOntologyUpdateCancellable
+ __OBJC_CLASS_PROTOCOLS_$_HDOntologyUpdateCancellationHandler
+ __OBJC_CLASS_RO_$_HDOntologyUpdateCancellationHandler
+ __OBJC_LABEL_PROTOCOL_$_HDOntologyUpdateCancellable
+ __OBJC_METACLASS_RO_$_HDOntologyUpdateCancellationHandler
+ __OBJC_PROTOCOL_$_HDOntologyUpdateCancellable
+ ___111+[HDOntologyManifestUpdater _updateManifestWithEntry:session:updateCoordinator:cancellationHandler:completion:]_block_invoke
+ ___113+[HDOntologyManifestUpdater _downloadManifestWithEntry:session:updateCoordinator:cancellationHandler:completion:]_block_invoke
+ ___117-[HDOntologyUpdateCoordinator _runOntologyUpdateWithShouldDefer:addExpirationHandler:reason:activityName:completion:]_block_invoke
+ ___62-[HDOntologyUpdateCoordinator _makePeriodicTaskWithScheduler:]_block_invoke
+ ___79-[HDOntologyUpdateCoordinator _makeOneShotTaskWithIdentifier:reason:scheduler:]_block_invoke
+ ___82-[HDOntologyUpdateCoordinator _runOntologyUpdateForOneShotTask:reason:completion:]_block_invoke
+ ___84-[HDOntologyUpdateCoordinator _runOntologyUpdateForRepeatingTask:reason:completion:]_block_invoke
+ ___91-[HDOntologyUpdateCoordinator _runOntologyUpdateWithReason:cancellationHandler:completion:]_block_invoke
+ ___91-[HDOntologyUpdateCoordinator _runOntologyUpdateWithReason:cancellationHandler:completion:]_block_invoke_2
+ ___91-[HDOntologyUpdateCoordinator _runOntologyUpdateWithReason:cancellationHandler:completion:]_block_invoke_3
+ ___95-[HDOntologyUpdateCoordinator _enqueueUpdateOntologyWithReason:cancellationHandler:completion:]_block_invoke
+ ___95-[HDOntologyUpdateCoordinator _enqueueUpdateOntologyWithReason:cancellationHandler:completion:]_block_invoke_2
+ ___97-[HDOntologyUpdateCoordinator _updateOntologyWithReason:updateID:cancellationHandler:completion:]_block_invoke
+ ___block_descriptor_40_e8_32s_e14_v16?0?<v?>8ls32l8
+ ___block_descriptor_40_e8_32w_e55_v24?0"HDRepeatingBackgroundTask"8?<v?q"NSError">16lw32l8
+ ___block_descriptor_48_e8_32w_e53_v24?0"HDOneShotBackgroundTask"8?<v?q"NSError">16lw32l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e20_v20?0B8"NSError"12ls32l8s56l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56bs64bs_e20_v20?0B8"NSError"12ls56l8s32l8s40l8s64l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56bs_e14_v16?0?<v?>8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56bs_e14_v16?0?<v?>8ls32l8s40l8s56l8s48l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72bs_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24ls32l8s72l8s40l8s48l8s56l8s64l8
- +[HDOntologyManifestUpdater _downloadManifestWithEntry:session:updateCoordinator:completion:]
- +[HDOntologyManifestUpdater _updateManifestWithEntry:session:updateCoordinator:completion:]
- +[HDOntologyResourceDirectoryManager _activeDirectoryNameForEntry:]
- +[HDOntologyResourceDirectoryManager _attemptDeleteOrphanedDirectoryAtURL:directoryName:fileManager:deletionErrors:]
- +[HDOntologyResourceDirectoryManager _finalizeDeletionResultsWithAttemptedCount:deletionErrors:error:]
- +[HDOntologyResourceDirectoryManager _isDirectoryAtURL:]
- +[HDOntologyResourceDirectoryManager _processDirectoryItem:activeDirectoryNames:fileManager:deletionErrors:]
- +[HDOntologyResourceDirectoryManager _shouldPreserveDirectoryNamed:activeDirectoryNames:]
- +[HDOntologyResourceDirectoryManager _stagedDirectoryNameForEntry:]
- +[HDOntologyResourceDirectoryManager _writeInfoPlistToBundleURL:bundleName:error:]
- +[HDOntologyResourceDirectoryManager activeResourceDirectoryURLForEntry:updateCoordinator:]
- +[HDOntologyResourceDirectoryManager baseResourcesDirectoryURLForUpdateCoordinator:]
- +[HDOntologyResourceDirectoryManager cleanupOrphanedDirectoriesExcluding:updateCoordinator:fileManager:error:]
- +[HDOntologyResourceDirectoryManager createResourceDirectoryForEntry:updateCoordinator:fileManager:error:]
- +[HDOntologyResourceDirectoryManager deleteResourceDirectoryForEntry:updateCoordinator:fileManager:error:]
- +[HDOntologyResourceDirectoryManager extractResourceEntry:entry:updateCoordinator:fileManager:error:]
- +[HDOntologyResourceDirectoryManager stagedResourceDirectoryURLForEntry:updateCoordinator:]
- +[HDOntologyUpdateCoordinator _endpointDictionary]
- +[HDOntologyUpdateCoordinator _fallbackActivityCriteria]
- +[HDOntologyUpdateCoordinator _gatedActivityCriteria]
- -[HDOntologyResourceDirectoryManager init]
- -[HDOntologyShardDownloader _downloadFilesForEntries:session:completion:]
- -[HDOntologyShardDownloader _downloadRequiredShardFilesWithSession:requiredEntries:completion:]
- -[HDOntologyUpdateCoordinator _runOntologyUpdateWithReason:completion:]
- -[HDOntologyUpdateCoordinator _runOntologyUpdateWithReason:session:completion:]
- -[HDOntologyUpdateCoordinator _triggerOntologyUpdateForGatedActivity:ontologyUpdateReason:completion:]
- -[HDOntologyUpdateCoordinator _updateOntologyWithReason:updateID:completion:]
- -[HDOntologyUpdateCoordinator performPeriodicActivity:completion:]
- -[HDOntologyUpdateCoordinator periodicActivity:configureXPCActivityCriteria:]
- -[_HDOntologyDownloadTask initForDownloader:session:queue:]
- -[_HDOntologyShardDownloadTask initForEntry:downloader:session:group:]
- GCC_except_table45
- GCC_except_table73
- _HDStringFromGatedActivityResult
- _HKErrorDomain
- _NSURLIsDirectoryKey
- _OBJC_CLASS_$_HDOntologyResourceDirectoryManager
- _OBJC_CLASS_$_HDPeriodicActivity
- _OBJC_CLASS_$_HDXPCGatedActivity
- _OBJC_CLASS_$_NSPropertyListSerialization
- _OBJC_IVAR_$_HDOntologyUpdateCoordinator._fallbackActivity
- _OBJC_IVAR_$_HDOntologyUpdateCoordinator._gatedActivity
- _OBJC_IVAR_$_HDOntologyUpdateCoordinator._periodicActivity
- _OBJC_METACLASS_$_HDOntologyResourceDirectoryManager
- _XPC_ACTIVITY_ALLOW_BATTERY
- _XPC_ACTIVITY_INTERVAL_8_HOURS
- _XPC_ACTIVITY_NETWORK_DOWNLOAD_SIZE
- _XPC_ACTIVITY_NETWORK_TRANSFER_ENDPOINT
- _XPC_ACTIVITY_PRIORITY
- _XPC_ACTIVITY_PRIORITY_UTILITY
- _XPC_ACTIVITY_REQUIRES_BUDDY_COMPLETE
- _XPC_ACTIVITY_REQUIRES_CLASS_A
- _XPC_ACTIVITY_REQUIRES_CLASS_B
- _XPC_ACTIVITY_REQUIRE_NETWORK_CONNECTIVITY
- __OBJC_$_CLASS_METHODS_HDOntologyResourceDirectoryManager
- __OBJC_$_INSTANCE_METHODS_HDOntologyResourceDirectoryManager
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_HDPeriodicActivityDelegate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HDPeriodicActivityDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_HDPeriodicActivityDelegate
- __OBJC_$_PROTOCOL_REFS_HDPeriodicActivityDelegate
- __OBJC_CLASS_RO_$_HDOntologyResourceDirectoryManager
- __OBJC_LABEL_PROTOCOL_$_HDPeriodicActivityDelegate
- __OBJC_METACLASS_RO_$_HDOntologyResourceDirectoryManager
- __OBJC_PROTOCOL_$_HDPeriodicActivityDelegate
- ___102-[HDOntologyUpdateCoordinator _triggerOntologyUpdateForGatedActivity:ontologyUpdateReason:completion:]_block_invoke
- ___110+[HDOntologyResourceDirectoryManager cleanupOrphanedDirectoriesExcluding:updateCoordinator:fileManager:error:]_block_invoke
- ___53-[HDOntologyUpdateCoordinator profileDidBecomeReady:]_block_invoke
- ___53-[HDOntologyUpdateCoordinator profileDidBecomeReady:]_block_invoke_2
- ___66-[HDOntologyUpdateCoordinator performPeriodicActivity:completion:]_block_invoke
- ___67-[HDOntologyUpdateCoordinator updateOntologyWithReason:completion:]_block_invoke
- ___67-[HDOntologyUpdateCoordinator updateOntologyWithReason:completion:]_block_invoke_2
- ___71-[HDOntologyUpdateCoordinator _runOntologyUpdateWithReason:completion:]_block_invoke
- ___77-[HDOntologyUpdateCoordinator _updateOntologyWithReason:updateID:completion:]_block_invoke
- ___79-[HDOntologyUpdateCoordinator _runOntologyUpdateWithReason:session:completion:]_block_invoke
- ___79-[HDOntologyUpdateCoordinator _runOntologyUpdateWithReason:session:completion:]_block_invoke_2
- ___91+[HDOntologyManifestUpdater _updateManifestWithEntry:session:updateCoordinator:completion:]_block_invoke
- ___93+[HDOntologyManifestUpdater _downloadManifestWithEntry:session:updateCoordinator:completion:]_block_invoke
- ___block_descriptor_40_e8_32w_e76_v32?0"HDXPCGatedActivity"8"NSObject<OS_xpc_object>"16?<v?q"NSError">24lw32l8
- ___block_descriptor_56_e8_32s40s48bs_e14_v16?0?<v?>8ls32l8s48l8s40l8
- ___block_descriptor_56_e8_32s40s48bs_e20_v20?0B8"NSError"12ls48l8s32l8s40l8
- ___block_descriptor_64_e8_32s40s48bs56bs_e20_v20?0B8"NSError"12ls48l8s32l8s56l8s40l8
- ___block_descriptor_64_e8_32s40s48bs_e14_v16?0?<v?>8ls32l8s40l8s48l8
- ___block_descriptor_72_e8_32s40s48s56r_e19_q24?0"NSURL"8^16lr56l8s32l8s40l8s48l8
- ___block_descriptor_80_e8_32s40s48s56s64bs_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24ls32l8s64l8s40l8s48l8s56l8
- _nw_endpoint_copy_dictionary
- _nw_endpoint_create_host
- _xpc_dictionary_create_empty
- _xpc_dictionary_set_bool
- _xpc_dictionary_set_int64
- _xpc_dictionary_set_string
- _xpc_dictionary_set_value
CStrings:
+ "%{public}@: Deferring ontology update for %{public}@ (shouldDefer at start)"
+ "%{public}@: Expiration handler fired, cancelling in-flight ontology update work"
+ "%{public}@: Fallback update result: %ld, error: %{public}@"
+ "%{public}@: Gated update result: %ld, error: %{public}@"
+ "%{public}@: Unable to run gated task immediately: %{public}@"
+ "%{public}@: Unable to schedule fallback task: %{public}@"
+ "%{public}@: Unable to submit gated task: %{public}@"
+ "%{public}@: Unable to submit periodic task: %{public}@"
+ "Ontology update cancelled during manifest fetch"
+ "Ontology update cancelled during shard download"
+ "v24@?0@\"HDOneShotBackgroundTask\"8@?<v@?q@\"NSError\">16"
+ "v24@?0@\"HDRepeatingBackgroundTask\"8@?<v@?q@\"NSError\">16"
- "%@_%@_%ld_%ld.bundle"
- "%{public}@: Cleaned up orphaned resource directories attempted %ld"
- "%{public}@: Deleted orphaned resource directory: %{public}@"
- "%{public}@: Fallback update result: %{public}@, error: %{public}@"
- "%{public}@: Gated update result: %{public}@, error: %{public}@"
- "6.0"
- "BNDL"
- "CFBundleDevelopmentRegion"
- "CFBundleIdentifier"
- "CFBundleInfoDictionaryVersion"
- "CFBundleName"
- "CFBundlePackageType"
- "Failed to delete %ld of %ld orphaned resource directories"
- "Info.plist"
- "com.apple.health.ontology.%@"
- "en"
- "resources"
- "v32@?0@\"HDXPCGatedActivity\"8@\"NSObject<OS_xpc_object>\"16@?<v@?q@\"NSError\">24"
```
