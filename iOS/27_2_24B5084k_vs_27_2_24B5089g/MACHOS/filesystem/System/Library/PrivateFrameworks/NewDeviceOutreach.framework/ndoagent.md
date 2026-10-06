## ndoagent

> `/System/Library/PrivateFrameworks/NewDeviceOutreach.framework/ndoagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x798d4` | `0x7a124` | **`+0x850`** |
| `__TEXT.__oslogstring` | `0x2e8b` | `0x2f0b` | **`+0x80`** |
| `__DATA_CONST.__objc_dictobj` | `0x50` | `0xa0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x2070` | `0x20b0` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0xfc0` | `0xfe0` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x78` | `0x98` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2600` | `0x2620` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x2d10` | `0x2d20` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x2a4f` | `0x2a5f` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xb30` | `0xb38` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1698` | `0x16a0` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x3fe0` | `0x3fe8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xb8c` | `0xb94` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1cf0` | `0x1ce8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-624.40.14.0.0
+624.40.15.0.0

-  Functions: 2508
-  Symbols:   1225
-  CStrings:  1052
+  Functions: 2511
+  Symbols:   1226
+  CStrings:  1057
Symbols:
+ _$s6NDOAPI15NDOSerialNumberO7isValidySbSSSgFZ
+ _$s6NDOAPI17NDOResponseMapperO8WarrantyO23deviceCoverageCachePath3for10Foundation3URLVSgSS_tFZ
- _$s6NDOAPI17NDOResponseMapperO8WarrantyO32deviceCoverageCachePathForSerialy10Foundation3URLVSSFZ
CStrings:
+ "%s: Malformed/invalid serial number"
+ "Rejected local device warranty request for malformed serial number"
+ "invalid serial number"
+ "isValid(serialNumber:)"
+ "isValidSerialNumber:"
```
