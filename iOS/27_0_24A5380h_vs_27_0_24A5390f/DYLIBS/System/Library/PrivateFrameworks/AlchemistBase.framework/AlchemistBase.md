## AlchemistBase

> `/System/Library/PrivateFrameworks/AlchemistBase.framework/AlchemistBase`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x3280` | `0x2980` | **`-0x900`** |
| `__DATA_DIRTY.__bss` | `—` | `0x900` | **`+0x900`** |
| `__TEXT.__text` | `0x2d62c` | `0x2de14` | **`+0x7e8`** |
| `__DATA_DIRTY.__data` | `0xa30` | `0xd80` | **`+0x350`** |
| `__TEXT.__oslogstring` | `0xc89` | `0xec1` | **`+0x238`** |
| `__AUTH.__data` | `0x1b0` | `—` | **`-0x1b0`** |
| `__DATA.__data` | `0x850` | `0x6f0` | **`-0x160`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x50` | `0xa0` | **`+0x50`** |
| `__DATA.__common` | `0x48` | `0x28` | **`-0x20`** |
| `__DATA_DIRTY.__common` | `0x68` | `0x88` | **`+0x20`** |
| `__TEXT.__cstring` | `0xc10` | `0xc30` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x13e0` | `0x13f0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x978` | `0x980` | **`+0x8`** |

### Other Changes

```diff

-32.0.2.0.0
+32.0.3.0.0

-  Symbols:   598
-  CStrings:  146
+  Symbols:   599
+  CStrings:  153
Symbols:
+ _swift_retain_x26
Functions:
~ sub_25083465c -> sub_2519c85c4 : 1300 -> 2008
~ sub_250834b70 -> sub_2519c8d9c : 508 -> 812
~ sub_250834d6c -> sub_2519c90c8 : 1300 -> 2008
~ sub_250835280 -> sub_2519c98a0 : 508 -> 812
CStrings:
+ "%{public}@ already contains linearized colorspace."
+ "%{public}@ cannot be linearized, set to linearSRGB."
+ "ANE session started for asset at %{private}s with pages: %ld/%ld"
+ "ANE session stopped for asset at %{private}s"
+ "Active ROI aspect ratio is less than lowest enumerated aspect ratio (%{public}f, %{public}f)"
+ "CVPixelBuffer already has %{public}@ colorSpace, skipping convert."
+ "CVPixelBufferCreate failed with error code: %{public}d"
+ "Downsize the pano image with %{public}f aspect ratio, tiling mode: %{public}s."
+ "Error converting MLMultiArray from Float32 to Float16: %{public}ld"
+ "Failed to create image source image from %{private}s."
+ "FoV predictor model loaded"
+ "FoV predictor model unloading."
+ "Gaussian composition %{public}ld/%{public}ld..."
+ "Incorrect FoV predictor path specified: %{private}s"
+ "Incorrect Gaussian predictor path specified: %{private}s"
+ "Input CIImage to CVPixelBuffer conversion completed with info: %{public}@"
+ "Joint predictor model is too old (date: %{public}s). Panorama images require models from 2025_09_16 or later."
+ "Joint predictor model loaded."
+ "Joint predictor model unloading."
+ "Loading FoV predictor model. (%{public}s)"
+ "Loading joint predictor. (%{public}s)"
+ "Model to be loaded has been identified as %{public}s version.\n  "
+ "Saved depth map to %{private}s."
+ "Saved normalized depth map to %{private}s."
+ "The mono-depth buffer shape is invalid. Expect %{public}ld x %{public}ld, but got %{public}s"
+ "Tile prediction %{public}ld/%{public}ld..."
+ "Unable to fetch ANE session starting data for asset at %{private}s"
+ "[FOV] (min constrain) cur %{public}f, maxFPx %{public}f -> %{public}f"
+ "[FOV] ROI to crop horizontal to fit hFOV_degrees(%{public}f) width: %{public}ld -> %{public}f (%{public}f%%)"
+ "[FOV] panoFocalLengthPx %{public}f"
+ "[FOV] roiW, roiH, roiAR: %{public}ld, %{public}ld, %{public}f"
+ "replacing existing"
- "%@ already contains linearized colorspace."
- "%@ cannot be linearized, set to linearSRGB."
- "ANE session started for asset at %{public}s with pages: %ld/%ld"
- "ANE session stopped for asset at %{public}s"
- "Active ROI aspect ratio is less than lowest enumerated aspect ratio (%f, %f)"
- "CVPixelBuffer already has %@ colorSpace, skipping convert."
- "CVPixelBufferCreate failed with error code: %d"
- "Downsize the pano image with %f aspect ratio, tiling mode: %s."
- "Error converting MLMultiArray from Float32 to Float16: %ld"
- "Failed to create image source image from %s."
- "Gaussian composition %ld/%ld..."
- "Incorrect FoV predictor path specified: %s"
- "Incorrect Gaussian predictor path specified: %s"
- "Input CIImage to CVPixelBuffer conversion completed with info: %@"
- "Joint predictor model is too old (date: %s). Panorama images require models from 2025_09_16 or later."
- "Model to be loaded has been identified as %s version.\n  "
- "Saved depth map to %s."
- "Saved normalized depth map to %s."
- "The mono-depth buffer shape is invalid. Expect %ld x %ld, but got %s"
- "Tile prediction %ld/%ld..."
- "Unable to fetch ANE session starting data for asset at %{public}s"
- "[FOV] (min constrain) cur %f, maxFPx %f -> %f"
- "[FOV] ROI to crop horizontal to fit hFOV_degrees(%f) width: %ld -> %f (%f%%)"
- "[FOV] panoFocalLengthPx %f"
- "[FOV] roiW, roiH, roiAR: %ld, %ld, %f"
```
