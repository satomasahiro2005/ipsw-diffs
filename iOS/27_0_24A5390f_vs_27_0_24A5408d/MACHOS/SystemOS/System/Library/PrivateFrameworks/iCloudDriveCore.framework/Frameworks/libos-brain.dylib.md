## libos-brain.dylib

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/Frameworks/libos-brain.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20be74` | `0x20b82c` | **`-0x648`** |
| `__DATA.__bss` | `0x11060` | `0x111e0` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x80e0` | `0x81e0` | **`+0x100`** |
| `__TEXT.__const` | `0xcef8` | `0xcfb8` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x11848` | `0x117f0` | **`-0x58`** |
| `__TEXT.__cstring` | `0x4362` | `0x4382` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x349d` | `0x34bd` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x450c` | `0x4528` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0x2e6c` | `0x2e88` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0xf90` | `0xfa8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x62e0` | `0x62f8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x5312` | `0x5322` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x8f4` | `0x900` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x740` | `0x748` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xcc4` | `0xcbc` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x2e0` | `0x2e4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_selrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5168.0.5.0.2
+5168.0.55.0.0

-  Functions: 6960
-  Symbols:   2118
-  CStrings:  1524
+  Functions: 6969
+  Symbols:   2121
+  CStrings:  1525
Symbols:
+ _NSFileProviderErrorCategoryKey
+ _associated conformance 8os_brain25FileProviderErrorCategoryOSHAASQ
+ _symbolic _____ 8os_brain25FileProviderErrorCategoryO
CStrings:
+ "CommonBrainError.readOnlyShareUploadRejected"
+ "Read-only share upload rejected"
+ "readOnlyShareUpload"
- "CommonBrainError.permissionFailure"
- "Permission failure"
```
