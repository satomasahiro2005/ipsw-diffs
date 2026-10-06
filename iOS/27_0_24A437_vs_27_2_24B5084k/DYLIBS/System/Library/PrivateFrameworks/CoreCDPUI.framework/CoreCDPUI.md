## CoreCDPUI

> `/System/Library/PrivateFrameworks/CoreCDPUI.framework/CoreCDPUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x1448` | `0x1458` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x4aa2` | `0x4a92` | **`-0x10`** |
| `__TEXT.__text` | `0x8c028` | `0x8c038` | **`+0x10`** |

### Other Changes

```diff

-447.0.0.0.0
+448.125.5.1.0

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftIntents.dylib

-  Symbols:   3729
+  Symbols:   3733
Symbols:
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftAVFoundation_$_CoreCDPUI
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftIntents_$_CoreCDPUI
Functions:
~ ___76-[CDPUIStatusChangeController(Presentation) authenticate:completionHandler:]_block_invoke : 444 -> 460
CStrings:
+ "User cancelled ADP disablement: %@"
- "User cancelled ADP disablement...Nothing to do... %@"
```
