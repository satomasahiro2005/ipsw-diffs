## BusinessChatService

> `/System/Library/PrivateFrameworks/BusinessChatService.framework/BusinessChatService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ddb8` | `0x6e080` | **`+0x2c8`** |
| `__TEXT.__cstring` | `0x8bd2` | `0x8c39` | **`+0x67`** |
| `__TEXT.__oslogstring` | `0x4fe7` | `0x5025` | **`+0x3e`** |
| `__TEXT.__objc_methlist` | `0x797c` | `0x79a4` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2788` | `0x2798` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0xfdd8` | `0xfde0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1560` | `0x1568` | **`+0x8`** |

### Other Changes

```diff

-30123.31.8.11.3
+30123.31.8.11.4

-  Functions: 2388
-  Symbols:   4904
-  CStrings:  1321
+  Functions: 2392
+  Symbols:   4908
+  CStrings:  1323
Symbols:
+ -[BCSBusinessQueryController fetchBusinessItemWithPhoneNumber:forClientBundleID:cacheOnly:completion:]
+ -[BCSBusinessQueryController fetchItemWithQuery:cacheOnly:completion:]
+ -[BCSBusinessQueryService cachedBusinessItemWithPhoneNumber:completion:]
+ GCC_except_table102
+ GCC_except_table57
+ GCC_except_table62
+ GCC_except_table73
+ GCC_except_table77
+ GCC_except_table84
+ ___102-[BCSBusinessQueryController fetchBusinessItemWithPhoneNumber:forClientBundleID:cacheOnly:completion:]_block_invoke
+ ___70-[BCSBusinessQueryController fetchItemWithQuery:cacheOnly:completion:]_block_invoke
+ ___72-[BCSBusinessQueryService cachedBusinessItemWithPhoneNumber:completion:]_block_invoke
- GCC_except_table100
- GCC_except_table55
- GCC_except_table60
- GCC_except_table71
- GCC_except_table75
- GCC_except_table82
- ___60-[BCSBusinessQueryController fetchItemWithQuery:completion:]_block_invoke
- ___92-[BCSBusinessQueryController fetchBusinessItemWithPhoneNumber:forClientBundleID:completion:]_block_invoke
CStrings:
+ "%s - Cache only lookup. Did not find item in cache - type: %@"
+ "-[BCSBusinessQueryController fetchBusinessItemWithPhoneNumber:forClientBundleID:cacheOnly:completion:]"
+ "-[BCSBusinessQueryController fetchItemWithQuery:cacheOnly:completion:]"
+ "-[BCSBusinessQueryController fetchItemWithQuery:cacheOnly:completion:]_block_invoke"
+ "-[BCSBusinessQueryService cachedBusinessItemWithPhoneNumber:completion:]"
- "-[BCSBusinessQueryController fetchBusinessItemWithPhoneNumber:forClientBundleID:completion:]"
- "-[BCSBusinessQueryController fetchItemWithQuery:completion:]"
- "-[BCSBusinessQueryController fetchItemWithQuery:completion:]_block_invoke"
```
