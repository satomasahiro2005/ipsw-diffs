## Message

> `/System/Library/PrivateFrameworks/Message.framework/Message`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xae2654` | `0xaf3a2c` | **`+0x113d8`** |
| `__AUTH_CONST.__const` | `0xa9aa8` | `0xac010` | **`+0x2568`** |
| `__TEXT.__swift5_capture` | `0x32574` | `0x33494` | **`+0xf20`** |
| `__TEXT.__oslogstring` | `0x27680` | `0x27b40` | **`+0x4c0`** |
| `__TEXT.__const` | `0x6b2c8` | `0x6b5e8` | **`+0x320`** |
| `__AUTH_CONST.__objc_const` | `0x22dd8` | `0x230d0` | **`+0x2f8`** |
| `__DATA.__bss` | `0x533c0` | `0x53640` | **`+0x280`** |
| `__AUTH.__data` | `0xb1d8` | `0xb408` | **`+0x230`** |
| `__TEXT.__cstring` | `0x31196` | `0x31346` | **`+0x1b0`** |
| `__TEXT.__swift5_typeref` | `0x10a9a` | `0x10c02` | **`+0x168`** |
| `__TEXT.__constg_swiftt` | `0xd8b8` | `0xda18` | **`+0x160`** |
| `__DATA.__data` | `0xe828` | `0xe958` | **`+0x130`** |
| `__TEXT.__unwind_info` | `0x1e900` | `0x1ea08` | **`+0x108`** |
| `__TEXT.__swift5_fieldmd` | `0x152fc` | `0x153a4` | **`+0xa8`** |
| `__DATA_CONST.__got` | `0x2ee8` | `0x2e90` | **`-0x58`** |
| `__TEXT.__swift5_reflstr` | `0xf1f0` | `0xf240` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x185ec` | `0x18634` | **`+0x48`** |
| `__TEXT.__swift5_assocty` | `0x1cd8` | `0x1d20` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x18620` | `0x18660` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x4108` | `0x40e8` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x2a04` | `0x2a20` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0xb50` | `0xb68` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x369cc` | `0x369e4` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xb848` | `0xb858` | **`+0x10`** |
| `__DATA.__common` | `0xeb1` | `0xea9` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x14454` | `0x1444c` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x1824` | `0x182c` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x68` | `0x6c` | **`+0x4`** |

### Other Changes

```diff

-3895.100.17.2.1
+3897.100.8.2.5

