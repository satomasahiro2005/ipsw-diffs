## IntelligenceFlowRuntime

> `/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/IntelligenceFlowRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdac780` | `0xdb43e8` | **`+0x7c68`** |
| `__TEXT.__eh_frame` | `0x79858` | `0x79e10` | **`+0x5b8`** |
| `__TEXT.__oslogstring` | `0x41abc` | `0x41f2c` | **`+0x470`** |
| `__AUTH_CONST.__const` | `0x5aff0` | `0x5b3b0` | **`+0x3c0`** |
| `__TEXT.__unwind_info` | `0x2b820` | `0x2b528` | **`-0x2f8`** |
| `__TEXT.__swift5_capture` | `0x16888` | `0x169f8` | **`+0x170`** |
| `__TEXT.__cstring` | `0x22463` | `0x22513` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x13d3d` | `0x13d9d` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x182e8` | `0x18340` | **`+0x58`** |
| `__TEXT.__swift_as_cont` | `0x5584` | `0x55d4` | **`+0x50`** |
| `__TEXT.__const` | `0x78f88` | `0x78fc8` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x18528` | `0x18554` | **`+0x2c`** |
| `__TEXT.__swift_as_ret` | `0x30c4` | `0x30e8` | **`+0x24`** |
| `__DATA.__data` | `0xe568` | `0xe588` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x2598` | `0x25b0` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x1d71d` | `0x1d731` | **`+0x14`** |

### Other Changes

```diff

-3605.22.501.10.0
+3605.22.501.11.0

-  Functions: 70067
+  Functions: 70234

-  CStrings:  6744
+  CStrings:  6759
CStrings:
+ "%ld entities"
+ "%s RiskResolver#isResolvedParameterValueShared: shared=%{bool,public}d reason=%{public}s preResolved=%{public}ld hydrated=%{public}ld skipped=[%{public}s]"
+ "%s RiskResolver#shouldConfirm: insert_text personalSearchInContext=%{bool,public}d — %{public}s confirmation"
+ "%s RiskResolver#shouldConfirm: suppressing confirmation for tool '%{public}s'. Every URL it carries came from the user utterance."
+ "Risk Assessment - Insert Text"
+ "Risk Assessment - Shared Entity"
+ "Risk Assessment - Web Content"
+ "RiskResolver#hydratedEntities: hydration failed for %{public}ld entities, treating as shared: errorCode=%{public}ld"
+ "RiskResolver#sharednessOutcome: hydrated entity carries no sharedness property, treating as not shared: type=%{public}s protocols=[%{public}s]"
+ "RiskResolver.sharednessHydration"
+ "[StandardRepresentationResolver] #resolve %s skips hydration, returning the standard representation with the app"
+ "[VideoAppResolver] #isTVSearchAppAvailable TVSearch tool lookup failed: %{sensitive}@"
+ "[VideoAppResolver] #isTVSearchAppAvailable no TVSearch tool found"
+ "[VideoAppResolver] #runAppSelection Apple TV freeform with no app mention: skipping SiriKit app selection, resolving to %s."
+ "leaving upstream decision"
```
