## remoteappintentsd

> `/usr/libexec/remoteappintentsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x79990` | `0x7630c` | **`-0x3684`** |
| `__DATA_CONST.__const` | `0x39b8` | `0x3548` | **`-0x470`** |
| `__TEXT.__unwind_info` | `0x2028` | `0x2330` | **`+0x308`** |
| `__TEXT.__swift5_capture` | `0x13a4` | `0x11f0` | **`-0x1b4`** |
| `__TEXT.__eh_frame` | `0x6080` | `0x5ef0` | **`-0x190`** |
| `__TEXT.__objc_methname` | `0x1575` | `0x13f5` | **`-0x180`** |
| `__TEXT.__objc_stubs` | `0xdc0` | `0xc40` | **`-0x180`** |
| `__TEXT.__cstring` | `0x13bd` | `0x12cd` | **`-0xf0`** |
| `__TEXT.__auth_stubs` | `0x2c10` | `0x2b30` | **`-0xe0`** |
| `__TEXT.__const` | `0x2458` | `0x23a8` | **`-0xb0`** |
| `__TEXT.__oslogstring` | `0x1d9a` | `0x1cea` | **`-0xb0`** |
| `__DATA_CONST.__auth_ptr` | `0xb68` | `0xae8` | **`-0x80`** |
| `__TEXT.__swift5_typeref` | `0x15ca` | `0x1554` | **`-0x76`** |
| `__DATA_CONST.__auth_got` | `0x1610` | `0x15a0` | **`-0x70`** |
| `__DATA.__objc_selrefs` | `0x4c0` | `0x460` | **`-0x60`** |
| `__DATA.__data` | `0x2430` | `0x23f0` | **`-0x40`** |
| `__DATA_CONST.__got` | `0x820` | `0x7e8` | **`-0x38`** |
| `__DATA.__common` | `0x3a8` | `0x378` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0xf8c` | `0xf70` | **`-0x1c`** |
| `__TEXT.__swift_as_cont` | `0x3fc` | `0x3e8` | **`-0x14`** |
| `__TEXT.__objc_methtype` | `0x655` | `0x645` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xa48` | `0xa38` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x8e4` | `0x8d4` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x2a8` | `0x298` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x2dc` | `0x2d0` | **`-0xc`** |
| `__TEXT.__swift5_types` | `0xe8` | `0xe4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-41.1.9.0.0
+41.1.10.0.0

-  - /System/Library/Frameworks/CoreSpotlight.framework/CoreSpotlight

-  Functions: 2787
-  Symbols:   1136
-  CStrings:  570
+  Functions: 2710
+  Symbols:   1111
+  CStrings:  547
Symbols:
+ _$s18AppIntentsServices0A19DescriptionExecutorO19describeApplication3forAA0aD0VAA0A10IdentifierV_tYaKFZ
+ _$s18AppIntentsServices0A19DescriptionExecutorO19describeApplication3forAA0aD0VAA0A10IdentifierV_tYaKFZTu
+ _$s18AppIntentsServices0aB8ProtocolO13PerformActionO7RequestV7OptionsV25lnConnectionPolicySignalsSo012LNConnectionkL0Cvg
+ _$sSo18LNConnectionPolicyC12LinkServicesE6policy3for7signalsSo021LNAppEntityConnectionB0CSo16LNEntityMetadataC_So0aB7SignalsCSgtKFZ
- _$s18AppIntentsServices06RemoteaB5ActorC16DelegateProtocolP14spotlightQuery_4peerAA0abG0O09SpotlightI0O8ResponseVAK7RequestV_7Network11NWActorPeer_ptYaKFTq
- _$s18AppIntentsServices0A16EntityIdentifierMp
- _$s18AppIntentsServices0A19DescriptionExecutorO19describeApplication3forAA0aD0VAA0A10IdentifierV_tKFZ
- _$s18AppIntentsServices0aB8ProtocolO13PerformActionO7RequestV7OptionsV25preferredBundleIdentifierSSSgvg
- _$s18AppIntentsServices0aB8ProtocolO14SpotlightQueryO7RequestV04userF0SSSgvg
- _$s18AppIntentsServices0aB8ProtocolO14SpotlightQueryO7RequestV15useManagedIndexSbvg
- _$s18AppIntentsServices0aB8ProtocolO14SpotlightQueryO7RequestV3appAA0A10IdentifierVvg
- _$s18AppIntentsServices0aB8ProtocolO14SpotlightQueryO7RequestVMa
- _$s18AppIntentsServices0aB8ProtocolO14SpotlightQueryO7RequestVMn
- _$s18AppIntentsServices0aB8ProtocolO14SpotlightQueryO8ResponseV17entityIdentifiersAGSayAA0A16EntityIdentifier_pG_tcfC
- _$s18AppIntentsServices0aB8ProtocolO14SpotlightQueryO8ResponseVMa
- _$s18AppIntentsServices0aB8ProtocolO14SpotlightQueryO8ResponseVMn
- _$sSS10describingSSx_tclufC
- _$sScI4next7ElementQzSgyYaKFTj
- _$sScI4next7ElementQzSgyYaKFTjTu
- _$sSo13CSSearchQueryC13CoreSpotlightE7ResultsV17makeAsyncIteratorAE0H0VyF
- _$sSo13CSSearchQueryC13CoreSpotlightE7ResultsV4ItemV4itemSo012CSSearchableF0Cvg
- _$sSo13CSSearchQueryC13CoreSpotlightE7ResultsV4ItemVMa
- _$sSo13CSSearchQueryC13CoreSpotlightE7ResultsV4ItemVMn
- _$sSo13CSSearchQueryC13CoreSpotlightE7ResultsV8IteratorVMa
- _$sSo13CSSearchQueryC13CoreSpotlightE7ResultsV8IteratorVScIACMc
- _$sSo13CSSearchQueryC13CoreSpotlightE7ResultsVMa
- _$sSo13CSSearchQueryC13CoreSpotlightE7resultsAbCE7ResultsVvg
- _$sSo18LNEntityIdentifierC18AppIntentsServices0c6EntityB0ACMc
- _OBJC_CLASS_$_CSSearchQuery
- _OBJC_CLASS_$_CSSearchQueryContext
- _OBJC_CLASS_$_LNConnectionPolicySignals
- _OBJC_CLASS_$_LNEntityIdentifier
- _swift_willThrowTypedImpl
CStrings:
- "%sCompleted with %s results"
- "%sConstructed query: %s"
- "%sPerforming %ld queries"
- "%sQuery failed: %s"
- "%sSearching Spotlight for userQuery=%s in %s"
- "AppIntentsTestKit"
- "Failed to query donated entities: "
- "Querying donated entities via remote execution for "
- "_kMDItemAppEntityInstanceIdentifier"
- "_kMDItemAppEntityTypeIdentifier"
- "appEntityInstanceId"
- "appEntityType"
- "attributeSet"
- "initWithQueryString:queryContext:"
- "initWithTypeIdentifier:instanceIdentifier:"
- "policyWithActionMetadata:"
- "policyWithActionMetadata:signals:schemaVersion:"
- "policyWithEntityMetadata:"
- "setBundleIDs:"
- "setFetchAttributes:"
- "setPreferredBundleIdentifier:"
- "setReason:"
- "spotlightQuery"
```
