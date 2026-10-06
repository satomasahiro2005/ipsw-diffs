## PrivacySettingsUI

> `/System/Library/PrivateFrameworks/Settings/PrivacySettingsUI.framework/PrivacySettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x71e0` | `0x7360` | **`+0x180`** |
| `__TEXT.__text` | `0x69b40` | `0x69c44` | **`+0x104`** |
| `__TEXT.__cstring` | `0x85d4` | `0x8694` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0xab0` | `0xad8` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0xad8` | `0xaf8` | **`+0x20`** |
| `__TEXT.__const` | `0x534` | `0x524` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x1ac` | `0x1bc` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x18b0` | `0x18c0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xe3` | `0xec` | **`+0x9`** |
| `__DATA.__data` | `0x600` | `0x5f8` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x542` | `0x544` | **`+0x2`** |

### Other Changes

```diff

-2027.1.5.1.100
+2027.1.7.0.0

-  Functions: 2176
-  Symbols:   3773
-  CStrings:  1441
+  Functions: 2178
+  Symbols:   3778
+  CStrings:  1452
Symbols:
+ ___swift__destructor
+ _swift_getFunctionTypeMetadata0
+ _swift_release_x24
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _symbolic ______pSgXw 17PrivacySettingsUI36PUILockdownModeLearnMoreActionTargetP
+ _symbolic y_____c 10Foundation3URLV
- _swift_release_x23
- _symbolic ______p 17PrivacySettingsUI36PUILockdownModeLearnMoreActionTargetP
- _symbolic ______pSg 17PrivacySettingsUI36PUILockdownModeLearnMoreActionTargetP
CStrings:
+ "AppAnalytics"
+ "CloudTelemetry"
+ "DiagnosticPipeline"
+ "DifferentialPrivacy"
+ "DistributedEvaluation"
+ "PerformanceTraces"
+ "PhotoLibrary"
+ "SpotlightMetadata"
+ "SymptomDiagnosticReporter"
+ "reportType"
+ "sysdiagnose"
```
