## PrivateCloudComputeDaemon

> `/System/Library/PrivateFrameworks/PrivateCloudComputeDaemon.framework/PrivateCloudComputeDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x253438` | `0x256060` | **`+0x2c28`** |
| `__DATA.__bss` | `0x10790` | `0xff90` | **`-0x800`** |
| `__DATA_DIRTY.__bss` | `0x9300` | `0x9b00` | **`+0x800`** |
| `__DATA_DIRTY.__data` | `0x8d80` | `0x9550` | **`+0x7d0`** |
| `__DATA.__data` | `0x2640` | `0x2128` | **`-0x518`** |
| `__TEXT.__eh_frame` | `0x11524` | `0x1198c` | **`+0x468`** |
| `__AUTH.__data` | `0x13a8` | `0x11a8` | **`-0x200`** |
| `__TEXT.__const` | `0x156b8` | `0x158b8` | **`+0x200`** |
| `__TEXT.__swift5_typeref` | `0x65e0` | `0x674c` | **`+0x16c`** |
| `__TEXT.__oslogstring` | `0x75d9` | `0x7729` | **`+0x150`** |
| `__TEXT.__swift5_reflstr` | `0x62a8` | `0x63a8` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x7490` | `0x7558` | **`+0xc8`** |
| `__DATA_DIRTY.__objc_data` | `0x6f0` | `0x798` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0x140` | `0xa0` | **`-0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x59f8` | `0x5a78` | **`+0x80`** |
| `__TEXT.__cstring` | `0x6141` | `0x61b1` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x3d88` | `0x3de8` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x5594` | `0x55f0` | **`+0x5c`** |
| `__TEXT.__swift5_capture` | `0x1144` | `0x119c` | **`+0x58`** |
| `__TEXT.__swift_as_entry` | `0x508` | `0x554` | **`+0x4c`** |
| `__TEXT.__swift_as_ret` | `0x59c` | `0x5e8` | **`+0x4c`** |
| `__DATA_DIRTY.__common` | `0x220` | `0x258` | **`+0x38`** |
| `__DATA.__common` | `0xc8` | `0x98` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x1228` | `0x1258` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0xbd4` | `0xbbc` | **`-0x18`** |
| `__AUTH_CONST.__const` | `0x9e80` | `0x9e90` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x718` | `0x728` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x398` | `0x3a8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xd58` | `0xd5c` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0xa0` | `0xa4` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x514` | `0x518` | **`+0x4`** |

### Other Changes

