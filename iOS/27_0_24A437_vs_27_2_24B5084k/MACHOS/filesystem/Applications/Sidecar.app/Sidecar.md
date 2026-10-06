## Sidecar

> `/Applications/Sidecar.app/Sidecar`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c20c` | `0x1c3d0` | **`+0x1c4`** |
| `__DATA_CONST.__const` | `0x16f8` | `0x1770` | **`+0x78`** |
| `__TEXT.__swift5_capture` | `0x718` | `0x748` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0xda0` | `0xdc0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x6d8` | `0x6e8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5b0` | `0x5b8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x48c` | `0x490` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-400.42.0.0.0
+412.2.0.0.0

-  Functions: 800
-  Symbols:   355
+  Functions: 806
+  Symbols:   357
Symbols:
+ _objc_retain_x26
+ _swift_isEscapingClosureAtFileLocation
```
