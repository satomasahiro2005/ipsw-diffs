## MobileAssetDaemon

> `/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/MobileAssetDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x261210` | `0x262d64` | **`+0x1b54`** |
| `__TEXT.__oslogstring` | `0x5b01d` | `0x5b5bd` | **`+0x5a0`** |
| `__TEXT.__cstring` | `0x3fb77` | `0x3fd97` | **`+0x220`** |
| `__AUTH_CONST.__cfstring` | `0x33240` | `0x333e0` | **`+0x1a0`** |
| `__TEXT.__gcc_except_tab` | `0xd518` | `0xd5b4` | **`+0x9c`** |
| `__TEXT.__objc_methlist` | `0x12dd4` | `0x12e2c` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x48b0` | `0x4900` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x1080` | `0x10c0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xb020` | `0xb058` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x191a8` | `0x191d8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x3210` | `0x3230` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1230` | `0x1238` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1830` | `0x1834` | **`+0x4`** |

### Other Changes

```diff

-2215.40.19.0.0
+2215.40.21.502.1

-  Functions: 7327
-  Symbols:   11506
-  CStrings:  11064
+  Functions: 7344
+  Symbols:   11526
+  CStrings:  11092
Symbols:
+ +[MAAutoAssetMigrationManager cleanupPreinstalledDirectoryAtPath:]
+ +[MAAutoAssetMigrationManager cleanupPreinstalledDirectory]
+ +[MAAutoAssetMigrationManager deleteDirectoryIfEmpty:error:]
+ -[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:existingNumberOfSeconds:logString:]
+ -[ControlManager maAutoAssetScheduledCleanup]
+ -[ControlManager respondToCacheDelete:targetingPurgeAmount:cacheDeleteResults:withUrgency:forVolume:maAutoAssetScheduledCleanup:then:]
+ -[ControlManager setMaAutoAssetScheduledCleanup:]
+ -[MADAutoAssetControlManager formLatestAssetVersionBySelector:]
+ -[MADAutoAssetControlManager schedulerReferencesDescriptor:withLatestVersionBySelector:]
+ -[MADAutoAssetControlManager setConfigurationReferencesDescriptor:withLatestVersionBySelector:]
+ GCC_except_table193
+ GCC_except_table205
+ GCC_except_table806
+ GCC_except_table809
+ _OBJC_IVAR_$_ControlManager._maAutoAssetScheduledCleanup
+ __OBJC_$_CLASS_METHODS_MAAutoAssetMigrationManager
+ ___134-[ControlManager respondToCacheDelete:targetingPurgeAmount:cacheDeleteResults:withUrgency:forVolume:maAutoAssetScheduledCleanup:then:]_block_invoke
+ ___174-[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:existingNumberOfSeconds:logString:]_block_invoke
+ ___174-[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:existingNumberOfSeconds:logString:]_block_invoke_2
+ ___174-[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:existingNumberOfSeconds:logString:]_block_invoke_3
+ ___53-[MobileAssetHealthReport scheduleReportWithReports:]_block_invoke_2
+ ___block_descriptor_32_e8_v16?0q8l
+ ___block_descriptor_80_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___clearXattrKey_block_invoke
+ ___updateXattrKeyWithDate_block_invoke
+ _clearXattrKey
+ _getDateOnXattrKey
+ _removexattr
+ _updateXattrKeyWithDate
- -[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:logString:]
- -[MADAutoAssetControlManager schedulerReferencesDescriptor:]
- -[MADAutoAssetControlManager setConfigurationReferencesDescriptor:]
- GCC_except_table152
- GCC_except_table201
- GCC_except_table802
- GCC_except_table808
- ___106-[ControlManager respondToCacheDelete:targetingPurgeAmount:cacheDeleteResults:withUrgency:forVolume:then:]_block_invoke
- ___block_descriptor_79_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
CStrings:
+ " | IGNORED - not UnlockedUnreferenced, not removed"
+ " | UnlockedUnreferenced for less than 24 hours - not removed"
+ " | UnlockedUnreferenced for more than 24 hours - immediate remove"
+ " | last UnlockedUnreferenced not set - not removed"
+ " | maCleanupMode"
+ " | used within 24 hours - not removed"
+ "Attempted to delete a directory that does not exists"
+ "Cannot clear xattr key %@ with %@ location"
+ "Cannot get xattr key %@ with %@ location"
+ "Cannot update xattr key %@ with %@ location"
+ "Directory is not empty"
+ "Failed to remove xattr '%@' on path '%s' with errno %lld (%s)"
+ "Loaded built-in MobileAssetDaemon_Framework Sep 29 2026 21:00:28"
+ "MADaemonAssetCleanupCheck"
+ "MobileAssetScheduledCleanUp"
+ "Provided path is a file instead of a directory"
+ "XPC activity %s performing AutoAsset clean up freed up %@ space"
+ "[AUTO-PRE-INSTALLED] {cleanupPreInstalledDirectory} Error removing empty directory at path(%@) error:%@"
+ "[AUTO-PRE-INSTALLED] {cleanupPreInstalledDirectory} Successfully removed empty directory at path(%@) error:%@"
+ "[AUTO-PRE-INSTALLED] {preInstalledRelocateAutoAssets} deleted pre-installed asset directory %{public}@"
+ "[AUTO-PRE-INSTALLED] {preInstalledRelocateAutoAssets} failed to delete pre-installed asset directory %{public}@ Error: %{public}@"
+ "clean up mode - not ready to be cleaned up"
+ "deleteDirectoryIfEmpty:error:"
+ "{copyCurrentDownloadedDescriptors} build container copies for auto-asset descriptor categories (with latest asset-version considered referenced) | dispatch..."
+ "{formLatestAssetVersionBySelector} unable to compare restore versions | assetDescriptorKey:%{public}@"
+ "{formLatestAssetVersionBySelector} unable to form withoutVersionKey | nextDownloadedDescriptor:%{public}@"
+ "{formLatestAssetVersionBySelector} unable to load nextDownloadedDescriptor | assetDescriptorKey:%{public}@"
+ "{respondToCacheDelete} %{public}@... | targetingPurgeAmount:%{public}@ | urgency:%{public}d(%{public}@) | volume:%{public}@ | assetTypeDirs:%{public}ld | preciousInterval:%{public}@%{public}@, defaultInterval:%{public}@%{public}@%{public}@ | autoAssetStatus:%{public}@ | maCleanup: %d"
+ "{respondToCacheDelete} ...%{public}@ | targetingPurgeAmount:%{public}@ | urgency:%{public}d(%{public}@) | volume:%{public}@ | assetTypeDirs:%{public}ld | preciousInterval:%{public}@%{public}@, defaultInterval:%{public}@%{public}@%{public}@ | autoAssetStatus:%{public}@ | %{public}@ | maCleanup: %d | MA_MILESTONE"
+ "{respondToCacheDelete} performing cache-delete triggered operation for volume %{public}@ at urgency %d, maCleanup %d ..."
+ "{schedulerReferencesDescriptor} missing latestVersionBySelector | withoutVersionKey:%{public}@"
+ "{setConfigurationReferencesDescriptor} missing latestVersionBySelector | withoutVersionKey:%{public}@"
+ "{setConfigurationReferencesDescriptor} unable to load set descriptor for discovered-in-flight | setConfiguration:%{public}@"
- "Loaded built-in MobileAssetDaemon_Framework Sep 13 2026 20:55:11"
- "{copyCurrentDownloadedDescriptors} build container copies for auto-asset descriptor categories | dispatch..."
- "{respondToCacheDelete} %{public}@... | targetingPurgeAmount:%{public}@ | urgency:%{public}d(%{public}@) | volume:%{public}@ | assetTypeDirs:%{public}ld | preciousInterval:%{public}@%{public}@, defaultInterval:%{public}@%{public}@%{public}@ | autoAssetStatus:%{public}@"
- "{respondToCacheDelete} ...%{public}@ | targetingPurgeAmount:%{public}@ | urgency:%{public}d(%{public}@) | volume:%{public}@ | assetTypeDirs:%{public}ld | preciousInterval:%{public}@%{public}@, defaultInterval:%{public}@%{public}@%{public}@ | autoAssetStatus:%{public}@ | %{public}@ | MA_MILESTONE"
- "{respondToCacheDelete} performing cache-delete triggered operation for volume %{public}@ at urgency %d ..."
```
