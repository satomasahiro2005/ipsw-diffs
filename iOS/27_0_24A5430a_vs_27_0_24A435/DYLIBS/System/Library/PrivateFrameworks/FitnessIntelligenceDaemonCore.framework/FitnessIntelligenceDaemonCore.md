## FitnessIntelligenceDaemonCore

> `/System/Library/PrivateFrameworks/FitnessIntelligenceDaemonCore.framework/FitnessIntelligenceDaemonCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x517a0` | `0x55794` | **`+0x3ff4`** |
| `__TEXT.__eh_frame` | `0x549c` | `0x585c` | **`+0x3c0`** |
| `__DATA.__bss` | `0x1410` | `0x1590` | **`+0x180`** |
| `__AUTH_CONST.__auth_got` | `0x1080` | `0x11e0` | **`+0x160`** |
| `__TEXT.__const` | `0x2310` | `0x2450` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x77b` | `0x89b` | **`+0x120`** |
| `__AUTH.__data` | `0x6d0` | `0x778` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x1ad0` | `0x1b68` | **`+0x98`** |
| `__DATA.__data` | `0x840` | `0x8a8` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x13b7` | `0x1409` | **`+0x52`** |
| `__TEXT.__cstring` | `0x7dd` | `0x81d` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x86c` | `0x8a4` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x1578` | `0x15a8` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x730` | `0x758` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x548` | `0x570` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x210` | `0x238` | **`+0x28`** |
| `__TEXT.__swift5_assocty` | `0x138` | `0x150` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x4c8` | `0x4dc` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x1d0` | `0x1e4` | **`+0x14`** |
| `__TEXT.__swift5_reflstr` | `0x6c1` | `0x6d1` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xe8` | `0xf4` | **`+0xc`** |
| `__DATA_DIRTY.__data` | `0x8c8` | `0x8d0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x7c` | `0x80` | **`+0x4`** |

### Other Changes

```diff

+  - /System/Library/PrivateFrameworks/AppliedSensingFitness.framework/AppliedSensingFitness
+  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

-  Functions: 1350
-  Symbols:   695
-  CStrings:  81
+  Functions: 1387
+  Symbols:   708
+  CStrings:  88
Symbols:
+ _FIIsTinkerVegaOrFitnessJunior
+ ___swift_closure_destructor.21Tm
+ _associated conformance 29FitnessIntelligenceDaemonCore0A21ContextReadinessQueryVAA0aeG0AA10ResultTypeAaDP_0aB00aE9Component
+ _associated conformance 29FitnessIntelligenceDaemonCore0A21ContextReadinessQueryVSHAASQ
+ _symbolic SiSg
+ _symbolic _____ 19FitnessIntelligence16ReadinessContextV
+ _symbolic _____ 29FitnessIntelligenceDaemonCore0A21ContextReadinessQueryV
+ _symbolic _____Sg 19FitnessIntelligence15TrainingLoadDayV
+ _symbolic _____Sg 19FitnessIntelligence15TrainingLoadDayV5StateO
+ _symbolic _____Sg 19FitnessIntelligence16ReadinessContextV
+ _symbolic _____Sg 21AppliedSensingFitness14ReadinessValueV
+ _symbolic _____Sg 21AppliedSensingFitness22ReadinessCategoryLabelO
+ _symbolic _____Sg 21AppliedSensingFitness24DaytimeMetricsParametersV
CStrings:
+ "%s Hardware Requirement for Readiness %{bool}d and override %{bool}d"
+ "%s readiness score %s and label %s"
+ "Failed to get Readiness Context. Error=%@"
+ "Readiness algorithm parameters "
+ "Readiness is not supported on Tinker, Vega, or Fitness Junior devices"
+ "ReadinessContext"
+ "Unhandled TrainingLoadBand: %s"
```
