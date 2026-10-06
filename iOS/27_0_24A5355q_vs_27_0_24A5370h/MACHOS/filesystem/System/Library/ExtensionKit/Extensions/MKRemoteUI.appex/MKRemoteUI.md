## MKRemoteUI

> `/System/Library/ExtensionKit/Extensions/MKRemoteUI.appex/MKRemoteUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0xc90` | `0xd00` | **`+0x70`** |
| `__TEXT.__text` | `0xec88` | `0xecec` | **`+0x64`** |
| `__DATA_CONST.__auth_got` | `0x650` | `0x688` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x448` | `0x450` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-281.30.5.15.1
+284.30.6.5.2

-  Symbols:   170
+  Symbols:   171
Symbols:
+ _swift_release_x23
Functions:
~ sub_10000526c : 784 -> 828
~ sub_10000557c -> sub_1000055a8 : 1356 -> 1300
~ sub_100005ac8 -> sub_100005abc : 276 -> 280
~ sub_10000783c -> sub_100007834 : 516 -> 640
~ sub_10000d410 -> sub_10000d484 : 544 -> 532
~ sub_100010008 -> sub_100010070 : 280 -> 276
```
