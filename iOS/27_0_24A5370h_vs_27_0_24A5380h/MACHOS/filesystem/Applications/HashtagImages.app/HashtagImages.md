## HashtagImages

> `/Applications/HashtagImages.app/HashtagImages`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x97cc` | `0x981c` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x8f0` | `0x900` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x480` | `0x488` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x4e0` | `0x4e8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x128` | `0x130` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3400.1.6.26.0
+3400.1.6.28.0

+  - /usr/lib/swift/libswiftCompression.dylib

-  Symbols:   235
+  Symbols:   238
Symbols:
+ ___stack_chk_fail
+ ___stack_chk_guard
+ __swift_FORCE_LOAD_$_swiftCompression
Functions:
~ sub_1000066d0 -> sub_100006718 : 300 -> 380
```
