## applekeystored

> `/usr/libexec/applekeystored`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9d990` | `0x9e060` | **`+0x6d0`** |
| `__DATA.__bss` | `0xbf20` | `0xc250` | **`+0x330`** |
| `__TEXT.__const` | `0x9e49` | `0xa009` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0xfeac` | `0xffbc` | **`+0x110`** |
| `__DATA_CONST.__const` | `0xeaa8` | `0xeb68` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x24d5` | `0x2539` | **`+0x64`** |
| `__TEXT.__swift5_fieldmd` | `0x2e10` | `0x2e60` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x1f78` | `0x1fc8` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x25f8` | `0x2640` | **`+0x48`** |
| `__DATA.__data` | `0x7328` | `0x7368` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x4848` | `0x4868` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x5f8` | `0x610` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2390` | `0x23a8` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x288` | `0x290` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2383.40.15.0.0
+2383.40.18.0.0

-  Functions: 3303
+  Functions: 3316

-  CStrings:  2640
+  CStrings:  2648
CStrings:
+ "/private/var/containers/Data/ProtectedSystem"
+ "ProtectedSystem"
+ "ProtectedSystemData"
+ "ProtectedSystemData Containers"
+ "ProtectedSystemDataContainerDomain"
+ "ProtectedSystemDataRootDomain"
+ "com.apple.DeviceConfigurationAgent"
+ "com.apple.deviceconfigurationd"
```