```diff

-2570.0.5.0.0
+2570.0.12.0.0

+  - /System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag

-  Functions: 9269
-  Symbols:   2475
-  CStrings:  1148
+  Functions: 9330
+  Symbols:   2476
+  CStrings:  1155
Symbols:
+ _MKBDeviceUnlockedSinceBoot
+ ___swift_closure_destructor.202Tm
+ ___swift_closure_destructor.209Tm
+ ___swift_closure_destructor.20Tm
+ ___swift_closure_destructor.26Tm
+ ___swift_closure_destructor.281Tm
+ ___swift_closure_destructor.285Tm
+ ___swift_closure_destructor.5Tm
+ ___swift_exist.box.addr_destructor.187Tm
+ _swift_release_x3
+ _symbolic $s25PrivateCloudComputeDaemon19DeviceStateProtocolP
+ _symbolic G1R1_
+ _symbolic SDy__________y_________________________y__________G_________________________yAchlMGAH_____GG 25PrivateCloudComputeDaemon16TC2ResolvedSetupV AA21TrustedRequestFactoryC 0abC020DefaultConfigurationV AA17NWAsyncConnectionV AA22LegacyAttestationStoreC AA08DeferredpQ0C AA0P8VerifierV AF18FeatureFlagCheckerV 0bP012MuxValidatorV AA0R11RateLimiterC AA012ServerDrivenL0C AA10SystemInfoV AA11DeviceStateV AA013TokenProviderJ0V s15ContinuousClockV
+ _symbolic ShySiG
+ _symbolic _____ 19PrivateCloudCompute18IdentifierSequenceV
+ _symbolic _____ 25PrivateCloudComputeDaemon11DeviceStateV
+ _symbolic _____4node_SS4udidt 25PrivateCloudComputeDaemon022ValidatedAttestationOrF0O
+ _symbolic _____m 25PrivateCloudComputeDaemon06Proto_abc1_abC7RequestV
+ _symbolic _____ySDy__________y_________________________y__________G_________________________yAdimNGAI_____GGG 15Synchronization5MutexVAARi_zrlE 25PrivateCloudComputeDaemon16TC2ResolvedSetupV AD21TrustedRequestFactoryC 0cdE020DefaultConfigurationV AD17NWAsyncConnectionV AD22LegacyAttestationStoreC AD08DeferredrS0C AD0R8VerifierV AI18FeatureFlagCheckerV 0dR012MuxValidatorV AD0T11RateLimiterC AD012ServerDrivenN0C AD10SystemInfoV AD11DeviceStateV AD013TokenProviderL0V s15ContinuousClockV
+ _symbolic _____ySiG s11_SetStorageC
+ _symbolic _____ySiG s23_ContiguousArrayStorageC
+ _symbolic _____y_ShySSGG 10Foundation20PredicateExpressionsO5ValueV
+ _symbolic _____y_____4node_SS4udidtG s23_ContiguousArrayStorageC 25PrivateCloudComputeDaemon022ValidatedAttestationOrI0O
+ _symbolic _____y__________G 25PrivateCloudComputeDaemon03TC2D4HostC AA10SystemInfoV AA11DeviceStateV
+ _symbolic _____y__________GSgXw 25PrivateCloudComputeDaemon03TC2D4HostC AA10SystemInfoV AA11DeviceStateV
+ _symbolic _____y_________________________y__________G_________________________yAbgkLGAG_____G 25PrivateCloudComputeDaemon21TrustedRequestFactoryC 0abC020DefaultConfigurationV AA17NWAsyncConnectionV AA22LegacyAttestationStoreC AA08DeferredmN0C AA0M8VerifierV AD18FeatureFlagCheckerV 0bM012MuxValidatorV AA0O11RateLimiterC AA012ServerDrivenI0C AA10SystemInfoV AA11DeviceStateV AA013TokenProviderG0V s15ContinuousClockV
+ _symbolic _____y__________y_________________________y__________G_________________________yAdimNGAI_____GG s18_DictionaryStorageC 25PrivateCloudComputeDaemon16TC2ResolvedSetupV AC21TrustedRequestFactoryC 0cdE020DefaultConfigurationV AC17NWAsyncConnectionV AC22LegacyAttestationStoreC AC08DeferredrS0C AC0R8VerifierV AH18FeatureFlagCheckerV 0dR012MuxValidatorV AC0T11RateLimiterC AC012ServerDrivenN0C AC10SystemInfoV AC11DeviceStateV AC013TokenProviderL0V s15ContinuousClockV
+ _symbolic _____y______y_ShySSGG_____y______y______GSSGG 10Foundation20PredicateExpressionsO16SequenceContainsV AC5ValueV AC7KeyPathV AC8VariableV 25PrivateCloudComputeDaemon16AttestationStoreC8SchemaV3O10NodeBundleC
+ _symbolic _____y______y_ShySSGG_____y______y______GSSGG 10Foundation20PredicateExpressionsO16SequenceContainsV AC5ValueV AC7KeyPathV AC8VariableV 25PrivateCloudComputeDaemon16AttestationStoreC8SchemaV3O12NodeMetadataC
+ _symbolic _____y______y_ShySSGG_____y______y______GSSGG 10Foundation20PredicateExpressionsO16SequenceContainsV AC5ValueV AC7KeyPathV AC8VariableV 25PrivateCloudComputeDaemon16AttestationStoreC8SchemaV3O13AvailableNodeC
+ _symbolic _____y______y_ShySSGG_____y______y______GSSGG 10Foundation20PredicateExpressionsO16SequenceContainsV AC5ValueV AC7KeyPathV AC8VariableV 25PrivateCloudComputeDaemon16AttestationStoreC8SchemaV3O13WorkloadEntryC
+ _symbolic _____y______y______G_____G 10Foundation20PredicateExpressionsO7KeyPathV AC8VariableV 25PrivateCloudComputeDaemon16AttestationStoreC8SchemaV3O15PrefetchStagingC AA4DateV
+ _symbolic _____y______y______G_____G 10Foundation20PredicateExpressionsO7KeyPathV AC8VariableV 25PrivateCloudComputeDaemon16AttestationStoreC8SchemaV3O16WorkloadRequestsC AA4DateV
+ _symbolic _____y______y______y______G_____G_____y_AFGG 10Foundation20PredicateExpressionsO10ComparisonV AC7KeyPathV AC8VariableV 25PrivateCloudComputeDaemon16AttestationStoreC8SchemaV3O15PrefetchStagingC AA4DateV AC5ValueV
+ _symbolic _____y______y______y______G_____G_____y_AFGG 10Foundation20PredicateExpressionsO10ComparisonV AC7KeyPathV AC8VariableV 25PrivateCloudComputeDaemon16AttestationStoreC8SchemaV3O16WorkloadRequestsC AA4DateV AC5ValueV
+ _symbolic _____y_____yx_GG 15Synchronization5MutexVAARi_zrlE 25PrivateCloudComputeDaemon8LRUCacheC5State33_87C61D947B8975B777A03B29D31BAE22LLV
+ _symbolic _____y_____yxq_q0_q1_q2__GG 15Synchronization5MutexVAARi_zrlE 25PrivateCloudComputeDaemon14RequestMetricsC5StateV
+ _symbolic _____yxq_G 25PrivateCloudComputeDaemon03TC2D4HostC
- ___swift_closure_destructor.203Tm
- ___swift_closure_destructor.210Tm
- ___swift_closure_destructor.21Tm
- ___swift_closure_destructor.276Tm
- ___swift_closure_destructor.27Tm
- ___swift_closure_destructor.280Tm
- ___swift_closure_destructor.7Tm
- ___swift_exist.box.addr_destructor.188Tm
- _get_type_metadata 15Synchronization5MutexVy25PrivateCloudComputeDaemon15PrefetchTrackerC5State33_E9F266A563EA29D0CE87FEC1DE9EC499LLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy25PrivateCloudComputeDaemon19NWConnectionWrapperC5State33_AAD96BAECD7A08EB51C0CA8D96E1D843LLOG noncopyable
- _get_type_metadata 15Synchronization5MutexVy25PrivateCloudComputeDaemon22IncomingUserDataReaderC5StateOG noncopyable
- _get_type_metadata 15Synchronization5MutexVy25PrivateCloudComputeDaemon22OutgoingUserDataWriterC12StateMachine33_6A13CE7E13BCD3AF38FC3DDBF6410D8DLLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy25PrivateCloudComputeDaemon25ServerDrivenConfigurationC9JsonModelVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy25PrivateCloudComputeDaemon28TrustedRequestProgressReaderC5StateOG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDy25PrivateCloudComputeDaemon16TC2ResolvedSetupVAD21TrustedRequestFactoryCy0cdE020DefaultConfigurationVAD17NWAsyncConnectionVAD22LegacyAttestationStoreCAD08DeferredrS0CAD0R8VerifierVyAI18FeatureFlagCheckerV0dR012MuxValidatorVGAD0T11RateLimiterCAD012ServerDrivenN0CAD10SystemInfoVAD013TokenProviderL0VyAkUA1_A3_GAUs15ContinuousClockVGGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySay25PrivateCloudComputeDaemon25ServerDrivenConfigurationC9JsonModelV16FeatureIdMappingVGSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVySo12NSFileHandleCSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVySo14NSUserDefaultsCG noncopyable
- _get_type_metadata 15Synchronization6AtomicVySbG noncopyable
- _get_type_metadata 19PrivateCloudCompute18IdentifierSequenceV noncopyable
- _get_type_metadata 25PrivateCloudComputeDaemon18SystemInfoProtocolRzl15Synchronization5MutexVySayAA22TrustedRequestXPCProxyCGG noncopyable
- _get_type_metadata 25PrivateCloudComputeDaemon19RateLimiterProtocolRzAA038DeviceQuotaConfigurationFetcherWrapperG0R_s8SendableR_0abC00J0R0_AE018FeatureFlagCheckerG0R1_AA021NotificationsProducerG0R2_r3_l15Synchronization5MutexVySDy10Foundation4UUIDVScTyyts5Error_pGGG noncopyable
- _get_type_metadata 25PrivateCloudComputeDaemon30OutgoingUserDataWriterProtocolRzAA08Incomingfg6ReaderI0R_AA024NWAsyncConnectionFactoryI0R0_AA022LegacyAttestationStoreI0R1_AA0pqI0R2_AA0p8VerifierI0R3_AA011RateLimiterI0R4_AA010SystemInfoI0R5_AA013TokenProviderI0R6_0abC0018FeatureFlagCheckerI0R7_AK30AppleIntelligenceEventReporterR8_s5ClockR9_s8DurationVAORt9_r10_l15Synchronization5MutexVySiSgG noncopyable
- _get_type_metadata SeRzSERzSHRzs8SendableRzl15Synchronization5MutexVy25PrivateCloudComputeDaemon8LRUCacheC5State33_87C61D947B8975B777A03B29D31BAE22LLVyx_GG noncopyable
- _get_type_metadata s5ClockRz25PrivateCloudComputeDaemon30LegacyAttestationStoreProtocolR_AB0ghI0R0_AB010SystemInfoI0R1_AB013BiomeReporterI0R2_s8DurationVAGRtzr3_l15Synchronization5MutexVyAB14RequestMetricsC5StateVyxq_q0_q1_q2__GG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic 8Duration_____Qy8_ s5ClockP
- _symbolic SDy__________y_________________________y__________G____________________yAchlMGAH_____GG 25PrivateCloudComputeDaemon16TC2ResolvedSetupV AA21TrustedRequestFactoryC 0abC020DefaultConfigurationV AA17NWAsyncConnectionV AA22LegacyAttestationStoreC AA08DeferredpQ0C AA0P8VerifierV AF18FeatureFlagCheckerV 0bP012MuxValidatorV AA0R11RateLimiterC AA012ServerDrivenL0C AA10SystemInfoV AA013TokenProviderJ0V s15ContinuousClockV
- _symbolic Say_____4node_SSSg4udidtG 25PrivateCloudComputeDaemon022ValidatedAttestationOrF0O
- _symbolic _____4node_SSSg4udidt 25PrivateCloudComputeDaemon022ValidatedAttestationOrF0O
- _symbolic _____ySDy__________y_________________________y__________G____________________yAdimNGAI_____GGG 15Synchronization5MutexVAARi_zrlE 25PrivateCloudComputeDaemon16TC2ResolvedSetupV AD21TrustedRequestFactoryC 0cdE020DefaultConfigurationV AD17NWAsyncConnectionV AD22LegacyAttestationStoreC AD08DeferredrS0C AD0R8VerifierV AI18FeatureFlagCheckerV 0dR012MuxValidatorV AD0T11RateLimiterC AD012ServerDrivenN0C AD10SystemInfoV AD013TokenProviderL0V s15ContinuousClockV
- _symbolic _____y_____4node_SSSg4udidtG s23_ContiguousArrayStorageC 25PrivateCloudComputeDaemon022ValidatedAttestationOrI0O
- _symbolic _____y_____G 25PrivateCloudComputeDaemon03TC2D4HostC AA10SystemInfoV
- _symbolic _____y_____GSgXw 25PrivateCloudComputeDaemon03TC2D4HostC AA10SystemInfoV
- _symbolic _____y_________________________y__________G____________________yAbgkLGAG_____G 25PrivateCloudComputeDaemon21TrustedRequestFactoryC 0abC020DefaultConfigurationV AA17NWAsyncConnectionV AA22LegacyAttestationStoreC AA08DeferredmN0C AA0M8VerifierV AD18FeatureFlagCheckerV 0bM012MuxValidatorV AA0O11RateLimiterC AA012ServerDrivenI0C AA10SystemInfoV AA013TokenProviderG0V s15ContinuousClockV
- _symbolic _____y__________y_________________________y__________G____________________yAdimNGAI_____GG s18_DictionaryStorageC 25PrivateCloudComputeDaemon16TC2ResolvedSetupV AC21TrustedRequestFactoryC 0cdE020DefaultConfigurationV AC17NWAsyncConnectionV AC22LegacyAttestationStoreC AC08DeferredrS0C AC0R8VerifierV AH18FeatureFlagCheckerV 0dR012MuxValidatorV AC0T11RateLimiterC AC012ServerDrivenN0C AC10SystemInfoV AC013TokenProviderL0V s15ContinuousClockV
- _symbolic _____yxG 25PrivateCloudComputeDaemon03TC2D4HostC
CStrings:
+ "\n    preSelectedInlineAttestationIndices: "
+ "%s Sending open request payload message on data stream. Remaining budget before ready for more chunks: %ld, message=%s"
+ "%s couldn't extract udid from inline attestation, failing request, cancelling other node streams, error=%@"
+ "%s inline nodes ready for full validation and use, totalReceived=%ld, selected=%ld"
+ "%s node was not pre-selected, index=%ld"
+ "%s node was pre-selected, index=%ld"
+ "FailedToExtractAttestationUDID"
+ "MissingAttestationUDID"
+ "ignoring addRateLimit: unavailable before first unlock"
+ "ignoring knownRateLimits: unavailable before first unlock"
+ "ignoring listRateLimits: unavailable before first unlock"
+ "ignoring prefetch request: unavailable before first unlock"
+ "ignoring prewarm request: unavailable before first unlock"
+ "ignoring resetRateLimits: unavailable before first unlock"
- "%s Failed to extract UDID for inline node: %@"
- "%s Sending open request payload message on data stream. Remaining budget before ready for more chunks: %ld"
- "%s UDID is nil for inline node %s"
- "%s V3 random validation: selected 1 of %ld inline attestations for full validation"
- "%s attestation validation did not return a unique device id for attestation: %s"
- "%s unique identifier for attestation %s missing"
- "missing validatedAttestation.udid"
```
