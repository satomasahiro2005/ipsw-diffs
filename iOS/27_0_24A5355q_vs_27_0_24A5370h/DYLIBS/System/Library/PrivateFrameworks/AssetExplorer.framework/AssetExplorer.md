## AssetExplorer

> `/System/Library/PrivateFrameworks/AssetExplorer.framework/AssetExplorer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20c30` | `0x210d0` | **`+0x4a0`** |
| `__TEXT.__cstring` | `0x1135` | `0x11b2` | **`+0x7d`** |
| `__AUTH_CONST.__cfstring` | `0xe80` | `0xee0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x1e1e` | `0x1e63` | **`+0x45`** |
| `__DATA_CONST.__objc_selrefs` | `0x2028` | `0x2060` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x600` | `0x620` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2a7c` | `0x2a94` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x8a8` | `0x8b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x590` | `0x598` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x950` | `0x958` | **`+0x8`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Functions: 772
-  Symbols:   1835
-  CStrings:  247
+  Functions: 774
+  Symbols:   1843
+  CStrings:  251
Symbols:
+ -[AEAssetPackage(DisplayMetadata) isScreenshot]
+ -[AEExplorerViewController _currentInterfaceOrientation]
+ GCC_except_table185
+ GCC_except_table267
+ GCC_except_table493
+ GCC_except_table500
+ GCC_except_table508
+ GCC_except_table553
+ GCC_except_table559
+ GCC_except_table571
+ GCC_except_table620
+ GCC_except_table629
+ GCC_except_table632
+ GCC_except_table665
+ _OBJC_CLASS_$_UIWindowScene
+ _PXCanAccessDocumentStorageURL
+ _PXPhotosFileProviderRegisterConfigurationSetShouldIncludeCaption
+ _PXPhotosFileProviderRegisterConfigurationSetShouldIncludeKeywords
+ _PXPhotosFileProviderRegisterConfigurationSetShouldIncludeLocation
+ _kAEAssetPackageDisplayIsScreenshot
- GCC_except_table184
- GCC_except_table266
- GCC_except_table492
- GCC_except_table499
- GCC_except_table507
- GCC_except_table552
- GCC_except_table558
- GCC_except_table570
- GCC_except_table618
- GCC_except_table627
- GCC_except_table630
- GCC_except_table663
CStrings:
+ "AEAssetPackageDisplayIsScreenshot"
+ "AEAssetPackageFileURLSandboxExtensionToken"
+ "AEAssetPackageThumbnailURLSandboxExtensionToken"
+ "[AEPhotosAssetPackageGenerator] No preferred DVP file representation"
```
