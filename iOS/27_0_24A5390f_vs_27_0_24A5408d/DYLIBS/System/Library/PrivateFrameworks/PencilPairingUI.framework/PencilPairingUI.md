## PencilPairingUI

> `/System/Library/PrivateFrameworks/PencilPairingUI.framework/PencilPairingUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x45e98` | `0x48fb0` | **`+0x3118`** |
| `__AUTH.__objc_data` | `0x3160` | `0x34c8` | **`+0x368`** |
| `__TEXT.__oslogstring` | `0xc5a` | `0xe4a` | **`+0x1f0`** |
| `__AUTH_CONST.__const` | `0xf60` | `0x1088` | **`+0x128`** |
| `__TEXT.__eh_frame` | `0x448` | `0x560` | **`+0x118`** |
| `__AUTH_CONST.__objc_const` | `0xc220` | `0xc2f8` | **`+0xd8`** |
| `__TEXT.__unwind_info` | `0x13c0` | `0x1498` | **`+0xd8`** |
| `__TEXT.__constg_swiftt` | `0x105c` | `0x10f0` | **`+0x94`** |
| `__TEXT.__objc_methlist` | `0x3d64` | `0x3df4` | **`+0x90`** |
| `__TEXT.__cstring` | `0x1e55` | `0x1ed5` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x7f4` | `0x874` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x620` | `0x684` | **`+0x64`** |
| `__TEXT.__const` | `0x1154` | `0x11b4` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x8e0` | `0x938` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x2670` | `0x26c0` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x208` | `0x23c` | **`+0x34`** |
| `__DATA.__data` | `0xfa8` | `0xfd8` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x658` | `0x678` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x71a` | `0x734` | **`+0x1a`** |
| `__AUTH_CONST.__auth_got` | `0x9d8` | `0x9e8` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x14` | `0x24` | **`+0x10`** |
| `__AUTH.__data` | `0x358` | `0x360` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x74` | `0x78` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x1c` | `0x20` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x8` | `0xc` | **`+0x4`** |

### Other Changes

```diff

-218.1.0.0.0
+221.100.0.0.0

+  - /usr/lib/swift/libswiftAppleArchive.dylib
+  - /usr/lib/swift/libswiftCallKit.dylib

+  - /usr/lib/swift/libswiftCoreAudio_Private.dylib

-  Functions: 1870
-  Symbols:   2673
-  CStrings:  378
+  Functions: 1941
+  Symbols:   2687
+  CStrings:  391
Symbols:
+ +[PencilEducationElementData elementDataForType:languageID:deviceType:]
+ -[PNPPairingViewController supportedInterfaceOrientations]
+ _UIEdgeInsetsZero
+ ___swift_closure_destructor.58Tm
+ __os_log_default
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftAppleArchive_$_PencilPairingUI
+ __swift_FORCE_LOAD_$_swiftCallKit
+ __swift_FORCE_LOAD_$_swiftCallKit_$_PencilPairingUI
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private_$_PencilPairingUI
+ _keypath_get.2Tm
+ _keypath_set.3Tm
+ _objc_retain_x27
+ _swift_deletedAsyncMethodErrorTu
+ _symbolic _____ 15PencilPairingUI0aB6AssetsO
+ _symbolic _____Sg 10Foundation3URLV
+ _symbolic _____Sg_ABt 10Foundation3URLV
- +[PencilEducationElementData elementDataForType:languageID:]
- _kPKB001ElementTopSpace
- _kPKB001SegControlBandHeight
- _kPKB001TextFieldHeight
CStrings:
+ "/AppleInternal/Library/PreferenceBundles/PencilPairingInternalSettings.bundle"
+ "Handing control to FMUICoordinator: %@"
+ "PNPDismiss: charging auto-dismiss (%.1fs, movePlatter) firing"
+ "PNPDismiss: charging auto-dismiss (%.1fs, slideOut) firing"
+ "PNPDismiss: pairingFailed -> dismiss"
+ "PNPDismiss: requestDismissal (angel/external-driven)"
+ "PNPDismiss: viewRequestsDismiss ENTER (state=%ld)"
+ "didCompleteAccessoryOnboarding: Pairing Successful: %{bool}d"
+ "didCompleteAccessoryOnboarding: Processing Next Controller."
+ "didCompleteAccessoryOnboarding: Saving onboarding status"
+ "enableChime"
+ "logLEDLevels"
+ "purrfectPairingModeEnabled"
```
