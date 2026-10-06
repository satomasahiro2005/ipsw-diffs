## Categories

> `/System/Library/PrivateFrameworks/Categories.framework/Categories`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb34c` | `0xb798` | **`+0x44c`** |
| `__TEXT.__cstring` | `0x2d54` | `0x2e04` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x36e0` | `0x3780` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x680` | `0x6e8` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x7c4` | `0x82c` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x6c8` | `0x720` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0xc70` | `0xca0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x388` | `0x3b0` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0xaa0` | `0xab8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x4c` | `0x50` | **`+0x4`** |

### Other Changes

```diff

-56.0.0.0.0
+58.0.1.0.0

-  Functions: 211
-  Symbols:   512
-  CStrings:  503
+  Functions: 221
+  Symbols:   526
+  CStrings:  508
Symbols:
+ +[CTCategories _cacheKeyForBundleID:targetUserIsU13:]
+ +[CTCategory _bundleCategoriesLookupResultsForBundleIdentifiers:platform:withCompletionHandler:]
+ +[CTCategory categoryForBundleID:platform:targetUserIsU13:withCompletionHandler:]
+ +[CTCategory categoryForBundleIdentifiers:platform:targetUserIsU13:withCompletionHandler:]
+ +[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:withCompletionHandler:]
+ +[CTCategoryResolver resolvedIdentifierForVersion:appStoreCategories:ckIdentifier:systemOverride:targetUserIsU13:]
+ -[CTAppStoreCategories contentDescriptors]
+ -[CTAppStoreCategories initWithPrimary:secondary:contentDescriptors:]
+ -[CTCategories categoriesForBundleIDs:platform:targetUserIsU13:completionHandler:]
+ -[CTCategories categoryForBundleID:platform:targetUserIsU13:completionHandler:]
+ GCC_except_table24
+ GCC_except_table25
+ GCC_except_table32
+ GCC_except_table36
+ GCC_except_table38
+ GCC_except_table40
+ GCC_except_table42
+ GCC_except_table53
+ GCC_except_table54
+ GCC_except_table66
+ GCC_except_table78
+ GCC_except_table95
+ _OBJC_IVAR_$_CTAppStoreCategories._contentDescriptors
+ ___79-[CTCategories categoryForBundleID:platform:targetUserIsU13:completionHandler:]_block_invoke
+ ___81+[CTCategory categoryForBundleID:platform:targetUserIsU13:withCompletionHandler:]_block_invoke
+ ___82-[CTCategories categoriesForBundleIDs:platform:targetUserIsU13:completionHandler:]_block_invoke
+ ___82-[CTCategories categoriesForBundleIDs:platform:targetUserIsU13:completionHandler:]_block_invoke_2
+ ___82-[CTCategories categoriesForBundleIDs:platform:targetUserIsU13:completionHandler:]_block_invoke_3
+ ___96+[CTCategory _bundleCategoriesLookupResultsForBundleIdentifiers:platform:withCompletionHandler:]_block_invoke
+ ___98+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:withCompletionHandler:]_block_invoke
+ ___98+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:withCompletionHandler:]_block_invoke_2
+ ___98+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:withCompletionHandler:]_block_invoke_3
+ ___block_descriptor_41_e8_32s_e37_v32?0"NSString"8"CTCategory"16^B24ls32l8
+ ___block_descriptor_49_e8_32s40s_e25_v32?0"NSString"8Q16^B24ls32l8s40l8
+ ___block_descriptor_57_e8_32bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8
+ ___block_descriptor_65_e8_32s40r_e57_v32?0"NSString"8"CTBundleCategoriesLookupResult"16^B24ls32l8r40l8
+ ___block_descriptor_65_e8_32s40s48bs56r_e34_v24?0"NSDictionary"8"NSError"16ls32l8r56l8s40l8s48l8
+ ___block_descriptor_73_e8_32s40bs48r_e34_v24?0"NSDictionary"8"NSError"16ls32l8r48l8s40l8
+ _objc_retain_x5
+ _objc_retain_x6
- +[CTCategoryResolver resolvedIdentifierForVersion:appStoreCategories:ckIdentifier:systemOverride:]
- GCC_except_table18
- GCC_except_table22
- GCC_except_table28
- GCC_except_table29
- GCC_except_table30
- GCC_except_table31
- GCC_except_table35
- GCC_except_table43
- GCC_except_table49
- GCC_except_table61
- GCC_except_table73
- GCC_except_table90
- _CTErrorKeyHTTPResponse
- _CTErrorKeyHTTPResponseData
- ___63-[CTCategories categoryForBundleID:platform:completionHandler:]_block_invoke
- ___66-[CTCategories categoriesForBundleIDs:platform:completionHandler:]_block_invoke
- ___66-[CTCategories categoriesForBundleIDs:platform:completionHandler:]_block_invoke_2
- ___66-[CTCategories categoriesForBundleIDs:platform:completionHandler:]_block_invoke_3
- ___82+[CTCategory categoryForBundleIdentifiers:platform:version:withCompletionHandler:]_block_invoke
- ___82+[CTCategory categoryForBundleIdentifiers:platform:version:withCompletionHandler:]_block_invoke_2
- ___82+[CTCategory categoryForBundleIdentifiers:platform:version:withCompletionHandler:]_block_invoke_3
- ___block_descriptor_56_e8_32bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8
- ___block_descriptor_64_e8_32s40r_e57_v32?0"NSString"8"CTBundleCategoriesLookupResult"16^B24ls32l8r40l8
- ___block_descriptor_72_e8_32s40bs48r_e34_v24?0"NSDictionary"8"NSError"16ls32l8r48l8s40l8
- _objc_retain_x4
CStrings:
+ "%@|u13=%d"
+ "com.apple.CompanionSetup"
+ "com.apple.LocalAuthenticationUIService"
+ "contentDescriptors"
+ "ios://com.apple.musicrecognition"
+ "macos://com.apple.musicrecognition.mac"
+ "watchos://com.apple.nanomusicrecognition"
- "HTTPResponse"
- "HTTPResponseData"
```
