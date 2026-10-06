## BarcodeScanner.videoprocessor

> `/System/Library/VideoProcessors/BarcodeScanner.videoprocessor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8e20` | `0x8e58` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0xf8` | `0x100` | **`+0x8`** |

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3
Functions:
~ _FigSampleBufferProcessorCreateForBarcodeScanner : 3580 -> 3584
~ _sbp_bcs_setProperty -> _sbp_bcs_setOutputCallback : 2160 -> 164
~ _sbp_bcs_invalidate -> _sbp_bcs_setProperty : 272 -> 2160
~ _sbp_bcs_finalize -> _sbp_bcs_invalidate : 80 -> 292
~ _sbp_bcs_copyDebugDescription -> _sbp_bcs_finalize : 316 -> 80
~ _sbp_bcs_copyProperty -> _sbp_bcs_copyDebugDescription : 840 -> 316
~ _createIOSurfacePropertiesDictionary -> _sbp_bcs_copyProperty : 160 -> 840
~ _sbp_bcs_setOutputCallback -> _createIOSurfacePropertiesDictionary : 164 -> 160
~ _sbp_bcs_processSampleBuffer : 9968 -> 9892
~ _sbp_bcs_updateBarcodeLocations : 2224 -> 2184
~ _detectBarcodesInFrame : 8748 -> 8892
~ _FigDraw420Color : 380 -> 372
~ _FigDrawLumaRectangle : 416 -> 428
```
