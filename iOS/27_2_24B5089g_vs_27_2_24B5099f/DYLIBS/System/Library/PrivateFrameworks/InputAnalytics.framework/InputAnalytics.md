## InputAnalytics

> `/System/Library/PrivateFrameworks/InputAnalytics.framework/InputAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fcac` | `0x2037c` | **`+0x6d0`** |
| `__AUTH_CONST.__cfstring` | `0x94c0` | `0x9b00` | **`+0x640`** |
| `__TEXT.__cstring` | `0x61c2` | `0x6602` | **`+0x440`** |
| `__DATA_CONST.__const` | `0x2000` | `0x21d8` | **`+0x1d8`** |
| `__AUTH_CONST.__objc_const` | `0x4238` | `0x4338` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x26fc` | `0x27bc` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x27ac` | `0x27fc` | **`+0x50`** |
| `__AUTH_CONST.__objc_intobj` | `0x1260` | `0x12a8` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x1260` | `0x12a0` | **`+0x40`** |
| `__AUTH.__objc_data` | `0xa70` | `0xa98` | **`+0x28`** |
| `__DATA_DIRTY.__objc_data` | `0x730` | `0x758` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x998` | `0x9c0` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x234` | `0x23c` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x280` | `0x288` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1c0` | `0x1c8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x100` | `0x108` | **`+0x8`** |

### Other Changes

```diff

-154.1.5.0.0
+154.1.8.0.0

