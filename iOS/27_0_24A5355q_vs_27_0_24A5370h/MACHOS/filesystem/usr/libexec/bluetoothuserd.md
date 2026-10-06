## bluetoothuserd

> `/usr/libexec/bluetoothuserd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f200` | `0x6f4c8` | **`+0x2c8`** |
| `__TEXT.__auth_stubs` | `0x1e80` | `0x1e90` | **`+0x10`** |
| `__TEXT.__cstring` | `0x23d1` | `0x23e1` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xf48` | `0xf50` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x13c8` | `0x13d0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
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

### Other Changes

```diff

-2700.37.0.0.0
+2700.41.1.1.0

-  Symbols:   835
+  Symbols:   836
Symbols:
+ _NSClassFromString
CStrings:
+ "LECAHap"
+ "LECAHapLow"
+ "LECATmap"
+ "LECATmapLow"
- "LECA1"
- "LECA2"
- "LECA3"
- "LECA4"
```
