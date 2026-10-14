## RTSCV1

> `/System/Library/VideoProcessors/RTSCV1.bundle/RTSCV1`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf46c` | `0xf4d8` | **`+0x6c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-764.40.7.0.0
+764.42.8.0.0
Functions:
~ -[RTSCProcessorV1 _updateOutputFOV] : 996 -> 1088
~ -[RTSCProcessorV1 _updateStabilization] : 392 -> 404
~ -[RTSCProcessorV1 _calculateCropRectForOutputFOV:] : 392 -> 380
~ -[RTSCProcessorV1 _confineCropRectToValidImageCircle:] : 288 -> 304
```
