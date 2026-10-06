## AVCPlugin

> `/System/Library/ExtensionKit/Extensions/AVCPlugin.appex/AVCPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1565c` | `0x1572c` | **`+0xd0`** |
| `__TEXT.__auth_stubs` | `0x1170` | `0x1190` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x8c0` | `0x8d0` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x9b8` | `0x9b0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x248` | `0x250` | **`+0x8`** |

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
Symbols:
+ _swift_retain_x27
- __swift_FORCE_LOAD_$_swiftAppleArchive
Functions:
~ sub_100013040 -> sub_100012ff8 : 424 -> 516
~ sub_1000131e8 -> sub_1000131fc : 1328 -> 1432
~ sub_1000137fc -> sub_100013878 : 240 -> 252
```
