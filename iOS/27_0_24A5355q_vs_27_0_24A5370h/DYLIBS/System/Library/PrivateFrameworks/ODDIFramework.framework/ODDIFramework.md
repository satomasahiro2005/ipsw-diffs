## ODDIFramework

> `/System/Library/PrivateFrameworks/ODDIFramework.framework/ODDIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a2f4` | `0x4edc0` | **`+0x4acc`** |
| `__DATA_CONST.__const` | `0x80d0` | `0x89f0` | **`+0x920`** |
| `__TEXT.__cstring` | `0x3ab6` | `0x3f46` | **`+0x490`** |
| `__TEXT.__swift5_reflstr` | `0x163d` | `0x189d` | **`+0x260`** |
| `__AUTH_CONST.__cfstring` | `0x2c80` | `0x2e60` | **`+0x1e0`** |
| `__TEXT.__swift5_typeref` | `0x2794` | `0x2970` | **`+0x1dc`** |
| `__TEXT.__constg_swiftt` | `0x1450` | `0x1610` | **`+0x1c0`** |
| `__AUTH_CONST.__const` | `0x38c8` | `0x3a80` | **`+0x1b8`** |
| `__AUTH_CONST.__objc_const` | `0x13b0` | `0x1530` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x18d0` | `0x19e8` | **`+0x118`** |
| `__AUTH.__data` | `0x1de0` | `0x1ec0` | **`+0xe0`** |
| `__TEXT.__const` | `0x7468` | `0x7528` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x70f` | `0x7bf` | **`+0xb0`** |
| `__DATA.__data` | `0x1470` | `0x1518` | **`+0xa8`** |
| `__DATA_DIRTY.__data` | `0xda8` | `0xe48` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0xa44` | `0xad4` | **`+0x90`** |
| `__DATA.__common` | `0x18` | `0x90` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x448` | `0x490` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x1fd0` | `0x2018` | **`+0x48`** |
| `__TEXT.__swift5_builtin` | `0xa0` | `0xc8` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0xa30` | `0xa38` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x78` | `0x80` | **`+0x8`** |

### Other Changes

```diff

-3600.43.6.1.1
+3600.49.3.0.0

-  Functions: 2654
-  Symbols:   1036
-  CStrings:  477
+  Functions: 2811
+  Symbols:   1057
+  CStrings:  506
Symbols:
+ _OBJC_CLASS_$_PLANNERSchemaPLANNERClientEvent
+ _OBJC_CLASS_$_PLANNERSchemaPLANNERPlanningModelInferenceContext
+ _OBJC_CLASS_$_PLANNERTOOLSSchemaPLANNERTOOLSClientEvent
+ _OBJC_CLASS_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionContext
+ _OBJC_CLASS_$_STSchemaSTGlobalSearchContext
+ _OBJC_CLASS_$_STSchemaSTGlobalSearchResult
+ _keypath_get.44Tm
+ _keypath_get.70Tm
+ _keypath_set.67Tm
+ _keypath_set.71Tm
+ _symbolic SaySo018ExecutorSiriSchemaA15ToolCallContextCGSg
+ _symbolic SaySo018ExecutorSiriSchemaA20AppIntentCallContextCGSg
+ _symbolic SaySo24SASchemaSARequestContextCGSg
+ _symbolic SaySo28STSchemaSTGlobalSearchResultCG
+ _symbolic SaySo29STSchemaSTGlobalSearchContextCGSg
+ _symbolic SaySo31SKIMMERSchemaSKIMMERFlowContextCGSg
+ _symbolic SaySo43SIRIXAGENTSchemaSIRIXAGENTInvocationContextCGSg
+ _symbolic SaySo46PLANNERTOOLSSchemaPLANNERTOOLSExecutionContextCGSg
+ _symbolic SaySo46SASchemaSAGlobalSearchStreamingResponseContextCGSg
+ _symbolic SaySo49PLANNERSchemaPLANNERPlanningModelInferenceContextCGSg
+ _symbolic SbSgSg
+ _symbolic _____ So18CNVSchemaCNVPluginV
+ _symbolic _____ So33ODDSiriSchemaODDExecutionCategoryV
+ _symbolic _____SgSg So33ODDSiriSchemaODDExecutionCategoryV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So18CNVSchemaCNVPluginV
- _keypath_get.40Tm
- _keypath_set.63Tm
- _symbolic So22SASchemaSARequestEndedCSgSg
- _symbolic So24SASchemaSARequestStartedCSgSg
CStrings:
+ "INVOCATIONSOURCE_CAMERA_APP_TEXT"
+ "INVOCATIONSOURCE_PHOTOS_APP_TEXT"
+ "INVOCATIONSOURCE_SCREENSHOT_UI_TEXT"
+ "INVOCATIONSOURCE_TRY_ASKING_SIRI"
+ "INVOCATIONSOURCE_VISUAL_INTELLIGENCE_PHOTOS_APP"
+ "INVOCATIONSOURCE_VISUAL_INTELLIGENCE_SCREENSHOT_UI"
+ "ODDEXECUTIONCATEGORY_APP_INTENT"
+ "ODDEXECUTIONCATEGORY_FLOW_TOOLS"
+ "ODDEXECUTIONCATEGORY_SEARCH_AND_ACT"
+ "ODDEXECUTIONCATEGORY_SEARCH_BOTH"
+ "ODDEXECUTIONCATEGORY_SEARCH_GLOBAL"
+ "ODDEXECUTIONCATEGORY_SEARCH_LOCAL"
+ "ODDEXECUTIONCATEGORY_SIRIX_AGENT"
+ "ODDEXECUTIONCATEGORY_THIRD_PARTY_GEN_AI"
+ "ODDEXECUTIONCATEGORY_UNKNOWN"
+ "ask_user_to_pick"
+ "didResumeSiriApp"
+ "didUseOnScreenAwareness"
+ "didUseWKASummarization"
+ "executionCategory"
+ "executionCategory signals: searchAgent=%{bool}d, globalSearch=%{bool}d, localSearch=%{bool}d, shouldRunBoth=%{bool}d, flowTool=%{bool}d, appIntent=%{bool}d, siriXInvocation=%{bool}d"
+ "get_entity_details"
+ "handoff-to-siri-x"
+ "isContextualFollowUp"
+ "pass_to_siri_models"
+ "productArea signals: cnv=%s, actionCreated=%s, skimmerFlow=%s, plannerTool=%s"
+ "query_context_prediction"
+ "siri_x_mini_tool"
+ "summarizedAnswer"
+ "utterance: %s"
- "useCase signals: searchAgentRequest=%{bool}d, flowTool=%{bool}d, appIntent=%{bool}d, siriXAgent=%{bool}d"
```
