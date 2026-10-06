## searchdiagnose

> `/usr/bin/searchdiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28c5c` | `0x29638` | **`+0x9dc`** |
| `__TEXT.__cstring` | `0x1356` | `0x13b6` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x1580` | `0x15a0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xac8` | `0xad8` | **`+0x10`** |
| `__TEXT.__const` | `0x1898` | `0x1888` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x9d0` | `0x9c0` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2451.1.101.0.0
+2454.100.0.0.0

-  Symbols:   591
-  CStrings:  214
+  Symbols:   593
+  CStrings:  216
Symbols:
+ _$s10Foundation4DateV11distantPastACvgZ
+ _swift_release_x26
CStrings:
+ "Failed to reset timestamp on "
+ "search: Failed to reset timestamp on photo_search.log: "
```
