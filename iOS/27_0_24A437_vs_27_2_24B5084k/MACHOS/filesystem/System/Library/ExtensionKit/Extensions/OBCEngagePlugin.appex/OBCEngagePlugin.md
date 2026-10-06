## OBCEngagePlugin

> `/System/Library/ExtensionKit/Extensions/OBCEngagePlugin.appex/OBCEngagePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11a88` | `0x11b58` | **`+0xd0`** |
| `__TEXT.__auth_stubs` | `0xe90` | `0xea0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x750` | `0x758` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x7d8` | `0x7d0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x198` | `0x1a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
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

-  Symbols:   134
+  Symbols:   133
Symbols:
+ _swift_retain_x27
- __swift_FORCE_LOAD_$_swiftAppleArchive
- _swift_retain_x25
Functions:
~ sub_1000023f4 -> sub_1000023ac : 424 -> 516
~ sub_10000259c -> sub_1000025b0 : 1256 -> 1360
~ sub_100002b68 -> sub_100002be4 : 240 -> 252
```
