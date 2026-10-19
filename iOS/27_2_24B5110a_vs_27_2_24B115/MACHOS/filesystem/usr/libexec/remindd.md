## remindd

> `/usr/libexec/remindd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x825cf0` | `0x825dd4` | **`+0xe4`** |
| `__TEXT.__oslogstring` | `0x62830` | `0x62870` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1bf40` | `0x1bf60` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x28891` | `0x288a1` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x7db8` | `0x7dc0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  11910
+  CStrings:  11912
Functions:
~ sub_1001133f4 : 404 -> 416
~ sub_100113588 -> sub_100113594 : 1156 -> 1372
CStrings:
+ "RDFeedbackProvider: Survey is not enabled for non-seed builds."
+ "enableGroceryFeedbackSurvey"
```
