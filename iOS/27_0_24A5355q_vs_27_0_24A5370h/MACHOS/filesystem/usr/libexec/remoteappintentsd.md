## remoteappintentsd

> `/usr/libexec/remoteappintentsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72cdc` | `0x742e8` | **`+0x160c`** |
| `__TEXT.__auth_stubs` | `0x29e0` | `0x2ad0` | **`+0xf0`** |
| `__DATA_CONST.__const` | `0x37b8` | `0x3870` | **`+0xb8`** |
| `__TEXT.__const` | `0x22d8` | `0x2368` | **`+0x90`** |
| `__DATA.__bss` | `0xd80` | `0xe00` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x1495` | `0x1515` | **`+0x80`** |
| `__DATA_CONST.__auth_got` | `0x14f8` | `0x1570` | **`+0x78`** |
| `__DATA.__data` | `0x2238` | `0x22a8` | **`+0x70`** |
| `__DATA.__objc_const` | `0x15b8` | `0x1620` | **`+0x68`** |
| `__TEXT.__constg_swiftt` | `0xea0` | `0xf08` | **`+0x68`** |
| `__DATA_CONST.__auth_ptr` | `0xa88` | `0xad8` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x9b8` | `0x9ec` | **`+0x34`** |
| `__TEXT.__swift5_typeref` | `0x14a8` | `0x14d4` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x7b8` | `0x7d8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x13f8` | `0x1418` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xd80` | `0xda0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x884` | `0x8a4` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1ed8` | `0x1ef8` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x1bba` | `0x1bca` | **`+0x10`** |
| `__DATA.__objc_data` | `0x498` | `0x4a0` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x4a8` | `0x4b0` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x5b50` | `0x5b48` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x98` | `0x9c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xdc` | `0xe0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-41.0.41.16.0
+41.0.42.6.0

-  Functions: 2712
-  Symbols:   1078
-  CStrings:  558
+  Functions: 2728
+  Symbols:   1103
+  CStrings:  562
Symbols:
+ _$s12LinkServices22LNPerformActionMetricsC7SegmentVMa
+ _$s12LinkServices22LNPerformActionMetricsC7SegmentVMn
+ _$s12LinkServices22LNPerformActionMetricsC8segmentsSayAC7SegmentVGvg
+ _$s12LinkServices22LNPerformActionMetricsC8segmentsSayAC7SegmentVGvs
+ _$s12LinkServices22LNPerformActionMetricsCMn
+ _$s18AppIntentsServices0A19IntentSpecificationV9telemetrySDySSs8Sendable_pGvg
+ _$s18AppIntentsServices0aB8ProtocolO13PerformActionO8ResponseO7successyAgA12IntentOutputVySo7LNValueCG_SS04LinkC009LNPerformF7MetricsCSgtcAGmFWC
+ _$s18AppIntentsServices15InstrumentationO19SharedTelemetryKeysO10entityTypeyA2EmFWC
+ _$s18AppIntentsServices15InstrumentationO19SharedTelemetryKeysO3appyA2EmFWC
+ _$s18AppIntentsServices15InstrumentationO19SharedTelemetryKeysO8rawValueSSvg
+ _$s18AppIntentsServices15InstrumentationO19SharedTelemetryKeysOMa
+ _$s18AppIntentsServices15InstrumentationO7SegmentV024asLNPerformActionMetricsE004LinkC00ghI0CADVvg
+ _$s18AppIntentsServices15InstrumentationO7SegmentV6HandleV3endyyF
+ _$s18AppIntentsServices15InstrumentationO7SegmentV6HandleVMa
+ _$s18AppIntentsServices15InstrumentationO7SegmentVMa
+ _$s18AppIntentsServices15InstrumentationO8ActivityC15appendTelemetryyySDySSs8Sendable_pGF
+ _$s18AppIntentsServices16ActivityProtocolP12beginSegmentyAA15InstrumentationO0G0V6HandleVs12StaticStringVFTj
+ _$s18AppIntentsServices16ActivityProtocolP8segmentsSayAA15InstrumentationO7SegmentVGvgTj
+ _$s18AppIntentsServices18QuerySpecificationO9telemetrySDySSs8Sendable_pGvg
+ _$s18AppIntentsServices19QueryRequestOptionsV22asyncSequenceThresholdSivs
+ _$s18AppIntentsServices20PerformIntentSegmentO18loadActionMetadatas12StaticStringVvgZ
+ _$s18AppIntentsServices20PerformIntentSegmentO20outputTransformations12StaticStringVvgZ
+ _$s18AppIntentsServices20PerformIntentSegmentO25createPolicyAndConnections12StaticStringVvgZ
+ _$s18AppIntentsServices29DeferredPropertyTelemetryKeysO8propertyyA2CmFWC
+ _$s18AppIntentsServices29DeferredPropertyTelemetryKeysO8rawValueSSvg
+ _$s18AppIntentsServices29DeferredPropertyTelemetryKeysOMa
+ _$s7Network13NWActorSystemC7service10parameters8delegateAcA10NWListenerC7ServiceV_AA12NWParametersCAA0bC8Delegate_pSgtcfC
+ _$s7Network21NWActorSystemDelegateMp
+ _$s7Network21NWActorSystemDelegateP19didHandleRemoteCall6callID6target13actorInstancey10Foundation4UUIDV_SS11Distributed0P5Actor_ptFTq
+ _$s7Network21NWActorSystemDelegateP20didExecuteRemoteCall6callID6targety10Foundation4UUIDV_SStFTq
+ _$s7Network21NWActorSystemDelegateP20willHandleRemoteCall6callID6target13actorInstancey10Foundation4UUIDV_SS11Distributed0P5Actor_ptFTq
+ _$s7Network21NWActorSystemDelegateP21willExecuteRemoteCall6callID6targety10Foundation4UUIDV_SStFTq
+ _$sSo15LNSuccessResultC12LinkServicesE7metricsAC22LNPerformActionMetricsCSgvg
- _$s18AppIntentsServices0A19IntentSpecificationV7metricsSDySSs8Sendable_pGvg
- _$s18AppIntentsServices0aB8ProtocolO13PerformActionO8ResponseO7successyAgA12IntentOutputVySo7LNValueCG_SStcAGmFWC
- _$s18AppIntentsServices15InstrumentationO17SharedMetricsKeysO10entityTypeSSvgZ
- _$s18AppIntentsServices15InstrumentationO17SharedMetricsKeysO3appSSvgZ
- _$s18AppIntentsServices15InstrumentationO8ActivityC10addMetricsyySDySSs8Sendable_pGF
- _$s18AppIntentsServices18QuerySpecificationO7metricsSDySSs8Sendable_pGvg
- _$s18AppIntentsServices26DeferredPropertyMetricKeysO8propertySSvgZ
- _$s7Network13NWActorSystemC7service10parametersAcA10NWListenerC7ServiceV_AA12NWParametersCtcfc
CStrings:
+ "%sLong running operation %s(%s) will start, requesting transaction"
+ "AsyncSequenceInlineThreshold"
+ "activity"
+ "actorSystemDelegate"
+ "perform(activity:intent:options:environment:executionIdentifier:peer:session:requestMetadata:systemContext:)"
+ "setAsyncSequenceThreshold:"
- "%sLong running operation %s will start, requesting transaction"
- "perform(intent:options:environment:executionIdentifier:peer:session:requestMetadata:systemContext:)"
```
