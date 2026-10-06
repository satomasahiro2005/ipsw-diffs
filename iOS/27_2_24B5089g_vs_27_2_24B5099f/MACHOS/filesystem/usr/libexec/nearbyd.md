## nearbyd

> `/usr/libexec/nearbyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55d8c0` | `0x55d9c4` | **`+0x104`** |
| `__TEXT.__oslogstring` | `0x63c1a` | `0x63c3a` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x5595c` | `0x55978` | **`+0x1c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-575.0.6.0.0
+575.0.8.0.0

-  CStrings:  19989
+  CStrings:  19990
Functions:
~ sub_10003af78 : 3568 -> 3828
CStrings:
+ "#ni-ca,NIItemFinderBTFinding"
```
