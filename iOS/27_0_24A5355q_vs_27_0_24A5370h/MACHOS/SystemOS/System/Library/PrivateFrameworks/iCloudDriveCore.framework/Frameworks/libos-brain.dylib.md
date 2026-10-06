## libos-brain.dylib

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/Frameworks/libos-brain.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2042cc` | `0x207794` | **`+0x34c8`** |
| `__DATA.__objc_const` | `0x4e40` | `0x5700` | **`+0x8c0`** |
| `__DATA_CONST.__const` | `0x7cc8` | `0x80e0` | **`+0x418`** |
| `__DATA.__bss` | `0x10950` | `0x10cd0` | **`+0x380`** |
| `__TEXT.__oslogstring` | `0x87cd` | `0x849d` | **`-0x330`** |
| `__TEXT.__const` | `0xca48` | `0xcd28` | **`+0x2e0`** |
| `__TEXT.__swift5_reflstr` | `0x319d` | `0x343d` | **`+0x2a0`** |
| `__TEXT.__swift5_typeref` | `0x5082` | `0x52e2` | **`+0x260`** |
| `__TEXT.__constg_swiftt` | `0x42b4` | `0x44dc` | **`+0x228`** |
| `__DATA.__data` | `0x4da8` | `0x4fb0` | **`+0x208`** |
| `__TEXT.__swift5_fieldmd` | `0x2cd0` | `0x2e38` | **`+0x168`** |
| `__TEXT.__eh_frame` | `0x119d0` | `0x11898` | **`-0x138`** |
| `__TEXT.__objc_methname` | `0x3b54` | `0x3c72` | **`+0x11e`** |
| `__DATA_CONST.__auth_ptr` | `0x3060` | `0x3168` | **`+0x108`** |
| `__TEXT.__objc_stubs` | `0x1e80` | `0x1f60` | **`+0xe0`** |
| `__TEXT.__swift5_capture` | `0x1798` | `0x1850` | **`+0xb8`** |
| `__TEXT.__objc_classname` | `0x368` | `0x418` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x61d8` | `0x6270` | **`+0x98`** |
| `__TEXT.__objc_methtype` | `0x114f` | `0x11cf` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0xcb4` | `0xd0c` | **`+0x58`** |
| `__TEXT.__cstring` | `0x4082` | `0x40d2` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xa10` | `0xa48` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x29a0` | `0x29d0` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x8b4` | `0x8d8` | **`+0x24`** |
| `__TEXT.__swift5_assocty` | `0xf70` | `0xf90` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x67c` | `0x65c` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0xcd8` | `0xcbc` | **`-0x1c`** |
| `__DATA_CONST.__auth_got` | `0x14d8` | `0x14f0` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x2c8` | `0x2dc` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x80` | `0x90` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x88` | `0x98` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x154` | `0x164` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x5a0` | `0x590` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x94` | `0x9c` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x748` | `0x740` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x48` | `0x50` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-5044.0.0.0.0
+5140.0.0.0.0

-  - /System/Library/PrivateFrameworks/MMCS.framework/MMCS

