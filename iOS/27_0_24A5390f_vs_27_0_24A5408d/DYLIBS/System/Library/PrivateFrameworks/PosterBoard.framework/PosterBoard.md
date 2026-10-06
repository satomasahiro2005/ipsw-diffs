## PosterBoard

> `/System/Library/PrivateFrameworks/PosterBoard.framework/PosterBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2742a4` | `0x279c78` | **`+0x59d4`** |
| `__TEXT.__oslogstring` | `0x1e04a` | `0x1ea9a` | **`+0xa50`** |
| `__AUTH_CONST.__objc_const` | `0x3daa0` | `0x3e268` | **`+0x7c8`** |
| `__TEXT.__gcc_except_tab` | `0x4624` | `0x4c60` | **`+0x63c`** |
| `__TEXT.__cstring` | `0x144e5` | `0x14745` | **`+0x260`** |
| `__AUTH_CONST.__cfstring` | `0xc300` | `0xc4c0` | **`+0x1c0`** |
| `__AUTH_CONST.__const` | `0x9250` | `0x9350` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x6c18` | `0x6d10` | **`+0xf8`** |
| `__TEXT.__objc_methlist` | `0xeee4` | `0xefbc` | **`+0xd8`** |
| `__TEXT.__const` | `0x73e4` | `0x7314` | **`-0xd0`** |
| `__DATA.__data` | `0x62a0` | `0x6360` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x3b38` | `0x3bf0` | **`+0xb8`** |
| `__DATA_CONST.__objc_selrefs` | `0x9c30` | `0x9ce8` | **`+0xb8`** |
| `__TEXT.__swift5_typeref` | `0x89b6` | `0x8a56` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x5210` | `0x52a8` | **`+0x98`** |
| `__TEXT.__swift5_capture` | `0x25d4` | `0x2624` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x4b6e` | `0x4bbd` | **`+0x4f`** |
| `__TEXT.__swift5_fieldmd` | `0x3090` | `0x30c4` | **`+0x34`** |
| `__AUTH.__data` | `0xfc0` | `0xff0` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x6234` | `0x6260` | **`+0x2c`** |
| `__AUTH_CONST.__objc_intobj` | `0x90` | `0xa8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2458` | `0x2468` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1084` | `0x1090` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x1db0` | `0x1db8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x748` | `0x750` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x6c8` | `0x6d0` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x2c8` | `0x2d0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x240` | `0x244` | **`+0x4`** |

### Other Changes

```diff

-350.1.100.0.0
+355.0.5.0.0

-  - /usr/lib/swift/libswiftCallKit.dylib

