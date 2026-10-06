## ClarityUIServer

> `/System/Library/AccessibilityBundles/ClarityUIServer.axuiservice/ClarityUIServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd6b4` | `0xd720` | **`+0x6c`** |
| `__TEXT.__auth_stubs` | `0xbd0` | `0xbc0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x5f0` | `0x5e8` | **`-0x8`** |

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
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-158.0.0.0.0
+161.0.0.0.0

-  Symbols:   181
+  Symbols:   180
Symbols:
+ _objc_release_x27
+ _swift_retain_x23
- _objc_retain_x22
- _swift_release_x25
- _swift_retain_x25
Functions:
~ sub_1d70 : 584 -> 576
~ sub_21d4 -> sub_21cc : 2556 -> 2576
~ sub_2df8 -> sub_2e04 : 4752 -> 4800
~ sub_5424 -> sub_5460 : 796 -> 804
~ sub_78c0 -> sub_7904 : 472 -> 476
~ sub_7c70 -> sub_7cb8 : 256 -> 264
~ sub_8448 -> sub_8498 : 256 -> 276
~ sub_854c -> sub_85b0 : 236 -> 256
~ sub_cfa4 -> sub_d01c : 280 -> 276
~ sub_d9f8 -> sub_da6c : 2600 -> 2592
```
