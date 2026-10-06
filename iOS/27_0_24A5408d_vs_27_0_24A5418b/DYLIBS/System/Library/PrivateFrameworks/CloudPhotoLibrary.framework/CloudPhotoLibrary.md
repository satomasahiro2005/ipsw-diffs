## CloudPhotoLibrary

> `/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/CloudPhotoLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cbd3c` | `0x1cbea4` | **`+0x168`** |
| `__AUTH_CONST.__cfstring` | `0x17ce0` | `0x17d00` | **`+0x20`** |
| `__TEXT.__cstring` | `0x18172` | `0x18188` | **`+0x16`** |
| `__TEXT.__objc_methlist` | `0x15d44` | `0x15d54` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x9310` | `0x9318` | **`+0x8`** |

### Other Changes

```diff

-912.0.111.0.0
+912.0.232.0.0

-  Functions: 9797
-  Symbols:   15565
-  CStrings:  5149
+  Functions: 9798
+  Symbols:   15566
+  CStrings:  5150
Symbols:
+ +[CPLTransportContainerConfiguration isValidContainerIdentifier:]
+ GCC_except_table8936
- GCC_except_table8935
Functions:
+ +[CPLTransportContainerConfiguration isValidContainerIdentifier:]
CStrings:
+ "CPLAllowAllContainers"
+ "CloudPhotoLibrary-912.0.232"
- "CloudPhotoLibrary-912.0.111"
```
