## DiagnosticsReporter

> `/Applications/DiagnosticsReporter.app/DiagnosticsReporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd04c` | `0xd0c0` | **`+0x74`** |
| `__TEXT.__cstring` | `0x3d3` | `0x405` | **`+0x32`** |

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
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  312
+  CStrings:  313
Functions:
~ sub_1000047dc : 2696 -> 2704
~ sub_100005d80 -> sub_100005d88 : 356 -> 360
~ sub_100005ee4 -> sub_100005ef0 : 1548 -> 1556
~ sub_10000659c -> sub_1000065b0 : 2200 -> 2204
~ sub_100007198 -> sub_1000071b0 : 1660 -> 1688
~ sub_100007814 -> sub_100007848 : 548 -> 556
~ sub_10000b0b0 -> sub_10000b0ec : 3492 -> 3496
~ sub_10000c048 -> sub_10000c088 : 1644 -> 1692
~ sub_10000c6b4 -> sub_10000c724 : 396 -> 400
CStrings:
+ "com.apple.DiagnosticsReporter"
```
