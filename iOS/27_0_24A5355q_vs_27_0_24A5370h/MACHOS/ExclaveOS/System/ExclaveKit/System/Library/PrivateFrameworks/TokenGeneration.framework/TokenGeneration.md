## TokenGeneration

> `/System/ExclaveKit/System/Library/PrivateFrameworks/TokenGeneration.framework/TokenGeneration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf374` | `0x10ce4` | **`+0x1970`** |
| `__TEXT.__cstring` | `0xe78` | `0xfe8` | **`+0x170`** |
| `__TEXT.__auth_stubs` | `0xce0` | `0xd90` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x18b` | `0x1fb` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0x670` | `0x6c8` | **`+0x58`** |
| `__DATA_CONST.__got` | `0x150` | `0x198` | **`+0x48`** |
| `__TEXT.__const` | `0x908` | `0x928` | **`+0x20`** |
| `__DATA.__data` | `0x7d8` | `0x7f0` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x4e8` | `0x500` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x3bc` | `0x3ca` | **`+0xe`** |
| `__DATA_CONST.__auth_ptr` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x510` | `0x508` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-289.0.15.0.0
+294.0.7.0.0

-  Symbols:   1173
-  CStrings:  75
+  Symbols:   1204
+  CStrings:  84
Symbols:
+ _$s15TokenGeneration0aB5ErrorO13abuseRejectedyAC29GenerativeFunctionsFoundation0fC0V06PromptC0V0C4TypeO05AbuseeC4InfoV_AC7ContextVtcACmFWC
+ _$s15TokenGeneration0aB5ErrorO4CodeO13abuseRejectedyA2EmFWC
+ _$s19TokenGenerationCore0aB13InferenceDataO7requestyAcA0aB7RequestOcACmFWC
+ _$s19TokenGenerationCore0aB13InferenceDataO8responseyAcA0aB8ResponseOcACmFWC
+ _$s19TokenGenerationCore0aB13InferenceDataOMa
+ _$s19TokenGenerationCore0aB7RequestO14completePromptyAC0aB008CompletefD0VcACmFWC
+ _$s19TokenGenerationCore0aB7RequestOMa
+ _$s19TokenGenerationCore0aB8ResponseO14completePromptyAC0aB008CompletefD0VcACmFWC
+ _$s19TokenGenerationCore0aB8ResponseOMa
+ _$s27ModelManagerExclaveServices0C13InferenceDataO15tokenGenerationyAcA15SendablePayloadVcACmFWC
+ _$s27ModelManagerExclaveServices0C13InferenceDataOMa
+ _$s27ModelManagerExclaveServices0C14InferenceErrorOMa
+ _$s27ModelManagerExclaveServices0C14InferenceErrorOs0F0AAWP
+ _$s27ModelManagerExclaveServices0C14OneShotRequestC7executeAA0C13InferenceDataOyKF
+ _$s27ModelManagerExclaveServices0C14OneShotRequestC7session4dataAcA0C7SessionC_AA0C13InferenceDataOtcfc
+ _$s27ModelManagerExclaveServices0C14OneShotRequestCMa
+ _$s27ModelManagerExclaveServices0caB5ErrorOs0E0AAWP
+ _$s27ModelManagerExclaveServices15SendablePayloadV5valueypvg
+ _$s27ModelManagerExclaveServices15SendablePayloadVMa
+ _$s27ModelManagerExclaveServices15SendablePayloadVyACypcfC
+ _$s29GenerativeFunctionsFoundation0A5ErrorV06PromptD0V0D4TypeO013AbuseRejectedD4InfoVMa
+ _$s29GenerativeFunctionsFoundation0A5ErrorV06PromptD0V0D4TypeO013AbuseRejectedD4InfoVMn
+ _$s29GenerativeFunctionsFoundation0A5ErrorV06PromptD0V0D4TypeO013AbuseRejectedD4InfoV_15TokenGeneration0jkD0O7ContextVtML
+ _$s29GenerativeFunctionsFoundation0A5ErrorV06PromptD0V0D4TypeO013AbuseRejectedD4InfoV_15TokenGeneration0jkD0O7ContextVtMR
+ _$s29GenerativeFunctionsFoundation0A5ErrorV06PromptD0V0D4TypeO013AbuseRejectedD4InfoV_15TokenGeneration0jkD0O7ContextVtMd
+ _$ss5Error_pMR
+ _$ss5Error_pMd
+ _$sypN
+ ___swift_allocate_boxed_opaque_existential_0
+ ___swift_project_boxed_opaque_existential_0
+ _swift_getDynamicType
+ _symbolic ___________t 29GenerativeFunctionsFoundation0A5ErrorV06PromptD0V0D4TypeO013AbuseRejectedD4InfoV 15TokenGeneration0jkD0O7ContextV
- _$sSo13os_log_type_ta0A0E5debugABvgZ
CStrings:
+ "An error explaining that the request was rejected by the abuse guardrail."
+ "CompletePromptResponse"
+ "ExclaveInferenceData"
+ "Failed to resolve model bundle %s: %{private}s"
+ "ModelManagerSession executing ExclaveOneShotRequest"
+ "Received response of unsupported type, expected "
+ "Received response of unsupported type, expected tokenGeneration but got "
+ "Request execution failed: "
+ "The request was rejected by the abuse guardrail"
+ "TokenGenerationResponse"
- "Not implemented yet"
```
