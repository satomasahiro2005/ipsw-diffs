## Cinematic

> `/System/Library/Frameworks/Cinematic.framework/Cinematic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14238` | `0x142f4` | **`+0xbc`** |
| `__TEXT.__oslogstring` | `0x927` | `0x98f` | **`+0x68`** |
| `__TEXT.__gcc_except_tab` | `0x290` | `0x2c0` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x4d8` | `0x4e0` | **`+0x8`** |

### Other Changes

```diff

-558.0.0.0.0
+560.22.1.0.0

-  Functions: 753
-  Symbols:   977
-  CStrings:  83
+  Functions: 755
+  Symbols:   978
+  CStrings:  84
Symbols:
+ _objc_retain_x28
Functions:
~ ____CNLoadMetadataTrackForVideoTrack_block_invoke : 1136 -> 1276
~ _OUTLINED_FUNCTION_1 : 16 -> 20
+ _OUTLINED_FUNCTION_2
~ ___65+[CNAssetInfo _loadFromAsset:requireDisparity:completionHandler:]_block_invoke.20.cold.1 : 60 -> 52
~ +[CNAssetInfo loadFromCinematicVideoTracks:requireDisparity:error:].cold.2 : 60 -> 52
~ +[CNAssetInfo loadFromCinematicVideoTracks:requireDisparity:error:].cold.3 : 64 -> 56
~ ____CNLoadMetadataTrackForVideoTrack_block_invoke.cold.1 : 68 -> 52
+ ____CNLoadMetadataTrackForVideoTrack_block_invoke.cold.2
CStrings:
+ "Warning: Cannot find associated metadata track. Using last found instance with correct tract identifier"
```
