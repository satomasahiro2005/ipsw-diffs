## securityd

> `/usr/libexec/securityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26eb54` | `0x272da8` | **`+0x4254`** |
| `__DATA_CONST.__cfstring` | `0x1c780` | `0x1cf20` | **`+0x7a0`** |
| `__DATA.__bss` | `0xec0` | `0x15d0` | **`+0x710`** |
| `__TEXT.__cstring` | `0x22c4d` | `0x23052` | **`+0x405`** |
| `__TEXT.__objc_methname` | `0x2e916` | `0x2ec67` | **`+0x351`** |
| `__TEXT.__objc_stubs` | `0x1db60` | `0x1dda0` | **`+0x240`** |
| `__TEXT.__oslogstring` | `0x2ff6b` | `0x30181` | **`+0x216`** |
| `__TEXT.__auth_stubs` | `0x4340` | `0x43f0` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x14ab8` | `0x14b50` | **`+0x98`** |
| `__DATA.__objc_selrefs` | `0x9918` | `0x99a8` | **`+0x90`** |
| `__TEXT.__objc_methtype` | `0xb0f7` | `0xb176` | **`+0x7f`** |
| `__DATA.__data` | `0x31b8` | `0x3158` | **`-0x60`** |
| `__DATA_CONST.__auth_got` | `0x21b0` | `0x2208` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x6aa8` | `0x6b00` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0xa12c` | `0xa0fc` | **`-0x30`** |
| `__DATA.__objc_const` | `0x23d80` | `0x23da8` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x2577` | `0x2559` | **`-0x1e`** |
| `__DATA_CONST.__objc_intobj` | `0x1428` | `0x1440` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x15f30` | `0x15f48` | **`+0x18`** |
| `__TEXT.__const` | `0x910` | `0x920` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1558` | `0x1560` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x268` | `0x260` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1af4` | `0x1af8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__thread_vars`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-62460.40.74.0.0
+62460.40.78.0.0

