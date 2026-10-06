## DMCApps

> `/System/Library/PrivateFrameworks/DMCApps.framework/DMCApps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x366a8` | `0x37e60` | **`+0x17b8`** |
| `__TEXT.__const` | `0x1324` | `0x13a4` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x18d0` | `0x1950` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x1048` | `0x10a0` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x483` | `0x4d5` | **`+0x52`** |
| `__TEXT.__constg_swiftt` | `0xa28` | `0xa64` | **`+0x3c`** |
| `__TEXT.__eh_frame` | `0x3270` | `0x32a8` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x13b0` | `0x13e0` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x780` | `0x7ac` | **`+0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x560` | `0x580` | **`+0x20`** |
| `__TEXT.__cstring` | `0x8e8` | `0x908` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x4e1` | `0x501` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x2d0` | `0x2e8` | **`+0x18`** |
| `__DATA.__data` | `0x188` | `0x180` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x90` | `0x94` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x34` | `0x38` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x80` | `0x84` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x2b0` | `0x2ac` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x1d8` | `0x1dc` | **`+0x4`** |

### Other Changes

```diff

-107.0.0.0.0
+111.0.0.0.0

-  Functions: 791
-  Symbols:   317
-  CStrings:  155
+  Functions: 794
+  Symbols:   324
+  CStrings:  159
Symbols:
+ ___swift_memcpy96_8
+ _free
+ _realpath$DARWIN_EXTSN
+ _swift_release_x24
+ _symbolic $s7DMCApps0A33DistinguishedAppEvaluatorProtocolP
+ _symbolic _____ 7DMCApps0A25DistinguishedAppEvaluatorV
+ _symbolic _____Sg 7DMCApps11StoreSourceO
+ _symbolic ______p 7DMCApps0A33DistinguishedAppEvaluatorProtocolP
+ _symbolic ______pSg 7DMCApps0A15ManagerProtocolP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5Int64V
- ___swift_memcpy49_8
- _objc_retain_x27
- _symbolic _____y_____G s23_ContiguousArrayStorageC s6UInt64V
CStrings:
+ "Extension path %{public}s escapes app bundle %{public}s"
+ "Failed to resolve app path"
+ "Failed to resolve app path %{public}s"
+ "Failed to resolve app record path %{public}s"
```
