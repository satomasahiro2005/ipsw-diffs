## transparencyd

> `/usr/libexec/transparencyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x346b5c` | `0x3520e8` | **`+0xb58c`** |
| `__TEXT.__const` | `0x20488` | `0x24de8` | **`+0x4960`** |
| `__DATA_CONST.__const` | `0x1e0e8` | `0x1e880` | **`+0x798`** |
| `__TEXT.__oslogstring` | `0x13d6e` | `0x143ea` | **`+0x67c`** |
| `__TEXT.__cstring` | `0x12c1e` | `0x13142` | **`+0x524`** |
| `__TEXT.__eh_frame` | `0xbda8` | `0xc228` | **`+0x480`** |
| `__TEXT.__objc_methname` | `0x258c2` | `0x25d02` | **`+0x440`** |
| `__DATA_CONST.__cfstring` | `0xe5c0` | `0xe880` | **`+0x2c0`** |
| `__TEXT.__unwind_info` | `0xd538` | `0xd788` | **`+0x250`** |
| `__TEXT.__objc_stubs` | `0x1ddc0` | `0x1e000` | **`+0x240`** |
| `__DATA.__objc_const` | `0x332d0` | `0x334b8` | **`+0x1e8`** |
| `__DATA.__data` | `0xeee0` | `0xf0a0` | **`+0x1c0`** |
| `__TEXT.__auth_stubs` | `0x4ac0` | `0x4c70` | **`+0x1b0`** |
| `__TEXT.__swift5_typeref` | `0x4bfe` | `0x4d52` | **`+0x154`** |
| `__TEXT.__gcc_except_tab` | `0x4bb4` | `0x4cec` | **`+0x138`** |
| `__TEXT.__swift5_fieldmd` | `0x4390` | `0x44ac` | **`+0x11c`** |
| `__TEXT.__objc_methlist` | `0x15be8` | `0x15cf8` | **`+0x110`** |
| `__TEXT.__swift5_reflstr` | `0x2fbe` | `0x30ce` | **`+0x110`** |
| `__TEXT.__objc_methtype` | `0x8528` | `0x8608` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x5810` | `0x58ec` | **`+0xdc`** |
| `__DATA_CONST.__auth_got` | `0x2570` | `0x2648` | **`+0xd8`** |
| `__DATA.__objc_selrefs` | `0x8980` | `0x8a30` | **`+0xb0`** |
| `__DATA.__objc_data` | `0xa7e8` | `0xa888` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x1730` | `0x17a8` | **`+0x78`** |
| `__DATA_CONST.__auth_ptr` | `0x1390` | `0x1400` | **`+0x70`** |
| `__DATA.__bss` | `0x1c2f0` | `0x1c330` | **`+0x40`** |
| `__TEXT.__swift5_acfuncs` | `0x78` | `0xb4` | **`+0x3c`** |
| `__DATA.__common` | `0xab0` | `0xad8` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x314` | `0x338` | **`+0x24`** |
| `__TEXT.__swift5_capture` | `0x1bbc` | `0x1bdc` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x59c` | `0x5b8` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x2e0` | `0x2fc` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x9c8` | `0x9d0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x440` | `0x448` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1150` | `0x1154` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__thread_vars`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-1766.0.39.0.2
+1766.0.60.0.0