-  Functions: 9934
-  Symbols:   1895
-  CStrings:  16459
+  Functions: 9945
+  Symbols:   1907
+  CStrings:  16559
Symbols:
+ _OBJC_CLASS_$_NSFileManager
+ _dirname_r
+ _fcntl
+ _pread
+ _rename
+ _sqlite3_close_v2
+ _statfs
+ _strcmp
+ _strlcpy
+ _strncmp
+ _strstr
+ _sysctl
CStrings:
+ "%02x"
+ "%s-wal"
+ "%s.%d.tmp"
+ "(%d) %s"
+ "-corruption-log.plist"
+ ":memory:"
+ "@\"OctagonStateTransitionWatcher\""
+ "@196@0:8@16@24@32@40@48@56@64@72@80@88@96@104@112@120@128@136#144#152@160B168B172B176@180@188"
+ "@64@0:8@16@24@32@40@48@?56"
+ "Attempting to update trusted device list, flowID: %@ (source: %s)"
+ "B16@?0^{__OpaqueSecDbConnection={__CFRuntimeBase=QAQ}^{__OpaqueSecDb}BBQBiB^{__CFError}{?=CCCCBBiiiiiCI[4[160c]][128c][256c][192c]}^{sqlite3}i^{__CFArray}}8"
+ "Received a %@ RPC for arguments (%@)"
+ "SELECT count(*) FROM cert"
+ "SELECT count(*) FROM genp"
+ "SELECT count(*) FROM inet"
+ "SELECT count(*) FROM keys"
+ "SecDBCheckCorrupted integrity_check returned %{public}s"
+ "SecDbCorruptionLog: close failed (%{darwin.errno}d)"
+ "SecDbCorruptionLog: log at %{public}@ was unusable, starting over"
+ "SecDbCorruptionLog: path too long: %{public}@"
+ "SecDbCorruptionLog: unable (%{darwin.errno}d) to create %s"
+ "SecDbCorruptionLog: unable (%{darwin.errno}d) to rename into place"
+ "SecDbCorruptionLog: unable (%{darwin.errno}d) to set protection class"
+ "SecDbCorruptionLog: unable to serialize log for %{public}@"
+ "SecDbCorruptionLog: write failed (%{darwin.errno}d)"
+ "SecDbHandleCorrupt: Tried to write corruption marker %{public}s but one already exists"
+ "SecDbSecDbProcessCorruptionMarker: found corruption marker %{public}s"
+ "T@\"OTMetricsSessionData\",&,V_currentFlowContext"
+ "T@\"OTMetricsSessionData\",R,V_flowContext"
+ "T@\"OTMetricsSessionData\",R,V_sessionMetrics"
+ "T@\"OctagonStateTransitionWatcher\",W,V_currentFlowWatcher"
+ "T@\"OctagonStateTransitionWatcher\",W,V_pathWatcher"
+ "_currentFlowContext"
+ "_currentFlowWatcher"
+ "_flowContext"
+ "_onqueueForgetFlowContextIfDone"
+ "_pathWatcher"
+ "absoluteString"
+ "afterAuthKitFetch:userInitiatedRemovals:evictedRemovals:unknownReasonRemovals:trustedDeviceHash:deletedDeviceHash:trustedDevicesUpdateTimestamp:accountIsDemo:version:idmsStableTrustedDevicesVersion:"
+ "bytesRead"
+ "checkEscrowCheck:sessionMetrics:reply:"
+ "checkOctagonHealth:repair:danglingPeerCleanup:caesarPeerCleanup:updateIdMS:forceStableTrustedDeviceIDReroll:sessionMetrics:reply:"
+ "componentsWithURL:resolvingAgainstBaseURL:"
+ "corruptionError"
+ "couldNotRun"
+ "currentFlowContext"
+ "currentFlowWatcher"
+ "dataWithContentsOfFile:options:error:"
+ "dbDeleted"
+ "dbMtime"
+ "dbSize"
+ "dbUnlinkFailed"
+ "defaultManager"
+ "detectedAt"
+ "disableWalrus:isDBRv2:pdpState:sessionMetrics:reply:"
+ "doSimpleStateMachineRPC:op:sourceStates:flowContext:reply:"
+ "doWatchedStateMachineRPC:sourceStates:path:flowContext:reply:"
+ "doWatchedStateMachineRPC:sourceStates:path:transitionOp:flowContext:reply:"
+ "enableWalrus:isDBRv2:pdpState:sessionMetrics:reply:"
+ "entries"
+ "episode"
+ "failingSQL"
+ "fetchStableTrustedDeviceIDWithSessionMetrics:reply:"
+ "fetchTrustedDeviceListWithStableTrustedDeviceIDStatus:sessionMetrics:reply:"
+ "file:"
+ "fileChangeCounter"
+ "fileExistsAtPath:"
+ "fileHeader"
+ "fileSystemRepresentation"
+ "fileURLWithPath:"
+ "filesAtDetection"
+ "flow"
+ "flowContext"
+ "hadPriorIOFailure"
+ "handlePairingRestart:sessionMetrics:"
+ "headerFirst32Hex"
+ "idms push"
+ "immutable=1"
+ "init:sourceStates:serialQueue:transitionOp:flowContext:"
+ "initForContainer:contextID:activeAccount:stateHolder:flagHandler:sosAdapter:octagonAdapter:accountsAdapter:authKitAdapter:personaAdapter:deviceInfoAdapter:secureBackupAdapter:laContextAdapter:ckksAccountSync:lockStateTracker:cuttlefishXPCWrapper:escrowRequestClass:notifierClass:sessionMetrics:permittedToSendMetrics:accountIsD:accountIsW:reachabilityTracker:escrowChecker:"
+ "initWithBytes:length:encoding:"
+ "integrityCheck"
+ "integrityCheckRowsTotal"
+ "integrityCheckStatus"
+ "isHomeAccessory"
+ "joinWithBottle:entropy:bottleSalt:sessionMetrics:reply:"
+ "joinWithCustodianRecoveryKey:sessionMetrics:reply:"
+ "joinWithInheritanceKey:sessionMetrics:reply:"
+ "joinWithRecoveryKey:sessionMetrics:reply:"
+ "lastObject"
+ "lastWriterSqliteVersion"
+ "localResetWithSessionMetrics:reply:"
+ "magicValid"
+ "markerAgeSeconds"
+ "markerOutcome"
+ "migrationFailure"
+ "noSuccessor"
+ "openErrmsg"
+ "openFailed"
+ "openResultCode"
+ "operationDependenciesWithSessionMetrics:"
+ "origin"
+ "pageSize"
+ "pathWatcher"
+ "performCKServerUnreadableDataRemoval:accountIsW:altDSID:sessionMetrics:reply:"
+ "postMortem"
+ "preexisted"
+ "prepareInformationWithSessionMetrics:"
+ "priorLogUnreadable"
+ "ranAndFailed"
+ "readErrno"
+ "remediation"
+ "removeObjectsInRange:"
+ "reportingFlowID"
+ "rerollWithSessionMetrics:reply:"
+ "resetOnly"
+ "rpcAccountWideSettingsWithForceFetch:sessionMetrics:reply:"
+ "rpcEstablish:sessionMetrics:reply:"
+ "rpcFetchAccountSettingsWithSessionMetrics:reply:"
+ "rpcFetchAllViableBottlesFromSource:sessionMetrics:reply:"
+ "rpcFetchUserControllableViewsSyncingStatusWithSessionMetrics:reply:"
+ "rpcJoin:vouchSig:sessionMetrics:reply:"
+ "rpcPrepareIdentityAsApplicantWithConfiguration:epoch:sessionMetrics:reply:"
+ "rpcRefetchCKKSPolicyWithSessionMetrics:reply:"
+ "rpcReset:isDBRv2:sessionMetrics:reply:"
+ "rpcResetAndEstablish:idmsTargetContext:idmsCuttlefishPassword:notifyIdMS:accountSettings:isDBRv2:accountIsW:sessionMetrics:reply:"
+ "rpcSetAccountSetting:sessionMetrics:reply:"
+ "rpcSetUserControllableViewsSyncingStatus:sessionMetrics:reply:"
+ "rpcVoucherWithConfiguration:permanentInfo:permanentInfoSig:stableInfo:stableInfoSig:sessionMetrics:reply:"
+ "schemaVersionNew"
+ "schemaVersionOld"
+ "setCurrentFlowContext:"
+ "setCurrentFlowWatcher:"
+ "setPathWatcher:"
+ "setQuery:"
+ "sizeInPages"
+ "sqlite3: (%d) %{public}s"
+ "sqliteCorrupt"
+ "sqliteErrmsg"
+ "sqliteExtendedCode"
+ "sqliteLog"
+ "sqliteNotADb"
+ "sqliteSystemErrno"
+ "staleWalLeftBehind"
+ "stringWithCapacity:"
+ "tableRowCounts"
+ "totalEpisodes"
+ "uptimeAtDetection"
+ "v36@0:8B16@\"OTMetricsSessionData\"20@?<v@?@\"OTEscrowCheckCallResult\"@\"NSError\">28"
+ "v40@0:8q16@24@?32"
+ "v44@0:8q16B24@28@?36"
+ "v48@0:8@16B24i28@32@?40"
+ "v48@0:8@16Q24@32@?40"
+ "v48@0:8B16B20@24@32@?40"
+ "v56@0:8B16B20B24B28B32B36@40@?48"
+ "v72@0:8@16@24@32@40@48@56@?64"
+ "v76@0:8q16@24@32B40@44B52B56@60@?68"
+ "v92@0:8@16@24@32@40@48@56@64B72@76@84"
+ "versionValidFor"
+ "volumeFreeBytes"
+ "volumeReadOnly"
+ "waitForOctagonUpgradeWithSessionMetrics:reply:"
+ "walBytesNotCounted"
+ "walSize"
+ "writeFailed"
+ "written"
+ "\xb1\x91"
+ "\xf1Q"
- "@\"<TDLNotificationFlowIDConsumer>\""
- "@212@0:8@16@24@32@40@48@56@64@72@80@88@96@104@112@120@128@136#144#152@160@168B176B180B184@188@196@204"
- "@?24@0:8@?16"
- "Attempting to update trusted device list"
- "B16@?0^{__OpaqueSecDbConnection={__CFRuntimeBase=QAQ}^{__OpaqueSecDb}BBQBiB^{__CFError}^{sqlite3}i^{__CFArray}}8"
- "SecDBCheckCorrupted integrity_check returned %s"
- "SecDbHandleCorrupt: Tried to write corruption marker %s but one already exists"
- "SecDbSecDbProcessCorruptionMarker: found corruption marker %s"
- "T@\"<TDLNotificationFlowIDConsumer>\",R,W,V_tdlNotificationFlowIDConsumer"
- "T@\"NSString\",&,V_deviceSessionID"
- "T@\"NSString\",&,V_flowID"
- "T@\"OTMetricsSessionData\",&,V_watchedFlowSessionMetrics"
- "TDLNotificationFlowIDConsumer"
- "Updating trusted device list, flowID source: %s"
- "_deviceSessionID"
- "_flowID"
- "_tdlNotificationFlowIDConsumer"
- "_watchedFlowSessionMetrics"
- "afterAuthKitFetch:userInitiatedRemovals:evictedRemovals:unknownReasonRemovals:trustedDeviceHash:deletedDeviceHash:trustedDevicesUpdateTimestamp:accountIsDemo:version:idmsStableTrustedDevicesVersion:flowID:"
- "checkEscrowCheck:reply:"
- "checkOctagonHealth:repair:danglingPeerCleanup:caesarPeerCleanup:updateIdMS:forceStableTrustedDeviceIDReroll:reply:"
- "claimWatchedFlowSessionMetrics"
- "disableWalrus:isDBRv2:pdpState:reply:"
- "doSimpleStateMachineRPC:op:sourceStates:reply:"
- "doWatchedStateMachineRPC:sourceStates:path:reply:"
- "doWatchedStateMachineRPC:sourceStates:path:transitionOp:reply:"
- "enableWalrus:isDBRv2:pdpState:reply:"
- "fetchStableTrustedDeviceIDWithReply:"
- "fetchTrustedDeviceListWithStableTrustedDeviceIDStatus:reply:"
- "handlePairingRestart:"
- "idms"
- "init:sourceStates:serialQueue:transitionOp:"
- "initForContainer:contextID:activeAccount:stateHolder:flagHandler:sosAdapter:octagonAdapter:accountsAdapter:authKitAdapter:personaAdapter:deviceInfoAdapter:secureBackupAdapter:laContextAdapter:ckksAccountSync:lockStateTracker:cuttlefishXPCWrapper:escrowRequestClass:notifierClass:flowID:deviceSessionID:permittedToSendMetrics:accountIsD:accountIsW:reachabilityTracker:escrowChecker:tdlNotificationFlowIDConsumer:"
- "joinWithBottle:entropy:bottleSalt:reply:"
- "joinWithCustodianRecoveryKey:reply:"
- "joinWithInheritanceKey:reply:"
- "joinWithRecoveryKey:reply:"
- "localReset:"
- "not idms"
- "performCKServerUnreadableDataRemoval:accountIsW:altDSID:reply:"
- "releaseWatchedFlowSessionMetrics:"
- "rerollWithReply:"
- "rpcAccountWideSettingsWithForceFetch:reply:"
- "rpcEstablish:reply:"
- "rpcFetchAccountSettings:"
- "rpcFetchAllViableBottlesFromSource:reply:"
- "rpcFetchUserControllableViewsSyncingStatus:"
- "rpcJoin:vouchSig:reply:"
- "rpcPrepareIdentityAsApplicantWithConfiguration:epoch:reply:"
- "rpcRefetchCKKSPolicy:"
- "rpcReset:isDBRv2:reply:"
- "rpcResetAndEstablish:idmsTargetContext:idmsCuttlefishPassword:notifyIdMS:accountSettings:isDBRv2:accountIsW:reply:"
- "rpcSetAccountSetting:reply:"
- "rpcSetUserControllableViewsSyncingStatus:reply:"
- "rpcVoucherWithConfiguration:permanentInfo:permanentInfoSig:stableInfo:stableInfoSig:reply:"
- "setWatchedFlowSessionMetrics:"
- "tdlNotificationFlowIDConsumer"
- "v100@0:8@16@24@32@40@48@56@64B72@76@84@92"
- "v28@0:8B16@?<v@?@\"OTEscrowCheckCallResult\"@\"NSError\">20"
- "v40@0:8@16B24i28@?32"
- "v40@0:8B16B20@24@?32"
- "v48@0:8B16B20B24B28B32B36@?40"
- "v68@0:8q16@24@32B40@44B52B56@?60"
- "waitForOctagonUpgrade:"
- "watchedFlowSessionMetrics"
- "wrapReplyReleasingWatchedFlowSessionMetrics:"
- "\xa1"
- "\xf1b"
```
