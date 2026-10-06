## AMPDSAPlugin

> `/System/Library/ExtensionKit/Extensions/AMPDSAPlugin.appex/AMPDSAPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb518` | `0xae48` | **`-0x6d0`** |
| `__TEXT.__auth_stubs` | `0xbc0` | `0xb30` | **`-0x90`** |
| `__DATA.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_CONST.__auth_got` | `0x5e8` | `0x5a0` | **`-0x48`** |
| `__DATA_CONST.__const` | `0x5d8` | `0x618` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x535` | `0x505` | **`-0x30`** |
| `__DATA.__objc_const` | `0x90` | `0xb8` | **`+0x28`** |
| `__TEXT.__const` | `0x932` | `0x918` | **`-0x1a`** |
| `__DATA.__data` | `0x278` | `0x260` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x158` | `0x140` | **`-0x18`** |
| `__TEXT.__eh_frame` | `0x640` | `0x650` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x40` | `0x30` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x338` | `0x328` | **`-0x10`** |
| `__TEXT.__constg_swiftt` | `0x120` | `0x114` | **`-0xc`** |
| `__TEXT.__swift5_fieldmd` | `0x1b8` | `0x1ac` | **`-0xc`** |
| `__TEXT.__objc_methname` | `0x51` | `0x46` | **`-0xb`** |
| `__TEXT.__swift5_reflstr` | `0x220` | `0x215` | **`-0xb`** |
| `__DATA.__common` | `0x8` | `—` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x218` | `0x210` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x238` | `0x232` | **`-0x6`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-31.0.0.0.0
+35.0.0.0.0

+  - /System/Library/Frameworks/UIKit.framework/UIKit

-  - /System/Library/PrivateFrameworks/PriMLDataPolicy.framework/PriMLDataPolicy

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftAppleArchive.dylib
+  - /usr/lib/swift/libswiftCompression.dylib

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

+  - /usr/lib/swift/libswiftIntents.dylib

+  - /usr/lib/swift/libswiftNaturalLanguage.dylib

+  - /usr/lib/swift/libswiftSpatial.dylib

-  Functions: 216
-  Symbols:   114
-  CStrings:  52
+  Functions: 210
+  Symbols:   120
+  CStrings:  50
Symbols:
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftUIKit
+ _swift_release_x27
- _objc_release_x23
- _swift_getSingletonMetadata
- _swift_updateClassMetadata2
CStrings:
- "Using synthetic taskId for Local_Directory: %s"
- "taskSource"
```
