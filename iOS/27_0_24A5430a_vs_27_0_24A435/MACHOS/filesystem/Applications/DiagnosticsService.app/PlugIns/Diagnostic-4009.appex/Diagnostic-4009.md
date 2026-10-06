## Diagnostic-4009

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-4009.appex/Diagnostic-4009`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77c8` | `0x7a38` | **`+0x270`** |
| `__TEXT.__cstring` | `0xac1` | `0xb33` | **`+0x72`** |
| `__TEXT.__objc_stubs` | `0x1820` | `0x1880` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x1abf` | `0x1b0d` | **`+0x4e`** |
| `__DATA_CONST.__cfstring` | `0x9e0` | `0xa20` | **`+0x40`** |
| `__DATA.__data` | `0x2e0` | `0x300` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x750` | `0x768` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1d8` | `0x1e8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x238` | `0x240` | **`+0x8`** |
| `__TEXT.__const` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xd5c` | `0xd64` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2b0` | `0x2a8` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0x46c` | `0x46d` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-  Functions: 245
-  Symbols:   207
-  CStrings:  569
+  Functions: 244
+  Symbols:   210
+  CStrings:  578
Symbols:
+ _EXDisplayPipeOpenDisplay
+ _OBJC_CLASS_$_NSMutableArray
+ _kFigCapturePortType_RenoFrontFacingSuperWideCamera
+ _kIdentifierInnerFrontSuperWide
- _EXDisplayPipeOpen
CStrings:
+ "/System/Library/MediaCapture/ISP.mediacapture"
+ "AppleCamera"
+ "ISPCaptureDeviceCreate"
+ "InnerFrontSuperWide"
+ "Returning %ld stat sets"
+ "Stats found on index %u."
+ "_innerFrontSuperWideCameraWithDevice:error:"
+ "addObject:"
+ "displayIndex"
+ "numberWithUnsignedInt:"
- "Failed to open ExDisplayPipe client for status!"
```
