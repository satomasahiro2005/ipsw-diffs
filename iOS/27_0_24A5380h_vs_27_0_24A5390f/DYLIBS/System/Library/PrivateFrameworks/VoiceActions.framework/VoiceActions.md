## VoiceActions

> `/System/Library/PrivateFrameworks/VoiceActions.framework/VoiceActions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18a814` | `0x1900e0` | **`+0x58cc`** |
| `__AUTH_CONST.__const` | `0x13920` | `0x13d58` | **`+0x438`** |
| `__TEXT.__const` | `0xca40` | `0xcd40` | **`+0x300`** |
| `__TEXT.__eh_frame` | `0xd1ec` | `0xd4d4` | **`+0x2e8`** |
| `__TEXT.__cstring` | `0x690d` | `0x6bcd` | **`+0x2c0`** |
| `__DATA.__bss` | `0x108d0` | `0x10b70` | **`+0x2a0`** |
| `__TEXT.__constg_swiftt` | `0x94dc` | `0x9684` | **`+0x1a8`** |
| `__AUTH.__data` | `0xbc70` | `0xbde8` | **`+0x178`** |
| `__AUTH_CONST.__objc_const` | `0xd698` | `0xd810` | **`+0x178`** |
| `__TEXT.__swift5_fieldmd` | `0x59dc` | `0x5ad4` | **`+0xf8`** |
| `__TEXT.__unwind_info` | `0x6230` | `0x6318` | **`+0xe8`** |
| `__TEXT.__swift5_reflstr` | `0x5d4d` | `0x5e2d` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x429e` | `0x433e` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x2a94` | `0x2b34` | **`+0xa0`** |
| `__TEXT.__swift5_proto` | `0x864` | `0x880` | **`+0x1c`** |
| `__DATA.__data` | `0x1e10` | `0x1e28` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x450` | `0x468` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xf0` | `0x104` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0xcb0` | `0xcc0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x510` | `0x520` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x590` | `0x598` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x2c` | `0x34` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x3c` | `0x40` | **`+0x4`** |

### Other Changes

```diff

-97.0.0.0.0
+99.0.0.0.0

-  Functions: 7527
+  Functions: 7609

-  CStrings:  1169
+  CStrings:  1188
CStrings:
+ " missing <InputFrameCount>"
+ " missing <StateShapes>"
+ " not found or wrong type"
+ " state shapes, got "
+ "/.AssetData/VAD.mlmodelc"
+ "/model.mil.config"
+ "/model.specialization.bundle/"
+ "/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_Siri_Understanding"
+ "/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_Speech_AutomaticSpeechRecognition"
+ "Failed to load vad model"
+ "Invalid S-VAD input shape "
+ "Invalid S-VAD output shape "
+ "Loading model %s function=%s"
+ "S-VAD OS asset missing model.mil.config at "
+ "S-VAD config at "
+ "S-VAD input input not found or wrong type"
+ "S-VAD output output not found or wrong type"
+ "S-VAD: OS asset at %s failed to load (%@); falling back to bundled snapshot"
+ "S-VAD: invalid state shape: "
+ "S-VAD: no OS asset found; using bundled snapshot"
+ "VAD engine is nil"
+ "VASpeechDetector loaded "
- "Failed to load vad model from "
- "Loading model %s"
- "VAD model is nil"
```
