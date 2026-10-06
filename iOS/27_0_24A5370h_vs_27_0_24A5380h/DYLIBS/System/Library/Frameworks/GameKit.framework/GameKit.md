## GameKit

> `/System/Library/Frameworks/GameKit.framework/GameKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x170` | `0x160` | **`-0x10`** |
| `__TEXT.__text` | `0x352f0` | `0x352e8` | **`-0x8`** |

### Other Changes

```diff

-821.0.16.0.0
+821.0.18.0.0

-  - /usr/lib/swift/libswiftAVFoundation.dylib

-  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Symbols:   500
+  Symbols:   496
Symbols:
- __swift_FORCE_LOAD_$_swiftAVFoundation
- __swift_FORCE_LOAD_$_swiftAVFoundation_$_GameKit
- __swift_FORCE_LOAD_$_swiftCoreMIDI
- __swift_FORCE_LOAD_$_swiftCoreMIDI_$_GameKit
Functions:
~ sub_2438c4a9c -> sub_247fb9a0c : 432 -> 428
~ sub_2438c4c4c -> sub_247fb9bb8 : 432 -> 428
```
