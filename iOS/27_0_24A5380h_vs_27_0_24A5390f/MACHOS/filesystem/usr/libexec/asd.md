## asd

> `/usr/libexec/asd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x782940` | `0x781b30` | **`-0xe10`** |
| `__DATA_CONST.__const` | `0x29298` | `0x28fc8` | **`-0x2d0`** |
| `__TEXT.__swift5_capture` | `0x1248` | `0x1128` | **`-0x120`** |
| `__DATA_CONST.__got` | `0xe38` | `0xe70` | **`+0x38`** |
| `__DATA.__data` | `0xebc0` | `0xebf0` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x1f8d` | `0x1f5d` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x4738` | `0x4710` | **`-0x28`** |
| `__TEXT.__auth_stubs` | `0x30f0` | `0x30e0` | **`-0x10`** |
| `__TEXT.__cstring` | `0x2c72` | `0x2c82` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x3224` | `0x3234` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1888` | `0x1880` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 6339
-  Symbols:   2023
-  CStrings:  2700
+  Functions: 6295
+  Symbols:   2022
+  CStrings:  2704
Symbols:
+ _abort_with_reason
- _abort
- _swift_willThrowTypedImpl
CStrings:
+ "DK"
+ "GS"
+ "LF"
+ "O"
```
