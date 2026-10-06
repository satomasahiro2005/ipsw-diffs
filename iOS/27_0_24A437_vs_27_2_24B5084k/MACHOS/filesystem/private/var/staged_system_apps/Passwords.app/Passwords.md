## Passwords

> `/private/var/staged_system_apps/Passwords.app/Passwords`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75c0` | `0x6414` | **`-0x11ac`** |
| `__TEXT.__auth_stubs` | `0xad0` | `0xba0` | **`+0xd0`** |
| `__DATA.__data` | `0x5a8` | `0x508` | **`-0xa0`** |
| `__DATA_CONST.__auth_got` | `0x570` | `0x5d8` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x378` | `0x3d0` | **`+0x58`** |
| `__TEXT.__objc_methname` | `0x576` | `0x5c6` | **`+0x50`** |
| `__DATA.__objc_const` | `0x2e0` | `0x320` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x133` | `0x163` | **`+0x30`** |
| `__DATA.__objc_data` | `0x110` | `0x130` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0xc8` | `0xa8` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x280` | `0x260` | **`-0x20`** |
| `__TEXT.__const` | `0x494` | `0x4a4` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x484` | `0x478` | **`-0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x258` | `0x250` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x220` | `0x218` | **`-0x8`** |
| `__TEXT.__eh_frame` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x2d4` | `0x2d8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-625.1.29.10.29
+625.2.4.1.0

-  Functions: 171
-  Symbols:   345
-  CStrings:  83
+  Functions: 158
+  Symbols:   357
+  CStrings:  85
Symbols:
+ _$s17PasswordManagerUI011PMAutomaticA24ChangeCompletionReporterV10SafariCore012WBSAutomaticaeF9ReportingAAMc
+ _$s17PasswordManagerUI011PMAutomaticA24ChangeCompletionReporterVACycfC
+ _$s17PasswordManagerUI011PMAutomaticA24ChangeCompletionReporterVMa
+ _$s17PasswordManagerUI14PMAccountStoreC19websiteNameProviderSo015WBSSavedAccounte7WebsitegH0_pSgvgTj
+ _$s17PasswordManagerUI17PMDependencyStoreC21accountIconControllerSo011_ASPasswordbgH0CSgvg
+ _$s17PasswordManagerUI17PMDependencyStoreC21accountIconControllerSo011_ASPasswordbgH0CSgvpMV
+ _$s17PasswordManagerUI17PMDependencyStoreC21accountIconControllerSo011_ASPasswordbgH0CSgvs
+ _$s17PasswordManagerUI18PMPausableFetchingMp
+ _$s17PasswordManagerUI21PMAppLifecycleMonitorC24addDidBecomeActiveActionyyyycF
+ _$s17PasswordManagerUI21PMAppLifecycleMonitorC26addPausableFetchingServiceyyAA010PMPausableI0_pF
+ _$s17PasswordManagerUI21PMAppLifecycleMonitorCACycfC
+ _$s17PasswordManagerUI21PMAppLifecycleMonitorCMa
+ _$s17PasswordManagerUI21PMAppLifecycleMonitorCMn
+ _$sSo20WBSSavedAccountStoreC10SafariCoreE52markUnprocessedAutomaticSecurityUpgradeTasksAsFailed15currentDeviceID08securityjC08reporterySS_AC0abiJ7Storing_pAC45WBSAutomaticPasswordChangeCompletionReporting_ptYaF
+ _$sSo20WBSSavedAccountStoreC10SafariCoreE52markUnprocessedAutomaticSecurityUpgradeTasksAsFailed15currentDeviceID08securityjC08reporterySS_AC0abiJ7Storing_pAC45WBSAutomaticPasswordChangeCompletionReporting_ptYaFTu
+ _$sSo32_ASPasswordManagerIconControllerC08PasswordB2UI18PMPausableFetchingACWP
+ _objc_retain_x28
+ _objc_retain_x8
+ _swift_beginAccess
+ _swift_conformsToProtocol2
+ _swift_release_n
+ _swift_retain_n
+ _swift_retain_x8
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
- _$s7SwiftUI10ScenePhaseO10backgroundyA2CmFWC
- _$s7SwiftUI10ScenePhaseO6activeyA2CmFWC
- _$s7SwiftUI10ScenePhaseO8inactiveyA2CmFWC
- _$s7SwiftUI10ScenePhaseOMa
- _$s7SwiftUI10ScenePhaseOMn
- _$s7SwiftUI10ScenePhaseOSQAAMc
- _$s7SwiftUI14ObservedObjectVMa
- _$s7SwiftUI17EnvironmentValuesV10scenePhaseAA05SceneF0Ovg
- _$s7SwiftUI17EnvironmentValuesV10scenePhaseAA05SceneF0OvpMV
- _$s7SwiftUI17EnvironmentValuesV10scenePhaseAA05SceneF0Ovs
- _$s7SwiftUI5ScenePAAE8onChange2of7initial_Qrqd___SbyyctSQRd__lF
- _$s7SwiftUI5ScenePAAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQOMQ
- _$sSo20WBSSavedAccountStoreC10SafariCoreE52markUnprocessedAutomaticSecurityUpgradeTasksAsFailed15currentDeviceID08securityjC0ySS_AC0abiJ7Storing_ptYaFZ
- _$sSo20WBSSavedAccountStoreC10SafariCoreE52markUnprocessedAutomaticSecurityUpgradeTasksAsFailed15currentDeviceID08securityjC0ySS_AC0abiJ7Storing_ptYaFZTu
CStrings:
+ "_TtC9Passwords19AppLifecycleActions"
+ "_accountIconController"
+ "appLifecycleMonitor"
- "_TtC9Passwords16AppLaunchActions"
```
