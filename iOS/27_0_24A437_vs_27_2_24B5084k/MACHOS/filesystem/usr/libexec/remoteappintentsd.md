## remoteappintentsd

> `/usr/libexec/remoteappintentsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x744c8` | `0x79990` | **`+0x54c8`** |
| `__TEXT.__eh_frame` | `0x5940` | `0x6080` | **`+0x740`** |
| `__TEXT.__unwind_info` | `0x1e28` | `0x2028` | **`+0x200`** |
| `__DATA.__data` | `0x2258` | `0x2430` | **`+0x1d8`** |
| `__TEXT.__auth_stubs` | `0x2ac0` | `0x2c10` | **`+0x150`** |
| `__TEXT.__const` | `0x2308` | `0x2458` | **`+0x150`** |
| `__DATA_CONST.__const` | `0x3870` | `0x39b8` | **`+0x148`** |
| `__DATA.__bss` | `0xe00` | `0xf00` | **`+0x100`** |
| `__TEXT.__swift5_typeref` | `0x14ea` | `0x15ca` | **`+0xe0`** |
| `__DATA_CONST.__auth_got` | `0x1568` | `0x1610` | **`+0xa8`** |
| `__TEXT.__constg_swiftt` | `0xf08` | `0xf8c` | **`+0x84`** |
| `__DATA_CONST.__auth_ptr` | `0xaf0` | `0xb68` | **`+0x78`** |
| `__TEXT.__swift5_capture` | `0x132c` | `0x13a4` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x9ec` | `0xa48` | **`+0x5c`** |
| `__TEXT.__swift_as_cont` | `0x3a0` | `0x3fc` | **`+0x5c`** |
| `__DATA_CONST.__got` | `0x7d0` | `0x820` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x1535` | `0x1575` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x8a4` | `0x8e4` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x2a0` | `0x2dc` | **`+0x3c`** |
| `__TEXT.__cstring` | `0x1388` | `0x13bd` | **`+0x35`** |
| `__DATA.__objc_const` | `0x1628` | `0x1648` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xda0` | `0xdc0` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x288` | `0x2a8` | **`+0x20`** |
| `__DATA.__common` | `0x390` | `0x3a8` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x1d8a` | `0x1d9a` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x4b8` | `0x4c0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x9c` | `0xa4` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xe0` | `0xe8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-41.0.50.0.0
+41.1.9.0.0

