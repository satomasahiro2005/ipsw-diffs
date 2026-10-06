## NotesSupport

> `/System/Library/PrivateFrameworks/NotesSupport.framework/NotesSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x58404` | `0x585e4` | **`+0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0x5f90` | `0x6028` | **`+0x98`** |
| `__TEXT.__objc_methlist` | `0x43f8` | `0x4460` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x3230` | `0x3258` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x224` | `0x230` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x1d40` | `0x1d48` | **`+0x8`** |

### Other Changes

```diff

-2998.0.0.0.0
+3001.2.1.0.0

-  Functions: 2570
-  Symbols:   3778
+  Functions: 2578
+  Symbols:   3789
Symbols:
+ -[ICCDCSIReindexer reindexSearchableItemsWithObjectIDURIs:scope:completionHandler:]
+ -[ICIndexItemsByIdentifiersOperation indexingScope]
+ -[ICIndexItemsByIdentifiersOperation setIndexingScope:]
+ -[ICSearchIndexer reindexSearchableItemsWithObjectIDURIs:inIndex:scope:completionHandler:]
+ -[ICSearchIndexer reindexSearchableItemsWithObjectIDURIs:scope:completionHandler:]
+ -[ICSelectorDelayer isFiringFromMaximumDelay]
+ -[ICSelectorDelayer isFiringImmediately]
+ -[ICSelectorDelayer setIsFiringFromMaximumDelay:]
+ -[ICSelectorDelayer setIsFiringImmediately:]
+ GCC_except_table59
+ GCC_except_table69
+ GCC_except_table72
+ _OBJC_IVAR_$_ICIndexItemsByIdentifiersOperation._indexingScope
+ _OBJC_IVAR_$_ICSelectorDelayer._isFiringFromMaximumDelay
+ _OBJC_IVAR_$_ICSelectorDelayer._isFiringImmediately
+ ___90-[ICSearchIndexer reindexSearchableItemsWithObjectIDURIs:inIndex:scope:completionHandler:]_block_invoke
+ ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
- -[ICSearchIndexer reindexSearchableItemsWithObjectIDURIs:inIndex:completionHandler:]
- GCC_except_table63
- GCC_except_table68
- GCC_except_table70
- ___84-[ICSearchIndexer reindexSearchableItemsWithObjectIDURIs:inIndex:completionHandler:]_block_invoke
- ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
```
