## SIDThinClient

> `/System/Library/PrivateFrameworks/SIDThinClient.framework/SIDThinClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa998` | `0x674c` | **`-0x424c`** |
| `__DATA.__bss` | `0x3080` | `0x1780` | **`-0x1900`** |
| `__TEXT.__const` | `0x1934` | `0xca4` | **`-0xc90`** |
| `__AUTH_CONST.__const` | `0xda8` | `0x6c8` | **`-0x6e0`** |
| `__TEXT.__eh_frame` | `0x6d0` | `0x418` | **`-0x2b8`** |
| `__TEXT.__swift5_typeref` | `0x457` | `0x23b` | **`-0x21c`** |
| `__AUTH.__data` | `0x1f0` | `—` | **`-0x1f0`** |
| `__TEXT.__constg_swiftt` | `0x3f0` | `0x21c` | **`-0x1d4`** |
| `__TEXT.__unwind_info` | `0x4a8` | `0x2d8` | **`-0x1d0`** |
| `__DATA.__data` | `0x398` | `0x1d8` | **`-0x1c0`** |
| `__TEXT.__swift5_fieldmd` | `0x390` | `0x1dc` | **`-0x1b4`** |
| `__DATA_DIRTY.__data` | `—` | `0x148` | **`+0x148`** |
| `__TEXT.__swift5_proto` | `0x184` | `0xbc` | **`-0xc8`** |
| `__AUTH_CONST.__objc_const` | `0x200` | `0x148` | **`-0xb8`** |
| `__TEXT.__swift5_reflstr` | `0xd3` | `0x88` | **`-0x4b`** |
| `__TEXT.__cstring` | `0xf0` | `0xbc` | **`-0x34`** |
| `__TEXT.__swift5_types` | `0x6c` | `0x38` | **`-0x34`** |
| `__TEXT.__swift_as_cont` | `0x3c` | `0x24` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x14` | **`-0x14`** |
| `__AUTH_CONST.__auth_got` | `0x2e8` | `0x2d8` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x40` | `0x30` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x18` | `0x10` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x10` | `0x8` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x18` | `0x10` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x18` | `0x10` | **`-0x8`** |

### Other Changes

