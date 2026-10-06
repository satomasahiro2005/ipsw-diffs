## AppPredictionInternal

> `/System/Library/PrivateFrameworks/AppPredictionInternal.framework/AppPredictionInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48e24c` | `0x48ec80` | **`+0xa34`** |
| `__TEXT.__oslogstring` | `0x3ba49` | `0x3bb49` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0xe580` | `0xe640` | **`+0xc0`** |
| `__AUTH_CONST.__cfstring` | `0x3b1e0` | `0x3b240` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xc080` | `0xc0d0` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x8d18` | `0x8d58` | **`+0x40`** |
| `__TEXT.__cstring` | `0x59672` | `0x596b2` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x38e74` | `0x38eac` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x1bf58` | `0x1bf80` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0xf48c` | `0xf4a0` | **`+0x14`** |
| `__DATA_CONST.__objc_arraydata` | `0x12e8` | `0x12f0` | **`+0x8`** |

### Other Changes

```diff

-667.0.0.0.0
+671.0.2.0.0

-  Functions: 25692
-  Symbols:   36740
-  CStrings:  12394
+  Functions: 25704
+  Symbols:   36753
+  CStrings:  12400
Symbols:
+ -[ATXModeMetricsLogUploader uploadNotificationLogsToCoreAnalyticsWithTask:contactStore:completionHandler:]
+ -[ATXNotificationTelemetryLogger logNotificationMetricsFromStartTimestamp:toEndTimestamp:withTask:completionHandler:]
+ -[ATXNotificationTelemetryLogger logNotificationMetricsWithTask:completionHandler:]
+ -[ATXSpotlightLayoutSelector _showAppShortcutsEnabled]
+ -[ATXSuggestionPreprocessor isResumeConversationSuggestion:]
+ GCC_except_table479
+ GCC_except_table491
+ GCC_except_table495
+ GCC_except_table507
+ GCC_except_table511
+ GCC_except_table542
+ GCC_except_table588
+ GCC_except_table593
+ GCC_except_table622
+ GCC_except_table640
+ GCC_except_table79
+ _ATXLaunchReasonComponentWithPrefix
+ _ATXLaunchReasonContainsReason
+ ___106-[ATXModeMetricsLogUploader uploadNotificationLogsToCoreAnalyticsWithTask:contactStore:completionHandler:]_block_invoke
+ ___117-[ATXNotificationTelemetryLogger logNotificationMetricsFromStartTimestamp:toEndTimestamp:withTask:completionHandler:]_block_invoke
+ ___117-[ATXNotificationTelemetryLogger logNotificationMetricsFromStartTimestamp:toEndTimestamp:withTask:completionHandler:]_block_invoke_2
+ ___65-[ATXNotificationTelemetryLogger logNotificationMetricsWithTask:]_block_invoke
+ ___83-[ATXNotificationTelemetryLogger logNotificationMetricsWithTask:completionHandler:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48bs_e8_v12?0B8ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e8_v12?0B8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72bs_e17_v16?0"NSArray"8ls32l8s40l8s48l8s72l8s56l8s64l8
- -[ATXModeMetricsLogUploader uploadNotificationLogsToCoreAnalyticsWithTask:contactStore:]
- GCC_except_table477
- GCC_except_table490
- GCC_except_table494
- GCC_except_table506
- GCC_except_table510
- GCC_except_table541
- GCC_except_table587
- GCC_except_table592
- GCC_except_table621
- GCC_except_table639
- ___99-[ATXNotificationTelemetryLogger logNotificationMetricsFromStartTimestamp:toEndTimestamp:withTask:]_block_invoke_2
- ___block_descriptor_80_e8_32s40s48s56s64s_e17_v16?0"NSArray"8ls32l8s40l8s48l8s56l8s64l8
CStrings:
+ "Blending: Suppressing Resume Conversation suggestion from UI surface: %{public}@"
+ "Notification metrics logging task deferred; not marking DONE"
+ "PRAGMA cache_size = -512"
+ "Returning %lu recent settings actions"
+ "SLS: [AppShortcut] Show App Shortcuts setting off; skipping generation"
+ "SuggestionsSpotlightAppShortcutsEnabled"
```
