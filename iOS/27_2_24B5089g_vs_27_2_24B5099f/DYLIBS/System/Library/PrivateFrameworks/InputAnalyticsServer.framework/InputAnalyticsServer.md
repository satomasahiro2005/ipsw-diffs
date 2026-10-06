## InputAnalyticsServer

> `/System/Library/PrivateFrameworks/InputAnalyticsServer.framework/InputAnalyticsServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8240c` | `0x86740` | **`+0x4334`** |
| `__TEXT.__oslogstring` | `0x8270` | `0x8700` | **`+0x490`** |
| `__AUTH_CONST.__objc_const` | `0xa858` | `0xab78` | **`+0x320`** |
| `__TEXT.__objc_methlist` | `0x6484` | `0x6714` | **`+0x290`** |
| `__AUTH_CONST.__cfstring` | `0x6fa0` | `0x7220` | **`+0x280`** |
| `__AUTH_CONST.__objc_intobj` | `0x1968` | `0x1bc0` | **`+0x258`** |
| `__DATA_CONST.__got` | `0x1968` | `0x1b48` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x69c2` | `0x6b92` | **`+0x1d0`** |
| `__DATA_DIRTY.__objc_data` | `0x1d10` | `0x1ea0` | **`+0x190`** |
| `__DATA_CONST.__objc_selrefs` | `0x3330` | `0x34b8` | **`+0x188`** |
| `__AUTH_CONST.__const` | `0x1638` | `0x1758` | **`+0x120`** |
| `__AUTH.__objc_data` | `0xbc8` | `0xad8` | **`-0xf0`** |
| `__DATA_CONST.__const` | `0x18b8` | `0x1988` | **`+0xd0`** |
| `__DATA_DIRTY.__bss` | `0x650` | `0x6f0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x1908` | `0x1998` | **`+0x90`** |
| `__TEXT.__const` | `0xac0` | `0xb10` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0xc00` | `0xc48` | **`+0x48`** |
| `__DATA.__objc_ivar` | `0x74c` | `0x774` | **`+0x28`** |
| `__DATA.__bss` | `0x810` | `0x7f0` | **`-0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x3e8` | `0x3f8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x220` | `0x230` | **`+0x10`** |
| `__DATA.__data` | `0x548` | `0x540` | **`-0x8`** |
| `__DATA_DIRTY.__data` | `0x240` | `0x248` | **`+0x8`** |
| `__TEXT.__ustring` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-154.1.5.0.0
+154.1.8.0.0

-  Functions: 2923
-  Symbols:   989
-  CStrings:  1562
+  Functions: 3012
+  Symbols:   1057
+  CStrings:  1600
Symbols:
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
+ _IASignalWritingToolsMailFormattingBarActionDismissed
+ _IASignalWritingToolsMailFormattingBarActionEngaged
+ _IASignalWritingToolsMailFormattingBarActionShown
+ _IATextInputActionsKeyboardTypeFloating
+ _IATextInputActionsKeyboardTypeHardware
+ _IATextInputActionsKeyboardTypeLandscape
+ _IATextInputActionsKeyboardTypePortrait
+ _IATextInputActionsKeyboardTypeSplit
+ _IATextInputActionsKeyboardTypeWebSuffix
+ _IOPSCopyPowerSourcesInfo
+ _IOPSCopyPowerSourcesList
+ _IOPSGetPowerSourceDescription
+ _OBJC_CLASS_$_NSProcessInfo
+ _TIKeyboardVisceralPreference
+ ___NSDictionary0__struct
+ ___exp10
+ _host_statistics
+ _host_statistics64
+ _log10
+ _mach_host_self
+ _mach_port_deallocate
+ _mach_task_self_
+ _vm_kernel_page_size
CStrings:
+ "Current Capacity"
+ "DELETE FROM %@ WHERE rowid != (SELECT rowid FROM %@ ORDER BY %@ DESC LIMIT 1)"
+ "Deleted extra rows from the battery table."
+ "Expiring the battery period that started at %f."
+ "Failed to delete the extra battery table rows: %{private}s"
+ "Failed to delete the extra rows from the battery table. It still has %lu rows."
+ "Failed to prepare the battery table delete statement: %{private}s"
+ "InternalBattery"
+ "KeyboardLatencyAnalytics"
+ "Max Capacity"
+ "P90LatencyMs"
+ "P95LatencyMs"
+ "P99LatencyMs"
+ "PreviewFailed"
+ "[IASKeyboardLatencyAnalyzer] Discarding a sample that is not a finite non-negative number."
+ "[IASKeyboardLatencyAnalyzer] IOPSCopyPowerSourcesInfo returned NULL."
+ "[IASKeyboardLatencyAnalyzer] Initialized analyzer"
+ "[IASKeyboardLatencyAnalyzer] No internal battery among the %lu power source(s)."
+ "[IASKeyboardLatencyAnalyzer] Sample cap %lu reached, dropping the rest."
+ "[IASKeyboardLatencyAnalyzer] Skipping an entry with a non-number key or non-array value."
+ "[IASKeyboardLatencyAnalyzer] Unrecognized input type %lu, reporting as Unspecified."
+ "[IASKeyboardLatencyAnalyzer] Unrecognized keyboard type token, reporting as Unspecified."
+ "[IASKeyboardLatencyAnalyzer] host_statistics(HOST_CPU_LOAD_INFO) failed with %d."
+ "[IASKeyboardLatencyAnalyzer] host_statistics64(HOST_VM_INFO64) failed with %d."
+ "[IASKeyboardLatencyAnalyzer] keystrokeLatenciesMsByInputType is not a dictionary."
+ "autocorrectionEnablement"
+ "candidateBarEnablement"
+ "com.apple.inputAnalytics.keyboardLatency"
+ "com.apple.inputAnalytics.server.IASKeyboardLatencyAnalyzer"
+ "cpuUsage"
+ "failureReasons"
+ "inputType"
+ "maxLatencyMs"
+ "medianLatencyMs"
+ "memoryUsage"
+ "numKeystrokes"
+ "styleEnum"
+ "≡"
```
