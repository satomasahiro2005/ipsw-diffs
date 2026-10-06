## royacaptured

> `/usr/libexec/royacaptured`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d604` | `0x2d5b4` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x510` | `0x500` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x13d0` | `0x13c0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x9f8` | `0x9f0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   542
+  Symbols:   539
Symbols:
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _swift_willThrowTypedImpl
Functions:
~ sub_100020344 : 880 -> 860
~ sub_1000206b4 -> sub_1000206a0 : 708 -> 688
~ sub_100020978 -> sub_100020950 : 1176 -> 1156
~ sub_100020e10 -> sub_100020dd4 : 1188 -> 1168
```
