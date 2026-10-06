## iCloudDriveCore

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/iCloudDriveCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x303850` | `0x306a58` | **`+0x3208`** |
| `__TEXT.__oslogstring` | `0x3d665` | `0x3db8d` | **`+0x528`** |
| `__TEXT.__gcc_except_tab` | `0x173a8` | `0x17698` | **`+0x2f0`** |
| `__TEXT.__cstring` | `0x82331` | `0x825b9` | **`+0x288`** |
| `__AUTH_CONST.__objc_const` | `0x41890` | `0x419f0` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0x1bd24` | `0x1be28` | **`+0x104`** |
| `__TEXT.__unwind_info` | `0xa340` | `0xa3f0` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x9da8` | `0x9e48` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x234a0` | `0x23520` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x2c68` | `0x2cc8` | **`+0x60`** |
| `__DATA.__data` | `0x2990` | `0x29f0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xf0c8` | `0xf128` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0xda8` | `0xd98` | **`-0x10`** |
| `__DATA.__bss` | `0x1f0` | `0x200` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x438` | `0x428` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x201c` | `0x2028` | **`+0xc`** |
| `__DATA_CONST.__objc_protolist` | `0x2b8` | `0x2c0` | **`+0x8`** |

### Other Changes

```diff

-5044.0.0.0.0
+5140.0.0.0.0

-  Functions: 14169
-  Symbols:   18202
-  CStrings:  12090
+  Functions: 14204
+  Symbols:   18237
+  CStrings:  12123
Symbols:
+ +[AppTelemetryTimeSeriesEvent(BRCAdditions) _newTelemetryEventWithIdentifier:zoneWithMangledID:enhancedDrivePrivacyEnabled:error:errorDescription:itemIDString:reason:]
+ +[AppTelemetryTimeSeriesEvent(BRCAdditions) newNonSandboxedIPCAccessEventForCheck:bundleID:]
+ +[AppTelemetryTimeSeriesEvent(BRCAdditions) newTelemetryEventWithIdentifier:reason:]
+ +[BRCServerChangesApplyUtil checkEarlyExitsPriorToUploadV2Applying:si:rank:scheduler:zone:diffs:]
+ +[CKRecord(BRCSerializationAdditions) _newFromSqliteBlobBytes:length:source:]
+ -[BRCAccountHandler description]
+ -[BRCAccountSession flushWithoutPersonaCheck]
+ -[BRCAccountSession getUserDefaultsForZoneName:ownerName:]
+ -[BRCAccountSession updateUploadedBytesWithSize:forItemIdentifiers:zoneName:ownerName:]
+ -[BRCAccountSession(IPCTelemetry) postNonSandboxedIPCCheckTelemetry:bundleID:]
+ -[BRCApplyScheduler _handleUploadV2WaitForServerUpdateWithLocalItem:serverItem:jobID:rank:zone:]
+ -[BRCBarrier description]
+ -[BRCClientPrivilegesDescriptor applicationName]
+ -[BRCDeviceConfiguration _isInSycnBubble]
+ -[BRCDirectoryItem(FPFSAdditions) revertFailedCrossZoneMoveIfNeeded]
+ -[BRCDocumentItem setCurrentVersion:]
+ -[BRCDocumentItem(BRCFPFSAdditions) revertFailedCrossZoneMoveIfNeeded]
+ -[BRCLocalItem revertFailedCrossZoneMoveIfNeeded]
+ -[BRCLocalVersion initWithServerVersion:replacingLocalVersion:uploadV2Enabled:]
+ -[BRCLocalVersion(BRCFPFSAdditions) clearPreviousItemGlobalID]
+ -[BRCTransferBatchOperation transferItemsWithCompletionHandler:]
+ -[BRCUploadConstraintChecker _resetAvailableSizeForUpload]
+ -[BRCUploadConstraintChecker _reset]
+ -[BRCUploadConstraintChecker updateWithUploadedBytesSize:uploadedItemIDs:]
+ -[BRCUserDefaults blockedThumbnailExtensions]
+ -[BRCUserDefaults recursiveOperationsDatabaseBatchSize]
+ -[BRCUserDefaults waitForSessionDBLoadingBarrierTimeoutInterval]
+ GCC_except_table111
+ GCC_except_table119
+ GCC_except_table132
+ GCC_except_table136
+ GCC_except_table149
+ GCC_except_table151
+ GCC_except_table152
+ GCC_except_table155
+ GCC_except_table158
+ GCC_except_table165
+ GCC_except_table168
+ GCC_except_table175
+ GCC_except_table182
+ GCC_except_table190
+ GCC_except_table195
+ GCC_except_table204
+ GCC_except_table214
+ GCC_except_table248
+ GCC_except_table257
+ GCC_except_table260
+ GCC_except_table298
+ GCC_except_table300
+ GCC_except_table331
+ GCC_except_table333
+ GCC_except_table337
+ GCC_except_table399
+ GCC_except_table408
+ GCC_except_table413
+ GCC_except_table418
+ GCC_except_table429
+ GCC_except_table432
+ GCC_except_table435
+ GCC_except_table441
+ GCC_except_table443
+ GCC_except_table445
+ GCC_except_table452
+ GCC_except_table456
+ GCC_except_table458
+ GCC_except_table462
+ GCC_except_table466
+ GCC_except_table468
+ GCC_except_table470
+ GCC_except_table472
+ GCC_except_table474
+ GCC_except_table478
+ GCC_except_table480
+ GCC_except_table484
+ GCC_except_table485
+ GCC_except_table96
+ _AGE_MIGRATION_LOCALIZATION_TABLE_block_invoke_2.__personaOnceToken
+ _AGE_MIGRATION_LOCALIZATION_TABLE_block_invoke_2.__personalPersona
+ _OBJC_IVAR_$_BRCAccountSession._ignorePersonaCheckOnMutexLock
+ _OBJC_IVAR_$_BRCSharingProcessFolderSubitemsOperation._czmGroup
+ _OBJC_IVAR_$_BRCStageRegistry._backupExclusionQueue
+ __OBJC_$_CLASS_METHODS_BRCAccountSession(OfflineInitialization|BRCDatabaseManager|BRCZoneMigration|DatabaseAdditions|DatabaseMigrationHelpers|FPFSAdditions|BRCContainerFindByName|IPCTelemetry|ItemFetching)
+ __OBJC_$_INSTANCE_METHODS_BRCAccountSession(OfflineInitialization|BRCDatabaseManager|BRCZoneMigration|DatabaseAdditions|DatabaseMigrationHelpers|FPFSAdditions|BRCContainerFindByName|IPCTelemetry|ItemFetching)
+ __OBJC_$_PROP_LIST_iCDUserDefaults
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_iCDUserDefaults
+ __OBJC_$_PROTOCOL_METHOD_TYPES_iCDUserDefaults
+ __OBJC_$_PROTOCOL_REFS_iCDUserDefaults
+ __OBJC_CLASS_PROTOCOLS_$_BRCUserDefaults
+ __OBJC_LABEL_PROTOCOL_$_iCDUserDefaults
+ __OBJC_PROTOCOL_$_iCDUserDefaults
+ ___25-[BRCStageRegistry close]_block_invoke_2
+ ___29-[BRCAccountMigrator perform]_block_invoke_2
+ ___45-[BRCAccountSession flushWithoutPersonaCheck]_block_invoke
+ ___48-[BRCAccountSession openWithError:pushWorkloop:]_block_invoke_2
+ ___48-[BRCAccountSession openWithError:pushWorkloop:]_block_invoke_3
+ ___48-[BRCAccountSession openWithError:pushWorkloop:]_block_invoke_4
+ ___53-[BRCXPCRegularIPCsClient _t_canReadFileAtURL:reply:]_block_invoke
+ ___64-[BRCTransferBatchOperation transferItemsWithCompletionHandler:]_block_invoke
+ ___block_descriptor_120_e8_32s40s48s56s64s72s80s88bs96r104r_e5_v8?0ls32l8s40l8s48l8s56l8s88l8s64l8r96l8s72l8s80l8r104l8
+ ___block_descriptor_144_e8_32s40s48s56s64s72s80s88bs96r104r112r120r_e5_v8?0ls32l8r96l8s40l8r104l8s48l8s56l8s64l8r112l8s72l8s80l8r120l8s88l8
+ ___block_descriptor_160_e8_32s40s48s56s64s72s80s88s96bs104r112r120r128r136r144r_e42_v16?0"BRCReadWriteClientDatabaseFacade"8ls32l8r104l8r112l8r120l8s40l8r128l8s48l8s56l8s96l8s64l8s72l8s80l8r136l8s88l8r144l8
+ ___block_descriptor_161_e8_32s40s48s56s64s72s80s88s96s104s112s120bs128r_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s120l8s88l8s96l8s104l8s112l8r128l8
+ ___block_descriptor_168_e8_32s40s48s56s64s72s80s88s96s104bs112r120r128r136r144r152r_e5_B8?0ls32l8r112l8r120l8r128l8s40l8r136l8s48l8s56l8s104l8s64l8s72l8s80l8s88l8r144l8s96l8r152l8
+ ___block_descriptor_168_e8_32s40s48s56s64s72s80s88s96s104s112s120s128bs136r144r_e5_v8?0ls32l8s40l8s48l8s56l8r136l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8r144l8s128l8s120l8
+ ___block_descriptor_48_e8_32s40w_e40_v24?0"CKOperationMetrics"8"NSError"16lw40l8s32l8
+ ___block_descriptor_48_e8_32s40w_e8_v16?0q8lw40l8s32l8
+ ___block_descriptor_56_e8_32s40s48s_e17_v16?0"NSArray"8ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e28_v24?0"NSData"8"NSError"16ls32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40bs48r56r64r_e17_v16?0"NSError"8lr48l8r56l8r64l8s32l8s40l8
+ ___block_descriptor_80_e8_32s40bs48r56r64r72r_e39_v36?0"BRQueryItem"8Q16B24"NSError"28lr48l8r56l8r64l8s32l8r72l8s40l8
+ ___block_descriptor_80_e8_32s40s48s56bs64r72r_e39_v36?0"BRQueryItem"8Q16B24"NSError"28lr64l8r72l8s32l8s40l8s48l8s56l8
+ ___block_descriptor_80_e8_32s40s48s56s64bs72r_e20_v24?08"NSError"16lr72l8s32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_88_e8_32s40s48s56bs64r72r_e48_v36?0"<NSFileProviderItem>"8Q16B24"NSError"28ls32l8r64l8s40l8s48l8r72l8s56l8
+ ___block_descriptor_88_e8_32s40s48s56s64bs72r_e17_v16?0"NSError"8ls32l8s40l8s48l8r72l8s64l8s56l8
+ ___block_descriptor_96_e8_32s40s48s56s64s72s80bs88r_e23_v16?0"BRCServerItem"8lr88l8s32l8s40l8s48l8s56l8s80l8s64l8s72l8
+ ___block_descriptor_97_e8_32s40s48s56s64s72bs80r_e48_v36?0"<NSFileProviderItem>"8Q16B24"NSError"28ls32l8s72l8s40l8s48l8s56l8s64l8r80l8
+ __xpc_type_data
+ _dispatch_barrier_sync
+ _objc_release_x3
+ _xpc_data_get_bytes_ptr
+ _xpc_data_get_length
- -[BRCAccountSession isDamagedDocumentOnDiskWithContentURL:]
- -[BRCAccountSession recoverDamagedDocumentOnDiskForItemIdentifier:zoneName:ownerName:completionHandler:]
- -[BRCAppLibrary _addTargetSharedServerZoneForSharedItem:]
- -[BRCDeviceConfiguration _isIsSycBubble]
- -[BRCFSImporter _ttrImportingPackageAsRegularFileWithTemplateItem:]
- -[BRCFSUploader resetAndRescheduleUploaderConstraintCheckerIfNeeded]
- -[BRCLocalVersion initWithServerVersion:]
- -[BRCUploadConstraintChecker updateWithUploadedBytesSize:forItemID:]
- -[BRCUserDefaults blacklistedThumbnailExtensions]
- -[BRCXPCRegularIPCsClient lookupMinFileSizeForThumbnailTransferWithReply:]
- GCC_except_table104
- GCC_except_table108
- GCC_except_table120
- GCC_except_table130
- GCC_except_table135
- GCC_except_table147
- GCC_except_table157
- GCC_except_table166
- GCC_except_table173
- GCC_except_table176
- GCC_except_table177
- GCC_except_table181
- GCC_except_table193
- GCC_except_table199
- GCC_except_table209
- GCC_except_table243
- GCC_except_table250
- GCC_except_table252
- GCC_except_table254
- GCC_except_table256
- GCC_except_table295
- GCC_except_table326
- GCC_except_table328
- GCC_except_table395
- GCC_except_table400
- GCC_except_table409
- GCC_except_table414
- GCC_except_table417
- GCC_except_table428
- GCC_except_table431
- GCC_except_table433
- GCC_except_table447
- GCC_except_table451
- GCC_except_table453
- GCC_except_table457
- GCC_except_table461
- GCC_except_table463
- GCC_except_table465
- GCC_except_table467
- GCC_except_table469
- GCC_except_table471
- GCC_except_table475
- GCC_except_table477
- GCC_except_table479
- GCC_except_table481
- __OBJC_$_CLASS_METHODS_BRCAccountSession(OfflineInitialization|BRCDatabaseManager|BRCZoneMigration|DatabaseAdditions|DatabaseMigrationHelpers|FPFSAdditions|BRCContainerFindByName|ItemFetching)
- __OBJC_$_INSTANCE_METHODS_BRCAccountSession(OfflineInitialization|BRCDatabaseManager|BRCZoneMigration|DatabaseAdditions|DatabaseMigrationHelpers|FPFSAdditions|BRCContainerFindByName|ItemFetching)
- ___104-[BRCAccountSession recoverDamagedDocumentOnDiskForItemIdentifier:zoneName:ownerName:completionHandler:]_block_invoke
- ___24-[BRCStageRegistry open]_block_invoke_3
- ___26-[BRCDaemon exitWithCode:]_block_invoke_2
- ___39-[BRCAppUpdateEvent initWithXPCObject:]_block_invoke
- ___57-[BRCAppLibrary _addTargetSharedServerZoneForSharedItem:]_block_invoke
- ___74-[BRCXPCRegularIPCsClient lookupMinFileSizeForThumbnailTransferWithReply:]_block_invoke
- ___block_descriptor_105_e8_32s40s48s56s64s72s80bs88r_e48_v36?0"<NSFileProviderItem>"8Q16B24"NSError"28ls32l8s80l8s40l8s48l8s56l8s64l8s72l8r88l8
- ___block_descriptor_120_e8_32s40s48s56s64s72s80s88s96bs104r_e5_v8?0ls32l8s40l8s48l8s56l8s96l8s64l8s72l8s80l8s88l8r104l8
- ___block_descriptor_152_e8_32s40s48s56s64s72s80s88s96bs104r112r120r128r_e5_v8?0ls32l8r104l8s40l8r112l8s48l8s56l8s64l8s72l8s80l8r120l8s88l8r128l8s96l8
- ___block_descriptor_168_e8_32s40s48s56s64s72s80s88s96s104s112bs120r128r136r144r152r_e5_B8?0ls32l8r120l8r128l8r136l8s40l8r144l8s48l8s56l8s112l8s64l8s72l8s80l8s88l8s96l8s104l8r152l8
- ___block_descriptor_168_e8_32s40s48s56s64s72s80s88s96s104s112s120s128s136bs144r_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8s120l8r144l8s136l8s128l8
- ___block_descriptor_169_e8_32s40s48s56s64s72s80s88s96s104s112s120s128bs136r_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s128l8s88l8s96l8s104l8s112l8s120l8r136l8
- ___block_descriptor_40_e8_32s_e36_B24?0Q8"NSObject<OS_xpc_object>"16ls32l8
- ___block_descriptor_40_e8_32w_e8_v16?0q8lw32l8
- ___block_descriptor_56_e8_32bs40r48r_e17_v16?0"NSError"8lr40l8r48l8s32l8
- ___block_descriptor_56_e8_32bs40r48r_e39_v36?0"BRQueryItem"8Q16B24"NSError"28lr40l8r48l8s32l8
- ___block_descriptor_56_e8_32s40s48w_e40_v24?0"CKOperationMetrics"8"NSError"16lw48l8s32l8s40l8
- ___block_descriptor_64_e8_32bs40r48r56r_e39_v36?0"BRQueryItem"8Q16B24"NSError"28lr40l8r48l8r56l8s32l8
- ___block_descriptor_96_e8_32s40s48s56s64bs72r80r_e48_v36?0"<NSFileProviderItem>"8Q16B24"NSError"28ls32l8s40l8s48l8r72l8s56l8r80l8s64l8
- ___block_descriptor_96_e8_32s40s48s56s64s72bs80r_e17_v16?0"NSError"8ls32l8s40l8s48l8s56l8r80l8s72l8s64l8
- __xpc_type_string
- _open.backupExclusionQueue
- _open.onceToken
- _voucher_process_can_use_arbitrary_personas
- _xpc_array_apply
- _xpc_dictionary_get_array
- _xpc_dictionary_get_bool
- _xpc_dictionary_get_dictionary
- _xpc_string_get_string_ptr
CStrings:
+ " AND (IFNULL(shared_alias_count, 1) > 0 OR item_type = 3)"
+ " AND (IFNULL(shared_children_count, 1) > 0 OR (item_sharing_options & 4) > 0)"
+ " AND (IFNULL(shared_children_count, 1) > 0 OR IFNULL(shared_alias_count, 1) > 0 OR item_type = 3 OR (item_sharing_options & 4) > 0)"
+ "((item_sharing_options & 4) != 0 OR item_parent_zone_rowid != zone_rowid)"
+ "+[CKRecord(BRCSerializationAdditions) _newFromSqliteBlobBytes:length:source:]"
+ "-[BRCAccountHandler waitForSessionDBLoadingBarrier]"
+ "-[BRCAccountSession openWithError:pushWorkloop:]_block_invoke_4"
+ "-[BRCAccountSession updateUploadedBytesWithSize:forItemIdentifiers:zoneName:ownerName:]"
+ "-[BRCApplyScheduler _handleUploadV2WaitForServerUpdateWithLocalItem:serverItem:jobID:rank:zone:]"
+ "-[BRCDirectoryItem(FPFSAdditions) revertFailedCrossZoneMoveIfNeeded]"
+ "-[BRCDocumentItem(BRCFPFSAdditions) revertFailedCrossZoneMoveIfNeeded]"
+ "-[BRCStageRegistry open]_block_invoke_2"
+ "-[BRCUploadConstraintChecker updateWithUploadedBytesSize:uploadedItemIDs:]"
+ "-[BRCXPCRegularIPCsClient _t_canReadFileAtURL:reply:]_block_invoke"
+ "-[BRCXPCRegularIPCsClient(FPFSAdditions) unboostFilePresenterForItemIdentifiers:reply:]_block_invoke"
+ "<%@:%p '%@'>"
+ "<%@:%p aid: %@>"
+ "<%@:%p dsid: %@>"
+ "J"
+ "NON_SANDBOXED_APP_IPC_ACCESS"
+ "SELECT ci.rowid, ci.zone_rowid, ci.item_id, ci.item_creator_id, ci.item_sharing_options, ci.item_side_car_ckinfo, ci.item_parent_zone_rowid, ci.item_localsyncupstate, ci.item_local_diffs, ci.item_notifs_rank, ci.app_library_rowid, ci.item_min_supported_os_rowid, ci.item_user_visible, ci.item_stat_ckinfo, ci.item_state, ci.item_type, ci.item_mode, ci.item_birthtime, ci.item_lastusedtime, ci.item_favoriterank,ci.item_parent_id, ci.item_filename, ci.item_hidden_ext, ci.item_finder_tags, ci.item_xattr_signature, ci.item_trash_put_back_path, ci.item_trash_put_back_parent_id, ci.item_alias_target, ci.item_creator, ci.item_processing_stamp, ci.item_bouncedname, ci.item_scope, ci.item_local_change_count, ci.item_old_version_identifier, ci.fp_creation_item_identifier, ci.version_name, ci.version_ckinfo, ci.version_mtime, ci.version_size, ci.version_thumb_size, ci.version_thumb_signature, ci.version_content_signature, ci.version_xattr_signature, ci.version_edited_since_shared, ci.version_device, ci.version_conflict_loser_etags, ci.version_quarantine_info, ci.version_uploaded_assets, ci.version_upload_error, ci.version_old_zone_item_id, ci.version_old_zone_rowid, ci.version_local_change_count, ci.version_old_version_identifier, ci.item_live_conflict_loser_etags, ci.item_file_id, ci.item_generation FROM client_items AS ci WHERE ci.item_localsyncupstate = 1 AND ci.item_localsyncupstate != 0 AND NOT EXISTS (SELECT 1 FROM client_unapplied_table AS cu WHERE cu.throttle_id = -ci.rowid   AND cu.throttle_state != 0)"
+ "UPDATE client_items SET item_parent_id = %@, item_parent_zone_rowid = %@ WHERE item_parent_id = %@ AND item_parent_zone_rowid = %@"
+ "[CRIT] Assertion failed: containerIdentifier%@"
+ "[CRIT] Assertion failed: item.syncUpState == BRC_SUS_WAIT_FOR_SERVER_UPDATE%@"
+ "[CRIT] UNREACHABLE: Failed to adopt persona for block adoption: %@%@"
+ "[CRIT] UNREACHABLE: No itemID for %@%@"
+ "[CRIT] UNREACHABLE: This is for uploadv2 only%@"
+ "[DEBUG] %@ - Account hasn't really changed, do nothing%@"
+ "[DEBUG] %@ - Cleaning up previous session belonging to account %@, to make room for new account %@%@"
+ "[DEBUG] %@ - Cleaning up session on disk belonging to account %@%@"
+ "[DEBUG] %@ - Done Waiting for barrier with result %@%@"
+ "[DEBUG] %@ - Exit bird without panic%@"
+ "[DEBUG] %@ - Failed adding FPFS domain. Skipping database reset and trying to open again%@"
+ "[DEBUG] %@ - Failed import FPFS domain. Skipping database reset and trying to open again%@"
+ "[DEBUG] %@ - Initialized%@"
+ "[DEBUG] %@ - Loading account session...%@"
+ "[DEBUG] %@ - Local session state has been resetted, try opening the session for the second time%@"
+ "[DEBUG] %@ - Looks like we hit disk space issue on second try --> don't panic or exit%@"
+ "[DEBUG] %@ - Signalling and retaking barrier%@"
+ "[DEBUG] %@ - Signalling barrier%@"
+ "[DEBUG] %@ - Starting up at %@%@"
+ "[DEBUG] %@ - Waiting for barrier%@"
+ "[DEBUG] %@ - Waiting for session %p%@"
+ "[DEBUG] %@ - sending apps account change notification%@"
+ "[DEBUG] AvailableSizeForUpload %lld -> %lld%@"
+ "[DEBUG] Detected shared bookmark (DeletionConflicted), redirecting to trash in private zone for %@%@"
+ "[DEBUG] Finished waiting for changes under container %@ - %@%@"
+ "[DEBUG] Not inserting tombstone for previous zone globalID in uploadv2%@"
+ "[DEBUG] Using sync engine to modify item %@ %@ %@ %@%@"
+ "[DEBUG] serverItem is nil for %@, waiting for sync-down before PCS chaining%@"
+ "[DEBUG] ┏%llx %@ - creating account for %@%@"
+ "[DEBUG] ┏%llx %@ - creating account session for %@%@"
+ "[DEBUG] ┏%llx %@ - destroying account for %@%@"
+ "[ERROR] %@ - %@%@"
+ "[ERROR] %@ - Capturing account session second open error: %@%@"
+ "[ERROR] %@ - Failed to open account session second time%@"
+ "[ERROR] %@ - Failed to open account session: %@%@"
+ "[ERROR] %@ - Failed to open account session: Exception [%@]%@"
+ "[ERROR] %@ - Your database is from the future, disabling iCloud Drive (%@)%@"
+ "[ERROR] failed to unarchive CKRecord from sqlite blob: %@%@"
+ "[ERROR] nonexistent container%@"
+ "[ERROR] sync-down failed while waiting for server item: %@%@"
+ "[NOTICE] %@ - now using account %@%@"
+ "[NOTICE] %@ - stop using account %@%@"
+ "[WARNING] %@ - Capturing account session open error of the first try: %@%@"
+ "[WARNING] %@ - we are already logged in %@%@"
+ "[WARNING] %@ is missing an identifier%@"
+ "[WARNING] Failed to deserialize XPCEvent UserInfo: %@%@"
+ "[WARNING] Record fetched from our DB is nil, reingesting the item%@"
+ "[WARNING] Reverted failed CZM pre-mark for %@%@"
+ "[WARNING] Reverting failed CZM pre-mark for directory %@ back to %@ in zone %@%@"
+ "[WARNING] Reverting failed CZM pre-mark for document %@ back to %@ in zone %@%@"
+ "[WARNING] Source server item not found for CZM revert of %@, cannot revert%@"
+ "[WARNING] UserInfo bundleIDs field is not an array%@"
+ "[WARNING] UserInfo has no field called bundleIDs%@"
+ "[WARNING] UserInfo has no field called isPlaceholder%@"
+ "[WARNING] XPCEvent UserInfo is not data%@"
+ "[WARNING] XPCEvent has no field called UserInfo%@"
+ "[WARNING] unable to find bundleID%@"
+ "com.apple.distnoted.matching.trusted"
+ "recursive-operations.database-batch-size"
+ "statement"
+ "v16@?0@\"BRCServerItem\"8"
+ "wait-for-session-DB-loading-barrier-timeout-interval"
- " AND (IFNULL(shared_children_count, 1) > 0 OR IFNULL(shared_alias_count, 1) > 0)"
- " AND IFNULL(shared_alias_count, 1) > 0"
- " AND IFNULL(shared_children_count, 1) > 0"
- "-[BRCAccountSession isDamagedDocumentOnDiskWithContentURL:]"
- "-[BRCAccountSession recoverDamagedDocumentOnDiskForItemIdentifier:zoneName:ownerName:completionHandler:]"
- "-[BRCStageRegistry open]_block_invoke_3"
- "-[BRCXPCRegularIPCsClient lookupMinFileSizeForThumbnailTransferWithReply:]"
- "-[BRCXPCRegularIPCsClient lookupMinFileSizeForThumbnailTransferWithReply:]_block_invoke"
- "B24@?0Q8@\"NSObject<OS_xpc_object>\"16"
- "Detected an attempt to import a package as a regular file"
- "SELECT ci.rowid, ci.zone_rowid, ci.item_id, ci.item_creator_id, ci.item_sharing_options, ci.item_side_car_ckinfo, ci.item_parent_zone_rowid, ci.item_localsyncupstate, ci.item_local_diffs, ci.item_notifs_rank, ci.app_library_rowid, ci.item_min_supported_os_rowid, ci.item_user_visible, ci.item_stat_ckinfo, ci.item_state, ci.item_type, ci.item_mode, ci.item_birthtime, ci.item_lastusedtime, ci.item_favoriterank,ci.item_parent_id, ci.item_filename, ci.item_hidden_ext, ci.item_finder_tags, ci.item_xattr_signature, ci.item_trash_put_back_path, ci.item_trash_put_back_parent_id, ci.item_alias_target, ci.item_creator, ci.item_processing_stamp, ci.item_bouncedname, ci.item_scope, ci.item_local_change_count, ci.item_old_version_identifier, ci.fp_creation_item_identifier, ci.version_name, ci.version_ckinfo, ci.version_mtime, ci.version_size, ci.version_thumb_size, ci.version_thumb_signature, ci.version_content_signature, ci.version_xattr_signature, ci.version_edited_since_shared, ci.version_device, ci.version_conflict_loser_etags, ci.version_quarantine_info, ci.version_uploaded_assets, ci.version_upload_error, ci.version_old_zone_item_id, ci.version_old_zone_rowid, ci.version_local_change_count, ci.version_old_version_identifier, ci.item_live_conflict_loser_etags, ci.item_file_id, ci.item_generation FROM client_items AS ci WHERE ci.item_localsyncupstate = 1 AND ci.item_localsyncupstate != 0 AND NOT EXISTS (SELECT 1 FROM client_unapplied_table AS cu WHERE cu.throttle_id = ci.rowid AND cu.throttle_state != 0)"
- "We are trying to import %@ as a regular file when it is actually a package."
- "[CRIT] UNREACHABLE: Failed to adopt persona for block adoption%@"
- "[DEBUG] Account hasn't really changed, do nothing%@"
- "[DEBUG] Cleaning up previous session belonging to account %@, to make room for new account %@%@"
- "[DEBUG] Cleaning up session on disk belonging to account %@%@"
- "[DEBUG] Detected shared bookmark, redirecting to trash in private zone for %@%@"
- "[DEBUG] Done Waiting for barrier %@ with result %@%@"
- "[DEBUG] Failed adding FPFS domain. Skipping database reset and trying to open again%@"
- "[DEBUG] Failed import FPFS domain. Skipping database reset and trying to open again%@"
- "[DEBUG] Finished waiting for changes under container root - %@%@"
- "[DEBUG] Local session state has been resetted, try opening the session for the second time%@"
- "[DEBUG] Looks like we hit disk space issue on second try --> don't panic or exit%@"
- "[DEBUG] Signalling and retaking barrier %@%@"
- "[DEBUG] Signalling barrier %@%@"
- "[DEBUG] Starting up at %@%@"
- "[DEBUG] Waiting for barrier %@%@"
- "[DEBUG] identified damaged document on disk with error: %@%@"
- "[DEBUG] sending apps account change notification%@"
- "[DEBUG] ┏%llx creating account for %@%@"
- "[DEBUG] ┏%llx creating account session for %@%@"
- "[DEBUG] ┏%llx destroying account for %@%@"
- "[ERROR] Capturing account session second open error: %@%@"
- "[ERROR] Failed to open account session second time%@"
- "[ERROR] Failed to open account session: %@%@"
- "[ERROR] Failed to open account session: Exception [%@]%@"
- "[ERROR] Your database is from the future, disabling iCloud Drive (%@)%@"
- "[NOTICE] now using account %@%@"
- "[NOTICE] simulating health issue on %@: %@%@"
- "[NOTICE] stop using account %@%@"
- "[Upload Error] Detected an attempt to import a package as a regular file"
- "[WARNING] Capturing account session open error of the first try: %@%@"
- "[WARNING] UserInfo has no dictionary field called bundleIDs%@"
- "[WARNING] UserInfo has no dictionary field called isPlaceholder%@"
- "[WARNING] XPCEvent has no dictionary field called UserInfo%@"
- "[WARNING] unable to find bundleID %@%@"
- "[WARNING] we are already logged in %@%@"
- "com.apple.distnoted.matching"
- "notifications.request-for-access"
- "requestForAccess"
- "session{account:%@}"
```
