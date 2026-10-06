## MigrationKit

> `/System/Library/PrivateFrameworks/MigrationKit.framework/MigrationKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x769228` | `0x78b120` | **`+0x21ef8`** |
| `__TEXT.__eh_frame` | `0x49284` | `0x4ade0` | **`+0x1b5c`** |
| `__DATA.__bss` | `0x3fd30` | `0x40df0` | **`+0x10c0`** |
| `__AUTH_CONST.__const` | `0x1c200` | `0x1cf68` | **`+0xd68`** |
| `__TEXT.__const` | `0x3af30` | `0x3baf8` | **`+0xbc8`** |
| `__TEXT.__unwind_info` | `0x19c10` | `0x1a5e8` | **`+0x9d8`** |
| `__AUTH.__data` | `0x17650` | `0x17af0` | **`+0x4a0`** |
| `__TEXT.__swift5_capture` | `0x3fc0` | `0x4388` | **`+0x3c8`** |
| `__TEXT.__swift5_typeref` | `0xc847` | `0xcbd3` | **`+0x38c`** |
| `__TEXT.__oslogstring` | `0x1061c` | `0x1098c` | **`+0x370`** |
| `__TEXT.__swift5_fieldmd` | `0xe4d4` | `0xe7ec` | **`+0x318`** |
| `__TEXT.__swift5_reflstr` | `0xd192` | `0xd482` | **`+0x2f0`** |
| `__TEXT.__constg_swiftt` | `0xf6bc` | `0xf98c` | **`+0x2d0`** |
| `__TEXT.__cstring` | `0x1ace1` | `0x1af21` | **`+0x240`** |
| `__AUTH_CONST.__objc_const` | `0x1c4f0` | `0x1c6a8` | **`+0x1b8`** |
| `__TEXT.__swift_as_cont` | `0x40dc` | `0x4270` | **`+0x194`** |
| `__DATA.__data` | `0xe908` | `0xe9f8` | **`+0xf0`** |
| `__TEXT.__swift5_proto` | `0x2478` | `0x24e0` | **`+0x68`** |
| `__DATA_CONST.__const` | `0xb68` | `0xbb0` | **`+0x48`** |
| `__TEXT.__swift_as_entry` | `0x1794` | `0x17dc` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x4d28` | `0x4d68` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x1cd0` | `0x1d0c` | **`+0x3c`** |
| `__AUTH_CONST.__auth_got` | `0x3568` | `0x35a0` | **`+0x38`** |
| `__DATA.__common` | `0x1b78` | `0x1bb0` | **`+0x38`** |
| `__AUTH.__objc_data` | `0x7d10` | `0x7d40` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x348` | `0x370` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0xd78` | `0xda0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x23c8` | `0x23e8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x169c` | `0x16b8` | **`+0x1c`** |
| `__DATA_CONST.__objc_protolist` | `0x2c8` | `0x2b8` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x6fcc` | `0x6fdc` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x128` | `0x120` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0xe0` | `0xdc` | **`-0x4`** |

### Other Changes

```diff

-1426.0.0.0.0
+1428.0.3.0.0