-  Functions: 10841
-  Symbols:   11074
-  CStrings:  3968
+  Functions: 10929
+  Symbols:   11118
+  CStrings:  4016
Symbols:
+ +[PBFPosterExtensionDataStoreMigrator mostUpToDateAvailableDataStoreVersionAtBaseURL:]
+ +[PBFPosterModelStoreCoordinator storeCoordinatorClassForType:]
+ -[PBFLockScreenColorConfigurationCache _lock_mergeConfigurations:ontoBase:]
+ -[PBFPosterConfigurationMigrator dealloc]
+ -[PBFPosterConfigurationMigrator invalidate]
+ -[PBFPosterConfigurationMigrator pbf_activeExtensionInstanceCount]
+ -[PBFPosterConfigurationMigrator perCallOutTimeoutIntervalForTesting]
+ -[PBFPosterConfigurationMigrator performConfigurationMigrations:budget:]
+ -[PBFPosterConfigurationMigrator setPerCallOutTimeoutIntervalForTesting:]
+ -[PBFPosterExtensionDataStore _migrateConfigurationsWithAdditionalSessionUserInfo:timeoutInterval:]
+ -[PBFPosterExtensionDataStore migrateLockScreenToPhotosWallpaperWithImageData:homeScreenImageData:error:]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue _executeMigration:migrationDescriptor:completion:]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue server:migrateLockScreenToPhotosWallpaperWithImageData:homeScreenImageData:completion:]
+ -[PBFPosterExtensionStoreCoordinator _correctPermissionsForURL:excludeFromBackup:]
+ -[SBSWallpaperService(StagingFor96847910) staging_fetchPosterSignificantEventsCounterForPosterUUID:completionHandler:]
+ GCC_except_table119
+ GCC_except_table125
+ GCC_except_table156
+ GCC_except_table162
+ GCC_except_table175
+ GCC_except_table176
+ GCC_except_table184
+ GCC_except_table432
+ GCC_except_table435
+ GCC_except_table452
+ GCC_except_table469
+ GCC_except_table470
+ GCC_except_table471
+ GCC_except_table473
+ GCC_except_table57
+ GCC_except_table59
+ GCC_except_table63
+ GCC_except_table92
+ GCC_except_table95
+ _OBJC_CLASS_$_PFPosterPathsAssertion
+ _OBJC_CLASS_$__TtC11PosterBoard14BlockAssertion
+ _OBJC_IVAR_$_PBFPosterConfigurationMigrator._extensionInstanceProvider
+ _OBJC_IVAR_$_PBFPosterConfigurationMigrator._perCallOutTimeoutInterval
+ _OBJC_IVAR_$_PBFPosterConfigurationMigrator._schedulerProvider
+ _OBJC_METACLASS_$__TtC11PosterBoard14BlockAssertion
+ _OUTLINED_FUNCTION_47
+ _PFServerPosterTypeEnumerate
+ _PUIAFSCEnqueueCompressionForURL
+ __DATA__TtC11PosterBoard14BlockAssertion
+ __INSTANCE_METHODS__TtC11PosterBoard14BlockAssertion
+ __IVARS__TtC11PosterBoard14BlockAssertion
+ __METACLASS_DATA__TtC11PosterBoard14BlockAssertion
+ __OBJC_$_PROP_LIST_PRPosterContentStyleGlassAppearanceSupporting
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_PRPosterContentStyleGlassAppearanceSupporting
+ __OBJC_$_PROTOCOL_METHOD_TYPES_PRPosterContentStyleGlassAppearanceSupporting
+ __OBJC_$_PROTOCOL_REFS_PRPosterContentStyleGlassAppearanceSupporting
+ __OBJC_LABEL_PROTOCOL_$_PRPosterContentStyleGlassAppearanceSupporting
+ __OBJC_PROTOCOL_$_PRPosterContentStyleGlassAppearanceSupporting
+ __OBJC_PROTOCOL_REFERENCE_$_PRPosterContentStyleGlassAppearanceSupporting
+ __PROTOCOLS__TtC11PosterBoard14BlockAssertion
+ ___105-[PBFPosterExtensionDataStore migrateLockScreenToPhotosWallpaperWithImageData:homeScreenImageData:error:]_block_invoke
+ ___105-[PBFPosterExtensionDataStore migrateLockScreenToPhotosWallpaperWithImageData:homeScreenImageData:error:]_block_invoke_2
+ ___120-[PBFPosterExtensionDataStore _stateLock_convertPosterUpdatesToRoleCoordinatorChanges:toPath:powerLogReason:completion:]_block_invoke_3
+ ___79-[PBFPosterExtensionStoreCoordinator _correctPermissionsForInternalDirectories]_block_invoke
+ ___94-[PBFPosterExtensionDataStoreXPCServiceGlue _executeMigration:migrationDescriptor:completion:]_block_invoke
+ ___96-[PBFPosterExtensionDataStoreXPCServiceGlue server:runMigration:migrationDescriptor:completion:]_block_invoke
+ ___block_descriptor_40_e8_32s_e12_v24?0q8^B16ls32l8
+ ___block_descriptor_48_e8_32r40r_e68_v32?0"PBFPosterConfigurationUpdateResult"8"NSArray"16"NSError"24lr32l8r40l8
+ ___block_descriptor_56_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_57_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56s_e30_"<PFTFuture>"16?0"NSError"8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_64_e8_32s40s48s56s_e59_v24?0"PBFPosterConfigurationMigrationResult"8"NSError"16ls32l8s40l8s48l8s56l8
+ ___block_descriptor_64_e8_32s40s48s56w_e21_"<PFTFuture>"16?08lw56l8s32l8s40l8s48l8
+ ___block_descriptor_96_e8_32s40s48bs56r64r72r80r88r_e68_v32?0"PBFPosterConfigurationUpdateResult"8"NSArray"16"NSError"24ls48l8r56l8s32l8s40l8r64l8r72l8r80l8r88l8
+ ___swift_closure_destructor.148Tm
+ ___swift_closure_destructor.155Tm
+ ___swift_closure_destructor.387Tm
+ ___swift_closure_destructor.681Tm
+ ___swift_closure_destructor.81Tm
+ ___unnamed_17
+ _symbolic So12NSCountedSetC
+ _symbolic _____ 11PosterBoard14BlockAssertionC
+ _symbolic _____SgXw 11PosterBoard0A20GalleryAssetProviderC
+ _symbolic _____SgXwz_Xx 11PosterBoard0A20GalleryAssetProviderC
+ _symbolic _____y______pSgG 7SwiftUI5StateV So15BSInvalidatableP
+ _symbolic _____y______pSgG 7SwiftUI9LazyStateV So15BSInvalidatableP
+ _symbolic _____y______pSg_G 7SwiftUI9LazyStateV7StorageO So15BSInvalidatableP
+ _symbolic _____y______pSg_G_yXlSgt 7SwiftUI9LazyStateV7StorageO So15BSInvalidatableP
+ _symbolic _____yyycSgG 2os21OSAllocatedUnfairLockV
+ _symbolic _____yyycSg_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
- -[PBFPosterExtensionDataStore _migrateConfigurationsWithAdditionalSessionUserInfo:]
- -[PBFPosterExtensionDataStore _migrateConfigurations]
- -[PBFPosterExtensionDataStoreXPCServiceGlue server:forceUpdatePosterPath:updates:completion:]
- GCC_except_table127
- GCC_except_table160
- GCC_except_table164
- GCC_except_table177
- GCC_except_table178
- GCC_except_table27
- GCC_except_table433
- GCC_except_table447
- GCC_except_table464
- GCC_except_table465
- GCC_except_table466
- GCC_except_table468
- GCC_except_table71
- GCC_except_table94
- GCC_except_table98
- _OBJC_CLASS_$_PRSLockScreenColorConfigurationCache
- ___65-[PBFPosterConfigurationMigrator performConfigurationMigrations:]_block_invoke
- ___93-[PBFPosterExtensionDataStoreXPCServiceGlue server:forceUpdatePosterPath:updates:completion:]_block_invoke
- ___93-[PBFPosterExtensionDataStoreXPCServiceGlue server:forceUpdatePosterPath:updates:completion:]_block_invoke_2
- ___block_descriptor_48_e8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e28_"PFTFuture"16?0"NSArray"8ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48s_e20_v24?0q8"NSError"16ls32l8s40l8s48l8
- ___block_descriptor_96_e8_32s40s48s56bs64r72r80r88r_e68_v32?0"PBFPosterConfigurationUpdateResult"8"NSArray"16"NSError"24ls56l8s32l8s40l8s48l8r64l8r72l8r80l8r88l8
- ___block_descriptor_96_e8_32s40s48s56s64s72s80s88w_e44_v24?0"PFPosterPathsAssertion"8"NSError"16lw88l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8
- ___swift_closure_destructor.154Tm
- ___swift_closure_destructor.161Tm
- ___swift_closure_destructor.394Tm
- ___swift_closure_destructor.682Tm
- ___swift_closure_destructor.80Tm
- ___swift_closure_destructor.91Tm
- ___swift_closure_destructor.94Tm
- ___swift_memcpy209_8
- ___unnamed_16
- ___unnamed_31
- __swift_FORCE_LOAD_$_swiftCallKit
- __swift_FORCE_LOAD_$_swiftCallKit_$_PosterBoard
- _get_enum_tag_for_layout_string 7SwiftUI11EnvironmentV7ContentOySo6CGSizeV_G
- _type_layout_string 11PosterBoard0A21GalleryAssetProvidingRzlAA20ThumbnailPreviewView33_CCF1049FF886DF369E238D7CEAD3F5D3LLVyxG
CStrings:
+ "-[PBFPosterExtensionStoreCoordinator _correctPermissionsForURL:excludeFromBackup:]> failed to correct exclude from backup state for file %@: %{public}@"
+ "-[PBFPosterExtensionStoreCoordinator _correctPermissionsForURL:excludeFromBackup:]> failed to correct file protection for file %@: %{public}@"
+ "-[PBFPosterExtensionStoreCoordinator _correctPermissionsForURL:excludeFromBackup:]> failed to correct purgability for file %@: %{public}@"
+ "-[PBFPosterExtensionStoreCoordinator _correctPermissionsForURL:excludeFromBackup:]> skipping nonexistent file %@"
+ "@\"<PFTFuture>\"16@?0@8"
+ "AndroidToiOSWallpaperMigration"
+ "AndroidToiOSWallpaperMigrationHomeScreen"
+ "AndroidToiOSWallpaperMigrationRollback"
+ "Configuration migration RBSAssertion could not be acquired: %{public}@"
+ "Configuration migration RBSAssertion invalidated: %{public}@"
+ "Could not build incoming PhotosPoster configuration"
+ "Error performing necessary migrations: %{public}@"
+ "Newly created poster could not be located after Add"
+ "PBFPosterConfigurationMigrator"
+ "PRSServer_executeMigration"
+ "PhotosPoster rejected the lock-screen image update"
+ "Post-migration"
+ "Post-migration data store version is NSNotFound; skipping introspection."
+ "Post-migration introspection raised (non-fatal, skipping tint apply): %{public}@"
+ "Post-migration version probe raised; skipping introspection: %{public}@"
+ "PosterBoard Configuration Migration Assertion"
+ "PosterBoard.BlockAssertion"
+ "PosterBoard: configuration migration timed out"
+ "Pre-migration"
+ "Pre-migration introspection raised (non-fatal): %{public}@"
+ "Pre-migration version probe raised; treating as never-initialized: %{public}@"
+ "Pre-migration; data store never ever initialized; skipping migration."
+ "Pre-migration; queuing..."
+ "Unknown exception during migrateLockScreenToPhotosWallpaperWithImageData:"
+ "[_spinUpExtensionAndMigrate] %{public}@ timed out after %.0fs; terminating extension instance"
+ "[_spinUpExtensionAndMigrate] Migration failed/timed out for %{public}@ (poster UUID: %{public}@): %{public}@"
+ "[_spinUpExtensionAndMigrate] Migration invalidated for %{public}@: %{public}@"
+ "[_spinUpExtensionAndMigrate] Relinquishing extension instance for %{public}@"
+ "[buildRequests] Configuration discovery failed for all %lu extension(s) that needed migration"
+ "[buildRequests] Failed to enumerate configurations for %{public}@: %{public}@"
+ "[performConfigurationMigrations] NOT marking %{public}@ as migrated to version %ld; at least one configuration failed and will be retried on the next migration"
+ "[performConfigurationMigrations] Out of migration budget (%.1fs left, need %.0fs); could NOT finish configuration %{public}@ for %{public}@ — will retry next migration"
+ "[runMigration] poster configuration migration raised: %{public}@"
+ "_home.png"
+ "_lock.png"
+ "lockScreenImageData is required and must be non-empty"
+ "migrateLockScreen: committing %lu changes (ingest + select + %lu prune)"
+ "migrateLockScreen: could not resolve latest path for home-screen update (not aborting)"
+ "migrateLockScreen: created new poster UUID=%{public}@"
+ "migrateLockScreen: created poster %{public}@ not found in post-Add collection"
+ "migrateLockScreen: data-store verb threw exception: %{public}@"
+ "migrateLockScreen: failed to acquire runtime assertion (continuing): %{public}@"
+ "migrateLockScreen: failed to build incoming poster configuration: %{public}@"
+ "migrateLockScreen: failed to create new poster: %{public}@"
+ "migrateLockScreen: failed to seed lock-screen image (rolling back): %{public}@"
+ "migrateLockScreen: failed to spill homeScreenImageData: %{public}@"
+ "migrateLockScreen: failed to spill lockScreenImageData: %{public}@"
+ "migrateLockScreen: home-screen image update failed (not aborting): %{public}@"
+ "migrateLockScreen: home-screen ingest transaction failed (not aborting): %{public}@"
+ "migrateLockScreen: ingest/select/prune transaction failed (rolling back): %{public}@"
+ "migrateLockScreen: pre-existing poster has nil UUID, excluded from delete-set: %{public}@"
+ "migrateLockScreen: rejecting nil/empty lockScreenImageData"
+ "migrateLockScreen: rollback delete of new poster %{public}@ failed: %{public}@"
+ "migrateLockScreen: snapshot captured %lu pre-existing posters"
+ "migrateLockScreen: success, new active poster UUID=%{public}@"
+ "migrateLockScreenToPhotosWallpaper"
+ "migration timed out or ran out of budget"
+ "stale snapshot dropped"
+ "v24@?0@\"PBFPosterConfigurationMigrationResult\"8@\"NSError\"16"
- "-[PBFPosterExtensionStoreCoordinator _correctPermissionsForInternalDirectories]> failed to correct exclude from backup state for file %@: %{public}@"
- "-[PBFPosterExtensionStoreCoordinator _correctPermissionsForInternalDirectories]> failed to correct file protection for file %@: %{public}@"
- "-[PBFPosterExtensionStoreCoordinator _correctPermissionsForInternalDirectories]> failed to correct purgability for file %@: %{public}@"
- "-[PBFPosterExtensionStoreCoordinator _correctPermissionsForInternalDirectories]> skipping nonexistent file %@"
- "@\"PFTFuture\"16@?0@\"NSArray\"8"
- "PBF_DATA_STORE_BUILD_MIGRATE_CONFIGS"
- "Post-migration bailed; failed to migrate: %{public}@"
- "Post-migration introspector error: %{public}@"
- "Pre-migration; data store never ever initialized!"
- "[_spinUpExtensionAndMigrate] Migration failed for %{public}@: %{public}@"
- "forceUpdatePosterPath: nil posterUUID"
- "forceUpdatePosterPath: nil posterUUID for %{public}@"
- "forceUpdatePosterPath: timeout waiting for PB completion"
- "itemViewDidAppear for %s"
- "itemViewDidDisappear for %s"
- "v24@?0q8@\"NSError\"16"
```
