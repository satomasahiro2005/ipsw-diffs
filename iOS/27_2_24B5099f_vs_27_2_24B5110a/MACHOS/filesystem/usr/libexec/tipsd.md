## tipsd

> `/usr/libexec/tipsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18cd4` | `0x18d8c` | **`+0xb8`** |
| `__TEXT.__auth_stubs` | `0xd70` | `0xd80` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x6c8` | `0x6d0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
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

-866.2.3.0.0
+866.2.4.0.0

-  Symbols:   402
+  Symbols:   403
Symbols:
+ _TPSHMManagerHomeAccessoryAddedNotificationString
Functions:
~ sub_100004ccc : 848 -> 936
~ sub_100006cc0 -> sub_100006d18 : 120 -> 188
~ sub_100006d38 -> sub_100006dd4 : 84 -> 112
```
