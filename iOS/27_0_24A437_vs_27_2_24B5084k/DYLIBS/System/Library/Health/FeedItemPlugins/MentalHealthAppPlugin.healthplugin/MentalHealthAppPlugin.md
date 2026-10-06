## MentalHealthAppPlugin

> `/System/Library/Health/FeedItemPlugins/MentalHealthAppPlugin.healthplugin/MentalHealthAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb78cc` | `0xbd610` | **`+0x5d44`** |
| `__DATA.__bss` | `0x4840` | `0x4bc0` | **`+0x380`** |
| `__TEXT.__const` | `0x5f24` | `0x61c4` | **`+0x2a0`** |
| `__AUTH_CONST.__auth_got` | `0x27c0` | `0x2a40` | **`+0x280`** |
| `__AUTH_CONST.__const` | `0x3f00` | `0x40b0` | **`+0x1b0`** |
| `__AUTH.__data` | `0x14b0` | `0x15e0` | **`+0x130`** |
| `__AUTH_CONST.__objc_const` | `0x1860` | `0x1980` | **`+0x120`** |
| `__TEXT.__eh_frame` | `0x1db4` | `0x1ecc` | **`+0x118`** |
| `__DATA.__data` | `0x2938` | `0x2a40` | **`+0x108`** |
| `__DATA_CONST.__got` | `0x1500` | `0x1608` | **`+0x108`** |
| `__TEXT.__swift5_reflstr` | `0x1573` | `0x164e` | **`+0xdb`** |
| `__TEXT.__unwind_info` | `0x25b0` | `0x2668` | **`+0xb8`** |
| `__TEXT.__oslogstring` | `0x14fb` | `0x1466` | **`-0x95`** |
| `__TEXT.__swift5_fieldmd` | `0x1660` | `0x16e8` | **`+0x88`** |
| `__TEXT.__constg_swiftt` | `0x2448` | `0x24c0` | **`+0x78`** |
| `__DATA_DIRTY.__data` | `0xfa8` | `0xf48` | **`-0x60`** |
| `__TEXT.__swift5_typeref` | `0x2184` | `0x21d8` | **`+0x54`** |
| `__TEXT.__swift5_capture` | `0xa30` | `0xa70` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0x770` | `0x798` | **`+0x28`** |
| `__TEXT.__cstring` | `0x3b4e` | `0x3b73` | **`+0x25`** |
| `__TEXT.__swift5_proto` | `0x354` | `0x370` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x8d8` | `0x8c0` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x234` | `0x244` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x16c` | `0x164` | **`-0x8`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/HealthContent.framework/HealthContent
+  - /System/Library/PrivateFrameworks/HealthContentUI.framework/HealthContentUI

+  - /System/Library/PrivateFrameworks/HealthReportCoreUI.framework/HealthReportCoreUI

+  - /System/Library/PrivateFrameworks/SurveyKit.framework/SurveyKit

-  Functions: 3320
-  Symbols:   341
+  Functions: 3377
+  Symbols:   340
Symbols:
+ _swift_cvw_enumFn_getEnumTag
- _OBJC_CLASS_$_HKSource
- _OBJC_CLASS_$_UIApplication
CStrings:
+ "ASSESSMENT_RESULTS_RESOURCE_CALL_PROVIDER_LABEL_%@"
+ "ASSESSMENT_RESULTS_RESOURCE_SMS_PROVIDER_LABEL_%@"
+ "MentalHealthAppPlugin/ResourcesListView.swift"
+ "[%{public}s] Missing escalation for escalation id: %s"
+ "level indicatedSuicideRisk metadata "
+ "level metadata "
+ "text.bubble.fill"
- "%s could not query for latest sample, predicate is nil"
- "%s unable to create Health App HKSource"
- "%s unable to create Journal App HKSource"
- "%s: Unexpectedly received more than one sample."
- "MentalHealthAppPlugin/ContentConfigurationItem+MentalHealth.swift"
- "MentalHealthAppPlugin/MentalHealthOptionsComponent.swift"
- "MentalHealthAppPlugin/StateOfMindLoggingPromotionActionHandler.swift"
```
