## livefiles_exfat.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_exfat.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bf50` | `0x1c0c8` | **`+0x178`** |
| `__TEXT.__oslogstring` | `0x4745` | `0x47f5` | **`+0xb0`** |

### Other Changes

```diff

-561.0.1.0.0
+561.0.3.0.0

-  Functions: 181
-  Symbols:   278
-  CStrings:  439
+  Functions: 182
+  Symbols:   279
+  CStrings:  441
Symbols:
+ _FAT_Access_M_FatBlockSize
Functions:
~ _FSOPS_ReadBootSector : 2064 -> 2224
~ _FAT_Access_M_GetFatEntry : 1188 -> 1196
+ _FAT_Access_M_FatBlockSize
CStrings:
+ "FAT_Access_M_FatBlockSize: block offset %llu is at/past FAT end %llu\n"
+ "FSOPS_ReadBootSector: FAT too small for ClusterCount: FatLength=%u sectors (%llu bytes), ClusterCount=%u\n"
```
