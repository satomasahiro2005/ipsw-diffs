## BiomeLibrary

> `/System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75abe0` | `0x75ad18` | **`+0x138`** |
| `__AUTH_CONST.__cfstring` | `0x4b940` | `0x4b9a0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1ee88` | `0x1eeb8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x4ed27` | `0x4ed40` | **`+0x19`** |
| `__TEXT.__const` | `0x48b8` | `0x48b4` | **`-0x4`** |

### Other Changes

```diff

-441.25.0.0.0
+441.26.3.0.0

-  CStrings:  9809
+  CStrings:  9812
Functions:
~ +[_BMHomeKitClientLibraryNode storeConfigurationForAccessoryControl] : 136 -> 188
~ +[_BMAppIntentsLibraryNode storeConfigurationForTranscript] : 136 -> 188
~ +[_BMSiriLibraryNode storeConfigurationForRecognizedUser] : 136 -> 188
~ +[_BMHomeKitClientLibraryNode storeConfigurationForActionSet] : 136 -> 188
~ +[_BMHomeKitClientLibraryNode storeConfigurationForMediaAccessoryControl] : 136 -> 188
~ +[_BMActivityLibraryNode storeConfigurationForLevel] : 140 -> 192
CStrings:
+ "CSEAI"
+ "PCCErrors"
+ "SWErrors"
```
