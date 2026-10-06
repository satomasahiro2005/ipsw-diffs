## GLKit

> `/System/Library/Frameworks/GLKit.framework/GLKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c200` | `0x1c1a4` | **`-0x5c`** |

### Other Changes

```text
Functions:
~ -[GLKEffect init] : 452 -> 456
~ __modelviewMatrixMask : 496 -> 488
~ __useTexCoordAttribMask : 332 -> 328
~ __texturingEnabledMask : 352 -> 348
~ __normalizedNormalsMask : 308 -> 304
~ __vNormalEyeMask : 340 -> 336
~ __vPositionEyeMask : 516 -> 508
~ -[GLKEffect initWithPropertyArray:] : 992 -> 984
~ __lightStateChanged : 484 -> 480
~ -[GLKEffect setTextureIndices] : 632 -> 628
~ -[GLKEffect useTexCoordAttrib] : 244 -> 240
~ -[GLKEffect createAndUseProgramWithShadingHash:] : 2056 -> 2040
~ -[GLKEffect bind] : 1296 -> 1284
~ -[GLKEffect initializeMasks] : 168 -> 180
~ -[GLKEffect includeShaderTextForRootNode:] : 1412 -> 1396
~ -[GLKMesh initWithMesh:error:] : 948 -> 940
~ +[GLKMesh _createMeshesFromObject:newMeshes:sourceMeshes:error:] : 452 -> 448
~ +[GLKMesh newMeshesFromAsset:sourceMeshes:error:] : 452 -> 448
~ +[GLKEffectPropertyFog setStaticMasksWithVshRoot:fshRoot:] : 260 -> 280
~ +[GLKEffectPropertyLight setStaticMasksWithVshRoot:fshRoot:] : 376 -> 360
~ -[GLKEffectPropertyLight setLightIndex:] : 164 -> 168
~ +[GLKEffectPropertyMaterial setStaticMasksWithVshRoot:fshRoot:] : 296 -> 288
~ -[GLKEffectPropertyTexture setTextureIndex:] : 540 -> 544
~ -[GLKEffectPropertyTexture setShaderBindings] : 356 -> 352
~ +[GLKEffectPropertyTexture setStaticMasksWithVshRoot:fshRoot:] : 332 -> 320
~ +[GLKEffectPropertyTexture clearAllTexturingMasks:fshMask:] : 132 -> 140
~ -[GLKEffectPropertyTexture bind] : 416 -> 412
~ _GLKQuaternionMakeWithMatrix3 : 448 -> 444
~ _GLKQuaternionMakeWithMatrix4 : 436 -> 432
~ _GLKQuaternionRotateVector3Array : 216 -> 228
~ _GLKQuaternionRotateVector4Array : 216 -> 224
~ -[GLKTexture determinePVRFormat:] : 500 -> 492
~ -[GLKSkyboxEffect updateSkyboxEffect] : 368 -> 376
```
