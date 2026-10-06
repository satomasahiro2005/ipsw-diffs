## QueryParser

> `/System/Library/PrivateFrameworks/QueryParser.framework/QueryParser`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x116d10` | `0x11766c` | **`+0x95c`** |
| `__TEXT.__gcc_except_tab` | `0x1369c` | `0x13798` | **`+0xfc`** |
| `__TEXT.__oslogstring` | `0x7a0e` | `0x7ace` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x4650` | `0x46f8` | **`+0xa8`** |
| `__TEXT.__objc_methlist` | `0x29ec` | `0x2a94` | **`+0xa8`** |
| `__AUTH_CONST.__cfstring` | `0x12760` | `0x12800` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x2130` | `0x21a8` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x52c0` | `0x5300` | **`+0x40`** |
| `__TEXT.__cstring` | `0xd315` | `0xd345` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x30c` | `0x310` | **`+0x4`** |

### Other Changes

```diff

-3600.31.21.0.0
+3600.31.21.11.1

-  Functions: 4295
-  Symbols:   5954
-  CStrings:  3396
+  Functions: 4311
+  Symbols:   5971
+  CStrings:  3403
Symbols:
+ +[QPAssetManager _contentTypesForAssetSet:]
+ +[QPAssetManager _isKnownContentType:forAssetSet:]
+ +[QPAssetManager(Testing) _test_assetNameEmbedding]
+ +[QPAssetManager(Testing) _test_assetNameGeo]
+ +[QPAssetManager(Testing) _test_assetNameQueryParser]
+ +[QPAssetManager(Testing) _test_assetNameQueryUnderstanding]
+ +[QPAssetManager(Testing) _test_assetNameSFC]
+ +[QPAssetManager(Testing) _test_assetNameSafety]
+ +[QPAssetManager(Testing) _test_assetSetQueryParserOverrides]
+ +[QPAssetManager(Testing) _test_assetSetQueryParser]
+ -[QPAssetManager _bulkPopulateForAssetSet:locale:]
+ -[QPAssetManager _cacheKeyForAssetSet:locale:contentType:]
+ -[QPAssetManager(Testing) _test_bulkPopulateForAssetSet:locale:]
+ -[QPAssetManager(Testing) _test_bulkPopulateShortCircuitCount]
+ _OBJC_IVAR_$_QPAssetManager._locked_bulkPopulateShortCircuitCount
+ __OBJC_$_CLASS_METHODS_QPAssetManager(Testing)
+ ___50-[QPAssetManager _bulkPopulateForAssetSet:locale:]_block_invoke
+ ___60-[QPAssetManager _filePathsDictionaryForContentType:locale:]_block_invoke_2
+ ___62-[QPAssetManager(Testing) _test_bulkPopulateShortCircuitCount]_block_invoke
+ ___block_descriptor_64_ea8_32s40s48r56r_e5_v8?0ls32l8s40l8r48l8r56l8
- __OBJC_$_CLASS_METHODS_QPAssetManager
- __ZL18assetManagerLoggerv
- ___block_descriptor_64_ea8_32s40s48s56r_e5_v8?0ls32l8s40l8s48l8r56l8
CStrings:
+ "[UAF] Unknown enumeratorTag %s for content type %s — skipping"
+ "[UAF] _bulkPopulateForAssetSet: no content descriptors registered for %s — BUG"
+ "[UAF] retrieveAssetSet: returned nil for %s locale %s — skipping bulk populate"
+ "assetName"
+ "contentType"
+ "enumeratorTag"
+ "flat"
+ "perLocale"
- "[UAF] Unknown content type: %s"
```
