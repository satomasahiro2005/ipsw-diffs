## livefiles_msdos.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_msdos.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19150` | `0x19250` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x260` | `0x258` | **`-0x8`** |

### Other Changes

```diff

-844.0.0.0.0
+845.0.0.0.0
Functions:
~ _msdosfs_dos2unixtime : 232 -> 228
~ _msdosfs_unicode2dos : 324 -> 320
~ _msdosfs_dos2unicodefn : 316 -> 276
~ _msdosfs_unicode_to_dos_name : 960 -> 984
~ _msdosfs_apply_generation_to_short_name : 192 -> 176
~ _msdosfs_unicode2winfn : 232 -> 248
~ _msdosfs_getunicodefn : 284 -> 324
~ _FSOPS_CopyVolumeLabel : 468 -> 480
~ _metaClear : 348 -> 352
~ _FILERECORD_AllocateRecord : 1364 -> 1368
~ _FILERECORD_GetChainFromCache : 1824 -> 1828
~ _FILERECORD_FindClusterToCreateChainCacheEntry : 840 -> 852
~ _FILERECORD_UpdateNewAllocatedClustersInChain : 564 -> 572
~ _FILERECORD_AddChainCacheEntryToMainList : 356 -> 360
~ _FILERECORD_GetLastElementNumInCacheEntry : 220 -> 232
~ _FILERECORD_MultiLock : 204 -> 208
~ _MSDOS_GetAttrFromDirEntry : 1172 -> 1164
~ _FILEOPS_FetchFileExtents : 604 -> 632
~ _MSDOS_Create : 1392 -> 1388
~ _MSDOS_SymLink : 1380 -> 1376
~ _MSDOS_Rename : 4076 -> 4072
~ _FATMOD_FlushAllCacheEntries : 272 -> 312
~ _FAT_Access_M_GetFatEntry : 900 -> 940
~ _FAT_Access_M_FATInit : 324 -> 352
~ _FAT_Access_M_FATFini : 172 -> 200
~ _FAT_Access_M_SetClustersFatEntryContent : 200 -> 216
~ _FATMOD_SetDriveDirtyBit : 536 -> 540
~ _FATMOD_FlushSpecificCacheEntry : 260 -> 276
~ _ht_LookupByName : 84 -> 92
~ _ht_insert : 520 -> 528
~ _ht_remove : 576 -> 584
~ _ht_free_all : 128 -> 124
~ _CONV_UTF8ToUnistr255 : 1364 -> 1352
~ _unicode_combinable : 88 -> 96
~ _CONV_Unistr255ToUTF8 : 840 -> 884
~ _CONV_ConvertToFSM : 124 -> 120
~ _CONV_LabelUTF8ToUTF16LocalEncoding : 344 -> 328
~ _DIROPS_GetDirBlockRelative : 1116 -> 1112
~ _DIROPS_GetMD5Digest : 220 -> 228
~ _DIROPS_PurgeNodeMetaBlocksFromCache : 964 -> 952
~ _DIROPS_ClearNewDirectoryClusters : 724 -> 716
~ _DIROPS_LookupInternal : 876 -> 872
~ _DIROPS_ReadDirInternal : 2816 -> 2800
~ _DIROPS_GetDirEntryByOffset : 1436 -> 1460
~ _DIROPS_AcquireHTLRUSlotAndUnlockNode : 412 -> 404
~ _DIROPS_LookForDirEntry : 2712 -> 2688
```
