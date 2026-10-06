## AppleProResHWDecoder.videodecoder

> `/System/Library/VideoDecoders/AppleProResHWDecoder.videodecoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x221d0` | `0x21a74` | **`-0x75c`** |
| `__TEXT.__oslogstring` | `0x46ce` | `0x487d` | **`+0x1af`** |
| `__TEXT.__gcc_except_tab` | `0x468` | `0x494` | **`+0x2c`** |
| `__TEXT.__cstring` | `0x12e6` | `0x1304` | **`+0x1e`** |

### Other Changes

```diff

-600.45.0.0.0
+600.53.0.0.0

-  Functions: 538
+  Functions: 545

-  CStrings:  424
+  CStrings:  430
CStrings:
+ "AppleProResHW (0x%x): %s(): Invalid Homography Matrix size: %zu, expected: %zu"
+ "ERROR AppleProResHW (0x%x): %d: %s(): AppleProResHW: GetSubFrameInfo failed for YCbCr\n"
+ "ERROR AppleProResHW (0x%x): %d: %s(): ERROR Downscaled stream height+offsetV > BufferPool Plane Height\n"
+ "ERROR AppleProResHW (0x%x): %d: %s(): ERROR Downscaled stream width+offsetH > BufferPool Plane Width\n"
+ "ERROR AppleProResHW (0x%x): %d: %s(): GetSubFrameInfo failed for RAW\n"
+ "ERROR AppleProResHW (0x%x): %d: %s(): LSC metadata keys not present in metadataDictionary\n"
+ "ERROR AppleProResHW (0x%x): %d: %s(): Malformed metadataExt for frame %d: metadataSetSize %u out of bounds (remaining %u), skip sending all metadata\n"
+ "ERROR AppleProResHW (0x%x): %d: %s(): Slice table for picture %d exceeds frameSize %u\n"
+ "ERROR AppleProResHW (0x%x): %d: %s(): VDD metadata keys not present in metadataDictionary\n"
+ "ProResDecoder_GetSubFrameInfo"
- "WARNING AppleProResHW (0x%x): %d: %s(): Invalid Homography Matrix size: %zu, expected: %zu\n"
- "WARNING AppleProResHW (0x%x): %d: %s(): LSC metadata keys not present in metadataDictionary\n"
- "WARNING AppleProResHW (0x%x): %d: %s(): Malformed metadataExt for frame %d: metadataSetSize %u out of bounds (remaining %u), skip sending all metadata\n"
- "WARNING AppleProResHW (0x%x): %d: %s(): VDD metadata keys not present in metadataDictionary\n"
```
