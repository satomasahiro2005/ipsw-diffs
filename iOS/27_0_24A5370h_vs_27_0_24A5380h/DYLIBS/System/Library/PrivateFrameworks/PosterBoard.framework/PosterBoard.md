## PosterBoard

> `/System/Library/PrivateFrameworks/PosterBoard.framework/PosterBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26e8fc` | `0x272a9c` | **`+0x41a0`** |
| `__TEXT.__oslogstring` | `0x1ceca` | `0x1db6a` | **`+0xca0`** |
| `__AUTH_CONST.__objc_const` | `0x3d318` | `0x3d940` | **`+0x628`** |
| `__TEXT.__cstring` | `0x14125` | `0x143c5` | **`+0x2a0`** |
| `__DATA_DIRTY.__objc_data` | `0x6c20` | `0x6e98` | **`+0x278`** |
| `__AUTH_CONST.__cfstring` | `0xbf40` | `0xc180` | **`+0x240`** |
| `__DATA_DIRTY.__data` | `0x1348` | `0x1548` | **`+0x200`** |
| `__TEXT.__objc_methlist` | `0xec84` | `0xee5c` | **`+0x1d8`** |
| `__DATA_DIRTY.__bss` | `0x1370` | `0x1520` | **`+0x1b0`** |
| `__DATA.__bss` | `0x30c8` | `0x2f38` | **`-0x190`** |
| `__AUTH.__objc_data` | `0x3cc0` | `0x3b38` | **`-0x188`** |
| `__AUTH_CONST.__const` | `0x90a8` | `0x9230` | **`+0x188`** |
| `__AUTH.__data` | `0x10a0` | `0xfc0` | **`-0xe0`** |
| `__DATA_CONST.__objc_selrefs` | `0x9ae8` | `0x9bc8` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x6b28` | `0x6c00` | **`+0xd8`** |
| `__DATA.__common` | `0x1b0` | `0x130` | **`-0x80`** |
| `__DATA_DIRTY.__common` | `0xd8` | `0x158` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x61bc` | `0x6234` | **`+0x78`** |
| `__TEXT.__swift5_reflstr` | `0x4afe` | `0x4b6e` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x8948` | `0x89b6` | **`+0x6e`** |
| `__TEXT.__swift5_capture` | `0x2574` | `0x25d4` | **`+0x60`** |
| `__TEXT.__ustring` | `0x62` | `0xe` | **`-0x54`** |
| `__TEXT.__swift5_fieldmd` | `0x3054` | `0x3090` | **`+0x3c`** |
| `__TEXT.__gcc_except_tab` | `0x463c` | `0x4604` | **`-0x38`** |
| `__DATA.__objc_ivar` | `0x103c` | `0x105c` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1d88` | `0x1da8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2438` | `0x2450` | **`+0x18`** |
| `__DATA.__data` | `0x62b0` | `0x62a0` | **`-0x10`** |
| `__TEXT.__const` | `0x73c4` | `0x73d4` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x740` | `0x748` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x6c0` | `0x6c8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x3d8` | `0x3e0` | **`+0x8`** |

### Other Changes

