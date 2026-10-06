## diagnosticspushd

> `/usr/libexec/diagnosticspushd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15dd0` | `0x15bf8` | **`-0x1d8`** |
| `__DATA_CONST.__const` | `0x11c9` | `0x1191` | **`-0x38`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-33.0.0.0.0
+34.0.0.0.0

-  - /System/Library/Frameworks/UIKit.framework/UIKit

-  - /usr/lib/swift/libswiftCoreImage.dylib

-  - /usr/lib/swift/libswiftMetal.dylib
-  - /usr/lib/swift/libswiftOSLog.dylib

-  - /usr/lib/swift/libswiftQuartzCore.dylib
-  - /usr/lib/swift/libswiftSpatial.dylib

-  - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 544
-  Symbols:   354
+  Functions: 541
+  Symbols:   347
Symbols:
- __swift_FORCE_LOAD_$_swiftCoreImage
- __swift_FORCE_LOAD_$_swiftMetal
- __swift_FORCE_LOAD_$_swiftOSLog
- __swift_FORCE_LOAD_$_swiftQuartzCore
- __swift_FORCE_LOAD_$_swiftSpatial
- __swift_FORCE_LOAD_$_swiftUIKit
- __swift_FORCE_LOAD_$_swiftsimd
CStrings:
+ "timberlorry"
- "timberLorry"
```
