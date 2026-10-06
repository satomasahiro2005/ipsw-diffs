## MercuryPosterExtension

> `/System/Library/ExtensionKit/Extensions/MercuryPosterExtension.appex/MercuryPosterExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfd5e4` | `0x107ebc` | **`+0xa8d8`** |
| `__DATA_CONST.__const` | `0xf0d8` | `0x104b8` | **`+0x13e0`** |
| `__DATA.__bss` | `0x7890` | `0x8490` | **`+0xc00`** |
| `__TEXT.__const` | `0xb2b8` | `0xbd88` | **`+0xad0`** |
| `__DATA.__objc_const` | `0x6718` | `0x70e0` | **`+0x9c8`** |
| `__DATA.__data` | `0x5608` | `0x5fa0` | **`+0x998`** |
| `__TEXT.__swift5_fieldmd` | `0x432c` | `0x4a78` | **`+0x74c`** |
| `__TEXT.__constg_swiftt` | `0x36b8` | `0x3d94` | **`+0x6dc`** |
| `__TEXT.__swift5_reflstr` | `0x428e` | `0x493e` | **`+0x6b0`** |
| `__TEXT.__cstring` | `0x30d1` | `0x34c1` | **`+0x3f0`** |
| `__TEXT.__eh_frame` | `0x2000` | `0x23a8` | **`+0x3a8`** |
| `__TEXT.__objc_methname` | `0x82f8` | `0x8628` | **`+0x330`** |
| `__TEXT.__unwind_info` | `0x1bd0` | `0x1dc8` | **`+0x1f8`** |
| `__TEXT.__swift5_typeref` | `0x2357` | `0x2519` | **`+0x1c2`** |
| `__TEXT.__objc_classname` | `0xa64` | `0xba4` | **`+0x140`** |
| `__TEXT.__objc_stubs` | `0x2e40` | `0x2f40` | **`+0x100`** |
| `__TEXT.__swift5_assocty` | `0x390` | `0x408` | **`+0x78`** |
| `__DATA_CONST.__auth_ptr` | `0x760` | `0x7c8` | **`+0x68`** |
| `__TEXT.__swift5_types` | `0x348` | `0x3b0` | **`+0x68`** |
| `__TEXT.__swift5_proto` | `0x3e8` | `0x44c` | **`+0x64`** |
| `__TEXT.__objc_methtype` | `0x3478` | `0x34d2` | **`+0x5a`** |
| `__DATA.__objc_selrefs` | `0x1928` | `0x1970` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x1e40` | `0x1e80` | **`+0x40`** |
| `__DATA.__common` | `0x38b0` | `0x38e8` | **`+0x38`** |
| `__DATA_CONST.__objc_classlist` | `0x118` | `0x148` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x370` | `0x398` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0xf28` | `0xf48` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1c0c` | `0x1c2c` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x6e8` | `0x700` | **`+0x18`** |
| `__TEXT.__swift5_mpenum` | `0x90` | `0x98` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 2735
-  Symbols:   396
-  CStrings:  2140
+  Functions: 2933
+  Symbols:   401
+  CStrings:  2219
Symbols:
+ _MTKTextureLoaderOriginFlippedVertically
+ _OBJC_CLASS_$_PRUnlockSpringConfiguration
+ _OBJC_CLASS_$_USKData
+ _dispatch_semaphore_create
+ _expf
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
- _objc_release_x9
- _objc_retain_x11
CStrings:
+ "Cx"
+ "Dx"
+ "Failed to create blit encoder"
+ "Failed to create texture array"
+ "Localizable-V63-V64"
+ "Lx"
+ "Rx"
+ "Tf,R"
+ "Unsupported format: "
+ "Unsupported primvar format: "
+ "Vitra.TextureLoader.blitQueue"
+ "Vitra.renderPipeline"
+ "Vitra.uniformsBuffer"
+ "Vitra::Glare::composite"
+ "Vitra::Glare::downsample"
+ "Vitra::Glare::tint_threshold"
+ "Vitra::Glare::upsample"
+ "Vitra::fragment_s"
+ "_TtC22MercuryPosterExtension5Vitra"
+ "_TtCC22MercuryPosterExtension5Vitra10VitraBloom"
+ "_TtCC22MercuryPosterExtension5Vitra10VitraScene"
+ "_TtCC22MercuryPosterExtension5Vitra11VitraCamera"
+ "_TtCC22MercuryPosterExtension5Vitra12VitraMeshV6x"
+ "_TtCC22MercuryPosterExtension5Vitra9VitraMesh"
+ "bloom"
+ "bloomChain"
+ "boundaryCropTexture"
+ "cachedRenderPassDescriptor"
+ "colorTextures"
+ "compositeParams"
+ "compositePipeline"
+ "constant"
+ "distancesTexture"
+ "easedDimming"
+ "easedGyro"
+ "f16@0:8"
+ "faceVarying"
+ "fillTexture"
+ "floatArray:maxCount:"
+ "forwardProgressUsage"
+ "maskTexture"
+ "matchCoverSheetExplicitly"
+ "maxSize"
+ "meshes"
+ "metadata"
+ "minLOD"
+ "newTexturesWithContentsOfURLs:options:completionHandler:"
+ "noisesTexture"
+ "offscreenTexture"
+ "orthoScale"
+ "postProcessUniforms"
+ "primvars:islandID"
+ "recommendedPersistentThreadgroupsPerGridForThreadsPerThreadgroup:"
+ "setAlphaToCoverageEnabled:"
+ "shadowsTexture"
+ "thresholdParams"
+ "tintThresholPipeline"
+ "transitionTracker"
+ "uniform"
+ "upsamplePipeline"
+ "v24@?0@\"NSArray\"8@\"NSError\"16"
+ "vertex"
+ "vertexDescriptor"
+ "vitra_boundary_crop"
+ "vitra_color_ramp_c1-v63-v64"
+ "vitra_color_ramp_c2-v63-v64"
+ "vitra_fill-v63-v64"
+ "vitra_noise-v63-v64"
+ "vitra_noise_1-v63-v64"
+ "vitra_noise_10-v63-v64"
+ "vitra_noise_11-v63-v64"
+ "vitra_noise_2-v63-v64"
+ "vitra_noise_3-v63-v64"
+ "vitra_noise_4-v63-v64"
+ "vitra_noise_5-v63-v64"
+ "vitra_noise_6-v63-v64"
+ "vitra_noise_7-v63-v64"
+ "vitra_noise_8-v63-v64"
+ "vitra_noise_9-v63-v64"
```