```diff

-344.0.101.0.0
+347.102.0.0.0

-  Functions: 10758
-  Symbols:   10981
-  CStrings:  3896
+  Functions: 10824
+  Symbols:   11046
+  CStrings:  3942
Symbols:
+ +[PBFGenericDisplayContext _embeddedDisplayContext]
+ +[PBFGenericDisplayContext augmentDisplayContexts:forRole:userInterfaceStyles:]
+ +[PBFGenericDisplayContext defaultPinnedDisplayContexts]
+ +[PBFGenericDisplayContext displayConfigurationsByType]
+ +[PBFGenericDisplayContext displayContextFromFBSDisplayConfiguration:]
+ +[PBFGenericDisplayContext displayContextsCollapsedToOnePerPhysicalDisplay:]
+ +[PBFGenericDisplayContext embeddedDisplayConfiguration]
+ -[PBFApplicationStateForegroundAssertion initWithMonitor:reason:pinnedDisplayContexts:]
+ -[PBFApplicationStateMonitor acquireForegroundAssertionWithReason:pinnedDisplayContexts:]
+ -[PBFGalleryController _notifyGalleryControllerDidRequestSnapshotRefreshForReason:]
+ -[PBFGalleryViewController initWithNibName:bundle:]
+ -[PBFGenericDisplayContext _lock_displayContextPersistenceIdentifier]
+ -[PBFGenericDisplayContext _lock_hash]
+ -[PBFPendingProactiveSnapshotRefreshPersistence .cxx_destruct]
+ -[PBFPendingProactiveSnapshotRefreshPersistence initWithUserDefaults:]
+ -[PBFPendingProactiveSnapshotRefreshPersistence init]
+ -[PBFPendingProactiveSnapshotRefreshPersistence roles]
+ -[PBFPendingProactiveSnapshotRefreshPersistence setRoles:]
+ -[PBFPosterExtensionDataStore _addPendingProactiveSnapshotRefreshRole:reason:]
+ -[PBFPosterExtensionDataStore _hasPendingProactiveSnapshotRefreshWork]
+ -[PBFPosterExtensionDataStore _kickGallerySnapshotRefreshForRole:powerLogReason:completion:]
+ -[PBFPosterExtensionDataStore _kickGallerySnapshotRefreshFromPendingProactiveRequestsIfNecessary:powerLogReason:context:]
+ -[PBFPosterExtensionDataStore _removePendingProactiveSnapshotRefreshRole:reason:]
+ -[PBFPosterExtensionDataStore _stateLock_savePendingProactiveSnapshotRefreshRoles]
+ -[PBFPosterExtensionDataStore _test_buildSwitcherConfigurationWithContext:]
+ -[PBFPosterExtensionDataStore _test_clearPendingProactiveSnapshotRefreshRoles]
+ -[PBFPosterExtensionDataStore _test_pendingProactiveSnapshotRefreshRoles]
+ -[PBFPosterExtensionDataStore _test_setGalleryConfiguration:forRole:]
+ -[PBFPosterExtensionDataStore _test_setHasBeenUnlockedSinceBoot:]
+ -[PBFPosterExtensionDataStore _test_setIsPrewarming:]
+ -[PBFPosterExtensionDataStore _test_setLastPrewarmRun:]
+ -[PBFPosterExtensionDataStore _test_setPendingProactiveSnapshotRefreshPersistence:]
+ -[PBFPosterExtensionDataStore galleryControllerDidRequestSnapshotRefresh:powerLogReason:]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue refreshPinnedDisplays]
+ -[PBFPosterGalleryPreviewViewController initWithRole:]
+ -[PBFPosterGalleryPreviewViewController role]
+ -[PBFPosterSnapshotManager _lock_beginFinishingActivePUIRequest:]
+ -[PBFPosterSnapshotManager _lock_releaseSnapshotterForOrphanedPUIRequest:]
+ -[PBFPosterSnapshotManager _test_cancelActiveOrphan:]
+ -[PBFPosterSnapshotManager _test_makePUIRequestActive:providerTracker:]
+ -[PBFPosterSnapshotManager _test_simulateSnapshotterCompletionForPUIRequest:]
+ -[_PBFGalleryCollectionViewController initWithCollectionViewLayout:role:]
+ -[_PBFGalleryCollectionViewController role]
+ GCC_except_table107
+ GCC_except_table110
+ GCC_except_table131
+ GCC_except_table142
+ GCC_except_table152
+ GCC_except_table163
+ GCC_except_table180
+ GCC_except_table183
+ GCC_except_table228
+ GCC_except_table255
+ GCC_except_table265
+ GCC_except_table348
+ GCC_except_table355
+ GCC_except_table357
+ GCC_except_table379
+ GCC_except_table392
+ GCC_except_table417
+ GCC_except_table433
+ GCC_except_table447
+ GCC_except_table464
+ GCC_except_table465
+ GCC_except_table466
+ GCC_except_table468
+ GCC_except_table68
+ GCC_except_table72
+ GCC_except_table90
+ _OBJC_CLASS_$_NSThread
+ _OBJC_CLASS_$_PBFPendingProactiveSnapshotRefreshPersistence
+ _OBJC_IVAR_$_PBFGalleryViewController._role
+ _OBJC_IVAR_$_PBFGenericDisplayContext._lock
+ _OBJC_IVAR_$_PBFPendingProactiveSnapshotRefreshPersistence._userDefaults
+ _OBJC_IVAR_$_PBFPosterExtensionDataStore._pendingProactiveSnapshotRefreshPersistence
+ _OBJC_IVAR_$_PBFPosterExtensionDataStore._stateLock_drainingProactiveSnapshotRefreshRoles
+ _OBJC_IVAR_$_PBFPosterExtensionDataStore._stateLock_pendingProactiveSnapshotRefreshRoles
+ _OBJC_IVAR_$_PBFPosterGalleryPreviewViewController._role
+ _OBJC_IVAR_$__PBFGalleryCollectionViewController._role
+ _OBJC_METACLASS_$_PBFPendingProactiveSnapshotRefreshPersistence
+ _PBFAlignmentKeyForPath
+ _PBFDisplayContextUnresolvedFieldCount
+ _PBFSnapshotDefinitionEnumerateSupportedOrientationsForCurrentDeviceClassAndRole
+ _PBFSnapshotDefinitionEnumerateSupportedOrientationsForDeviceClassAndRole
+ __OBJC_$_INSTANCE_METHODS_PBFPendingProactiveSnapshotRefreshPersistence
+ __OBJC_$_INSTANCE_VARIABLES_PBFPendingProactiveSnapshotRefreshPersistence
+ __OBJC_$_PROP_LIST_PBFPendingProactiveSnapshotRefreshPersistence
+ __OBJC_$_PROP_LIST_PBFPendingProactiveSnapshotRefreshPersisting
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_PBFPendingProactiveSnapshotRefreshPersisting
+ __OBJC_$_PROTOCOL_METHOD_TYPES_PBFPendingProactiveSnapshotRefreshPersisting
+ __OBJC_$_PROTOCOL_REFS_PBFPendingProactiveSnapshotRefreshPersisting
+ __OBJC_CLASS_PROTOCOLS_$_PBFPendingProactiveSnapshotRefreshPersistence
+ __OBJC_CLASS_RO_$_PBFPendingProactiveSnapshotRefreshPersistence
+ __OBJC_LABEL_PROTOCOL_$_PBFPendingProactiveSnapshotRefreshPersisting
+ __OBJC_METACLASS_RO_$_PBFPendingProactiveSnapshotRefreshPersistence
+ __OBJC_PROTOCOL_$_PBFPendingProactiveSnapshotRefreshPersisting
+ __PBFSnapshotDefinitionSupportedOrientationsForDeviceClassAndRole
+ __PBFSnapshotDefinitionSupportedOrientationsForDeviceClassAndRole.onceToken
+ __PBFSnapshotDefinitionSupportedOrientationsForDeviceClassAndRole.padSupportedOrientations
+ __PBFSnapshotDefinitionSupportedOrientationsForDeviceClassAndRole.phoneAmbientSupportedOrientations
+ __PBFSnapshotDefinitionSupportedOrientationsForDeviceClassAndRole.phoneSupportedOrientations
+ __PBFSnapshotDefinitionSupportedOrientationsForDeviceClassAndRole.tvSupportedOrientations
+ ___55+[PBFGenericDisplayContext displayConfigurationsByType]_block_invoke
+ ___73-[_PBFGalleryCollectionViewController initWithCollectionViewLayout:role:]_block_invoke
+ ___73-[_PBFGalleryCollectionViewController initWithCollectionViewLayout:role:]_block_invoke_2
+ ___79+[PBFGenericDisplayContext augmentDisplayContexts:forRole:userInterfaceStyles:]_block_invoke
+ ___92-[PBFPosterExtensionDataStore _kickGallerySnapshotRefreshForRole:powerLogReason:completion:]_block_invoke
+ ___92-[PBFPosterExtensionDataStore _kickGallerySnapshotRefreshForRole:powerLogReason:completion:]_block_invoke_2
+ ___PBFSnapshotDefinitionEnumerateSupportedOrientationsForDeviceClassAndRole_block_invoke
+ ____PBFSnapshotDefinitionSupportedOrientationsForDeviceClassAndRole_block_invoke
+ ___block_descriptor_104_e8_32s40s48s56s64s72s80s88s96w_e18_v16?0"NSString"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8w96l8s88l8
+ ___block_descriptor_104_e8_32s40s48s56s64s72s80s88s96w_e33_v16?0"PBFGalleryConfiguration"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8w96l8s88l8
+ ___block_descriptor_48_e8_32s40s_e5_q8?0ls32l8s40l8
+ ___block_descriptor_72_e8_32s40s48s56bs64r_e17_v16?0"NSError"8ls32l8r64l8s40l8s48l8s56l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72w_e17_v16?0"NSError"8lw72l8s32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72s80w_e48_v24?0"PUIPosterSnapshotterResult"8"NSError"16lw80l8s32l8s40l8s48l8s56l8s64l8s72l8
+ ___swift_closure_destructor.137Tm
+ ___swift_closure_destructor.226Tm
+ ___swift_closure_destructor.394Tm
+ ___swift_closure_destructor.682Tm
+ _displayConfigurationsByType.configurationsByType
+ _displayConfigurationsByType.lock
+ _displayConfigurationsByType.onceToken
+ _swift_release_x11
+ _symbolic So24PBFGenericDisplayContextCSg
+ _symbolic So26PBFApplicationStateContextC
+ _symbolic So28PBFApplicationStateComponentCSg
+ _symbolic _____SgXw 11PosterBoard21SwitcherSceneDelegateC
+ _type_layout_string So12PRPosterRolea
- -[PBFGalleryController _notifyGalleryControllerDidRequestSnapshotRefresh]
- -[PBFPosterExtensionDataStore _buildSwitcherConfigurationWithContext:]
- -[PBFPosterExtensionDataStore galleryControllerDidRequestSnapshotRefresh:]
- -[PBFPosterExtensionDataStore pbf_test_setGalleryConfiguration:forRole:]
- -[PBFPosterExtensionDataStore pbf_test_setHasBeenUnlockedSinceBoot:]
- -[PBFPosterExtensionDataStore pbf_test_setLastPrewarmRun:]
- -[PBFPosterGalleryPreviewViewController initWithNibName:bundle:]
- -[_PBFGalleryCollectionViewController initWithCollectionViewLayout:]
- GCC_except_table101
- GCC_except_table109
- GCC_except_table125
- GCC_except_table136
- GCC_except_table144
- GCC_except_table147
- GCC_except_table159
- GCC_except_table176
- GCC_except_table179
- GCC_except_table224
- GCC_except_table252
- GCC_except_table260
- GCC_except_table338
- GCC_except_table345
- GCC_except_table347
- GCC_except_table372
- GCC_except_table385
- GCC_except_table410
- GCC_except_table426
- GCC_except_table440
- GCC_except_table457
- GCC_except_table53
- GCC_except_table57
- GCC_except_table63
- GCC_except_table67
- GCC_except_table92
- _PBFSnapshotDefinitionEnumerateSupportedOrientationsForCurrentDeviceClass
- _PBFSnapshotDefinitionEnumerateSupportedOrientationsForDeviceClass
- __PBFSnapshotDefinitionSupportedOrientationForDeviceClass
- __PBFSnapshotDefinitionSupportedOrientationForDeviceClass.onceToken
- __PBFSnapshotDefinitionSupportedOrientationForDeviceClass.padSupportedOrientations
- __PBFSnapshotDefinitionSupportedOrientationForDeviceClass.phoneSupportedOrientations
- __PBFSnapshotDefinitionSupportedOrientationForDeviceClass.tvSupportedOrientations
- ___140-[PBFPosterExtensionDataStore executeUpdate:hostContext:refreshStrategy:galleryUpdateOptions:powerLogReason:cleanupOldResources:completion:]_block_invoke_2
- ___153-[PBFPosterExtensionDataStoreXPCServiceGlue server:augmentDownloadablePosterMetadataForApp:sandboxExtendedBundleURL:bundleIdentifierOverride:completion:]_block_invoke_7
- ___153-[PBFPosterExtensionDataStoreXPCServiceGlue server:augmentDownloadablePosterMetadataForApp:sandboxExtendedBundleURL:bundleIdentifierOverride:completion:]_block_invoke_8
- ___154-[PBFPosterExtensionDataStore _stateLock_pushUpdateNotificationsForRole:diff:previouslyActiveConfiguration:newActiveConfiguration:options:reason:context:]_block_invoke_4
- ___189-[PBFPosterExtensionDataStore _processGalleryItemRequestsMatchingDescriptorIdentifier:extensionIdentifier:displayContexts:role:loadFromCacheIfAvailable:intention:powerLogReason:completion:]_block_invoke_3
- ___68-[_PBFGalleryCollectionViewController initWithCollectionViewLayout:]_block_invoke
- ___68-[_PBFGalleryCollectionViewController initWithCollectionViewLayout:]_block_invoke_2
- ___74-[PBFPosterExtensionDataStore galleryControllerDidRequestSnapshotRefresh:]_block_invoke
- ___83-[PBFPosterExtensionDataStore importPosterConfigurationFromArchiveData:completion:]_block_invoke_2
- ___89-[PBFPosterExtensionDataStore refreshSnapshotForPosterConfigurationMatchUUID:completion:]_block_invoke_4
- ___PBFSnapshotDefinitionEnumerateSupportedOrientationsForDeviceClass_block_invoke
- ____PBFSnapshotDefinitionSupportedOrientationForDeviceClass_block_invoke
- ___block_descriptor_56_e8_32s40s48r_e17_v16?0"NSError"8ls32l8s40l8r48l8
- ___block_descriptor_56_e8_32s40s48r_e5_v8?0ls32l8r48l8s40l8
- ___block_descriptor_64_e8_32s40s48s56r_e17_v16?0"NSError"8ls32l8s40l8s48l8r56l8
- ___block_descriptor_80_e8_32s40s48s56s64s72w_e48_v24?0"PUIPosterSnapshotterResult"8"NSError"16lw72l8s32l8s40l8s48l8s56l8s64l8
- ___block_descriptor_88_e8_32s40s48s56s64s72s80r_e33_v16?0"PBFGalleryConfiguration"8ls32l8s40l8s48l8s56l8s64l8r80l8s72l8
- ___block_descriptor_96_e8_32s40s48s56s64s72s80s88r_e18_v16?0"NSString"8ls32l8s40l8s48l8s56l8s64l8s72l8r88l8s80l8
- ___swift_closure_destructor.225Tm
- ___swift_closure_destructor.393Tm
- ___swift_closure_destructor.681Tm
- _swift_willThrowTypedImpl
- _type_layout_string So36PRPosterSnapshotDefinitionIdentifiera
CStrings:
+ "%@ phase %@ no requests to fan out"
+ "%@ phase %@ snapshot fanout success"
+ "(%{public}@) data is fresh, but pending proactive snapshot-refresh roles exist; proceeding so the deferred work can run"
+ "(%{public}@) phase %{public}@ role %{public}@ galleryConfiguration has %lu sections, %lu display contexts to process"
+ "(%{public}@) phase %{public}@ role %{public}@ no snapshot requests to prewarm - all fulfilled or none generated"
+ "(%{public}@) phase %{public}@ role %{public}@ prewarmSnapshotsForRequests completed successfully for %lu requests"
+ "(%{public}@) phase %{public}@ role %{public}@ prewarmSnapshotsForRequests completed with error: %{public}@"
+ "(%{public}@) phase %{public}@ role %{public}@ prewarming gallery snapshots: %lu total requests"
+ "Added pending proactive snapshot refresh for role %{public}@ — reason: %{public}@"
+ "Attempted to decrement running snapshotters below 0 while releasing orphaned PUI request"
+ "Failed to prewarm gallery snapshots for role %{public}@: exceeded prewarm time; invalidating runtime assertion."
+ "Found %lu role(s) with deferred proactive snapshot refresh from previous session: %{public}@"
+ "Gallery controller requested snapshot prewarm for role: %{public}@ (reason: %{public}@)"
+ "PBFPendingProactiveSnapshotRefreshPersistence.m"
+ "PBFPendingProactiveSnapshotRefreshRoles"
+ "Proactive gallery push for role %{public}@; midPrewarm=%{BOOL}u withinPostPrewarmWindow=%{BOOL}u — proceeding with snapshot fanout."
+ "Proactive gallery push for role %{public}@; not mid-prewarm and outside %.0fs post-prewarm window (last prewarm: %{public}@) — deferring snapshot work; newlyAdded=%{BOOL}u"
+ "Refresh-if-necessary for role '%{public}@' (%{public}@): pending=%{BOOL}u alreadyDraining=%{BOOL}u → %{public}@"
+ "Removed pending proactive snapshot refresh for role %{public}@ — reason: %{public}@"
+ "Snapshot fanout exceeded 120s; timed out."
+ "Unable to determine display configurations; bailing"
+ "[%s] Scene disconnecting - tearing down lock cells before releasing window"
+ "[%{public}@] Gallery updated; triggering snapshot refresh for gallery items (reason: %{public}@)"
+ "[_checkIfLanguageChangeOccurred] current=%{public}@ vs stashed=%{public}@ -> languageChanged=%d"
+ "[_checkIfLanguageChangeOccurred] no stashed locale identifier; recovering a baseline from the newest usable gallery layout"
+ "[_checkIfLanguageChangeOccurred] sticky pbf_snapshotsLocaleDidChange flag is set; reporting languageChanged=YES"
+ "[_localeDidChange] 1s elapsed without clean exit; force path: xpc_transaction_try_exit_clean() then exit(0)."
+ "[_localeDidChange] Calling xpc_transaction_exit_clean() (armed 1s force-exit fallback)..."
+ "[_localeDidChange] LANGUAGE CHANGE detected (stashed=%{public}@ -> current=%{public}@); tearing down: invalidate dataModel XPC server + cancel data store, then xpc_transaction_exit_clean() to relaunch."
+ "[_localeDidChange] cancelling long-running data store work (acquiring service _lock)..."
+ "[_localeDidChange] data store cancelled; service _lock released."
+ "[_localeDidChange] dataModel XPC server invalidated."
+ "[_localeDidChange] invalidating dataModel XPC server (_server=%{public}@)..."
+ "[_localeDidChange] language unchanged (current=%{public}@ == stashed=%{public}@); NOT tearing down the dataModel XPC server."
+ "[_localeDidChange] notification received: current=%{public}@ stashed=%{public}@ stickyDidChangeFlag=%d -> languageChangeOccurred=%d"
+ "[_localeDidChange] xpc_transaction_exit_clean() RETURNED without exiting (process not yet quiescent); awaiting quiescence or the 1s force-exit timer."
+ "augmentDownloadablePosterMetadataForApp: no embedded display context; skipping orientation %ld"
+ "b[%@]-f[%@]-s[%f]-o[%lu]-ui[%lu]-ax[%lu]-dt[%@]-dc[%lu]-ao[%lu]"
+ "cancelRequests: No more active work for alignment key %{public}@, invalidating orphaned snapshotter"
+ "cancelRequests: No more active work for alignment key %{public}@, releasing orphaned snapshotter for reuse"
+ "cancelRequests: alignment key %{public}@ still in use by another active request, keeping snapshotter"
+ "display context could not be hydrated"
+ "displayConfigurationsByType"
+ "displayContextForDisplayIdentifier: no configuration for display identity %{public}@"
+ "displayContextForPRSDisplayInfo: invalid frame %{public}@"
+ "displayContextForWallpaperDisplayPin: no configuration for display identity %{public}@"
+ "displayContextForWallpaperDisplayPin: pin carries neither a configuration nor a display identity"
+ "displayContextFromFBSDisplayConfiguration: invalid geometry referenceBounds=%{public}@ frame=%{public}@ scale=%f"
+ "drain already in flight, no-op"
+ "draining deferred proactive snapshot fanout"
+ "enterPosterSwitcher"
+ "enterPosterSwitcherForRole:'%{public}@' — gallery has %lu items across %lu sections; EMPTY → kicking prewarm"
+ "enterPosterSwitcherForRole:'%{public}@' — gallery has %lu items across %lu sections; populated → checking for deferred proactive snapshot fanout"
+ "geo:%@:%g"
+ "kickoff: Provider %{public}@ entered crash cooldown (>=3 snapshot failures within %.0fs) — pausing its non-visible posters"
+ "no pending fanout, no-op"
+ "persistence"
+ "proactive push deferred (lastPrewarmRun=%@)"
+ "role != nil"
+ "snapshot fanout success"
+ "snapshots for %@ cannot be updated until display contexts are available"
+ "unable to ascertain display context for prewarm"
+ "updatePinnedDisplays: rebuilt pinned-context set was empty (embedded context unavailable); retaining prior pinned component"
+ "userDefaults"
+ "\xf0\xf0\xf0\xc2"
- "(%{public}@) phase %{public}@ galleryConfiguration has %lu sections, %lu display contexts to process"
- "(%{public}@) phase %{public}@ prewarming gallery snapshots: %lu total requests"
- "Checking current locale: %{public}@ vs stashed locale: %{public}@"
- "EMPTY → kicking prewarm"
- "Gallery controller requested snapshot prewarm for role: %{public}@"
- "No more work for alignment key %{public}@, releasing snapshotter"
- "Role %{public}@ exceeded prewarm time; invalidating runtime assertion."
- "[%{public}@] Gallery updated; triggering snapshot refresh for gallery items"
- "[_localeDidChange] Calling xpc_transaction_exit_clean()"
- "[_localeDidChange] Locale changes did occur; cancelling long running operation and preparing for xpc_transaction_exit_clean()"
- "[_localeDidChange] Second time calling xpc_transaction_exit_clean()"
- "[_localeDidChange] XPC server invalidated, data store cancelled long running.  Calling xpc_transaction_exit_clean()"
- "b[%@]-f[%@]-s[%f]-o[%lu]-ui[%lu]-ax[%lu]-dt[%@]-dc[%lu]-ao[%lu]-sa[%@]"
- "displayContextForPRSDisplayInfo: displayContextForDisplayConfiguration returned nil, falling back to scalar construction"
- "enterPosterSwitcherForRole:'%{public}@' — gallery has %lu items across %lu sections; %{public}@"
- "populated → no-op"
- "prewarmGallerySnapshotRequestsForDisplayContext: %lu total sections, %lu sections for prewarm (skipFirst: %{BOOL}d), maxPerSection: %lu, maxTotal: %lu"
- "prewarmGallerySnapshotRequestsForDisplayContext: reached maxItemsToPrewarm (%lu), stopping early"
- "\xf0\xf0\xf0\xb2"
```
