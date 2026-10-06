## deviceaccessd

> `/usr/libexec/deviceaccessd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x95d2c` | `0x9616c` | **`+0x440`** |
| `__TEXT.__cstring` | `0x16094` | `0x16154` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0xa864` | `0xa8a4` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x8360` | `0x83a0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x4300` | `0x432c` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x2998` | `0x29c0` | **`+0x28`** |
| `__DATA_CONST.__objc_intobj` | `0xa8` | `0xc0` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x2858` | `0x2868` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1b00` | `0x1b10` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x2808` | `0x2810` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2701.3.0.0.0
+2701.6.0.0.0

-  Functions: 2554
+  Functions: 2557

-  CStrings:  4074
+  CStrings:  4079
CStrings:
+ "-[DADaemonServer _moveWiFiProfileForDevice:fromBundleID:toBundleID:]"
+ "[WiFi] failed to move profile = '%@' from '%@' to '%@' error = '%@'"
+ "[WiFi] moved profile = '%@' from '%@' to '%@'"
+ "_moveWiFiProfileForDevice:fromBundleID:toBundleID:"
+ "setWithObject:"
```
