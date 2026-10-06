## AlchemistService

> `/System/Library/PrivateFrameworks/AlchemistService.framework/AlchemistService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6c948` | `0x6e884` | **`+0x1f3c`** |
| `__DATA.__bss` | `0xb080` | `0x9380` | **`-0x1d00`** |
| `__DATA_DIRTY.__bss` | `0x180` | `0x1e80` | **`+0x1d00`** |
| `__DATA_DIRTY.__data` | `0x1758` | `0x1ef8` | **`+0x7a0`** |
| `__DATA.__data` | `0x1730` | `0x1248` | **`-0x4e8`** |
| `__TEXT.__oslogstring` | `0x1cad` | `0x216d` | **`+0x4c0`** |
| `__AUTH.__objc_data` | `0x3d0` | `0x48` | **`-0x388`** |
| `__DATA_DIRTY.__objc_data` | `0x50` | `0x3d8` | **`+0x388`** |
| `__AUTH.__data` | `0x4b0` | `0x290` | **`-0x220`** |
| `__TEXT.__eh_frame` | `0x3848` | `0x38b0` | **`+0x68`** |
| `__DATA.__common` | `0x120` | `0xd0` | **`-0x50`** |
| `__DATA_DIRTY.__common` | `0x98` | `0xe8` | **`+0x50`** |
| `__TEXT.__cstring` | `0x19b3` | `0x19f3` | **`+0x40`** |
| `__TEXT.__const` | `0x7516` | `0x7546` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1a98` | `0x1ab8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1328` | `0x1318` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x174e` | `0x175e` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1aec` | `0x1af8` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x9d0` | `0x9d8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x194` | `0x198` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x9c` | `0xa0` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x94` | `0x98` | **`+0x4`** |

### Other Changes

