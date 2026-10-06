## ActivityRingsUI

> `/System/Library/PrivateFrameworks/ActivityRingsUI.framework/ActivityRingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x226e0` | `0x22668` | **`-0x78`** |

### Other Changes

```text
Functions:
~ -[ARUIRenderer _renderRings:commandEncoder:passDescriptor:commandBuffer:withContext:] : 388 -> 384
~ -[ARUIObserverStore enumerateObserversWithBlock:] : 292 -> 288
~ -[ARUISpriteUniforms _updateVertexAttributesWithSprite:inContet:] : 412 -> 404
~ -[ARUIRenderer ringsRenderPipelineConfigurationForRings:context:] : 856 -> 848
~ -[ARUIRenderer renderRingGroupControllers:withSize:intoTexture:withDrawable:waitUntilCompleted:completionHandler:] : 560 -> 556
~ -[ARUIRenderer snapshotRingGroupControllers:withSize:] : 484 -> 480
~ -[ARUIRingGroup _updateRingGroupLayout] : 324 -> 320
~ -[ARUIRingsView _sharedInitWithWithRingGroupControllers:renderer:] : 364 -> 360
~ -[ARUIRingsView _allRings] : 328 -> 324
~ -[ARUIRingsView _anySpriteSheet] : 320 -> 316
~ +[ARUICountdownView(Configuration) countdownViewConfiguredForDisplayWithRingDiameter:] : 668 -> 664
~ _matrix_float4x4_zRotation_and_translation : 260 -> 256
~ ___ARUIColorForCurrentContrastMode_block_invoke : 80 -> 76
~ -[ARUIAnimatableProperty update:] : 696 -> 688
~ -[ARUISpritesRenderer renderSpriteSheet:intoContext:withCommandEncoder:] : 556 -> 552
~ -[ARUIAnimatableObject update:] : 260 -> 256
~ -[ARUIAnimatableObject areAnimationsInProgress] : 260 -> 256
~ ___vfx_script_Sparks_particleInit_47 : 1320 -> 1324
~ -[ARUISpritesParticleRenderer renderSpriteSheet:intoContext:withCommandEncoder:] : 712 -> 688
~ -[ARUIRingUniforms _updateVertexAttributesWithRing:inContext:] : 620 -> 608
~ -[ARUICelebrationsRenderer renderCelebrationsForRings:withCommandBuffer:intoTexture:withContext:] : 584 -> 580
~ sub_1cfe1c178 -> sub_1d42ea104 : 612 -> 608
```
