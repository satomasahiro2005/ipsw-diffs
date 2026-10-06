## libGFXShared.dylib

> `/System/Library/Frameworks/OpenGLES.framework/libGFXShared.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6518` | `0x6598` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x178` | `0x180` | **`+0x8`** |

### Other Changes

```text
Functions:
~ _gfxInitializeBufferObject : 152 -> 164
~ _gfxWaitPluginBuffer : 112 -> 108
~ _gfxWaitBufferOnDevices : 132 -> 128
~ _gfxCreatePluginBuffer : 124 -> 120
~ _gfxDestroyPluginBuffer : 120 -> 108
~ _gfxInitializeLibrary : 2164 -> 2156
~ _gfxCreateSharedState : 472 -> 448
~ _gfxGetGLDShareGroupForDeviceID : 56 -> 64
~ _gfxCompareSharedState : 96 -> 100
~ _gfxRetainSharedStateAndHash : 192 -> 200
~ _gfxSharedHasFloatRenderer : 60 -> 76
~ _gfxInitializeGLTexture : 928 -> 952
~ _gfxCreatePluginTexture : 172 -> 164
~ _gfxDestroyPluginTexture : 136 -> 144
~ _gfxGetGLDTextureForDeviceID : 56 -> 68
~ _gfxWaitPluginTexture : 112 -> 108
~ _gfxWaitTextureOnDevices : 132 -> 128
~ _gfxSynchronizeTexLevelStorage : 320 -> 304
~ _gfxModifyPluginTextureLevel : 144 -> 152
~ _gfxEvaluateTextureForParameterChange : 1148 -> 1164
~ _gfxEvaluateTextureCore : 740 -> 764
~ _gfxEvaluateTextureForGeometryChange : 2052 -> 2088
~ _gfxUpdateTextureForGeometryChange : 636 -> 676
~ _gfxAnnotateTexture : 340 -> 336
~ _gfxAnnotateBuffer : 304 -> 300
~ _AnnotateObjectsInHash : 4444 -> 4448
~ _gfxWaitSyncObject : 112 -> 136
~ _gfxClearSyncObjectsInHash : 228 -> 212
~ _gfxCreateGLSyncFromCLEvent : 540 -> 536
```
