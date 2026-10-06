## Enhanced Logging

> `/Applications/Enhanced Logging.app/Enhanced Logging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77cec` | `0x78128` | **`+0x43c`** |
| `__DATA.__data` | `0x2f60` | `0x2fb0` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x4a43` | `0x4a83` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1fe0` | `0x2020` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x2c4e` | `0x2c8e` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x1c68` | `0x1c38` | **`-0x30`** |
| `__DATA.__objc_data` | `0x24e0` | `0x2508` | **`+0x28`** |
| `__DATA.__objc_const` | `0x2a28` | `0x2a48` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x2268` | `0x2288` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x199e` | `0x19be` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x16d8` | `0x16f0` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xf40` | `0xf50` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x29a0` | `0x29b0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x14d8` | `0x14e0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1950` | `0x1958` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-277.40.5.0.0
+277.40.10.0.0

-  Functions: 2045
-  Symbols:   1134
-  CStrings:  1075
+  Functions: 2047
+  Symbols:   1135
+  CStrings:  1078
Symbols:
+ _$sSS10lowercasedSSyF
CStrings:
+ "hasDiscoveredDevices"
+ "isHidden"
+ "isViewLoaded"
```
