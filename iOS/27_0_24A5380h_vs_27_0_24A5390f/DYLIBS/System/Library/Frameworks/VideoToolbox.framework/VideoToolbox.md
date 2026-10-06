## VideoToolbox

> `/System/Library/Frameworks/VideoToolbox.framework/VideoToolbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x720a48` | `0x720a64` | **`+0x1c`** |
| `__TEXT.__oslogstring` | `0x2d8b8` | `0x2d8c6` | **`+0xe`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3350.67.2.0.0
+3350.71.2.11.1
Functions:
~ _vtDecompressionDuctEmitDecodedFrame : 3028 -> 3040
~ _VTPixelTransferSessionSetProperty : 496 -> 500
~ _vtCompressionSessionCompressionWork : 11392 -> 11396
~ _VTDecompressionSessionRemote_Invalidate : 1004 -> 1012
CStrings:
+ "<<<< VT-DS >>>> %s: [%p:%{public}s] Output frame for sourceFrameRefCon: %p frame: %p imageBuffer: %p infoFlags: %x status: %d"
+ "description=CoreMedia_VideoToolbox-3350.71.2.11.1"
- "<<<< VT-DS >>>> %s: [%p:%{public}s] Output frame for sourceFrameRefCon: %p frame: %p imageBuffer: %p status: %d"
- "description=CoreMedia_VideoToolbox-3350.67.2"
```
