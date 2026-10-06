## AssetExplorer

> `/System/Library/PrivateFrameworks/AssetExplorer.framework/AssetExplorer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2111c` | `0x21264` | **`+0x148`** |
| `__TEXT.__oslogstring` | `0x1e63` | `0x1f80` | **`+0x11d`** |
| `__AUTH_CONST.__auth_got` | `0x628` | `0x630` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2078` | `0x2080` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x958` | `0x950` | **`-0x8`** |

### Other Changes

```diff

-912.0.235.0.0
+916.40.110.0.0

-  Symbols:   1844
-  CStrings:  251
+  Symbols:   1845
+  CStrings:  255
Symbols:
+ _PXPhotosFileProviderRegisterConfigurationSetShouldIncludeRating
Functions:
~ -[AEPackageTransport expectedPackageIdentifiers] : 96 -> 92
~ -[AEAssetPackage(CKBrowserItemPayload) browserItemPayload] : 2052 -> 2184
~ -[AEPhotosAssetPackageGenerator _generatePackageFromAsset:] : 816 -> 896
~ -[AEPhotosAssetPackageGenerator _generatePackageFromAssetUsingDVPSharing:] : 1364 -> 1484
CStrings:
+ "Failed to generate sandbox token for fileProviderURL: %@"
+ "Failed to generate sandbox token for thumbnailFilePathURL: %@"
+ "[AEPhotosAssetPackageGenerator] Failed to create file provider register for DVP sharing"
+ "[AEPhotosAssetPackageGenerator] No file representations found for DVP sharing"
```