-  Functions: 48085
-  Symbols:   21315
-  CStrings:  8507
+  Functions: 48452
+  Symbols:   21324
+  CStrings:  8521
Symbols:
+ -[MFMailMessageLibrary hasUnindexedMessageBodiesForAccount:beyondCount:]
+ -[MFPersistence_iOS persistenceStatisticsForcingRefresh:]
+ -[MFPersistence_iOS searchableIndexStatisticsForcingRefresh:]
+ -[MFSearchableIndexManager_iOS _ensureIndexingObjectsConstructed]
+ -[MFSearchableIndexManager_iOS downloadRequestQueue]
+ -[MFSearchableIndexManager_iOS spotlightDaemonClient]
+ GCC_except_table410
+ GCC_except_table419
+ GCC_except_table450
+ GCC_except_table455
+ GCC_except_table476
+ GCC_except_table479
+ GCC_except_table485
+ GCC_except_table495
+ GCC_except_table500
+ GCC_except_table504
+ GCC_except_table508
+ GCC_except_table512
+ GCC_except_table516
+ GCC_except_table518
+ GCC_except_table523
+ GCC_except_table531
+ GCC_except_table533
+ GCC_except_table555
+ GCC_except_table558
+ GCC_except_table564
+ __DATA__TtC7MessageP33_8C94728D29B9D9CACC7F5FFB5564322B13DASRunContext
+ __DATA__TtC7MessageP33_8C94728D29B9D9CACC7F5FFB5564322B19BootstrapRunContext
+ __DATA__TtCE7MessageCSo30MFBackFillMessageBodySchedulerP33_8C94728D29B9D9CACC7F5FFB5564322B11ActivityBox
+ __IVARS__TtC7MessageP33_8C94728D29B9D9CACC7F5FFB5564322B13DASRunContext
+ __IVARS__TtC7MessageP33_8C94728D29B9D9CACC7F5FFB5564322B19BootstrapRunContext
+ __IVARS__TtCE7MessageCSo30MFBackFillMessageBodySchedulerP33_8C94728D29B9D9CACC7F5FFB5564322B11ActivityBox
+ __METACLASS_DATA__TtC7MessageP33_8C94728D29B9D9CACC7F5FFB5564322B13DASRunContext
+ __METACLASS_DATA__TtC7MessageP33_8C94728D29B9D9CACC7F5FFB5564322B19BootstrapRunContext
+ __METACLASS_DATA__TtCE7MessageCSo30MFBackFillMessageBodySchedulerP33_8C94728D29B9D9CACC7F5FFB5564322B11ActivityBox
+ _associated conformance 7Message22BackFillBootstrapError33_8C94728D29B9D9CACC7F5FFB5564322BLLV10Foundation09LocalizedE0AAs0E0
+ _associated conformance 7Message5Phase33_8C94728D29B9D9CACC7F5FFB5564322BLLOSHAASQ
+ _associated conformance 7Message5Phase33_8C94728D29B9D9CACC7F5FFB5564322BLLOSLAASQ
+ _associated conformance 7Message5Phase33_8C94728D29B9D9CACC7F5FFB5564322BLLOs12CaseIterableAA8AllCasessAEP_Sl
+ _associated conformance So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC2IDVSHACSQ
+ _symbolic $s7Message18BackFillRunContext33_8C94728D29B9D9CACC7F5FFB5564322BLLP
+ _symbolic SDy__________G So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC2IDV AF
+ _symbolic Say_____G 7Message13WatchOSRenderO9ContentIDV
+ _symbolic Say_____G 7Message5Phase33_8C94728D29B9D9CACC7F5FFB5564322BLLO
+ _symbolic Say_____G So37EDSearchableIndexDownloadRequestQueueC11EmailDaemonE0C0V
+ _symbolic Say______So19BGSystemTaskRequestCtG 7Message5Phase33_8C94728D29B9D9CACC7F5FFB5564322BLLO
+ _symbolic Shy_____G 7Message13WatchOSRenderO9ContentIDV
+ _symbolic _____ 7Message13DASRunContext33_8C94728D29B9D9CACC7F5FFB5564322BLLC
+ _symbolic _____ 7Message19BootstrapRunContext33_8C94728D29B9D9CACC7F5FFB5564322BLLC
+ _symbolic _____ 7Message22BackFillBootstrapError33_8C94728D29B9D9CACC7F5FFB5564322BLLV
+ _symbolic _____ 7Message5Phase33_8C94728D29B9D9CACC7F5FFB5564322BLLO
+ _symbolic _____ So30MFBackFillMessageBodySchedulerC0C0E11ActivityBox33_8C94728D29B9D9CACC7F5FFB5564322BLLC
+ _symbolic _____Sg 7Message5Phase33_8C94728D29B9D9CACC7F5FFB5564322BLLO
+ _symbolic _____Sg So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC
+ _symbolic _____SgAAc 7Message5Stage33_8C94728D29B9D9CACC7F5FFB5564322BLLO
+ _symbolic _____SgXw So33MFNanoServerMessageContentLoader2C0C0E14Implementation33_55FE1C6453F069120C6D9FDA55988047LLC
+ _symbolic _____SgXwz_Xx So33MFNanoServerMessageContentLoader2C0C0E14Implementation33_55FE1C6453F069120C6D9FDA55988047LLC
+ _symbolic ______So19BGSystemTaskRequestCt 7Message5Phase33_8C94728D29B9D9CACC7F5FFB5564322BLLO
+ _symbolic ___________t So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC2IDV AF
+ _symbolic ______p 7Message18BackFillRunContext33_8C94728D29B9D9CACC7F5FFB5564322BLLP
+ _symbolic _____ySay_____GG s16IndexingIteratorV 7Message5Phase33_8C94728D29B9D9CACC7F5FFB5564322BLLO
+ _symbolic _____y_____So19BGSystemTaskRequestC__G SD6ValuesV8IteratorV 7Message5Phase33_8C94728D29B9D9CACC7F5FFB5564322BLLO
+ _symbolic _____y___________G SD4KeysV 7Message13WatchOSRenderO9ContentIDV 10Foundation4DataV
+ _symbolic _____y____________G SD6ValuesV8IteratorV So30MFBackFillMessageBodySchedulerC0E0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC2IDV AJ
+ _type_layout_string 7Message22BackFillBootstrapError33_8C94728D29B9D9CACC7F5FFB5564322BLLV
- -[MFPersistence_iOS persistenceStatistics]
- -[MFPersistence_iOS searchableIndexStatistics]
- -[MFSearchableIndexManager_iOS enableIndexingAndBeginScheduling:]
- -[MFSearchableIndexManager_iOS setIndex:]
- -[MFSearchableIndexManager_iOS setScheduler:]
- GCC_except_table411
- GCC_except_table420
- GCC_except_table451
- GCC_except_table475
- GCC_except_table478
- GCC_except_table483
- GCC_except_table487
- GCC_except_table497
- GCC_except_table503
- GCC_except_table507
- GCC_except_table511
- GCC_except_table515
- GCC_except_table517
- GCC_except_table522
- GCC_except_table524
- GCC_except_table532
- GCC_except_table554
- GCC_except_table557
- GCC_except_table559
- _XPC_ACTIVITY_ALLOW_BATTERY
- _XPC_ACTIVITY_CHECK_IN
- _XPC_ACTIVITY_DELAY
- _XPC_ACTIVITY_EXPECTED_DURATION
- _XPC_ACTIVITY_GRACE_PERIOD
- _XPC_ACTIVITY_INTERVAL_1_DAY
- _XPC_ACTIVITY_INTERVAL_30_MIN
- _XPC_ACTIVITY_NETWORK_DOWNLOAD_SIZE
- _XPC_ACTIVITY_NETWORK_UPLOAD_SIZE
- _XPC_ACTIVITY_REPEATING
- _XPC_ACTIVITY_REQUIRE_INEXPENSIVE_NETWORK_CONNECTIVITY
- _associated conformance So30MFBackFillMessageBodySchedulerC0C0E10TurboError33_8C94728D29B9D9CACC7F5FFB5564322BLLO10ConstraintOSHACSQ
- _associated conformance So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC4KindOSHACSQ
- _get_enum_tag_for_layout_string So30MFBackFillMessageBodySchedulerC0C0E10TurboError33_8C94728D29B9D9CACC7F5FFB5564322BLLO
- _symbolic Shy_____G So30MFBackFillMessageBodySchedulerC0C0E10TurboError33_8C94728D29B9D9CACC7F5FFB5564322BLLO10ConstraintO
- _symbolic _____ So30MFBackFillMessageBodySchedulerC0C0E10TurboError33_8C94728D29B9D9CACC7F5FFB5564322BLLO
- _symbolic _____ So30MFBackFillMessageBodySchedulerC0C0E10TurboError33_8C94728D29B9D9CACC7F5FFB5564322BLLO10ConstraintO
- _symbolic _____ So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC4KindO
- _symbolic ______Sbt So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC4KindO
- _symbolic ______Sit 12NIOIMAPCore216SectionSpecifierV4PartV
- _symbolic _____y______SitG s23_ContiguousArrayStorageC 12NIOIMAPCore216SectionSpecifierV4PartV
- _type_layout_string So30MFBackFillMessageBodySchedulerC0C0E10TurboError33_8C94728D29B9D9CACC7F5FFB5564322BLLO
- _xpc_activity_copy_criteria
- _xpc_activity_get_state
- _xpc_activity_register
- _xpc_activity_set_completion_status
- _xpc_activity_set_criteria
- _xpc_activity_set_state
- _xpc_activity_should_defer
- _xpc_copy_clean_description
- _xpc_dictionary_create_empty
- _xpc_equal
CStrings:
+ "%hx: Running %ld account(s) from lowest stage %{public}s (search-ready eligible: %{bool}d)."
+ "%ld new account(s) added. Reporting checkpoint."
+ "(searchable_messages.message IS NULL OR searchable_messages.message_body_indexed = 0 OR searchable_messages.transaction_id = 0)%@"
+ ".bootstrap"
+ ".phase-"
+ "Back-fill bootstrap ended with status "
+ "Backfill work pending. Submitting initial backfill tasks."
+ "Bootstrap: complete."
+ "Bootstrap: ended with status %{public}s."
+ "Bootstrap: foreground back-fill for %ld account(s)."
+ "Bootstrap: no accounts need back-fill. Completing."
+ "DELETE FROM properties WHERE key = 'BackFillMessageBodiesStages';"
+ "No accounts need backfill in phase %ld. Completing."
+ "PartsForHTMLBody"
+ "RaveAddHeadersIndexedFieldsToProgressStatistics"
+ "RaveResetSearchIndexForMissedUpgradeReDonation"
+ "Resetting BackFillMessageBodiesStages cursor for body re-discovery."
+ "Search AVAILABLE: oneMonth reached terminal (run started at %{public}s). Reporting .available for feature %ld."
+ "Skipping image part [%{public}s] for watch: %ld bytes (total so far: %ld)."
+ "Skipping part [%{public}s] for watch: %ld bytes exceeds limit (total so far: %ld)."
+ "[%.*hhx-%.*X] Sealing .everything .complete — remaining unindexed bodies (≤%ld) were given up on this session (undownloadable); recurring backfill will retry."
+ "[%.*hhx-%.*X] Withholding .everything .complete — fetchable unindexed bodies remain (beyond %ld given up on); reporting .pendingWork so backfill re-stages."
+ "[%.*hhx-%.*X] [%{sensitive,mask.mailbox}s] Gave up on %ld message(s) larger than the index-download budget (%lld bytes); excluded from future backfill scans."
+ "[%lld] (%u) Did finish loading. All attachments delivered."
+ "[%lld] (%u) Did finish loading. Delivered %ld attachment(s) in second phase."
+ "[%lld] (%u) Missing %ld attachment(s). Starting second-phase download."
+ "[%lld] (%u) Second-phase download complete."
+ "[%lld] (%u) Second-phase download failed."
+ "[%lld] (%u) Second-phase parse failed."
+ "[%lld] Skipping attachment [%{public}s]: %ld bytes exceeds limit."
+ "[%{public}s] DAS deferred this task before we could start work. Bailing out; starting an Activity now would take a power assertion no one could release."
+ "[%{public}s] Deferred before Activity started; nothing to stop"
+ "[%{public}s] Failing attachment download for watch. No PersistenceAdaptor."
+ "[%{public}s] Phase %ld BOUNDARY: stopping after %{public}s (next %{public}s belongs to phase %ld)."
+ "[%{public}s] Phase %ld CROSSING: account finished %{public}s; submitting phase %ld task '%{public}s'."
+ "[%{public}s] Preempting %ld in-flight activit(ies)."
+ "apple.com"
- "%hx: Failed to set completion status to %{public}d"
- "%hx: Running."
- "%hx: Still waiting for work to be deferred."
- "%hx: Timer fired"
- "%hx: Work needs to be deferred."
- "Checked in."
- "Checking in: Updating criteria to %{public}s"
- "Failed to set completion status for duplicate activity"
- "Failed to set completion status while deferring during turbo"
- "New account was added. Submitting initial backfill task."
- "Received new activity, but already have a turbo one: %hx."
- "Received new activity, but already have an existing one %hx."
- "Received new task run, but already have a turbo one: %hx."
- "Received new task run, but already have an existing one %hx"
- "Received new turbo request, but already have an existing one: %hx."
- "Received turbo request, but already have a scheduled one: %hx. Cancelling."
- "Registering XPC activity for '%{public}s'."
- "Run XPC activity"
- "Running turbo request"
- "Un-registering XPC activity for '%s'."
- "Unable to set state to CONTINUE."
- "Unexpected activity state: %ld."
- "radar@apple.com"
```
