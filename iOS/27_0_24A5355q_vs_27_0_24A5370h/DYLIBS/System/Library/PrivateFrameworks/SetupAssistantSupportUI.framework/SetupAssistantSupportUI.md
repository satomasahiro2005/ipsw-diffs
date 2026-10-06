## SetupAssistantSupportUI

> `/System/Library/PrivateFrameworks/SetupAssistantSupportUI.framework/SetupAssistantSupportUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x88ad4` | `0x892c8` | **`+0x7f4`** |
| `__TEXT.__oslogstring` | `0x1ab2` | `0x1b62` | **`+0xb0`** |
| `__AUTH_CONST.__const` | `0x4c50` | `0x4c78` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x1a58` | `0x1a78` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1520` | `0x1538` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x23e8` | `0x2400` | **`+0x18`** |
| `__AUTH.__data` | `0x3260` | `0x3270` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x924` | `0x934` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1e0` | `0x1d4` | **`-0xc`** |
| `__AUTH_CONST.__objc_const` | `0xa328` | `0xa330` | **`+0x8`** |

### Other Changes

```diff

-563.0.0.0.0
+565.0.0.0.0

-  Functions: 3230
-  Symbols:   1718
-  CStrings:  346
+  Functions: 3235
+  Symbols:   1719
+  CStrings:  351
Symbols:
+ -[SASCaptureSessionTextureDataSource captureContextWithID:layerBound:contentsScale:]
+ -[SASFigCaptureSession captureContextWithID:layerBound:contentsScale:error:]
+ GCC_except_table15
+ ___76-[SASFigCaptureSession captureContextWithID:layerBound:contentsScale:error:]_block_invoke
- GCC_except_table14
- GCC_except_table3
- ___43-[SASFigCaptureSession captureLayer:error:]_block_invoke
CStrings:
+ "Capturing Layer"
+ "Capturing Layer Context"
+ "Capturing View"
+ "Failed to capture layer with contextId: %d, error: %@"
+ "Wallpaper failed to load, but did not pass an error"
```
