## PosterBoardServices

> `/System/Library/PrivateFrameworks/PosterBoardServices.framework/PosterBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7eb44` | `0x7dd60` | **`-0xde4`** |
| `__TEXT.__oslogstring` | `0x39ee` | `0x37de` | **`-0x210`** |
| `__DATA_CONST.__const` | `0x1ce8` | `0x1bd0` | **`-0x118`** |
| `__AUTH_CONST.__cfstring` | `0x4ca0` | `0x4d80` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x6c8b` | `0x6d1b` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x10998` | `0x10a18` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x1000` | `0xfbc` | **`-0x44`** |
| `__TEXT.__objc_methlist` | `0x5308` | `0x5348` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1bb8` | `0x1b88` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0xc40` | `0xc20` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0x8a8` | `0x8c8` | **`+0x20`** |
| `__DATA.__bss` | `0xc50` | `0xc60` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c20` | `0x2c30` | **`+0x10`** |
| `__TEXT.__const` | `0xb18` | `0xb28` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x5c8` | `0x5d0` | **`+0x8`** |

### Other Changes

```diff

-350.1.100.0.0
+355.0.5.0.0

-  Functions: 2702
-  Symbols:   3890
-  CStrings:  1118
+  Functions: 2697
+  Symbols:   3884
+  CStrings:  1103
Symbols:
+ +[PRSPosterUpdater _sharedNotificationService]
+ -[PRSLockScreenColorConfigurationCache invalidateCacheWithReason:]
+ -[PRSMigrationDescriptor configurationMigrationTimeoutInterval]
+ -[PRSMigrationDescriptor setConfigurationMigrationTimeoutInterval:]
+ -[PRSPosterIconConfiguration configVersion]
+ -[PRSPosterIconConfiguration initWithPoster:type:variant:accentColor:size:configVersion:]
+ -[PRSPosterUpdate canBeServicedWithoutExtension]
+ -[PRSServer migrateLockScreenToPhotosWallpaperWithImageData:homeScreenImageData:completion:]
+ -[PRSService migrateLockScreenToPhotosWallpaperWithImageData:homeScreenImageData:completion:]
+ _OBJC_IVAR_$_PRSMigrationDescriptor._configurationMigrationTimeoutInterval
+ _OBJC_IVAR_$_PRSPosterIconConfiguration._configVersion
+ ___46+[PRSPosterUpdater _sharedNotificationService]_block_invoke
+ ___92-[PRSServer migrateLockScreenToPhotosWallpaperWithImageData:homeScreenImageData:completion:]_block_invoke
+ ___93-[PRSService migrateLockScreenToPhotosWallpaperWithImageData:homeScreenImageData:completion:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e28_v24?0"NSUUID"8"NSError"16ls32l8
+ __sharedNotificationService.onceToken
+ __sharedNotificationService.service
- -[PRSExternalSystemService createLockScreenPhotosPosterWithImageAtURL:selectedLockScreenPoster:]
- -[PRSPosterIconConfiguration initWithPoster:type:variant:accentColor:size:]
- -[PRSPosterUpdater synchronouslyApplyUpdates:error:]
- -[PRSServer forceUpdatePosterPath:updates:completion:]
- -[PRSService forceUpdatePosterPath:updates:error:]
- GCC_except_table1
- GCC_except_table18
- ___50-[PRSService forceUpdatePosterPath:updates:error:]_block_invoke
- ___96-[PRSExternalSystemService createLockScreenPhotosPosterWithImageAtURL:selectedLockScreenPoster:]_block_invoke
- ___block_descriptor_40_e8_32bs_e32_v16?0"PRSPosterConfiguration"8ls32l8
- ___block_descriptor_40_e8_32s_e44_v24?0"PRSPosterConfiguration"8"NSError"16ls32l8
- ___block_descriptor_48_e8_32s40bs_e45_"<PFTFuture>"16?0"PRSPosterConfiguration"8ls32l8s40l8
- ___block_descriptor_48_e8_32s40r_e17_v16?0"NSError"8ls32l8r40l8
- ___block_descriptor_48_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e43_"PFTFuture"16?0"PRSPosterConfiguration"8ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e70_v32?0"PRSPosterConfiguration"8"PRSPosterUpdateResult"16"NSError"24ls32l8s40l8
- ___block_descriptor_72_e8_32s40s48s56s64bs_e29_v24?0"NSArray"8"NSError"16ls64l8s32l8s40l8s48l8s56l8
- ___getPRPosterPathModelObjectCacheClass_block_invoke
- _dispatch_group_create
- _dispatch_group_enter
- _dispatch_group_leave
- _dispatch_group_notify
- _getPRPosterPathModelObjectCacheClass.softClass
CStrings:
+ "-[PRSServer migrateLockScreenToPhotosWallpaperWithImageData:homeScreenImageData:completion:]"
+ "Active poster provider is %@, not PhotosPosterProvider; will not return data"
+ "Cache file unavailable (errno %d)"
+ "Could not render the poster snapshot (the render may have timed out)"
+ "Failed to read homeScreenWallpaperURL: %{public}@"
+ "Failed to read lockScreenImageURL: %{public}@"
+ "No poster snapshot was produced (the render may have timed out or returned nothing)"
+ "PRSLockScreenColorConfigurationCache: cache open failed: %{darwin.errno}d"
+ "PRSLockScreenColorConfigurationCache: invalidate (%{public}@) delete failed: %{public}@"
+ "PRSLockScreenColorConfigurationCache: invalidated (deleted) cache: %{public}@"
+ "PRSLockScreenColorConfigurationCache: unarchive failed / unexpected root type: %{public}@"
+ "PRSLockScreenColorConfigurationCache: unarchive threw: %{public}@"
+ "Reset complete; new active poster UUID=%{public}@"
+ "Snapshot contained no %@ configuration; the poster render did not complete"
+ "Snapshot has no %{public}@ configuration path; render did not complete"
+ "_configVersion"
+ "_configurationMigrationTimeoutInterval"
+ "com.apple.migrationd"
+ "configurationMigrationTimeoutInterval"
+ "file unavailable"
+ "home-screen"
+ "hostConfiguredPropertiesDidChange"
+ "lock-screen"
+ "lockScreenImageData"
+ "migrateLockScreenToPhotosWallpaper failed: %{public}@"
+ "migrateLockScreenToPhotosWallpaper: allowing com.apple.migrationd via temporary signing-identity bypass (pending deleteDescriptors adoption, rdar://TODO-ADOPTION)"
- "-[PRSServer forceUpdatePosterPath:updates:completion:]"
- "@\"<PFTFuture>\"16@?0@\"PRSPosterConfiguration\"8"
- "@\"PFTFuture\"16@?0@\"PRSPosterConfiguration\"8"
- "Cache file missing"
- "Checking if lockScreenImageURL is reachable: %{public}@"
- "Class getPRPosterPathModelObjectCacheClass(void)_block_invoke"
- "Cleanup completed successfully"
- "Creating lock screen photos poster and starting reset operation"
- "Deleting configuration: %{public}@"
- "Error deleting configuration %{public}@: %{public}@"
- "Error fetching configurations for cleanup: %{public}@"
- "Error updating home screen wallpaper (not aborting operation): %{public}@"
- "Found %ld configurations to process for cleanup"
- "Future-based poster creation failed: %{public}@"
- "Future-based poster creation succeeded"
- "Initiated deletion of %ld configurations"
- "Lock screen poster created successfully: %{public}@"
- "New configuration UUID to preserve: %{public}@"
- "No home screen wallpaper to update"
- "No snapshots available"
- "PRPosterPathModelObjectCache"
- "Provider is not PhotosPosterProvider; will not return data"
- "Reset lock screen wallpapers operation completed successfully"
- "Reset lock screen wallpapers operation failed: %{public}@"
- "Skipping deletion of new configuration: %{public}@"
- "Starting cleanup of existing poster configurations"
- "Starting createLockScreenPhotosPosterWithImageAtURL (future variant): %{public}@, selectPoster: %{public}@"
- "Successfully deleted configuration: %{public}@"
- "Successfully updated home screen wallpaper"
- "Updating home screen wallpaper"
- "file missing"
- "force RPC failed on %{public}@: %{public}@"
- "force RPC reply received on %{public}@"
- "forceUpdatePosterPath: nil path"
- "homeScreenWallpaperURL is not reachable"
- "homeScreenWallpaperURL is not reachable: %{public}@"
- "homeScreenWallpaperURL is reachable"
- "lockScreenImageURL is not reachable"
- "lockScreenImageURL is not reachable: %{public}@"
- "lockScreenImageURL is reachable"
- "v16@?0@\"PRSPosterConfiguration\"8"
```
