## Categories

> `/System/Library/PrivateFrameworks/Categories.framework/Categories`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb364` | `0xb7bc` | **`+0x458`** |
| `__AUTH_CONST.__cfstring` | `0x3900` | `0x3bc0` | **`+0x2c0`** |
| `__TEXT.__cstring` | `0x3028` | `0x32d8` | **`+0x2b0`** |
| `__DATA_CONST.__objc_arraydata` | `0xb88` | `0xc18` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x84c` | `0x89c` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x738` | `0x770` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0xca0` | `0xcc8` | **`+0x28`** |
| `__AUTH_CONST.__objc_intobj` | `0xa8` | `0xc0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x3b0` | `0x3c0` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x6db` | `0x6e7` | **`+0xc`** |

### Other Changes

```diff

-58.1.5.0.0
+58.1.7.1.0

-  Functions: 222
-  Symbols:   526
-  CStrings:  523
+  Functions: 228
+  Symbols:   532
+  CStrings:  545
Symbols:
+ +[CTCategory _bundleCategoriesLookupResultsForBundleIdentifiers:platform:origin:withCompletionHandler:]
+ +[CTCategory _lookupAppStoreUsing:platform:origin:withCompletionHandler:]
+ +[CTCategory _shouldExcludeBundleIdentifierFromCategoryLookup:]
+ +[CTCategory categoryForBundleIdentifiers:platform:targetUserIsU13:origin:withCompletionHandler:]
+ +[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:origin:withCompletionHandler:]
+ GCC_except_table100
+ GCC_except_table44
+ GCC_except_table58
+ GCC_except_table59
+ GCC_except_table74
+ ___103+[CTCategory _bundleCategoriesLookupResultsForBundleIdentifiers:platform:origin:withCompletionHandler:]_block_invoke
+ ___105+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:origin:withCompletionHandler:]_block_invoke
+ ___105+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:origin:withCompletionHandler:]_block_invoke_2
+ ___105+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:origin:withCompletionHandler:]_block_invoke_3
+ ___73+[CTCategory _lookupAppStoreUsing:platform:origin:withCompletionHandler:]_block_invoke
+ ___73+[CTCategory _lookupAppStoreUsing:platform:origin:withCompletionHandler:]_block_invoke_2
+ ___block_descriptor_64_e8_32s40s48bs_e5_v8?0ls48l8s32l8s40l8
+ ___block_descriptor_96_e8_32s40s48bs56r64r72r_e34_v24?0"NSDictionary"8"NSError"16ls32l8r56l8r64l8r72l8s40l8s48l8
- GCC_except_table48
- GCC_except_table54
- GCC_except_table69
- GCC_except_table94
- ___66+[CTCategory _lookupAppStoreUsing:platform:withCompletionHandler:]_block_invoke
- ___66+[CTCategory _lookupAppStoreUsing:platform:withCompletionHandler:]_block_invoke_2
- ___96+[CTCategory _bundleCategoriesLookupResultsForBundleIdentifiers:platform:withCompletionHandler:]_block_invoke
- ___98+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:withCompletionHandler:]_block_invoke
- ___98+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:withCompletionHandler:]_block_invoke_2
- ___98+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:withCompletionHandler:]_block_invoke_3
- ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls48l8s32l8s40l8
- ___block_descriptor_88_e8_32s40s48bs56r64r72r_e34_v24?0"NSDictionary"8"NSError"16ls32l8r56l8r64l8r72l8s40l8s48l8
CStrings:
+ "SB"
+ "_lookupAppStoreUsing %@ origin: %ld"
+ "com.apple.control-center"
+ "com.apple.sharing."
+ "com.apple.springboard."
+ "homeaccessory"
+ "homeaccessory://com.apple.CalendarPebble"
+ "homeaccessory://com.apple.Home"
+ "homeaccessory://com.apple.MobileAddressBook"
+ "homeaccessory://com.apple.MobileSMS"
+ "homeaccessory://com.apple.Music"
+ "homeaccessory://com.apple.PebbleSettingsApp"
+ "homeaccessory://com.apple.facetime"
+ "homeaccessory://com.apple.findmy"
+ "homeaccessory://com.apple.iBooks"
+ "homeaccessory://com.apple.mobilesafari"
+ "homeaccessory://com.apple.mobiletimer"
+ "homeaccessory://com.apple.news"
+ "homeaccessory://com.apple.podcasts"
+ "homeaccessory://com.apple.reminders"
+ "homeaccessory://com.apple.stocks"
+ "homeaccessory://com.apple.tv"
+ "homeaccessory://com.apple.weather"
- "_lookupAppStoreUsing %@"
```
