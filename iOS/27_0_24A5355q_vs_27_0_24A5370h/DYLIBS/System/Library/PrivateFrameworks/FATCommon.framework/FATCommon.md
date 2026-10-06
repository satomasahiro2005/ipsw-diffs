## FATCommon

> `/System/Library/PrivateFrameworks/FATCommon.framework/FATCommon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d0e4` | `0x1d0a8` | **`-0x3c`** |
| `__TEXT.__gcc_except_tab` | `0x1084` | `0x108c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6a8` | `0x6a0` | **`-0x8`** |

### Other Changes

```diff

-844.0.0.0.0
+845.0.0.0.0
Functions:
~ ___80-[DirItem createNewDirEntryNamed:type:attributes:firstDataCluster:replyHandler:]_block_invoke_2 : 128 -> 124
~ -[NameCacheBucket removeEntryAtIndex:] : 116 -> 120
~ -[DirNameCache insertDirEntryNamedUtf16:offsetInDir:] : 504 -> 488
~ -[DirNameCache lookupDirEntryNamedUtf16:replyHandler:] : 400 -> 388
~ -[DirNameCachePool getDNCEntryByKey:] : 300 -> 296
~ -[DirNameCachePool getAvailableEntry] : 444 -> 440
~ -[DirNameCachePool removeNameCacheForDir:] : 416 -> 412
~ -[DirNameCachePool check] : 388 -> 384
~ ___38-[FATItem setAttributes:replyHandler:]_block_invoke : 128 -> 124
~ +[SymLinkItem verifyAndGetLink:replyHandler:] : 428 -> 432
~ ___78-[FATVolume createItemNamed:type:inDirectory:attributes:content:replyHandler:]_block_invoke.31 : 128 -> 124
~ ___69-[FATVolume internalLookupItemNamed:inDirectory:packer:replyHandler:]_block_invoke_2 : 128 -> 124
~ ___94-[FATVolume internalRenameItem:inDirectory:named:toNewName:inDirectory:overItem:replyHandler:]_block_invoke.65 : 128 -> 124
~ ___94-[FATVolume internalRenameItem:inDirectory:named:toNewName:inDirectory:overItem:replyHandler:]_block_invoke_2.68 : 128 -> 124
```
