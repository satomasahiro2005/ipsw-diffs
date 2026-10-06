## FileProviderDaemon

> `/System/Library/PrivateFrameworks/FileProviderDaemon.framework/FileProviderDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa33bfc` | `0xa5943c` | **`+0x25840`** |
| `__TEXT.__cstring` | `0x43675` | `0x49825` | **`+0x61b0`** |
| `__AUTH_CONST.__const` | `0x45888` | `0x49750` | **`+0x3ec8`** |
| `__TEXT.__swift5_capture` | `0x18928` | `0x1a7c4` | **`+0x1e9c`** |
| `__DATA.__bss` | `0x27af0` | `0x26ef0` | **`-0xc00`** |
| `__TEXT.__const` | `0x2e230` | `0x2d910` | **`-0x920`** |
| `__TEXT.__eh_frame` | `0x2be38` | `0x2c688` | **`+0x850`** |
| `__DATA_DIRTY.__bss` | `0xf808` | `0xf588` | **`-0x280`** |
| `__TEXT.__swift5_typeref` | `0x14ad0` | `0x148d0` | **`-0x200`** |
| `__DATA_DIRTY.__data` | `0x10ad0` | `0x10910` | **`-0x1c0`** |
| `__TEXT.__oslogstring` | `0x1fef2` | `0x1fd62` | **`-0x190`** |
| `__DATA.__data` | `0x8340` | `0x81d0` | **`-0x170`** |
| `__TEXT.__constg_swiftt` | `0x145b8` | `0x14464` | **`-0x154`** |
| `__AUTH_CONST.__objc_const` | `0x276b0` | `0x27598` | **`-0x118`** |
| `__TEXT.__swift5_fieldmd` | `0xcf88` | `0xce7c` | **`-0x10c`** |
| `__AUTH.__data` | `0x2638` | `0x2738` | **`+0x100`** |
| `__AUTH.__objc_data` | `0x18c8` | `0x1968` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x96d4` | `0x976c` | **`+0x98`** |
| `__TEXT.__gcc_except_tab` | `0xd354` | `0xd2c4` | **`-0x90`** |
| `__TEXT.__swift5_proto` | `0x1cc4` | `0x1c4c` | **`-0x78`** |
| `__TEXT.__swift5_reflstr` | `0xf5dd` | `0xf64d` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x161e0` | `0x161a0` | **`-0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x6158` | `0x6188` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x4660` | `0x4688` | **`+0x28`** |
| `__DATA.__common` | `0x1cb` | `0x1eb` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0xf8` | `0x118` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0xc40` | `0xc24` | **`-0x1c`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xd8` | `0xf0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x560` | `0x570` | **`+0x10`** |
| `__DATA_DIRTY.__common` | `0x8d0` | `0x8c0` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0xb90` | `0xb9c` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x30d8` | `0x30d0` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x288` | `0x290` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x3358` | `0x3360` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1bc` | `0x1b4` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x190` | `0x188` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x374` | `0x370` | **`-0x4`** |

### Other Changes

```diff

-4780.0.0.502.1
+4838.0.29.502.2

