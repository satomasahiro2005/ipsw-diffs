## CloudPhotoLibrary

> `/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/CloudPhotoLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x17d00` | `0x17d60` | **`+0x60`** |
| `__TEXT.__text` | `0x1cbea4` | `0x1cbee8` | **`+0x44`** |
| `__TEXT.__cstring` | `0x18188` | `0x181b9` | **`+0x31`** |
| `__DATA.__bss` | `0xc90` | `0xc98` | **`+0x8`** |

### Other Changes

```diff

-912.0.234.0.0
+912.0.235.0.0

-  CStrings:  5150
+  CStrings:  5153
Functions:
~ sub_1d0f45100 -> sub_1d1525100 : 112 -> 116
~ sub_1d0f45170 -> sub_1d1525174 : 116 -> 120
~ sub_1d0f451e4 -> sub_1d15251ec : 124 -> 128
~ sub_1d0f45260 -> sub_1d152526c : 124 -> 128
~ -[CPLEngineScopeStorage _updateGlobalStatusWithScopeChange:forScope:] : 872 -> 856
~ +[CPLResource descriptionForResourceType:] : 908 -> 932
~ +[CPLResource shortDescriptionForResourceType:] : 908 -> 932
~ -[CPLResource bestFileNameForResource] : 588 -> 600
~ -[CPLResource estimatedResourceSize] : 180 -> 188
~ _OUTLINED_FUNCTION_18 : 24 -> 32
~ _OUTLINED_FUNCTION_20 : 32 -> 24
CStrings:
+ "CPLResourceTypeProvenance"
+ "CloudPhotoLibrary-912.0.235"
+ "Provenance"
+ "Provenance_"
- "CloudPhotoLibrary-912.0.234"
```
