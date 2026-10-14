## CommCenter

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b559dc` | `0x1b569ec` | **`+0x1010`** |
| `__TEXT.__gcc_except_tab` | `0x1d740c` | `0x1d7528` | **`+0x11c`** |
| `__TEXT.__oslogstring` | `0x176658` | `0x176768` | **`+0x110`** |
| `__TEXT.__objc_methname` | `0x200e3` | `0x201b1` | **`+0xce`** |
| `__DATA.__objc_const` | `0x135b8` | `0x13668` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0xafef8` | `0xaff80` | **`+0x88`** |
| `__TEXT.__const` | `0x23dc44` | `0x23dcc4` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x1926c` | `0x192e4` | **`+0x78`** |
| `__DATA_CONST.__auth_ptr` | `0x15a8` | `0x15e8` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x16ce20` | `0x16ce60` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1a080` | `0x1a0c0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xc574` | `0xc5ac` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x27b8` | `0x27e8` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x3104` | `0x3128` | **`+0x24`** |
| `__TEXT.__auth_stubs` | `0x15490` | `0x15470` | **`-0x20`** |
| `__TEXT.__cstring` | `0x80f1c` | `0x80f3c` | **`+0x20`** |
| `__DATA.__data` | `0xc86c` | `0xc87c` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x8730` | `0x8740` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xaa68` | `0xaa58` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x5a2d5` | `0x5a2e5` | **`+0x10`** |
| `__DATA.__objc_data` | `0x45c8` | `0x45d0` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x4c42` | `0x4c4a` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x614` | `0x61c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x30c` | `0x314` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-13498.0.0.0.0
+13499.0.0.0.0

-  Functions: 133882
-  Symbols:   9261
-  CStrings:  56410
+  Functions: 133904
+  Symbols:   9260
+  CStrings:  56422
Symbols:
+ _$ss6UInt16VMn
+ _$ss6UInt16VN
+ _$ss6UInt16Vs23CustomStringConvertiblesWP
- _$s12TelephonyKit31CrossPlatformCellularPlanClientV10ExportablePAAE27didUpdateTelemetrySessionID07sessionM0ys6UInt16V_tYaF
- _$s12TelephonyKit31CrossPlatformCellularPlanClientV10ExportablePAAE27didUpdateTelemetrySessionID07sessionM0ys6UInt16V_tYaFTu
- _$s12TelephonyKit31CrossPlatformCellularPlanClientV10ImportablePAAE27didUpdateTelemetrySessionID07sessionM0ys6UInt16V_tYaF
- _$s12TelephonyKit31CrossPlatformCellularPlanClientV10ImportablePAAE27didUpdateTelemetrySessionID07sessionM0ys6UInt16V_tYaFTu
CStrings:
+ "@\"NSNumber\"16@0:8"
+ "Bootstrap disabled"
+ "Bootstrap disabled - deactivating"
+ "Deferring notification session - bootstrap disabled"
+ "Not preparing acquisition session - bootstrap disabled"
+ "Not starting acquisition session - bootstrap disabled"
+ "T@\"NSNumber\",N,R"
+ "T@\"NSNumber\",R"
+ "initWithUnsignedShort:"
+ "sending crossPlatformTransfer CA event with sessionID:%@"
+ "telemetrySessionID"
+ "telemetrySessionID updated to "
```
