## CMCapture

> `/System/Library/PrivateFrameworks/CMCapture.framework/CMCapture`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69734c` | `0x696db0` | **`-0x59c`** |
| `__TEXT.__cstring` | `0xb0599` | `0xb0381` | **`-0x218`** |
| `__TEXT.__oslogstring` | `0x54c86` | `0x54cfb` | **`+0x75`** |
| `__DATA.__data` | `0x988` | `0x930` | **`-0x58`** |
| `__DATA_DIRTY.__data` | `0x6678` | `0x66d0` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x118f8` | `0x11920` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x3e180` | `0x3e198` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x18e40` | `0x18e48` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 39455
-  Symbols:   59487
-  CStrings:  22059
+  Functions: 39435
+  Symbols:   59488
+  CStrings:  22047
Symbols:
+ -[FigCaptureSessionConfiguration initWithXPCEncoding:clientAuditToken:]
+ -[FigCaptureSourceConfiguration initWithXPCEncoding:clientAuditToken:]
+ ___71-[FigCaptureSessionConfiguration initWithXPCEncoding:clientAuditToken:]_block_invoke
+ ___71-[FigCaptureSessionConfiguration initWithXPCEncoding:clientAuditToken:]_block_invoke_2
+ ___block_descriptor_72_e8_32o_e36_B24?0Q8"NSObject<OS_xpc_object>"16ls32l8
- _FigDepthBlurEffectRenderingMaximumSimulatedAperture
- _FigDepthBlurEffectRenderingMinimumSimulatedAperture
- ___54-[FigCaptureSessionConfiguration initWithXPCEncoding:]_block_invoke
- ___54-[FigCaptureSessionConfiguration initWithXPCEncoding:]_block_invoke_2
CStrings:
+ "21:12:50"
+ "<<<< FigCaptureSourceServer >>>> %s: Found matching FigCaptureSource %p for token %d but audit token does not match!"
+ "Oct 13 2026"
- "*maximumSimulatedAperture > 0.0f"
- "*minimumSimulatedAperture > 0.0f"
- "0 == (effectiveVersion >> 16 )"
- "01:21:13"
- "Maximum simulated aperture invalid."
- "Minimum simulated aperture invalid."
- "Oct 10 2026"
- "Unsupported SDOFRendering parameters version"
- "Unsupported version of SDOF; cannot re-use v4 struct."
- "maximumSimulatedAperture"
- "minimumSimulatedAperture"
- "minimumSimulatedAperture is NULL"
- "renderingParametersData.bytes"
- "renderingParametersData.length == renderingParameters->header.size"
- "renderingParametersData.length >= sizeof( FigDepthBlurEffectRenderingParametersHeader )"
```
