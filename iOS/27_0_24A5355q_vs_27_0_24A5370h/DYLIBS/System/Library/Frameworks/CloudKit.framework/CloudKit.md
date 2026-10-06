## CloudKit

> `/System/Library/Frameworks/CloudKit.framework/CloudKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3667d8` | `0x365c84` | **`-0xb54`** |
| `__TEXT.__unwind_info` | `0x11428` | `0x10fb0` | **`-0x478`** |
| `__TEXT.__oslogstring` | `0x16c4b` | `0x16f36` | **`+0x2eb`** |
| `__TEXT.__const` | `0xe2f0` | `0xe1f0` | **`-0x100`** |
| `__DATA.__bss` | `0xe6c8` | `0xe648` | **`-0x80`** |
| `__AUTH_CONST.__cfstring` | `0x1dd00` | `0x1dd60` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x39a20` | `0x39a80` | **`+0x60`** |
| `__TEXT.__swift5_mpenum` | `0xac` | `0x60` | **`-0x4c`** |
| `__TEXT.__cstring` | `0x20784` | `0x207c5` | **`+0x41`** |
| `__TEXT.__eh_frame` | `0x10154` | `0x10114` | **`-0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x255c` | `0x251c` | **`-0x40`** |
| `__AUTH_CONST.__const` | `0x12d50` | `0x12d18` | **`-0x38`** |
| `__TEXT.__objc_methlist` | `0x2181c` | `0x21854` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x4088` | `0x40bc` | **`+0x34`** |
| `__TEXT.__swift5_typeref` | `0x6c58` | `0x6c32` | **`-0x26`** |
| `__TEXT.__swift_as_cont` | `0xeac` | `0xed0` | **`+0x24`** |
| `__TEXT.__swift5_reflstr` | `0x1d5f` | `0x1d7f` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x2920` | `0x2904` | **`-0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x2558` | `0x2540` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x1cc` | `0x1b8` | **`-0x14`** |
| `__TEXT.__swift_as_entry` | `0x6a4` | `0x690` | **`-0x14`** |
| `__DATA_CONST.__got` | `0x1998` | `0x1988` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x7c0` | `0x7b0` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x6f00` | `0x6f08` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xbf50` | `0xbf58` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x848` | `0x840` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1970` | `0x1974` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x354` | `0x350` | **`-0x4`** |

### Other Changes

