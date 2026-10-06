## FRC

> `/System/Library/PrivateFrameworks/FRC.framework/FRC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x2d0` | `—` | **`-0x2d0`** |
| `__DATA_DIRTY.__objc_data` | `0xbe0` | `0xeb0` | **`+0x2d0`** |
| `__TEXT.__text` | `0x400dc` | `0x400fc` | **`+0x20`** |

### Other Changes

```text
Functions:
~ _saveTextureInterleaved : 324 -> 328
~ _readYUV10bit : 484 -> 480
~ _writeYUV10bit : 476 -> 472
~ -[OpticalFlowAnalyzer processGPUOutputs:blockWidth:blockHeight:faceHandLegBoundingBoxBlocks:] : 2132 -> 2168
```
