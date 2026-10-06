## CarPlaySettings

> `/Applications/CarPlaySettings.app/CarPlaySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd0a08` | `0xd2754` | **`+0x1d4c`** |
| `__TEXT.__swift5_typeref` | `0xf638` | `0xf808` | **`+0x1d0`** |
| `__TEXT.__eh_frame` | `0x2060` | `0x21a0` | **`+0x140`** |
| `__DATA.__data` | `0x4dd8` | `0x4ed8` | **`+0x100`** |
| `__TEXT.__const` | `0x6c24` | `0x6d24` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x58c0` | `0x5980` | **`+0xc0`** |
| `__DATA.__bss` | `0x4698` | `0x4738` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x33c8` | `0x3460` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x2744` | `0x27a4` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x12f15` | `0x12f65` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x34c0` | `0x3500` | **`+0x40`** |
| `__TEXT.__cstring` | `0x4114` | `0x4154` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x9ae0` | `0x9b20` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x1914` | `0x193c` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x3630` | `0x3650` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x760` | `0x778` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x14b4` | `0x14c8` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x3f00` | `0x3f10` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1b28` | `0x1b38` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1c73` | `0x1c83` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x104` | `0x114` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0xb0` | `0xbc` | **`+0xc`** |
| `__DATA.__objc_data` | `0x37d8` | `0x37e0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xe0` | `0xe8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1ec` | `0x1f0` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x1e0` | `0x1e4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-571.3.0.0.0
+574.2.0.0.0

-  Functions: 4760
-  Symbols:   1668
-  CStrings:  4191
+  Functions: 4797
+  Symbols:   1670
+  CStrings:  4196
Symbols:
+ _$sScC6resume8throwingyq_n_tF
+ _AFIsLinwoodEnabledAndAvailable
CStrings:
+ "Failed to get active drive mode or display name, defaulting to Normal: %@"
+ "Initialized active drive mode: %@ (display name: %@)"
+ "SIRI_TITLE"
+ "com.apple.SiriApp"
+ "crsui_glassSymbolImageNamed:compatibleWithTraitCollection:"
+ "displayName(for:)"
+ "getDisplayNameForDriveMode:completionHandler:"
- "Failed to get initial active drive mode, defaulting to Normal: %@"
- "Initialized active drive mode: %@"
```