-  Functions: 30668
-  Symbols:   12482
-  CStrings:  7522
+  Functions: 31187
+  Symbols:   12460
+  CStrings:  7964
Symbols:
+ -[FPDAccessRight _computeAccessForURL:entitlements:connection:callerSelector:]
+ -[FPDAccessRight initWithURL:entitlements:connection:callerSelector:manager:]
+ -[FPDClaimKnownFolderOperation resolveKnownFolderURLsWithError:]
+ -[FPDDomain _createIndexerWithExtension:]
+ -[FPDDomain _migrateIndexerStateIfNeeded]
+ -[FPDKnownFolderAttachForDetachAlertPresenter .cxx_destruct]
+ -[FPDKnownFolderAttachForDetachAlertPresenter initWithNewProviderDomain:previousProviderDomain:]
+ -[FPDKnownFolderAttachForDetachAlertPresenter presentAlertWithUserAprovalToContinue]
+ -[FPDKnownFolderAttachForDetachAlertPresenter presentAlertWithoutUserApprovalNeededToContinue]
+ -[FPDKnownFolderAttachForDetachAlertPresenter previousIsiCloudDriveProvider]
+ -[FPDKnownFolderAttachForDetachAlertPresenter previousProviderDisplayName]
+ -[FPDTelemetryService _handleExpiration]
+ -[FPDXPCServicer _allowAlternateContentsAccessWithSandboxAccess:callerSelector:]
+ -[FPDXPCServicer startAccessingServiceWithName:itemID:domain:connection:enumerateEntitlementRequired:callerSelector:completionHandler:]
+ _OBJC_CLASS_$_FPDKnownFolderAttachForDetachAlertPresenter
+ _OBJC_IVAR_$_FPDClaimKnownFolderOperation._knownFolderPhysicalURLs
+ _OBJC_IVAR_$_FPDKnownFolderAttachForDetachAlertPresenter._previousIsiCloudDriveProvider
+ _OBJC_IVAR_$_FPDKnownFolderAttachForDetachAlertPresenter._previousProviderDisplayName
+ _OBJC_METACLASS_$_FPDKnownFolderAttachForDetachAlertPresenter
+ __DATA__TtC18FileProviderDaemon11VFSCounters
+ __IVARS__TtC18FileProviderDaemon11VFSCounters
+ __METACLASS_DATA__TtC18FileProviderDaemon11VFSCounters
+ __OBJC_$_INSTANCE_METHODS_FPDKnownFolderAttachForDetachAlertPresenter
+ __OBJC_$_INSTANCE_VARIABLES_FPDKnownFolderAttachForDetachAlertPresenter
+ __OBJC_$_PROP_LIST_FPDKnownFolderAttachForDetachAlertPresenter
+ __OBJC_CLASS_RO_$_FPDKnownFolderAttachForDetachAlertPresenter
+ __OBJC_METACLASS_RO_$_FPDKnownFolderAttachForDetachAlertPresenter
+ ___135-[FPDXPCServicer startAccessingServiceWithName:itemID:domain:connection:enumerateEntitlementRequired:callerSelector:completionHandler:]_block_invoke
+ ___64-[FPDClaimKnownFolderOperation resolveKnownFolderURLsWithError:]_block_invoke
+ ___block_descriptor_73_e8_32s40s48s_e40_"NSString"16?0"FPXServiceDescriptor"8ls32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48s56s64bs_e30_v24?0"FPItemID"8"NSError"16ls32l8s64l8s40l8s48l8s56l8
+ ___block_descriptor_88_e8_32s40s48s56s64bs_e55_v32?0"NSXPCListenerEndpoint"8"NSArray"16"NSError"24ls64l8s32l8s40l8s48l8s56l8
+ ___swift_closure_destructor.1001Tm
+ ___swift_closure_destructor.1204Tm
+ ___swift_closure_destructor.1543Tm
+ ___swift_closure_destructor.1604Tm
+ ___swift_closure_destructor.1652Tm
+ ___swift_closure_destructor.1655Tm
+ ___swift_closure_destructor.1701Tm
+ ___swift_closure_destructor.1721Tm
+ ___swift_closure_destructor.1728Tm
+ ___swift_closure_destructor.1740Tm
+ ___swift_closure_destructor.1744Tm
+ ___swift_closure_destructor.176Tm
+ ___swift_closure_destructor.1824Tm
+ ___swift_closure_destructor.1852Tm
+ ___swift_closure_destructor.192Tm
+ ___swift_closure_destructor.1941Tm
+ ___swift_closure_destructor.199Tm
+ ___swift_closure_destructor.203Tm
+ ___swift_closure_destructor.2463Tm
+ ___swift_closure_destructor.267Tm
+ ___swift_closure_destructor.2770Tm
+ ___swift_closure_destructor.2883Tm
+ ___swift_closure_destructor.3020Tm
+ ___swift_closure_destructor.3027Tm
+ ___swift_closure_destructor.3037Tm
+ ___swift_closure_destructor.3040Tm
+ ___swift_closure_destructor.3114Tm
+ ___swift_closure_destructor.3145Tm
+ ___swift_closure_destructor.3251Tm
+ ___swift_closure_destructor.3389Tm
+ ___swift_closure_destructor.3419Tm
+ ___swift_closure_destructor.346Tm
+ ___swift_closure_destructor.3495Tm
+ ___swift_closure_destructor.3505Tm
+ ___swift_closure_destructor.3508Tm
+ ___swift_closure_destructor.3511Tm
+ ___swift_closure_destructor.3587Tm
+ ___swift_closure_destructor.3593Tm
+ ___swift_closure_destructor.3602Tm
+ ___swift_closure_destructor.363Tm
+ ___swift_closure_destructor.381Tm
+ ___swift_closure_destructor.4088Tm
+ ___swift_closure_destructor.4132Tm
+ ___swift_closure_destructor.4138Tm
+ ___swift_closure_destructor.4268Tm
+ ___swift_closure_destructor.4475Tm
+ ___swift_closure_destructor.4478Tm
+ ___swift_closure_destructor.4482Tm
+ ___swift_closure_destructor.4565Tm
+ ___swift_closure_destructor.4591Tm
+ ___swift_closure_destructor.4630Tm
+ ___swift_closure_destructor.4746Tm
+ ___swift_closure_destructor.4752Tm
+ ___swift_closure_destructor.4967Tm
+ ___swift_closure_destructor.5155Tm
+ ___swift_closure_destructor.515Tm
+ ___swift_closure_destructor.5428Tm
+ ___swift_closure_destructor.5460Tm
+ ___swift_closure_destructor.5763Tm
+ ___swift_closure_destructor.5974Tm
+ ___swift_closure_destructor.603Tm
+ ___swift_closure_destructor.609Tm
+ ___swift_closure_destructor.6276Tm
+ ___swift_closure_destructor.6290Tm
+ ___swift_closure_destructor.6445Tm
+ ___swift_closure_destructor.6452Tm
+ ___swift_closure_destructor.6477Tm
+ ___swift_closure_destructor.6600Tm
+ ___swift_closure_destructor.682Tm
+ ___swift_closure_destructor.698Tm
+ ___swift_closure_destructor.709Tm
+ ___swift_closure_destructor.813Tm
+ ___swift_closure_destructor.830Tm
+ ___swift_closure_destructor.839Tm
+ ___swift_closure_destructor.847Tm
+ ___swift_closure_destructor.992Tm
+ ___swift_closure_destructor.995Tm
+ ___swift_closure_destructor.998Tm
+ ___unnamed_116
+ _get_type_metadata 15Synchronization6AtomicVys6UInt64VG noncopyable
+ _symbolic Say_____G 18FileProviderDaemon7VFSItemV
+ _symbolic Say_____Gz_Xx 18FileProviderDaemon7VFSItemV
+ _symbolic Say_____y______GGSay_____G______pSgIegg_SgIegggg_Sg 18FileProviderDaemon0A10TreeWriterC0aD6ChangeO AA7VFSItemV AA9SyncStateO s5ErrorP
+ _symbolic _____ 18FileProviderDaemon11VFSCountersC
+ _symbolic _____y_____G 15Synchronization6AtomicV s6UInt64V
- -[FPDAccessRight _computeAccessForURL:entitlements:connection:]
- -[FPDAccessRight initWithURL:entitlements:connection:manager:]
- -[FPDXPCServicer _isNonSandboxedConnection]
- -[FPDXPCServicer startAccessingServiceWithName:itemID:domain:connection:enumerateEntitlementRequired:completionHandler:]
- __IVARS__TtC18FileProviderDaemon17TruncationMonitor
- ___120-[FPDXPCServicer startAccessingServiceWithName:itemID:domain:connection:enumerateEntitlementRequired:completionHandler:]_block_invoke
- ___79-[FPDClaimKnownFolderOperation attachClaimedKnownFoldersWithCompletionHandler:]_block_invoke_2
- ___block_descriptor_65_e8_32s40s48s_e40_"NSString"16?0"FPXServiceDescriptor"8ls32l8s40l8s48l8
- ___block_descriptor_80_e8_32s40s48s56s64bs_e55_v32?0"NSXPCListenerEndpoint"8"NSArray"16"NSError"24ls64l8s32l8s40l8s48l8s56l8
- ___swift_closure_destructor.1030Tm
- ___swift_closure_destructor.1033Tm
- ___swift_closure_destructor.1118Tm
- ___swift_closure_destructor.1202Tm
- ___swift_closure_destructor.1230Tm
- ___swift_closure_destructor.1541Tm
- ___swift_closure_destructor.164Tm
- ___swift_closure_destructor.1699Tm
- ___swift_closure_destructor.1719Tm
- ___swift_closure_destructor.1726Tm
- ___swift_closure_destructor.173Tm
- ___swift_closure_destructor.1742Tm
- ___swift_closure_destructor.1827Tm
- ___swift_closure_destructor.186Tm
- ___swift_closure_destructor.189Tm
- ___swift_closure_destructor.198Tm
- ___swift_closure_destructor.2084Tm
- ___swift_closure_destructor.2346Tm
- ___swift_closure_destructor.261Tm
- ___swift_closure_destructor.2653Tm
- ___swift_closure_destructor.2766Tm
- ___swift_closure_destructor.281Tm
- ___swift_closure_destructor.2903Tm
- ___swift_closure_destructor.290Tm
- ___swift_closure_destructor.2910Tm
- ___swift_closure_destructor.2920Tm
- ___swift_closure_destructor.2923Tm
- ___swift_closure_destructor.2997Tm
- ___swift_closure_destructor.3028Tm
- ___swift_closure_destructor.307Tm
- ___swift_closure_destructor.3134Tm
- ___swift_closure_destructor.3272Tm
- ___swift_closure_destructor.3302Tm
- ___swift_closure_destructor.3378Tm
- ___swift_closure_destructor.3388Tm
- ___swift_closure_destructor.3391Tm
- ___swift_closure_destructor.3394Tm
- ___swift_closure_destructor.3470Tm
- ___swift_closure_destructor.3476Tm
- ___swift_closure_destructor.3485Tm
- ___swift_closure_destructor.375Tm
- ___swift_closure_destructor.3821Tm
- ___swift_closure_destructor.3865Tm
- ___swift_closure_destructor.3871Tm
- ___swift_closure_destructor.4001Tm
- ___swift_closure_destructor.4208Tm
- ___swift_closure_destructor.4211Tm
- ___swift_closure_destructor.4215Tm
- ___swift_closure_destructor.4218Tm
- ___swift_closure_destructor.4298Tm
- ___swift_closure_destructor.4324Tm
- ___swift_closure_destructor.4363Tm
- ___swift_closure_destructor.4479Tm
- ___swift_closure_destructor.459Tm
- ___swift_closure_destructor.4700Tm
- ___swift_closure_destructor.476Tm
- ___swift_closure_destructor.4888Tm
- ___swift_closure_destructor.5148Tm
- ___swift_closure_destructor.5180Tm
- ___swift_closure_destructor.5450Tm
- ___swift_closure_destructor.5661Tm
- ___swift_closure_destructor.580Tm
- ___swift_closure_destructor.593Tm
- ___swift_closure_destructor.5963Tm
- ___swift_closure_destructor.596Tm
- ___swift_closure_destructor.5977Tm
- ___swift_closure_destructor.599Tm
- ___swift_closure_destructor.602Tm
- ___swift_closure_destructor.608Tm
- ___swift_closure_destructor.6132Tm
- ___swift_closure_destructor.6139Tm
- ___swift_closure_destructor.6164Tm
- ___swift_closure_destructor.680Tm
- ___swift_closure_destructor.688Tm
- ___swift_closure_destructor.707Tm
- ___swift_closure_destructor.713Tm
- ___swift_closure_destructor.811Tm
- ___swift_closure_destructor.822Tm
- ___swift_closure_destructor.845Tm
- ___swift_closure_destructor.982Tm
- ___unnamed_118
- _associated conformance 18FileProviderDaemon11VFSCountersV10CodingKeys33_304ED64B271778B28A3D5A78B01E942BLLOSHAASQ
- _associated conformance 18FileProviderDaemon11VFSCountersV10CodingKeys33_304ED64B271778B28A3D5A78B01E942BLLOs0E3KeyAAs23CustomStringConvertible
- _associated conformance 18FileProviderDaemon11VFSCountersV10CodingKeys33_304ED64B271778B28A3D5A78B01E942BLLOs0E3KeyAAs28CustomDebugStringConvertible
- _associated conformance 18FileProviderDaemon14TruncatedItemsV10CodingKeys33_26512BA742A84555167AE8AC7BF31468LLOyx_GSHAASQ
- _associated conformance 18FileProviderDaemon14TruncatedItemsV10CodingKeys33_26512BA742A84555167AE8AC7BF31468LLOyx_Gs0F3KeyAAs23CustomStringConvertible
- _associated conformance 18FileProviderDaemon14TruncatedItemsV10CodingKeys33_26512BA742A84555167AE8AC7BF31468LLOyx_Gs0F3KeyAAs28CustomDebugStringConvertible
- _associated conformance 18FileProviderDaemon15TruncationEventV10CodingKeys33_26512BA742A84555167AE8AC7BF31468LLOSHAASQ
- _associated conformance 18FileProviderDaemon15TruncationEventV10CodingKeys33_26512BA742A84555167AE8AC7BF31468LLOs0F3KeyAAs23CustomStringConvertible
- _associated conformance 18FileProviderDaemon15TruncationEventV10CodingKeys33_26512BA742A84555167AE8AC7BF31468LLOs0F3KeyAAs28CustomDebugStringConvertible
- _associated conformance 18FileProviderDaemon20FPDDomainFPFSBackendC8CountersV10CodingKeys33_37A6F768C70A5B8920883F88E539AEF9LLOSHAASQ
- _associated conformance 18FileProviderDaemon20FPDDomainFPFSBackendC8CountersV10CodingKeys33_37A6F768C70A5B8920883F88E539AEF9LLOs0G3KeyAAs23CustomStringConvertible
- _associated conformance 18FileProviderDaemon20FPDDomainFPFSBackendC8CountersV10CodingKeys33_37A6F768C70A5B8920883F88E539AEF9LLOs0G3KeyAAs28CustomDebugStringConvertible
- _objc_retain_x11
- _swift_retain_x11
- _symbolic SDy2ID_____Qz_____G 18FileProviderDaemon0A4ItemP AA13NSecTimestampV
- _symbolic SDy2ID_____Qz_____G 18FileProviderDaemon0A4ItemP AA15TruncationEventV
- _symbolic SDy_____ySo6FPItemCG_____G 18FileProviderDaemon11JobLockRuleO AA0deF14AssociatedJobsV
- _symbolic Say_____y2ID_____QzAbCQy_G______tG 18FileProviderDaemon13ThrottlingKeyO AA0A4ItemP AA11JobThrottleV
- _symbolic Say_____y__________G______tG 18FileProviderDaemon13ThrottlingKeyO AA9VFSItemIDO So06NSFileB14ItemIdentifiera AA11JobThrottleV
- _symbolic Say_____y__________G______tG 18FileProviderDaemon13ThrottlingKeyO So06NSFileB14ItemIdentifiera AA9VFSItemIDO AA11JobThrottleV
- _symbolic _____ 18FileProviderDaemon11VFSCountersV
- _symbolic _____ 18FileProviderDaemon11VFSCountersV10CodingKeys33_304ED64B271778B28A3D5A78B01E942BLLO
- _symbolic _____ 18FileProviderDaemon14TruncatedItemsV
- _symbolic _____ 18FileProviderDaemon14TruncatedItemsV10CodingKeys33_26512BA742A84555167AE8AC7BF31468LLO
- _symbolic _____ 18FileProviderDaemon15TruncationEventV
- _symbolic _____ 18FileProviderDaemon15TruncationEventV10CodingKeys33_26512BA742A84555167AE8AC7BF31468LLO
- _symbolic _____ 18FileProviderDaemon17TruncationMonitorC
- _symbolic _____ 18FileProviderDaemon20FPDDomainFPFSBackendC8CountersV10CodingKeys33_37A6F768C70A5B8920883F88E539AEF9LLO
- _symbolic _____y_____3key______5valuetG s23_ContiguousArrayStorageC 18FileProviderDaemon9VFSItemIDO AC13NSecTimestampV
- _symbolic _____y_____3key______5valuetG s23_ContiguousArrayStorageC 18FileProviderDaemon9VFSItemIDO AC15TruncationEventV
- _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE So16os_unfair_lock_sV
- _symbolic _____y_____G 18FileProviderDaemon14TruncatedItemsV AA7VFSItemV
- _symbolic _____y_____G s22KeyedDecodingContainerV 18FileProviderDaemon11VFSCountersV10CodingKeys33_304ED64B271778B28A3D5A78B01E942BLLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 18FileProviderDaemon15TruncationEventV10CodingKeys33_26512BA742A84555167AE8AC7BF31468LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 18FileProviderDaemon20FPDDomainFPFSBackendC8CountersV10CodingKeys33_37A6F768C70A5B8920883F88E539AEF9LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 18FileProviderDaemon11VFSCountersV10CodingKeys33_304ED64B271778B28A3D5A78B01E942BLLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 18FileProviderDaemon15TruncationEventV10CodingKeys33_26512BA742A84555167AE8AC7BF31468LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 18FileProviderDaemon20FPDDomainFPFSBackendC8CountersV10CodingKeys33_37A6F768C70A5B8920883F88E539AEF9LLO
- _symbolic _____y_____So6FPItemCG 18FileProviderDaemon17TruncationMonitorC AA7VFSItemV
- _symbolic _____y_____So6FPItemCGSgXw 18FileProviderDaemon17TruncationMonitorC AA7VFSItemV
- _symbolic _____y__________G s18_DictionaryStorageC 18FileProviderDaemon9VFSItemIDO AC13NSecTimestampV
- _symbolic _____y__________G s18_DictionaryStorageC 18FileProviderDaemon9VFSItemIDO AC15TruncationEventV
- _symbolic _____y_____yxGG 18FileProviderDaemon13WharfResourceC AA14TruncatedItemsV
- _symbolic _____yxq_G 18FileProviderDaemon17TruncationMonitorC
- _symbolic _____yxq_GSg 18FileProviderDaemon17TruncationMonitorC
- _symbolic _____yxq_GSgXw 18FileProviderDaemon17TruncationMonitorC
- _symbolic _____yxq_GSgXwz_x_q______RzADR_r0_lXX 18FileProviderDaemon17TruncationMonitorC AA0A4ItemP
- _type_layout_string 18FileProviderDaemon0A4ItemRzlAA14TruncatedItemsVyxG
- _type_layout_string 18FileProviderDaemon15TruncationEventV
CStrings:
+ "\n            AND "
+ "\n        OR (fp.metadata_kind == "
+ "\n   AND bd.reason & "
+ "\n   AND rt.rowid <= "
+ "\n WHERE 1 ORDER BY item_id, kind, job_type"
+ "\nRECURSIVE STEP\nSCAN c\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "\nUSE TEMP B-TREE FOR ORDER BY"
+ " != 0\n   AND rt.fp_content_status IN ("
+ " (parent_id=? AND filename=?)\nSEARCH rt USING INDEX "
+ " USING COVERING INDEX sqlite_autoindex_"
+ " USING INDEX sqlite_autoindex_"
+ " USING INTEGER PRIMARY KEY (rowid=?)"
+ " USING INTEGER PRIMARY KEY (rowid=?)\nLIST SUBQUERY 1\nSCAN "
+ " USING INTEGER PRIMARY KEY (rowid>?)"
+ ")\n   AND rt.fs_disk_import_status IS NULL\n   AND rt.fs_id IS NOT NULL\n   AND rt.fp_id IS NOT NULL\n   AND rt.rowID > "
+ ")\n   AND rt.fs_disk_import_status IS NULL\n   AND rt.fs_id IS NOT NULL\n   AND rt.rowID > "
+ ")\n  AND fs_disk_import_status IS NULL\n  AND fs_id IS NOT NULL"
+ ")) AS checks_passed\n  FROM reconciliation_table AS rt\n  INNER JOIN fp_snapshot AS fp ON (rt.fp_id = fp.id)\n WHERE rt.fp_content_status IN ("
+ "-[FPDKnownFolderAttachForDetachAlertPresenter presentAlertWithoutUserApprovalNeededToContinue]"
+ "-[FPDXPCServicer startAccessingServiceWithName:itemID:domain:connection:enumerateEntitlementRequired:callerSelector:completionHandler:]_block_invoke"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/FileProviderTools/fssync/libfssync/implementations/file-system/persistence/FPFSSQLRestoreEngine.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/FileProviderTools/fssync/libfssync/implementations/file-system/persistence/SQLDatabase+EagerlyDownload.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/FileProviderTools/fssync/libfssync/implementations/file-system/persistence/SQLDatabase+Telemetry.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/FileProviderTools/fssync/libfssync/implementations/file-system/persistence/SQLDatabase+VFSIDLookupCache.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/FileProviderTools/fssync/libfssync/implementations/file-system/persistence/SQLHistoryTable.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/FileProviderTools/fssync/libfssync/implementations/file-system/persistence/SQLReconciliationTable+Search.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/FileProviderTools/fssync/libfssync/implementations/file-system/persistence/SQLSyncStateTable.swift"
+ "CO-ROUTINE cycles\nSETUP\nSCAN "
+ "CO-ROUTINE ignored_parents\nSETUP\nSEARCH "
+ "CO-ROUTINE parentHierarchy\nSETUP\nSEARCH rec USING INDEX "
+ "CO-ROUTINE parentHierarchy\nSETUP\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "CO-ROUTINE parent_dirs\nSETUP\nSEARCH "
+ "CO-ROUTINE parent_is_pinned\nSETUP\nSEARCH "
+ "CO-ROUTINE path_matching\nSETUP\nSEARCH s USING INDEX sqlite_autoindex_"
+ "CREATE INDEX idx_reconciliation_eagerly_download_optimized\nON reconciliation_table(fs_disk_import_status)\nWHERE fp_content_status IN ("
+ "DROP INDEX IF EXISTS idx_reconciliation_eagerly_download_optimized"
+ "EXPLAIN QUERY PLAN"
+ "Error resolving vfs item for url %{public}s: %{public}@"
+ "SCAN rt USING INDEX reconciliation_content_indexable_non_user_evicted\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "SCAN snap\nSEARCH parent_snap USING COVERING INDEX sqlite_autoindex_"
+ "SCAN snap USING COVERING INDEX "
+ "SEARCH fp USING INTEGER PRIMARY KEY (rowid>?)\nCORRELATED SCALAR SUBQUERY 1\nSEARCH child USING INDEX "
+ "SEARCH fs_item_jobs USING INDEX FS_item_jobs_state_type__scheduling_ordering (scheduling_state=? AND type=?)"
+ "SEARCH j USING INDEX "
+ "SEARCH reconciliation_table USING COVERING INDEX "
+ "SEARCH reconciliation_table USING INDEX sqlite_autoindex_reconciliation_table_2 (fp_id=?)"
+ "SEARCH rt USING COVERING INDEX reconciliation_fs_disk_import_status__fs_id ("
+ "SEARCH rt USING COVERING INDEX reconciliation_pending_set (fp_id=? AND fs_scheduling_state=?)\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "SEARCH rt USING INDEX "
+ "SEARCH rt USING INDEX idx_reconciliation_eagerly_download_optimized (fs_disk_import_status=? AND rowid>?)\nSEARCH fp USING INDEX sqlite_autoindex_FP_snapshot_1 (id=?)"
+ "SEARCH rt USING INDEX reconciliation__fp_scheduling_state__fs_id (fp_scheduling_state=? AND fs_id=?)\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "SEARCH rt USING INDEX reconciliation_content_indexable_non_user_evicted (last_content_change<?)\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "SEARCH rt USING INDEX reconciliation_content_indexable_non_user_evicted (last_content_change=?)\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "SEARCH rt USING INDEX reconciliation_global_progress_materialize ("
+ "SEARCH rt USING INDEX reconciliation_kind_last_change (kind=? AND last_change<?)\nSEARCH snap USING COVERING INDEX sqlite_autoindex_"
+ "SEARCH rt USING INDEX reconciliation_kind_last_change (kind=? AND last_change<?)\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "SEARCH rt USING INDEX reconciliation_kind_last_content_change (kind=? AND last_content_change<?)\nSEARCH snap USING COVERING INDEX sqlite_autoindex_"
+ "SEARCH rt USING INTEGER PRIMARY KEY (rowid>? AND rowid<?)\nSEARCH bd USING INDEX sqlite_autoindex_background_downloader_1 (id=?)"
+ "SEARCH rt USING INTEGER PRIMARY KEY (rowid>?)\nCORRELATED LIST SUBQUERY 3\nMATERIALIZE parent_1\nSETUP\nSEARCH rec_snap_1 USING INDEX sqlite_autoindex_"
+ "SEARCH snap USING INDEX "
+ "SEARCH snap USING INTEGER PRIMARY KEY (rowid>?)"
+ "SELECT bd.id\n  FROM reconciliation_table AS rt\n INNER JOIN background_downloader AS bd ON (bd.id = rt.fs_id)\n WHERE rt.rowid > "
+ "SELECT rt.rowID, rt.fs_id,\n       ("
+ "SELECT rt.rowID, rt.fs_id,\n       fs.metadata_is_in_pinned_folder AS checks_passed\n  FROM reconciliation_table AS rt\n  INNER JOIN fs_snapshot AS fs ON (rt.fs_id = fs.id)\n WHERE rt.fp_content_status IN ("
+ "USE TEMP B-TREE FOR count(DISTINCT)\nSCAN "
+ "[ERROR] failed to migrate indexer state file %@: %@"
+ "[ERROR] failed to remove old indexer support directory at %@: %s"
+ "[ERROR] indexer state migration incomplete, keeping old directory at %@"
+ "[ERROR] supportURL: support path for %@ not found: %@"
+ "[INFO] migrated indexer state from %@ to %@"
+ "_1 (id=?)\nLIST SUBQUERY 1\nSEARCH "
+ "_1 (id=?)\nRECURSIVE STEP\nSCAN parentHierarchy\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "_1 (id=?)\nRECURSIVE STEP\nSCAN parent_1\nSEARCH rec_snap_1 USING INDEX sqlite_autoindex_"
+ "_1 (id=?)\nRECURSIVE STEP\nSCAN parent_dirs\nSEARCH "
+ "_1 (id=?)\nRECURSIVE STEP\nSCAN parent_is_pinned\nSEARCH "
+ "_1 (id=?)\nSCAN cycles"
+ "_1 (id=?)\nSCAN parentHierarchy"
+ "_1 (id=?)\nSCAN parent_1"
+ "_1 (id=?)\nSCAN parent_1\nUSE TEMP B-TREE FOR ORDER BY"
+ "_1 (id=?)\nSCAN parent_dirs"
+ "_1 (id=?)\nSCAN parent_is_pinned"
+ "_1 (id=?)\nSCAN path_matching"
+ "_1 (id=?)\nSEARCH jobs USING INDEX "
+ "_1 (id=?)\nSEARCH parent_rec USING INDEX "
+ "_1 (id=?)\nSEARCH rt USING INDEX "
+ "_1 (id=?)\nSEARCH rt USING INDEX reconciliation_"
+ "_1 (id=?)\nUSE TEMP B-TREE FOR ORDER BY"
+ "_1 (id=?) LEFT-JOIN"
+ "__scheduling_state__scheduling_state_conditions__pending_scheduling_timestamp"
+ "__scheduling_state__scheduling_state_conditions__pending_scheduling_timestamp (scheduling_state=?)"
+ "__type__state (type=? AND scheduling_state=? AND rowid>?)"
+ "__type__state (type=? AND scheduling_state=? AND rowid>?)\nCORRELATED LIST SUBQUERY 3\nMATERIALIZE parent_1\nSETUP\nSEARCH rec_snap_1 USING INDEX sqlite_autoindex_"
+ "__type__state (type=? AND scheduling_state=? AND rowid>?)\nSEARCH snap USING COVERING INDEX sqlite_autoindex_"
+ "__type__state (type=? AND scheduling_state=?)\nUSE TEMP B-TREE FOR ORDER BY"
+ "__type__state (type=?)"
+ "__type__state (type=?)\nUSE TEMP B-TREE FOR ORDER BY"
+ "_accountActiveFPContentJobs(with:)"
+ "_accountActiveFPMaterializeJobs(with:)"
+ "_accountActiveFPOtherJobs(with:)"
+ "_disk_import_status=?)\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "_fixupOutOfSyncFSBaseVersionInternal(from:with:)"
+ "_id=? AND rowid>?)\nCORRELATED LIST SUBQUERY 3\nMATERIALIZE parent_1\nSETUP\nSEARCH rec_snap_1 USING INDEX sqlite_autoindex_"
+ "_id=?)\nRECURSIVE STEP\nSCAN ignored_parents\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "_id=?)\nRECURSIVE STEP\nSCAN parentHierarchy\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "_id=?)\nRECURSIVE STEP\nSCAN pm\nSEARCH parent_rt USING INDEX "
+ "_id=?)\nSCAN ignored_parents"
+ "_id=?)\nSCAN parentHierarchy"
+ "_id=?)\nSEARCH other_snap USING INDEX sqlite_autoindex_"
+ "_id=?)\nSEARCH other_snapshot USING INDEX "
+ "_id=?)\nSEARCH s USING INDEX sqlite_autoindex_"
+ "_id=?)\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "_id=?) LEFT-JOIN"
+ "_id__kind__job_type__ordering"
+ "_id__kind__job_type__ordering (item_id=? AND kind=?)"
+ "_id__kind__job_type__ordering (item_id=?)"
+ "_item_jobs_state_type__scheduling_ordering (scheduling_state=? AND type=?)\nBLOOM FILTER ON p (id=?)\nSEARCH p USING AUTOMATIC COVERING INDEX (id=?)"
+ "_item_jobs_state_type__scheduling_ordering (scheduling_state=? AND type=?)\nSEARCH rt USING INDEX "
+ "_item_jobs_type (item_id=? AND type=?)"
+ "_materialization_status=?)\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "_materialize_children (parent_id=? AND metadata_is_dataless=? AND metadata_kind=?)\nSEARCH rt USING INDEX sqlite_autoindex_reconciliation_table_1 (fs_id=?)"
+ "_parent_id__filename_idx (parent_id=? AND filename=?)"
+ "_parent_id__filename_idx (parent_id=?)"
+ "_parent_id__filename_idx (parent_id=?)\nSEARCH job USING INDEX "
+ "_parent_id__filename_idx (parent_id=?)\nSEARCH reconciliation_table USING COVERING INDEX "
+ "_parent_id__filename_idx (parent_id=?)\nSEARCH rt USING INDEX "
+ "_parent_id__id__ignore\nRECURSIVE STEP\nSCAN c\nSEARCH snap USING INDEX sqlite_autoindex_"
+ "_parent_id__id__ignore\nSEARCH parent_snap USING COVERING INDEX sqlite_autoindex_"
+ "_parent_id__id__syncroot (id=?)\nRECURSIVE STEP\nSCAN parent_dirs\nSEARCH "
+ "_parent_id__id__syncroot (id=?)\nSCAN parent_dirs"
+ "_parent_id_idx (parent_id=? AND rowid>?)"
+ "_parent_id_idx (parent_id=?)"
+ "_parent_id_idx (parent_id=?)\nSEARCH job USING INDEX "
+ "_parent_id_idx (parent_id=?)\nSEARCH reconciliation_table USING COVERING INDEX "
+ "_parent_id_idx (parent_id=?)\nSEARCH rt USING INDEX "
+ "_per_job (kind=? AND item_id=? AND job_type=?)"
+ "_refreshItemContentRank(isDataless:isEvicting:with:condition:)"
+ "_scheduling_state ("
+ "_scheduling_state=?)\nBLOOM FILTER ON p (id=?)\nSEARCH p USING AUTOMATIC COVERING INDEX (id=?)"
+ "_snapshot_1 (id=?)"
+ "_snapshot_1 (id=?)\nRECURSIVE STEP\nSCAN parent_1\nSEARCH rec_snap_1 USING INDEX sqlite_autoindex_"
+ "_snapshot_1 (id=?)\nSCAN parent_1\nUSE TEMP B-TREE FOR ORDER BY"
+ "_snapshot_1 (id=?) LEFT-JOIN\nUSE TEMP B-TREE FOR ORDER BY"
+ "_snapshot_parent_id__filename_idx"
+ "_snapshot_parent_id__filename_idx (parent_id=? AND filename=?)\nSEARCH rt USING INDEX "
+ "_state (scheduling_state=? AND rowid>?)"
+ "_state (scheduling_state=?)"
+ "_state_type__scheduling_ordering (scheduling_state=? AND type=?)\nUSE TEMP B-TREE FOR ORDER BY"
+ "_type (item_id=? AND type=?)"
+ "_type (item_id=? AND type=?)\nLIST SUBQUERY 1\nSEARCH reconciliation_table USING INDEX sqlite_autoindex_reconciliation_table_1 (fs_id=?)"
+ "_type (item_id=? AND type=?)\nLIST SUBQUERY 1\nSEARCH reconciliation_table USING INDEX sqlite_autoindex_reconciliation_table_2 (fp_id=?)"
+ "_type (item_id=?)"
+ "_uploading_errors (decoration_is_uploaded=? AND decoration_uploading_error>?)"
+ "accountActiveFSJobs(with:)"
+ "accumulatedSizeOfItems(with:)"
+ "accumulatedSizeOfPinnedItems(with:)"
+ "activate(with:)"
+ "addSideColumn(_:with:)"
+ "applyBugfixHeuristics(from:with:)"
+ "backgroundDownloadReason(for:with:)"
+ "bootstrapSchema(with:)"
+ "bootstrapTriggers(with:)"
+ "bumpPriority(of:for:on:to:with:)"
+ "bumpPriority(of:for:to:with:)"
+ "cacheInheritedUserInfo(by:with:)"
+ "calculateSizeOfPendingDownload(jobLimit:with:matching:)"
+ "cancelRunningSpeculativeDownloads(with:)"
+ "checkAndUpgradeDatabase(creationReason:with:)"
+ "checkIfAllRunningDownloadsFinished(with:)"
+ "clearThrottling(with:for:)"
+ "containsBoundChildren(below:with:)"
+ "containsChildren(below:checkDeletionStatus:with:)"
+ "containsChildrenReparentingToTrashRoot(below:with:)"
+ "containsChildrenWithRunningCreations(below:with:)"
+ "containsItem(with:with:)"
+ "containsMustDownloadedChildren(below:with:)"
+ "containsPendingDeletionChildren(below:forRecursiveDeletion:with:)"
+ "containsPendingEvictionChildren(below:with:)"
+ "containsPendingReconciliationChildren(below:with:)"
+ "containsUnboundChildren(below:ignoreThrottled:with:)"
+ "countPendingItemsInDB(with:)"
+ "countRunnableJobs(of:max:with:)"
+ "createLastChangeTriggers(with:)"
+ "createMaterializedSetTriggers(with:)"
+ "createRecursiveTrigger(_:for:with:condition:)"
+ "createRecursiveTriggerWithRec(_:for:with:condition:)"
+ "delete(_:mode:with:)"
+ "delete(entry:at:cancelMaterialization:with:)"
+ "deleteChildrenInDB(_:with:)"
+ "deleteLastChangeTriggers(with:)"
+ "deleteLazy(_:mode:with:)"
+ "deleteMaterializedSetTriggers(with:)"
+ "deleteRecursiveEvictabilityTriggers(with:)"
+ "deleteRecursiveTriggers(_:with:)"
+ "deleteRecursiveTriggersWithRecTable(_:with:)"
+ "descendantsPendingScan(below:startingRowID:barrierTimestamp:pageSize:with:)"
+ "descendentsWithIncomingChanges(of:startingRowID:scheduledBefore:pageSize:with:)"
+ "descendentsWithIncomingMetadataChanges(of:startingRowID:scheduledBefore:pageSize:with:)"
+ "disable(_:with:)"
+ "doWhile(pendingOnly:with:callback:)"
+ "doWhile(with:callback:)"
+ "dump(with:to:)"
+ "dump(with:to:limitNumberOfItems:)"
+ "dump(with:to:runOnDBQueue:)"
+ "dumpActiveFPJobsInGlobalProgress(with:to:)"
+ "eagerlyDownloadContentPolicyExhausted"
+ "eagerlyDownloadPinnedExhausted"
+ "eagerlyDownloadRowIDContentPolicy"
+ "eagerlyDownloadRowIDPinned"
+ "enable(_:now:with:nextThrottleCb:)"
+ "enumerateBackgroundWork(for:with:_:)"
+ "enumerateChildrenIDAndKind(below:from:with:)"
+ "enumerateConflictedDatalessItems(from:with:)"
+ "enumerateDatalessContainersIDs(below:with:_:)"
+ "enumerateDiskImportStatusOnFPSide(from:with:)"
+ "enumerateEvictingItemsWithNotInterestedContent(from:with:)"
+ "enumerateFPPendingItems(from:with:)"
+ "enumerateFSPendingItems(from:with:)"
+ "enumerateFoldersWithUnpropagatedContentPolicy(from:with:)"
+ "enumerateIgnoredItemsBlockedOldContentInjection(from:with:)"
+ "enumerateImportingFolders(with:cb:)"
+ "enumerateItemsBlockedOnBouncing(from:with:)"
+ "enumerateItemsPendingRejection(from:with:)"
+ "enumerateItemsWaiting(for:on:with:from:connection:)"
+ "enumerateItemsWithParentDeletedChildren(from:with:)"
+ "enumerateNonLockedDictoriesIDNotAllowingChanges(from:with:)"
+ "enumerateNonPurgeablePackageItemIDs(from:with:)"
+ "enumerateNonSyncRootPackageItemIDs(from:with:)"
+ "enumerateOrphanedItemsWithParentDeleted(below:from:with:)"
+ "enumeratePackages(from:with:)"
+ "enumeratePathMatchingDuringImport(from:with:)"
+ "enumeratePausedReconciliations(with:)"
+ "enumerateRunningEntries(from:with:)"
+ "enumerateSnapshottingItems(on:from:with:)"
+ "enumerateSpeculativeDocuments(limit:rowID:with:block:)"
+ "enumerateStuckChildrenDeletion(from:with:)"
+ "enumerateStuckDiskImportItems(from:with:)"
+ "enumerateStuckPathMatching(on:from:with:)"
+ "enumerateStuckRemoteDeletions(from:with:)"
+ "enumerateThrottledEntries(from:with:)"
+ "enumerateUploadedNonEvictableItems(from:with:)"
+ "expire(limit:with:_:)"
+ "fetch(for:useCache:with:)"
+ "fetchBackgroundUploadWaitingItems(from:limit:anyCondition:with:)"
+ "fetchBackgroundUploadWaitingItems(limit:anyCondition:with:)"
+ "fetchBoundaryEntry(_:with:)"
+ "fetchDomainWideError(_:with:)"
+ "fetchEagerlyDownloadPendingItems(from:lookForPinnedItems:limit:with:)"
+ "fetchEvictedWithOldVersionPendingItems(from:limit:with:)"
+ "fetchJobs(with:index:where:callback:)"
+ "fetchJobs(with:where:callback:)"
+ "fetchMaterializedItemsWithInfiniteRank(from:with:)"
+ "fetchMinEntryWith(_:with:)"
+ "fetchNumberOfNonMaterializedFiles(with:)"
+ "fetchParentHierarchy(of:with:)"
+ "fetchPreventIgnoreFolderProcessing(with:)"
+ "fetchPreventedEvictability(with:)"
+ "fetchRunnableEntries(side:with:jobLimitsGetter:)"
+ "fetchScheduledItemsInRange(prevRTRowID:currentRTRowID:reason:with:)"
+ "fetchTestingOperations(with:)"
+ "fetchThrottles(for:job:since:state:with:)"
+ "fetchUploadingErrors(with:callback:)"
+ "fetchWaitingJobs(ofEither:on:max:with:)"
+ "fetchWithFlockedFiles(_:with:)"
+ "filterBoundItems(_:with:)"
+ "findClosestSyncRoot(_:with:)"
+ "forceAttachToDetachPromptLastInterception"
+ "fpTelemetryReport(indexBarrier:with:report:)"
+ "fsTelemetryReport(with:report:)"
+ "getIDAndKindOfChildren(ofParent:with:)"
+ "hasAncestorBeingRescanned(_:interestingReasons:with:)"
+ "hasAnyDeletedParent(for:with:)"
+ "hasBoundIgnoredItems(with:)"
+ "hasCreationReason(_:with:)"
+ "hasExpiredUploadTimeoutThrottling(with:)"
+ "hasIgnoredItems(for:with:)"
+ "hasItemJob(for:of:reason:with:)"
+ "hasItemJob(withEitherType:with:)"
+ "hasJob(matching:with:)"
+ "hasJobs(of:with:)"
+ "hasNonWatchedImportedItems(with:)"
+ "hasResetingOrDeletedParent(_:with:)"
+ "hasRunningDiskScanning(with:)"
+ "hasRunningJob(of:on:with:)"
+ "hasRunningJobs(of:with:)"
+ "hasRunningPendingSelection(with:)"
+ "hasSchedulableWaitingJobs(with:)"
+ "hasWaitingJobs(mode:with:)"
+ "hasWaitingJobs(ofEither:on:with:)"
+ "hasWaitingJobs(with:)"
+ "hasWaitingReconciliations(mode:with:)"
+ "importProgressForItemsPendingReconciliation(progressReport:with:diagnosticAttributesHandler:)"
+ "importProgressForItemsPendingScanningDisk(progressReport:with:diagnosticAttributesHandler:)"
+ "importProgressForItemsPendingScanningProvider(progressReport:with:diagnosticAttributesHandler:)"
+ "insert(_:mode:with:)"
+ "insert(entry:with:)"
+ "insert(job:with:)"
+ "insertOrUpdate(_:with:)"
+ "isInDiskImport(with:)"
+ "isInResetStream(with:)"
+ "isJobThrottled(_:for:priority:permanently:with:)"
+ "item(_:containsChildRemotelyParentedTo:with:)"
+ "item(_:isBeingMovedInto:with:)"
+ "item(_:isBlockedOn:byPathMatching:with:)"
+ "item(_:isDescendentOf:with:)"
+ "itemCount(with:)"
+ "itemIsIgnoredOrHasAnIgnoredAncestor(_:with:)"
+ "itemWithNoAllowsEvictCapabilityCount(with:)"
+ "lastAnchor(with:)"
+ "listPendingIngestionsOfUnknownItems(startingRowID:barrierTimestamp:pageSize:with:)"
+ "lookup(byFileID:with:)"
+ "lookupDecorations(by:includeNonSyncableAttributes:with:)"
+ "lookupEffectiveContentPolicy(by:with:)"
+ "lookupFPRecursiveProperties(by:with:)"
+ "lookupFSRecursiveProperties(by:with:)"
+ "lookupID(_:with:)"
+ "lookupID(for:with:)"
+ "lookupInheritedContentPolicy(by:with:)"
+ "lookupInheritedNamespacePolicy(by:with:)"
+ "lookupInheritedUserInfo(by:with:)"
+ "lookupIsInPinnedFolder(by:allowCache:with:)"
+ "lookupItem(by:snapshotVersion:with:)"
+ "lookupItem(by:with:)"
+ "lookupItem(byFileID:with:)"
+ "lookupItemIDs(byParent:andFilename:excluding:with:)"
+ "lookupItemNonSyncableAttributesColumns(by:with:)"
+ "lookupItemReadyForImport(with:)"
+ "lookupLink(byFileID:with:)"
+ "lookupParentID(for:with:)"
+ "lookupPathMatchingItemIDInCreationParentHierarchy(for:with:)"
+ "lookupRandomItems(count:with:callback:)"
+ "lookupSnapshotVersion(by:with:)"
+ "materializationJobEnded(_:now:with:)"
+ "materializedSetChanges(since:limit:with:)"
+ "no source base version"
+ "no source baseVersion"
+ "nonAutoEvictableDiskSpace(with:)"
+ "nonDownloadedAfterIndexDrop(indexDropBarrier:from:maxCount:with:)"
+ "nonDownloadedRecents(dateThreshold:maxCount:with:block:)"
+ "nonDownloadedUnindexed(maxCount:with:block:)"
+ "parentHierarchy(of:contains:with:)"
+ "patchFSItemJobsTable(with:backupManifest:)"
+ "patchFSSnapshotTable(with:backupManifest:)"
+ "patchFSThrottleTable(with:backupManifest:)"
+ "patchJobsTable(with:backupManifest:)"
+ "patchReconciliationTable(with:backupManifest:)"
+ "patchTombstoneTable(with:backupManifest:)"
+ "pendingBackgroundDownloadsDidChange(with:)"
+ "pendingIndexDeletionItemCount(from:with:)"
+ "pendingIndexableItemCount(from:with:)"
+ "pendingIndexingDeletion(from:limit:with:_:)"
+ "pendingIndexingItems(from:limit:with:_:)"
+ "persist(_:with:)"
+ "persistProgression(of:with:)"
+ "react(to:conditions:side:with:query:)"
+ "react(to:with:)"
+ "rearm(with:)"
+ "recursiveLookupIsParentPinned(id:with:)"
+ "refreshItem(_:with:)"
+ "registerUpdate(db:fs:fp:creationReason:forceStoreReason:with:)"
+ "resetDatalessWithCloneItemRecursiveCount(for:with:)"
+ "resetRecursiveDatalessWithCloneCount(with:)"
+ "resolveChildInheritedNamespacePolicy(by:with:)"
+ "runningBackgroundDownloadReason(for:with:)"
+ "scan(directoryID:startingFrom:includeDecorations:additionalFilter:with:)"
+ "scanDBForPendingItems(with:)"
+ "scanDecoratedItems(below:continuation:with:_:)"
+ "scanDecoratedItemsForAppLibraries(below:filename:with:continuation:_:)"
+ "scanIgnoredItems(from:with:)"
+ "scanPendingReimportCleanupItems(with:)"
+ "scheduleBackgroundDownload(for:reason:now:range:with:)"
+ "scheduleEagerlyDownloadContinuationIfNeeded(remainingSlots:)"
+ "set(_:with:)"
+ "sharedSchedulerIsDeferred(_:)"
+ "sqlite_autoindex_reconciliation_table_"
+ "stageUpdate(itemID:continuation:capturedContent:requestedState:otherVersion:otherBaseVersion:baseVersion:on:result:nonSyncableAttributes:with:completion:)"
+ "startBackgroundDownloads(with:)"
+ "syncPausedItemCount(with:)"
+ "syncRootsHierarchyResult(for:with:)"
+ "totalIndexableItemCount(with:)"
+ "treeRoots(with:fast:)"
+ "unboundDescendents(of:startingRowID:scheduledBefore:pageSize:with:)"
+ "unscheduleBackgroundDownload(for:reason:with:)"
+ "update(_:diffs:mode:with:)"
+ "update(entry:from:at:with:)"
+ "update(itemID:continuation:capturedContent:stagedContext:requestedState:otherVersion:otherBaseVersion:baseVersion:on:result:nonSyncableAttributes:completion:)"
+ "updateActivityRegistration(with:)"
+ "updateAndSchedulePending(_:with:)"
+ "updateBackgroundDownloaderWithNewScheduledDownload(id:with:extraCondition:)"
+ "updateItemsClosestSyncRoot(previousClosestSyncRoot:newClosestSyncRoot:with:)"
+ "updateItemsConflictVersionsInGS(from:with:)"
+ "updateItemsSpeculativeFulfilled(from:with:)"
+ "updatePending(_:)"
+ "updateSpeculativeDiskManagementOnDownloaderActivation(with:)"
+ "update_v10_255_DLV2(with:)"
+ "update_v10_256_residencyReasons(with:)"
+ "update_v10_257_DLV2_recursiveDatalessWithCloneCount(with:)"
+ "update_v11_1_DLV2_recursiveDatalessWithCloneCount(with:)"
+ "update_v11_3_lastContentChange(with:)"
+ "update_v11_4_indexDocument(with:)"
+ "update_v11_7_betterIndexForContentRank(with:)"
+ "update_v12_0_dropContentPolicyDBTriggers(with:)"
+ "update_v12_1_namespacePolicy(with:)"
+ "update_v12_2_materializedSetChangesImprovement(with:)"
+ "update_v12_3_dropPinningTriggers(with:)"
+ "update_v13_1_dropUnusedIndexes(with:)"
+ "update_v13_2_dropLowUsedIndexes(with:)"
+ "update_v13_3_stuckDeletionMonitor(with:)"
+ "update_v13_4_eagerlyDownloadIndex(with:)"
+ "update_v2_0_domainVersion(with:)"
+ "update_v2_1_indexing(with:)"
+ "update_v2_2_pendingSet(with:)"
+ "update_v2_3_featureFlags(with:)"
+ "update_v2_4_missingIndex(with:)"
+ "update_v2_5_ignoredFiles(with:)"
+ "update_v2_6_globalProgresses(with:)"
+ "update_v2_8_closestSyncRoot(with:)"
+ "update_v2_9_globalProgressesIndexes(with:)"
+ "update_v3_0_inheritedUserInfo(with:)"
+ "update_v3_1_osType(with:)"
+ "update_v3_2_recursiveEvictable(with:)"
+ "update_v3_3_recursiveCapabilities(with:)"
+ "update_v3_4_probePendingSetIndex(with:)"
+ "update_v3_5_linkCount(with:)"
+ "update_v3_6_materializedSetTrigger(with:)"
+ "update_v3_7_recursiveDeletionIndex(with:)"
+ "update_v4_0_capturedContent(with:)"
+ "update_v5_0_pause(with:)"
+ "update_v5_10_errorGeneration(with:)"
+ "update_v5_11_persistedPendingSet(with:)"
+ "update_v5_1_sharedItemIdentifier(with:)"
+ "update_v5_2_contentPolicy(with:)"
+ "update_v5_3_conflictingVersions(with:)"
+ "update_v5_4_collaborationIdentifier(with:)"
+ "update_v5_6_lastEditorDeviceName(with:)"
+ "update_v5_7_collaborationIdentifierInFS(with:)"
+ "update_v5_8_backgroundBRM(with:)"
+ "update_v6_0_fileConflictInGenStore(with:)"
+ "update_v6_2_databaseCreationReason(with:)"
+ "update_v6_4_fixupWrongTriggerErase(with:)"
+ "update_v6_4_namespaceContentPolicy(with:)"
+ "update_v6_5_namespaceContentPolicy(with:)"
+ "update_v7_0_detachedRoots(with:)"
+ "update_v7_1_speculativeContentPolicy(with:)"
+ "update_v7_3_speculativeContentParentChange(with:)"
+ "update_v7_4_contentPolicyReduceParentMaterializationCallsWork(with:)"
+ "update_v8_0_fileSystemCaseSensitivity(with:)"
+ "update_v8_1_itemFlockedIndexes(with:)"
+ "update_v8_2_uploadingErrorIndex(with:)"
+ "update_v8_3_postponeUploadError(with:)"
+ "update_v9_255_backgroundDownloaderReasonIndex(with:)"
+ "update_v9_256_showSpeculativeDownloadsInGlobalProgress(with:)"
+ "update_v9_257_policyTriggers(with:)"
+ "update_v9_258_purgeReasons(with:)"
+ "update_v9_260_removeContentPolicyTriggers(with:)"
+ "update_v9_261_pinning(with:)"
+ "update_v9_264_stuckDeletionMonitor2(with:)"
+ "value(key:with:)"
+ "vendorContentPolicyCount(policy:with:)"
+ "vendorEffectiveEvictOnRemoteUpdatePolicyCount(with:)"
+ "vendorEffectiveKeepDownloadedPolicyCount(with:)"
+ "vendorEffectiveLazyPolicyCount(with:)"
+ "🔮  eagerly-download continuation cancelled: %@"
+ "🔮  refreshing eagerly download set continuation with %ld slots"
- "\n    OR (fp.metadata_kind == "
- "  - monitored items:"
- "  - requested diagnostics:"
- "+ truncation monitor:"
- "+ truncation monitor: no activity"
- "-[FPDXPCServicer startAccessingServiceWithName:itemID:domain:connection:enumerateEntitlementRequired:completionHandler:]_block_invoke"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/FileProviderTools/fssync/libfssync/implementations/file-system/persistence/DatabaseAccessors.swift"
- "1 ORDER BY item_id, kind, job_type"
- "Error resolving vfs item for url %{public}s: %@"
- "SEARCH rt USING INDEX idx_reconciliation_eagerly_download_optimized (fs_disk_import_status=? AND rowid>?)\nSEARCH fs USING INDEX sqlite_autoindex_FS_snapshot_1 (id=?)\nSEARCH fp USING INDEX sqlite_autoindex_FP_snapshot_1 (id=?) LEFT-JOIN"
- "SELECT rt.rowID, rt.fs_id\n  FROM reconciliation_table AS rt\n  LEFT JOIN fs_snapshot AS fs ON (rt.fs_id = fs.id)\n  LEFT JOIN fp_snapshot AS fp ON (rt.fp_id = fp.id)\n WHERE fs.metadata_is_dataless = 1\n   AND rt.fs_disk_import_status IS NULL\n   AND "
- "[DEBUG] [Indexer] Error creating support directory for %@, error: %@"
- "_evict(_:evictionReason:completion:)"
- "execute(_:)"
- "fetch(_:)"
- "fetchValue(of:query:)"
- "fs.metadata_is_in_pinned_folder"
- "stageUpdate(itemID:continuation:capturedContent:requestedState:otherVersion:baseVersion:on:result:nonSyncableAttributes:with:completion:)"
- "truncation-monitor.plist"
- "truncationMonitor"
- "update(itemID:continuation:capturedContent:stagedContext:requestedState:otherVersion:baseVersion:on:result:nonSyncableAttributes:completion:)"
```
