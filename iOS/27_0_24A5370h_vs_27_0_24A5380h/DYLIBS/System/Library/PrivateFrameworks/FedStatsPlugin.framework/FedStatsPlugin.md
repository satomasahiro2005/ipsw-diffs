## FedStatsPlugin

> `/System/Library/PrivateFrameworks/FedStatsPlugin.framework/FedStatsPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x319e8` | `0x3199c` | **`-0x4c`** |
| `__DATA_CONST.__const` | `0xe8` | `0x108` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x338` | `0x328` | **`-0x10`** |

### Other Changes

```diff

-31.0.0.0.0
+35.0.0.0.0

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftAppleArchive.dylib
+  - /usr/lib/swift/libswiftCompression.dylib

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Symbols:   436
+  Symbols:   444
Symbols:
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftAVFoundation_$_FedStatsPlugin
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftAppleArchive_$_FedStatsPlugin
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCompression_$_FedStatsPlugin
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftCoreMIDI_$_FedStatsPlugin
Functions:
~ sub_25c1bea50 -> sub_260cd0b70 : 1032 -> 1020
~ sub_25c1cab20 -> sub_260cdcc34 : 1484 -> 1464
~ sub_25c1cb0ec -> sub_260cdd1ec : 900 -> 880
~ sub_25c1cb470 -> sub_260cdd55c : 720 -> 700
~ sub_25c1cc5b0 -> sub_260cde688 : 132 -> 1172
~ sub_25c1cc634 -> sub_260cdeb1c : 1176 -> 132
```
