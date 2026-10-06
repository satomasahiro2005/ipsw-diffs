## NanoUniverse

> `/System/Library/PrivateFrameworks/NanoUniverse.framework/NanoUniverse`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41550` | `0x414d0` | **`-0x80`** |
| `__TEXT.__unwind_info` | `0xd68` | `0xd70` | **`+0x8`** |

### Other Changes

```diff

-38.0.0.0.0
+39.0.0.0.0
Functions:
~ -[NUNIGlobetrotterRenderer _renderGlobeLinesWithCommandBuffer:state:spheroid:] : 852 -> 848
~ __NUNIEqualize : 428 -> 432
~ __NUNIAddCloudLayer : 196 -> 204
~ __NUNIConvertEquirectangularToOctahedral : 716 -> 728
~ __NUNIGenerateAllMipmapsR8 : 264 -> 276
~ -[NUNIAstronomyVistaView setTritiumBrightness:] : 268 -> 264
~ -[NUNIAstronomyVistaView showSupplemental:animated:] : 1912 -> 1904
~ _NUNIAstronomyVistaView_GenerateZoomAnimationArrayFromSceneBlob : 3952 -> 3848
~ _NUNIAstronomyVistaView_GenerateCarouselAnimationArrayFromSceneBlob : 3272 -> 3188
~ -[NUNIAstronomyVistaView applyVista:transitionStyle:] : 1400 -> 1388
~ ___NUNIAstronomyComplicationForegroundColor_block_invoke : 180 -> 184
~ -[NUNIScene update:] : 420 -> 416
~ -[NUNIScene isAnimating:forKeys:] : 344 -> 340
~ -[NUNIScene addAnimation:] : 392 -> 388
~ -[NUNIScene removeAllAnimationsFor:withKeys:] : 432 -> 428
~ -[NUNIScene updateSunLocationForDate:animated:lightingPreference:adjustEarthRotation:] : 1328 -> 1324
~ -[NUNIScene spheroidOfType:] : 300 -> 296
~ -[NUNIScene packIntoBlob] : 280 -> 284
~ -[NUNIScene unpackFromBlob:] : 252 -> 256
~ -[NUNICalliopeRenderer _updateBaseUniformsForViewport:] : 712 -> 700
~ -[NUNICalliopeRenderer _renderPatchSpheroid:frustumCullingState:drawableSize:frameBufferIndex:renderEncoder:] : 4112 -> 4132
~ -[NUNICalliopeRenderer _renderOffscreenSceneWithScene:spheroids:viewport:commandBuffer:frameBufferIndex:drawableTexture:] : 2436 -> 2432
~ -[NUNICalliopeRenderer _setupBloomChainWithViewport:bloomTexture:] : 684 -> 724
~ -[NUNICalliopeRenderer _computeBloomChainTextures:] : 556 -> 552
~ -[NUNICalliopeRenderer prepareWorldSpaceFrustumWithTransform:withState:] : 140 -> 132
~ -[NUNICalliopeRenderer prepareObjectSpaceFrustumWithTransform:withState:] : 204 -> 236
~ -[NUNICalliopeRenderer classifyObjectBoundingBoxVersusFrustum:max:withState:] : 260 -> 256
~ -[NUNICalliopeRenderer isObjectBoundingBoxInsideOrIntersectingFrustum:max:withState:] : 216 -> 212
~ -[NUNICalliopeRenderer .cxx_destruct] : 384 -> 368
~ ___destructor_8_s0_AB8s32n16_S_s8_AE : 68 -> 76
~ -[NUNICalliopeResourceManager setPipelineConstants:] : 284 -> 304
~ -[NUNICalliopeResourceManager _loadGeometry] : 716 -> 720
~ -[NUNICalliopeResourceManager patchIndexCountForLod:] : 36 -> 32
~ -[NUNICalliopeResourceManager textureGroupWithSuffix:] : 324 -> 336
~ -[NUNICalliopeResourceManager purgeAllCloudCoverTextures] : 280 -> 276
~ -[NUNICalliopeResourceManager .cxx_destruct] : 476 -> 472
~ _NUNIMoonPhaseDescription : 148 -> 152
~ -[NUNIAstronomyVistaController prepareForTransitions] : 144 -> 140
~ -[NUNIAstronomyVistaController cleanUpAfterTransitions] : 124 -> 136
~ -[NUNIAstronomyVistaController applyTransitionFraction:fromVista:toVista:] : 416 -> 412
~ -[NUNIAstronomyVistaController applyTransitionFraction:fromVista:fromStyleDefinition:toVista:toStyleDefinition:] : 508 -> 504
~ -[NUNIAstronomyVistaController animateToVista:styleDefinition:duration:] : 344 -> 340
~ +[NUNIAnimation generateSlerpKeys:times:count:from:to:] : 140 -> 148
~ -[NUNIClassicGeometry addIndices:count:vbase:] : 152 -> 160
~ -[NUNIClassicRenderer discard] : 96 -> 104
~ -[NUNIClassicRenderer renderWithScene:viewport:commandBuffer:passDescriptor:] : 968 -> 960
~ -[NUNIClassicRenderer renderOffscreenWithScene:viewport:commandBuffer:] : 832 -> 824
~ _NUNILoadMtlTextureFromMemory : 952 -> 948
~ ___destructor_8_AB0s8n4_s0_AE_s32_s40 : 88 -> 96
~ __NTKCreateHalfOctahedron : 1648 -> 1560
~ -[NUNIAegirResourceManager setPipelineConstants:] : 924 -> 932
~ -[NUNIAegirResourceManager textureGroupWithSuffix:] : 1340 -> 1332
~ -[NUNIAegirResourceManager purgeAllCloudCoverTextures] : 280 -> 276
~ -[NUNIAegirRenderer _updateBaseUniformsForViewport:] : 812 -> 800
~ -[NUNIAegirRenderer _renderOffscreenSceneWithScene:viewport:commandBuffer:frameBufferIndex:drawableTexture:] : 1992 -> 1984
~ -[NUNIAegirRenderer .cxx_destruct] : 368 -> 352
~ sub_28b6ccb80 -> sub_28cc86a94 : 1072 -> 1088
~ sub_28b6cda60 -> sub_28cc87984 : 280 -> 276
~ sub_28b6ce070 -> sub_28cc87f90 : 1072 -> 1088
~ sub_28b6ceff4 -> sub_28cc88f24 : 232 -> 236
~ sub_28b6d04c8 -> sub_28cc8a3fc : 656 -> 664
~ sub_28b6d090c -> sub_28cc8a848 : 1592 -> 1604
~ sub_28b6d1a70 -> sub_28cc8b9b8 : 376 -> 384
~ sub_28b6d6c54 -> sub_28cc90ba4 : 1332 -> 1312
~ sub_28b6d7188 -> sub_28cc910c4 : 272 -> 288
~ sub_28b6d7298 -> sub_28cc911e4 : 652 -> 672
~ sub_28b6da2f0 -> sub_28cc94250 : 264 -> 268
~ sub_28b6da880 -> sub_28cc947e4 : 296 -> 268
~ sub_28b6dbd30 -> sub_28cc95c78 : 1448 -> 1468
~ sub_28b6dc7c0 -> sub_28cc9671c : 2636 -> 2624
~ sub_28b6dd234 -> sub_28cc97184 : 948 -> 956
~ sub_28b6dd5e8 -> sub_28cc97540 : 2344 -> 2360
~ sub_28b6e3a90 -> sub_28cc9d9f8 : 1640 -> 1656
~ sub_28b6e90c8 -> sub_28cca3040 : 3476 -> 3480
~ sub_28b6eab30 -> sub_28cca4aac : 476 -> 480
```
