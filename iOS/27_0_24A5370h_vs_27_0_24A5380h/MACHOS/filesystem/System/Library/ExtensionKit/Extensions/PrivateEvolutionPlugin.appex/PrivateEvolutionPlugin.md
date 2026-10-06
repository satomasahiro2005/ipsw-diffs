## PrivateEvolutionPlugin

> `/System/Library/ExtensionKit/Extensions/PrivateEvolutionPlugin.appex/PrivateEvolutionPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e594` | `0x1e5ac` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xb09` | `0xb19` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
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

+  - /usr/lib/swift/libswiftAppleArchive.dylib

+  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Symbols:   166
+  Symbols:   168
Symbols:
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
Functions:
~ sub_100015ecc -> sub_100015f64 : 3360 -> 3376
~ sub_100016cf4 -> sub_100016d9c : 2704 -> 2712
```
