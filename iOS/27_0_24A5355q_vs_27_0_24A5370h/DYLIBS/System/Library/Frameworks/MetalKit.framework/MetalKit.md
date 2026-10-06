## MetalKit

> `/System/Library/Frameworks/MetalKit.framework/MetalKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11288` | `0x11244` | **`-0x44`** |

### Other Changes

```text
Functions:
~ -[MTKView __initCommon] : 1176 -> 1172
~ -[MTKView configureColorAttachments:] : 404 -> 392
~ ___76-[MTKTextureLoader newTexturesWithContentsOfURLs:options:completionHandler:]_block_invoke : 1192 -> 1188
~ -[MTKTextureLoaderPVR3 parseMetadataWithError:] : 344 -> 348
~ -[MTKTextureLoader _newAsyncTextureWithNames:scaleFactor:displayGamut:bundle:options:completionHandler:] : 1092 -> 1084
~ ___104-[MTKTextureLoader _newAsyncTextureWithNames:scaleFactor:displayGamut:bundle:options:completionHandler:]_block_invoke_2 : 264 -> 260
~ -[MTKTextureLoader _newSyncTexturesFromTXRTextures:labels:options:error:] : 2372 -> 2368
~ -[MTKTextureLoaderKTX determineFormatFromSizedFormat:] : 124 -> 120
~ -[MTKMesh initWithMesh:device:error:] : 908 -> 900
~ +[MTKMesh _createMeshesFromObject:newMeshes:sourceMeshes:device:error:] : 476 -> 472
~ +[MTKMesh newMeshesFromAsset:device:sourceMeshes:error:] : 448 -> 444
~ ___61+[MTKTextureLoaderASTCHelper isASTCHDRData:is3DBlocks:error:]_block_invoke : 1372 -> 1368
~ -[MTKView multisampleColorTexturesForceUpdate:] : 864 -> 848
~ -[MTKView colorTexturesForceUpdate:] : 1024 -> 1044
~ -[MTKView initWithCoder:] : 964 -> 960
~ -[MTKView encodeWithCoder:] : 700 -> 704
~ -[MTKView .cxx_destruct] : 400 -> 384
```
