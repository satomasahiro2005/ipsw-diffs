## bluetoothuserd

> `/usr/libexec/bluetoothuserd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x2461` | `0x2471` | **`+0x10`** |
| `__TEXT.__text` | `0x711c8` | `0x711b8` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2701.3.0.0.0
+2701.7.0.0.0

-  CStrings:  1116
+  CStrings:  1117
Functions:
~ sub_100002a78 : 3320 -> 3300
~ sub_1000037dc -> sub_1000037c8 : 64 -> 68
CStrings:
+ "MusicHandoffScan"
```
