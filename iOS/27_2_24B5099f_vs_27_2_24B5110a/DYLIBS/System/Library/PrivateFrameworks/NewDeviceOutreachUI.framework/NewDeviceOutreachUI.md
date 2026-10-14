## NewDeviceOutreachUI

> `/System/Library/PrivateFrameworks/NewDeviceOutreachUI.framework/NewDeviceOutreachUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ce74` | `0x3f4a0` | **`+0x262c`** |
| `__AUTH_CONST.__const` | `0x1c98` | `0x1fe0` | **`+0x348`** |
| `__TEXT.__oslogstring` | `0x12d0` | `0x1490` | **`+0x1c0`** |
| `__AUTH_CONST.__objc_const` | `0x3470` | `0x32f0` | **`-0x180`** |
| `__TEXT.__swift5_capture` | `0xadc` | `0xc44` | **`+0x168`** |
| `__TEXT.__cstring` | `0x866` | `0x8f6` | **`+0x90`** |
| `__AUTH_CONST.__auth_got` | `0xc78` | `0xca0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x550` | `0x578` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xdd8` | `0xe00` | **`+0x28`** |
| `__DATA.__data` | `0xb98` | `0xbb8` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x12c8` | `0x12e8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x990` | `0x978` | **`-0x18`** |
| `__TEXT.__const` | `0x1284` | `0x1294` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x840` | `0x838` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x20` | `0x1c` | **`-0x4`** |

### Other Changes

```diff

-624.40.21.0.0
+624.40.22.0.0

-  Functions: 1245
+  Functions: 1293

-  CStrings:  147
+  CStrings:  157
Symbols:
+ ___swift_closure_destructor.103Tm
+ ___swift_closure_destructor.116Tm
+ ___swift_closure_destructor.14Tm
+ ___swift_closure_destructor.29Tm
+ _symbolic Ieg_SgytSgIeggd_
+ _symbolic Sbz_Xx
+ _symbolic So16UIViewControllerCSgXwz_Xx
- -[NDOAppleCareAMSUIViewController navController]
- -[NDOAppleCareAMSUIViewController setNavController:]
- _OBJC_IVAR_$_NDOAppleCareAMSUIViewController._navController
- ___swift_closure_destructor.12Tm
- ___swift_closure_destructor.21Tm
- ___swift_closure_destructor.27Tm
- _symbolic So16UIViewControllerCSg
CStrings:
+ "%s.%s - dismissing presented view controller."
+ "%s.%s - no outgoing sheet, proceeding immediately"
+ "%s.%s - no presenter to dismiss, the sheet stays on screen"
+ "%s.%s - outgoing sheet cleared"
+ "%s.%s - outgoing sheet did not clear in time, proceeding anyways"
+ "%s.%s - outgoing sheet is already being dismissed, waiting for the teardown to finish"
+ "%s.%s - presenter dismissal completed"
+ "%s: no presenter for %@, reporting the action as unhandled"
+ "NewDeviceOutreachUI/UIComposition.swift"
+ "afterOutgoingSheetClears(on:work:)"
+ "makeAMSDelegate(manager:presenter:onDismiss:)"
- "Reusing existing sheet delegate for path: %s"
```
