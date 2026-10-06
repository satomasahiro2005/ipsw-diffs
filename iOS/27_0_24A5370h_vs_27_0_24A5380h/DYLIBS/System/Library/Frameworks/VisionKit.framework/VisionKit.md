## VisionKit

> `/System/Library/Frameworks/VisionKit.framework/VisionKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `—` | `0x270` | **`+0x270`** |
| `__DATA_DIRTY.__objc_data` | `0x8d8` | `0x668` | **`-0x270`** |
| `__DATA_DIRTY.__data` | `0x458` | `0x2b8` | **`-0x1a0`** |
| `__AUTH.__data` | `—` | `0x198` | **`+0x198`** |
| `__TEXT.__text` | `0x184d0` | `0x184bc` | **`-0x14`** |
| `__DATA_CONST.__const` | `0x240` | `0x238` | **`-0x8`** |

### Other Changes

```diff

-338.0.0.0.0
+341.0.0.0.0

-  - /usr/lib/swift/libswiftIntents.dylib

-  Symbols:   464
+  Symbols:   462
Symbols:
- __swift_FORCE_LOAD_$_swiftIntents
- __swift_FORCE_LOAD_$_swiftIntents_$_VisionKit
Functions:
~ sub_2474a1158 -> sub_24c0081f8 : 356 -> 336
```
