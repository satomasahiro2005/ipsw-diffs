## NanoUniverse

> `/System/Library/PrivateFrameworks/NanoUniverse.framework/NanoUniverse`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x415c0` | `0x415e4` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0xbf0` | `0xbf8` | **`+0x8`** |

### Other Changes

```diff

-  Symbols:   1909
+  Symbols:   1910
Symbols:
+ _objc_release_x10
Functions:
~ -[NUNICalliopeRenderer _renderOffscreenSceneWithScene:spheroids:viewport:commandBuffer:frameBufferIndex:drawableTexture:] : 2432 -> 2440
~ -[NUNICalliopeRenderer _setupBloomChainWithViewport:bloomTexture:] : 724 -> 716
~ -[NUNICalliopeRenderer _computeBloomChainTextures:] : 552 -> 556
~ -[NUNICalliopeRenderer spheroidAtPoint:scene:viewport:] : 824 -> 832
~ -[NUNICalliopeResourceManager patchTextureGroupForSpheroid:index:suffix:] : 608 -> 612
~ -[NUNIClassicGeometry addVertices:count:] : 120 -> 124
~ -[NUNIClassicRenderer renderWithScene:viewport:commandBuffer:passDescriptor:] : 960 -> 968
~ -[NUNIClassicRenderer renderOffscreenWithScene:viewport:commandBuffer:] : 824 -> 832
~ -[NUNIAegirResourceManager setPipelineConstants:] : 932 -> 924
~ sub_292932b10 -> sub_293685b2c : 3504 -> 3508
~ sub_292934278 -> sub_293687298 : 2064 -> 2068
```
