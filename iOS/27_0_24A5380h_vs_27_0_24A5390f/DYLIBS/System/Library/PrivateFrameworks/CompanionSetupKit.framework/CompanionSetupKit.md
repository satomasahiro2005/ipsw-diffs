## CompanionSetupKit

> `/System/Library/PrivateFrameworks/CompanionSetupKit.framework/CompanionSetupKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4039e0` | `0x40b1bc` | **`+0x77dc`** |
| `__TEXT.__eh_frame` | `0x35230` | `0x35618` | **`+0x3e8`** |
| `__TEXT.__const` | `0x2ce90` | `0x2d240` | **`+0x3b0`** |
| `__TEXT.__oslogstring` | `0x8775` | `0x8a75` | **`+0x300`** |
| `__TEXT.__cstring` | `0xb7ad` | `0xb93d` | **`+0x190`** |
| `__TEXT.__unwind_info` | `0x12640` | `0x127b0` | **`+0x170`** |
| `__AUTH_CONST.__const` | `0x18828` | `0x18968` | **`+0x140`** |
| `__DATA.__bss` | `0x45200` | `0x45300` | **`+0x100`** |
| `__TEXT.__swift5_typeref` | `0x97a0` | `0x9880` | **`+0xe0`** |
| `__AUTH_CONST.__objc_const` | `0x7038` | `0x7110` | **`+0xd8`** |
| `__DATA.__data` | `0x89e8` | `0x8ab8` | **`+0xd0`** |
| `__AUTH.__data` | `0x5470` | `0x5520` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1820` | `0x18b8` | **`+0x98`** |
| `__TEXT.__swift_as_ret` | `0x153c` | `0x15d4` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x690c` | `0x6990` | **`+0x84`** |
| `__TEXT.__swift_as_entry` | `0x1068` | `0x10ec` | **`+0x84`** |
| `__TEXT.__swift5_fieldmd` | `0x9034` | `0x90ac` | **`+0x78`** |
| `__TEXT.__swift5_reflstr` | `0x7ade` | `0x7b3e` | **`+0x60`** |
| `__TEXT.__swift_as_cont` | `0x35e4` | `0x3634` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x12e0` | `0x1318` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0x14e0` | `0x1510` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x36e4` | `0x370c` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x11c8` | `0x11e8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2510` | `0x2528` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0xa84` | `0xa90` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x270` | `0x278` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x2288` | `0x2290` | **`+0x8`** |

### Other Changes

```diff

-524.0.26.0.0
+524.0.38.0.0

+  - /System/Library/PrivateFrameworks/AuthKitUI.framework/AuthKitUI

+  - /System/Library/PrivateFrameworks/DMCEnrollmentLibrary.framework/DMCEnrollmentLibrary
+  - /System/Library/PrivateFrameworks/DMCEnrollmentProvider.framework/DMCEnrollmentProvider

+  - /System/Library/PrivateFrameworks/SiriCrossDeviceArbitration.framework/SiriCrossDeviceArbitration

-  Functions: 17924
-  Symbols:   4914
-  CStrings:  2305
+  Functions: 18015
+  Symbols:   4935
+  CStrings:  2333
Symbols:
+ _OBJC_CLASS_$_AKAppleIDAuthenticationController
+ _OBJC_CLASS_$_AKAppleIDAuthenticationInAppContext
+ _OBJC_CLASS_$_DMCEnrollmentFlowController
+ _OBJC_CLASS_$_DMCReturnToServiceController
+ _OBJC_CLASS_$_DMCReturnToServiceHelper
+ _OBJC_CLASS_$_SCDACoordinator
+ __DATA__TtC17CompanionSetupKit19CSKMyriadAdvertiser
+ __IVARS__TtC17CompanionSetupKit19CSKMyriadAdvertiser
+ __METACLASS_DATA__TtC17CompanionSetupKit19CSKMyriadAdvertiser
+ ___swift_closure_destructor.212Tm
+ ___swift_closure_destructor.369Tm
+ ___swift_closure_destructor.395Tm
+ ___swift_closure_destructor.418Tm
+ ___swift_closure_destructor.441Tm
+ ___swift_closure_destructor.50Tm
+ ___swift_memcpy320_8
+ ___swift_memcpy505_8
+ _flat unique So14NSSecureCoding_p
+ _keypath_set.52Tm
+ _symbolic ScCySb_____G s5NeverO
+ _symbolic So15SCDACoordinatorC
+ _symbolic So24DMCReturnToServiceHelperCSgSg
+ _symbolic So33AKAppleIDAuthenticationControllerC
+ _symbolic _____ 17CompanionSetupKit19CSKMyriadAdvertiserC
+ _symbolic _____ 17CompanionSetupKit33PendingSiriEnableCUEnvironmentKey33_104953712DCBF74CC797CEE885C606F1LLV
+ _symbolic _____ 17CompanionSetupKit36DefersSiriEnablementCUEnvironmentKey33_104953712DCBF74CC797CEE885C606F1LLV
+ _symbolic _____Sg 12AppleIDSetup13SymptomReportV
+ _symbolic ___________p So14NSSecureCodingP So8NSObjectP
+ _symbolic _____ySo27DMCEnrollmentFlowControllerCG 14CoreUtilsSwift17CUSendableWrapperV
- ___swift_closure_destructor.214Tm
- ___swift_closure_destructor.364Tm
- ___swift_closure_destructor.390Tm
- ___swift_closure_destructor.413Tm
- ___swift_closure_destructor.436Tm
- ___swift_closure_destructor.49Tm
- ___swift_memcpy304_8
- ___swift_memcpy489_8
CStrings:
+ "### RTS Wi-Fi profile install failed: %@"
+ "### RTS enrollment failed, falling back: %@"
+ "### iCloud repair auth failed: error=%@"
+ "### iCloud repair: no authentication controller"
+ "CDP check disabled"
+ "CSKStepPreflight-iCloudRepair"
+ "CheckForUpdate failed"
+ "Not owner of preconfigured home: homeUser="
+ "RTS Wi-Fi profile installed"
+ "RTS enrollment canceled"
+ "RTS enrollment failed without error"
+ "RTS enrollment succeeded"
+ "Signaling RTS flow completed"
+ "Starting RTS enrollment flow"
+ "_iCloudRepair(altDSID:viewController:)"
+ "_performReturnToServiceEnrollment()"
+ "appleAccountForceUIRepair"
+ "cdpCheckEnabled"
+ "cleanup"
+ "com.apple.setupbackground.ca-context-id"
+ "iCloud check needs repair: symptoms=%s"
+ "iCloud repair auth completed"
+ "iCloud repair finished: healthy=%{bool}d, symptoms=%s"
+ "iCloud repair: authenticating account: forceInteractive=%{bool}d"
+ "performHomePreconfigured(configuration:homeName:homeUser:)"
+ "siri enablement deferred; applying companion settings"
+ "siri enablement deferred; setting enabled=%{bool}d"
+ "start: maxInterval=%fs"
+ "stop: delay=%fs"
- "performHomePreconfigured(configuration:homeName:)"
```
