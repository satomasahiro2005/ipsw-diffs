## SafariCore

> `/System/Library/PrivateFrameworks/SafariCore.framework/SafariCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f6b98` | `0x1f74d0` | **`+0x938`** |
| `__DATA.__data` | `0x3680` | `0x37c0` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0xe721` | `0xe7f1` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x171c7` | `0x17237` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0xa700` | `0xa760` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x9df0` | `0x9e38` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x7930` | `0x7974` | **`+0x44`** |
| `__AUTH_CONST.__cfstring` | `0x1af60` | `0x1afa0` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0xb3b8` | `0xb3d8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x21b8` | `0x21c8` | **`+0x10`** |
| `__DATA.__bss` | `0xa710` | `0xa720` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x5b80` | `0x5b88` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x7710` | `0x7718` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xd34c` | `0xd354` | **`+0x8`** |

### Other Changes

```diff

-625.2.7.1.0
+625.2.8.10.4

-  Functions: 11439
-  Symbols:   12119
-  CStrings:  5290
+  Functions: 11469
+  Symbols:   12127
+  CStrings:  5297
Symbols:
+ -[NSFileManager(SafariNSFileManagerExtras) safari_pebbleSafariContainer]
+ -[WBSAnalyticsLogger didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:pageLoadSource:]
+ GCC_except_table54
+ GCC_except_table74
+ _WBSCloudBookmarkListRecordNamePinnedSuggestions
+ __ZZ72-[NSFileManager(SafariNSFileManagerExtras) safari_pebbleSafariContainer]E12containerURL
+ __ZZ72-[NSFileManager(SafariNSFileManagerExtras) safari_pebbleSafariContainer]E9onceToken
+ ___72-[NSFileManager(SafariNSFileManagerExtras) safari_pebbleSafariContainer]_block_invoke
+ ___94-[WBSAnalyticsLogger didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:pageLoadSource:]_block_invoke
+ _container_get_path
+ _container_query_set_group_identifiers
- -[WBSAnalyticsLogger didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:]
- GCC_except_table67
- ___79-[WBSAnalyticsLogger didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:]_block_invoke
CStrings:
+ "Failed to consume sandbox extension for BrowserKit group container"
+ "Failed to get BrowserKit group container for primary persona: %{public}s"
+ "Failed to get Pebble Safari group container path, groupID = %{public}@"
+ "PebbleDataFetching"
+ "Pinned Suggestions"
+ "WebContentRestrictions"
+ "group.com.apple.safari.pebble"
+ "pageLoadSource"
- "wasUserLoggedIn"
```
