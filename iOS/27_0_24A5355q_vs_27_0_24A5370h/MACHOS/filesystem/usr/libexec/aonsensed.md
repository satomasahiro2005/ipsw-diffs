## aonsensed

> `/usr/libexec/aonsensed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x408118` | `0x407a3c` | **`-0x6dc`** |
| `__TEXT.__oslogstring` | `0x314a` | `0x317a` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x3360` | `0x3370` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x11998` | `0x11988` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x19c0` | `0x19c8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0xc088` | `0xc080` | **`-0x8`** |

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
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-112.0.1.0.0
+114.0.0.0.0

-  Functions: 27119
+  Functions: 27121

-  CStrings:  4476
+  CStrings:  4477
Symbols:
+ _$s8Dispatch0A3QoSV13userInitiatedACvgZ
- __swift_FORCE_LOAD_$_swiftCoreLocation
CStrings:
+ "DaemonBackgroundActor,configuredQoS,%s"
```
