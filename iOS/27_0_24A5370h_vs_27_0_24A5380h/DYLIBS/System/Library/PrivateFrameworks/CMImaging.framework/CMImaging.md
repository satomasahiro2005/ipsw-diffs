## CMImaging

> `/System/Library/PrivateFrameworks/CMImaging.framework/CMImaging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dd8a4` | `0x1da208` | **`-0x369c`** |
| `__TEXT.__oslogstring` | `0x1526c` | `0x1551e` | **`+0x2b2`** |
| `__AUTH.__objc_data` | `0x1e0` | `—` | **`-0x1e0`** |
| `__DATA_DIRTY.__objc_data` | `0x39d0` | `0x3bb0` | **`+0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0x1f050` | `0x1f118` | **`+0xc8`** |
| `__TEXT.__objc_methlist` | `0xd31c` | `0xd3bc` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0xc00` | `0xc48` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x6a0` | `0x6e8` | **`+0x48`** |
| `__TEXT.__cstring` | `0x28ae8` | `0x28b23` | **`+0x3b`** |
| `__DATA_CONST.__objc_selrefs` | `0x6218` | `0x6240` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x6bc0` | `0x6be0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xbf0` | `0xc00` | **`+0x10`** |
| `__DATA.__bss` | `0x80` | `0x70` | **`-0x10`** |
| `__DATA.__common` | `0x1d0` | `0x1e0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x17c4` | `0x17d4` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x1d8` | `0x1e8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x31d0` | `0x31e0` | **`+0x10`** |
| `__DATA.__data` | `0x12d88` | `0x12d90` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x8` | `—` | **`-0x8`** |

### Other Changes

```diff

-753.0.0.122.3
+758.0.0.122.2

-  Functions: 7581
-  Symbols:   8750
-  CStrings:  5286
+  Functions: 7597
+  Symbols:   8769
+  CStrings:  5293
Symbols:
+ +[CMITIPConfig initialize]
+ -[CMIInferenceExecutionStreamBypass setANEExecutionPriority:]
+ -[CMIInferenceExecutionStreamEspressoV1 aneExecutionPriority]
+ -[CMIInferenceExecutionStreamEspressoV1 setANEExecutionPriority:]
+ -[CMIInferenceExecutionStreamEspressoV1 setAneExecutionPriority:]
+ -[CMIInferenceExecutionStreamEspressoV2 aneExecutionPriority]
+ -[CMIInferenceExecutionStreamEspressoV2 setANEExecutionPriority:]
+ -[CMIInferenceExecutionStreamEspressoV2 setAneExecutionPriority:]
+ -[CMITIPConfig aneExecutionPriorityOverride]
+ -[CMITIPConfig setAneExecutionPriorityOverride:]
+ -[CMITiledInferenceProcessorConfig aneExecutionPriority]
+ -[CMITiledInferenceProcessorConfig setAneExecutionPriority:]
+ GCC_except_table70
+ GCC_except_table93
+ GCC_except_table94
+ _OBJC_IVAR_$_CMIInferenceExecutionStreamEspressoV1._aneExecutionPriority
+ _OBJC_IVAR_$_CMIInferenceExecutionStreamEspressoV2._aneExecutionPriority
+ _OBJC_IVAR_$_CMITIPConfig._aneExecutionPriorityOverride
+ _OBJC_IVAR_$_CMITiledInferenceProcessorConfig._aneExecutionPriority
+ _e5rt_execution_stream_set_ane_execution_priority
+ _espresso_plan_set_priority
+ _gCMITIPConfig
- GCC_except_table79
- GCC_except_table89
- GCC_except_table92
CStrings:
+ "-[CMIInferenceExecutionStreamEspressoV1 submitAsyncWithCompletionHandler:]"
+ "<<<< CMISmartStyleUtilitiesV1 >>>> %s: Could not load default biases for cast type %@"
+ "<<<< CMISmartStyleUtilitiesV1 >>>> %s: [SmartStyles] Error: Failed to load %s.plist - falling back to compiled-in version"
+ "<<<< CMITIP >>>> %s: Warning! CMITiledInferenceProcessor is configured with CMIInferenceANEExecutionPriorityHigh — this maps to ANE HW band 2 which should be reserved for streaming inferences. CMITiledInferenceProcessor is used for stills processing and running at high ANE priority will conflict with concurrent streaming inference workloads on the ANE."
+ "<<<< CMITIP >>>> %s: e5rt_execution_stream_set_ane_execution_priority failed, %s."
+ "<<<< CMITIP >>>> %s: e5rt_execution_stream_submit_async_with_timeout failed %s."
+ "<<<< CMITIP >>>> %s: espresso_plan_set_priority failed (%d)"
+ "<<<< CMITIP >>>> %s: setANEExecutionPriority failed (err:%d)"
+ "<<<< CMITIPConfig >>>> %s: CMITIPConfig aneExecutionPriorityOverride:  %lu"
+ "<<<< CMITIPConfig >>>> %s: CMITIPConfig aneSubmitTimeoutMs:            %llu"
+ "<<<< CMITIPConfig >>>> %s: CMITIPConfig shareIntermediates:            %d"
+ "_loadDefaultUserBiasByCastType"
+ "cmitipconfig_trace"
- "+[CMISmartStyleUtilitiesV1 defaultStyleForCastType:]_block_invoke"
- "<<<< CMISmartStyleUtilitiesV1 >>>> %s: Invalid cast type %@"
- "<<<< CMISmartStyleUtilitiesV1 >>>> %s: [SmartStyles] Error: Failed to load RendererTuning.plist - falling back to compiled in version"
- "<<<< CMITIP >>>> %s: CMITIPConfig aneSubmitTimeoutMs:    %llu"
- "<<<< CMITIP >>>> %s: CMITIPConfig shareIntermediates:    %d"
- "<<<< CMITIP >>>> %s: e5rt_execution_stream_execute_sync failed %s."
```
