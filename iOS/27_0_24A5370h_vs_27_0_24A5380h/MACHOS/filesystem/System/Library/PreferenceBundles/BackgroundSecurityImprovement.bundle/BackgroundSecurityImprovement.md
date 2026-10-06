## BackgroundSecurityImprovement

> `/System/Library/PreferenceBundles/BackgroundSecurityImprovement.bundle/BackgroundSecurityImprovement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd7abc` | `0xe0860` | **`+0x8da4`** |
| `__DATA_CONST.__const` | `0x69c0` | `0x7250` | **`+0x890`** |
| `__TEXT.__swift5_typeref` | `0x45de` | `0x4a42` | **`+0x464`** |
| `__TEXT.__swift5_capture` | `0x29ac` | `0x2cf0` | **`+0x344`** |
| `__TEXT.__unwind_info` | `0x2498` | `0x2690` | **`+0x1f8`** |
| `__TEXT.__oslogstring` | `0x29fa` | `0x2bba` | **`+0x1c0`** |
| `__DATA.__bss` | `0x1188` | `0x1298` | **`+0x110`** |
| `__TEXT.__eh_frame` | `0x1f3c` | `0x2004` | **`+0xc8`** |
| `__TEXT.__const` | `0x2a18` | `0x2ac8` | **`+0xb0`** |
| `__TEXT.__objc_methname` | `0x1373` | `0x1403` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0xba0` | `0xc20` | **`+0x80`** |
| `__TEXT.__objc_methtype` | `0x862` | `0x8cd` | **`+0x6b`** |
| `__TEXT.__cstring` | `0x1c7c` | `0x1cbc` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x9d4` | `0xa14` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0xa84` | `0xab0` | **`+0x2c`** |
| `__DATA.__objc_const` | `0xb50` | `0xb70` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x4f8` | `0x518` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x538` | `0x550` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x150` | `0x168` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x5cc` | `0x5e4` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0xbc` | `0xd4` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x64` | `0x78` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x1b4` | `0x1c0` | **`+0xc`** |
| `__DATA.__data` | `0x1438` | `0x1440` | **`+0x8`** |
| `__DATA.__objc_data` | `0x1d0` | `0x1d8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x78` | `0x80` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x154` | `0x15c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xb0` | `0xb4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-772.0.3.0.0
+772.0.8.0.0

-  Functions: 3522
-  Symbols:   183
-  CStrings:  597
+  Functions: 3687
+  Symbols:   186
+  CStrings:  612
Symbols:
+ _OBJC_CLASS_$_SUUIRetryConfiguration
+ _OBJC_CLASS_$_SUUIRetryExecutor
+ _SUErrorDomain
CStrings:
+ "executeOperation:completion:"
+ "initWithConfiguration:identifier:"
+ "initializeState - daemon scan guard passed"
+ "initializeState - waiting for daemon scan to finish"
+ "isScanning:"
+ "performActualInstallation: install could not start - success: %{bool}d, error: %s"
+ "rollbackUpdate: SUS failed to start rollback, result: %{bool}d, error: %s"
+ "scan-guard"
+ "scanGuardRetryConfiguration"
+ "scanWaitConfiguration"
+ "v16@?0@?<v@?B@@\"NSError\">8"
+ "v32@?0q8@16@\"NSError\"24"
+ "waitUntilClientIsNotScanning()"
+ "waitUntilClientIsNotScanning: error querying isScanning: %@, proceeding"
+ "waitUntilClientIsNotScanning: exhausted all retry attempts, proceeding anyway"
```
