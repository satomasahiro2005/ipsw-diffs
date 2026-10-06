## AVCPlugin

> `/System/Library/ExtensionKit/Extensions/AVCPlugin.appex/AVCPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x988` | `0x9b8` | **`+0x30`** |
| `__TEXT.__text` | `0x15a74` | `0x15a64` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-31.0.0.0.0
+35.0.0.0.0

+  - /System/Library/Frameworks/UIKit.framework/UIKit

+  - /usr/lib/swift/libswiftAppleArchive.dylib
+  - /usr/lib/swift/libswiftCompression.dylib

+  - /usr/lib/swift/libswiftIntents.dylib

+  - /usr/lib/swift/libswiftNaturalLanguage.dylib

+  - /usr/lib/swift/libswiftSpatial.dylib

-  Symbols:   141
+  Symbols:   147
Symbols:
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftUIKit
Functions:
~ sub_10001689c -> sub_100016a5c : 844 -> 828
```
