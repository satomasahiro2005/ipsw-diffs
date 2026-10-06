## QueryParser

> `/System/Library/PrivateFrameworks/QueryParser.framework/QueryParser`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x117260` | `0x118224` | **`+0xfc4`** |
| `__TEXT.__gcc_except_tab` | `0x13708` | `0x138f4` | **`+0x1ec`** |
| `__TEXT.__oslogstring` | `0x7a5e` | `0x7bee` | **`+0x190`** |
| `__AUTH_CONST.__cfstring` | `0x127a0` | `0x128c0` | **`+0x120`** |
| `__AUTH_CONST.__objc_const` | `0x4650` | `0x46f8` | **`+0xa8`** |
| `__TEXT.__objc_methlist` | `0x29ec` | `0x2a94` | **`+0xa8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2130` | `0x21c0` | **`+0x90`** |
| `__TEXT.__cstring` | `0xd355` | `0xd3c5` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x52d0` | `0x5310` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x730` | `0x738` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x30c` | `0x310` | **`+0x4`** |

### Other Changes

```diff

-3605.7.1.0.0
+3605.7.1.1.1

-  Functions: 4301
-  Symbols:   5962
-  CStrings:  3399
+  Functions: 4317
+  Symbols:   5980
+  CStrings:  3413
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
+ _OBJC_CLASS_$_RBSAcquisitionCompletionAttribute
+ _OBJC_IVAR_$_QPAssetManager._locked_bulkPopulateShortCircuitCount
+ __OBJC_$_CLASS_METHODS_QPAssetManager(Testing)
+ ___50-[QPAssetManager _bulkPopulateForAssetSet:locale:]_block_invoke
+ ___60-[QPAssetManager _filePathsDictionaryForContentType:locale:]_block_invoke_2
+ ___62-[QPAssetManager(Testing) _test_bulkPopulateShortCircuitCount]_block_invoke
+ ___block_descriptor_56_ea8_32s40s48s_e17_v16?0"NSError"8ls32l8s40l8s48l8
+ ___block_descriptor_64_ea8_32s40s48r56r_e5_v8?0ls32l8s40l8r48l8r56l8
- __OBJC_$_CLASS_METHODS_QPAssetManager
- __ZL18assetManagerLoggerv
- ___block_descriptor_48_ea8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
- ___block_descriptor_64_ea8_32s40s48s56r_e5_v8?0ls32l8s40l8s48l8r56l8
CStrings:
+ "UAFAssetAccess"
+ "[UAF] Asset set changed during enumeration for %s locale %s — discarding"
+ "[UAF] Failed to acquire scoped RBS assertion: %s"
+ "[UAF] Timed out waiting for UAF flock release; skipping enumeration (%s locale %s)"
+ "[UAF] UAFAssetAccess unavailable, using FinishTaskUninterruptable: %s"
+ "[UAF] Unknown enumeratorTag %s for content type %s — skipping"
+ "[UAF] _bulkPopulateForAssetSet: no content descriptors registered for %s — BUG"
+ "[UAF] retrieveAssetSet: returned nil for %s locale %s — skipping bulk populate"
+ "assetName"
+ "com.apple.UnifiedAssetFramework"
+ "contentType"
+ "directory"
+ "entryKey"
+ "enumeratorTag"
+ "flat"
+ "perLocale"
- "[UAF] Failed to acquire scoped RBS assertion; skipping OTA retrieval this call: %s"
- "[UAF] Unknown content type: %s"
```
