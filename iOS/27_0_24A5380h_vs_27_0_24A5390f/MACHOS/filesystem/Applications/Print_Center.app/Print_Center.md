## Print Center

> `/Applications/Print Center.app/Print Center`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xf91` | `0xff8` | **`+0x67`** |
| `__TEXT.__text` | `0x166a8` | `0x166f4` | **`+0x4c`** |
| `__TEXT.__auth_stubs` | `0x1340` | `0x1330` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x42b` | `0x43b` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x4a4` | `0x4b0` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x9a8` | `0x9a0` | **`-0x8`** |
| `__DATA_CONST.__const` | `0xa58` | `0xa60` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-44.1.0.0.0
+45.0.0.0.0

-  Symbols:   657
-  CStrings:  293
+  Symbols:   656
+  CStrings:  295
Symbols:
- _$s7SwiftUI17VerticalAlignmentV17firstTextBaselineACvgZ
Functions:
~ sub_100014d00 : 692 -> 712
~ sub_100014fb4 -> sub_100014fc8 : 128 -> 132
~ sub_1000163ec -> sub_100016404 : 1712 -> 1756
~ sub_100016bcc -> sub_100016c10 : 128 -> 132
~ sub_100016e50 -> sub_100016e98 : 128 -> 132
CStrings:
+ "The printer software is not compatible with this device."
+ "com.apple.badarch-error"
```
