## cloudphotod

> `/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/Support/cloudphotod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cd904` | `0x1ce784` | **`+0xe80`** |
| `__DATA.__objc_const` | `0x1eee8` | `0x1f1b0` | **`+0x2c8`** |
| `__TEXT.__objc_methname` | `0x2ae71` | `0x2b091` | **`+0x220`** |
| `__TEXT.__oslogstring` | `0x1290b` | `0x12abe` | **`+0x1b3`** |
| `__TEXT.__cstring` | `0x1c1bc` | `0x1c2b3` | **`+0xf7`** |
| `__TEXT.__objc_methlist` | `0x109cc` | `0x10a84` | **`+0xb8`** |
| `__TEXT.__objc_stubs` | `0x1cc20` | `0x1cca0` | **`+0x80`** |
| `__DATA.__objc_data` | `0x4c58` | `0x4ca8` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x8d26` | `0x8d66` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x6e18` | `0x6e58` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x13f8` | `0x1428` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x8dc8` | `0x8df8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xb098` | `0xb0c0` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x2e28` | `0x2e0c` | **`-0x1c`** |
| `__TEXT.__auth_stubs` | `0x1e10` | `0x1e20` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x2c93` | `0x2ca3` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xf18` | `0xf20` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xe70` | `0xe78` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x1c0` | `0x1c8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x748` | `0x750` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x6b0` | `0x6b8` | **`+0x8`** |
| `__TEXT.__const` | `0xa060` | `0xa068` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
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

-912.0.235.0.0
+916.40.110.0.0

-  Functions: 10189
-  Symbols:   1060
-  CStrings:  11496
+  Functions: 10220
+  Symbols:   1062
+  CStrings:  11532
Symbols:
+ _OBJC_CLASS_$_CKServerTimestamp
+ _dispatch_queue_get_label
CStrings:
+ "%s.watchdog"
+ "%{public}s did not respond in time: %@"
+ "%{public}s is alive"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Photos/workspaces/cloudphotolibrary/Daemon/CPLQueueWatchdog.m"
+ "@\"NSObject<OS_os_log>\""
+ "@48@0:8@16d24d32@?40"
+ "CPLQueueWatchdog"
+ "Checking %{public}s"
+ "Container has been wiped - informing engine"
+ "Daemon queue is not responding"
+ "Daemon queue is not responding (%lu)"
+ "Daemon queue is not responding (%lu) - aborting process"
+ "Decoded key asset from CKShare %@ (etag %@) for %@: keyAssetIdentifier %@, thumbnailImageData length %lu"
+ "Error deserializing base shared CKRecord for %@: %@"
+ "Failed to read back %@ after updating it, reporting the saved share instead: %@"
+ "Found zone %@ deleted by encrypted data reset"
+ "Ignoring %@ deleted by encrypted data reset"
+ "Share at %@ needs to request access to get any meaningful info"
+ "Share needs to request access"
+ "Starting watchdog for %{public}s"
+ "Stopping watchdog for %{public}s"
+ "T@\"CPLQueueWatchdog\",&,N"
+ "T@?,R,N,V_timeoutBlock"
+ "Td,R,N,V_timeoutInterval"
+ "Td,R,N,V_watchInterval"
+ "Zone was wiped by an encrypted data reset - %@ will re-create it"
+ "_changesFromRecordID"
+ "_failAllFutureOperationsWithContainerHasBeenWipedDueToEncryptedDataResetError"
+ "_fetchRecordsFollowRemappingWithIDs:alreadyFetchRecordIDs:remappedRecordIDs:realRecords:desiredKeys:type:storeRequestUUIDsIn:completionHandler:"
+ "_log"
+ "_noteContainerHasBeenWipedDueToEncryptedDataReset"
+ "_queueWatchdogStartCount"
+ "_startCount"
+ "_timeoutBlock"
+ "_timeoutCount"
+ "_timeoutGeneration"
+ "_timeoutInterval"
+ "_timeoutTimer"
+ "_watchInterval"
+ "_watchQueue"
+ "_watchTimer"
+ "accessRequestsEnabled"
+ "com.apple.queue.watchdog"
+ "containerHasBeenWipedDueToEncryptedDataReset"
+ "createsMissingZone"
+ "fetchRecordsFollowRemappingWithIDs:desiredKeys:wantsAllRecords:type:completionHandler:"
+ "initWithQueue:watchInterval:timeoutInterval:timeoutBlock:"
+ "isContainerHasBeenWipedDueToEncryptedDataResetError:"
+ "processWatchdog"
+ "scopeTypeForShareURL:"
+ "setContainerHasBeenWipedDueToEncryptedDataReset:"
+ "setProcessWatchdog:"
+ "setRecordZoneWithIDWasDeletedDueToUserEncryptedDataResetBlock:"
+ "shareNeedsToRequestAccess:"
+ "timeoutBlock"
+ "timeoutInterval"
+ "v24@?0@\"CPLQueueWatchdog\"8Q16"
+ "v52@0:8@16@24B32q36@?44"
+ "v80@0:8@16@24@32@40@48q56@64@?72"
+ "watchInterval"
- "Container have been wiped - informing engine"
- "Failed to prepare CK record: %@"
- "Failed to prepare CK record: record change data returned nil"
- "Updated contributors on %lu records"
- "Won't update contributors for %@ as the record is not in the cloud"
- "Won't update contributors for %@ as the record is not shared"
- "_computeUpdatedSharedCKRecordsFromFoundRecord:usingUpdates:error:"
- "_deactivateMarkerURL"
- "_failAllFutureOperationsWithContainerHasBeenWipedError"
- "_fetchRecordsFollowRemappingWithIDs:alreadyFetchRecordIDs:remappedRecordIDs:realRecords:type:storeRequestUUIDsIn:completionHandler:"
- "_noteContainerHasBeenWiped"
- "_scopedIdentifiersFromCKRecordID"
- "_startWatchingURL:forPauseReason:"
- "_stopWatchingSystemState"
- "addKnownTarget:forRecordWithScopedIdentifier:"
- "containerHasBeenWiped"
- "isContainerHasBeenWipedError:"
- "pathComponents"
- "photos"
- "photos_sharing"
- "setContainerHasBeenWiped:"
- "update contributors"
- "v72@0:8@16@24@32@40q48@56@?64"
- "\xc1"
```
