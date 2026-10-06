## Print Center

> `/Applications/Print Center.app/Print Center`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16680` | `0x166a8` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x1360` | `0x1340` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x9b8` | `0x9a8` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x3b0` | `0x3a0` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
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
+44.1.0.0.0

-  Symbols:   661
+  Symbols:   657
Symbols:
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _objc_retain_x25
- _swift_willThrowTypedImpl
Functions:
~ sub_100006318 : 932 -> 1008
~ sub_100006744 -> sub_100006790 : 432 -> 428
~ sub_10000e838 -> sub_10000e880 : 620 -> 600
~ sub_100015cf8 -> sub_100015d2c : 896 -> 884
```
