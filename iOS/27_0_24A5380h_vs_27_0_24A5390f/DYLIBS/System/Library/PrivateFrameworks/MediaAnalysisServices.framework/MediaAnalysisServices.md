## MediaAnalysisServices

> `/System/Library/PrivateFrameworks/MediaAnalysisServices.framework/MediaAnalysisServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d698` | `0x3d790` | **`+0xf8`** |
| `__TEXT.__gcc_except_tab` | `0x43fc` | `0x4458` | **`+0x5c`** |
| `__TEXT.__cstring` | `0x3ab9` | `0x3aed` | **`+0x34`** |
| `__AUTH_CONST.__cfstring` | `0x4cc0` | `0x4ce0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xa70` | `0xa78` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1c60` | `0x1c58` | **`-0x8`** |

### Other Changes

```diff

-435.69.2.0.0
+435.73.2.0.0

-  CStrings:  862
+  CStrings:  863
Functions:
~ -[MADService(Photos) requestApplicationDataFolderIdentifierVisionServiceWithPhotosLibraryURL:error:] : 572 -> 820
CStrings:
+ "Vision cache storage directory access not available"
```
