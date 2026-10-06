## QueryParser

> `/System/Library/PrivateFrameworks/QueryParser.framework/QueryParser`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x117670` | `0x117260` | **`-0x410`** |
| `__AUTH_CONST.__objc_const` | `0x46f8` | `0x4650` | **`-0xa8`** |
| `__TEXT.__objc_methlist` | `0x2a94` | `0x29ec` | **`-0xa8`** |
| `__TEXT.__gcc_except_tab` | `0x13798` | `0x13708` | **`-0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x21a8` | `0x2130` | **`-0x78`** |
| `__TEXT.__oslogstring` | `0x7ace` | `0x7a5e` | **`-0x70`** |
| `__AUTH_CONST.__cfstring` | `0x12800` | `0x127a0` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0x5300` | `0x52d0` | **`-0x30`** |
| `__TEXT.__const` | `0x2d28` | `0x2d48` | **`+0x20`** |
| `__TEXT.__cstring` | `0xd345` | `0xd355` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x15d8` | `0x15e0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x310` | `0x30c` | **`-0x4`** |

### Other Changes

```diff

-3600.31.21.11.1
+3605.7.1.0.0

-  Functions: 4311
-  Symbols:   5971
-  CStrings:  3403
+  Functions: 4301
+  Symbols:   5962
+  CStrings:  3399
Symbols:
+ GCC_except_table140
+ GCC_except_table195
+ GCC_except_table247
+ _CFStringCompareWithOptions
+ __OBJC_$_CLASS_METHODS_QPAssetManager
+ __ZL18assetManagerLoggerv
+ __ZN2QP13isHomeDaypartENS_22QPDateComponentsPeriodE
+ __ZN2QP25getHomeDaypartOffsetHoursENS_22QPDateComponentsPeriodE
+ __ZN2QPL14endsWithWordCIEPK10__CFStringlS2_
+ __ZNK2QP19ParserConfiguration17languageIsEnglishEv
+ __ZNK2QP19ParserConfiguration29embeddingStringMaskForArgTypeE15QUIntentArgType
+ __ZNK2QP19ParserConfiguration30embeddingStringExcludesArgTypeE15QUIntentArgType
+ ___block_descriptor_64_ea8_32s40s48s56r_e5_v8?0ls32l8s40l8s48l8r56l8
- +[QPAssetManager _contentTypesForAssetSet:]
- +[QPAssetManager _isKnownContentType:forAssetSet:]
- +[QPAssetManager(Testing) _test_assetNameEmbedding]
- +[QPAssetManager(Testing) _test_assetNameGeo]
- +[QPAssetManager(Testing) _test_assetNameQueryParser]
- +[QPAssetManager(Testing) _test_assetNameQueryUnderstanding]
- +[QPAssetManager(Testing) _test_assetNameSFC]
- +[QPAssetManager(Testing) _test_assetNameSafety]
- +[QPAssetManager(Testing) _test_assetSetQueryParserOverrides]
- +[QPAssetManager(Testing) _test_assetSetQueryParser]
- -[QPAssetManager _bulkPopulateForAssetSet:locale:]
- -[QPAssetManager _cacheKeyForAssetSet:locale:contentType:]
- -[QPAssetManager(Testing) _test_bulkPopulateForAssetSet:locale:]
- -[QPAssetManager(Testing) _test_bulkPopulateShortCircuitCount]
- GCC_except_table193
- GCC_except_table244
- _OBJC_IVAR_$_QPAssetManager._locked_bulkPopulateShortCircuitCount
- __OBJC_$_CLASS_METHODS_QPAssetManager(Testing)
- ___50-[QPAssetManager _bulkPopulateForAssetSet:locale:]_block_invoke
- ___60-[QPAssetManager _filePathsDictionaryForContentType:locale:]_block_invoke_2
- ___62-[QPAssetManager(Testing) _test_bulkPopulateShortCircuitCount]_block_invoke
- ___block_descriptor_64_ea8_32s40s48r56r_e5_v8?0ls32l8s40l8r48l8r56l8
CStrings:
+ "(InRange(_%@%@%@, %d, 23) || InRange(_%@%@%@, 0, %d))"
+ "[QPNLU][qid=%ld][DateGround][LegacyParser] Skipping non-date lexeme type=%s flag=%u"
+ "[UAF] Unknown content type: %s"
+ "a person"
- "[UAF] Unknown enumeratorTag %s for content type %s — skipping"
- "[UAF] _bulkPopulateForAssetSet: no content descriptors registered for %s — BUG"
- "[UAF] retrieveAssetSet: returned nil for %s locale %s — skipping bulk populate"
- "assetName"
- "contentType"
- "enumeratorTag"
- "flat"
- "perLocale"
```
