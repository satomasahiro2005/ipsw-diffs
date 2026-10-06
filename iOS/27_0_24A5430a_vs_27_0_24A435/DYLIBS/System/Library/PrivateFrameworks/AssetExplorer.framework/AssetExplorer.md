## AssetExplorer

> `/System/Library/PrivateFrameworks/AssetExplorer.framework/AssetExplorer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x210d0` | `0x2111c` | **`+0x4c`** |
| `__AUTH_CONST.__auth_got` | `0x620` | `0x628` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2070` | `0x2078` | **`+0x8`** |

### Other Changes

```diff

-912.0.234.0.0
+912.0.235.0.0

-  Symbols:   1843
+  Symbols:   1844
Symbols:
+ _PXPhotosFileProviderRegisterConfigurationSetShouldIncludeProvenance
Functions:
~ -[AEPhotosAssetPackageGenerator _generatePackageFromAsset:] : 776 -> 816
~ -[AEPhotosAssetPackageGenerator _generatePackageFromAssetUsingDVPSharing:] : 1328 -> 1364
```
