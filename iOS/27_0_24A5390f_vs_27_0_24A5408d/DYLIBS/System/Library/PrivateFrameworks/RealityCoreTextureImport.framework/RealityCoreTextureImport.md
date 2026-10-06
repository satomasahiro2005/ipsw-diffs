## RealityCoreTextureImport

> `/System/Library/PrivateFrameworks/RealityCoreTextureImport.framework/RealityCoreTextureImport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3502` | `0x352f` | **`+0x2d`** |
| `__TEXT.__text` | `0x4b744` | `0x4b770` | **`+0x2c`** |

### Other Changes

```diff

-24.0.4.0.0
+24.0.5.0.1

-  CStrings:  527
+  CStrings:  528
Functions:
~ __ZNK2re16DataImportSource18tryReadHeaderBytesEPvm : 100 -> 104
~ __ZN2re16DataImportSource20tryCreateImageSourceEPK14__CFDictionaryb : 236 -> 284
~ __Z27loadTextureDataWithProviderRN2re15ImportOperationEb : 2768 -> 2760
CStrings:
+ "Failed to create CGImageSource for nil data."
```
