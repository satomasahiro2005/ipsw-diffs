## JPEGH1.videodecoder

> `/System/Library/VideoDecoders/JPEGH1.videodecoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4378` | `0x438c` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0xd8` | `0xe0` | **`+0x8`** |

### Other Changes

```diff

-3350.58.3.11.1
+3350.63.2.11.1
Functions:
~ _H1JPEGVideoDecoder_Invalidate : 652 -> 660
~ _jpeg_createSuggestedQualityOfServiceTiers : 332 -> 340
~ _H1JPEGVideoDecoder_StartSession : 2244 -> 2240
~ _jpeg_checkAndMaybeUpdateOutputPixelBufferAttributes : 968 -> 976
~ _jpeg_createSurfaceFromBBuf : 1352 -> 1344
~ _releaseJPEGInputSurface : 148 -> 156
```