-  Functions: 1051
-  Symbols:   2687
-  CStrings:  1386
+  Functions: 1067
+  Symbols:   2771
+  CStrings:  1437
Symbols:
+ +[IATextInputActionsSessionKeyboardLatencyAction(NSSecureCoding) supportsSecureCoding]
+ -[IATextInputActionsAnalytics didMeasureKeyboardLatency:]
+ -[IATextInputActionsAnalytics(TestingSupport) setFlushedActionObserver:]
+ -[IATextInputActionsSessionAction asKeyboardLatency]
+ -[IATextInputActionsSessionKeyboardLatencyAction .cxx_destruct]
+ -[IATextInputActionsSessionKeyboardLatencyAction changedContent]
+ -[IATextInputActionsSessionKeyboardLatencyAction description]
+ -[IATextInputActionsSessionKeyboardLatencyAction inputActionCount]
+ -[IATextInputActionsSessionKeyboardLatencyAction keystrokeLatenciesMsByInputType]
+ -[IATextInputActionsSessionKeyboardLatencyAction setKeystrokeLatenciesMsByInputType:]
+ -[IATextInputActionsSessionKeyboardLatencyAction(NSSecureCoding) encodeWithCoder:]
+ -[IATextInputActionsSessionKeyboardLatencyAction(NSSecureCoding) initFromDictionary:]
+ -[IATextInputActionsSessionKeyboardLatencyAction(NSSecureCoding) initWithCoder:]
+ -[IATextInputActionsSessionKeyboardLatencyAction(NSSecureCoding) toDictionary]
+ _IAPayloadKeyImageGenerationBlockingSafetyModel
+ _IAPayloadKeyImageGenerationFailureReason
+ _IAPayloadKeyImageGenerationStyleEnum
+ _IAPayloadValueGenmojiUsageSourceFindAndReplace
+ _IAPayloadValueGenmojiUsageSourcePreGenerated
+ _IAPayloadValueGenmojiUsageTypeDelete
+ _IAPayloadValueGenmojiUsageTypeFindAndReplaceAccepted
+ _IAPayloadValueGenmojiUsageTypeFindAndReplaceHighlightShown
+ _IAPayloadValueGenmojiUsageTypeFindAndReplaceSuggestionShown
+ _IAPayloadValueGenmojiUsageTypeOther
+ _IAPayloadValueGenmojiUsageTypeShare
+ _IAPayloadValueImageGenerationBlockingSafetyModelMultimodalGuardrail
+ _IAPayloadValueImageGenerationBlockingSafetyModelPixelGuardrail
+ _IAPayloadValueImageGenerationBlockingSafetyModelTextGuardrail
+ _IAPayloadValueImageGenerationBlockingSafetyModelUnspecified
+ _IAPayloadValueImageGenerationFailureReasonBlocklistCategoryAppleProducts
+ _IAPayloadValueImageGenerationFailureReasonBlocklistCategoryBlocklistDrugs
+ _IAPayloadValueImageGenerationFailureReasonBlocklistCategoryCopyright
+ _IAPayloadValueImageGenerationFailureReasonBlocklistCategoryCustomWords
+ _IAPayloadValueImageGenerationFailureReasonBlocklistCategoryDesecration
+ _IAPayloadValueImageGenerationFailureReasonBlocklistCategoryMinor
+ _IAPayloadValueImageGenerationFailureReasonBlocklistCategoryPersonalization
+ _IAPayloadValueImageGenerationFailureReasonExternalGeneratorNetworkFailure
+ _IAPayloadValueImageGenerationFailureReasonExternalGeneratorRateLimited
+ _IAPayloadValueImageGenerationFailureReasonLexiconOrLanguage
+ _IAPayloadValueImageGenerationFailureReasonModelsDownloading
+ _IAPayloadValueImageGenerationFailureReasonPCCErrors
+ _IAPayloadValueImageGenerationFailureReasonPCCNoNodesAvailable
+ _IAPayloadValueImageGenerationFailureReasonSWErrors
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryCSEAI
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryCopyright
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryDrugs
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryHarassment
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryHate
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryIdentityEditing
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryMapsAndFlags
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryNudity
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryOffensive
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryPhotorealism
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryPublicFigure
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryRacy
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategorySelfHarm
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategorySuggestive
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryTerrorism
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryToxic
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryViolenceAndGore
+ _IAPayloadValueImageGenerationFailureReasonUnspecified
+ _IASignalSmartRepliesMailFormattingBarIntentDismissed
+ _IASignalSmartRepliesMailFormattingBarIntentEngaged
+ _IASignalSmartRepliesMailFormattingBarIntentShown
+ _IASignalWritingToolsMailFormattingBarActionDismissed
+ _IASignalWritingToolsMailFormattingBarActionEngaged
+ _IASignalWritingToolsMailFormattingBarActionShown
+ _IATextInputActionsKeyboardTypeFloating
+ _IATextInputActionsKeyboardTypeHardware
+ _IATextInputActionsKeyboardTypeLandscape
+ _IATextInputActionsKeyboardTypePortrait
+ _IATextInputActionsKeyboardTypeSplit
+ _IATextInputActionsKeyboardTypeWebSuffix
+ _OBJC_CLASS_$_IATextInputActionsSessionKeyboardLatencyAction
+ _OBJC_IVAR_$_IATextInputActionsAnalytics._flushedActionObserver
+ _OBJC_IVAR_$_IATextInputActionsSessionKeyboardLatencyAction._keystrokeLatenciesMsByInputType
+ _OBJC_METACLASS_$_IATextInputActionsSessionKeyboardLatencyAction
+ __OBJC_$_CLASS_METHODS_IATextInputActionsSessionKeyboardLatencyAction(NSSecureCoding)
+ __OBJC_$_INSTANCE_METHODS_IATextInputActionsSessionKeyboardLatencyAction(NSSecureCoding)
+ __OBJC_$_INSTANCE_VARIABLES_IATextInputActionsSessionKeyboardLatencyAction
+ __OBJC_$_PROP_LIST_IATextInputActionsSessionKeyboardLatencyAction
+ __OBJC_CLASS_RO_$_IATextInputActionsSessionKeyboardLatencyAction
+ __OBJC_METACLASS_RO_$_IATextInputActionsSessionKeyboardLatencyAction
+ ___57-[IATextInputActionsAnalytics didMeasureKeyboardLatency:]_block_invoke
CStrings:
+ ", latencyInputTypeCount=%lu, latencySampleCount=%lu"
+ "BlockingSafetyModel"
+ "BlocklistAppleProducts"
+ "BlocklistCopyright"
+ "BlocklistCustomWords"
+ "BlocklistDesecration"
+ "BlocklistDrugs"
+ "BlocklistMinor"
+ "BlocklistPersonalization"
+ "FindAndReplace"
+ "FindAndReplaceAccepted"
+ "FindAndReplaceHighlightShown"
+ "FindAndReplaceSuggestionShown"
+ "Floating"
+ "Hardware"
+ "Landscape"
+ "MailFormattingBarActionDismissed"
+ "MailFormattingBarActionEngaged"
+ "MailFormattingBarActionShown"
+ "MailFormattingBarIntentDismissed"
+ "MailFormattingBarIntentEngaged"
+ "MailFormattingBarIntentShown"
+ "ModelsDownloading"
+ "MultimodalGuardrail"
+ "PCCErrors"
+ "PCCNoNodesAvailable"
+ "PixelGuardrail"
+ "PreGenerated"
+ "SWErrors"
+ "SafetyCategoryCSEAI"
+ "SafetyCategoryCopyright"
+ "SafetyCategoryDrugs"
+ "SafetyCategoryHarassment"
+ "SafetyCategoryHate"
+ "SafetyCategoryIdentityEditing"
+ "SafetyCategoryMapsAndFlags"
+ "SafetyCategoryNudity"
+ "SafetyCategoryOffensive"
+ "SafetyCategoryPhotorealism"
+ "SafetyCategoryPublicFigure"
+ "SafetyCategoryRacy"
+ "SafetyCategorySelfHarm"
+ "SafetyCategorySuggestive"
+ "SafetyCategoryTerrorism"
+ "SafetyCategoryToxic"
+ "SafetyCategoryViolenceAndGore"
+ "Split"
+ "StyleEnum"
+ "TextGuardrail"
+ "[IATextInputActionsAnalytics] didMeasureKeyboardLatency with %lu input types"
+ "keystrokeLatenciesMsByInputType"
```
