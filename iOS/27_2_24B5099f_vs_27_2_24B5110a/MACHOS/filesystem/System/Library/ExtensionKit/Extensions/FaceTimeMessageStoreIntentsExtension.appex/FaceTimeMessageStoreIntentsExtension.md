## FaceTimeMessageStoreIntentsExtension

> `/System/Library/ExtensionKit/Extensions/FaceTimeMessageStoreIntentsExtension.appex/FaceTimeMessageStoreIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x0` | `0x2dc` | **`+0x2dc`** |
| `__DATA.__bss` | `—` | `0x180` | **`+0x180`** |
| `__TEXT.__const` | `0x2` | `0x112` | **`+0x110`** |
| `__TEXT.__auth_stubs` | `0x10` | `0xa0` | **`+0x90`** |
| `__TEXT.__unwind_info` | `—` | `0x88` | **`+0x88`** |
| `__DATA_CONST.__const` | `0x78` | `0xf8` | **`+0x80`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0x60` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `—` | `0x5d` | **`+0x5d`** |
| `__DATA_CONST.__auth_got` | `0x8` | `0x50` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `—` | `0x44` | **`+0x44`** |
| `__DATA.__data` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__got` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `—` | `0xe` | **`+0xe`** |
| `__TEXT.__swift5_proto` | `—` | `0xc` | **`+0xc`** |
| `__TEXT.__swift5_entry` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-1626.200.84.0.0
+1626.200.91.2.3

+  - /System/Library/Frameworks/ExtensionFoundation.framework/ExtensionFoundation

+  - /usr/lib/swift/libswiftAccelerate.dylib
+  - /usr/lib/swift/libswiftCallKit.dylib
+  - /usr/lib/swift/libswiftCompression.dylib
+  - /usr/lib/swift/libswiftCore.dylib

+  - /usr/lib/swift/libswiftCoreLocation.dylib

+  - /usr/lib/swift/libswiftIntents.dylib
+  - /usr/lib/swift/libswiftMLCompute.dylib

+  - /usr/lib/swift/libswiftNaturalLanguage.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib

-  Functions: 0
-  Symbols:   18
+  Functions: 13
+  Symbols:   32
Symbols:
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftCallKit
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCoreLocation
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftMLCompute
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
+ __swift_FORCE_LOAD_$_swiftOSLog
+ _main
+ _swift_allocObject
+ _swift_errorInMain
+ _swift_getOpaqueTypeConformance2
+ _swift_getTypeByMangledNameInContext2
+ _swift_getWitnessTable
```
