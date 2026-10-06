## HomeAI

> `/System/Library/PrivateFrameworks/HomeAI.framework/HomeAI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17f8ac` | `0x17f7a4` | **`-0x108`** |
| `__TEXT.__cstring` | `0xdb8d` | `0xdb67` | **`-0x26`** |
| `__TEXT.__const` | `0x497d` | `0x496d` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0xe98` | `0xe90` | **`-0x8`** |

### Other Changes

```diff

-  Symbols:   10272
-  CStrings:  3233
+  Symbols:   10271
+  CStrings:  3231
Symbols:
- __os_feature_enabled_impl
Functions:
~ +[HMISignificantActivityFcosDetector defaultAssetPath] : 176 -> 120
~ -[HMIMLModel _ensureModelWithError:] : 704 -> 656
~ ___58+[HMIVideoAnalyzerEvent defaultConfidenceThresholdsMedium]_block_invoke : 388 -> 316
~ ___56+[HMIVideoAnalyzerEvent defaultConfidenceThresholdsHigh]_block_invoke : 452 -> 364
CStrings:
- "CameraSignificantActivityModelV2"
- "Home"
```
