## csfdiagnose

> `/usr/bin/csfdiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16400` | `0x15bf4` | **`-0x80c`** |
| `__TEXT.__swift5_reflstr` | `0x30c` | `0x2bc` | **`-0x50`** |
| `__TEXT.__cstring` | `0xf61` | `0xf21` | **`-0x40`** |
| `__DATA.__data` | `0x918` | `0x8e0` | **`-0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x658` | `0x628` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x2b0` | `0x288` | **`-0x28`** |
| `__TEXT.__auth_stubs` | `0xd20` | `0xd10` | **`-0x10`** |
| `__TEXT.__const` | `0x15b2` | `0x15a2` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x698` | `0x690` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x208` | `0x200` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x4db` | `0x4d3` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-301.24.0.22.0
+301.24.0.25.0

-  Functions: 460
-  Symbols:   371
-  CStrings:  86
+  Functions: 458
+  Symbols:   365
+  CStrings:  84
Symbols:
- _$s25CloudSubscriptionFeatures16AssetDiagnosticsVMa
- _$s25CloudSubscriptionFeatures16AssetDiagnosticsVMn
- _$s25CloudSubscriptionFeatures16AssetDiagnosticsVSEAAMc
- _$s25CloudSubscriptionFeatures16AssetDiagnosticsVSeAAMc
- _$s25CloudSubscriptionFeatures20FrameworkDiagnosticsV13DiagnosticKeyO9admAssetsyA2EmFWC
- _$s25CloudSubscriptionFeatures20FrameworkDiagnosticsV13DiagnosticKeyO9afmAssetsyA2EmFWC
CStrings:
- "lastADMAssetEvaluation"
- "lastAFMAssetEvaluation"
```
