## SidecarRelay

> `/usr/libexec/SidecarRelay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8788c` | `0x87b0c` | **`+0x280`** |
| `__TEXT.__objc_stubs` | `0x1a40` | `0x1a60` | **`+0x20`** |
| `__DATA.__data` | `0x38f8` | `0x3908` | **`+0x10`** |
| `__TEXT.__const` | `0x49cd` | `0x49dd` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x2539` | `0x2549` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x820` | `0x828` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x4f8` | `0x500` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-400.39.0.0.0
+400.40.0.0.0

-  Symbols:   773
-  CStrings:  879
+  Symbols:   774
+  CStrings:  880
Symbols:
+ _RPOptionStatusFlags
CStrings:
+ "400.40"
+ "initWithUnsignedLongLong:"
- "400.39"
```
