## DiskImages

> `/System/Library/PrivateFrameworks/DiskImages.framework/DiskImages`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c520` | `0x3c600` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x69dc` | `0x6a1c` | **`+0x40`** |

### Other Changes

```diff

-698.0.0.0.0
+701.0.0.0.0

-  CStrings:  1031
+  CStrings:  1033
Functions:
~ sub_25e52437c -> sub_25f76037c : 420 -> 432
~ sub_25e524520 -> sub_25f76052c : 1124 -> 1216
~ sub_25e527a10 -> sub_25f763a78 : 1360 -> 1396
~ sub_25e52fa90 -> sub_25f76bb1c : 940 -> 988
~ sub_25e54d578 -> sub_25f789634 : 740 -> 776
CStrings:
+ "inStartSector>=0"
+ "inStartSector>=0 && inStartSector<fSectorCount"
```
