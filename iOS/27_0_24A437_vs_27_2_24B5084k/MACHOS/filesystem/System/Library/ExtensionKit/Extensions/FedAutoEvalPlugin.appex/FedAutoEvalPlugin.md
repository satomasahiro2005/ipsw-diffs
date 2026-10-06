## FedAutoEvalPlugin

> `/System/Library/ExtensionKit/Extensions/FedAutoEvalPlugin.appex/FedAutoEvalPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10cec` | `0x10dc4` | **`+0xd8`** |
| `__TEXT.__auth_stubs` | `0xf30` | `0xf40` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x7a0` | `0x7a8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x3c0` | `0x3b8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1d0` | **`+0x8`** |

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

-42.0.0.0.0
+44.0.0.0.0

-  - /usr/lib/swift/libswiftAppleArchive.dylib

-  Symbols:   129
+  Symbols:   128
Symbols:
+ _swift_retain_x27
- __swift_FORCE_LOAD_$_swiftAppleArchive
- _swift_retain_x25
Functions:
~ sub_100002df4 -> sub_100002dac : 424 -> 516
~ sub_100002f9c -> sub_100002fb0 : 1420 -> 1532
~ sub_10000360c -> sub_100003690 : 240 -> 252
```
