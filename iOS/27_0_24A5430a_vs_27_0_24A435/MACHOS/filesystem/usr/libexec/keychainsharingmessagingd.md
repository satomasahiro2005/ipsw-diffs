## keychainsharingmessagingd

> `/usr/libexec/keychainsharingmessagingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x160a4` | `0x160cc` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0xdf0` | `0xde0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x700` | `0x6f8` | **`-0x8`** |

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

-62460.2.2.0.0
+62460.2.3.0.0

-  Symbols:   337
+  Symbols:   336
Symbols:
- _objc_retain_x9
Functions:
~ sub_100007094 : 680 -> 684
~ sub_10000cee4 -> sub_10000cee8 : 4224 -> 4248
~ sub_1000112e0 -> sub_1000112fc : 356 -> 360
~ sub_100016cf4 -> sub_100016d14 : 256 -> 264
```
