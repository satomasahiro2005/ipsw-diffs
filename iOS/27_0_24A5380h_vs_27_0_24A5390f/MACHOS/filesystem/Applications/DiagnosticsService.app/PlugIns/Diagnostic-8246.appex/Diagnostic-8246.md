## Diagnostic-8246

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8246.appex/Diagnostic-8246`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4950` | `0x4c60` | **`+0x310`** |
| `__TEXT.__oslogstring` | `0x3f2` | `0x52d` | **`+0x13b`** |
| `__TEXT.__gcc_except_tab` | `0x70` | `—` | **`-0x70`** |
| `__TEXT.__objc_methname` | `0x1795` | `0x1802` | **`+0x6d`** |
| `__TEXT.__objc_stubs` | `0x1620` | `0x1660` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x730` | `0x760` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x694` | `0x6ac` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x3d0` | `0x3e0` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x138` | `0x130` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__TEXT.__const` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x148` | `0x140` | **`-0x8`** |
| `__TEXT.__objc_methtype` | `0x41b` | `0x41e` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1374.0.5.0.0
+1374.0.27.0.0

-  Functions: 124
-  Symbols:   143
-  CStrings:  427
+  Functions: 126
+  Symbols:   144
+  CStrings:  441
Symbols:
+ _CGRectGetMidX
+ _CGRectGetMidY
+ _OBJC_CLASS_$_CATransaction
- __Unwind_Resume
- ___objc_personality_v0
CStrings:
+ "@\"AVCaptureVideoPreviewLayer\""
+ "Device does not have Exclaves. Skipping stat capture."
+ "Display pipe stats captured"
+ "Exclaves is not supported, skipping status."
+ "Exclaves is supported."
+ "Platform has display pipe stats, preparing to capture"
+ "Retrieving display pipe stats..."
+ "Returning %lu stats for display pipe client"
+ "Starting display pipe stat capture"
+ "T@\"AVCaptureVideoPreviewLayer\",&,N,V_capturePreviewLayer"
+ "_capturePreviewLayer"
+ "begin"
+ "capturePreviewLayer"
+ "commit"
+ "layoutSubviews"
+ "setAutoresizingMask:"
+ "setCapturePreviewLayer:"
+ "setDisableActions:"
+ "viewDidLayoutSubviews"
- "@\"DAExclavesStatusCapture\""
- "T@\"DAExclavesStatusCapture\",&,N,V_exclavesCapture"
- "_exclavesCapture"
- "exclavesCapture"
- "setExclavesCapture:"
```
