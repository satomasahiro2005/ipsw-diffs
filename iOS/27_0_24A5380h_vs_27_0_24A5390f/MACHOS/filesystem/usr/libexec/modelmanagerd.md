## modelmanagerd

> `/usr/libexec/modelmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b4730` | `0x1b4d3c` | **`+0x60c`** |
| `__TEXT.__auth_stubs` | `0x3da0` | `0x3e40` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x82d8` | `0x8260` | **`-0x78`** |
| `__DATA_CONST.__auth_got` | `0x1ed8` | `0x1f28` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x9e69` | `0x9e99` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x2504` | `0x24d4` | **`-0x30`** |
| `__TEXT.__eh_frame` | `0x16514` | `0x164ec` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x6c98` | `0x6cc0` | **`+0x28`** |
| `__DATA.__data` | `0x6378` | `0x6398` | **`+0x20`** |
| `__TEXT.__const` | `0x67b6` | `0x67d6` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0xd38` | `0xd50` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x2861` | `0x2879` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xf30` | `0xf40` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x25b3` | `0x25c3` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x21a8` | `0x21b4` | **`+0xc`** |
| `__TEXT.__constg_swiftt` | `0x2d5c` | `0x2d64` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x121c` | `0x1218` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0xad0` | `0xacc` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-703.0.11.0.0
+703.0.21.502.1

-  Functions: 9078
-  Symbols:   1681
-  CStrings:  1214
+  Functions: 9074
+  Symbols:   1696
+  CStrings:  1215
Symbols:
+ _$s12ModelCatalog0B8ResourceP12resourceTypeSSvgTj
+ _$s20ModelManagerServices0aB5ErrorO027underlyingInferenceProviderD0SS6domain_Si4codetSgvg
+ _$s20ModelManagerServices0aB5ErrorO28inferenceProviderTerminatingyA2CmFWC
+ _$s20ModelManagerServices15RequestMetadataV17loggingIdentifier10clientData4UUID9sessionID16requiredAssetIDs21excludedResourceTypes11isInference0S6Stream0s5InputU0010subrequestL003allV8Streamed07useCaseL0ACSS_AA06ClientI0V10FoundationAFVAA14UUIDIdentifierVyAA7SessionCGShySSGSgAZS3bs6UInt32VSbSStcfC
+ _$s20ModelManagerServices15RequestMetadataV17loggingIdentifier10clientData4UUID9sessionID16requiredAssetIDs21excludedResourceTypes11isInference0S6Stream0s5InputU0010subrequestL003allV8Streamed07useCaseL0ACSS_AA06ClientI0V10FoundationAFVAA14UUIDIdentifierVyAA7SessionCGShySSGSgAZS3bs6UInt32VSbSStcfcfA7_
+ _$s20ModelManagerServices15RequestMetadataV17loggingIdentifier10clientData4UUID9sessionID16requiredAssetIDs21excludedResourceTypes11isInference0S6Stream0s5InputU0010subrequestL003allV8Streamed07useCaseL0ACSS_AA06ClientI0V10FoundationAFVAA14UUIDIdentifierVyAA7SessionCGShySSGSgAZS3bs6UInt32VSbSStcfcfA8_
+ _$s20ModelManagerServices15RequestMetadataV17loggingIdentifier10clientData4UUID9sessionID16requiredAssetIDs21excludedResourceTypes11isInference0S6Stream0s5InputU0010subrequestL003allV8Streamed07useCaseL0ACSS_AA06ClientI0V10FoundationAFVAA14UUIDIdentifierVyAA7SessionCGShySSGSgAZS3bs6UInt32VSbSStcfcfA9_
+ _$s20ModelManagerServices15RequestMetadataV21excludedResourceTypesShySSGSgvg
+ _$s20ModelManagerServices17PriorityWorkQueueV15runBlockAndWait11description10isolatedTo7performqd__SS_xYiqd__yYaqd_0_YKctYaqd_0_YKs8SendableRd__s5ErrorRd_0_r0_lF
+ _$s20ModelManagerServices17PriorityWorkQueueV15runBlockAndWait11description10isolatedTo7performqd__SS_xYiqd__yYaqd_0_YKctYaqd_0_YKs8SendableRd__s5ErrorRd_0_r0_lFTu
+ _$s20ModelManagerServices17PriorityWorkQueueVACyxGycfC
+ _$s20ModelManagerServices17PriorityWorkQueueVMa
+ _$s20ModelManagerServices17PriorityWorkQueueVMn
+ _$s20ModelManagerServices20PrewarmConfigurationV16requiredAssetIDs21excludedResourceTypes8metadata17requestClientDataACShySSGSg_AISDyS2SGSgAA0nO0VSgtcfC
+ _$s20ModelManagerServices20PrewarmConfigurationV21excludedResourceTypesShySSGSgvg
+ _$s26AppleIntelligenceReporting0aB14InferenceEventV9subsystem17sessionIdentifier04stepH0017invocationRequestH006clientkH0012modelManagerkH06errors07useCaseH0013additionalUseQ11Identifiers015requestorBundleH0010onBehalfOfvH0017inferenceProviderH005assetvH06assets8metadata11spanContext9timestamp18monotonicTimestamp19underlyingErrorCode21underlyingErrorDomain15routingDecisionACSS_10Foundation4UUIDVSgSSSgAA14UUIDIdentifierVSgA0_A0_SayAA0aB5Error_pGAA0absQ0VSgSayA8_GA1_A1_A1_A1_SayAA0aB5AssetVGAA0abC8MetadataOSgAA0abC11SpanContextVSgAY4DateVSg0B15PlatformLibrary18MonotonicTimestampVSgSiSgA1_A1_tcfC
+ _$s26AppleIntelligenceReporting0abC11SpanContextVMa
+ _$s26AppleIntelligenceReporting0abC11SpanContextVMn
+ _$s27IntelligencePlatformLibrary18MonotonicTimestampVMa
+ _$s27IntelligencePlatformLibrary18MonotonicTimestampVMn
- _$s20ModelManagerServices15RequestMetadataV17loggingIdentifier10clientData4UUID9sessionID16requiredAssetIDs11isInference0P6Stream0p5InputR0010subrequestL003allS8Streamed07useCaseL0ACSS_AA06ClientI0V10FoundationAFVAA14UUIDIdentifierVyAA7SessionCGShySSGSgS3bs6UInt32VSbSStcfC
- _$s20ModelManagerServices15RequestMetadataV17loggingIdentifier10clientData4UUID9sessionID16requiredAssetIDs11isInference0P6Stream0p5InputR0010subrequestL003allS8Streamed07useCaseL0ACSS_AA06ClientI0V10FoundationAFVAA14UUIDIdentifierVyAA7SessionCGShySSGSgS3bs6UInt32VSbSStcfcfA6_
- _$s20ModelManagerServices15RequestMetadataV17loggingIdentifier10clientData4UUID9sessionID16requiredAssetIDs11isInference0P6Stream0p5InputR0010subrequestL003allS8Streamed07useCaseL0ACSS_AA06ClientI0V10FoundationAFVAA14UUIDIdentifierVyAA7SessionCGShySSGSgS3bs6UInt32VSbSStcfcfA7_
- _$s20ModelManagerServices15RequestMetadataV17loggingIdentifier10clientData4UUID9sessionID16requiredAssetIDs11isInference0P6Stream0p5InputR0010subrequestL003allS8Streamed07useCaseL0ACSS_AA06ClientI0V10FoundationAFVAA14UUIDIdentifierVyAA7SessionCGShySSGSgS3bs6UInt32VSbSStcfcfA8_
- _$s20ModelManagerServices20PrewarmConfigurationV16requiredAssetIDs8metadata17requestClientDataACShySSGSg_SDyS2SGSgAA0kL0VSgtcfC
CStrings:
+ "Excluding resource types %s; asset set now: %s"
```