```diff

-2710.108.20.0.0
+2710.112.0.0.0

-  Functions: 24337
-  Symbols:   6535
-  CStrings:  6187
+  Functions: 24304
+  Symbols:   6516
+  CStrings:  6190
Symbols:
+ _$s8CloudKit12CKSyncEngineC18SendChangesContextV12invocationIDSSvg
+ _$s8CloudKit12CKSyncEngineC18SendChangesContextV12invocationIDSSvpMV
+ _$s8CloudKit12CKSyncEngineC19FetchChangesContextV12invocationIDSSvg
+ _$s8CloudKit12CKSyncEngineC19FetchChangesContextV12invocationIDSSvpMV
+ _CKTestDeviceOptionConcurrentZoneReadingDisabled
+ _kCKTCCManagerEntitlementKey
- _$s8CloudKit12CKSyncEngineC10fetchAssetySo7CKAssetCAC05FetchF7OptionsVYaKF
- _$s8CloudKit12CKSyncEngineC10fetchAssetySo7CKAssetCAC05FetchF7OptionsVYaKFTu
- _$s8CloudKit12CKSyncEngineC16PendingAssetSyncO05fetchF0yAESo7CKAssetCcAEmFWC
- _$s8CloudKit12CKSyncEngineC17FetchAssetOptionsV11descriptionSSvg
- _$s8CloudKit12CKSyncEngineC17FetchAssetOptionsV11descriptionSSvpMV
- _$s8CloudKit12CKSyncEngineC17FetchAssetOptionsV5asset14operationGroupAESo7CKAssetC_So011CKOperationJ0CSgtcfC
- _$s8CloudKit12CKSyncEngineC17FetchAssetOptionsV5assetSo7CKAssetCvg
- _$s8CloudKit12CKSyncEngineC17FetchAssetOptionsV5assetSo7CKAssetCvpMV
- _$s8CloudKit12CKSyncEngineC17FetchAssetOptionsV8progressSo10NSProgressCvg
- _$s8CloudKit12CKSyncEngineC17FetchAssetOptionsV8progressSo10NSProgressCvpMV
- _$s8CloudKit12CKSyncEngineC17FetchAssetOptionsVAC17ProgressReportingAAMc
- _$s8CloudKit12CKSyncEngineC17FetchAssetOptionsVAC17ProgressReportingAAWP
- _$s8CloudKit12CKSyncEngineC17FetchAssetOptionsVMa
- _$s8CloudKit12CKSyncEngineC17FetchAssetOptionsVMn
- _$s8CloudKit12CKSyncEngineC17FetchAssetOptionsVN
- _$s8CloudKit12CKSyncEngineC17FetchAssetOptionsVs23CustomStringConvertibleAAMc
- _$s8CloudKit12CKSyncEngineC5EventO13DidFetchAssetV5assetSo7CKAssetCvg
- _$s8CloudKit12CKSyncEngineC5EventO13DidFetchAssetV5assetSo7CKAssetCvpMV
- _$s8CloudKit12CKSyncEngineC5EventO14WillFetchAssetV5assetSo7CKAssetCvg
- _$s8CloudKit12CKSyncEngineC5EventO14WillFetchAssetV5assetSo7CKAssetCvpMV
- _$sScisE5first5where7ElementQzSgSbADYaKXE_tYaKF
- _$sScisE5first5where7ElementQzSgSbADYaKXE_tYaKFTu
- _$sSo10NSProgressC10FoundationE11subprogress14assigningCountAC11SubprogressVSi_tF
- _OBJC_CLASS_$_NSProgress
- _swift_release_x10
CStrings:
+ "%@ BUG IN CLOUDKIT: Error serializing sync engine metadata: %@"
+ "%@ calling notifyChangeHandlerWithCoalescing: %d scheduleSync: %d"
+ "%p"
+ "%s Exclusive access waiter %s cancelled after being granted access; releasing"
+ "%s Waiter %s cancelled after being granted resources %s; releasing"
+ "%s [invocationID:%s] BUG IN CLOUDKIT: CKSyncEngine finished fetching changes for a zone that it never started: %@"
+ "%s [invocationID:%s] error fetching changes for context %s: %@"
+ "%s [invocationID:%s] error fetching changes for zone %@: %@"
+ "%s [invocationID:%s] error fetching record zone changes: %@"
+ "%s [invocationID:%s] failed sending changes for context %s: %@"
+ "%s [invocationID:%s] failed to fetch database changes for context %s: %@"
+ "%s [invocationID:%s] fetched %ld database changes without a push notification for context %s"
+ "%s [invocationID:%s] fetching changes for context %s"
+ "%s [invocationID:%s] fetching changes for scope %s"
+ "%s [invocationID:%s] fetching database changes at least once"
+ "%s [invocationID:%s] finished fetch record zone changes request"
+ "%s [invocationID:%s] finished fetching changes for context %s"
+ "%s [invocationID:%s] finished fetching database changes"
+ "%s [invocationID:%s] finished sending changes for context %s"
+ "%s [invocationID:%s] next database send changes options for context %s: %s"
+ "%s [invocationID:%s] next fetch changes options for context %s: %s"
+ "%s [invocationID:%s] next recordZone send changes options for context %s: %s"
+ "%s [invocationID:%s] no batch received from nextRecordZoneChangeBatch"
+ "%s [invocationID:%s] no more pending database changes"
+ "%s [invocationID:%s] no need to fetch changes for scope %s"
+ "%s [invocationID:%s] no record zone change batch to send for context: %s"
+ "%s [invocationID:%s] no record zone changes to fetch for context %s"
+ "%s [invocationID:%s] not clearing needsToFetchChanges for %@ due to retryable record-level error"
+ "%s [invocationID:%s] not getting next record zone change batch for deallocated engine"
+ "%s [invocationID:%s] not requesting nextFetchChangesOptions for deallocated engine"
+ "%s [invocationID:%s] not requesting nextSendChangesOptions for deallocated engine"
+ "%s [invocationID:%s] received record zone change batch: %s"
+ "%s [invocationID:%s] sending changes for context %s"
+ "%s [invocationID:%s] will fetch next database changes for context %s: %s"
+ "%s [invocationID:%s] will fetch next record zone changes for context %s"
+ "%s [invocationID:%s] will send database changes %s"
+ "%s [invocationID:%s] will send next change batch for context: %s"
+ "%s re-submitting activity %s and overwriting earliestStartDate (%s) to new date (%s)"
+ "%s received database notification (zone=%@)"
+ "%s scheduling another sync after this scheduled sync due to pending work"
+ "%s will fetch database and zone changes because our last fetch was too long ago: (%s)"
+ "<AccountChange switchAccounts previousUser="
+ "<FetchChangesContext invocationID="
+ "<SendChangesContext invocationID="
+ "Cleared all enabled and opportunistic topics from connection %@"
+ "ConcurrentZoneReadingDisabled"
+ "DisableConcurrentZoneReads"
+ "Failed to prepare fetch for asset '%s' with error: %@"
+ "Handler called without both result and error."
+ "SQLiteDatabase(%p) statement executing: %s"
+ "SQLiteDatabase(%p): Database busy at %{public}@"
+ "com.apple.private.cloudkit.tccmanager"
+ "concurrentZoneReadingDisabled"
+ "itemCount=%llu"
- " %p"
- " switchAccounts previousUser="
- "%s error fetching changes for context %s: %@"
- "%s error fetching changes for zone %@: %@"
- "%s error fetching record zone changes: %@"
- "%s failed sending changes for context %s: %@"
- "%s failed to fetch database changes for context %s: %@"
- "%s fetched %ld database changes without a push notification for context %s"
- "%s fetching changes for context %s"
- "%s fetching changes for scope %s"
- "%s fetching database changes at least once"
- "%s finished fetch record zone changes request"
- "%s finished fetching changes for context %s"
- "%s finished fetching database changes"
- "%s finished sending changes for context %s"
- "%s next database send changes options for context %s: %s"
- "%s next fetch changes options for context %s: %s"
- "%s next recordZone send changes options for context %s: %s"
- "%s no batch received from nextRecordZoneChangeBatch"
- "%s no more pending database changes"
- "%s no need to fetch changes for scope %s"
- "%s no record zone change batch to send for context: %s"
- "%s no record zone changes to fetch for context %s"
- "%s not clearing needsToFetchChanges for %@ due to retryable record-level error"
- "%s not getting next record zone change batch for deallocated engine"
- "%s not requesting nextFetchChangesOptions for deallocated engine"
- "%s not requesting nextSendChangesOptions for deallocated engine"
- "%s re-submitting activity %s and overwriting earliestStartDate (%s to new date (%s)"
- "%s received database notification (zone=%@"
- "%s received record zone change batch: %s"
- "%s scheduling another sync after this scheduled sync due to hasPendingUntrackedChanges"
- "%s sending changes for context %s"
- "%s will fetch database and zone changes because our last fetch was too long ago: (%s"
- "%s will fetch next database changes for context %s: %s"
- "%s will fetch next record zone changes for context %s"
- "%s will send database changes %s"
- "%s will send next change batch for context: %s"
- "<FetchAssetOptions asset="
- "<FetchChangesContext reason="
- "<SendChangesContext reason="
- "BUG IN CLOUDKIT: CKSyncEngine finished fetching changes for a zone that it never started: %@"
- "BUG IN CLOUDKIT: Error serializing sync engine metadata: %@"
- "Calling notifyChangeHandlerWithCoalescing: %d scheduleSync: %d"
- "Cleared all enabled topics from connection %@"
- "Failed to prepare fetch for asset '%s` with error: %@"
- "Handler called wihout both result and error."
- "Missing result for asset: "
- "SQLitDatabase(%p) statement executing: %s"
- "SQLitDatabase(%p): Database busy at %{public}@"
- "engine/fetch-asset"
- "itemCount=%llu, size=%llu"
```
