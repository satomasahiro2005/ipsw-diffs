## MusicLibrary

> `/System/Library/PrivateFrameworks/MusicLibrary.framework/MusicLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3070` | `0x19f0` | **`-0x1680`** |
| `__DATA_DIRTY.__objc_data` | `0x15e0` | `0x2c60` | **`+0x1680`** |
| `__TEXT.__text` | `0x3b4984` | `0x3b4abc` | **`+0x138`** |
| `__AUTH_CONST.__cfstring` | `0x28700` | `0x28760` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x144ec` | `0x14518` | **`+0x2c`** |
| `__TEXT.__cstring` | `0x74db0` | `0x74dd1` | **`+0x21`** |
| `__DATA_CONST.__const` | `0x9dc8` | `0x9de8` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x1d65c` | `0x1d678` | **`+0x1c`** |
| `__DATA_DIRTY.__bss` | `0x10d0` | `0x10e0` | **`+0x10`** |

### Other Changes

```diff

-4026.100.72.0.0
+4026.110.81.1.0

-  CStrings:  7527
+  CStrings:  7530
Functions:
~ __ZNK23ML3MatchAlbumImportItem15getIntegerValueEj : 632 -> 660
~ __ZNK28ML3ProtoSyncArtistImportItem8hasValueEj : 1124 -> 1156
~ __ZNK28ML3ProtoSyncArtistImportItem15getIntegerValueEj : 584 -> 600
~ __ZN16ML3ImportSession9_addAlbumENSt3__110shared_ptrI13ML3ImportItemEEP26ML3AlbumGroupingIdentifierxS3_ : 20004 -> 20084
~ __ZN16ML3ImportSession15_addAlbumArtistENSt3__110shared_ptrI13ML3ImportItemEEP6NSDataS3_ : 10252 -> 10408
CStrings:
+ "Disliked"
+ "Liked"
+ "Setting albumArtistLikedState=%{public}@ (oldValue=%{public}@)"
+ "Setting albumLikedState=%{public}@ (oldValue=%{public}@)"
+ "Unrecognized(%ld)"
- "Setting albumArtistLikedState=%d (oldValue=%d)"
- "Setting albumLikedState=%lld (oldValue=%lld)"
```
