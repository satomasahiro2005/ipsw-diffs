## WellnessFlowPlugin

> `/System/Library/Assistant/FlowDelegatePlugins/WellnessFlowPlugin.bundle/WellnessFlowPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16370c` | `0x166c78` | **`+0x356c`** |
| `__TEXT.__swift5_typeref` | `0x3083` | `0x33cd` | **`+0x34a`** |
| `__TEXT.__const` | `0xaec0` | `0xb020` | **`+0x160`** |
| `__TEXT.__swift5_fieldmd` | `0x5ec4` | `0x600c` | **`+0x148`** |
| `__TEXT.__swift5_reflstr` | `0x70c5` | `0x71e5` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x6da3` | `0x6ea3` | **`+0x100`** |
| `__DATA.__data` | `0x6a50` | `0x6b28` | **`+0xd8`** |
| `__TEXT.__eh_frame` | `0xf0f8` | `0xf188` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x5618` | `0x56a0` | **`+0x88`** |
| `__DATA.__bss` | `0xb630` | `0xb6b0` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x7ab0` | `0x7b18` | **`+0x68`** |
| `__TEXT.__constg_swiftt` | `0x40f8` | `0x4150` | **`+0x58`** |
| `__TEXT.__swift5_assocty` | `0x5b8` | `0x5d0` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xd88` | `0xd98` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xfa0` | `0xf90` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x33a0` | `0x3390` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x1150` | `0x1160` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x19d8` | `0x19d0` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x5d0` | `0x5d4` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x328` | `0x32c` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0xd68` | `0xd6c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xae4` | `0xae8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-3600.12.4.1.1
+3600.12.12.0.0

-  Functions: 7848
+  Functions: 7898

-  CStrings:  1604
+  CStrings:  1608
CStrings:
+ "#GenerateLoggingResponseOutput: Snippet dialog is %{sensitive}s"
+ "#GetActivitySummaryFlow: dialog is %{sensitive}s"
+ "#GetActivitySummaryFlow: snippet header model is %{sensitive}s"
+ "#GetActivitySummaryFlow: snippet model is %{sensitive}s"
+ "#GetBloodPressureFlow: snippet model is %{sensitive}s"
+ "#GetHealthQuantityFlow: In successResponseFlow intent is %{sensitive}@"
+ "#GetHealthQuantityFlow: In successResponseFlow intent response is %{sensitive}@"
+ "#GetSleepAnalysisFlow: output is %{sensitive}s"
+ "#GetSleepAnalysisFlow: snippet model is %{sensitive}s"
+ "Executing intent: %{sensitive}@"
+ "Failed to produce patternResult from response"
+ "LogPeriodIntentResponse missing date param"
+ "Received response: %{sensitive}@"
+ "Recommendation: %{sensitive}s"
+ "Recommended INDateComponentsRange: %{sensitive}@"
+ "Recommended dateInterval: %{sensitive}s"
- "#GenerateLoggingResponseOutput: Snippet dialog is %s"
- "#GetActivitySummaryFlow: dialog is %s"
- "#GetActivitySummaryFlow: snippet header model is %s"
- "#GetActivitySummaryFlow: snippet model is %s"
- "#GetBloodPressureFlow: snippet model is %s"
- "#GetHealthQuantityFlow: In successResponseFlow intent is %@"
- "#GetHealthQuantityFlow: In successResponseFlow intent response is %@"
- "#GetSleepAnalysisFlow: output is %s"
- "#GetSleepAnalysisFlow: snippet model is %s"
- "Failed to produce patternResult from response: %@"
- "LogPeriodIntentResponse missing date param: %@"
- "Recommendation: %s"
```