-  Functions: 6837
-  Symbols:   2057
-  CStrings:  1510
+  Functions: 6918
+  Symbols:   2111
+  CStrings:  1513
Symbols:
+ -[iCDCreateItemContext initWithReserverItemIDString:reservedFileProviderIdentifier:parentZoneName:parentZoneOwner:parentIDString:primaryZoneNeedsCreation:appLibraryRootNeedsCreation:appLibraryIsConsolidated:symlinkTarget:parentShareState:shareRootItemIdentifierString:parentPCSChainState:parentSharePermissions:initialItem:resetItem:isInDocumentScope:trashPutBackPath:trashPutbackItemIDString:progress:]
+ -[iCDCreateItemContext isInDocumentScope]
+ -[iCDModifyItemContext initWithResetItem:forceParentShared:zoneName:zoneOwner:itemIDString:parentZoneNeedsCreation:appLibraryRootNeedsCreation:appLibraryIsConsolidated:parentZoneName:parentZoneOwner:parentIDString:isInDocumentScope:trashPutBackPath:trashPutbackItemIDString:progress:]
+ -[iCDModifyItemContext isInDocumentScope]
+ OBJC_IVAR_$_iCDCreateItemContext._isInDocumentScope
+ OBJC_IVAR_$_iCDModifyItemContext._isInDocumentScope
+ __DATA__TtC8os_brainP33_3314DE9DFC97F8F2A3D1D266C5536DEE22ICDUserSettingsAdapter
+ __DATA__TtC8os_brainP33_3314DE9DFC97F8F2A3D1D266C5536DEE23ICDUserSettingsProvider
+ __IVARS__TtC8os_brainP33_3314DE9DFC97F8F2A3D1D266C5536DEE22ICDUserSettingsAdapter
+ __IVARS__TtC8os_brainP33_3314DE9DFC97F8F2A3D1D266C5536DEE23ICDUserSettingsProvider
+ __METACLASS_DATA__TtC8os_brainP33_3314DE9DFC97F8F2A3D1D266C5536DEE22ICDUserSettingsAdapter
+ __METACLASS_DATA__TtC8os_brainP33_3314DE9DFC97F8F2A3D1D266C5536DEE23ICDUserSettingsProvider
+ __OBJC_$_PROP_LIST_iCDUserDefaults
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_iCDUserDefaults
+ __OBJC_$_PROTOCOL_METHOD_TYPES_iCDUserDefaults
+ __OBJC_$_PROTOCOL_REFS_iCDUserDefaults
+ __OBJC_LABEL_PROTOCOL_$_iCDUserDefaults
+ __OBJC_PROTOCOL_$_iCDUserDefaults
+ ___swift_memcpy144_8
+ ___swift_memcpy176_8
+ ___swift_memcpy184_8
+ ___swift_memcpy56_8
+ ___swift_memcpy80_8
+ ___swift_memcpy88_8
+ ___swift_memcpy8_8
+ ___unnamed_2
+ __swift_closure_destructor.10Tm
+ __swift_closure_destructor.37Tm
+ __swift_closure_destructor.75Tm
+ __swift_exist.box.addr_destructor.243Tm
+ __swift_exist.box.addr_destructor.261Tm
+ __swift_exist.box.addr_destructorTm
+ _associated conformance 12common_brain20DatabaseTableMonitorV17ContinuationTokenV10CodingKeys33_5E1606F16A5203251D42B8F3B27E9E4DLLOyxq_q0___Gs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 12common_brain20DatabaseTableMonitorV17ContinuationTokenV10CodingKeys33_5E1606F16A5203251D42B8F3B27E9E4DLLOyxq_q0___Gs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12common_brain20DatabaseTableMonitorVyxq_q0_GAA12PeriodicTaskAA17ContinuationTokenAaEP_SE
+ _associated conformance 12common_brain20DatabaseTableMonitorVyxq_q0_GAA12PeriodicTaskAA17ContinuationTokenAaEP_Se
+ _associated conformance So24CKModifyRecordsOperationC12common_brain012ServerModifybC003os_E00C7MetricsAcDP_AC0fcI0
+ _flat unique So15iCDUserDefaults_p
+ _objc_msgSend$MMCSMetrics
+ _objc_msgSend$blockedThumbnailExtensions
+ _objc_msgSend$bytesUploaded
+ _objc_msgSend$getUserDefaultsForZoneName:ownerName:
+ _objc_msgSend$isInDocumentScope
+ _objc_msgSend$maxRelativePathDepth
+ _objc_msgSend$metrics
+ _objc_msgSend$minFileSizeForThumbnailTransfer
+ _objc_msgSend$recursiveOperationsDatabaseBatchSize
+ _objc_msgSend$updateUploadedBytesWithSize:forItemIdentifiers:zoneName:ownerName:
+ _swift_release_x3
+ _symbolic $s12common_brain12UserSettingsP
+ _symbolic $s12common_brain20UserSettingsProviderP
+ _symbolic $s12common_brain22ServerOperationMetricsP
+ _symbolic $s12common_brain39UploadConstraintExternalServiceProtocolP
+ _symbolic 16ContainerManager______0A4Type_____22ModifyRecordsOperation_____0F7Metrics_____QZSg 12common_brain30SyncUpBaseStageHandlerProtocolP AA022ServerContainerManagerH0P AA0ijH0P AA0I22ModifyRecordsOperationP
+ _symbolic 16ContainerManager______0A4Type_____22ModifyRecordsOperation_____QZ 12common_brain30SyncUpBaseStageHandlerProtocolP AA022ServerContainerManagerH0P AA0ijH0P
+ _symbolic 16OperationMetrics_____Qz 12common_brain28ServerModifyRecordsOperationP
+ _symbolic SDy13JobIdentifier_____Qz_____yx_GG 12common_brain11PipelineJobP AA26ExclusiveAccessCoordinatorC06ActiveD5Entry33_8EA3B7E6C4F5005094B4C9C7AEEDFA0FLLV
+ _symbolic SDy_____SDy_____ScCyyt______pGGG 12common_brain20GlobalItemIdentifierV 10Foundation4UUIDV s5ErrorP
+ _symbolic Say_____y6Record_____Qz_GG 12common_brain9SyncUpJobV0E5SliceV AA0cD24BaseStageHandlerProtocolP
+ _symbolic ScCyyt______pGSg s5ErrorP
+ _symbolic So18CKOperationMetricsCSg
+ _symbolic _____ 12common_brain20DatabaseTableMonitorV
+ _symbolic _____ 12common_brain20DatabaseTableMonitorV17ContinuationTokenV
+ _symbolic _____ 12common_brain20DatabaseTableMonitorV17ContinuationTokenV10CodingKeys33_5E1606F16A5203251D42B8F3B27E9E4DLLO
+ _symbolic _____ 12common_brain26ExclusiveAccessCoordinatorC14ActiveJobEntry33_8EA3B7E6C4F5005094B4C9C7AEEDFA0FLLV
+ _symbolic _____ 8os_brain22ICDUserSettingsAdapter33_3314DE9DFC97F8F2A3D1D266C5536DEELLC
+ _symbolic _____ 8os_brain23ICDUserSettingsProvider33_3314DE9DFC97F8F2A3D1D266C5536DEELLC
+ _symbolic _____ 8os_brain25CKOperationMetricsWrapperV
+ _symbolic _____3key_ScCyyt______pG5valuet 10Foundation4UUIDV s5ErrorP
+ _symbolic ______SDy_____ScCyyt______pGGt 12common_brain20GlobalItemIdentifierV 10Foundation4UUIDV s5ErrorP
+ _symbolic ______ScCyyt______pGt 10Foundation4UUIDV s5ErrorP
+ _symbolic ______p 12common_brain20UserSettingsProviderP
+ _symbolic ______p 12common_brain39UploadConstraintExternalServiceProtocolP
+ _symbolic ______p So15iCDUserDefaultsP
+ _symbolic ______pSg 12common_brain17SyncUpRecordErrorP
+ _symbolic _____y_____SDy_____ScCyyt______pGGG s18_DictionaryStorageC 12common_brain20GlobalItemIdentifierV 10Foundation4UUIDV s5ErrorP
+ _symbolic _____y_____ScCyyt______pGG s18_DictionaryStorageC 10Foundation4UUIDV s5ErrorP
+ _symbolic _____yxq_q0__G 12common_brain20DatabaseTableMonitorV17ContinuationTokenV
+ _symbolic _____yyt______pGSg s6ResultOsRi_zRi0_zrlE s5ErrorP
+ _symbolic _____yyt______pGSgz_Xx s6ResultOsRi_zRi0_zrlE s5ErrorP
+ _type_layout_string 8os_brain25CKOperationMetricsWrapperV
+ _type_layout_string 8os_brain27CreateThumbnailStageHandlerV
- -[iCDCreateItemContext initWithReserverItemIDString:reservedFileProviderIdentifier:parentZoneName:parentZoneOwner:parentIDString:primaryZoneNeedsCreation:appLibraryRootNeedsCreation:appLibraryIsConsolidated:symlinkTarget:parentShareState:shareRootItemIdentifierString:parentPCSChainState:parentSharePermissions:initialItem:resetItem:trashPutBackPath:trashPutbackItemIDString:progress:]
- -[iCDModifyItemContext initWithResetItem:forceParentShared:zoneName:zoneOwner:itemIDString:parentZoneNeedsCreation:appLibraryRootNeedsCreation:appLibraryIsConsolidated:parentZoneName:parentZoneOwner:parentIDString:trashPutBackPath:trashPutbackItemIDString:progress:]
- __IVARS__TtC12common_brain20DatabaseTableMonitor
- ___swift_allocate_boxed_opaque_existential_0Tm
- ___swift_memcpy104_8
- ___swift_memcpy136_8
- ___swift_memcpy152_8
- ___unnamed_7
- __swift_closure_destructor.38Tm
- __swift_closure_destructor.76Tm
- _kMMCSErrorDomain
- _objc_msgSend$isDamagedDocumentOnDiskWithContentURL:
- _objc_msgSend$megabytes
- _objc_msgSend$recoverDamagedDocumentOnDiskForItemIdentifier:zoneName:ownerName:completionHandler:
- _swift_release_x10
- _swift_task_future_wait_throwing
- _symbolic 9ValueType_____Qy_ 12common_brain17DatabaseCodingKeyP
- _symbolic G2R1_
- _symbolic SDy13JobIdentifier_____QzxG 12common_brain11PipelineJobP
- _symbolic _____ 12common_brain20DatabaseTableMonitorC
- _symbolic _____ 12common_brain33DatabaseTableMonitorConfigurationV
- _symbolic _____20globalItemIdentifier_t 12common_brain20GlobalItemIdentifierV
- _symbolic _____3key_ScTy___________pG5valuet 12common_brain20GlobalItemIdentifierV 10Foundation4DataV s5ErrorP
- _symbolic _____y_____3key_ScTy___________pG5valuetG s23_ContiguousArrayStorageC 12common_brain20GlobalItemIdentifierV 10Foundation4DataV s5ErrorP
- _symbolic _____y_____G 12common_brain33CrossZoneMoveMonitorActionHandlerV 03os_B027ExpensiveOperationsDatabaseC
- _symbolic _____y__________y_____G_____y______GG 12common_brain20DatabaseTableMonitorC AA22CrossZoneMoveOperationV AA0fghE13ActionHandlerV 03os_B0019ExpensiveOperationsC0C AE0C4KeysV 10Foundation4DateV
- _symbolic _____yxq0_G 12common_brain33DatabaseTableMonitorConfigurationV
- _symbolic _____yxq_q0_G 12common_brain20DatabaseTableMonitorC
CStrings:
+ " with no in-flight task"
+ "@\"<iCDUserDefaults>\"32@0:8@\"NSString\"16@\"NSString\"24"
+ "@112@0:8B16B20@24@32@40B48B52B56@60@68@76B84@88@96@104"
+ "@132@0:8@16@24@32@40@48B56B60B64@68I76@80I88I92B96B100B104@108@116@124"
+ "@32@0:8@16@24"
+ "Action handler reported failure for stale records in %s"
+ "Checking %s for records older than %s"
+ "CreateZoneAndSubscriptionStageHandler: Subscription already registered for zone %s"
+ "CrossZoneMoveStageHandler[%ld]: Destination zone error, aborting operation: %@"
+ "Handled %ld stale records in %s"
+ "MMCSMetrics"
+ "No stale records in %s"
+ "Sync down flush: cancelled by caller, propagating"
+ "Sync down flush: ignoring non-network error for item %s in zone %s: %@"
+ "Sync down flush: network error for zone %s, propagating: %@"
+ "SyncUpPipelineManager: Job %s - Slice %s needs subhierarchy exclusive access"
+ "SyncUpResult: Adding item %s to sync down coordinator for zone %s"
+ "SyncUpResult: Handling zone reset error for %s, resetting zone %s, reset type: %s, reason: %s"
+ "TB,R,N,V_isInDocumentScope"
+ "_TtC8os_brainP33_3314DE9DFC97F8F2A3D1D266C5536DEE22ICDUserSettingsAdapter"
+ "_TtC8os_brainP33_3314DE9DFC97F8F2A3D1D266C5536DEE23ICDUserSettingsProvider"
+ "_isInDocumentScope"
+ "blockedThumbnailExtensions"
+ "bytesUploaded"
+ "common_brain/SyncDownCoordinator.swift"
+ "crossZoneMoveRecovery"
+ "defaults"
+ "getUserDefaultsForZoneName:ownerName:"
+ "iCDUserDefaults"
+ "initWithReserverItemIDString:reservedFileProviderIdentifier:parentZoneName:parentZoneOwner:parentIDString:primaryZoneNeedsCreation:appLibraryRootNeedsCreation:appLibraryIsConsolidated:symlinkTarget:parentShareState:shareRootItemIdentifierString:parentPCSChainState:parentSharePermissions:initialItem:resetItem:isInDocumentScope:trashPutBackPath:trashPutbackItemIDString:progress:"
+ "initWithResetItem:forceParentShared:zoneName:zoneOwner:itemIDString:parentZoneNeedsCreation:appLibraryRootNeedsCreation:appLibraryIsConsolidated:parentZoneName:parentZoneOwner:parentIDString:isInDocumentScope:trashPutBackPath:trashPutbackItemIDString:progress:"
+ "isInDocumentScope"
+ "itemWaiters"
+ "maxRelativePathDepth"
+ "metrics"
+ "minFileSizeForThumbnailTransfer"
+ "recursiveOperationsDatabaseBatchSize"
+ "updateUploadedBytesWithSize:forItemIdentifiers:zoneName:ownerName:"
+ "userSettingsProvider"
+ "v48@0:8q16@\"NSArray\"24@\"NSString\"32@\"NSString\"40"
+ "v48@0:8q16@24@32@40"
+ "waitForItemSyncDown called for "
+ "waitForItemSyncDown(key:)"
- ") as min_timestamp\nFROM "
- "@108@0:8B16B20@24@32@40B48B52B56@60@68@76@84@92@100"
- "@128@0:8@16@24@32@40@48B56B60B64@68I76@80I88I92B96B100@104@112@120"
- "B24@0:8@\"NSURL\"16"
- "Checking for stale records in %s with staleness date: %s"
- "DatabaseTableMonitor for %s already running"
- "Error in monitor loop for %s: %@"
- "Failed to handle stale records in %s"
- "Failed to initialize DatabaseTableMonitor for %s: %@"
- "Initialized DatabaseTableMonitor for %s with earliest timestamp: %s"
- "Next check in %fs for %s"
- "No known timestamps for %s, stopping monitor"
- "No stale records found in %s"
- "Record already stale for %s, checking immediately"
- "Starting DatabaseTableMonitor for %s with staleness threshold: %fs"
- "Stopped DatabaseTableMonitor for %s"
- "Successfully handled %ld stale records in %s"
- "SyncEngine: recover damaged document on disk with %s"
- "SyncUpPipelineManager: Job %s - Slice %s contains recursive operations - applying subhierarchy exclusive access"
- "SyncUpResult: Adding newly created item %s to sync down coordinator for zone %s"
- "SyncUpResult: Damaged document error - content URL extracted: %s"
- "SyncUpResult: Damaged document error - creation job"
- "SyncUpResult: Damaged document error - deletion job, skipping"
- "SyncUpResult: Damaged document error - modification job"
- "SyncUpResult: Damaged document error - no content URL available"
- "SyncUpResult: Failed to check if document is damaged on disk: %@"
- "SyncUpResult: Handling damaged document on disk error for %s"
- "SyncUpResult: Handling zone reset error for %s in zone %s, reset type: %s, reason: %s"
- "SyncUpResult: Zone reset error - added resetZone action for zone %s with type %s"
- "actionHandler"
- "crossZoneMoveMonitor"
- "dataSource"
- "earliestKnownTimestamp"
- "initWithReserverItemIDString:reservedFileProviderIdentifier:parentZoneName:parentZoneOwner:parentIDString:primaryZoneNeedsCreation:appLibraryRootNeedsCreation:appLibraryIsConsolidated:symlinkTarget:parentShareState:shareRootItemIdentifierString:parentPCSChainState:parentSharePermissions:initialItem:resetItem:trashPutBackPath:trashPutbackItemIDString:progress:"
- "initWithResetItem:forceParentShared:zoneName:zoneOwner:itemIDString:parentZoneNeedsCreation:appLibraryRootNeedsCreation:appLibraryIsConsolidated:parentZoneName:parentZoneOwner:parentIDString:trashPutBackPath:trashPutbackItemIDString:progress:"
- "isDamagedDocumentOnDiskWithContentURL:"
- "megabytes"
- "monitorTask"
- "recoverDamagedDocumentOnDisk(globalItemIdentifier:)"
- "recoverDamagedDocumentOnDiskForItemIdentifier:zoneName:ownerName:completionHandler:"
```
