## ReportCrash

> `/System/Library/CoreServices/ReportCrash`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4def4` | `0x4e048` | **`+0x154`** |
| `__DATA_CONST.__cfstring` | `0x7da0` | `0x7dc0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x2d11` | `0x2d31` | **`+0x20`** |
| `__TEXT.__cstring` | `0x5beb` | `0x5bfb` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1056.0.12.0.0
+1056.0.17.0.0

-  CStrings:  2284
+  CStrings:  2286
Functions:
~ sub_100010d80 : 10892 -> 11232
CStrings:
+ "Stripping thread state (register information)"
+ "mdworker"
```
