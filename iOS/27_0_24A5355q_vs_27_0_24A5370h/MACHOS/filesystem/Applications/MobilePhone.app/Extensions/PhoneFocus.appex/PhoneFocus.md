## PhoneFocus

> `/Applications/MobilePhone.app/Extensions/PhoneFocus.appex/PhoneFocus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9ea0` | `0x9f00` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0xb70` | `0xb40` | **`-0x30`** |
| `__DATA_CONST.__auth_got` | `0x5c0` | `0x5a8` | **`-0x18`** |

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
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3060.100.14.2.1
+3064.100.8.0.0

-  Symbols:   141
+  Symbols:   138
Symbols:
+ _swift_retain_x23
- _swift_release_x25
- _swift_retain_x19
- _swift_retain_x28
- _swift_retain_x9
Functions:
~ sub_10000188c : 268 -> 280
~ sub_1000035ec -> sub_1000035f8 : 280 -> 276
~ sub_100003ae4 -> sub_100003aec : 1048 -> 1052
~ sub_100003fc8 -> sub_100003fd4 : 1752 -> 1760
~ sub_10000476c -> sub_100004780 : 1552 -> 1548
~ sub_100004e38 -> sub_100004e48 : 672 -> 676
~ sub_1000064a8 -> sub_1000064bc : 380 -> 376
~ sub_100006c88 -> sub_100006c98 : 1768 -> 1792
~ sub_100009938 -> sub_100009960 : 1504 -> 1516
~ sub_10000b2dc -> sub_10000b310 : 236 -> 256
~ sub_10000b3c8 -> sub_10000b410 : 252 -> 276
```
