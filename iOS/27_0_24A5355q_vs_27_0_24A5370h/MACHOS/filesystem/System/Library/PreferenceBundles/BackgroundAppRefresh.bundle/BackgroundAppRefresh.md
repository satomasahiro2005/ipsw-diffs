## BackgroundAppRefresh

> `/System/Library/PreferenceBundles/BackgroundAppRefresh.bundle/BackgroundAppRefresh`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0xe50` | `0xe70` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x730` | `0x740` | **`+0x10`** |
| `__TEXT.__text` | `0x100f8` | `0x10104` | **`+0xc`** |

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

-1257.0.0.0.0
+1259.0.0.0.0

-  Symbols:   161
+  Symbols:   163
Symbols:
+ _objc_release_x26
+ _swift_retain_x26
Functions:
~ sub_3938 : 412 -> 388
~ sub_3ad4 -> sub_3abc : 256 -> 276
~ sub_508c -> sub_5088 : 2076 -> 2080
~ sub_6c34 : 656 -> 660
~ sub_9bbc -> sub_9bc0 : 5556 -> 5552
~ sub_dd70 : 924 -> 932
~ sub_eaa0 -> sub_eaa8 : 260 -> 264
~ sub_ed90 -> sub_ed9c : 140 -> 148
~ sub_f2b0 -> sub_f2c4 : 328 -> 320
~ sub_f4dc -> sub_f4e8 : 300 -> 304
~ sub_f9fc -> sub_fa0c : 1224 -> 1188
~ sub_fec4 -> sub_feb0 : 256 -> 260
~ sub_ffc4 -> sub_ffb4 : 628 -> 648
~ sub_10238 -> sub_1023c : 748 -> 756
```
