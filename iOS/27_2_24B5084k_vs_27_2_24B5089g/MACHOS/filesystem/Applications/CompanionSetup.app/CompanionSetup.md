## CompanionSetup

> `/Applications/CompanionSetup.app/CompanionSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa3874` | `0xa3970` | **`+0xfc`** |
| `__DATA_CONST.__const` | `0x85e0` | `0x85e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
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

-524.10.88.0.0
+524.10.94.0.0

+  - /usr/lib/swift/libswiftAppleArchive.dylib

-  Symbols:   1269
+  Symbols:   1270
Symbols:
+ __swift_FORCE_LOAD_$_swiftAppleArchive
Functions:
~ sub_10005ec54 -> sub_10005ec9c : 1148 -> 1232
~ sub_10005f0d0 -> sub_10005f16c : 1148 -> 1232
~ sub_10005f54c -> sub_10005f63c : 1148 -> 1232
```
