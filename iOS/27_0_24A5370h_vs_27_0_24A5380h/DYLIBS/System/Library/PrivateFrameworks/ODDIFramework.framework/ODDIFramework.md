## ODDIFramework

> `/System/Library/PrivateFrameworks/ODDIFramework.framework/ODDIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4edc0` | `0x4f9ac` | **`+0xbec`** |
| `__TEXT.__cstring` | `0x3f46` | `0x4046` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x2e60` | `0x2f20` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x89f0` | `0x8aa8` | **`+0xb8`** |
| `__TEXT.__const` | `0x7528` | `0x75c8` | **`+0xa0`** |
| `__DATA.__bss` | `0xda80` | `0xdb00` | **`+0x80`** |
| `__DATA_DIRTY.__bss` | `0x1c00` | `0x1c80` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x7bf` | `0x83f` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x2970` | `0x29ac` | **`+0x3c`** |
| `__DATA_DIRTY.__data` | `0xe48` | `0xe80` | **`+0x38`** |
| `__AUTH.__data` | `0x1ec0` | `0x1e98` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x3a80` | `0x3aa0` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x1530` | `0x1550` | **`+0x20`** |
| `__DATA.__common` | `0x90` | `0xb0` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x1610` | `0x1630` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x590` | `0x5b0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x189d` | `0x18bd` | **`+0x20`** |
| `__DATA.__data` | `0x1518` | `0x1530` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0xba0` | `0xbb8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x19e8` | `0x1a00` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xc8` | `0xdc` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x490` | `0x4a0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xad4` | `0xae0` | **`+0xc`** |
| `__TEXT.__swift5_proto` | `0x7c4` | `0x7cc` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x80` | `0x84` | **`+0x4`** |

### Other Changes

```diff

-3600.49.3.0.0
+3600.49.7.1.1

-  Functions: 2811
-  Symbols:   1057
-  CStrings:  506
+  Functions: 2817
+  Symbols:   1061
+  CStrings:  514
Symbols:
+ _symbolic _____ So31ORCHSchemaORCHOrchestrationModeV
+ _symbolic _____Sg So31ORCHSchemaORCHOrchestrationModeV
+ _symbolic ______p8strategy______Sg4modet 13ODDIFramework16SiriTurnStrategyP So31ORCHSchemaORCHOrchestrationModeV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So31ORCHSchemaORCHOrchestrationModeV
CStrings:
+ "ORCHORCHESTRATIONMODE_LLM_SIRI"
+ "ORCHORCHESTRATIONMODE_SIRI_CLASSIC"
+ "ORCHORCHESTRATIONMODE_SIRI_X_FULL_UOD"
+ "ORCHORCHESTRATIONMODE_SIRI_X_HYBRID_UOD"
+ "ORCHORCHESTRATIONMODE_SYSTEM_ASSISTANT_EXPERIENCE"
+ "ORCHORCHESTRATIONMODE_UNKNOWN"
+ "Strategy selected from ORCH orchestrationMode=%s"
+ "executionCategory signals: searchAgent=%{bool}d, globalSearch=%{bool}d, localSearch=%{bool}d, shouldRunBoth=%{bool}d, finalGoalPurpose=%{bool}d, useInToolPurpose=%{bool}d, flowTool=%{bool}d, appIntent=%{bool}d, siriXInvocation=%{bool}d, montara=%{bool}d"
+ "orchestrationMode"
- "executionCategory signals: searchAgent=%{bool}d, globalSearch=%{bool}d, localSearch=%{bool}d, shouldRunBoth=%{bool}d, flowTool=%{bool}d, appIntent=%{bool}d, siriXInvocation=%{bool}d"
```
