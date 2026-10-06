## FitnessIntelligenceDaemonCore

> `/System/Library/PrivateFrameworks/FitnessIntelligenceDaemonCore.framework/FitnessIntelligenceDaemonCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55794` | `0x55a34` | **`+0x2a0`** |
| `__TEXT.__cstring` | `0x81d` | `0x84d` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x89b` | `0x8cb` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x110` | `0xf8` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x4a8` | `0x4b8` | **`+0x10`** |

### Other Changes

```diff

-2027.0.77.1.3
+2027.1.26.0.0

-  - /System/Library/Frameworks/UIKit.framework/UIKit

-  - /usr/lib/swift/libswiftCoreImage.dylib

-  - /usr/lib/swift/libswiftSpatial.dylib

-  Symbols:   708
-  CStrings:  88
+  Symbols:   703
+  CStrings:  90
Symbols:
+ _OBJC_CLASS_$_NSUserDefaults
- __swift_FORCE_LOAD_$_swiftCoreImage
- __swift_FORCE_LOAD_$_swiftCoreImage_$_FitnessIntelligenceDaemonCore
- __swift_FORCE_LOAD_$_swiftSpatial
- __swift_FORCE_LOAD_$_swiftSpatial_$_FitnessIntelligenceDaemonCore
- __swift_FORCE_LOAD_$_swiftUIKit
- __swift_FORCE_LOAD_$_swiftUIKit_$_FitnessIntelligenceDaemonCore
Functions:
~ sub_2134ee16c -> sub_21524508c : 168 -> 260
~ sub_2134ee214 -> sub_215245190 : 808 -> 1356
~ sub_2134ee634 -> sub_2152457d4 : 108 -> 128
~ sub_2134ee798 -> sub_21524594c : 144 -> 160
~ sub_213519ffc -> sub_2152711c0 : 324 -> 320
CStrings:
+ "[%s] Bypassing HealthKitCloudRestoreStatus"
+ "bypassHealthKitCloudRestoreStatus"
```
