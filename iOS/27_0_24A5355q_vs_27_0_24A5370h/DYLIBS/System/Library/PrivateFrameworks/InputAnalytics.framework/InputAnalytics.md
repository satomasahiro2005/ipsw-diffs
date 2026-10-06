## InputAnalytics

> `/System/Library/PrivateFrameworks/InputAnalytics.framework/InputAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f534` | `0x1f7e8` | **`+0x2b4`** |
| `__AUTH_CONST.__cfstring` | `0x8920` | `0x8b80` | **`+0x260`** |
| `__TEXT.__cstring` | `0x5832` | `0x5a92` | **`+0x260`** |
| `__AUTH_CONST.__objc_const` | `0x40c0` | `0x4200` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x1cf8` | `0x1da0` | **`+0xa8`** |
| `__TEXT.__objc_methlist` | `0x260c` | `0x26b4` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0xa48` | `0xa98` | **`+0x50`** |
| `__AUTH_CONST.__objc_intobj` | `0xff0` | `0x1038` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x1200` | `0x1240` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x950` | `0x988` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x224` | `0x230` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xf8` | `0x100` | **`+0x8`** |

### Other Changes

```diff

-139.0.0.0.0
+141.0.0.0.0

-  Functions: 1029
-  Symbols:   2551
-  CStrings:  1292
+  Functions: 1042
+  Symbols:   2595
+  CStrings:  1311
Symbols:
+ -[IASRollingSet .cxx_destruct]
+ -[IASRollingSet addObject:]
+ -[IASRollingSet containsObject:]
+ -[IASRollingSet count]
+ -[IASRollingSet current]
+ -[IASRollingSet init]
+ -[IASRollingSet previous]
+ -[IASRollingSet removeAllObjects]
+ -[IASRollingSet roll]
+ -[IASRollingSet setCurrent:]
+ -[IASRollingSet setPrevious:]
+ -[IASRollingSet setUnionCount:]
+ -[IASRollingSet unionCount]
+ _IAPayloadKeyImageGenerationImageHeight
+ _IAPayloadKeyImageGenerationImageWidth
+ _IAPayloadKeyWritingToolsAlwaysOnBundleID
+ _IAPayloadKeyWritingToolsAlwaysOnGrammarUUID
+ _IAPayloadKeyWritingToolsAlwaysOnInputTokenCount
+ _IAPayloadKeyWritingToolsAlwaysOnModelInfo
+ _IAPayloadKeyWritingToolsAlwaysOnSuggestionCategory
+ _IAPayloadKeyWritingToolsAlwaysOnSuggestionCount
+ _IASignalImageGenerationCreateImageIntentInvoked
+ _IASignalImageGenerationGenerateImageIntentInvoked
+ _IASignalImageGenerationPreviewGenerationFailed
+ _IASignalWritingToolsAlwaysOnProofreadingAcceptAllSuggestionsEngaged
+ _IASignalWritingToolsAlwaysOnProofreadingIgnoreAllSuggestionsEngaged
+ _IASignalWritingToolsAlwaysOnProofreadingPanelDismissed
+ _IASignalWritingToolsAlwaysOnProofreadingPanelIndexChanged
+ _IASignalWritingToolsAlwaysOnProofreadingPanelShown
+ _IASignalWritingToolsAlwaysOnProofreadingSuggestionAccepted
+ _IASignalWritingToolsAlwaysOnProofreadingSuggestionAcceptedInPanel
+ _IASignalWritingToolsAlwaysOnProofreadingSuggestionBubbleShown
+ _IASignalWritingToolsAlwaysOnProofreadingSuggestionIgnored
+ _IASignalWritingToolsAlwaysOnProofreadingSuggestionShown
+ _IASignalWritingToolsAlwaysOnProofreadingTemporarilyPauseSuggestionsEngaged
+ _OBJC_CLASS_$_IASRollingSet
+ _OBJC_IVAR_$_IASRollingSet._current
+ _OBJC_IVAR_$_IASRollingSet._previous
+ _OBJC_IVAR_$_IASRollingSet._unionCount
+ _OBJC_METACLASS_$_IASRollingSet
+ __OBJC_$_INSTANCE_METHODS_IASRollingSet
+ __OBJC_$_INSTANCE_VARIABLES_IASRollingSet
+ __OBJC_$_PROP_LIST_IASRollingSet
+ __OBJC_CLASS_RO_$_IASRollingSet
+ __OBJC_METACLASS_RO_$_IASRollingSet
- _IAPayloadKeyImageGenerationResolution
CStrings:
+ "AlwaysOnProofreadingAcceptAllSuggestionsEngaged"
+ "AlwaysOnProofreadingIgnoreAllSuggestionsEngaged"
+ "AlwaysOnProofreadingPanelDismissed"
+ "AlwaysOnProofreadingPanelIndexChanged"
+ "AlwaysOnProofreadingPanelShown"
+ "AlwaysOnProofreadingSuggestionAccepted"
+ "AlwaysOnProofreadingSuggestionAcceptedInPanel"
+ "AlwaysOnProofreadingSuggestionBubbleShown"
+ "AlwaysOnProofreadingSuggestionIgnored"
+ "AlwaysOnProofreadingSuggestionShown"
+ "AlwaysOnProofreadingTemporarilyPauseSuggestionsEngaged"
+ "CreateImageIntentInvoked"
+ "GenerateImageIntentInvoked"
+ "GrammarUUID"
+ "ImageHeight"
+ "ImageWidth"
+ "ModelInfo"
+ "PreviewGenerationFailed"
+ "SuggestionCategory"
+ "SuggestionCount"
- "Resolution"
```
