## SetupAssistantSoftwareUpdateUI

> `/System/Library/PrivateFrameworks/SetupAssistantSoftwareUpdateUI.framework/SetupAssistantSoftwareUpdateUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77604` | `0x78b6c` | **`+0x1568`** |
| `__TEXT.__cstring` | `0xf5b` | `0x104b` | **`+0xf0`** |
| `__AUTH_CONST.__const` | `0x5190` | `0x5258` | **`+0xc8`** |
| `__TEXT.__swift5_capture` | `0x2018` | `0x2078` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x17d8` | `0x1800` | **`+0x28`** |
| `__AUTH.__objc_data` | `0x1620` | `0x1640` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x1cb7` | `0x1c97` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0xfeb` | `0x1005` | **`+0x1a`** |
| `__AUTH_CONST.__auth_got` | `0x870` | `0x888` | **`+0x18`** |
| `__DATA.__data` | `0x9d0` | `0x9b8` | **`-0x18`** |
| `__TEXT.__constg_swiftt` | `0x940` | `0x948` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x78` | `0x7c` | **`+0x4`** |

### Other Changes

```diff

-772.0.10.0.0
+772.0.20.0.0

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 2110
-  Symbols:   447
-  CStrings:  190
+  Functions: 2125
+  Symbols:   450
+  CStrings:  195
Symbols:
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_wapiCapability
+ _symbolic So17SUUIStatefulErrorCSg
CStrings:
+ "%{public}s button pressed"
+ "%{public}s: environment is nil when instantiating progress view"
+ "%{public}s: reactivePlatformEnvironment is nil in handlePreUpdateError"
+ "A WLAN connection is needed to download this update."
+ "A Wi-Fi connection is needed to download this update."
+ "Choose WLAN Network"
+ "Choose Wi-Fi Network"
+ "Failed to check for updates: %{public}@"
+ "Requesting %{public}s status text for a presented descriptor that is unknown/availableToDownload. Returning \"Update requested\" as a fallback."
+ "SUUISetupAssistantController StatefulUI Observer: Refresh triggered via: %{public}s (state: %{public}s, descriptor state: %{public}s)"
+ "SUUISetupAssistantProgressController StatefulUI Observer: Refresh triggered via: %{public}s (state: %{public}s, descriptor state: %{public}s)"
+ "Transfer Data from \""
+ "Transfer Data from Device"
+ "Transferring directly from this "
+ "Update action \"%{public}s\" has been made by SUUISetupAssistantController but failed.\n    error: %{public}@\n    flowDone: %{bool,public}d"
+ "Update action \"%{public}s\" has been resolved by SUUISetupAssistantController.\n    success: %{bool,public}d\n    flowDone: %{bool,public}d"
+ "Update has maximum version %{public}s ..."
+ "Update has minimum version %{public}s ..."
+ "We got error: %{public}s"
+ "{nil}"
- "%s button pressed"
- "%s: environment is nil when instantiating progress view"
- "%s: reactivePlatformEnvironment is nil in handlePreUpdateError"
- "Failed to check for updates: %@"
- "Migrate from \""
- "Migrate from Device"
- "Migrating from this "
- "Requesting %s status text for a presented descriptor that is unknown/availableToDownload. Returning \"Update requested\" as a fallback."
- "SUUISetupAssistantController StatefulUI Observer: Refresh triggered via: %s (state: %s, descriptor state: %s)"
- "SUUISetupAssistantProgressController StatefulUI Observer: Refresh triggered via: %s (state: %{public}s, descriptor state: %{public}s)"
- "Update action \"%{public}s\" has been made by SUUISetupAssistantController but failed.\n    error: %{public}@\n    flowDone: %{bool}d"
- "Update action \"%{public}s\" has been resolved by SUUISetupAssistantController.\n    success: %{bool,public}d\n    flowDone: %{bool}d"
- "Update action \"%{public}s\" has been resolved by SUUISetupAssistantController.\n    success: %{bool}d\n    flowDone: %{bool}d"
- "Update has maximum version %s ..."
- "Update has minimum version %s ..."
```
