## TVAppExtension

> `/System/Library/ExtensionKit/Extensions/TVAppExtension.appex/TVAppExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7904` | `0x7934` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0xa00` | `0xa20` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x2f0` | `0x30e` | **`+0x1e`** |
| `__DATA_CONST.__auth_got` | `0x508` | `0x518` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x1c8` | `0x1d8` | **`+0x10`** |
| `__TEXT.__const` | `0x568` | `0x578` | **`+0x10`** |
| `__DATA.__data` | `0x440` | `0x448` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x288` | `0x290` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1145.0.6.0.0
+1145.1.1.0.0

+  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Symbols:   139
+  Symbols:   140
Symbols:
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
Functions:
~ sub_100001ae4 -> sub_100001b34 : 132 -> 180
```
