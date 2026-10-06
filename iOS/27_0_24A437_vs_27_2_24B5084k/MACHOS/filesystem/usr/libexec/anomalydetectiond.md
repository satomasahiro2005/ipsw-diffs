## anomalydetectiond

> `/usr/libexec/anomalydetectiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3797b0` | `0x37ab00` | **`+0x1350`** |
| `__DATA_CONST.__const` | `0x29230` | `0x292d0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1cba4` | `0x1cbed` | **`+0x49`** |
| `__TEXT.__const` | `0xffb6` | `0xfff6` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xca20` | `0xca60` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x12537` | `0x12559` | **`+0x22`** |
| `__TEXT.__objc_methname` | `0xc263` | `0xc275` | **`+0x12`** |
| `__TEXT.__gcc_except_tab` | `0x10b50` | `0x10b40` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x60f1` | `0x60f4` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-174.0.0.0.0
+175.0.2.0.0

-  Functions: 17293
+  Functions: 17329

-  CStrings:  9424
+  CStrings:  9427
CStrings:
+ "C28@0:8@16B24"
+ "Do not gate upload with manifest, igneousPath %d, containSensorData %d"
+ "checkWithManifest:containSensorData:"
+ "distanceCalibratedPedometer"
+ "inHandDoubleTapBaseDetectorReset"
+ "pencilState"
- "C24@0:8@16"
- "Do not gate upload with manifest, %d"
- "checkWithManifest:"
```
