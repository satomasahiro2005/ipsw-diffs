## WebBookmarks

> `/System/Library/PrivateFrameworks/WebBookmarks.framework/WebBookmarks`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf122c` | `0xf1258` | **`+0x2c`** |

### Other Changes

```diff

-625.1.29.10.28
+625.1.29.10.29
Symbols:
+ _objc_release_x10
- _objc_release_x11
Functions:
~ sub_2b5777ab4 -> sub_2b65d3ab4 : 780 -> 776
~ sub_2b5778eec -> sub_2b65d4ee8 : 424 -> 428
~ sub_2b5779204 -> sub_2b65d5204 : 352 -> 356
~ sub_2b5779364 -> sub_2b65d5368 : 356 -> 360
~ sub_2b57794c8 -> sub_2b65d54d0 : 360 -> 364
~ sub_2b5779630 -> sub_2b65d563c : 456 -> 460
~ sub_2b5781f40 -> sub_2b65ddf50 : 744 -> 752
~ sub_2b578ada4 -> sub_2b65e6dbc : 1668 -> 1672
~ -[WebBookmark(Internal) initWithSQLiteStatement:hasIcon:collectionType:skipDecodingSyncData:].cold.1 : 96 -> 104
~ -[WebBookmark(Internal) initWithSQLiteStatement:hasIcon:collectionType:skipDecodingSyncData:].cold.2 : 96 -> 104
~ ___58-[WebBookmark(Internal) _setParentID:incrementGeneration:]_block_invoke.cold.1 : 80 -> 76
~ -[WebBookmark(Internal) _setID:].cold.1 : 80 -> 76
~ +[WBBookmarkDatabaseSyncData databaseSyncDataWithContentsOfData:].cold.1 : 84 -> 92
~ +[WBBookmarkDatabaseSyncData databaseSyncDataWithContentsOfData:].cold.2 : 88 -> 84
~ +[WBBookmarkDatabaseSyncData databaseSyncDataWithContentsOfData:].cold.3 : 68 -> 64
~ -[WBBookmarkDatabaseSyncData writeToDatabase:databaseAccessor:].cold.1 : 84 -> 92
```
