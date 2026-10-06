## IOMFB_bics_daemon

> `/usr/libexec/IOMFB_bics_daemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f354` | `0x30868` | **`+0x1514`** |
| `__TEXT.__const` | `0x5064` | `0x5cf4` | **`+0xc90`** |
| `__TEXT.__cstring` | `0x4dac` | `0x51fc` | **`+0x450`** |
| `__TEXT.__eh_frame` | `0xc40` | `0xd48` | **`+0x108`** |
| `__DATA_CONST.__const` | `0xee0` | `0xf90` | **`+0xb0`** |
| `__TEXT.__gcc_except_tab` | `0xaf0` | `0xb5c` | **`+0x6c`** |
| `__DATA.__data` | `0xbc8` | `0xb80` | **`-0x48`** |
| `__TEXT.__unwind_info` | `0xcd8` | `0xd18` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x38c` | `0x3b0` | **`+0x24`** |
| `__TEXT.__swift5_reflstr` | `0x248` | `0x268` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`

### Other Changes

```diff

-700.50.72.0.0
+700.50.80.0.0

-  Functions: 962
+  Functions: 978

-  CStrings:  736
+  CStrings:  762
Symbols:
+ _CFRunLoopTimerInvalidate
+ _exp
- __ZdaPvSt19__type_descriptor_t
- __ZnamSt19__type_descriptor_t
CStrings:
+ "%s saving genx history "
+ "%s: %s file not found, skipping"
+ "%s: concatenated storage is full"
+ "%s: could not allocate enough memory, skipping"
+ "%s: could not stat genx history file, skipping"
+ "%s: failed to read genx history data"
+ "%s: invalid buffer ptr"
+ "%s: invalid concatenated storage header in buffer"
+ "GenX disabled, canceling timer\n"
+ "GenX: backup history storage is not in correct format"
+ "GenX: backup storage is not in correct format"
+ "GenX: ean data too small for concatenated storage"
+ "GenX: ean handle not available for backup history read"
+ "GenX: error with backup history buffer"
+ "GenX: failed to read history from backup: 0x%x"
+ "GenX: failed to upload calibration ACSS matrix %s"
+ "GenX: failed to upload calibration data, disabling GenX"
+ "GenX: failed to upload calibration temperature %s"
+ "GenX: failing to initialize Aref and beta %s skip fitting"
+ "GenX: genx history file is invalid, trying backup history"
+ "GenX: invalid GenX data size in concatenated storage"
+ "GenX: no backup history found in ean"
+ "GenX: no genx history file, trying backup history"
+ "GenX: reading history from storage backup"
+ "GenX: successfully restored history from storage backup"
+ "Invalid buffer"
+ "Not Privileged"
+ "backup genx history"
+ "save_genx_backup"
- " no genx history file "
- "GenX: failed to upload calibration data %s, disabling GenX"
- "diagnostics"
```