```diff

-32.0.2.0.0
+32.0.3.0.0

-  Functions: 2262
-  Symbols:   1203
-  CStrings:  317
+  Functions: 2269
+  Symbols:   1201
+  CStrings:  333
Symbols:
+ ___swift_memcpy213_8
- _CGRectGetMinX
- _CGRectGetMinY
- ___swift_memcpy205_8
CStrings:
+ "\n [Stereo Baking] \n  Near Distance: %{public}s, \n Max disparity %%: %{public}f \n Focal Length(35mm): %{public}f, Recommended stereo baseline (mm): %{public}f"
+ "\n [Stereo Baking] Recommended Disparity Adjustment: %{public}f"
+ "%{public}@ is unsupported in baking, setting to default linearSRGB"
+ "%{public}s checking cancellation"
+ "Baking MXI finished"
+ "Baking MXI started"
+ "Baking: 3dgs rendering finished"
+ "Baking: 3dgs rendering started"
+ "CIImage already has headroom %{public}f, no need to convert."
+ "CIImage is has different headroom %{public}f, convert to %{public}f."
+ "Comment eligible: %{bool,public}d"
+ "Converted CIImage colorspace: %{public}@"
+ "Converting colorspace to %{public}@"
+ "Could not check os eligibility: %{public}s"
+ "Couldn't create auxiliary dictionary for %{public}s"
+ "Couldn't create auxiliary image for %{public}s"
+ "Encountered error: %{public}@.  Retrying - remaining retries available: %{public}ld"
+ "Finished in-process inference operationfor client: %{public}s"
+ "Found too many models at %{private}s"
+ "Generating RefineImage: %{public}ld x %{public}ld"
+ "Generation starting — %{public}ldx%{public}ld %{public}s Pipeline:%{public}s Thermal:%{public}s Memory:%{public}llu PeakMemory: %{public}llu MB"
+ "Image preprocessing complete — %{public}ldx%{public}ld"
+ "Image preprocessing starting"
+ "Inference complete: %{public}s"
+ "Inference starting: %{public}s; Thermal:%{public}s Memory:%{public}llu PeakMemory: %{public}llu MB"
+ "InferenceRequest inference progress updated: %{public}f"
+ "Input CIImage to CVPixelBuffer conversion completed with info: %{public}@"
+ "Input colorspace %{public}@ is not natively supported, will be converted to sRGB."
+ "Input colorspace is not natively supported: %{public}@."
+ "Input image is not supported. Reason: %{public}s"
+ "Loading fov model from resource: %{private}s"
+ "Loading model from resource: %{private}s"
+ "MXI baking triangle density: %{public}f (limit: %{public}f)"
+ "Missing bundle for resources: %{public}s"
+ "Multilayer render finished."
+ "Multilayer render starting"
+ "PPD resize: targeting %f PPD (vFOV=%f°), scale=%f"
+ "Pipeline configuration is not supported. Reason: %{public}s"
+ "Received transition to dynamic mode for %{public}s"
+ "Received transition to loaded for %{public}s"
+ "Received transition to unloaded for %{public}s"
+ "Running inference operation in-process for client: %{public}s"
+ "Running inference operation via ModelManager for client: %{public}s"
+ "Setting OTFRefinement flag from user defaults: %{bool,public}d"
+ "Setting baking resolution from user defaults: %{public}ld"
+ "Setting baking tile size from user defaults: %{public}ld"
+ "Setting memoryless texture flag from user defaults: %{bool,public}d"
+ "Setting ndc overlap factor from user defaults: %{public}f"
+ "Setting number of baking layers from user defaults: %{public}ld"
+ "Setting number of baking passes from user defaults: %{public}ld"
+ "Setting scene complexity reduction retry limit from user defaults: %{public}ld"
+ "Setting scene triangle density limit from user defaults: %{public}f"
+ "Setting separate opaque geometry flag from user defaults: %{bool,public}d"
+ "Setting target refinement PPD (panoEnvironmentMVP) from user defaults: %s"
+ "Setting target refinement PPD from user defaults: %s"
+ "Setting texture compression flag from user defaults: %{bool,public}d"
+ "Splat inference complete — focalLength:%{public}f px"
+ "Splat inference starting"
+ "Successfully transitioned to dynamic mode for %{public}s"
+ "Successfully transitioned to loaded for %{public}s"
+ "Successfully transitioned to unloaded for %{public}s"
+ "Unable to get resources from bundle: %{public}s"
+ "Unknown panoTilingMode '%{public}s', keeping %{public}s."
+ "Unsupported depth pixel format %{public}u."
+ "Unsupported pixel format type in output image: %{public}s"
+ "Using pano tiling mode from user defaults: %{public}s"
+ "[FOV] Cropped image size: %{public}fx%{public}f"
+ "progress error: %{public}s"
+ "progress update: %{public}s"
+ "targetRefinementPPD_Pano"
+ "targetRefinementPPD_PanoMVP"
- "\n [Stereo Baking] \n  Near Distance: %s, \n Max disparity %%: %f \n Focal Length(35mm): %f, Recommended stereo baseline (mm): %f"
- "\n [Stereo Baking] Recommended Disparity Adjustment: %f"
- "%@ is unsupported in baking, setting to default linearSRGB"
- "%s checking cancellation"
- "Applying work around for 176468103"
- "Applying work around for 176468103 pt 2 - closer enforcement"
- "CIImage already has headroom %f, no need to convert."
- "CIImage is has different headroom %f, convert to %f."
- "Comment eligible: %{bool}d"
- "Converted CIImage colorspace: %@"
- "Converting colorspace to %@"
- "Could not check os eligibility: %s"
- "Couldn't create auxiliary dictionary for %s"
- "Couldn't create auxiliary image for %s"
- "Encountered error: %@.  Retrying - remaining retries available: %ld"
- "Finished in-process inference operationfor client: %s"
- "Found too many models at %s"
- "Generating RefineImage: %ld x %ld"
- "InferenceRequest inference progress updated: %f"
- "Input CIImage to CVPixelBuffer conversion completed with info: %@"
- "Input colorspace %@ is not natively supported, will be converted to sRGB."
- "Input colorspace is not natively supported: %@."
- "Input image is not supported. Reason: %s"
- "Loading fov model from resource: %s"
- "Loading model from resource: %s"
- "MXI baking triangle density: %f (limit: %f)"
- "Missing bundle for resources: %s"
- "Pipeline configuration is not supported. Reason: %s"
- "Received transition to dynamic mode for %s"
- "Received transition to loaded for %s"
- "Received transition to unloaded for %s"
- "Running inference operation in-process for client: %s"
- "Running inference operation via ModelManager for client: %s"
- "Setting OTFRefinement flag from user defaults: %{bool}d"
- "Setting baking resolution from user defaults: %ld"
- "Setting baking tile size from user defaults: %ld"
- "Setting memoryless texture flag from user defaults: %{bool}d"
- "Setting ndc overlap factor from user defaults: %f"
- "Setting number of baking layers from user defaults: %ld"
- "Setting number of baking passes from user defaults: %ld"
- "Setting scene complexity reduction retry limit from user defaults: %ld"
- "Setting scene triangle density limit from user defaults: %f"
- "Setting separate opaque geometry flag from user defaults: %{bool}d"
- "Setting texture compression flag from user defaults: %{bool}d"
- "Successfully transitioned to dynamic mode for %s"
- "Successfully transitioned to loaded for %s"
- "Successfully transitioned to unloaded for %s"
- "Unable to get resources from bundle: %s"
- "Unknown panoTilingMode '%s', keeping %s."
- "Unsupported depth pixel format %u."
- "Unsupported pixel format type in output image: %s"
- "Using pano tiling mode from user defaults: %s"
- "[FOV] Cropped image size: %fx%f"
- "progress error: %s"
- "progress update: %s"
```
