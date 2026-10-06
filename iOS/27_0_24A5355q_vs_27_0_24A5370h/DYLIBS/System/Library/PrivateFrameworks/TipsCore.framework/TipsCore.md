## TipsCore

> `/System/Library/PrivateFrameworks/TipsCore.framework/TipsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb0204` | `0xb1264` | **`+0x1060`** |
| `__TEXT.__oslogstring` | `0x1327` | `0x141e` | **`+0xf7`** |
| `__DATA_CONST.__const` | `0x2260` | `0x22b0` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x8af8` | `0x8b40` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x1908` | `0x1948` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x33b8` | `0x33f0` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0xf90` | `0xfbc` | **`+0x2c`** |
| `__AUTH_CONST.__cfstring` | `0x5400` | `0x5420` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3cf8` | `0x3d18` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4f93` | `0x4fb3` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1202` | `0x1222` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x39f8` | `0x3a10` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0xe7d0` | `0xe7e0` | **`+0x10`** |
| `__DATA.__data` | `0x1360` | `0x1370` | **`+0x10`** |
| `__TEXT.__const` | `0x2a54` | `0x2a64` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x10d0` | `0x10dc` | **`+0xc`** |
| `__AUTH.__data` | `0x988` | `0x990` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x23c0` | `0x23c8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x18dc` | `0x18e4` | **`+0x8`** |

### Other Changes

```diff

-850.0.0.0.0
+853.0.0.0.0

-  Functions: 5362
-  Symbols:   5774
-  CStrings:  1114
+  Functions: 5381
+  Symbols:   5783
+  CStrings:  1121
Symbols:
+ +[TPSDataCacheController cacheRootDirectory]
+ +[TPSDataCacheController proxyCacheDirectory]
+ +[TPSWidgetController cacheIdentifierForDocument:userInterfaceStyle:]
+ -[TPSSearchQueryClient reindexAllSearchableItemsForScope:completionHandler:]
+ -[TPSSearchQueryClient reindexSearchableItemsWithIdentifiers:scope:completionHandler:]
+ GCC_except_table38
+ GCC_except_table44
+ GCC_except_table51
+ __OBJC_$_CLASS_METHODS_TPSWidgetController
+ ___76-[TPSSearchQueryClient reindexAllSearchableItemsForScope:completionHandler:]_block_invoke
+ ___76-[TPSSearchQueryClient reindexAllSearchableItemsForScope:completionHandler:]_block_invoke_2
+ ___86-[TPSSearchQueryClient reindexSearchableItemsWithIdentifiers:scope:completionHandler:]_block_invoke
+ ___86-[TPSSearchQueryClient reindexSearchableItemsWithIdentifiers:scope:completionHandler:]_block_invoke_2
+ ___block_descriptor_48_e8_32bs_e33_v16?0"<TPSXPCServerInterface>"8ls32l8
+ ___block_descriptor_56_e8_32s40bs_e33_v16?0"<TPSXPCServerInterface>"8ls32l8s40l8
+ _symbolic SS______t 8TipsCore12SearchResultC4ItemC
+ _symbolic _____ySS_____G s18_DictionaryStorageC 8TipsCore12SearchResultC4ItemC
+ _symbolic _____ySS______tG s23_ContiguousArrayStorageC 8TipsCore12SearchResultC4ItemC
- -[TPSSearchQueryClient reindexAllSearchableItemsWithCompletionHandler:]
- -[TPSSearchQueryClient reindexSearchableItemsWithIdentifiers:completionHandler:]
- GCC_except_table36
- GCC_except_table42
- GCC_except_table47
- ___71-[TPSSearchQueryClient reindexAllSearchableItemsWithCompletionHandler:]_block_invoke
- ___71-[TPSSearchQueryClient reindexAllSearchableItemsWithCompletionHandler:]_block_invoke_2
- ___80-[TPSSearchQueryClient reindexSearchableItemsWithIdentifiers:completionHandler:]_block_invoke
- ___80-[TPSSearchQueryClient reindexSearchableItemsWithIdentifiers:completionHandler:]_block_invoke_2
CStrings:
+ "(nil)"
+ "Cache data path to remove is nil."
+ "Path '%@' is not inside cache root '%@'. Skipping (rdar://164839865)"
+ "TPSDisplayAllYourApps"
+ "Unable to create proxy cache directory %@. Error: %@"
+ "Unable to resolve cache directory for %@"
+ "Unable to resolve cache directory for cache reset"
```
