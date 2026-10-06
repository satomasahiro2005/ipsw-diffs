## PhotosUIEdit

> `/System/Library/PrivateFrameworks/PhotosUIEdit.framework/PhotosUIEdit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe265c` | `0xe2fa0` | **`+0x944`** |
| `__AUTH_CONST.__cfstring` | `0x3e40` | `0x3ee0` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0xabc8` | `0xac58` | **`+0x90`** |
| `__DATA.__bss` | `0x3ec8` | `0x3f48` | **`+0x80`** |
| `__TEXT.__cstring` | `0x6037` | `0x60ac` | **`+0x75`** |
| `__TEXT.__oslogstring` | `0x4333` | `0x438d` | **`+0x5a`** |
| `__TEXT.__objc_methlist` | `0x49bc` | `0x49fc` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d48` | `0x3d78` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x2b2c` | `0x2b5c` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x4028` | `0x4058` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x21c0` | `0x21e8` | **`+0x28`** |
| `__TEXT.__const` | `0x7778` | `0x7798` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x678` | `0x690` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x4d4` | `0x4e4` | **`+0x10`** |
| `__DATA.__data` | `0x2890` | `0x2898` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1650` | `0x1658` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x13140` | `0x13148` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x254` | `0x258` | **`+0x4`** |

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0

+  - /System/Library/PrivateFrameworks/PhotosRendering.framework/PhotosRendering

-  Functions: 7036
-  Symbols:   4944
-  CStrings:  1130
+  Functions: 7043
+  Symbols:   4957
+  CStrings:  1137
Symbols:
+ +[PEAdjustmentPreset _sanitizedCompositionForCompositionController:autoType:]
+ +[PEEditAIToolCompletedEventBuilder sendEventForCleanupTool:requestDuration:result:guardrailReasons:generativeModel:interactionMode:userSelectedInteractionMode:modelResolution:]
+ +[PEEditAIToolCompletedEventBuilder sendEventForTool:requestDuration:result:guardrailReasons:sourceTab:interactionCount:generativeModel:interactionMode:userSelectedInteractionMode:modelResolution:]
+ -[PEAdjustmentPreset _deserializedComposition]
+ -[PEAdjustmentPreset _serializeComposition:autoType:includeSidecar:]
+ -[PEAdjustmentPreset _serializeDeferredComposition]
+ -[PEAdjustmentPreset initWithCompositionControllerDeferringSerialization:asset:]
+ -[PECleanupSegmentAnalyzer ciContext]
+ -[PECleanupSegmentAnalyzer setCiContext:]
+ GCC_except_table1001
+ GCC_except_table1013
+ GCC_except_table1128
+ GCC_except_table1239
+ GCC_except_table1240
+ GCC_except_table1241
+ GCC_except_table1279
+ GCC_except_table1292
+ GCC_except_table402
+ GCC_except_table428
+ GCC_except_table439
+ GCC_except_table459
+ GCC_except_table473
+ GCC_except_table731
+ GCC_except_table753
+ GCC_except_table909
+ GCC_except_table920
+ GCC_except_table928
+ GCC_except_table988
+ GCC_except_table992
+ _OBJC_IVAR_$_PEAdjustmentPreset._deferredAutoType
+ _OBJC_IVAR_$_PEAdjustmentPreset._deferredSerialization
+ _OBJC_IVAR_$_PEAdjustmentPreset._deferredSourceAssetUUID
+ _OBJC_IVAR_$_PECleanupSegmentAnalyzer._ciContext
+ ___80-[PEAdjustmentPreset initWithCompositionControllerDeferringSerialization:asset:]_block_invoke
+ ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
+ _associated conformance 12PhotosUIEdit24CompositionMediaProvider33_6B0A8C9A6CD579A51EF3C64FC30C5F82LLC0A7Editing0aD9ProvidingAA11Observation10Observable
+ _kCIContextName
- +[PEEditAIToolCompletedEventBuilder sendEventForCleanupTool:requestDuration:result:guardrailReasons:generativeModel:interactionMode:userSelectedInteractionMode:]
- +[PEEditAIToolCompletedEventBuilder sendEventForTool:requestDuration:result:guardrailReasons:sourceTab:interactionCount:generativeModel:interactionMode:userSelectedInteractionMode:]
- -[PEAdjustmentPreset _serializeCompositionController:includeSidecar:]
- GCC_except_table1006
- GCC_except_table1121
- GCC_except_table1232
- GCC_except_table1233
- GCC_except_table1234
- GCC_except_table1272
- GCC_except_table1285
- GCC_except_table423
- GCC_except_table434
- GCC_except_table454
- GCC_except_table468
- GCC_except_table724
- GCC_except_table746
- GCC_except_table902
- GCC_except_table913
- GCC_except_table921
- GCC_except_table971
- GCC_except_table981
- GCC_except_table987
- _OUTLINED_FUNCTION_280
- _OUTLINED_FUNCTION_281
CStrings:
+ "PEAdjustmentPreset failed to serialize deferred composition, keeping it in memory"
+ "PECleanupSegmentAnalyzer"
+ "PENoUpsellRateLimitErrorMessage"
+ "PESerializationUtility sidecar data could not be loaded: %{public}@"
+ "composition"
+ "isEditAIEligible"
+ "modelResolution"
+ "outAutoType"
- "PESerializationUtility sidecar data could not be loaded: %@"
```
