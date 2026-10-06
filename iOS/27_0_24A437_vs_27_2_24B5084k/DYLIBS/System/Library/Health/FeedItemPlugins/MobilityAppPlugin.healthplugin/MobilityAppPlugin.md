## MobilityAppPlugin

> `/System/Library/Health/FeedItemPlugins/MobilityAppPlugin.healthplugin/MobilityAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x409b0` | `0x411a8` | **`+0x7f8`** |
| `__DATA.__bss` | `0x2280` | `0x2080` | **`-0x200`** |
| `__AUTH_CONST.__auth_got` | `0x1388` | `0x1500` | **`+0x178`** |
| `__TEXT.__eh_frame` | `0x5f8` | `0x690` | **`+0x98`** |
| `__TEXT.__const` | `0x2ba4` | `0x2b14` | **`-0x90`** |
| `__AUTH_CONST.__const` | `0x1538` | `0x15a0` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x748` | `0x6f8` | **`-0x50`** |
| `__TEXT.__swift5_reflstr` | `0x538` | `0x57a` | **`+0x42`** |
| `__TEXT.__cstring` | `0x2942` | `0x2975` | **`+0x33`** |
| `__TEXT.__objc_methlist` | `0x60c` | `0x5dc` | **`-0x30`** |
| `__TEXT.__swift5_assocty` | `0x1d8` | `0x1a8` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x1010` | `0xff0` | **`-0x20`** |
| `__DATA.__data` | `0x970` | `0x958` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0xa32` | `0xa1e` | **`-0x14`** |
| `__TEXT.__constg_swiftt` | `0xdac` | `0xd9c` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x244` | `0x234` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x704` | `0x710` | **`+0xc`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

+  - /System/Library/Frameworks/SwiftUI.framework/SwiftUI

+  - /System/Library/PrivateFrameworks/HealthAppServices.framework/HealthAppServices

+  - /System/Library/PrivateFrameworks/HealthDomains.framework/HealthDomains
+  - /System/Library/PrivateFrameworks/HealthDomainsUI.framework/HealthDomainsUI

+  - /System/Library/PrivateFrameworks/HealthFoundationUI.framework/HealthFoundationUI

+  - /System/Library/PrivateFrameworks/HealthReportCoreUI.framework/HealthReportCoreUI

-  Functions: 1158
-  Symbols:   272
-  CStrings:  267
+  Functions: 1162
+  Symbols:   271
+  CStrings:  270
Symbols:
+ _OBJC_CLASS_$_LSApplicationWorkspace
+ _swift_cvw_enumFn_getEnumTag
+ _swift_task_deinitOnExecutor
- _OBJC_CLASS_$_NSCollectionLayoutGroup
- _OBJC_CLASS_$_NSCollectionLayoutItem
- _OBJC_CLASS_$_UIApplication
- _objc_retain_x2
CStrings:
+ "ESCALATION_BODY_LOW"
+ "ESCALATION_BODY_LOW_PREGNANCY"
+ "ESCALATION_BODY_VERY_LOW"
+ "ESCALATION_BODY_VERY_LOW_PREGNANCY"
+ "Guidance.DiscussWithYourDoctorAtNextAppointment.Body"
+ "Guidance.DiscussWithYourDoctorAtNextAppointment.Title"
- "MobilityAppPlugin/ImproveWalkingSteadinessArticleDataProvider.swift"
- "MobilityAppPlugin/MobilityAppPluginAppDelegate.swift"
- "MobilityAppPlugin/WalkingSteadinessChartOrOnboardingComponent.swift"
```
