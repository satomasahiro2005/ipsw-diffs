## livefiles_exfat.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_exfat.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1be14` | `0x1bf14` | **`+0x100`** |

### Other Changes

```diff

-560.0.0.0.0
+561.0.0.0.0
Functions:
~ _FSOPS_SetDeviceAsDirty : 252 -> 276
~ _FSOPS_ReadBootSector : 2068 -> 2064
~ _FSOPS_ReadUpcase : 1240 -> 1236
~ _metaClear : 328 -> 332
~ _FILEOPS_FetchFileExtents : 772 -> 792
~ _EXFAT_Rename : 4600 -> 4592
~ _CONV_UTF8ToUnistr255 : 1360 -> 1368
~ _unicode_combinable : 88 -> 96
~ _CONV_Unistr255ToUTF8 : 876 -> 912
~ _DIROPS_ChecksumFileSet : 80 -> 76
~ _DIROPS_GetDirEntryByOffset : 3244 -> 3240
~ _DIROPS_GetMD5Digest : 220 -> 228
~ _DIROPS_LookForDirEntry : 2932 -> 2900
~ _DIROPS_PurgeNodeMetaBlocksFromCache : 984 -> 972
~ _DIROPS_CreateNewEntry : 2196 -> 2200
~ _DIROPS_CreateFileEntrySet : 808 -> 816
~ _DIROPS_SaveNewEntriesIntoDevice : 956 -> 984
~ _DIROPS_GetDirBlockRelative : 892 -> 880
~ _DIROPS_UpdateDirectoryEntries : 2768 -> 2760
~ _DIROPS_AcquireHTLRUSlotAndUnlockNode : 412 -> 404
~ _DIROPS_ReadDirInternal : 2784 -> 2724
~ _DIROPS_ClearNewDirectoryClusters : 892 -> 880
~ _DIROPS_LookupInternal : 692 -> 688
~ _ht_LookupByName : 84 -> 92
~ _ht_insert : 524 -> 532
~ _ht_remove : 560 -> 568
~ _ht_free_all : 128 -> 124
~ _FILERECORD_AllocateRecord : 1312 -> 1316
~ _FILERECORD_GetChainFromCache : 1796 -> 1800
~ _FILERECORD_FindClusterToCreateChainCacheEntry : 932 -> 944
~ _FILERECORD_UpdateNewAllocatedClustersInChain : 564 -> 572
~ _FILERECORD_AddChainCacheEntryToMainList : 356 -> 360
~ _FILERECORD_GetLastElementNumInCacheEntry : 220 -> 232
~ _FILERECORD_MultiLock : 208 -> 212
~ _FAT_Access_M_GetFatEntry : 1092 -> 1172
~ _FAT_Access_M_BitmapMap : 1424 -> 1480
~ _FATMOD_FlushAllCacheEntries : 692 -> 732
~ _FAT_Access_M_SetClustersFatEntryContent : 196 -> 212
~ _FAT_Access_M_AllocateClusters : 4252 -> 4192
~ _FAT_Access_M_FATInit : 312 -> 340
~ _FAT_Access_M_FATFini : 176 -> 200
~ _FAT_Access_M_BitmapCacheFini : 128 -> 140
~ _FAT_Access_M_BitmapCacheInit : 196 -> 212
```