-  Functions: 25807
-  Symbols:   10357
-  CStrings:  4426
+  Functions: 26222
+  Symbols:   10424
+  CStrings:  4454
Symbols:
+ _OBJC_CLASS_$_EKCalendarItem
+ _OBJC_CLASS_$_WiFiAwareDataSessionConfig
+ _OBJC_CLASS_$_WiFiAwarePairingConfig
+ _OBJC_CLASS_$_WiFiAwarePairingPasswordVoucher
+ _OBJC_CLASS_$_WiFiAwarePairingPasswordVoucherStore
+ _OBJC_CLASS_$_WiFiAwarePairingSession
+ __DATA__TtC12MigrationKit26AttestationMetricsRecorder
+ __IVARS__TtC12MigrationKit26AttestationMetricsRecorder
+ __METACLASS_DATA__TtC12MigrationKit26AttestationMetricsRecorder
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_WiFiAwarePairingDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_WiFiAwarePairingDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_WiFiAwarePairingDelegate
+ __OBJC_$_PROTOCOL_REFS_WiFiAwarePairingDelegate
+ __OBJC_LABEL_PROTOCOL_$_WiFiAwarePairingDelegate
+ __OBJC_PROTOCOL_$_WiFiAwarePairingDelegate
+ ___block_descriptor_72_e8_32s40s48r56r64r_e29_v24?0"NSArray"8"NSError"16lr48l8r56l8r64l8s32l8s40l8
+ ___swift_closure_destructor.133Tm
+ ___swift_closure_destructor.15Tm
+ ___swift_closure_destructor.219Tm
+ ___swift_closure_destructor.22Tm
+ ___swift_closure_destructor.36Tm
+ ___swift_closure_destructor.47Tm
+ ___swift_get_extra_inhabitant_index.172Tm
+ ___swift_get_extra_inhabitant_index.209Tm
+ ___swift_memcpy22_8
+ ___swift_store_extra_inhabitant_index.173Tm
+ ___swift_store_extra_inhabitant_index.210Tm
+ ___unnamed_12
+ _associated conformance 12MigrationKit12CommonFieldsV10CodingKeys33_703A8D8B92D72B2764A7A61BBD4D883ELLOSHAASQ
+ _associated conformance 12MigrationKit12CommonFieldsV10CodingKeys33_703A8D8B92D72B2764A7A61BBD4D883ELLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 12MigrationKit12CommonFieldsV10CodingKeys33_703A8D8B92D72B2764A7A61BBD4D883ELLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12MigrationKit15RecoveryTriggerO10Foundation13CustomNSErrorAAs5Error
+ _associated conformance 12MigrationKit18NotesStagedMetricsV10CodingKeys33_6AB54993EFD7403C0F0377FF7FFA95D2LLOSHAASQ
+ _associated conformance 12MigrationKit18NotesStagedMetricsV10CodingKeys33_6AB54993EFD7403C0F0377FF7FFA95D2LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 12MigrationKit18NotesStagedMetricsV10CodingKeys33_6AB54993EFD7403C0F0377FF7FFA95D2LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12MigrationKit24AppContentImportProgressV10CodingKeys33_5CFEF590F937534BCDAD402684A4DA00LLOSHAASQ
+ _associated conformance 12MigrationKit24AppContentImportProgressV10CodingKeys33_5CFEF590F937534BCDAD402684A4DA00LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 12MigrationKit24AppContentImportProgressV10CodingKeys33_5CFEF590F937534BCDAD402684A4DA00LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12MigrationKit31OSMigrationDisconnectionRequestV0D6ReasonO10Foundation13CustomNSErrorAAs5Error
+ _get_enum_tag_for_layout_string 12MigrationKit20DeferredEraseManagerV5PhaseO
+ _symbolic SDySSypG______pIeghHrzo_ s5ErrorP
+ _symbolic SS______SgABt 10Foundation4DateV
+ _symbolic ScCySo31WiFiAwarePairingPasswordVoucherC______pG s5ErrorP
+ _symbolic ScCy______A2AtSg_____G s6UInt64V s5NeverO
+ _symbolic Si11pendingWork_______pSg5actort 12MigrationKit19PersistenceDatabaseP
+ _symbolic Si11pendingWork_yyYbcSg8onErasedt
+ _symbolic So23WiFiAwarePairingSessionC
+ _symbolic So23WiFiAwarePairingSessionCSg
+ _symbolic So36WiFiAwarePairingPasswordVoucherStoreC
+ _symbolic So7EKEventCSaySay_____y___________pGGSgGIeghgo_ s6ResultOsRi_zRi0_zrlE 12MigrationKit15EventAttachmentV s5ErrorP
+ _symbolic So7EKEventCSay______A2CtGIeghgo_ s6UInt64V
+ _symbolic So7EKEventCSay_____y___________pGGIeghgo_ s6ResultOsRi_zRi0_zrlE 12MigrationKit24OSMigrationCalendarEventV s5ErrorP
+ _symbolic _____ 12MigrationKit12CommonFieldsV
+ _symbolic _____ 12MigrationKit12CommonFieldsV10CodingKeys33_703A8D8B92D72B2764A7A61BBD4D883ELLO
+ _symbolic _____ 12MigrationKit15RecoveryTriggerO
+ _symbolic _____ 12MigrationKit18AttestationMetricsV
+ _symbolic _____ 12MigrationKit18NotesStagedMetricsV
+ _symbolic _____ 12MigrationKit18NotesStagedMetricsV10CodingKeys33_6AB54993EFD7403C0F0377FF7FFA95D2LLO
+ _symbolic _____ 12MigrationKit20DeferredEraseManagerV
+ _symbolic _____ 12MigrationKit20DeferredEraseManagerV5PhaseO
+ _symbolic _____ 12MigrationKit22NetworkRecoveryMetricsV
+ _symbolic _____ 12MigrationKit24AppContentImportProgressV
+ _symbolic _____ 12MigrationKit24AppContentImportProgressV10CodingKeys33_5CFEF590F937534BCDAD402684A4DA00LLO
+ _symbolic _____ 12MigrationKit25ExtensionUnavailableErrorV
+ _symbolic _____ 12MigrationKit26AttestationMetricsRecorderC
+ _symbolic _____ So26WiFiAwareTerminationReasonV
+ _symbolic _____Sg 12MigrationKit21PlayIntegrityResponseV
+ _symbolic _____Sg s8DurationV
+ _symbolic _____SgSg 12MigrationKit18OSMigrationV1FrameV06OneOf_E0O
+ _symbolic _____Sg______pIeghHrzo_ 12MigrationKit18OSMigrationV1FrameV06OneOf_E0O s5ErrorP
+ _symbolic ______A2AtSg s6UInt64V
+ _symbolic ___________pIeghHrzo_ 12MigrationKit13AppPropertiesV s5ErrorP
+ _symbolic ___________pIeghHrzo_ 12MigrationKit21PlayIntegrityResponseV s5ErrorP
+ _symbolic ______p______t s5ErrorP 12MigrationKit18AttestationMetricsV
+ _symbolic _____m 12MigrationKit14AppPersistenceC
+ _symbolic _____m 12MigrationKit34AppContentImportMetricsPersistenceC
+ _symbolic _____m 12MigrationKit35AppContentExportMetadataPersistenceC
+ _symbolic _____m 12MigrationKit35FileAttributesPersistenceModelActorC
+ _symbolic _____ySDySSypG______p_G Scg8IteratorV s5ErrorP
+ _symbolic _____ySS______SgACtG s23_ContiguousArrayStorageC 10Foundation4DateV
+ _symbolic _____ySiG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySo14EKCalendarItemCG s11_SetStorageC
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 12MigrationKit18AttestationMetricsV
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 12MigrationKit20DeferredEraseManagerV
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV s5Int64V
+ _symbolic _____y_____G s11_SetStorageC 10Foundation8CalendarV9ComponentO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12MigrationKit12CommonFieldsV10CodingKeys33_703A8D8B92D72B2764A7A61BBD4D883ELLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12MigrationKit18NotesStagedMetricsV10CodingKeys33_6AB54993EFD7403C0F0377FF7FFA95D2LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12MigrationKit24AppContentImportProgressV10CodingKeys33_5CFEF590F937534BCDAD402684A4DA00LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12MigrationKit12CommonFieldsV10CodingKeys33_703A8D8B92D72B2764A7A61BBD4D883ELLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12MigrationKit18NotesStagedMetricsV10CodingKeys33_6AB54993EFD7403C0F0377FF7FFA95D2LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12MigrationKit24AppContentImportProgressV10CodingKeys33_5CFEF590F937534BCDAD402684A4DA00LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation8CalendarV9ComponentO
+ _symbolic _____y_____Sg______p_G Scg8IteratorV 12MigrationKit18OSMigrationV1FrameV06OneOf_F0O s5ErrorP
+ _symbolic _____y______A2BtG 12MigrationKit12BoundedQueue33_216C1161B9422D30049BD8E7799DA82DLLC s6UInt64V
+ _symbolic _____y______A2BtG 12MigrationKit18AsyncBoundedStreamC s6UInt64V
+ _symbolic _____y______A2BtG s23_ContiguousArrayStorageC s6UInt64V
+ _symbolic _____y______A2BtGIeghg_ 12MigrationKit18AsyncBoundedStreamC s6UInt64V
+ _symbolic _____y______A2Bt_G 12MigrationKit18AsyncBoundedStreamC8IteratorV s6UInt64V
+ _symbolic _____y______G 10Foundation20PredicateExpressionsO10NilLiteralV s6UInt64V
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 12MigrationKit18AttestationMetricsV So16os_unfair_lock_sV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 12MigrationKit20DeferredEraseManagerV So16os_unfair_lock_sV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE s5Int64V So16os_unfair_lock_sV
+ _symbolic _____y___________p_G Scg8IteratorV 10Foundation3URLV s5ErrorP
+ _symbolic _____y___________p_G Scg8IteratorV 12MigrationKit13AppPropertiesV s5ErrorP
+ _symbolic _____y___________p_G Scg8IteratorV 12MigrationKit21PlayIntegrityResponseV s5ErrorP
+ _symbolic _____y______y______G_____SgG 10Foundation20PredicateExpressionsO7KeyPathV AC8VariableV 12MigrationKit23AppContentImportMetricsC s6UInt64V
+ _symbolic _____y______y______y______G_____SgG_____y_AFGG 10Foundation20PredicateExpressionsO5EqualV AC7KeyPathV AC8VariableV 12MigrationKit23AppContentImportMetricsC s6UInt64V AC10NilLiteralV
+ _symbolic _____yt______pIeghHgrzo_ 12MigrationKit9APIClientV s5ErrorP
+ _symbolic _____yyt_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic yyYacSg
+ _type_layout_string 12MigrationKit12CommonFieldsV
+ _type_layout_string 12MigrationKit18AttestationMetricsV
+ _type_layout_string 12MigrationKit18NotesStagedMetricsV
+ _type_layout_string 12MigrationKit20DeferredEraseManagerV
+ _type_layout_string 12MigrationKit20DeferredEraseManagerV5PhaseO
+ _type_layout_string 12MigrationKit22NetworkRecoveryMetricsV
+ _type_layout_string 12MigrationKit24AppContentImportProgressV
+ _type_layout_string 12MigrationKit25ExtensionUnavailableErrorV
- _OBJC_CLASS_$_NSPipe
- __DATA__TtC12MigrationKit19NotesLegacyImporter
- __IVARS__TtC12MigrationKit19NotesLegacyImporter
- __METACLASS_DATA__TtC12MigrationKit19NotesLegacyImporter
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_WiFiAwareDataSessionPairingDelegate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_WiFiAwarePublisherPairingDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_WiFiAwareDataSessionPairingDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_WiFiAwarePublisherPairingDelegate
- __OBJC_$_PROTOCOL_REFS_WiFiAwareDataSessionPairingDelegate
- __OBJC_$_PROTOCOL_REFS_WiFiAwarePublisherPairingDelegate
- __OBJC_LABEL_PROTOCOL_$_WiFiAwareDataSessionPairingDelegate
- __OBJC_LABEL_PROTOCOL_$_WiFiAwarePublisherPairingDelegate
- __OBJC_PROTOCOL_$_WiFiAwareDataSessionPairingDelegate
- __OBJC_PROTOCOL_$_WiFiAwarePublisherPairingDelegate
- ___swift_closure_destructor.132Tm
- ___swift_closure_destructor.19Tm
- ___swift_closure_destructor.213Tm
- ___swift_closure_destructor.24Tm
- ___swift_get_extra_inhabitant_index.197Tm
- ___swift_get_extra_inhabitant_index.200Tm
- ___swift_store_extra_inhabitant_index.198Tm
- ___swift_store_extra_inhabitant_index.201Tm
- _get_enum_tag_for_layout_string 12MigrationKit14DatabaseHandleC5State022_5F5479FF8FD2B9769B8C9J9E51353C2ALLO
- _get_enum_tag_for_layout_string xRi_zRi0_zlyxIseghHn_Sg
- _symbolic ScCy______AAtSg_____G s6UInt64V s5NeverO
- _symbolic ScTy_____Sg______pG 12MigrationKit36OSMigrationTargetToSourceFlowControlV06OneOf_defgH0O s5ErrorP
- _symbolic ScTyx______pG s5ErrorP
- _symbolic Si_____Sg______pIeghHyrzo_ 12MigrationKit36OSMigrationTargetToSourceFlowControlV06OneOf_defgH0O s5ErrorP
- _symbolic So7EKEventCSay_____y___________pGGSgIeghgr_ s6ResultOsRi_zRi0_zrlE 12MigrationKit15EventAttachmentV s5ErrorP
- _symbolic So7EKEventC______ACtIeghgr_ s6UInt64V
- _symbolic So7EKEventC_____y___________pGIeghgr_ s6ResultOsRi_zRi0_zrlE 12MigrationKit24OSMigrationCalendarEventV s5ErrorP
- _symbolic _____ 12MigrationKit14DatabaseHandleC5State022_5F5479FF8FD2B9769B8C9J9E51353C2ALLO
- _symbolic _____ 12MigrationKit19NotesLegacyExporterV
- _symbolic _____ 12MigrationKit19NotesLegacyImporterC
- _symbolic _____ 12MigrationKit29AsyncInputStreamWithWriteTaskV
- _symbolic _____ 15AppMigrationKit18ResourcesExtractorV
- _symbolic ______AAtSg s6UInt64V
- _symbolic ________________pXj r0_lScI_px7ElementRts_q_7FailureRtsXPXGMq s5UInt8V s5ErrorP
- _symbolic ______pSg5actor_t 12MigrationKit19PersistenceDatabaseP
- _symbolic _____y_SdG 12MigrationKit16AnalyticsPayload33_703A8D8B92D72B2764A7A61BBD4D883ELLC5FieldV
- _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 12MigrationKit14DatabaseHandleC5State022_5F5479FF8FD2B9769B8C9N9E51353C2ALLO
- _symbolic _____y______ABtG 12MigrationKit12BoundedQueue33_216C1161B9422D30049BD8E7799DA82DLLC s6UInt64V
- _symbolic _____y______ABtG 12MigrationKit18AsyncBoundedStreamC s6UInt64V
- _symbolic _____y______ABtG s23_ContiguousArrayStorageC s6UInt64V
- _symbolic _____y______ABtGIeghg_ 12MigrationKit18AsyncBoundedStreamC s6UInt64V
- _symbolic _____y______ABt_G 12MigrationKit18AsyncBoundedStreamC8IteratorV s6UInt64V
- _symbolic _____y__________G s13ManagedBufferCsRi__rlE 12MigrationKit14DatabaseHandleC5State022_5F5479FF8FD2B9769B8C9L9E51353C2ALLO So16os_unfair_lock_sV
- _symbolic _____y_____y___________pGG 12MigrationKit29AsyncInputStreamWithWriteTaskV s6ResultOsRi_zRi0_zrlE 03AppaB00J7ContentV s5ErrorP
- _symbolic yxYaYbcSg
- _type_layout_string 12MigrationKit14DatabaseHandleC5State022_5F5479FF8FD2B9769B8C9J9E51353C2ALLO
- _type_layout_string 12MigrationKit19NotesLegacyExporterV
- _type_layout_string s8SendableRzl12MigrationKit29AsyncInputStreamWithWriteTaskVyxG
CStrings:
+ " per-item persistence error(s) across "
+ "%@ did receive progress from client. progress=%f, remainingTime=%llu, state=%ld, success=%d, fail=%d"
+ "%@ export complete (client reported >= 100%%); will announce import. completedOperationCount=%llu, totalOperationCount=%llu"
+ "A disconnection request is already in flight; ignoring new request with reason %s"
+ "App content fetch error on attempt #"
+ "Comma-separated `DATACLASS[.ROLE]=VERSION` list that pins version negotiation. Use the data-class defaults key (e.g. `NOTES`, `PASSWORDS`) optionally suffixed with `.IMPORT` or `.EXPORT` to target a single side; bare `NOTES=2` pins both sides. Example: `NOTES=2,PASSWORDS.EXPORT=3`. Pinned version must match a registered migrator version; otherwise the clamp is ignored."
+ "Data session terminated before confirmation"
+ "Deferring .telemetry clean: AppContent import is in flight (handed off to app-content completion)"
+ "Detached event's master or occurrence not found"
+ "DisconnectionRequestReason"
+ "Failed to fetch total metrics count"
+ "Failed to fetch unresolved metrics count"
+ "Failed to import staged notes"
+ "Failed to load app content import progress"
+ "Failed to record pending purchase"
+ "Failed to record staging failure telemetry"
+ "Failed to record staging failure telemetry for"
+ "Failed to save app content import progress"
+ "Failed to send completed-data-transfer state"
+ "Failed to update import metrics"
+ "Imported event has nil eventIdentifier"
+ "MigrationKit.RecoveryTrigger"
+ "MigrationKit/AppContentImportProgress.swift"
+ "Modified detached occurrence has nil eventIdentifier"
+ "Modified detached occurrence has nil eventIdentifier, likely deleted before reading"
+ "New pairing session received"
+ "No import analytics session could be restored; notes dataClass telemetry will be dropped"
+ "No local or iCloud source available"
+ "Notes import extension not reachable yet; leaving notes staged"
+ "Pairing delegate responding with password"
+ "Pairing session already active, not starting another"
+ "Pairing session failed"
+ "Pairing session failed to start"
+ "Pairing session failed to start: %s"
+ "Pairing session failed: %s"
+ "Pairing session succeeded"
+ "Per-attempt deadline for a single Andata Play Integrity request before it is abandoned and retried, in seconds (0 disables)"
+ "Publisher failed to start: "
+ "Publisher terminated: "
+ "Server may not be fully informed of completion"
+ "Starting pairing session"
+ "Subscriber torn down before activation completed"
+ "Timed out bringing up WiFiAware subscriber"
+ "Timed out while waiting for disconnection response"
+ "Unexpected error while waiting for disconnection response"
+ "WiFi Aware publisher did not produce a pairing password"
+ "_requestAndataValidation(playIntegrityToken:recorder:)"
+ "_sendAndata(request:session:attempt:recorder:)"
+ "app_content_import_progress"
+ "attestationServiceAttemptTimeoutSeconds"
+ "attestation_error"
+ "attestation_final_state"
+ "attestation_http_response_code"
+ "attestation_retry_count"
+ "dataSession(_:terminatedWith:)"
+ "database torn down mid-import — stopping asset import"
+ "database torn down mid-import — stopping collection import"
+ "did serialize deleted occurrence event: %s"
+ "failed to update app mapping"
+ "import-incomplete"
+ "imported detached occurrence: %@"
+ "lastActivityMillis"
+ "lazyPhaseComplete"
+ "marked %llu detached events as untransferable"
+ "master/occurrence not found for detached event %s; skipping"
+ "network_recovery_attempt_count"
+ "network_recovery_success_count"
+ "network_recovery_trigger_reason"
+ "pairingSession(_:didFailTo:error:)"
+ "pairingSessionFailed(toStart:)"
+ "photo lazy import finished with "
+ "processCalendarEvent(_:_:)"
+ "publisher(_:terminatedWith:)"
+ "removed detached occurrence for event %s"
+ "run(scheme:originatingUIFlow:)"
+ "send data control message: "
+ "sendControlMessage(_:)"
+ "startSubscriber()"
+ "store item has no valid offer and will be skipped. id=%@"
+ "tearDown()"
+ "will import %ld detached events"
+ "will remove detached occurrence: %@"
+ "withRetryingClient(maxAttempts:backoff:acquireTimeout:body:)"
- "Comma-separated `DATACLASS[.ROLE]=VERSION` list that pins version negotiation. Use the data-class defaults key (e.g. `NOTES`, `PASSWORDS`) optionally suffixed with `.IMPORT` or `.EXPORT` to target a single side; bare `NOTES=1` pins both sides. Example: `NOTES=1,PASSWORDS.EXPORT=3`. Pinned version must match a registered migrator version; otherwise the clamp is ignored."
- "Controller finished exporting resources for %s"
- "Exporting resources for %s"
- "Failed to create client; server will not be informed of completion"
- "Failed to fetch accounts from database"
- "Failed to import staged notes; leaving staged for retry"
- "Failed to load app match stats from plist"
- "Failed to save context"
- "Failed to save inserted PendingAppInstall"
- "Failed to save inserted metrics"
- "Failed to save to persistence"
- "Failed to send transfer summary"
- "Failed to send updated state"
- "Failed to update metrics for bundleID"
- "Fetching resources for %s"
- "Finished fetching resources for %s"
- "Ignored %llu archive files from %s"
- "MigrationKit/AccountPersistenceModelActor.swift"
- "MigrationKit/AppPersistence.swift"
- "MigrationKit/AsyncInputStreamWithWriteTask.swift"
- "MigrationKit/HomeScreenPersistence2.swift"
- "MigrationKit/NotesLegacyImporter.swift"
- "MigrationKit/WiFiNetworkPersistenceModelActor.swift"
- "No notes exporter for negotiated version "
- "No notes importer for negotiated version "
- "Notes appex returned indeterminate result after staging "
- "Notes appex returned sentinel counts (successes="
- "Pairing request started; responding with password: %s"
- "Pairing requested by subscriber; passphrase=%s"
- "Publisher failed to start"
- "Received 204 No Content for /notes - no data to import"
- "Received disconnection response"
- "Timed out waiting for read from extension"
- "Unexpected content type for v1 /notes response: "
- "Unexpected error while waiting for disconnection request delivery"
- "Warning: disconnection request may not be delivered to peer"
- "_requestAndataValidation(playIntegrityToken:)"
- "_sendAndata(request:session:)"
- "application/x-gtar"
- "application/x-tar"
- "application/x-tgz"
- "exportResources(for:platform:exportOptions:)"
- "exporter(selection:appPropertiesController:appDataclassesController:negotiatedVersion:)"
- "failed to add assets to a collection"
- "failed to create assets"
- "failed to create collections"
- "failed to create relationships"
- "fetchResources(from:identifier:bytesWritten:context:)"
- "getAllAccounts()"
- "import notes (v1) into appex"
- "importEvents(_:_:)"
- "run(scheme:)"
- "send data control message (#"
- "sendControlMessage(_:maxAttempts:)"
- "system-dataclass:notes"
```
