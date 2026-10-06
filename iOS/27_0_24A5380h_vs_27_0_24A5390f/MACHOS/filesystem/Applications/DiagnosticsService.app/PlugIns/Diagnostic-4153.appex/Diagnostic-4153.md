## Diagnostic-4153

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-4153.appex/Diagnostic-4153`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8494` | `0x8940` | **`+0x4ac`** |
| `__TEXT.__oslogstring` | `0x282` | `0x3bd` | **`+0x13b`** |
| `__TEXT.__objc_stubs` | `0x2480` | `0x2560` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x2cf8` | `0x2db0` | **`+0xb8`** |
| `__DATA.__objc_selrefs` | `0xc40` | `0xc80` | **`+0x40`** |
| `__DATA.__objc_const` | `0x1238` | `0x1268` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xc08` | `0xc38` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x420` | `0x440` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0xc54` | `0xc72` | **`+0x1e`** |
| `__DATA_CONST.__auth_got` | `0x220` | `0x230` | **`+0x10`** |
| `__TEXT.__const` | `0x60` | `0x70` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1d0` | `0x1e0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x1f8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xdc` | `0xe0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`

### Other Changes

```diff

-1374.0.5.0.0
+1374.0.27.0.0

-  Functions: 203
-  Symbols:   172
-  CStrings:  711
+  Functions: 207
+  Symbols:   175
+  CStrings:  730
Symbols:
+ _CGRectGetMidX
+ _CGRectGetMidY
+ _OBJC_CLASS_$_CATransaction
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
+ "T@\"AVCaptureVideoPreviewLayer\",&,N,V_previewLayer"
+ "_previewLayer"
+ "begin"
+ "commit"
+ "layoutSubviews"
+ "previewLayer"
+ "setAutoresizingMask:"
+ "setDisableActions:"
+ "setPreviewLayer:"
+ "viewDidLayoutSubviews"
```
