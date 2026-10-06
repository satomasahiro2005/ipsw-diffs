## PencilPairingUI

> `/System/Library/PrivateFrameworks/PencilPairingUI.framework/PencilPairingUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f918` | `0x42038` | **`+0x2720`** |
| `__AUTH_CONST.__objc_const` | `0xb9d0` | `0xbe60` | **`+0x490`** |
| `__AUTH.__objc_data` | `0x2a48` | `0x2e18` | **`+0x3d0`** |
| `__TEXT.__constg_swiftt` | `0xbcc` | `0xdb8` | **`+0x1ec`** |
| `__TEXT.__objc_methlist` | `0x3ba4` | `0x3ccc` | **`+0x128`** |
| `__TEXT.__cstring` | `0x1b95` | `0x1c85` | **`+0xf0`** |
| `__TEXT.__const` | `0xec4` | `0xfa4` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0xa5a` | `0xb0a` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x564` | `0x606` | **`+0xa2`** |
| `__TEXT.__swift5_reflstr` | `0x5e2` | `0x674` | **`+0x92`** |
| `__TEXT.__swift5_fieldmd` | `0x460` | `0x4f0` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0xcd8` | `0xd58` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x1278` | `0x12f8` | **`+0x80`** |
| `__DATA.__data` | `0xe88` | `0xee8` | **`+0x60`** |
| `__AUTH.__data` | `0x2d8` | `0x328` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x25e0` | `0x2620` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x920` | `0x948` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0x8c` | `0xa0` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x630` | `0x640` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x200` | `0x210` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x60` | `0x6c` | **`+0xc`** |
| `__TEXT.__swift5_proto` | `0x58` | `0x5c` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x4` | `0x8` | **`+0x4`** |

### Other Changes

```diff

-213.100.0.0.0
+216.0.0.0.0

-  Functions: 1738
-  Symbols:   2592
-  CStrings:  351
+  Functions: 1780
+  Symbols:   2624
+  CStrings:  360
Symbols:
+ -[PNPPairingViewController isShowingPairingEducationPane]
+ -[PNPPairingViewController transitionToEducationFlowIfNecessary:]
+ -[PNPPairingViewController transitionToPairingMode:]
+ _OBJC_CLASS_$_PNPPairingEducationController
+ _OBJC_CLASS_$_PNPWizardMovieView
+ _OBJC_CLASS_$_UIBarButtonItem
+ _OBJC_METACLASS_$_PNPPairingEducationController
+ _OBJC_METACLASS_$_PNPWizardMovieView
+ __CLASS_METHODS_PNPPairingEducationController
+ __CLASS_METHODS_PNPWizardMovieView
+ __CLASS_PROPERTIES_PNPWizardMovieView
+ __DATA_PNPPairingEducationController
+ __DATA_PNPWizardMovieView
+ __INSTANCE_METHODS_PNPPairingEducationController
+ __INSTANCE_METHODS_PNPWizardMovieView
+ __IVARS_PNPPairingEducationController
+ __IVARS_PNPWizardMovieView
+ __METACLASS_DATA_PNPPairingEducationController
+ __METACLASS_DATA_PNPWizardMovieView
+ _objc_retain_x9
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _swift_release_x28
+ _symbolic $s15PencilPairingUI37PNPPairingEducationControllerDelegateP
+ _symbolic SaySo16UIViewControllerCGSg
+ _symbolic So6UIViewC
+ _symbolic So8AVPlayerCSg
+ _symbolic _____ 15PencilPairingUI18PNPWizardMovieViewC
+ _symbolic _____ 15PencilPairingUI29PNPPairingEducationControllerC
+ _symbolic _____ So23PNPPairingEducationModeV
+ _symbolic _____Sg 15PencilPairingUI18PNPWizardMovieViewC
+ _symbolic _____Sg 15PencilPairingUI29PNPPairingEducationControllerC
+ _symbolic ______pSgXw 15PencilPairingUI37PNPPairingEducationControllerDelegateP
CStrings:
+ "Being asked to transition to a pairing education mode, but the controller is nil"
+ "CONNECTING_TITLE"
+ "PencilPairingUI.PNPWizardMovieView"
+ "PencilPairingUI/PNPPairingEducationController.swift"
+ "PencilPairingUI/PNPWizardMovieView.swift"
+ "Removing pairingEducation view controllers"
+ "Unknown welcome controller type"
+ "init(coder:) has not been implemented"
+ "init(frame:)"
```
