## CoreRoutineDiagnostics

> `/System/Library/PrivateFrameworks/CoreRoutineDiagnostics.framework/CoreRoutineDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x1860` | `0x1940` | **`+0xe0`** |
| `__TEXT.__text` | `0xeda4` | `0xee74` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x172f` | `0x17c7` | **`+0x98`** |
| `__TEXT.__oslogstring` | `0x1c05` | `0x1c9a` | **`+0x95`** |
| `__TEXT.__ustring` | `—` | `0x7c` | **`+0x7c`** |
| `__DATA_CONST.__const` | `0x560` | `0x5d8` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0x390` | `0x3cc` | **`+0x3c`** |
| `__AUTH_CONST.__objc_intobj` | `0x108` | `0x120` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xb24` | `0xb14` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x900` | `0x8f8` | **`-0x8`** |
| `__TEXT.__const` | `0x178` | `0x170` | **`-0x8`** |

### Other Changes

```diff

-1109.0.3.0.0
+1114.0.0.0.0

-  Symbols:   677
-  CStrings:  360
+  Symbols:   667
+  CStrings:  370
Symbols:
+ GCC_except_table21
+ GCC_except_table25
+ GCC_except_table38
+ GCC_except_table40
+ _RTBugCaptureCategoryString
+ ___block_descriptor_104_e8_32s40s48s56s64s72bs80r_e17_v16?0"NSArray"8ls32l8s40l8s48l8r80l8s56l8s64l8s72l8
+ ___block_descriptor_80_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s56l8s48l8
+ ___block_descriptor_88_e8_32s40s48s56s64bs_e8_v12?0B8ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_89_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ __os_feature_enabled_impl
+ _kRTBugCaptureCategoryStrings
+ _kRTBugCaptureMetricKeySuppressedPromptingDisabled
- -[RTBugCaptureManager _backoffPeriodForCategory:]
- GCC_except_table22
- GCC_except_table26
- GCC_except_table39
- GCC_except_table41
- ___block_descriptor_80_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
- ___block_descriptor_80_e8_32s40s48s56s64bs_e8_v12?0B8ls32l8s40l8s48l8s56l8s64l8
- ___block_descriptor_81_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
- ___block_descriptor_96_e8_32s40s48s56s64s72bs80r_e17_v16?0"NSArray"8ls32l8s40l8s48l8r80l8s56l8s64l8s72l8
- _kRTBugCaptureCategoryBackgroundTaskHighFailureRate
- _kRTBugCaptureCategoryBackgroundTaskSchedulingViolation
- _kRTBugCaptureCategoryCombinedPerformanceViolation
- _kRTBugCaptureCategoryDataIntegrityViolation
- _kRTBugCaptureCategoryExceptionCaught
- _kRTBugCaptureCategoryHighCPUDetected
- _kRTBugCaptureCategoryHighLatencyDetected
- _kRTBugCaptureCategoryIpsDetected
- _kRTBugCaptureCategoryLOIUUIDStabilityIssueDetected
- _kRTBugCaptureCategoryLongProcessInit
- _kRTBugCaptureCategoryMemoryThresholdExceeded
- _kRTBugCaptureCategorySemaphoreHangDetected
- _kRTBugCaptureCategoryVisitGapDetected
CStrings:
+ "%@, %@, unknown category, %lu, metricType, %{public}@"
+ "Bug capture called with invalid category value"
+ "Bug capture called with invalid category value: %lu"
+ "Bug capture prompts disabled by user"
+ "Bug capture suppressed by user until 90-day period expires"
+ "Bug capture suppressed for reason: %{public}@ (category: %{public}@, backoff not elapsed)"
+ "Bug capture suppressed for reason: %{public}@ (user has disabled radar filing prompts)"
+ "Bug capture suppressed for reason: %{public}@ (user selected 'Stop Asking for 90 days' - suppressed until %@)"
+ "Bug capture suppressed — category rotation window not elapsed"
+ "BugCaptureDailySuppressedPromptingDisabled"
+ "Category '%{public}@' rotation window not elapsed (%.0fs since last filing, %.0fs required)"
+ "Global rate limit active (%.0fs since last filing, %.0fs required)"
+ "RBCRadarPrompts"
+ "Starvation escape triggered for '%{public}@' (%.0fs since last filing, %.0fs threshold)"
+ "Stop Asking (for 90 days)"
+ "Uncategorized"
+ "User selected 'Stop Asking (for 90 days)' for reason, %@"
+ "rotationWindowPeriod"
+ "starvationWindowPeriod"
+ "suppressedPromptingDisabled"
+ "suppressed_prompting_disabled"
- "%@, %@, unknown category, %{public}@, metricType, %{public}@"
- "Bug capture suppressed - backoff period not elapsed (category: %.0fs, global: %.0fs)"
- "Bug capture suppressed by user until 30-day period expires"
- "Bug capture suppressed for reason: %{public}@ (category: %{public}@, backoff period not elapsed)"
- "Bug capture suppressed for reason: %{public}@ (user selected 'Stop Asking for 30 days' - suppressed until %@)"
- "Category '%{public}@' backoff not elapsed (%.0fs since last filing, %.0fs required)"
- "Global backoff not elapsed (%.0fs since last filing of any category, %.0fs required)"
- "Invalid parameter not satisfying: category (in %s:%d)"
- "Stop Asking (for 30 days)"
- "User selected 'Stop Asking (for 30 days)' for reason, %@"
- "categoryBackoffPeriod"
```
