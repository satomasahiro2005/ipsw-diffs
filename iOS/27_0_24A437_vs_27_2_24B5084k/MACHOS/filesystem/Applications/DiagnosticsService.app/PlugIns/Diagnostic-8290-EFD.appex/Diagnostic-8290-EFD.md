## Diagnostic-8290-EFD

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8290-EFD.appex/Diagnostic-8290-EFD`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe8b8` | `0xead4` | **`+0x21c`** |
| `__TEXT.__oslogstring` | `0x155b` | `0x1620` | **`+0xc5`** |
| `__TEXT.__objc_methname` | `0x4065` | `0x4115` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0x3420` | `0x3480` | **`+0x60`** |
| `__DATA.__objc_const` | `0x2910` | `0x2940` | **`+0x30`** |
| `__DATA_CONST.__objc_intobj` | `0x300` | `0x330` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0xf00` | `0xf20` | **`+0x20`** |
| `__TEXT.__cstring` | `0xa61` | `0xa7a` | **`+0x19`** |
| `__DATA.__objc_selrefs` | `0xe98` | `0xeb0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x137c` | `0x1384` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x208` | `0x20c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1374.2.2.0.0
+1374.40.35.0.0

-  Functions: 432
+  Functions: 434

-  CStrings:  1065
+  CStrings:  1073
CStrings:
+ "Requesting host tolerate AirPods disconnect for %@ seconds"
+ "Resuming normal AirPods disconnect handling"
+ "T@\"NSNumber\",R,N,V_hostAppDisconnectTimeout"
+ "Unable to request AirPods disconnect tolerance; a mid-test disconnect will cancel the session"
+ "_hostAppDisconnectTimeout"
+ "allowSessionAccessoryDisconnectForDuration:"
+ "clearAllowSessionAccessoryDisconnect"
+ "hostAppDisconnectTimeout"
```
