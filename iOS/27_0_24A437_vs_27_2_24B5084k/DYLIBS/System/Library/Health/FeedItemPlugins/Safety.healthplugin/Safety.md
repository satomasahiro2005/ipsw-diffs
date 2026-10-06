## Safety

> `/System/Library/Health/FeedItemPlugins/Safety.healthplugin/Safety`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb37a0` | `0xb27b0` | **`-0xff0`** |
| `__DATA.__bss` | `0x9400` | `0x8f00` | **`-0x500`** |
| `__TEXT.__const` | `0x71e4` | `0x6fb4` | **`-0x230`** |
| `__AUTH_CONST.__const` | `0x3188` | `0x3318` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0x2150` | `0x1fc8` | **`-0x188`** |
| `__TEXT.__constg_swiftt` | `0x3218` | `0x30b8` | **`-0x160`** |
| `__TEXT.__cstring` | `0x35f8` | `0x3738` | **`+0x140`** |
| `__DATA_DIRTY.__data` | `0x2978` | `0x2868` | **`-0x110`** |
| `__AUTH_CONST.__objc_const` | `0x47c0` | `0x46d8` | **`-0xe8`** |
| `__TEXT.__unwind_info` | `0x2708` | `0x2628` | **`-0xe0`** |
| `__AUTH.__data` | `0x1ba8` | `0x1ad8` | **`-0xd0`** |
| `__AUTH.__objc_data` | `0x18b8` | `0x17e8` | **`-0xd0`** |
| `__AUTH_CONST.__auth_got` | `0x1930` | `0x1a00` | **`+0xd0`** |
| `__TEXT.__swift5_capture` | `0xa74` | `0xb34` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x1d08` | `0x1c88` | **`-0x80`** |
| `__TEXT.__swift5_typeref` | `0x1d74` | `0x1d04` | **`-0x70`** |
| `__TEXT.__swift5_reflstr` | `0x1d2f` | `0x1cc9` | **`-0x66`** |
| `__TEXT.__swift5_assocty` | `0x500` | `0x540` | **`+0x40`** |
| `__DATA.__data` | `0x1860` | `0x1898` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0xaa0` | `0xad0` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x618` | `0x5e8` | **`-0x30`** |
| `__DATA.__common` | `0x270` | `0x288` | **`+0x18`** |
| `__DATA_DIRTY.__objc_data` | `0xfb0` | `0xf98` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x904` | `0x8ec` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x228` | `0x218` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x70` | `0x80` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x278` | `0x268` | **`-0x10`** |
| `__DATA_CONST.__objc_catlist2` | `0x18` | `0x20` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x38` | `0x40` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x238` | `0x230` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x48` | `0x44` | **`-0x4`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/Frameworks/SwiftUI.framework/SwiftUI

-  Functions: 3165
-  Symbols:   325
-  CStrings:  468
+  Functions: 3147
+  Symbols:   328
+  CStrings:  476
Symbols:
+ _OBJC_CLASS_$_UIAlertAction
+ _OBJC_CLASS_$_UIAlertController
+ _swift_getOpaqueTypeConformance2
+ _swift_getOpaqueTypeMetadata2
- _OBJC_CLASS_$_UIApplication
CStrings:
+ "Available on Watch"
+ "Available on Watch: "
+ "Safety.FallDetection.hasPairedWatch"
+ "Safety.FallDetection.isAvailableOnWatch"
+ "Safety.FallDetection.isEnabled"
+ "Safety.FallDetection.isWorkoutsOnlyAvailable"
+ "Safety.FallDetection.isWorkoutsOnlyEnabled"
+ "Safety.FallDetection.useDebugState"
+ "Safety/SafetyInternalSettingsView.swift"
+ "Switch to Standard"
+ "Workouts Only Available"
+ "Workouts Only Available: "
- "Safety.ApplicationInstallationInputSignal"
- "application.installation"
- "applicationAvailabilities"
- "com.apple.health.application.installation"
```
