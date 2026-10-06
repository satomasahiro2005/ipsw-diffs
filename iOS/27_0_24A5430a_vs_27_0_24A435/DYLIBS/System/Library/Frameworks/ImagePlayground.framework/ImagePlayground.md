## ImagePlayground

> `/System/Library/Frameworks/ImagePlayground.framework/ImagePlayground`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd898c` | `0xd8aa0` | **`+0x114`** |
| `__AUTH_CONST.__cfstring` | `0x220` | `0x260` | **`+0x40`** |
| `__TEXT.__const` | `0x194c4` | `0x19504` | **`+0x40`** |
| `__TEXT.__cstring` | `0x201f` | `0x203f` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x16d0` | `0x16e0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x10b0` | `0x10b8` | **`+0x8`** |

### Other Changes

```diff

-  Symbols:   2915
-  CStrings:  301
+  Symbols:   2918
+  CStrings:  303
Symbols:
+ _MGCopyAnswer
+ _MGIsDeviceOfType
+ _prefersGenericWallpaperSizes.prefersGenericWallpaperSizes
Functions:
~ +[GPWallpaperUtilities prefersGenericWallpaperSizes] : 52 -> 56
~ ___52+[GPWallpaperUtilities prefersGenericWallpaperSizes]_block_invoke : 4 -> 252
~ sub_20edd4cb0 -> sub_20f4a0dac : 436 -> 444
~ sub_20edf587c -> sub_20f4c1980 : 3204 -> 3212
~ sub_20ee5190c -> sub_20f51da18 : 968 -> 972
~ sub_20ee60240 -> sub_20f52c350 : 680 -> 684
CStrings:
+ "TargetSubType"
+ "V68"
```
