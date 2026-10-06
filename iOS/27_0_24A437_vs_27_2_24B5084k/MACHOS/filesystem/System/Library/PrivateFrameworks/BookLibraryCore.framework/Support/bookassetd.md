## bookassetd

> `/System/Library/PrivateFrameworks/BookLibraryCore.framework/Support/bookassetd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe11c4` | `0xe27c4` | **`+0x1600`** |
| `__TEXT.__objc_methname` | `0x118ce` | `0x11bd7` | **`+0x309`** |
| `__DATA_CONST.__cfstring` | `0x3820` | `0x3ac0` | **`+0x2a0`** |
| `__TEXT.__cstring` | `0x3850` | `0x3ae1` | **`+0x291`** |
| `__DATA.__objc_const` | `0xb2a0` | `0xb4d8` | **`+0x238`** |
| `__TEXT.__objc_stubs` | `0xd340` | `0xd560` | **`+0x220`** |
| `__TEXT.__gcc_except_tab` | `0x1854` | `0x1a18` | **`+0x1c4`** |
| `__TEXT.__objc_methlist` | `0x6350` | `0x6480` | **`+0x130`** |
| `__TEXT.__oslogstring` | `0xc53a` | `0xc63b` | **`+0x101`** |
| `__DATA.__objc_selrefs` | `0x40d8` | `0x4170` | **`+0x98`** |
| `__DATA_CONST.__const` | `0x7e10` | `0x7ea0` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x19d8` | `0x1a30` | **`+0x58`** |
| `__DATA.__objc_data` | `0x1f90` | `0x1fe0` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x778` | `0x798` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0xd5d` | `0xd7b` | **`+0x1e`** |
| `__TEXT.__objc_methtype` | `0x3198` | `0x31a9` | **`+0x11`** |
| `__DATA_CONST.__objc_classlist` | `0x328` | `0x330` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-2310.0.0.0.0
+2353.0.0.0.0

-  Functions: 2407
+  Functions: 2440

-  CStrings:  4571
+  CStrings:  4626
CStrings:
+ "(dID=%{public}@) [Database]: No sinf.xml written; no epubRightsData supplied."
+ "(dID=%{public}@) [Purchase-Mgr]: No sinf.xml written; no epubRightsData supplied."
+ "AMS purchase finished, posting result"
+ "AMS purchase started, no result yet"
+ "BLPurchaseManager.ongoingPurchaseRequests"
+ "No FairPlay rights data (sinf) was supplied for the download; nothing to write."
+ "T@\"BUOSStateHandler\",&,N,V_ongoingPurchaseStateHandler"
+ "T@\"NSDate\",&,N,V_startDate"
+ "T@\"NSMutableDictionary\",R,N,V_ongoingPurchaseRequestsByStoreID"
+ "T@\"NSNumber\",&,N,V_stageAttributionStoreID"
+ "T@\"NSString\",C,N,V_lastStageLogKey"
+ "T@?,C,N,V_stageReporter"
+ "Tq,N,V_lastStage"
+ "[Purchase-Mgr]: Skipping because there is ongoing purchase request for storeIdentifier=%{mask.hash}@ (age %{public}.0fs, last stage: %{public}@, logKey %{public}@, downloadID %{public}@), buyParameters=%@"
+ "_BLOngoingPurchaseRequestInfo"
+ "_lastStage"
+ "_lastStageLogKey"
+ "_ongoingPurchaseStateHandler"
+ "_reportStage:logKey:"
+ "_stageAttributionStoreID"
+ "_stageReporter"
+ "_startDate"
+ "accepted, not yet enqueued to AMS"
+ "ageSeconds"
+ "auth answered, back inside AMS"
+ "auth forwarded, awaiting reply"
+ "checkAndAddStoreIDForRequest:existingSnapshot:"
+ "dialog answered, back inside AMS"
+ "dialog forwarded, awaiting reply"
+ "dq_noteStage:logKey:forStoreID:"
+ "engagement answered, back inside AMS"
+ "engagement forwarded, awaiting reply"
+ "inFlightPurchases"
+ "lastStage"
+ "lastStageLogKey"
+ "none"
+ "none recorded yet"
+ "noteAMSPurchaseFinishedForRequest:"
+ "noteAMSPurchaseStartedForRequest:downloadID:"
+ "noteStage:forRequest:"
+ "noteStageForAttributedRequest:logKey:"
+ "ongoingPurchaseStateHandler"
+ "payment sheet answered, back inside AMS"
+ "payment sheet forwarded, awaiting reply"
+ "post-AMS, triggering downloads"
+ "setLastStage:"
+ "setLastStageLogKey:"
+ "setOngoingPurchaseStateHandler:"
+ "setStageAttributionStoreID:"
+ "setStageReporter:"
+ "setStartDate:"
+ "stageAttributionStoreID"
+ "stageReporter"
+ "startDate"
+ "stateSnapshotForLog"
+ "unrecognised stage %ld"
+ "v24@?0q8@\"NSString\"16"
+ "v40@0:8q16@24@32"
+ "writeToURL:options:error:"
- "T@\"NSMutableSet\",R,N,V_ongoingPurchaseRequestsByStoreID"
- "[Purchase-Mgr]: Skipping because there is ongoing purchase request for storeIdentifier=%@, buyParameters=%@"
- "checkAndAddStoreIDForRequest:"
- "writeToURL:atomically:"
```
