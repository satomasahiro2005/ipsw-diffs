## SiriAutoEvalPlugin

> `/System/Library/ExtensionKit/Extensions/SiriAutoEvalPlugin.appex/SiriAutoEvalPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x521` | `0x549` | **`+0x28`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-31.0.0.0.0
+35.0.0.0.0

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftAppleArchive.dylib
+  - /usr/lib/swift/libswiftCompression.dylib

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

+  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Symbols:   127
+  Symbols:   132
Symbols:
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
```