-  Functions: 20564
-  Symbols:   2322
-  CStrings:  11736
+  Functions: 20711
+  Symbols:   2370
+  CStrings:  11820
Symbols:
+ _$s10Foundation4UUIDV36_unconditionallyBridgeFromObjectiveCyACSo6NSUUIDCSgFZ
+ _$s12Transparency18CKVQueryCacheStatsV9itemCount4hits6misses16insertsOrUpdates21validityWindowSeconds13countersSinceACSi_S3iSd10Foundation4DateVtcfC
+ _$s12Transparency18CKVQueryCacheStatsVMa
+ _$s12Transparency18CKVQueryCacheStatsVMn
+ _$s12Transparency18CKVQueryCacheStatsVSEAAMc
+ _$s12Transparency18CKVQueryCacheStatsVSeAAMc
+ _$s12Transparency21CKVDiagnosticsServiceP15clearQueryCacheyyYaKFTq
+ _$s12Transparency21CKVDiagnosticsServiceP15clearQueryCacheyyYaKFTqTE
+ _$s12Transparency21CKVDiagnosticsServiceP15queryCacheStatsAA08CKVQueryeF0VyYaKFTq
+ _$s12Transparency21CKVDiagnosticsServiceP15queryCacheStatsAA08CKVQueryeF0VyYaKFTqTE
+ _$s12Transparency21CKVDiagnosticsServiceP27setQueryCacheValidityWindowyySdSgYaKFTq
+ _$s12Transparency21CKVDiagnosticsServiceP27setQueryCacheValidityWindowyySdSgYaKFTqTE
+ _$s12Transparency22CKVFailureHistoryEntryV3uri11application11failureTime6source5error9traceUUID13idsServerHint02ktnO014deviceFailures21successfulDeviceCount16uiStatusRawValue11mapRevision0Z11TimestampMs9fromCacheACSS_SS10Foundation4DateVAC6SourceOAA12KTErrorChainVSgSSSgA2ZSayAA16CKVDeviceFailureVGS2is5Int64VSgA4_SbtcfC
+ _$s15Synchronization5MutexVMa
+ _$s15Synchronization5MutexVMn
+ _$s15Synchronization5_CellVMn
+ _$s16CoreTransparency031AETEventsResponseLogConsistencyD8ProtocolP0E4TypeAC_SYTn
+ _$s16CoreTransparency031AETEventsResponseLogConsistencyD8ProtocolP7logType0eI0QzvgTq
+ _$s16CoreTransparency10CTEMapHeadV10populatingSbvg
+ _$s16CoreTransparency10CTEMapHeadVAA28SignedObjectProtobufParsableAAWP
+ _$s16CoreTransparency10CTEMapHeadVMa
+ _$s16CoreTransparency15CTEPublicKeyBagV10serverHint15treeRollInfoUrl7appKeys03tltM009vrfPublicD013patConfigNode0nrS018mapStillPopulating19shutDownTimestampMsACSSSg_SSAA011CTEscapablepD10CollectionVAoA020CTEscapableVRFPublicD0VSgAA011CTPATConfigS0VSgAA011CTTLTConfigS0VSgSbs6UInt64VtcfC
+ _$s16CoreTransparency15CTEPublicKeyBagV22fromPublicKeysResponse_011putativeAppH00j3TltH016requestedVersion08allowOldH011application10serverHintACx_AA011CTEscapablegD10CollectionVAlA012CTPBProtocolN0OSbAA15CTPBApplicationOSSSgtAA0gdE5ErrorOYKAA0ghI8ProtocolRz17PatInclusionProof_8LogEntry5BytesQZAV_AWRTzAU_AV12SignedObjectQZAV_AZRTzlFZ
+ _$s16CoreTransparency15CTLogClosedNodeV11timestampMss6UInt64Vvg
+ _$s16CoreTransparency15CTLogClosedNodeV8binarypbACx_tKcAA18CTBytesConvertibleRzlufC
+ _$s16CoreTransparency15CTLogClosedNodeVMa
+ _$s16CoreTransparency15CTPATConfigNodeV12vrfPublicKeyAA020CTEscapableVRFPublicG0Vvg
+ _$s16CoreTransparency15CTPATConfigNodeV8binarypbACx_tKcAA18CTBytesConvertibleRzlufC
+ _$s16CoreTransparency15CTPATConfigNodeVMa
+ _$s16CoreTransparency15CTPATConfigNodeVMn
+ _$s16CoreTransparency15CTTLTConfigNodeV8binarypbACx_tKcAA18CTBytesConvertibleRzlufC
+ _$s16CoreTransparency15CTTLTConfigNodeVMa
+ _$s16CoreTransparency15CTTLTConfigNodeVMn
+ _$s16CoreTransparency16LogEntryProtocolP9nodeBytes0G0QzvgTj
+ _$s16CoreTransparency16LogEntryProtocolTL
+ _$s16CoreTransparency23CTEscapableVRFPublicKeyV03vrfE0Says5UInt8VGvg
+ _$s16CoreTransparency23CTEscapableVRFPublicKeyVMa
+ _$s16CoreTransparency23CTEscapableVRFPublicKeyVMn
+ _$s16CoreTransparency25PatInclusionProofProtocolP23perApplicationTreeEntry03LogJ0QzvgTj
+ _$s16CoreTransparency25PatInclusionProofProtocolTL
+ _$s16CoreTransparency26PublicKeysResponseProtocolP14patConfigProof012PatInclusionI0QzvgTj
+ _$s16CoreTransparency26PublicKeysResponseProtocolP14tltConfigProof8LogEntryQzvgTj
+ _$s16CoreTransparency26PublicKeysResponseProtocolP23patClosedInclusionProof03PatiJ0QzSgvgTj
+ _$s16CoreTransparency26PublicKeysResponseProtocolP27populatingPamHeadInPatProof8LogEntryQzSgvgTj
+ _$s16CoreTransparency9CTPATNodeV15predecessorHeadAA23CTEscapableSignedObjectVvg
+ _$s16CoreTransparency9CTPATNodeV8binarypbACx_tKcAA18CTBytesConvertibleRzlufC
+ _$s16CoreTransparency9CTPATNodeVMa
+ _$s7LogType16CoreTransparency017AETEventsResponsea11ConsistencyF8ProtocolPTl
+ _$s9SwiftData12ModelContextC10fetchCountySiAA15FetchDescriptorVyxGKAA010PersistentC0RzlFTj
+ _$sSdSEsWP
+ _$sSdSesWP
+ _CNErrorDomain
+ _swift_release_x1
+ _swift_retain_x1
- _$s10Foundation20PredicateExpressionsO14build_NotEqual3lhs3rhsAC0eF0Vy_xq_Gx_q_tAA0B10ExpressionRzAaJR_SQ6OutputRpzAKQy_ALRSr0_lFZ
- _$s10Foundation20PredicateExpressionsO8NotEqualVMn
- _$s10Foundation20PredicateExpressionsO8NotEqualVy_xq_GAA08StandardB10ExpressionA2aGRzAaGR_rlMc
- _$s12Transparency22CKVFailureHistoryEntryV3uri11application11failureTime6source5error9traceUUID13idsServerHint02ktnO014deviceFailures21successfulDeviceCount16uiStatusRawValueACSS_SS10Foundation4DateVAC6SourceOAA12KTErrorChainVSgSSSgA2WSayAA16CKVDeviceFailureVGS2itcfC
- _$s16CoreTransparency15CTEPublicKeyBagV10serverHint15treeRollInfoUrl7appKeys03tltM0ACSSSg_SSAA017CTEscapablePublicD10CollectionVAJtcfC
- _$s16CoreTransparency9CTLogTypeO12topLevelTreeyA2CmFWC
CStrings:
+ "$__lazy_storage_$_queryCache"
+ "@\"NSString\"32@0:8@\"NSString\"16^@24"
+ "ALTER TABLE FailureHistory ADD COLUMN "
+ "B32@0:8@\"KTIDSDataURI\"16@\"<KTLogClientProtocol>\"24"
+ "CREATE TABLE IF NOT EXISTS FailureHistory (\n    uri TEXT NOT NULL,\n    application TEXT NOT NULL,\n    failureTime REAL NOT NULL,\n    errorTree BLOB,\n    deviceFailures BLOB,\n    successfulDeviceCount INTEGER NOT NULL CHECK (successfulDeviceCount >= 0),\n    uiStatus INTEGER NOT NULL,\n    source INTEGER NOT NULL CHECK (source IN (0, 1)),\n    traceUUID TEXT,\n    idsServerHint TEXT,\n    ktServerHint TEXT,\n    mapRevision INTEGER,\n    mapTimestampMs INTEGER,\n    fromCache INTEGER\n)"
+ "CacheVerifyCreateFailed"
+ "CloudKit account has no valid credentials"
+ "CloudKit account has no valid credentials, holding start up: %@"
+ "ConsistencyProof"
+ "INSERT INTO FailureHistory\n  (uri, application, failureTime, errorTree, deviceFailures,\n   successfulDeviceCount, uiStatus, source, traceUUID,\n   idsServerHint, ktServerHint, mapRevision, mapTimestampMs,\n   fromCache)\nVALUES (?, ?, ?, ?, ?, ?, ?, ?, ?, ?, ?, ?, ?, ?)"
+ "KT request pending past MMD with no underlying error"
+ "KTConfigBagNetwork"
+ "KTPublicKeyBagNetwork"
+ "KTQueryBatchURICount"
+ "KTQueryCachedConcurrent"
+ "KTQueryDiskCacheHit"
+ "KTQueryFreshConcurrent"
+ "KTQueryNetworkBatch"
+ "KTQueryNetworkPeer"
+ "KTQueryNetworkSelf"
+ "KTQueryNetworkSingle"
+ "KTQueryStaleLeafRefreshConcurrent"
+ "KTRPC"
+ "KTRPCConfigBag"
+ "PRAGMA table_info(FailureHistory)"
+ "PRAGMA user_version"
+ "PeerStateCalculator: %{mash.hash}@ resolved failure %{public}@ (%{public}@) superseded by successful verification against rotated account key"
+ "PublicKeys"
+ "Report"
+ "RevisionLog"
+ "SELECT uri, application, failureTime, errorTree, deviceFailures,\n       successfulDeviceCount, uiStatus, source, traceUUID,\n       idsServerHint, ktServerHint, mapRevision, mapTimestampMs,\n       fromCache\nFROM FailureHistory\nORDER BY application, uri, failureTime ASC, rowid ASC"
+ "Static key entry for %{mask.hash}@ missing publicKeyID"
+ "T@\"NSNumber\",N,R,VmapRevision"
+ "T@\"NSNumber\",N,R,VmapTimestampMs"
+ "T@\"NSString\",&,V_requestType"
+ "T@\"_TtC13transparencyd12KTQueryCache\",N,&"
+ "T@?,N,C"
+ "TB,N,R,VfromCache"
+ "UPDATE FailureHistory\nSET failureTime = ?, mapRevision = ?, mapTimestampMs = ?, fromCache = ?\nWHERE rowid = ?"
+ "ValidatePendingRequests: expired requestId %{public}@ vanished before its failure could be recorded"
+ "_requestType"
+ "accounts-support accepting new connection from: %{public}@[%d]"
+ "accounts-support rejecting client %{public}@[%d] due to lack of entitlement"
+ "cacheValidityWindow"
+ "canonicalContactIdentifier:"
+ "canonicalContactIdentifier: %@ -> %@"
+ "canonicalContactIdentifier: could not resolve %@ to a unified contact: %@ (using raw identifier)"
+ "canonicalIDSHandle:"
+ "consistencyVerified "
+ "count %lu->%lu"
+ "counters"
+ "deviceID/pushToken"
+ "failed to persist concurrent-path RPCSingleQuery for %{mask.hash}@: %@"
+ "failureSupersededByRotatedKeySuccess"
+ "fetchOrCreateVerification: cache miss; server loggable data changed: %{public}@"
+ "fromCache"
+ "garbageCollectOrphanedStaticKeys fetch failed: %@"
+ "garbageCollectOrphanedStaticKeys keeping %@: not a definitive not-found: %@"
+ "garbageCollectOrphanedStaticKeys removing orphaned pin for deleted contact %@"
+ "garbageCollectOrphanedStaticKeys save failed: %@"
+ "garbageCollectOrphanedStaticKeysOnce"
+ "ids-support accepting new connection from: %{public}@[%d]"
+ "ids-support rejecting client %{public}@[%d] due to lack of entitlement"
+ "inclusionVerified "
+ "initWithQueryCache:network:analytics:"
+ "inputsDiffReasonVersus:"
+ "insertCompletedSingleQueryForURI:application:request:response:requestTime:rpcId:"
+ "insertOrUpdateSLH: inserted new SLH %s"
+ "insertOrUpdateSLH: updated existing SLH %s; changed: %s"
+ "mapRevision"
+ "mapTimestampMs"
+ "peerVerificationIdForKTUri: need update because server loggable data changed: %{public}@"
+ "peerVerificationIdForUri: no cache match; newest candidate differs: %{public}@"
+ "q24@?0@\"KTLoggableData\"8@\"KTLoggableData\"16"
+ "queryCacheValidityWindow"
+ "recordFailureForURI:application:error:deviceFailures:successfulDeviceCount:uiStatus:source:traceUUID:idsServerHint:ktServerHint:mapRevision:mapTimestampMs:fromCache:"
+ "recorded concurrent-path RPCSingleQuery %@ for %{mask.hash}@"
+ "reorder-only (same device set; rdar://182543321)"
+ "requestType"
+ "serverRPCWriteBlock"
+ "setCacheValidityWindow:"
+ "setQueryCache:"
+ "setQueryCacheValidityWindow:"
+ "setRequestType:"
+ "setServerRPCWriteBlock:"
+ "signatureVerified "
+ "signedLogHead replaced"
+ "staticKeyOrphanGCVersion"
+ "suppliedLeafContradictsIDSData:"
+ "suppliedLeafContradictsIDSData: %lu IDS device(s) marked/absent in the supplied (cached) leaf for %{mask.hash}@ -> refresh before verdict"
+ "suppliedLeafContradictsIDSRegistration:logClient:"
+ "transparency accepting new connection from: %{public}@[%d]"
+ "transparency rejecting client %{public}@[%d] due to lack of entitlement"
+ "unifiedContactIdentifierForContactIdentifier:error:"
+ "v116@0:8@16@24@32@40q48Q56q64@72@80@88@96@104B112"
+ "v56@?0@\"NSString\"8@\"NSString\"16@\"NSData\"24@\"NSData\"32@\"NSDate\"40@\"NSUUID\"48"
+ "validatePeer: completed result %{public}@ resolved to UIStatus %{public}@ pre-write; recomputed to %{public}@ post-write for verificationId %{public}@ (rdar://181633621)"
+ "validateURI: %s supplied (cached) leaf contradicts current IDS registration -> refreshing before verdict"
+ "validityWindow"
+ "veriferResultForPeer static key: no account key for %{mask.hash}@"
- "CREATE TABLE IF NOT EXISTS FailureHistory (\n    uri TEXT NOT NULL,\n    application TEXT NOT NULL,\n    failureTime REAL NOT NULL,\n    errorTree BLOB,\n    deviceFailures BLOB,\n    successfulDeviceCount INTEGER NOT NULL CHECK (successfulDeviceCount >= 0),\n    uiStatus INTEGER NOT NULL,\n    source INTEGER NOT NULL CHECK (source IN (0, 1)),\n    traceUUID TEXT,\n    idsServerHint TEXT,\n    ktServerHint TEXT\n)"
- "Fetching public key bag from network [%s]"
- "INSERT INTO FailureHistory\n  (uri, application, failureTime, errorTree, deviceFailures,\n   successfulDeviceCount, uiStatus, source, traceUUID,\n   idsServerHint, ktServerHint)\nVALUES (?, ?, ?, ?, ?, ?, ?, ?, ?, ?, ?)"
- "SELECT uri, application, failureTime, errorTree, deviceFailures,\n       successfulDeviceCount, uiStatus, source, traceUUID,\n       idsServerHint, ktServerHint\nFROM FailureHistory\nORDER BY application, uri, failureTime ASC, rowid ASC"
- "UPDATE FailureHistory SET failureTime = ? WHERE rowid = ?"
- "accounts-support accepting new connection from %@"
- "accounts-support rejecting client %d/[%@] due to lack of entitlement"
- "ids-support accepting new connection from: %@[%d]"
- "ids-support rejecting client %d/[%@] due to lack of entitlement"
- "initWithQueryCache:network:"
- "modelContainer"
- "recordFailureForURI:application:error:deviceFailures:successfulDeviceCount:uiStatus:source:traceUUID:idsServerHint:ktServerHint:"
- "transparency accepting new connection from: %@[%d]"
- "transparency rejecting client %d/[%@] due to lack of entitlement"
- "v96@0:8@16@24@32@40q48Q56q64@72@80@88"
- "veriferResultForPeer static key: no public id for %{mask.hash}@"
```
