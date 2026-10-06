## SiriUICore

> `/System/Library/PrivateFrameworks/SiriUICore.framework/SiriUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x7f172` | `0x68972` | **`-0x16800`** |
| `__TEXT.__text` | `0x2b95c` | `0x2b9e4` | **`+0x88`** |
| `__TEXT.__cstring` | `0x87ea` | `0x885b` | **`+0x71`** |
| `__TEXT.__oslogstring` | `0xd3d` | `0xd80` | **`+0x43`** |

### Other Changes

```diff

-3600.9.2.0.0
+3605.4.1.0.0

-  Functions: 1151
+  Functions: 1152

-  CStrings:  374
+  CStrings:  377
Symbols:
+ _precalcSUICILNoise3DTextureASTC5x5
- _precalcSUICILNoise3DTexture
Functions:
~ +[SUICIntelligentLightLayer createNoiseTextureWithDevice:commandQueue:] : 428 -> 496
+ -[SUICIntelligentLightLayer _drawFrame:].cold.1
CStrings:
+ "!\"ASTC5x5 3D texture failed to allocate\""
+ "%s Failed to create compressed noise texture. Requires Apple3 GPU."
+ "+[SUICIntelligentLightLayer createNoiseTextureWithDevice:commandQueue:]"
```
