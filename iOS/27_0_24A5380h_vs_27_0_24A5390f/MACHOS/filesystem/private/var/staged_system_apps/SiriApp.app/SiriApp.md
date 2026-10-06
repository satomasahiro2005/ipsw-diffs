## SiriApp

> `/private/var/staged_system_apps/SiriApp.app/SiriApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b5c` | `0x1bb0` | **`+0x54`** |
| `__DATA_CONST.__const` | `0xb0` | `0xf8` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x3d0` | `0x3f0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1f0` | `0x200` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x148` | `0x150` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-73.0.5.102.0
+73.0.12.0.0

+  - /System/Library/PrivateFrameworks/SnippetUI.framework/SnippetUI

+  - /usr/lib/swift/libswiftAVFoundation.dylib
+  - /usr/lib/swift/libswiftAccelerate.dylib
+  - /usr/lib/swift/libswiftCompression.dylib

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

+  - /usr/lib/swift/libswiftIntents.dylib
+  - /usr/lib/swift/libswiftMLCompute.dylib

+  - /usr/lib/swift/libswiftMetalKit.dylib
+  - /usr/lib/swift/libswiftModelIO.dylib
+  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Symbols:   129
+  Symbols:   140
Symbols:
+ _$s9SnippetUI22VisualResponseProviderC14preloadPluginsyyFZ
+ _$s9SnippetUI22VisualResponseProviderCMa
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftMLCompute
+ __swift_FORCE_LOAD_$_swiftMetalKit
+ __swift_FORCE_LOAD_$_swiftModelIO
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
Functions:
~ sub_100001300 -> sub_1000015f0 : 8 -> 48
~ sub_100001308 -> sub_100001620 : 244 -> 288
```
