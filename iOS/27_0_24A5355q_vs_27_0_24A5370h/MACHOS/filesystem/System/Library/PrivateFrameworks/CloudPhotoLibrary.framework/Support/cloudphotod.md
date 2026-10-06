## cloudphotod

> `/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/Support/cloudphotod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ca584` | `0x1cc134` | **`+0x1bb0`** |
| `__TEXT.__oslogstring` | `0x1237a` | `0x125eb` | **`+0x271`** |
| `__TEXT.__cstring` | `0x1be5f` | `0x1c0a2` | **`+0x243`** |
| `__TEXT.__objc_methname` | `0x2aae1` | `0x2ace1` | **`+0x200`** |
| `__DATA_CONST.__const` | `0xaeb8` | `0xb030` | **`+0x178`** |
| `__DATA.__objc_const` | `0x1ed30` | `0x1ee98` | **`+0x168`** |
| `__DATA_CONST.__cfstring` | `0x13320` | `0x13440` | **`+0x120`** |
| `__TEXT.__objc_stubs` | `0x1ca00` | `0x1cb00` | **`+0x100`** |
| `__TEXT.__gcc_except_tab` | `0x2d74` | `0x2e68` | **`+0xf4`** |
| `__TEXT.__objc_methlist` | `0x10894` | `0x1091c` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x6d40` | `0x6db8` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0x8d10` | `0x8d68` | **`+0x58`** |
| `__DATA.__objc_data` | `0x4c08` | `0x4c58` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x8c8a` | `0x8cda` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0x2c63` | `0x2c93` | **`+0x30`** |
| `__DATA.__bss` | `0xec58` | `0xec78` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x13e8` | `0x13f4` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xd68` | `0xd70` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x740` | `0x748` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x6a8` | `0x6b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Functions: 10127
-  Symbols:   1058
-  CStrings:  11420
+  Functions: 10152
+  Symbols:   1059
+  CStrings:  11458
Symbols:
+ _OBJC_CLASS_$_CPLEngineDownloadSyncTask
CStrings:
+ "%@ is trying to deregister %{public}@ but it has been registered by %@ (%{public}@)"
+ "%@ is trying to deregister %{public}@ while it is not registered"
+ "%@ is trying to register %{public}@ while %@ has already registered it (%{public}@)"
+ "%{public}@ has not changed since last known fetch - using known record"
+ "@\"<CPLEngineTransportGroup>\"24@0:8@\"CPLScopeChange\"16"
+ "Account does not support device-to-device encryption required for %@ - disabling synchronization"
+ "Account now supports device-to-device encryption required for %@ - re-enabling synchronization"
+ "Collection Share Migration"
+ "Collection Share Migration Changes Upload"
+ "Collection Share Migration Direct Changes Upload"
+ "Container (%@) does not require device-to-device encryption anymore - re-enabling synchronization"
+ "Failed to register %@"
+ "Failed to submit %@: %@"
+ "Forced initial download for %@ completed"
+ "Forced initial download for %@ finished with error: %@"
+ "Forced initial download for %@ has been interrupted"
+ "Launching forced initial download for %@"
+ "Registering Subscription"
+ "T@\"<CPLCloudKitScopeProvider>\",R,W,N,V_scopeProvider"
+ "T@\"CKRecord\",C,N"
+ "Trying to deregister %@ while it has been registered by an other manager"
+ "Trying to deregister %@ while it is not registered"
+ "Trying to register %@ twice"
+ "_CPLRegisteredTaskIdentifierEvent"
+ "_backgroundSchedulerManagerForLibraryWithIdentifier:involvedProcesses:relatedApplications:queue:"
+ "_disabledSyncBecauseOfD2DEncryptionMissing"
+ "_registrationDate"
+ "backgroundSchedulerManagerForLibraryWithIdentifier:involvedProcesses:relatedApplications:queue:"
+ "barrierWithBlock:"
+ "ckGroupNameForChangeUpload"
+ "ckGroupNameForDirectUpload"
+ "ckScopeTypeName"
+ "createGroupForChangeUploadInScopeChange:"
+ "createGroupForDirectUploadInScopeChange:"
+ "createGroupForPublishingScopeChange:"
+ "createGroupForUpdatingScopeChange:"
+ "fetchRecordsWithIDs:fetchResources:desiredKeys:wantsAllRecords:recordIDsToKnownRecords:type:perFoundRecordBlock:completionHandler:"
+ "initWithTaskIdentifier:involvedProcesses:relatedApplications:groupName:queue:"
+ "initial download of %@"
+ "knownCKRecords"
+ "libraryState"
+ "migrationState"
+ "no device-to-device encryption"
+ "noteScopeNeedsToPullFromTransportWithSignificantEvent"
+ "otherKnownCKRecords"
+ "setAllowsForcedTaskQueuing:"
+ "setCkRecord:"
+ "setPerRecordETagMatchedBlock:"
+ "setRecordIDsToETags:"
+ "setScopeHasChangesToPullFromTransport:alsoUpdateScopeInfoIfNecessary:error:"
+ "setShouldForceInitialDownloadWhenJoining:"
+ "setTransportData:"
+ "shouldForceInitialDownloadWhenJoining"
+ "transportData"
+ "updateCollectionShareSettingsWithCKRecord:recordID:"
+ "updateLibraryShareSettingsWithCKRecord:recordID:"
+ "updateOtherKnownCKRecord:forRecordID:"
+ "updateOtherKnownCKRecords:"
+ "updateWithSCMigrationStatusCKRecord:recordID:"
+ "v16@?0@\"CKRecord\"8"
+ "v16@?0@\"CKRecordID\"8"
+ "v72@0:8@16B24@28B36@40q48@?56@?64"
+ "void _managerWillDeregisterTaskIdentifier(NSString *__strong, CPLBGSTBackgroundSchedulerManager *__strong, BOOL)_block_invoke"
+ "void _managerWillRegisterTaskIdentifier(NSString *__strong, CPLBGSTBackgroundSchedulerManager *__strong)_block_invoke"
- "Failed to register %{public}@, deregistering"
- "Failed to register background task"
- "Failed to register task request %{public}@"
- "Failed to submit task request %{public}@: %@"
- "Skipping persisted sync session — registration failed for %{public}@"
- "_backgroundSchedulerManagerForLibraryWithIdentifier:involvedProcesses:relatedApplications:"
- "_disableSchedulerBecauseAccountIsUnavailableWithReason:"
- "_enableSchedulerBecauseAccountIsAvailable"
- "_errorsByTaskForTasksByRecordId:fromUnderlyingError:"
- "_forceUpdateAccountInfoWithReason:"
- "_forceUpdateAccountInfoWithReason:completionHandler:"
- "_libraryStateFromRootRecord:"
- "_stopWatchingAccountInfoChanges"
- "_updateAccountInfoWithCompletionHandler:"
- "_updateStateWithAccountInfo:walrusEnabledDefault:"
- "_updateStateWithAccountStatus:"
- "_updateWalrusTo:"
- "backgroundSchedulerManagerForLibraryWithIdentifier:involvedProcesses:relatedApplications:"
- "com.apple.cpl.bgst.backgroundScheduler"
- "hasFinishedInitialDownloadForScope:"
- "initWithTaskIdentifier:involvedProcesses:relatedApplications:groupName:"
- "isKeychainCDPEnabled"
- "strongToStrongObjectsMapTable"
- "updateCollectionShareSettingsWithCKRecord:"
- "updateLibraryShareSettingsWithCKRecord:"
- "updateWithSCMigrationStatusCKRecord:"
```