```diff

-1.60.0.0.0
+1.65.0.0.0

-  Functions: 398
-  Symbols:   232
-  CStrings:  12
+  Functions: 231
+  Symbols:   167
+  CStrings:  11
Symbols:
+ _objc_release_x27
- __DATA__TtC13SIDThinClient16SIDFitnessClient
- __IVARS__TtC13SIDThinClient16SIDFitnessClient
- __METACLASS_DATA__TtC13SIDThinClient16SIDFitnessClient
- ___swift_closure_destructorTm
- ___swift_memcpy40_8
- _associated conformance 13SIDThinClient15SIDXPCTreatmentV10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOSHAASQ
- _associated conformance 13SIDThinClient15SIDXPCTreatmentV10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0D3KeyAAs23CustomStringConvertible
- _associated conformance 13SIDThinClient15SIDXPCTreatmentV10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0D3KeyAAs28CustomDebugStringConvertible
- _associated conformance 13SIDThinClient15SIDXPCTreatmentVSHAASQ
- _associated conformance 13SIDThinClient19SIDFitnessXPCResultO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOSHAASQ
- _associated conformance 13SIDThinClient19SIDFitnessXPCResultO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0E3KeyAAs23CustomStringConvertible
- _associated conformance 13SIDThinClient19SIDFitnessXPCResultO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0E3KeyAAs28CustomDebugStringConvertible
- _associated conformance 13SIDThinClient19SIDFitnessXPCResultO17FailureCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOSHAASQ
- _associated conformance 13SIDThinClient19SIDFitnessXPCResultO17FailureCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0F3KeyAAs23CustomStringConvertible
- _associated conformance 13SIDThinClient19SIDFitnessXPCResultO17FailureCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0F3KeyAAs28CustomDebugStringConvertible
- _associated conformance 13SIDThinClient19SIDFitnessXPCResultO17SuccessCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOSHAASQ
- _associated conformance 13SIDThinClient19SIDFitnessXPCResultO17SuccessCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0F3KeyAAs23CustomStringConvertible
- _associated conformance 13SIDThinClient19SIDFitnessXPCResultO17SuccessCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0F3KeyAAs28CustomDebugStringConvertible
- _associated conformance 13SIDThinClient20SIDFitnessXPCRequestO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOSHAASQ
- _associated conformance 13SIDThinClient20SIDFitnessXPCRequestO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0E3KeyAAs23CustomStringConvertible
- _associated conformance 13SIDThinClient20SIDFitnessXPCRequestO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0E3KeyAAs28CustomDebugStringConvertible
- _associated conformance 13SIDThinClient20SIDFitnessXPCRequestO15HelloCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOSHAASQ
- _associated conformance 13SIDThinClient20SIDFitnessXPCRequestO15HelloCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0F3KeyAAs23CustomStringConvertible
- _associated conformance 13SIDThinClient20SIDFitnessXPCRequestO15HelloCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0F3KeyAAs28CustomDebugStringConvertible
- _associated conformance 13SIDThinClient21SIDFitnessXPCResponseO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOSHAASQ
- _associated conformance 13SIDThinClient21SIDFitnessXPCResponseO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0E3KeyAAs23CustomStringConvertible
- _associated conformance 13SIDThinClient21SIDFitnessXPCResponseO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0E3KeyAAs28CustomDebugStringConvertible
- _associated conformance 13SIDThinClient21SIDFitnessXPCResponseO15HelloCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOSHAASQ
- _associated conformance 13SIDThinClient21SIDFitnessXPCResponseO15HelloCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0F3KeyAAs23CustomStringConvertible
- _associated conformance 13SIDThinClient21SIDFitnessXPCResponseO15HelloCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLOs0F3KeyAAs28CustomDebugStringConvertible
- _get_enum_tag_for_layout_string 13SIDThinClient19SIDFitnessXPCResultO
- _symbolic SS13correlationId_t
- _symbolic ScCy___________pG 13SIDThinClient19SIDFitnessXPCResultO s5ErrorP
- _symbolic _____ 13SIDThinClient010SIDFitnessB0C
- _symbolic _____ 13SIDThinClient15SIDXPCTreatmentV
- _symbolic _____ 13SIDThinClient15SIDXPCTreatmentV10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____ 13SIDThinClient19SIDFitnessXPCResultO
- _symbolic _____ 13SIDThinClient19SIDFitnessXPCResultO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____ 13SIDThinClient19SIDFitnessXPCResultO17FailureCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____ 13SIDThinClient19SIDFitnessXPCResultO17SuccessCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____ 13SIDThinClient20SIDFitnessXPCRequestO
- _symbolic _____ 13SIDThinClient20SIDFitnessXPCRequestO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____ 13SIDThinClient20SIDFitnessXPCRequestO15HelloCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____ 13SIDThinClient21SIDFitnessXPCResponseO
- _symbolic _____ 13SIDThinClient21SIDFitnessXPCResponseO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____ 13SIDThinClient21SIDFitnessXPCResponseO15HelloCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 13SIDThinClient15SIDXPCTreatmentV10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 13SIDThinClient19SIDFitnessXPCResultO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 13SIDThinClient19SIDFitnessXPCResultO17FailureCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 13SIDThinClient19SIDFitnessXPCResultO17SuccessCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 13SIDThinClient20SIDFitnessXPCRequestO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 13SIDThinClient20SIDFitnessXPCRequestO15HelloCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 13SIDThinClient21SIDFitnessXPCResponseO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 13SIDThinClient21SIDFitnessXPCResponseO15HelloCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 13SIDThinClient15SIDXPCTreatmentV10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 13SIDThinClient19SIDFitnessXPCResultO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 13SIDThinClient19SIDFitnessXPCResultO17FailureCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 13SIDThinClient19SIDFitnessXPCResultO17SuccessCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 13SIDThinClient20SIDFitnessXPCRequestO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 13SIDThinClient20SIDFitnessXPCRequestO15HelloCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 13SIDThinClient21SIDFitnessXPCResponseO10CodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 13SIDThinClient21SIDFitnessXPCResponseO15HelloCodingKeys33_E2A7D3695D5759A413EA9E36890019A0LLO
- _type_layout_string 13SIDThinClient15SIDXPCTreatmentV
- _type_layout_string 13SIDThinClient19SIDFitnessXPCResultO
- _type_layout_string 13SIDThinClient20SIDFitnessXPCRequestO
- _type_layout_string 13SIDThinClient21SIDFitnessXPCResponseO
CStrings:
- "com.apple.servicesintelligence.xpc.fitness"
```
