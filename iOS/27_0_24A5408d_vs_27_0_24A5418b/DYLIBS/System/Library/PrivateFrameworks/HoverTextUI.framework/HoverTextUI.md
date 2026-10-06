## HoverTextUI

> `/System/Library/PrivateFrameworks/HoverTextUI.framework/HoverTextUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6efe4` | `0x6930c` | **`-0x5cd8`** |
| `__TEXT.__eh_frame` | `0x2688` | `0x1ed8` | **`-0x7b0`** |
| `__TEXT.__oslogstring` | `0x1711` | `0x13e1` | **`-0x330`** |
| `__TEXT.__unwind_info` | `0x1850` | `0x16e8` | **`-0x168`** |
| `__AUTH_CONST.__const` | `0x2f88` | `0x2e70` | **`-0x118`** |
| `__TEXT.__swift5_capture` | `0xa80` | `0x9d0` | **`-0xb0`** |
| `__TEXT.__swift_as_cont` | `0x168` | `0xf8` | **`-0x70`** |
| `__TEXT.__const` | `0x3e20` | `0x3dd0` | **`-0x50`** |
| `__TEXT.__swift_as_ret` | `0x70` | `0x44` | **`-0x2c`** |
| `__AUTH_CONST.__objc_const` | `0x1a10` | `0x19f0` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1672` | `0x1652` | **`-0x20`** |
| `__DATA_DIRTY.__data` | `0x1a8` | `0x198` | **`-0x10`** |
| `__TEXT.__constg_swiftt` | `0x1e70` | `0x1e80` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x9c` | `0x8c` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xff4` | `0xfe8` | **`-0xc`** |

### Other Changes

```diff

-3240.3.0.0.0
+3240.8.0.0.0

-  Functions: 2215
-  Symbols:   1045
-  CStrings:  195
+  Functions: 2158
+  Symbols:   1043
+  CStrings:  182
Symbols:
+ ___swift_closure_destructor.186Tm
+ ___swift_closure_destructor.87Tm
- _AXkMobileKeyBagLockStatusNotificationID
- ___swift_closure_destructor.180Tm
- ___swift_closure_destructor.228Tm
- ___swift_closure_destructor.81Tm
CStrings:
+ "Continuity/mirroring state changed. isContinuitySessionActive=%{bool}d. Refreshing Hover Text UI capture exclusion."
+ "Starting monitor for Continuity/mirroring status (Hover Text UI)."
+ "Stopping monitor for Continuity/mirroring status (Hover Text UI)."
- "Continuity display state changed. isContinuitySessionActive=%{bool}d"
- "Continuity session active. Removing Hover Text UI from view hierarchy."
- "Continuity session ended and device unlocked. Re-attaching Hover Text UI to view hierarchy."
- "Continuity session ended but device still locked. Will reattach on unlock."
- "Device lock status changed. AXDeviceIsUnlocked=%{bool}d"
- "Device locked. Removing Hover Text UI from view hierarchy."
- "Device unlocked. Re-attaching Hover Text UI to view hierarchy."
- "Failed to detach Hover Text UI external VC: %s"
- "Failed to detach Hover Text UI main VC: %s"
- "Failed to detach Hover Text UI scene VC: %s"
- "Failed to reattach Hover Text UI after secure mode: %s"
- "Initial state: isContinuitySessionActive=%{bool}d, isLocked=%{bool}d"
- "Re-attaching Hover Text UI VCs to display manager."
- "Skipping initial Hover Text UI attach. isLocked=%{bool}d isContinuitySessionActive=%{bool}d"
- "Starting monitor for device lock status (Hover Text UI)."
- "Stopping monitor for device lock status (Hover Text UI)."
```
