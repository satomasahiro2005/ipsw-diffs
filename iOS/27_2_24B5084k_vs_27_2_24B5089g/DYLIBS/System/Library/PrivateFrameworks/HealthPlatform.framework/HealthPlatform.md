## HealthPlatform

> `/System/Library/PrivateFrameworks/HealthPlatform.framework/HealthPlatform`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2809d8` | `0x28779c` | **`+0x6dc4`** |
| `__DATA.__bss` | `0x19ef0` | `0x180f0` | **`-0x1e00`** |
| `__DATA_DIRTY.__bss` | `0x8380` | `0xa180` | **`+0x1e00`** |
| `__DATA_DIRTY.__data` | `0x6ec8` | `0x8c58` | **`+0x1d90`** |
| `__AUTH.__data` | `0x2ef0` | `0x1a90` | **`-0x1460`** |
| `__DATA.__data` | `0x42d0` | `0x3a40` | **`-0x890`** |
| `__TEXT.__eh_frame` | `0xabcc` | `0xb0f4` | **`+0x528`** |
| `__AUTH_CONST.__const` | `0x15878` | `0x15bd0` | **`+0x358`** |
| `__DATA_DIRTY.__objc_data` | `0x1078` | `0x1248` | **`+0x1d0`** |
| `__AUTH.__objc_data` | `0xeb0` | `0xce8` | **`-0x1c8`** |
| `__TEXT.__unwind_info` | `0x9058` | `0x91e8` | **`+0x190`** |
| `__TEXT.__oslogstring` | `0x698c` | `0x6afc` | **`+0x170`** |
| `__TEXT.__swift5_capture` | `0x3764` | `0x3890` | **`+0x12c`** |
| `__TEXT.__const` | `0x177d0` | `0x178e0` | **`+0x110`** |
| `__TEXT.__swift5_typeref` | `0x6776` | `0x683c` | **`+0xc6`** |
| `__TEXT.__swift5_reflstr` | `0x5a57` | `0x5ae7` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x695c` | `0x69c4` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x7928` | `0x7978` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x75e4` | `0x7634` | **`+0x50`** |
| `__TEXT.__cstring` | `0x6cc5` | `0x6d15` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x6d4` | `0x714` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x2730` | `0x2768` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0xc8c` | `0xcbc` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x280` | `0x2a8` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x244` | `0x268` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x16c8` | `0x16e8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x11e0` | `0x11f8` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xcb0` | `0xcc0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x8cc` | `0x8d4` | **`+0x8`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 13993
-  Symbols:   3333
-  CStrings:  1088
+  Functions: 14089
+  Symbols:   3348
+  CStrings:  1093
Symbols:
+ _OBJC_CLASS_$_HKSPSleepScheduleModel
+ ___swift_assign_boxed_opaque_existential_0
+ ___swift_closure_destructor.10Tm
+ ___swift_closure_destructor.19Tm
+ _symbolic Say______pG 14HealthPlatform0A41AppPluginDailyAnalyticsPayloadContributorP
+ _symbolic So12NSDictionaryCSgSo7NSErrorCSgIeyBhyy_
+ _symbolic So22HKSPSleepScheduleModelC
+ _symbolic So22HKSPSleepScheduleModelCSg
+ _symbolic So32HKAnalyticsEnvironmentDataSourceC
+ _symbolic _____ 14HealthPlatform21DashboardAvailabilityO
+ _symbolic _____ 14HealthPlatform30DailyAnalyticsPayloadCollectorV
+ _symbolic _____SgXwz_Xx 14HealthPlatform29UpcomingSleepScheduleProviderC
+ _symbolic _____ySbG 19HealthOrchestration25IndependentAtomicPropertyV
+ _symbolic ytSgIeAgHr_
+ _type_layout_string 14HealthPlatform30DailyAnalyticsPayloadCollectorV
CStrings:
+ "[%{public}s] %{public}s failed to build its %{public}s daily analytics payload: %{public}s"
+ "[%{public}s] %{public}s returned %{public}s daily analytics key %{public}s, which another contributor already provided; dropping the later value."
+ "[%{public}s] Error loading sleep schedule model: %{public}s"
+ "[%{public}s]: XPC request received to gather IH&A gated daily analytics payload"
+ "[%{public}s]: XPC request received to gather unrestricted daily analytics payload"
+ "_createCheckedThrowingContinuation(_:)"
+ "pinnedContentIdentifier"
- "[%{public}s] Error loading upcoming resolved occurrence: %{public}s"
- "[%{public}s] Failed to get initial state: %s"
```