-  Functions: 2665
-  Symbols:   1101
-  CStrings:  566
+  Functions: 2787
+  Symbols:   1136
+  CStrings:  570
Symbols:
+ _$s18AppIntentsServices06RemoteaB5ActorC16DelegateProtocolP13prewarmIntent_4peerAA0abG0O07PrewarmI0O8ResponseOAK7RequestV_7Network11NWActorPeer_ptYaFTq
+ _$s18AppIntentsServices0A19IntentSpecificationV11description7privacySSAA0bC0O14PayloadPrivacyO_tF
+ _$s18AppIntentsServices0A19IntentSpecificationV13schemaVersionAA06SchemaG0VSgvg
+ _$s18AppIntentsServices0aB8ProtocolO13PrewarmIntentO7RequestV13specificationAA0aF13SpecificationVvg
+ _$s18AppIntentsServices0aB8ProtocolO13PrewarmIntentO7RequestV15requestMetadataAA0gI0Vvg
+ _$s18AppIntentsServices0aB8ProtocolO13PrewarmIntentO7RequestVMa
+ _$s18AppIntentsServices0aB8ProtocolO13PrewarmIntentO7RequestVMn
+ _$s18AppIntentsServices0aB8ProtocolO13PrewarmIntentO8ResponseO5erroryAGSo7NSErrorCcAGmFWC
+ _$s18AppIntentsServices0aB8ProtocolO13PrewarmIntentO8ResponseO7successyA2GmFWC
+ _$s18AppIntentsServices0aB8ProtocolO13PrewarmIntentO8ResponseOMa
+ _$s18AppIntentsServices0aB8ProtocolO13PrewarmIntentO8ResponseOMn
+ _$s18AppIntentsServices0bC0O14NetworkOptionsV13internetRelayA2E08InternetG4ModeO_tcfC
+ _$s18AppIntentsServices0bC0O14NetworkOptionsV17InternetRelayModeO7enabledyA2GmFWC
+ _$s18AppIntentsServices0bC0O14NetworkOptionsV17InternetRelayModeOMa
+ _$s18AppIntentsServices0bC0O14NetworkOptionsVMa
+ _$s18AppIntentsServices22ASQUICRapportTransportV14networkOptions4userAcA0bC0O07NetworkG0V_AA12UserInternalVtcfC
+ _$s18AppIntentsServices22ASQUICRapportTransportVAA07NetworkE9ProvidingAAMc
+ _$s18AppIntentsServices22ASQUICRapportTransportVMa
+ _$s18AppIntentsServices22ASQUICRapportTransportVs23CustomStringConvertibleAAMc
+ _$s18AppIntentsServices23ASQUICTerminusTransportV14networkOptions4userAcA0bC0O07NetworkG0V_AA12UserInternalVtcfC
+ _$s18AppIntentsServices23ASQUICTerminusTransportVs23CustomStringConvertibleAAMc
+ _$s18AppIntentsServices25NetworkTransportProvidingP10attributesAA0dE10AttributesVvgTj
+ _$s18AppIntentsServices25NetworkTransportProvidingP15listenerService0D010NWListenerC0H0VvgTj
+ _$s18AppIntentsServices25NetworkTransportProvidingP22makeListenerParameters13applicationID0D012NWParametersCAF013NWApplicationK0V_tFTj
+ _$s18AppIntentsServices26NetworkTransportAttributesV2eeoiySbAC_ACtFZ
+ _$s18AppIntentsServices26NetworkTransportAttributesVSHAAMc
+ _$s18AppIntentsServices30RemoteBundleIdentifierRemapperC08resolvedA0yAA0aF0VAFYaKF
+ _$s18AppIntentsServices30RemoteBundleIdentifierRemapperC08resolvedA0yAA0aF0VAFYaKFTu
+ _$s18AppIntentsServices30RemoteBundleIdentifierRemapperC08resolvedF03forS2S_tYaKF
+ _$s18AppIntentsServices30RemoteBundleIdentifierRemapperC08resolvedF03forS2S_tYaKFTu
+ _$s18AppIntentsServices30RemoteBundleIdentifierRemapperC6sharedACvgZ
+ _$s18AppIntentsServices30RemoteBundleIdentifierRemapperCMa
+ _$s18AppIntentsServices5TasksO5after_7closureScTyyts5NeverOGs8DurationV_yyYbctFZ
+ _$s7Network21NWActorSystemDelegateP16inboundWorkBegan6workIDy10Foundation4UUIDV_tFTq
+ _$s7Network21NWActorSystemDelegateP16inboundWorkEnded6workIDy10Foundation4UUIDV_tFTq
+ _$s7Network21NWActorSystemDelegatePAAE16inboundWorkBegan6workIDy10Foundation4UUIDV_tF
+ _$s7Network21NWActorSystemDelegatePAAE20didExecuteRemoteCall6callID6targety10Foundation4UUIDV_SStF
+ _$s7Network21NWActorSystemDelegatePAAE21willExecuteRemoteCall6callID6targety10Foundation4UUIDV_SStF
+ _$sScTMa
+ _$sSo18LNConnectionPolicyC12LinkServicesE6policy3for7signals13schemaVersionSo021LNAppIntentConnectionB0CSo16LNActionMetadataC_So0aB7SignalsCSgSo08LNSchemaI0CSgtKFZ
+ _swift_getDynamicType
- _$s18AppIntentsServices17NetworkTransportsO25preferredRapportTransportAA0dH9Providing_pXpvgZ
- _$s18AppIntentsServices25NetworkTransportProvidingP15listenerService0D010NWListenerC0H0VvgZTj
- _$s18AppIntentsServices25NetworkTransportProvidingP22makeListenerParameters13applicationID0D012NWParametersCAF013NWApplicationK0V_tFZTj
- _$s18AppIntentsServices25NetworkTransportProvidingP4userxAA12UserInternalV_tcfCTj
- _$s18AppIntentsServices25NetworkTransportProvidingPAAE10attributesAA0dE10AttributesVvg
- _swift_getMetatypeMetadata
CStrings:
+ "%sLong running operation completed, but no transaction found for %s"
+ "%sLong running operation completed, released transaction %s"
+ "%sLong running operation will start, creating transaction %s"
+ "NWActorCall_legacy"
+ "prewarm-keep-alive."
+ "prewarmAppIntent"
+ "prewarmKeepAlives"
+ "prewarmWithCompletionHandler:"
- "%sLong running operation %s completed, released transaction"
- "%sLong running operation %s(%s) will start, requesting transaction"
- "%sNo transaction found for operation %s"
- "ASQUICTerminusTransport"
```
