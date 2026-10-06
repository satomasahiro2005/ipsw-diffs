## CoreODI

> `/System/Library/PrivateFrameworks/CoreODI.framework/CoreODI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__bss` | `0x1520` | `0x24a0` | **`+0xf80`** |
| `__DATA.__bss` | `0xa480` | `0x9680` | **`-0xe00`** |
| `__TEXT.__text` | `0x52f1c` | `0x53a94` | **`+0xb78`** |
| `__DATA_DIRTY.__data` | `0x8b0` | `0x13b8` | **`+0xb08`** |
| `__AUTH.__data` | `0x830` | `0x100` | **`-0x730`** |
| `__DATA.__data` | `0x1020` | `0xc70` | **`-0x3b0`** |
| `__AUTH.__objc_data` | `0x1d8` | `0x48` | **`-0x190`** |
| `__DATA_DIRTY.__objc_data` | `0x390` | `0x520` | **`+0x190`** |
| `__TEXT.__const` | `0x7b32` | `0x7c42` | **`+0x110`** |
| `__DATA.__common` | `0x58` | `0x10` | **`-0x48`** |
| `__DATA_DIRTY.__common` | `0x48` | `0x90` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x4310` | `0x4358` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x1c1f` | `0x1c5f` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1bf4` | `0x1c24` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x2ba8` | `0x2bd0` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x1228` | `0x1250` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x1368` | `0x138c` | **`+0x24`** |
| `__TEXT.__unwind_info` | `0x1b58` | `0x1b70` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xa58` | `0xa48` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x961` | `0x971` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x5d0` | `0x5dc` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x198` | `0x19c` | **`+0x4`** |

### Other Changes

```diff

-27.0.44.0.0
+27.0.49.0.0

-  Functions: 2096
-  Symbols:   1065
-  CStrings:  254
+  Functions: 2102
+  Symbols:   1067
+  CStrings:  255
Symbols:
+ ___swift_memcpy73_8
+ _associated conformance 7CoreODI18EvaluationErrorDTOO015PayloadSecurityD10CodingKeys33_844884413CAAF6E205C8BD9AB0EF5997LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 7CoreODI18EvaluationErrorDTOO015PayloadSecurityD10CodingKeys33_844884413CAAF6E205C8BD9AB0EF5997LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _symbolic S2SSay_____GSay_____Gx______p_____Rz_____RzlIetMHgTgTgTgTgzo_ 7CoreODI21InsightConsumptionDTOV AA0c6ResultE0V s5ErrorP AA18OnDeviceAPIServiceP 11Distributed01_K9ActorStubP
+ _symbolic S2SSay_____GSay_____Gx______p_____RzlIetWHgTgTgTgTgzo_ 7CoreODI21InsightConsumptionDTOV AA0c6ResultE0V s5ErrorP AA18OnDeviceAPIServiceP
+ _symbolic _____ 7CoreODI18EvaluationErrorDTOO015PayloadSecurityD10CodingKeys33_844884413CAAF6E205C8BD9AB0EF5997LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7CoreODI18EvaluationErrorDTOO015PayloadSecurityG10CodingKeys33_844884413CAAF6E205C8BD9AB0EF5997LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7CoreODI18EvaluationErrorDTOO015PayloadSecurityG10CodingKeys33_844884413CAAF6E205C8BD9AB0EF5997LLO
- ___swift_memcpy57_8
- ___swift_memcpy64_8
- _swift_bridgeObjectRelease_n
- _swift_willThrowTypedImpl
- _symbolic SSSay_____GSay_____Gx______p_____Rz_____RzlIetMHgTgTgTgzo_ 7CoreODI21InsightConsumptionDTOV AA0c6ResultE0V s5ErrorP AA18OnDeviceAPIServiceP 11Distributed01_K9ActorStubP
- _symbolic SSSay_____GSay_____Gx______p_____RzlIetWHgTgTgTgzo_ 7CoreODI21InsightConsumptionDTOV AA0c6ResultE0V s5ErrorP AA18OnDeviceAPIServiceP
CStrings:
+ "payloadSecurityError"
+ "submitConsumption(conversationId:operationCategory:statuses:insights:)"
- "submitConsumption(conversationId:statuses:insights:)"
```
