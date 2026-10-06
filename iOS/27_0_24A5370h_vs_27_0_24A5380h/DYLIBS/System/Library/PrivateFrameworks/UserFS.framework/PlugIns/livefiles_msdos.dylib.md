## livefiles_msdos.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_msdos.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19250` | `0x193c0` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x45d9` | `0x4736` | **`+0x15d`** |

### Other Changes

```diff

-845.0.0.0.0
+845.0.2.0.0

-  CStrings:  422
+  CStrings:  426
Functions:
~ _msdosfs_dos2unicodefn : 276 -> 272
~ _msdosfs_unicode_to_dos_name : 984 -> 940
~ _msdosfs_unicode2winfn : 248 -> 200
~ _msdosfs_winChkName : 492 -> 468
~ _msdosfs_getunicodefn : 324 -> 280
~ _FSOPS_InitReadBootSectorAndSetFATType : 3952 -> 4460
~ _FAT_Access_M_GetFatEntry : 940 -> 948
~ _FATMOD_FlushSpecificCacheEntry : 276 -> 284
~ _priortysort : 140 -> 148
CStrings:
+ "FSOPS_InitReadBootSectorAndSetFATType: FAT size overflows (fat_sectors=%u, bytes/sector=%u)\n"
+ "FSOPS_InitReadBootSectorAndSetFATType: cluster offset overflows\n"
+ "FSOPS_InitReadBootSectorAndSetFATType: device reported zero bytes-per-sector\n"
+ "FSOPS_InitReadBootSectorAndSetFATType: root directory block overflows (FATs=%u, fat_sectors=%u, res_sectors=%u)\n"
```
