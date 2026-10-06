## WallpaperKit

> `/System/Library/PrivateFrameworks/WallpaperKit.framework/WallpaperKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8e530` | `0x8e6c4` | **`+0x194`** |
| `__AUTH_CONST.__objc_const` | `0xd3c8` | `0xd500` | **`+0x138`** |
| `__AUTH.__objc_data` | `0x208` | `0x1b8` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xd20` | `0xd70` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x1b00` | `0x1b20` | **`+0x20`** |
| `__DATA.__bss` | `0x31b0` | `0x3190` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x4858` | `0x4878` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x216c` | `0x2188` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x6d8` | `0x6e8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x32c0` | `0x32d0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1f98` | `0x1fa8` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x3d98` | `0x3da0` | **`+0x8`** |
| `__DATA_CONST.__const` | `0xd70` | `0xd78` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1418` | `0x1420` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x1ff0` | `0x1ff8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x21c` | `0x220` | **`+0x4`** |

### Other Changes

```diff

-2143.0.0.0.0
+2144.0.0.0.0

-  Functions: 3254
-  Symbols:   2766
-  CStrings:  598
+  Functions: 3258
+  Symbols:   2769
+  CStrings:  599
Symbols:
+ -[WKWallpaperBundle sectionSubtitle]
+ _OBJC_IVAR_$_WKWallpaperBundle._sectionSubtitle
+ _WKWallpaperMetadataOptionSectionSubtitleKey
Functions:
~ -[WKWallpaperBundle .cxx_destruct] : 188 -> 200
~ -[WKWallpaperBundle _loadBundle] : 5408 -> 5572
+ -[WKWallpaperBundle preferredProminentColors]
+ sub_1d512c620
+ sub_1d512d044
+ sub_1d5142bb0
CStrings:
+ "SectionSubtitleKey"
```
