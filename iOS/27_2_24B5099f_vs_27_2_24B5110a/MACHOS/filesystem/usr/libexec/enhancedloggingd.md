## enhancedloggingd

> `/usr/libexec/enhancedloggingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb5590` | `0xb5890` | **`+0x300`** |
| `__TEXT.__cstring` | `0x2ffd` | `0x305d` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xa450` | `0xa470` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xa80` | `0xa90` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1571` | `0x1581` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x17b0` | `0x17bc` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x1d28` | `0x1d20` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
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

-277.40.10.0.0
+277.42.1.0.0

+  - /System/Library/Frameworks/UniformTypeIdentifiers.framework/UniformTypeIdentifiers

-  Functions: 3022
-  Symbols:   1032
-  CStrings:  1425
+  Functions: 3024
+  Symbols:   1034
+  CStrings:  1427
Symbols:
+ _$s15EnhancedLogging12TargetDeviceV0D4TypeO13homeAccessoryyA2EmFWC
+ _ELSPlatformHomeAccessory
CStrings:
+ "com.apple.perception.PerceptionDaemon.PerceptionDiagnosticExtension"
+ "homeaccessory"
```
