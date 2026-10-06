## PhotosGenerativeServices

> `/System/Library/PrivateFrameworks/PhotosGenerativeServices.framework/PhotosGenerativeServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb33b8` | `0xafcfc` | **`-0x36bc`** |
| `__TEXT.__cstring` | `0x7494` | `0x70d4` | **`-0x3c0`** |
| `__TEXT.__eh_frame` | `0x61d8` | `0x5e20` | **`-0x3b8`** |
| `__AUTH_CONST.__const` | `0x5a38` | `0x5ba0` | **`+0x168`** |
| `__DATA_DIRTY.__data` | `0x1d00` | `0x1be0` | **`-0x120`** |
| `__AUTH_CONST.__objc_const` | `0x38b0` | `0x37b0` | **`-0x100`** |
| `__TEXT.__unwind_info` | `0x2e80` | `0x2da8` | **`-0xd8`** |
| `__TEXT.__constg_swiftt` | `0x1f94` | `0x1f4c` | **`-0x48`** |
| `__TEXT.__const` | `0x69f0` | `0x6a30` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x233c` | `0x236c` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x6e4` | `0x710` | **`+0x2c`** |
| `__TEXT.__swift_as_cont` | `0x33c` | `0x310` | **`-0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x13c8` | `0x13a0` | **`-0x28`** |
| `__TEXT.__swift5_reflstr` | `0x17dd` | `0x17fd` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x1f7c` | `0x1f94` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x160` | `0x14c` | **`-0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x168` | `0x158` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x506` | `0x516` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1040` | `0x1038` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x158` | `0x150` | **`-0x8`** |

### Other Changes

```diff

-910.27.103.0.0
+910.33.102.0.0

+  - /System/Library/PrivateFrameworks/ModelCatalog.framework/ModelCatalog

-  Functions: 5048
-  Symbols:   1629
-  CStrings:  588
+  Functions: 4992
+  Symbols:   1628
+  CStrings:  565
Symbols:
+ _CGRectApplyAffineTransform
+ ___swift_closure_destructor.31Tm
+ _objc_retain_x11
+ _symbolic _____ 24PhotosGenerativeServices17GuardrailDetectorC21runOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in4face8depthmap8maskInfoySo6CGRectV_AA12DetectedFaceVSo10MTLTexture_pAC0v4MaskS0AELLVSgtF12QueueElementL_V
+ _symbolic _____ 24PhotosGenerativeServices18InpaintADMPipelineV10TileCanvasV
+ _symbolic _____ 24PhotosGenerativeServices19PGSServerGuardrailsO
+ _symbolic _____Sg 16VisualGeneration0A9GeneratorC20RequestConfigurationV09ImageTileE0V
+ _symbolic _____Sg 16VisualGeneration5ImageO
+ _symbolic _____Sg 24PhotosGenerativeServices18InpaintADMPipelineV10TileCanvasV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 24PhotosGenerativeServices17GuardrailDetectorC21runOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in4face8depthmap8maskInfoySo6CGRectV_AC12DetectedFaceVSo10MTLTexture_pAE0y4MaskV0AGLLVSgtF12QueueElementL_V
+ _type_layout_string 24PhotosGenerativeServices17GuardrailDetectorC21runOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in4face8depthmap8maskInfoySo6CGRectV_AA12DetectedFaceVSo10MTLTexture_pAC0v4MaskS0AELLVSgtF12QueueElementL_V
+ _type_layout_string 24PhotosGenerativeServices18InpaintADMPipelineV10TileCanvasV
- _OBJC_CLASS_$_NSData
- _OBJC_CLASS_$_NSHTTPURLResponse
- _OBJC_CLASS_$_NSURLSession
- _OUTLINED_FUNCTION_156
- __DATA__TtC24PhotosGenerativeServices17ADMNetworkService
- __DATA__TtC24PhotosGenerativeServices21ReframeNetworkService
- __METACLASS_DATA__TtC24PhotosGenerativeServices17ADMNetworkService
- __METACLASS_DATA__TtC24PhotosGenerativeServices21ReframeNetworkService
- _symbolic _____ 24PhotosGenerativeServices17ADMNetworkServiceC
- _symbolic _____ 24PhotosGenerativeServices17GuardrailDetectorC21runOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in4face8depthmapySo6CGRectV_AA12DetectedFaceVSo10MTLTexture_ptF12QueueElementL_V
- _symbolic _____ 24PhotosGenerativeServices21ReframeNetworkServiceC
- _symbolic _____y_____G s23_ContiguousArrayStorageC 24PhotosGenerativeServices17GuardrailDetectorC21runOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in4face8depthmapySo6CGRectV_AC12DetectedFaceVSo10MTLTexture_ptF12QueueElementL_V
- _type_layout_string 24PhotosGenerativeServices17GuardrailDetectorC21runOcclusionDetection33_5EE2695231A8854EF8EA336C55C41202LL2in4face8depthmapySo6CGRectV_AA12DetectedFaceVSo10MTLTexture_ptF12QueueElementL_V
CStrings:
+ "PGSInpaintScaledMaskSensitivity"
+ "VGF request timed out after %llds"
- "Bad default combination: PCC is not supported without VisualGeneration"
- "Clementine: Cleanup request done"
- "Clementine: Reframe request done"
- "Clementine: Submitting cleanup request to server..."
- "Clementine: Submitting reframe request ("
- "Failed to parse JSON string: "
- "Failed to parse server response: "
- "First few characters: '"
- "GenerativeEdit.CleanUp"
- "Invalid JSON response"
- "Invalid response from server"
- "Invalid response from server: "
- "PGSUseVisualGeneration"
- "Reframe request payload size: "
- "Server duration: "
- "Server returned HTTP "
- "SpatialRefinementEndPoint"
- "SpatialReframeDiagnostics/spatial_refinement_reference_sent"
- "SpatialReframeDiagnostics/spatial_refinement_target_sent"
- "SpatialReframeImageCompression"
- "Using override URL: %s"
- "application/json"
- "didn't get expected result from the server"
- "no RGB colorspace"
- "no gray colorspace"
```
