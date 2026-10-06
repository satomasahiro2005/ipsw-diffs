## Diagnostic-8262

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8262.appex/Diagnostic-8262`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26e0` | `0x2828` | **`+0x148`** |
| `__TEXT.__oslogstring` | `0x411` | `0x493` | **`+0x82`** |
| `__DATA.__objc_const` | `0x400` | `0x430` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x640` | `0x660` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x88c` | `0x8ac` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x800` | `0x820` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1fc` | `0x20c` | **`+0x10`** |
| `__TEXT.__cstring` | `0x5f4` | `0x600` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x2c8` | `0x2d0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x20` | `0x24` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1291.0.0.502.1
+1307.0.16.0.0

-  Functions: 30
+  Functions: 31

-  CStrings:  223
+  CStrings:  228
CStrings:
+ "Bypassing asset downloading since useLocalPDI is set to YES"
+ "TB,R,N,VuseLocalPDI"
+ "Using local PDI, skipping URL requests"
+ "useLocalPDI"
+ "useLocalPDI flag is set to YES"
```
