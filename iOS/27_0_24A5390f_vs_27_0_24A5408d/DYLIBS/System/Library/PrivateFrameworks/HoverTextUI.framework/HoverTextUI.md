## HoverTextUI

> `/System/Library/PrivateFrameworks/HoverTextUI.framework/HoverTextUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6cc7c` | `0x6efe4` | **`+0x2368`** |
| `__TEXT.__eh_frame` | `0x2420` | `0x2688` | **`+0x268`** |
| `__AUTH_CONST.__const` | `0x2ec8` | `0x2f88` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x17c0` | `0x1850` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0xa14` | `0xa80` | **`+0x6c`** |
| `__TEXT.__oslogstring` | `0x16d1` | `0x1711` | **`+0x40`** |
| `__TEXT.__const` | `0x3df0` | `0x3e20` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x1e48` | `0x1e70` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x144` | `0x168` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x858` | `0x870` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1360` | `0x1368` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x718` | `0x720` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x68` | `0x70` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x98` | `0x9c` | **`+0x4`** |

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  - /System/Library/PrivateFrameworks/AccessibilityUIUtilities.framework/AccessibilityUIUtilities

-  Functions: 2184
+  Functions: 2215

-  CStrings:  194
+  CStrings:  195
Symbols:
+ ___swift_closure_destructor.14Tm
+ ___swift_closure_destructor.228Tm
- _AXUIScreenForDisplayID
- ___swift_closure_destructor.222Tm
CStrings:
+ "Continuity session active. Removing Hover Text UI from view hierarchy."
+ "Continuity session ended and device unlocked. Re-attaching Hover Text UI to view hierarchy."
+ "Device locked. Removing Hover Text UI from view hierarchy."
+ "Device unlocked. Re-attaching Hover Text UI to view hierarchy."
+ "Failed to detach Hover Text UI external VC: %s"
+ "Failed to detach Hover Text UI main VC: %s"
+ "Failed to detach Hover Text UI scene VC: %s"
+ "Failed to reattach Hover Text UI after secure mode: %s"
+ "Re-attaching Hover Text UI VCs to display manager."
+ "Skipping initial Hover Text UI attach. isLocked=%{bool}d isContinuitySessionActive=%{bool}d"
+ "Starting monitor for device lock status (Hover Text UI)."
+ "Stopping monitor for device lock status (Hover Text UI)."
- "Continuity session active. Removing Hover Typing from view hierarchy."
- "Continuity session ended and device unlocked. Re-attaching Hover Typing to view hierarchy."
- "Device locked. Removing Hover Typing from view hierarchy."
- "Device unlocked. Re-attaching Hover Typing to view hierarchy."
- "Failed to detach Hover Typing main VC: %s"
- "Failed to detach Hover Typing scene VC: %s"
- "Failed to reattach Hover Typing after lock: %s"
- "Re-attaching Hover Typing VCs to display manager."
- "Skipping initial Hover Typing UI attach. isLocked=%{bool}d isContinuitySessionActive=%{bool}d"
- "Starting monitor for device lock status (Hover Typing)."
- "Stopping monitor for device lock status (Hover Typing)."
```
