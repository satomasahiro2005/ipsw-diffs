## HashtagImagesExtension

> `/Applications/HashtagImages.app/PlugIns/HashtagImagesExtension.appex/HashtagImagesExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbd50` | `0xbda0` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x900` | `0x910` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x488` | `0x490` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x698` | `0x6a0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x120` | `0x128` | **`+0x8`** |

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
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3400.1.6.26.0
+3400.1.6.28.0

+  - /usr/lib/swift/libswiftCompression.dylib

-  Symbols:   146
+  Symbols:   149
Symbols:
+ ___stack_chk_fail
+ ___stack_chk_guard
+ __swift_FORCE_LOAD_$_swiftCompression
Functions:
~ sub_10000765c -> sub_1000076a4 : 300 -> 380
```
