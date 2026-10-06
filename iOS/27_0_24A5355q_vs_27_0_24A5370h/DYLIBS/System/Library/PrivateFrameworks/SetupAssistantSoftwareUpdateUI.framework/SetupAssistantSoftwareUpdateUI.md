## SetupAssistantSoftwareUpdateUI

> `/System/Library/PrivateFrameworks/SetupAssistantSoftwareUpdateUI.framework/SetupAssistantSoftwareUpdateUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72c70` | `0x77604` | **`+0x4994`** |
| `__AUTH_CONST.__const` | `0x4c40` | `0x5190` | **`+0x550`** |
| `__TEXT.__swift5_capture` | `0x1dd8` | `0x2018` | **`+0x240`** |
| `__AUTH.__objc_data` | `0x14c0` | `0x1620` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x1b5d` | `0x1cb7` | **`+0x15a`** |
| `__TEXT.__unwind_info` | `0x16b0` | `0x17d8` | **`+0x128`** |
| `__AUTH_CONST.__objc_const` | `0x3708` | `0x37a8` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x43d` | `0x4dd` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x8c8` | `0x940` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x2e4` | `0x320` | **`+0x3c`** |
| `__DATA.__data` | `0x998` | `0x9d0` | **`+0x38`** |
| `__TEXT.__const` | `0xec8` | `0xee8` | **`+0x20`** |
| `__AUTH.__data` | `0x170` | `0x180` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x758` | `0x748` | **`-0x10`** |

### Other Changes

```diff

-772.0.0.0.0
+772.0.3.0.0

-  Functions: 2009
-  Symbols:   448
-  CStrings:  187
+  Functions: 2110
+  Symbols:   447
+  CStrings:  190
Symbols:
+ _OBJC_CLASS_$_NSThread
- _OBJC_CLASS_$_SUDescriptor
- __CLASS_METHODS_SUUISetupAssistantMandatoryUpdateController
CStrings:
+ "%{public}s: Skipping scan failure alert — one is already on screen."
+ "SUUISetupAssistantProgressController StatefulUI Observer: Descriptor State Changed (in-progress -> available) for %{public}s: %{public}s -> %{public}s"
+ "SUUISetupAssistantProgressController StatefulUI Observer: Install Failed triggered for %{public}s: %{public}@"
```
