## transparencyd

> `/usr/libexec/transparencyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31da68` | `0x338ee0` | **`+0x1b478`** |
| `__TEXT.__eh_frame` | `0xa4f8` | `0xb5a0` | **`+0x10a8`** |
| `__TEXT.__cstring` | `0x11d69` | `0x12794` | **`+0xa2b`** |
| `__TEXT.__const` | `0x1f4d8` | `0x1fce8` | **`+0x810`** |
| `__DATA.__bss` | `0x1b3b0` | `0x1bae0` | **`+0x730`** |
| `__DATA.__objc_const` | `0x32b48` | `0x325e8` | **`-0x560`** |
| `__TEXT.__auth_stubs` | `0x4450` | `0x4950` | **`+0x500`** |
| `__TEXT.__unwind_info` | `0xcd58` | `0xd218` | **`+0x4c0`** |
| `__DATA.__data` | `0xe848` | `0xec48` | **`+0x400`** |
| `__DATA_CONST.__const` | `0x1d710` | `0x1dad0` | **`+0x3c0`** |
| `__TEXT.__oslogstring` | `0x13669` | `0x13a0e` | **`+0x3a5`** |
| `__TEXT.__objc_stubs` | `0x1dde0` | `0x1dac0` | **`-0x320`** |
| `__TEXT.__swift5_fieldmd` | `0x3f9c` | `0x42b8` | **`+0x31c`** |
| `__DATA.__objc_data` | `0xa318` | `0xa620` | **`+0x308`** |
| `__TEXT.__swift5_reflstr` | `0x2d1e` | `0x2fbe` | **`+0x2a0`** |
| `__DATA_CONST.__auth_got` | `0x2238` | `0x24b8` | **`+0x280`** |
| `__TEXT.__constg_swiftt` | `0x54a0` | `0x5718` | **`+0x278`** |
| `__DATA_CONST.__got` | `0x1498` | `0x16c8` | **`+0x230`** |
| `__TEXT.__swift5_typeref` | `0x47d0` | `0x49fa` | **`+0x22a`** |
| `__TEXT.__gcc_except_tab` | `0x4980` | `0x4b5c` | **`+0x1dc`** |
| `__TEXT.__objc_methlist` | `0x15af0` | `0x15990` | **`-0x160`** |
| `__TEXT.__objc_methname` | `0x255d2` | `0x25472` | **`-0x160`** |
| `__DATA_CONST.__auth_ptr` | `0x1208` | `0x1330` | **`+0x128`** |
| `__DATA.__objc_selrefs` | `0x89b0` | `0x88a8` | **`-0x108`** |
| `__DATA_CONST.__cfstring` | `0xe480` | `0xe540` | **`+0xc0`** |
| `__TEXT.__objc_methtype` | `0x84bd` | `0x8418` | **`-0xa5`** |
| `__TEXT.__swift5_capture` | `0x1a58` | `0x1ad4` | **`+0x7c`** |
| `__TEXT.__swift_as_cont` | `0x4ec` | `0x568` | **`+0x7c`** |
| `__DATA.__common` | `0xa38` | `0xaa8` | **`+0x70`** |
| `__TEXT.__objc_classname` | `0x4024` | `0x4074` | **`+0x50`** |
| `__TEXT.__swift_as_ret` | `0x268` | `0x2b4` | **`+0x4c`** |
| `__TEXT.__swift_as_entry` | `0x2a0` | `0x2e4` | **`+0x44`** |
| `__TEXT.__swift5_acfuncs` | `—` | `0x3c` | **`+0x3c`** |
| `__TEXT.__swift5_proto` | `0xcfc` | `0xd30` | **`+0x34`** |
| `__TEXT.__swift5_builtin` | `0x12c` | `0x154` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x400` | `0x428` | **`+0x28`** |
| `__DATA_CONST.__objc_arrayobj` | `0x1f8` | `0x1e0` | **`-0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x1b8` | `0x1a8` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x430` | `0x420` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x6f8` | `0x6e8` | **`-0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x130` | `0x128` | **`-0x8`** |
| `__TEXT.__swift5_assocty` | `0x9c0` | `0x9c8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1128` | `0x1124` | **`-0x4`** |
| `__TEXT.__swift5_protos` | `0x38` | `0x3c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__thread_vars`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-1766.0.13.0.0
+1766.0.27.0.0

+  - /System/Library/PrivateFrameworks/XPCDistributed.framework/XPCDistributed

+  - /usr/lib/swift/libswiftDistributed.dylib

-  Functions: 19986
-  Symbols:   2154
-  CStrings:  11648
+  Functions: 20334
+  Symbols:   2280
+  CStrings:  11652
Symbols:
+ _$s10Foundation19PropertyListDecoderC6decode_4fromxxm_AA4DataVtKSeRzlFTj
+ _$s10Foundation19PropertyListDecoderCACycfc
+ _$s10Foundation19PropertyListDecoderCMa
+ _$s10Foundation19PropertyListEncoderC12outputFormatSo010NSPropertycF0VvsTj
+ _$s10Foundation19PropertyListEncoderC6encodeyAA4DataVxKSERzlFTj
+ _$s10Foundation19PropertyListEncoderCACycfc
+ _$s10Foundation19PropertyListEncoderCMa
+ _$s10Foundation3URLV25deletingLastPathComponentACyF
+ _$s10Foundation3URLV34withUnsafeFileSystemRepresentationyxxSPys4Int8VGSgKXEKlF
+ _$s10Foundation3URLV4pathSSvg
+ _$s10Foundation4DateV21timeIntervalSince1970ACSd_tcfC
+ _$s11ActorSystem11Distributed0cA0PTl
+ _$s11Distributed012buildDefaultA19RemoteActorExecutoryScexAA0aE0RzlF
+ _$s11Distributed0A11ActorSystemP10actorReadyyyqd__AA0aB0Rd__2IDQyd__0bF0RtzlFTj
+ _$s11Distributed0A11ActorSystemP7resolve2id2asqd__Sg0B2IDQz_qd__mtKAA0aB0Rd__0G0Qyd__AIRSlFTj
+ _$s11Distributed0A11ActorSystemP8assignIDy0bE0Qzqd__mAA0aB0Rd__0E0Qyd__AFRSlFTj
+ _$s11Distributed0A11ActorSystemP8resignIDyy0bE0QzFTj
+ _$s11Distributed0A5ActorMp
+ _$s11Distributed0A5ActorP0B6SystemAC_AA0abC0Tn
+ _$s11Distributed0A5ActorP11actorSystem0bD0QzvgTq
+ _$s11Distributed0A5ActorP15unownedExecutorScevgTq
+ _$s11Distributed0A5ActorP7resolve2id5usingx2IDQz_0B6SystemQztKFZTq
+ _$s11Distributed0A5ActorPAAE2eeoiySbx_xtFZ
+ _$s11Distributed0A5ActorPAAE4hash4intoys6HasherVz_tF
+ _$s11Distributed0A5ActorPAASE2IDRpzrlE6encode2toys7Encoder_p_tKF
+ _$s11Distributed0A5ActorPAASe2IDRpzrlE4fromxs7Decoder_p_tKcfC
+ _$s11Distributed0A5ActorPSHTb
+ _$s11Distributed0A5ActorPs12IdentifiableTb
+ _$s11Distributed14__isLocalActorySbyXlF
+ _$s11Distributed16RemoteCallTargetVMa
+ _$s11Distributed16RemoteCallTargetVyACSScfC
+ _$s11Distributed18RemoteCallArgumentV5label4name5valueACyxGSSSg_SSxtcfC
+ _$s11Distributed18RemoteCallArgumentVMn
+ _$s12Transparency12KTErrorChainV24dictionaryRepresentationSDySSypGvg
+ _$s12Transparency12KTErrorChainV5errorACSo7NSErrorC_tcfC
+ _$s12Transparency12KTErrorChainV6domain4code16underlyingErrorsACSS_SiSayACGSgtcfC
+ _$s12Transparency12KTErrorChainVMa
+ _$s12Transparency12KTErrorChainVMn
+ _$s12Transparency12KTErrorChainVSEAAMc
+ _$s12Transparency12KTErrorChainVSeAAMc
+ _$s12Transparency16CKVDeviceFailureV9pushToken5errorACSSSg_AA12KTErrorChainVtcfC
+ _$s12Transparency16CKVDeviceFailureVMa
+ _$s12Transparency16CKVDeviceFailureVMn
+ _$s12Transparency21CKVDiagnosticsServiceMp
+ _$s12Transparency21CKVDiagnosticsServiceP11Distributed0D5ActorTb
+ _$s12Transparency21CKVDiagnosticsServiceP14failureHistory6forURI11applicationSayAA010CKVFailureE5EntryVGSSSg_SStYaKFTq
+ _$s12Transparency21CKVDiagnosticsServiceP14failureHistory6forURI11applicationSayAA010CKVFailureE5EntryVGSSSg_SStYaKFTqTE
+ _$s12Transparency21CKVDiagnosticsServiceP16urisWithFailures11applicationSaySSGSS_tYaKFTq
+ _$s12Transparency21CKVDiagnosticsServiceP16urisWithFailures11applicationSaySSGSS_tYaKFTqTE
+ _$s12Transparency21CKVDiagnosticsServiceP19clearFailureHistory6forURI11applicationySSSg_SStYaKFTq
+ _$s12Transparency21CKVDiagnosticsServiceP19clearFailureHistory6forURI11applicationySSSg_SStYaKFTqTE
+ _$s12Transparency22$CKVDiagnosticsServiceC11Distributed01_D9ActorStubAAMc
+ _$s12Transparency22$CKVDiagnosticsServiceCMa
+ _$s12Transparency22CKVFailureHistoryEntryV11failureTime10Foundation4DateVvg
+ _$s12Transparency22CKVFailureHistoryEntryV3uri11application11failureTime6source5error9traceUUID13idsServerHint02ktnO014deviceFailures21successfulDeviceCount16uiStatusRawValueACSS_SS10Foundation4DateVAC6SourceOAA12KTErrorChainVSgSSSgA2WSayAA16CKVDeviceFailureVGS2itcfC
+ _$s12Transparency22CKVFailureHistoryEntryV6SourceO10concurrentyA2EmFWC
+ _$s12Transparency22CKVFailureHistoryEntryV6SourceO17idsKTVerificationyA2EmFWC
+ _$s12Transparency22CKVFailureHistoryEntryV6SourceOMa
+ _$s12Transparency22CKVFailureHistoryEntryVMa
+ _$s12Transparency22CKVFailureHistoryEntryVMn
+ _$s12Transparency22CKVFailureHistoryEntryVSEAAMc
+ _$s12Transparency22CKVFailureHistoryEntryVSeAAMc
+ _$s12Transparency26AETEventVerificationResultCMn
+ _$s12Transparency26kCKVDiagnosticsServiceNameSSvg
+ _$s14XPCDistributed9XPCSystemC10SetupErrorVMa
+ _$s14XPCDistributed9XPCSystemC10SetupErrorVs0D0AAMc
+ _$s14XPCDistributed9XPCSystemC10remoteCall2on6target10invocation8throwing9returningq0_x_11Distributed06RemoteD6TargetVAC17InvocationEncoderVzq_mq0_mtYaAC0kM17CancellationErrorVYKAJ0J5ActorRzs0P0R_SeR0_SER0_AC0Q2IDV0R0Rtzr1_lF
+ _$s14XPCDistributed9XPCSystemC10remoteCall2on6target10invocation8throwing9returningq0_x_11Distributed06RemoteD6TargetVAC17InvocationEncoderVzq_mq0_mtYaAC0kM17CancellationErrorVYKAJ0J5ActorRzs0P0R_SeR0_SER0_AC0Q2IDV0R0Rtzr1_lFTu
+ _$s14XPCDistributed9XPCSystemC11Distributed0C11ActorSystemAAMc
+ _$s14XPCDistributed9XPCSystemC14remoteCallVoid2on6target10invocation8throwingyx_11Distributed06RemoteD6TargetVAC17InvocationEncoderVzq_mtYaKAI0J5ActorRzs5ErrorR_AC0O2IDV0Q0Rtzr0_lF
+ _$s14XPCDistributed9XPCSystemC14remoteCallVoid2on6target10invocation8throwingyx_11Distributed06RemoteD6TargetVAC17InvocationEncoderVzq_mtYaKAI0J5ActorRzs5ErrorR_AC0O2IDV0Q0Rtzr0_lFTu
+ _$s14XPCDistributed9XPCSystemC17InvocationDecoderV18decodeNextArgumentxyKSeRzSERzlF
+ _$s14XPCDistributed9XPCSystemC17InvocationEncoderV13doneRecordingyyKF
+ _$s14XPCDistributed9XPCSystemC17InvocationEncoderV14recordArgumentyy11Distributed010RemoteCallF0VyxGKSeRzSERzlF
+ _$s14XPCDistributed9XPCSystemC17InvocationEncoderV15recordErrorTypeyyxmKs0F0RzlF
+ _$s14XPCDistributed9XPCSystemC17InvocationEncoderV16recordReturnTypeyyxmKSeRzSERzlF
+ _$s14XPCDistributed9XPCSystemC17InvocationEncoderVMa
+ _$s14XPCDistributed9XPCSystemC21makeInvocationEncoderAC0dE0VyF
+ _$s14XPCDistributed9XPCSystemC33RemoteInvocationCancellationErrorVMa
+ _$s14XPCDistributed9XPCSystemC33RemoteInvocationCancellationErrorVs0F0AAMc
+ _$s14XPCDistributed9XPCSystemC6listen2on18forPeersSatisfying21andExecuteForEachPeeryAC7ServiceV_3XPC18XPCPeerRequirementVyt6result_AC7SessionC14LocalInterfaceV15ActivationTokenV5tokentAQnYaYbXEtYaAC10SetupErrorVYKF
+ _$s14XPCDistributed9XPCSystemC6listen2on18forPeersSatisfying21andExecuteForEachPeeryAC7ServiceV_3XPC18XPCPeerRequirementVyt6result_AC7SessionC14LocalInterfaceV15ActivationTokenV5tokentAQnYaYbXEtYaAC10SetupErrorVYKFTu
+ _$s14XPCDistributed9XPCSystemC7ActorIDVMa
+ _$s14XPCDistributed9XPCSystemC7ActorIDVMn
+ _$s14XPCDistributed9XPCSystemC7ActorIDVSEAAMc
+ _$s14XPCDistributed9XPCSystemC7ActorIDVSHAAMc
+ _$s14XPCDistributed9XPCSystemC7ActorIDVSeAAMc
+ _$s14XPCDistributed9XPCSystemC7ServiceV04machC0yAESSFZ
+ _$s14XPCDistributed9XPCSystemC7ServiceVMa
+ _$s14XPCDistributed9XPCSystemC7SessionC14LocalInterfaceV31activateThenWaitForCancellationyt6result_AG15ActivationTokenV5tokentyYaF
+ _$s14XPCDistributed9XPCSystemC7SessionC14LocalInterfaceV31activateThenWaitForCancellationyt6result_AG15ActivationTokenV5tokentyYaFTu
+ _$s14XPCDistributed9XPCSystemC7SessionC14LocalInterfaceV6export_17asDefaultActorForyx_q_mt11Distributed0kI0RzAJ01_kI4StubR_AC0I6SystemRtzAcMRt_r0_lF
+ _$s14XPCDistributed9XPCSystemCMa
+ _$s14XPCDistributed9XPCSystemCMn
+ _$s14XPCDistributed9XPCSystemCyACSScfc
+ _$s16CoreTransparency20AETEscapableVerifierV11parseEvents14serverResponse13verifyingWith010verifiableF07traceIdAA0C23ProofVerificationResultVAA020CTEscapableAETEventsH0V_AA15CTEPublicKeyBagVSayxGSStAA16AETVerifierErrorOYKAA26AETVerifiableEventProtocolRzlF
+ _$s16CoreTransparency23DeviceClientBagProtocolP16dtMinimumVersions5Int32VvgTj
+ _$s16CoreTransparency28CTEscapableAETEventsResponseV7copyingACx_tcAA0dE8ProtocolRzlufC
+ _$s16CoreTransparency28CTEscapableAETEventsResponseVMa
+ _$s16CoreTransparency35AETEscapableProofVerificationResultVMn
+ _$s24SerializationRequirement11Distributed0C5ActorPTl
+ _$s3XPC18XPCPeerRequirementV14hasEntitlementyACSSFZ
+ _$s3XPC18XPCPeerRequirementVMa
+ _$sBpWV
+ _$sSD15reserveCapacityyySiF
+ _$sSPyxGs7CVarArgsMc
+ _$sSS7cStringSSSPys4Int8VG_tcfC
+ _$sSS7cStringSSSPys5UInt8VG_tcfC
+ _$sScP13userInitiatedScPvgZ
+ _$ss13OpaquePointerVMn
+ _$ss15__VaListBuilderC7va_lists03CVaB7PointerVyF
+ _$ss15__VaListBuilderCMa
+ _$ss4Int8VMn
+ _$ss5ErrorP10FoundationE20localizedDescriptionSSvg
+ _$ss5ErrorPsE5_codeSivg
+ _$ss5ErrorPsE7_domainSSvg
+ _$ss7CVarArgP05_cVarB8EncodingSaySiGvgTj
+ _CFArrayContainsValue
+ _CFArrayGetCount
+ _sqlite3_free
+ _sqlite3_get_autocommit
+ _sqlite3_vmprintf
+ _swift_conformsToProtocol2
+ _swift_cvw_initEnumMetadataSingleCaseWithLayoutString
+ _swift_deletedAsyncMethodErrorTu
+ _swift_distributedActor_remote_initialize
+ _swift_distributed_actor_is_remote
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "%Q"
+ "%lu"
+ "%s: sqlite3_exec: %s[%d]"
+ "@32@0:8Q16q24"
+ "CKV listener failed: %{public}s"
+ "CKV listener returned (cancelled)"
+ "CKV peer connected"
+ "CREATE INDEX IF NOT EXISTS FailureHistory_failureTime\nON FailureHistory (failureTime)"
+ "CREATE INDEX IF NOT EXISTS FailureHistory_uri_app\nON FailureHistory (uri, application)"
+ "CREATE TABLE IF NOT EXISTS FailureHistory (\n    uri TEXT NOT NULL,\n    application TEXT NOT NULL,\n    failureTime REAL NOT NULL,\n    errorTree BLOB,\n    deviceFailures BLOB,\n    successfulDeviceCount INTEGER NOT NULL CHECK (successfulDeviceCount >= 0),\n    uiStatus INTEGER NOT NULL,\n    source INTEGER NOT NULL CHECK (source IN (0, 1)),\n    traceUUID TEXT,\n    idsServerHint TEXT,\n    ktServerHint TEXT\n)"
+ "CREATE TRIGGER IF NOT EXISTS FailureHistory_cap_per_uri\nAFTER INSERT ON FailureHistory\nBEGIN\n    DELETE FROM FailureHistory\n    WHERE rowid IN (\n        SELECT rowid FROM FailureHistory\n        WHERE uri = NEW.uri AND application = NEW.application\n        ORDER BY failureTime DESC, rowid DESC\n        LIMIT -1 OFFSET "
+ "DELETE FROM FailureHistory"
+ "DELETE FROM FailureHistory WHERE application = ?"
+ "DELETE FROM FailureHistory WHERE application = ? AND uri = ?"
+ "DELETE FROM FailureHistory WHERE failureTime < ?"
+ "DELETE FROM FailureHistory WHERE uri = ?"
+ "DTEnforceProofVerification"
+ "Failed to open FailureHistory sidecar at "
+ "Failed to quote SQL string"
+ "GroupSeedGeneration"
+ "GroupSeedKCV"
+ "GroupSeedWrappingType"
+ "GroupUserCount"
+ "INSERT INTO FailureHistory\n  (uri, application, failureTime, errorTree, deviceFailures,\n   successfulDeviceCount, uiStatus, source, traceUUID,\n   idsServerHint, ktServerHint)\nVALUES (?, ?, ?, ?, ?, ?, ?, ?, ?, ?, ?)"
+ "KTSwiftDBStmt prepare: %s"
+ "No CTServerEnvironment provided; emitting unknown sentinel."
+ "PRAGMA auto_vacuum = incremental"
+ "PRAGMA journal_mode = WAL"
+ "SELECT rowid, errorTree, deviceFailures FROM FailureHistory\nWHERE uri = ? AND application = ?\nORDER BY failureTime DESC, rowid DESC\nLIMIT 1"
+ "SELECT uri, application, failureTime, errorTree, deviceFailures,\n       successfulDeviceCount, uiStatus, source, traceUUID,\n       idsServerHint, ktServerHint\nFROM FailureHistory\nORDER BY application, uri, failureTime ASC, rowid ASC"
+ "T@\"NSData\",N,R"
+ "TQ,N,R,VuiStatus"
+ "Tq,N,R,Vsource"
+ "Tq,N,R,VsuccessfulDeviceCount"
+ "Tq,V_timeoutErrorCode"
+ "Transparency: application support directory unavailable"
+ "TransparencyCacheFailureHistory.sqlite"
+ "UPDATE FailureHistory SET failureTime = ? WHERE rowid = ?"
+ "Unhandled CTServerEnvironment case: %{public}s"
+ "VolumeBagVEKCacheStatus"
+ "_TtC13transparencyd13KTSwiftDBStmt"
+ "_TtC13transparencyd15KTDeviceFailure"
+ "_TtC13transparencyd18CKVDiagnosticsImpl"
+ "_TtC13transparencyd18CKVServiceDelegate"
+ "_TtC13transparencyd21KTFailureHistoryEntry"
+ "_timeoutErrorCode"
+ "actorSystem"
+ "clearFailureHistory: %{public}s"
+ "clearFailureHistoryWithApplication:uri:"
+ "com.apple.Transparency.KTDatabase.FailureHistory"
+ "com.apple.transparency.aet.verification.fullProof"
+ "com.apple.transparency.ckv"
+ "com.apple.transparencyd.ckv"
+ "concurrent"
+ "deviceFailures"
+ "enforcedVerification"
+ "errorTree"
+ "failed to open FailureHistory sidecar at %{public}s: %{public}s; deleting and retrying"
+ "failureEventSnapshotForSysdiagnose:"
+ "failureEventSnapshotForSysdiagnose: fetch failed: %@"
+ "failureHistory"
+ "failureHistoryDB"
+ "failureHistoryQueue"
+ "failureHistorySnapshot"
+ "failureHistorySnapshot: %{public}s"
+ "garbageCollectFailureHistory: %{public}s"
+ "garbageCollectFailureHistoryWithOlderThan:"
+ "getInt:"
+ "initWithApplication:dependencies:timeout:intendedState:errorState:"
+ "initWithContextStore:queryManager:ktLogClient:database:"
+ "initWithDatabase:dataStore:"
+ "initWithPushToken:error:"
+ "isFeatureEnabled"
+ "ktServerHint"
+ "proofVerificationMode: override=%ld dtMinimumVersion=%d transparencyVersion=%lld"
+ "q24@0:8@\"NSString\"16"
+ "recordFailure: %{public}s"
+ "recordFailureForURI:application:error:deviceFailures:successfulDeviceCount:uiStatus:source:traceUUID:idsServerHint:ktServerHint:"
+ "setTimeoutErrorCode:"
+ "sqlite3_bind_blob(rawbuffer): %d"
+ "sqlite3_bind_null: %d"
+ "starting CKV listener on %{public}s"
+ "stepWithError %d error: %s"
+ "successfulDeviceCount"
+ "telemetryVersion"
+ "timeout:errorCode:"
+ "timeoutErrorCode"
+ "transparencyFilesPath"
+ "transparencyFilesPath failed, KTDatabase will not start: %@"
+ "transparencyd.CKVServiceDelegate"
+ "transparencyd.KTDeviceFailure"
+ "transparencyd.KTFailureHistoryEntry"
+ "v96@0:8@16@24@32@40q48Q56q64@72@80@88"
+ "verifyProof: not returning all logged events [%s]"
+ "verifyProof: proofVerificationMode=%s [%s]"
+ "verifyProof: returning %ld logged events [%s]"
+ "\xf0\""
- "%@: %s"
- "@\"KTSDBObjc\""
- "B16@?0@\"<KTSDBRow>\"8"
- "B32@0:8@16*24"
- "B32@0:8@?16^@24"
- "KTSDBObjc"
- "KTSDBObjcError"
- "KTSDBRow"
- "KTSDBStmt"
- "KTSDBStmt prepare: %@"
- "RPCBatchQuery"
- "SubclassUtilsBatchQuery"
- "T@\"KTSDBObjc\",&,V_db"
- "T@\"NSArray\",&,D,N"
- "T@\"NSDictionary\",&,N,V_indexesByColumnName"
- "TB,V_needReset"
- "T^{sqlite3=},V_db"
- "T^{sqlite3_stmt=},V_stmt"
- "VACUUM"
- "^{sqlite3=}"
- "^{sqlite3=}16@0:8"
- "^{sqlite3_stmt=}"
- "^{sqlite3_stmt=}16@0:8"
- "_TtCC13transparencyd9KTSwiftDB12SQLStatement"
- "_TtCC13transparencyd9KTSwiftDB6SQLRow"
- "_db"
- "_indexesByColumnName"
- "_needReset"
- "_stmt"
- "allObjectsByColumnName"
- "application == %@ && requestTime > %@ && state == %@"
- "autoVacuumSetting"
- "batchQuery"
- "bindData:column:"
- "bindDate:column:"
- "bindDouble:column:"
- "bindInt64:column:"
- "bindInt:column:"
- "bindNullAtColumn:"
- "bindString:column:"
- "blobAtColumn:"
- "clearBindings"
- "columnCount"
- "columnNameAtColumn:"
- "columnTypeAtColumn:"
- "createBatchQuery"
- "createBatchQuery:backgroundOpId:error:"
- "createBatchQuery:error:"
- "dateAtColumn:"
- "dictionaryWithCapacity:"
- "doubleAtColumn:"
- "enumerateColumnsUsingBlock:"
- "executeSQL:"
- "executeSQL:arguments:"
- "executeSQLStmt:"
- "generateDone"
- "generateError:method:"
- "getLatestSuccessfulBatchQueryForUri:application:requestYoungerThan:error:"
- "indexForColumnName:"
- "initDatabaseWithURL:"
- "initWithContextStore:queryManager:ktLogClient:"
- "initWithFormat:arguments:"
- "initWithStatement:db:error:"
- "int64AtColumn:"
- "intAtColumn:"
- "objectAtColumn:"
- "pragma auto_vacuum = incremental"
- "pragma journal_mode = WAL"
- "prepareStatement:error:"
- "row"
- "setDb:"
- "setIndexesByColumnName:"
- "setNeedReset:"
- "setObject:atIndexedSubscript:"
- "setStmt:"
- "sqlite3_exec: %s[%d]"
- "sqliteCode"
- "step"
- "stepWithError %d error: %@"
- "stepWithError:"
- "steps"
- "steps: %@"
- "steps:error:"
- "telemetryversion"
- "textAtColumn:"
- "v24@0:8^{sqlite3=}16"
- "v24@0:8^{sqlite3_stmt=}16"
- "v24@?0Q8@\"NSString\"16"
- "validatePeerIDSKTVerification:batchQuery:completionBlock:"
- "validatePendingPeersForBatchQuery:"
- "validatePendingPeersForBatchQuery: batch query is unimplemented"
- "validatePendingSMTsForBatchQuery:"
- "validatePendingSMTsForBatchQuery: batch query is unimplemented"
```
